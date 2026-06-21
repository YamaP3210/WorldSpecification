# HTML Reference Policy

## Purpose

This file defines how HTML and Markdown materials should be treated in this project.

The HTML files are the primary specification documents for the world.

Markdown files exist to support operation, orientation, image generation, and session restart.

Markdown files do not override HTML world specification unless the user explicitly revises the specification and the HTML has not yet been updated.

## Priority

When information conflicts, use this order:

1. User's latest explicit instruction
2. Relevant HTML file as primary world specification
3. Operational Markdown files
4. Older archived notes under `OLD/`

If a conflict is found between HTML and a support Markdown file, HTML should be treated as canonical unless the user has just provided a newer correction that has not yet been reflected.

## Role Of HTML

The HTML files are primary documents.

They define the world itself, not just presentation pages.

Current domain split:

- `HTML/history/human-history.html`
  - Primary source for long-term history, state formation, political chronology, and historical interpretation
- `HTML/magic/index.html`
  - Primary source for magic systems, magical theory, magical materials, magical ethics, and related hazards
- `HTML/geography/index.html`
  - Primary source for regional geography, terrain logic, settlement structure, and regional strategic shape
- `HTML/species/index.html`
  - Primary source for species-level traits and species-specific cultural tendencies where recorded
- `HTML/combat/index.html`
  - Primary source for military culture, equipment roles, and combat interpretation where recorded

Other HTML files should be treated the same way within their own domain.

## Role Of Markdown

Markdown files are secondary operational materials.

They exist for one of the following purposes:

- project identity and design philosophy
- workflow rules
- image generation guidance
- restart and handover guidance
- targeted topic notes that are not yet formalized

They should not silently become replacement world canon.

## HTML Update Rule

HTML should be updated only when the user explicitly instructs it.

Do not update HTML automatically just because a new setting was discussed.

Until the user requests HTML updates, new information may remain in session memory.

If the amount of unreflected important information grows large enough that loss risk becomes meaningful, that risk must be stated clearly to the user before continuing.

## Handling Unreflected Information

Unreflected information should not be silently treated as safely preserved forever.

When risk rises, the correct action is:

1. clearly state that important information is still only in session memory
2. ask whether the user wants HTML updated now
3. if the user does not want HTML updated yet, continue with that explicit understanding

Do not create silent "next time" buckets and do not assume indefinite memory persistence.

## Archive Handling

Files under `OLD/` are reference material only.

They may help reconstruct past reasoning, but they are not current canonical sources unless the user explicitly revives them.

## Practical Reading Order

For most tasks, use this order:

1. relevant user instruction in the current session
2. relevant HTML page
3. supporting Markdown guidance

Examples:

- history question -> `HTML/history/human-history.html`
- magic mechanics -> `HTML/magic/index.html`
- regional structure or map interpretation -> `HTML/geography/index.html`
- image generation request -> relevant HTML first, then `IMAGE_GENERATION_WEIGHTS.md` and `IMAGE_GENERATION_CONTEXT.md`

