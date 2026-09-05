---
title: First Playable Scenario
tags: [design, prototype]
status: adopted-baseline
---

# First Playable Scenario

## Purpose and scope

Build one real encounter that exercises the adopted card, grid, resource, and component rules. This is the selected design validation scenario, not an implemented game. Ask the creator to play the actual build before claiming the economy or movement works.

## The valley

Two factions begin with a Level 1 Core, Worker with Construction Rig, Worker with Cargo Trailer, Scout, the curated opening hand, and a bootstrap reserve. Each has reachable Metal, Wood, and Water sources. The terrain offers a short exposed cargo route and a longer sheltered route. Solar time and four card phases follow [[Cards and World Time]].

The bootstrap reserve must cover a Yard, Generator, Fabricator, required collection sites, and enough Wood for the first productive jobs under final recipes. A remote source additionally requires a Relay; reserve and travel-time checks must include it. [[Initial Economy Tuning]] supplies initial rates and a material-only opening budget; this constraint still requires checking actual travel and timing.

The neutral enclave has a generator need and a second damaged network station. Its infrastructure is an existing world entity; the baseline does not require simulating a civilian population. One announced contract rewards the first delivery of a specified Water quantity; another accepts a compatible coupler installation to restore the second station. Both are finite contracts with visible consequences.

## Objective and the contested branch

Initial tuning: earn 3 enclave standing points first. Complete each of these at most once per faction, except the two public first-completer contracts, which resolve globally once:

- Deliver the enclave's requested Water before its deadline: 1 point to the first completer.
- Complete a Repair Network project at a damaged enclave station using delivered Metal: 1 point per faction at separate designated stations.
- Resolve the contested coupler through any one qualifying use: 1 point to its successful user, globally once for that object.
- Hold the designated relay ridge continuously for a scenario-defined interval: 1 point per faction, once.

Standing is scenario objective progress, not a fourth spendable resource. Point values, quantities, and deadlines are initial tuning data. Elimination follows [[Worker Attachments and Couplings]]: the faction must lack a Core/Relay and a viable Worker construction-recovery path; a temporarily detached rig does not cause defeat. A standing tie in the same simulation step produces a draw.

A live coupler can be installed at the enclave for the public restoration contract, installed in the player's Generator for fuel efficiency, or consumed in a Foundry to obtain Gravitic Lance. Any one earns the component's one resolution point; the resulting capability or restoration also persists. Removing and reinstalling it cannot score again. This makes the branch relevant without making one use the only winning action.

## Rare access and causality

For this scenario, one announced salvage cache contains the rare Foundry construction card. Both factions can pursue it under the same rules. The coupler is located at a separate eligible wreck and remains useful even if its holder never acquires the rare card. The cache is an explicit scenario opportunity, not a hidden AI gift. Ordinary research, building, and military choices remain available to both factions.

The director may add bounded contextual incidents such as a supply convoy breakdown or an exhausted-card recovery task. These require actual eligible assets and cannot replace the primary objectives or create new victory points implicitly.

## Expected choices

A player can invest Wood in power or expansion, use an outpost to reduce hauling distance, defend a Factory lane, interrupt a Foundry module, switch from synthesis to Generator installation before conversion, and use common requisition to recover a missing construction opportunity. Opponents act on their own knowledge and needs.

## Real-play observations

Observe whether the initial reserve reaches replenishment; whether the initial footprints leave driveable lanes; whether players can manage a hand while piloting; whether transport and module attacks create recoverable pressure; and whether the three coupler uses compete meaningfully. Verify actual accounting through the implemented operations, including cancelled delivery, interrupted processing, card recovery, and the unique active-weapon cap.

Do not substitute mock tests or invented success reports. The current documentation checks establish only internal consistency. See [[Design Baseline]], [[Core Resources]], and [[World Assets and Outcome Resolution]].


Initial quantitative defaults: [[Initial Economy Tuning]].



