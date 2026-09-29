# 4.4 — Positioning, Range & Battlefield State

Status: Provisional design section pending explicit approval.

This section defines how the simulation represents physical space, distance, engagement, cover, terrain, elevation, line of sight, movement constraints, and battlefield control.

## 4.4.1 Positioning Should Be Precise Enough to Matter, Not Precise for Its Own Sake

The simulation should track exact or approximate physical location only to the degree needed for meaningful decisions.

The system may internally use coordinates, distances, or geometry when useful, but the player-facing model should normally communicate relative tactical position.

Examples:
- adjacent;
- within striking distance;
- close;
- short range;
- medium range;
- long range;
- out of practical range;
- behind cover;
- above;
- below;
- inside a chokepoint;
- concealed;
- separated by an obstacle.

Exact measurements should be used when a technique, movement limit, or environmental hazard requires them.

## 4.4.2 Use a Hybrid Distance Model

The preferred model is hybrid:

- contextual range bands for most narration and decision-making;
- exact or estimated distance when a technique, movement contest, projectile travel time, or spatial edge case requires precision.

This preserves tactical depth without making every exchange a geometry exercise.

## 4.4.3 Suggested Contextual Range Bands

The following are descriptive categories rather than universal fixed numbers:

### Contact
Bodies are touching or grappling.

### Melee
Within immediate striking, weapon, or interception distance.

### Close
A short burst of movement can create melee contact.

### Short
Throwing weapons, short-range jutsu, rapid closing, and immediate tactical interaction are common.

### Medium
Movement and projectile timing matter noticeably.

### Long
Direct interaction may require specialized ranged techniques, significant travel time, or exceptional speed.

### Extreme
The target is outside ordinary combat reach without specialized abilities, artillery-scale jutsu, sensory support, or travel.

Individual techniques define their own actual effective ranges.

## 4.4.4 Range Is Relational

Distance alone does not determine tactical range.

The same twenty meters can feel:
- very close to a high-speed taijutsu specialist;
- moderate to an average genin;
- effectively distant to an injured civilian.

Therefore, the simulation should distinguish physical distance from practical engagement range.

## 4.4.5 Position Has Multiple Components

A combatant's tactical position may include:
- physical location;
- facing or attention where relevant;
- elevation;
- cover;
- concealment;
- footing;
- nearby obstacles;
- available escape routes;
- adjacent allies/enemies;
- hazards;
- current engagement relationships.

Not every component needs explicit tracking at all times.

## 4.4.6 Line of Sight Is Not the Same as Awareness

A target can be known without currently being visible.

Examples:
- sensed through chakra;
- heard behind a wall;
- tracked through footprints;
- known to be inside smoke;
- remembered entering a room.

Likewise, visible does not always mean clearly identified.

Ruleset 2 resolves uncertain perception. Ruleset 4 tracks whether attacks, reactions, and movement require direct visual contact.

## 4.4.7 Cover and Concealment Are Separate

### Cover
Physically blocks or mitigates attacks.

Examples:
- stone wall;
- tree trunk;
- earth barrier;
- building corner.

### Concealment
Makes detection, targeting, or tracking harder without necessarily stopping attacks.

Examples:
- smoke;
- darkness;
- foliage;
- mist;
- dust.

Something may provide both.

Cover should influence attack paths, available targeting, and physical protection.
Concealment should primarily influence information and targeting confidence.

## 4.4.8 Cover Has Direction

Cover only protects against attacks whose path intersects it.

A wall may protect against an enemy in front while providing no protection against an attacker above or behind.

Therefore, battlefield geometry matters when relevant without requiring a grid.

## 4.4.9 Elevation Matters Tactically

Elevation may affect:
- visibility;
- projectile arcs;
- cover;
- fall risk;
- movement cost;
- access routes;
- attack angles;
- concealment;
- line of sight;
- ability to disengage.

Elevation should not automatically grant a flat universal bonus.

Its advantage depends on the specific interaction.

## 4.4.10 Footing and Surface Matter

Combatants may fight on:
- stable ground;
- rooftops;
- trees;
- water;
- walls;
- ice;
- mud;
- rubble;
- narrow branches;
- unstable structures.

Surface conditions may affect:
- acceleration;
- stopping;
- turning;
- balance;
- reaction options;
- chakra control requirements;
- fall risk.

Characters trained for a surface may largely ignore penalties that would affect others.

## 4.4.11 Terrain Can Restrict Movement

Terrain may create:
- narrow lanes;
- dead ends;
- bottlenecks;
- low ceilings;
- dense obstacles;
- open ground;
- deep water;
- cliffs;
- enclosed rooms.

This affects what movement and jutsu are practical.

A powerful wide-area technique may be unusable in a confined allied space.
A large summon may not fit indoors.
A long weapon may become awkward in a narrow corridor.

## 4.4.12 Engagement Is a Tactical Relationship

Two characters are engaged when they are close enough and sufficiently focused on one another that movement or action can be directly contested.

Engagement may involve:
- melee range;
- immediate interception threat;
- active pursuit;
- control of a narrow route;
- grappling.

Being engaged does not mean movement is impossible.
It means leaving or ignoring the opponent may create an opportunity for them.

## 4.4.13 Engagement Is Not Automatically Symmetric

A fast or long-reach fighter may threaten an opponent who cannot threaten them equally.

Likewise, an injured character may be trapped inside an opponent's engagement range without having meaningful offensive control.

Therefore, the engine should track practical threat relationships rather than a binary shared "engaged" flag when needed.

## 4.4.14 Disengaging Requires Space or Disruption

A character may disengage by:
- creating distance;
- breaking line of sight;
- forcing the opponent to defend;
- using terrain;
- knocking the opponent away;
- using smoke or concealment;
- switching targets;
- receiving allied intervention;
- using a movement technique.

Simply stepping backward does not guarantee escape from a faster pursuer.

## 4.4.15 Chokepoints Create Control

Doors, hallways, bridges, narrow streets, cave passages, and similar spaces may allow a small number of characters to control access.

A character controlling a chokepoint can:
- intercept movement;
- protect allies behind them;
- restrict flanking;
- force enemies into predictable paths.

The value of a chokepoint depends on:
- width;
- terrain;
- mobility techniques;
- vertical access;
- destructive jutsu;
- teleportation or bypass abilities.

## 4.4.16 Zones of Threat Are Contextual

The system may recognize areas where entering creates immediate tactical risk.

Examples:
- sword reach;
- explosive tag radius;
- minefield;
- trap network;
- active fire;
- enemy kill zone;
- area controlled by a large summon;
- sustained jutsu field.

These are not universal grid "zones of control."
They arise from actual abilities and battlefield conditions.

## 4.4.17 Forced Movement Has Consequences

Characters may be:
- knocked back;
- thrown;
- dragged;
- pulled;
- launched;
- swept away;
- blasted upward;
- buried.

Forced movement may produce additional consequences if it causes:
- collision;
- falling;
- separation from allies;
- entry into hazards;
- loss of cover;
- broken line of sight;
- disengagement or forced engagement.

## 4.4.18 Collision Matters When Relevant

Being thrown into a wall or tree may create additional trauma.

The effect depends on:
- speed;
- distance;
- surface;
- angle;
- body control;
- defensive reinforcement.

Not every minor shove requires collision damage.

## 4.4.19 Positioning Can Create Openings

A positional disadvantage may make certain defenses harder.

Examples:
- trapped against a wall;
- airborne without mobility options;
- standing on unstable terrain;
- surrounded;
- balancing on a narrow surface;
- protecting someone behind you.

This should narrow available choices rather than automatically impose generic penalties.

## 4.4.20 Surrounding a Target Is More Than a Bonus

Multiple attackers gain value by:
- attacking from different angles;
- restricting escape;
- splitting attention;
- creating overlapping reaction demands;
- forcing poor movement choices.

A surrounded defender may still escape through speed, terrain, area attacks, substitution, or tactical skill.

The system should resolve the actual spatial problem rather than apply a universal "surrounded" modifier.

## 4.4.21 Battlefield Control Can Be Created Deliberately

Characters can alter space through:
- fire;
- water;
- earth walls;
- traps;
- smoke;
- explosive tags;
- summoned creatures;
- wires;
- ice;
- poison clouds;
- collapsing terrain.

These effects can:
- deny routes;
- funnel movement;
- separate teams;
- create cover;
- destroy cover;
- force repositioning;
- restrict vision.

Battlefield control is therefore often as valuable as direct damage.

## 4.4.22 Terrain Is Mutable

Naruto combat frequently changes the battlefield.

The system must allow:
- trees to fall;
- walls to collapse;
- craters to form;
- water levels to change;
- fire to spread;
- structures to break;
- earthworks to appear;
- cover to be destroyed.

Battlefield state should update persistently as terrain changes.

## 4.4.23 Destruction Scale Must Match Technique Scale

A technique capable of destroying a building should not leave ordinary cover intact simply because the cover had a generic defensive value.

Likewise, a weak attack should not casually destroy reinforced structures.

Structural consequences should follow technique output, material, and impact.

Detailed structure rules can remain lightweight unless destruction becomes central to the encounter.

## 4.4.24 Vertical Combat Is Fully Supported

The battlefield is three-dimensional.

Characters may fight:
- on walls;
- across rooftops;
- in trees;
- underwater;
- underground;
- while airborne;
- on summoned creatures.

Positioning rules must not assume flat ground.

## 4.4.25 Airborne State Matters

A character in the air may have:
- limited directional options;
- increased visibility;
- fall risk;
- reduced cover;
- greater attack angle;
- access to aerial mobility techniques.

Airborne characters with flight or equivalent control function differently from characters merely jumping.

## 4.4.26 Water and Wall Movement Interact With Chakra Control

Tree walking, water walking, wall movement, and similar chakra-assisted positioning should rely on the relevant Ruleset 3 chakra-control mechanics.

Ruleset 4 determines the tactical benefits and consequences of occupying those positions.

## 4.4.27 Obstruction Can Affect Jutsu

Terrain may:
- block projectile techniques;
- interfere with line-based attacks;
- contain explosions;
- redirect water;
- spread fire;
- conduct electricity;
- provide material for earth techniques.

Jutsu descriptions define specific behavior; Ruleset 4 supplies the battlefield context.

## 4.4.28 Friendly Positioning Matters

Allies can obstruct one another.

Poor positioning can cause:
- blocked firing lines;
- friendly-fire risk;
- restricted movement;
- inability to use area techniques;
- difficulty protecting wounded allies.

Good formation can provide:
- mutual protection;
- layered interception;
- safe retreat routes;
- coordinated attack angles.

## 4.4.29 Exact Distance Becomes Mandatory Only When It Changes the Outcome

The simulation should switch from relative range to explicit distance when needed for:
- technique maximum range;
- movement race;
- explosive radius;
- fall height;
- projectile timing;
- chase resolution;
- environmental hazard boundary;
- teleportation limit;
- similar thresholds.

After the precise question is resolved, the system may return to contextual range.

## 4.4.30 Hidden Spatial State

The engine may know more about the battlefield than the player character.

Examples:
- a hidden enemy behind a wall;
- an underground tunnel;
- a trap ten meters ahead;
- an unseen sniper angle;
- concealed explosive tags.

The player receives only spatial information their character can reasonably perceive or infer.

## 4.4.31 Minimum Battlefield State

For detailed combat, the engine should be able to represent:
- approximate or exact positions;
- relative range;
- elevation;
- line of sight;
- cover;
- concealment;
- major obstacles;
- hazards;
- engagement/threat relationships;
- escape routes;
- terrain changes;
- hidden spatial information.

## Core Design Rule

Positioning matters when it changes what characters can perceive, reach, defend against, escape from, or safely attempt.

The system should model enough space to support tactical decisions without requiring constant grid-level measurement.
