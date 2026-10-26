<a href="https://weavour.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/weavour-on-dark.png">
    <img src="assets/weavour-on-light.png" alt="Weavour" width="180">
  </picture>
</a>

Email creation, woven into your product. [Explore Weavour](https://weavour.com) ↗

# Weavour email templates

Public, editable email templates for [Weavour](https://weavour.com). One directory per template. Templates and tooling are MIT licensed; see LICENSE. This is a standalone Git repository; publishing it to GitHub is a separate step.

## Catalog

[Forty seasonal email designs](seasonal-campaigns/) span Christmas, Halloween, Black Friday, Cyber Monday, Valentine’s Day and eight more occasions across different verticals. Includes native editable layouts, original continuous backgrounds, local previews and copy notes.

Featured creative workshop: [Wildform — Make art with a little sunshine](wildform-sunprint/) uses one continuous cyanotype background, Palatino typography and clear beginner-focused booking copy. [Local preview](wildform-sunprint/preview-local.html) · [Desktop](wildform-sunprint/screenshot.png) · [Mobile](wildform-sunprint/screenshot-mobile.png).

Featured continuous design: [Nocturne — Some nights are worth staying for](nocturne-garden-supper/) layers editable text over three coordinated native layout backgrounds. [Local preview](nocturne-garden-supper/preview-local.html) · [Desktop](nocturne-garden-supper/screenshot.png) · [Mobile](nocturne-garden-supper/screenshot-mobile.png).

Featured new design: [A slower shade of summer](casa-mare-summer/) — an editorial Mediterranean stay with four original photographs. [Desktop preview](casa-mare-summer/screenshot.png) · [Mobile preview](casa-mare-summer/screenshot-mobile.png).

The newest ten designs include a watch dossier, supper-club menu, product release bulletin, rail itinerary, evening letter, cinema programme, homewares catalogue, race bib, writing-school correspondence and river appeal. [Browse all ten](NEW-TEMPLATES.md) · [Collection preview](new-ten-preview.jpg).

154 templates across distinct niches. The latest 80 have been reviewed for image relevance, campaign-specific copy, contrast and mobile reading order. The manifest is the complete catalog index; the table below highlights the original collection. [Browse the collection preview](catalog-preview.jpg).

Reviewed collection previews: [1–20](review-preview-1.jpg) · [21–40](review-preview-2.jpg) · [41–60](review-preview-3.jpg) · [61–80](review-preview-4.jpg). [Review findings](REVIEW.md) · [Per-template review inventory](review-latest-80.json).

Some campaigns use a deliberate text-led design. Image-led campaigns use subject-matched generated artwork, including new photography created for this review. Each template README records the actual image prompt and any reuse from the original collection. Historical image files remain available; the manifest lists active images.

The latest 80 now have independent creative directions, recorded in [design-variety.json](design-variety.json) and each template README: lookbooks, service work orders, cinema tickets, editorial letters, timetables, record sleeves, specimen sheets, field guides, impact reports and more. Layout variety changes the actual native block composition, image placement, type scale and reading order. The previews above show the current designs.

| Template | Niche | Preview |
| --- | --- | --- |
| [A slower kind of Sunday](fieldwork-sunday/) | Homewares | [Desktop](fieldwork-sunday/screenshot.png) · [Mobile](fieldwork-sunday/screenshot-mobile.png) |
| [The weekend bake](hearth-bakery/) | Bakery | [Desktop](hearth-bakery/screenshot.png) · [Mobile](hearth-bakery/screenshot-mobile.png) |
| [Find your morning note](ember-coffee/) | Specialty coffee | [Desktop](ember-coffee/screenshot.png) · [Mobile](ember-coffee/screenshot-mobile.png) |
| [An evening at the counter](nori-omakase/) | Restaurant | [Desktop](nori-omakase/screenshot.png) · [Mobile](nori-omakase/screenshot-mobile.png) |
| [A little room for the sea](tidehouse-retreat/) | Boutique hotel | [Desktop](tidehouse-retreat/screenshot.png) · [Mobile](tidehouse-retreat/screenshot-mobile.png) |
| [Take the long way](switchback-adventures/) | Outdoor adventure | [Desktop](switchback-adventures/screenshot.png) · [Mobile](switchback-adventures/screenshot-mobile.png) |
| [Find your next chapter](archway-open-house/) | Real estate | [Desktop](archway-open-house/screenshot.png) · [Mobile](archway-open-house/screenshot-mobile.png) |
| [Your next best friend](good-company-adoption/) | Pet adoption | [Desktop](good-company-adoption/screenshot.png) · [Mobile](good-company-adoption/screenshot-mobile.png) |
| [Begin where you are](stillpoint-yoga/) | Yoga & wellness | [Desktop](stillpoint-yoga/screenshot.png) · [Mobile](stillpoint-yoga/screenshot-mobile.png) |
| [Build your own strong](form-training/) | Fitness | [Desktop](form-training/screenshot.png) · [Mobile](form-training/screenshot-mobile.png) |
| [A softer daily ritual](morrow-skincare/) | Beauty & skincare | [Desktop](morrow-skincare/screenshot.png) · [Mobile](morrow-skincare/screenshot-mobile.png) |
| [The art of the everyday](aurelia-jewelry/) | Jewelry | [Desktop](aurelia-jewelry/screenshot.png) · [Mobile](aurelia-jewelry/screenshot-mobile.png) |
| [Wear your own rules](offscript-fashion/) | Fashion | [Desktop](offscript-fashion/screenshot.png) · [Mobile](offscript-fashion/screenshot-mobile.png) |
| [A little wild at heart](stem-seasonal/) | Florist | [Desktop](stem-seasonal/screenshot.png) · [Mobile](stem-seasonal/screenshot-mobile.png) |
| [Keep the blue alive](bluecurrent-ocean/) | Ocean conservation | [Desktop](bluecurrent-ocean/screenshot.png) · [Mobile](bluecurrent-ocean/screenshot-mobile.png) |
| [Make something real](openbench-workshop/) | Creative education | [Desktop](openbench-workshop/screenshot.png) · [Mobile](openbench-workshop/screenshot-mobile.png) |
| [Less between idea and done](relay-product-update/) | SaaS product update | [Desktop](relay-product-update/screenshot.png) · [Mobile](relay-product-update/screenshot-mobile.png) |
| [Ideas meet here](common-ground-conference/) | Design conference | [Desktop](common-ground-conference/screenshot.png) · [Mobile](common-ground-conference/screenshot-mobile.png) |
| [The night has a rhythm](afterhours-jazz/) | Live music | [Desktop](afterhours-jazz/screenshot.png) · [Mobile](afterhours-jazz/screenshot-mobile.png) |
| [Find your next obsession](margin-bookshop/) | Independent bookstore | [Desktop](margin-bookshop/screenshot.png) · [Mobile](margin-bookshop/screenshot-mobile.png) |
| [A good week starts here](little-table-mealkit/) | Meal kit | [Desktop](little-table-mealkit/screenshot.png) · [Mobile](little-table-mealkit/screenshot-mobile.png) |

`manifest.json` is the catalog index. Its `schemaVersion` versions the manifest format. Each entry has a stable `id`, display name, description, language, tags, JSON/HTML/screenshot paths and an image inventory with source information. All paths are relative to the repository root.

## Tags

The catalog uses 18 shared tags, defined in [tags.json](tags.json). Each template has exactly two: one broad industry, followed by one campaign purpose. Keep niche details in names and descriptions rather than creating more tags.

Industries: Retail, Food & drink, Travel, Health & wellness, Arts & culture, Education, Business, Technology, Community, Pets, Sports & outdoors.

Purposes: Product launch, Update, Newsletter, Event, Service, Fundraising, Promotion. Reuse these exact labels when adding templates; avoid synonyms such as Launch/Announcement, Events/Event invitation, or SaaS/Technology.

Each template directory contains:

- `template.json`: a Weavour schema-version-1 email document with native editable blocks, subject, preheader and matching HTML preview.
- `template.html`: the actual Weavour / React Email export, with inline email styles and hosted image URLs.
- `screenshot.png` and `screenshot-mobile.png`: local full-page browser previews at 800px and 375px viewport widths.
- `images/`: the email's source image files, retained for reproducible uploads and previews.
- `README.md`: template-specific notes, image provenance and personalization instructions.

## Images

Catalog images live at `https://assets.weavour.com/templates/:id/:filename`. These public shared catalog assets are distinct from organization and personal image libraries. Keep image paths immutable: when bytes change, use a new content-hashed filename, upload it, and retain old images because previously copied emails may still use them. Do not place customer information, credentials or tenant asset IDs in this repository.

## Build and check

Maintainer commands live in the sibling private Weavour application repository because JSON validation and HTML export use the hosted editor's actual extension profile. After installing its dependencies, run from `../weavour`:

```sh
npm run templates:render
npm run templates:test
```

Rendering needs the Playwright Chromium browser (`cd editor && npx playwright install chromium`). `--catalog /path/to/email-templates` overrides the sibling path for rendering.

Tenant import (`templates:import`), image publishing and provisioning release instructions are maintained in the private application's `README.md`, under “Public email template catalog”.

HTML previews have been checked in Chromium. Email clients, especially Outlook, may render differently; test with your sending system before a campaign. Replace example links and configure unsubscribe substitution before sending.
