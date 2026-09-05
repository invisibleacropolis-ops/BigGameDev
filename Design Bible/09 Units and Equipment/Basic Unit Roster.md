---
title: Basic Unit Roster
tags: [design, units, common]
status: adopted-design-initial-tuning
---

# Basic Unit Roster

[[Units and Equipment Index|Units and Equipment]]

## Established direction

There are three basic chassis: two military vehicles, Assault and Scout, and one utility vehicle, Worker. All ground vehicles hover. The Worker is a small truck whose front and rear attachments determine its job. Attachments are separate physical objects that must be acquired, approached, aligned, and locked onto the chassis.

Assault carries a top-mounted cannon and missile rack. Scout carries a top-mounted machine gun and a spotting/designation system. The exact alternative weapons below are design additions with provisional tuning. Earlier constructor and hauler references now name Worker configurations, not separately manufactured chassis types.

## Chassis roles

| Chassis | Default equipment | Movement identity | Main responsibility | Limitation |
| --- | --- | --- | --- | --- |
| Assault | Top cannon; side/rear-top missile rack | Heavy momentum, slower turning, stable weapon platform | Fight vehicles, escort Workers, attack defended sites | Limited scouting and pursuit ability; ammunition/reload exposure |
| Scout | Top machine gun; designation mast | Fast acceleration, responsive turns, strong ridge traversal | Discover routes and objects, track targets, direct available air support | Fragile under sustained cannon fire; poor frontal assault |
| Worker | Front and rear standardized utility sockets; no permanent military weapon | Small hovertruck; attached mass changes acceleration, turning, and slope behavior | Haul, gather, build, recover equipment, and support logistics | Role needs a compatible working attachment; towing creates exposure |

Direct control is available for every chassis. AI pilots obey the same handling, weapon, and connector limits. Final speed, health, armour, and collision values need actual driving and combat trials.

## Slots and constraints

Assault has one main turret slot, one secondary rack slot, and basic optics. Scout has one light turret slot and one recon slot. Worker has one front tool socket and one rear articulated utility socket. Weapon mounts are not Worker hinge connectors; military refits occur at a Service Bay under their own rules.

A slot accepts declared compatible equipment only. A Scout cannot carry an Assault cannon merely because a player recovered one. Worker attachments have envelope, mass, power, and socket constraints in addition to their role tags. The first rear module has no further tow socket: trailer trains are future content, not an accidental consequence of shared connectors.

The Worker cannot mine and build simply because both orders exist in its command menu. Capability queries use the attached, locked, functional equipment. A damaged module can remove a capability while leaving the truck driveable.

## Worker configuration names

| Role label | Required equipment | What it can do |
| --- | --- | --- |
| Hauler | Rear Cargo Trailer | Transport up to 60 bundles, including sealed Water tanks |
| Miner | Front Mining Head | Work a compatible Metal deposit into its small output buffer; can use a Cargo Trailer |
| Timber Worker | Front Forestry Head | Cut and collect compatible timber; can use a Cargo Trailer |
| Constructor | Rear Construction Rig | Build, expand, plant claim beacons, and manipulate installed components; carries 20 bundles |
| Water Collector | Front Pump Head plus Rear Cargo Trailer | Collect usable Water into carried tanks at a valid intake |
| Recovery Worker | Front Recovery Winch | Reposition a loose compatible module into a docking position; does not turn it into a powered tool |

These labels update with physical equipment. The same chassis may be a Constructor in one phase and a Hauler after it drops one rear module and attaches another.

## Acquisition and production

Produce Support selects one Worker chassis, one common attachment, or one listed chassis-and-attachment package at a capable facility. It remains a 1-CP common authorization, with different physical recipes. The chosen output is fixed at commitment.

The Core can produce Worker chassis, Cargo Trailers, Construction Rigs, and their two bootstrap packages at half standard work rate. The Construction Yard adds all common Worker attachments and Worker chassis at standard rate. The Vehicle Fabricator can produce these and the two military chassis. Tool use does not require a continuously surviving production building.

Worker packages manufacture separate chassis and attachment identities. The factory/yard uses its real staging area to perform the same alignment and latch process before delivery; there is no permanent merged package object. Blocked docking space leaves the finished parts waiting visibly. Initial scenario-supplied packages begin already safely coupled.

## Initial roster and continuity

The opening keeps its previous two utility roles: one Worker with Construction Rig, one Worker with Cargo Trailer, and one standard Scout. Assault is the first standard military production option, not an additional free starting unit. Resource buildings retain automatic baseline extraction; mobile Worker tools add a flexible alternative without deleting fixed-site value.

A Worker with a Construction Rig is required to perform construction orders. A bare Worker can haul only the baseline recovery pallet of 5 bundles and pick up loose salvage; it cannot construct. A detached Construction Rig remains recoverable equipment. Defeat rules therefore consider recovery capability rather than instantly eliminating a faction when a rig detaches: see [[Worker Attachments and Couplings]].

## Unit and equipment damage

Track chassis, weapon, module, and connector condition separately. Chassis destruction does not automatically destroy a physically separated trailer. A component that takes lethal damage becomes its own wreck; surviving equipment remains recoverable. Cargo remains in its actual container until unloaded, spilled, destroyed, or transferred by an explicit interaction.

Military default production prices include the standard weapon fit. Alternative fits have explicit recipe and work costs; the old weapon goes into physical storage when removed intact. Refit does not generate an extra free stock weapon. See [[Common Vehicle Weapons]] and [[Worker Attachments and Couplings]].
