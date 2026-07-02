# Ruby QA Checklist

Route id: `ruby`.
Route status: `active`.
Output path: `assets/<article-slug>-ruby/`.
Source authority: `source.md`.
Ruby identity note: preserve the energetic orange-bob-haired human IP with black cat-eye glasses, white or light inner top, red lips, confident friendly expression, hand-drawn black linework, and orange hand-drawn connection-line motif.
Wardrobe note: outfits may change, but the Ruby identity markers must remain stable; use the wardrobe library only when the user asks for clothing variants, avatars, stickers, or social assets.
Ruby route block: generic anime-girl drift, missing orange hair, missing black cat-eye glasses, wrong glasses shape, missing hand-drawn orange connection line, changed face identity, passive decoration, over-glam fashion poster, realistic photo drift, chibi drift, excessive text, route leakage, and copied composition all fail the route.
Save accepted Ruby output under `assets/<article-slug>-ruby/` with an ordered English slug filename such as `01-topic-name.png`.

## Pass Checks

- The selected route is `ruby` and the output path is `assets/<article-slug>-ruby/`.
- Ruby's orange bob hair is visible and dominant enough for recognition.
- Black cat-eye glasses are present and readable.
- Ruby has a warm confident human face, not a generic anime face.
- Red lips or smile accent appears when the face is visible.
- White or light inner top appears unless the requested outfit explicitly prevents it.
- Orange hand-drawn connection line/cable appears in article, wardrobe, sticker, or action outputs unless this is a plain avatar.
- Ruby performs the central action; removing Ruby breaks the metaphor or sticker action.
- The composition matches the requested mode: article illustration, avatar, transparent sticker, wardrobe variant, or action sticker.
- Labels, if present, are short, sparse, in the user's requested language, and do not cover Ruby's face, glasses, hair, hands, main prop, or orange connection line.
- Transparent stickers have clean silhouette, generous padding, and validated alpha after chroma-key removal.
- Wardrobe variants preserve stable identity markers while changing outfit language.

## Failure Signals

Regenerate or edit when any of these appear:

- generic anime-girl drift
- missing orange hair
- missing black cat-eye glasses
- wrong glasses shape
- missing hand-drawn orange connection line in non-plain-avatar outputs
- changed face identity
- passive decoration
- over-glam fashion poster
- realistic photo drift
- chibi drift
- excessive text
- route leakage
- copied composition
- Ruby standing beside the idea while props carry the meaning
- labels covering Ruby's face, glasses, hair, hands, main prop, or orange line
- dense PPT-like infographic or formal architecture diagram
- top-left title artifact
- public-figure or celebrity resemblance

## Iteration Moves

- If identity drifts: use `Ruby Identity Repair` from `prompt-template.md`.
- If Ruby is decorative: use `Stronger Ruby Participation`.
- If text is too much: use `Text Reduction`.
- If outfit cues drift: use `Wardrobe Continuity Repair`.
- If sticker alpha is dirty: rerun chroma-key removal with stronger edge contraction and inspect corners/alpha extrema.
- If the image is too fashion-poster-like: reduce pose glamour, add a concrete action, and bring back the orange connection line.
- If the image is too generic: inspect accepted wardrobe artifacts from `assets/vibrant-ruby-wardrobe-expansion/` and restate the exact identity markers.

## Delivery Judgment

A good Ruby output is recognizable in one second: orange bob hair, black cat-eye glasses, fresh human expression, and a hand-drawn orange connection line. The output should feel alive and useful, not like a generic fashion illustration.

Delivery should state:

- selected visual IP: Ruby / 活力Ruby / 鲜活人类
- image count
- purpose per image
- saved path under `assets/<article-slug>-ruby/`
- stability notes: which identity markers are strongest, and whether a wardrobe or sticker variant is optional
