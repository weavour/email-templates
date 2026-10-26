# Public template catalog

Keep this repository public-safe: no credentials, customer content or internal tenant IDs.

- One directory per template; list every template in root manifest.json.
- Display names must be a plain word or group of words. Never use double hyphens, en/em dashes, colons or event/brand separators in template names. Keep event, industry and sender context in metadata or descriptions. Preserve stable IDs, directories and asset URLs when renaming display names.
- Use exactly two tags from tags.json: one industry, then one campaign purpose. Keep niche details in names/descriptions; do not add niche tags or synonyms.
- Keep template IDs stable. Use native editable Weavour blocks, never a monolithic HTML block.
- Give new templates an intentional composition. Consult design-variety.json and existing previews; avoid repeating a masthead/headline/image/three-section stack with palette changes. Preserve email-safe typography, mobile readability and native editability.
- Include JSON, matching exported HTML, local desktop/mobile screenshots, local images and provenance.
- Images use https://assets.weavour.com/templates/:id/:filename. Use a new content-hashed filename for changed image bytes; preserve previous published assets for existing emails.
- Record generated-image prompts or stock-image source and license information in the template README.
- Build/check/import through the sibling private application's templates:render, templates:test and templates:import commands, documented in README.md. Do not copy private application source here.
- Replace placeholder destinations before sending. Keep unsubscribe merge tokens intact.
