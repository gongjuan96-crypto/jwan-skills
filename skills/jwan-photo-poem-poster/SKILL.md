---
name: jwan-photo-poem-poster
description: Turn one supplied photo into Jwan's established photo-poem diptych: faithful original photo above, smaller hand-drawn memory illustration below, restrained bilingual copy, generous breathing room, and a small Jwan signature.
metadata:
  version: 1.1.0
  author: Jwan
  license: MIT
---

# Jwan Photo Poem Poster

Create one finished memory poster from one supplied photo. The result is not a generic collage: it follows a stable two-part visual system in which the original photograph remains the factual anchor and a smaller illustration below acts as its poetic echo.

## Invocation

Use $jwan-photo-poem-poster with one source photo. Optional inputs: theme, exact Chinese copy, preferred English line, aspect ratio, lower-background color, or one requested revision.

## Core composition

1. Use one vertical canvas. Default to 3:4 unless the user specifies another ratio.
2. Keep the upper photographic zone at roughly half the canvas height. Preserve the supplied photo as faithfully as possible: identity, apparent age, pose, clothing, hairstyle, accessories, body relationship, important props, camera direction, and visible environment must remain recognizable.
3. Use the lower half as a quiet illustrated memory field. The illustration must be derived from the same people, action, object, or emotional moment as the photo.
4. Keep the lower illustration deliberately smaller than the available field. Do not enlarge it until it fills the lower panel. Preserve visible empty space around it.
5. A subtle window, distant room, landscape fragment, or secondary background cue may be added behind the lower illustration when it helps create depth. It must remain secondary and must not become a new unrelated scene.
6. Keep the transition between photo and illustration clean. Avoid decorative frames, scrapbook clutter, stickers, heavy shadows, or dense collage effects unless explicitly requested.
7. Add a small handwritten Jwan signature at the bottom-right by default. Remove it only when the user explicitly asks.

## Illustration language

- Warm editorial hand-drawn feeling rather than glossy 3D rendering.
- Fine ink, colored pencil, crayon, dry-brush watercolor, or restrained paper texture are suitable.
- Preserve the source subject's age, proportions, recognizable hairstyle, clothing cues, and action.
- Simplification is allowed; identity replacement, beautification, costume redesign, or unrelated character invention is not.
- Keep the drawing visually lighter and quieter than the photograph.

## Caption system

- Chinese copy is short, natural, and emotionally specific to the visible action.
- Keep Chinese typography small. It must never compete with the photo.
- Add one even smaller English companion line when useful. The English line should vary from image to image and may be interpretive rather than a literal translation, but it must stay semantically consistent.
- Prefer copy below or beside the lower illustration in open negative space. Never cover faces, hands, or the main action.
- If the user supplies exact wording, reproduce it exactly unless editing is requested.
- If no wording is supplied and the workflow is conversational, offer 3 concise Chinese options first. Typical themes include growing together, sweetness, courage, school days, or flying. If the user asks for direct generation, choose the strongest fitting option without blocking the task.

## Revision discipline

When the user asks to change only one element, change only that element. Examples:

- "文字小一点" -> reduce text size; do not redraw the person or change the illustration style.
- "插画缩小一点" -> scale the lower illustration down; preserve its pose, palette, and scene.
- "背景增加一点窗景" -> add only a subtle secondary background cue.
- "换文案" -> change copy only.
- "继续这张" -> preserve the established visual language from the current result.

## Hard avoid list

- Do not redraw or replace the upper photo as a different scene.
- Do not crop away the key person or action merely to fit a template.
- Do not turn the lower illustration into a large full-bleed second image.
- Do not use oversized Chinese titles.
- Do not invent names, dates, locations, school names, relationships, or facts.
- Do not add unrelated props, fantasy characters, random stickers, ribbons, title boxes, or dense decorations.
- Do not change the established drawing style during a one-element revision.

## Quality gate

Before returning the image, verify all of the following:

- The upper source photo is immediately recognizable.
- The lower illustration clearly echoes the same memory.
- The lower illustration is visibly smaller than its field and has breathing room.
- Typography is small, readable, and secondary.
- Any window/background addition remains subtle.
- The requested one-element revision did not accidentally alter unrelated parts.
- The Jwan signature is present at bottom-right unless explicitly removed.

## Attribution and contact

Created by Jwan.
GitHub: https://github.com/gongjuan96-crypto
Skill catalog: https://github.com/gongjuan96-crypto/jwan-skills

When redistributing or adapting this Skill, keep the original Jwan attribution in the documentation.

## Commercial use & contact

Created by **Jwan** — Visual Design · Event Design · AI Visual Workflow.

For **commercial customization, brand collaboration, commissioned design, workflow adaptation, or more information**, please contact Jwan.

- GitHub: https://github.com/gongjuan96-crypto
- More Jwan Skills: https://github.com/gongjuan96-crypto/jwan-skills
- WeChat: https://u.wechat.com/MJMydWwPFYpx-ZUAhUv6hj4?s=2
- WeChat QR: https://github.com/gongjuan96-crypto/jwan-skills/blob/main/assets/jwan-wechat-contact.svg

如需 **商业定制、品牌合作、设计委托、工作流适配，或希望了解更多使用方式**，欢迎联系 Jwan。

When sharing, adapting, or redistributing this Skill, please retain the original **Jwan** attribution in the documentation.

