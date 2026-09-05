---
title: Vision and Pillars
tags: [design, vision]
status: adopted-baseline
---

# Vision and Pillars

## Intent

The player operates inside a real-time 3D battlefield and can issue RTS orders or take direct FPS control of any friendly unit. The world layer combines base development, resource discovery, territory competition, and large scenario objectives. Cards govern building and other strategic interventions; opponents use the same card logic and have access to comparable armies and resources.

The creator's reference points include Battlezone for embodied command; XCOM, Midwinter, Magic Carpet, Civilization, and Heroes of Might and Magic for aspects of the wider world; and Tribes for jetpack and skiing movement. These are starting references, not commitments to reproduce every system from each game.

## Pillars

1. **The commander belongs in the action.** Personal piloting should offer meaningful opportunities while squads remain competent without constant attention.
2. **Strategic choices become physical situations.** Build sites, convoys, salvage, and resource operations invite intervention.
3. **Opponents play the same game.** Resources, prerequisites, card resolution, and visibility rules apply consistently.
4. **Movement is intrinsically enjoyable.** Terrain, momentum, altitude, and controlled sliding support traversal and combat.
5. **Events connect to an existing world.** Missions arise from places, factions, resources, and current circumstances.

## Movement intent

Ground vehicles hover: cars, trucks, tanks, and other roles without wheels or treads. Aircraft include true jets and flying vehicles. Characters have FPS movement, jetpacks, and skiing. Physics should feel coherent across these forms, with cinematic concessions where useful.

Share momentum and terrain-reading principles without forcing identical handling. A loaded hovertruck preserves speed but turns widely; a scout changes direction quickly; a skier converts slopes into speed; an aircraft trades minimum speed for reach. Cargo changes handling, giving delivery missions a physical identity.

Unit switching follows [[Command and Opponent AI]] without a range limit. Exact durability, pilot-death rules, remote-control fiction, aircraft handling, and collision tuning are deferred.

## Art intent

Models and landscape textures use the same 256-color palette. Geometry density and texture resolution evoke the PlayStation 1 era. Modern shaders and particles can use the full color spectrum.

Keep terrain and units readable through bold silhouettes, material blocks, and restrained texture noise. Reserve the brightest effects for weapons, navigation, and exceptional events. Explore a hover convoy on a ridge, a contested salvage crater, and a base under construction as the first three concept-art subjects.

**Deferred:** Actual palette, setting, factions, tone, camera treatment, and whether to emulate period rendering artifacts. Low polygon counts do not automatically imply texture wobble or vertex jitter.

## Scope tensions to keep visible

- A large deck can create variety but also increase the time spent reading instead of piloting.
- Direct control must matter without making autonomous armies feel useless.
- Rich base management must remain understandable while combat continues elsewhere.
- Rare cards should create interesting situations without deciding every contest before it starts.

See [[Cards and World Time]], [[Command and Opponent AI]], and [[First Playable Scenario]].

