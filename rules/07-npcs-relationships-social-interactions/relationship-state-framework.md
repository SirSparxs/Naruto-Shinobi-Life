# 7.9 — Relationship State Framework

Status: Provisional design section pending explicit approval.

Ruleset 7.9 defines the architecture used to represent persistent relationships between individuals.

The governing principle is:

**A relationship is a structured collection of independent but interacting interpersonal states, memories, expectations, and history—not a single approval meter.**

Detailed definitions of individual relationship dimensions are owned by Ruleset 7.10.

## 7.9.1 Relationship Objects

When a relationship becomes persistent enough to matter, the simulation may create a relationship object between two characters.

A relationship object may contain:
- relationship dimensions;
- relationship category labels where useful;
- major shared memories;
- current unresolved conflicts;
- promises, favors, debts, and obligations;
- romantic status where relevant;
- relationship expectations;
- important boundaries;
- recent trajectory;
- hidden interpretations;
- notable asymmetries.

The relationship object does not replace the two individual NPC profiles.

It represents the interpersonal state between them.

## 7.9.2 Relationships Are Directional

Relationships should usually be tracked directionally.

Example:

**Rex -> Karn**
- high trust;
- moderate respect;
- high affection.

**Karn -> Rex**
- moderate trust;
- high respect;
- moderate affection;
- mild resentment.

These do not have to match.

A relationship may be strongly asymmetric.

## 7.9.3 No Universal Relationship Score

There should be no single number such as:

**Relationship = 82/100**

A single score would incorrectly imply that:
- affection cancels resentment;
- fear creates loyalty;
- trust creates romantic interest;
- sexual chemistry creates affection;
- obligation creates friendship.

Instead, different interpersonal dimensions coexist.

## 7.9.4 Core Relationship Dimensions

Ruleset 7.10 should define at minimum:
- Trust;
- Respect;
- Affection / Attachment;
- Loyalty;
- Fear;
- Familiarity;
- Obligation / Indebtedness;
- Resentment;
- Hostility;
- Romantic Interest;
- Adult Arousal / Sexual Chemistry where applicable.

Some dimensions may be inactive or irrelevant in many relationships.

## 7.9.5 Optional vs Universal Dimensions

Not every relationship needs every axis instantiated.

Likely near-universal axes:
- familiarity;
- trust;
- respect;
- affection;
- resentment / hostility.

Conditional axes:
- loyalty;
- obligation;
- romantic interest;
- adult arousal / sexual chemistry;
- fear.

The engine may omit dormant dimensions until they become relevant.

## 7.9.6 Dimension Independence

Relationship dimensions should influence one another but remain conceptually separate.

Examples:
- betrayal can reduce Trust while Affection remains high;
- repeated competence can raise Respect without increasing Affection;
- intimidation can raise Fear while lowering Trust;
- romance can increase Affection without creating Loyalty;
- adult sexual chemistry may increase while romantic interest remains low.

No dimension automatically substitutes for another.

## 7.9.7 Relationship Categories Are Derived Labels

Labels such as:
- stranger;
- acquaintance;
- friend;
- close friend;
- best friend;
- rival;
- enemy;
- mentor;
- student;
- teammate;
- romantic interest;
- partner;
- spouse;
- ex-partner;

should describe the relationship rather than replace the underlying state.

A label may carry social expectations, but the actual relationship dimensions still determine behavior.

## 7.9.8 Multiple Relationship Categories

A relationship may fit several categories simultaneously.

Examples:
- teammate + rival + friend;
- mentor + family member;
- spouse + political ally;
- ex-partner + teammate;
- enemy + respected rival.

The system should allow layered relationships.

## 7.9.9 Relationship History

Current state should not erase history.

A relationship object may preserve:
- how they met;
- major turning points;
- betrayals;
- reconciliations;
- important favors;
- shared danger;
- romantic milestones;
- major conflicts.

Two relationships with identical current Trust may still behave differently because their histories differ.

## 7.9.10 Relationship Trajectory

The simulation should track recent direction.

Examples:
- improving rapidly;
- slowly warming;
- stable;
- cooling;
- deteriorating;
- volatile;
- recovering after rupture.

Trajectory influences expectations.

A Trust value that recently fell sharply should feel different from the same level that has been stable for years.

## 7.9.11 Relationship Stability

Some relationships are more stable than others.

Stability may depend on:
- duration;
- repeated reinforcement;
- shared history;
- emotional intensity;
- institutional ties;
- family ties;
- commitment;
- unresolved conflict.

A ten-year friendship should generally resist small fluctuations more than a new acquaintance relationship.

## 7.9.12 Relationship Inertia

Established relationships should possess inertia.

Small events may have limited effect when:
- history is extensive;
- expectations are well-established;
- trust has been repeatedly tested.

New relationships should be more volatile because less history exists.

Inertia should not provide immunity to major betrayal.

## 7.9.13 Relationship Expectations

Characters may develop expectations such as:
- honesty;
- exclusivity;
- emotional support;
- professional conduct;
- availability;
- loyalty;
- discretion;
- mutual aid.

Violation severity depends partly on what was expected.

The same action can be harmless in one relationship and deeply hurtful in another.

## 7.9.14 Explicit and Implicit Expectations

Expectations may be:
- explicitly discussed;
- culturally assumed;
- inferred from prior behavior;
- incorrectly assumed.

Misaligned expectations can create conflict even when neither character intended harm.

## 7.9.15 Relationship Boundaries

Relationships may include boundaries involving:
- privacy;
- physical contact;
- secrets;
- money;
- mission information;
- public behavior;
- romance;
- adult sexual behavior;
- exclusivity;
- family involvement.

Boundaries may differ by character and relationship.

## 7.9.16 Boundary Knowledge

A boundary only influences intentional behavior if the other person knows or reasonably infers it.

Unknown boundaries may be crossed accidentally.

The resulting reaction can still matter.

## 7.9.17 Mutual vs One-Sided State

Some relationship features may be mutual.

Others may be one-sided.

Examples:
- one-sided friendship;
- one-sided rivalry;
- unrequited romantic interest;
- one-sided loyalty;
- one-sided resentment;
- adult sexual attraction that is not reciprocated.

The system should never assume reciprocity.

## 7.9.18 Relationship Context

One relationship may behave differently across contexts.

Examples:
- close friends privately;
- highly formal at work;
- competitive during training;
- secret romantic relationship publicly concealed.

Context does not create a second relationship.
It changes expression.

## 7.9.19 Public Relationship vs Private Relationship

The world may perceive a relationship differently from its true state.

Example:
Publicly:
- professional teammates.

Privately:
- romantic partners.

Track:
- actual relationship;
- publicly known status;
- suspected status;
- false public narrative where relevant.

## 7.9.20 Relationship Knowledge

Characters may misunderstand their own relationship.

Examples:
- one believes they are close friends;
- the other sees them as a useful acquaintance.

Or:
- one believes a relationship is exclusive;
- the other believes it is casual.

These mismatches can create conflict.

## 7.9.21 Relationship Salience

Not every relationship occupies equal mental importance.

Salience may depend on:
- intimacy;
- frequency of interaction;
- emotional intensity;
- conflict;
- obligation;
- family;
- danger;
- romance;
- shared goals.

Higher-salience relationships influence decisions more often.

## 7.9.22 Relationship Priority

When relationships conflict, an NPC may prioritize one over another.

Examples:
- sibling vs teammate;
- spouse vs village commander;
- mentor vs clan;
- close friend vs political ally.

Priority is not fixed and may depend on the situation.

## 7.9.23 Relationship Networks

A relationship does not exist in isolation.

Other relationships may affect it through:
- shared friends;
- family;
- teams;
- clans;
- gossip;
- rivalry;
- romantic competition;
- institutional pressure.

Detailed network mechanics are developed later.

## 7.9.24 Relationship Spillover

Behavior toward one person may influence relationships with others.

Examples:
- betraying a teammate reduces trust from the rest of the team;
- helping a sibling increases family goodwill;
- insulting a clan elder harms relations with loyal relatives.

Spillover should require plausible awareness and relevance.

## 7.9.25 Relationship State vs Current Emotion

Persistent relationship dimensions are distinct from current emotions.

Example:
An NPC may have:
- high Affection;
- high Trust;
- currently intense Anger.

The anger may fade while the underlying relationship remains strong.

Likewise, temporary attraction or arousal does not automatically rewrite the persistent relationship.

## 7.9.26 Relationship State vs Memory

Relationship state is influenced by memory but is not identical to it.

A memory explains:
- what happened.

Relationship state summarizes:
- what that history currently means interpersonally.

The system should preserve important memories even after dimensions stabilize.

## 7.9.27 Relationship State vs Reputation

Relationship state is personal.

Reputation is broader social belief.

An NPC may personally trust someone with a terrible public reputation.

Or distrust someone universally considered heroic.

## 7.9.28 Relationship Change Inputs

Relationship dimensions may change from:
- direct actions;
- observed behavior;
- promises;
- betrayal;
- shared hardship;
- gifts;
- lies;
- support;
- conflict;
- rescue;
- intimacy;
- humiliation;
- reputation information;
- third-party testimony.

Detailed change mechanics belong to Ruleset 7.11.

## 7.9.29 Relationship Thresholds

Certain ranges may qualitatively change behavior.

Examples:
- sufficient Trust allows sharing sensitive information;
- severe Hostility makes voluntary cooperation unlikely;
- strong Loyalty increases willingness to accept risk;
- meaningful Romantic Interest permits courtship to become plausible.

Thresholds should unlock possibilities, not force outcomes.

## 7.9.30 Relationship Contradictions

Relationships may contain apparently contradictory states.

Examples:
- high Affection + high Resentment;
- high Respect + high Hostility;
- high Loyalty + low Trust;
- high Romantic Interest + low compatibility;
- high adult sexual chemistry + low Affection;
- high Fear + high Respect.

These combinations are valid and often dramatically useful.

## 7.9.31 Relationship Ambivalence

When opposing dimensions are both strong, the relationship may become ambivalent.

Ambivalence may cause:
- inconsistent approach/avoidance;
- emotional volatility;
- indecision;
- recurring conflict;
- difficulty ending the relationship.

Ambivalence should emerge from state rather than be a separate universal meter.

## 7.9.32 Relationship Formation

New relationships begin with:
- initial familiarity;
- first impressions;
- reputation;
- context;
- prior information;
- cultural expectations.

They should not begin at universal neutral zero.

A clan member may begin with assumed familiarity or obligation.
A feared missing-nin may begin with negative expectations.

## 7.9.33 Relationship Baselines

Initial state may be influenced by:
- kinship;
- shared clan;
- shared village;
- profession;
- rank;
- known reputation;
- prior rumor;
- social norms.

Baseline does not equal permanent state.

Experience can override assumptions.

## 7.9.34 Relationship Decay

Some dimensions may naturally weaken without reinforcement.

Examples:
- Familiarity;
- active Affection;
- obligation salience;
- romantic interest.

Others may persist strongly:
- deep Trust;
- severe betrayal;
- family Loyalty;
- major Resentment.

Detailed decay rates belong to Ruleset 7.11.

## 7.9.35 Relationship Persistence Across Absence

Distance should not reset relationships.

An NPC absent for years may retain:
- affection;
- resentment;
- loyalty;
- history;
- unresolved promises.

However, current knowledge and expectations may become outdated.

## 7.9.36 Relationship Compression

Low-relevance relationships may be compressed.

Example:
Instead of storing every axis precisely:

**Former academy classmate; friendly, moderate trust, little current contact, no unresolved issues.**

If relevance increases, the relationship can be expanded conservatively.

## 7.9.37 Relationship Promotion

When a relationship becomes important:
- preserve prior facts;
- preserve major memories;
- infer only missing state consistent with history;
- do not retroactively create intimacy or hostility without basis.

## 7.9.38 Canon Relationships

Canon relationships should begin from established state appropriate to the current timeline.

After divergence, they may evolve normally.

Canon labels should not override actual simulated development.

## 7.9.39 Player-Facing Relationship Information

Exact internal relationship dimensions should generally remain hidden.

The player receives:
- behavior;
- dialogue;
- tone;
- willingness;
- known history;
- explicit statements;
- social cues.

The player may misread the relationship.

## 7.9.40 Debug / Developer Representation

For internal development or debugging, a relationship may be represented explicitly.

Example:

**Rex -> Karn**
- Trust: High
- Respect: Moderate
- Affection: High
- Loyalty: High
- Fear: None
- Familiarity: Very High
- Obligation: Low
- Resentment: Mild
- Romantic Interest: None
- Adult Arousal: N/A

This representation should not normally be visible during gameplay.

## 7.9.41 Design Standard

A relationship framework should be rejected or revised if it:
- collapses relationships into one approval score;
- assumes reciprocity;
- treats labels as more important than actual dimensions;
- erases history when current state changes;
- confuses current emotion with persistent relationship;
- assumes romantic interest from affection;
- assumes consent from attraction or adult arousal;
- makes all relationships begin at identical neutral state;
- prevents contradictory feelings;
- ignores expectations and boundaries;
- reveals hidden relationship state automatically;
- requires full multidimensional tracking for every incidental NPC.

## Governing Rule

**Relationships should be persistent, directional, multi-dimensional, historically grounded, and capable of contradiction, with labels describing the relationship rather than controlling it.**
