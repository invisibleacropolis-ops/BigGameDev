---
title: Design Baseline
tags: [design, baseline]
status: adopted-baseline
---

# Design Baseline

The creator authorized developing and adopting the recent proposals as part of the game. This baseline resolves their alternatives into current design rules. It is a design specification, not a claim that the game has been implemented or balanced. Numeric defaults are initial tuning values that can change through actual play.

## Integrated decisions

| System | Current rule | Detail |
| --- | --- | --- |
| World time | Continuous simulation; four card phases per day | [[Cards and World Time]] |
| Deckbuilding | Draw, hand, discard, exhaust, collection; explicit zone effects | [[Cards and World Time]] |
| Economy | Physical Metal, Wood, Water; Wood-powered industry | [[Core Resources]] |
| Bases | Seeded world-space grids; contiguous, card-authorized expansion | [[Base Grids and Connections]] |
| Buildings | Universal common roster with physical logistics and separate work capacity | [[Common Base Buildings]] |
| Layout | Footprints, clearance, matching ports, mandatory patterns | [[Base Grids and Connections]] |
| Rare industry | Foundry core with attached coolant and control modules | [[Rare Building - Coupler Foundry]] |
| World assets | Custody precedes chosen processing; results apply once at completion | [[World Assets and Outcome Resolution]] |
| Rarity | Mechanical access tiers plus independent scoped uniqueness | [[Procedural Content and Rarity]] |
| Emergence | Eligible modules, competing uses, bounded selection, persistent consequences | [[Procedural Content and Rarity]] |
| Opponents | Same legal actions and visibility constraints; layered strategic and unit control | [[Command and Opponent AI]] |

## Design invariants

1. Menus and phase transitions never pause or accelerate movement.
2. A card authorizes an operation; changing its zone does not erase the operation or its output.
3. Every material quantity has a location, and every exceptional component has an identity.
4. Exclusive inputs cannot complete incompatible uses twice.
5. A building can be placed legally yet lack a functional attachment; the interface explains why.
6. Ordinary recovery cannot depend on obtaining a rare reward.
7. Arrangement, resource, and visibility checks apply equally to AI and humans.
8. Random generation selects possible situations; it does not secretly replace a known completion result.

## Selected defaults versus future work

Current rules below select how claiming, expansion, common-card access, processing, cancellation, and uniqueness work. Starting counts and durations are tuning defaults. [[Initial Economy Tuning]] supplies provisional material prices, work rates, and throughput. Those values, unit handling curves, and combat damage require actual play before any balance claim.

Setting names, campaign persistence, multiplayer networking, civilian society, full aircraft combat, pipelines, forest regrowth, and procedural terrain grading are later design work. Their absence does not block this baseline. No concept art or implementation is produced by this revision.

## Review of the integrated design

The documentation review checks the bootstrap dependency order, the Level 1 layout, Foundry port positions, card/operation separation, exceptional-input exclusivity, and recovery without rare cards. This is a paper consistency review. The next evidence must come from the actual scenario described in [[First Playable Scenario]].


Initial quantitative defaults: [[Initial Economy Tuning]].


## Basic chassis and physical equipment

The basic roster is Assault, Scout, and Worker. Constructor and hauler are Worker configurations. Modules are recoverable physical objects; capability requires compatible attachment, alignment, lock, and adequate connector condition. See [[Basic Unit Roster]] and [[Worker Attachments and Couplings]]. Standard military fits and brainstormed alternatives are in [[Common Vehicle Weapons]]; alternative weapon balance is not yet adopted.

