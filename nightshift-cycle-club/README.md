# Meet after the rush

A night cycling dispatch: a giant meeting time, reflector-yellow hierarchy, a cinematic riverside strip and a native three-stop route board.

Created with the email-design skill: [visual study](design/concept.png), [design intent](design/intent.md), native editable implementation, then inspection of the real export.

[Open local preview](preview-local.html) · [Desktop screenshot](screenshot.png) · [Mobile screenshot](screenshot-mobile.png)

## Design

Asphalt #171d22, reflector yellow #ebf783, warm white #f6f2e8 and supporting text #b7c2bf. Arial Black with Arial/Helvetica fallbacks gives the meeting time weight; Arial/Helvetica and Courier New/Courier keep the dispatch practical. The desktop canvas is 600px wide.

The meeting time stays the first visual event and fits at 320px with Arial fallback. The study’s transit-board routes become native number/label rows. Nonessential illustrative icons are omitted; lights, helmet and bicycle requirements remain live text.

All campaign copy, headings, labels, buttons and layout blocks remain native editable Weavour content. No external web font or monolithic HTML block is used.

Subject: 19:45. Meet after the rush.

Preheader: A social riverside loop, regrouping stops and a café finish.

Industry and purpose tags: Sports & outdoors, Event.

## Example content

Nightshift Social Cycle Club, Thursday 11 March 2027, the 19:45 meeting, 20:00 rollout, 12 km loop and all named landmarks are fictional examples. The generated photograph does not document a real route or event. The copy asks participants to check current organiser details and local conditions; it does not claim a traffic-free or guaranteed-safe route. Replace all sender identity, postal information, dates, availability, prices and offer claims with verified sender content before use. Replace the example.com reservation destination before sending. Keep and substitute `{{unsubscribe_url}}` through the sending system. Customers handle email delivery.

## Image provenance

Both [the visual study](design/concept.png) and the standalone production photograph were generated with OpenAI's built-in image-generation tool on 26 October 2026. The standalone photograph used its own complete prompt without an external reference image. No stock imagery is included. The study remains a design artifact and is excluded from the active image inventory.

Local artwork: [images/riverside-ride-746890ad414f.jpg](images/riverside-ride-746890ad414f.jpg)

Hosted URL: https://assets.weavour.com/templates/nightshift-cycle-club/riverside-ride-746890ad414f.jpg

The original PNG's actual dimensions were verified as 1536 × 1024px. It was proportionally resized and encoded as JPEG at quality 84; the final file's actual dimensions were verified as 1200 × 800px. The filename contains the first twelve characters of the final bytes' SHA-256. Full SHA-256: `746890ad414fafbc9e1cb2aa5a09459ad49382b69702089e5a0c87b25663c86b`.

Alternative text: Three helmeted cyclists with working rear lights follow a city riverside path at blue hour.

### Actual production photograph prompt

> Use case: photorealistic-natural. Asset type: standalone cinematic photograph for a fictional social cycling event email. A small group of three adult cyclists wearing helmets and normal practical jackets ride away from camera along a wide city riverside path at blue hour. The bikes have realistically visible front/rear lights; warm yellow bridge lights and city windows are reflected in the river to the right. Subtle motion in the bicycle wheels, the riders not racing and not leaning competitively. Landscape 3:2 framing, figures occupy left-of-centre lower half, a real small-group social ride atmosphere and rich dark asphalt, blue evening sky and warm reflections. No close-up faces, no logos or specific identifiable landmark, no text, no watermark, no impossible light trails. Original fictional event illustration, not documentary proof of a route.

### Actual visual study prompt

> Use case: ads-marketing. Asset type: full email visual design study for fictional NIGHTSHIFT social cycle club. One narrow portrait editorial dispatch, edge-to-edge straight-on, no device/browser. Deep asphalt #171d22, warm white #f6f2e8, reflector yellow #ebf783. This is a night ride meeting notice with the typography of an urban transport dispatch, not a generic sports newsletter. Small NIGHTSHIFT masthead and THU 11 MAR 2027 top line. A monumental bold sans-serif "19:45" meeting time is the first visual event, reflector yellow on asphalt. Below it a modest white headline "Meet after the rush." and small "ROLL OUT 20:00 / SOCIAL PACE". Across the middle, a cinematic very wide photograph of three cyclists with real front/rear lights travelling along a city riverside at blue hour, long city reflections, the figures small in the frame, no racing. Below it a thin reflector-yellow horizontal line and useful route details like a transit board: "01 / RIVERSIDE GATE", "02 / OLD BRIDGE", "03 / NIGHT WINDOW CAFÉ", arranged as three successive full-width rows with small separators, not cards. Text "12 km. Regrouping stops. Café finish." A contrasting yellow rectangular RSVP action and short practical kit line "LIGHTS / HELMET / ROADWORTHY BIKE". Tiny adult-event note, sender and Unsubscribe footer. Strong time-led hierarchy, compact reading rhythm, no gradients or rounded panels, no fake performance metrics.

Exact prompts also appear in [design/artwork-prompt.txt](design/artwork-prompt.txt) and [design/concept-prompt.txt](design/concept-prompt.txt).

## Verification

The actual Weavour renderer passed native import, authored-text and alternative-text preservation, button export, reopen/export stability, desktop/mobile captures and keyboard link access. Final desktop (800px viewport) and mobile (375px viewport) screenshots were visually inspected against the design direction.

Additional local browser checks passed at 320, 375, 600, 800 and 1440px: no horizontal overflow, loaded local artwork, visible links/actions and keyboard access. An Arial fallback passed at 320 and 375px. The unsubscribe merge token is retained. [Recorded browser checks](design/verification.json).

`template.json` is the editable source; `template.html` is its actual renderer export, synchronized with JSON `previewHtml`. `preview-local.html` changes only the hosted image URL to a relative local path. Browser previews do not certify every email client.

The production image is published on assets.weavour.com and was verified against its local SHA-256. Hosted tenant imports and application deployment remain separate release actions.
