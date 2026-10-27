# Room for quiet

An email for fictional Feltwork, a small room-acoustics consultancy. Created with the email-design skill, beginning with [a visual study](design/concept.png) and [design intent](design/intent.md) before native implementation.

[Local preview](preview-local.html) · [Desktop](screenshot.png) · [Mobile](screenshot-mobile.png)

## Visual direction

A service letter designed to feel quiet before the reader reads it. Oversized italic live “shh.” sits on warm uncoated-paper colour. A panoramic wool-felt photograph serves as a material pause; the designer’s letter and an open ruled appointment summary carry the offer. No performance statistics, feature-card grid or generic office hero.

Palette: paper #f7f3e9, oxblood #4a2935, terracotta #a7472c, muted mauve #75646a. Georgia/Times New Roman/serif for the live display and letter; Courier New/Courier/monospace for practical details. Native editable headings, text, columns, rules, spacers and a button. No external font requests or essential copy in images.

## Sample offer and sender

Feltwork, Lena, 12 Workshop Mews, a 90-minute room review, £180, the written shortlist and the stated service scope are fictional sample details. Replace these with the sender’s verified offer, service area, qualifications and contact details. No measured acoustic improvement is claimed. The artwork is an imagined material study, not a photograph of a delivered client project.

Replace https://example.com/feltwork/room-review before sending, add the actual sender details as appropriate, and preserve/substitute `{{unsubscribe_url}}` through the sending system. Customers handle email delivery.

Subject: Your meeting room has a voice.

Preheader: A 90-minute room review from Feltwork. Less echo. More conversation.

Tags: Business, Service.

## Image provenance

Both the concept and the standalone production photograph were generated using OpenAI’s built-in image-generation tool on 26 October 2026. No stock images or competitor artwork are included. The concept is kept in `design/` and is not an active email asset. The final photograph was generated independently from the chosen art direction, without an input-image reference.

Local production image: [images/felt-baffles-7ed219563c40.jpg](images/felt-baffles-7ed219563c40.jpg)

Hosted URL: https://assets.weavour.com/templates/feltwork-room-review/felt-baffles-7ed219563c40.jpg

The generated original was 2170 × 725px. The final email JPEG was proportionally resized to a 1440 × 481px and encoded at quality 86. The filename hashes the final JPEG bytes. SHA-256: `7ed219563c4082274d317d254cf7a49d547fd1fb32c4f6924c0dcbd841222ab0`.

Alternative text: Curved clay and oat wool-felt acoustic baffles hang above a sunlit oak meeting table.

### Actual production photograph prompt

> Use case: photorealistic-natural.
> Asset type: standalone panoramic architectural material photograph for an editable acoustic-consultancy email. No text, no email mockup.
> Primary request: A beautifully observed intimate architectural studio with a sculptural set of suspended wool-felt acoustic baffles. Three thick real felt panels curl gently like broad hanging ribbons above the edge of a long oak meeting table. Colours are terracotta clay, oatmeal and warm ivory. Slim suspension wires are realistically attached to the ceiling. Visible tactile dense wool fibres and beautifully considered curves. Strong physical presence and honest architectural photography.
> Framing: wide panoramic 3:1 photograph, low upward view toward the baffles, left-side window light raking across warm pale plaster. A little oak table and a single simple chair at the bottom edge, no decorative clutter, plants, people, laptop or office branding. The curving felt forms occupy the upper two-thirds with quiet plaster negative space below. The photo acts as a material sample and visual pause within a quiet editorial service letter.
> Lighting: natural morning sunlight with sculptural but soft shadows, believable materials, warm neutral white balance. No glossy render aesthetic, no dramatic cinematic effects.
> Palette: warm uncoated paper #f7f3e9, clay terracotta, oat wool and dark wine/oxblood small shadow notes.
> Constraints: NO lettering, no numbers, labels, logo, watermark, borders, email interface or diagrams. Fresh original photograph.

### Actual design study prompt

> Use case: ads-marketing.
> Asset type: full-email visual design study for a fictional acoustic consultancy FELTWORK. This is a concept reference, not a production email image.
> Design a highly considered editorial email about a 90-minute room-acoustics review. Narrow portrait composition 600 wide by about 1550 tall, straight-on, edge to edge, no device or browser.
> Visual idea: a quietly radical service letter that makes the reader feel the difference between noise and calm. Warm uncoated paper #f7f3e9, oxblood ink #4a2935, terracotta #a7472c, fine muted mauve rules. No gradients, icons, cards, graphs, benefit columns or typical business newsletter sections.
> At top a restrained serif FELTWORK wordmark at left, ROOM ACOUSTICS at right in tiny monospaced type. Below, small ROOM NOTE 01 and a huge lowercase italic Georgia-like “shh.” in oxblood, occupying much of the upper third with beautiful paper space. Beneath it, a small serif line “A room can do some of the listening.”
> A panoramic material photograph acts as a horizontal visual pause: sculptural curved wool-felt acoustic baffles suspended in an intimate warm-white architectural studio, clay and oatmeal fabric, generous empty plaster wall, real daylight and delicate sculptural shadows. This is a tactile material sample, NOT a generic office stock photograph.
> Below the photograph, a short full-width editorial letter in a beautiful readable serif: “If your meeting room keeps talking after everyone stops, start with the room.” Follow with a few realistic lines about looking at hard surfaces, layout and how people actually use the space, then a practical written plan. Sign off in small italic “Lena, acoustic designer”.
> An open ruled appointment summary, no boxed card, uses large oxblood “90” at left with small MINUTES and practical right text THE ROOM REVIEW / £180 / One room. A practical starting point.
> One small terracotta rectangular button “Book a room review”. Finish with small “Less echo. More conversation.”, restrained FELTWORK and Unsubscribe footer.
> Creative emphasis: typographic scale, intentional empty paper, evocative panoramic material image and an informal designer’s letter. Single coherent elegant composition. Actual copy must look credible, no filler text, no price guarantee or made-up performance measurements.

Exact text is also retained in [design/art-prompt.txt](design/art-prompt.txt) and [design/concept-prompt.txt](design/concept-prompt.txt).

## Implementation

`template.json` is the native editable source; `template.html` is the actual Weavour renderer export. `preview-local.html` changes only the hosted photograph URL to a relative local image path. Desktop/mobile screenshots are local browser captures, not certification across all email clients.

The design study’s paper texture and live typography are translated into flat native surfaces and system fonts, while the photograph retains real material texture. Essential text, offer, layout and action remain editable. The production image is published on assets.weavour.com and was verified against its local SHA-256. Tenant imports and deployment remain separate release actions.


## Validation

The actual private application renderer passed native import, reopen/export stability, authored text and alternative-text preservation, button export, desktop/mobile captures and keyboard access. Additional local previews passed at 320, 375, 600, 800 and 1440px, with loaded photography and a visible booking action. Arial fallback passed at 320 and 375px. The opening type was reduced from 170px to 160px after the 320px check caught a six-pixel overflow. Final desktop/mobile renders were visually inspected.
