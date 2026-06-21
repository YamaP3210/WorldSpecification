# Image Generation Context

## Document Role

This document stores background-understanding conditions for image generation.

It is not the primary list of direct visual requirements. Instead, it explains background logic that can help resolve ambiguous generation choices when `IMAGE_GENERATION_WEIGHTS.md` alone does not give a sufficiently clear answer.

Use order:

1. Official world specification in HTML and core MD files
2. `IMAGE_GENERATION_WEIGHTS.md` for direct visible conditions
3. `IMAGE_GENERATION_CONTEXT.md` for secondary interpretive context

This document is useful when deciding what kind of landscape, settlement density, or political atmosphere should emerge from the world specification, even if those conditions are not always stated directly in the image prompt.

## Context Policy

- These notes are not direct prompt defaults.
- These notes should not override clear visual conditions unless the visual conditions are incomplete or contradictory.
- These notes exist to stabilize interpretation when image generation would otherwise drift into generic fantasy assumptions.

---

## Current Background Context

### Image Use and Interpretation

- Generated images are reference material for checking what the world specification produces visually.
- Images do not automatically become specification simply by existing.
- If an image and the written specification diverge, the written specification remains primary unless intentionally revised.
- For weapons, equipment, clothing, and decorative objects, a civilization level roughly comparable to the 12th to 13th centuries should be treated as the default point of departure.
- Any visible advancement beyond that baseline should come from explicit world-specification reasons such as magic, old infrastructure, regional specialization, or inherited mage-state knowledge.

### Political Space, Settlement, and Territory

- Territory should not be interpreted as modern uniform area-control by default.
- Political control tends to radiate from towns, ports, crossing points, roads, depots, and similar nodes.
- This is not pure point-and-line control; there is also a loose sense that the surrounding area belongs to a given power.
- Uninhabited land that is neither farmland nor strategic land is often not deeply managed in practice even if nominally inside someone's sphere.
- For major cities, inhabited settlement corridors may extend roughly 100 km to 200 km outward under favorable conditions.
- Beyond those corridors, sparse habitation, open land, tribal zones, hunting grounds, and ambiguous buffer areas become more common.
- Recent maritime logistics have made some intermediate settlements and small exchange points more viable.

### Visual Consequences of the Settlement Model

- Do not assume that every piece of land inside a nominal territory is equally developed.
- Borderlands, backcountry, and remote districts should often retain open land, uneven habitation, and visible gaps between organized settlements.
- A landscape can still belong to a realm without looking densely administered or evenly cultivated.

### Mage-State Agricultural and Infrastructure Context

- The mage-state's superiority was not only military or monumental; it also depended on advanced sanitation, water control, lighting, planning, and agricultural management.
- Magical research affected agriculture as well as people. Through experience-driven experimentation, the mage-state discovered crop traits that improved tolerance for cold and poor conditions.
- This helped make harsher regions, including the northeast, more productive and strategically useful.
- Visuals of the mage-state do not always need to show this directly, but when agricultural outskirts or managed land appear, they may plausibly suggest unusually disciplined and effective cultivation.

### Social Zoning in the Mage-State Capital

- A capital image may represent an elf-dominant central district rather than the full social mix of the entire capital.
- Laboring plainfolk quarters, warehouses, transport districts, and mixed utility districts may exist outside the pictured core.
- Therefore, an image of the capital may look cleaner, more ordered, and more exclusively elven than the capital as a whole actually was.

### Combat and Support Structure

- Casters are usually not front-line spectacle weapons by default.
- Rear-line personnel often exist to stabilize the fight, recover wounded, and protect specialists.
- Everyday combat culture should not be visualized as everyone behaving like duelists or high-fantasy heroes.
- This does not always need to appear directly in a single image, but it should affect how group scenes, camp scenes, escorts, and battle readiness are interpreted.

---

## Notes For Future Use

- If a background note starts directly controlling visible composition or materials in most images, consider moving it into `IMAGE_GENERATION_WEIGHTS.md`.
- If a supposedly visual rule only explains why something exists but rarely changes what the image should visibly contain, consider moving it into this file.
- If a future image repeatedly drifts because a contextual assumption is too hidden, promote the relevant item into the direct visual layer.
