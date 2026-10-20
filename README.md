# Weavour email templates

Public, editable email templates for [Weavour](https://weavour.com). One directory per template. Templates and tooling are MIT licensed; see LICENSE. This is a standalone Git repository; publishing it to GitHub is a separate step.

## Catalog

| Template | Use | Preview |
| --- | --- | --- |
| [Fieldwork — A slower kind of Sunday](fieldwork-sunday/) | Product announcement / lifestyle | [Desktop](fieldwork-sunday/screenshot.png) · [Mobile](fieldwork-sunday/screenshot-mobile.png) |

`manifest.json` is the catalog index. Its `schemaVersion` versions the manifest format. Each entry has a stable `id`, display name, description, language, tags, JSON/HTML/screenshot paths and an image inventory with source information. All paths are relative to the repository root.

Each template directory contains:

- `template.json`: a Weavour schema-version-1 email document with native editable blocks, subject, preheader and matching HTML preview. Store this document in the tenant `templates.document` column, not the entire manifest entry.
- `template.html`: the actual Weavour / React Email export, with inline email styles and hosted image URLs.
- `screenshot.png` and `screenshot-mobile.png`: local full-page browser previews at 800px and 375px viewport widths.
- `images/`: the email's source image files, retained for reproducible uploads and previews.
- `README.md`: template-specific notes, image provenance and personalization instructions.

## Images

Catalog images live at `https://assets.weavour.com/templates/:id/:filename`. These public shared catalog assets are distinct from organization and personal image libraries. Keep image paths immutable: when bytes change, use a new content-hashed filename, upload it, and retain old images because previously copied emails may still use them. Do not place customer information, credentials or tenant asset IDs in this repository.

## Build and tenant import

Maintainer commands live in the private Weavour application repository because JSON validation and HTML export use the hosted editor's actual extension profile. With this repository next to `weavour/`, run there:

```sh
npm run templates:render
npm run templates:test
npm run templates:import -- --sql /tmp/templates.sql
npm run templates:import -- --remote --upload-images
npm run templates:import -- --local --database TENANT_PREVIEW --config tenant-pool/wrangler.jsonc
npm run templates:import -- --remote --database-id TENANT_D1_UUID
# Fleet discovery and import:
npm run templates:import -- --remote --all --list
npm run templates:import -- --remote --all
npm run templates:import -- --local --all
```

Install the application dependencies with its documented setup first. Rendering needs the Playwright Chromium browser (`cd editor && npx playwright install chromium`). `--catalog /path/to/email-templates` overrides the sibling path on render/import commands. Local import uses the application's `.wrangler/state`; override with `--persist-to PATH` when needed. Production commands use the operator's Wrangler authentication; no credentials are stored here.

Production import targets **tenant** D1 databases, never the shared control database. Choose a single `--database-id`, or use `--all` to discover every active, provisioned tenant database from the selected control registry and import serially. `--all --list` lists targets without importing. Local fleet discovery uses the local control registry and honors `--persist-to`; preview fixtures without active registry entries use the single-target command. Database IDs are deduplicated; pending/failed provisioning records and unrelated databases are excluded. Each failure is reported while remaining imports continue, followed by a summary and a nonzero exit status if any failed. Repeating the command is safe. `--all` cannot be combined with single-target options, `--sql` or image publishing. Apply the application's tenant migrations before import. These commands explicitly sync existing tenants. New tenants are automatically seeded from the versioned snapshot bundled with the provisioner. Templates are published workspace-owned templates, visible in Included and available across that customer's editors. Catalog IDs map to stable UUID-shaped database IDs. Reimporting unchanged content does nothing; changes create a revision and retain history. Reimporting also restores deleted/unpublished catalog entries and overwrites dashboard edits to catalog-owned originals. User-owned templates and independent copies are preserved. Removing a manifest entry does not delete an already imported template.

Review generated SQL before production import if desired. Take the normal tenant backup before production updates. Direct SQL import uses the same schema and revision format as the application; it does not bypass the requirement to choose the correct tenant database.

HTML previews have been checked in Chromium. Email clients, especially Outlook, may render differently; test with your sending system before a campaign. Replace example links and configure unsubscribe substitution before sending.


## Provisioning releases

After rendering and publishing images, run `npm run templates:bundle` in the private application repository. This verifies published image bytes and writes its committed `shared/template-catalog.json`, pinned by a SHA-256 content version. Commit that snapshot with the application release. Normal builds verify the snapshot offline; the public checkout and GitHub are not needed when provisioning a workspace. New tenants receive every bundled template after migrations and before activation; failed seeds retry safely. The local launcher follows the same sequence. Existing production tenants are updated separately with `--remote --all`.
