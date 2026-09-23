---
name: jwan-event-space-render-system
description: Convert an event floor plan, venue reference, and approved key visual into coherent spatial renders while preserving object count, zoning, walls, doors, circulation, seating logic, and visual branding.
metadata:
  version: 1.0.0
  author: Jwan
  license: MIT
---

# Jwan Event Space Render System

Create event-space renders from a supplied floor plan, venue reference, and approved key visual. The planning drawing is authoritative.

## Inputs

Use any combination of:
- floor plan / hand-marked plan
- venue photo
- key visual
- exact dimensions
- object list
- camera-view request
- lighting / build-method notes

## Core principle

Do not beautify by inventing a different layout.

Preserve:
- zone locations
- walls and doors
- circulation paths
- stage position
- sign-in / photo / display positions
- control desk
- seating count and rhythm
- truss / lighting location
- requested structures and materials

If a wall separates two spaces except for two doors, keep that wall and those doors.

## Object-count lock

When user says every object in the plan must appear:
- do not omit objects
- do not add unrequested objects
- do not move functional zones merely for composition
- do not replace requested build methods with prettier alternatives

## Key-visual lock

If a key visual is supplied:
- preserve title
- preserve typography character
- preserve visual motif
- preserve layout logic
- adapt only where the physical surface requires cropping or extension

Do not rewrite or redesign the key visual.

## Build-method fidelity

Respect specified production methods:
- printed truss wall
- PVC board
- LED screen
- fabric
- lighting truss
- freestanding signage
- platform / riser
- sofa / table modules

Example: if user specifies printed truss, do not expose an open exhibition rack or replace it with a solid scenic wall.

## Seating logic

When exact sofa/table order is specified, follow it literally.

Example:
2 sofas — table — 2 sofas — table — 1 sofa — table — 2 sofas — table — 2 sofas

Do not simplify into evenly spaced generic lounge seating.

## Camera outputs

Supported views:
- bird's-eye
- oblique bird's-eye
- eye-level
- front elevation
- side view
- 360-style multi-angle composite when explicitly requested

Changing camera does not authorize changing layout.

## Lighting

Lighting should explain the planned build:
- conference truss lighting
- architectural wash
- practical venue lighting
- stage key light
- controlled ambient light

Do not add theatrical rigs if the plan does not support them.

## Revision discipline

- "签到区沿墙摆放" -> move sign-in zone only to the specified wall.
- "留影区顺墙竖着摆" -> rotate / position photo area only.
- "舞台桁架加一排会议灯" -> add that lighting only.
- "控台增加主视觉围边" -> wrap the control desk only.
- "不要门头" -> remove / avoid entrance gateway, do not replace with another gateway.

## Hard avoid list

- moving zones for a prettier render
- deleting walls
- inventing access openings
- changing exact seating count
- replacing specified materials
- changing approved key-visual copy
- adding decorative structures not present in plan
- ignoring user-marked orientation

## Quality gate

Verify:
- plan geometry and access logic remain intact
- every required object exists
- no unrequested object exists
- seating count/order matches brief
- signage zones follow marked orientation
- build materials match specification
- key visual remains recognizable
- requested camera view is correct
- presentation render may carry a small Jwan signature bottom-right

## Commercial use & contact

Created by **Jwan** — Visual Design · Event Design · AI Visual Workflow.

For **commercial customization, brand collaboration, commissioned design, workflow adaptation, or more information**, please contact Jwan.

- GitHub: https://github.com/gongjuan96-crypto
- More Jwan Skills: https://github.com/gongjuan96-crypto/jwan-skills

如需 **商业定制、品牌合作、设计委托、工作流适配，或希望了解更多使用方式**，欢迎联系 Jwan。

When sharing, adapting, or redistributing this Skill, please retain the original **Jwan** attribution in the documentation.
