# Breakfast gets brighter

A public editable email template for fictional Sunroom, created using the email-design skill. The [visual study](design/concept.png) and [design intent](design/intent.md) were created before inspecting the native implementation schema.

[Open local preview](preview-local.html) · [Desktop](screenshot.png) · [Mobile](screenshot-mobile.png)

## Design

A sunny grocery order slip: yellow stock, tomato-red live typography, a full-width appetising still life, a ruled tasting ledger, a large live £8 price and a tear-off-style order close. Specific flavour and pairing details replace filler marketing sections.

Typography: Georgia/Times New Roman/serif display text, Arial/Helvetica/sans-serif body text and Courier New/Courier/monospace ledger labels. No external web fonts. All essential wording, product details, prices, actions and layout remain native editable Weavour blocks. Artwork contains no lettering or essential campaign details. JSON is the source and HTML is its actual Weavour renderer export.

Implementation interpretation: The visual study’s decorative sun mark is omitted, keeping the sender name live editable. The tasting table and price remain native columns and sections. The order-close dashed rule is a native border.

## Sample campaign

Pink grapefruit marmalade, 220g, £8 per jar. Sunroom, the product description and every offer detail are fictional sample content. Replace sender details, prices, availability, claims and the example.com destination before sending. Add the actual sender identification/address as appropriate. Keep the preserved `{{unsubscribe_url}}` merge token and substitute it through the sending system. Customers handle email delivery.

Subject: Something bright for your toast

Preheader: Pink grapefruit marmalade. Fine ribbons of peel. £8 a jar.

Tags: Food & drink, Promotion.

## Image provenance

The design study and final artwork were generated using OpenAI's built-in image-generation tool on 26 October 2026. No stock photograph or competitor artwork is included. The production image is an original standalone photograph-style generation. The concept study is separate and excluded from the active email asset inventory.

Local image: [images/grapefruit-toast-d6e750fc7ba8.jpg](images/grapefruit-toast-d6e750fc7ba8.jpg)

Hosted asset URL: https://assets.weavour.com/templates/sunroom-preserve-drop/grapefruit-toast-d6e750fc7ba8.jpg

Actual file dimensions: 1536 × 1024px original PNG; proportionally resized to 1200 × 800px JPEG. JPEG quality 86, with no creative image editing after generation. The content-hashed filename uses the first twelve characters of the final JPEG's SHA-256. Full SHA-256: `d6e750fc7ba82b9f4a8116c9710418a636af8fd8cbf9d96fa497298a8664e610`.

Alternative text: A jar of glowing grapefruit marmalade beside a grapefruit half and thick-cut toast on yellow gingham.

### Actual artwork prompt

> Use case: photorealistic-natural. Asset type: landscape editorial food photograph for a preserve maker's editable email, no mockup. A sunlit breakfast still life: one unlabelled small clear glass jam jar filled with glowing amber-pink grapefruit marmalade, fine suspended ribbons of peel, a thick-cut toast slice generously spread with marmalade in front, half a ripe pink grapefruit with real juicy segments to the left, one curling grapefruit peel and a simple butter knife on warm yellow-and-white gingham. Warm morning side light, delectable natural food texture, restrained generous styling, physically plausible glass and fruit, close editorial crop. Landscape 3:2 framing, all key objects visible. Color feeling warm cream, sunny yellow, deep pink grapefruit and orange preserve. No words, logos, labels, badges, watermarks, borders or writing anywhere.

### Actual visual study prompt

> Use case: ads-marketing. Asset type: full-email design study for fictional small-batch preserve maker SUNROOM. One straight-on narrow portrait composition, no device or browser, warm paper #fff1c9 and tomato red #a52c20 with sunny orange photography.
> Make a distinctive grocery order slip crossed with a small family recipe card. At top a small playful serif SUNROOM masthead and a thin rule, then the headline 'Breakfast gets brighter.' in handsome dark-red Georgia-like type. Under the headline, a wide cheerful editorial still life of an unlabelled small glass jar of amber-pink grapefruit marmalade, one thick toast slice with glowing marmalade, a cut pink grapefruit and peel on yellow gingham, warm bright morning light, delicious physically plausible food.
> Below, a red thin caption 'SMALL BATCH / PINK GRAPEFRUIT'. A ruled tasting ledger, not a card grid: three neat rows with small monospaced labels 'FLAVOUR', 'TEXTURE', 'BEST WITH' and editable-looking descriptions 'Bittersweet citrus', 'Fine ribbons of peel', 'Thick-cut toast'. Then an oversized red live-looking £8 and small '220g jar' alongside a short note about making breakfast worth sitting down for.
> A dashed red tear-off line above a full-width tomato-red order area: warm-cream words 'Save a jar for breakfast' and clear cream rectangular 'Shop the batch' action. Small footer SUNROOM and Unsubscribe. Include a little whimsical citrus cut-paper feeling but no unnecessary decorative clip art. Composition should feel like a useful grocery slip with appetite and craft. No gradients, no rounded cards, no repeated newsletter sections, no health or origin badges.

Exact prompt text is also stored in [design/artwork-prompt.txt](design/artwork-prompt.txt) and [design/concept-prompt.txt](design/concept-prompt.txt).

## Validation

The private application's actual catalog renderer passed native import, authored-text preservation in HTML/plain text, image and alternative-text preservation, button destination export, reopen/export stability, desktop/mobile screenshots, horizontal-overflow checks and keyboard access. Desktop (800px) and mobile (375px) screenshots were visually inspected against the study.

Additional local-preview checks passed at 320, 375, 600, 800 and 1440px: loaded imagery, no horizontal overflow, visible action, preserved unsubscribe token and keyboard access. An Arial fallback passed at 320 and 375px. A machine-readable viewport report is in [design/verification.json](design/verification.json). Browser previews do not certify every email client.

`preview-local.html` changes only the final asset URL to a relative local image path. The production image is published on assets.weavour.com and was verified against its local SHA-256. Tenant import and deployment remain separate release actions.
