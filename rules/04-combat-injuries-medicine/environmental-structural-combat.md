# 4.17 — Environmental & Structural Combat

Status: Provisional design section pending explicit approval.

This section defines how the physical environment can be damaged, altered, destroyed, ignited, flooded, collapsed, or otherwise transformed by combat.

It must preserve:
- battlefield persistence;
- mechanism-specific damage;
- meaningful cover and terrain;
- collateral consequences;
- scalable abstraction.

The environment should matter because it affects what characters can perceive, reach, traverse, defend behind, or survive.

## 4.17.1 The Environment Is Part of Combat State

Buildings, walls, trees, roads, bridges, water, cliffs, tunnels, and other terrain should not be decorative backdrops.

They can:
- block line of sight;
- provide cover;
- restrict movement;
- become hazards;
- be damaged;
- collapse;
- burn;
- flood;
- create debris;
- alter escape routes.

Once altered, the battlefield should remain altered.

## 4.17.2 Structural Damage Uses the Same Core Logic as Other Damage

Environmental objects should respond to:
- blunt force;
- cutting;
- penetration;
- heat;
- explosion;
- pressure;
- specialized chakra effects.

The object’s:
- material;
- thickness;
- construction;
- support;
- current condition

determine the result.

There should not be a completely separate arbitrary “object damage” system.

## 4.17.3 Material Matters

Relevant material properties may include:
- hardness;
- toughness;
- brittleness;
- flexibility;
- density;
- heat resistance;
- conductivity;
- combustibility.

Examples:
- wood may burn and splinter;
- stone may crack or fragment;
- metal may bend, conduct, or melt;
- earth may deform or collapse;
- glass may shatter.

The system should use broad material classes unless more detail matters.

## 4.17.4 Structural Integrity Is Not a Simple HP Bar

A structure should not necessarily behave like:
“Wall HP: 200.”

Instead, the engine should care about:
- what part was damaged;
- whether it supports weight;
- whether cracks or breaches exist;
- whether the material failed locally or globally.

A wall with a large hole may remain standing.
A smaller failure at a critical support can collapse a larger structure.

## 4.17.5 Structural Condition States

For practical simulation, structures may use broad states such as:

### Intact
No meaningful damage.

### Damaged
Local damage exists but ordinary function remains.

### Compromised
Structural function is meaningfully reduced; further stress may cause failure.

### Breached
A passage, opening, or major protective failure exists.

### Partially Collapsed
Some sections have failed.

### Collapsed / Destroyed
The structure no longer performs its original function.

These are summaries of actual damage.

## 4.17.6 Local Damage and Global Failure Are Different

An attack may:
- crack one wall;
- cut a beam;
- destroy a door;
- make a crater;
- collapse one roof section

without destroying the entire structure.

Global collapse should require sufficient damage to critical supports or overwhelming force.

## 4.17.7 Critical Structural Elements

Some parts of a structure may matter more than others.

Examples:
- columns;
- load-bearing walls;
- bridge supports;
- roof beams;
- foundations;
- retaining walls.

Damage to these may create disproportionate consequences.

Detailed engineering should only appear when the interaction becomes important.

## 4.17.8 Buildings Should Not Collapse Arbitrarily

The simulation should avoid:
- cinematic collapse with no structural cause;
- indestructible scenery despite overwhelming attacks.

Collapse should follow:
- attack scale;
- material;
- support damage;
- accumulated stress;
- technique behavior.

## 4.17.9 Large-Scale Jutsu Can Transform Terrain

Powerful techniques may:
- create craters;
- split ground;
- flood areas;
- raise walls;
- destroy buildings;
- uproot trees;
- alter waterways.

These changes should persist in battlefield state.

The exact creation mechanics belong to Ruleset 3.
Ruleset 4 tracks their environmental consequence.

## 4.17.10 Terrain Destruction Can Change Positioning

Destroying terrain may:
- remove cover;
- create cover;
- open new routes;
- block old routes;
- create elevation changes;
- isolate combatants;
- expose hidden positions.

Environmental attacks can therefore be tactically valuable without directly targeting a character.

## 4.17.11 Falling Debris

Structural damage can create secondary hazards.

Debris may:
- strike characters;
- block movement;
- pin someone;
- obscure vision;
- damage equipment.

Significant debris should use normal impact or penetration mechanics.

## 4.17.12 Collapse Zones

A failing structure may create an area where:
- debris can fall;
- footing is unstable;
- routes may close;
- line of sight changes.

The system may represent this as a dynamic hazard rather than calculating every fragment.

## 4.17.13 Entrapment

Collapse can trap or partially bury characters.

Possible consequences:
- restraint;
- crushing;
- impaired breathing;
- blocked movement;
- separation from allies.

This interfaces with 4.15 restraint and 4.11 deterioration.

## 4.17.14 Fire Is a Persistent Environmental Process

Fire may:
- spread;
- consume fuel;
- produce heat;
- create smoke;
- damage structures;
- block routes;
- ignite equipment or clothing.

Fire should continue after the initiating technique ends if fuel and conditions support it.

## 4.17.15 Fire Spread

Fire spread depends on:
- fuel;
- dryness;
- wind;
- barriers;
- moisture;
- structure layout.

The system should model spread broadly unless fire becomes central to the encounter.

## 4.17.16 Smoke

Smoke may:
- reduce visibility;
- impair breathing;
- reveal airflow;
- spread through enclosed spaces.

Smoke should be tracked as an area condition.

## 4.17.17 Water and Flooding

Water techniques or environmental failures may:
- flood rooms;
- create currents;
- change footing;
- extinguish fire;
- conduct electricity;
- alter movement;
- create drowning risk.

Water depth and flow only need precise tracking when consequential.

## 4.17.18 Currents and Moving Water

Strong current may:
- force movement;
- separate teams;
- carry debris;
- interfere with footing;
- pull characters underwater.

This should be treated as a persistent environmental force.

## 4.17.19 Mud, Ice, Snow, and Loose Ground

Terrain conditions may affect:
- traction;
- balance;
- acceleration;
- concealment;
- movement cost.

The effect should come from the actual surface rather than a universal terrain penalty.

## 4.17.20 Cliffs and Height Hazards

Edges, rooftops, cliffs, and pits create:
- fall risk;
- forced-movement danger;
- restricted escape routes.

A character near an edge is not automatically penalized.
The danger comes from what actions can move them across it.

## 4.17.21 Underground Combat

Tunnels, caves, and underground techniques can create:
- confined spaces;
- collapse risk;
- limited visibility;
- restricted air;
- unusual attack angles.

Structural support becomes especially important underground.

## 4.17.22 Water Surface and Tree Combat

Tree trunks, branches, and water surfaces are valid battlefield surfaces where chakra control permits.

Environmental damage can:
- break branches;
- cut trees;
- create waves;
- destabilize footing.

## 4.17.23 Vegetation

Vegetation may:
- provide concealment;
- catch fire;
- block movement;
- hide traps;
- create climbing routes.

Dense forests should feel tactically different from open ground.

## 4.17.24 Weather

Weather may affect:
- visibility;
- projectile behavior;
- fire spread;
- water availability;
- footing;
- temperature;
- sound.

Weather should only receive explicit mechanical attention when it meaningfully changes the encounter.

## 4.17.25 Wind

Wind may:
- alter smoke;
- spread fire;
- affect light projectiles;
- carry sound;
- change airborne movement.

Technique-generated wind follows the same environmental logic when appropriate.

## 4.17.26 Rain

Rain may:
- reduce fire spread;
- increase surface moisture;
- affect visibility;
- change electrical conductivity;
- create mud.

Rain should not simply grant elemental bonuses.

## 4.17.27 Heat and Cold Environments

Extreme environment may affect:
- fatigue;
- equipment;
- visibility;
- movement;
- medical stability.

These effects belong partly to 4.13 and later medical systems.

## 4.17.28 Environmental Hazards Have Sources

A hazard should identify:
- source;
- affected area;
- severity;
- duration;
- progression;
- escape or mitigation options.

Examples:
- active fire;
- collapsing ceiling;
- toxic smoke;
- flood current;
- unstable ground.

## 4.17.29 Hazard Zones Can Move

Some hazards are dynamic.

Examples:
- spreading fire;
- moving smoke;
- floodwater;
- collapsing structure;
- rolling debris.

The battlefield state must be able to update hazard boundaries.

## 4.17.30 Collateral Damage

Combat can affect:
- civilians;
- buildings;
- infrastructure;
- animals;
- supplies;
- mission objectives.

Collateral consequences should follow actual effects rather than exist only for narrative flavor.

## 4.17.31 Friendly Infrastructure Can Matter

Destroying:
- bridges;
- hospitals;
- roads;
- water systems;
- homes

may create long-term mission or village consequences.

Those downstream effects belong to broader simulation systems.

Ruleset 4 records the physical damage accurately.

## 4.17.32 Area Attacks and Structures

Area attacks may interact with structures differently from open terrain.

Walls can:
- block;
- redirect;
- contain;
- fragment;
- collapse.

Enclosed spaces may amplify some explosive or heat effects.

## 4.17.33 Cover Can Be Destroyed

Cover should not remain effective after it is physically compromised.

A wall may transition from:
- solid cover;
- damaged cover;
- breached;
- collapsed.

The battlefield should update accordingly.

## 4.17.34 Terrain Can Be Used Defensively

Characters may deliberately:
- collapse a passage;
- raise earth barriers;
- flood a corridor;
- cut down trees;
- destroy bridges.

The tactical value comes from the new environment.

## 4.17.35 Terrain Can Be Used Offensively

Characters may:
- drop structures on opponents;
- trigger landslides;
- ignite buildings;
- flood enclosed areas;
- destroy footing.

This should be resolved through ordinary environmental and damage rules.

## 4.17.36 Chain Reactions

Environmental damage may trigger secondary effects.

Examples:
- fire reaches explosives;
- broken support collapses a roof;
- water contacts electrical hazard;
- falling debris ruptures another structure.

Chain reactions should only occur when physically or technique-specifically justified.

## 4.17.37 Structural Traps

Prepared environments may include:
- weakened floors;
- rigged supports;
- explosive charges;
- collapsible bridges;
- concealed pits.

Ruleset 2 handles detection.
Ruleset 4 handles the physical consequence.

## 4.17.38 Destruction Scale

The system should recognize broad scale differences.

Examples:
- handheld weapon;
- human-scale jutsu;
- room-scale;
- building-scale;
- city-block-scale;
- larger strategic-scale effects.

A low-scale attack should not casually destroy high-scale structures without a specific vulnerability.

## 4.17.39 Precision Destruction

A smaller attack may still destroy a large structure if it targets a critical weak point.

This should require:
- knowledge;
- access;
- sufficient localized effect.

This allows tactical engineering without ignoring material reality.

## 4.17.40 Reinforced Structures

Some structures may be:
- fortified;
- chakra-reinforced;
- sealed;
- specially constructed.

Their protection should be represented through the actual mechanism.

## 4.17.41 Barriers and Constructed Terrain

Jutsu-created barriers, walls, domes, and similar constructs should define:
- material/effect;
- thickness or effective resilience;
- duration;
- regeneration if any;
- failure conditions.

Ruleset 3 defines creation and chakra behavior.
Ruleset 4 handles physical interaction and battlefield consequence.

## 4.17.42 Persistent Destruction

Destroyed terrain should not reset after combat.

A collapsed house remains collapsed.
A crater remains.
A burned forest remains damaged.

Long-term repair belongs to world simulation.

## 4.17.43 Environmental Knowledge

Characters familiar with the area may know:
- weak structures;
- escape routes;
- hidden tunnels;
- flood risks;
- combustible zones.

Information advantage can create tactical leverage.

## 4.17.44 Hidden Structural Weakness

The engine may know:
- a beam is already cracked;
- a bridge support is weak;
- a wall is hollow.

Characters only know this if they can perceive or infer it.

## 4.17.45 Environmental Damage Record

A consequential environmental change should be able to store:
- location;
- object/terrain affected;
- material;
- damage mechanism;
- structural condition;
- hazards created;
- movement changes;
- cover changes;
- line-of-sight changes;
- persistence;
- repairability if relevant.

## 4.17.46 Suggested Structural Resolution Pipeline

1. Identify object/terrain and material.
2. Identify attack mechanism and scale.
3. Determine contact area and location.
4. Apply material/construction resistance.
5. Determine local damage.
6. Check whether critical supports or functions were affected.
7. Update structural condition.
8. Generate debris, fire, flooding, collapse, or other hazards if justified.
9. Update battlefield routes, cover, and line of sight.
10. Persist the environmental change.

## 4.17.47 Compression

For ordinary environmental interaction, the simulation may summarize:
- wall breached;
- room burning;
- bridge compromised;
- trees knocked down;
- corridor flooded.

The system should zoom in when:
- collapse timing matters;
- people are trapped;
- escape routes depend on structural state;
- precise destruction is part of the objective.

## Core Design Rule

The environment should be treated as **persistent physical state that can protect, obstruct, injure, collapse, burn, flood, and change the tactical problem**.

Environmental destruction should be detailed only when it changes decisions, safety, or future world state.
