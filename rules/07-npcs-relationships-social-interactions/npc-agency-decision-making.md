# 7.5 — NPC Agency & Decision-Making

Status: Provisional design section pending explicit approval.

Ruleset 7.5 defines how NPCs choose actions.

The purpose is to produce behavior that is:
- internally consistent;
- causally understandable;
- imperfect;
- context-sensitive;
- capable of surprise without becoming arbitrary.

The simulation should not ask:
**What action would make the story most dramatic?**

It should ask:
**Given this NPC's identity, beliefs, goals, relationships, emotional state, obligations, and perceived options, what action would they plausibly choose?**

## 7.5.1 Decision Inputs

An NPC decision may draw from:
- baseline identity;
- personality;
- temperament;
- values;
- moral boundaries;
- current goals;
- goal priority;
- current needs;
- knowledge;
- false beliefs;
- uncertainty;
- memories;
- relationships;
- current emotions;
- current physical/medical state;
- social context;
- authority structures;
- available resources;
- perceived risks;
- perceived rewards;
- time pressure;
- opportunity;
- habit;
- previous commitments.

Not every decision needs every input.

The simulation should only evaluate factors that materially affect the choice.

## 7.5.2 Perceived Options

NPCs can only choose among options they:
- know about;
- can imagine;
- believe are possible;
- can currently access.

The simulation may know a perfect solution exists while the NPC never considers it.

This preserves imperfect reasoning.

## 7.5.3 Action Candidate Generation

For meaningful decisions, generate a small set of plausible actions.

Examples:
- comply;
- refuse;
- delay;
- negotiate;
- lie;
- seek help;
- flee;
- confront;
- report;
- conceal;
- investigate;
- compromise;
- wait;
- retaliate;
- apologize;
- disengage.

Do not generate every theoretically possible action.

Candidates should come from:
- goals;
- habits;
- personality;
- knowledge;
- social role;
- current situation.

## 7.5.4 Satisficing, Not Perfect Optimization

NPCs should usually choose an action that is **good enough**, not mathematically optimal.

Real people:
- overlook information;
- underestimate consequences;
- act from habit;
- simplify choices;
- become emotionally biased;
- stop searching once they find an acceptable option.

Therefore NPCs should often satisfice.

A highly analytical NPC may evaluate more options.
An impulsive NPC may evaluate fewer.

## 7.5.5 Decision Weighting

Each candidate action may be weighed by:
- goal advancement;
- goal conflict;
- value alignment;
- relationship consequences;
- moral cost;
- risk;
- reward;
- urgency;
- effort;
- social cost;
- institutional consequences;
- emotional appeal;
- habit familiarity;
- perceived feasibility.

The system does not require a visible universal score.

Qualitative weighting is acceptable when sufficient.

## 7.5.6 Hard Constraints

Some options may be removed before comparison.

Examples:
- physically impossible;
- unknown to the NPC;
- violates a true absolute boundary under current conditions;
- inaccessible due to authority or resources;
- contradicted by current knowledge;
- impossible within the time available.

Hard constraints should be used sparingly.

Most resistance should remain a strong preference rather than absolute impossibility.

## 7.5.7 Soft Constraints

Soft constraints make an action less likely without removing it.

Examples:
- dislikes lying;
- afraid of punishment;
- reluctant to hurt a friend;
- values reputation;
- dislikes public embarrassment;
- avoids conflict;
- fears intimacy.

Strong pressure may overcome a soft constraint.

## 7.5.8 Red Lines

A red line is a particularly strong boundary.

Examples:
- never harm children;
- never betray squadmates;
- never reveal a clan secret;
- never submit to a specific enemy.

Crossing a red line should require extreme pressure, changed beliefs, severe desperation, coercion, supernatural influence, or major character development.

If crossed, it should often produce lasting consequences.

## 7.5.9 Role Conflict

NPCs may hold multiple roles with conflicting expectations.

Example:
- sibling;
- shinobi;
- clan member;
- commander.

When roles conflict, the decision should consider:
- which identity is most central;
- current stakes;
- relationship strength;
- formal obligation;
- expected consequences;
- values.

## 7.5.10 Relationship Influence

Relationships affect decisions by changing:
- trust;
- willingness to accept risk;
- credibility;
- protectiveness;
- forgiveness;
- suspicion;
- tolerance;
- obligation;
- willingness to sacrifice.

Relationship strength should influence decisions, not guarantee them.

A loyal friend may still refuse a request that crosses a moral boundary.

## 7.5.11 Emotion as Bias

Current emotion should modify:
- which options are noticed;
- how risks are perceived;
- how quickly choices are made;
- how much patience exists;
- how hostile or generous interpretations become.

Examples:
- anger increases confrontational options;
- fear increases escape, appeasement, concealment, or preemptive aggression;
- affection increases tolerance and protectiveness;
- jealousy increases sensitivity to romantic threats;
- shame may increase withdrawal or defensiveness.

Emotion should bias decisions rather than dictate them.

## 7.5.12 Stress & Cognitive Narrowing

High stress may reduce:
- number of options considered;
- patience;
- long-term thinking;
- social nuance;
- willingness to gather more information.

Very high stress may cause tunnel vision.

Experienced or disciplined NPCs may resist this effect better.

## 7.5.13 Habit

Habit can strongly influence low-stakes choices.

Examples:
- always reports suspicious behavior;
- avoids asking for help;
- apologizes quickly;
- withdraws during arguments;
- confronts problems immediately.

Habit reduces cognitive effort.

Major stakes may override habit.

## 7.5.14 Impulsiveness

Impulsive NPCs:
- act faster;
- evaluate fewer consequences;
- give more weight to emotion;
- may regret decisions afterward.

Impulsiveness should not mean randomness.

Their actions should still make sense from immediate motives and perception.

## 7.5.15 Caution

Cautious NPCs:
- seek information;
- prefer reversible options;
- avoid irreversible commitments;
- delay under uncertainty;
- create contingencies.

Too much caution may produce inaction.

## 7.5.16 Risk Tolerance

Risk tolerance should be context-specific.

An NPC may:
- accept physical danger but avoid social humiliation;
- gamble money but not reputation;
- risk career for family;
- risk life for village duty.

Do not use one universal risk stat for every domain unless a later system proves it necessary.

## 7.5.17 Time Pressure

Time pressure changes decision quality.

Under severe time pressure, NPCs may:
- rely on habit;
- choose familiar options;
- accept higher risk;
- skip verification;
- obey authority more readily;
- make mistakes.

## 7.5.18 Information Seeking

An NPC may delay action to:
- investigate;
- ask questions;
- consult someone;
- verify evidence;
- gather intelligence.

Whether they do so depends on:
- urgency;
- skepticism;
- intelligence;
- caution;
- available time;
- trust in the source.

## 7.5.19 Authority & Obedience

Formal authority modifies decision-making but does not erase agency.

NPCs may:
- comply;
- comply reluctantly;
- question;
- delay;
- seek clarification;
- refuse;
- secretly disobey;
- report the order;
- reinterpret the order.

Response depends on:
- legitimacy;
- rank;
- loyalty;
- fear;
- trust;
- ideology;
- consequences;
- moral boundaries.

## 7.5.20 Social Pressure

NPCs may change behavior because of:
- audience;
- clan expectations;
- teammates;
- family;
- reputation;
- fear of embarrassment;
- desire for approval.

Public and private decisions may differ.

## 7.5.21 Commitment & Consistency

Previous choices create pressure for consistency.

An NPC who publicly supported a policy may resist reversing position because of:
- pride;
- reputation;
- sunk cost;
- social expectations.

This should not make change impossible.

## 7.5.22 Sunk Cost

NPCs may irrationally continue investing in a failing plan because of:
- pride;
- previous sacrifice;
- fear of admitting failure;
- emotional attachment.

More reflective NPCs may recognize this better.

## 7.5.23 Cognitive Bias

NPCs may display believable biases such as:
- confirmation bias;
- optimism bias;
- pessimism;
- status quo bias;
- authority bias;
- in-group favoritism;
- loss aversion;
- overconfidence.

Biases should reflect character history and personality.

Do not assign every NPC every bias.

## 7.5.24 Uncertainty

NPCs may represent confidence in their own judgment.

Possible states:
- certain;
- confident;
- unsure;
- doubtful;
- confused.

Low confidence may produce:
- hesitation;
- consultation;
- reversible choices;
- avoidance.

## 7.5.25 Mixed Motives

An action can satisfy multiple motives simultaneously.

Example:
An NPC volunteers for a dangerous mission because:
- duty;
- desire for promotion;
- attraction to a teammate;
- need to prove themselves.

Mixed motives are normal.

## 7.5.26 Internal Conflict

When two high-priority motives strongly oppose each other, mark internal conflict.

Internal conflict may cause:
- hesitation;
- emotional stress;
- inconsistent behavior;
- bargaining;
- delay;
- secrecy;
- compromise;
- later regret.

## 7.5.27 Regret

After acting, NPCs may reassess the decision using:
- outcome;
- new information;
- moral evaluation;
- social consequences.

Regret may:
- change future behavior;
- create apology goals;
- create self-justification;
- create resentment;
- alter self-concept.

## 7.5.28 Rationalization

NPCs may justify their own behavior after the fact.

Examples:
- "I had no choice."
- "They deserved it."
- "I only lied to protect them."

Rationalization may protect self-concept while delaying genuine reflection.

## 7.5.29 Deliberate Deception in Decision-Making

An NPC may choose one action publicly while pursuing another privately.

Examples:
- agree publicly, resist privately;
- pretend neutrality;
- fake cooperation;
- conceal opposition.

Decision simulation should distinguish:
- actual intent;
- presented intent;
- chosen action.

## 7.5.30 Strategic Social Behavior

Some NPCs deliberately manage impressions.

They may:
- flatter;
- withhold emotion;
- appear weaker;
- exaggerate confidence;
- hide attraction;
- conceal resentment;
- perform loyalty.

This is not automatically deception in every case.
It may simply be social self-presentation.

## 7.5.31 Romantic Decision-Making

Romantic decisions may consider:
- attraction;
- affection;
- trust;
- compatibility;
- current relationship status;
- boundaries;
- reputation;
- family/clan expectations;
- fear of rejection;
- emotional readiness;
- opportunity;
- prior experiences.

An NPC may be attracted to someone and still choose not to pursue them.

## 7.5.32 Adult Sexual Decision-Making

For adults, sexual decisions may consider:
- attraction;
- current arousal;
- trust;
- compatibility;
- personal boundaries;
- relationship expectations;
- privacy;
- risk;
- consequences;
- desire;
- current physical and emotional state;
- consent.

Arousal should never directly determine the action.

The simulation should preserve the distinction between:
- wanting;
- considering;
- initiating;
- consenting;
- declining.

## 7.5.33 Romantic Rejection

Rejection should be a valid stable outcome.

An NPC may reject someone because of:
- no attraction;
- incompatible goals;
- existing relationship;
- lack of trust;
- timing;
- cultural expectations;
- professional boundaries;
- personal preference.

High social skill does not guarantee reversal.

## 7.5.34 Reconsideration

NPCs may later reconsider previous choices because:
- circumstances changed;
- beliefs changed;
- relationship changed;
- attraction changed;
- new evidence appeared;
- pressure disappeared.

Reconsideration should have a causal reason.

## 7.5.35 Randomness in Decisions

Randomness may be used only when multiple actions are similarly plausible.

Randomness should not replace reasoning.

A random choice is appropriate when:
- options are nearly equivalent;
- the NPC is genuinely uncertain;
- habit does not strongly favor one;
- no major motive dominates.

## 7.5.36 Deterministic Decisions

If one action overwhelmingly fits the NPC's state and circumstances, the simulation should choose it without a roll.

Ruleset 2 is not required for internal NPC choices unless uncertainty itself matters.

## 7.5.37 Opposed Social Influence

If another character is actively trying to influence the NPC, Ruleset 2 may resolve the influence attempt.

Ruleset 7 then integrates that result into the NPC's decision.

A successful influence roll may:
- increase perceived benefit;
- reduce perceived risk;
- increase trust;
- change interpretation;
- create emotional pressure.

It does not directly force the final decision unless the outcome is already within plausible willingness.

## 7.5.38 Decision Memory

Important decisions should create memory.

Track where relevant:
- what was chosen;
- why;
- who influenced it;
- whether the NPC regrets it;
- resulting consequences.

This supports future consistency.

## 7.5.39 Off-Screen Decisions

Major NPCs may make meaningful decisions while off-screen.

The same process should apply:
- current beliefs;
- active goals;
- relationships;
- opportunity;
- world events.

Off-screen decisions should not be chosen solely for surprise.

## 7.5.40 Decision Depth by Simulation Tier

### Major NPC
Use full contextual reasoning for meaningful choices.

### Supporting NPC
Use:
- current goal;
- key trait;
- relationship;
- relevant risk;
- one or two major constraints.

### Persistent Minor NPC
Use a compact heuristic based on:
- role;
- disposition;
- immediate concern.

### Background NPC
Use situational norms and immediate incentives.

## 7.5.41 Decision Compression

Minor decisions should be compressed.

The simulation does not need to separately model:
- what to eat;
- which chair to sit in;
- every casual conversation.

Unless the choice becomes meaningful.

## 7.5.42 Player Unpredictability

NPCs should update decisions when the player behaves unexpectedly.

They should not remain locked into a prewritten script.

Example:
An enemy expects intimidation.
The player offers genuine mercy.

That may create:
- confusion;
- suspicion;
- gratitude;
- strategic reconsideration.

## 7.5.43 Inconsistent Behavior

Occasional inconsistency is realistic if it has a cause.

Possible causes:
- stress;
- incomplete information;
- changing priorities;
- emotion;
- hypocrisy;
- self-deception;
- fatigue;
- social pressure.

Unexplained inconsistency should be avoided.

## 7.5.44 Decision Audit

For major choices, the simulation should be able to reconstruct:

1. What did the NPC believe?
2. What did they want?
3. Which options did they perceive?
4. Which values or relationships mattered?
5. What risks did they anticipate?
6. Why did one option win?

This may remain hidden from the player.

## 7.5.45 Design Standard

A decision mechanic should be rejected or revised if it:
- makes NPCs perfectly rational;
- makes NPC actions random without cause;
- ignores what the NPC knows;
- lets emotion completely replace personality;
- lets authority automatically override red lines;
- lets social rolls directly seize control of decisions;
- assumes attraction guarantees pursuit;
- assumes arousal guarantees consent;
- ignores opportunity and feasibility;
- requires full optimization for trivial decisions;
- chooses off-screen actions only for dramatic surprise;
- prevents NPCs from changing their minds when circumstances change;
- makes every NPC use the same decision logic regardless of personality.

## Governing Rule

**An NPC should choose from the options they can perceive, using the motives, values, relationships, emotions, obligations, risks, and habits that matter to them, and should usually select a plausible option rather than a mathematically perfect one.**
