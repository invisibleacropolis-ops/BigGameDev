---
title: Design Conversations
tags: [design, decisions]
status: active
---

# Design Conversations

## 2026-09-05 — Initial capture

**Established by the creator:** Embodied RTS control; possession of friendly units; strategic cards including construction; opponents using the same card system; contextual world events and contested missions; hover vehicles plus jetpack/skiing characters; shared 256-color model/terrain palette with low-poly geometry and modern effects; a growing Obsidian design bible.

**Proposed in this session, not yet accepted:** Cards as commitments that become physical operations; continuous real-time world with periodic hand refresh; a small command budget; essential orders remaining free; a cargo recovery scenario as the first integrated experiment.

## 2026-09-05 — Continuous time confirmed

**Accepted:** World simulation remains continuous at normal FPS speed, including while choosing cards. Day/night timing advances continuously. Players may miss a daily phase's hand-play window. Multiplayer is a possible future direction.

**Working idea from the creator:** Approximately four hands per full day, two in daylight and two at night. Exact count and timing are not locked.

**Implications proposed for discussion:** Shared phase boundaries for factions; committed operations persist across hand refreshes; distinguish hand availability from operation duration and situational deadlines.

**Updated note:** [[Cards and World Time]]. The initial capture above is historical; continuous time is now accepted.

## Next conversation

The recent proposals have been developed into [[Design Baseline]]. Review the adopted common-card access, cell scale/allowances, and the first complete scenario; then establish material recipes and handling through actual play. Earlier open questions below are historical unless repeated as deferred work in the baseline.

## Base grid and seed definitions

**Accepted:** Bases occupy the shared real-world game map. A claim creates a central seed point. A grid overlays the terrain for placement, base level determines available spaces, and each building consumes a defined footprint. Certain structures can require specific attachments or spatial patterns to function.

**Unresolved:** Claim mechanism, cell scale, base orientation, cell counts per level, expansion shape versus selectable cells, and exact building patterns. [[Base Grids and Connections]] records the definitions and clearly labeled proposals. The rare Foundry's attached support modules are a new example, not a confirmed design.

## 2026-09-05 — Core resources and first building roster

**Accepted resource identities:** Metal, Wood, and Water, collectible in the physical world.

**Requested and drafted:** Research-informed common building roster with functions, dependencies, and input needs; a viable starting-loop proposal; one rare building. Sources and design adaptations are in [[Strategy Building Research]].

**Proposals awaiting discussion:** Wood as biomass fuel, Water as industrial process input, physical local inventories and hauling, power as service capacity, and the building roster in [[Common Base Buildings]]. [[Rare Building - Coupler Foundry]] extends the coupler example with a specialized processing branch. Costs and timing remain unbalanced; no playable economy exists yet.

## 2026-09-05 — World assets and realized outcomes

**Accepted:** Tiers must be mechanical, trackable properties. The contested recovery example successfully expresses the creator's intended experience. This validates the design direction, not an implementation.

**Creator's clarification:** While an asset is live or recoverable in the world, it represents an option rather than an already owned reward card. A dark matter coupler can produce a legendary card for a player or serve as a base building's upgrade component. The recovering player's use determines the result at final objective completion. Emergence must remain grounded in what is actually happening to the player.

**New note:** [[World Assets and Outcome Resolution]]. Its field definitions, processing stages, and example completion rules are proposals supporting this accepted principle. Exact uniqueness scope and tier behavior remain undecided.

## 2026-09-05 — Deckbuilding states and procedural content confirmed

**Accepted:** Unplayed cards enter discard at phase end. Discard and exhaust are distinct rules categories with interactions. The overall game aims for highly procedural, emergent situations whose interlocking concerns resemble authored content. Design should work backward from desired results into modular rules, equations, and formulae.

**Creator's content direction:** Structured procedural randomness; collectible assets; common, rare, unique, and legendary content; some rare units accessible only through rare cards; special weapons accessible through unique legendary cards. Both sufficient variety within categories and controlled amounts appearing in play matter. This supports ongoing content expansion.

**Open:** Exact rarity distribution, meaning and scope of uniqueness, post-play behavior of rare cards, and persistent versus temporary unlocks. The creator's phrase “unique legendary” may mean uniqueness and rarity overlap; do not force a single exclusive tier interpretation yet.

**New note:** [[Procedural Content and Rarity]]. All example formulas and scenarios there are proposals.

## Questions to revisit afterward

1. Are cards reusable capabilities, consumable assets, or an explicitly marked mixture?
2. How much time should a typical player spend piloting versus commanding?
3. What setting explains remote control, card acquisition, and competing factions?
4. Is progression scenario-local, campaign-persistent, or both?
5. How do bases recover when critical construction cards are unavailable?
6. What multiplayer constraints should be anticipated given that multiplayer is a possible future direction?
7. What makes the first handful of unit types distinct to pilot?

## Decision record template

- **Date:**
- **Question:**
- **Accepted decision:**
- **Reason:**
- **Alternatives considered:**
- **Notes affected:**
- **What would make us revisit it:**

## Adoption and integration of recent proposals

The creator requested that recent suggestions and proposals be fully developed into the game. The current topic notes now specify rules rather than repeating unselected alternatives. New decisions include constructor-deployed seed beacons; contiguous cell selection; all permanent structures occupying base grids; independent local power and physical hauling; explicit Foundry ports; cancellable component processing until final conversion; collection as the reward destination; mechanical access tiers and separate scoped uniqueness; and common-card requisition for recovery.

Four phases, 24 minutes per day, 5-card hands, 3 command points, 16-metre cells, level allowances, footprints, and 25% Generator efficiency are selected initial tuning defaults. They are not playtested balance claims. The common roster and Foundry branch are adopted. The first scenario now supports alternative component uses rather than requiring only a fixed delivery ending.

The original brief and research source observations remain unchanged. Original alternatives here preserve the design history. Active rules are linked from [[Design Baseline]].

Initial material recipes, work times, output rates, storage limits, and production costs are now recorded in [[Initial Economy Tuning]]. They are provisional values for real validation, not deferred blank fields. The opening inventory fits within the adopted Core storage capacity.


## Category organization and common building cards

Organized the bible into eight topic folders, each with a titled category index, while retaining Start Here as the home note and Assets for supporting media. Existing note names and wikilinks are preserved. Added [[Common Building Cards]] under Cards and Deckbuilding: five core authorizations and six specialist common cards with costs, targets, timing, and interruption rules. Numeric effects are initial tuning. The starter deck and requisition library remain as previously defined.


## Basic units and articulated Worker equipment

The creator defined two military chassis (Assault and Scout) and one small hovertruck Worker chassis. Worker functions come from physical front/rear attachments, including hauling, mining, timber, and construction. Alignment, locking time, connector strength, and equipment acquisition/recovery are gameplay systems. Standard Assault carries a top cannon and missile rack; Scout carries a machine gun and spotting equipment.

Created [[Units and Equipment Index]] with the roster, coupling design, and common weapon alternatives. Previous constructor/hauler types are now named configurations; package prices are preserved by splitting chassis and module recipes. Docking thresholds, mobile work rates, repair costs, and spotting timing are initial design values. Weapon alternatives remain brainstorm candidates. Recovery-aware elimination replaces the earlier simple constructor-presence check.

