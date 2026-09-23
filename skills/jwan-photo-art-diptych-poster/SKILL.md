---
name: jwan-photo-art-diptych-poster
description: Turn one supplied photo into a 3:4 top-original / bottom-art diptych. Preserve the original photo above and reinterpret the same composition below using either travel mixed-media or contemporary East Asian ink.
metadata:
  version: 1.0.0
  author: Jwan
  license: MIT
---

# Jwan Photo Art Diptych Poster

Create one vertical 3:4 poster from one supplied photo. The top half remains the photographic source; the bottom half becomes a materially distinct artistic reinterpretation of the same scene.

This Skill is for photo-to-art comparison posters, not generic before/after layouts.

## Invocation

Use $jwan-photo-art-diptych-poster with one source photo.

Optional mode:
- travel-mixed-media
- east-asian-ink

Optional inputs:
- exact English theme line
- material labels
- palette preference
- whether people must remain strictly recognizable
- one requested revision

## Core geometry

1. Canvas: vertical 3:4.
2. Use a near-even horizontal split: each half approximately 48–52% of total height.
3. Place the original photograph on top.
4. Place the reinterpretation below.
5. Use a narrow warm off-white divider between the two zones.
6. Keep both halves aligned to the same scene geometry so the viewer can compare them immediately.
7. Add a small handwritten Jwan signature at bottom-right by default.

## Top-half fidelity

The upper photo is the source record.

Preserve:
- people and recognizable identity
- age cues
- clothing and accessories
- camera angle
- architecture / landscape structure
- major props and visual relationships
- original scene hierarchy

Do not redraw, replace, restage, or add unrelated objects in the upper half unless explicitly requested.

## Mode A — travel-mixed-media

Use when the image is travel, architecture, street, exhibition, landscape, or lifestyle oriented.

Visual language:
- black or dark ink contour
- dry brush
- watercolor blocks
- 4–6 controlled spot colors
- torn-paper or printed-fragment accents
- visible paper grain
- simplified forms with recognizable source structure
- editorial travel-poster feeling

Rules:
- derive every important shape from the source photo
- preserve horizon, major architecture, subject position, and camera logic
- simplify texture before simplifying identity
- let paper and brush marks remain visible
- avoid photorealistic repainting
- do not turn the bottom into a cartoon scene

Typography:
- optional short English theme
- optional small material field such as INK / DRY BRUSH / WATERCOLOR / COLLAGE
- keep all text secondary and outside important subject areas

## Mode B — east-asian-ink

Use when the user wants a more restrained contemporary East Asian visual language.

Visual language:
- xuan-paper feeling
- broken ink
- dry-brush flying-white texture
- large negative space
- restrained grayscale or very limited accent color
- fine clustered ink dots
- abstracted edges
- minimal brush intervention

Rules:
- preserve the photographic composition while reducing visual information
- keep the subject recognizable through silhouette, posture, spatial position, and a few key details
- use blank paper as an active compositional element
- prefer fewer, stronger brush decisions
- avoid decorative traditional motifs unless they are already in the source or explicitly requested

## Human fidelity

When people appear:
- preserve recognizable facial identity as accurately as the tool allows
- preserve apparent age, hairstyle, clothing, body proportion, and pose
- do not replace the person with a generic illustrated character
- do not exaggerate facial features unless requested

## Revision discipline

If the user requests one change, change only that element.

Examples:
- "下面颜色少一点" -> reduce lower palette only
- "插画更水墨一点" -> change lower rendering language, not the top photo
- "人物不要变" -> lock identity and pose
- "文字删掉" -> remove typography only
- "分隔线窄一点" -> adjust divider only

## Hard avoid list

- redrawing the top photo
- unrelated lower composition
- large title blocking the source
- arbitrary fantasy details
- overdecorated Chinese motifs
- heavy gradient backgrounds
- full-bleed photorealistic lower repaint
- changing unrelated elements during a one-item revision

## Quality gate

Verify:
- 3:4 vertical
- source photo remains on top
- lower art clearly derives from the same composition
- narrow divider is visible
- chosen mode is visually consistent
- people remain recognizable when present
- negative space and material texture are intentional
- typography is secondary
- small Jwan signature is present bottom-right

## Attribution and contact

Created by Jwan.
GitHub: https://github.com/gongjuan96-crypto
Skill catalog: https://github.com/gongjuan96-crypto/jwan-skills

Keep Jwan attribution when redistributing or adapting this Skill.
