# 7.1 — Core Philosophy, Scope & Ownership

Status: Provisional design section pending explicit approval.

Ruleset 7 governs individual NPC agency, social state, relationships, social interpretation, and the persistent consequences of interaction.

It does not replace Ruleset 2's resolution engine, Ruleset 1's character-capability system, Ruleset 3's supernatural mind-affecting mechanics, or later systems governing factions, law, politics, missions, and economics.

## Core Principles

1. **NPCs are autonomous people, not player-facing functions.**
   NPCs should possess their own motives, beliefs, relationships, obligations, routines, preferences, fears, and priorities. They do not exist primarily to provide quests, information, training, romance, rewards, opposition, or validation to the player.

2. **The same social reality applies to PCs and NPCs.**
   NPCs may persuade, deceive, intimidate, befriend, resent, seduce, recruit, manipulate, forgive, betray, and form relationships with one another using the same underlying principles that govern player interactions. The player does not receive a unique social exemption.

3. **Agency is preserved even when influence succeeds.**
   Social success modifies willingness, interpretation, confidence, emotional response, negotiation position, or available choices. It does not normally seize control of another person's decision-making. NPCs retain the ability to refuse, reconsider, withdraw, compromise, lie, comply reluctantly, or act for mixed reasons.

4. **Social capability operates inside plausible possibility.**
   Ruleset 2 may determine how well a social attempt succeeds, but exceptional resolution cannot create an outcome that the circumstances, relationship, target, and action do not make possible. A social skill cannot manufacture lifelong loyalty, erase a fundamental incompatibility, create knowledge the target lacks, or bypass an absolute refusal merely because a roll is exceptional.

5. **Relationships are multi-dimensional rather than one approval score.**
   Trust, respect, affection, fear, loyalty, familiarity, obligation, resentment, hostility, romantic interest, and adult arousal may coexist in different combinations. One dimension should not silently stand in for another.

6. **Relationship dimensions are not interchangeable currencies.**
   High affection does not automatically create trust. Fear does not equal loyalty. Respect does not imply friendship. Adult arousal does not imply affection, compatibility, commitment, or consent. Obligation does not guarantee willingness.

7. **NPC decisions should be causally explainable from their perspective.**
   Important choices should arise from what the NPC knows or believes, what they want, what they fear, whom they care about, what they owe, what they value, and what consequences they expect. NPCs should not make unexplained decisions merely because the plot needs them to.

8. **NPCs act on beliefs, not objective omniscience.**
   The simulation may know the truth while an NPC believes something incomplete, false, outdated, biased, manipulated, or uncertain. NPC behavior must use the NPC's accessible information rather than hidden world-state knowledge.

9. **Social information is often uncertain.**
   Characters should not automatically know exact trust, attraction, suspicion, resentment, loyalty, motives, secrets, or emotional states. They receive observable behavior and whatever they can reasonably infer through context, familiarity, Perception, social skills, evidence, or special abilities.

10. **NPC memory matters.**
    Meaningful conversations, favors, promises, betrayals, humiliation, rescue, abandonment, threats, lies, shared hardship, affection, and repeated behavior should influence later interactions. A conversation ending does not reset social state.

11. **Repeated behavior establishes patterns.**
    NPCs learn what a character is like over time. Consistently keeping promises, exploiting people, lying, flirting indiscriminately, protecting teammates, breaking rules, showing mercy, or acting recklessly can become part of how others predict future behavior.

12. **Social context matters as much as raw skill.**
    Rank, authority, setting, witnesses, culture, timing, leverage, evidence, prior history, stakes, mood, danger, institutional rules, and the reasonableness of a request may matter more than the actor's skill level.

13. **Not every social interaction requires a roll.**
    Routine conversation, obvious cooperation, trivial requests, established habits, and outcomes with no meaningful uncertainty may resolve deterministically. Rolls are used when uncertainty matters.

14. **Social resolution should resolve meaningful intent, not every sentence.**
    Dialogue may contain many lines without requiring repeated checks. A roll should normally resolve a meaningful attempt, contested objective, negotiation phase, deception, emotional turning point, or other uncertain social action.

15. **Failure changes the situation.**
    Failed persuasion, deception, intimidation, seduction, negotiation, or interrogation should not simply invite an identical retry. Failure can create suspicion, embarrassment, irritation, resistance, reduced credibility, new demands, withdrawal, or other state changes.

16. **Success should have degrees and tradeoffs.**
    A social success may produce partial cooperation, a concession, temporary compliance, increased openness, delayed agreement, a counteroffer, or cooperation with conditions rather than a binary yes/no result.

17. **Emotions influence decisions without replacing personality or agency.**
    Anger, fear, grief, jealousy, pride, shame, stress, affection, or adult arousal can affect judgment and willingness, but they should not mechanically dictate behavior. Different NPCs respond differently to the same emotional state.

18. **Romance is a relationship process, not a reward track.**
    Attraction, chemistry, affection, romantic interest, courtship, trust, intimacy, commitment, jealousy, conflict, separation, and reconciliation may develop separately. Romantic involvement should emerge from compatible state and history rather than unlocking at a fixed relationship score.

19. **Adult arousal is distinct from consent and romantic attachment.**
    Arousal may exist as an adult-only contextual relationship dimension, but it never automatically grants consent, willingness, affection, romantic interest, trust, exclusivity, or future access. It may rise, fall, conflict with other states, or be ignored by the NPC's decision.

20. **Seduction is influence, not control.**
    Seduction may improve presentation, flirtation, chemistry, tension, reciprocal interest, or openness between adults where the possibility already exists. It cannot override refusal, erase boundaries, bypass incompatibility, or transform an impossible romantic or sexual outcome into an automatic success.

21. **Younger characters use age-appropriate romance only.**
    Crushes, dating, romantic interest, embarrassment, jealousy, rejection, affection, and relationship development may exist for younger characters where appropriate to the setting. Adult sexual-state mechanics such as arousal and seduction do not apply to them.

22. **NPC-to-NPC life continues without the player.**
    Friendships, rivalries, romances, arguments, promotions, betrayals, alliances, grief, family events, and changing opinions may develop off-screen. The social world should not freeze when the player is absent.

23. **The player is important because of causal impact, not protagonist privilege.**
    The player's actions may make them famous, feared, loved, trusted, hated, or politically significant, but NPCs should not become disproportionately interested in the player merely because the player is the protagonist.

24. **Simulation depth should scale with relevance.**
    Major NPCs may track detailed motives, memories, relationships, and beliefs. Background NPCs can use compressed state until greater detail becomes meaningful. Increased importance should expand simulation without contradicting established facts.

25. **Narrative portrayal follows underlying state.**
    Dialogue, body language, tone, hesitation, affection, hostility, flirtation, and other descriptions should reflect the simulated NPC state. Narrative flourish should not secretly create or erase relationship changes that the underlying state does not support.

26. **Complexity should emerge from simple interacting states.**
    The system should prefer a limited set of meaningful persistent variables, memories, motives, and tags over hundreds of bespoke relationship rules. Rich behavior should arise from interaction between systems rather than excessive bookkeeping.

## Default Social Consequence Chain

The default conceptual chain is:

**Context → Actor Intent → NPC Interpretation → Existing Willingness / Resistance → Resolution if Uncertain → NPC Decision / Response → Immediate Social Consequence → Relationship / Memory / Reputation Update → Future Behavior**

Not every interaction needs every stage.

Routine or obvious interactions may compress several stages. High-stakes negotiations, betrayals, confessions, interrogations, political conversations, or major romantic developments may use the full chain.

## Five Persistent NPC Social Layers

Ruleset 7 should generally distinguish five layers:

### 1. Identity & Disposition
Relatively stable traits:
- personality;
- values;
- preferences;
- boundaries;
- temperament;
- cultural background;
- long-term tendencies.

### 2. Goals & Motives
What the NPC currently wants, fears, needs, or feels obligated to accomplish.

### 3. Knowledge & Beliefs
What the NPC knows, suspects, misunderstands, remembers, or believes about the world and other people.

### 4. Relationship State
Persistent interpersonal state such as:
- trust;
- respect;
- affection;
- fear;
- loyalty;
- familiarity;
- obligation;
- resentment;
- hostility;
- romantic interest;
- adult arousal where applicable.

### 5. Current Social / Emotional State
Shorter-lived state such as:
- mood;
- stress;
- anger;
- grief;
- confidence;
- jealousy;
- embarrassment;
- suspicion;
- immediate willingness;
- current interpersonal tension.

These layers interact but should not collapse into a single disposition number.

## Ruleset Ownership Principle

Each mechanic should have one primary owner.

Ruleset 7 owns a mechanic when it defines:
- what the social state represents;
- how it is structured;
- what persistent NPC information is stored;
- how social events normally change it;
- how NPCs interpret that state when making decisions.

Other rulesets may supply inputs, modifiers, constraints, or consequences without recreating the same mechanic.

## Ruleset 7 Owns

Ruleset 7 primarily owns:
- individual NPC motives and priorities;
- NPC beliefs and social knowledge;
- NPC memory relevant to social behavior;
- individual-to-individual relationship state;
- personal trust, respect, affection, fear, loyalty, familiarity, obligation, resentment, hostility, romantic interest, and adult arousal where applicable;
- social interpretation of actions;
- social willingness and resistance;
- persuasion, negotiation, deception, intimidation, interrogation, leadership, etiquette, seduction, and related social-action meaning;
- interpersonal promises, favors, grudges, and obligations;
- individual reputation perception;
- NPC social routines and access where primarily interpersonal;
- NPC-to-NPC social development;
- social consequences of personal interactions;
- hidden social state and player-facing social cues.

## Ruleset 1 Owns Character Capability

Ruleset 1 owns:
- attributes;
- skills;
- mastery;
- prerequisites;
- training;
- growth;
- potential;
- progression.

Ruleset 7 may define what Persuasion, Insight, Negotiation, Seduction, Leadership, Deception, or another social skill accomplishes.

Ruleset 1 defines how those skills are learned and improved.

## Ruleset 2 Owns Resolution & Probability

Ruleset 2 owns:
- difficulty;
- probability;
- opposed checks;
- hidden checks;
- uncertainty;
- degrees of success;
- critical or exceptional outcomes;
- information-dependent resolution.

Ruleset 7 determines:
- what the social action is attempting;
- what outcomes are socially possible;
- what contextual factors matter;
- what state changes follow the result.

Ruleset 2 determines uncertain resolution where a check is actually required.

## Ruleset 3 Owns Chakra, Jutsu & Supernatural Mental Effects

Ruleset 3 owns:
- genjutsu mechanics;
- chakra-based sensory effects;
- supernatural mind alteration;
- memory-altering techniques;
- compulsions created by jutsu;
- technique costs, mastery, and limits.

Ruleset 7 owns the social consequences afterward:
- whether someone resents being manipulated;
- whether trust is damaged;
- what they remember if the technique permits memory;
- how others react if the manipulation is discovered.

Normal persuasion or seduction must never silently reproduce supernatural mind control.

## Ruleset 4 Owns Physical & Medical State

Ruleset 4 owns:
- injury;
- pain;
- fatigue;
- physical impairment;
- intoxication where modeled there;
- medical condition;
- combat aftermath;
- capture/restraint physical state.

Ruleset 7 may consume those states as social context.

For example, exhaustion may reduce patience, injury may create fear or dependency, and captivity may alter the credibility of a threat.

Ruleset 7 should not redefine the physical mechanics.

## Later Rulesets Own Their Institutional Systems

Future rulesets should own:
- faction structure;
- village governance;
- laws and criminal procedure;
- mission generation and administration;
- economic prices and markets;
- political offices and formal institutional power;
- stealth/infiltration mechanics;
- broader world-event simulation.

Ruleset 7 may determine how individual NPCs inside those systems feel, decide, communicate, negotiate, cooperate, resist, or exploit those structures.

## Individual Relationship vs Institutional Standing

A major boundary is:

**Ruleset 7 owns what a person thinks and feels about another person.**

A later faction or politics system may own:
- official clan standing;
- village reputation;
- criminal status;
- diplomatic relations;
- political approval;
- formal rank or office.

An individual NPC may disagree with the institution.

Example:
A shinobi may personally trust the player while their village officially considers the player a security risk.

Both states can be true simultaneously.

## Social Skill Cannot Create Missing Information

A successful interrogation, persuasion, flirtation, deception, or intimidation attempt cannot cause an NPC to reveal information they do not possess.

It may:
- reveal what they know;
- reveal what they falsely believe;
- expose uncertainty;
- cause them to speculate;
- persuade them to seek information elsewhere.

The distinction between knowledge and willingness must remain intact.

## Design Standard

A Ruleset 7 mechanic should be rejected or revised if it:
- reduces relationships to one universal approval meter;
- makes social skill function as mind control;
- allows one exceptional roll to erase established character history without causal justification;
- treats fear as loyalty or arousal as consent;
- assumes NPCs know facts they could not plausibly know;
- lets repeated identical attempts brute-force an NPC;
- freezes NPC relationships when the player is absent;
- makes every important NPC disproportionately interested in the player;
- reveals exact hidden social state without an in-world reason;
- duplicates Ruleset 1 progression or Ruleset 2 probability;
- reproduces supernatural effects owned by Ruleset 3 through mundane social mechanics;
- ignores physical or medical states owned by Ruleset 4 when they are materially relevant;
- requires detailed bookkeeping for every incidental background interaction;
- makes romance a reward ladder rather than a relationship process;
- allows seduction, attraction, or adult arousal to override refusal or boundaries;
- gives important NPCs unexplained immunity from social consequences;
- forces all NPCs to react similarly to the same event regardless of personality, values, motives, or context.

## Guiding Test

When resolving an NPC's social behavior, the simulation should be able to answer:

**Given who this person is, what they currently know and believe, what they want, how they feel about the people involved, what just happened, and what they expect will happen next — does this response make sense from their perspective?**

If the answer is no, the behavior should be revised even if it would be more convenient for the narrative.
