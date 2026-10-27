# The stars stay late

A midnight travel field journal: a serif invitation, a star-filled cabin panorama, brief observational notes and a contrasting reservation slip.

Created with the email-design skill: [visual study](design/concept.png), [design intent](design/intent.md), native editable implementation, then inspection of the real export.

[Open local preview](preview-local.html) · [Desktop screenshot](screenshot.png) · [Mobile screenshot](screenshot-mobile.png)

## Design

Midnight #111e2d, starlight #f1ebd9 and pale gold #e6ba64. Georgia/Times New Roman carry the editorial statements; Arial/Helvetica and Courier New/Courier carry practical copy. The desktop canvas is 600px wide.

The study’s title over a star field becomes live serif copy on a readable solid midnight field followed by a full-width photograph. Keeping the whole image visible preserves the small cabin and distant horizon on mobile. The cream reservation close becomes a single short sequence that reads cleanly at 320px.

All campaign copy, headings, labels, buttons and layout blocks remain native editable Weavour content. No external web font or monolithic HTML block is used.

Subject: The stars stay late. So can you.

Preheader: Two quiet nights, a warm cabin and no plans after sundown.

Industry and purpose tags: Travel, Promotion.

## Example content

Aster, the illustrated cabin and landscape, the two-night stay for two guests, 12–14 February 2027 and £320 total are fictional examples. The generated night sky is illustrative and does not establish the actual sky at a destination or date. Weather and sky visibility are variable. Replace all sender identity, postal information, dates, availability, prices and offer claims with verified sender content before use. Replace the example.com reservation destination before sending. Keep and substitute `{{unsubscribe_url}}` through the sending system. Customers handle email delivery.

## Image provenance

Both [the visual study](design/concept.png) and the standalone production photograph were generated with OpenAI's built-in image-generation tool on 26 October 2026. The standalone photograph used its own complete prompt without an external reference image. No stock imagery is included. The study remains a design artifact and is excluded from the active image inventory.

Local artwork: [images/night-cabin-867733fa4920.jpg](images/night-cabin-867733fa4920.jpg)

Hosted URL: https://assets.weavour.com/templates/aster-stargazing-stay/night-cabin-867733fa4920.jpg

The original PNG's actual dimensions were verified as 1536 × 1024px. It was proportionally resized and encoded as JPEG at quality 84; the final file's actual dimensions were verified as 1200 × 800px. The filename contains the first twelve characters of the final bytes' SHA-256. Full SHA-256: `867733fa492016a4725fe31ffbb0ac0592aa20e1e76e3b4f079b1e5694a853ea`.

Alternative text: A small timber cabin with one warm window sits beneath a starry mountain sky beside a lake.

### Actual production photograph prompt

> Use case: photorealistic-natural. Asset type: standalone production photograph for a fictional remote cabin travel email. Create a magnificent editorial landscape in a dark navy and pale gold palette. A very small simple timber cabin with one warmly lit window sits on a rocky grassy rise at the lower left, a few dark pine silhouettes, a distant mountain ridge and a quiet lake. Above it a vast crisp starry night sky with a subtle natural-looking Milky Way. Landscape 3:2 framing. Real low-light long-exposure photographic texture, finely observed natural materials. The sky occupies the upper two thirds, cabin small enough to make the landscape feel immense. Calm and intimate rather than fantasy. No people, text, lettering, logo, watermark, labels, planets or unreal giant moon. This is a fictional illustrative destination photograph, not evidence of a real accommodation.

### Actual visual study prompt

> Use case: ads-marketing. Asset type: full email visual design study for fictional remote cabin stay ASTER. One narrow portrait editorial composition, straight on, edge to edge, no browser or phone. Create a beautiful midnight field journal, not a conventional travel newsletter. Dark ink navy #111e2d, ivory #f1ebd9, pale gold #e6ba64. Small widely spaced ASTER masthead, small journal issue notation. Elegant large serif headline at top left "The stars stay late." with a smaller italic "So can you." An extremely beautiful dark-sky cabin panorama occupies the middle: tiny timber cabin with one warm window under a vast real-looking starry sky, distant mountain silhouette. Below the panorama a gold hairline and small monospaced FIELD NOTES heading; two brief short observations arranged asymmetrically, "A kettle. A wool blanket." and "No plans after sundown." Finish with a contrasting cream reservation slip: "TWO NIGHTS / TWO GUESTS", "12–14 FEB 2027", "£320 total" and a navy rectangular View the cabin button. Tiny Unsubscribe footer. Make the typographic pacing deliberate and the panorama substantial; no rounded cards, no features grid, no decorative travel icons. This is a visual study; actual implementation later will keep text editable.

Exact prompts also appear in [design/artwork-prompt.txt](design/artwork-prompt.txt) and [design/concept-prompt.txt](design/concept-prompt.txt).

## Verification

The actual Weavour renderer passed native import, authored-text and alternative-text preservation, button export, reopen/export stability, desktop/mobile captures and keyboard link access. Final desktop (800px viewport) and mobile (375px viewport) screenshots were visually inspected against the design direction.

Additional local browser checks passed at 320, 375, 600, 800 and 1440px: no horizontal overflow, loaded local artwork, visible links/actions and keyboard access. An Arial fallback passed at 320 and 375px. The unsubscribe merge token is retained. [Recorded browser checks](design/verification.json).

`template.json` is the editable source; `template.html` is its actual renderer export, synchronized with JSON `previewHtml`. `preview-local.html` changes only the hosted image URL to a relative local path. Browser previews do not certify every email client.

The production image is published on assets.weavour.com and was verified against its local SHA-256. Hosted tenant imports and application deployment remain separate release actions.
