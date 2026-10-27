# Nothing to keep up with

A quiet bathhouse appointment slip: large unhurried serif copy, native rule-separated receipt rows and an architectural photographic pause late in the email.

Created with the email-design skill: [visual study](design/concept.png), [design intent](design/intent.md), native editable implementation, then inspection of the real export.

[Open local preview](preview-local.html) · [Desktop screenshot](screenshot.png) · [Mobile screenshot](screenshot-mobile.png)

## Design

Pale bone #eeeee5, deep jade #244d48 and a mist rule #aabbb3. Georgia/Times New Roman carry the invitation; Arial/Helvetica carry practical details. The desktop canvas is 520px wide.

The receipt rows and the late image placement survive as native sections, rules and paired columns. The booking copy explicitly says ninety minutes so it agrees with the example service duration; no essential campaign text is baked into the image.

All campaign copy, headings, labels, buttons and layout blocks remain native editable Weavour content. No external web font or monolithic HTML block is used.

Subject: Nothing to keep up with

Preheader: An unhurried ninety-minute visit to Stillwater Bathhouse.

Industry and purpose tags: Health & wellness, Service.

## Example content

Stillwater Bathhouse, 8 Mill Yard, a ninety-minute visit, £28, and included towel/locker are fictional sender and offer details. The image depicts an imagined venue. The copy makes no medical or treatment claims. Replace all sender identity, postal information, dates, availability, prices and offer claims with verified sender content before use. Replace the example.com reservation destination before sending. Keep and substitute `{{unsubscribe_url}}` through the sending system. Customers handle email delivery.

## Image provenance

Both [the visual study](design/concept.png) and the standalone production photograph were generated with OpenAI's built-in image-generation tool on 26 October 2026. The standalone photograph used its own complete prompt without an external reference image. No stock imagery is included. The study remains a design artifact and is excluded from the active image inventory.

Local artwork: [images/jade-pool-d0a9e2f78397.jpg](images/jade-pool-d0a9e2f78397.jpg)

Hosted URL: https://assets.weavour.com/templates/stillwater-bathhouse/jade-pool-d0a9e2f78397.jpg

The original PNG's actual dimensions were verified as 1536 × 1024px. It was proportionally resized and encoded as JPEG at quality 84; the final file's actual dimensions were verified as 1200 × 800px. The filename contains the first twelve characters of the final bytes' SHA-256. Full SHA-256: `d0a9e2f78397d565819fa40b534fe39fb3aac39c78fa308664dcba054a97a534`.

Alternative text: Morning light and steam pass through an arched opening above a quiet jade-tiled bathhouse pool.

### Actual production photograph prompt

> Use case: photorealistic-natural. Asset type: standalone architecture photograph for a fictional urban bathhouse email. A beautiful empty bathhouse, intimate scale, deep muted jade green square tiles, a single tall arched opening toward the upper right with soft warm natural light coming through light realistic steam. A quiet pale stone pool edge and still jade-tinted water with tiny ripples occupies the lower third. Landscape 3:2 framing, cropped architectural fragment rather than a grand hotel lobby. Real tactile tile glaze and gently aged grout, restrained photographic color, calm light, elegant composition. No people, models, towels, spa products, flowers, candles, lettering, logos, watermarks or typography. No promise of a real venue; this is original illustrative campaign imagery.

### Actual visual study prompt

> Use case: ads-marketing. Asset type: full email visual design study for fictional STILLWATER urban bathhouse. A narrow portrait piece of quiet appointment stationery, straight-on, no device/browser mockup. Pale bone paper #eeeee5, dark jade #244d48, mist #d8e4df. Cultured small serif STILLWATER masthead, fine horizontal rule. Large soft serif statement left aligned with three short lines "Nothing to / keep up / with." Generous breathing space, but a compact email overall. A small sentence "Leave your phone in the locker. The next ninety minutes belong to you." The central section is a refined unboxed receipt with hairline-separated rows: "YOUR VISIT / 90 MINUTES", "BRING / YOURSELF", "WE PROVIDE / TOWEL + LOCKER", "ENTRY / £28". A wide, cropped photographic pause appears AFTER this practical receipt: serene empty jade-tiled bathhouse with a single arched opening, a small pool and luminous morning steam. An intimate architectural image, no model, no candles, no flowers. Under it the line "Warm rooms. Quiet water. Somewhere to sit for a while." and a modest jade Book a quiet hour rectangular button, then a small sender/footer/unsubscribe. The elegance comes from restraint, exact alignment and varied type scale. Avoid generic spa newsletter, benefits icons, floating cards, gold luxury clichés and three feature sections.

Exact prompts also appear in [design/artwork-prompt.txt](design/artwork-prompt.txt) and [design/concept-prompt.txt](design/concept-prompt.txt).

## Verification

The actual Weavour renderer passed native import, authored-text and alternative-text preservation, button export, reopen/export stability, desktop/mobile captures and keyboard link access. Final desktop (800px viewport) and mobile (375px viewport) screenshots were visually inspected against the design direction.

Additional local browser checks passed at 320, 375, 600, 800 and 1440px: no horizontal overflow, loaded local artwork, visible links/actions and keyboard access. An Arial fallback passed at 320 and 375px. The unsubscribe merge token is retained. [Recorded browser checks](design/verification.json).

`template.json` is the editable source; `template.html` is its actual renderer export, synchronized with JSON `previewHtml`. `preview-local.html` changes only the hosted image URL to a relative local path. Browser previews do not certify every email client.

The production image is published on assets.weavour.com and was verified against its local SHA-256. Hosted tenant imports and application deployment remain separate release actions.
