# A slower kind of love

A quiet senior-cat adoption invitation built around an original sunlit portrait, a live personal letter, short full-width profile notes and a gentle meeting invitation.

Created with the email-design skill: original visual direction and [design study](design/concept.png), then native Weavour implementation. [Design intent](design/intent.md) records the campaign idea, intended copy, mobile reading order and translation decisions.

[Local preview](preview-local.html) · [Desktop](screenshot.png) · [Mobile](screenshot-mobile.png)

## Example content

Windowseat, Mabel, the stated age of twelve, temperament, home preferences and adoption arrangements are fictional sample content, not an actual adoptable animal or a verified assessment. Replace the entire profile and contact route with verified adoption-service details.

Replace example.com destinations before sending, add the actual sender identification/address as appropriate and preserve `{{unsubscribe_url}}` for substitution by the sending system. Customers handle email delivery. The public template contains no customer content or internal identifiers.

Subject: She has nowhere to be. Except, perhaps, your sofa.

Preheader: Meet Mabel, twelve years young and ready for a quieter chapter.

Tags: Pets, Promotion.

## Native design

The generated portrait postcard becomes a native photograph-first letter. The heading uses three intentional live lines, the letter is shorter than the study, and profile notes occupy full-width reading rows on all screens. The essential copy and action remain editable. The handwritten signature is interpreted as live italic Georgia rather than an image.

All essential text, headings, prices, campaign details, buttons and structure are native editable Weavour blocks. There is no monolithic HTML block and no campaign lettering in the production image. Typography uses local system font stacks with fallbacks; no web font dependency.

## Image provenance

The design study and final production image were created using OpenAI’s built-in image-generation tool on 26 October 2026. The final image used this template’s own generated concept as a visual reference. No stock or competitor artwork ships with this template. `design/concept.png` is a design reference, not an active email asset.

Production file: [images/mabel-window-bb06d93b0995.jpg](images/mabel-window-bb06d93b0995.jpg)

Hosted URL: https://assets.weavour.com/templates/windowseat-senior-cats/mabel-window-bb06d93b0995.jpg

The original generated file was 1254 × 1254px. It was proportionally resized to 1200 × 1200px and encoded as JPEG at quality 86. These dimensions were read from the actual files. The immutable filename includes the first twelve characters of the final bytes’ SHA-256: `bb06d93b09952e9111af0833a662c78640339826aa13e85385bc70bd8b76462d`.

### Actual production image prompt

Reference: the generated [design/concept.png](design/concept.png) for this template only.

> Use case: photorealistic-natural. Asset type: standalone production photograph for a fictional senior cat adoption email. An emotionally warm but unsentimental editorial portrait of a relaxed older cream-and-ginger domestic cat lying on a simple cream-painted windowsill in late-afternoon sunlight. Cat rests front paws naturally, looks calmly toward the camera with greenish-gold eyes, slightly mature face, soft real fur, sharp whiskers, dignified ordinary expression. The cat is beautiful in an everyday way, not cartoonish or extravagantly groomed. Warm window light and blurred soft green outdoors, close portrait showing the face, front paws and enough body to feel resting. Square composition with the whole ears and front paws in frame. The reference email is visual direction only. Produce a new standalone photograph, no text, typography, name label, logo, watermark, frames or email mockup. No props, collars, costumes or hands.

### Actual design study prompt

> Use case: ads-marketing. Asset type: full-email visual design study, not final production image. Create an emotionally intelligent, highly art-directed email introducing a fictional senior cat from WINDOWSEAT adoption service. A big tender editorial photograph arrives immediately after a tiny WINDOWSEAT masthead: relaxed older cream-and-ginger cat lying on a warm windowsill in afternoon sunlight, dignified natural expression, close portrait with visible soft fur and whiskers, no props or clothing. A narrow small-cap caption MABEL / 12 YEARS YOUNG. Then a generous very pale rose #f2e3de field with dark plum #4b2938 Georgia-style serif headline She has nowhere to be. and smaller line Except, perhaps, your sofa. A quiet personal letter in clear sans-serif explains an older cat with a gift for making a room feel like home. Two simple full-width ruled profile notes FAVOURITE PLACE / The sunny patch by the window. IDEAL HOME / A quiet room and a little company. Finish with a restrained plum Meet Mabel button and warm Windowseat signature. Design should feel like an intimate portrait postcard, no shelter card grid, no cute paw clip art, no three benefits panels. 600 wide by 1500 tall straight-on edge-to-edge, no browser/device. Minimal Unsubscribe footer.

Exact prompt files are also preserved at [design/artwork-prompt.txt](design/artwork-prompt.txt) and [design/concept-prompt.txt](design/concept-prompt.txt).

## Files and verification

`template.json` is the editable source. `template.html` is its actual Weavour renderer export. `preview-local.html` replaces only the production image URL with a relative image path for local use. Desktop and mobile screenshots are local browser captures at 800px and 375px viewports.

The private application’s catalog renderer passed native schema import, authored-text and alternative-text preservation, action export, reopen/export stability, desktop/mobile screenshots and first-link keyboard access. Actual desktop and mobile renders were visually inspected against the design study. Additional local-preview checks passed at 320, 375, 600, 800 and 1440px: no horizontal overflow, loaded imagery, visible action, keyboard access and preserved unsubscribe token. Arial fallback checks also passed at 320 and 375px. Browser captures do not certify every email client. The production image is published on assets.weavour.com and was verified against its local SHA-256. Tenant imports and deployment remain separate release actions.
