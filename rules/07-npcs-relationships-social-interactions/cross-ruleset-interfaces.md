# 7.42 — Cross-Ruleset Interfaces

Status: Provisional design section pending explicit approval.

Ruleset 7.42 defines the ownership boundaries and data exchanges between NPCs/relationships/social interaction systems and the rest of Naruto: Shinobi Life.

The governing principle is:

**Each mechanic should have one primary ruleset owner. Ruleset 7 may consume, influence, or expose state from other systems, but it should not duplicate their core mechanics or silently override their rules.**

## 7.42.1 Scope

This section defines interfaces with:
- Ruleset 1 — Character Growth;
- Ruleset 2 — Resolution, Probability & Difficulty;
- Ruleset 3 — Chakra, Jutsu & Special Abilities;
- Ruleset 4 — Combat, Injuries & Medicine;
- future mission systems;
- organizations and institutions;
- economy and resources;
- law and crime;
- travel and location;
- world simulation;
- procedural generation;
- save-state architecture.

## 7.42.2 Primary-Owner Rule

When two rulesets touch the same event:

1. determine which ruleset owns the underlying mechanic;
2. let that ruleset resolve or define the state;
3. let Ruleset 7 consume the result socially;
4. store only the social consequences Ruleset 7 actually owns.

Example:
- injury severity -> Ruleset 4;
- whether injury causes fear, dependence, gratitude, or relationship strain -> Ruleset 7.

## 7.42.3 No Duplicate Mechanics

Ruleset 7 should not independently recreate:
- attribute progression;
- probability formulas;
- chakra cost;
- injury severity;
- legal sentencing;
- money balances;
- travel time;
- institutional promotions.

It should reference those systems.

# Interface with Ruleset 1 — Character Growth

## 7.42.4 What Ruleset 1 Owns

Ruleset 1 owns:
- core Attributes;
- Skills;
- skill XP;
- mastery;
- tiers;
- training;
- potential;
- prerequisites;
- age/rank soft limits;
- progression rates.

## 7.42.5 What Ruleset 7 Uses From Ruleset 1

Ruleset 7 consumes:
- Intelligence;
- Perception;
- Willpower;
- Strength;
- Agility;
- Endurance where socially relevant;
- social-skill mastery;
- relevant specializations;
- learned cultural or professional competencies where defined.

## 7.42.6 Social Skills Stay Ruleset 1 Skills

Skills such as:
- Persuasion;
- Negotiation;
- Deception;
- Insight;
- Etiquette;
- Leadership;
- Intimidation;
- Teaching;
- Interrogation;
- Performance;
- Diplomacy;
- adult Seduction;

may be defined conceptually in Ruleset 7 but mechanically belong to Ruleset 1's skill framework.

## 7.42.7 No Social Attribute

Ruleset 7 must not introduce a hidden universal:
- Charisma;
- Social Power;
- Influence stat.

Social effectiveness comes from:
- relevant skill;
- relevant attribute;
- relationship;
- context;
- reputation;
- leverage;
- plausibility.

## 7.42.8 Skill Growth Interface

Ruleset 7 provides:
- action category;
- skill actually practiced;
- difficulty;
- feedback quality;
- relevance;
- consequences.

Ruleset 1 decides:
- whether XP/progression occurs;
- amount;
- tier advancement;
- mastery;
- prerequisite checks.

## 7.42.9 Relationship Familiarity Is Not Global Skill

Knowing one person well may improve social interpretation of that person.

This should be a Ruleset 7 relationship/context benefit.

It should not silently increase global Insight or Persuasion.

# Interface with Ruleset 2 — Resolution, Probability & Difficulty

## 7.42.10 What Ruleset 2 Owns

Ruleset 2 owns:
- uncertainty resolution;
- difficulty;
- probability;
- opposed checks;
- hidden checks;
- degrees of success;
- failure;
- exceptional outcomes.

## 7.42.11 What Ruleset 7 Sends to Ruleset 2

Ruleset 7 defines:
- social intent;
- desired outcome;
- possibility boundaries;
- baseline willingness/resistance;
- relevant skill;
- relevant attribute;
- contextual factors;
- target opposition;
- stakes.

Ruleset 2 then resolves uncertainty.

## 7.42.12 What Ruleset 2 Returns

Ruleset 2 may return:
- strong failure;
- failure;
- partial success;
- success;
- exceptional success;

or whatever final generic degree structure Ruleset 2 establishes.

Ruleset 7 interprets that result socially.

## 7.42.13 Possibility Before Probability

Ruleset 7 must determine whether an outcome is socially possible before asking Ruleset 2 to roll.

Examples:
- persuading someone to consider a plausible compromise -> potentially resolvable;
- socially rolling to force attraction after firm rejection -> not a valid outcome;
- interrogating someone for information they do not know -> impossible to obtain as truth.

Impossible outcomes should not receive high-difficulty checks.

## 7.42.14 Outcome Meaning Belongs to Ruleset 7

Ruleset 2 says how well the uncertain attempt resolved.

Ruleset 7 determines what that means in terms of:
- cooperation;
- hesitation;
- Trust;
- Resentment;
- information disclosure;
- relationship change.

## 7.42.15 Hidden Social Checks

Ruleset 2 may resolve hidden:
- Insight;
- deception detection;
- rumor credibility;
- concealed emotion;
- NPC belief formation.

Ruleset 7 determines player-facing social feedback.

# Interface with Ruleset 3 — Chakra, Jutsu & Special Abilities

## 7.42.16 What Ruleset 3 Owns

Ruleset 3 owns:
- chakra mechanics;
- jutsu;
- genjutsu;
- mind-affecting abilities;
- memory-altering abilities;
- emotional manipulation through chakra;
- compulsion;
- supernatural sensory abilities;
- sealing effects.

## 7.42.17 Mundane Social Influence vs Supernatural Control

Ruleset 7 owns ordinary:
- persuasion;
- deception;
- intimidation;
- attraction;
- social pressure.

Ruleset 3 owns any ability that explicitly:
- compels behavior;
- alters memory;
- forces emotion;
- controls perception;
- suppresses agency through chakra.

## 7.42.18 Jutsu Must Explicitly Define Agency Effects

Ruleset 7 should not assume that a genjutsu can:
- force obedience;
- manufacture love;
- compel confession;

unless Ruleset 3 explicitly defines that capability.

## 7.42.19 Social Consequences of Supernatural Influence

After Ruleset 3 resolves an effect, Ruleset 7 may handle:
- fear;
- betrayal;
- Trust damage;
- stigma;
- relationship consequences;
- changed beliefs;
- social response after discovery.

## 7.42.20 Memory Alteration

If Ruleset 3 changes memory:
- Ruleset 3 owns what memory was altered;
- Ruleset 7.7 consumes the resulting memory state;
- Ruleset 7.6 updates beliefs/knowledge;
- Ruleset 7.41 persists the new state.

## 7.42.21 Emotion Manipulation

If a jutsu creates:
- fear;
- calm;
- anger;
- attraction-like sensation;

Ruleset 3 owns the supernatural effect.

Ruleset 7.8 tracks resulting emotional state where applicable.

The effect must not be silently reinterpreted as ordinary genuine relationship development.

## 7.42.22 Supernatural Attraction Is Not Relationship State by Default

A supernatural effect producing desire or fixation should remain tagged as:
- induced;
- externally caused;

unless later genuine relationship change occurs independently.

## 7.42.23 Chakra Signatures and Social Knowledge

If characters can identify:
- chakra signatures;
- genjutsu traces;
- clan techniques;

Ruleset 3 owns detection capability.

Ruleset 7.6 owns what social belief or knowledge results.

# Interface with Ruleset 4 — Combat, Injuries & Medicine

## 7.42.24 What Ruleset 4 Owns

Ruleset 4 owns:
- wounds;
- pain;
- fatigue;
- impairment;
- medical treatment;
- recovery;
- incapacitation;
- physical aftermath;
- captivity-related physical state.

## 7.42.25 Physical State Influences Social Context

Ruleset 7 may consume:
- pain;
- exhaustion;
- injury;
- medication effects;
- recovery status;

as context affecting:
- patience;
- availability;
- emotional regulation;
- dependence;
- vulnerability;
- communication.

## 7.42.26 No Social Override of Medical State

Persuasion cannot:
- heal injury;
- remove fatigue;
- erase pain;

unless another owned mechanic explicitly allows it.

Social support may affect morale or willingness, not underlying wound severity.

## 7.42.27 Caregiving

Ruleset 4 determines:
- what care is medically required;
- recovery needs.

Ruleset 7 determines:
- who helps;
- gratitude;
- caregiver strain;
- Attachment;
- resentment;
- obligation.

## 7.42.28 Pain, Coercion & Interrogation

Ruleset 4 determines physical consequences of:
- torture;
- deprivation;
- exhaustion.

Ruleset 7 determines:
- fear;
- false confession risk;
- willingness;
- resentment;
- relationship consequences.

Ruleset 2 resolves uncertainty where needed.

## 7.42.29 Captivity

Physical restraint and injury state belong to Ruleset 4 or future captivity systems.

Ruleset 7 governs:
- coercion;
- interrogation;
- power imbalance;
- social response;
- apparent compliance.

# Interface with Future Mission Systems

## 7.42.30 Mission System Owns

A future mission system should own:
- mission generation;
- assignment;
- objectives;
- formal success/failure;
- rewards;
- mission logistics.

## 7.42.31 Ruleset 7 Mission Effects

Ruleset 7 handles:
- teammate Trust;
- leadership confidence;
- rivalry;
- gratitude;
- blame;
- reputation;
- promises;
- betrayal;
- shared hardship;
- social consequences of decisions.

## 7.42.32 Mission Eligibility

Social state may affect:
- recommendation;
- willingness to work together;
- informal assignment preference.

Formal eligibility remains with mission/institution systems.

## 7.42.33 Shared Mission History

Ruleset 7 may preserve socially meaningful mission history:
- rescue;
- abandonment;
- sacrifice;
- repeated reliable teamwork.

Do not duplicate full mission logs.

# Interface with Organizations & Institutions

## 7.42.34 Institutional Systems Own

Future organization systems should own:
- formal membership;
- rank;
- promotion;
- command chain;
- office;
- formal authority;
- expulsion;
- institutional policy.

## 7.42.35 Ruleset 7 Owns Subjective Group Relationship

Ruleset 7 owns:
- belonging;
- loyalty;
- legitimacy;
- resentment;
- informal standing;
- cohesion;
- informal leaders;
- faction relationships.

## 7.42.36 Formal Rank vs Social Legitimacy

Institution system:
- "This person is captain."

Ruleset 7:
- "Do people actually trust, respect, or follow them?"

These must remain separate.

## 7.42.37 Institutional Access

Institution systems own official clearance.

Ruleset 7 may affect:
- who recommends;
- who vouches;
- how quickly a meeting occurs;
- informal treatment.

Friendship cannot silently grant formal clearance.

# Interface with Economy & Resources

## 7.42.38 Economy System Owns

Future economy systems should own:
- money;
- prices;
- wages;
- debt balances;
- property;
- inventory;
- market transactions.

## 7.42.39 Ruleset 7 Economic Social Effects

Ruleset 7 handles:
- gifts;
- generosity;
- hospitality;
- lending willingness;
- favors;
- patronage;
- financial dependence;
- reputation from economic behavior.

## 7.42.40 Gift Meaning vs Gift Value

Economy system determines:
- objective cost/value.

Ruleset 7 determines:
- personal meaning;
- appropriateness;
- gratitude;
- social interpretation.

Expensive does not automatically mean socially effective.

## 7.42.41 Formal Debt vs Social Debt

Economy system:
- financial debt.

Ruleset 7:
- gratitude debt;
- favor;
- obligation.

They may coexist but should not be conflated.

# Interface with Law, Crime & Justice

## 7.42.42 Legal System Owns

Future law systems should own:
- laws;
- arrest;
- prosecution;
- sentencing;
- legal status;
- warrants;
- formal penalties.

## 7.42.43 Ruleset 7 Legal Social Effects

Ruleset 7 handles:
- stigma;
- fear;
- reputation;
- witness willingness;
- family reaction;
- ostracism;
- loyalty conflict;
- social consequences after accusation or conviction.

## 7.42.44 Accusation vs Conviction

Ruleset 7 must distinguish:
- rumor;
- accusation;
- evidence;
- official finding.

Social reaction may begin before legal resolution.

## 7.42.45 Witness Cooperation

Ruleset 7 may govern:
- willingness to report;
- fear of retaliation;
- loyalty;
- credibility judgments.

The legal system governs formal evidentiary procedure.

# Interface with Travel & Location

## 7.42.46 Travel System Owns

Future travel systems should own:
- travel time;
- route;
- distance;
- movement speed;
- transportation;
- encounter generation where appropriate.

## 7.42.47 Ruleset 7 Uses Location

Ruleset 7 consumes location to determine:
- social opportunity;
- availability;
- chance meetings;
- rumor pathways;
- long-distance strain;
- network access.

## 7.42.48 Distance Is Not Social Decay by Itself

Travel/location provides actual separation.

Ruleset 7 determines whether that separation affects:
- contact;
- Attachment;
- Satisfaction;
- rumor delay;
- social opportunity.

## 7.42.49 Communication Systems

If future systems define:
- mail;
- messenger animals;
- radio;
- chakra communication;

those systems own:
- speed;
- reliability;
- interception.

Ruleset 7 owns:
- message meaning;
- disclosure;
- response;
- relationship effect.

# Interface with World Simulation

## 7.42.50 World System Owns

Future world simulation may own:
- wars;
- disasters;
- economic shifts;
- political change;
- demographics;
- settlement state;
- major public events.

## 7.42.51 Ruleset 7 Social Response

Ruleset 7 consumes world events to update:
- fear;
- grief;
- group loyalty;
- rumor;
- reputation;
- social networks;
- routines;
- relationships;
- migration-related ties.

## 7.42.52 Public Events Do Not Create Universal Knowledge

Even major world events must still propagate through:
- witnesses;
- announcements;
- rumor;
- institutions.

Ruleset 7.6 and 7.21 govern individual knowledge and spread.

## 7.42.53 Social Climate

Ruleset 7 may maintain local social climate such as:
- tense;
- celebratory;
- grieving;
- suspicious.

World systems provide the causes.

# Interface with Procedural Generation

## 7.42.54 Procedural System Role

Ruleset 7.40 may generate social components of NPCs.

Other systems may generate:
- combat build;
- jutsu;
- economy;
- location;
- institutional role.

## 7.42.55 Generation Must Be Cross-System Coherent

Example:
If Ruleset 1/3 generates:
- elite medic specialization;

Ruleset 7 should plausibly generate:
- hospital connections;
- medical colleagues;
- appropriate reputation;
- relevant routine.

## 7.42.56 Social Generation Cannot Override Mechanical Validity

Ruleset 7 cannot invent:
- impossible rank;
- invalid jutsu;
- impossible mastery;

to support a desired social backstory.

Other owner rulesets validate those states.

# Interface with Save-State Architecture

## 7.42.57 Persistence Ownership

Ruleset 7.41 defines what social information must persist.

A technical save system owns:
- serialization;
- file format;
- versioning implementation;
- validation;
- loading.

## 7.42.58 Hidden vs Player-Visible State

Technical persistence should support:
- internal GM state;
- player-facing known state.

Ruleset 7 defines which social information belongs in each.

## 7.42.59 Already-Resolved Outcomes Must Persist

Save systems must preserve:
- hidden social checks;
- established beliefs;
- relationship changes;
- promises;
- rumors;
- NPC decisions.

Reloading must not reroll established social reality.

# Generic Interface Procedure

## 7.42.60 Cross-Ruleset Event Procedure

When a social event touches another ruleset:

1. identify the underlying mechanic;
2. identify primary owner;
3. obtain current external state;
4. determine social interpretation/context;
5. resolve uncertainty through Ruleset 2 if needed;
6. let primary owner apply non-social mechanical changes;
7. apply Ruleset 7 social consequences;
8. persist both sides through their relevant storage systems.

## 7.42.61 Example — Injured Teammate Rescue

Ruleset 4:
- injury severity;
- treatment;
- survival.

Ruleset 7:
- fear;
- gratitude;
- obligation;
- Trust;
- shared memory;
- reputation among witnesses.

Ruleset 2:
- any uncertain treatment or social response checks.

## 7.42.62 Example — Genjutsu Coercion

Ruleset 3:
- whether genjutsu compels or alters perception.

Ruleset 2:
- resistance/resolution if defined there.

Ruleset 7:
- resulting fear;
- perceived betrayal;
- relationship damage;
- beliefs after recovery.

## 7.42.63 Example — Promotion

Institution system:
- promotion occurs.

Ruleset 1:
- no automatic skill gain unless progression rules justify it.

Ruleset 7:
- status change;
- altered routine;
- peer reactions;
- jealousy;
- authority;
- new social access.

## 7.42.64 Example — Gift

Economy:
- item ownership/value transfer.

Ruleset 7:
- meaning;
- gratitude;
- obligation if any;
- romantic interpretation;
- reputation.

## 7.42.65 Example — Criminal Accusation

Legal system:
- investigation/status.

Ruleset 7:
- rumor spread;
- social distrust;
- witness response;
- family reaction;
- ostracism.

# Ownership Conflict Rules

## 7.42.66 If Two Rulesets Claim Ownership

Prefer the rule that describes the underlying physical/mechanical reality.

Ruleset 7 generally owns:
- interpretation;
- relationship;
- belief;
- social consequence.

## 7.42.67 Social Consequence Does Not Rewrite Source State

Example:
If someone believes an injured character is dying but Ruleset 4 says they are stable:
- Ruleset 7 stores the mistaken belief;
- it does not change the medical reality.

## 7.42.68 Source State Can Change Social State

If external systems change:
- rank;
- wealth;
- injury;
- location;
- legal status;

Ruleset 7 reevaluates relevant:
- reputation;
- availability;
- opportunity;
- relationships;
- expectations.

## 7.42.69 Social State Can Influence External Decisions Without Owning Them

Example:
High reputation may influence whether an institution considers a promotion.

Ruleset 7 supplies:
- recommendation;
- reputation;
- relationships.

Institution rules decide:
- promotion.

## 7.42.70 No Circular Auto-Boosting

Avoid loops such as:
- high rank -> automatic Respect;
- Respect -> automatic promotion;
- promotion -> more automatic Respect.

Each transition needs causal justification and owner-system logic.

## 7.42.71 Interface Data Should Be Minimal

Rulesets should exchange only necessary state.

Do not copy entire external-system records into Ruleset 7.

Reference:
- injury status;
- rank;
- location;
- wealth category;

only when socially relevant.

## 7.42.72 Cross-Ruleset Audit

For a mechanic touching multiple systems, the engine should answer:

1. What is the underlying mechanic?
2. Which ruleset owns it?
3. What state does Ruleset 7 consume?
4. What social state does Ruleset 7 produce?
5. Does Ruleset 2 need to resolve uncertainty?
6. Are any effects being duplicated?
7. Is social interpretation being mistaken for objective reality?
8. Which system persists each result?

## 7.42.73 Design Standard

A cross-ruleset interface should be rejected or revised if it:
- gives one mechanic multiple competing owners;
- lets Ruleset 7 recreate another ruleset's progression or physics;
- allows social skill to bypass mechanical prerequisites;
- treats supernatural compulsion as ordinary persuasion;
- lets friendship override formal institutional rules automatically;
- lets social belief rewrite objective physical state;
- rerolls already-resolved external outcomes;
- duplicates full external records inside social storage;
- creates circular automatic bonuses without causal steps.

## Governing Rule

**Ruleset 7 should own social meaning, relationship state, belief, influence, and interpersonal consequence while consuming objective states from the systems that own progression, resolution, chakra, injury, institutions, economy, law, travel, and world events.**
