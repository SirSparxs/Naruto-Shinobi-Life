# 4.29 — Persistent Combat & Medical State

Status: Provisional design section pending explicit approval.

This section defines which combat, injury, medical, equipment, environmental, and information states must persist beyond the immediate encounter.

Persistent state exists so that:
- injuries remain after combat;
- treatment history matters;
- scars and permanent damage remain;
- equipment stays damaged;
- hidden diagnoses remain hidden;
- different characters can hold different beliefs about the same event;
- time skips advance rather than erase consequences;
- save/load does not rewrite established facts.

The governing rule is:
**If a fact can affect future decisions or outcomes, it should persist until something actually changes it.**

## 4.29.1 Persistence Is State Continuity

Combat does not end the existence of:
- wounds;
- missing anatomy;
- chronic conditions;
- fatigue;
- chakra depletion;
- treatment restrictions;
- damaged equipment;
- poison;
- disease;
- prisoners;
- evidence;
- environmental destruction.

A new scene should begin from the state left by the previous one.

## 4.29.2 Persistent State and Temporary State Are Different

Some states naturally expire.

Examples:
- brief disorientation;
- short-lived smoke exposure;
- temporary numbness;
- acute combat fatigue.

Other states remain until treated, repaired, healed, or otherwise changed.

Examples:
- fracture;
- missing finger;
- damaged sword;
- prisoner status;
- collapsed bridge;
- chronic nerve deficit.

The record should know which kind each state is.

## 4.29.3 Persistence Should Be Cause-Based

A state should end because its cause or duration condition ended.

Examples:
- burning ends when the fire is extinguished;
- bleeding ends when the vessel seals or is treated;
- restraint ends when bindings are removed;
- fracture ends as an active injury only after healing;
- poison ends when cleared or neutralized.

A scene transition should never remove state by itself.

## 4.29.4 Character Physical State

A persistent character may need to retain:
- active injuries;
- healed injuries with consequences;
- scars;
- amputations;
- prosthetics;
- chronic pain;
- reduced range of motion;
- sensory deficits;
- nerve damage;
- altered physiology.

Only consequences that can matter later need explicit storage.

## 4.29.5 Injury Records Persist Until Resolution

An injury record should remain until it is:
- fully healed;
- converted into chronic state;
- permanently resolved;
- removed because the affected anatomy no longer exists.

Even then, relevant historical information may remain in the medical history.

## 4.29.6 Injury History Can Matter After Healing

Past injuries may affect:
- reinjury risk;
- diagnosis;
- surgery;
- scars;
- chronic weakness;
- medical knowledge;
- character history.

A healed injury can therefore move from:
**Active Injury**
to:
**Medical History**
rather than being deleted.

## 4.29.7 Scars

Scars may persist as:
- cosmetic history;
- restricted tissue;
- altered sensation;
- identifying marks.

Most scars need no mechanical effect.

Only functionally relevant scars require active mechanical state.

## 4.29.8 Missing Anatomy

Loss of:
- limb;
- eye;
- finger;
- organ;
- other structure

must remain persistent until:
- transplanted;
- regenerated;
- replaced;
- otherwise restored.

The system should never infer anatomical restoration from time alone.

## 4.29.9 Prosthetics and Implants

Persistent records should include relevant:
- prosthetic type;
- fit;
- integration;
- condition;
- maintenance needs;
- chakra interaction;
- learned adaptation.

The prosthetic is part of the character's current body state.

## 4.29.10 Chronic Conditions

Long-term medical state may include:
- chronic pain;
- recurring weakness;
- instability;
- reduced endurance;
- sensory deficit;
- recurring inflammation;
- chakra-network impairment.

These remain until improved, cured, or replaced by a new state.

## 4.29.11 Recovery State

A recovering injury may need to retain:
- healing phase;
- structural progress;
- functional progress;
- restrictions;
- reinjury risk;
- rehabilitation plan;
- next milestone.

Time advancement updates these fields.

## 4.29.12 Medical Restrictions

Characters may have persistent restrictions such as:
- no sprinting;
- no heavy lifting;
- no frontline duty;
- avoid chakra use in affected limb;
- restricted training.

Restrictions remain advisory or institutional state until medically revised.

## 4.29.13 Characters May Ignore Restrictions

Ignoring a medical restriction does not delete it.

The system should instead apply:
- increased reinjury risk;
- delayed recovery;
- performance limitations;
- possible complications.

## 4.29.14 Fatigue Persistence

Acute fatigue may recover over:
- seconds;
- minutes;
- hours.

Deeper exhaustion may persist across:
- scenes;
- travel;
- sleep cycles.

The engine should preserve fatigue until sufficient recovery occurs.

## 4.29.15 Chakra State Persistence

Current chakra reserves and relevant chakra-system impairment should survive:
- scene transitions;
- encounter endings;
- travel;
- compression.

Ruleset 3 governs chakra recovery.

Ruleset 4 should never assume full reserves merely because combat ended.

## 4.29.16 Conditions With Long Duration

Some conditions may persist beyond one encounter.

Examples:
- partial paralysis;
- toxin-induced weakness;
- sensory impairment;
- chakra-flow disruption.

These must remain active until their actual resolution condition occurs.

## 4.29.17 Poison and Disease State

Persistent toxic or infectious records may include:
- substance/disease;
- exposure time;
- dose or burden;
- current phase;
- symptoms;
- progression;
- treatment;
- clearance;
- contagiousness where relevant.

Time skips must advance rather than erase them.

## 4.29.18 Medical Treatment History

Relevant care should be recorded when it affects future state.

Examples:
- surgery;
- major medical ninjutsu;
- transplant;
- antidote;
- blood replacement;
- prosthetic fitting.

Routine minor treatment can be summarized.

## 4.29.19 Treatment Quality Can Persist

A poor or incomplete repair may create:
- scar restriction;
- weak healing;
- chronic instability;
- need for revision surgery.

The treatment result should therefore remain part of the injury history.

## 4.29.20 Observer-Specific Medical Knowledge

Different characters may know different things about the same injury.

The engine may know:
- exact diagnosis.

The patient may know:
- symptoms.

A teammate may know:
- visible signs.

A medic may know:
- likely diagnosis.

These knowledge states should remain distinct across scenes.

## 4.29.21 Hidden Diagnoses Persist

If internal bleeding has not been discovered, it remains:
- physically real;
- informationally hidden.

A scene change does not reveal it.

The patient may later deteriorate because the hidden condition continued.

## 4.29.22 Correct and Incorrect Beliefs Persist

A character may hold:
- accurate diagnosis;
- mistaken diagnosis;
- uncertainty;
- false belief.

These beliefs remain until:
- corrected;
- forgotten where appropriate;
- disproven by later evidence.

The engine truth remains unchanged.

## 4.29.23 Combat Knowledge Persistence

Characters may remember:
- enemy techniques;
- fighting style;
- vulnerabilities;
- tactics;
- equipment;
- injuries witnessed.

This can affect future encounters.

Detailed memory rules belong elsewhere, but Ruleset 4 should produce the relevant observations.

## 4.29.24 Secret Ability Exposure

If someone witnesses a secret technique, that information does not disappear after battle.

The record should preserve:
- who observed it;
- what they plausibly understood;
- uncertainty.

This can later influence intelligence and enemy adaptation.

## 4.29.25 Equipment State Persistence

Equipment may remain:
- damaged;
- broken;
- lost;
- contaminated;
- depleted;
- modified.

Repairs, replacement, or resupply must actually occur.

## 4.29.26 Ammunition and Consumables

Meaningful remaining quantities should persist.

Examples:
- explosive tags;
- antidotes;
- special ammunition;
- medical supplies;
- restraint tools.

Routine abundant consumables can be compressed.

## 4.29.27 Dropped and Lost Equipment

An item left behind should remain:
- at that location;
- recoverable if conditions permit;
- available to others;
- potentially destroyed later.

It should not automatically return to inventory after encounter end.

## 4.29.28 Prisoner State

A prisoner record may need:
- identity;
- injuries;
- restraints;
- chakra suppression;
- consciousness;
- location;
- guard assignment;
- escape capability;
- medical needs.

Capture remains a persistent state until:
- release;
- escape;
- transfer;
- death;
- other explicit change.

## 4.29.29 Death State

Confirmed death is persistent.

Relevant record may include:
- time;
- place;
- cause;
- confirmation;
- body location;
- body disposition.

True resurrection or revival requires a specific mechanism.

## 4.29.30 Body State After Death

A corpse may persist with:
- injuries;
- bloodline tissue;
- equipment;
- evidence;
- decomposition;
- seals.

The body can remain relevant to:
- investigation;
- burial;
- transplantation;
- experimentation;
- intelligence security.

## 4.29.31 Environmental State Persistence

Battlefield changes may persist:
- crater;
- destroyed wall;
- burned building;
- flooded tunnel;
- collapsed bridge;
- contaminated water.

World repair or natural change must explicitly alter them.

## 4.29.32 Hazard Persistence

Hazards may continue across scenes.

Examples:
- fire;
- smoke;
- structural instability;
- toxic contamination;
- active traps.

Each hazard should have:
- duration/progression;
- resolution condition.

## 4.29.33 Evidence State

Evidence may remain:
- present;
- moved;
- contaminated;
- destroyed;
- collected.

Investigations should use the actual preserved evidence state.

## 4.29.34 Location Matters

Persistent state should generally retain where it exists.

Examples:
- dropped sword in alley;
- prisoner in holding cell;
- body at battlefield;
- damaged bridge outside village.

Location is necessary for later interaction.

## 4.29.35 Ownership and Custody

Items, bodies, prisoners, and evidence may change custody.

The system may need to track:
- current holder;
- current location;
- responsible organization.

This matters for continuity.

## 4.29.36 Time Stamps

Important persistent states should record enough temporal information to support:
- healing;
- poison progression;
- deterioration;
- evidence age;
- reinforcements;
- recovery.

Not every minor state needs exact-second precision.

## 4.29.37 Time Skips Must Update State Before Resuming Play

Before a scene begins after elapsed time, the engine should advance relevant processes:
- recovery;
- chakra restoration;
- fatigue recovery;
- poison;
- disease;
- bleeding;
- environmental hazards;
- prisoner transport.

Then the new scene begins from the updated state.

## 4.29.38 Time Skip Does Not Mean Automatic Safe Outcome

If a character with untreated internal bleeding is skipped forward six hours, the engine should not simply place them six hours later unchanged.

The medical process must resolve first.

The character may:
- deteriorate;
- collapse;
- receive off-screen care;
- die.

The causal path must be represented.

## 4.29.39 Off-Screen Treatment Must Actually Exist

If a character improves between scenes because of treatment, the simulation should know:
- who treated them;
- what capability was available;
- what treatment occurred.

Routine care may be summarized, but not invented without world support.

## 4.29.40 State Changes Need Provenance

For important changes, the engine should be able to answer:
- what changed;
- when;
- why;
- through which event or treatment.

This helps prevent continuity errors.

## 4.29.41 Current State and Historical State Are Different

The game should distinguish:
- what is true now;
- what happened before.

Example:
**Current**
Right forearm fully healed.

**History**
Serious fracture during River Mission; surgically repaired.

Both may matter.

## 4.29.42 Canonical State

For persistent simulation, there should be one canonical current truth for each stateful entity.

Narration, reports, and character beliefs may differ.

But the engine should not maintain contradictory physical truths.

## 4.29.43 State Conflict Resolution

If two stored facts conflict, resolution should prioritize:
1. more recent confirmed state change;
2. explicit causal event;
3. higher-confidence canonical record;
4. clarification or reconstruction if still uncertain.

Do not silently choose whichever detail is convenient.

## 4.29.44 Unknown State Is Valid

The canonical engine may sometimes know:
- character missing;
- exact current location unknown to player.

In some systems, even engine-level uncertainty may be retained until a background event resolves.

Do not invent precision solely to fill a field.

## 4.29.45 Save / Load Integrity

Saving and reloading should preserve:
- active injuries;
- recovery timers/phases;
- medical restrictions;
- chakra;
- fatigue;
- equipment;
- prisoners;
- environment;
- knowledge states.

Loading a game must not reset temporary-but-still-active state.

## 4.29.46 Chat / Session Continuity

For this project's conversational implementation, important canonical state should be externalized into persistent project/game-state storage rather than relying only on conversation context.

Ruleset documents define mechanics.
Game-state records define the current world.

The exact storage implementation belongs outside Ruleset 4, but Ruleset 4 defines what must be preserved.

## 4.29.47 Ruleset State and Game State Must Stay Separate

Ruleset documents answer:
**How does the system work?**

Game-state records answer:
**What is currently true?**

Do not store changing character injury state inside permanent rules documentation.

## 4.29.48 Hidden State Must Remain Hidden From Player-Facing Output

Persistent hidden information may include:
- exact internal injury;
- concealed enemy condition;
- undiscovered poison;
- hidden reinforcement status.

The storage system may retain it without revealing it to the player.

## 4.29.49 Hidden State Needs Stable Identity

A hidden fact should be tied to:
- character;
- item;
- location;
- event

so it can be retrieved later without ambiguity.

Example:
“PP-Character-17: internal bleeding, abdomen, onset 14:22.”

The exact data format belongs to implementation.

## 4.29.50 State Summaries Can Be Derived

Player-facing summaries may say:
- injured;
- recovering;
- exhausted;
- medically restricted.

These should be derived from detailed records.

The summary should not replace the underlying state.

## 4.29.51 State Compression

Old state can be compressed when:
- no unresolved consequence remains;
- exact detail is unlikely to matter.

Example:
Several healed minor cuts from routine missions may become:
“minor prior field injuries, no lasting effect.”

Permanent or plot-relevant consequences should not be discarded.

## 4.29.52 Promotion From Compressed to Detailed State

If an old fact becomes relevant again, the simulation may expand from stored summary where enough information exists.

Do not invent details beyond what the compressed record supports.

## 4.29.53 Persistent Character Medical Summary

A persistent character may have a concise current summary containing:
- active injuries;
- chronic conditions;
- permanent losses;
- prosthetics;
- medical restrictions;
- current recovery;
- relevant unusual physiology.

This gives fast access without reading the entire history.

## 4.29.54 Persistent Combat Readiness Summary

A useful derived readiness view may include:
- combat capacity;
- fatigue;
- chakra;
- active conditions;
- usable equipment;
- medical restrictions.

This is a convenience view, not an independent resource pool.

## 4.29.55 Persistent Equipment Summary

Important equipment may store:
- ownership;
- location;
- condition;
- ammunition;
- modifications;
- contamination;
- repair needs.

## 4.29.56 Persistent Encounter Summary

A concluded encounter may store:
- participants;
- outcome;
- casualties;
- major injuries;
- deaths;
- captures;
- techniques revealed;
- equipment losses;
- environmental changes;
- mission result.

This supports later reports and world consequences.

## 4.29.57 Persistent World Hooks

Unresolved aftermath may generate persistent hooks such as:
- injured NPC awaiting surgery;
- prisoner awaiting transfer;
- destroyed bridge awaiting repair;
- escaped enemy;
- contaminated site;
- unidentified body;
- missing teammate.

These remain active until resolved.

## 4.29.58 State Update Pipeline

Whenever a consequential event occurs:

1. Resolve the event.
2. Identify which persistent entities changed.
3. Update canonical physical state.
4. Update time-sensitive processes.
5. Update observer-specific knowledge.
6. Record treatment/resource/environment changes.
7. Preserve relevant event history.
8. Derive summaries for fast use.
9. Remove only states whose actual end conditions were met.
10. Continue simulation from the new canonical state.

## 4.29.59 Persistence Audit

At scene, mission, or major time transitions, the engine should be able to audit:
- unresolved injuries;
- deteriorating patients;
- ongoing poison/disease;
- fatigue/chakra state;
- damaged equipment;
- prisoners;
- missing characters;
- environmental hazards;
- unresolved mission aftermath.

This helps prevent state from being forgotten.

## 4.29.60 Compression Audit

Before discarding detailed state, ask:
- Could this fact plausibly affect future combat?
- Could it affect medicine?
- Could it affect investigation?
- Could it affect character relationships or world state?
- Could the player reasonably expect continuity?

If yes, preserve it at least in summarized form.

## Core Design Rule

Persistent state should preserve **what remains true after the moment has passed**.

Scenes, encounters, summaries, time skips, and save/load are presentation boundaries.
They are not physical reset buttons.

Anything that can still affect the future should remain in canonical state until something actually changes it.
