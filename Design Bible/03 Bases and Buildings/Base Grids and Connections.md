---
title: Base Grids and Connections
tags: [design, bases, placement]
status: adopted-baseline
---

# Base Grids and Connections

## Seed and real terrain

A base is a world location anchored by a seed point. Its grid overlays the same terrain occupied by units and structures. Initial tuning: cells measure 16 metres per side. Grid orientation is chosen at establishment and remains fixed; individual buildings rotate in 90-degree steps.

A Civil Works establishment commitment sends a constructor carrying a colonization beacon to the chosen point. The constructor plants the beacon and builds either a Command Core or Outpost Relay. A player can directly pilot that constructor. Flags mark ownership; they are the visible result of the claim rather than an unrelated free-building route.

The seed remains part of the base record if the Core is destroyed. Core and Relay both anchor the same base/grid system; a Relay is a cheaper remote foothold with storage and no support-unit production. Upgrading a Relay to a Core expands its footprint only if the additional cells are clear.

## Levels and selected cells

Initial tuning: Level 1 permits 25 cells, Level 2 permits 49, Level 3 permits 81, Level 4 permits 121. Establishment enables a valid connected 25-cell area including the seed. A level upgrade increases the allowance. Expand Perimeter then claims up to 8 new cells per play, within that allowance.

New cells must connect through shared edges to enabled cells. Blocked terrain does not become usable merely because the allowance increased. A claim cannot overlap another base's physical claimed area, even when grids have different orientations. World-space overlap is authoritative.

Base upgrades require the current Core/Relay, a constructor, delivered recipe materials, and Upgrade Base. Higher levels do not require a rare building. The size and price curves are tuning data. Footprints, enabled land, and clearance use the same cell accounting: empty lanes occupy enabled land but are not building footprints.

Every player-built permanent structure occupies a base grid, including remote extractors and their depots. Claim an outpost at a remote source before installing structures. Loose field salvage requires no claim. Extraction machinery occupies valid ground adjacent to or over its declared source; a Water Station can have a bank footprint and an intake extending to water under its placement rule.

## Footprints and connection semantics

A footprint is a set of cells, not just an area count. Ports have types, edges, positions, and capacity. Rotation transforms both footprint and ports. Diagonal proximity never counts as attachment unless a structure expressly declares it.

Required predicates are: shares edge, matching ports touch, required relative-cell pattern, connected service, valid terrain, and clear access. Pattern slots require distinct structures unless sharing is explicitly supported. The baseline Foundry uses dedicated modules; one module cannot satisfy two Foundries.

Construction of incomplete arrangements is permitted with a clear inactive-state preview. Placement legality and operation readiness are separate. A missing module suspends its dependent function rather than invalidating ownership of the building.

## Footprint defaults

| Structure | Cells | Clearance or connection |
| --- | --- | --- |
| Command Core | 2×2 | One open entrance cell |
| Construction Yard | 1×2 | One approach cell |
| Resource Depot | 1×2 | One loading cell; optional matching transfer port |
| Metal Extractor | 1×2 | Deposit access and one loading cell |
| Timber Yard | 1×2 | Reachable harvest area and loading cell |
| Water Station | 1×2 | Source intake and loading cell |
| Biomass Generator | 1×2 | Wood delivery access |
| Vehicle Fabricator | 2×2 | Two-cell-wide, one-cell-deep exit apron |
| Service Bay | 2×2 | Same vehicle apron |
| Research Workshop | 1×2 | One delivery cell |
| Sensor Mast | 1×1 | Valid sensing position |
| Defense Tower | 1×1 | Firing arc; no loading lane required |
| Outpost Relay | 1×1 | One loading cell |
| Air Hangar | 3×3 | Three-cell-wide launch apron and clear air approach |
| Foundry core | 2×2 | South delivery edge; two mandatory module ports |
| Foundry coolant / control module | 1×1 each | Designated matching port |

These are adopted initial layout values, not validated scale. Entrances can share a lane if the actual navigation geometry supports it; footprints cannot overlap clearances. Traffic congestion is physical, not an automatic adjacency penalty.

## Power and loading

A completed Generator supplies buildings in its base through visible ground service links across contiguous enabled cells. Links are integral to the developed ground, not separate mandatory cards. Rock-blocked or unclaimed gaps do not conduct. Local power capacity is shared and allocated by player priority; different bases have separate networks. A surviving base grid works without its Core.

A Depot attached by matching ports transfers materials directly to that building at a finite rate. Other transfers require haulers, including within the base. Attachment therefore saves trips without moving goods between distant locations. Power connectivity never implies material connectivity.

## Layout example: Level 1

Each token is one cell. The fourth row is a five-cell shared clearance lane. This demonstrates space accounting only; terrain and vehicle navigation require real verification.

```text
C C D G G
C C D F F
. . . F F
. . . . .
Y Y W W .
```

C = Core, D = Depot, G = Generator, F = Fabricator, Y = Construction Yard, W = Water Station. Orient entrances toward the middle/lower lanes; the Fabricator exits south. Timber and Metal collection can begin through field salvage or remote outposts. A single Level 1 base does not fit the entire mature roster.

## Loss, demolition, and capture

Losing a Core disables its support production and new level/land upgrades, not existing units, inventory, structures, or local generator services. A surviving constructor can rebuild it at the seed using Civil Works. Constructors can scavenge and carry a limited bootstrap load; they are not dependent on haulers for every recovery step.

Buildings are not freely dragged to new cells. Demolition is a constructor order with a visible delay, releases unconsumed inputs, and produces physical salvage from part of completed construction. A new placement needs a construction card. No operation creates more materials through build/demolish cycling.

Base capture requires an establishment commitment, a constructor at the seed, and disabled or destroyed original Core/Relay. The claim channel stops under hostile damage. Completion transfers claimed land and intact buildings/local stocks; defenders' units and cards do not transfer. Active jobs cancel under ordinary input rules before transfer. Damaged structures need repairs before useful operation. Claim duration and salvage fractions are tuning data.

Inspect and preview enabled cells, allowance, footprint, ports, clearance, delivery routes, and exact reasons for inactivity. See [[Common Base Buildings]] and [[Rare Building - Coupler Foundry]].


## Worker role terminology

Constructor means a [[Basic Unit Roster|Worker]] with a locked, working Construction Rig; hauler means a Worker with Cargo Trailer. These are equipment configurations of one chassis. Orders requiring a role wait for its physical attachment and valid coupling. See [[Worker Attachments and Couplings]] for acquisition, docking, damage, and recovery.

