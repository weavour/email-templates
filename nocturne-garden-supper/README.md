# Some nights are worth staying for

A continuous candlelit garden-supper invitation for the fictional Nocturne supper club. Inspired by the campaign variety in [Unlayer’s gallery](https://unlayer.com/templates), with original composition, copy and newly generated backgrounds.

[Local HTML preview](preview-local.html) · [Desktop](screenshot.png) · [Mobile](screenshot-mobile.png)

## Design

Deep forest #101d1b, warm ivory #f5eedf, muted sage #d4d9cd and restrained candle gold #ddbf83. Georgia supplies the editorial headlines; Arial keeps practical copy and the action email-safe. The 600px document has no outer card or section gutters. Three native section background images carry the garden-table arrival, botanical menu and final invitation. Their shared dark field and photographic fades create a continuous atmosphere across sections; the hero’s edited lower edge removes a hard cut through the table. All headlines, menu courses, event details, spacers and the booking action are native editable content layered above those images. There are no HTML blocks and no content baked into a composite email image.

Backgrounds use the editor’s native cover/center treatment, so mobile crops preserve the central reading field while trimming peripheral decoration. A transparent native two-column layout holds event details within the final background. Solid forest colors preserve readable ivory and gold copy when backgrounds are unavailable. Background imagery is decorative; the event, menu and action remain expressed in live text and the plain-text export.

The Nocturne palette and typography belong to the fictional sender’s email, independently of Weavour’s website branding and configurable editor chrome.

## Personalize before sending

Nocturne, the venue, menu, Thursday 17 June 2027, event time and £68 price are fictional campaign examples. The pictures depict an imagined dinner and are not photographs of an actual venue. Replace sender identity and postal details, campaign facts, dietary/allergen guidance, and example.com destinations before sending. Configure your platform’s substitution for the intact {{unsubscribe_url}} token. Customers handle delivery.

## Artifacts and compatibility

The JSON document is the native editable source. template.html is the actual Weavour export, including standard background attributes and Outlook VML fallbacks for the three sections. preview-local.html changes only image URLs to relative paths so the design opens locally before asset publication. Desktop and mobile screenshots are browser captures at 800px and 375px. Background rendering and cropping can vary across email clients; the screenshots do not certify mailbox behavior.

## Image provenance

Three original photographic backgrounds were created with OpenAI’s built-in image-generation tool. The hero received one built-in edit to fade its lower edge into forest green. No competitor artwork, stock photos or reused catalog imagery was used. Generated originals were encoded as JPEG for email delivery; each final file embeds its exact prompt history and has a SHA-256-derived immutable filename. No campaign lettering is part of the artwork.

### garden-dinner

Local file: [images/garden-dinner-ddd5e473a648.jpg](images/garden-dinner-ddd5e473a648.jpg)

Hosted URL: https://assets.weavour.com/templates/nocturne-garden-supper/garden-dinner-ddd5e473a648.jpg

Dimensions: 1024 × 1536px.

Exact built-in generation prompt:

> Use case: photorealistic-natural. Asset type: photographic background for a native editable email layout, not an email mockup. A magical intimate outdoor supper table in a Mediterranean walled garden at blue hour, ivory linen and hand-thrown ceramic plates, small brass candleholders with warm candle flames, olive branches and a few white blossoms. Cinematic fine dining editorial photography, photoreal materials, restrained warm amber against extremely deep forest green. Tall portrait 2:3 framing. Composition is CRITICAL: top 55 percent is beautifully quiet almost-solid very dark forest green (#101d1b), with barely visible leafy silhouettes only at extreme edges; the actual table and candles occupy the bottom 40 percent, inviting a sense of arrival. Keep the central upper field empty for separately editable ivory text, with no bright objects behind text. Both the very top and bottom edges must fade softly and invisibly into uniform solid #101d1b, no vignette border or rectangular frame. No lettering, no people, no logos, no watermark, no UI.

Exact built-in edit prompt, applied to the generated original:

> Edit this existing garden supper photograph. Preserve the camera composition, candlelit table, olive trees, all upper and middle details, colors and photographic realism. Change ONLY the lower 28 percent: gently dissolve the lower linen tablecloth and chair into a smooth natural deep forest-green fade matching #101d1b. The bottom 12 percent must be completely uniform solid #101d1b across the ENTIRE width, including both corners, with no remaining table, chair, texture or light. The transition above must be invisible and gradual, not a hard horizontal band. This will be a continuous email layout background merging with another #101d1b section. Leave a beautiful visible table and candles above the fade; preserve the upper dark negative space for live editable copy. Keep the same portrait aspect ratio. No lettering, no logo, no border, no UI.

### botanical-menu

Local file: [images/botanical-menu-2a92617d30e6.jpg](images/botanical-menu-2a92617d30e6.jpg)

Hosted URL: https://assets.weavour.com/templates/nocturne-garden-supper/botanical-menu-2a92617d30e6.jpg

Dimensions: 1024 × 1536px.

Exact built-in generation prompt:

> Use case: photorealistic-natural. Asset type: photographic background for an editable email menu layout, not a mockup. Coordinated fine dining campaign at night: extremely deep matte forest green backdrop exactly #101d1b, with photoreal olive sprigs and a few tiny ivory jasmine blossoms appearing very sparingly along the extreme left and right edges, a small softly lit lemon half and subtle brass candleholder at the far bottom corners. Refined still-life editorial photograph with soft candle light, believable textures, very restrained, luxurious without ornate ornament. Tall portrait 2:3 framing. Center 80 percent remains nearly uniform #101d1b with low contrast for ivory editable menu text. Top and bottom 12 percent fade seamlessly to absolutely uniform solid #101d1b, no visible frame or border. No lettering, no people, no logos, no watermark, no UI.

### last-candle

Local file: [images/last-candle-57fe8a12d6ca.jpg](images/last-candle-57fe8a12d6ca.jpg)

Hosted URL: https://assets.weavour.com/templates/nocturne-garden-supper/last-candle-57fe8a12d6ca.jpg

Dimensions: 1536 × 1024px.

Exact built-in generation prompt:

> Use case: photorealistic-natural. Asset type: photographic background for a native email invitation closing layout, not an email mockup. The end of an intimate garden supper at blue hour, one elegant small brass candle holder with lit cream taper and soft olive leaves at the far bottom right, a rumpled ivory linen napkin barely visible in the bottom left, distant tiny amber candlelight bokeh confined to extreme edges. Refined analog fine dining editorial photography, rich dark forest green and subtle warm gold. Wide landscape 3:2 framing. Central 75 percent and upper half are nearly uniform solid deep forest green #101d1b, very dark calm negative space for editable invitation text. All four edges merge softly to uniform #101d1b so this image blends invisibly with a dark page. No lettering, no people, no logos, no watermark, no UI.

## Verification

The final visual reviewer confirmed that the earlier abrupt hero/table seam was resolved at 800px desktop and 375px mobile widths and approved shipping within that browser-review scope. This is not cross-client email certification.

Completed validation reported for this extension:

- Native import and reopen preserved the authored text, booking button and all three background attributes without export drift.
- Browser checks at 800px and 375px passed image loading, overflow and keyboard access to the first link. The local preview loads all three relative background files.
- All three sections retain the solid `rgb(16, 29, 27)` fallback; the export retains three VML fallbacks and the unsubscribe token. Final asset filenames were checked against their hashes.
- All five catalog tests passed, including the new background validator security-boundary test. The source catalog contains 113 templates; the application’s pinned snapshot remains unchanged at 101.

## Publishing

The new image URLs have not been published. Publish assets before refreshing the private application’s pinned catalog or importing into hosted tenant libraries. Local rendering and SQL generation do not publish, deploy or send anything.
