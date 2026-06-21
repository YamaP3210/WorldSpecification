# Session Restart Guide

## Purpose

This file defines the minimum reading order for resuming work in a new session.

It is not a lore summary.

It is an operational guide for quickly rebuilding the correct context from canonical sources.

## Core Principle

HTML is the primary specification source.

Markdown is support material.

Read HTML for the world itself.

Read Markdown for workflow, priorities, and supporting rules.

## Minimum Restart Order

Read these files in this order:

1. `PROJECT_CONCEPT.md`
   - project identity
   - what this project is and is not

2. `WORLD_FOUNDATION.md`
   - high-level worldbuilding philosophy
   - realism and causality priorities

3. `HTML_REFERENCE_POLICY.md`
   - canonical priority rules
   - HTML vs Markdown handling

4. relevant HTML pages for the current task
   - history -> `HTML/history/human-history.html`
   - magic -> `HTML/magic/index.html`
   - geography -> `HTML/geography/index.html`
   - species -> `HTML/species/index.html`
   - combat -> `HTML/combat/index.html`

5. only after that, read support Markdown if the task needs it
   - `LANGUAGE_FOUNDATION.md`
   - `IMAGE_GENERATION_WEIGHTS.md`
   - `IMAGE_GENERATION_CONTEXT.md`
   - `WEAPON_REFERENCE_NOTES.md`

## Typical Restart Paths

### History / politics / chronology

Read:

1. `PROJECT_CONCEPT.md`
2. `WORLD_FOUNDATION.md`
3. `HTML_REFERENCE_POLICY.md`
4. `HTML/history/human-history.html`
5. `HTML/geography/index.html` if geography affects the question

### Magic / magical materials / magical ethics

Read:

1. `PROJECT_CONCEPT.md`
2. `WORLD_FOUNDATION.md`
3. `HTML_REFERENCE_POLICY.md`
4. `HTML/magic/index.html`
5. `HTML/history/human-history.html` if historical context matters
6. `HTML/geography/index.html` if ruins or regions matter

### Image generation

Read:

1. `PROJECT_CONCEPT.md`
2. `WORLD_FOUNDATION.md`
3. `HTML_REFERENCE_POLICY.md`
4. relevant HTML pages for the subject
5. `IMAGE_GENERATION_WEIGHTS.md`
6. `IMAGE_GENERATION_CONTEXT.md`
7. `WEAPON_REFERENCE_NOTES.md` only if equipment design matters

## Important Operating Rules

- Do not assume support Markdown overrides HTML canon.
- Do not update HTML unless the user explicitly asks.
- If large amounts of important new lore remain only in session memory, warn the user before risk becomes significant.
- If the user requests HTML update, reflect the in-scope important items immediately instead of leaving silent pending items.

## Current Canonical Domains

- History: `HTML/history/human-history.html`
- Magic: `HTML/magic/index.html`
- Geography: `HTML/geography/index.html`
- Species: `HTML/species/index.html`
- Combat and equipment roles: `HTML/combat/index.html`

