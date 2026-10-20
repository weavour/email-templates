# Public template catalog

Keep this repository public-safe: no credentials, customer content or internal tenant IDs.

- One directory per template; list every template in root manifest.json.
- Keep template IDs stable. Use native editable Weavour blocks, never a monolithic HTML block.
- Include JSON, matching exported HTML, local desktop/mobile screenshots, local images and provenance.
- Images use https://assets.weavour.com/templates/:id/:filename. Use a new content-hashed filename for changed image bytes; preserve previous published assets for existing emails.
- Record generated-image prompts or stock-image source and license information in the template README.
- Build/check/import through the sibling private application's templates:render, templates:test and templates:import commands, documented in README.md. Do not copy private application source here.
- Replace placeholder destinations before sending. Keep unsubscribe merge tokens intact.
