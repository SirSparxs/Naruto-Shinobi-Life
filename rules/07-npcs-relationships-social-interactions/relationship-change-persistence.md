# 7.11 — Relationship Change & Persistence

Status: Provisional design section pending explicit approval.

Ruleset 7.11 defines how persistent relationship dimensions change over time.

The governing principle is:

**Relationship change should be causal, proportional, dimension-specific, history-sensitive, and resistant to trivial grinding.**

A relationship should evolve because something meaningful happened, not because the player repeated a low-value interaction until a meter filled.

## 7.11.1 Relationship Change Inputs

A relationship event may be influenced by:
- what objectively happened;
- what the NPC believes happened;
- perceived intent;
- event severity;
- relationship history;
- current expectations;
- current emotional state;
- existing relationship dimensions;
- public vs private context;
- consequences;
- repetition;
- whether the event was voluntary;
- whether accountability followed.

The NPC's interpretation matters more than objective intent when determining immediate relationship change.

## 7.11.2 Event Magnitude

Events should be categorized by significance.

Suggested qualitative levels:
- trivial;
- minor;
- meaningful;
- major;
- defining.

### Trivial
Examples:
- casual compliment;
- routine greeting;
- small courtesy.

### Minor
Examples:
- small favor;
- mild disagreement;
- thoughtful gesture.

### Meaningful
Examples:
- keeping an important promise;
- providing real support;
- serious argument;
- lying about something consequential.

### Major
Examples:
- saving someone's life;
- major betrayal;
- public humiliation;
- abandoning someone during crisis.

### Defining
Examples:
- sacrificing greatly for the person;
- causing death of someone they love;
- years-long betrayal;
- life-changing rescue;
- extreme personal violation.

Magnitude determines potential change, not automatic change.

## 7.11.3 Interpretation Before Update

The engine should first ask:
- what does the NPC think happened?
- why do they think it happened?
- was it intentional?
- was it justified?
- was it avoidable?
- what did it cost them?

Two NPCs can interpret the same act differently and update different dimensions.

## 7.11.4 Dimension-Specific Change

Each event should affect only relevant dimensions.

Examples:
- reliable secrecy -> Trust increases;
- competent leadership -> Respect increases;
- shared vulnerability -> Affection may increase;
- credible threat -> Fear increases;
- betrayal -> Trust decreases, Resentment increases;
- repeated support -> Loyalty may increase;
- romantic rejection -> Romantic Interest may decrease, Resentment may or may not change.

Do not modify every relationship axis after every event.

## 7.11.5 Existing-State Scaling

The same event may have different effect depending on current state.

Examples:
- one honest act matters more when Trust is low than when Trust is already very high;
- one compliment matters little in an established marriage;
- one betrayal matters more when Trust was extremely high;
- one insult may matter more when Resentment is already near a breaking point.

## 7.11.6 Diminishing Returns

Repeated similar positive actions should produce less change.

Examples:
- repeated gifts;
- repeated compliments;
- routine favors;
- expected duties.

A gesture that initially feels meaningful may later become normal.

This prevents farming.

## 7.11.7 Novelty Bonus

Meaningful first-time actions may have greater impact.

Examples:
- first genuine apology;
- first major act of vulnerability;
- first time someone risks themselves for the other;
- first romantic confession.

Novelty matters most when the act changes the NPC's model of the other person.

## 7.11.8 Expectation Effects

Events should be judged against expectation.

If a trusted teammate performs routine support, little may change.

If a known coward risks their life for someone, Respect may rise sharply.

If a highly trusted friend tells one serious lie, Trust may fall heavily because the act violated expectation.

## 7.11.9 Betrayal Asymmetry

Trust and Loyalty should be especially asymmetric.

Building them often requires repeated evidence.

Destroying them may require only one severe event.

This should depend on:
- severity;
- intent;
- stakes;
- prior Trust;
- prior warnings;
- consequences;
- accountability.

## 7.11.10 Relationship Shock

A major event may cause an immediate sharp update.

Examples:
- witnessed betrayal;
- unexpected rescue;
- public rejection;
- death caused by the other person;
- confession of a major secret.

Shock should not be overused.

Most relationships should change gradually.

## 7.11.11 Slow Drift

Some dimensions may drift when a relationship receives little reinforcement.

Possible examples:
- Familiarity;
- active Affection;
- Romantic Interest;
- perceived Obligation.

Deep Trust or long-standing Loyalty should usually decay more slowly.

Resentment may fade if:
- no new harm occurs;
- the grievance loses relevance;
- time passes;
- the NPC reinterprets the event.

## 7.11.12 Stabilization

Repeated consistent experiences can stabilize a relationship.

Stable relationships should:
- resist trivial fluctuations;
- have stronger expectations;
- require more meaningful events for major movement.

Stability is not invulnerability.

## 7.11.13 Relationship Inertia

Long relationships should have more inertia than new ones.

Inertia grows through:
- time;
- repetition;
- shared hardship;
- commitment;
- family bonds;
- major shared history.

A new acquaintance can shift quickly.
A decades-long relationship usually moves more slowly except during major rupture.

## 7.11.14 Threshold Crossing

When a dimension crosses a meaningful threshold, new behaviors may become plausible.

Examples:
- Trust becomes high enough for sensitive disclosure;
- Resentment becomes high enough for open confrontation;
- Romantic Interest becomes high enough for pursuit;
- Loyalty becomes high enough for sacrifice.

Thresholds should not force action.

## 7.11.15 Multi-Dimension Events

One event may change several dimensions in different directions.

Example:
A commander saves an NPC's life but lies about why.

Possible result:
- Affection up;
- Respect up;
- Trust down;
- Obligation up.

Complex updates are valid.

## 7.11.16 Relationship Scars

Some events should leave persistent scars.

A scar is not simply a permanent penalty.

It is a remembered vulnerability that continues affecting interpretation.

Examples:
- previous infidelity;
- abandonment;
- torture;
- betrayal during crisis;
- public humiliation.

A relationship may recover while the scar remains.

## 7.11.17 Repair

Repair may require:
- acknowledgment;
- apology;
- restitution;
- changed behavior;
- transparency;
- time;
- repeated reliability;
- accepting consequences.

Different dimensions recover differently.

Trust may require evidence.
Affection may return faster.
Resentment may remain even after cooperation resumes.

## 7.11.18 Apology Quality

An apology may be judged by:
- sincerity;
- specificity;
- responsibility taken;
- understanding of harm;
- absence of excuses;
- restitution;
- future behavior.

Words alone should not automatically repair major damage.

## 7.11.19 Forgiveness

Forgiveness is not equivalent to:
- restored Trust;
- restored relationship;
- forgetting;
- removal of consequences.

An NPC may forgive someone while:
- refusing reconciliation;
- maintaining boundaries;
- never trusting them again.

## 7.11.20 Reconciliation

Reconciliation means rebuilding a functional relationship.

It may involve:
- renewed contact;
- repaired Trust;
- reduced Resentment;
- renegotiated expectations;
- new boundaries.

Reconciliation may be partial.

## 7.11.21 Permanent or Near-Permanent Change

Some events may create changes that are effectively permanent.

Examples:
- murder of a loved one;
- severe betrayal after decades of trust;
- life-saving sacrifice;
- irreversible public disgrace.

Permanent change should be rare and justified.

It may affect:
- baseline expectations;
- future Trust ceiling;
- persistent Resentment;
- permanent Respect;
- relationship category.

## 7.11.22 Relationship Ceilings and Floors

History may create practical ceilings or floors.

Example:
After a catastrophic betrayal:
- Trust may recover from 10 to 50;
- but may never return to 90 without extraordinary circumstances.

Likewise:
A parent may retain a minimum level of Affection despite conflict.

Ceilings and floors should be character-specific, not universal.

## 7.11.23 Recovery Curves

Repair should generally become harder at extremes.

Examples:
- moving Trust from 20 to 40 may be easier than 70 to 90 after betrayal;
- reducing Resentment from 90 to 70 may require acknowledgment before time helps.

Recovery should reflect the cause of damage.

## 7.11.24 Relationship Decay

Decay should be selective.

Possible decay:
- Familiarity decreases with long absence;
- Romantic Interest may fade;
- Obligation becomes less salient;
- mild Resentment may soften.

Persistent states:
- deep family Affection;
- severe betrayal memory;
- strong Loyalty;
- entrenched Hostility.

## 7.11.25 Absence Effects

Time apart may:
- reduce day-to-day closeness;
- increase idealization;
- reduce Familiarity with current behavior;
- preserve old Affection;
- create uncertainty;
- weaken active Romantic Interest;
- intensify longing.

Absence should not automatically weaken every dimension.

## 7.11.26 Reunions

Reunions should compare:
- remembered relationship;
- current expectations;
- visible changes;
- new information.

This can produce:
- warmth;
- awkwardness;
- disappointment;
- renewed attraction;
- estrangement.

## 7.11.27 Relationship Momentum

Recent repeated changes may create momentum.

Examples:
- several positive interactions -> easier warming;
- repeated conflict -> easier deterioration.

Momentum should be temporary.

It represents current trajectory, not destiny.

## 7.11.28 Saturation

Dimensions near their extremes should be harder to move further.

Example:
Increasing Trust from 95 to 100 should require something exceptional.

Likewise, reducing Hostility from 100 to 95 may require a genuine crack in the grievance.

## 7.11.29 Negative Events Often Weigh More

For some dimensions, negative events should have greater impact than equivalent positive events.

Especially:
- Trust;
- Fear;
- Resentment;
- Hostility.

This reflects how severe harm can dominate many routine positives.

But this should not create universal pessimism across every axis.

## 7.11.30 Relationship Change Through Observation

A relationship may change from witnessing behavior toward others.

Examples:
- seeing someone abuse a subordinate lowers Respect;
- watching them protect civilians raises Respect;
- seeing them betray a friend lowers Trust.

The observer must actually know or believe the event occurred.

## 7.11.31 Third-Party Information

Relationship change may also come from:
- rumors;
- testimony;
- reports;
- reputation.

The magnitude should depend on credibility.

Unverified rumor should usually change less than direct observation.

## 7.11.32 Misunderstanding

False beliefs can cause real relationship changes.

If an NPC wrongly believes someone betrayed them:
- Trust may fall;
- Resentment may rise.

Later correction may repair some damage.

But the emotional consequences of the misunderstanding may not disappear instantly.

## 7.11.33 Romantic Change

Romantic Interest may increase through:
- compatibility;
- emotional intimacy;
- admiration;
- shared experiences;
- attraction;
- courtship.

It may decrease through:
- incompatibility;
- rejection;
- changing goals;
- betrayal;
- loss of attraction;
- prolonged separation.

Romantic Interest should not increase just because Affection does.

## 7.11.34 Adult Sexual Chemistry Change

For adults, person-specific sexual chemistry may change through:
- increased attraction;
- consensual intimacy;
- satisfying compatibility;
- fantasy;
- changing presentation;
- emotional associations.

It may decrease through:
- incompatibility;
- negative experiences;
- loss of attraction;
- resentment;
- changed preferences;
- altered relationship dynamics.

Current arousal remains temporary and should not permanently move chemistry without meaningful repeated or salient experience.

## 7.11.35 Consent Does Not Persist as Relationship State

Past consent should never create a permanent consent flag.

Consent remains contextual to the immediate interaction.

Relationship history may influence comfort and expectation, but not automatic permission.

## 7.11.36 Repeated Unwanted Advances

Repeated unwanted romantic or sexual advances should tend to:
- reduce Trust;
- reduce Romantic Interest;
- increase discomfort or Resentment;
- potentially increase Fear or Hostility depending on severity.

The system should not allow spammed Seduction checks to brute-force attraction.

## 7.11.37 Gift Effects

Gifts should matter based on:
- thoughtfulness;
- appropriateness;
- meaning;
- timing;
- relationship;
- cost relative to giver;
- cultural norms.

Expensive gifts are not automatically more effective.

Repeated gifts should rapidly diminish in impact unless context makes them meaningful.

## 7.11.38 Shared Hardship

Shared hardship may increase:
- Trust;
- Loyalty;
- Affection;
- Familiarity;
- Respect.

But it can also increase:
- Resentment;
- Fear;
- conflict.

The result depends on how each person behaved.

## 7.11.39 Conflict Without Damage

Disagreement should not automatically damage relationships.

Healthy relationships may tolerate:
- arguments;
- competition;
- different opinions.

Damage depends on:
- disrespect;
- betrayal;
- contempt;
- harm;
- violated expectations.

## 7.11.40 Relationship Maintenance

Established relationships may require maintenance depending on character expectations.

Examples:
- regular communication;
- shared time;
- honesty;
- mutual support;
- affection;
- reliability.

Maintenance should not become repetitive chores.

The system should summarize routine healthy maintenance unless something changes.

## 7.11.41 Relationship Neglect

Neglect may matter when:
- contact was expected;
- support was needed;
- promises were ignored;
- one person repeatedly deprioritizes the other.

Neglect should be interpreted through personality and expectations.

## 7.11.42 Relationship Change by Tier

### Major NPC
Track important dimension changes individually.

### Supporting NPC
Track meaningful updates and trajectory.

### Persistent Minor NPC
Use broad disposition changes unless promoted.

### Background NPC
No persistent update unless the interaction becomes consequential.

## 7.11.43 Update Logging

Important relationship changes may preserve:
- event;
- dimensions affected;
- magnitude;
- interpretation;
- timestamp;
- persistence;
- related memory.

Routine trivial changes need not be logged individually.

## 7.11.44 Anti-Grinding

The system should block:
- repeated compliment farming;
- repetitive gift farming;
- repeated persuasion until success;
- apology spam;
- low-risk favor loops;
- repeated flirtation after rejection.

Anti-grinding methods include:
- diminishing returns;
- expectation normalization;
- failure consequences;
- cooldown through changing context;
- NPC irritation;
- requirement for qualitatively new evidence.

## 7.11.45 Design Standard

A relationship-change mechanic should be rejected or revised if it:
- moves every dimension equally;
- ignores interpretation;
- makes trivial repetition stronger than meaningful action;
- lets one apology erase major betrayal;
- makes time heal everything automatically;
- makes absence reduce every dimension identically;
- makes reconciliation erase memory;
- lets romance increase automatically from friendship;
- lets prior consent persist permanently;
- makes repeated rejection attempts eventually succeed by RNG;
- prevents catastrophic events from causing major change;
- makes long-established relationships as volatile as new ones.

## Governing Rule

**Relationship change should reflect what happened, what it meant to the NPC, how important the relationship already was, and whether later behavior reinforced, repaired, or worsened that meaning.**
