---
title: Rare Building - Coupler Foundry
tags: [design, buildings, rarity]
status: adopted-baseline
---

# Rare Building - Coupler Foundry

## Access and role

The Rare Establish Coupler Foundry card authorizes one complex with a core, coolant module, and control module. Construction Yard and Research Workshop are prerequisite unlocks. The core can be constructed before a coupler is recovered; a coupler is a processing input, not a construction prerequisite.

The complex requires Metal-heavy construction, structural Wood, commissioning Water, local power, and cargo access. Its core has one processing bay. Common infrastructure works without it. It is Rare and not Unique: multiple complexes are permitted if land, cards, materials, and power support them.

## Exact baseline pattern

Unrotated coordinates: core occupies (0,0), (1,0), (0,1), (1,1). Coolant occupies (2,0), attaching its west port to the core's upper east port. Control occupies (-1,0), attaching its east port to the core's upper west port. The south edge has a two-cell delivery apron at (0,2), (1,2). Rotate the whole pattern in quarter turns.

```text
Control  Core Core Coolant
         Core Core
         Lane Lane
```

The complex occupies six building cells plus two clearance cells. Modules are dedicated to that core. The initial rare construction card authorizes all three staged pieces and reserves their sites; constructors build them independently. The card discards when committed while construction continues. Missing pieces are visible as pending work.

After initial completion, a destroyed module can be rebuilt at its reserved port through common Upgrade Facility plus its material recipe; another rare card is not required. A destroyed core requires the rare construction card to replace. Intact orphan modules can be reused only when reassigned to a newly authorized compatible core, one-to-one.

## Processing and interruption

The coolant module receives Water and spends the recipe's process-water allocation. The control module provides the operating control dependency. Neither adds a fourth currency. All three pieces must function and be powered for processing to advance. Loss of one suspends work; the core retains the object and progress. Destruction of the core follows exceptional-input recovery rules.

Research Project authorizes a known synthesis recipe here. It consumes Metal tooling, Water, power supplied through Wood consumption, real processing time, and the coupler on completion. The rare facility does not automatically grant every legendary output; the component, recipe knowledge, and exclusive output slot must also qualify.

## First result: Gravitic Lance authorization

The coupler's synthesis recipe grants a Legendary, Unique card: **Gravitic Lance**. Its uniqueness scope is the scenario and its capability key is Gravitic Lance. Reserve that output slot when synthesis is committed; release it if the operation is cancelled. Two factions cannot consume inputs for duplicate promised unique outputs.

Playing the card at a Service Bay fits one compatible assault hovercraft with the weapon, consuming Metal, Water, and refit time. It costs 2 command points and exhausts at commitment. The weapon is a charged line-of-sight siege shot with a visible charge and a cooldown; damage and timing require real tuning. It uses vehicle energy rather than a fourth stocked resource.

An equipped unit creates no extra card. Destroying it removes the active weapon. The owner's exhausted authorization remains recoverable only through explicit card-recovery effects, and replay still checks that no active or pending Lance refit exists. Thus recovering a card does not duplicate a surviving weapon. Card uniqueness, pending refit, and active weapon are separately tracked linked constraints.

## Competing infrastructure use

Installing the same coupler in a Generator reduces its Wood consumption by 25% at equal served load. This uses common Upgrade Facility and a constructor; it does not require the Foundry. The player may redirect cargo or cancel uncompleted synthesis to choose this use. Final synthesis consumes the component; final installation keeps it as an installed object. See [[World Assets and Outcome Resolution]].

The Foundry therefore changes the owner's possible uses while increasing dependence on common supply routes and vulnerable module placement. See [[Base Grids and Connections]], [[Core Resources]], and [[Procedural Content and Rarity]].
