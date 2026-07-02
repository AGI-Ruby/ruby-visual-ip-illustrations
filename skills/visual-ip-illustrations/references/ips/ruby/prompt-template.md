# Ruby Prompt Template

Use this file after selecting the `ruby` route. Planning and delivery notes follow the user's language. Image-generation prompts may be English for model consistency. Visible labels are copied exactly in the user's requested language.

Route id: `ruby`.
Route status: `active`.
Output path: `assets/<article-slug>-ruby/`.
Source authority: `source.md`.
Ruby identity note: preserve the energetic orange-bob-haired human IP with black cat-eye glasses, white or light inner top, red lips, confident friendly expression, hand-drawn black linework, and orange hand-drawn connection-line motif.
Wardrobe note: outfits may change, but the Ruby identity markers must remain stable; use the wardrobe library only when the user asks for clothing variants, avatars, stickers, or social assets.
Ruby route block: generic anime-girl drift, missing orange hair, missing black cat-eye glasses, wrong glasses shape, missing hand-drawn orange connection line, changed face identity, passive decoration, over-glam fashion poster, realistic photo drift, chibi drift, excessive text, route leakage, and copied composition all fail the route.
Save accepted Ruby output under `assets/<article-slug>-ruby/` with an ordered English slug filename such as `01-topic-name.png`.

## Planning Output Format

Use this format for Ruby shot lists:

```text
1. Placement: [where this image appears]
   Core idea: [one sentence]
   Output mode: [Ruby Article Sketch / Ruby Social IP / Avatar / Transparent Sticker / Wardrobe Variant / Action Sticker / Mini Comic]
   Structure type: [Workflow / System Local View / Before/After / Character State / Concept Metaphor / Method Layers / Map Route / Mini Comic]
   Ruby state: [connecting / inspecting / tuning / presenting / sprinting / thinking / shining / playing / sorting / marking / bridging]
   Ruby action: [the physical cognitive or expressive action Ruby performs]
   Supporting objects: [1-3 objects]
   Visible labels: [short labels copied exactly in the user's requested language]
   Wardrobe: [default Ruby / Japanese City Boy / French Chic / Techwear / Vintage Rock v2 / Hip-hop / requested outfit]
   Output path: assets/<article-slug>-ruby/
   Ruby identity note: preserve orange bob hair, black cat-eye glasses, white or light inner top, red lips, hand-drawn black linework, and orange connection-line motif.
```

## Article Illustration Prompt

Replace bracketed fields. Keep one image per prompt.

```text
Generate one standalone 16:9 horizontal article illustration.

Route status note: Ruby is an `active` human personal visual-IP route. Use `source.md` as the source authority for identity markers, wardrobe library, sample policy, and route status.

Ruby identity note: preserve the energetic orange-bob-haired human IP with black cat-eye glasses, warm confident human face, white or light inner top, red lips/smile accent, expressive black hand-drawn linework, and the orange hand-drawn connection-line/cable motif.

Scene: [core idea in one sentence].

Visual language: clean hand-drawn/anime-line article illustration on a clean white or near-white background. Crisp but human black linework, generous whitespace, one enlarged Ruby action subject, and 1-3 low-density supporting objects. Use orange for hair and the connection-line motif. Use black for glasses, linework, and selected wardrobe. Use red only for lips/smile or tiny emphasis. No gradients, no dark background, no glossy vector corporate style, no dense infographic, no PPT slide, no UI screenshot, no poster composition.

Recurring IP: Ruby / 活力Ruby / 鲜活人类. Preserve vivid orange bob hair, black cat-eye glasses, warm confident face, red lips, white or light inner top, and the orange hand-drawn connection line. Ruby must perform the central action, not decorate the scene.

Structure type: [Workflow / System Local View / Before/After / Character State / Concept Metaphor / Method Layers / Map Route / Mini Comic].

Ruby state: [connecting / inspecting / tuning / presenting / sprinting / thinking / shining / playing / sorting / marking / bridging].

Ruby action: Ruby must perform the central cognitive or expressive action: [specific action]. The image should lose its meaning if Ruby is removed.

Supporting objects: [1-3 low-tech objects: orange cable, plug, notes, tags, map, bridge, gate, sign, lamp, stamp, key, lens, tote, bass, small machine, or requested props].

Composition: one core idea only. [Describe exact positions, Ruby's body direction, hand action, supporting objects, and information flow]. Ruby action takes about 35%-60% of the canvas. Leave generous whitespace around the action. Keep labels away from Ruby's face, glasses, hair, hands, main prop, and orange connection line.

Visible handwritten labels, copied exactly in the user's requested language: [quoted labels]. Keep labels concise, sparse, legible, and hand-drawn. Omit labels when the image is an avatar, sticker, or pure social asset unless the user asks for text.

Save reminder: save accepted output under `assets/<article-slug>-ruby/` with an ordered English slug filename such as `01-topic-name.png`.

Constraints: one image explains one core idea. Keep Ruby as the central action subject. Use no generic anime-girl drift, no missing orange hair, no missing black cat-eye glasses, no wrong glasses shape, no missing hand-drawn orange connection line, no changed face identity, no passive decoration, no over-glam fashion poster, no realistic photo drift, no chibi drift, no excessive text, no route leakage, no copied composition, no formal diagrams, no dense PPT-like infographics, no UI screenshots, no top-left titles, no clean digital font labels, no crowded nodes.
```

## Avatar Prompt

```text
Create a square avatar portrait of Ruby / 活力Ruby / 鲜活人类.

Preserve vivid orange bob hair, black cat-eye glasses, warm confident human face, red lips/smile accent, white or light inner top, expressive hand-drawn black linework, and a small orange hand-drawn connection-line motif if it fits naturally. Frame as head-and-shoulders or upper bust. Face and glasses must be large and unobstructed. Show requested wardrobe cues at the collar, shoulder, scarf, jacket, strap, bass, tote, or neckline. Clean white or near-white background. No text, no watermark, no extra characters, no chibi, no realistic photo drift, no over-glam fashion poster.
```

## Transparent Sticker Prompt

Use this with `imagegen` chroma-key removal unless the user explicitly chooses a native transparent-image fallback.

```text
Create a full-body or half-body sticker source image of Ruby / 活力Ruby / 鲜活人类 on a perfectly flat solid #00ff00 chroma-key background for background removal.

Preserve vivid orange bob hair, black cat-eye glasses, warm confident human face, red lips/smile accent, white or light inner top, expressive black hand-drawn linework, requested wardrobe, complete readable silhouette, and orange hand-drawn connection-line motif. One clear action only: [wave / think / sprint / shine / play bass / hold sign / connect cable / point / celebrate / pause / requested action]. Center Ruby with generous padding around all edges. No cast shadow, no contact shadow, no reflection, no text, no watermark, no extra characters. Do not use #00ff00 anywhere in Ruby, clothing, cable, glasses, props, or shoes.
```

## Editing Prompts

### Ruby Identity Repair

```text
Edit or regenerate with the same composition, successful action, style, labels, aspect ratio, and unaffected objects, but repair the character so it follows the Ruby route identity.

Preserve vivid orange bob hair, black cat-eye glasses, warm confident human face, red lips/smile accent, white or light inner top, expressive hand-drawn black linework, and orange hand-drawn connection-line motif. Remove generic anime-girl drift, wrong glasses shape, changed face identity, realistic photo drift, chibi drift, and over-glam fashion poster cues.
```

### Stronger Ruby Participation

```text
Regenerate with the same core idea and style, but make Ruby perform the central cognitive or expressive action. Ruby should physically connect, pull, plug, point, inspect, tune, carry, mark, sort, bridge, wave, think, sprint, shine, play, hold, celebrate, or pause the concept through the scene. The metaphor should depend on Ruby's action.
```

### Text Reduction

```text
Edit or regenerate with the same core idea, Ruby action, style, and unaffected objects, but reduce visible text. Keep only these labels, copied exactly in the user's requested language: [quoted labels]. Remove dense annotations, bilingual text, top-left titles, clean digital typography, and labels that crowd Ruby's face, glasses, hair, hands, main prop, or orange connection line.
```

### Wardrobe Continuity Repair

```text
Edit or regenerate with the same Ruby identity and successful composition, but repair the wardrobe to match: [Japanese City Boy / French Chic / Techwear / Vintage Rock v2 / Hip-hop / requested outfit]. Keep orange hair, black cat-eye glasses, white or light inner top, red lips/smile, and orange connection line stable.
```
