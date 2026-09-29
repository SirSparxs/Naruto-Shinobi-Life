# 4.28 — Combat Abstraction & Simulation Compression

Status: Provisional design section pending explicit approval.

This section defines how the simulation can resolve combat at different levels of detail without changing the underlying rules.

The system must support:
- detailed player combat;
- routine encounters;
- background NPC fights;
- large battles;
- travel-time danger;
- medical and aftermath compression;
- later reconstruction of important events.

The governing rule is:
**Compression removes unnecessary detail, not causality.**

## 4.28.1 One Ruleset, Multiple Levels of Detail

The simulation should not have:
- one “real” combat system for the player;
- a completely different random system for NPCs.

Instead, the same underlying concepts remain:
- capability;
- timing;
- positioning;
- attacks and defenses;
- damage mechanisms;
- injury;
- fatigue;
- chakra;
- medical deterioration.

Only the amount of explicit resolution changes.

## 4.28.2 Detail Should Follow Decision Relevance

The engine should zoom in when:
- player decisions matter;
- several plausible outcomes exist;
- timing matters;
- injury details matter;
- hidden information matters;
- rescue or capture is possible;
- resource expenditure matters.

The engine should compress when:
- outcome is overwhelmingly predictable;
- participants greatly outclass opposition;
- no meaningful player decision exists;
- detailed intermediate actions would not affect future state.

## 4.28.3 Suggested Resolution Scales

Useful broad scales may include:

### Moment-to-Moment
Individual actions, reactions, timing, positioning, hit quality, and injuries are explicitly resolved.

### Exchange
Several tightly related actions are compressed into one tactical exchange.

### Engagement
A portion of combat between specific opponents or groups resolves as a coherent sequence.

### Encounter
An entire routine fight may resolve with only major turning points and consequences.

### Strategic / Background
Large or distant conflicts resolve through capability, objectives, resources, environment, and major events.

These are simulation zoom levels, not separate mechanics.

## 4.28.4 Moment-to-Moment Resolution

Use detailed resolution when:
- player character is directly involved;
- a decisive attack is occurring;
- an injury may permanently matter;
- a rescue window is narrow;
- unusual jutsu interactions occur;
- exact positioning changes options.

This is the highest-cost resolution mode.

## 4.28.5 Exchange-Level Resolution

An exchange may summarize:
- approach;
- attack;
- defense;
- counter;
- positional result.

Example:
“After several rapid clashes, A forces B backward and opens a shallow cut on the forearm.”

The engine may still internally determine:
- relative capability;
- fatigue;
- jutsu expenditure;
- injury significance.

## 4.28.6 Engagement-Level Resolution

An engagement may summarize a longer contest between:
- two combatants;
- squad elements;
- one specialist and several minor opponents.

Important outputs may include:
- who gained control;
- meaningful injuries;
- chakra/fatigue expenditure;
- position;
- objective progress.

## 4.28.7 Encounter-Level Resolution

A routine encounter may resolve through:
- initial conditions;
- power disparity;
- tactical context;
- objective;
- major resource cost;
- casualty risk.

The result should still produce persistent consequences.

## 4.28.8 Strategic / Background Resolution

Distant or large conflicts may be resolved using:
- participating forces;
- command;
- terrain;
- preparation;
- intelligence;
- morale/discipline where applicable;
- medical support;
- logistics;
- major techniques;
- objectives.

The system should output:
- casualties;
- injuries;
- resource loss;
- territory/objective changes;
- surviving important actors;
- major revealed information.

## 4.28.9 Compression Should Preserve Significant Events

Even in highly compressed combat, the engine should explicitly surface events such as:
- death of a named character;
- permanent injury;
- capture;
- major jutsu reveal;
- destruction of important infrastructure;
- mission-objective change;
- severe resource depletion.

These events should never disappear inside a generic summary.

## 4.28.10 Named and Persistent Characters Deserve More State

Important persistent characters should retain:
- injuries;
- chakra/resource expenditure;
- equipment loss;
- knowledge gained;
- medical state;
- survival.

This does not mean they always require detailed action-by-action simulation.

## 4.28.11 Minor NPCs Can Use Aggregated State

Unnamed or low-persistence NPCs may be represented with broader state such as:
- combat-ready;
- pressured;
- injured;
- incapacitated;
- dead;
- routed.

If one becomes narratively or mechanically important, the simulation can expand their record.

## 4.28.12 Power Disparity Enables Compression

When capability difference is overwhelming and no special factor interferes, the engine can resolve quickly.

Examples:
- elite Jōnin restraining an untrained civilian;
- high-rank shinobi defeating trivial wildlife;
- specialist medic treating a routine minor wound.

Compression should not create uncertainty where little exists.

## 4.28.13 Overwhelming Advantage Is Not Absolute

Before compressing, the engine should still check for:
- ambush;
- hidden weapon;
- poison;
- hostage;
- trap;
- environmental hazard;
- unusual physiology;
- hard counter;
- mission restriction.

A seemingly trivial opponent can still matter if context creates a real threat.

## 4.28.14 Compression Should Not Ignore Objectives

A stronger side may win the fight while failing the objective.

Therefore compressed resolution must still ask:
- what was each side trying to achieve;
- what counted as success;
- whether retreat, delay, escape, or capture mattered.

## 4.28.15 Background NPCs Follow Player-Parity Rules

An off-screen NPC does not:
- automatically survive because important;
- automatically lose because minor;
- receive hidden narrative protection.

Their outcomes derive from the same world logic.

## 4.28.16 No Arbitrary Off-Screen Death Rolls

A persistent character should not die simply because:
“Background combat was dangerous.”

The engine should establish:
- actual exposure;
- opposition;
- injury mechanism;
- medical access;
- timing.

Compression can summarize the process but must retain causal justification.

## 4.28.17 Probability Still Comes From Ruleset 2

Compression should not replace the probability system.

Ruleset 2 still determines uncertain outcomes.

Compression changes:
- how many intermediate resolutions are made;
- what information is surfaced.

## 4.28.18 Aggregate Rather Than Repeated Micro-Rolls

A long low-detail engagement should usually not perform:
- hundreds of individual attack rolls.

Instead, it may resolve:
- control of the exchange;
- accumulated pressure;
- meaningful breakthrough points;
- final consequences.

This reduces noise and extreme random drift.

## 4.28.19 Avoid Random-Walk Distortion

Repeated low-stakes rolls can produce implausible results through accumulated randomness.

Compression should favor:
- expected capability;
- tactical context;
- a smaller number of meaningful uncertainty points.

This keeps strong capability differences stable.

## 4.28.20 Zoom In at Decision Boundaries

A compressed scene should expand when:
- the player can intervene;
- a character becomes critically injured;
- someone attempts escape;
- a powerful technique begins;
- a hidden threat appears;
- the objective changes.

The simulation may shift scale mid-encounter.

## 4.28.21 Zoom Out After Resolution Becomes Predictable

Detailed combat can compress again when:
- remaining enemies are helpless;
- retreat is uncontested;
- rescue is secured;
- only routine cleanup remains.

Do not continue expensive simulation after meaningful uncertainty ends.

## 4.28.22 Scale Changes Must Preserve State

When zooming in or out, preserve:
- exact meaningful injuries;
- position at useful resolution;
- chakra;
- fatigue;
- conditions;
- equipment;
- hazards;
- knowledge.

Changing detail level must not reset or reinterpret established facts.

## 4.28.23 Broad Position Can Expand Into Detailed Position

A compressed battle may store:
“B is holding the eastern street.”

If the player enters that location, the engine can expand into:
- nearby cover;
- building positions;
- opponents;
- hazards.

The detailed state should be consistent with the prior summary.

## 4.28.24 Compression Should Avoid False Precision

If the simulation only resolved a background fight broadly, it should not later invent exact unsupported details such as:
“the third kunai cut the left biceps at 14:03.”

Store only the precision actually generated.

## 4.28.25 Preserve Uncertainty

If an off-screen battle's exact details are unknown to the player, they should remain unknown.

The engine may know:
- who survived;
- injuries;
- major events.

The player may only hear:
“the patrol took heavy casualties.”

## 4.28.26 Retrospective Expansion Has Limits

A later investigation may reconstruct more detail through:
- witnesses;
- evidence;
- medical findings.

But the system should not pretend that ungenerated micro-events were always known with certainty.

## 4.28.27 Large Battles Need Unit-Level Abstraction

Large conflicts may group ordinary fighters into:
- squads;
- platoons;
- units;
- fronts;
- defensive positions.

Named characters and decisive specialists can remain individually modeled.

This creates mixed-resolution battles.

## 4.28.28 Mixed-Resolution Combat

One battle may simultaneously contain:
- detailed duel between important characters;
- squad-level fighting nearby;
- abstract distant fighting.

These layers should influence each other through:
- reinforcements;
- terrain changes;
- casualties;
- objective shifts;
- information.

## 4.28.29 Named Character Intersections Trigger Detail

If two important persistent characters directly engage, the engine may increase resolution detail automatically.

This is especially appropriate when:
- permanent injury;
- capture;
- death;
- secret ability exposure

could result.

## 4.28.30 Mass Casualties Can Be Aggregated

For large anonymous groups, casualty outputs may be summarized:
- lightly wounded;
- seriously wounded;
- incapacitated;
- dead;
- missing.

The engine should avoid creating hundreds of unnecessary individual injury records unless those characters become persistent.

## 4.28.31 Medical Compression

Routine treatment can be compressed when:
- diagnosis is known;
- care is available;
- practitioner skill is sufficient;
- no complication is likely.

Medical detail should expand when:
- survival is uncertain;
- treatment resources are scarce;
- compatibility matters;
- surgery is high-risk;
- player choice matters.

## 4.28.32 Recovery Compression

Long recovery periods can advance by:
- daily;
- weekly;
- milestone

updates.

The engine should interrupt compression for:
- complication;
- medical clearance;
- reinjury;
- major rehabilitation choice.

## 4.28.33 Travel Compression

Travel can usually be compressed while preserving:
- elapsed time;
- fatigue;
- chakra recovery;
- injury progression;
- weather;
- supplies.

If a meaningful threat appears, the simulation zooms in.

## 4.28.34 Repeated Routine Tasks

Repeated low-risk actions may be aggregated.

Examples:
- standard patrol;
- ordinary training spar;
- routine wound care.

If conditions change, detail increases.

## 4.28.35 Compression Should Respect Resource Consumption

Even when actions are summarized, the engine should still account for meaningful:
- chakra;
- ammunition;
- medical supplies;
- fatigue;
- equipment wear.

Do not grant free resources because events occurred off-screen.

## 4.28.36 Compression Should Respect Time

A compressed fight still consumes time.

A ten-minute engagement should:
- advance poison;
- advance bleeding;
- affect reinforcements;
- alter travel schedules.

Time remains real.

## 4.28.37 Compression Should Respect Environmental Change

Large techniques used in compressed combat may still create:
- craters;
- fires;
- collapsed structures;
- flooding.

Environmental consequences must persist.

## 4.28.38 Compression and Hidden Rolls

The engine may use hidden uncertainty resolution where appropriate.

However, it should preserve:
- result;
- consequence;
- relevant hidden state

so later scenes remain consistent.

The exact roll itself need not always be exposed.

## 4.28.39 Deterministic Resolution Is Allowed

If capability and context make an outcome effectively certain, no roll is required.

Examples:
- unconscious civilian being tied securely;
- trivial routine treatment by an elite medic;
- overwhelming strength breaking fragile restraint.

This applies equally in detailed and compressed simulation.

## 4.28.40 Background Conflict Should Advance Without Player Observation

The world may contain conflicts the player never sees.

These should still:
- consume time;
- produce casualties;
- alter territory;
- reveal information;
- affect future NPC availability.

The simulation does not freeze outside the player's current scene.

## 4.28.41 Background Events Need Relevance Filtering

Not every distant fight deserves a full stored record.

Persist events when they affect:
- named characters;
- factions;
- locations;
- mission availability;
- resources;
- world state.

Trivial irrelevant conflicts may be discarded after aggregate world effects are applied.

## 4.28.42 Summary Quality Should Match Importance

A trivial encounter may need one sentence.

A major compressed battle may need:
- key phases;
- turning points;
- casualties;
- objective result;
- notable reveals.

Compression affects mechanical detail, not necessarily narrative significance.

## 4.28.43 Player-Facing Detail and Engine Detail Can Differ

The engine may internally track:
- injuries;
- resource loss;
- hidden reinforcements.

The player-facing narration should show only:
- what their character can perceive;
- what matters to the current decision.

This prevents information overload.

## 4.28.44 Simulation Budget Should Go to Consequential Uncertainty

The most detail should be spent on questions such as:
- Does this attack land?
- Can the medic stabilize the casualty?
- Does the target escape?
- Does the structure collapse?
- Does the secret technique get revealed?

Not:
- the exact trajectory of every irrelevant shuriken.

## 4.28.45 Compression Is Not Railroading

The engine should not compress away meaningful player agency.

If a player could reasonably choose:
- a different tactic;
- rescue;
- retreat;
- capture;
- spend a resource

then the simulation should pause or zoom in before deciding for them.

## 4.28.46 Player-Controlled Characters Receive Decision Windows

When the player character is directly involved, compression may summarize routine execution but should surface meaningful decision points.

Do not auto-resolve:
- irreversible choices;
- high-risk commitments;
- major resource spending;
- permanent injury risk

without giving the player the relevant opportunity to act when their character would have one.

## 4.28.47 NPC Autonomy Remains Intact

NPCs make decisions according to:
- goals;
- personality;
- knowledge;
- training;
- command;
- fear;
- self-preservation.

Compression may summarize those decisions but should not reduce NPCs to passive probability objects.

## 4.28.48 Compression Level Can Be Contextual Per Participant

The player may receive detailed resolution for:
- their own duel

while an allied squad nearby is resolved at engagement scale.

If the two situations intersect, detail can merge.

## 4.28.49 Combat Summary Record

A compressed encounter should preserve enough state to support continuity.

Possible fields:
- participants or units;
- objectives;
- start/end time;
- location;
- broad tactical progression;
- resource expenditure;
- injuries/casualties;
- deaths;
- captures;
- escapees;
- major techniques;
- environmental changes;
- mission outcome;
- unresolved consequences.

## 4.28.50 Expansion Trigger Record

For long-running simulations, the engine may note triggers such as:
- named character endangered;
- player can intervene;
- critical injury;
- major jutsu use;
- objective threatened.

These triggers indicate when compression should stop.

## 4.28.51 Suggested Compression Pipeline

1. Determine current simulation relevance.
2. Identify meaningful decision points.
3. Select the lowest detail level that preserves those decisions.
4. Establish participants, goals, capability, terrain, and resources.
5. Resolve only consequential uncertainty.
6. Aggregate routine actions.
7. Preserve injuries, resource costs, environmental changes, and information.
8. Check whether an expansion trigger occurs.
9. Zoom in if needed.
10. Otherwise produce a concise outcome and persist state.

## 4.28.52 Calibration Rule

If two resolution scales applied to the same scenario repeatedly produce substantially different outcome tendencies, the abstraction is miscalibrated.

Compressed resolution should approximate the same:
- win likelihood;
- casualty severity;
- resource use;
- objective success

that detailed resolution would produce over many comparable cases.

## 4.28.53 Compression Bias Must Be Avoided

The system should test for biases such as:
- compressed fights being too lethal;
- important NPCs surviving more often;
- stronger characters losing too frequently;
- resources being undercounted;
- capture being unrealistically easy.

These belong to 4.30 calibration testing.

## Core Design Rule

Simulation compression should preserve:
**causes, meaningful uncertainty, persistent consequences, player agency, and world continuity**

while removing:
**irrelevant micro-actions, redundant rolls, and detail that cannot affect the outcome.**

The engine should always use the lowest-cost level of detail that still preserves the decisions and consequences that matter.
