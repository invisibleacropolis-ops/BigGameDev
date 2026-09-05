---
title: Core Resources
tags: [design, economy, resources]
status: adopted-baseline
---

# Core Resources

## Locked resource identities

The three primary collectible resources are **Metal, Wood, and Water**, as requested by the creator. They exist in the actual world. The extraction roles and logistics below are adopted rules. Costs and rates still require actual playtesting.

| Resource | World sources | Primary uses | Distinct strategic pressure |
| --- | --- | --- | --- |
| Metal | Surface deposits, mines, wrecks, ruined machinery | Vehicles, mechanisms, weapons, repairs, advanced facilities | Expansion and replacement forces compete for durable material |
| Wood | Forests, fallen timber, salvageable wooden structures | Structural frames, utility buildings, biomass generator fuel | Immediate construction competes with continued power generation |
| Water | Rivers, lakes, springs, accessible groundwater, recoverable tanks | Industrial cooling/process water, powered drilling, repair and research operations | High industrial activity requires sustained delivered supply |

Wood remains literal harvested material; using it for structural composites is the baseline material explanation, not a fourth resource. Metal sources can differ in extraction rate without requiring a separate ore currency. The extraction facility accounts for processing in its output rate. Exotic components such as the dark matter coupler remain individual assets with compatible uses, not a fourth universal resource bar.

## Physical accounting

Track quantities at sources, extractor output buffers, cargo carriers, depots, and job input buffers. A faction-wide total is informative; only material at a facility or deliverable through its logistics can supply that facility. Show available, reserved, and in-transit quantities separately.

For each resource: `new stock = previous stock + delivered + recovered - dispatched - consumed - lost`.

Reservations restrict availability without consuming material or duplicating it. Loading transfers stock into cargo; unloading transfers it to storage. A queued job reserves its recipe and starts after required inputs arrive. Consumption occurs through defined work stages. Interruption preserves unused inputs and applies explicit salvage rules to work already done.

Hover haulers automate repeated delivery routes. Player orders set priorities and destinations freely; cards authorize construction and production rather than every trip. Matching attached Depot ports permit finite-rate direct transfer. Every other transfer uses physical haulers, including short trips within a base.

Water is transported in sealed tanks by the same logistics system initially. Pipelines can be a later alternative with their own infrastructure and vulnerability. Extracted water becomes usable Water; contamination and treatment subtypes are deferred.

## Capacity and operating rules

Power is a connected facility's available service capacity, not a fourth collectible. The Biomass Generator consumes Wood to provide it. Work bays and constructors provide time-based production capacity, not stored production points. Base power follows visible service links through contiguous enabled cells as defined in [[Base Grids and Connections]]. None of these service rules restricts friendly unit possession unless separately decided.

**Water rule:** Charge a clear process-water amount per active industrial job. Power consumes Wood while supplying loads. Avoid full idle Water upkeep in the first economy. Lost supply suspends affected work; it does not instantly destroy buildings or immobilize field units. This keeps disruptions meaningful without creating an immediate collapse spiral.

## Scarcity and recovery

- Metal deposits have finite reserves; combat and demolition return a defined fraction of recoverable Metal.
- Forest sites have finite harvestable stock. Regrowth, if added, must use an explicit rate and conditions rather than silently replenishing a cleared site.
- Water sources have extraction limits. Whether a source also depletes depends on its type; rivers and small tanks should not use identical reserve rules.
- Common map starts must provide reachable sources for all three resources, or an explicitly designed substitute such as accessible salvage. Do not generate a normal start dependent on a rare card.
- Basic collection can work slowly without grid power. Losing advanced infrastructure therefore leaves a recovery route.

Source yield, cargo capacity, trip time, and operating consumption together determine whether an economy is sustainable. We must measure these in a real playable loop before choosing final rates.

See [[Common Base Buildings]], [[World Assets and Outcome Resolution]], and [[Strategy Building Research]].

## Operating allocation and job accounting

A Generator consumes Wood proportional to served demand, with no baseline idle fuel charge. When supply is insufficient, the player-defined priority order powers complete loads until remaining capacity is insufficient; unsupported jobs suspend. Automatic defaults prioritize active defenses and already-running work before new production. Players can override that order without a card. Core support production and baseline collection have their own low-rate independent operation.

Industrial job recipes declare total process Water, consumed in proportion to completed work. Power interruption stops work and process consumption together. Previously consumed Water is not refunded. Construction materials are consumed in declared work stages; unused reserved cargo is released on cancellation at its current location. These rules distinguish reservation, delivery, and irreversible consumption.

Basic gathering and storage buffers are finite. A full buffer pauses extraction. A blocked delivery route causes a waiting or rerouting hauler state with an alert; it does not silently credit a distant stockpile. Congestion, reserve exhaustion, and empty fuel storage are readable world conditions.


Initial quantitative defaults: [[Initial Economy Tuning]].


## Worker role terminology

Constructor means a [[Basic Unit Roster|Worker]] with a locked, working Construction Rig; hauler means a Worker with Cargo Trailer. These are equipment configurations of one chassis. Orders requiring a role wait for its physical attachment and valid coupling. See [[Worker Attachments and Couplings]] for acquisition, docking, damage, and recovery.

