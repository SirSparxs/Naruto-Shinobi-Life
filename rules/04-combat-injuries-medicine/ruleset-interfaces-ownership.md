# 4.31 — Ruleset Interfaces & Ownership

Status: Provisional design section pending explicit approval.

This section defines ownership boundaries between Ruleset 4 and the other core systems.

Its purpose is to prevent:
- duplicate mechanics;
- contradictory resolution rules;
- hidden exceptions;
- scope creep;
- the same concept being tracked in several places;
- special abilities bypassing foundational systems without explicit justification.

The governing rule is:
**Each mechanic should have one primary owner. Other rulesets may reference or modify it, but should not silently recreate it.**

## 4.31.1 Ruleset Ownership

A ruleset “owns” a mechanic when it defines:
- what the mechanic represents;
- how it is structured;
- what state it stores;
- how it normally changes.

Other systems may:
- provide inputs;
- impose modifiers;
- consume outputs;
- create exceptions through explicit abilities.

They should not redefine the underlying mechanic.

## 4.31.2 Ruleset 1 Owns Character Capability

Ruleset 1 owns:
- core attributes;
- skills;
- mastery;
- prerequisites;
- training;
- growth;
- potential;
- capability progression.

Ruleset 4 may ask:
- how strong is the character?
- how skilled are they with a weapon?
- what is their medical skill?
- what is their grappling skill?

It should not define a second attribute or skill progression system.

## 4.31.3 Ruleset 1 Attributes Used by Ruleset 4

Ruleset 4 may consume:
- Agility;
- Intelligence;
- Strength;
- Endurance;
- Perception;
- Willpower;
- Chakra.

Examples:
- Strength influences force and grappling.
- Endurance influences sustained exertion.
- Perception supports threat recognition.
- Willpower affects persistence through pain or stress.
- Chakra may influence reserve-related or physiology-linked mechanics as defined elsewhere.

Ruleset 4 does not redefine what these attributes mean.

## 4.31.4 Derived Combat Capability Is Not a New Attribute

Ruleset 4 may derive summaries such as:
- combat readiness;
- reaction capability;
- mobility;
- current functional capacity.

These are convenience states derived from:
- attributes;
- skills;
- injuries;
- fatigue;
- position;
- conditions.

They should not become permanent parallel attributes.

## 4.31.5 Ruleset 1 Owns Skill Progression

Examples of skills relevant to Ruleset 4 may include:
- taijutsu;
- weapon skills;
- grappling;
- first aid;
- medical diagnosis;
- medical ninjutsu;
- surgery;
- toxicology;
- field medicine.

Ruleset 4 defines what those skills can accomplish in combat or medicine.
Ruleset 1 defines how the skills are learned and improved.

## 4.31.6 Ruleset 2 Owns Uncertainty and Resolution

Ruleset 2 owns:
- difficulty;
- opposed actions;
- uncertainty;
- probability;
- degrees of outcome;
- hidden resolution;
- information-dependent resolution.

Ruleset 4 determines:
- what is being attempted;
- what consequences are physically possible;
- what state changes result.

Ruleset 2 determines uncertain success or quality where needed.

## 4.31.7 Ruleset 4 Should Not Invent Separate Combat Dice

Combat does not need its own unrelated probability engine.

An attack, defense, diagnosis, treatment, restraint attempt, or escape uses Ruleset 2 when uncertainty is genuine.

Ruleset 4 supplies the combat-specific context.

## 4.31.8 Deterministic Combat Outcomes Are Allowed

If an outcome is effectively certain, Ruleset 2 may not require a roll.

Examples:
- overwhelming force breaks fragile restraint;
- unconscious unguarded target can be securely bound;
- trivial injury is treated by an elite medic under ideal conditions.

Ruleset 4 should not force probability merely because combat or medicine is involved.

## 4.31.9 Outcome Degree Feeds Consequence Quality

Ruleset 2 may output:
- failure;
- partial success;
- strong success;
- exceptional success;
- another context-appropriate degree.

Ruleset 4 converts that into:
- miss/contact quality;
- defense quality;
- treatment quality;
- control gained;
- diagnostic confidence.

The exact physical consequence remains bounded by what the action could plausibly accomplish.

## 4.31.10 Ruleset 2 Cannot Override Physical Limits

Exceptional resolution cannot:
- make an incapable technique regenerate a limb;
- make an ordinary bandage stop inaccessible internal bleeding;
- let a normal weapon cut through physically impossible material without mechanism.

Probability resolves uncertainty inside the action's possible range.

It does not create new capabilities.

## 4.31.11 Ruleset 2 Owns Information Uncertainty

Ruleset 4 frequently creates hidden state:
- internal injury;
- concealed weapon;
- hidden poison;
- uncertain enemy condition.

Ruleset 2 governs whether characters:
- notice;
- diagnose;
- infer;
- identify;
- misunderstand

that information.

Ruleset 4 preserves the underlying truth.

## 4.31.12 Ruleset 3 Owns Chakra

Ruleset 3 owns:
- chakra reserves;
- chakra generation/recovery;
- Chakra Control;
- chakra output;
- nature transformation;
- jutsu structure;
- jutsu costs;
- special abilities;
- sealing mechanics;
- technique mastery where defined there.

Ruleset 4 should consume those outputs rather than recreate them.

## 4.31.13 Ruleset 4 Owns Physical Consequences of Jutsu

Ruleset 3 answers:
**What does this technique create or attempt to do?**

Ruleset 4 answers:
**What happens when that effect reaches a body, object, or battlefield?**

Example:
Ruleset 3 defines a Fire Release technique's:
- output;
- shape;
- range;
- chakra cost.

Ruleset 4 determines:
- exposure;
- burns;
- ignition;
- smoke;
- structural damage;
- environmental persistence.

## 4.31.14 Ruleset 3 Owns Technique Requirements

Ruleset 3 defines whether a technique requires:
- hand seals;
- concentration;
- touch;
- line of sight;
- chakra nature;
- minimum control;
- specific anatomy.

Ruleset 4 tracks whether combat conditions allow those requirements to be fulfilled.

## 4.31.15 Ruleset 4 Owns Interruption Consequences

If a technique can be interrupted, Ruleset 3 defines the technique's relevant requirements and behavior.

Ruleset 4 determines whether:
- timing;
- injury;
- restraint;
- movement;
- pressure

actually interrupts execution.

The technique record may specify what interruption does.

## 4.31.16 Ruleset 3 Owns Special Ability Mechanisms

Examples:
- dōjutsu;
- transformations;
- regeneration techniques;
- chakra cloaks;
- summoning;
- clones;
- seals.

Ruleset 4 applies their defined mechanisms to:
- attack/defense;
- injury;
- physiology;
- environment;
- medicine.

A special ability should not receive vague combat privileges beyond its explicit mechanism.

## 4.31.17 Ruleset 4 Owns Combat Consequence

Ruleset 4 owns:
- combat flow;
- initiative/tempo interaction;
- tactical position;
- attack-defense interaction;
- hit quality;
- physical exposure;
- injury;
- bleeding;
- shock;
- incapacitation;
- death;
- fatigue;
- combat conditions;
- restraint;
- equipment damage;
- structural damage;
- medical stabilization;
- recovery consequences.

This is the primary boundary of Ruleset 4.

## 4.31.18 Combat Flow Does Not Own General Time

Ruleset 4 tracks time when:
- action windows;
- deterioration;
- fatigue;
- treatment;
- hazards

depend on it.

A broader time/calendar system should own:
- dates;
- schedules;
- age progression;
- long-term world timing.

Ruleset 4 consumes elapsed time.

## 4.31.19 Ruleset 4 Does Not Own General Inventory

Ruleset 4 defines combat-relevant properties and damage for:
- weapons;
- armor;
- medical gear;
- capture tools.

A future inventory/equipment system should own:
- storage;
- carrying;
- purchasing;
- crafting ownership;
- general item records.

Ruleset 4 reads the relevant item properties.

## 4.31.20 Ruleset 4 Does Not Own Crafting

Ruleset 4 may define the resulting functional profile of:
- poison;
- weapon;
- armor;
- medical supply.

A future crafting system should own:
- recipes;
- materials;
- crafting time;
- manufacturing quality.

## 4.31.21 Ruleset 4 Does Not Own Economy

Ruleset 4 may create:
- damaged equipment;
- medical bills;
- supply consumption;
- repair needs.

A future economic system should determine:
- prices;
- wages;
- reimbursement;
- resource scarcity at market level.

## 4.31.22 Ruleset 4 Does Not Own Mission Structure

Ruleset 4 records:
- objective achieved;
- target escaped;
- prisoner captured;
- casualties;
- collateral damage.

A mission system should own:
- mission generation;
- rank;
- employer;
- objectives;
- rewards;
- evaluation;
- consequences.

Combat victory and mission success remain separate.

## 4.31.23 Ruleset 4 Does Not Own Reputation or Politics

Combat may produce facts such as:
- civilian casualties;
- destroyed infrastructure;
- enemy captured;
- treaty violation witnessed.

Future social/political systems determine:
- reputation;
- diplomatic consequences;
- legal consequences;
- faction reaction.

Ruleset 4 supplies the facts.

## 4.31.24 Ruleset 4 Does Not Own Personality or Morale as General Systems

Characters may:
- surrender;
- panic;
- persist;
- retreat.

Ruleset 4 can represent the tactical consequences.

A broader character/psychology system should determine:
- motives;
- fear tendencies;
- loyalty;
- trauma;
- values.

Do not create universal morale bars solely inside combat unless a later ruleset explicitly establishes one.

## 4.31.25 Willpower Is Not a Morale Meter

Willpower may influence:
- pain tolerance;
- persistence;
- concentration;
- resistance to some mental pressures.

It does not automatically decide:
- loyalty;
- courage;
- surrender;
- ideology.

Those require context and character state.

## 4.31.26 Ruleset 4 Does Not Own Social Interaction

Negotiation, intimidation, deception, interrogation, and persuasion may affect:
- surrender;
- cooperation;
- prisoner behavior.

Their general resolution should belong to Ruleset 2 plus future social systems.

Ruleset 4 applies the resulting tactical state.

## 4.31.27 Ruleset 4 Does Not Own Long-Term Psychology

Severe combat may create triggers for:
- grief;
- fear;
- trauma;
- confidence changes.

Ruleset 4 records the event.
Future psychological systems determine the long-term mental outcome.

Avoid automatically assigning psychological disorders from injury severity alone.

## 4.31.28 Ruleset 4 Does Not Own World Simulation

Combat aftermath may create:
- destroyed bridge;
- dead commander;
- contaminated district;
- escaped enemy.

A future world simulation system determines:
- rebuilding;
- faction response;
- population changes;
- strategic consequences.

Ruleset 4 ensures the initiating state is preserved.

## 4.31.29 Ruleset 4 Does Not Own AI Decision-Making

Ruleset 4 defines:
- legal actions;
- risks;
- consequences;
- tactical information.

An NPC decision system should determine what an NPC chooses based on:
- goals;
- personality;
- orders;
- knowledge;
- training;
- self-preservation.

The player chooses player-character actions when they have agency.

## 4.31.30 AI Should Use Ruleset 4 State

NPC tactical decisions may consider:
- injury;
- fatigue;
- chakra;
- position;
- ally state;
- medical danger;
- escape routes;
- objective.

The AI should not receive information its character does not know.

## 4.31.31 Ruleset 4 Does Not Own Canon Lore

A lore/world database should determine:
- village institutions;
- known characters;
- clans;
- historical events;
- geography;
- established abilities.

Ruleset 4 determines how those things behave mechanically when combat or medicine occurs.

## 4.31.32 Canon and Custom Content Use the Same Interfaces

A canon jutsu and a custom jutsu should both provide the same kinds of relevant inputs:
- mechanism;
- output;
- range;
- duration;
- requirements;
- limits.

Ruleset 4 should not need a special “canon exception” mode.

## 4.31.33 Future Rulesets Should Declare Ownership Explicitly

Every future ruleset should state:
- what it owns;
- what it reads from prior systems;
- what outputs it provides;
- what it deliberately does not own.

This should become a project-wide design standard.

## 4.31.34 Shared Terms Need One Canonical Definition

Terms such as:
- injury;
- fatigue;
- chakra control;
- mastery;
- difficulty;
- condition;
- incapacitation

should have one canonical meaning.

Other rulesets should link to that meaning rather than redefine the term locally.

## 4.31.35 Derived States Should Not Become Duplicate Truth

Examples:
- “Combat Capacity” derives from injuries, fatigue, consciousness, function.
- “Medical State” derives from injury and deterioration.
- “Readiness” derives from several systems.

If the underlying state changes, the summary should update.

Do not separately store contradictory truth unless the summary is explicitly cached and invalidated correctly.

## 4.31.36 One Cause Can Produce Outputs in Several Systems

Example:
A severe leg injury may create:
- Ruleset 4 injury;
- reduced functional mobility;
- Ruleset 1 temporary effective limitation on skill use;
- mission restrictions;
- future social consequences.

This is not duplicate ownership if each system handles a different consequence.

## 4.31.37 Cross-System Changes Need Clear Direction

A useful rule is:

**Foundational capability → action → resolution → consequence → persistence/world reaction**

For example:
Ruleset 1 skill
→ Ruleset 3 technique
→ Ruleset 2 resolution
→ Ruleset 4 injury
→ future mission/social/world consequences.

This direction helps prevent circular mechanics.

## 4.31.38 Avoid Circular Bonuses

Do not create loops such as:
- being injured lowers combat power;
- lower combat power increases injury severity directly;
- increased injury severity further lowers combat power independent of actual injury.

Effects should arise from concrete state once.

Avoid repeatedly applying the same consequence through several rulesets.

## 4.31.39 Avoid Double-Counting Attributes

If Agility already influences:
- movement;
- reaction execution;
- hand speed where appropriate,

do not add another hidden “combat speed” stat that simply repeats Agility unless it is a justified derived value.

Derived values should clarify, not multiply, the same advantage.

## 4.31.40 Avoid Double-Counting Skill

If weapon mastery already influences attack execution, do not separately add:
- weapon skill bonus;
- mastery bonus;
- experience bonus

for the same underlying capability unless they represent genuinely distinct factors.

## 4.31.41 Avoid Double-Counting Injury

A broken leg may:
- reduce movement;
- impair balance;
- increase pain.

Do not also apply a generic “Severe Injury -30% All Actions” unless the injury genuinely affects those actions.

Specific consequences are preferred.

## 4.31.42 Special Abilities Must Declare Interfaces

A new ability should state:
- which rules it modifies;
- which normal rules still apply;
- whether it introduces new persistent state;
- how it interacts with injury;
- what counters exist.

This prevents accidental system bypass.

## 4.31.43 Exception Hierarchy

When a specific ability explicitly conflicts with a general rule:
1. identify the general rule;
2. confirm the ability truly specifies an exception;
3. apply the narrow exception;
4. preserve all unaffected rules.

Specific exceptions should be narrow, not contagious.

## 4.31.44 Explicit Beats Inferred

If a technique explicitly says:
“this form cannot bleed while fully liquefied,”
that modifies bleeding while the form is active.

Do not infer:
“therefore it cannot suffer any internal injury, poison, or chakra disruption.”

Only the explicit mechanism changes.

## 4.31.45 Ruleset 4 Outputs

Ruleset 4 may output persistent facts such as:
- injuries;
- deaths;
- scars;
- functional limitations;
- prisoners;
- equipment damage;
- environmental destruction;
- medical restrictions;
- treatment outcomes;
- revealed combat information.

Future systems should consume these facts rather than recompute them.

## 4.31.46 Ruleset 4 Inputs

Ruleset 4 commonly consumes:
- attributes and skills from Ruleset 1;
- uncertainty/outcome degree from Ruleset 2;
- chakra and technique definitions from Ruleset 3;
- equipment/item data from future systems;
- environmental/world state;
- character goals and knowledge.

## 4.31.47 Ruleset 4 Internal State Layers

Ruleset 4 should preserve its established separation between:

### Combat Capacity
What the character can currently do in the encounter.

### Injury State
What physical structures are damaged.

### Medical State
What processes threaten health or life.

### Recovery State
How healing and rehabilitation are progressing.

### Tactical State
Position, pressure, restraint, cover, engagement.

These layers interact but should not collapse into one universal condition.

## 4.31.48 Persistent Knowledge Layer

Separate from physical state, the simulation should preserve:
- what each observer has seen;
- what each observer believes;
- diagnostic confidence;
- revealed abilities.

This interfaces strongly with Ruleset 2.

## 4.31.49 Interface Example — Fireball

1. Ruleset 1 provides user capability.
2. Ruleset 3 defines Fireball technique, chakra cost, output, range, requirements.
3. Ruleset 2 resolves uncertain execution/contact as needed.
4. Ruleset 4 resolves:
   - dodge/cover;
   - heat exposure;
   - burns;
   - ignition;
   - structural/environmental effects;
   - injury and aftermath.
5. Persistent systems record resulting state.

No ruleset needs to redefine another's job.

## 4.31.50 Interface Example — Medical Ninjutsu

1. Ruleset 1 provides medical skill/mastery and related capability.
2. Ruleset 3 defines the medical technique and chakra requirements.
3. Ruleset 4.18 identifies the medical problem.
4. Ruleset 2 resolves uncertainty when needed.
5. Ruleset 4.20 applies actual stabilization/repair.
6. Ruleset 4.22 handles recovery.
7. Ruleset 4.29 preserves the result.

## 4.31.51 Interface Example — Live Capture

1. Mission system defines “capture alive.”
2. Character/AI system chooses tactics.
3. Ruleset 1 supplies relevant skills.
4. Ruleset 2 resolves uncertain control attempts.
5. Ruleset 4.15 handles grappling/restraint.
6. Ruleset 4.25 handles nonlethal risk.
7. Ruleset 4.19 handles any necessary field care.
8. Ruleset 4.27 records capture outcome.
9. Ruleset 4.29 preserves prisoner state.

## 4.31.52 Interface Example — Regeneration

1. Ruleset 3 or physiology record defines regeneration mechanism.
2. Ruleset 4.8 determines trauma exposure.
3. Ruleset 4.10 records injury.
4. Ruleset 4.24 applies regeneration-specific modification.
5. Ruleset 4.11 still tracks blood loss unless regeneration explicitly replaces it.
6. Ruleset 4.22 handles remaining recovery.
7. Ruleset 4.29 preserves any lasting consequence.

## 4.31.53 Interface Example — Hidden Internal Injury

1. Ruleset 4 creates the true injury.
2. Ruleset 4.29 stores it canonically.
3. Ruleset 2 determines what observers detect.
4. Ruleset 4.18 converts detected signs into diagnosis/confidence.
5. Player-facing narration reveals only justified knowledge.
6. Ruleset 4.11 advances deterioration regardless of whether anyone knows the cause.

## 4.31.54 Scope-Creep Test

Before adding a new Rule 4 mechanic, ask:
- Is this specifically about combat consequence, injury, medical state, treatment, recovery, or tactical physical interaction?
- Is another ruleset already the natural owner?
- Can Ruleset 4 simply consume that system's output?

If another system owns it, add only the interface required.

## 4.31.55 Interface Documentation Standard

When adding a future mechanic that touches Ruleset 4, document:

### Owner
Which ruleset defines it?

### Inputs
What state does it read?

### Outputs
What state can it change?

### Persistence
What survives after resolution?

### Knowledge
Who can perceive or know the result?

### Exceptions
What explicit abilities modify the normal rule?

This should reduce future ambiguity.

## 4.31.56 Rules Changes Must Respect Ownership

When a problem appears during testing, modify the owning rule first.

Example:
If extreme speed breaks reaction timing:
- fix Ruleset 4.3 timing if the issue is action windows;
- fix Ruleset 1 if the underlying derived speed calculation is wrong;
- fix Ruleset 2 if probability scaling is wrong.

Do not patch the issue simultaneously in three places.

## 4.31.57 Ruleset 4 Completion Criteria

Ruleset 4 can be considered structurally complete when it can consistently answer:

- When can a character act or respond?
- Where are combatants and what options does space allow?
- What happens when attacks and defenses interact?
- What physical exposure reaches the target?
- What injury or condition results?
- Can the character continue functioning?
- Is the injury medically dangerous?
- How does it deteriorate or stabilize?
- What treatment is possible?
- How does recovery proceed?
- What state persists afterward?
- Which other ruleset owns any remaining question?

## 4.31.58 Future Refinement

Structural completion does not mean numerical or content completion.

Ruleset 4 will still need:
- benchmark testing;
- balance calibration;
- jutsu integration;
- equipment integration;
- NPC scenario testing;
- playtesting;
- revisions.

The architecture should remain stable enough that these refinements occur inside clear ownership boundaries.

## Core Design Rule

Ruleset 4 owns the **physical, tactical, injury, medical, and recovery consequences of conflict**.

It should consume capability from Ruleset 1, uncertainty from Ruleset 2, and chakra/technique behavior from Ruleset 3.

Future systems should consume Ruleset 4's persistent consequences without redefining them.

Every mechanic should have one clear home, and every exception should be explicit, narrow, and causally justified.
