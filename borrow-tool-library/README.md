# Own the project

A neighbourhood tool-library membership email designed as a bold photo-first checkout slip, with a live dashed inventory receipt and a clear annual membership close.

Created with the email-design skill: original visual direction and [design study](design/concept.png), then native Weavour implementation. [Design intent](design/intent.md) records the campaign idea, intended copy, mobile reading order and translation decisions.

[Local preview](preview-local.html) · [Desktop](screenshot.png) · [Mobile](screenshot-mobile.png)

## Example content

Borrow, 8 Workshop Yard, the £18 annual price, available tool inventory and lending terms are fictional examples. Replace all membership terms, eligibility and availability with verified sender details.

Replace example.com destinations before sending, add the actual sender identification/address as appropriate and preserve `{{unsubscribe_url}}` for substitution by the sending system. Customers handle email delivery. The public template contains no customer content or internal identifiers.

Subject: Own the project. Borrow the tools.

Preheader: A year of useful things, without a shed full of equipment.

Tags: Community, Promotion.

## Native design

The concept’s checkout structure is preserved through editable dashed borders, native inventory rows and a bold membership close. The little tool thumbnails and illustrated receipt edges in the design study are omitted; one original tools photograph carries the material detail. Practical copy stays live. The title is sized for a normal Arial fallback at mobile widths.

All essential text, headings, prices, campaign details, buttons and structure are native editable Weavour blocks. There is no monolithic HTML block and no campaign lettering in the production image. Typography uses local system font stacks with fallbacks; no web font dependency.

## Image provenance

The design study and final production image were created using OpenAI’s built-in image-generation tool on 26 October 2026. The final image used this template’s own generated concept as a visual reference. No stock or competitor artwork ships with this template. `design/concept.png` is a design reference, not an active email asset.

Production file: [images/workshop-tools-0c065d165224.jpg](images/workshop-tools-0c065d165224.jpg)

Hosted URL: https://assets.weavour.com/templates/borrow-tool-library/workshop-tools-0c065d165224.jpg

The original generated file was 1536 × 1024px. It was proportionally resized to 1200 × 800px and encoded as JPEG at quality 86. These dimensions were read from the actual files. The immutable filename includes the first twelve characters of the final bytes’ SHA-256: `0c065d165224727937d374109d6cf040ab23700da7ed318ed186a5ebdfa7be4d`.

### Actual production image prompt

Reference: the generated [design/concept.png](design/concept.png) for this template only.

> Use case: photorealistic-natural. Asset type: standalone production photograph for a tool lending-library email. A striking top-down editorial photograph of three real, slightly worn workshop tools: a black cordless drill with subtle warm yellow details, a wooden-handled claw hammer, and two small orange metal clamps. Arrange them diagonally with practical intention on a charcoal-green scarred workbench, with a few wood shavings, real worn metal and wood grain, warm raking workshop light and deep shadows. Close, graphic, textural, no human, no brand names or lettering on the tools. Landscape 3:2 composition, the important tools all recognisable in frame. The reference email is only an art-direction reference. Deliver a new standalone photograph matching its physical material feeling, no words, labels, text, logos, watermark, frames, borders or email interface.

### Actual design study prompt

> Use case: ads-marketing. Asset type: full-email visual design study, not final production image. Create an original email for fictional BORROW TOOL LIBRARY. It is a contemporary tool checkout slip: canary yellow #f6d94f, near-black #20251f, receipt cream #faf7e9. Opening small masthead BORROW / NEIGHBOURHOOD TOOL LIBRARY. A bold full-width editorial still-life photograph comes FIRST: a used black cordless drill, wooden hammer and orange clamps carefully arranged diagonally on a charcoal-green workbench, real worn materials and dramatic practical light, no words on tools. Then huge black heavy sans title OWN THE PROJECT. and contrasting line BORROW THE TOOLS. in a yellow field. A dashed-line cream lending receipt lists three kit/job pairings DRILL / THE SHELF, SANDER / THE CHAIR, CLAMPS / THE BIG IDEA in monospaced type. Finish as a checkout strip with a large £18 / PER YEAR and a black rectangular Join the library button. Small copy explains choose a tool, borrow it, bring it back. Short, bold and specific, no generic three-card stack or round corners. 600 wide by 1400 tall straight-on, no device/browser. Small Unsubscribe footer.

Exact prompt files are also preserved at [design/artwork-prompt.txt](design/artwork-prompt.txt) and [design/concept-prompt.txt](design/concept-prompt.txt).

## Files and verification

`template.json` is the editable source. `template.html` is its actual Weavour renderer export. `preview-local.html` replaces only the production image URL with a relative image path for local use. Desktop and mobile screenshots are local browser captures at 800px and 375px viewports.

The private application’s catalog renderer passed native schema import, authored-text and alternative-text preservation, action export, reopen/export stability, desktop/mobile screenshots and first-link keyboard access. Actual desktop and mobile renders were visually inspected against the design study. Additional local-preview checks passed at 320, 375, 600, 800 and 1440px: no horizontal overflow, loaded imagery, visible action, keyboard access and preserved unsubscribe token. Arial fallback checks also passed at 320 and 375px. Browser captures do not certify every email client. The production image is published on assets.weavour.com and was verified against its local SHA-256. Tenant imports and deployment remain separate release actions.
