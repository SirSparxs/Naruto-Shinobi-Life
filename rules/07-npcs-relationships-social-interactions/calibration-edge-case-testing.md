# 7.44 — Calibration & Edge-Case Testing

Status: Provisional design section pending explicit approval.

Ruleset 7.44 defines how the NPC, relationship, romance, social-resolution, reputation, access, and persistence systems should be stress-tested before and during play.

The governing principle is:

**A social rule is not finished because it sounds plausible in isolation; it must produce believable, consistent results across ordinary situations, extreme skill levels, conflicting motives, incomplete information, and adversarial edge cases.**

## 7.44.1 Scope

This section governs:
- calibration scenarios;
- expected qualitative outcomes;
- edge-case testing;
- exploit testing;
- cross-ruleset integration testing;
- low/high mastery comparisons;
- NPC/player symmetry tests;
- hidden-information tests;
- persistence tests;
- regression testing after rules change.

It does not replace Ruleset 2's probability mathematics.
It tests whether Ruleset 7 supplies appropriate inputs and interprets outcomes coherently.

## 7.44.2 Test Philosophy

Testing should ask:
- Is the outcome plausible?
- Is the same logic applied to NPCs and players?
- Does high skill improve quality without becoming mind control?
- Do relationships matter without becoming deterministic?
- Does hidden information remain hidden fairly?
- Do consequences persist?
- Can the mechanic be exploited through repetition?

## 7.44.3 Qualitative Calibration Before Exact Math

Before tuning exact probabilities, test the expected ordering of outcomes.

Example:
- novice negotiator against resistant target should generally struggle;
- expert negotiator should perform meaningfully better;
- neither should make an impossible bargain possible merely through skill.

If qualitative ordering is wrong, probability tuning alone will not fix the design.

## 7.44.4 Standard Skill Bands

When testing, compare at least:
- Low competence;
- Ordinary competence;
- Skilled;
- Expert;
- Exceptional / near-maximum plausible mastery.

Exact numerical mappings belong to Ruleset 1 and Ruleset 2.

## 7.44.5 Standard Relationship Contexts

Repeat tests under:
- stranger;
- acquaintance;
- trusted friend;
- rival;
- hostile enemy;
- authority relationship;
- indebted relationship.

The same skill should produce different outcome spaces depending on context.

## 7.44.6 Standard Stakes

Test:
- trivial;
- minor;
- meaningful;
- major;
- life-changing.

High stakes should generally increase resistance, caution, consequence, or need for evidence.

## 7.44.7 Standard Information Conditions

Test with:
- full accurate information;
- incomplete information;
- false belief;
- deliberate deception;
- hidden motive.

The system should not accidentally grant omniscience.

# Core Social Resolution Tests

## 7.44.8 Reasonable Request Test

Scenario:
A trusted teammate is asked to cover a routine shift.

Expected:
- often no roll if cost is low and willingness is obvious;
- relationship and current obligations matter;
- repeated requests may create burden.

Failure condition:
Every request requires a roll regardless of obvious willingness.

## 7.44.9 High-Cost Request Test

Scenario:
A friend is asked to risk their career for the requester.

Expected:
- friendship increases willingness;
- cost and values remain substantial;
- high Persuasion cannot guarantee agreement.

Failure condition:
High Affection automatically produces compliance.

## 7.44.10 Firm Refusal Test

Scenario:
NPC clearly refuses a romantic advance.

Expected:
- current pursuit closes;
- immediate retries do not create new independent chances;
- respectful acceptance may preserve relationship;
- repeated pressure worsens context.

Failure condition:
Switching from Seduction to Persuasion creates a fresh chance.

## 7.44.11 Impossible Knowledge Test

Scenario:
Prisoner is interrogated for information they never learned.

Expected:
- truthful answer cannot be extracted;
- false statements, guesses, or confession may occur;
- high Interrogation improves diagnosis, not omniscience.

Failure condition:
Critical success generates true information from nowhere.

# Skill Calibration Tests

## 7.44.12 Persuasion Calibration

Use the same reasonable but resisted request with multiple competence bands.

Expected progression:
- Low: awkward framing, limited adaptation.
- Ordinary: competent case.
- Skilled: identifies relevant motives.
- Expert: adapts dynamically and handles objections.
- Exceptional: highly efficient, subtle, accurate judgment.

At no level:
- agency override;
- impossible belief rewrite;
- automatic consent.

## 7.44.13 Negotiation Calibration

Scenario:
Two parties have overlapping but conflicting interests.

Expected:
Higher mastery improves:
- issue identification;
- trade construction;
- concession timing;
- face-saving;
- value creation.

Failure condition:
Expert creates resources or concessions neither side can actually provide.

## 7.44.14 Deception Calibration

Scenario:
Character tells a plausible lie.

Expected:
Higher mastery improves:
- consistency;
- presentation;
- adaptation;
- maintenance.

Counterevidence and target knowledge remain relevant.

Failure condition:
Master Deception erases contradictory evidence.

## 7.44.15 Insight Calibration

Expected:
Higher mastery improves:
- cue recognition;
- baseline comparison;
- contradiction detection;
- confidence calibration.

Failure condition:
Expert Insight directly reveals exact thoughts or objective truth.

## 7.44.16 Leadership Calibration

Scenario:
Squad receives dangerous but justified order.

Expected:
Higher Leadership may improve:
- clarity;
- confidence;
- morale support;
- acceptance.

Follower values, Trust, legitimacy, and risk still matter.

Failure condition:
Leadership mastery guarantees obedience.

## 7.44.17 Intimidation Calibration

Expected:
Higher mastery improves:
- credible threat presentation;
- target reading;
- leverage selection.

Possible responses still include:
- compliance;
- defiance;
- flight;
- deception;
- later retaliation.

Failure condition:
Fear automatically becomes Loyalty.

## 7.44.18 Seduction Calibration

Adults 18+ only.

Expected:
Higher mastery improves:
- cue-reading;
- pacing;
- presentation;
- reciprocal tension;
- graceful disengagement.

Failure condition:
Higher mastery increases ability to overcome clear refusal.

# Relationship Tests

## 7.44.19 High Affection / Low Trust

Scenario:
Two siblings love each other, but one repeatedly lies.

Expected:
- high Affection may persist;
- Trust remains low;
- closeness may coexist with caution.

Failure condition:
Affection automatically restores Trust.

## 7.44.20 High Trust / Low Affection

Scenario:
Two professionals trust each other's competence but dislike each other personally.

Expected:
- reliable cooperation;
- limited personal warmth;
- professional access without intimacy.

Failure condition:
Trust automatically creates friendship.

## 7.44.21 High Loyalty / High Resentment

Scenario:
Shinobi remains loyal to clan while resenting leadership.

Expected:
- continued service is possible;
- dissent and internal conflict remain plausible.

Failure condition:
Loyalty deletes Resentment.

## 7.44.22 Romantic Interest Without Compatibility

Expected:
- attraction and courtship can occur;
- long-term conflict may emerge;
- relationship formation is not guaranteed.

Failure condition:
Mutual attraction automatically means successful partnership.

## 7.44.23 Sexual Chemistry Without Romance

Adults 18+ only.

Expected:
- strong sexual chemistry may exist without Affection or commitment;
- consent and willingness remain event-specific.

Failure condition:
Chemistry creates automatic relationship formation.

## 7.44.24 Stable Relationship Test

Scenario:
Healthy long-term couple with no major current stressor.

Expected:
- relationship can remain stable;
- simulation does not manufacture conflict for drama.

Failure condition:
Off-screen simulation creates arbitrary jealousy or betrayal to create content.

# Betrayal and Repair Tests

## 7.44.25 Accidental Harm vs Deliberate Betrayal

Use same harmful outcome with different intent.

Expected:
- both may cause pain;
- deliberate betrayal generally causes more Trust damage;
- later evidence of accident may alter interpretation.

Failure condition:
Intent has no effect at all or completely erases impact.

## 7.44.26 Apology Without Change

Scenario:
Character apologizes repeatedly but repeats behavior.

Expected:
- apology credibility declines;
- Trust repair stalls;
- pattern memory strengthens.

Failure condition:
Each successful apology resets damage.

## 7.44.27 Genuine Repair

Scenario:
Character admits harm, makes restitution, and behaves differently over time.

Expected:
- some dimensions gradually repair;
- scars may remain;
- reconciliation is possible but not mandatory.

Failure condition:
One conversation instantly restores previous state.

## 7.44.28 Forgiveness Without Reconciliation

Expected:
- Resentment may fall;
- no-contact or distance may remain.

Failure condition:
Forgiveness automatically restores relationship.

# Leadership Tests

## 7.44.29 Formal Leader / Low Legitimacy

Expected:
- formal orders retain institutional weight;
- reluctant compliance may occur;
- dissent and alternative informal leadership may grow.

Failure condition:
Rank forces genuine Loyalty.

## 7.44.30 Informal Leader / No Rank

Expected:
- group may seek their judgment;
- formal authority remains elsewhere;
- dual influence may create tension.

Failure condition:
Informal Respect automatically grants official command authority.

## 7.44.31 Fear-Based Command Collapse

Scenario:
Leader controls group primarily through fear, then loses enforcement power.

Expected:
- obedience may weaken sharply;
- Resentment or defection may surface.

Failure condition:
Past obedience is treated as durable Loyalty.

# Reputation and Information Tests

## 7.44.32 Local Reputation Test

Scenario:
Character embarrasses themselves in one small network.

Expected:
- reputation changes locally;
- spread requires actual channels.

Failure condition:
Entire world immediately knows.

## 7.44.33 False Rumor Test

Expected:
- people who hear and believe it may change behavior;
- objective truth remains unchanged;
- correction spreads separately.

Failure condition:
Rumor changes objective event history.

## 7.44.34 Secret Leakage Test

Scenario:
One confidant reveals a secret to one other person.

Expected:
- knowledge expands only through actual transmissions;
- not globally exposed immediately.

Failure condition:
Secret status flips from hidden to universally known.

## 7.44.35 Insight Under Deception

Scenario:
Skilled deceiver lies to skilled observer.

Expected:
- uncertainty remains possible;
- neither skill guarantees outcome;
- narration reflects evidence available.

Failure condition:
Higher numeric skill automatically knows or fools without contextual resolution.

# Access and Routine Tests

## 7.44.36 Busy Friend Test

Scenario:
Close friend is working during emergency-duty shift.

Expected:
- relationship improves chance of brief access;
- job responsibilities may still prevent long conversation.

Failure condition:
Friendship makes schedules irrelevant.

## 7.44.37 Restricted Institution Test

Scenario:
Character's close friend works in secure archive.

Expected:
- friend may arrange legitimate meeting or advocate;
- cannot automatically grant forbidden clearance.

Failure condition:
Relationship bypasses institution entirely.

## 7.44.38 Repeated Uninvited Visit Test

Expected:
- increasing discomfort or boundary response;
- no automatic access from persistence.

Failure condition:
Enough visits eventually unlock the home.

# NPC Autonomy Tests

## 7.44.39 NPC Chooses Another Person

Scenario:
NPC has stronger mutual romantic development with another NPC than with player.

Expected:
- NPC may pursue that relationship;
- player receives no protagonist priority.

Failure condition:
NPC remains artificially available for player.

## 7.44.40 NPC Refuses Player

Expected:
- refusal can stand;
- NPC does not become a puzzle requiring correct dialogue sequence.

Failure condition:
Every refusal has a hidden combination that guarantees success.

## 7.44.41 NPC Changes Independently

Scenario:
Player leaves village for several years.

Expected:
- important NPCs may change jobs, relationships, goals, and beliefs;
- changes have causal histories.

Failure condition:
NPCs remain frozen awaiting player return.

# Hidden-State Tests

## 7.44.42 Concealed Resentment Test

Scenario:
NPC remains polite while resentful.

Expected:
- subtle behavioral changes may be observable;
- exact Resentment remains hidden.

Failure condition:
Narration exposes the exact hidden emotion without evidence.

## 7.44.43 Wrong Player Inference Test

Scenario:
Player reasonably misreads ambiguous behavior.

Expected:
- later revelation explains why the inference was understandable;
- game did not fabricate contradictory state afterward.

Failure condition:
Surprise depends on information that had no prior causal support.

## 7.44.44 OOC Knowledge Separation Test

Scenario:
Player sees debug information.

Expected:
- player character knowledge remains unchanged.

Failure condition:
NPC dialogue or choices suddenly assume debug knowledge.

# Persistence Tests

## 7.44.45 Broken Promise Across Sessions

Scenario:
Player makes serious promise, session ends, several sessions pass.

Expected:
- promise remains;
- NPC remembers according to memory rules;
- future fulfillment or violation still matters.

Failure condition:
Promise disappears because original conversation left context.

## 7.44.46 Hidden Roll Persistence

Scenario:
Hidden check determines NPC believed a lie.

Expected:
- result persists on reload;
- later behavior remains consistent.

Failure condition:
Same state is rerolled in new session.

## 7.44.47 Long Time-Skip Test

Scenario:
Five years pass.

Expected:
- relevant relationships and goals evolve;
- routine events compress;
- defining state persists.

Failure condition:
everything freezes or every relationship randomly changes.

# Procedural NPC Tests

## 7.44.48 Ordinary NPC Test

Generate ten background/supporting NPCs.

Expected:
- most are relatively ordinary;
- jobs, skills, networks, and histories cohere;
- not everyone has tragedy, rare ability, or secret destiny.

Failure condition:
generation overproduces exceptional characters.

## 7.44.49 Exceptional NPC Test

Generate one rare specialist.

Expected:
- exceptional ability has plausible cause;
- rarity and prerequisites hold;
- weaknesses still exist.

Failure condition:
importance creates omni-competence.

## 7.44.50 Network Coherence Test

Generated adult NPC should usually have plausible:
- coworkers;
- family or prior ties;
- acquaintances.

Failure condition:
persistent adults repeatedly spawn socially isolated without explanation.

# Cross-Ruleset Tests

## 7.44.51 Injury/Social Interface Test

Scenario:
Character saves severely injured teammate.

Expected:
- Ruleset 4 owns injury;
- Ruleset 7 may create gratitude, fear, obligation, Attachment;
- no social outcome changes wound severity directly.

## 7.44.52 Genjutsu/Social Interface Test

Scenario:
Genjutsu creates fear.

Expected:
- Ruleset 3 owns induced state;
- Ruleset 7 consumes fear socially;
- induced fear is not mislabeled as genuine Loyalty.

## 7.44.53 Promotion/Social Interface Test

Scenario:
NPC promoted over peer.

Expected:
- institution owns promotion;
- Ruleset 7 may create Respect, jealousy, legitimacy changes;
- promotion does not auto-grant Leadership mastery.

## 7.44.54 Gift/Economy Interface Test

Scenario:
Expensive gift given.

Expected:
- economy owns value;
- Ruleset 7 interprets meaning;
- expensive gift may be disliked or inappropriate.

# Extreme-State Tests

## 7.44.55 Maximum Trust Test

Even at extremely high Trust:
- NPC may refuse unethical request;
- institutional restrictions remain;
- disagreement remains possible.

Failure condition:
Trust becomes obedience.

## 7.44.56 Maximum Hostility Test

Even at extreme Hostility:
- strategic cooperation may occur;
- shared emergency may temporarily align goals.

Failure condition:
Hostility mechanically prevents all cooperation.

## 7.44.57 Maximum Skill vs Hard Boundary

Exceptional social skill confronts:
- core moral red line;
- firm refusal;
- impossible knowledge;
- formal security restriction.

Expected:
skill improves judgment and presentation but does not erase the boundary.

## 7.44.58 Extreme Fear Test

Overwhelming fear may produce:
- compliance;
- freezing;
- fleeing;
- deception;
- resistance.

Failure condition:
Fear always produces obedience.

# Regression Testing

## 7.44.59 Rule Change Regression

Whenever a major Ruleset 7 rule changes, rerun affected tests.

Examples:
- relationship dimension changes -> rerun relationship and romance tests;
- social-resolution changes -> rerun Persuasion, Deception, retry, and autonomy tests;
- persistence changes -> rerun save/load and time-skip tests.

## 7.44.60 Canonical Test Cases

A compact set of canonical scenarios should eventually be stored for repeat testing.

Recommended minimum:
1. reasonable request;
2. firm refusal;
3. deception vs Insight;
4. interrogation of unknown information;
5. betrayal and repair;
6. formal leader with low legitimacy;
7. mutual attraction but incompatible goals;
8. adult Seduction after clear refusal;
9. local rumor spread;
10. off-screen NPC relationship development;
11. long time skip;
12. cross-ruleset injury/social event.

## 7.44.61 Expected-Range Testing

Tests should not require one exact scripted outcome unless the situation is deterministic.

Instead define acceptable ranges.

Example:
A trusted friend asked for a moderate favor might:
- agree;
- agree conditionally;
- refuse due conflicting duty.

All can be valid depending on state.

The test fails only if outcomes violate established causality.

## 7.44.62 Symmetry Test

For every major social mechanic, ask:

**Would this still be fair and coherent if an NPC used it on the player?**

If not, investigate protagonist privilege or agency violation.

## 7.44.63 Adversarial Exploit Test

Actively attempt:
- reroll spam;
- gift spam;
- compliment spam;
- apology loops;
- obligation inflation;
- Insight fishing;
- schedule abuse;
- social-skill bypasses.

The system should respond through causal consequences, not reward the exploit.

## 7.44.64 Calibration Log

When play reveals a mismatch, record:
- scenario;
- expected behavior;
- actual behavior;
- cause;
- rule implicated;
- proposed adjustment.

This creates evidence-based balancing instead of ad hoc rule changes.

## 7.44.65 Edge-Case Review Questions

Before approving an unusual social outcome, ask:

1. Is the outcome possible?
2. What does each person want?
3. What does each person know?
4. What relationship already exists?
5. Which skill actually applies?
6. What does Ruleset 2 resolve?
7. Does another ruleset own part of the event?
8. Does the result preserve agency?
9. Does it create appropriate memory and consequences?
10. Would the same logic apply to an NPC?

## 7.44.66 Design Standard

Ruleset 7 should be revised if testing repeatedly shows:
- high skill behaving like mind control;
- low skill never succeeding in favorable contexts;
- relationships overwhelming all other motives;
- relationships having no practical effect;
- hidden state producing unfair surprise;
- NPCs receiving different agency protections than players;
- social retries being exploitable;
- off-screen simulation generating excessive drama;
- persistence losing causal history;
- cross-ruleset ownership conflicts.

## Completion Criterion

Ruleset 7 is sufficiently calibrated for play when:
- ordinary outcomes feel predictable in broad terms but not deterministic;
- exceptional social skill is powerful without breaking autonomy;
- relationship dimensions produce distinct consequences;
- NPCs act independently;
- hidden information remains fair;
- repeated behavior creates memory and consequence;
- long-running state remains coherent;
- edge cases resolve without needing arbitrary GM exceptions.

## Governing Rule

**Calibration should test the social system at its boundaries as well as its center, ensuring that competence matters, relationships matter, context matters, and consequences persist without allowing any of those factors to become a universal override of agency, reality, or other rulesets.**
