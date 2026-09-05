---
title: Procedural Content and Rarity
tags: [design, procedural, deckbuilding, rarity]
status: adopted-baseline
---

# Procedural Content and Rarity

## Working backward from experience

Design a situation worth playing, identify its actors, needs, objects, constraints, decisions, and consequences, then implement reusable rules capable of producing it. The creator-confirmed reference is a contested component whose recovery can lead to a weapon capability or a building upgrade. The exact chain is not scripted as the only outcome.

A situation consists of an eligible place, interested actors, a need or opportunity, an actionable asset, constraints, and persistent consequences. Modules declare prerequisites, information visibility, compatible inputs, success, interruption, and failure effects.

## Mechanical rarity and uniqueness

Access tiers are Common, Rare, and Legendary. Unique is an independent mechanical property that can combine with any access tier. This resolves the earlier ambiguous four-label arrangement while preserving a unique legendary asset.

| Property | Game rule |
| --- | --- |
| Common | Available through universal common libraries or ordinary acquisition; no exceptional discovery required |
| Rare | Restricted to declared rare sources or operations; excluded from the common requisition library |
| Legendary | Requires a declared exceptional acquisition chain and a legendary opportunity budget; not awarded by an unrestricted common roll |
| Unique | Has a capability/identity key, explicit scope, and maximum count enforced at reservation and completion |

Uniqueness defaults to one realization per scenario for named artifacts, with scope recorded rather than inferred. Content may expressly define per-faction or per-base limits. Building level, power, rarity, and uniqueness are independent. The Foundry is Rare and not Unique; Gravitic Lance is Legendary and scenario-Unique.

A unique realization can change owners only through a defined transfer rule; its provenance remains the same. Removing or exhausting a card does not free its uniqueness slot. A capability's separate active-unit cap prevents card recovery from duplicating a surviving equipped unit. If a recipe requires a slot already held, it cannot reserve or consume the input.

## Scenario budgets and selection

Track cumulative introduced opportunities and currently active exceptional assets separately. Hard introduction caps prevent repeatedly destroying an asset from farming new rare spawns. A single object offering mutually exclusive rare or legendary outcomes reserves one opportunity identity with the highest supported acquisition tier; it does not count as several guaranteed rewards.

At each daily phase the director may introduce an eligible incident, issue a developing warning, or introduce nothing. Initial tuning: maximum three unresolved urgent incidents and at most one new urgent incident per phase. Persistent nonurgent discoveries have their own scenario cap. Story density is bounded by playable attention, not a quota that must always be filled.

`weight = eligibility × source frequency × contextual fit × novelty × remaining budget`

Eligibility enforces reachable sites, actual world entities, necessary mechanics, and supported outcomes. Hard caps are checked before sampling. Normalize positive weights; if no valid candidates exist, defer. Novelty reduces repeated combinations without overriding eligibility. Each scenario defines its own tier counts, source pools, cooldowns, and map seed; there is no universal legendary drop percentage yet.

Reserve any guaranteed finite reward when announcing a contract. Do not promise two factions independently awardable copies of a unique result. A contested contract may promise one result to its first valid completer. Explain that condition before participation.

## Sources and consequences

Acquisition channels include discovered caches, physical salvage, faction contracts, completed research, and scenario milestones. Each channel names eligible content and rarity rules. Ordinary collection rewards enter collection; recovered world objects remain cargo until an applicable use is completed.

Use carry, escort, scan, hold, repair, extract, install, and transform as shared verbs. A mine collapse requires a real mine. A failing generator has real output consequences. A delivery uses a compatible object and a valid destination. Alternate uses can remain viable after a player changes custody or plans.

Night reduces optical visibility while active sensors retain their own explicit sensing rules; day/night does not change travel speed. Numeric detection ranges remain tuning data. Terrain and lighting therefore influence routes without forcing every mission to become a nighttime event.

## Data contract

Each content definition includes identity, tags, access tier, uniqueness key/scope/cap if any, source eligibility, prerequisites, compatible inputs, effects, world representation, card-zone behavior where applicable, failure behavior, and visibility rules. Definitions refer to shared predicates; they cannot bypass material or slot accounting.

Each generated opportunity records its source conditions, selected modules, involved object identities, offered outcomes, deadline, reward reservation, and applied consequences. This makes outcomes explainable and lets the AI reason about the same conditions the player encounters.

Triggered effects carry an event identity and resolve once for that event. An effect cannot recursively trigger itself on its own unchanged transition. Explicit repeatable interactions require a cost and legal new transition; unlimited discard/exhaust loops are not accidental default behavior.

## Content growth

Expand across handling, terrain use, logistics, resource dependencies, card-zone effects, timing, counterplay, and consequences. Judge variety by different decisions observed in actual generated play, not combination counts alone. Track repeated event chains, unusable rewards, dominant strategies, and unmet dependencies when the implementation exists.

See [[World Assets and Outcome Resolution]], [[Cards and World Time]], [[World Events and Objectives]], and [[Rare Building - Coupler Foundry]].
