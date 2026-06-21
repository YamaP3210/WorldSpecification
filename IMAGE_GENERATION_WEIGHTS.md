# Image Generation Weights

## Document Role

This document stores weighted guidance for direct visual conditions in image generation.

It is not a world-specification source of truth like the HTML pages. It is a working control sheet for which directly visible traits should be prioritized in generated images.

Use this file as the primary image-generation layer.

When visual conditions alone are not enough to decide what should be shown, consult `IMAGE_GENERATION_CONTEXT.md` as the secondary background-understanding layer.

Weights are treated as absolute values within a categorized system, but may be rebalanced later for optimization as the project evolves.

## Weight Policy

- `90-100`: top-level principle or very strong condition
- `70-89`: strong tendency
- `40-69`: moderate tendency
- `10-39`: weak tendency or useful reference
- `0-9`: tentative memo

Important:

- these values are not eternal
- values may be reassigned later
- lower values do not mean "wrong"
- negative values are allowed in future if needed, but are not currently used

## Category Policy

Each entry should be understood according to its category.

- `Principle`: a high-level generation rule or interpretation rule
- `Tendency`: a condition-dependent tendency that often follows from the world specification
- `Prompt condition`: a condition specific to one kind of image or one generation target

Tendencies are not universal laws.

If a future prompt or world-specification context clearly changes the situation, a tendency can be overridden without violating the system.

---

## Current Weighted Entries

### World-Spec Visual Method

- `100` `Principle` World-specification compliance comes first. Images should be derived from the established world specification rather than from generic fantasy habits.
- `100` `Principle` For weapons, equipment, clothing, and adornment, start from a real-civilization baseline roughly comparable to the 12th to 13th centuries, then modify from there only where the world specification gives reason.
- `96` `Principle` Avoid drifting toward existing-franchise imitation, especially Elder Scrolls or The Witcher style gravity.
- `92` `Principle` Generated images are reference material for checking what the specification produces visually; they are not automatically specification themselves.
- `74` `Tendency` Building visual component samples first, then using them to inform larger scenes, is a preferred workflow.

### Plainfolk Travelers and Mercenary-Road Work

- `100` `Principle` Weapon logic must remain coherent. Sheathed state, drawn state, scabbard presence, carrying position, and shield position must make physical sense.
- `96` `Principle` Weapon choice should be derived from job type and fighting style rather than from generic fantasy class expectations.
- `100` `Tendency` For road-traveling plainfolk mercenary-type work, avoid unrealistically oversized weapons whose scale is driven mainly by game-like spectacle rather than believable function.
- `88` `Tendency` Mercenary-type fighters who make a living through escort, exploration, and similar work often favor relatively compact main weapons because they value handling and practical usability.
- `80` `Tendency` Common examples in that context include smaller one-handed swords, short swords, maces, hand axes, and short spears.
- `62` `Tendency` Many exceptions can still exist depending on work type, fighting style, region, and personal skill.
- `90` `Tendency` Equipment for escort, exploration, and similar mercenary road work should read as practical working gear rather than parade gear or heroic fantasy costuming.
- `86` `Tendency` In escort, exploration, and similar mercenary road work, small shields are generally more natural than large ones.
- `82` `Tendency` In escort, exploration, and similar mercenary road work, a buckler or similarly compact shield is a natural default.
- `78` `Tendency` The buckler is naturally carried at the left rear waist area in travel state.
- `72` `Tendency` The buckler is naturally removed and equipped with the left hand.
- `72` `Tendency` Belt pouches and small utility items naturally bias toward the right waist when shield and sword logistics are considered together.
- `66` `Tendency` Mercenary road workers and soldiers should not be visualized as sharing identical equipment logic.
- `58` `Tendency` For inn-supported travel, luggage should be somewhat lighter than for fully camp-dependent travel.
- `50` `Tendency` For camp-dependent travel, heavier travel gear remains plausible.

### Clothing, Practicality, and Appeal

- `96` `Principle` Female characters must not be pushed into implausibly light, exposed, or decorative gear merely because they are women.
- `92` `Principle` Clothing should remain practical, protective, and non-sexualized unless there is a very specific in-world reason otherwise.
- `90` `Tendency` The main peninsula is temperate, roughly comparable to Japan in latitude, so ordinary travel clothing should not default to cold-climate bulk.
- `84` `Tendency` For ordinary short-to-medium road travel in the main peninsula, somewhat lighter temperate-climate clothing is natural.
- `78` `Prompt condition` A useful baseline for many current human travel images is realism 7 to visual appeal 3.
- `64` `Tendency` The practical, grounded equipment sensibility associated with Tactics Ogre-type character design is a useful reference.
- `52` `Tendency` A balance between realism and mild stylization can be desirable, as long as function remains primary.

### Combat Role Interpretation

- `88` `Principle` Casters are not default rapid-fire artillery. Visuals should not assume fantasy-machine-gun spellcasting as the normal mode.
- `80` `Tendency` Rear-line personnel should often read as people who protect casters, recover wounded, and manage the back of the fight rather than simply "ranged attackers."
- `64` `Tendency` Bow users in mercenary contexts are more naturally scouts, skirmishers, or support specialists than standalone front-line fighters.
- `50` `Tendency` Longbows are more naturally military than everyday mercenary equipment.
- `48` `Tendency` Longswords exist and may be common in some contexts, but they are less natural as the everyday default of escort-and-exploration road work.

### Mage-State and Elf Urban Visuals

- `100` `Principle` Mage-state urban imagery should not become visually near-modern.
- `100` `Principle` The superiority of mage-state cities should be shown through infrastructure, sanitation, planning, water control, lighting, and disciplined civic order rather than through impossible megastructures.
- `100` `Principle` Dense forests of towers or strongly vertical skylines are not a natural default for the mage-state capital.
- `96` `Tendency` Stone is the primary urban building material in major elf urban cores.
- `92` `Tendency` Elf urban aesthetics should show plant life, gardens, vines, planted courtyards, water, and controlled greenery as ornament and continuity with nature.
- `90` `Tendency` Elves should not be treated as a civilization that casually normalizes large-scale logging for urban expansion.
- `86` `Tendency` Heavy timber urban character should be de-emphasized in mage-state core districts.
- `84` `Tendency` The atmosphere should suggest a refined ethnic state or civilizational center rather than a flatly "imperial" human-style monumentality.
- `74` `Tendency` A feeling somewhat reminiscent of highly organized ancient Mediterranean urbanism can be useful, as long as it remains subordinate to the project's own specification.
- `60` `Tendency` The capital image may naturally represent an elf-dominant central district rather than a socially mixed whole-city cross section.
- `44` `Tendency` Laboring plainfolk districts may exist outside the pictured central district and do not need to be visible in every capital image.

## Notes For Future Rebalancing

- If an entry starts behaving like a false universal law, it should either be reduced in weight or rewritten as a conditional tendency.
- If a prompt-specific condition keeps being reused, it may deserve promotion into a broader tendency.
- If an image repeatedly fails because a rule is too weak, its weight may need to be raised.
- If an image repeatedly becomes overly constrained, some tendencies may need to be lowered or split into narrower conditions.
