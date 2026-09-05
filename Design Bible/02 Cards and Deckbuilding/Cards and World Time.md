---
title: Cards and World Time
tags: [design, cards, economy]
status: adopted-baseline
---

# Cards and World Time

## Continuous phases

The world runs continuously through early day, late day, early night, and late night. All factions share the clock. Initial tuning: a 24-minute day, four 6-minute phases. FPS movement and physics do not accelerate with the solar clock. Phase duration is tunable.

A hand window governs when a card may be committed. Operation duration governs its physical work. Situational deadlines govern whether the world still supports a use. An operation committed before sunset can finish at night.

## Hand and zone rules

Initial tuning: 12 cards in the active deck, hand size 5, and 3 command points per phase. Ordinary cards cost 1 point; powerful operations state a higher cost. Material costs remain additional requirements.

At a boundary, discard the old hand, expire unused command points, reset points, and draw to hand size. Shuffle discard into draw only when a draw is required and the draw pile is empty. Draw fewer if insufficient eligible cards remain. A card commits only if accepted before the boundary; an open targeting preview does not reserve the old hand.

| Zone | Rule |
| --- | --- |
| Collection | Owned cards outside the active deck; includes newly earned rewards |
| Draw | Eligible for future hands |
| Hand | Available for normal play during this phase |
| Discard | Eligible for reshuffling and discard-targeting effects |
| Exhaust | Excluded from ordinary recycling until an explicit recovery effect or scenario end |
| Removed | Only for explicitly permanent consumption; never a synonym for exhaust |

Played cards normally discard at commitment. An Exhaust keyword overrides that destination. Retain is a supported explicit exception but is absent from the starter deck. Rarity alone does not determine destination. Exhausted cards return to their owner's collection at scenario end; campaign carryover is outside this baseline.

## Reliable common access and deck editing

Every faction's command library contains Civil Works, Resource Works, Produce Support, Survey Sector, Expand Perimeter, Upgrade Base, Upgrade Facility, and Research Project. Recovery-effect cards and Emergency Allocation are excluded; they must be acquired and added to the active deck. Once per phase, a player may discard one hand card to requisition one common library card into that slot. This costs 1 command point. The temporary card cannot be retained, exchanged again, or targeted by retrieval effects; it returns to the library after use or at phase end. Playing it costs its normal command points and materials. Thus missing a draw costs tempo without permanently blocking a viable base.

Common cards can also occupy the ordinary active deck and be drawn at full efficiency. The starting hand is Civil Works, Resource Works, Produce Support, Survey Sector, and Expand Perimeter. The remaining seven starter cards are two Civil Works, Resource Works, Produce Scouts, Produce Assault Hovercraft, Field Repair, and Research Project.

A card's declared choices are visible before play. Civil Works selects one common non-extraction building, including a Core or Relay establishment. Resource Works selects one of the three extraction buildings. These broad common cards reduce the number of near-identical building cards while rare structures require their own specific authorization.

At a phase boundary, a player may apply one queued deck swap: exchange a non-exhausted active card for a card in collection before drawing. The player selects it in advance without pausing. A drawn or discarded card moves to collection; the incoming card joins draw, which is shuffled. A card with an outstanding operation cannot leave the active deck. Exhaustion cannot be cleared through deck swaps. New rewards enter collection and never unexpectedly interrupt a current hand.

## What requires cards

New construction, expansion, upgrades, production batches, surveys, research, refits, and special operations require cards. Movement, attacks, formations, patrols, escort, hauling, pickup, ordinary repair, power priorities, and resuming an authorized interrupted job do not.

Field Repair accelerates or enables repair through a deployed support unit with physical supplies; ordinary Service Bay repair remains free to order. Salvage of loose resources is free to order. Transforming an exceptional component into a capability requires the appropriate project card.

## Starter and interaction vocabulary

| Card | Operation or effect |
| --- | --- |
| Civil Works | Build one selected common infrastructure building; Core/Relay variants establish a seed |
| Resource Works | Build an Extractor, Timber Yard, or Water Station at a valid source |
| Produce Support | Produce one Worker chassis, common attachment, or declared Worker package at a supporting Core/Yard/Fabricator; see [[Basic Unit Roster]] |
| Produce Scouts / Produce Assault Hovercraft | Commit the stated batch at a capable facility |
| Survey Sector | Assign a capable scout to scan a location and identify resources or component properties |
| Expand Perimeter | Claim additional contiguous cells within the current level allowance |
| Upgrade Base | Commit a Core/Relay level upgrade through a constructor |
| Upgrade Facility | Apply a selected supported common upgrade or component installation |
| Research Project | Commit a known research or exceptional processing recipe at a capable facility |
| Field Repair | Dispatch a support unit and supplies for expedited field repairs |
| Recover Orders | Exhaust this card to move one other non-temporary card from discard into hand; hand limit still applies |
| Emergency Allocation | Exhaust this card to gain 1 command point; zero play cost, no creation of materials |
| Airstrike | Commit an available aircraft and known target; no conjured aircraft |

Recover Orders, Emergency Allocation, and Airstrike are expansion content, not starter-deck cards. An exhausted-card recovery mission identifies one eligible owned exhausted card when offered; successful physical completion moves that card to discard once. No eligible card means no such mission. Recovery of a card never repeats a previously completed operation.

## Commitment and interruption

Validate the card, phase, points, target, prerequisite unlocks, capacity reservation, and accessible material stock together. A valid card pays command points and reserves material; work begins when delivered inputs and operational services are ready. Placement may allow missing functional modules with explicit warnings. An invalid commitment spends nothing.

The operation records its own identity, inputs, work stages, and destination. Cancellation does not return the played card or spent command points. Unused materials are released at their current location; consumed materials follow salvage rules. Resuming an interrupted operation retains its authorization; changing to a different recipe requires a new commitment.

The interface shows phase time, known prerequisites, legal placement, delivery status, card destination, and the point of irreversible processing. See [[World Assets and Outcome Resolution]] and [[Core Resources]].


## Common building catalogue

[[Common Building Cards]] defines the five building authorizations and six additional common specialist cards. The specialist cards enter the common collection pool; they are not added to the universal requisition library or starter deck. The catalogue supplies precise targeting, timing, and recovery rules for those cards.


