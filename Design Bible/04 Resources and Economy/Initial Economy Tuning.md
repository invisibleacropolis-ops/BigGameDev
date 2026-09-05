---
title: Initial Economy Tuning
tags: [design, tuning, economy]
status: initial-tuning
---

# Initial Economy Tuning

These are concrete starting values for implementing and playing the baseline. They are not measured balance. Quantities are resource bundles, not kilograms; work times are real seconds of uninterrupted work. Card cadence, travel, worker availability, and interruptions add elapsed time.

## Buildings

| Building | Metal | Wood | Water | Build seconds | Active power demand |
| --- | ---: | ---: | ---: | ---: | ---: |
| Command Core | 80 | 60 | 0 | 90 | 0 for baseline services |
| Construction Yard | 30 | 50 | 0 | 60 | 2 for enhanced work |
| Resource Depot | 20 | 30 | 0 | 30 | 0 |
| Metal Extractor | 40 | 20 | 0 | 45 | 2 for powered mode |
| Timber Yard | 20 | 30 | 0 | 45 | 1 for powered mode |
| Water Station | 30 | 20 | 0 | 45 | 1 for powered mode |
| Biomass Generator | 40 | 30 | 0 | 60 | Supplies 12 |
| Vehicle Fabricator | 100 | 60 | 20 | 90 | 4 |
| Service Bay | 60 | 30 | 10 | 60 | 2 |
| Research Workshop | 60 | 40 | 10 | 60 | 2 |
| Sensor Mast | 25 | 15 | 0 | 30 | 1 |
| Defense Tower | 60 | 20 | 0 | 45 | 2 |
| Outpost Relay | 20 | 20 | 0 | 30 | 0 |
| Air Hangar | 160 | 80 | 30 | 120 | 6 |
| Foundry core | 140 | 60 | 20 | 120 | 4 |
| Foundry coolant module | 30 | 10 | 10 | 30 | 1 |
| Foundry control module | 40 | 10 | 0 | 30 | 1 |

Facility construction Water is commissioning input, separate from later job Water. The Foundry complex totals 210 Metal, 80 Wood, and 30 Water; its full operating load is 6. Its core and both modules are covered by one rare card but consume their own work time.

## Collection, hauling, and consumption

| Parameter | Initial value |
| --- | --- |
| Metal extraction | 5 bundles/minute baseline; 10 powered, consuming 2 Water/minute |
| Wood harvest | 8/minute baseline; 16 with powered-processing upgrade |
| Water collection | 6/minute baseline; 12 powered |
| Loose salvage gathering | 10 bundles/minute per capable unit while at a valid source |
| Worker Cargo Trailer capacity | 60 bundles total, including sealed Water tanks |
| Worker Construction Rig cargo | 20 bundles; supports bootstrap hauling/scavenging |
| Core storage | 1000 bundles combined |
| Depot storage | 1500 bundles combined |
| Relay storage | 120 bundles combined |
| Extractor output buffer | 60 bundles |
| Direct attached transfer | 60 bundles/minute |
| Hauler loading/unloading | 60 bundles/minute at each endpoint |
| Generator fuel | 0.5 Wood per served power unit per minute; zero when serving no load |

Routes must include loading, unloading, travel, and congestion. Two bases do not share stored quantities or power. Several haulers can service one route subject to endpoint capacity. Core support manufacture is independent but runs at half the standard job work rate.

Timber and Metal deposits start with scenario-defined reserves; initial test source minimum is 500 bundles each. A river is renewable with a station extraction cap; stored tanks are finite. No forest regrowth in the baseline.

## Production and projects

| Job | Metal | Wood | Water | Work seconds | Command points |
| --- | ---: | ---: | ---: | ---: | ---: |
| Worker + Cargo Trailer package | 25 | 0 | 5 | 45 | 1 |
| Worker + Construction Rig package | 30 | 0 | 5 | 45 | 1 |
| Produce scout | 40 | 0 | 10 | 60 | 1 |
| Produce assault hovercraft | 80 | 0 | 15 | 90 | 1 |
| Base level increase | 60 × current level | 40 × current level | 10 × current level | 60 × current level | 1 |
| Expand Perimeter, up to 8 cells | 0 | 0 | 0 | 15 per cell | 1 |
| Standard facility upgrade | 50% of original recipe | 50% of original recipe | 50% of original recipe | 50% of original time | 1 |
| Coupler synthesis | 60 | 0 | 30 | 120 | 1 |
| Coupler install/remove | 20 | 0 | 10 | 60 | 1 |
| Gravitic Lance refit | 40 | 0 | 10 | 60 | 2 |

Round fractional recipe values upward. Standard facility upgrades are limited to one per declared upgrade category in the baseline. They grant one named benefit: storage ×1.5, loading ×1.5, an additional work bay, or work rate ×1.25 as appropriate. Powered drilling/processing unlocks the separately listed powered rates. An additional bay adds that job's full power demand when active. Faster work uses the same total job materials but completes sooner; it does not create resources.

Repairing 25% of a unit's maximum health consumes 10% of its production Metal and Water, rounded up, and takes 20 seconds at a Service Bay. Fractional repair is proportional before final rounding. Demolition salvages 50% of spent Metal/Wood, destruction 25%; spent Water is not recovered. Unspent inventory is separate: demolition releases it, destruction recovers 50% as cargo. Durable exceptional components follow their explicit full-recovery rule.

## Opening arithmetic and priorities

Starting Core, Worker with Construction Rig, Worker with Cargo Trailer, and Scout are supplied. These are two Workers of the same chassis type with different physical equipment. Starting inventory is 400 Metal, 350 Wood, and 150 Water. A Yard, Depot, three collection buildings, Generator, Fabricator, and two remote Relays require 320 Metal, 280 Wood, and 20 Water, leaving 80 Metal, 70 Wood, and 130 Water before gathering or production. That remainder can fund one assault hovercraft or several smaller support decisions.

At its maximum 12-unit load, one Generator burns 6 Wood/minute; a baseline Timber Yard produces 8/minute before hauling losses. These rates show a possible supply margin, not guaranteed delivery. Build the Timber Yard and establish delivery before placing sustained load on the Generator. A Generator supports a Fabricator, Service Bay, Workshop, Sensor, and Tower together at 11 power units; other powered work requires load priorities or another Generator.

Card windows, actual driving, layout congestion, and opponent pressure must still be measured. In particular, one truck cannot be assumed to satisfy every route simultaneously. The first real play session should establish whether more starting hauling capacity or shorter windows are needed.

See [[Design Baseline]], [[Common Base Buildings]], [[Core Resources]], and [[First Playable Scenario]].



## Modular Worker production

The earlier two utility production recipes now represent chassis-and-attachment packages. A bare Worker costs 20 Metal and 3 Water with 30 seconds of manufacturing; a Cargo Trailer adds 5 Metal/2 Water and 15 seconds; a Construction Rig adds 10 Metal/2 Water and 15 seconds. Physical docking occurs afterward and can be blocked. Initial supplied packages start coupled. Additional front-tool recipes are in [[Worker Attachments and Couplings]]. Core support manufacture still takes twice standard work time.

Repair chassis, tool, trailer, and connector condition separately. Percentage repair recipes use the relevant component's manufacture cost; connector repair uses the explicit integrity recipe in the attachment note. Neither chassis repair nor module salvage duplicates stored equipment.

