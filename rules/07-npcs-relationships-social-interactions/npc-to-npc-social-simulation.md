# 7.35 — NPC-to-NPC Social Simulation

Status: Provisional design section pending explicit approval.

Ruleset 7.35 defines how NPC relationships and social events continue developing without direct player involvement.

The governing principle is:

**NPC social life should continue off-screen through causal, relevance-weighted simulation, with detail expanded only when events materially affect important characters, relationships, groups, or future play.**

## 7.35.1 Scope

This section governs:
- NPC-to-NPC social interactions;
- off-screen relationship change;
- friendship formation;
- rivalry development;
- romance development;
- arguments and reconciliation;
- favors and obligations;
- rumor transmission;
- social-network change;
- group tensions;
- social consequences that later reach the player.

It does not require every NPC conversation to be explicitly generated.

## 7.35.2 NPCs Do Not Pause When Off-Screen

NPCs may continue to:
- work;
- socialize;
- argue;
- make friends;
- date;
- reconcile;
- gossip;
- help each other;
- form opinions;

while the player is elsewhere.

The world should not socially freeze outside the player's current scene.

## 7.35.3 Same Rules, Lower Resolution

NPC-to-NPC interactions use the same underlying systems as player-facing interactions.

However, off-screen simulation may use:
- compressed resolution;
- broader event summaries;
- relationship-state inference;

when exact dialogue is unnecessary.

This preserves consistency without excessive processing.

## 7.35.4 No Protagonist-Centered Social World

NPC friendships and romances should not exist only in relation to the player.

An NPC may:
- prefer another NPC;
- become closer to someone else;
- gain a rival;
- leave a relationship;
- form a family;
- become estranged;

independently.

## 7.35.5 Relevance-Weighted Simulation

Off-screen social processing should prioritize:

### High Relevance
- Major NPCs;
- close relationships;
- active rivals;
- current teammates;
- romantic partners;
- key leaders;
- active antagonists.

### Medium Relevance
- Supporting NPCs;
- important group members;
- recurring contacts.

### Low Relevance
- background characters;
- distant acquaintances;
- unrelated civilians.

Detail should scale accordingly.

## 7.35.6 Event-Driven Simulation

Do not simulate every minute.

Instead, process meaningful triggers such as:
- shared mission;
- prolonged proximity;
- major argument;
- party or gathering;
- crisis;
- promotion;
- injury;
- rumor;
- betrayal;
- romantic opportunity;
- group reorganization.

Social development should occur around meaningful events.

## 7.35.7 Routine Social Drift

Some relationships may change gradually through:
- repeated contact;
- absence;
- routine cooperation;
- recurring friction.

This can be summarized rather than scene-by-scene.

Example:
- "Over several weeks, the two medics become casual friends."

## 7.35.8 Interaction Opportunity

For an off-screen interaction to occur, NPCs need a plausible opportunity through:
- shared location;
- work;
- family;
- team;
- social network;
- communication channel;
- scheduled event.

The engine should not invent contact between socially disconnected NPCs without a path.

## 7.35.9 Availability Matters

NPC routines and commitments affect:
- who meets;
- how often;
- under what context.

Ruleset 7.36 will govern routines and availability in greater detail.

## 7.35.10 Existing Relationship Bias

Off-screen interactions should begin from existing:
- Trust;
- Affection;
- Familiarity;
- Loyalty;
- Resentment;
- Hostility;
- Romantic Interest.

Do not repeatedly regenerate relationships from scratch.

## 7.35.11 Personality Matters

NPC behavior should reflect:
- temperament;
- goals;
- communication style;
- values;
- confidence;
- emotional state.

Two NPCs exposed to the same event may respond differently.

## 7.35.12 Goals Drive Social Activity

NPCs may initiate interactions because they want:
- help;
- friendship;
- information;
- romance;
- status;
- reconciliation;
- revenge;
- support.

Off-screen social events should arise from motives where possible.

## 7.35.13 Relationship Opportunity Heuristic

A relationship is more likely to change when there is:
- repeated contact;
- emotional salience;
- conflict;
- vulnerability;
- shared success;
- shared hardship;
- mutual attraction;
- important obligation.

Routine coexistence alone should produce slow change.

## 7.35.14 Friendship Formation Off-Screen

NPCs may become friends through:
- repeated positive contact;
- shared interests;
- mutual support;
- work;
- missions;
- social introduction.

Friendship should emerge gradually unless a major event creates rapid bonding.

## 7.35.15 Friendship Drift

NPC friendships may:
- deepen;
- stabilize;
- weaken;
- become distant.

Absence should not automatically erase close bonds.

## 7.35.16 Rivalry Formation Off-Screen

Rivalry may emerge from:
- repeated competition;
- comparison;
- shared goals;
- jealousy;
- ideological conflict.

The same rivalry rules apply as in player-facing simulation.

## 7.35.17 Romantic Development Off-Screen

NPCs may:
- notice attraction;
- flirt;
- date;
- form relationships;
- reject each other;
- separate.

Important relationships should be stored persistently.

## 7.35.18 Romance Does Not Auto-Pair NPCs

Do not randomly pair available NPCs simply because:
- they are single;
- they spend time together;
- both are attractive.

Romance still requires:
- plausible attraction;
- opportunity;
- mutual interest;
- compatible willingness.

## 7.35.19 Relationship Formation Compression

For off-screen romance, the engine may summarize stages such as:
- attraction developed;
- mutual flirting;
- several dates;
- relationship established.

Detailed scenes should be generated only if:
- player involvement matters;
- major consequences depend on exact events;
- later memory requires specific detail.

## 7.35.20 Conflict Off-Screen

NPCs may:
- argue;
- betray;
- reconcile;
- become estranged.

Important conflict should preserve:
- trigger;
- interpretation;
- relationship effects;
- unresolved issues.

## 7.35.21 Conflict Does Not Require Player Witness

A later interaction may reveal:
- two former friends no longer speak;
- a team became divided;
- a sibling feud worsened.

The change must have a causal history even if the player missed it.

## 7.35.22 Favors and Obligations Off-Screen

NPCs may:
- help each other;
- make promises;
- incur debts;
- repay favors.

Only meaningful obligations require persistent tracking.

## 7.35.23 Rumor Propagation Off-Screen

Ruleset 7.21 may propagate rumors through:
- work networks;
- family;
- markets;
- teams;
- institutions.

The player does not need to witness each transmission.

## 7.35.24 Social Network Growth

NPCs may gain:
- new acquaintances;
- introductions;
- professional contacts;
- family connections;
- romantic-network ties.

Ruleset 7.22 owns the network structure.

## 7.35.25 Group Relationship Change

Teams and institutions may experience:
- Cohesion change;
- faction formation;
- informal leader emergence;
- conflict;
- member integration.

Only socially relevant changes require detailed storage.

## 7.35.26 Important NPC Pair Prioritization

Pairs should receive more attention when they have:
- strong existing relationship;
- active shared context;
- strong conflict;
- mutual attraction;
- shared goal;
- direct impact on player.

Do not process all possible NPC pairs equally.

## 7.35.27 Pair Explosion Prevention

A world with 100 NPCs has thousands of possible pairs.

The engine should process:
- active ties;
- plausible new ties;
- event-relevant pairs;

rather than every combination.

## 7.35.28 Social Radius

Each NPC should have an effective social radius based on:
- routine;
- location;
- work;
- family;
- network;
- status.

Most new relationships should form inside this radius or through bridges.

## 7.35.29 New Connection Generation

A new connection requires a plausible cause:
- introduction;
- workplace;
- mission;
- neighborhood;
- event;
- family;
- shared interest.

Random social generation should remain contextual.

## 7.35.30 Time Compression

Weeks or months may be processed in broader steps.

Example:
- repeated team contact -> increased Familiarity;
- occasional friction -> mild Resentment;
- several positive interactions -> friendship possibility.

Exact daily logs are unnecessary unless events matter.

## 7.35.31 Salience Threshold

Store detailed events when they:
- materially change relationship state;
- create memory;
- create obligation;
- create rumor;
- affect group structure;
- change future decisions.

Routine talk can remain abstract.

## 7.35.32 Hidden Event Record

Important off-screen social events may store:

**Participants**
**Time**
**Context**
**Intent**
**Outcome**
**Relationship changes**
**Memories created**
**Information transferred**
**Obligations created**
**Publicity**
**Future hooks**

## 7.35.33 No Retroactive Convenience

The engine should not invent an off-screen relationship solely because it would now be narratively convenient.

Newly revealed relationships should have:
- plausible prior opportunity;
- stored or reconstructable history;
- consistency with previous states.

## 7.35.34 Soft Reconstruction

For low-detail NPCs, some history may be generated when first needed.

It must remain consistent with:
- age;
- location;
- occupation;
- network;
- previous appearances;
- world events.

This is simulation completion, not arbitrary retconning.

## 7.35.35 Promotion to Higher Detail

When a background NPC becomes important:
- preserve known facts;
- expand relationships;
- generate plausible missing context;
- avoid contradicting prior behavior.

## 7.35.36 Demotion to Lower Detail

When an NPC becomes less relevant:
- preserve core identity;
- major relationships;
- major memories;
- obligations;
- secrets;
- major goals.

Routine details may be compressed.

## 7.35.37 Social Consequence Propagation

An off-screen event may later affect:
- player access;
- NPC mood;
- reputation;
- group cohesion;
- mission cooperation;
- available information.

The player should experience consequences even if they missed the cause.

## 7.35.38 Discovery of Off-Screen Changes

The player may learn through:
- direct conversation;
- gossip;
- changed behavior;
- introductions;
- public events.

The engine should not dump every off-screen update automatically.

## 7.35.39 Surprise Without Arbitrary Twist

Off-screen events may surprise the player.

But surprise should come from:
- hidden state;
- unseen opportunity;
- independent NPC agency;

not arbitrary narrative reversal.

## 7.35.40 Causal Audit

For any major off-screen social change, the engine should be able to answer:
1. Why were these NPCs interacting?
2. What did each want?
3. What relationship existed beforehand?
4. What happened?
5. Why did the relationship change?
6. What consequences persist?

## 7.35.41 NPC Social Scheduling

Some interactions should arise from routine opportunities:
- coworkers see each other;
- families interact;
- teammates train together.

Other interactions require intentional action:
- secret meeting;
- date;
- reconciliation attempt.

## 7.35.42 Initiative

NPCs should independently initiate:
- conversations;
- invitations;
- confrontations;
- favors;
- apologies;
- flirting;
- requests.

Initiation should derive from goals and personality.

## 7.35.43 Missed Opportunities

NPCs may fail to act because of:
- fear;
- shyness;
- lack of time;
- conflicting goals;
- uncertainty.

The engine should not optimize every NPC into perfect social behavior.

## 7.35.44 Coincidence Limits

Chance meetings may occur.

They should be more likely when NPCs:
- share location;
- share routine;
- share network.

Avoid implausible repeated coincidence.

## 7.35.45 Social Event Seeds

The simulation may create potential events from:
- unresolved tension;
- attraction;
- obligation;
- rumor;
- shared goal;
- rivalry.

A seed does not guarantee an event.

Opportunity still matters.

## 7.35.46 Emotional Carryover

NPC emotional state may affect later off-screen interactions.

Example:
- grief makes someone withdraw;
- anger increases confrontation risk;
- excitement increases sociability.

Ruleset 7.8 owns emotion.

## 7.35.47 Physical-State Interface

Ruleset 4 states such as:
- injury;
- pain;
- exhaustion;

may affect:
- availability;
- mood;
- dependence;
- caregiving.

## 7.35.48 Supernatural Influence Interface

Ruleset 3 may alter:
- memory;
- emotion;
- perception;
- agency.

NPC social simulation consumes those altered states without redefining them.

## 7.35.49 Resolution Interface

Ruleset 2 resolves uncertain off-screen outcomes when needed.

For low-stakes events, broad causal resolution may be enough.

Do not roll merely to produce noise.

## 7.35.50 Hidden Rolls

Important off-screen uncertain outcomes may use hidden resolution.

The result should be stored so later consequences remain consistent.

## 7.35.51 Relationship Change Magnitude

Off-screen changes should follow Ruleset 7.11:
- small routine interactions -> small changes;
- meaningful events -> moderate changes;
- major betrayal or sacrifice -> large changes.

No accelerated growth merely because it happened off-screen.

## 7.35.52 NPC Social Autonomy

NPCs may choose outcomes the player dislikes.

They may:
- reject another NPC;
- leave a friend;
- form a romance;
- support a rival;
- reconcile with an enemy.

The world should not preserve NPC availability for the player.

## 7.35.53 Player Relationship Protection Prohibited

Do not freeze NPC relationships because:
- player may want to romance them later;
- player might prefer them single;
- player dislikes another NPC.

NPCs have independent social lives.

## 7.35.54 Canon NPC Handling

Canon NPCs should follow:
- established personality;
- timeline;
- known relationships;

while still allowing causal divergence when the simulation changes circumstances.

## 7.35.55 Canon Relationship Divergence

A canon friendship or romance may change if:
- events differ;
- people die;
- missions change;
- new relationships form;
- beliefs diverge.

Canon should provide baseline, not invulnerability to causality.

## 7.35.56 Background Population Simulation

Large populations should use aggregate social tendencies rather than individual pair simulation.

Examples:
- market gossip;
- academy social climate;
- village support for a leader.

Individuals are expanded only when needed.

## 7.35.57 Social Climate

A group or location may have broad temporary social states such as:
- tense;
- celebratory;
- suspicious;
- grieving;
- politically divided.

These can influence many local interactions without simulating every person.

## 7.35.58 Dormant Relationship Hooks

Some unresolved states may remain dormant:
- old rivalry;
- hidden attraction;
- unpaid favor;
- unresolved betrayal.

They reactivate when relevant opportunity occurs.

## 7.35.59 Long-Term Social Arcs

NPC relationships may evolve over months or years through:
- careers;
- aging;
- family;
- rank;
- trauma;
- shared history.

Long arcs should be built from accumulated events rather than sudden arbitrary state changes.

## 7.35.60 Frequency Control

The simulation should avoid making every off-screen interval full of:
- breakups;
- betrayals;
- dramatic confessions;
- feuds.

Most social life is ordinary.

Major events should remain proportionate to:
- character tendencies;
- opportunity;
- unresolved pressures.

## 7.35.61 Drama Bias Prohibited

Do not generate conflict simply because it is narratively exciting.

Stable friendships and relationships should remain stable when nothing plausibly disrupts them.

## 7.35.62 Positive Off-Screen Development

Off-screen simulation should also produce:
- friendships strengthening;
- reconciliation;
- mentorship;
- support;
- peaceful romance;
- improved group cohesion.

The system should not privilege negative drama.

## 7.35.63 Persistence

All important off-screen changes should update:
- relationship state;
- memories;
- beliefs;
- goals;
- obligations;
- reputation;
- network connections;

as appropriate.

## 7.35.64 Player-Facing Summaries

When useful, the engine may summarize:
- "While you were away, Karn and Rena became noticeably closer."
- "The squad's tension has eased over the last month."

Do not reveal hidden causes or exact values unless the player has access to them.

## 7.35.65 Social Simulation Audit

For an important off-screen development, the engine should be able to answer:

1. Why did these NPCs have contact?
2. What did each NPC want?
3. What prior relationship existed?
4. What meaningful event occurred?
5. Was uncertainty resolved consistently?
6. What changed afterward?
7. What information became known?
8. What future consequences now exist?

## 7.35.66 Design Standard

An NPC-to-NPC simulation mechanic should be rejected or revised if it:
- freezes NPC social lives when off-screen;
- simulates every possible pair;
- randomly creates relationships without opportunity;
- pairs single NPCs automatically;
- invents dramatic conflict for entertainment;
- protects NPCs from relationships because the player may want them later;
- changes relationships faster off-screen than on-screen;
- reveals every off-screen event to the player;
- creates major social changes without a causal history.

## Governing Rule

**NPC-to-NPC social simulation should keep the world socially alive through causal, opportunity-based, relevance-weighted development, preserving important consequences while compressing routine interaction and refusing to center every relationship around the player.**
