# No undo

A printmaking workshop invitation for fictional Offcut Studio. Built with the email-design skill: [visual study](design/concept.png), [design intent and copy](design/intent.md), then native implementation and comparison with the rendered result.

[Open local preview](preview-local.html) · [Desktop screenshot](screenshot.png) · [Mobile screenshot](screenshot-mobile.png)

## Design

A narrow 440px studio poster with a monumental live NO / UNDO. title, a full-width two-ink brayer still life, a short vermilion date strip and a compact booking close. Warm paper #f3ebcd and cobalt #1838d0 carry the composition; the date strip uses #c3321f for readable cream text. Dark body ink is #20272c. The title uses Arial Black with bold Arial/Helvetica fallbacks, supporting display copy uses Impact with system fallbacks, and practical copy uses Courier New/Courier/monospace. No external font loading.

The generated concept was created before inspecting the document schema. The final interpretation uses different live type sizes for the two headline lines, moves the artwork's side note into a live caption, and uses crisp editable lettering rather than rasterized distress. The secondary headline was tightened after mobile inspection. All campaign copy, offer details, typography, buttons and layout blocks remain native editable Weavour content. The image contains no words or essential information.

## Example campaign details

Offcut Studio, 14 Foundry Lane, Saturday 20 March 2027, 18:30–21:00, £45 per person, ten take-home prints, and included paper, inks and first drink are fictional sample details. Replace sender details, venue, date, availability and claims with verified content before use. Replace the example.com booking destination before sending and add the actual sender identification/address as appropriate. Preserve and substitute `{{unsubscribe_url}}` through the sending system. Customers handle email delivery.

Subject: Your hands. Two inks. No undo.

Preheader: A printmaking evening at Offcut. Make ten prints, keep the happy accidents.

Industry and campaign tags: Arts & culture, Event.

## Image provenance

Both the visual study and the final artwork were generated with OpenAI's built-in image-generation tool on 26 October 2026. The final still life used the generated concept as a style/composition reference; no stock photograph or competitor artwork is included. The concept is a design artifact and is not part of the active email image inventory.

Final artwork: [images/ink-brayer-3a3a39e4ac49.jpg](images/ink-brayer-3a3a39e4ac49.jpg)

Hosted asset URL: https://assets.weavour.com/templates/offcut-print-night/ink-brayer-3a3a39e4ac49.jpg

The original generated photograph was 1536 × 1024px. It was proportionally resized to 1200 × 800px and encoded as JPEG at quality 90. The filename contains the first twelve characters of the final JPEG's SHA-256. Full SHA-256: `3a3a39e4ac49fb3d8e12b081e4204174a764fd9637e69c9f98e85465f09cd8e6`.

Alternative text: A cobalt ink-covered brayer lies diagonally over a blue circle and a vermilion block printed on torn cream paper.

### Actual final artwork prompt

Reference input: the generated full-email visual study at [design/concept.png](design/concept.png).

> Use case: photorealistic-natural.
> Asset type: production artwork for the central image of an editable printmaking workshop email. This is ONLY a photograph, no email mockup and NO TEXT.
> Primary request: An arresting tactile editorial flat-lay still life of an authentic ink-covered black rubber printmaking brayer resting diagonally across handmade warm yellow paper with two fresh block prints. The brayer roller is heavily coated in vivid cobalt blue ink, its black handle points toward the bottom right, the whole brayer is visible within frame. A large beautifully imperfect blue printed circle fills the left part; a vermilion red rough rectangular print comes in from the lower left. Layers of torn and deckle-edged warm cream paper, richly visible fibres and real viscous ink. Limited two-ink palette cobalt #1838d0, vermilion #e34428 and warm cream #f3ebcd. Real photography, sharp material detail, rich raking studio light, striking print-culture art direction. No polished plastic or 3D illustration.
> Composition: landscape 3:2, designed for a full-width graphic editorial email. Strong diagonal brayer from upper right through middle to lower right. The blue circle and red block give a bold graphic balance. Include a small blank torn cream paper area at the far lower right; absolutely no marks resembling letters. Crop close for strong impact while keeping the roller recognisable.
> Match the physical ink/paper feeling of the central still life in the reference email design study. The reference is visual direction only. Deliver a fresh standalone photograph, not the email design, with no typography, captions, words, numbers, logo, watermark, frames or borders.

### Actual visual study prompt

> Use case: ads-marketing.
> Asset type: full-email visual design study, NOT a production asset.
> Design a superb, highly art-directed contemporary email poster for a fictional independent print studio OFFCUT announcing an evening printmaking workshop. One narrow portrait composition, about 600 wide by 1500 tall, shown straight-on edge-to-edge, no device, no browser, no outer mockup shadows.
> Concept: NO UNDO. Physical ink, paper, human marks. Modern independent print-culture design with a fiercely confident asymmetrical editorial composition, NOT a generic newsletter.
> Palette strictly warm yellow paper #f3ebcd, forceful cobalt #1838d0, vermilion #e34428, dark ink #20272c. Heavy grotesk oversized live-looking typography, compact monospaced details. No gradient, no rounded cards.
> Opening: cream paper masthead with small cobalt OFFCUT wordmark left and small PRINT STUDIO right. Next a cobalt field with very large warm-paper words NO then UNDO. stacked flush left, forceful, monumental, nearly filling the width. Small vermilion registration marks at the edges. The composition should feel like a print poster.
> Central art moment: asymmetrical graphic editorial flat-lay photograph: real black rubber printmaking brayer with ink-blue roller diagonally across tactile torn warm paper, hand-printed cobalt rough circle, vermilion irregular block, vivid real ink texture, warm raking light. Integrate a small cream side note reading Your hands. Two inks. Ten prints. Give this artwork real scale. No faces, no plants.
> Below the artwork: a vermilion narrow caption band reading PRINT NIGHT / SAT 20 MAR 2027. On warm stock use a short editorial note with cobalt heading Leave the perfect edges to someone else. and a little realistic body copy explaining rolling ink, cutting a shape and pulling ten prints.
> Finish compactly with a cobalt booking panel using small warm-paper typography: 18:30–21:00, £45 per person, Paper, inks and your first drink included, Offcut Studio, 14 Foundry Lane. An obvious warm-paper rectangular Book a place button. Minimal cream footer with OFFCUT and Unsubscribe.
> No three-card stack. No generic stock photo. Short sharp composition with strong changes of scale and no large dead empty gap. This is a designer's visual study to guide later native editable implementation.

Exact prompt text is also kept in [design/artwork-prompt.txt](design/artwork-prompt.txt) and [design/concept-prompt.txt](design/concept-prompt.txt).

## Files and verification

`template.json` is the editable source and `template.html` is its actual Weavour renderer export. `preview-local.html` changes only the artwork URL to its relative local image path. Local screenshots use 800px desktop and 375px mobile viewports. Concept studies remain in `design/`.

The private application's catalog renderer passed native import, authored-text and alternative-text preservation, button export, reopen/export stability, desktop/mobile capture and first-link keyboard access. All six catalog tests passed with 156 templates, including migration-backed import idempotency and preservation of independent copies. The import command generated review SQL for all 156 templates without applying it.

Additional local-preview checks passed at 320, 375, 440, 600, 800 and 1440px: no horizontal overflow, loaded artwork, visible booking action, keyboard access and preserved unsubscribe token. An Arial fallback also passed at 320 and 375px. Final desktop, mobile and 320px fallback screenshots were visually inspected. Local browser previews do not certify rendering in every email client.

This template is created locally. Hosted image publication, tenant imports and application deployment are separate release actions.

