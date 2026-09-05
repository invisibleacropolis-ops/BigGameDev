---
title: Common Building Cards
tags: [design, cards, common, buildings]
status: adopted-design-initial-tuning
---

# Common Building Cards

[[Cards and Deckbuilding Index|Cards and Deckbuilding]] · [[Bases and Buildings Index|Bases and Buildings]]

These are the first common cards specifically for creating, arranging, improving, and recovering base infrastructure. The first five formalize existing authorizations. The six specialist cards extend the common collection with distinct planning choices. All prices and durations are initial tuning; none has been playtested.

## Shared card rules

All cards here have access tier **Common**, no uniqueness restriction, and the explicit destination shown below. A common card need not be in the requisition library: basic capabilities are guaranteed, while specialist effects are ordinary collectible rewards. Specialist cards are not added automatically to the established starting deck.

Costs use command points (CP), plus the target's material recipe unless stated otherwise. Footprints, terrain, clearance, required attachments, delivery, power, and work capacity follow the same building rules. A card never materializes a completed building instantly. Materials are reserved on commitment and consumed through work; played cards change zone immediately while authorized jobs continue across phase boundaries.

All multi-site cards validate and reserve every site and recipe together before spending. Their child jobs then build independently. Loss or cancellation of one child never duplicates the other, refunds the card, or permits substituting a different site. Unused inputs remain physical under ordinary cancellation rules.

## Catalogue

| ID | Card | CP | After play | Access | Role |
| --- | --- | ---: | --- | --- | --- |
| CB-001 | Civil Works | 1 | Discard | Starter/library | Flexible ordinary construction |
| CB-002 | Resource Works | 1 | Discard | Starter/library | Establish collection infrastructure |
| CB-003 | Expand Perimeter | 1 | Discard | Starter/library | Enable contiguous building cells |
| CB-004 | Upgrade Base | 1 | Discard | Library/common collection | Increase the base's cell allowance |
| CB-005 | Upgrade Facility | 1 | Discard | Library/common collection | Improve a building or restore its supported module |
| CB-006 | Depot Network | 2 | Discard | Common collection | Commit two storage sites with one card |
| CB-007 | Forward Works | 2 | Discard | Common collection | Establish a Relay and Depot together |
| CB-008 | Construction Overtime | 1 | Exhaust | Common collection | Accelerate one already authorized construction job |
| CB-009 | Emergency Reconstruction | 1 | Exhaust | Common collection | Rebuild a documented destroyed common structure |
| CB-010 | Standardized Plans | 1 | Exhaust | Common collection | Retrieve one basic building authorization from discard |
| CB-011 | Perimeter Watch | 2 | Discard | Common collection | Commit a Sensor Mast and Defense Tower together |

## CB-001 — Civil Works

**Card face:** “Construct one common infrastructure building at a valid site. A Core or Relay may establish a new base.”

Choose Core, Construction Yard, Depot, Generator, Fabricator, Service Bay, Research Workshop, Sensor Mast, Defense Tower, Relay, or Air Hangar. Pay its full recipe and work time. Prerequisite unlocks still apply. Extractors use Resource Works; rare buildings use their dedicated cards.

For a new Core or Relay, preview the seed, orientation, initial cells, and entry space, then send a constructor to complete the claim. A destroyed Core can be rebuilt at its existing seed without duplicating claimed land. An ordinary building requires already enabled cells.

**Choice:** Keep a flexible card available or commit it to the most urgent need. Choosing a building ends that flexibility for this play. The opponent can intercept deliveries or attack the site.

## CB-002 — Resource Works

**Card face:** “Construct one Metal Extractor, Timber Yard, or Water Station at a compatible source within your claimed base grid.”

Choose one source and matching building; reserve its full recipe. A remote unclaimed source first needs a Relay claim. Machinery must occupy valid land, even when the resource is water or extends beyond the footprint. No card creates a deposit, forest, or lake.

Baseline collection becomes available when construction finishes; powered mode requires its normal service and upgrade rules. Discarding Resource Works does not stop harvest or require renewed authorization each phase.

**Choice:** Invest in persistent throughput instead of gathering loose salvage. The visible source and route give opponents meaningful targets.

## CB-003 — Expand Perimeter

**Card face:** “Enable up to eight connected building cells within this base's current level allowance.”

Choose a batch joined by shared edges to existing enabled cells. The selected cells must be terrain-valid, non-overlapping with other claims, and within the allowance. Constructor work takes 15 seconds per cell, with no material cost in the initial tuning.

Cells complete in an outward connected order. Completed cells persist if the remaining work is interrupted. Pending cells remain reserved to this operation until cancellation; they cannot already host another structure. A second play cannot exceed the level cap or claim the same cells twice.

**Choice:** Make room for a lane, a resource site, or a multi-module pattern. This extends usable land; it does not upgrade the level or clear impossible terrain.

## CB-004 — Upgrade Base

**Card face:** “Upgrade one functioning Core or Relay by one level, increasing its maximum building-space allowance.”

At current level L, reserve 60L Metal, 40L Wood, and 10L Water; perform 60L seconds of constructor work. The cap is Level 4 in this baseline. Allowances are 25, 49, 81, and 121 cells. Only one level-up operation may be pending per base.

Completion increases the allowance without moving existing structures or automatically enabling new cells. Use Expand Perimeter afterward. Losing the anchor suspends the upgrade; destroying its job site cancels it under normal recovery rules.

**Choice:** Pay for growth ahead of need, or use those supplies for vehicles now. The level is retained if the Core is subsequently destroyed.

## CB-005 — Upgrade Facility

**Card face:** “Apply one supported upgrade or component operation to a building. Rebuild a compatible destroyed support module at its reserved attachment.”

Choose a known, explicitly listed operation: storage, loading, powered extraction, work-bay capacity, repair rate, detection, Relay-to-Core replacement, coupler installation/removal, or supported module replacement. This card cannot invent a recipe or unlock an unknown rare capability.

Standard upgrade recipes cost 50% of the original building recipe and work time, rounded up. Component jobs and module replacements use their explicit recipes instead. Relay-to-Core replacement pays the Core recipe and requires a clear expanded footprint; the old Relay is replaced at completion without extra salvage or duplicated inventory. Coupler jobs follow their exclusive-object rules.

For a previously completed Foundry, this common card can replace a destroyed coolant/control module at its known port. Replacing the rare core still needs its rare card. Module replacement pays the module's full recipe; it is not a half-price standard upgrade.

**Choice:** Improve a working site without expanding its footprint, or restore a required connection under pressure. Initial standard upgrades retain the existing footprint and have the listed category caps.

## CB-006 — Depot Network

**Card face:** “Construct two Resource Depots at valid claimed sites. Pay both recipes.”

Cost: 40 Metal and 60 Wood total; 30 seconds of work per Depot. Sites can be in one base or two owned bases. Reserve both 1×2 footprints and loading clearances together. One constructor may travel between sites or two may build concurrently.

This saves a hand slot compared with two Civil Works plays; it does not discount materials or command points. Supplies travel to each actual location. Matching attached ports permit direct transfer only at that site. No global inventory link is created.

**Choice:** Commit to a planned supply corridor, sacrificing Civil Works' flexibility. Losing one depot does not erase the other.

## CB-007 — Forward Works

**Card face:** “Establish an Outpost Relay and a Resource Depot in one new base claim.”

Cost: 40 Metal and 50 Wood; Relay work 30 seconds, Depot work 30 seconds. The complete seed/grid/footprint preview must be valid before commitment. A constructor first completes the Relay claim; the Depot can begin only after its cells are enabled by that establishment.

If the claim fails, the Depot remains unbuilt; cancellation releases unconsumed supplies. The initial 25-cell area includes both structures and their access space. No extraction building is included. A valid resource site nearby gives a reason to use Resource Works later.

**Choice:** Establish a supplied foothold with one hand slot and two CP. An opponent can contest the constructor before the beachhead functions.

## CB-008 — Construction Overtime

**Card face:** “Deliver 10 Water to one construction job. Once supplied and working, its work rate increases by 50% for 60 real seconds. Exhaust.”

Target an existing authorized constructor-built job: common construction, a base/land upgrade, or one piece of a rare complex. This does not authorize a new structure, speed a factory's unit queue, or accelerate exceptional-object synthesis.

The 10 Water is a separate overtime allocation, not a substitute for the job's recipe. The effect activates when the supplies and constructor are ready. Its 60-second timer then runs continuously even if the constructor is interrupted; unused time is lost. Consume the Water when the effect activates. Cancellation beforehand releases that Water at its location.

Only one overtime effect may be pending or active on a job. Standard permanent work-rate upgrades can apply, but timed overtime does not stack with itself. Early job completion ends the effect without transferring it to another job.

**Choice:** Spend Water and a card's scenario availability to finish a critical connection sooner. Harassing the constructor can waste the acceleration window.

## CB-009 — Emergency Reconstruction

**Card face:** “Rebuild one destroyed common building at its recorded site using its full recipe and 75% of its normal build time. Exhaust.”

Target the recorded footprint of a previously completed common building that the player owned at destruction. The site must still be controlled, clear, and grid-valid. Voluntary demolition does not qualify. One reconstruction claim may exist per destruction record; commitment reserves that record.

The replacement begins at its standard unupgraded configuration. Pay full materials; physically recovered salvage may supply that recipe but is not also deducted as a discount. A previous coupler installation is not recreated. A Core rebuilt at its seed retains the base's recorded level; this does not recover its destroyed inventory.

The card cannot rebuild a rare Foundry core or its specialized modules; module recovery uses Upgrade Facility. If reconstruction is interrupted, resume the same authorized job. Cancelling consumes the card opportunity and releases the destruction record for another valid reconstruction attempt.

**Choice:** Recover quickly under pressure without making normal destruction profitable or erasing the loss of upgrades.

## CB-010 — Standardized Plans

**Card face:** “Move one Civil Works, Resource Works, Expand Perimeter, Upgrade Base, or Upgrade Facility card from your discard pile into your hand. Exhaust.”

Target an owned, non-temporary card already in discard. This card exhausts first, freeing its hand slot, then the target moves into hand under the normal hand limit. It cannot retrieve an exhausted card, a requisition copy, itself, or another recovery-effect card.

The retrieved card still costs normal CP and materials to play. Its earlier operation remains a distinct record; retrieving the authorization does not repeat or undo that operation. Subsequent plays validate new sites and capacity normally.

**Choice:** Spend 1 CP and exhaust a specialist card to recover a specific construction option. Unlike library requisition, this preserves another hand card and can be used after that phase's requisition has already been spent.

## CB-011 — Perimeter Watch

**Card face:** “Construct one Sensor Mast and one Defense Tower within the same base. Pay both recipes.”

Cost: 85 Metal and 35 Wood; Mast work 30 seconds, Tower work 45 seconds. Reserve two 1×1 footprints with valid sightlines and firing conditions. Completion is independent. Total operating demand is 3 power units when both are active.

This is a coordinated pair, not a mandatory attachment pattern: either building works alone when its own requirements are met. The card grants no hidden detection range or damage bonus. Sites need not touch, so the player can separate observation from the defended approach.

**Choice:** Commit to defending a real route with one hand slot. Both card points and physical power could otherwise support industrial growth.

## How these fit the deck

The universal cards provide recovery and baseline agency. Specialist common cards trade flexibility for hand efficiency, accelerated work, or targeted retrieval. None is required to build a viable base. Acquire specialists through ordinary card choices, common salvage rewards, and completed common contracts; add them through the existing phase-boundary deck-swap rule.

Initial examples: an expansion-focused deck chooses Forward Works and Depot Network; an industrial deck uses Construction Overtime and Standardized Plans; a defensive deck chooses Perimeter Watch and Emergency Reconstruction. These are tendencies, not exclusive faction classes or free bonuses.

## Example across a real-time phase

With Forward Works and Resource Works in hand, a player spends all 3 CP to establish a remote Relay/Depot complex and then authorize extraction once the claim is complete. They must wait for actual claim completion before Resource Works is legal; choosing the wrong timing can lose that card's window. Haulers and constructors continue into the next phase regardless.

Alternatively, the player spends 2 CP on Perimeter Watch and keeps 1 CP for Standardized Plans. That retrieval gives an option for a later phase but leaves no CP to play it now; without an explicit Retain effect, it will discard at the boundary. The interface must make this opportunity cost clear rather than implying retrieval also grants a free play.

## Definition and review contract

Every card definition records ID, tier, CP cost, zone destination, acquisition channel, legal targets, recipe references, work/effect timing, footprint or pattern checks, reservation rules, interruption, and outcome. Dedicated cards refer to the same building definitions used by Civil Works; they never maintain competing versions of a Depot recipe.

Review these in the actual game for useful decisions, readable timing, legal recovery, and the value of a hand slot. Material totals in this note are checked against [[Initial Economy Tuning]]; these are documentation calculations, not playtest results.

Related rules: [[Cards and World Time]], [[Common Base Buildings]], [[Base Grids and Connections]], [[World Assets and Outcome Resolution]].

## Worker role terminology

Constructor means a [[Basic Unit Roster|Worker]] with a locked, working Construction Rig; hauler means a Worker with Cargo Trailer. These are equipment configurations of one chassis. Orders requiring a role wait for its physical attachment and valid coupling. See [[Worker Attachments and Couplings]] for acquisition, docking, damage, and recovery.

