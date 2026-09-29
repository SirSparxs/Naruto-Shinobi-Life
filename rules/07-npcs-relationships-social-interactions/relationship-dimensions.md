# 7.10 — Relationship Dimensions

Status: Provisional design section pending explicit approval.

Ruleset 7.10 defines the persistent interpersonal dimensions used inside relationship objects.

The governing principle is:

**Each relationship dimension answers a different question. No dimension may silently substitute for another.**

A relationship should be capable of representing contradictory, asymmetric, and evolving states without collapsing them into one overall score.

## 7.10.1 Internal Representation

Relationship dimensions may use hidden internal values for simulation precision.

A recommended implementation is a bounded scale such as:

- 0–19: negligible / absent
- 20–39: low
- 40–59: moderate
- 60–79: high
- 80–100: very high / extreme

These values are primarily an internal engine representation.

Normal gameplay should usually communicate relationship state through:
- behavior;
- dialogue;
- decisions;
- willingness;
- remembered history;
- observable social cues.

The player should not normally see exact numerical values.

## 7.10.2 Zero Does Not Always Mean Opposite

Most relationship axes represent the presence of a state rather than a bipolar spectrum.

Examples:

- Trust 0 does not automatically mean hatred.
- Affection 0 does not automatically mean hostility.
- Loyalty 0 does not automatically mean betrayal.
- Fear 0 does not automatically mean courage.
- Romantic Interest 0 does not automatically mean disgust.
- Adult Arousal 0 does not automatically mean sexual aversion.

Negative interpersonal states are represented separately where needed.

This prevents false equivalencies.

# 7.10.3 Trust

Trust answers:

**How willing is this person to rely on the other person's honesty, judgment, intentions, discretion, or behavior?**

Trust may be domain-specific.

An NPC may trust someone:
- with secrets;
- in combat;
- with money;
- with emotional vulnerability;
- with children;
- with mission judgment;

to very different degrees.

### Low Trust
May produce:
- verification;
- guarded disclosure;
- contingency planning;
- skepticism;
- reluctance to become vulnerable.

### High Trust
May produce:
- accepting claims with less verification;
- sharing sensitive information;
- delegating important tasks;
- vulnerability;
- reliance during danger.

### Trust Increases Through
- kept promises;
- repeated honesty;
- discretion;
- reliability;
- successful cooperation;
- admitting mistakes;
- protecting vulnerability.

### Trust Decreases Through
- lies;
- broken promises;
- betrayal;
- reckless judgment;
- exposed secrets;
- manipulation;
- unexplained inconsistency.

Trust does not imply:
- affection;
- loyalty;
- obedience;
- romance;
- agreement.

Someone may trust an enemy to keep their word.

## 7.10.4 Respect

Respect answers:

**How highly does this person regard the other's capability, character, judgment, achievements, status, or principles?**

Respect may be based on:
- competence;
- courage;
- discipline;
- intelligence;
- integrity;
- leadership;
- rank;
- achievement;
- adherence to values.

Respect may be reluctant.

An NPC may deeply respect someone they dislike.

### Low Respect
May cause:
- dismissal;
- condescension;
- reduced weight given to advice;
- underestimation.

### High Respect
May cause:
- serious consideration of advice;
- willingness to learn;
- deference in relevant domains;
- admiration of achievement.

Respect does not imply:
- affection;
- trust;
- fear;
- loyalty;
- moral approval.

## 7.10.5 Affection / Attachment

Affection answers:

**How emotionally fond, caring, or attached is this person toward the other?**

Affection may appear in:
- family;
- friendship;
- mentorship;
- romance;
- chosen family.

### Low Affection
Means little emotional attachment.

It does not necessarily mean dislike.

### High Affection
May produce:
- concern for wellbeing;
- desire for contact;
- patience;
- emotional investment;
- comfort;
- protectiveness;
- grief if the person is harmed.

Affection can remain high during:
- arguments;
- betrayal;
- separation;
- resentment.

Affection does not imply:
- trust;
- romantic interest;
- sexual attraction;
- loyalty;
- consent.

## 7.10.6 Loyalty

Loyalty answers:

**How strongly does this person feel committed to standing by, protecting, supporting, or remaining aligned with the other person?**

Loyalty is more behavioral and commitment-oriented than Affection.

Sources may include:
- love;
- friendship;
- shared hardship;
- oath;
- duty;
- gratitude;
- identity;
- ideology.

### Low Loyalty
The person feels little obligation to remain aligned.

### High Loyalty
May increase willingness to:
- defend;
- keep secrets;
- remain during hardship;
- accept personal cost;
- resist outside pressure.

Loyalty can exist without trust.

Example:
A shinobi may remain loyal to a commander while believing the commander's judgment is poor.

Loyalty does not guarantee unlimited obedience.

Moral boundaries, stronger loyalties, or extreme conflict can override it.

## 7.10.7 Fear

Fear answers:

**How strongly does this person perceive the other as personally threatening or dangerous?**

Fear may come from:
- physical danger;
- political power;
- unpredictability;
- cruelty;
- social power;
- prior trauma;
- credible threats.

### Low Fear
The person does not significantly anticipate danger from the other.

### High Fear
May produce:
- caution;
- avoidance;
- appeasement;
- concealment;
- defensive preparation;
- preemptive aggression;
- compliance under some circumstances.

Fear does not imply:
- obedience;
- respect;
- loyalty;
- hatred.

A frightened person may flee, fight, submit, lie, or seek protection.

## 7.10.8 Familiarity

Familiarity answers:

**How much lived experience and practical knowledge does this person have with the other?**

Familiarity comes from:
- time together;
- repeated interaction;
- shared routines;
- observation;
- shared experiences.

### Low Familiarity
Produces more reliance on:
- first impressions;
- stereotypes;
- reputation;
- explicit information.

### High Familiarity
May improve:
- prediction of behavior;
- recognition of mood changes;
- understanding of habits;
- detection of unusual behavior;
- comfort.

Familiarity does not imply liking.

A long-term enemy may know someone extremely well.

## 7.10.9 Obligation / Indebtedness

Obligation answers:

**How strongly does this person believe they owe the other something?**

Sources may include:
- favors;
- rescue;
- gifts;
- debts;
- promises;
- hospitality;
- social norms;
- family duty.

### Low Obligation
Little perceived debt exists.

### High Obligation
May increase willingness to:
- repay favors;
- accept inconvenience;
- provide aid;
- tolerate a request;
- honor a promise.

Obligation should preserve:
- source;
- perceived magnitude;
- expected repayment;
- whether repayment has occurred.

Obligation does not imply:
- affection;
- trust;
- loyalty;
- friendship.

An NPC may resent owing someone.

## 7.10.10 Resentment

Resentment answers:

**How much unresolved grievance, bitterness, or sense of unfairness does this person hold toward the other?**

Common sources:
- betrayal;
- humiliation;
- neglect;
- unfair treatment;
- broken promises;
- exploitation;
- favoritism;
- repeated irritation.

### Low Resentment
Little unresolved bitterness.

### High Resentment
May produce:
- reduced patience;
- negative interpretation;
- reluctance to help;
- emotional distance;
- desire for acknowledgment or restitution.

Resentment may coexist with high Affection.

Example:
An NPC may deeply love a sibling while resenting years of favoritism.

Resentment does not automatically imply active hostility.

## 7.10.11 Hostility

Hostility answers:

**How strongly does this person actively oppose, dislike, or wish harm or defeat upon the other?**

Hostility is more action-oriented than Resentment.

Sources may include:
- ideological conflict;
- active feud;
- revenge;
- direct threat;
- hatred;
- warfare;
- severe betrayal.

### Low Hostility
The person is not actively opposed.

### High Hostility
May increase:
- refusal to cooperate;
- confrontation;
- sabotage;
- retaliation;
- willingness to harm;
- efforts to undermine.

Hostility does not require low Respect.

A respected rival or enemy may still receive very high Hostility.

## 7.10.12 Romantic Interest

Romantic Interest answers:

**How strongly does this person desire a romantic relationship or romantic closeness with the other?**

It is distinct from:
- affection;
- friendship;
- sexual attraction;
- current arousal;
- compatibility;
- commitment.

### Low Romantic Interest
The person does not meaningfully desire romance.

### Moderate Romantic Interest
May involve:
- curiosity;
- crush;
- increased attention;
- wondering about compatibility;
- tentative pursuit.

### High Romantic Interest
May produce:
- desire for courtship;
- emotional investment;
- jealousy risk;
- future-oriented thinking;
- willingness to prioritize the relationship.

Romantic Interest may be:
- one-sided;
- hidden;
- denied;
- conflicted;
- culturally constrained.

High Romantic Interest does not guarantee:
- successful relationship;
- compatibility;
- consent;
- exclusivity;
- sexual desire.

## 7.10.13 Adult Arousal / Sexual Chemistry

For adult characters only, this dimension answers:

**How readily and strongly does this person experience sexual arousal or sexual chemistry specifically in relation to the other adult?**

This is a relationship-specific tendency rather than the NPC's moment-to-moment physiological state.

Current temporary arousal remains owned by Ruleset 7.8.

### Low Adult Arousal / Sexual Chemistry
May mean:
- little sexual response toward the person;
- sexual attraction is weak or absent;
- chemistry does not naturally emerge.

This does not imply:
- dislike;
- romantic incompatibility;
- inability to love the person.

### Moderate Adult Arousal / Sexual Chemistry
May involve:
- noticeable physical attraction;
- sexual curiosity;
- context-dependent arousal;
- flirtatious tension.

### High Adult Arousal / Sexual Chemistry
May involve:
- strong sexual attraction;
- frequent responsiveness to sexual or intimate cues from that person;
- strong anticipation of consensual adult intimacy;
- heightened sexual tension in appropriate contexts.

The dimension may be influenced by:
- physical attraction;
- personality;
- scent, voice, mannerisms, or presentation;
- compatible sexual preferences;
- previous consensual experiences;
- fantasy;
- emotional associations;
- novelty;
- relationship dynamics.

It may change after:
- positive adult sexual experiences;
- incompatibility;
- rejection;
- betrayal;
- changed attraction;
- altered relationship dynamics.

Adult Arousal / Sexual Chemistry does not imply:
- Romantic Interest;
- Affection;
- Trust;
- Compatibility overall;
- initiation;
- consent;
- availability;
- exclusivity.

An adult may experience strong sexual chemistry with someone they:
- dislike;
- distrust;
- do not want to date;
- intentionally avoid.

Likewise, two adults may be deeply in love while having low sexual chemistry.

## 7.10.14 Current Arousal vs Persistent Sexual Chemistry

These must remain separate.

### Persistent Relationship Dimension
Represents person-specific sexual responsiveness or chemistry over time.

### Current Arousal
Represents immediate temporary physiological/emotional state.

A person may have:
- high chemistry + no current arousal;
- moderate chemistry + strong situational arousal;
- low chemistry + temporary context-specific arousal.

Current arousal should decay normally through Ruleset 7.8.

Persistent chemistry changes more slowly through relationship experience.

## 7.10.15 Attraction Is Not One Thing

The simulation should distinguish at least conceptually:
- aesthetic attraction;
- emotional attraction;
- romantic attraction;
- adult sexual attraction.

These can overlap or diverge.

A character may find someone beautiful without wanting romance.

A character may love someone romantically without strong sexual attraction.

A character may experience strong adult sexual attraction without emotional attachment.

These distinctions support deeper romance later without requiring a separate full numeric axis for every possible type unless needed.

## 7.10.16 Domain-Specific Dimensions

Some axes may require subdomains when important.

Examples:

### Trust
- honesty;
- judgment;
- secrecy;
- competence;
- emotional safety.

### Respect
- combat ability;
- intellect;
- moral character;
- leadership.

The relationship may store a global summary plus domain exceptions.

Example:
**Trust: High overall**
- judgment: low;
- secrecy: very high.

Do not create subdimensions unless the distinction matters.

## 7.10.17 Relationship Dimension Change Speed

Different dimensions should naturally change at different rates.

### Faster-changing
- Fear;
- Resentment;
- Romantic Interest in early stages;
- adult sexual chemistry during early attraction.

### Medium
- Respect;
- Affection;
- Obligation.

### Slower
- deep Trust;
- Loyalty;
- long-established Attachment;
- entrenched Hostility.

This is a tendency, not a hard law.

A catastrophic betrayal can destroy Trust quickly.

## 7.10.18 Positive and Negative Evidence Asymmetry

Some dimensions should respond asymmetrically.

Trust is the clearest example.

Building Trust may require:
- repeated reliable behavior.

Destroying Trust may require:
- one severe betrayal.

Similarly:
- Respect can collapse after cowardice or hypocrisy.
- Affection may persist despite conflict.
- Resentment may take longer to fade than to form after major harm.

This asymmetry should be dimension-specific.

## 7.10.19 Diminishing Returns

Repeated identical positive actions should have diminishing effect.

Examples:
- giving the same gift repeatedly;
- offering routine compliments;
- completing expected duties.

The first meaningful action may matter.

The twentieth identical action may add almost nothing.

This prevents relationship grinding.

## 7.10.20 Contextual Interpretation

The same event may modify different dimensions depending on context.

Example:
The player violently defeats an enemy.

NPC A:
- Respect increases.

NPC B:
- Fear increases.

NPC C:
- Hostility increases.

NPC D:
- Affection decreases.

NPC E:
- no meaningful change.

Relationship changes depend on the observer's values, beliefs, and relationship history.

## 7.10.21 Event Magnitude

Relationship changes should depend on event significance.

Useful conceptual classes:

- trivial;
- minor;
- meaningful;
- major;
- defining.

A trivial interaction should rarely move a major relationship noticeably.

Defining events can permanently reshape several dimensions at once.

## 7.10.22 Relationship Contradiction Examples

Valid relationship states include:

### Trusted Enemy
- Trust: High
- Respect: High
- Affection: Low
- Hostility: High

### Estranged Sibling
- Trust: Low
- Affection: High
- Loyalty: Moderate
- Resentment: High

### Feared Commander
- Trust: Moderate
- Respect: High
- Loyalty: Moderate
- Fear: High
- Affection: Low

### Intense Adult Fling
- Affection: Low
- Romantic Interest: Low
- Adult Arousal / Sexual Chemistry: Very High
- Trust: Moderate

### Loving but Sexually Incompatible Adult Partners
- Trust: Very High
- Affection: Very High
- Loyalty: Very High
- Romantic Interest: Very High
- Adult Arousal / Sexual Chemistry: Low

### Unrequited Love
Person A -> B:
- Affection: High
- Romantic Interest: Very High

Person B -> A:
- Affection: High
- Romantic Interest: None

These examples should be fully valid without forcing convergence.

## 7.10.23 Derived Social Interpretations

The engine may derive useful qualitative interpretations from dimension combinations.

Examples:
- close friend;
- trusted rival;
- feared authority;
- bitter ex-partner;
- affectionate but strained sibling;
- sexually charged adult relationship;
- loyal subordinate;
- reluctant ally.

Derived labels should never overwrite the underlying dimensions.

## 7.10.24 Relationship Thresholds

Dimensions may create thresholds that alter what becomes plausible.

Examples:
- high Trust may permit disclosure of sensitive personal information;
- high Respect may make mentorship plausible;
- high Loyalty may make personal sacrifice plausible;
- high Romantic Interest may make courtship plausible;
- high adult sexual chemistry may make consensual sexual escalation more plausible when all other required conditions are present.

A threshold does not guarantee the action.

Other factors still matter:
- current willingness;
- boundaries;
- context;
- goals;
- existing commitments;
- consent;
- consequences.

## 7.10.25 No Cross-Dimension Purchase

One dimension cannot be "spent" to override another.

Examples:
- high Affection cannot purchase Trust after betrayal;
- high Loyalty cannot erase Fear;
- high Respect cannot buy Romance;
- high Romantic Interest cannot buy Consent;
- high adult sexual chemistry cannot override a boundary.

This is a hard anti-exploitation rule.

## 7.10.26 Asymmetry

Every dimension may differ by direction.

Person A may:
- trust B deeply.

Person B may:
- distrust A.

One adult may:
- experience intense sexual chemistry.

The other may:
- experience none.

No system should automatically average the two.

## 7.10.27 Hidden State

Exact dimension values remain hidden unless using developer/debug mode.

Player-facing information should come from:
- behavior;
- statements;
- choices;
- body language;
- history;
- social inference.

Even highly perceptive characters should generally infer ranges or tendencies rather than exact values.

## 7.10.28 Relationship Dimension Update Record

For important changes, the engine may internally preserve:

- dimension affected;
- direction;
- approximate magnitude;
- event cause;
- interpretation;
- timestamp;
- whether the change is temporary, persistent, or uncertain.

This allows later auditing and debugging.

## 7.10.29 Design Standard

A dimension system should be rejected or revised if it:
- collapses all interpersonal state into one score;
- treats zero as the automatic opposite of every axis;
- makes all dimensions change at identical rates;
- assumes reciprocity;
- lets repeated trivial actions farm relationship state;
- assumes affection creates trust;
- assumes loyalty creates obedience;
- assumes fear creates loyalty;
- assumes romantic interest creates compatibility;
- assumes adult arousal creates consent;
- prevents strong contradictory states;
- exposes exact values during ordinary play;
- requires unnecessary subdimensions when a broad state is sufficient.

## Governing Rule

**Each relationship dimension should represent one specific interpersonal truth, change according to causes relevant to that truth, and remain independent enough that complex relationships can emerge from their combination.**
