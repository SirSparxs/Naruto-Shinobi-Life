# 7.41 — Continuity, Persistence & State Storage

Status: Provisional design section pending explicit approval.

Ruleset 7.41 defines how social simulation state is stored, updated, compressed, restored, and preserved across scenes, sessions, time skips, save files, and long-running campaigns.

The governing principle is:

**Persistent social state should preserve every fact necessary for future causal consistency while compressing routine detail that no longer affects decisions, relationships, knowledge, obligations, or world state.**

## 7.41.1 Scope

This section governs persistence of:
- NPC identity;
- relationships;
- memories;
- beliefs;
- secrets;
- obligations;
- routines;
- social access;
- reputation;
- hidden motives;
- player knowledge;
- NPC knowledge;
- social-event history;
- unresolved conflict;
- romantic state;
- group relationships;
- social-network ties;
- compressed off-screen history.

It does not define the technical storage format in code.
Schemas and save architecture may implement these principles separately.

## 7.41.2 Persistence Is Required for Causality

If an event can meaningfully affect future:
- behavior;
- interpretation;
- access;
- relationship;
- reputation;
- obligation;
- knowledge;
- goal;

then enough information about that event must persist.

The simulation should never rely on remembering only the latest scene.

## 7.41.3 Persistent Identity

Every persistent NPC should retain:
- stable unique identifier;
- name;
- age or birth date where known;
- origin;
- role;
- core identity traits;
- simulation tier.

Surface details may expand later, but identity must remain stable.

## 7.41.4 Unique IDs Over Names

NPC identity should not rely solely on names.

Two people may:
- share a name;
- change names;
- use aliases;
- conceal identity.

Persistent state should reference stable IDs internally.

## 7.41.5 Canon Identity

Canon characters should have stable identifiers separate from:
- titles;
- rank;
- aliases.

Changes in timeline should not create duplicate versions unless alternate timelines are explicitly supported.

## 7.41.6 Relationship Objects

Important relationships should persist as directional relationship objects.

At minimum, preserve relevant:
- Trust;
- Respect;
- Affection;
- Loyalty;
- Fear;
- Familiarity;
- Obligation;
- Resentment;
- Hostility;
- Romantic Interest;
- adult Sexual Chemistry where relevant.

Do not reconstruct major relationships from labels alone.

## 7.41.7 Relationship Labels

Also preserve socially meaningful labels such as:
- friend;
- sibling;
- teammate;
- mentor;
- rival;
- partner;
- ex-partner;
- commander.

Labels represent structure and expectations, not full state.

## 7.41.8 Relationship Asymmetry

A->B and B->A must remain separate.

Do not collapse:
- Trust;
- Loyalty;
- Romantic Interest;
- Resentment;

into one shared value.

## 7.41.9 Relationship History

Persist major relationship milestones such as:
- first meeting where relevant;
- relationship formation;
- betrayal;
- reconciliation;
- breakup;
- major sacrifice;
- major conflict.

Routine interactions can be compressed.

## 7.41.10 Current Relationship Expectations

Where relevant, preserve expectations involving:
- secrecy;
- exclusivity;
- communication;
- support;
- role;
- boundaries;
- professional conduct.

Expectation exists, expectation communicated, and expectation mutually agreed should remain distinguishable.

## 7.41.11 Memory Persistence

Ruleset 7.7 governs memory content.

Persistent storage should retain memories that are:
- major;
- defining;
- unresolved;
- repeatedly referenced;
- tied to promises;
- tied to betrayal;
- tied to important relationships;
- necessary for future knowledge.

## 7.41.12 Memory Compression

Routine repeated experiences may compress into pattern memories.

Example:
Instead of storing twenty similar training sessions:
- "Repeated reliable training partnership over six months."

Compression should preserve:
- meaning;
- trend;
- relevant emotional impact.

## 7.41.13 Do Not Compress Away Causal Exceptions

If one event significantly differed from the pattern, preserve it separately.

Example:
- nineteen positive missions;
- one mission where teammate abandoned them.

The betrayal cannot disappear inside:
- "Mostly positive mission history."

## 7.41.14 Knowledge State

For important facts, store separately:
- objective truth;
- who knows;
- who believes;
- who suspects;
- confidence;
- source;
- whether information is outdated.

This prevents accidental omniscience.

## 7.41.15 Player Knowledge

Persistent state should preserve what the player character:
- knows;
- suspects;
- believes;
- has been told;
- has personally observed.

The simulation should not grant knowledge merely because hidden state exists.

## 7.41.16 NPC Knowledge

Important NPC knowledge should also persist.

If an NPC learns:
- a secret;
- a rumor;
- the player's identity;
- a betrayal;

that knowledge should influence later behavior.

## 7.41.17 Belief vs Truth

Storage should not merge:
- "NPC believes X"

with:
- "X is true."

Both may need separate representation.

## 7.41.18 Source Provenance

Important beliefs should preserve where they came from when source matters.

Examples:
- personally witnessed;
- told by trusted friend;
- rumor;
- official report;
- enemy claim.

This supports later credibility reevaluation.

## 7.41.19 Secrets

Important secrets should persist with:
- objective content;
- owner or subject;
- who knows;
- who suspects;
- sensitivity;
- exposure state.

Secrets should not become globally known merely because one NPC learned them.

## 7.41.20 Obligation State

Ruleset 7.32 obligations should persist until:
- satisfied;
- broken;
- explicitly released;
- no longer socially meaningful.

Store:
- parties;
- origin;
- content;
- magnitude;
- status;
- conditions.

## 7.41.21 Promise Persistence

Meaningful promises should survive:
- session changes;
- time skips;
- temporary absence;
- relationship changes.

A promise does not vanish because the conversation ended.

## 7.41.22 Unresolved Conflict

Persist unresolved:
- arguments;
- betrayals;
- resentment;
- suspicion;
- grievances;
- reconciliation conditions.

Do not reset interpersonal tension between sessions.

## 7.41.23 Rupture State

Major rupture should preserve:
- trigger;
- perceived violation;
- objective facts;
- contact state;
- repair attempts;
- forgiveness;
- remaining scars.

## 7.41.24 Romantic State

Where relevant, preserve:
- relationship label;
- formation date;
- exclusivity/structure;
- commitment;
- key expectations;
- public/private status;
- breakup history;
- reconciliation history.

## 7.41.25 Adult Private State

For adults 18+ where simulation-relevant, private persistence may include:
- adult Sexual Chemistry;
- sexual compatibility;
- broad intimate preferences;
- relationship expectations.

These remain hidden unless revealed in-world.

## 7.41.26 Routine State

Persist enough routine information to support:
- locating NPCs;
- availability;
- social opportunity;
- off-screen interactions.

Do not store every minute.

Prefer:
- recurring pattern;
- current exceptions;
- major schedule commitments.

## 7.41.27 Current Location

Important NPCs may require current:
- location;
- mission status;
- travel state;
- hospital status;
- availability.

This should persist when relevant to immediate play.

## 7.41.28 Temporary State

Temporary states may include:
- current emotion;
- fatigue;
- immediate suspicion;
- short-term social momentum.

These should persist only as long as their duration requires.

## 7.41.29 Expiring State

Temporary state should include:
- creation time;
- expected duration or decay condition;
- trigger for removal.

Avoid keeping obsolete temporary modifiers forever.

## 7.41.30 Goals

Persist active NPC goals and priorities.

If a goal:
- completes;
- fails;
- is abandoned;
- changes;

update state rather than deleting history where the change remains relevant.

## 7.41.31 Motives

Stable or recurring motives may persist.

Temporary motives can be discarded after:
- resolution;
- irrelevance;
- replacement.

Do not store every fleeting thought.

## 7.41.32 Reputation

Ruleset 7.20 reputation should persist by:
- audience;
- domain;
- confidence;
- reach.

Do not store one global reputation value.

## 7.41.33 Rumor State

Important rumors may persist with:
- claim;
- origin;
- current tellers;
- audiences reached;
- confidence;
- distortion;
- correction state.

Routine rumor transmissions can be compressed.

## 7.41.34 Social Network State

Persist meaningful ties:
- family;
- team;
- workplace;
- friendship;
- rivalry;
- mentorship;
- romantic;
- broker/gatekeeper;
- important acquaintance.

Do not store every one-time interaction as a permanent edge.

## 7.41.35 Group State

Important groups may persist:
- membership;
- informal standing;
- cohesion;
- factions;
- leadership;
- current tensions;
- shared narratives.

Formal institutional systems may own membership or rank.

## 7.41.36 Social Access State

Persist meaningful:
- invitations;
- restricted access;
- home access;
- private contact privileges;
- revoked privileges;
- gatekeeper relationships.

Temporary event access may expire.

## 7.41.37 Social Event History

Not every conversation needs permanent storage.

Persist detailed event records when they:
- create memory;
- change relationship significantly;
- transfer important knowledge;
- create obligation;
- alter access;
- change group state;
- create rumor;
- affect future decisions.

## 7.41.38 Event Summaries

Older event detail may compress into structured summaries.

Example:
Instead of retaining every conversation from a year of mentorship:
- "Regular mentorship from 14-15; strong Trust and professional Respect developed."

## 7.41.39 Preserve Key Quotes Sparingly

Exact dialogue should persist only when wording itself matters.

Examples:
- solemn promise;
- explicit threat;
- confession;
- breakup statement;
- oath.

Most dialogue can be paraphrased into event meaning.

## 7.41.40 Time Stamps

Important persistent events should retain:
- date;
- approximate date;
- age;
- sequence;

as available.

Temporal order is important for causal reasoning.

## 7.41.41 Unknown Dates

If exact timing is unknown, preserve:
- relative order;
- approximate period.

Do not invent false precision.

## 7.41.42 State Snapshots vs Event Log

The system should conceptually maintain both:
- current state;
- major causal history.

Current state answers:
- "What is true now?"

History answers:
- "How did it become true?"

Both matter.

## 7.41.43 Avoid Event-Only Storage

Reconstructing everything from a giant event log is inefficient for simulation.

Maintain current summarized state for active use.

## 7.41.44 Avoid Snapshot-Only Storage

A snapshot without history cannot explain:
- resentment;
- trust damage;
- obligation;
- reconciliation conditions.

Preserve important causes.

## 7.41.45 Compression Layers

A useful hierarchy is:

### Active Detail
Current scene-relevant facts.

### Persistent State
Current relationships, goals, knowledge, routines, obligations.

### Historical Summary
Major past events and compressed long-term patterns.

### Archive
Rarely needed detailed records, if retained.

## 7.41.46 Recency Is Not the Only Importance Measure

Old events may remain highly relevant.

Examples:
- childhood betrayal;
- old oath;
- deceased mentor;
- ancestral feud.

Compression should consider:
- salience;
- causal importance;
- unresolved status;

not only age.

## 7.41.47 Persistence by Simulation Tier

### Major NPC
Retain detailed state and important history.

### Supporting NPC
Retain core relationships, goals, knowledge, and key memories.

### Persistent Minor NPC
Retain identity, role, meaningful ties, major events.

### Background NPC
Retain only if needed for world continuity.

## 7.41.48 Promotion

When an NPC is promoted to higher simulation detail:
- preserve all existing facts;
- expand missing context;
- never overwrite established history.

## 7.41.49 Demotion

When reducing detail:
preserve:
- identity;
- major relationships;
- unresolved obligations;
- major secrets;
- important goals;
- major memories;
- current location if relevant.

Compress routine details.

## 7.41.50 Dormant NPCs

NPCs absent for long periods should remain persistent if they possess:
- important relationships;
- obligations;
- unresolved conflict;
- secrets;
- likely future relevance.

They should not be deleted merely because they are off-screen.

## 7.41.51 Dead NPCs

Death does not erase:
- memories;
- promises;
- reputation;
- relationship history;
- inheritance;
- unresolved grief.

The NPC becomes historical state rather than active agent.

## 7.41.52 Destroyed or Dissolved Groups

A dissolved:
- squad;
- clan faction;
- organization;

may remain historically relevant.

Preserve:
- former membership;
- major events;
- legacy relationships.

## 7.41.53 Alias and Identity Linking

If an NPC uses:
- alias;
- disguise;
- false identity;

store the identities separately until they are linked in-world.

Different characters may know different identity links.

## 7.41.54 Hidden State Separation

Hidden GM state should be stored separately from:
- player-facing summaries;
- save codes;
- visible journals;

where feasible.

The player should not accidentally read:
- secret motives;
- hidden rolls;
- unrevealed relationships;
- objective truth behind rumors.

## 7.41.55 Public Save Summary

A player-visible save summary may include:
- known relationships;
- known commitments;
- known goals;
- current location;
- known events.

It should not expose hidden state.

## 7.41.56 Internal Save State

Internal persistence may additionally include:
- exact hidden relationship values;
- NPC beliefs;
- secrets;
- hidden motives;
- unrevealed events;
- hidden roll results.

## 7.41.57 Save/Load Determinism

Loading a save should restore:
- prior social state;
- hidden decisions;
- unresolved consequences.

It should not reroll already-resolved hidden events.

## 7.41.58 Hidden Roll Persistence

Once a hidden outcome has been resolved and matters later, store the result.

Do not reroll:
- whether NPC believed lie;
- whether rumor reached group;
- whether attraction emerged;

simply because a new session began.

## 7.41.59 Random Seed Independence

Even if technical implementation uses random seeds, important resolved social outcomes should become explicit stored state.

Do not rely solely on recreating them through future random generation.

## 7.41.60 Long Time Skips

During long skips:
1. preserve starting state;
2. identify active pressures and opportunities;
3. simulate relevant developments;
4. update current state;
5. create compressed history.

Do not simply advance the date and leave relationships frozen.

## 7.41.61 Time-Skip Compression

After a multi-year skip, store important developments such as:
- relationship formed;
- friendship faded;
- promotion changed routine;
- rumor became reputation;
- obligation repaid.

Routine daily interaction should compress.

## 7.41.62 Contradiction Prevention

Before adding persistent state, verify it does not contradict:
- prior known facts;
- chronology;
- relationships;
- location;
- age;
- established knowledge.

If conflict exists, reconcile it explicitly rather than silently overwriting.

## 7.41.63 Canon Continuity

Canon facts should remain stable until:
- simulation causally diverges.

Once divergence occurs, persistent project state becomes authoritative for that simulation timeline.

Do not revert to canon later if doing so contradicts established events.

## 7.41.64 Player Choice Persistence

Important player choices must persist.

Examples:
- promise made;
- friendship ended;
- mentor chosen;
- secret revealed;
- relationship formed.

The simulation should never forget player-created history.

## 7.41.65 NPC Choice Persistence

Important NPC choices must persist equally.

NPC autonomy loses meaning if their decisions are forgotten when inconvenient.

## 7.41.66 State Versioning

As rules evolve, save-state schema may change.

Migration should preserve:
- meaning;
- identity;
- major relationships;
- history.

Do not silently reinterpret old state under new rules without migration logic.

## 7.41.67 Rule Version Reference

Persistent saves may store:
- ruleset version;
- schema version;
- migration version.

This allows future compatibility.

## 7.41.68 Conflict Resolution Between Sources

If multiple records disagree, priority should generally be:

1. explicit canonical project state for this simulation;
2. latest valid persistent save;
3. stored historical event;
4. compressed summary;
5. inferred/generated missing detail.

Do not let generated filler override explicit state.

## 7.41.69 Unknown vs Missing

Storage should distinguish:
- fact unknown in-world;
- fact not yet generated;
- data accidentally missing.

These are different states.

## 7.41.70 Lazy Generation

For low-relevance details not yet generated:
- generate when needed;
- respect all existing constraints;
- mark new detail as newly established.

This reduces unnecessary storage.

## 7.41.71 Soft Deletion

When state becomes irrelevant, prefer:
- compression;
- archival marking;

over destructive deletion if it might later affect continuity.

## 7.41.72 Hard Deletion

Hard deletion is appropriate only for:
- duplicate technical artifacts;
- invalid generated detail never established in-world;
- obsolete implementation data.

Do not delete meaningful fictional history merely to save space.

## 7.41.73 Persistence Audit

For any persistent social record, the engine should be able to answer:

1. Why might this matter later?
2. Is it current state, historical state, or temporary state?
3. Who knows it?
4. Who believes it?
5. Does it affect relationships, goals, access, obligations, or reputation?
6. Can it be compressed safely?
7. Would deleting it risk contradiction?
8. Is it player-visible or hidden?

## 7.41.74 Minimum Persistent NPC Record

For a persistent NPC, retain at minimum where relevant:

**ID**
**Identity**
**Age / timeline anchor**
**Role**
**Simulation tier**
**Core traits**
**Major goals**
**Important relationships**
**Major knowledge / secrets**
**Major obligations**
**Routine summary**
**Current status / location**
**Important memories**
**Current social access**
**Known aliases**

## 7.41.75 Minimum Relationship Record

For an important relationship, retain:

**Participants**
**Directional dimensions**
**Relationship labels**
**Major expectations**
**Key memories**
**Unresolved conflict**
**Obligations**
**Romantic structure where relevant**
**Last major change**
**Current contact state**

## 7.41.76 Minimum Social Event Record

For a major social event, retain:

**Participants**
**Time**
**Context**
**What happened objectively**
**What each relevant person believes happened**
**Outcome**
**Relationship changes**
**Knowledge changes**
**Memories created**
**Obligations created**
**Reputation / rumor consequences**
**Future unresolved hooks**

## 7.41.77 Design Standard

A persistence mechanic should be rejected or revised if it:
- stores only the most recent scene;
- collapses directional relationships into shared values;
- forgets promises across sessions;
- rerolls hidden outcomes after loading;
- exposes hidden state in player saves;
- freezes NPCs during time skips;
- discards old but unresolved events;
- lets generated filler override explicit history;
- stores every trivial conversation forever;
- deletes history needed to explain current state.

## Governing Rule

**Continuity should preserve the causal skeleton of the social world—identity, relationships, knowledge, memories, obligations, goals, access, and major history—while compressing routine detail so that long-running simulation remains coherent without becoming an unbounded transcript archive.**
