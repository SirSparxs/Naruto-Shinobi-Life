# 7.2 — NPC Simulation Tiers

Status: Provisional design section pending explicit approval.

Ruleset 7 should simulate NPCs at different levels of detail depending on their current relevance, persistence, and causal importance.

The purpose of simulation tiers is not to make some NPCs "less real." It is to allocate detail efficiently while preserving believable continuity.

## Core Principle

Every NPC should be treated as a potentially real person in the world, but not every NPC needs identical amounts of stored state at all times.

Simulation depth should scale with:
- narrative relevance;
- frequency of interaction;
- current proximity to important events;
- number of active relationships;
- possession of important knowledge;
- current role in ongoing conflicts;
- likelihood of future reappearance;
- consequences of inconsistency if their state is forgotten.

The system should simulate only enough detail to preserve meaningful causality.

## 7.2.1 Tier Structure

Ruleset 7 uses four default NPC simulation tiers:

1. Major NPC
2. Supporting NPC
3. Persistent Minor NPC
4. Background NPC

A character may move between tiers over time.

Tier determines simulation depth, not power level, rank, intelligence, or intrinsic importance to the world.

A random civilian may become a Major NPC if they become central to the player's life.
A Kage may temporarily be represented as Supporting or Background if they are distant and irrelevant to the current simulation.

## 7.2.2 Tier 1 — Major NPC

Major NPCs receive the deepest persistent simulation.

Typical examples:
- teammates;
- close friends;
- rivals;
- mentors;
- family members;
- romantic partners or major romantic interests;
- major antagonists;
- recurring political figures;
- faction leaders directly affecting the player;
- long-term employers, commanders, or subordinates;
- major NPCs central to active arcs.

Major NPCs should normally track:

### Identity
- personality;
- values;
- worldview;
- temperament;
- boundaries;
- cultural background;
- preferences;
- important habits.

### Goals
- short-term goals;
- medium-term goals;
- long-term goals;
- competing priorities;
- fears;
- obligations;
- hidden motives where relevant.

### Knowledge & Beliefs
- important known facts;
- suspicions;
- false beliefs;
- confidence levels;
- important secrets;
- information sources.

### Relationships
Detailed relationship state with:
- the player;
- other major NPCs;
- selected supporting NPCs;
- important groups or institutions where relevant.

### Memory
Track:
- major shared events;
- promises;
- betrayals;
- favors;
- important conversations;
- emotional turning points;
- romantic developments;
- major conflicts;
- significant acts of loyalty or abandonment.

### Emotional / Social State
Track active:
- anger;
- grief;
- jealousy;
- suspicion;
- fear;
- confidence;
- affection;
- embarrassment;
- stress;
- other currently relevant states.

### Routines & Availability
Track:
- occupation;
- mission status;
- schedule patterns;
- important obligations;
- current location when relevant;
- relationships likely to affect availability.

### Active Threads
Track:
- unresolved promises;
- debts;
- grudges;
- courtship;
- investigations;
- conflicts;
- secrets;
- loyalties under pressure;
- plans involving other characters.

Major NPCs are eligible for meaningful off-screen development.

## 7.2.3 Tier 2 — Supporting NPC

Supporting NPCs are recurring characters with meaningful but narrower influence.

Typical examples:
- recurring coworkers;
- squadmates outside the player's closest circle;
- shopkeepers visited often;
- instructors;
- neighbors;
- recurring clients;
- lower-level political contacts;
- secondary antagonists;
- occasional allies;
- acquaintances;
- recurring clan members.

Supporting NPCs should usually track:

- concise identity profile;
- 1–3 active goals;
- key values or personality traits;
- relationship state with the player;
- relationships with directly relevant NPCs;
- important knowledge and secrets;
- several meaningful memories;
- current emotional state only when relevant;
- unresolved favors, promises, grudges, or conflicts;
- broad routine and availability.

Supporting NPCs may receive off-screen updates when:
- they are connected to an active plot;
- their relationships matter;
- they possess relevant information;
- enough time has passed for a meaningful change.

They do not require constant full-state advancement.

## 7.2.4 Tier 3 — Persistent Minor NPC

Persistent Minor NPCs are named or recognizable characters who may return but do not currently require deep simulation.

Typical examples:
- a ramen vendor;
- a gate guard;
- a clerk;
- an academy classmate;
- a hospital receptionist;
- a recurring customer;
- a distant cousin;
- a local civilian;
- a low-relevance shinobi previously encountered.

Persistent Minor NPCs should normally track:

- name and identity;
- role;
- a few defining traits;
- broad disposition toward the player;
- one or two important memories;
- important knowledge they possess;
- any unresolved social obligation or conflict;
- basic affiliations;
- rough routine if likely to matter.

Detailed relationship axes need not all be stored unless they become relevant.

Instead, compressed descriptors may be used, such as:
- recognizes player;
- mildly distrustful;
- grateful for prior help;
- professional but distant;
- has heard a rumor;
- owes a small favor.

If the NPC becomes more important, these descriptors should be expanded into full state.

## 7.2.5 Tier 4 — Background NPC

Background NPCs exist primarily as part of the living world and may initially have little or no persistent individual state.

Examples:
- unnamed pedestrians;
- crowd members;
- random customers;
- civilians briefly encountered;
- anonymous guards;
- background workers;
- incidental shinobi;
- one-scene witnesses.

Background NPCs may be represented through:
- role;
- immediate context;
- culture;
- location;
- broad competence;
- temporary attitude;
- current task.

They do not require persistent memory unless something meaningful happens.

If a Background NPC:
- has a meaningful conversation;
- witnesses a major event;
- becomes personally involved;
- is harmed, helped, threatened, recruited, or deceived in a consequential way;
- is given a name;
- is likely to reappear;

they should usually be promoted to Persistent Minor or higher.

## 7.2.6 Promotion Between Tiers

Promotion occurs when increased detail becomes necessary to preserve causality.

Common promotion triggers:
- repeated interaction;
- significant emotional event;
- new personal relationship;
- important knowledge gained;
- involvement in an active plot;
- becoming a recurring contact;
- receiving a promise or debt;
- major conflict;
- romance or courtship;
- witnessing a consequential event;
- being recruited into a team or organization relevant to the player;
- becoming a rival, enemy, dependent, mentor, student, or ally.

Promotion should not rewrite history.

When an NPC is promoted:
1. preserve all established facts;
2. convert compressed descriptors into explicit state;
3. infer missing details conservatively from culture, role, prior behavior, and known history;
4. do not invent retroactive secrets or relationships solely to make the NPC more interesting;
5. mark uncertain inferred details internally when needed.

## 7.2.7 Demotion & Compression

NPCs may be compressed when:
- they leave the active region;
- an arc ends;
- their current role becomes minor;
- they have not meaningfully interacted for a long period;
- detailed active state no longer affects near-term outcomes.

Demotion should preserve:
- identity;
- major memories;
- major relationships;
- unresolved promises;
- major secrets;
- ongoing long-term goals;
- current status;
- important injuries or life changes;
- romantic/family status;
- major institutional affiliations.

Temporary details can be summarized.

Example:
Instead of preserving 14 separate recent emotional flags for an old teammate, the system may compress them into:
- relationship remains warm but strained after the argument;
- trust partially recovered;
- still owes player a favor;
- currently assigned outside the village.

## 7.2.8 No Continuity Reset

Moving to a lower tier must never mean:
- forgetting major history;
- erasing relationship consequences;
- removing debts;
- resetting romance;
- restoring trust automatically;
- deleting grudges;
- forgetting injuries;
- losing important secrets;
- reverting personality.

Compression reduces detail, not causality.

## 7.2.9 Simulation Frequency by Tier

### Major NPC
Update frequently when:
- time advances;
- relevant events occur;
- off-screen goals are active;
- relationships are changing;
- the NPC has meaningful choices to make.

### Supporting NPC
Update when:
- connected events occur;
- significant time passes;
- an active goal advances;
- another important NPC affects them.

### Persistent Minor NPC
Update mainly when:
- directly encountered;
- affected by a relevant local event;
- specifically pulled into an active social network;
- time passage would obviously alter their situation.

### Background NPC
No individual off-screen update unless promoted.

## 7.2.10 Event-Driven Simulation

Tier does not mean every NPC updates on a fixed schedule.

Prefer event-driven updates.

Examples:
- A rumor enters a clan network.
- A mission ends.
- A family member is injured.
- A friend is arrested.
- A romantic partner leaves the village.
- A superior issues a new order.
- A secret is exposed.
- A major battle occurs.

Only NPCs plausibly affected by the event need processing.

## 7.2.11 Social Radius

Each NPC has a practical social radius:
- people they interact with regularly;
- institutions they belong to;
- information channels they can access;
- locations they frequent.

Off-screen updates should normally propagate through this radius rather than globally.

A shopkeeper in Kusagakure should not update their opinion about events in Kirigakure unless a believable information path exists.

## 7.2.12 Importance Is Contextual

Simulation tier must not be based solely on:
- combat rank;
- canon prominence;
- political title;
- bloodline;
- wealth;
- power.

A genin teammate may require deeper simulation than a distant Kage.

A civilian spouse may be more socially important than an S-rank commander.

A recurring shopkeeper may become more important than a clan elder if they hold key information or have a close personal relationship with the player.

## 7.2.13 Canon Characters

Canon status alone does not force Major NPC simulation.

Canon NPCs should be simulated at the tier justified by their actual involvement.

This prevents the world from becoming artificially centered around famous characters.

A canon character should still retain:
- established personality;
- established history;
- known affiliations;
- known capabilities;
- known relationships;

to the extent relevant to the campaign timeline.

## 7.2.14 Romantic Relationships & Tier Priority

Romantic involvement usually increases simulation priority because it creates:
- frequent interaction;
- emotional stakes;
- expectations;
- private knowledge;
- jealousy/conflict possibilities;
- commitment decisions;
- off-screen relationship development.

A serious romantic partner should normally become Major.

An early crush or brief flirtation may remain Supporting or Persistent Minor until it develops further.

Adult arousal alone does not justify promotion.

## 7.2.15 Hidden State by Tier

The simulation may store hidden information at any tier, but detail should match relevance.

Major NPC:
- detailed motives, secrets, relationships, suspicions, and hidden conflicts.

Supporting NPC:
- only hidden state likely to affect future interaction.

Persistent Minor:
- only essential hidden facts.

Background:
- no persistent hidden state unless generated by a meaningful event.

## 7.2.16 Generated NPCs

Procedurally generated NPCs should begin at the lowest sufficient tier.

Generation should avoid creating full biographies for people who may never reappear.

If they become important, generate additional detail using:
- already established facts;
- location;
- culture;
- profession;
- rank;
- age;
- clan;
- observed behavior;
- prior interactions.

New detail must remain consistent with previous portrayal.

## 7.2.17 Tier Changes Should Be Invisible In-World

NPCs should not behave as if they were promoted or demoted.

The tier is purely a simulation-management tool.

The player should experience:
- consistent personality;
- consistent memory;
- continuous relationships;
- believable off-screen life.

They should never see:
- "this NPC became Major";
- "relationship detail was expanded";
- "background simulation activated";

unless using an explicit developer/debug interface.

## 7.2.18 Compression Standard

When compressing an NPC, preserve enough information that future expansion can answer:

- Who are they?
- What matters most to them?
- What important things happened between us?
- How do they broadly feel about us?
- What do they know that matters?
- What do they owe or expect?
- What major relationships or obligations remain active?
- What unresolved thread could matter later?

If those questions cannot be answered, too much state was discarded.

## 7.2.19 Performance Guardrail

Do not simulate every NPC every day.

The system should prefer:
- event triggers;
- relevance filters;
- social-network propagation;
- summarized long-term change;
- selective detailed expansion.

The goal is believable persistence, not maximal computation.

## 7.2.20 Example Promotion Chain

An unnamed ramen customer begins as Background.

The player speaks with them during a disturbance.
They reveal useful information and receive a name.

They become Persistent Minor.

The player repeatedly visits them and learns they are connected to a smuggling network.

They become Supporting.

They later become a trusted informant, develop a close friendship with the player, and become central to an investigation.

They become Major.

At no point should earlier facts be rewritten merely because more detail is now stored.

## Design Standard

A simulation-tier mechanic should be rejected or revised if it:
- makes lower-tier NPCs disposable or unreal;
- causes continuity loss when tier changes;
- uses combat rank as the main measure of simulation depth;
- fully simulates large populations without a meaningful reason;
- invents retroactive history when an NPC becomes important;
- deletes major memories or relationships during compression;
- prevents incidental NPCs from becoming important organically;
- gives canon characters automatic priority solely because they are canon;
- treats romantic attraction alone as sufficient reason for deep simulation;
- requires the player to see internal tier labels during normal play.

## Governing Rule

**Simulate the minimum detail required to preserve believable causality, then expand only when the character becomes important enough for additional detail to matter.**
