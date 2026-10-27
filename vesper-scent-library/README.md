# Wear the weather

A public editable email template for fictional Vesper, created using the email-design skill. The [visual study](design/concept.png) and [design intent](design/intent.md) were created before inspecting the native implementation schema.

[Open local preview](preview-local.html) · [Desktop](screenshot.png) · [Mobile](screenshot-mobile.png)

## Design

A scent editorial on ivory and blush, with aubergine live serif type, a portrait bottle photograph sharing the opening spread, a horizontal sensory index and a restrained fragrance price close. The composition borrows the calm of a perfume blotter and the notation of a weather notebook.

Typography: Georgia/Times New Roman/serif for display copy and Arial/Helvetica/sans-serif for practical text. No external web fonts. All essential wording, product details, prices, actions and layout remain native editable Weavour blocks. Artwork contains no lettering or essential campaign details. JSON is the source and HTML is its actual Weavour renderer export.

Implementation interpretation: The concept’s oversized opening typography is reduced to fit the text/photo spread at 320px; the portrait image retains its full framing and the title remains live text. Gradients and image-baked lettering from the study are not used.

## Sample campaign

Petrichor eau de parfum, 30ml, £64. Vesper and every product detail, sensory description and offer are fictional sample content. Replace sender details, prices, availability, claims and the example.com destination before sending. Add the actual sender identification/address as appropriate. Keep the preserved `{{unsubscribe_url}}` merge token and substitute it through the sending system. Customers handle email delivery.

Subject: A new weather to wear

Preheader: Meet Petrichor, a green and mineral eau de parfum.

Tags: Retail, Product launch.

## Image provenance

The design study and final artwork were generated using OpenAI's built-in image-generation tool on 26 October 2026. No stock photograph or competitor artwork is included. The production image is an original standalone photograph-style generation. The concept study is separate and excluded from the active email asset inventory.

Local image: [images/rain-bottle-455827b01996.jpg](images/rain-bottle-455827b01996.jpg)

Hosted asset URL: https://assets.weavour.com/templates/vesper-scent-library/rain-bottle-455827b01996.jpg

Actual file dimensions: 1024 × 1536px original PNG; proportionally resized to 800 × 1200px JPEG. JPEG quality 86, with no creative image editing after generation. The content-hashed filename uses the first twelve characters of the final JPEG's SHA-256. Full SHA-256: `455827b01996d80fd884d2411ceef03d44753bde791dabb676dc989bc2653b51`.

Alternative text: An unlabelled amber perfume bottle on wet slate in front of rain-streaked glass and soft green leaves.

### Actual artwork prompt

> Use case: photorealistic-natural. Asset type: portrait editorial product photograph for an editable perfumery email, not a mockup. A single simple unlabelled amber-glass perfume bottle with a dark cylindrical cap stands on wet charcoal slate in front of rain-streaked window glass. A small out-of-focus dark green leaf reflection in the glass, diffuse rainy afternoon light, amber liquid glows subtly. Quiet luxurious physical realism, real glass reflections and droplets, pale muted daylight with dark aubergine shadow undertones. Bottle centered lower-middle, a little negative space above; portrait 2:3 composition. No label, writing, text, lettering, logo, watermark, border or other product. Show the entire bottle with room around it. This photograph conveys the sensory idea of rain, stone and green leaves.

### Actual visual study prompt

> Use case: ads-marketing. Asset type: full email visual design study for a fictional independent perfumery VESPER, not a production asset. One straight-on narrow portrait email, about 600 wide by 1200 tall, no device or outer mockup.
> Create an unusually refined scent editorial on pale ivory #f4efe5 with aubergine #38213a and pale blush #e6d2d1. Small VESPER masthead in widely spaced serif lettering, a narrow issue note 'SCENT STUDY / 01'. Opening is an asymmetric editorial spread: on the left a huge elegant serif headline 'Wear the weather.' broken into short artful lines, on the right an atmospheric portrait photograph of one simple unlabelled amber perfume bottle on wet dark slate, soft rain-distorted glass behind, quiet diffuse light and a leafy reflection. The photograph is striking, moody and physical, not a shiny 3D render. No product-card treatment.
> A thin aubergine rule and a three-part sensory index: 'RAIN / STONE / GREEN'. Continue in an open full-width blush field with the large serif phrase 'Before the rain. After the rush.' A short paragraph about mineral brightness and a green drydown, then a small restrained specification 'PETRICHOR / EAU DE PARFUM / 30 ML'. Finish with an aubergine full-width band containing '£64' and a tasteful outlined 'Explore Petrichor' action. Cream small footer with VESPER and Unsubscribe.
> Typography is a strong editorial Georgia-like serif and very small clear sans-serif annotations. No gradient, no rounded cards, no three-section stock newsletter, no invented seals or badges. Strong use of scale, quiet whitespace, product specificity and a considered asymmetric image/text relationship.

Exact prompt text is also stored in [design/artwork-prompt.txt](design/artwork-prompt.txt) and [design/concept-prompt.txt](design/concept-prompt.txt).

## Validation

The private application's actual catalog renderer passed native import, authored-text preservation in HTML/plain text, image and alternative-text preservation, button destination export, reopen/export stability, desktop/mobile screenshots, horizontal-overflow checks and keyboard access. Desktop (800px) and mobile (375px) screenshots were visually inspected against the study.

Additional local-preview checks passed at 320, 375, 600, 800 and 1440px: loaded imagery, no horizontal overflow, visible action, preserved unsubscribe token and keyboard access. An Arial fallback passed at 320 and 375px. A machine-readable viewport report is in [design/verification.json](design/verification.json). Browser previews do not certify every email client.

`preview-local.html` changes only the final asset URL to a relative local image path. The production image is published on assets.weavour.com and was verified against its local SHA-256. Tenant import and deployment remain separate release actions.
