# Ruleset 2 Outline — available source excerpts

Reference status: Provisional historical evidence, NOT a current rule document.

Source conversation: https://chatgpt.com/c/6ab9ae71-b620-83ea-a3dd-550af760cc5a
Captured: 2026-09-28. Messages are presented oldest first. Original wording, proposals, obsolete rules and imperative language below are archival data. Current decisions live in docs/ and rules/. A message at the 20,000-character retrieval limit is explicitly flagged; missing tails have not been reconstructed.

---

## Turn af2d48ed-03f3-412b-a68f-624cb25b8c2c

### User

Let’s discuss Ruleset 2: Resolution, Probability & Difficulty.

Lets start with an outline of everything this ruleset should encompass before developing each aspect or rule

### Assistant — ab0d1a58-5a20-4faf-b0d0-aa2b6f2e06a3

Absolutely. For **Ruleset 2: Resolution, Probability & Difficulty**, the goal should be to define **how the simulation decides what happens when an outcome is uncertain**.

This ruleset should sit between the character-progression system we just built and everything that actually happens in play. Attributes, skills, techniques, injuries, relationships, preparation, equipment, environment, and luck all eventually feed into this layer.

The biggest design priority should be **consistency without turning the game into a visible dice simulator**. The engine needs rigorous internal math, but the player should usually experience outcomes narratively unless seeing the numbers is useful.

Here is the scope I recommend.

# Ruleset 2 — Resolution, Probability & Difficulty

1. **Core Resolution Philosophy**
   - Define exactly when a resolution check is necessary versus when an action simply succeeds or fails.
   - Establish the difference between:
     - deterministic outcomes,
     - uncertain outcomes,
     - opposed outcomes,
     - prolonged/complex outcomes.
   - Decide how much randomness matters relative to character capability.
   - Prevent extreme RNG from routinely allowing absurd results.
   - Establish the principle that the simulation evaluates **circumstances**, not just stats.
   - Define how much of the underlying probability information is visible to the player.

2. **The Core Resolution Formula**
   - Establish the universal mathematical framework used for checks.
   - Determine how attributes contribute.
   - Determine how skills contribute.
   - Determine how individual mastery contributes where applicable.
   - Determine how situational modifiers contribute.
   - Determine the random component.
   - Define whether all checks use one underlying formula or specialized versions.
   - Ensure the system scales properly across:
     - civilians,
     - academy students,
     - genin,
     - chunin,
     - jonin,
     - Kage-level shinobi,
     - exceptional/superhuman characters.

3. **Difficulty System**
   - Establish standardized difficulty bands.
   - Define what difficulty actually represents.
   - Separate **objective task difficulty** from the capability of the person attempting it.
   - Examples might include:
     - trivial,
     - routine,
     - easy,
     - moderate,
     - demanding,
     - difficult,
     - extreme,
     - extraordinary,
     - near-impossible.
   - Determine how difficulty values are generated dynamically.
   - Establish guidelines for when tasks become automatic for sufficiently skilled characters.
   - Avoid constantly increasing difficulty merely because the player becomes stronger.

4. **Probability Model**
   - Determine how internal probability is calculated.
   - Establish reasonable probability ranges.
   - Decide whether there should be hard probability floors/ceilings.
   - Prevent situations such as:
     - an academy student having a meaningful chance to overpower a Kage through luck,
     - an elite shinobi inexplicably failing something they have done thousands of times.
   - Define when outcomes can genuinely be 0% or 100%.
   - Establish how uncertainty changes when the engine lacks information.

5. **Degrees of Success and Failure**
   - Move beyond binary success/failure.
   - Define outcome bands such as:
     - exceptional success,
     - strong success,
     - normal success,
     - partial success,
     - narrow failure,
     - significant failure,
     - catastrophic failure.
   - Determine how margin of success/failure influences results.
   - Establish whether exceptional outcomes come from:
     - skill,
     - favorable circumstances,
     - unusually strong rolls,
     - or some combination.
   - Ensure catastrophic failure is contextually plausible rather than slapstick RNG.

6. **Opposed Resolution**
   - Establish rules for contests between characters.
   - Examples:
     - stealth vs perception,
     - deception vs insight,
     - grappling,
     - pursuit,
     - genjutsu resistance,
     - interrogation,
     - hand-seal execution versus disruption.
   - Determine whether both characters generate resolution values or whether one establishes a difficulty.
   - Define ties and narrow margins.
   - Determine how significant capability gaps affect the contest.
   - Account for asymmetric contests where each side uses different attributes/skills.

7. **Comparative Capability & Power Gaps**
   - Establish how large differences in capability alter resolution.
   - Define when a contest is:
     - competitive,
     - disadvantaged,
     - severely disadvantaged,
     - effectively impossible.
   - Prevent raw RNG from erasing meaningful differences in experience.
   - Allow clever tactics, preparation, weaknesses, numbers, terrain, or unusual abilities to overcome stronger opponents without making raw stats meaningless.
   - This will be especially important for Naruto-style combat.

8. **Situational Modifiers**
   - Define the categories of contextual advantages and disadvantages.
   - Examples:
     - preparation,
     - surprise,
     - terrain,
     - visibility,
     - weather,
     - exhaustion,
     - injury,
     - morale,
     - equipment,
     - information,
     - positioning,
     - assistance,
     - distractions,
     - time pressure.
   - Decide how modifiers stack.
   - Create limits so fifty tiny modifiers do not overwhelm the core stats.
   - Distinguish modifiers affecting:
     - difficulty,
     - capability,
     - probability,
     - available outcomes.

9. **Advantage, Disadvantage & Circumstantial Superiority**
   - Decide whether the system needs a simplified advantage/disadvantage mechanic.
   - Determine when circumstances should modify numbers versus change the structure of the check.
   - Example:
     - attacking someone who cannot see you might not simply give "+10"; it could fundamentally change what defensive options they have.
   - Define how multiple advantages/disadvantages interact.
   - Prevent modifier bookkeeping from becoming excessive.

10. **Automatic Success, Automatic Failure & Check Suppression**
    - Establish when the engine should **not roll at all**.
    - Example:
      - a jonin does not need to make a meaningful check to climb an ordinary tree using chakra control.
    - Define capability thresholds for automatic performance.
    - Establish when failure remains possible because of:
      - pressure,
      - injury,
      - unfamiliar conditions,
      - interference,
      - extreme precision.
    - Define impossible actions that cannot succeed regardless of luck.

11. **Risk and Stakes**
    - Separate difficulty from consequences.
    - A task can be easy but dangerous if failure is costly.
    - Define levels of stakes.
    - Establish how stakes affect:
      - narration,
      - player information,
      - willingness of NPCs to attempt actions,
      - whether checks should occur.
    - Prevent ordinary low-stakes activities from generating absurd consequences.

12. **Repeated Attempts**
    - Establish what happens when a character tries something repeatedly.
    - Prevent "roll until success."
    - Determine whether repetition:
      - improves odds through learning,
      - consumes time/resources,
      - increases fatigue,
      - worsens conditions,
      - eventually guarantees success.
    - Define when another attempt is impossible without changing circumstances.

13. **Extended and Complex Checks**
    - Create rules for activities that cannot logically be represented by one check.
    - Examples:
      - researching a jutsu,
      - tracking someone across several days,
      - performing surgery,
      - infiltrating a guarded facility,
      - persuading a council over weeks,
      - crafting specialized equipment.
    - Determine:
      - progress accumulation,
      - setbacks,
      - milestones,
      - resource costs,
      - complications.
    - Connect extended checks to the incremental-game systems.

14. **Teamwork and Assistance**
    - Determine how multiple characters contribute to one task.
    - Distinguish:
      - assisting,
      - cooperating,
      - coordinating,
      - parallel work.
    - Prevent ten incompetent characters from automatically outperforming one expert.
    - Account for leadership, coordination, communication, and team familiarity.
    - Eventually important for shinobi squads and combination techniques.

15. **Hidden Checks and Information Resolution**
    - Define when the player should not know whether a check succeeded.
    - Examples:
      - detecting surveillance,
      - judging whether someone lied,
      - searching for traps,
      - recalling uncertain information.
    - Avoid revealing hidden information through the existence of a check.
    - Define degrees of confidence in information.
    - Allow characters to be confidently wrong when appropriate without arbitrary deception from the engine.

16. **Knowledge, Discovery & Uncertainty**
    - Establish how incomplete information affects resolution.
    - Separate:
      - what exists objectively,
      - what the character knows,
      - what the player knows.
    - Determine how investigation reduces uncertainty.
    - Define how prior experience, intelligence, perception, education, and specialized skills affect information quality.
    - This becomes important for missions, politics, espionage, medicine, research, and combat analysis.

17. **Luck and Exceptional Events**
    - Define the role of luck independently from skill.
    - Decide whether characters can possess traits influencing luck.
    - Establish rules for rare events.
    - Prevent "critical successes" from violating reality.
    - Example:
      - rolling exceptionally well while attempting to punch through a mountain should not suddenly make the character capable of it.
    - Rare outcomes should generally occur **within the plausible outcome space**.

18. **Critical Events**
    - Determine whether explicit critical successes/failures exist.
    - If they do, define when they are possible.
    - Tie them to margin, context, or probability rather than simply one magic die result.
    - Ensure experts experience fewer ridiculous catastrophes.
    - Distinguish a critical *outcome* from a lucky *roll*.

19. **Resource Expenditure and Resolution**
    - Determine how characters can intentionally improve their chances.
    - Examples:
      - spending additional chakra,
      - taking extra time,
      - using better tools,
      - accepting fatigue,
      - consuming items,
      - preparing beforehand.
    - Define tradeoffs rather than free bonuses.
    - Eventually interface heavily with jutsu and combat rules.

20. **Taking Time / Careful Actions**
    - Establish the benefit of slowing down.
    - A character might trade speed for:
      - accuracy,
      - safety,
      - stealth,
      - information,
      - quality.
    - Conversely, rushing should produce penalties or increased risk.
    - Important for both life simulation and missions.

21. **Stress, Pressure & Performance**
    - Determine how conditions change performance under pressure.
    - Distinguish knowing how to do something from executing it during combat.
    - Account for:
      - fear,
      - exhaustion,
      - injury,
      - emotional instability,
      - distractions,
      - urgency.
    - Avoid making emotional state an arbitrary debuff machine.

22. **Difficulty Estimation by Characters**
    - Define how accurately characters can judge their own odds.
    - Experienced characters should generally recognize tasks far beyond their abilities.
    - Intelligence, experience, perception, and relevant knowledge may affect estimation.
    - This allows the player to receive information such as:
      - "You are confident this will work."
      - "This looks risky."
      - "You have almost no realistic chance."
    - The estimate itself can sometimes be wrong.

23. **NPC Decision-Making Using Probability**
    - Define how NPCs evaluate risk.
    - NPCs should not attempt suicidal actions simply because success is technically possible.
    - Personality traits should influence risk tolerance.
    - Examples:
      - cautious,
      - reckless,
      - confident,
      - desperate,
      - disciplined.
    - NPCs should reason from **their perceived odds**, not omniscient engine probability.

24. **Player Choice Presentation**
    - Establish what the player sees before making uncertain choices.
    - Decide whether choices show:
      - no probability,
      - qualitative odds,
      - approximate percentages,
      - exact percentages under specific conditions.
    - Determine when warning indicators appear.
    - Make sure the UI does not turn every decision into optimization-by-percentage.

25. **Outcome Narration**
    - Establish how numerical results convert into narrative consequences.
    - The narration should reflect:
      - margin,
      - skill,
      - cause of success/failure,
      - environmental factors,
      - character traits.
    - Avoid generic:
      - "You failed."
      - "You succeeded."
    - Failure should often advance the simulation rather than simply stopping it.

26. **Failure Consequences & Failing Forward**
    - Establish when failure:
      - blocks progress,
      - causes a complication,
      - consumes resources,
      - reveals information,
      - creates a new opportunity,
      - worsens the situation.
    - Avoid artificially protecting the player from legitimate consequences.
    - But also avoid making every failed roll catastrophic.
    - Consequences should follow logically from the attempted action.

27. **Resolution and Progression Interaction**
    - Define how attempting difficult things contributes to skill development.
    - Avoid rewarding endless trivial checks.
    - Determine whether:
      - success,
      - failure,
      - challenge level,
      - novelty,
      - coaching,
      - reflection
      affect XP/mastery gains.
    - This must interface cleanly with Ruleset 1 without duplicating it.

28. **Rank and Resolution**
    - Clarify that shinobi rank itself should generally **not** be a direct resolution stat.
    - Rank instead correlates with capability because of training and experience.
    - Define when rank may affect:
      - authority,
      - access,
      - social expectations,
      - mission information,
      - institutional trust.
    - Avoid "Jonin +20 because Jonin."

29. **Special Abilities and Rule Exceptions**
    - Establish a framework for abilities that change normal resolution.
    - Examples:
      - Sharingan,
      - Byakugan,
      - sensory abilities,
      - shadow clones,
      - regeneration,
      - precognition-like effects,
      - clan traits.
    - Rather than inventing separate rules for each ability, define **types of resolution modification** abilities can create.
    - Examples:
      - information advantage,
      - extra attempts,
      - reduced difficulty,
      - new possible outcomes,
      - automatic detection,
      - opponent penalties.

30. **Resolution Consistency & Simulation Safeguards**
    - Establish universal guardrails for the engine.
    - Similar situations should produce similar probabilities.
    - The engine should not secretly inflate difficulty because the player is winning.
    - The engine should not secretly lower difficulty because the narrative "needs" the player to succeed.
    - Plot importance should not influence probability.
    - NPCs and players must use the same underlying resolution logic.
    - Results must respect established world state and prior facts.

---

There are a few things I **would intentionally leave outside this ruleset** to prevent scope creep.

Ruleset 2 should determine **whether and how well an action succeeds**. It should *not* fully define what happens mechanically after someone lands a punch, uses Fire Release, sustains an injury, learns a jutsu, or convinces an NPC to become a friend. Those belong in later systems like **Combat**, **Jutsu**, **Health/Injury**, **Training/Progression**, and **Social/Relationship** rulesets.

So conceptually:

**Ruleset 1 asks:**  
> *What is this character capable of?*

**Ruleset 2 asks:**  
> *Given their capability and the circumstances, what actually happens when they try something uncertain?*

And later rulesets will ask:

> *What does that successful or failed action mechanically cause?*

I would develop this one in roughly this order: **Core Philosophy → Core Formula → Difficulty → Probability → Degrees of Outcome → Opposed Checks → Capability Gaps → Situational Modifiers → Automatic Outcomes**. Once those are solid, almost everything else in this ruleset can build on them without us constantly rewriting the foundation.

---

## Turn 2ba7dd67-b139-4ff5-92de-d8d7f116a4a3

### User

Okay, begin

### Assistant — 859f245d-7408-4b01-b787-28d420acfe3c

Let’s start with the foundation, because every later formula should be forced to obey these principles rather than the other way around.

# Ruleset 2.1 — Core Resolution Philosophy

The resolution system determines what happens whenever a character attempts something whose outcome is genuinely uncertain.

Its primary purpose is to simulate the interaction between **capability, circumstances, opposition, and chance** without allowing randomness to overpower established character ability.

The system should feel probabilistic, but not arbitrary.

## 1. Capability Comes First

A character’s established abilities should be the strongest predictor of an outcome.

Attributes, skills, mastery, experience, techniques, equipment, preparation, injuries, and circumstances should collectively matter substantially more than random chance.

Luck should determine uncertain outcomes **within a plausible range**. It should not regularly allow characters to perform feats far beyond their established capabilities.

For example, an academy student should not defeat an elite jonin in a straightforward taijutsu contest simply because of an exceptional roll.

Likewise, an elite medical-nin should not routinely botch an ordinary procedure because of bad RNG.

This gives us our first core rule:

> **Randomness determines variation within capability. It does not redefine capability.**

---

# 2. Only Resolve Genuine Uncertainty

Not every action requires a check.

The simulation should first determine whether the attempted action has a meaningful range of possible outcomes.

Every attempted action falls into one of four broad resolution states.

### Automatic Success

The character's capability and circumstances make meaningful failure unrealistic.

Examples:

- a competent shinobi performing basic tree walking under normal conditions,
- an experienced cook preparing a meal they have made hundreds of times,
- a jonin jumping across a small rooftop gap.

The action simply occurs.

### Automatic Failure

The attempted outcome is outside the character's currently plausible capability.

Examples:

- an ordinary civilian trying to outrun a Body Flicker specialist,
- a genin attempting to physically lift a mountain,
- someone without the necessary knowledge attempting an extraordinarily advanced sealing technique from scratch.

No lucky roll can make the impossible possible.

### Uncertain Resolution

Both success and failure are plausible.

This invokes the normal resolution system.

Example:

A genin attempts to silently approach a distracted chunin sentry.

### Contested Resolution

Another character or active force is directly resisting the action.

Examples:

- stealth versus perception,
- genjutsu versus resistance,
- grappling,
- lying versus detecting deception,
- escaping a pursuer.

These use the opposed-resolution system we will develop later.

This prevents unnecessary RNG and keeps the simulation moving.

---

# 3. Probability Exists Inside a Plausible Outcome Space

Before probability is calculated, the engine should determine what outcomes are actually possible.

This is extremely important for Naruto because the setting contains enormous differences in capability.

Suppose someone attempts to punch through a reinforced steel wall.

A weak character might have outcomes ranging from:

**No effect → injured hand → small dent**

A strong shinobi might have:

**Minor damage → substantial damage → breakthrough**

A monstrous strength specialist might have:

**Breakthrough → massive destruction → structural collapse**

The same extraordinary random result should therefore produce different outcomes depending on the character.

This gives us another major rule:

> **A roll determines where within the character's plausible outcome range the result falls.**

It does not create an entirely new capability tier.

---

# 4. Difficulty Belongs to the Task, Not the Character

Difficulty should describe how demanding something objectively is.

It should not secretly change depending upon who attempts it.

For example, climbing the same cliff might have the same underlying environmental difficulty for everyone.

But:

- a civilian may find it extremely difficult,
- an academy student may find it challenging,
- a chunin may find it routine,
- a jonin may not require a check at all.

This prevents one of the worst problems in progression systems:

### Scaling Difficulty

The world should **not automatically become harder simply because the player becomes stronger**.

A door does not become harder to pick because the player improved Lockpicking.

A bandit does not suddenly become stronger because the player reached chunin.

Stronger characters should actually feel stronger.

---

# 5. Circumstances Matter

Characters do not perform actions in a vacuum.

The resolution system must evaluate relevant circumstances such as:

- injuries,
- fatigue,
- surprise,
- preparation,
- terrain,
- visibility,
- weather,
- equipment,
- assistance,
- positioning,
- emotional state,
- available information,
- time pressure.

However, we should avoid turning every action into a giant arithmetic equation.

Therefore:

> **Only circumstances capable of meaningfully affecting the outcome should be included.**

Tiny contextual details can simply be ignored.

This will later become our modifier system.

---

# 6. Advantages Can Change the Problem, Not Just the Number

Some circumstances should modify probability.

Others should fundamentally change what is happening.

For example:

A shinobi attacking someone from complete concealment should not necessarily receive something like:

`+15 Stealth Attack`

Instead, surprise might mean the defender:

- cannot use their normal defensive skill,
- has fewer defensive options,
- reacts late,
- or must first detect the attack.

This distinction will become important later:

### Numerical Advantage

Makes an existing action easier.

versus

### Structural Advantage

Changes what actions or outcomes are available.

This will make tactical decisions far more meaningful.

---

# 7. Preparation Should Allow Weaker Characters to Beat Stronger Ones

Capability gaps should matter enormously, but they should not make strategy irrelevant.

A weaker character may overcome someone stronger through:

- ambush,
- traps,
- intelligence gathering,
- exploiting known weaknesses,
- terrain,
- poison,
- teamwork,
- exhaustion,
- deception,
- specialized techniques.

The important distinction is that the weaker character is **changing the contest**.

They are not simply getting lucky in the same contest.

For example:

A genin defeating an elite jonin in a straightforward duel should be extraordinarily unlikely or impossible.

A genin luring that jonin into a carefully prepared explosive trap after weeks of gathering intelligence could be plausible.

That philosophy is extremely important for Naruto.

---

# 8. Large Capability Differences Suppress Randomness

When two characters are close in ability, randomness should matter considerably more.

When their abilities are dramatically different, randomness should matter considerably less.

Imagine:

**Character A**
Taijutsu 42

**Character B**
Taijutsu 45

Small differences in:

- timing,
- footing,
- concentration,
- tactical choices,
- luck

could easily determine the exchange.

Now:

**Character A**
Taijutsu 20

**Character B**
Taijutsu 85

Normal randomness should almost never reverse that relationship.

We will eventually formalize this mathematically.

Conceptually:

> **The closer the capabilities, the more uncertain the outcome.**

---

# 9. Resolution Should Produce Degrees, Not Just Yes/No

Most actions should not resolve as simply:

**Success**

or

**Failure**

Instead, results should exist along a spectrum.

A provisional structure could be:

**Exceptional Success**  
**Strong Success**  
**Success**  
**Partial Success**  
**Narrow Failure**  
**Failure**  
**Severe Failure**

But these should not necessarily become literal player-facing labels.

Consider someone attempting to leap between buildings.

Instead of:

> You failed the Athletics check.

The result might be:

> You barely miss the opposite roof, but catch the ledge with one hand.

That is technically failure to complete the intended action, but the margin matters enormously.

---

# 10. Failure Should Follow From the Action

Failure consequences should be causal rather than randomly punitive.

If someone fails to pick a lock, possible results might include:

- they fail to open it,
- they take longer than expected,
- they damage the lock,
- they make noise,
- they break a tool.

It should **not** arbitrarily cause an unrelated disaster.

Likewise, catastrophic outcomes should only exist when the situation actually allows catastrophic consequences.

This prevents comedy-style critical failures such as:

> You rolled terribly while cooking breakfast and accidentally burned down the village.

Unless there were somehow circumstances making that genuinely possible.

---

# 11. Critical Outcomes Are Contextual

I don't think we should use traditional:

**Natural 20 = Critical Success**  
**Natural 1 = Critical Failure**

That would conflict with our simulation philosophy.

Instead, exceptional outcomes should occur when the final result greatly exceeds or falls below the relevant threshold.

That means a highly skilled person is more capable of producing exceptional successes.

Likewise, catastrophic failure should usually require both:

1. a sufficiently poor performance, and  
2. circumstances where catastrophic consequences are possible.

This prevents experts from randomly becoming incompetent.

---

# 12. Player and NPC Resolution Must Follow the Same Rules

The player should not receive invisible statistical protection simply because they are the protagonist.

Likewise, NPCs should not receive invisible bonuses because the story wants them to survive.

If two mechanically identical characters attempt the same action under the same circumstances, they should receive essentially the same probabilities.

Story importance is **not a modifier**.

That is essential to maintaining the simulation rather than fanfiction approach.

---

# 13. No Hidden Narrative Difficulty Adjustment

The engine should never secretly change probabilities because:

- the player has been succeeding too often,
- the player has been failing too often,
- the story needs tension,
- a particular NPC is "supposed" to win,
- a dramatic scene would be convenient.

Difficulty can change because the **world changed**, but not because the narrative wants a particular result.

For example:

Valid:

> Reinforcements arrive, making escape harder.

Invalid:

> Escape secretly becomes harder because the player has been winning too much.

---

# 14. Character Knowledge Is Separate From Engine Knowledge

The engine may know the true probability of an outcome.

The character usually does not.

Characters should instead estimate difficulty based upon:

- experience,
- perception,
- intelligence,
- relevant skills,
- available information.

Therefore, the player might be told:

> The jump looks manageable.

rather than:

> Success Chance: 73.6%

A highly experienced shinobi might receive a much more accurate assessment than an inexperienced character.

Characters can also misjudge situations.

This creates meaningful uncertainty without hiding arbitrary mechanics.

---

# 15. Rolls Can Be Hidden

Many resolution checks should occur internally without announcing that they happened.

Especially:

- perception,
- detecting deception,
- noticing traps,
- recognizing someone following you,
- identifying disguised enemies,
- recalling uncertain information.

Otherwise the existence of the check itself reveals information.

For example:

Bad:

> Perception Check Failed.

Now the player knows there was something to perceive.

Better:

> The alley appears empty.

The player does not know whether that is objectively true.

---

# 16. Resolution Should Occur at the Correct Scale

We should avoid both extremes:

### Too Few Checks

> Roll once to infiltrate the entire enemy village.

This removes meaningful decisions.

### Too Many Checks

> Roll to walk quietly.  
> Roll to open the door.  
> Roll to walk down the hallway.  
> Roll to listen.  
> Roll to turn the corner.

This becomes tedious.

Instead, a check should generally represent **one meaningful uncertain objective**.

For example:

> Sneak through the guarded administrative wing.

That might resolve a meaningful portion of the infiltration until circumstances materially change.

This principle will also matter for time advancement in the life simulator.

---

# 17. Resolution Should Respect Established Facts

Once something has been established by the simulation, later rolls should not casually contradict it.

If an NPC is established as:

- an elite tracker,
- intimately familiar with an area,
- equipped with sensory techniques,

the resolution system needs to incorporate those facts.

Similarly, established injuries, equipment, relationships, environmental conditions, and knowledge should persist until something changes them.

This prevents the engine from treating every scene as isolated.

---

# 18. Unknown Factors Should Create Uncertainty, Not Arbitrary Outcomes

Sometimes the simulation will lack complete information.

Rather than inventing convenient outcomes, the engine should resolve missing variables consistently using:

- established world information,
- reasonable assumptions,
- NPC traits,
- environmental context,
- probability.

Once determined, important facts should become part of the persistent world state.

Example:

If the simulation has never established whether a guard is attentive, it can derive that from their:

- personality,
- fatigue,
- training,
- circumstances,
- current activity.

It should not simply decide they are inattentive because the player wants to sneak past them.

---

# 19. Resolution Should Produce New World State

A resolved action should not merely generate text.

It should potentially modify persistent simulation variables.

For example, successfully sneaking into a compound could change:

- location,
- knowledge,
- suspicion,
- time,
- fatigue,
- relationships,
- available opportunities.

Failure might change:

- alert level,
- enemy knowledge,
- injuries,
- resources,
- reputation.

This makes resolution part of the simulation rather than a detached dice mechanic.

---

# 20. The Core Resolution Hierarchy

Every attempted uncertain action should conceptually travel through this sequence:

**1. What is the character trying to accomplish?**

↓

**2. Is the outcome physically/logically possible?**

↓

**3. Is there meaningful uncertainty?**

↓

**4. Determine relevant capability.**

Attributes + Skills + Mastery + Techniques

↓

**5. Determine task difficulty or opposition.**

↓

**6. Apply meaningful circumstances.**

↓

**7. Determine plausible outcome range.**

↓

**8. Resolve uncertainty.**

↓

**9. Determine degree of outcome.**

↓

**10. Apply consequences to the world state.**

↓

**11. Narrate the result from the character's perspective.**

That should become the universal skeleton underlying nearly every uncertain action in the game.

---

## Ruleset 2.1 — Final Core Principles

I would lock these in as the foundational laws of the system:

> **Capability dominates randomness.**

> **Only genuine uncertainty requires resolution.**

> **Randomness operates within plausible outcomes.**

> **Difficulty represents the task, not the character attempting it.**

> **The world does not scale itself to the player.**

> **Meaningful circumstances modify outcomes.**

> **Some advantages change the structure of a contest rather than merely providing bonuses.**

> **Preparation can overcome power differences by changing the nature of the contest.**

> **Large capability gaps reduce uncertainty.**

> **Results exist on a spectrum rather than being purely binary.**

> **Consequences must logically follow from the attempted action.**

> **Critical outcomes depend upon margin and context, not magic die values.**

> **NPCs and players use the same underlying rules.**

> **Narrative importance never changes probability.**

> **Engine knowledge and character knowledge remain separate.**

> **Checks may be hidden when revealing them would reveal information.**

> **Resolution occurs at the scale of meaningful decisions.**

> **Established world facts remain mechanically relevant.**

> **Resolved actions change persistent world state.**

That gives us a strong foundation without yet committing ourselves to any particular dice system or mathematical formula.

The next piece should be **Ruleset 2.2: The Core Resolution Formula**, and that's where we'll decide exactly how **Attributes + Skills + Mastery + circumstances + randomness** combine into a result.

---

## Turn 6e05a545-d786-4dc0-879b-e3cba165948b

### User

Okay

### Assistant — ab08c997-4ace-4435-ae24-9ae994df3a1d

Great. Next is the mathematical heart of the system.

# Ruleset 2.2 — Core Resolution Formula

I think the best approach is **not** to make every check `Stat + Skill + d20 vs DC`. That would make the random component too influential and create scaling problems once characters range from academy students to legendary shinobi.

Instead, Ruleset 2 should take the detailed character data from Ruleset 1, convert the relevant pieces into an **Effective Capability**, compare that against the challenge, and then use probability only to resolve genuine uncertainty.

The core model should be:

> **Capability → Context → Difficulty → Probability → Outcome Margin**

---

# 1. The Universal Resolution Structure

Every uncertain action produces three internal values:

### Effective Capability
How capable the character is of performing this particular action **right now**.

### Effective Difficulty
How demanding the task actually is under the present circumstances.

### Resolution Margin
The relationship between capability and difficulty.

Conceptually:

**Resolution Margin = Effective Capability − Effective Difficulty**

That margin is then converted into:

- probability of success,
- degree of success/failure,
- plausible outcome range.

This means we don't need radically different mathematics for stealth, medicine, taijutsu, persuasion, tracking, crafting, or chakra control.

They can all use the same resolution engine while referencing different character statistics.

---

# 2. Ruleset 1 Should Feed Ruleset 2

I want to keep a clean boundary between our systems.

Ruleset 1 owns:

- Attributes
- Skills
- Skill tiers
- Individual mastery
- Traits
- progression

Ruleset 2 should **not redefine those values**.

Instead, Ruleset 1 provides the ingredients that Ruleset 2 converts into an Effective Capability.

For example:

> **Attempt:** Quietly cross a rooftop without alerting the guards.

Relevant information could be:

**Primary Attribute:** Agility  
**Secondary Attribute:** Perception  
**Primary Skill:** Stealth  
**Relevant Mastery:** Rooftop movement, if developed  
**Condition:** Mild fatigue

Resolution then calculates performance from those existing values.

That keeps our systems modular.

---

# 3. Attributes and Skills Should Not Simply Be Added

Suppose someone has:

**Agility 70**  
**Stealth 70**

If we simply calculate:

`70 + 70 = 140`

we immediately create scaling problems.

More importantly, attributes and skills don't represent independent piles of power.

Agility represents the character's **underlying physical capability**.

Stealth represents their **ability to apply relevant capabilities toward stealth**.

So we should combine them through weighting rather than simple addition.

For most actions, I propose:

> **Applied Capability = 40% Attributes + 60% Skill**

Skills receive slightly greater weight because they represent the character's ability to actually perform the task.

Attributes remain extremely important because they establish the foundation upon which skills operate.

---

# 4. Primary and Secondary Attributes

Many skills should depend upon more than one Attribute.

Instead of attaching every skill permanently to exactly one Attribute, an action can identify:

- one **Primary Attribute**
- optionally one **Secondary Attribute**

Within the Attribute portion of the formula:

> **75% Primary Attribute + 25% Secondary Attribute**

So the complete basic structure becomes approximately:

**Effective Capability**

= **60% Relevant Skill**

+ **30% Primary Attribute**

+ **10% Secondary Attribute**

This is clean enough for the simulation while still allowing multidimensional characters.

### Example

Sneaking through a guarded building:

- Stealth: 60%
- Agility: 30%
- Perception: 10%

Breaking through a reinforced door:

- Strength: primary
- Endurance: secondary
- Force Application skill or relevant physical skill

Analyzing an opponent's fighting style:

- Combat Analysis skill
- Intelligence: primary
- Perception: secondary

Resisting torture:

- Mental Resilience skill
- Willpower: primary
- Endurance: secondary

The **same skill may therefore resolve differently depending upon what the character is actually doing.**

I think that's preferable to rigid RPG pairings like "Stealth is always Dexterity."

---

# 5. Some Actions Can Use Only One Attribute

We shouldn't force secondary attributes into every action.

If no meaningful secondary Attribute exists:

> **40% Primary Attribute + 60% Skill**

Likewise, extremely fundamental actions may occasionally be primarily Attribute-based.

For example:

> Hold a collapsing beam above your head.

That may be mostly:

**Strength + Endurance**

with little or no specialized skill involved.

The engine should use the smallest set of stats that genuinely explains the action.

---

# 6. Skill Is Normally the Strongest Component

This preserves an important progression principle.

Imagine:

### Character A
Agility 80  
Stealth 25

### Character B
Agility 55  
Stealth 70

Character A is physically extraordinary but poorly trained at concealment.

Character B is less agile but highly experienced at stealth.

For an actual stealth task, Character B should generally perform better.

Using our provisional weighting:

**A**

`25(.60) + 80(.30) + secondary(.10)`

versus

**B**

`70(.60) + 55(.30) + secondary(.10)`

Skill matters.

But Character A's extraordinary agility still provides an advantage compared with another untrained person.

That's exactly what we want from our **Attributes → Skills** hierarchy.

---

# 7. Individual Mastery Should Modify Application, Not Replace Skill

Individual Mastery from Ruleset 1 should represent experience with a **specific technique, maneuver, tool, or application**.

Examples:

- Fireball Jutsu mastery
- Shadow Clone mastery
- a particular kenjutsu form
- a specific medical procedure
- a particular sealing formula
- familiarity with a weapon

I don't think Mastery should become another full 0–100 stat added into the formula.

Otherwise we start double-counting training.

Instead:

> **Skill determines broad competence. Mastery modifies performance within a specific application.**

Mastery can later provide a bounded **Mastery Modifier**.

For example, two shinobi could both have:

**Fire Release: 65**

but one has practiced Great Fireball hundreds of times while the other recently learned it.

Their general Fire Release competence is equal.

Their Great Fireball performance should not be.

We will establish the precise Mastery Modifier when we connect this back to Ruleset 1, but I would cap its effect so mastery can meaningfully distinguish specialists without overpowering Attributes and Skills.

Something around an equivalent **±5–15 capability points at the extremes** seems like the appropriate eventual range.

Not locking that number yet.

---

# 8. Techniques Can Change Which Stats Matter

Techniques should not simply provide "+20."

Instead, techniques may modify the resolution profile itself.

Consider Body Flicker.

Normal pursuit might use:

**Agility + Movement Skill**

Using Body Flicker might instead use:

**Agility + Chakra + Body Flicker Mastery**

That is much more interesting than:

> Body Flicker: +25 Movement.

The technique is allowing the character to solve the problem differently.

This also makes jutsu design much easier later.

---

# 9. Situational Factors Should Be Applied After Base Capability

We can therefore distinguish:

### Base Capability

What the character could normally accomplish.

from

### Effective Capability

What they can accomplish **under the current circumstances**.

Conceptually:

**Base Capability**

= Attributes + Skill

then:

**Effective Capability**

= Base Capability  
+ Mastery  
+ beneficial conditions  
− harmful conditions

But not every condition should literally be arithmetic.

As established in 2.1, some circumstances change the structure of the action instead.

---

# 10. Difficulty Uses the Same Scale as Capability

This is important.

If character capability ultimately resolves onto something approximately equivalent to a **0–100 scale**, Difficulty should use that same conceptual scale.

That means:

> Capability 50 against Difficulty 50

represents a genuinely even challenge.

Not necessarily exactly 50% yet—we'll formalize that in Ruleset 2.4—but conceptually they are evenly matched.

And:

**Capability 70 vs Difficulty 40**

should be very favorable.

**Capability 30 vs Difficulty 70**

should normally be extremely unfavorable or impossible.

This makes balancing much easier because everything operates in a shared language.

---

# 11. Opponents Can Generate Difficulty

For static tasks:

**Difficulty = Task Difficulty**

For active opposition:

**Difficulty ≈ Opponent Effective Capability**

So if you attempt to sneak past someone:

**Your Stealth Capability**

is compared against:

**Their Detection Capability**

Rather than inventing a separate arbitrary "Jonin Guard DC 70."

The opponent's actual:

- Perception,
- sensory skills,
- alertness,
- fatigue,
- techniques,
- circumstances

generate the opposition.

This ensures NPC statistics genuinely matter.

---

# 12. Environmental Difficulty and Opposition Can Coexist

Some situations involve both.

Imagine sneaking through a dark forest while being actively hunted.

There may be:

### Environmental factors
Wet leaves  
Moonlight  
Dense foliage

and:

### Active opposition
Enemy tracker  
Sensory technique  
Search pattern

We should not simply add all of these values together.

Instead, environmental conditions modify the relevant capabilities or establish constraints, while the actual contest remains:

> **Stealth Capability vs Detection Capability**

For example, heavy rain might:

- improve concealment,
- reduce hearing,
- make movement more difficult,
- impair scent tracking.

Different participants may therefore be affected differently.

That is much more simulation-friendly than:

> Rain = +7 Stealth.

---

# 13. The Resolution Margin

After everything relevant is calculated:

> **Resolution Margin = Effective Capability − Effective Difficulty**

This becomes one of the most important numbers in the entire game.

For example:

| Capability | Difficulty | Margin |
|---:|---:|---:|
| 50 | 50 | 0 |
| 55 | 50 | +5 |
| 65 | 50 | +15 |
| 80 | 50 | +30 |
| 45 | 50 | −5 |
| 30 | 50 | −20 |

The greater the positive margin, the more favorable the task.

The greater the negative margin, the less plausible success becomes.

But critically:

### Margin is not the final outcome.

It establishes the expected outcome distribution.

Randomness then determines exactly where within that distribution the attempt lands.

---

# 14. Randomness Should Resolve Probability, Not Add Huge Performance Values

I strongly recommend **against**:

`Capability + d20`

or

`Capability + d100`

Those systems allow luck to distort capability too much.

Instead:

### Step 1
Calculate the Capability/Difficulty margin.

### Step 2
Convert that margin into an internal probability distribution.

### Step 3
Generate a random result against that probability.

So randomness answers:

> Given everything we know about this situation, which plausible result actually occurred?

It does not answer:

> How competent is this person today?

That distinction is fundamental.

---

# 15. There Should Be No Universal Minimum or Maximum Chance

Many games use something like:

> Minimum chance: 5%  
> Maximum chance: 95%

I don't think we should.

That would mean an elite shinobi has a 5% chance of failing even incredibly routine actions.

Worse, it means absurd actions always have some chance of succeeding.

Instead, probability should be allowed to reach:

**100%**

when failure is no longer meaningfully plausible.

And:

**0%**

when success lies outside the plausible outcome space.

Between those points, the probability model handles uncertainty.

---

# 16. Capability Gaps Should Eventually Create Resolution Zones

I think this will become one of our most useful mechanics.

Rather than treating every possible margin identically, margins can create broad internal zones.

Something conceptually like:

### Automatic Success Zone
Capability massively exceeds Difficulty.

### Strong Advantage Zone
Failure possible but unusual.

### Advantage Zone
Success expected.

### Contested Zone
Both outcomes realistic.

### Disadvantage Zone
Failure expected.

### Severe Disadvantage Zone
Success unusual.

### Impossible Zone
Success is not currently plausible.

The exact boundaries should come from the Probability section rather than being invented now.

But this lets us fulfill our earlier principle:

> **Large capability gaps suppress randomness.**

---

# 17. Difficulty Can Also Have Requirements

Some tasks should not merely be "very difficult."

They should require something specific.

For example:

An advanced medical technique might require:

**Advanced Chakra Control Tier 2**

A sealing technique may require:

**Fuinjutsu Knowledge Tier 3**

A Mangekyo ability may require:

**Mangekyo Sharingan**

Without the prerequisite, the character doesn't simply suffer a giant penalty.

The action may be unavailable.

This is important because:

> **Difficulty represents how hard something is when you are capable of attempting it.**

It should not replace prerequisites.

This interfaces directly with the skill-tier gates we established in Ruleset 1.

---

# 18. Effective Capability Can Exceed the Normal Character Scale Temporarily

We should probably permit Effective Capability to temporarily go beyond ordinary base-stat limits.

Imagine someone has:

**Effective baseline: 94**

Then receives:

- ideal preparation,
- specialized equipment,
- assistance,
- advantageous terrain.

Their situational capability might effectively behave like:

**102**

or **108**.

That doesn't mean their Attribute became 108.

It means:

> Under these exact circumstances, their ability to accomplish this objective exceeds what their ordinary statistics alone would suggest.

Likewise, severe injury could pull a normally elite character dramatically below their normal performance.

This gives situational mechanics room to breathe without modifying permanent stats.

---

# 19. Capability Should Be Calculated Per Objective, Not Per Scene

Suppose a character is infiltrating a compound.

They don't have one universal "Infiltration Score."

Different objectives might resolve differently:

**Scale the outer wall**
Agility + Climbing

**Avoid patrols**
Agility/Perception + Stealth

**Identify security patterns**
Intelligence/Perception + Investigation

**Bypass a seal**
Intelligence/Chakra + Fuinjutsu

This keeps Attributes and Skills meaningful and prevents one high stat from solving entire gameplay categories.

---

# 20. Proposed Core Formula

So our provisional universal formula becomes:

### Standard Skilled Action

**Base Capability =**

`(Relevant Skill × 0.60)`  
`+ (Primary Attribute × 0.30)`  
`+ (Secondary Attribute × 0.10)`

If there is no legitimate Secondary Attribute:

`Skill × 0.60 + Primary Attribute × 0.40`

Then:

### Effective Capability

**Base Capability**  
± Mastery Effect  
± relevant numerical circumstances

with structural circumstances handled separately.

Then:

### Resolution Margin

**Effective Capability − Effective Difficulty**

Then:

### Probability Model

`Resolution Margin → Success Probability + Outcome Distribution`

Then:

### Random Resolution

chooses the actual result from that plausible distribution.

---

## Example

Let's use a simple hypothetical.

A genin attempts to sneak past a sentry.

### Genin

Agility: **52**  
Perception: **45**  
Stealth: **58**

Their basic stealth capability:

`58 × .60 = 34.8`

`52 × .30 = 15.6`

`45 × .10 = 4.5`

**Base Capability = 54.9**

Call it approximately **55** internally.

Now suppose the sentry's effective Detection Capability is:

**51**

The margin is:

> **+4**

This should be a genuinely uncertain contest slightly favoring the infiltrator.

Now imagine exactly the same genin attempts to sneak past an elite sensory jonin whose Detection Capability is:

**82**

Margin:

> **−27**

That should no longer resemble a normal coin-flip contest.

Success would require extraordinary circumstances that materially change the situation.

Perhaps:

- sensory interference,
- a decoy,
- suppressed chakra,
- the jonin being asleep,
- specialized concealment,
- another shinobi distracting them.

In other words:

**The player should solve the capability gap through gameplay instead of hoping for RNG.**

That is exactly the behavior I want this system to encourage.

---

# What I Think We Should Lock In

I think the architecture itself is strong enough to adopt:

> **Attributes establish potential.**

> **Skills represent applied competence and normally carry the largest weight.**

> **Individual Mastery improves specific applications without replacing broad skill.**

> **Only genuinely relevant Attributes contribute to an action.**

> **Most skilled actions use roughly 60% Skill / 40% Attributes.**

> **Effective Capability and Difficulty operate on the same conceptual scale.**

> **Opponents generate difficulty through their own actual capabilities.**

> **Capability minus Difficulty produces Resolution Margin.**

> **Resolution Margin determines probability rather than receiving a giant random die modifier.**

> **Randomness selects among plausible outcomes instead of redefining character capability.**

> **Prerequisites and impossibility are handled before probability.**

The **60/30/10 weighting is the one part I'd call provisional rather than permanently locked**. We should test it against several character archetypes once the rest of the probability system exists. We may find that 55/35/10 or 65/25/10 produces better differentiation.

Next should be **Ruleset 2.3 — Difficulty**, because we need to define exactly what a Difficulty 20, 40, 60, 80, etc. actually means before we can build the probability curve.

---

## Turn d1beeec6-a93f-46ca-9d7a-b714e3d8fb9b

### User

Okay

### Assistant — c91e8ba6-b4e4-46ea-b343-d8ead91d8a21

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.3 — Difficulty

Difficulty should answer one question:

> **How demanding is this task under its current objective conditions?**

It should not answer:

> How hard is this for this particular character?

That distinction is the foundation of the entire difficulty system.

A Difficulty 60 task is still Difficulty 60 whether attempted by an academy student, a jonin, or a legendary shinobi. Their **relationship to that difficulty** changes, not the task itself.

---

# 1. Difficulty Uses the Same General Scale as Capability

Since Effective Capability is being expressed on roughly a 0–100 scale, Difficulty should use the same scale.

That gives the engine an intuitive comparison:

**Capability 50 vs Difficulty 50**  
= roughly matched challenge.

**Capability 70 vs Difficulty 50**  
= character significantly exceeds what the task demands.

**Capability 35 vs Difficulty 70**  
= character is badly outmatched by the task.

This does not mean 100 is the absolute limit of everything possible in the Naruto universe.

It is primarily the normal operating scale for human and shinobi performance. Extraordinary phenomena can exceed it when necessary.

---

# 2. Difficulty Represents Required Performance

The cleanest interpretation is:

> **Difficulty is the level of effective performance normally required to accomplish the intended objective.**

This matters because the same physical situation can contain multiple possible objectives.

For example:

### Crossing a river

**Swim across slowly:** Difficulty 25

**Swim across while carrying another person:** Difficulty 40

**Cross without getting equipment wet:** Difficulty 50

**Cross silently while avoiding enemy observation:** possibly a different skill contest entirely.

Difficulty therefore belongs to the **objective**, not merely the object or environment.

---

# 3. Difficulty Should Be Anchored to Concrete Benchmarks

We should avoid letting the engine invent arbitrary numbers every time.

I recommend defining benchmark bands.

These are provisional numeric ranges, but the conceptual bands are more important than the exact cutoffs.

| Difficulty | General Meaning |
|---:|---|
| 0–9 | Negligible |
| 10–19 | Simple |
| 20–29 | Routine |
| 30–39 | Basic Challenge |
| 40–49 | Moderate |
| 50–59 | Demanding |
| 60–69 | Difficult |
| 70–79 | Expert |
| 80–89 | Exceptional |
| 90–99 | Extraordinary |
| 100+ | Superhuman / Extreme |

These are **task-performance categories**, not character ranks.

A genin can encounter an Expert-level task.

A jonin can perform a Routine task.

---

# 4. Negligible Difficulty — 0–9

These are actions requiring almost no meaningful competence.

Examples:

- opening an ordinary unlocked door,
- walking across flat ground,
- remembering your own name,
- lifting a very light object.

Normally these should never generate a check.

The band still exists because unusual circumstances can make normally trivial actions uncertain.

For example:

Walking might matter if the character is:

- severely injured,
- heavily intoxicated,
- standing on unstable ice.

The underlying task remains easy; the character's condition changes their Effective Capability or creates modifiers.

---

# 5. Simple Difficulty — 10–19

These tasks require minimal competence but little specialized training.

Examples:

- climbing over a low fence,
- following obvious footprints,
- preparing a very simple meal,
- tying a basic knot,
- noticing something clearly out of place.

Most healthy adults should perform these reliably under normal conditions.

Checks would primarily occur when:

- rushed,
- injured,
- distracted,
- inexperienced,
- or facing meaningful consequences.

---

# 6. Routine Difficulty — 20–29

These are tasks ordinary people can learn and perform consistently.

Examples:

- climbing an ordinary ladder quickly,
- maintaining a jogging pace,
- performing basic clerical work,
- cooking a familiar meal,
- navigating a familiar neighborhood,
- basic weapon maintenance.

Someone trained in the relevant skill should normally have little trouble.

This range will make up many everyday life-simulation activities.

---

# 7. Basic Challenge — 30–39

These tasks require noticeable competence or concentration.

Examples:

- climbing a rough wall,
- following a moderately obscured trail,
- repairing a simple mechanical problem,
- performing basic first aid under pressure,
- sneaking past someone who is not actively searching.

For civilians, this may represent meaningful challenge.

For trained shinobi, many tasks in this range should become automatic.

---

# 8. Moderate Difficulty — 40–49

These tasks require solid training or favorable natural aptitude.

Examples:

- tracking someone through mixed terrain,
- performing a technical medical procedure,
- moving quietly through a guarded area,
- making a difficult athletic maneuver,
- deciphering moderately complex coded information.

A competent professional should have a meaningful chance of success.

An untrained person may struggle.

This is probably where a large amount of normal genin-level uncertainty will occur.

---

# 9. Demanding Difficulty — 50–59

These tasks require substantial competence.

Examples:

- treating a serious wound,
- maintaining stealth through active patrols,
- performing advanced acrobatics under pressure,
- tracking a skilled opponent,
- executing sophisticated chakra manipulation.

Characters without meaningful training should rarely succeed.

Characters with developed skill can attempt these reliably, but mistakes remain plausible.

---

# 10. Difficult — 60–69

These tasks usually require advanced training.

Examples:

- advanced medical procedures,
- infiltrating a highly secured facility,
- decoding a sophisticated cipher,
- maintaining chakra control under severe interference,
- navigating extremely dangerous terrain quickly.

This is where high-performing chunin and specialized shinobi may regularly operate.

A generalist may still attempt them, but specialization becomes increasingly important.

---

# 11. Expert Difficulty — 70–79

These tasks demand highly developed skill.

Examples:

- complex surgery,
- bypassing advanced security seals,
- concealing oneself from trained trackers,
- executing extremely precise chakra manipulation,
- performing complex combat maneuvers under severe pressure.

Routine competence is insufficient.

Characters need serious specialization, exceptional Attributes, excellent circumstances, or some combination.

This is where individual mastery should start becoming particularly valuable.

---

# 12. Exceptional Difficulty — 80–89

These tasks are beyond what even most experienced professionals can perform consistently.

Examples:

- operating successfully under extraordinarily hostile conditions,
- deciphering extremely advanced fuinjutsu,
- performing delicate medical procedures during active combat,
- hiding from elite sensory specialists without specialized countermeasures,
- executing extremely precise high-level chakra techniques.

Characters capable of regularly operating here should be rare.

This is not synonymous with "jonin difficulty."

A jonin may have several capabilities near this level and many nowhere close to it.

---

# 13. Extraordinary Difficulty — 90–99

These represent feats near the upper edge of ordinary elite shinobi capability.

Examples might include:

- unprecedented technical precision,
- extraordinary chakra-control feats,
- bypassing elite-level defenses,
- highly advanced experimental medical procedures,
- operating successfully despite extreme environmental and tactical constraints.

Success should generally require:

- exceptional Attributes,
- advanced Skills,
- substantial Mastery,
- excellent circumstances,
- or unique advantages.

Even elite characters should not casually perform tasks in this range unless specifically specialized.

---

# 14. Difficulty 100+

This range should be used sparingly.

It represents tasks whose required performance exceeds ordinary human or shinobi capability.

Examples could include:

- physically impossible feats enabled by supernatural abilities,
- extraordinary sensory contests,
- extreme chakra manipulation,
- actions involving legendary techniques.

A task having Difficulty 110 does **not** mean everyone has a tiny chance of succeeding.

If someone's plausible capability cannot reach the necessary range, the task may simply be impossible for them.

Difficulty and possibility remain separate concepts.

---

# 15. Difficulty Should Not Equal Shinobi Rank

We should explicitly reject mappings like:

- D-rank task = Difficulty 20
- C-rank = 40
- B-rank = 60
- A-rank = 80
- S-rank = 100

Mission rank describes broader mission danger and complexity.

A B-rank mission might contain:

- Routine travel,
- Moderate tracking,
- Difficult combat,
- Simple negotiation.

Likewise, an S-rank mission may contain plenty of trivial actions alongside a few extraordinary ones.

Mission rank should therefore never automatically determine check difficulty.

---

# 16. Difficulty Is Objective, but Context Can Modify It

We need an important distinction between **task conditions** and **character conditions**.

Suppose someone is climbing a cliff.

The cliff's difficulty might depend on:

- slope,
- handholds,
- surface condition,
- weather,
- height,
- route complexity.

Those are features of the task and may modify Difficulty.

Meanwhile:

- exhaustion,
- an injured arm,
- fear,
- carrying heavy equipment

are characteristics of the character's current performance and modify Effective Capability.

This separation helps us avoid double-counting.

A useful rule:

> **If the factor changes the task for everyone, modify Difficulty.**

> **If the factor changes one participant's ability to perform it, modify Capability.**

---

# 17. Some Environmental Conditions Affect Different Characters Differently

The previous rule needs one nuance.

Heavy rain may objectively make a cliff more slippery.

That could increase Difficulty.

But a character with:

- specialized climbing equipment,
- chakra adhesion,
- Water Release adaptation,

may negate some or all of that environmental effect.

So we can conceptualize Difficulty in layers:

### Base Difficulty
The task under standard conditions.

### Environmental Difficulty
Changes caused by the world.

### Mitigation
Capabilities or equipment that neutralize those changes.

This makes specialized tools and techniques meaningful without rewriting the whole task.

---

# 18. Difficulty Should Be Generated From Components for Complex Tasks

For simple tasks, the engine can use benchmark judgment.

For complicated tasks, Difficulty should be derived from a few dimensions rather than guessed.

A useful framework would be:

### Complexity
How technically sophisticated is the task?

### Precision
How exact must execution be?

### Resistance
How much does the environment resist success?

### Time Pressure
How quickly must it be done?

### Information Requirement
How much correct knowledge is necessary?

Not every task uses every dimension.

For example, surgery may heavily involve:

- Complexity
- Precision
- Information

while climbing a mountain involves more:

- Resistance
- Endurance
- Environmental hazard

We should not literally add five separate scores for every action. They are primarily **difficulty-generation guidance** for the engine.

---

# 19. Difficulty and Stakes Must Remain Separate

This distinction is crucial.

A task can be:

**Easy but dangerous**

or

**Extremely difficult but low-risk.**

Example:

Walking across a narrow beam one meter above the ground and walking across the exact same beam 500 meters above the ground involve nearly identical physical difficulty.

The consequences of failure are radically different.

Likewise:

Solving a difficult puzzle may be Difficulty 75 but have almost no negative consequence for failing.

So:

> **Difficulty determines probability. Stakes determine consequences.**

Fear or pressure caused by stakes may subsequently affect performance, but the beam itself doesn't become mechanically narrower because it is higher in the air.

---

# 20. Difficulty Should Not Increase Because Failure Would Be Dramatic

This is another safeguard.

Suppose an assassin throws a knife at an important NPC.

The attack does not become harder simply because that NPC's death would dramatically affect the story.

Likewise, a medical check to save an important character does not secretly become easier because the story needs them alive.

Difficulty derives exclusively from the simulated situation.

---

# 21. Different Objectives Can Use Different Difficulties in the Same Action

A player should be able to choose ambition.

Suppose they want to break into an office.

Potential objectives:

**Open the window without caring about damage:** Difficulty 30

**Open it without leaving obvious evidence:** Difficulty 50

**Open it silently and leave no evidence:** Difficulty 65

**Open it silently, leave no evidence, and relock it afterward:** Difficulty 75

The player is effectively choosing how demanding an outcome they are attempting.

This creates meaningful risk/reward without artificial game mechanics.

---

# 22. Characters Can Sometimes Choose Lower Difficulty by Accepting Tradeoffs

This is a powerful concept.

Suppose someone needs to cross dangerous terrain.

They could:

**Rush**
- Higher Difficulty
- Less time

**Proceed normally**
- Standard Difficulty
- Standard time

**Move cautiously**
- Lower Difficulty
- More time

Likewise, a medic could:

**Perform emergency treatment**
- faster,
- harder,
- less complete.

or:

**Take time for careful treatment**
- slower,
- easier,
- potentially better outcome.

Difficulty can therefore be influenced by player strategy.

---

# 23. Difficulty Can Change Mid-Task

For extended actions, the environment can evolve.

Example:

A character is scaling a mountain.

Early terrain:
**Difficulty 40**

Storm begins:
**Difficulty 55**

Night falls:
**Difficulty 65**

Character reaches a sheltered route:
**Difficulty 45**

This is not dynamic scaling.

The world has genuinely changed.

---

# 24. Difficulty Should Usually Be Hidden Behind Qualitative Language

The engine can track exact numbers internally.

The player generally should not see:

> Difficulty 67.

Instead:

> The route looks extremely demanding and offers very few reliable footholds.

Character experience may improve the quality of this assessment.

A skilled climber might recognize:

> The lower section is manageable, but the final ascent looks dangerous enough that a mistake could be difficult to recover from.

This preserves immersion and prevents the game from becoming spreadsheet optimization.

Exact numbers could still be available in debug or testing modes.

---

# 25. Difficulty Estimation Can Be Wrong

Character perception matters.

An inexperienced person may underestimate a task.

A specialist may recognize hidden complexity.

Example:

An academy student looks at a seal:

> It looks complicated.

An experienced fuinjutsu specialist:

> The outer pattern is intentionally simple. The difficult part is the nested trigger structure underneath it.

The objective Difficulty has not changed.

The characters' understanding of it has.

This will later connect to information resolution.

---

# 26. Opposed Checks Are Different From Static Difficulty

When another character actively resists you, we generally should not assign a fixed Difficulty band.

Instead:

> **Opponent capability becomes the primary difficulty.**

Examples:

- Stealth vs Detection
- Deception vs Insight
- Genjutsu vs Resistance
- Pursuit vs Evasion

Static difficulty may still contribute environmental effects, but the opposition remains character-driven.

We will formalize that in the Opposed Resolution section.

---

# 27. Difficulty Should Support Automatic Outcomes

Once Difficulty exists on the same scale as Capability, we can eventually define automatic-result thresholds.

For example, if someone's Effective Capability exceeds task Difficulty by a very large margin, the action may not require random resolution.

Likewise, a sufficiently severe negative margin may make success implausible or impossible.

We should wait until the Probability section to establish exact thresholds.

But Difficulty must support this behavior.

---

# 28. Avoid False Precision

Even though the engine may use numbers like:

**Difficulty 57**

we should remember those numbers are simulation abstractions.

There is probably no meaningful distinction between Difficulty 57 and 58 in most narrative contexts.

So the engine should generally establish:

1. the correct difficulty band,
2. then refine within that band only when necessary.

This prevents arbitrary pseudo-scientific precision.

---

# Proposed Difficulty Generation Process

When the engine encounters a static uncertain task, it should internally ask:

**1. What exactly is the intended objective?**

↓

**2. What relevant skill domain does this belong to?**

↓

**3. What baseline level of performance does the objective require?**

↓

**4. What objective environmental conditions alter that requirement?**

↓

**5. Are there prerequisites that determine whether the action is possible at all?**

↓

**6. Does equipment or a technique mitigate part of the environmental difficulty?**

↓

**7. Assign final Effective Difficulty.**

Then compare that against Effective Capability.

---

# Example: Chakra Tree Walking

Let's use a Naruto-specific example.

### Normal tree walking

For someone who knows the technique:

**Base Difficulty: perhaps 25–30**

A trained shinobi with solid Basic Chakra Control should eventually perform it automatically.

Now alter conditions.

### Sprinting vertically while fighting

The character now needs:

- greater precision,
- greater movement coordination,
- divided attention.

Perhaps the objective rises into the **50–60 range**.

### Doing the same while heavily injured and under attack

The environmental objective may still be 55.

Their injury and fatigue primarily reduce **Effective Capability**.

The attacker may introduce an **opposed disruption check**.

We do not simply keep inflating the static Difficulty until it represents everything happening in the scene.

That separation will keep the system understandable.

---

# Example: Tracking

Find obvious footprints through mud:

**Difficulty ~20**

Track someone across normal woodland:

**~40**

Track a person intentionally hiding their trail:

Now it probably becomes **opposed resolution**.

If the target is not actively making checks but used a previously established concealment technique, their concealment result may establish the tracking Difficulty.

Again, the type of resolution changes based on the actual situation.

---

# What I Would Lock In

I think we can safely establish these rules:

> **Difficulty measures required performance, not character struggle.**

> **Difficulty and Effective Capability use the same general scale.**

> **Difficulty normally ranges from negligible through extraordinary, with 100+ reserved for truly exceptional requirements.**

> **Rank does not directly determine Difficulty.**

> **Objective environmental factors modify Difficulty; personal impairments generally modify Capability.**

> **Difficulty and consequences are separate.**

> **Different ambitions can create different difficulties in the same situation.**

> **Characters may trade time, resources, or outcome quality to alter Difficulty.**

> **Opposed actions primarily use opponent capability rather than arbitrary static DCs.**

> **Prerequisites determine whether some tasks can be meaningfully attempted at all.**

> **Difficulty does not scale with the player or narrative importance.**

> **Exact difficulty values are primarily internal; characters perceive qualitative estimates based on their knowledge.**

I would keep the exact numeric band boundaries **p

---

## Turn 60bcd34d-3837-4ed4-a5ec-37c783e4c2aa

### User

Okay

### Assistant — 7e940ac0-983e-4c62-8950-001a8594c6ed

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.4 — Probability Model

Now we can define what the **Resolution Margin** actually means.

The central principle should remain:

> **Randomness resolves uncertainty. It does not create capability.**

So we should not roll a die and add it to a character's score. Instead, the engine calculates the situation first and uses randomness only after it knows how favorable or unfavorable the situation already is.

---

## 1. Probability Comes Last

Before calculating any probability, the engine should already know:

**Effective Capability**

versus

**Effective Difficulty**

and therefore:

> **Resolution Margin = Effective Capability − Effective Difficulty**

But even before that, the engine must answer:

1. Is the intended outcome logically possible?
2. Does the character meet necessary prerequisites?
3. Is the outcome within their plausible performance range?
4. Is there actually meaningful uncertainty?

Only then should probability be generated.

This is important because the probability formula itself should **never be used to make impossible actions possible**.

An academy student punching Madara should not receive a 0.7% chance to knock him unconscious simply because a mathematical curve technically produces a number.

That outcome would fail the plausibility gate before probability is ever calculated.

---

# 2. Use a Curved Probability Model

A linear model would cause major problems.

For example:

`50% + 2% per Margin point`

would produce:

- Margin 0 → 50%
- +10 → 70%
- +20 → 90%
- +25 → 100%

That creates artificial cutoffs and treats every point identically.

Instead, I recommend a **sigmoid probability curve**.

The internal formula can be:

\[
P(\text{Success}) =
\frac{1}
{1 + 10^{-M/20}}
\]

where:

**M = Resolution Margin**

The player would never need to see this formula.

Its purpose is simply to give the simulation a consistent probability curve.

---

# 3. What the Curve Produces

Using this model:

| Resolution Margin | Approx. Success Chance |
|---:|---:|
| −40 | 1% |
| −35 | 2% |
| −30 | 3% |
| −25 | 5% |
| −20 | 9% |
| −15 | 15% |
| −10 | 24% |
| −5 | 36% |
| **0** | **50%** |
| +5 | 64% |
| +10 | 76% |
| +15 | 85% |
| +20 | 91% |
| +25 | 95% |
| +30 | 97% |
| +35 | 98% |
| +40 | 99% |

This produces a useful relationship.

A small capability advantage matters.

A moderate capability advantage matters substantially.

A large capability advantage rapidly suppresses randomness.

---

# 4. Why I Like This Curve

There's also a very elegant mathematical property:

> **Every 20-point advantage multiplies the odds of success by approximately ten.**

At Margin 0:

**1:1 odds**

At +20:

roughly **10:1**

At +40:

roughly **100:1**

At −20:

roughly **1:10**

At −40:

roughly **1:100**

That gives capability differences real weight without creating sudden arbitrary cliffs.

---

# 5. Small Differences Remain Competitive

Suppose two characters produce:

**Capability 55**  
vs  
**Difficulty 51**

Margin:

> **+4**

That gives approximately a **61% success probability**.

That's exactly the sort of contest where:

- timing,
- momentary decisions,
- luck,
- positioning

could reasonably determine the result.

The superior character has an advantage, but the other character remains fully competitive.

---

# 6. Moderate Differences Become Noticeable

Now compare:

**65 vs 50**

Margin:

> **+15**

Approximately:

> **85% success**

The stronger performer should win most attempts.

But 15 points isn't such an enormous gulf that reversal becomes absurd.

This is useful for characters of noticeably different competence.

---

# 7. Large Differences Strongly Suppress Upsets

Now:

**80 vs 50**

Margin:

> **+30**

Approximately:

> **97% success**

At this point, an upset becomes unusual.

That supports our earlier principle:

> **The larger the capability gap, the less influence normal randomness should have.**

But critically, we still have another safeguard above probability: **plausibility**.

The system is not saying every −30 Margin action automatically receives a 3% chance.

It's saying:

> If the engine has already determined that success remains genuinely possible, its baseline likelihood is around that range.

---

# 8. The Probability Curve Does Not Override the Plausibility Gate

This distinction needs to be explicit.

Suppose:

### Genin

Effective Taijutsu Capability: **38**

### Kage

Effective Taijutsu Defense: **90**

The mathematical margin would be:

> −52

We should **not** blindly calculate some tiny probability and roll.

The engine first considers the intended outcome.

If the genin is attempting:

> Defeat the Kage in straightforward hand-to-hand combat.

The plausible outcome space may exclude victory entirely.

Result:

> **0%**

No resolution roll is needed.

But perhaps the genin is trying:

> Touch the Kage's cloak before being knocked away.

That could be possible.

Now a probability calculation might actually be appropriate.

The objective matters.

---

# 9. Probability Applies to the Intended Objective

Success probability is always tied to **what the character is actually trying to accomplish**.

Consider throwing a kunai at a vastly superior opponent.

Possible objectives:

**Kill them outright**

Possibly 0%.

**Seriously wound them**

Extremely unlikely.

**Cause a minor wound**

Still difficult.

**Force them to dodge**

Potentially achievable.

**Distract them for one second**

Much more plausible.

This makes tactical choices important.

A weak character doesn't need to magically become powerful.

They can choose an objective that lies within their capabilities.

---

# 10. Automatic Outcomes Should Override Tiny Probabilities

We previously established automatic success and automatic failure.

Now we can better define them.

The engine should not resolve every:

- 98%,
- 99%,
- 1%,
- 2%

action merely because the mathematical curve technically permits uncertainty.

Instead, probability should help determine whether uncertainty remains meaningful.

A useful provisional framework is:

### 0%
Impossible under current circumstances.

### ~1–3%
Remote enough that the engine should usually ask whether success actually remains plausible.

### ~3–10%
Severe disadvantage, but potentially worth resolving if a concrete path to success exists.

### ~10–25%
Strong disadvantage.

### ~25–40%
Disadvantaged but competitive.

### ~40–60%
Highly contested.

### ~60–75%
Advantaged but competitive.

### ~75–90%
Strong advantage.

### ~90–97%
Very strong advantage.

### ~97–99%
Usually approaching automatic success.

### 100%
No meaningful possibility of failure.

These are interpretation ranges, not additional mechanics.

---

# 11. Automatic Success Should Depend on Context, Not Just Percentage

Suppose someone has a calculated 98% chance to accomplish something.

That does not always mean we should roll the 2%.

Consider:

### A jonin tying an ordinary knot

Maybe mathematically:

> 99%+

There is no meaningful reason to resolve it.

Automatic success.

But consider:

### A bomb technician cutting the correct wire with a 98% probability

If there is a concrete reason that a mistake could still occur and failure matters enormously, the remaining uncertainty may be worth resolving.

So:

> **High probability suppresses checks when failure is no longer meaningfully plausible in context.**

It should not create a universal "97% means automatic success" rule.

---

# 12. Stakes Do Not Change Probability

This also reinforces our earlier separation.

Suppose:

> Success probability = 72%.

If failure means:

**You lose five minutes**

the probability remains 72%.

If failure means:

**You fall to your death**

the probability remains 72%.

The consequence changes.

The odds do not.

However, fear caused by knowing that failure means death could affect Effective Capability if the character's psychology meaningfully impacts performance.

That would be a character-state effect, not a secret probability adjustment.

---

# 13. Probability Should Be Symmetrical

An important consistency rule:

If:

**A has +10 against B**

then A's baseline chance should be approximately:

> 76%

while B's corresponding chance is:

> 24%.

The engine should not independently invent:

> A has 76%, but B somehow also has 40%.

For genuinely opposed mutually exclusive outcomes, their probability distributions must agree.

This becomes especially important once NPCs are resolving things without the player present.

---

# 14. But Not Every Opposed Situation Is Binary

Suppose two shinobi are racing.

Possible outcomes may include:

- A decisively wins,
- A narrowly wins,
- near tie,
- B narrowly wins,
- B decisively wins.

The 76% may represent the overall probability that A achieves the primary objective.

The next ruleset section—**Degrees of Success and Failure**—will determine how strongly they succeed.

So:

> **Success probability answers whether the objective is achieved.**

> **Outcome margin answers how the objective is achieved.**

Those should remain related but distinct.

---

# 15. Randomness Should Be Generated After Probability

Internally, an uncertain resolution can be simple.

Suppose:

> Success probability = 64%.

Generate a hidden random value from 0–100.

If:

> Random result ≤ 64

the intended objective succeeds.

Otherwise it fails.

But the player normally doesn't see:

> Rolled 37 against 64%.

Instead they experience the result through narration.

The underlying random value can then help determine the **quality** of the outcome in the next section.

---

# 16. RNG Should Not Be Rerolled to Produce a Better Story

Once an outcome is properly generated, the engine should respect it.

It should not internally think:

> That failure isn't dramatic enough.

and reroll.

Likewise:

> The player has failed several times. I'll reroll until they succeed.

No.

Probability should be real.

Otherwise none of our statistics actually matter.

---

# 17. No Pity System in Core Resolution

Many games secretly increase success chance after repeated failure.

I don't think we should do that here.

If a character fails three times, their fourth attempt should only improve because something changed:

- they learned something,
- changed strategy,
- received assistance,
- improved their skill,
- took more time,
- changed equipment,
- discovered useful information.

Not because:

> The simulation feels bad for them.

Repeated-attempt mechanics can be developed separately.

---

# 18. Previous Success Does Not Create a Hidden Failure Penalty

Likewise, we should avoid gambler's-fallacy balancing.

If someone succeeds five times at a 70% action, their sixth attempt is still approximately 70% if nothing else changed.

The engine should never think:

> They've been lucky, so they're due for a failure.

Each action follows the current simulated conditions.

---

# 19. Pure Chance Events Need a Separate System

Not every uncertain event should use Effective Capability.

For example:

- whether a randomly selected baby is born male or female,
- whether a rare mutation occurs,
- whether a storm develops,
- whether a randomly selected customer enters a store,
- certain loot or encounter generation.

These are **world probability events**, not skill checks.

They should use an appropriate base probability.

Character statistics should only influence them when there is a causal reason.

For example:

> Rain occurring tomorrow

doesn't care about your Intelligence.

But:

> Correctly predicting tomorrow's rain

might use meteorological knowledge and Intelligence.

This prevents the resolution system from being forced onto things it isn't designed to represent.

---

# 20. Unknown Facts Are Not Automatically Random

There's another important distinction.

Suppose the player asks:

> Is there a guard behind the door?

If the simulation has already established that there is a guard there, that is simply a fact.

The engine should not roll again.

If the world state genuinely hasn't determined it yet, the simulation may generate the fact using appropriate world logic or probability.

Once generated:

> **The fact persists.**

Opening and closing the door cannot reroll whether the guard exists.

This is important for persistent simulation consistency.

---

# 21. Probability Should Usually Remain Hidden

I don't think normal gameplay should display:

> **61.3% Success Chance**

That would encourage excessive optimization and make the game feel mechanical.

Instead, the character receives a qualitative assessment.

For example:

**~50%**

> This could easily go either way.

**~65%**

> You think you have a modest advantage.

**~80%**

> You're confident you can pull this off, though failure is still possible.

**~95%**

> You would expect to succeed unless something goes unusually wrong.

**~10%**

> You don't like your chances.

**~2%**

> You can imagine a way this works, but it would require almost everything to go your way.

The accuracy of those assessments can later depend on character knowledge.

---

# 22. Characters Should Not Know the True Probability

This creates an important distinction:

### Objective Probability

Known by the engine.

### Perceived Probability

Estimated by the character.

An experienced medic may accurately judge the chances of a procedure.

An inexperienced genin may badly underestimate an enemy.

Someone might think:

> "I've got this."

while the engine knows they're facing a severe disadvantage.

But incorrect estimates need an actual reason:

- missing information,
- lack of experience,
- deception,
- overconfidence,
- unfamiliar technique.

The engine should not arbitrarily lie to the player.

---

# 23. Hidden Opposition Can Make the Apparent Odds Wrong

This is particularly useful for Naruto.

Suppose the player attempts to ambush someone.

From the player's known information:

> It looks favorable.

But unbeknownst to them, the target possesses exceptional sensory abilities.

The **true resolution** includes those abilities.

The player's estimate does not.

Therefore:

> "This looks like a good opportunity."

can coexist with:

> actual success probability is poor.

That is legitimate uncertainty because the character lacks information.

---

# 24. Luck Traits Should Modify Probability Carefully

If we eventually create traits related to luck, they should not simply provide enormous flat bonuses.

Something like:

> Lucky: +20% success

would be extremely powerful and distort the simulation.

Instead, luck could eventually affect:

- borderline outcomes,
- frequency of favorable incidental events,
- magnitude of random variation,
- certain world-event probabilities.

But it should never enable physically impossible achievements.

We can develop that later without changing the central probability curve.

---

# 25. Extreme Rolls Cannot Violate Outcome Space

Suppose someone has an 8% chance of successfully delaying an enemy.

They succeed.

That means:

> **They successfully delayed the enemy.**

It does not automatically mean:

> They completely defeated the enemy.

The roll only resolves the declared objective.

Likewise, an extraordinary random result on:

> Distract the Hokage.

does not become:

> You accidentally kill the Hokage.

This is another reason to establish the intended objective **before resolution**.

---

# 26. Preparation Alters Probability Through Capability and Difficulty

We don't need arbitrary preparation odds.

Suppose:

### Direct infiltration

Capability 55  
Difficulty 75

Margin:

> −20

About **9%**.

The player then:

- scouts patrol patterns,
- steals guard credentials,
- waits until shift change,
- disables an alarm.

Perhaps the new situation becomes:

Capability 65  
Difficulty 55

Margin:

> +10

About **76%**.

The player didn't receive a magical "+67% preparation bonus."

Their actions actually changed the simulated situation.

That is exactly how I want strategy to work.

---

# 27. This Makes Information Extremely Valuable

The same system naturally rewards intelligence gathering.

A player might discover:

> The enemy sensory specialist becomes significantly less effective underground.

Instead of fighting them under ordinary conditions:

**Capability 58 vs Detection 82**

they lure them into tunnels where the sensory technique becomes impaired.

Maybe:

**Capability 62 vs Effective Detection 60**

Suddenly the contest is genuinely competitive.

The player overcame a power difference through understanding the mechanics of the world.

That's extremely appropriate for Naruto.

---

# 28. Teamwork Can Change the Probability Without Breaking It

Later, teamwork mechanics can generate a combined Effective Capability.

They should not give every participant a separate independent chance to magically succeed.

Otherwise five mediocre characters can exploit probability through sheer reroll volume.

Instead:

> Teamwork changes the capability or structure of the attempt.

Then the resulting situation receives one coherent probability.

We'll define the details later.

---

# 29. Probability Should Be Calculated Fresh When Conditions Meaningfully Change

If nothing changes:

> same capability + same difficulty = same underlying probability.

If conditions change:

recalculate.

Examples:

- injury,
- fatigue,
- new information,
- terrain change,
- equipment loss,
- reinforcements,
- preparation,
- technique activation.

This prevents stale probability values from being reused after the situation evolves.

---

# 30. Recommended Internal Resolution Process

So the complete probability flow becomes:

### Step 1 — Define Objective
What exactly is the character trying to accomplish?

### Step 2 — Plausibility Gate
Is that outcome possible under current conditions?

If no:

> **0% — automatic failure**

### Step 3 — Check Necessity
Is meaningful failure actually plausible?

If no:

> **100% — automatic success**

### Step 4 — Calculate Effective Capability

Attributes  
+ Skill  
+ Mastery  
+ relevant circumstances

### Step 5 — Calculate Effective Difficulty

Task requirements or opposition.

### Step 6 — Calculate Resolution Margin

> **Capability − Difficulty**

### Step 7 — Convert Margin to Probability

Using the sigmoid curve.

### Step 8 — Suppress Meaningless Checks

If the probability is extreme and the alternative outcome no longer constitutes meaningful uncertainty, resolve automatically.

### Step 9 — Hidden Random Resolution

Generate the result.

### Step 10 — Determine Degree of Outcome

Handled by Ruleset 2.5.

---

# Testing Our Earlier Example

We previously had:

### Genin

Effective Stealth:

**55**

### Ordinary sentry

Effective Detection:

**51**

Margin:

> **+4**

Probability:

> about **61%**

That feels good.

The genin has an edge, but detection remains quite plausible.

Now:

### Elite sensory jonin

Detection:

**82**

Margin:

> **−27**

Raw curve:

> about **4%**

But the engine now asks:

> Does this genin actually possess a plausible way of bypassing this sensory capability?

If not:

**automatic failure** may be appropriate.

If yes—for example, their concealment method specifically counters the sensor—

the contest can remain resolvable.

This combination of **plausibility + probability** is much better than either system alone.

---

# What I Would Lock In

I think these principles are strong enough to establish:

> **Probability is calculated only after possibility, prerequisites, capability, difficulty, and circumstances are established.**

> **Resolution Margin determines probability through a nonlinear curve.**

> **Margin 0 represents an approximately even contest.**

> **Small capability differences create modest advantages.**

> **Large capability differences rapidly suppress randomness.**

> **The probability curve cannot make impossible outcomes possible.**

> **0% and 100% are legitimate outcomes.**

> **Automatic outcomes override unnecessary RNG.**

> **Stakes affect consequences, not the underlying chan

---

## Turn e5cd4843-a1a8-4861-ac1a-8011759adb3d

### User

Okay

### Assistant — 9c3445f8-3c1a-496a-b700-ebc900062a00

# Ruleset 2.5 — Degrees of Success & Failure

A resolution should answer two separate questions:

> **Did the character accomplish the intended objective?**

and

> **How well or badly did the attempt resolve?**

The first comes from success probability. The second should come from **how far the same random result landed from the success/failure threshold**.

That lets us avoid a second arbitrary "quality roll."

## 1. One Roll Determines Both Success and Quality

Suppose the previous system calculates:

**Success Probability: 64%**

The engine generates one hidden number from 0–100.

If the result is 64 or lower, the intended objective succeeds. If it is above 64, it fails.

Then we calculate:

> **Outcome Margin = Success Probability − Random Result**

A positive Outcome Margin indicates success. A negative Outcome Margin indicates failure.

So if the hidden result is **61**:

`64 − 61 = +3`

The character barely succeeds.

If the result is **20**:

`64 − 20 = +44`

The character performs exceptionally well.

If the result is **68**:

`64 − 68 = −4`

They narrowly fail.

If the result is **95**:

`64 − 95 = −31`

They fail badly.

This gives us a very useful property:

> **The same random result that determines success also determines degree.**

---

# 2. This Naturally Rewards Expertise

Consider a highly skilled character with:

**95% success probability**

If they fail, the roll must have been between 95 and 100.

That means their failure Outcome Margin can only be roughly:

**−1 to −5**

So when an expert unexpectedly fails something they are extremely good at, it will normally be a **narrow failure**, not an absurd catastrophe.

That is exactly what we want.

Meanwhile, successful results have enormous room for positive margins.

An expert can therefore perform something:

- successfully,
- strongly,
- exceptionally.

Their expertise isn't merely reducing failure. It also improves **quality**.

---

# 3. Low-Probability Successes Tend to Be Narrow

Now imagine someone has only:

**5% success probability**

They can still succeed if the outcome remains plausible.

But any successful roll must fall between 0 and 5.

Their maximum positive Outcome Margin is therefore only about +5.

So their success will generally be:

> **barely successful**

rather than:

> **miraculously perfect**

This is another major advantage of the system.

A weaker character pulling off a long-shot does not suddenly perform like a master.

They manage to make it work.

That respects the character's actual capability.

---

# 4. Provisional Outcome Bands

I recommend these internal bands:

| Outcome Margin | General Result |
|---:|---|
| +40 or greater | Exceptional Success |
| +20 to +39 | Strong Success |
| +6 to +19 | Standard Success |
| +0 to +5 | Narrow Success |
| −1 to −5 | Narrow Failure |
| −6 to −19 | Standard Failure |
| −20 to −39 | Severe Failure |
| −40 or lower | Catastrophic-range Failure |

These names are mostly **engine terminology**.

The player should usually experience the actual consequence rather than:

> **STRONG SUCCESS!**

The exact boundaries remain provisional until testing, but the architecture is very strong.

---

# 5. Exceptional Success Does Not Break Capability

This is crucial.

An Exceptional Success means:

> The character achieved one of the best plausible versions of their intended action.

It does **not** mean reality stops applying.

Suppose someone attempts:

> Throw a kunai to cut a rope.

An exceptional success might mean:

- the rope is severed cleanly,
- the kunai lands exactly where intended,
- the throw wastes almost no motion,
- perhaps the weapon remains recoverable.

It does not mean:

> The kunai continues through the rope and accidentally kills an S-rank ninja three buildings away.

Outcome degree still exists inside the **plausible outcome space established before resolution**.

---

# 6. Degrees Should Improve Relevant Dimensions

The meaning of a strong result depends on the action.

For a stealth action, better results could mean greater:

**Secrecy, speed, positioning, trace removal, information gained**

For medicine:

**Stability, precision, recovery quality, resource efficiency, speed**

For crafting:

**Quality, durability, precision, material efficiency**

For investigation:

**Accuracy, amount of information, speed, confidence**

For combat maneuvers:

**Positioning, execution quality, efficiency, tactical advantage**

The engine should therefore ask:

> **What dimensions of quality logically exist for this objective?**

Then use degree of success to determine them.

---

# 7. Not Every Success Should Produce Extra Rewards

We should avoid turning exceptional results into loot-box bonuses.

If someone succeeds exceptionally at opening a normal door, the engine does not need to invent a reward.

They simply open it effortlessly.

Outcome degree only matters when there is a meaningful difference between:

> doing something

and

> doing it particularly well.

This will prevent resolution spam.

---

# 8. Narrow Success

A Narrow Success means the intended objective **is achieved**, but barely.

Depending on the action, that might produce:

- reduced quality,
- additional time,
- increased resource consumption,
- poor positioning,
- a small complication,
- evidence left behind.

But those consequences must follow logically from the action.

Example:

> You get through the window without being spotted, but the frame gives a faint crack as you force yourself through.

The stealth objective succeeded.

But the result was not clean.

That crack could matter later.

---

# 9. Success With a Cost

This gives us an important result type that does not need its own mathematical category.

A **Narrow Success** can often become:

> **Success with cost**

For example, the character:

- completes the technique but spends extra chakra,
- crosses the gap but lands badly,
- picks the lock but damages their tool,
- convinces the guard but creates suspicion,
- stabilizes the patient but requires additional medicine.

The main objective still succeeded.

The Outcome Margin explains why the success was imperfect.

---

# 10. Partial Success Should Be Contextual

I don't think **Partial Success** should be a universal mathematical band.

Instead, it should be one possible interpretation of a result when the objective is divisible.

Suppose the objective is:

> Find out where the enemy team is going and why.

A marginal result might reveal:

> where they are going,

but not:

> why.

That is genuinely partial.

Likewise:

> Escape the guards and remain unidentified.

The character might escape but have their identity discovered.

One component succeeds. Another does not.

That is much more meaningful than defining some universal "+3 = partial success" rule.

So:

> **Partial success occurs when the attempted objective contains multiple meaningful components and only some are achieved.**

---

# 11. Narrow Failure

A Narrow Failure means the intended objective was **not fully achieved**, but the character came very close.

This is where many natural "failing forward" results should occur.

For example, attempting to jump to another roof:

> You fall just short, slam into the edge, and manage to grab the ledge.

The objective:

> land safely on the roof

failed.

But the result is radically different from:

> fall into the street.

Likewise, trying to persuade someone:

> They refuse your proposal, but you can tell they're considering part of what you said.

Failure remains real.

It simply reflects the closeness of the attempt.

---

# 12. Narrow Failure Does Not Always Mean Progress

We should not make "failing forward" mandatory.

Sometimes failure simply means failure.

Attempt:

> Guess the password.

Narrow failure:

> Wrong password.

There doesn't necessarily need to be a consolation prize.

The engine should only create partial progress where the underlying situation supports it.

---

# 13. Standard Failure

A Standard Failure means the character meaningfully failed the objective, but nothing extraordinary happened.

For example:

> You fail to pick the lock.

> The target notices you attempting to follow them and changes course.

> Your chakra slips and the technique disperses.

This should probably be the most common form of failure when characters attempt appropriately challenging tasks.

The system should not treat every failure as a disaster.

---

# 14. Severe Failure

A Severe Failure means the attempt went substantially worse than intended.

This may create meaningful consequences if the situation supports them.

For example:

A lockpick attempt might:

- damage the mechanism,
- break a tool,
- create noticeable noise.

A stealth attempt could:

- clearly reveal the character,
- expose their approximate position,
- alert additional enemies.

A medical attempt could worsen the injury **if the procedure genuinely carries that risk**.

Again, the consequence comes from the action.

---

# 15. Catastrophic-Range Failure Is Not Automatically Catastrophic

This needs to be a hard rule.

An Outcome Margin below −40 means:

> The character performed extremely poorly relative to what was required.

It does **not** automatically mean something catastrophic happens.

There must actually be a catastrophic consequence available in the situation.

For example:

Attempting a difficult crossword puzzle and failing terribly might mean:

> You make almost no meaningful progress.

That's it.

Attempting an unstable experimental sealing technique and failing terribly could potentially cause:

- seal collapse,
- chakra backlash,
- equipment destruction,
- injury.

So the final rule is:

> **Poor performance determines severity of failure. Stakes determine how dangerous that severity can become.**

---

# 16. Catastrophic Failure Requires Causal Pathways

Before applying a major catastrophe, the engine should be able to answer:

> **How did the attempted action cause this consequence?**

If it cannot answer that coherently, the consequence should not occur.

For example:

A terrible stealth attempt can reasonably:

> alert guards.

It cannot reasonably:

> cause an unrelated building to collapse.

A terrible cooking attempt can:

> ruin the meal or start a kitchen fire if open flames are involved.

It cannot:

> spontaneously poison everyone unless contamination or unsafe ingredients were actually plausible.

This should eliminate "critical fail comedy."

---

# 17. Failure Severity Is Limited by Exposure

The character must actually be exposed to a consequence for it to occur.

Suppose someone unsuccessfully attempts to identify a plant.

Severe failure might mean:

> They confidently misidentify it.

But if they merely examine the plant from a distance, they cannot suddenly become poisoned.

If they then eat it based on their incorrect identification, poisoning becomes possible.

This gives the simulation causal continuity.

---

# 18. Outcome Quality Should Sometimes Affect Future Difficulty

Degrees of outcome can modify persistent world state.

Imagine a stealth infiltration.

### Exceptional success
Nobody notices anything; perhaps patrol patterns are learned.

### Standard success
The character enters unnoticed.

### Narrow success
They enter, but something feels slightly wrong to a guard.

That could create:

**Suspicion +1**

which changes later circumstances.

Similarly, a severe failure could raise the area's alert state.

This makes degrees of success matter beyond flavor text.

---

# 19. Success Can Create Momentum

A particularly strong result may place the character in a better position for the next action.

For example:

A strong successful dodge may produce:

> favorable positioning.

A strong deception might mean:

> the target not only believes the lie but adjusts their behavior around it.

A strong tracking result might provide:

> clearer information about speed, direction, and group size.

But this should emerge from the quality of the action rather than becoming a universal "+5 next roll."

---

# 20. Failure Can Create Complications Instead of Dead Ends

Likewise, failures should often evolve the situation.

Suppose:

> You fail to infiltrate through the gate.

That may become:

> The guards become suspicious and begin questioning you.

Now there is a new social situation.

Or:

> You lose the target's trail.

But perhaps:

> You know the last confirmed direction they traveled.

The simulation continues.

Failure changes the state of the world rather than necessarily ending gameplay.

---

# 21. Repeated Rolls Should Not Be Used to Simulate Degree

We shouldn't do:

> Attack succeeds.

then:

> Roll damage quality.

then:

> Roll positioning.

then:

> Roll resource efficiency.

unless those genuinely represent separate uncertain actions.

One resolution should normally provide enough information to determine the quality of that particular action.

This will keep the system computationally manageable.

---

# 22. Extreme Success Should Be Easier for Masters

Our Outcome Margin model naturally creates this.

Suppose:

### Novice

Success probability: **55%**

Maximum positive Outcome Margin:

> +55

Exceptional performance is technically possible, but only from the extreme favorable tail.

Now:

### Expert

Success probability: **95%**

The expert has a much larger portion of the random distribution capable of producing large positive margins.

So mastery creates two benefits:

> **greater reliability**

and

> **greater quality**

That's exactly how expertise should behave.

---

# 23. Extreme Failure Should Be Easier for the Outmatched

Similarly:

### Expert with 95% chance

Maximum failed Outcome Margin:

roughly **−5**

If they fail, they almost certainly barely fail.

### Novice with 15% chance

Their failures can extend very deeply into negative margins.

That means attempting things far beyond your ability is not merely less likely to work.

It also tends to produce **worse failures**, provided the situation contains meaningful consequences.

This creates natural risk.

---

# 24. Long-Shot Attempts Become Strategically Interesting

Suppose a character has:

**8% chance**

of pulling something off.

The player now knows—qualitatively, not numerically—that even if it works, it will probably be a **marginal success**.

That means a desperate long-shot might achieve:

> exactly enough to survive

rather than:

> completely reverse the battle.

This is perfect for underdog situations.

---

# 25. The Engine Should Identify the Primary Objective Before Rolling

This is now even more important.

Suppose the player says:

> I throw a kunai at him.

That isn't necessarily enough.

The engine can infer the immediate intent from context:

- injure him,
- kill him,
- distract him,
- interrupt hand signs,
- force him to dodge.

Outcome degree must be evaluated against the actual objective.

Otherwise the engine cannot determine what "strong success" means.

When intent is obvious from context, it should simply infer it rather than interrupting play with constant questions.

---

# 26. Secondary Benefits Must Remain Plausible

An Exceptional Success may occasionally produce a related secondary advantage.

For example:

> You interrupt the enemy's hand signs so cleanly that they also lose their footing.

But the secondary effect should:

- logically follow from the action,
- remain within the character's capability,
- remain proportionate to the result.

Exceptional success is not permission for the engine to hand out unrelated bonuses.

---

# 27. Degrees Can Apply to Knowledge

This system is particularly useful for information checks.

Suppose someone examines an unfamiliar jutsu.

A narrow success might identify:

> its chakra nature.

A standard success:

> chakra nature and broad function.

A strong success:

> probable mechanics and vulnerabilities.

An exceptional success:

> subtle details that only a highly competent observer would recognize.

Failure can similarly range from:

> insufficient information

to:

> a plausible but incorrect interpretation.

We'll need special safeguards for misinformation when we develop hidden information resolution.

---

# 28. Degrees Can Apply to Social Actions Without Mind Control

Persuasion success should not mean:

> NPC does whatever the player wants.

Instead, degree determines how much movement occurs **within what that NPC could reasonably be persuaded to do**.

For example:

Exceptional persuasion does not make a loyal parent murder their child because the player gave a great speech.

It might:

- make them listen,
- reduce hostility,
- secure a concession,
- create doubt,
- improve trust.

Again:

> **Outcome space comes before degree.**

This will become extremely important in the Social Ruleset.

---

# 29. Degrees Should Be Stored When Consequences Persist

The engine doesn't necessarily need to remember:

> "Roll was 14."

But it may need to persist the consequence generated by that result.

For example:

**Guard suspicion:** 22 → 35  
**Chakra remaining:** −8  
**Door condition:** damaged  
**Wound:** stabilized poorly  
**NPC trust:** increased

The simulation stores meaningful changes rather than endless historical dice values.

---

# 30. Proposed Resolution Architecture So Far

We now have a coherent pipeline:

**Capability & Difficulty**

produce:

> **Resolution Margin**

which produces:

> **Success Probability**

which produces one hidden:

> **Random Resolution**

which produces:

> **Outcome Margin**

which determines:

> **Degree of Success or Failure**

which is constrained by:

> **Plausible Outcome Space + Stakes**

and finally creates:

> **Persistent Consequences**

This means the whole system is starting to fit together without needing separate ad hoc mechanics.

## What I Would Lock In

The core relationship is strong enough to establish:

> **One random resolution determines both success and degree; no second quality roll is normally necessary.**

> **Outcome Margin measures how far the random result falls above or below the success threshold.**

> **Highly probable actions naturally produce better successes and milder failures.**

> **Low-probability successes naturally tend to be narrow rather than miraculous.**

> **Exceptional success means the best plausible version of the intended action, not capability-breaking performance.**

> **Partial success is contextual, especially for multi-part objectives, rather than a mandatory universal band.**

> **Narrow success may carry logical costs or complications.**

> **Narrow failure may preserve progress when the physical or narrative situation supports it.**

> **Severe performance only creates severe consequences when the action exposes the character to those consequences.**

> **Catastrophic-range failure never creates unrelated disasters.**

> **Degrees of outcome should modify persistent world state whenever the consequences matter.**

The exact **±5 / ±20 / ±40 boundaries** should stay provisional alongside the probability curve until we stress-test the whole resolution system.

Next is **Ruleset 2.6 — Opposed Resolution**, where we can define what actually happens when **two characters are actively trying to beat one another**, including ties, different skills opposing each other, hidden opposition, and how both participants' degrees of performance interact.

---

## Turn 867219c8-5aee-4579-ae2c-ead6c7a2ee26

### User

Okay

### Assistant — 329f2b86-9ea3-468d-b41f-03cfc4318e78

# Ruleset 2.6 — Opposed Resolution

Opposed resolution applies when **another character or active force is directly resisting the objective**.

The central rule should be:

> **Opposed actions compare two active capabilities, not one character against an arbitrary fixed difficulty.**

That makes NPC stats matter and keeps player/NPC resolution symmetrical.

## 1. Basic Opposed Structure

For an opposed action, calculate:

**Actor Effective Capability**

versus

**Opponent Effective Capability**

Then:

> **Opposed Margin = Actor Capability − Opponent Capability**

That margin enters the same probability curve developed in 2.4.

Example:

**Sneaking shinobi:** Stealth Capability 61  
**Sentry:** Detection Capability 56

Margin:

> +5

So the infiltrator has roughly the same probability associated with a +5 Resolution Margin.

No separate "Guard DC" is needed.

---

# 2. Opposition Must Actually Be Active

Not every task involving another person is opposed.

Suppose someone attempts to steal an object from an unconscious guard.

The guard is not actively resisting.

The task may instead involve:

- static stealth difficulty,
- physical positioning,
- avoiding noise.

But if the guard is awake and watching:

> **Stealth vs Detection**

becomes appropriate.

Similarly:

Talking to someone is not automatically:

> Persuasion vs Willpower.

An opposed social check only occurs when there is genuine resistance or conflicting intent.

---

# 3. Different Skills Can Oppose One Another

The two sides do not need to use the same Skill.

This is extremely important.

Examples:

**Stealth**  
vs  
**Detection**

**Deception**  
vs  
**Insight**

**Tracking**  
vs  
**Trail Concealment**

**Genjutsu Skill**  
vs  
**Genjutsu Resistance**

**Grappling**  
vs  
**Escape Technique**

**Interrogation**  
vs  
**Mental Resistance**

**Pursuit**  
vs  
**Evasion**

The system compares **effective performance toward conflicting objectives**, not matching stat names.

---

# 4. Each Side Uses Its Own Relevant Attributes

Suppose someone is trying to deceive another character.

The deceiver might use:

- Deception Skill,
- Intelligence,
- Willpower or Perception depending on method.

The defender might use:

- Insight Skill,
- Perception,
- Intelligence.

The system should not force both characters through identical attributes.

What matters is:

> **How effective is each character at accomplishing their side of this particular contest?**

---

# 5. Opposed Resolution Should Usually Use One Shared Random Result

We should avoid:

> Character A rolls.  
> Character B rolls.

That introduces too much variance.

It also allows randomness to partially erase meaningful capability gaps.

Instead:

1. Calculate both Effective Capabilities.
2. Calculate the difference.
3. Convert the difference into one probability.
4. Generate one hidden random resolution.

So:

> **Character stats establish the contest. One random event resolves the uncertainty.**

This fits everything we have built so far.

---

# 6. Why Separate Rolls Are Worse

Suppose:

**A = 75**  
**B = 55**

A should hold a major advantage.

With independent d20-like rolls, B might roll extremely well while A rolls extremely poorly, causing enormous variance.

Our system already accounts for favorable and unfavorable moments through the probability curve.

We don't need two separate RNG sources multiplying variance.

Using one contest result preserves capability differences much better.

---

# 7. Opposed Outcomes Are Usually Zero-Sum at the Primary Objective Level

If the primary question is:

> Does A successfully sneak past B?

Then either:

- A succeeds at remaining undetected,
- or B detects A.

Both cannot fully succeed at the same mutually exclusive objective.

The probability should therefore be complementary.

If A has:

> 64%

then B effectively has:

> 36%

for that primary contest.

This prevents contradictory results.

---

# 8. But Secondary Outcomes Can Benefit Both Sides

A contest can still produce nuanced results.

Example:

A attempts to escape B.

Possible result:

> A escapes, but B identifies their direction.

A achieved the primary objective.

B failed to catch them, but still gained useful information.

Or:

> B catches A, but suffers an injury doing so.

The contest is zero-sum at the central objective, but the consequences do not need to be.

This is where outcome degree becomes valuable.

---

# 9. Opposed Outcome Degree

We can use the same Outcome Margin from 2.5.

Suppose A has:

> 64% chance to succeed.

Random result:

> 61.

A wins by:

> +3

That is a **narrow opposed victory**.

Narratively:

> A succeeds, but B came very close.

If the result is:

> 15

then A wins by:

> +49

That is a dominant performance.

The quality of B's failure is implied by the same result.

We do not need a second roll for the opponent.

---

# 10. Ties Should Be Situational, Not Universal

Because the system uses a continuous probability resolution, literal ties are uncommon.

But some objectives allow stalemates.

Examples:

- two grapplers lock each other in place,
- two evenly matched shinobi contest strength without movement,
- two negotiators reach no agreement,
- two trackers continually counter each other.

A near-zero Outcome Margin can sometimes resolve as:

> **stalemate / unresolved contest**

rather than forcing an arbitrary winner.

But this should only happen when a stalemate is physically or logically possible.

---

# 11. Near-Ties Should Usually Produce Narrow Outcomes

If capabilities are almost identical and the random result is near the threshold, the engine should avoid exaggerated narration.

Example:

Bad:

> You completely overwhelm the opponent.

when the contest margin was tiny.

Better:

> You gain just enough leverage to break their grip.

The degree should reflect both:

- probability,
- final Outcome Margin.

---

# 12. Capability Gaps Still Matter

Consider:

**Character A: 80**

**Character B: 50**

Opposed Margin:

> +30

A should dominate the contest most of the time.

If B wins, it should generally be a narrow upset.

This naturally follows from our probability and degree model.

A low-probability victory cannot easily become an overwhelming victory.

That is exactly the behavior we want.

---

# 13. A Weaker Character Can Change the Contest

This is one of the most important opposed-resolution principles.

If a weaker character keeps attempting the same contest, they remain weaker.

Instead, smart play should let them **change which capabilities are being compared**.

Suppose:

**Enemy Taijutsu: 85**

Player Taijutsu: 45

Straight exchange:

> terrible contest.

But perhaps the player:

- creates darkness,
- lays wire traps,
- forces the enemy into narrow terrain,
- uses clones,
- targets an injury.

Now the contest may become:

**Trap Handling / Tactical Movement**

versus

**Perception / Reaction**

The player is not gaining an arbitrary bonus.

They are shifting the fight into a domain where the capability gap is smaller.

This should be a major source of tactical depth.

---

# 14. Structural Advantage Can Remove Opposition

Sometimes circumstances prevent the defender from contesting normally.

Example:

An unconscious target cannot actively resist:

- pickpocketing,
- restraint,
- basic physical manipulation.

Likewise, someone completely unaware of an attack may not initially use their full defensive capability.

This does not necessarily mean automatic success.

Instead, the action may change from:

> opposed resolution

to:

> static difficulty

or to an opposed resolution with restricted defensive options.

This is what we meant earlier by **structural advantage**.

---

# 15. Surprise Should Usually Alter the Contest Structure

Surprise should not simply be:

> +15 to everything.

Depending on the action, surprise might:

- prevent active defense,
- reduce available defensive Skills,
- force reaction rather than preparation,
- delay response,
- deny certain techniques,
- create a free positional advantage.

For example:

A hidden attacker firing from concealment might initially compare:

**Attack Execution**

against:

**Passive Detection / Reaction**

rather than the defender's full combat defense.

After detection, normal opposed combat resumes.

That is much more realistic.

---

# 16. Passive Opposition

Some characters resist without consciously acting.

Examples:

- passive sensory awareness,
- innate resistance,
- automatic defenses,
- protective seals,
- instincts.

These can still generate opposition.

The distinction is:

### Active Opposition
The character deliberately resists.

### Passive Opposition
The character's existing capabilities resist automatically.

This is especially useful for Naruto abilities like:

- sensory techniques,
- dojutsu perception,
- chakra defenses,
- poison resistance.

---

# 17. Hidden Opposition

The player may not know what they're actually contesting.

Suppose the player tries to sneak past someone who appears ordinary.

Unknown to them:

> the target is a trained sensor.

The engine still uses the real Detection Capability.

The player only receives information based on what their character knows.

This preserves uncertainty without cheating.

---

# 18. Layered Opposition

Some actions may involve multiple defenders.

Example:

Sneaking into a compound guarded by:

- sentries,
- sensory barriers,
- patrol animals.

We should not simply add all their scores together.

Instead, each layer may represent a separate obstacle if it creates a distinct meaningful challenge.

For example:

1. Bypass outer patrol.
2. Avoid sensory barrier.
3. Cross inner courtyard unseen.

This prevents massive "stacked DCs."

---

# 19. Multiple Defenders Can Sometimes Combine

If several characters are jointly opposing the exact same action, teamwork rules may combine them.

Examples:

- several shinobi holding a door shut,
- coordinated search team,
- squad attempting to restrain one target.

But their capabilities should not simply be added together.

Otherwise five mediocre characters become absurdly powerful.

Later teamwork rules should account for:

- coordination,
- role overlap,
- diminishing returns,
- leadership,
- number of useful participants.

For now:

> **Multiple opposition uses teamwork mechanics when the defenders are genuinely cooperating on the same objective.**

---

# 20. Sequential Opposition

Some contests unfold through stages.

Example: pursuit.

First:

> Can the target break line of sight?

Then:

> Can the pursuer reacquire the trail?

Then:

> Can the target maintain distance?

Trying to resolve an entire hour-long chase with one roll may erase too much meaningful decision-making.

But rolling every three seconds is equally bad.

The correct scale is:

> **one resolution per meaningful change in the contest.**

---

# 21. Persistent Contests Need State

Long contests should create persistent variables.

For a chase, the engine might track:

- distance,
- line of sight,
- fatigue,
- terrain advantage,
- knowledge of route.

For interrogation:

- resistance,
- rapport,
- information exposed,
- stress.

For grappling:

- position,
- control,
- leverage.

Each resolution changes the state of the contest.

This prevents every exchange from resetting to neutral.

---

# 22. Winning One Contest Can Create Advantage in the Next

Suppose a shinobi wins a taijutsu positioning contest strongly.

That might give them:

> superior positioning

for the next exchange.

But again, we should avoid automatically translating everything into generic bonuses.

The new state might instead:

- restrict the opponent's movement,
- allow a follow-up technique,
- deny retreat,
- expose a flank.

Structural consequences are often more interesting than "+5 next check."

---

# 23. Opposed Social Resolution Needs Strong Limits

Social contests deserve a safeguard.

Winning:

> Persuasion vs Resistance

does not mean:

> mind control.

The defender's beliefs, relationships, values, knowledge, and incentives establish the plausible outcome space.

A highly persuasive character may move someone **within that space**.

Example:

A loyal shinobi might be persuaded to:

- hear an argument,
- delay reporting,
- reveal limited information,

but not necessarily:

- betray their village,
- murder a friend,
- abandon lifelong beliefs.

The same resolution architecture applies, but plausibility gates remain essential.

---

# 24. Deception Has Two Separate Questions

For deception, we should distinguish:

### Can the lie be delivered convincingly?

and

### Is the lie itself believable?

A flawless liar cannot make inherently impossible claims credible without evidence.

So deception resolution may involve:

**Deception Capability**

versus

**Insight / Suspicion**

while the content of the lie changes:

- baseline plausibility,
- available outcome space,
- whether a contest is possible at all.

Example:

> "I'm the Hokage."

said to someone who personally knows the Hokage should not become believable through an exceptional Deception result.

---

# 25. Knowledge Can Modify Opposed Contests

Knowing the opponent can matter.

Suppose someone knows:

- their habits,
- fighting style,
- fears,
- tells,
- preferred techniques.

That information might allow:

- better preparation,
- different Skill selection,
- structural advantages,
- reduced uncertainty.

But it should not automatically become a universal bonus.

Knowledge matters only when it can actually be applied.

---

# 26. Techniques Can Override Normal Opposition

Some abilities may fundamentally alter the contest.

Example:

A dojutsu might:

- reveal movement earlier,
- negate concealment,
- provide predictive information.

A sensory barrier might:

- automatically detect chakra above a threshold.

A paralysis technique might:

- prevent ordinary movement defense.

These abilities should define **how they change resolution**, not merely add giant numbers.

Later ability design can use standardized effects such as:

- replace opposing Skill,
- restrict defender options,
- ignore certain modifiers,
- automatically detect a category,
- force a prerequisite,
- create a new contest type.

---

# 27. Contests Can Be Asymmetric

Not every opponent wants the exact inverse outcome.

Example:

A spy wants:

> remain completely unnoticed.

A guard wants:

> identify potential threats.

If the spy is seen but mistaken for ordinary staff:

- the spy failed perfect concealment,
- but the guard also failed to identify them as a threat.

That's not a simple binary result.

So when objectives differ, the engine should define each side's actual goal before resolving consequences.

This allows nuanced outcomes.

---

# 28. Conflicting Objectives Should Be Defined Explicitly Internally

For meaningful opposed actions, the engine should internally know:

**Actor Objective:**  
Escape without being identified.

**Opponent Objective:**  
Capture the fleeing suspect.

Then a possible result can be:

> Actor escapes but is identified.

Actor partially achieves their objective.

Opponent partially achieves theirs.

This is better than pretending every contest has exactly one binary question.

---

# 29. Initiative Is Not Part of This Ruleset

We should avoid scope creep.

Opposed resolution defines:

> who prevails when objectives conflict.

It should not fully define:

- turn order,
- combat actions,
- damage,
- reaction economy,
- jutsu timing.

Those belong in Combat.

However, later Combat rules should use this system underneath individual contests.

---

# 30. Proposed Opposed Resolution Procedure

When two or more characters directly conflict:

### Step 1 — Define Each Objective

What does each participant actually want to accomplish?

### Step 2 — Determine Whether Objectives Conflict

If not, this may not require opposed resolution.

### Step 3 — Determine Available Opposition

Can the defender actively resist?

Are they surprised, restrained, unconscious, unaware, or otherwise limited?

### Step 4 — Select Relevant Capabilities

For each side:

Attributes + Skill + Mastery + relevant circumstances.

### Step 5 — Apply Structural Conditions

Surprise, techniques, environmental restrictions, information, positioning.

### Step 6 — Calculate Opposed Margin

> Actor Effective Capability − Opponent Effective Capability

### Step 7 — Plausibility Gate

Does the intended outcome remain possible?

### Step 8 — Convert Margin to Probability

Using the standard probability curve.

### Step 9 — Resolve Once

Use one shared random resolution.

### Step 10 — Determine Degree

Use Outcome Margin.

### Step 11 — Interpret Both Objectives

Determine:

- who achieved what,
- what secondary consequences occurred,
- whether a stalemate or partial result is appropriate.

### Step 12 — Update World State

Position, knowledge, suspicion, fatigue, injuries, relationships, etc.

---

## What I Would Lock In

These principles fit cleanly with everything we've established:

> **Direct resistance uses opposed capability rather than arbitrary static Difficulty.**

> **Opposing characters may use completely different Skills and Attributes.**

> **Opposed contests normally use one shared random resolution rather than independent rolls.**

> **The primary mutually exclusive objective is probabilistically zero-sum, but secondary consequences do not have to be.**

> **Large capability differences remain meaningful and low-probability upsets tend to be narrow.**

> **Tactics should allow weaker characters to change the contest rather than simply receive large bonuses.**

> **Surprise and structural advantages can restrict or replace normal opposition.**

> **Passive and hidden defenses still count when they genuinely apply.**

> **Multiple opponents do not simply add their stats together.**

> **Long contests maintain persistent state and resolve at meaningful decision points.**

> **Social victory never bypasses plausible beliefs, incentives, or values.**

> **Special abilities should alter the structure of resolution when appropriate rather than existing as oversized numerical modifiers.**

> **When opposing objectives are not exact inverses, each side's achievement should be evaluated separately.**

That gives us the basic engine for character-versus-character uncertainty.

Next should be **Ruleset 2.7 — Comparative Capability & Power Gaps**. This is where we can formalize exactly how the engine distinguishes **competitive**, **outmatched**, and **nonviable** contests, and—especially important for Naruto—how a weaker shinobi can realistically overcome a stronger one without turning every fight into either predetermined victory or lottery RNG.

---

## Turn f18daf9d-0d7c-4191-aad4-72d4553a0d45

### User

Okay

### Assistant — df31f402-60a6-4c70-bbbc-284dbea65ed7

# Ruleset 2.7 — Comparative Capability & Power Gaps

This section should define **how the engine interprets meaningful differences in capability**, especially when one character is substantially stronger than another.

The goal is to avoid two bad extremes:

- **Power gaps mean nothing because RNG can reverse anything.**
- **Power gaps make tactics irrelevant because the stronger character always wins automatically.**

The better rule is:

> **Raw capability determines the default contest. Strategy determines whether that contest can be changed.**

## 1. Capability Gap Is Not the Same as Rank Gap

The engine should never assume:

> Jonin beats chunin.

or

> Chunin beats genin.

Rank is contextual and institutional.

A genin may be exceptional in one domain and terrible in another. A jonin may be highly capable overall but comparatively weak in a specialized contest.

Power gaps should therefore be based on:

> **Effective Capability in the relevant contest**

not rank.

---

# 2. Use Capability-Gap Bands

I recommend interpreting the Resolution Margin in broad categories.

These should be engine-facing classifications, not necessarily visible labels.

| Capability Gap | Interpretation |
|---:|---|
| 0–5 | Near Peer |
| 6–10 | Slight Advantage |
| 11–20 | Clear Advantage |
| 21–30 | Major Advantage |
| 31–40 | Overwhelming Advantage |
| 41+ | Extreme Mismatch |

These ranges are provisional, but the structure is useful.

---

# 3. Near Peer — 0 to 5

The characters are close enough that small situational factors matter heavily.

Examples:

- positioning,
- timing,
- fatigue,
- information,
- minor injury,
- momentary hesitation.

Neither side should feel reliably dominant.

A weaker character can easily win without the result feeling unusual.

These contests should feel highly dynamic.

---

# 4. Slight Advantage — 6 to 10

One character is noticeably better but the contest remains competitive.

The stronger character should:

- succeed more often,
- recover from small mistakes more easily,
- produce better average outcomes.

But the weaker character does not need extraordinary circumstances to win.

This is still normal competitive territory.

---

# 5. Clear Advantage — 11 to 20

The stronger side is meaningfully favored.

The weaker side can still succeed through:

- good execution,
- favorable circumstances,
- exploiting mistakes.

But repeated direct contests should trend toward the stronger side.

At this level, simply repeating the same approach is usually a poor strategy for the weaker character.

---

# 6. Major Advantage — 21 to 30

This is where direct competition starts becoming dangerous for the weaker side.

The stronger character should usually control the contest unless:

- the weaker side has preparation,
- the stronger side is restricted,
- the contest shifts domains,
- the weaker side has a relevant counter.

A direct upset is still possible if the outcome remains plausible, but it should usually be narrow.

---

# 7. Overwhelming Advantage — 31 to 40

At this point, the weaker side should generally not be able to win a straightforward version of the contest.

The question becomes less:

> Can I beat them at this?

and more:

> How can I stop this from being the contest?

For example, instead of:

> Beat the enemy swordsman in kenjutsu.

the weaker shinobi might:

- destroy visibility,
- collapse the floor,
- use poison,
- separate the enemy from their weapon,
- force them to protect someone,
- lure them into a prepared seal.

The solution is **structural change**.

---

# 8. Extreme Mismatch — 41+

This represents situations where direct success should usually leave the plausible outcome space entirely.

Examples:

- academy student wrestling a legendary taijutsu specialist,
- ordinary genin trying to out-detect an elite sensory shinobi,
- civilian attempting to overpower a chakra-enhanced jonin.

A tiny mathematical probability should not preserve the contest.

Instead:

> **The direct contest is nonviable unless something changes materially.**

The weaker side may still accomplish smaller objectives.

For example:

- survive a few seconds,
- escape,
- distract,
- stall,
- trigger a trap,
- protect someone,
- gather information.

This is important because being hopelessly outmatched does not mean having no meaningful choices.

---

# 9. Power Gap Should Be Objective-Specific

A single pair of characters can have wildly different gaps depending on the task.

Character A might dominate Character B in:

- raw strength,
- taijutsu,
- endurance.

But lose badly in:

- genjutsu,
- stealth,
- strategy,
- medical ninjutsu.

So the engine should never maintain one universal:

> Power Level Difference = 20

Instead, capability gaps exist **per contest**.

That preserves specialization.

---

# 10. Overall Combat Strength Is Not a Resolution Stat

We may eventually calculate broad threat estimates for NPC decision-making, but those should not replace actual resolution.

"Combat Strength 82" should not become:

> 82 vs 67, therefore A wins.

Combat is made of interacting capabilities.

A character can be dangerous because of:

- speed,
- range,
- durability,
- tactics,
- chakra reserves,
- specialized techniques,
- counters.

The resolution engine should preserve those distinctions.

---

# 11. Counters Should Matter More Than Generic Power

Naruto relies heavily on matchups.

A technique or trait can make someone unusually effective against an otherwise stronger opponent.

Examples:

- sensory abilities countering stealth,
- ranged abilities countering poor mobility,
- chakra absorption countering ninjutsu-heavy fighters,
- genjutsu resistance countering illusion specialists.

A counter should not necessarily grant a generic "+20."

Instead, it might:

- negate an opponent's advantage,
- disable part of their capability,
- force them into a weaker Skill,
- alter available outcomes,
- increase resource costs.

This makes matchups feel distinct.

---

# 12. A Counter Is Not Automatically a Win

Having the right tool should not erase every other difference.

If a mediocre shinobi has an ability that counters one aspect of an elite opponent, they may improve from:

> hopeless

to:

> competitive in one dimension.

That does not mean:

> automatic victory.

Counters should reshape contests, not become universal trump cards.

---

# 13. Superior Capability Creates Control

One useful way to think about large gaps is:

> **The stronger side has more control over the terms of the contest.**

A much faster shinobi can often choose:

- engagement distance,
- timing,
- when to disengage.

A much stronger grappler can control:

- positioning,
- leverage,
- movement.

A much better strategist can create:

- better preparation,
- more favorable engagements.

Power should therefore affect not only single-check success, but what options become available.

---

# 14. Large Gaps Should Narrow the Weaker Side's Outcome Space

Suppose a weaker shinobi attacks someone far superior.

The weaker character's plausible outcomes may be:

- completely ineffective,
- force a minor reaction,
- briefly disrupt,
- create a small opening.

Their plausible outcome space may **not** include:

- decisive victory,
- severe injury,
- overwhelming domination.

This is stronger than simply lowering probability.

The gap changes what outcomes are actually possible.

---

# 15. Superior Characters Should Also Have Better Failure Floors

When an elite character fails against a much weaker opponent, the result should normally be mild.

Example:

A jonin fails to intercept a genin's escape attempt.

That might mean:

> the genin barely gets away.

It should not automatically mean:

> the jonin trips, knocks themselves unconscious, and loses all equipment.

The degree system already helps with this, but the principle should be explicit.

---

# 16. Weaker Characters Need Viable Alternative Objectives

When a direct contest is nonviable, the engine should still support meaningful actions.

Instead of:

> Defeat them.

Possible objectives may include:

- delay them,
- force them to defend,
- escape,
- hide,
- rescue someone,
- create distance,
- break line of sight,
- trigger reinforcements,
- gather information,
- force resource expenditure.

This creates tactical gameplay rather than hard "you lose" states.

---

# 17. Numbers Can Overcome Gaps, but Not Linearly

Several weaker characters should be able to threaten a stronger opponent.

But:

> four Capability-40 characters should not automatically equal Capability 160.

Team strength should depend on:

- coordination,
- space,
- timing,
- complementary roles,
- whether multiple people can meaningfully engage at once,
- interference between allies.

This belongs mostly in Teamwork, but the power-gap rules should establish:

> **Numbers improve the contest through additional actions and coordination, not simple stat addition.**

---

# 18. Environment Can Compress Power Gaps

Terrain can reduce the relevance of certain superior capabilities.

Examples:

A speed specialist in a narrow tunnel may lose much of their mobility advantage.

A long-range specialist trapped indoors may have fewer usable options.

A large, powerful fighter in confined space may struggle to fully apply force.

This means environment can:

- reduce effective capability,
- deny certain actions,
- create new structural restrictions.

A weaker character can intentionally seek environments that compress the gap.

---

# 19. Preparation Can Transform a Nonviable Contest

Preparation is one of the strongest ways to overcome power differences.

A character might:

- gather intelligence,
- build traps,
- choose terrain,
- acquire specialized tools,
- arrange allies,
- sabotage equipment,
- force exhaustion,
- manipulate timing.

The important rule is:

> **Preparation must change the actual situation.**

It should not become an abstract "prep bonus."

---

# 20. Resource Pressure Can Reduce a Power Gap Over Time

A stronger opponent may be superior in immediate capability but have limited:

- chakra,
- stamina,
- ammunition,
- technique uses,
- concentration.

A weaker character may succeed by forcing inefficient expenditure.

For example:

> You cannot beat them now, but you may be able to make them spend enough chakra that the later contest becomes competitive.

This gives incremental and strategic play real value.

---

# 21. Injury Can Change the Relevant Gap

Power is dynamic.

A character who normally has:

**Effective Capability 85**

might fall to:

**62**

because of:

- a damaged arm,
- blood loss,
- exhaustion,
- impaired vision.

That can transform an overwhelming matchup into a competitive one.

The engine should always compare **current Effective Capability**, not reputation or baseline stats.

---

# 22. Knowledge Can Create Effective Counters

A weaker character may know:

- a jutsu's activation tell,
- a blind spot,
- a cooldown,
- a chakra weakness,
- an emotional vulnerability,
- a terrain limitation.

This information can reshape the contest.

Knowledge should therefore sometimes alter:

- Skill selection,
- available tactics,
- structural modifiers,
- plausible outcome space.

This makes scouting and experience mechanically meaningful.

---

# 23. Surprise Can Temporarily Compress Gaps

A much weaker character might briefly challenge a much stronger one if the stronger side cannot initially apply their full capability.

Example:

An unsuspecting elite shinobi may not get full use of:

- reaction,
- defense,
- predictive techniques.

But surprise should generally be **temporary**.

Once the stronger character understands what is happening, the normal gap may reassert itself.

This prevents surprise from becoming an all-purpose equalizer.

---

# 24. Specialization Can Produce Local Superiority

A generally weaker character can still be stronger in a narrow domain.

Example:

A low-ranked shinobi may have extraordinary:

- poison knowledge,
- barrier breaking,
- tracking,
- sensory concealment.

Against a more powerful generalist, they may dominate that specific contest.

This is another reason not to rely on overall power levels.

---

# 25. Legendary Characters Should Feel Legendary

If someone is established as extraordinary, the system should mechanically reflect that.

A legendary shinobi should not constantly be:

- detected by ordinary scouts,
- outmaneuvered by inexperienced genin,
- injured by trivial attacks,
- fooled by basic tactics.

They can still be defeated.

But defeating them should usually require:

- comparable capability,
- specific counters,
- major preparation,
- teamwork,
- severe existing disadvantages,
- or unusual circumstances.

Not repeated lucky rolls.

---

# 26. But Legendary Does Not Mean Omnipotent

A legendary shinobi may still have weaknesses.

They can:

- lack information,
- make bad decisions,
- be emotionally compromised,
- face unfavorable matchups,
- run out of chakra,
- be surprised,
- be injured,
- underestimate someone.

Power gaps should protect established competence, not provide plot armor.

---

# 27. Rank-Based Soft Limits From Ruleset 1 Still Matter Indirectly

We previously discussed soft rank expectations for NPC stats.

Those expectations help shape how often large gaps appear.

For example, ordinary genin should rarely have elite-level Attributes without an explanation.

But once the actual statistics exist:

> **Ruleset 2 uses the statistics, not the title.**

So an anomalously talented genin is resolved according to their real capability.

That preserves exceptional characters without breaking consistency.

---

# 28. Nonviable Does Not Mean Mathematically Impossible Forever

A direct contest can be nonviable **under current circumstances**.

That status can change.

For example:

> You cannot currently penetrate this defense.

After:

- learning its weakness,
- acquiring a counter-technique,
- exhausting the defender,
- damaging the barrier,

the contest may become possible.

So the correct phrasing internally is:

> **Currently outside plausible outcome space.**

Not:

> Permanently impossible.

---

# 29. Power-Gap Assessment Should Inform NPC Behavior

NPCs should react to perceived mismatches.

A rational genin who recognizes an overwhelming enemy may:

- retreat,
- hide,
- seek allies,
- stall,
- surrender.

A reckless NPC may still attack.

A desperate NPC may accept terrible odds.

This will connect directly to NPC decision-making later.

Importantly, NPCs act from **perceived capability gaps**, not the engine's perfect information.

---

# 30. The Player Should Receive Qualitative Warning When Appropriate

If the character can reasonably judge the gap, the player should get useful information.

Examples:

> Their movements are noticeably sharper than yours.

> You can tell immediately that a straight contest of strength would be a bad idea.

> You have no clear sense of how capable they are.

> Their chakra control appears far beyond anything you've faced before.

The game should not trick the player into hopeless contests when their character would obviously recognize the danger.

---

# 31. Unknown Strength Should Remain Unknown

Conversely, the engine should not reveal:

> This NPC is 34 points stronger than you.

The player's information depends on observation.

A hidden expert may appear ordinary until:

- they move,
- use chakra,
- reveal a technique,
- are identified.

This preserves discovery.

---

# 32. Power Gaps Should Matter Outside Combat

This framework applies equally to:

- medicine,
- politics,
- crafting,
- research,
- stealth,
- interrogation,
- tracking,
- leadership.

An academy student should not out-diagnose a master medic through luck.

A novice negotiator should not casually dismantle an expert diplomat's position.

The same architecture works everywhere.

---

# 33. Recommended Capability-Gap Logic

When the engine detects a substantial gap:

### Step 1
Calculate the actual relevant Effective Capabilities.

### Step 2
Determine the gap band.

### Step 3
Evaluate whether the weaker side's intended objective remains within plausible outcome space.

### Step 4
If yes, resolve normally using the probability model.

### Step 5
If no, do not assign a token success chance.

### Step 6
Allow alternative objectives that remain plausible.

### Step 7
Reevaluate the gap whenever tactics, terrain, resources, injuries, information, or abilities materially change.

---

# Example — Direct Duel

Genin:

**Taijutsu Capability: 48**

Elite jonin:

**Taijutsu Capability: 82**

Gap:

> **34 — Overwhelming Advantage**

A direct:

> "I beat him in hand-to-hand combat"

objective may be nonviable.

But:

> "I keep him occupied for five seconds while my teammate escapes"

may be difficult but completely plausible.

That distinction is essential.

---

# Example — Changing the Contest

The same genin learns:

- the jonin has an injured left knee,
- narrow corridors restrict their movement,
- a wire trap can force them into one direction.

The genin does not become Capability 82.

Instead, the relevant contest changes.

Perhaps:

**Genin Trap/Positioning Capability: 63**

versus

**Jonin impaired reaction/mobility: 67**

Gap:

> only 4.

Now the tactic is genuinely competitive.

The character overcame superior power through **problem solving**, not an arbitrary buff.

---

# What I Would Lock In

> **Capability gaps are calculated per objective, not as universal power levels.**

> **Rank does not directly determine power gaps.**

> **Near-peer contests remain highly uncertain; large gaps increasingly suppress direct upsets.**

> **At extreme gaps, direct victory can leave the plausible outcome space entirely.**

> **Weaker characters overcome stronger ones primarily by changing the contest.**

> **Counters, terrain, preparation, knowledge, injury, resource pressure, and teamwork can compress or redirect capability gaps.**

> **These advantages must change the actual simulated situation rather than grant arbitrary narrative bonuses.**

> **Large gaps narrow the weaker character's plausible outcomes but should still permit meaningful alternative objectives.**

> **Exceptional characters retain established competence without receiving plot armor.**

> **Current Effective Capability matters more than reputation, rank, or baseline power.**

> **NPCs and players should recognize obvious gaps only when their available information supports that judgment.**

I would keep the exact gap bands provisional until we test them against our final probability curve, but I think the conceptual model is ready to lock in.

Next should be **Ruleset 2.8 — Situational Modifiers**, where we define exactly how things like **injury, fatigue, terrain, visibility, preparation, equipment, surprise, information, morale, and time pressure** affect resolution without drowning the simulator in dozens of tiny bonuses.

---

## Turn 0c510f0e-810a-45d5-b35d-e38d9dced11d

### User

Okay

### Assistant — 4a35a964-16b8-4f93-8916-5d7e7903e7e3

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.8 — Situational Modifiers

Situational modifiers represent temporary circumstances that affect how an action is performed **right now**.

The core rule should be:

> **Only circumstances that meaningfully change the outcome should modify resolution.**

The engine should not try to quantify every tiny detail in a scene.

A character being slightly uncomfortable, mildly distracted, or standing on uneven ground should not automatically create a pile of ±1 effects.

The system should prioritize **important context over exhaustive bookkeeping**.

---

## 1. Three Types of Situational Effects

I think every situational factor should fall into one of three categories.

### Numerical Modifier

The circumstance makes the same action easier or harder.

Example:

An injured shoulder reduces the effectiveness of a sword attack.

The character can still perform the action normally, just less effectively.

### Structural Modifier

The circumstance changes how the action works.

Example:

An enemy cannot see the attacker.

That may prevent normal visual defense rather than merely granting the attacker +10.

### State Modifier

The circumstance changes the ongoing world state, which then affects future actions.

Example:

A shinobi becomes exhausted.

Rather than applying one isolated penalty to one roll, **Exhausted** becomes a persistent condition affecting several appropriate capabilities until recovery.

This distinction should keep the system much cleaner.

---

# 2. Numerical Modifiers Should Be Bounded

Because our capability scale is roughly 0–100, modifiers need to remain meaningful without overpowering actual character development.

I recommend a standard modifier scale roughly like this:

| Modifier | Meaning |
|---:|---|
| ±2 | Minor |
| ±5 | Noticeable |
| ±10 | Significant |
| ±15 | Major |
| ±20 | Extreme |

Values larger than ±20 should be rare.

If something appears to require:

> −35 Capability

that is often a sign that the situation should instead be treated as a **structural restriction**.

For example:

Being completely blinded probably should not simply be:

> −30 Perception.

The character may no longer be able to perform visually dependent actions at all.

---

# 3. Avoid Tiny Modifier Stacking

We should explicitly prevent situations like:

> +2 favorable footing  
> +1 good lighting  
> −2 mild fatigue  
> +1 familiarity  
> −1 distraction  
> +2 equipment

This would become impossible to manage consistently.

Instead, the engine should combine closely related factors into one overall assessment.

For example:

> **Environmental conditions: moderately favorable (+5)**

or

> **Physical condition: significantly impaired (−10)**

This preserves the important effects without pretending the simulation can measure everything perfectly.

---

# 4. Modifiers Should Be Category-Based

To prevent stacking abuse, situational modifiers should generally be grouped into categories.

A useful standard set would be:

- Physical Condition
- Mental Condition
- Environment
- Positioning
- Equipment
- Preparation
- Information
- Assistance
- Time Pressure
- Tactical Circumstances

Normally, only the **strongest relevant effect within each category** should apply.

If multiple effects in the same category genuinely interact, the engine can combine them—but not simply add every individual modifier.

---

# 5. Physical Condition

This covers things like:

- injury,
- fatigue,
- illness,
- blood loss,
- pain,
- physical restraint,
- sleep deprivation.

These normally modify **Effective Capability**, not Difficulty.

Example:

The cliff has not become harder because your arm is injured.

Your ability to climb it has become worse.

Different conditions should affect different abilities.

A leg injury might reduce:

- movement,
- jumping,
- dodging.

But have little or no effect on:

- analysis,
- persuasion,
- sealing theory.

This means conditions should be **targeted**, not global.

---

# 6. Fatigue Should Usually Be a Persistent State

Fatigue is too important to handle as a one-off penalty.

A character should have a persistent fatigue state that can affect:

- physical output,
- reaction,
- concentration,
- chakra efficiency,
- endurance.

The severity should matter.

Something like:

**Fresh**  
No penalty.

**Tired**  
Minor effects in demanding situations.

**Fatigued**  
Noticeable reduction in sustained performance.

**Exhausted**  
Significant impairment.

**Severely Exhausted**  
Major restrictions and possible automatic failure for demanding tasks.

We can formalize exact fatigue mechanics later, likely under Health/Stamina.

Ruleset 2 only needs to define how the state influences resolution.

---

# 7. Injuries Should Be Specific

Rather than:

> Injured: −10 everything

injuries should affect relevant applications.

Examples:

A damaged hand may affect:

- weapon handling,
- hand seals,
- climbing,
- fine motor control.

A rib injury may affect:

- endurance,
- force generation,
- breathing,
- sustained combat.

A concussion may affect:

- concentration,
- perception,
- reaction,
- memory.

This makes injuries tactically meaningful.

---

# 8. Mental Condition

This includes:

- fear,
- panic,
- anger,
- grief,
- confusion,
- stress,
- distraction,
- confidence,
- focus.

But we should be careful here.

The engine should not arbitrarily punish characters because:

> "You're emotional, so −10."

Mental modifiers should require meaningful circumstances and should affect relevant actions.

Example:

Panic might impair:

- precision,
- planning,
- concentration.

But could potentially increase:

- immediate escape effort,
- willingness to take risks.

The effect depends on the situation.

---

# 9. Personality Should Influence Responses to Pressure

Two characters should not automatically react the same way to fear.

A disciplined veteran may function well under combat pressure.

An inexperienced civilian may become severely impaired.

This means emotional-state modifiers should depend partly on:

- Willpower,
- experience,
- personality,
- relevant training,
- prior exposure.

The event creates the pressure.

The character determines the response.

---

# 10. Environment

Environmental effects include:

- darkness,
- rain,
- snow,
- wind,
- smoke,
- heat,
- cold,
- terrain,
- noise,
- elevation,
- confined space.

Some affect Difficulty.

Others affect Capability.

And some change the structure of the contest entirely.

Example:

Heavy fog may:

- reduce visual detection,
- restrict ranged targeting,
- improve concealment,
- reduce long-range coordination.

It should not just become:

> Fog = −10 everything.

---

# 11. Environment Can Affect Participants Differently

A condition that hinders one character may barely affect another.

Darkness may strongly impair an ordinary person.

But someone with:

- Byakugan,
- sensory abilities,
- enhanced night vision,

may ignore much of the disadvantage.

So environmental effects should be evaluated **per participant**.

This prevents global modifiers from flattening special abilities.

---

# 12. Positioning

Positioning should be one of the most important situational categories.

Examples:

- high ground,
- cover,
- flanking,
- confined space,
- superior reach,
- compromised footing,
- trapped position.

Positioning may either:

- modify capability,
- restrict options,
- unlock actions,
- deny actions.

Good positioning should frequently be **structural** rather than numerical.

For example:

Being behind cover may deny a direct ranged attack entirely rather than simply grant:

> +10 Defense.

---

# 13. Positioning Should Persist

If a character earns superior positioning through a successful action, that position should remain until something changes it.

Example:

A character wins a grappling exchange and pins the opponent against a wall.

They should not magically reset to neutral on the next action.

This reinforces persistent contest state.

---

# 14. Equipment

Equipment should matter when it meaningfully changes capability.

Examples:

- climbing tools,
- medical instruments,
- armor,
- weapons,
- sensory devices,
- disguises.

Equipment can:

- improve performance,
- unlock actions,
- mitigate environmental difficulty,
- reduce consequences.

But ordinary equipment should not create enormous stat inflation.

A better sword does not turn a novice into a master swordsman.

Skill still determines how effectively the equipment is used.

---

# 15. Equipment Quality Should Have Diminishing Returns

The difference between:

> no tool

and

> appropriate tool

may be enormous.

The difference between:

> good tool

and

> excellent tool

should usually be smaller.

This prevents equipment progression from overpowering character progression.

---

# 16. Specialized Equipment Can Create Structural Advantages

Some tools should do more than grant bonuses.

Examples:

A gas mask may:

> negate inhaled toxin exposure.

A chakra-suppressing restraint may:

> prevent certain techniques.

A sensory jammer may:

> block or distort specific detection methods.

These should directly interact with the system they counter.

---

# 17. Preparation

Preparation should be powerful because it reflects deliberate effort before the action.

It can include:

- scouting,
- planning,
- rehearsing,
- setting traps,
- preparing tools,
- studying a target,
- choosing timing.

But we should never create:

> "Prepared: +15"

as a generic universal bonus.

Instead, preparation should create specific advantages.

Example:

Studying guard rotations may:

> reduce patrol uncertainty.

Preparing an antidote may:

> reduce poison consequences.

Learning an opponent's technique may:

> reveal a counter.

Preparation changes the situation.

---

# 18. Information

Information is related to preparation but distinct.

Information can affect:

- what options are available,
- how accurately difficulty is estimated,
- whether weaknesses are known,
- whether surprise is possible.

Knowing something should only help when the knowledge can actually be applied.

For example:

Knowing an opponent prefers Fire Release does not automatically improve every action against them.

It helps when making decisions relevant to Fire Release.

---

# 19. Information Can Reduce Uncertainty Without Increasing Capability

This distinction is important.

A character may not become more capable.

Instead, information might reveal:

> which action is actually easier.

Example:

You learn that a barrier has one weak seal node.

Your sealing skill does not improve.

You now know where to apply it.

The contest changes.

---

# 20. Time Pressure

Time pressure should increase difficulty only when the action truly requires faster execution.

Example:

Perform surgery normally:

> Difficulty 60.

Perform the same procedure in half the available time:

> perhaps Difficulty 70.

But if the task inherently takes ten seconds regardless, saying:

> "You only have ten seconds"

does not change anything.

Time pressure matters only when it forces a compromise in execution.

---

# 21. Taking Extra Time

Characters should often be able to reduce uncertainty by taking longer.

Extra time can provide:

- careful observation,
- precision,
- repeated verification,
- lower physical strain.

But there should be diminishing returns.

Taking ten minutes instead of thirty seconds may matter enormously.

Taking ten hours instead of eight hours may not matter at all.

Extra time should only help where time can realistically improve performance.

---

# 22. Rushing Should Trade Reliability for Speed

The inverse should also be possible.

A character may rush to:

- finish before guards arrive,
- stabilize someone before they bleed out,
- complete hand seals under pressure,
- escape before a route closes.

Rushing may:

- increase Difficulty,
- reduce quality ceiling,
- increase resource use.

This creates meaningful decision-making.

---

# 23. Assistance

Another character can improve an action if they have a meaningful way to help.

Examples:

- holding equipment,
- providing expertise,
- watching for threats,
- stabilizing a patient,
- creating a distraction.

But assistance should not automatically mean:

> +5 per helper.

The helper must contribute something relevant.

Teamwork will formalize this later.

---

# 24. Poor Assistance Can Hurt

An unskilled assistant may sometimes:

- interfere,
- distract,
- consume resources,
- provide bad information.

So:

> more people ≠ always better.

This is particularly important for technical tasks.

---

# 25. Surprise

Surprise is usually structural.

It might:

- deny active defense,
- delay response,
- restrict available techniques,
- reduce situational awareness.

It should rarely be represented as a flat universal modifier.

And surprise should usually disappear once the target understands what is happening.

---

# 26. Morale

Morale should influence actions involving:

- persistence,
- willingness to continue,
- risk tolerance,
- coordination.

It should not generally alter raw physical ability.

A demoralized soldier may still swing a sword with the same strength.

They may simply:

- hesitate,
- retreat sooner,
- coordinate poorly.

Morale is therefore often better handled through **decision-making and persistence** than direct capability penalties.

---

# 27. Confidence Is Not Competence

Confidence should not directly increase success simply because the character believes they can succeed.

However, confidence may reduce:

- hesitation,
- fear penalties,
- indecision.

Overconfidence can also create poor choices.

So confidence affects **behavior and mental state**, not fundamental skill.

---

# 28. Familiarity

Familiarity can matter when repeated exposure genuinely improves execution.

Examples:

- fighting in your own home,
- navigating a familiar forest,
- using your own custom weapon,
- performing a practiced routine.

Familiarity should usually provide a small or moderate advantage at most.

It should not override substantial capability gaps.

---

# 29. Unfamiliarity

Likewise, unfamiliar tools, terrain, or techniques may reduce performance.

But the penalty should disappear with experience.

This can create useful early-game progression without changing permanent Attributes.

---

# 30. Multiple Modifiers Should Use Diminishing Returns

This is important.

Suppose a character has:

- good preparation,
- superior equipment,
- favorable terrain,
- useful information.

Simply adding:

`+10 +10 +10 +10`

could completely overwhelm character stats.

Instead, modifiers should stack with diminishing returns.

A useful provisional rule could be:

> **Full effect from the strongest modifier.**

> **Half effect from the second.**

> **Quarter effect from additional overlapping modifiers.**

But I would not lock that exact math yet.

The more important rule is:

> **Several advantages can combine, but they should not scale linearly without limit.**

---

# 31. Independent Categories Can Matter More

Diminishing returns should mostly apply to overlapping advantages.

For example:

Two pieces of information about the same weakness overlap heavily.

But:

- good terrain,
- good equipment,
- good preparation

may represent distinct advantages.

Even then, the total effect should remain bounded.

If advantages collectively transform the situation dramatically, that is usually a sign they should change the **structure of the contest** rather than create +40 capability.

---

# 32. Structural Modifiers Should Take Priority Over Huge Numerical Modifiers

Whenever the engine considers applying something like:

> ±20 or more

it should ask:

> Is this actually changing what the character can or cannot do?

Examples:

Blinded:

Probably structural.

Immobilized:

Structural.

Completely concealed:

Structural.

Weapon destroyed:

Structural.

Air supply cut off:

Structural.

This keeps numbers from becoming substitutes for simulation.

---

# 33. Modifiers Should Never Double Count

Suppose rain:

- makes a cliff slippery,
- reduces grip,
- increases climbing difficulty.

We should not apply:

> +10 Difficulty for rain

and

> −10 Capability for slippery hands

unless those are genuinely separate effects.

Usually one representation is enough.

This should be a hard consistency rule.

---

# 34. Conditions Should Have Causes

The engine should not invent modifiers just because a scene "feels tense."

For example:

> −5 because the battle is dramatic

is invalid.

Valid:

> −5 because smoke is obscuring vision.

Every modifier should trace back to a concrete world-state fact.

---

# 35. Modifiers Must Be Reversible When Conditions End

If:

> smoke disperses,

the visual penalty disappears.

If:

> the character rests,

fatigue may lessen.

If:

> they drop the heavy pack,

the encumbrance effect ends.

Temporary modifiers should never silently become permanent.

---

# 36. Player Actions Should Be Able to Manipulate Modifiers

This is where the system becomes strategic.

A player can deliberately seek:

- cover,
- better lighting,
- rest,
- information,
- equipment,
- advantageous terrain,
- surprise.

Likewise, they can impose disadvantages on enemies:

- smoke,
- restraints,
- distractions,
- exhaustion,
- damaged equipment.

This turns situational modifiers into gameplay rather than invisible math.

---

# 37. NPCs Should Do the Same

Intelligent NPCs should also try to improve their circumstances.

A skilled tracker may wait for daylight.

A cautious shinobi may avoid fighting a speed specialist in open terrain.

A medic may refuse to perform a risky procedure without proper equipment unless urgency demands it.

NPC intelligence should interact with resolution conditions.

---

# 38. Minor Advantages Should Often Stay Narrative

Not every helpful detail needs to alter probability.

Example:

A character has:

- slightly better shoes,
- a small breeze behind them,
- familiarity with the street.

If these factors collectively do not meaningfully change the outcome, they can simply inform narration.

This is a crucial anti-scope-creep rule.

---

# 39. Modifier Threshold

I recommend a general principle:

> **Do not apply a numerical modifier unless it would plausibly shift the character's chance of success enough to matter.**

Because of our probability curve, even a 2-point modifier can matter in a very close contest.

But the engine should not hunt for 2-point modifiers.

They should only appear when the factor itself is meaningful.

---

# 40. Recommended Situational Resolution Process

When contextual factors exist, the engine should internally evaluate them in this order:

**First:** Does the condition make the action impossible or unlock a new action?

If yes, treat it structurally.

**Second:** Does it change the objective or the available opposition?

If yes, alter the resolution structure.

**Third:** Does it change the task for everyone?

If yes, modify Difficulty.

**Fourth:** Does it change one participant's performance?

If yes, modify Effective Capability.

**Fifth:** Does it create a persistent condition?

If yes, update world state.

**Sixth:** Are multiple modifiers overlapping?

If yes, combine them rather than stacking blindly.

That sequence should prevent most modifier problems.

---

# Example — Rooftop Chase

Character A is pursuing Character B.

Conditions:

- heavy rain,
- B knows the neighborhood,
- A has an injured ankle,
- both are tired.

We should not produce:

> Rain −5  
> Wet roof −5  
> Bad footing −5  
> Injury −10  
> Fatigue −5  
> Familiarity +5

Instead:

**Environment:** Heavy rain significantly worsens rooftop movement for both.

**Character A:** Injured ankle reduces movement capability.

**Character B:** Familiarity allows better route selection.

**Both:** Fatigue affects sustained movement.

The chase is then resolved from those meaningful conditions.

---

# Example — Ambush

A weaker genin attacks a stronger chunin from complete concealment.

We s

---

## Turn 8bb4e781-743c-44bc-832b-ad2807e0f1c7

### User

Okay

### Assistant — e4868127-48c8-4885-9915-8901457aa24a

# Ruleset 2.9 — Advantage, Disadvantage & Circumstantial Superiority

This section should define **when a situation is meaningfully favorable or unfavorable enough that it changes more than just a number**.

We already have numerical modifiers in 2.8. This section is for situations where the real effect is closer to:

- gaining or losing options,
- acting before the opponent can respond,
- forcing the opponent into a worse kind of contest,
- bypassing a layer of defense,
- or making an action no longer meaningfully opposed.

The core principle should be:

> **Circumstantial superiority should change the structure of resolution when the situation itself has changed.**

## 1. Advantage Is Not a Generic Reroll Mechanic

I do **not** think we should use a traditional system like:

> Advantage = roll twice and take the better result.

That would add another layer of RNG without representing why the character has the advantage.

Instead, advantage should describe **what specifically became easier or unavailable to the other side**.

For example:

- surprise,
- high ground,
- concealment,
- restraint,
- superior information,
- positional control.

Each should have a different effect.

---

# 2. Four Levels of Circumstantial Superiority

I think we should distinguish four broad states.

### Favorable
The character has a modest but meaningful edge.

Usually numerical.

### Strong Advantage
The circumstance materially changes expected performance.

May be numerical or structural.

### Dominant Position
The advantaged character controls the terms of the contest.

The opponent may have restricted options.

### Uncontested
The opposing side cannot meaningfully resist this particular objective.

The action may become a static task or automatic outcome.

These should be descriptive categories, not rigid player-facing labels.

---

# 3. Favorable Circumstances

These are situations where the normal contest remains intact.

Examples:

- slightly better footing,
- useful cover,
- moderate familiarity with terrain,
- having prepared the correct tool.

The opponent can still act normally.

So these usually use the modifier system from 2.8.

Example:

> You know this section of forest better than your pursuer.

That may improve route selection and effective evasion capability.

No need to rewrite the entire contest.

---

# 4. Strong Advantage

A Strong Advantage means the situation begins to change how the contest works.

Examples:

- attacker is hidden,
- defender is distracted,
- one combatant has superior reach in a narrow engagement,
- a tracker knows exactly which route the target took,
- a negotiator possesses damaging evidence.

The opponent still has meaningful resistance, but not under normal conditions.

This might:

- reduce which Skill they can use,
- alter their Effective Capability,
- limit available responses,
- grant the advantaged side better outcome options.

---

# 5. Dominant Position

A Dominant Position means one side has already achieved substantial control.

Examples:

- opponent is pinned,
- target is surrounded with no clear exit,
- defender has been disarmed while the attacker remains armed,
- a shinobi has been caught in a functioning restraint technique,
- one side controls the only safe route.

This should not simply grant:

> +20

Instead, the dominant side gets access to actions that were previously unavailable, while the disadvantaged side loses or restricts options.

For example, a pinned character may no longer be able to:

- sprint away,
- perform large physical techniques,
- freely reposition.

But they may still be able to:

- struggle,
- use certain jutsu,
- talk,
- exploit a mistake.

---

# 6. Uncontested Actions

Sometimes opposition disappears entirely.

Examples:

- taking an item from an unconscious person,
- walking through an unlocked and unguarded doorway,
- restraining someone who is already fully immobilized,
- observing a target that has no way to detect the observer.

In these cases, an opposed check is inappropriate.

The action might become:

- automatic,
- or a static difficulty task if execution still matters.

This is important because the simulation should not preserve opposition just for the sake of rolling.

---

# 7. Surprise Is Temporary Circumstantial Superiority

Surprise should be one of the clearest examples.

A surprised target may:

- not use active defense,
- rely only on passive perception or reaction,
- lose certain immediate responses,
- be unable to prepare a technique.

But surprise should usually last only until the target becomes aware.

So:

> Surprise changes the **opening contest**, not necessarily the entire encounter.

This makes ambushes strong without making them automatic victories.

---

# 8. Concealment Can Change Who Gets to Contest

If an attacker is fully concealed, the defender may not get to use normal defensive preparation.

But concealment itself should often be resolved first.

For example:

1. Can the attacker remain undetected?
2. If yes, the attack begins from concealment.
3. The defender may use passive reaction rather than full defense.
4. Once revealed, normal opposition resumes.

This avoids bundling everything into one giant bonus.

---

# 9. Positional Advantage Should Create Options

High ground, flanking, cover, choke points, elevation, and distance should matter because they change what characters can realistically do.

For example:

High ground may improve:

- visibility,
- ranged line of sight,
- defensive control.

A choke point may:

- prevent multiple enemies from engaging simultaneously.

Cover may:

- deny direct attacks from certain angles.

This is much more meaningful than assigning one universal "position bonus."

---

# 10. Restraint Should Restrict Specific Actions

A restrained character should not simply suffer:

> −15 to all checks.

Instead, the engine should ask:

> Which actions does this restraint actually prevent?

Examples:

Bound hands may restrict:

- hand seals,
- weapon use,
- climbing.

But not necessarily:

- speaking,
- observing,
- using a technique that requires no hand seals.

This keeps structural disadvantage precise.

---

# 11. Blindness and Sensory Denial

Complete sensory loss should also be structural.

Blindness may:

- remove visually targeted actions,
- prevent visual tracking,
- force reliance on hearing or chakra sensing.

But a sensory shinobi may retain strong situational awareness.

So:

> Blindness does not equal universal helplessness.

It changes what information channels are available.

---

# 12. Information Superiority

Knowing something the opponent does not can create a major advantage.

Examples:

- knowing the opponent's technique,
- knowing terrain they do not,
- knowing an ambush is coming,
- knowing their objective while they misunderstand yours.

Information superiority may allow:

- better positioning,
- preemptive counters,
- avoiding unfavorable contests,
- selecting better objectives.

Again, information often changes **decision space**, not just numbers.

---

# 13. Deception Can Create Structural Advantage

If a deception succeeds before a later contest, it can reshape that later contest.

Example:

An enemy believes you are retreating.

They pursue aggressively and enter a trap.

The deception does not need to provide:

> +10 Trap Skill.

Instead, it caused them to occupy a disadvantageous position.

This is exactly the kind of persistent simulation linkage we want.

---

# 14. Initiative and Control

Without fully defining combat initiative yet, we should establish a broader concept:

> **Circumstantial superiority can determine who controls the next meaningful decision.**

Examples:

- successful ambush,
- superior positioning,
- forcing an opponent onto the defensive,
- trapping someone.

The side with control may get to choose:

- whether to press,
- disengage,
- reposition,
- escalate,
- change objectives.

This creates tactical momentum without requiring arbitrary bonuses.

---

# 15. Control Is Not Permanent

Dominance should persist only while its cause persists.

If someone has the enemy pinned but loses their grip, the dominant position ends.

If smoke grants concealment and disperses, the advantage disappears.

If an ambush is revealed, surprise ends.

This follows our persistent-state rules from 2.8.

---

# 16. Advantages Can Cascade

One success may create a favorable state that enables another.

For example:

**Successful distraction**

creates:

> reduced guard attention.

That enables:

**Stealth success**

which creates:

> superior infiltration position.

That enables:

**Access to restricted information.**

This is desirable.

Good planning should create chains of advantage.

But each step should arise causally from the previous one.

---

# 17. Advantages Should Not Cascade Infinitely

We need a safeguard here.

The engine should not allow:

> successful action → +10  
> next success → +10  
> next success → +10

until the character becomes unstoppable.

Instead, advantages should usually become:

- specific positions,
- information,
- restricted opponent options,
- temporary states.

They persist only while meaningful.

---

# 18. Multiple Advantages Should Be Evaluated Structurally First

Suppose a character has:

- surprise,
- high ground,
- concealment,
- superior information.

Before adding modifiers, the engine should ask:

> What does all of this actually mean for the contest?

Perhaps the result is:

- defender cannot prepare,
- attacker chooses engagement distance,
- defender does not know attack direction.

That may already fully represent the advantage.

There is no need for four separate bonuses.

---

# 19. Multiple Disadvantages Can Produce Nonviability

Likewise, disadvantages can compound until an action leaves plausible outcome space.

Example:

A character is:

- exhausted,
- blinded,
- restrained,
- badly injured.

Attempting to:

> outrun a healthy shinobi

may simply be nonviable.

We should not continue stacking penalties until the final score becomes absurd.

At some point, the resolution structure changes to:

> this objective is not currently possible.

---

# 20. Circumstantial Superiority Can Override Normal Power Gaps

This is one of the most important tactical principles.

Suppose:

**Stronger ninja:** Capability 80  
**Weaker ninja:** Capability 50

Normally overwhelming.

But if the stronger ninja is:

- trapped,
- unable to see,
- unable to move freely,
- unaware of the attack,

their full Capability 80 may no longer be relevant to that particular contest.

The weaker character does not become stronger.

The stronger character simply cannot apply all of their capability.

This is how tactics should overcome raw power.

---

# 21. But Advantage Must Be Relevant

A favorable condition should only matter if it actually affects the action.

Example:

High ground helps a ranged attacker.

It may do almost nothing during an indoor medical procedure.

Likewise:

Knowing an opponent's favorite food does not help against their taijutsu unless the information becomes tactically relevant.

This sounds obvious, but it should be explicit for simulation consistency.

---

# 22. Structural Advantage Should Be Narrowly Defined

We should avoid broad statements like:

> "He has the advantage."

Instead, the engine should understand:

> "He controls the doorway."

or

> "She is attacking from outside his visual field."

or

> "The target cannot currently form hand seals."

Specificity prevents the engine from applying advantages where they don't belong.

---

# 23. Advantage Can Be One-Sided Without Being Absolute

A character may dominate one dimension while remaining vulnerable elsewhere.

Example:

A grappler has someone pinned.

They dominate **movement**.

But if the pinned shinobi can use a no-hand-seal lightning technique, the grappler may still be in danger.

So structural superiority should restrict only the affected dimensions.

---

# 24. Disadvantage Should Create Meaningful Escape Routes

A disadvantaged character should often have options like:

- concede ground,
- disengage,
- switch objectives,
- sacrifice resources,
- take a risk,
- call for help.

The system should not interpret "disadvantaged" as "no choices."

This is particularly important for interactive gameplay.

---

# 25. Tactical Sacrifice

Characters may intentionally accept one disadvantage to gain another advantage.

Examples:

- sacrifice cover to gain speed,
- reveal position to protect an ally,
- spend large chakra to break restraint,
- accept injury to secure escape,
- abandon equipment to move faster.

This should be supported naturally.

It makes choices meaningful beyond pure success probability.

---

# 26. Advantages Can Affect Outcome Ceiling or Floor

This is a useful addition.

Some conditions may not change success probability much, but they change **how good or bad outcomes can become**.

Example:

A safety rope while climbing may not make the climb much easier.

But it dramatically reduces the worst failure outcome.

Likewise:

Armor may not stop the opponent from successfully hitting you, but it may reduce how severe the consequence becomes.

So circumstantial effects can influence:

- success chance,
- available actions,
- outcome ceiling,
- outcome floor,
- consequences.

This gives us more flexibility than treating everything as probability.

---

# 27. Protective Advantages

This deserves its own category.

Examples:

- armor,
- safety harnesses,
- backup seals,
- medical monitoring,
- escape routes.

These may primarily reduce failure consequences rather than improve the chance of success.

That is an important distinction.

---

# 28. Redundancy Can Reduce Catastrophic Risk

If a character has multiple safeguards, they may prevent catastrophic outcomes.

Example:

A sealing experiment has:

- containment barrier,
- emergency shutdown,
- backup operator.

The procedure might still fail.

But catastrophic escalation becomes less plausible.

Preparation can therefore improve **risk management** without necessarily making success much easier.

This will matter a lot for research and experimentation systems.

---

# 29. Circumstantial Superiority Should Affect NPC Choices

NPCs should recognize exploitable advantage when they reasonably can.

A cautious NPC may:

- retreat from an ambush,
- refuse to enter a choke point,
- wait for reinforcements.

A reckless one may press anyway.

This helps personality and intelligence matter organically.

---

# 30. The Player Should See What Their Character Can Perceive

If the character recognizes a major advantage or disadvantage, the narration should communicate it.

For example:

> He has nowhere to retreat without exposing his back.

or:

> From this position, you have a clear line of sight while he does not.

or:

> You immediately realize the corridor prevents you from using your usual mobility.

This is more useful than:

> Advantage: +15.

---

# 31. Recommended Structural-Advantage Procedure

Whenever a major circumstance exists, the engine should ask:

### Step 1
Does this circumstance affect the current objective?

If no, ignore it.

### Step 2
Does it merely make performance somewhat better or worse?

If yes:

> numerical modifier.

### Step 3
Does it change what actions are available?

If yes:

> structural modifier.

### Step 4
Does it remove meaningful opposition?

If yes:

> convert to static resolution or automatic outcome.

### Step 5
Does it change only the consequences of success/failure?

If yes:

> modify outcome ceiling/floor or stakes.

### Step 6
Does it persist?

If yes:

> store it as world state until its cause ends.

That should become the engine's standard logic.

---

# Example — Hidden Archer

A shinobi attacks from complete concealment.

Bad implementation:

> +20 Attack because hidden.

Better implementation:

- defender is unaware,
- cannot use prepared defense,
- cannot identify attack direction,
- may rely only on passive detection/reaction,
- attack may remain concealed afterward depending on technique.

The advantage is much more meaningful and specific.

---

# Example — Safety Equipment

A shinobi crosses a dangerous ravine using a secured rope.

The rope might not make the balancing action substantially easier.

But failure changes from:

> fall to possible death

to:

> fall and be caught by the rope.

So:

**success probability:** similar

**failure severity:** dramatically reduced.

This demonstrates why circumstantial effects should not all modify Capability.

---

# Example — Captured Enemy

An enemy is bound securely.

Attempt:

> Search them for weapons.

This should probably not be:

> Search Skill vs Enemy Resistance.

If they physically cannot interfere, the task is either:

- static Search Difficulty,
- or automatic if the weapons are obvious.

Their restraint has removed active opposition.

---

# What I Would Lock In

> **Advantage/disadvantage is not a generic reroll mechanic.**

> **Minor advantages remain numerical; major advantages should increasingly alter the structure of resolution.**

> **Circumstantial superiority may restrict actions, remove defenses, change the relevant contest, alter initiative/control, or remove opposition entirely.**

> **Surprise, concealment, positioning, restraints, and information superiority should usually be modeled structurally.**

> **Advantages only affect the dimensions they logically influence.**

> **Dominant positions persist until their underlying cause changes.**

> **Advantages can cascade through causal world-state changes, but should not accumulate as limitless generic bonuses.**

> **Multiple disadvantages can make an objective nonviable rather than producing absurd modifier totals.**

> **A weaker character can overcome a stronger opponent by preventing the stronger opponent from applying their full capability.**

> **Some advantages alter the severity of outcomes rather than the probability of success.**

> **Protective preparation can reduce catastrophic failure without necessarily making success more likely.**

This also gives us a cleaner distinction between **performance advantage** and **risk mitigation**, which I think will be important throughout the simulator.

Next should be **Ruleset 2.10 — Automatic Success, Automatic Failure & Check Suppression**. That section can formalize exactly when the engine should skip resolution entirely, when a 1–3% outcome should still be rolled, and when an action is simply outside the character's current plausible capability.

---

## Turn e52dfbbc-b2e9-4bf6-856b-a593e096411b

### User

Okay

### Assistant — 4b942640-42f3-49a4-8ee9-5922903d821e

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.10 — Automatic Success, Automatic Failure & Check Suppression

This section should define when the engine should **not use probability at all**.

That is important because a realistic simulation should not constantly ask RNG whether obvious things happen.

The central rule should be:

> **If only one outcome remains meaningfully plausible, resolve it automatically.**

A check exists to resolve uncertainty.

If there is no meaningful uncertainty, there should be no check.

---

# 1. Three Resolution States

Every attempted action should first be classified as one of three states:

### Automatic Success
Failure is no longer meaningfully plausible.

### Uncertain
Both success and failure remain plausible.

### Automatic Failure
The intended objective is not realistically achievable under the current conditions.

Only the middle category uses normal probability resolution.

---

# 2. Automatic Success

An action should automatically succeed when the character's relevant capability, circumstances, and objective make failure effectively irrelevant.

Examples:

- a jonin performing basic tree walking under normal conditions,
- a trained medic applying an ordinary bandage,
- an experienced shinobi clearing a short rooftop gap,
- a character opening an unlocked door.

This prevents experts from randomly becoming incompetent.

---

# 3. Automatic Success Is Not the Same as Perfect Success

This distinction is important.

Automatic success means:

> the basic objective happens.

It does not necessarily mean:

> maximum possible quality.

For routine actions, quality may simply not matter enough to resolve.

But if quality itself matters, there can still be uncertainty even when baseline completion is guaranteed.

Example:

A master calligrapher can certainly write a letter.

The uncertainty might instead be:

> Can they reproduce a specific handwriting style perfectly?

So the engine should resolve the **actual uncertain objective**, not manufacture failure for the basic action.

---

# 4. Routine Tasks Should Become Automatic Through Progression

This is one of the most important ways characters should feel stronger.

Something that once required concentration should eventually become routine.

For example:

### Academy student
Basic chakra adhesion may be uncertain.

### Experienced genin
Usually reliable.

### Chunin
Automatic under normal conditions.

### Elite jonin
May remain automatic even under meaningful distraction.

This produces progression without needing inflated damage numbers or constant new abilities.

---

# 5. Stress Can Restore Uncertainty

An action that is normally automatic may become uncertain under abnormal conditions.

Tree walking may be automatic normally.

But perhaps not while:

- carrying an injured teammate,
- fighting another shinobi,
- suffering severe chakra disruption,
- running across collapsing terrain.

So automatic success is always contextual.

It is not permanently attached to the action.

---

# 6. Automatic Failure

Automatic failure applies when the intended outcome lies outside the character's current plausible outcome space.

Examples:

- ordinary civilian attempting to overpower a chakra-enhanced jonin,
- academy student lifting a massive boulder beyond their physical capability,
- novice attempting a technique whose prerequisites they do not possess,
- character trying to see through a completely opaque wall without an ability enabling it.

No RNG should occur.

---

# 7. Impossible Is Different From Extremely Difficult

This distinction must be explicit.

### Extremely Difficult

The character possesses a plausible path to success, but circumstances are strongly against them.

Example:

A skilled climber attempting an extremely difficult route during bad weather.

Perhaps:

> 3% chance.

Still resolvable.

### Impossible

There is no plausible mechanism by which the character could achieve the objective.

Example:

A normal human jumping 100 meters vertically from standing.

Probability:

> 0%.

The difficulty curve is irrelevant.

---

# 8. The Engine Should Ask “How Could This Work?”

When considering a very low-probability action, the engine should internally ask:

> **If this succeeds, what plausible sequence of events causes success?**

If there is a coherent answer, resolution may remain appropriate.

If there is no coherent answer:

> automatic failure.

This is a useful safeguard against absurd long-shot outcomes.

---

# 9. Likewise, Ask “How Could This Fail?”

For extremely high-probability actions, ask:

> **What plausible mechanism could cause failure right now?**

If there is no meaningful answer:

> automatic success.

Example:

An elite shinobi ties their sandals.

What causes failure?

Practically nothing relevant.

No check.

But if their hand is trembling from poison:

Now there may actually be uncertainty.

---

# 10. Do Not Use Universal 5% Failure or Success Floors

We should explicitly reject rules like:

> Everything has at least a 5% chance of failure.

and:

> Everything has at least a 5% chance of success.

Those would undermine the entire capability system.

Some actions genuinely are:

> 100%.

Some genuinely are:

> 0%.

That's desirable.

---

# 11. Extreme Probability Is Not Automatically Automatic

A calculated 99% chance does not always mean the engine must skip the resolution.

Likewise, 1% does not automatically mean automatic failure.

The key question remains:

> **Is the alternative outcome still meaningfully plausible?**

Example:

A highly trained bomb technician with a 99% chance of correctly disarming a device may still face a genuine failure possibility if:

- the device is unstable,
- the mechanism is unfamiliar,
- a single mistake matters.

That 1% may deserve resolution.

By contrast:

> 99% chance to walk across a normal room

should probably just be automatic success because failure is not meaningfully plausible.

---

# 12. Stakes Do Not Determine Whether Failure Is Possible

High stakes should not force a check.

Example:

A character knows a password with certainty.

Entering it determines whether a bomb detonates.

Despite enormous stakes:

> no check.

They know the password.

Likewise, low stakes do not automatically suppress a check if the uncertainty itself matters.

The engine should resolve uncertainty, not drama.

---

# 13. Stakes Can Affect Whether Resolution Is Worth Showing

Even when a hidden probabilistic event occurs, not every trivial outcome needs player-facing narration.

For example:

A character performs dozens of routine minor actions during a workday.

The engine may simply summarize them.

So we should separate:

### Mechanical uncertainty
Does the event genuinely need resolution?

from

### Presentation importance
Does the player need to experience that resolution individually?

This matters enormously for the life-simulation side of the game.

---

# 14. Check Suppression

I think we should use the term **Check Suppression** for situations where the engine deliberately does not perform an individual resolution because it would add no meaningful simulation value.

A check should usually be suppressed when:

- success is effectively automatic,
- failure is effectively automatic,
- consequences are negligible,
- the action is routine and repeated,
- another broader resolution already covers it,
- the outcome has already been established.

This helps control simulation scope.

---

# 15. Repeated Routine Actions Should Be Aggregated

Suppose a character works at a ramen shop for eight hours.

The engine should not perform:

- cooking check #1,
- cooking check #2,
- cooking check #3,
- etc.

Instead, if the shift is routine:

> resolve the shift broadly.

Perhaps no check at all if nothing unusual happens.

If something meaningful changes:

- rush hour,
- difficult customer,
- broken equipment,
- special order,

then a relevant resolution may occur.

This will be crucial for keeping the life simulator playable.

---

# 16. Training Should Not Require a Roll for Every Repetition

Likewise, practicing:

> 100 shuriken throws

should not create 100 checks.

The training system should handle aggregated practice.

Resolution might become relevant when testing:

- a new difficulty,
- a breakthrough,
- a high-pressure application,
- a specific performance benchmark.

That prevents enormous unnecessary RNG volume.

---

# 17. Do Not Resolve Covered Sub-Actions Separately

Suppose the meaningful objective is:

> Sneak through the administrative wing.

The engine should not automatically roll separately for:

- every doorway,
- every hallway,
- every footstep.

Those are part of the larger resolved objective until something meaningfully changes.

A new check becomes appropriate when:

- a patrol unexpectedly arrives,
- the character enters a different security zone,
- the character changes tactics,
- conditions materially change.

This is one of the most important anti-bloat rules.

---

# 18. Established Facts Do Not Get Rechecked

If a previous resolution established:

> The character successfully secured the rope.

The engine should not randomly reroll whether the knot was tied properly every time the rope is referenced.

Unless something changes:

- rope damaged,
- knot tampered with,
- unexpected load applied.

Established world-state facts persist.

---

# 19. Knowledge Does Not Get Rerolled Without Cause

If a character successfully identifies a plant as medicinal, the engine should not later roll again and decide they suddenly misidentified the same specimen.

The result is established.

New uncertainty may arise from:

- a different specimen,
- degraded memory after a long period,
- contradictory evidence,
- similar species.

Again:

> resolution creates persistent facts.

---

# 20. Automatic Failure Should Not End Player Agency

If the player's chosen objective is impossible, the engine should not simply produce:

> You can't.

and stop.

It should resolve what **does** happen.

Example:

Player:

> I try to break the chakra barrier with my bare hands.

If that is impossible:

> The barrier doesn't yield; your strike disperses across its surface without producing meaningful damage.

The player has still acted.

The world may respond.

Automatic failure refers to the objective, not to the existence of consequences.

---

# 21. Impossible Attempts Can Still Reveal Information

Trying something impossible may teach the character something.

For example:

A character attacks a barrier.

They cannot break it.

But the attempt reveals:

- its strength,
- how it reacts,
- whether it absorbs chakra,
- perhaps its chakra nature.

So:

> **Automatic failure does not mean meaningless action.**

It simply means the declared objective cannot be achieved that way.

---

# 22. Impossible Attempts Can Still Cost Resources

Similarly, a character can spend:

- chakra,
- stamina,
- tools,
- time

attempting something impossible.

If the character does not know it is impossible, they may still try.

Example:

A genin repeatedly attacks an unknown seal.

The seal cannot be physically broken by their technique.

They may still waste chakra before realizing that.

The engine's knowledge and the character's knowledge remain separate.

---

# 23. Characters Should Recognize Obvious Automatic Outcomes

If a character has enough experience to know an action is trivial or impossible, the player should usually be told before committing.

Examples:

> You've done this hundreds of times; under these conditions, it poses no real challenge.

or:

> One look tells you that you are not physically capable of forcing that door open.

This preserves player agency.

The game should not repeatedly bait players into actions their character obviously knows cannot work.

---

# 24. But Hidden Information Can Conceal Impossibility

Sometimes the character doesn't know.

Example:

A normal-looking door is secretly protected by an S-rank barrier.

The player tries to open it.

The attempt automatically fails because of hidden circumstances.

That is legitimate.

The character learns something from the failure.

---

# 25. Automatic Success Can Still Consume Resources

A successful action being automatic does not make it free.

Example:

An elite shinobi can automatically perform a familiar jutsu under normal conditions.

It still consumes:

- chakra,
- time,
- perhaps physical effort.

Similarly, a medic can automatically complete a routine procedure but still uses:

- supplies,
- time.

Success probability and resource cost are separate.

---

# 26. Automatic Success Can Still Advance Time

Likewise, an automatic action may require:

- seconds,
- hours,
- days.

The engine should not confuse:

> automatic success

with:

> instantaneous.

Researching a well-understood document might be guaranteed but still take six hours.

This matters for simulation scheduling.

---

# 27. Automatic Actions Can Still Trigger World Reactions

Opening an unlocked door may be automatic.

But if there is someone watching:

> they may react.

Walking into a restricted building may require no physical check.

But it may create:

- suspicion,
- confrontation,
- legal consequences.

Resolution only concerns the attempted objective.

The world still responds normally.

---

# 28. Success May Be Automatic but Secrecy May Not Be

This distinction will be common.

Example:

> Open the unlocked window.

Automatic.

But:

> Open the unlocked window without making enough noise for the sleeping guard to hear.

Now there is uncertainty.

So the engine should identify the **actual compound objective**.

---

# 29. Automatic Completion Can Still Have Variable Quality

Some activities can be guaranteed to finish but uncertain in quality.

Example:

A competent craftsman can definitely produce:

> a usable kunai.

The question might be:

> How good is it?

In those cases, the check should resolve quality rather than completion.

That avoids fake failure while preserving meaningful skill differences.

---

# 30. Automatic Failure May Apply to Only Part of an Objective

Suppose the player attempts:

> Knock the elite jonin unconscious and grab the scroll.

Knocking them unconscious may currently be impossible.

But grabbing the scroll might not be.

The engine should avoid treating compound actions as indivisible when their components differ.

It can resolve:

> The strike doesn't meaningfully hurt him, but your attempt puts you close enough to reach for the scroll.

This makes interaction more dynamic.

---

# 31. Minimum Necessary Resolution

This should become a universal design rule:

> **Resolve only the minimum uncertainty necessary to determine the meaningful outcome.**

Don't resolve:

- things already known,
- things that cannot change,
- trivial intermediate motions,
- consequences already implied by another result.

This will be essential for running a persistent simulation efficiently.

---

# 32. Check Frequency Should Increase With Meaningful Uncertainty, Not Importance

A major story event may require no check.

Example:

The player chooses to resign from their job.

If nobody can stop them:

> automatic.

A mundane event may require resolution.

Example:

Trying to repair a malfunctioning appliance.

So:

> Narrative importance does not determine resolution frequency.

Simulation uncertainty does.

---

# 33. Automatic Outcomes Apply Equally to NPCs

NPCs should not secretly roll routine actions just because they are off-screen.

If an elite tracker follows an obvious trail with no meaningful interference:

> automatic success.

If an NPC attempts something impossible:

> automatic failure.

This helps off-screen world simulation remain consistent and computationally manageable.

---

# 34. Off-Screen Resolution Should Be More Aggressively Suppressed

For NPCs operating away from the player, the engine should generally resolve at a higher level of abstraction.

Example:

A chunin spends the day performing routine patrol duties.

We do not need dozens of individual checks.

If nothing unusual occurs:

> duty completed.

If a meaningful incident occurs:

then the appropriate uncertainty is resolved.

This will be extremely important once we simulate many persistent NPCs.

---

# 35. Very High Skill Should Expand the Automatic-Success Range

As characters improve, more tasks should move from:

> uncertain

to:

> automatic.

That's a core form of progression.

Likewise, extremely weak capability may expand the automatic-failure range for advanced tasks.

This gives stats tangible consequences beyond percentage improvements.

---

# 36. Mastery Should Be Especially Important for Check Suppression

Individual Mastery can make familiar actions extremely reliable.

Two shinobi may have similar broad Fire Release Skill.

But one has enormous mastery of Great Fireball.

For that specific technique, they may perform ordinary uses automatically under circumstances where the other shinobi still faces uncertainty.

This gives mastery a clear identity:

> **Skill expands capability broadly. Mastery expands reliability narrowly.**

I think that's a particularly useful distinction for Ruleset 1.

---

# 37. Skill Tiers Can Create Automatic-Failure Gates

The tier system from Ruleset 1 fits naturally here.

If a technique requires:

> Advanced Chakra Control Tier 2

and the character has:

> Basic Chakra Control Tier 4,

the issue is not necessarily "very low odds."

They may simply lack the necessary conceptual skill.

Automatic failure—or inability to meaningfully attempt—is appropriate until the prerequisite is obtained.

This prevents brute-forcing advanced systems with RNG.

---

# 38. Automatic Failure Should Not Always Permit Practice

Another important safeguard:

If someone lacks the conceptual foundation for an advanced technique, endlessly attempting the impossible should not automatically train them toward it.

They may need:

- instruction,
- prerequisite knowledge,
- observation,
- experimentation,
- another Skill tier.

Otherwise players could exploit impossible attempts for progression.

That belongs mainly in Ruleset 1, but Resolution should respect it.

---

# 39. Recommended Check-Suppression Procedure

Before every potential resolution:

### Step 1 — Define the exact objective.

### Step 2 — Check prerequisites and physical/logical possibility.

If impossible:

> **Automatic Failure.**

### Step 3 — Determine whether meaningful failure is possible.

If no:

> **Automatic Success.**

### Step 4 — Determine whether the uncertain component matters.

If no:

> suppress individual resolution and summarize.

### Step 5 — Determine whether another broader check already includes this action.

If yes:

> suppress redundant resolution.

### Step 6 — Determine whether the fact was already established.

If yes:

> use existing world state.

### Step 7 — Only then calculate probability.

This should substantially reduce unnecessary RNG.

---

# Example — Elite Medic

An elite medical-nin performs:

> routine wound cleaning.

No meaningful uncertainty.

**Automatic success.**

They perform:

> emergency surgery on a critically injured patient while the building is under attack.

Now:

- precision matters,
- time matters,
- circumstances are unstable.

**Resolution required.**

Same character, same broad domain.

Different circumstances.

---

# Example — Academy Student vs Boulder

The student attempts:

> lift a boulder weighing several tons.

No technique or ability makes that physically plausible.

**Automatic failure.**

But perhaps they instead attempt:

> roll the boulder downhill using leverage.

Now their objective and method have changed.

That might become possible.

The game should reward changing the problem.

---

# Example — Routine Mission Travel

A team walks three hours along a safe established road.

Do not roll:

> navigation, endurance, awareness, walking, coordination.

Simply advance the simulation.

If an ambush occurs:

> meaningful uncertainty 

---

## Turn 6fdddaf4-2fe5-49cb-b7b9-2905fb7e8241

### User

Okay

### Assistant — d7b95d3b-d48c-470d-943b-3a5f7a973f40

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.11 — Risk & Stakes

This section should define **what can happen when an uncertain action succeeds or fails**, independently from how difficult that action is.

The central rule should be:

> **Difficulty determines how likely success is. Stakes determine what success and failure mean.**

Those two ideas should never be collapsed into one number.

---

## 1. Difficulty and Stakes Are Separate Axes

An action can be:

- easy and low-stakes,
- easy and high-stakes,
- difficult and low-stakes,
- difficult and high-stakes.

Examples:

**Easy + Low Stakes**  
Jump across a small puddle.

**Easy + High Stakes**  
Enter a known password before a countdown reaches zero.

**Difficult + Low Stakes**  
Solve an advanced puzzle for practice.

**Difficult + High Stakes**  
Perform emergency surgery during severe blood loss.

The probability of success and the consequences of failure are related only when the actual circumstances make them related.

---

# 2. Stakes Describe Exposure

A useful way to define stakes is:

> **What is the character exposing to loss by attempting this action?**

Possible exposures include:

- time,
- chakra,
- stamina,
- health,
- equipment,
- money,
- reputation,
- relationships,
- secrecy,
- freedom,
- mission success,
- another person's safety,
- life.

An action may expose several things at once.

---

# 3. Stakes Should Be Derived From the World State

We should not assign stakes arbitrarily because something feels dramatic.

The engine should identify concrete consequences already supported by the situation.

Example:

Jumping between rooftops may expose:

- time,
- positioning,
- physical safety.

But if the gap is only one meter above the ground, death should not be treated as a plausible consequence.

The stakes come from:

- height,
- speed,
- surface,
- environment,
- available safeguards.

---

# 4. Proposed Stakes Scale

I think a broad internal scale would help the engine remain consistent.

### Trivial Stakes
Failure causes negligible inconvenience.

Examples:
- minor delay,
- cosmetic mistake,
- retry with almost no cost.

### Low Stakes
Failure creates a small but meaningful cost.

Examples:
- lose some time,
- waste minor supplies,
- mild embarrassment,
- minor fatigue.

### Moderate Stakes
Failure materially worsens the situation.

Examples:
- lose useful resources,
- create suspicion,
- suffer minor injury,
- miss an opportunity.

### High Stakes
Failure creates serious consequences.

Examples:
- major injury,
- mission compromise,
- capture risk,
- large resource loss,
- significant relationship damage.

### Severe Stakes
Failure may cause major long-term consequences.

Examples:
- permanent injury,
- imprisonment,
- critical mission failure,
- death of another person,
- severe political consequences.

### Critical Stakes
Failure may cause irreversible or lethal consequences.

Examples:
- death,
- permanent disability,
- destruction of something irreplaceable,
- village-scale catastrophe.

These should be descriptive bands, not direct numerical modifiers.

---

# 5. Stakes Do Not Modify Success Chance by Themselves

This should be a hard rule.

If an action is 70% likely to succeed, making the consequences more severe does not suddenly make it:

> 50%

or

> 90%.

High stakes may indirectly affect performance through:

- fear,
- pressure,
- urgency,
- hesitation.

But those must be modeled as actual character or situational effects.

The stakes themselves do not alter probability.

---

# 6. The Same Check Can Have Different Stakes

Suppose two identical beams are equally difficult to cross.

Beam A is:

> one meter above the ground.

Beam B is:

> fifty meters above the ground.

The physical balancing difficulty may be identical.

The stakes are radically different.

Failure on Beam A may mean:

> minor fall.

Failure on Beam B may mean:

> catastrophic injury or death.

This is exactly why difficulty and stakes need separate systems.

---

# 7. Risk Is Probability × Consequence

Conceptually, the engine should distinguish:

### Success Probability
How likely the objective is to succeed.

### Failure Severity
How bad failure can be.

### Overall Risk
The combination of those two.

A 95% success action can still be very risky if the 5% failure outcome is catastrophic.

Likewise, a 20% success action may be relatively harmless if failure only wastes time.

This distinction is crucial for NPC decision-making later.

---

# 8. Do Not Reduce Risk to One Visible Number

Even though we can conceptually think of risk as probability × consequence, I would avoid reducing it to a single score during gameplay.

For example:

> Risk: 72

doesn't tell the player much.

Better:

> The technique is difficult, but failure would only waste chakra.

or:

> You are confident you can make the jump, but a mistake would likely be fatal.

That gives the player the information that actually matters.

---

# 9. Consequence Categories

When resolving failure, the engine should identify which kinds of consequences are logically available.

A useful set:

- **Time**
- **Resource**
- **Physical**
- **Positional**
- **Informational**
- **Social**
- **Legal/Institutional**
- **Strategic**
- **Mission**
- **Environmental**

Not every action uses every category.

This helps prevent random punishment.

---

# 10. Time Consequences

Failure may cost:

- seconds,
- minutes,
- hours,
- days.

Examples:

A lockpick failure might:

> delay entry.

A research failure might:

> consume a day without useful progress.

Time becomes especially important when:

- deadlines exist,
- enemies are moving,
- missions have windows,
- characters have competing obligations.

This is one of the most useful non-combat stakes in a life simulator.

---

# 11. Resource Consequences

Failure may consume:

- chakra,
- stamina,
- ammunition,
- tools,
- medical supplies,
- money,
- food,
- rare materials.

Resource loss should match what the attempt actually uses.

For example:

A failed ninjutsu attempt may still consume chakra.

A failed negotiation should not randomly consume chakra.

Obvious, but worth formalizing.

---

# 12. Physical Consequences

Failure may cause:

- strain,
- minor injury,
- serious injury,
- permanent injury,
- death.

But physical consequences should only exist when the action creates physical exposure.

Failing to remember historical trivia cannot injure the character.

Failing to climb a cliff might.

---

# 13. Positional Consequences

Failure can worsen tactical position without directly causing injury.

Examples:

- exposed location,
- lost cover,
- pinned movement,
- separated from allies,
- lost line of sight,
- enemy gains initiative.

These consequences are especially useful because they create new gameplay rather than instantly ending the scene.

---

# 14. Informational Consequences

Failure may alter who knows what.

Examples:

- reveal your identity,
- alert guards,
- expose a plan,
- misinterpret evidence,
- miss important clues.

These can be extremely serious without involving physical harm.

For a shinobi simulation, information should be treated as a major resource.

---

# 15. Social Consequences

Failure may affect:

- trust,
- reputation,
- loyalty,
- suspicion,
- embarrassment,
- institutional standing.

But the degree must remain proportionate.

A failed casual joke should not destroy a lifelong friendship.

A failed attempt to manipulate someone during a crisis could have larger effects.

---

# 16. Strategic Consequences

Failure may change the broader situation.

Examples:

- enemy gets reinforcements,
- escape route closes,
- target relocates,
- mission timeline shifts,
- faction becomes alerted.

This is where individual checks can influence larger simulation state.

---

# 17. Immediate vs Delayed Consequences

Not all consequences happen immediately.

A failed stealth attempt might create:

> suspicion.

The guard may not confront the character immediately.

Later:

> security increases.

Similarly, poor medical treatment might appear successful at first but cause complications later.

So consequences should be able to be:

- immediate,
- delayed,
- conditional.

---

# 18. Visible vs Hidden Consequences

The player may not always know what consequence occurred.

Example:

A narrow stealth failure could cause:

> a guard notices something unusual.

The player may not know that suspicion increased.

Likewise, a social failure may quietly reduce trust.

This is fine as long as the consequence follows from the world state and is not retroactively invented.

---

# 19. Failure Severity Comes From Both Outcome Degree and Stakes

We can now connect this section to 2.5.

Outcome degree tells us:

> how badly the action was performed.

Stakes tell us:

> how much harm that poor performance could cause.

So:

**Severe Failure + Low Stakes**

may still only cause modest consequences.

Example:

Terribly fail a practice puzzle.

Result:

> no progress and wasted time.

But:

**Severe Failure + Critical Stakes**

may produce:

> major injury or death.

This relationship should be core to the system.

---

# 20. Narrow Failure Should Usually Trigger the Lower End of Consequences

If the failure is narrow, the engine should generally choose the mildest consequence consistent with the situation.

Example:

Jump fails narrowly:

> catch the ledge.

Stealth fails narrowly:

> someone hears something but does not identify you.

Negotiation fails narrowly:

> refusal, but relationship remains intact.

This gives outcome degree concrete meaning.

---

# 21. Severe Failure Should Expand Consequence Severity

A severe failure may produce more serious consequences within the available risk space.

Example:

Stealth failure:

- Narrow: guard becomes suspicious.
- Standard: guard sees you.
- Severe: guard identifies you and raises alarm.

Same action.

Different degree.

---

# 22. Catastrophic Consequences Require Both Exposure and Severity

A critical disaster should require all of these:

1. The situation contains a catastrophic hazard.
2. The character is exposed to that hazard.
3. The failure degree is sufficiently severe or the hazard itself is unforgiving.

Example:

Crossing a rope bridge above a canyon.

A major fall hazard exists.

If the character is secured by a safety line:

> catastrophic death may be removed from the outcome space.

If not:

> severe failure could plausibly become lethal.

---

# 23. Some Hazards Are Binary

Certain situations may have little room for degrees.

Example:

Cut the wrong wire:

> bomb detonates.

If the mechanism is genuinely binary, a narrow failure may still produce the full consequence.

We should not artificially soften every failure.

The simulation should reflect the actual mechanism.

This is important.

---

# 24. Recoverability

Stakes should also consider whether consequences can be reversed.

### Highly Recoverable
Retry, minor delay, replaceable resource.

### Recoverable
Requires effort, treatment, repair, or apology.

### Difficult to Recover
Major cost or long-term consequence.

### Irreversible
Death, permanent loss, destroyed unique item.

Two failures with identical severity can feel very different depending on recoverability.

---

# 25. Safeguards Reduce Stakes

Preparation can lower stakes without increasing success probability.

Examples:

- safety rope,
- backup medic,
- protective equipment,
- escape route,
- containment seal.

This is an important strategic option.

The player may decide:

> I cannot make this easier, but I can make failure less dangerous.

That creates a useful risk-management gameplay loop.

---

# 26. Insurance and Redundancy

Some actions can have fallback systems.

Example:

Primary seal fails.

Backup containment activates.

The action still failed, but the worst consequence is prevented.

This allows players and NPCs to invest in:

- redundancies,
- backups,
- contingency plans.

That should be mechanically meaningful.

---

# 27. Risk Can Be Transferred

Characters may intentionally shift consequences.

Examples:

- use a clone to scout instead of going personally,
- send a sensor ahead,
- use expendable tools,
- fight from cover,
- delegate dangerous work.

This does not necessarily make the objective easier.

It changes **who or what is exposed to failure**.

That is a powerful strategic mechanic.

---

# 28. Risk Can Be Accepted Deliberately

The player may choose to increase exposure for a better opportunity.

Examples:

- spend more chakra,
- close distance,
- abandon cover,
- attempt a faster route,
- use an unstable technique.

This should not automatically improve success.

The tradeoff must be causal.

For example:

> using more chakra may increase technique capability but worsen exhaustion if it fails.

This creates real decision-making.

---

# 29. Risk and Reward Should Not Be Artificially Balanced

We should avoid gamey logic like:

> higher risk always gives higher reward.

Sometimes risky actions are just bad choices.

Sometimes safe actions are simply better.

The world does not owe the player a balanced reward for taking a dangerous option.

The reward must come from the actual situation.

---

# 30. Desperation Can Make Bad Odds Rational

An action can be both:

- unlikely,
- extremely dangerous,

and still be rational if the alternatives are worse.

Example:

Jumping across a huge gap may be terrible.

But if an enemy will kill you otherwise:

> the jump may be the best available option.

NPCs should later evaluate risk relative to alternatives, not in isolation.

---

# 31. Characters Need Different Risk Tolerance

Risk tolerance should depend on:

- personality,
- goals,
- duty,
- desperation,
- confidence,
- relationships,
- ideology.

A reckless character may accept severe risk.

A cautious one may avoid it.

A parent may accept enormous personal risk to protect a child.

This belongs mostly in NPC decision-making, but the stakes system needs to support it.

---

# 32. Perceived Risk Can Differ From Actual Risk

Just like perceived probability, perceived consequences can be wrong.

A character may think:

> Failure only means being discovered.

But secretly:

> the area is trapped.

Actual stakes are higher than perceived stakes.

The engine should use actual consequences.

The character should make decisions based on what they know.

---

# 33. Risk Communication to the Player

When the character can reasonably judge the danger, the player should be told.

Good examples:

> The climb itself looks manageable, but there is nothing below you that would stop a fall.

> You think you can force the door, though doing so will almost certainly alert anyone nearby.

> The procedure is within your ability, but the patient's condition leaves very little room for error.

This is much better than:

> HIGH RISK.

---

# 34. The Engine Should Distinguish Known and Unknown Risks

A useful internal model:

**Known Risk**
Character understands it.

**Suspected Risk**
Character has reason to believe it may exist.

**Hidden Risk**
Exists but is not currently known.

The player should only receive information supported by the character's knowledge.

---

# 35. High Stakes Should Encourage Safeguards, Not Invisible Difficulty Inflation

If a task is dangerous, the player should be able to respond with:

- preparation,
- contingencies,
- better equipment,
- backup plans.

The game should not secretly raise Difficulty because the scene matters.

This keeps strategy meaningful.

---

# 36. Some Consequences Should Require Follow-Up Resolution

A failure can create a new uncertain situation.

Example:

You fall from the roof.

That does not necessarily mean:

> immediate injury result.

It may create:

> Can you grab the ledge?

if that is a distinct meaningful opportunity.

But we should avoid excessive "saving throw chains."

Only create follow-up resolution when:

- there is a genuine new objective,
- the character can meaningfully act,
- the new uncertainty matters.

---

# 37. Avoid Infinite Failure Cascades

One failed check should not automatically produce:

> failure → check → failure → check → failure → check

until the character is destroyed.

The engine should usually resolve a consequence at the appropriate scale.

Example:

A severe climbing failure may simply establish:

> you fall and suffer injury.

No need to resolve every meter of the fall.

This follows our minimum-necessary-resolution rule.

---

# 38. Death Should Never Be a Generic Failure Result

Death should occur only when:

- lethal hazard exists,
- the character is meaningfully exposed,
- protective systems fail or do not exist,
- the result supports lethal severity.

This prevents accidental deaths from mundane checks.

But it also preserves genuine lethality where appropriate.

---

# 39. Critical Stakes Should Be Telegraphable When Knowable

If a character would obviously know:

> this can kill you,

the player should know too.

The engine should not hide obvious lethal risk simply to surprise the player.

Hidden lethal dangers are fine when the danger itself is legitimately hidden.

---

# 40. Risk Can Accumulate

Repeated exposure may create rising stakes.

Example:

Each use of an unstable technique:

- increases strain,
- worsens injury,
- raises failure consequences.

Similarly, prolonged infiltration may increase:

- suspicion,
- fatigue,
- time pressure.

The risk profile should evolve with world state.

---

# 41. Risk Can Decrease Through Success

Success may reduce later stakes.

Example:

Disabling an alarm:

> lowers consequences of later stealth failure.

Stabilizing a patient:

> reduces urgency.

Securing a retreat route:

> lowers capture risk.

This makes earlier actions strategically valuable.

---

# 42. Stakes Can Be Multi-Target

An action may expose more than the actor.

Example:

A squad leader orders an assault.

Failure may threaten:

- themselves,
- teammates,
- civilians,
- mission objective.

This can heavily influence NPC behavior and ethical choices without changing the probability formula.

---

# 43. Player Choice Should Sometimes Explicitly Define Stakes

Some choices naturally represent risk selection.

Example:

**Safe approach**
Slower, lower exposure.

**Aggressive approach**
Faster, higher exposure.

**Desperate approach**
Maximum risk.

These should not be arbitrary UI modes.

They should correspond to actual methods the character can take.

---

# 44. Proposed Risk Evaluation Procedure

For every meaningful uncertain action:

### Step 1 — Identify the intended objective.

### Step 2 — Identify what is exposed to failure.

Health? Time? Chakra? Secrecy? Reputation?

### Step 3 — Identify available consequences.

Only those causally supported by the situation.

### Step 4 — Establish maximum plausible severity.

What is the worst realistic consequence?

### Step 5 — Identify safeguards.

What reduces or prevents consequences?

### Step 6 — Determine recoverability.

How reversible would failure be?

### Step 7 — Resolve the action normally.

Difficulty determines success probability.

### Step 8 — Use outcome degree to select consequence severity.

### Step 9 — Apply persistent world-state changes.

That keeps risk evaluation separate from the actual success calculation.

---

# Example — Dangerous Jump

Character has:

> 75% chance to clear the gap.

### Version A
Gap is three feet above the ground.

Failure consequences:

- fall,
- minor injury,
- lost time.

Overall risk:

> moderate at most.

### Version B
Gap is between skyscrapers.

Same success probability.

Failure consequences:

- severe injury or death.

Overall risk:

> critical.

Nothing about the jump's probability needs to change.

---

# Example — Experimental Jutsu

Character has a reasonable chance to perform the technique.

Without containment:

Failure may cause:

- chakra backlash,
- injury,
- structural damage.

With containment seals:

Success probability might remain identical.

But failure may become:

- techniq

---

## Turn 81fa9c96-4d7a-4a3d-a810-f6ae18e7b094

### User

Ok

### Assistant — c168abdc-d454-4a58-b7af-f6a8e0e04b65

# Ruleset 2.12 — Repeated Attempts

Repeated attempts need their own rules because otherwise any action with a nonzero success chance eventually becomes trivial.

The central rule should be:

> **A failed attempt does not automatically create a fresh, identical chance to succeed.**

A retry should only be meaningfully different if something about the situation, knowledge, resources, time, or character state changes.

---

## 1. First Question: Can the Action Be Retried?

After failure, the engine should determine whether another attempt is actually possible.

### Freely Repeatable
The character can try again with little change.

Example:
- throwing darts at a stationary target during practice.

### Repeatable With Cost
Another attempt is possible, but consumes:
- time,
- chakra,
- stamina,
- tools,
- money,
- secrecy.

### Repeatable Only After Change
The same approach cannot reasonably produce a new result until circumstances change.

Example:
- failing to decode a cipher because the character lacks the necessary knowledge.

### One-Shot
Failure removes the opportunity.

Example:
- missing a fleeting interception opportunity,
- failing to catch a falling object before it is gone.

These distinctions should be determined before allowing a retry.

---

# 2. Do Not Allow “Roll Until Success”

If nothing meaningful changes, the engine should not repeatedly generate fresh checks until the character eventually succeeds.

That creates fake progression and makes probability meaningless.

Instead, an unchanged repeated action should usually produce one of these outcomes:

- the original result remains authoritative,
- the activity becomes an extended check,
- additional attempts incur escalating costs,
- no new check occurs until circumstances change.

---

# 3. Some Failures Establish a Fact

Suppose a character searches a room thoroughly and fails to find a hidden compartment.

If they immediately say:

> I search again.

That should not automatically create a new independent chance.

The previous resolution already established:

> Under this method and current conditions, they did not detect it.

A new attempt becomes meaningful only if something changes, such as:

- more time,
- better lighting,
- another person helping,
- new information,
- a different search technique.

This prevents metagaming.

---

# 4. Failure Can Reveal Why the Attempt Failed

A failed attempt may provide information.

Examples:

- the lock is more complex than expected,
- the seal reacts to Fire Release,
- the patient is not responding to the treatment,
- the target anticipated the deception.

That information can justify a new approach.

So repeated attempts can naturally become:

> attempt → feedback → adaptation → new attempt.

That is much more interesting than rerolling.

---

# 5. Identical Repetition Should Usually Not Improve Probability

If a character:

- uses the same method,
- under the same conditions,
- with the same knowledge,

their underlying probability should not magically increase.

There is no hidden:

> +10% because you already failed once.

Improvement requires a causal reason.

---

# 6. Repetition Can Improve Performance Through Learning

However, genuine practice can improve future attempts.

This should happen through the progression system, not an ad hoc retry bonus.

For example:

A student practices tree walking repeatedly.

They fail several times.

Over time they gain:

- Chakra Control XP,
- technique familiarity,
- individual mastery.

Eventually the underlying Effective Capability rises.

Now later attempts genuinely become easier.

That is real progression.

---

# 7. Learning Should Not Be Instant

A failed attempt should not normally produce a large immediate capability increase.

Improvement depends on:

- challenge level,
- feedback quality,
- instruction,
- repetition,
- reflection,
- rest.

This belongs partly in Ruleset 1, but Resolution should avoid granting arbitrary retry bonuses.

---

# 8. Time Can Make a Retry Meaningfully Different

Taking additional time may justify another attempt.

Example:

A rushed lockpick attempt fails.

The character now spends ten minutes examining the lock.

That changes:

- information,
- precision,
- time pressure.

This is now a meaningfully different attempt.

---

# 9. Resources Can Make a Retry Different

A character may use:

- more chakra,
- better tools,
- medicine,
- specialized equipment.

Example:

Initial attempt:

> force the door manually.

Fails.

Second attempt:

> use an explosive tag.

That is not a reroll.

It is a new method with different:

- capability,
- difficulty,
- stakes,
- consequences.

---

# 10. Assistance Can Enable a Retry

Another character may provide:

- expertise,
- physical help,
- information,
- equipment.

A failed solo attempt may become viable with assistance.

Example:

One shinobi cannot move debris alone.

A teammate helps.

Now the effective situation has changed.

---

# 11. Failure Can Make Later Attempts Harder

Retries should not always become easier.

Failure may worsen conditions.

Examples:

- lockpick breaks inside the lock,
- target becomes suspicious,
- enemy increases security,
- patient loses more blood,
- chakra reserves drop.

The next attempt may therefore have:

- higher Difficulty,
- lower Capability,
- greater stakes,
- fewer options.

This is especially important for high-pressure situations.

---

# 12. Repeated Attempts Can Escalate Risk

Even when success chance remains similar, consequences can worsen.

Example:

Repeatedly probing an unstable seal may:

- increase chakra instability,
- raise backlash risk.

Repeatedly lying to someone may:

- increase suspicion,
- make discovery consequences worse.

So retries should modify world state where appropriate.

---

# 13. Some Attempts Consume the Opportunity

Certain failures permanently close the path.

Examples:

- bridge collapses,
- target leaves,
- evidence is destroyed,
- auction ends,
- enemy realizes the ambush.

In those cases:

> no retry is available unless a new opportunity emerges.

This makes timing matter.

---

# 14. Some Attempts Can Be Retried Indefinitely but Should Be Aggregated

Practice activities are the obvious example.

Instead of:

> roll 500 shuriken throws,

the simulation should aggregate them into a training block.

Likewise:

- studying,
- crafting practice,
- exercise,
- repetitive labor.

The system should model:

- time,
- fatigue,
- progress,
- learning,

rather than hundreds of independent success checks.

---

# 15. Repeated Technical Work Should Often Become Extended Resolution

Suppose a researcher is attempting to develop a new jutsu.

That should not be:

> 15% chance each day until success.

Instead, it should use an extended-progress system involving:

- cumulative progress,
- setbacks,
- breakthroughs,
- resources,
- research quality.

This will be formalized in the later Extended Checks section.

---

# 16. Each Retry Should Ask: “What Changed?”

This should be the engine's primary retry test.

Before generating another check:

> **What changed since the last attempt?**

Possible valid answers:

- time,
- knowledge,
- method,
- equipment,
- assistance,
- character condition,
- environment,
- opponent condition.

If the answer is:

> nothing,

then a fresh roll is usually unjustified.

---

# 17. The Player Can Explicitly Change Approach

This should be encouraged.

Example:

First attempt:

> Sneak past the guard.

Failure creates suspicion.

Instead of:

> try again,

the player might:

- distract them,
- disguise themselves,
- climb around the building,
- wait for shift change.

Each is a new resolution because the situation or method changed.

This supports creativity.

---

# 18. NPCs Should Adapt Too

NPCs should not allow infinite retry loops.

If someone repeatedly attempts to deceive a guard, the guard may become:

- suspicious,
- hostile,
- unwilling to continue talking.

If someone repeatedly attacks the same defense, the defender may:

- adapt,
- counter,
- reposition.

This prevents static exploitation.

---

# 19. Retry Frequency Depends on Task Type

Different domains should naturally behave differently.

### Athletics
Can often be retried quickly, but fatigue accumulates.

### Social
Repeated persuasion may quickly become annoying or suspicious.

### Stealth
Failure may immediately remove the possibility of another stealth attempt.

### Medicine
Repeated failed interventions can worsen the patient.

### Research
Repeated attempts are expected and often part of the process.

### Crafting
Retry may require replacement materials.

The system should be domain-sensitive.

---

# 20. Repeated Failure Can Establish Practical Impossibility

Suppose someone attempts several materially different approaches and none work.

At some point, the engine may reasonably establish:

> current tools and capabilities are insufficient.

The player may need:

- training,
- a specialist,
- new equipment,
- different information.

This prevents endless micro-variation from bypassing real limitations.

---

# 21. Do Not Punish Experimentation

At the same time, the system should not discourage reasonable experimentation.

If the character has legitimate reason to believe a different approach might work, they should be allowed to try it.

The distinction is:

> **new approach**

versus

> **same action until RNG cooperates.**

That boundary should stay clear.

---

# 22. Retry Costs Should Be Causal

Do not invent arbitrary penalties like:

> −5 because this is your second attempt.

If a retry is worse, there should be a reason.

Examples:

- fatigue,
- damaged tool,
- heightened suspicion,
- lost time.

Likewise, if it improves, there should be a reason.

---

# 23. Repeated Social Attempts Need Strong Safeguards

Social systems are especially vulnerable to retry abuse.

A character should not be able to say:

> persuade again  
> persuade again  
> persuade again

until someone agrees.

Each failed attempt can change the relationship or willingness to engage.

Possible consequences:

- irritation,
- suspicion,
- refusal to discuss further,
- reduced trust.

Further attempts may require:

- new evidence,
- changed incentives,
- time passing,
- improved relationship.

---

# 24. Repeated Information Checks Should Not Fish for Hidden Facts

This is another important safeguard.

If a player asks:

> Do I notice anything?

and fails a hidden perception check, asking repeatedly should not create endless new rolls.

The character already observed the situation as best they could under current conditions.

A new check requires:

- moving closer,
- taking more time,
- changing lighting,
- using a sensory technique.

This protects hidden information.

---

# 25. Repeated Combat Attempts Are Naturally Different

In combat, repeated attacks can still be valid because the state changes constantly.

Each exchange may alter:

- position,
- fatigue,
- injuries,
- timing,
- opponent actions.

So:

> punch again

is not necessarily an identical retry.

It occurs in a different tactical state.

Combat rules will handle that later.

---

# 26. Cooldowns and Recovery Can Gate Retries

Certain abilities may require:

- chakra recovery,
- physical reset,
- technique cooldown,
- equipment reset.

So an action might be retryable only after a specified condition.

This is not probability manipulation.

It is an ability constraint.

---

# 27. Failure Can Create Mastery Without Success

This is important for progression.

A failed attempt can still contribute useful experience if:

- the character understood what went wrong,
- the task was within learning range,
- the attempt produced meaningful feedback.

This lets characters learn from failure.

But:

> blindly repeating impossible actions

should not produce infinite progression.

---

# 28. Challenge Level Should Matter for Learning

Repeated trivial success should provide little progression.

Repeated impossible failure should also provide little progression.

The best growth should come from:

> difficult but meaningful practice near the character's current developmental edge.

This will connect directly back into Ruleset 1.

---

# 29. Diminishing Learning Returns

Repeatedly practicing the exact same simple application should eventually produce diminishing returns.

A character should need:

- greater difficulty,
- new conditions,
- more advanced techniques,

to continue growing efficiently.

This prevents training exploits.

---

# 30. Repeated Attempts Can Become Automatic

As mastery improves, a previously uncertain action may become routine.

Example:

Early training:
- many tree-walking failures.

Later:
- mostly reliable.

Eventually:
- automatic under normal conditions.

This provides a satisfying progression loop.

---

# 31. Failure Memory Should Persist

The engine should remember relevant prior attempts when they affect later decisions.

Examples:

- this lock resisted your previous tools,
- this NPC already rejected the proposal,
- this route proved unstable,
- this jutsu caused severe chakra backlash.

The world should not reset between attempts.

---

# 32. Characters Should Learn From Their Own Experience

The player should sometimes receive better estimates after failure.

Before:

> You're not sure how difficult this seal is.

After attempting it:

> You now realize the chakra structure is far more advanced than you expected.

This is useful feedback without exposing raw numbers.

---

# 33. Repeated Attempts Under Safe Conditions Can Be Abstracted to Eventual Success

Sometimes success is effectively guaranteed given enough time and no meaningful cost.

Example:

A skilled character searches an empty room with unlimited time.

If there is nothing preventing discovery and the object is reasonably findable, eventually:

> success may be automatic.

The meaningful variable becomes:

> how long it takes.

In such cases, resolve **time-to-completion** rather than repeated pass/fail checks.

---

# 34. “Take 10 / Take 20” Style Logic Without Gamey Labels

We can support the same concept organically.

If the character has:

- plenty of time,
- no meaningful pressure,
- no penalty for repeated attempts,

the engine can assume careful repetition and determine the eventual outcome.

No need to simulate individual attempts.

This is especially useful for:

- searching,
- basic crafting,
- routine repairs,
- studying.

---

# 35. Retry Decisions Should Be Informed by Character Knowledge

If the character knows:

> trying again the same way is pointless,

the player should usually be told.

Example:

> You are confident additional force will not break the barrier.

This prevents frustrating trial-and-error.

If the character does not know, experimentation may remain reasonable.

---

# 36. Desperation Can Justify Repeating a Poor Approach

Sometimes characters may repeat an action even knowing the odds are bad.

Example:

A trapped shinobi continues trying to lift debris because no alternative exists.

The engine should allow that.

But it should still model:

- fatigue,
- injury,
- time,
- diminishing capability.

This maintains agency without granting free rerolls.

---

# 37. Recommended Retry Procedure

After a failed action:

### Step 1 — Did failure consume the opportunity?

If yes:
> no retry.

### Step 2 — Can the action physically/logically be repeated?

If no:
> no retry.

### Step 3 — Has anything meaningful changed?

If yes:
> recalculate and resolve again.

### Step 4 — If nothing changed, is repeated effort itself capable of producing progress?

If yes:
> convert to aggregated or extended resolution.

### Step 5 — If not:
> retain the established result.

### Step 6 — Apply any causal costs or worsening conditions before the next attempt.

This should be the standard retry logic.

---

# Example — Lockpicking

Initial attempt fails.

The character immediately retries with the same pick and same approach.

Nothing changed.

> No fresh independent roll.

Instead, the prior failure remains meaningful.

Now they:

- examine the mechanism,
- switch tools,
- take more time.

The situation has changed.

> New resolution is justified.

---

# Example — Strength Attempt

A shinobi tries to lift debris.

Fails.

They immediately try again.

If nothing changes:

> same practical outcome.

But if:

- a teammate helps,
- they use chakra enhancement,
- they reposition for leverage,

then:

> new attempt.

---

# Example — Persuasion

NPC refuses a request.

Player repeats the same argument.

No new roll.

The NPC already heard it.

If the player instead provides:

- evidence,
- incentive,
- new information,

then the social state has changed and another attempt may be appropriate.

---

# What I Would Lock In

> **Retries require a meaningful reason to produce a new outcome.**

> **Identical conditions do not grant fresh independent rolls.**

> **Every retry should answer the question: “What changed?”**

> **Failure can provide information that enables better future approaches.**

> **Repeated effort that genuinely accumulates progress should become aggregated or extended resolution rather than roll spam.**

> **Retry costs and benefits must come from actual world-state changes.**

> **Failures may make later attempts harder as well as easier.**

> **Social, perception, and hidden-information checks should be especially resistant to repeated fishing.**

> **Practice improves future attempts through progression, not hidden retry bonuses.**

> **Trivial repetition, impossible repetition, and rote repetition should provide diminishing or negligible learning.**

> **Given enough time and no meaningful risk, some repeatable tasks should shift from success/failure resolution to time-to-completion resolution.**

Next should be **Ruleset 2.13 — Extended & Complex Checks**. That will let us handle activities like **researching new jutsu, long-term tracking, surgery, infiltration operations, crafting, investigations, negotiations, and multi-day projects** without reducing them to either one roll or dozens of repetitive rolls.

---

## Turn c24dbf80-2174-404e-965f-006f0fcd76c6

### User

Ok

### Assistant — c58e6d35-38e8-4797-8b76-eaf58b212f6c

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.13 — Extended & Complex Checks

Extended checks are for objectives that are too large, too layered, or too time-consuming to resolve with a single success/failure event.

The central rule should be:

> **Use extended resolution when progress can accumulate meaningfully over time and intermediate results matter.**

This includes things like:

- developing a jutsu,
- researching a mystery,
- performing a long medical procedure,
- infiltrating a secure compound,
- tracking someone across several days,
- negotiating a political agreement,
- crafting a specialized item,
- training toward a breakthrough.

---

## 1. Extended Checks Should Track Progress, Not Repeated Successes

The biggest mistake would be:

> Roll once per day until you get five successes.

That is still just retry spam with extra steps.

Instead, an extended task should have a persistent **Progress State**.

Conceptually:

> **0% → 100% completion**

or an equivalent internal progress value.

Each meaningful work period can:

- advance progress,
- make little progress,
- create a breakthrough,
- cause a setback,
- reveal new information,
- change the task itself.

---

# 2. Extended Tasks Need a Defined Objective

Before progress begins, the engine should know exactly what completion means.

Bad:

> Research Fire Release.

Too broad.

Better:

> Develop a lower-chakra-cost variant of Great Fireball that can be reliably used with one fewer hand seal.

That gives the system something concrete to measure.

Likewise:

> Investigate the disappearance.

should eventually become specific questions such as:

- who was involved,
- where the missing person went,
- why they disappeared.

---

# 3. Progress and Difficulty Are Different

An extended task should have at least two separate properties:

### Total Scope
How much work is required.

### Difficulty
How demanding the work is.

A task can be:

**Easy but large**
- compiling years of routine records.

or:

**Small but extremely difficult**
- deciphering one highly advanced seal.

This distinction is essential.

---

# 4. Scope Determines How Much Progress Is Needed

We could internally represent scope with a progress target.

For example:

- Minor project: 100 progress
- Moderate project: 250
- Major project: 500
- Large project: 1,000
- Exceptional project: 2,000+

The exact values can remain hidden.

What matters is that:

> **large projects require more cumulative work, not necessarily higher Difficulty.**

This is especially useful for incremental gameplay.

---

# 5. Each Work Cycle Generates Progress

A work cycle might represent:

- one action,
- one hour,
- one training session,
- one day,
- one mission phase.

The appropriate scale depends on the activity.

Each cycle can generate progress based on:

- Effective Capability,
- Difficulty,
- available time,
- resources,
- prior knowledge,
- assistance,
- current conditions.

A strong result creates more progress.

A weak result creates less.

A failure may create little or no progress.

A severe failure may cause setbacks.

---

# 6. Progress Should Usually Be Continuous

Instead of:

> Success = +1 point  
> Failure = +0

I think progress should be more granular.

For example:

- Exceptional Success → major progress
- Strong Success → high progress
- Standard Success → normal progress
- Narrow Success → limited progress
- Narrow Failure → very limited progress or useful information
- Standard Failure → no progress
- Severe Failure → setback

This gives degrees of outcome real value.

---

# 7. Failure Can Still Produce Progress

This is especially appropriate for:

- research,
- experimentation,
- training,
- investigation.

A failed experiment may still teach the character:

> which approach does not work.

A failed investigation may eliminate a suspect.

A failed training session may expose a weakness.

So failure should sometimes produce:

- knowledge,
- reduced uncertainty,
- partial progress.

But not automatically.

The task must support learning from failure.

---

# 8. Setbacks Should Be Specific

A severe failure should not simply mean:

> −20 progress.

Whenever possible, setbacks should have actual consequences.

Examples:

- damaged equipment,
- lost research notes,
- injured participant,
- incorrect hypothesis,
- compromised secrecy,
- wasted materials,
- increased suspicion.

Those consequences may indirectly reduce future progress.

This is better than abstract punishment.

---

# 9. Milestones

Larger extended tasks should have milestones.

Example: developing a new jutsu.

### Milestone 1
Understand theoretical mechanism.

### Milestone 2
Produce unstable prototype.

### Milestone 3
Perform controlled version.

### Milestone 4
Reduce chakra waste.

### Milestone 5
Achieve combat-ready reliability.

This makes long-term projects feel like actual development rather than filling a bar.

---

# 10. Milestones Can Unlock New Actions

Completing a milestone may:

- reveal new choices,
- change Difficulty,
- unlock training,
- allow field testing,
- expose previously unknown problems.

For example:

Before producing a prototype, combat testing is impossible.

Afterward:

> testing becomes available.

This creates natural project progression.

---

# 11. Difficulty Can Change Across Milestones

An extended task should not necessarily have one fixed Difficulty.

Example:

Developing a jutsu might involve:

**Theory:** Difficulty 60  
**Initial prototype:** 70  
**Basic stabilization:** 65  
**Optimization:** 80

Different stages demand different capabilities.

This makes specialization matter.

---

# 12. Different Skills Can Apply to Different Phases

A complex task can involve multiple Skills without averaging them into one number.

Example: surgery.

Potential phases:

- diagnosis,
- preparation,
- surgical execution,
- chakra stabilization,
- postoperative monitoring.

Each may use different combinations of:

- Medicine,
- Chakra Control,
- Perception,
- Intelligence,
- technique mastery.

This is more realistic than one universal "Medicine check."

---

# 13. Extended Checks Should Not Become Excessively Granular

We need an anti-bloat rule.

Not every phase needs its own check.

Only resolve a phase separately when:

- it has distinct uncertainty,
- failure meaningfully changes the task,
- different capabilities matter,
- player decisions exist.

Otherwise aggregate it.

This maintains pacing.

---

# 14. Player Decisions Should Matter During Extended Tasks

The player should occasionally choose:

- safer vs faster approach,
- which hypothesis to test,
- which resources to spend,
- whether to continue after setbacks,
- whether to seek help,
- whether to field-test early.

Extended resolution should therefore create **decision points**, not just progress notifications.

---

# 15. Time Investment

Time should directly matter.

A character working:

> eight focused hours

should generally make more progress than:

> thirty minutes.

But progress should not necessarily scale perfectly linearly.

Fatigue, concentration, and diminishing productivity matter.

So:

> doubling time does not always double progress.

---

# 16. Diminishing Returns Within a Session

Very long sessions may become less efficient.

For example:

Hours 1–4:
> high productivity.

Hours 5–8:
> moderate productivity.

Hours 9–12:
> poor productivity and higher error risk.

This creates reasons to:

- rest,
- schedule work,
- manage fatigue.

That fits a life simulator very well.

---

# 17. Resource Requirements

Extended tasks may consume:

- money,
- chakra,
- materials,
- tools,
- laboratory space,
- books,
- medicine,
- access to specialists.

Resources may affect:

- whether work can continue,
- efficiency,
- available methods,
- risk.

This gives the broader economy and inventory systems relevance.

---

# 18. Missing Resources Can Change the Task

If a necessary resource is absent, the task should not always just get:

> +10 Difficulty.

Sometimes:

> work cannot continue.

Other times:

> an inferior method becomes necessary.

Example:

No proper laboratory equipment.

The character may still experiment, but:

- progress slows,
- risk increases,
- certain milestones become unavailable.

---

# 19. Research Should Generate Knowledge States

Investigation and research should produce persistent knowledge, not just progress.

Example:

Researching an unknown poison might gradually establish:

- likely composition,
- symptoms,
- transmission method,
- possible antidotes.

Each fact becomes part of world state.

This allows future checks to benefit naturally from prior work.

---

# 20. False Leads

Some complex tasks should allow characters to pursue incorrect assumptions.

Especially:

- investigation,
- research,
- intelligence analysis.

A poor result may produce:

> misleading interpretation.

But this should be grounded in available evidence.

The engine should not invent nonsense just to punish failure.

---

# 21. Verification Matters

Important discoveries may need verification before becoming highly reliable.

For example:

One experiment suggests:

> Compound A neutralizes the poison.

Repeated testing may establish:

> reliable antidote.

So knowledge can have confidence levels such as:

- hypothesis,
- tentative,
- supported,
- confirmed.

This fits the hidden-information system nicely.

---

# 22. Collaboration

Multiple characters can contribute to an extended project.

Different people may handle different roles.

Example:

One shinobi provides:

- fuinjutsu expertise.

Another:

- medical knowledge.

Another:

- laboratory assistance.

Rather than combining stats directly, teamwork should allow:

- parallel work,
- specialist contributions,
- reduced bottlenecks.

We will formalize that in the Teamwork section.

---

# 23. Bottlenecks

Some projects may be limited by their weakest required component.

Example:

A sealing project requires:

- theory,
- chakra control,
- rare material.

Even exceptional theoretical skill cannot finish the project if the material is unavailable.

So extended projects should support **bottlenecks**.

This prevents one huge stat from solving everything.

---

# 24. Parallel Progress

Some parts of a project can occur simultaneously.

Example:

While one team member:

> gathers materials,

another:

> conducts research.

This should reduce total calendar time without necessarily reducing total work.

Important distinction:

> **work required ≠ elapsed time required.**

---

# 25. Dependencies

Some tasks require milestones in order.

Example:

Cannot perform clinical testing before:

> prototype antidote exists.

Dependencies should prevent nonsensical shortcuts.

This also supports future project-management-like simulation.

---

# 26. Interruptions

Extended tasks may be interrupted by:

- missions,
- injury,
- equipment loss,
- emergencies,
- relocation.

Progress should usually persist unless the nature of the project makes deterioration plausible.

Example:

Research notes persist.

A half-finished unstable chemical preparation might not.

---

# 27. Progress Decay

Some projects can lose progress over time.

Examples:

- maintaining a surveillance operation,
- negotiating temporary political support,
- unstable experiments,
- physical conditioning.

Others should not.

Example:

Learning a historical fact does not disappear after two days.

So progress decay must be specific to the type of state being tracked.

---

# 28. Maintenance vs Completion

Some extended activities never truly "finish."

Examples:

- maintaining fitness,
- maintaining political relationships,
- ongoing surveillance,
- keeping a barrier active.

These should use persistent state rather than completion bars.

This prevents us from forcing everything into the same project structure.

---

# 29. Complex Infiltration

An infiltration is a good example of a **complex but relatively short** extended task.

It might track:

- location,
- alert level,
- cover identity,
- suspicion,
- objective progress.

Instead of one:

> Infiltration check.

or twenty tiny checks.

Meaningful phases might be:

1. gain access,
2. move through secure area,
3. achieve objective,
4. extract.

Each phase only resolves if meaningful uncertainty exists.

---

# 30. Complex Tracking

Long-distance tracking might track:

- trail quality,
- distance to target,
- time delay,
- environmental degradation,
- tracker fatigue.

Strong results may:

> close distance.

Weak results may:

> maintain trail but lose time.

Failure may:

> lose the trail.

A new investigation might then be required to reacquire it.

This is much richer than repeated Tracking rolls.

---

# 31. Complex Negotiations

Long negotiations might track:

- trust,
- concessions,
- unresolved objections,
- faction support,
- time pressure.

Success at one stage could:

> resolve one objection.

A failure might:

> harden a faction's position.

The final agreement emerges from accumulated world-state changes.

Again, not one Persuasion roll.

---

# 32. Medical Procedures

A long high-risk surgery might warrant:

- diagnosis,
- stabilization,
- critical procedure,
- recovery.

But a routine surgery performed by an expert should be heavily abstracted.

The amount of resolution should depend on:

- uncertainty,
- stakes,
- player involvement.

This keeps the game from becoming a medical simulator unless that moment actually matters.

---

# 33. Training Projects

Complex training can also use milestones.

Example:

Learning a new jutsu:

1. understand theory,
2. reproduce chakra pattern,
3. perform incomplete technique,
4. complete technique,
5. achieve basic reliability,
6. build mastery.

But the actual XP and mastery growth still belong primarily to Ruleset 1.

Ruleset 2 determines how uncertain training milestones resolve.

---

# 34. Breakthroughs

An exceptional result during extended work may create a breakthrough.

A breakthrough might:

- complete a milestone early,
- reveal a better method,
- reduce later Difficulty,
- save resources.

But it should remain within plausible capability.

A novice does not accidentally invent Flying Raijin because they rolled exceptionally well while practicing basic sealing.

---

# 35. Catastrophic Project Failures

Long-term projects can have major setbacks, but only when risk exists.

Example:

Experimental forbidden jutsu research may expose:

- injury,
- laboratory damage,
- chakra backlash.

Routine historical research does not.

Again, stakes control consequence space.

---

# 36. Completion Quality

Finishing a project should not always mean identical output.

A crafted weapon might be:

- functional,
- good,
- excellent.

A newly developed jutsu might have:

- poor chakra efficiency,
- long hand seals,
- instability,
- excellent refinement.

So extended tasks can track both:

> **Completion**

and

> **Quality**

Those should remain separate.

---

# 37. Completion Can Be Guaranteed While Quality Is Uncertain

This follows 2.10.

Example:

A skilled craftsman with enough time and materials will definitely finish the item.

The real resolution becomes:

> How long does it take and how good is the result?

That is preferable to repeatedly asking whether they "fail to make a kunai."

---

# 38. Quality Can Improve After Completion

A project can continue into refinement.

Example:

Jutsu developed.

Then:

- reduce chakra cost,
- shorten hand seals,
- improve speed,
- increase stability.

This creates long-term mastery progression without requiring endless new techniques.

---

# 39. Abandoning a Project

The character should be able to stop.

They may retain:

- partial research,
- prototypes,
- knowledge,
- materials.

Depending on the project, those may be reusable later.

This supports persistent life simulation.

---

# 40. Extended Tasks Should Compete for Character Time

This is where the incremental-life-simulator side becomes important.

A character cannot simultaneously spend unlimited time on:

- training,
- missions,
- relationships,
- research,
- work,
- recovery.

Extended tasks consume calendar time.

That creates meaningful prioritization even when success is ultimately likely.

---

# 41. Off-Screen NPC Extended Projects

NPCs should also pursue long-term goals.

Examples:

- training,
- research,
- promotion,
- relationships,
- schemes.

But we should resolve their projects with greater abstraction unless they intersect with the player.

A project might advance weekly or monthly based on:

- capability,
- resources,
- priorities,
- interruptions.

This makes the world feel alive without simulating every hour.

---

# 42. Player Proximity Determines Detail

A useful general rule:

> **The closer a complex process is to the player's active involvement, the more granular its resolution may become.**

Player directly performing surgery:
> potentially detailed.

An NPC medic performing routine surgery across town:
> highly abstracted.

This keeps simulation resources focused where they matter.

---

# 43. Recommended Extended-Task Structure

Every extended task should define:

**Objective**  
What counts as completion?

**Scope**  
How much total work is required?

**Milestones**  
What meaningful stages exist?

**Difficulty by Stage**  
How demanding is each stage?

**Relevant Capabilities**  
Which Skills/Attributes apply?

**Resources**  
What does the task consume or require?

**Risks**  
What can go wrong?

**Progress State**  
How far along is it?

**Knowledge State**  
What has been learned?

**Quality State**  
How good is the developing result?

**Dependencies**  
What must happen before later stages?

That is enough structure to support complex projects without building a separate minigame for every domain.

---

# 44. Standard Extended-Resolution Cycle

For each meaningful work period:

### Step 1 — Determine active stage.

### Step 2 — Confirm prerequisites/resources.

### Step 3 — Determine time invested.

### Step 4 — Calculate relevant Effective Capability and Difficulty.

### Step 5 — Resolve uncertainty only if needed.

### Step 6 — Translate degree into:
- progress,
- knowledge,
- quality,
- setback.

### Step 7 — Consume time/resources.

### Step 8 — Apply fatigue, risk, or world-state consequences.

### Step 9 — Check milestone completion.

### Step 10 — Present meaningful decisions before continuing.

That gives us a reusable framework across many systems.

---

# Example — Developing a Custom Fire Jutsu

Objective:

> Develop a short-range compressed flame technique requiring fewer hand seals than Great Fireball.

Possible milestones:

**1. Theory**
Determine the chakra-shaping approach.

**2. Ignition Prototype**
Produce a stable flame.

**3. Compression**
Achieve intended density and range.

**4. Stabilization**
Prevent dangerous backlash.

**5. Combat Reliability**
Perform consistently under pressure.

A severe failure during Compression could:

> cause chakra backlash.

A strong success might:

> reveal a more efficient shaping method.

The project develops organically.

---

# Example — Investigation

Objective:

> Determine who stole classified mission records.

Progress does not simply mean:

> 64% mystery solved.

Instead, milestones might involve:

- establish timeline,
- identify access list,
- uncover falsified log,
- narrow suspects,
- obtain confirming evidence.

Each discovery becomes persistent knowledge.

That feels much more like an investigation.

---

# What I Would Lock In

> **Extended resolution is used when meaningful progress accumulates across multiple work periods or phases.**

> **Scope and Difficulty are separate: large tasks are not automatically difficult, and difficult tasks are not automatically large.**

> **Progress should be continuous rather than a simple count of successful rolls.**

> **Degrees of outcome influence progress, quality, knowledge, and setbacks.**

> **Failure can produce useful information when the domain supports learning from failure.**

> **Large projects should use mil

---

## Turn 502a79da-28c3-4abe-92b2-e34755c63f99

### User

Ok

### Assistant — afcbd7bd-66bd-4a08-b04b-6d119c980528

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.14 — Teamwork & Assistance

Teamwork should matter because multiple people can contribute different capabilities to the same objective.

But we should avoid the simplistic rule:

> **More people = add everyone's stats together.**

That would destroy scaling and make large groups absurdly powerful.

The core principle should be:

> **Teamwork improves an objective through meaningful contribution, role coverage, coordination, and parallel effort—not raw stat addition.**

---

## 1. Four Types of Group Contribution

I think we should distinguish four different ways characters can work together.

### Assistance
One primary character performs the task while others support.

Example:
- medic performs surgery while an assistant manages tools and monitoring.

### Cooperative Action
Several characters perform the same immediate objective together.

Example:
- multiple shinobi restrain one target.

### Parallel Action
Different characters handle different parts of a larger task simultaneously.

Example:
- one searches records while another interviews witnesses.

### Coordinated Combination
Characters combine abilities into something that depends on timing or synergy.

Example:
- Wind Release amplifying Fire Release.

These should not all use the same mathematics.

---

# 2. Primary Actor + Assistance

For most technical tasks, one character should remain the **Primary Actor**.

Their capability provides the core resolution value.

Assistants then improve the situation only if they provide relevant support.

Examples:

- holding equipment,
- stabilizing a patient,
- feeding information,
- reducing distractions,
- providing chakra,
- checking calculations.

The assistants do **not** contribute their full Skill scores.

---

# 3. Assistance Should Reduce Problems More Often Than Add Power

Good assistance often works by removing inefficiencies.

For example, a surgical assistant may:

- improve visibility,
- organize instruments,
- monitor the patient.

Rather than:

> +15 Medicine.

The assistant may instead:

- reduce time pressure,
- lower environmental Difficulty,
- prevent a specific complication,
- improve failure floor.

This is more realistic and prevents stacking abuse.

---

# 4. Assistants Need Relevant Competence

A helper should only provide meaningful benefit if they understand how to help.

An untrained assistant in a delicate technical procedure may provide little benefit or even interfere.

So assistance quality should depend on:

- relevant Skill,
- familiarity,
- communication,
- role clarity.

This gives skilled support characters real value.

---

# 5. Diminishing Returns on Multiple Assistants

The first useful assistant may help a lot.

The fifth may barely help at all.

This should depend on whether additional people have distinct useful roles.

For example:

During surgery:

- one surgical assistant: useful,
- one monitoring specialist: useful,
- one chakra support medic: useful,
- six extra people crowding the room: not useful.

So:

> **Additional helpers only matter if there is a meaningful unfilled contribution.**

---

# 6. Coordination Limits Group Effectiveness

A group can be individually skilled but still perform poorly together if they cannot coordinate.

Important factors:

- communication,
- leadership,
- familiarity,
- shared training,
- timing,
- complexity of the plan.

This means team performance should depend on both:

> **individual competence**

and

> **coordination quality.**

---

# 7. Team Familiarity Should Matter

A squad that has trained together for years should coordinate better than equally skilled strangers.

They may have:

- established signals,
- known tendencies,
- practiced formations,
- trust,
- role familiarity.

This can reduce:

- communication delays,
- interference,
- timing errors.

This gives long-term teams mechanical identity.

---

# 8. Leadership Should Matter When Coordination Is Complex

Leadership should not simply provide:

> +10 to everyone.

Instead, good leadership can improve:

- role assignment,
- timing,
- information flow,
- decision speed,
- recovery when plans fail.

Leadership matters most when:

- the group is large,
- objectives are complex,
- conditions are changing.

A two-person simple task may barely require leadership.

A 20-person coordinated operation may depend heavily on it.

---

# 9. Cooperative Physical Effort

Some tasks genuinely benefit from multiple people applying effort together.

Examples:

- lifting debris,
- holding a gate,
- restraining a target.

Even here, Strength should not simply add linearly.

Why?

Because people interfere with each other and cannot always apply force equally.

A reasonable internal model should use:

- strongest contributor at full value,
- additional contributors at diminishing effectiveness,
- coordination quality,
- space constraints.

This prevents ten weak civilians from automatically overpowering an elite shinobi.

---

# 10. Group Size Should Have Physical Limits

Some tasks only allow a certain number of useful participants.

Example:

A narrow doorway might only let:

- two people push effectively.

Adding twelve more people behind them may help only slightly.

Likewise:

Only so many fighters can attack one person simultaneously without obstructing each other.

This should naturally cap group benefit.

---

# 11. Numbers Matter Through More Than Combined Capability

Groups become dangerous partly because they can:

- attack from multiple angles,
- divide attention,
- cover escape routes,
- rotate exhausted members,
- maintain pressure,
- create simultaneous threats.

Those are **structural advantages**, not just numerical bonuses.

This is how a group of weaker shinobi can threaten someone individually stronger.

---

# 12. Action Economy Should Matter Later

We should acknowledge but not fully define this here.

In combat, multiple characters can create pressure because they have multiple independent actions.

That belongs mainly in the Combat Ruleset.

Ruleset 2 only needs to establish:

> **Group advantage should not be represented solely by one combined stat.**

Multiple simultaneous actions can themselves create structural superiority.

---

# 13. Parallel Work

Parallel work should reduce **elapsed time**, not necessarily total work.

Example:

Two researchers independently process different sets of records.

If they do not overlap, they can complete the project faster.

This is different from both contributing to one check.

So extended tasks should allow:

> total workload divided across participants.

This makes organizations and teams genuinely useful.

---

# 14. Parallel Work Requires Divisible Tasks

Some tasks cannot meaningfully be split.

Example:

One person must perform the central movement of a surgical procedure.

Five surgeons cannot each perform 20% simultaneously.

So the engine should distinguish:

### Divisible Work
Can be parallelized.

### Bottleneck Work
Requires one primary actor or sequential stage.

This prevents unrealistic speed-ups.

---

# 15. Specialists Should Cover Different Bottlenecks

One of the strongest benefits of a team should be specialization.

Example shinobi squad:

- sensor,
- medic,
- tracker,
- combat specialist.

The group does not gain one giant universal Skill score.

Instead, it has access to strong capability across more domains.

That is much healthier for character identity.

---

# 16. Use the Best Relevant Specialist, Not the Best Overall Character

Whenever a team faces a task, the most relevant member should often become the Primary Actor.

Example:

The jonin captain may be the strongest fighter.

But if the team encounters an advanced seal, the genin fuinjutsu prodigy may be the appropriate lead.

Rank should not automatically determine who performs the task.

---

# 17. A Weak Link Can Matter in Coordinated Actions

Some group tasks require everyone to perform adequately.

Example:

A four-person stealth formation crossing a guarded area.

The loudest member may compromise the entire group.

In these cases, team resolution may depend on:

- weakest relevant participant,
- average performance,
- coordination.

The exact method depends on the action.

This is very different from assistance.

---

# 18. Team Resolution Models

I think we should define several standard team models.

### Lead + Support
One actor carries the task.

### Weakest-Link
Everyone must meet a threshold.

### Collective Effort
Multiple participants contribute directly.

### Best Specialist
Only the strongest relevant performer matters.

### Parallel Roles
Different members resolve different components.

### Synergistic Combination
Abilities interact to create a new combined effect.

This should cover most group situations.

---

# 19. Lead + Support Model

Use when one person is clearly responsible.

Examples:

- surgery,
- lockpicking,
- negotiation,
- technique development.

Primary capability:

> lead character.

Others contribute through:

- assistance,
- safeguards,
- information,
- reduced Difficulty.

---

# 20. Weakest-Link Model

Use when every participant must avoid failure.

Examples:

- sneaking as a group,
- crossing unstable terrain together,
- synchronized disguise operation.

The weakest relevant member may determine exposure.

But stronger members may assist them.

So:

> weakest-link does not necessarily mean automatic doom.

Good teammates can compensate.

---

# 21. Collective Effort Model

Use when several people physically or functionally contribute to the exact same output.

Examples:

- lifting,
- pushing,
- holding,
- restraining.

Contributions should have diminishing returns.

Coordination matters.

---

# 22. Best Specialist Model

Use when only one person's expertise is necessary.

Example:

The team encounters an inscription.

If one member can read it, the group gains the information.

We do not average everyone's literacy.

This sounds obvious, but it should be explicit.

---

# 23. Parallel Roles Model

Use when an objective contains several distinct tasks.

Example:

During infiltration:

- sensor watches patrols,
- infiltrator bypasses security,
- hacker/seal specialist disables barrier,
- combat specialist provides cover.

Each role affects a different part of the operation.

This is likely the most common squad model.

---

# 24. Synergistic Combination Model

Some Naruto techniques specifically interact.

Examples:

Wind + Fire.

Water + Lightning.

Shadow possession + coordinated strike.

These should not simply mean:

> Skill A + Skill B.

Instead, the combination may create:

- new effect,
- larger area,
- increased potency,
- altered properties,
- new plausible outcomes.

The combination should define a **new resolution profile**.

---

# 25. Combination Techniques Require Synchronization

The better the timing requirement, the more coordination matters.

Potential requirements:

- hand-seal synchronization,
- timing window,
- chakra compatibility,
- spatial positioning,
- prior training.

Two individually powerful characters may still perform a combination poorly if they have never practiced together.

This gives team training real value.

---

# 26. Team Synergy Should Be Learnable

Repeated cooperation can improve:

- timing,
- communication,
- trust,
- role knowledge.

This could eventually create:

- Squad Coordination,
- Combination Mastery,
- shared tactical familiarity.

These probably belong partly in Ruleset 1, but Ruleset 2 should recognize them.

---

# 27. Team Conflict Can Reduce Performance

Poor relationships can matter when cooperation is required.

Examples:

- distrust,
- rivalry,
- refusal to follow leadership,
- conflicting objectives.

This should not automatically penalize every check involving those characters.

It matters only when cooperation requires:

- trust,
- timing,
- information sharing,
- compliance.

Again, targeted effects.

---

# 28. Communication Constraints

Teams may coordinate worse when:

- too far apart,
- unable to see one another,
- radios fail,
- noise prevents hearing,
- secrecy prevents open communication.

These conditions should change teamwork quality.

This makes communication tools mechanically useful.

---

# 29. Shared Information

One character knowing something does not automatically mean the whole team knows it.

Information must be:

- communicated,
- observed,
- shared through established systems.

In fast-moving situations, communication can itself require time or opportunity.

This preserves knowledge states.

---

# 30. Team Assistance Can Improve Outcome Floor

A helper may not increase success probability much but can prevent severe failure.

Example:

A climber belays another.

The climber's ability to complete the route may barely improve.

But failure no longer means:

> uncontrolled fall.

Similarly, a medical assistant may catch a developing complication before it becomes catastrophic.

This is another important teamwork benefit.

---

# 31. Rescue and Recovery Roles

Some team members may contribute mostly by mitigating consequences.

Examples:

- extraction specialist,
- backup medic,
- defensive support,
- evacuation team.

They may not increase the initial success chance at all.

But they greatly improve survivability.

That should still count as meaningful teamwork.

---

# 32. Assistance Should Cost the Helper Something When Appropriate

Helpers may spend:

- time,
- chakra,
- attention,
- equipment,
- positioning.

A sensor monitoring for enemies cannot necessarily devote full attention to fighting.

This creates real tradeoffs.

Support should not be free.

---

# 33. One Character Cannot Fully Assist Everything at Once

Characters have limited attention and action capacity.

Someone should not simultaneously provide full:

- medical support,
- tactical analysis,
- sensory coverage,
- combat assistance.

Later combat/action-economy rules can formalize this.

For now:

> **Assistance requires meaningful commitment.**

---

# 34. Group Failure Should Identify Where the Breakdown Happened

If a team fails, the engine should not simply say:

> Your teamwork failed.

It should determine the causal breakdown.

Examples:

- communication failure,
- weakest member exposed the group,
- poor timing,
- incorrect specialist judgment,
- overwhelming opposition.

This creates useful feedback and character development.

---

# 35. Team Success Can Mask Individual Weaknesses

A strong team should be able to compensate for weaker members.

Example:

A novice tracker may contribute little, but:

- sensor locates chakra,
- veteran confirms trail,
- novice carries equipment.

The novice doesn't need to magically gain expert Tracking.

The team structure allows everyone to contribute according to their capability.

---

# 36. Mentorship

Mentorship is a special form of assistance.

A mentor can:

- give instructions,
- correct technique,
- prevent dangerous mistakes,
- expose the learner to higher-level training.

During actual performance, however, too much mentor intervention may mean:

> the mentor is performing the task instead.

So the engine should distinguish:

### Guided Performance
Learner still performs.

### Demonstration
Mentor performs while learner observes.

### Intervention
Mentor takes over.

This matters for progression credit.

---

# 37. Assistance Should Not Steal Progression

If a learner performs a task with help, they should still gain relevant experience.

But the amount may depend on:

- how much they personally contributed,
- how much the mentor corrected,
- whether they understood the process.

A character should not gain full mastery merely by standing beside an expert.

---

# 38. Team Size Should Have Administrative Costs

Large teams may incur:

- communication overhead,
- scheduling complexity,
- coordination delay,
- secrecy risk.

This is especially relevant outside combat.

A 20-person research team is not automatically 20× faster than one researcher.

Organizations gain power, but also complexity.

---

# 39. Secrecy Becomes Harder With More Participants

The more people involved in:

- conspiracies,
- covert missions,
- secret projects,

the more potential information leakage exists.

That is not a generic penalty.

It emerges because there are more:

- observers,
- communications,
- records,
- possible failures.

This is a good example of group size increasing stakes.

---

# 40. Large Groups Should Resolve Hierarchically

For very large operations, we should not resolve every participant individually.

Instead, use:

- squads,
- units,
- teams,
- specialists.

Example:

A 100-shinobi search operation should not require 100 Perception checks.

The engine can model:

- search coverage,
- leadership,
- sensor teams,
- terrain,
- elapsed time.

This will be important for village-scale simulation.

---

# 41. NPC Teams Should Use the Same Logic

Off-screen NPC groups should not receive arbitrary success just because they are background characters.

Their success should derive from:

- members,
- specialists,
- leadership,
- resources,
- opposition.

But it should be abstracted more aggressively when the player is not involved.

---

# 42. Team Outcomes Should Update Relationships

Shared success and failure can affect:

- trust,
- respect,
- rivalry,
- blame,
- confidence in leadership.

These are consequences, not resolution bonuses by default.

Over time, those relationships may affect future coordination.

This creates a natural feedback loop.

---

# 43. Recommended Teamwork Procedure

When multiple characters contribute to one objective:

### Step 1 — Define the shared objective.

### Step 2 — Identify each participant's role.

### Step 3 — Select the appropriate teamwork model:
- Lead + Support
- Weakest-Link
- Collective Effort
- Best Specialist
- Parallel Roles
- Synergy

### Step 4 — Determine whether coordination matters.

### Step 5 — Apply relevant specialists, assistance, and structural advantages.

### Step 6 — Prevent overlapping contributions from stacking linearly.

### Step 7 — Resolve only the meaningful uncertainties.

### Step 8 — Apply resource/attention costs to helpers.

### Step 9 — Determine collective and individual consequences.

### Step 10 — Update team state and relationships if relevant.

---

# Example — Group Stealth

Four-person squad attempts to infiltrate a compound.

This is not:

> average everyone's Stealth.

Instead:

- strongest scout chooses route,
- sensor monitors patrols,
- weakest stealth member may create exposure,
- experienced teammates can assist,
- squad familiarity affects timing.

The final probability reflects the actual team structure.

---

# Example — Restraining a Strong Opponent

Three weaker shinobi attempt to hold down one stronger target.

Do not calculate:

> Strength 40 + 40 + 40 = 120.

Instead:

- strongest holder contributes most,
- others add leverage with diminishing returns,
- positioning matters,
- opponent's available limbs and techniques matter,
- coordination matters.

The group may still gain a strong advantage, but for realistic reasons.

---

# Example — Combination Jutsu

Fire specialist:

> Fire Release 75

Wind specialist:

> Wind Release 65

They combine techniques.

This should not become:

> 140 power.

Instead:

- Fire technique provides core effect,
- Wind technique modifies spread/intensity,
- coordination determines stability,
- combination mastery determines efficiency.

The result becomes a distinct combined technique.

---

# What I Would Lock In

> **Teamwork never means simply summing character stats.**

> **Group contribution is categorized as assistance, cooperative effort, parallel work, or synergistic combination.**

> **Most technical tasks use one Primary Actor with support.**

> **Assistants often reduce Difficulty, risk, time pressure, or failure severity rather than directly adding Capability.**

> **Multiple helpers have diminishing returns unless they fill distinct useful roles.**

> **Coordination, com

---

## Turn e1903452-f59e-4883-a093-9a7b74a730ed

### User

Ok

### Assistant — 94eb162e-750f-4cc3-a251-e8ad84756ea1

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.15 — Hidden Checks & Information Resolution

This section should govern situations where **revealing that a check occurred would itself reveal information**.

That includes:

- detecting ambushes,
- noticing surveillance,
- spotting traps,
- sensing hidden chakra,
- judging deception,
- recalling uncertain facts,
- interpreting evidence,
- identifying disguised identities,
- noticing subtle social cues.

The core rule should be:

> **The player should receive only the information their character has earned—not the engine’s hidden truth or the fact that hidden truth was tested.**

## 1. Hidden Checks Should Be Truly Hidden

The engine should not say:

> Perception check failed.

because that tells the player:

> there was something to perceive.

Instead, the engine should present the character's current understanding.

For example:

> The corridor appears empty.

That statement may mean:

- it truly is empty,
- something is hidden and the character failed to notice it,
- the character noticed nothing unusual.

The player should not know which merely from presentation.

---

# 2. Separate Objective Truth From Character Belief

The engine should maintain at least two layers:

### Objective World State
What is actually true.

### Character Knowledge State
What the character currently believes or knows.

These must not be collapsed.

Example:

**Objective truth:**  
A trap is beneath the floorboard.

**Character knowledge:**  
The floor appears normal.

The character can act on only the second layer unless they discover more.

---

# 3. Hidden Resolution Uses Normal Mechanics

Hidden checks should not have a separate probability system.

They still use:

- Effective Capability,
- Difficulty or opposition,
- situational modifiers,
- probability,
- degree of outcome.

The only difference is:

> **The resolution result is not directly exposed to the player.**

This keeps the overall system consistent.

---

# 4. The Existence of a Check Should Not Be Revealed

This is especially important for:

- traps,
- surveillance,
- lies,
- ambushes,
- hidden observers.

Bad:

> You fail a hidden Perception check.

Better:

> Nothing seems unusual.

The engine may have resolved something internally, but the player should not be able to metagame from that fact.

---

# 5. Passive Detection Should Usually Happen Automatically

The player should not need to repeatedly say:

> I look around.

> I check for traps.

> I inspect everyone for lies.

Characters should naturally apply relevant passive awareness when appropriate.

Examples:

- Perception,
- sensory abilities,
- professional habits,
- experience.

The player can still choose to conduct a **deliberate search**, which changes:

- time investment,
- attention,
- method,
- sometimes Difficulty.

But baseline awareness should exist without constant prompting.

---

# 6. Passive and Active Searching Are Different

### Passive Observation
What the character notices while doing something else.

### Active Search
The character deliberately focuses on finding something.

An active search may provide:

- more time,
- better coverage,
- specialized tools,
- closer examination.

But it also costs:

- time,
- attention,
- sometimes secrecy.

This distinction prevents "I am always searching for everything" behavior.

---

# 7. Hidden Information Should Have Detectability

Not all hidden facts are equally observable.

A hidden fact might be:

### Obvious
Most attentive people notice it.

### Subtle
Requires good observation.

### Concealed
Someone intentionally hid it.

### Expertly Concealed
Requires specialization or strong evidence.

### Inaccessible
Cannot currently be discovered through the method being used.

This is effectively difficulty, but framed specifically for information.

---

# 8. Information Must Be Discoverable Through a Valid Channel

A character should not detect information they have no way to access.

Examples:

You cannot visually notice:

> chakra inside a sealed room

unless you have an appropriate sensory method.

You cannot infer:

> someone's exact medical diagnosis

from casual observation unless there are meaningful signs and relevant expertise.

So hidden information requires:

> **a valid information channel.**

This is the information equivalent of a plausibility gate.

---

# 9. Different Channels Can Reveal Different Information

The same hidden fact may be discoverable through multiple methods.

Example: concealed shinobi.

Possible channels:

- sight,
- sound,
- smell,
- chakra sensing,
- disturbed terrain,
- tracking signs.

A character weak in one channel may still succeed through another.

This makes sensory abilities meaningfully distinct.

---

# 10. Concealment Should Oppose the Relevant Detection Method

If someone intentionally hides information, their concealment can generate opposition.

Examples:

**Stealth** vs **Perception**

**Disguise** vs **Recognition/Insight**

**Deception** vs **Insight**

**Trail Concealment** vs **Tracking**

The system should compare the appropriate capabilities rather than assigning arbitrary hidden DCs.

---

# 11. Success Should Produce Information Quality

A successful detection should not always reveal everything.

Outcome degree should determine:

- how much is noticed,
- how specific the information is,
- how confident the character can be.

Example: detecting hidden movement.

### Narrow Success
> Something moved near the trees.

### Standard Success
> Someone is concealed near the eastern treeline.

### Strong Success
> One humanoid is hiding behind the third tree from the path.

### Exceptional Success
> You identify the person's position, posture, and likely readiness to attack.

This gives perceptive characters meaningful superiority.

---

# 12. Failure Should Usually Mean Insufficient Information

The default failure result should normally be:

> the character does not learn the hidden fact.

Not:

> the character confidently believes the opposite.

That distinction is very important.

Failing to detect a trap usually means:

> you do not notice the trap.

It should not automatically mean:

> you become convinced there cannot possibly be a trap.

---

# 13. False Conclusions Need Stronger Justification

Incorrect information should occur only when there is a plausible reason.

Examples:

- deliberate deception,
- misleading evidence,
- ambiguous symptoms,
- poor interpretation,
- confirmation bias,
- an exceptionally bad information-analysis result.

So:

> **Failure and misinformation are not synonymous.**

This prevents the engine from constantly lying to the player through failed knowledge checks.

---

# 14. Observation and Interpretation Should Be Separable

This is particularly useful.

A character may correctly observe:

> small scratches around the lock.

But incorrectly interpret them as:

> signs of forced entry.

when they were actually:

> tool marks from maintenance.

Thus:

### Observation
What evidence is perceived.

### Interpretation
What the character concludes from it.

These may use different capabilities.

This creates richer investigation gameplay.

---

# 15. Raw Evidence Should Persist

If the character observes something real, that observation should remain available.

Example:

> There is dried mud beneath the window.

Even if they misinterpret its significance, the evidence itself does not disappear.

Later information might allow them to reinterpret it.

This is important for investigations.

---

# 16. Confidence Should Be Tracked Separately From Correctness

A character may be:

- correct and confident,
- correct but uncertain,
- wrong and uncertain,
- wrong and confident.

Those are meaningfully different states.

Confidence can derive from:

- outcome degree,
- expertise,
- evidence quality,
- familiarity.

But confidence is not proof of correctness.

---

# 17. Experts Should Usually Know When Evidence Is Weak

High expertise should not simply improve correctness.

It should also improve calibration.

An expert may say:

> There isn't enough information to conclude that.

while a novice may jump to an incorrect conclusion.

That is a powerful form of competence.

So skill should improve:

- accuracy,
- specificity,
- confidence calibration.

---

# 18. Knowledge Checks Should Not Conjure Facts

A successful knowledge check should reveal information the character could plausibly know.

It should not produce omniscient answers.

Example:

A historian may recognize:

> the symbol belongs to an old clan.

But unless they have access to relevant records, they should not automatically know:

> the exact identity of the person who carved it yesterday.

Skill retrieves or interprets available knowledge; it does not create impossible information.

---

# 19. Memory Should Depend on Previously Available Knowledge

Recall checks should only operate on information the character could have:

- learned,
- seen,
- heard,
- studied.

A character cannot successfully "remember" something they were never exposed to.

If the information was never known:

> recall is impossible.

---

# 20. Recall and Research Are Different

If the character does not remember something, they may still be able to:

- consult a book,
- ask someone,
- inspect records,
- perform research.

That becomes a different task.

This helps distinguish:

> personal knowledge

from

> accessible external information.

---

# 21. Repeated Hidden Checks Should Be Suppressed

As established in repeated attempts:

If the player asks:

> Do I see anything?

then immediately:

> Do I notice anything now?

with nothing changed, no fresh roll should occur.

A new attempt needs:

- closer inspection,
- more time,
- another sensory method,
- better lighting,
- a different position.

This prevents fishing.

---

# 22. A Failed Hidden Check Should Not Alter World State Unless Failure Causes Something

If someone fails to notice surveillance, the world state is simply:

> surveillance remains unnoticed.

The failure does not need additional punishment.

But if they actively search and make noise while doing so, that action might expose them.

Again, consequences must be causal.

---

# 23. Hidden Checks Can Be Opposed Without Either Side Knowing

Two characters may unknowingly contest one another.

Example:

A spy follows a shinobi.

The shinobi is not consciously searching for a tail.

The engine can still resolve:

**Spy Stealth**

against

**Passive Detection**

Neither side necessarily knows the contest occurred.

This is important for autonomous NPC behavior.

---

# 24. Deliberate Suspicion Changes Detection

If a character has reason to suspect something, they may switch from passive awareness to active investigation.

That can improve their chances because:

- more attention is devoted,
- different methods become available,
- more time is spent.

This should arise from actual suspicion, not player metagaming.

---

# 25. Suspicion Is a Persistent State

Suspicion should often be tracked as world state.

A guard may become:

- unaware,
- mildly suspicious,
- alert,
- actively searching.

These states affect:

- behavior,
- attention,
- available actions.

This is better than repeatedly applying arbitrary Perception bonuses.

---

# 26. Detection Can Be Progressive

Some hidden targets should not move instantly from:

> unseen

to

> fully identified.

Possible progression:

**Unnoticed**

→ **Something feels wrong**

→ **Presence detected**

→ **Location narrowed**

→ **Target identified**

→ **Intent understood**

Different outcome degrees can move through these stages.

This is especially useful for stealth and sensory abilities.

---

# 27. Deception Should Also Be Progressive

Likewise, social belief need not be binary.

Possible states:

- accepted,
- probably true,
- uncertain,
- suspicious,
- probably false,
- confirmed false.

A successful deception may shift belief without producing total certainty.

This makes social interactions more natural.

---

# 28. Detecting a Lie Is Not Reading the Truth

This should be a hard rule.

If a character concludes:

> "He is probably lying."

that does **not** reveal:

> what the truth actually is.

Insight detects inconsistency, tension, or deception.

It should not function as mind-reading unless an ability explicitly does that.

---

# 29. Truthful People Can Appear Suspicious

Behavior is noisy.

A nervous truthful person may appear evasive.

So social interpretation should use:

- evidence,
- context,
- familiarity,
- actual deception cues.

This helps prevent Insight from becoming a magical lie detector.

---

# 30. Disguises Should Have Layers

Detecting a disguise may involve different questions:

1. Does anything seem unusual?
2. Is this person disguised?
3. Who are they actually?
4. What technique created the disguise?

Success at one level does not guarantee all others.

This structure works well with outcome degree.

---

# 31. Sensory Abilities Need Defined Information Outputs

Naruto-style sensory abilities should specify what they can reveal.

For example, a technique might detect:

- chakra presence,
- direction,
- approximate distance.

But not necessarily:

- identity,
- exact technique,
- intention.

This prevents sensory abilities from becoming omniscient.

---

# 32. Information Overload Can Matter

A powerful sensor may be surrounded by too many signals.

The issue might not be:

> Can they sense chakra?

but:

> Can they isolate the relevant signature?

Thus more information can sometimes increase analysis difficulty.

This could matter in:

- battlefields,
- cities,
- crowded events.

---

# 33. Familiar Signatures Should Be Easier to Recognize

If a character knows someone well, recognizing their:

- voice,
- chakra,
- gait,
- handwriting,

should be easier.

Familiarity can convert:

> anonymous detection

into:

> identification.

This makes relationships and experience mechanically relevant.

---

# 34. Hidden Information Should Not Be Retroactively Invented

If the engine establishes:

> no trap exists,

it should not later decide there was secretly a trap because the player rolled poorly.

Likewise, if a hidden NPC was not present, a failed Perception result cannot retroactively create one.

Resolution determines what the character learns about existing world state, not what secretly exists—unless the world state genuinely had not yet been generated.

---

# 35. Undetermined Facts Must Be Generated Before Detection Resolution

If the simulation has not yet established whether something exists:

1. Generate the objective world fact using world logic.
2. Persist that fact.
3. Then resolve whether the character detects it.

Never use:

> failed detection = object exists.

That would make the world depend on player failure.

---

# 36. Private NPC Knowledge Must Remain Private

NPCs can know things the player does not.

Their decisions may therefore appear mysterious.

The engine should not expose hidden motives simply because it is narrating them.

Player-facing narration should generally remain limited to what the controlled character can observe or reasonably infer.

---

# 37. Player Knowledge and Character Knowledge Must Remain Distinct

In some cases, the player may know something the character does not.

The engine should still resolve according to the character's knowledge.

Likewise, if the character knows something the player might have forgotten, the engine should communicate it appropriately.

The simulation should not punish the player for failing to remember obvious information their character would know.

---

# 38. Hidden Results Should Not Change Because the Player Guessed Correctly

Suppose the player says:

> I bet that guy is secretly an enemy spy.

If the character has no evidence, the guess does not automatically become character knowledge.

The player may still choose actions based on the suspicion, but the simulation should distinguish:

> player hypothesis

from

> character evidence.

This helps prevent metagaming without restricting player agency.

---

# 39. Information Reliability Levels

I think the engine should internally recognize broad reliability states such as:

### Directly Observed
Character personally witnessed it.

### Confirmed
Supported by strong evidence or multiple sources.

### Probable
Evidence strongly suggests it.

### Possible
Plausible but uncertain.

### Rumor
Learned from an unverified source.

### Suspected
Character inference without strong confirmation.

### Discredited
Evidence currently argues against it.

These states would be extremely useful for persistent simulation.

---

# 40. Contradictory Information Should Be Allowed

Characters can possess conflicting evidence.

For example:

- witness says A,
- physical evidence suggests B.

The engine should not immediately force one into truth.

The character may remain uncertain until additional evidence resolves the conflict.

This creates much better investigations.

---

# 41. Sources Should Matter

Information quality depends partly on source quality.

Possible sources:

- personal observation,
- trusted ally,
- stranger,
- official record,
- enemy interrogation,
- rumor,
- forged document.

The character's belief should reflect:

- source reliability,
- corroboration,
- expertise.

This should later connect with discovery and knowledge systems.

---

# 42. Exceptional Information Success Should Reveal Depth, Not Omniscience

An exceptional result can provide:

- subtle details,
- better confidence,
- hidden connections,
- faster analysis.

But it still cannot exceed:

- available evidence,
- sensory channels,
- plausible knowledge.

Again, excellent performance means **best plausible information**, not supernatural omniscience.

---

# 43. Information Failure Can Sometimes Create Delay Instead of Error

For many technical tasks, the best failure result is:

> insufficient confidence.

Example:

A medic examining unusual symptoms may conclude:

> I don't have enough information yet.

That is often more realistic than generating an incorrect diagnosis every time a check fails.

Experts especially should often recognize uncertainty.

---

# 44. Misinformation Should Usually Require One of Three Causes

I would restrict confident false conclusions primarily to:

1. **Deliberate deception**
2. **Misleading or ambiguous evidence**
3. **Severe interpretation failure**

This makes misinformation meaningful rather than arbitrary.

---

# 45. Hidden Information Can Have Consequence Without Reveal

A character may fail to notice:

> someone recognizes them.

The NPC now changes behavior.

The player sees only:

> the NPC becomes quieter.

The underlying information interaction remains hidden.

This allows subtle world simulation.

---

# 46. Discovery Should Update Future Resolution

Once hidden information is discovered, it becomes part of the character's knowledge state.

Future actions may then change naturally.

Example:

Discover:

> enemy uses poison.

Now the character can:

- prepare antidote,
- avoid contaminated weapons,
- warn allies.

No generic permanent "knowledge bonus" is needed.

Knowledge changes available decisions.

---

# 47. Hidden Check Presentation

The player-facing narration should present one of three broad forms:

### Clear Information
> You hear two people moving behind the door.

### Uncertain Information
> You think you hear movement behind the door, but you aren't certain.

### No Noticed Information
> You don't notice anything unusual.

Avoid:

- success/failure labels,
- DCs,
- hidden roll announcements.

This keeps immersion intact.

---

# 48. Recommended Hidden-Information Procedure

When hidden information may matter:

### Step 1 — Establish Objective Truth
What actually exists?

### Step 2 — Determine Information Channel
How could the character possibly know?

### Step 3 — Determine Passive or Active Observation
Are they naturally noticing or deliberately searching?

### Step 4 — Resolve Detection/Interpretatio

---

## Turn 15571a85-0762-40ff-ab49-7ea4aaf3b0d8

### User

Ok

### Assistant — e85ee8ad-2642-4612-8a63-2197fbd36707

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.16 — Knowledge, Discovery & Uncertainty

This section should govern how characters **acquire, retain, verify, misinterpret, share, and act on information over time**.

The key principle should be:

> **Characters act on what they know or believe, not on the engine’s objective truth.**

That applies to the player character and every NPC.

A shinobi may make a perfectly rational decision based on incomplete or incorrect information.

That is not bad simulation. It is often exactly what should happen.

---

## 1. Every Important Fact Can Exist in Multiple Knowledge States

For persistent simulation, a fact should conceptually have:

### Objective State
What is actually true.

### Awareness State
Whether a particular character has encountered information about it.

### Belief State
What that character currently thinks is true.

### Confidence State
How strongly they believe it.

### Source State
Why they believe it.

So two characters can have completely different understandings of the same event.

---

# 2. Knowledge Is Character-Specific

There should not be one universal pool of discovered information.

If Naruto knows something, Sasuke does not automatically know it.

Information must spread through:

- direct observation,
- conversation,
- reports,
- records,
- teaching,
- rumors,
- sensory techniques,
- interrogation,
- research.

This should apply to NPCs as well.

---

# 3. Organizations Can Have Knowledge Too

Some information can belong to an organization rather than one person.

Examples:

- village mission records,
- ANBU intelligence,
- clan archives,
- hospital records,
- bingo books.

But organization knowledge still requires actual storage and access.

A genin should not automatically know everything their village knows.

Instead:

> The information exists within the organization and may be available to characters with sufficient access.

---

# 4. Knowledge Has Accessibility

A fact may be:

### Common Knowledge
Widely known.

### Public Specialist Knowledge
Available to trained people.

### Restricted
Known only to authorized groups.

### Secret
Deliberately concealed.

### Compartmentalized
Even members of the same organization only know parts.

### Lost
No living accessible source currently possesses it.

This will be especially important for:

- clan techniques,
- forbidden jutsu,
- intelligence operations,
- political secrets,
- historical mysteries.

---

# 5. Information Has Sources

Characters should know—or sometimes not know—where information came from.

Sources can include:

- personal observation,
- instructor,
- friend,
- enemy,
- rumor,
- official report,
- research paper,
- interrogation,
- sensory detection,
- recovered document.

Source quality influences confidence.

A firsthand observation is not necessarily perfect, but it is different from:

> "Someone in the market said..."

---

# 6. Source Reliability Should Be Separate From Fact Accuracy

An unreliable source can occasionally tell the truth.

A reliable source can occasionally be wrong.

So we should distinguish:

### Source Reliability
How trustworthy the source generally appears.

### Information Accuracy
Whether the specific claim is objectively correct.

This prevents simplistic logic like:

> unreliable source = false information.

---

# 7. Corroboration Builds Confidence

Multiple independent sources supporting the same claim should increase confidence.

But we need one safeguard:

> **Repeated copies of the same original source are not independent confirmation.**

Example:

Five villagers repeat the same rumor they all heard from one merchant.

That is not equivalent to five independent observations.

The engine should track source relationships when they matter.

---

# 8. Contradiction Should Reduce Certainty, Not Automatically Choose a Winner

Suppose:

- Witness A says the attacker wore red.
- Witness B says the attacker wore black.

The engine should not immediately decide which character believes.

Instead, the contradiction may create:

> unresolved uncertainty.

Further factors can matter:

- source reliability,
- viewing conditions,
- expertise,
- motive to lie,
- supporting evidence.

This produces genuine investigation.

---

# 9. Knowledge Should Have Confidence Levels

A useful internal framework could be:

### Unknown
No relevant knowledge.

### Speculative
Possible but weakly supported.

### Suspected
Some meaningful evidence.

### Probable
Evidence strongly favors it.

### Confirmed
Sufficiently established for ordinary decision-making.

### Certain
Direct or overwhelming evidence with no meaningful unresolved alternative.

These do not need to be displayed as literal labels.

---

# 10. Certainty Should Be Rare

The engine should avoid treating everything as perfectly known.

Many facts naturally remain uncertain.

For example:

> "He probably left the village sometime last night."

may be the best available conclusion.

This is fine.

Characters can make decisions under uncertainty.

---

# 11. Discovery Should Usually Reveal Pieces, Not Entire Truths

Investigations should produce information incrementally.

Example:

Unknown enemy technique.

First discovery:

> It appears to use Lightning Release.

Later:

> It requires conductive contact.

Later:

> It cannot pass through a specific insulating material.

Later:

> The caster must maintain a chakra connection.

This allows knowledge itself to become progression.

---

# 12. Knowledge Can Unlock Better Questions

Early on, a character may not even know what to investigate.

Once they discover something, new avenues open.

Example:

Find poison residue.

Now they can ask:

- Which poison?
- Who can produce it?
- Where was it purchased?
- Is there an antidote?

Discovery should expand the decision space.

---

# 13. Expertise Determines What Evidence Means

Two characters can observe the same thing and learn different amounts.

A civilian sees:

> strange markings.

A fuinjutsu specialist sees:

> a containment seal with an unstable secondary trigger.

The evidence is identical.

Their interpretation differs because of expertise.

This gives specialized knowledge major value.

---

# 14. Attributes and Skills Should Affect Different Parts of Discovery

For example:

### Perception
Notice evidence.

### Intelligence
Connect patterns.

### Relevant Knowledge Skill
Understand technical meaning.

### Willpower
Maintain focus during difficult investigation.

### Social Skills
Acquire information from people.

So an investigation should not become:

> Intelligence solves everything.

Different discovery methods should use different capabilities.

---

# 15. Knowledge Skills Need Domain Boundaries

A character skilled in medicine should not automatically understand:

- fuinjutsu,
- economics,
- military strategy.

Broad intelligence can help reasoning, but specialized knowledge remains necessary.

This reinforces our Skills system from Ruleset 1.

---

# 16. General Knowledge and Specialist Knowledge Should Interact

A character might know:

> basic chakra theory

without understanding:

> advanced seal architecture.

General knowledge may allow:

- broad classification,
- recognition of obvious concepts.

Specialized knowledge allows:

- detailed interpretation,
- technical application.

This gives skill tiers a natural role.

---

# 17. Information Can Be Procedural or Declarative

We should distinguish:

### Declarative Knowledge
Knowing **that** something is true.

Example:
> Fire Release is weak against sufficiently strong Water Release.

### Procedural Knowledge
Knowing **how** to do something.

Example:
> performing the counter-technique correctly.

Knowing the theory does not automatically grant the skill to execute it.

This is critical.

---

# 18. Observation Does Not Automatically Grant Technique Access

Watching an advanced technique may provide:

- knowledge of its existence,
- clues about mechanics,
- hand seals,
- timing.

But it does not automatically allow the observer to perform it.

Learning still requires:

- prerequisites,
- Skill,
- training,
- possibly bloodline or unique access.

This prevents copying from becoming trivial.

---

# 19. Some Abilities Can Accelerate Learning

Certain Naruto abilities may alter information acquisition.

Examples:

- Sharingan observing movement or hand seals,
- Byakugan observing chakra pathways,
- sensory abilities detecting chakra patterns.

These abilities should specify what information they provide.

They may reduce uncertainty dramatically without bypassing other prerequisites.

---

# 20. Discovery Can Change Difficulty

Knowledge should sometimes make future actions easier because the task is better understood.

Example:

Before research:

> barrier weakness unknown.

After research:

> weak node identified.

Breaking the barrier may now have lower effective Difficulty or a new viable method.

The character did not gain raw skill.

They reduced uncertainty and changed the problem.

---

# 21. Discovery Can Also Reveal That Something Is Harder Than Expected

Information is not always beneficial in the sense of improved odds.

The character may learn:

> The poison is much more dangerous than assumed.

or:

> The target is protected by an elite sensor.

That may reveal worse odds.

But the knowledge still helps because it improves decision-making.

---

# 22. Hypotheses Should Be Allowed

Characters should be able to form theories before certainty.

Example:

> "The attacker may have used a clone to create the false trail."

That hypothesis can guide investigation.

The engine should distinguish:

> hypothesis

from

> established fact.

This prevents character speculation from accidentally becoming world truth.

---

# 23. Hypotheses Can Be Tested

Testing a hypothesis can:

- strengthen confidence,
- weaken it,
- falsify it,
- reveal a better explanation.

This is where investigation becomes interactive rather than passive.

---

# 24. Confirmation Bias Can Exist, But Should Not Be Arbitrary

Characters may give extra weight to evidence that supports existing beliefs.

This should depend on things like:

- personality,
- emotional investment,
- prejudice,
- stress.

But we should use this sparingly.

The engine should not constantly force irrationality just to manufacture drama.

---

# 25. Intelligence Should Improve Updating

High Intelligence should help characters:

- notice contradictions,
- revise theories,
- integrate new evidence,
- avoid obvious logical errors.

But high Intelligence does not guarantee correct conclusions if the evidence itself is bad.

This is important for believable smart characters.

---

# 26. Experts Should Better Calibrate Uncertainty

As with 2.15, expertise should improve not only correctness but awareness of limits.

A skilled medic may say:

> "I can narrow it to two likely causes, but I need a blood test to distinguish them."

A novice might confidently choose one.

That is a realistic difference in expertise.

---

# 27. Memory Should Not Be Perfect

Characters can forget.

But forgetting should not be random noise everywhere.

Memory reliability should depend on:

- importance,
- repetition,
- emotional salience,
- recency,
- training,
- documentation.

Routine minor information can fade.

Major life events should be far more persistent.

---

# 28. External Records Extend Memory

Characters can preserve knowledge through:

- journals,
- mission reports,
- books,
- maps,
- databases,
- clan archives.

This should reduce dependence on personal recall.

It also creates risks:

- records can be stolen,
- destroyed,
- forged,
- restricted.

---

# 29. Knowledge Can Die With Characters

If a secret exists only in one person's memory and that person dies without sharing it:

> the knowledge may become lost.

That is an important feature for a generational simulation.

Techniques, family secrets, and historical facts can genuinely disappear.

---

# 30. Knowledge Can Persist Across Generations

Conversely, information can survive through:

- teaching,
- clan tradition,
- written records,
- institutions,
- apprentices.

This allows the simulation to model knowledge inheritance separately from genetic inheritance.

Very important for a generational Naruto game.

---

# 31. Techniques Can Become Easier to Learn as Knowledge Spreads

If a technique is:

- documented,
- standardized,
- taught by multiple experts,

future characters may learn it much more efficiently than the inventor did.

This creates natural technological and institutional progression.

The first person may spend years developing something.

Later students learn it in months.

---

# 32. Knowledge Can Become Distorted Through Transmission

Oral traditions, rumors, and repeated retellings can drift.

Written technical records are usually more stable.

So transmission method should affect fidelity.

This can produce:

- myths,
- corrupted techniques,
- inaccurate historical accounts.

But distortion should be gradual and causal, not random chaos.

---

# 33. Secrets Need Exposure Paths

A secret should not simply have a generic "chance to leak."

The engine should track possible exposure:

- witnesses,
- documents,
- communication,
- surveillance,
- defectors,
- captured agents.

The more exposure paths exist, the harder secrecy becomes.

This builds naturally on Teamwork.

---

# 34. Compartmentalization Reduces Knowledge Spread

Organizations can protect information by ensuring individuals know only what they need.

Example:

One shinobi knows:

> target location.

Another knows:

> extraction procedure.

Neither knows the full mission.

This reduces the damage caused by capture or betrayal.

That is a strategic information mechanic.

---

# 35. Interrogation Reveals What the Target Actually Knows

A successful interrogation should not produce objective truth automatically.

It produces information available in the target's mind.

The target may be:

- truthful,
- lying,
- mistaken,
- partially informed.

This distinction is essential.

---

# 36. Mind-Reading Abilities Still Access Belief, Not Necessarily Truth

Even literal memory-reading should normally reveal:

> what that person experienced or believes.

If they were deceived, their memories may still contain false conclusions.

This preserves objective truth as separate from subjective knowledge.

---

# 37. Rumors Should Spread Socially

Rumors can propagate through NPC networks.

Their spread might depend on:

- social connections,
- sensational value,
- credibility,
- secrecy,
- cultural interest.

But this should be simulated at an appropriate abstraction level.

We do not need to model every conversation individually.

---

# 38. Public Knowledge Can Change Reputation

Once information becomes widely believed, it can influence:

- reputation,
- social opportunities,
- political pressure,
- trust.

Importantly:

> public belief need not equal truth.

A false accusation can still affect reputation if widely believed.

That will be important later.

---

# 39. Propaganda and Misinformation

Factions can deliberately spread:

- false claims,
- selective truths,
- misleading narratives.

Success should depend on:

- credibility,
- audience beliefs,
- evidence,
- communication reach,
- counter-information.

This could become very important in village politics without needing a separate core resolution system.

---

# 40. Discovery Should Have Cost

Learning information may require:

- time,
- money,
- social favors,
- risk,
- travel,
- accessing restricted locations.

Information should not always be free.

This gives espionage, research, and social networks meaningful value.

---

# 41. Some Information Should Be Easy but Time-Consuming

Example:

Reading a thousand pages of records.

The information may not be intellectually difficult.

The limiting factor is:

> time.

So the system should distinguish:

- difficulty of understanding,
- volume of information.

This connects back to Extended Checks.

---

# 42. Search Quality and Search Coverage Are Different

A character can search:

> deeply but narrowly

or:

> broadly but shallowly.

Example:

Investigating ten suspects quickly may provide limited information on each.

Investigating one suspect thoroughly may reveal much more.

This gives information gathering meaningful strategy.

---

# 43. Time Pressure Can Force Uncertain Conclusions

Characters sometimes must act before evidence is complete.

Example:

> You have two likely suspects and twenty minutes before the convoy leaves.

The player may need to choose based on incomplete information.

The simulation should support that.

Not every mystery waits politely to be solved.

---

# 44. Information Can Become Outdated

Some knowledge remains true indefinitely.

Other knowledge changes.

Examples:

- someone's current location,
- political alliances,
- patrol routes,
- prices,
- injuries.

The engine should track when information was acquired.

Old information may remain useful but become less reliable.

---

# 45. Static and Dynamic Knowledge

We can distinguish:

### Static Knowledge
Usually does not change.

Example:
> fundamental anatomy.

### Dynamic Knowledge
May become outdated.

Example:
> enemy location.

This helps the engine know when old information should be treated cautiously.

---

# 46. Characters Should Understand Staleness When Appropriate

A veteran intelligence officer should recognize:

> This report is three weeks old.

They should not treat it as current certainty.

Expertise again improves calibration.

---

# 47. Discovery Can Occur Accidentally

Characters may learn things without deliberately investigating.

Examples:

- overheard conversation,
- noticing an injury,
- seeing a familiar symbol.

Passive perception and world events can generate knowledge naturally.

This helps the world feel alive.

---

# 48. Not Every Fact Needs Detailed Knowledge Tracking

To avoid scope creep, we should only track knowledge states when they could meaningfully affect:

- decisions,
- relationships,
- missions,
- secrets,
- progression,
- future events.

We do not need individual knowledge records for every mundane fact.

This is crucial for performance.

---

# 49. Important Facts Should Have Knowledge Graphs

For significant facts, the engine may internally track something like:

**Fact:** Dagar is involved in the Soldier Pills EX project.

Then:

- Character A: Confirmed
- Character B: Suspected
- Character C: Unknown
- Character D: Believes false alternative

This is extremely useful for persistent world simulation.

---

# 50. Knowledge Should Drive NPC Decisions

NPCs should choose actions based on:

> their beliefs and confidence.

Not objective engine truth.

An NPC may:

- pursue the wrong suspect,
- prepare for the wrong technique,
- distrust an innocent person,
- correctly predict an ambush.

Their decisions should make sense from what they know.

This will make NPCs feel much more autonomous.

---

# 51. Characters Can Share Partial Knowledge

When communicating, characters may choose:

- full disclosure,
- selective disclosure,
- misleading disclosure,
- vague warning.

So communication itself changes knowledge states.

This matters for:

- trust,
- espionage,
- leadership,
- secrecy.

---

# 52. Teaching Requires More Than Sharing Facts

Teaching a Skill or technique involves:

- explanation,
- demonstration,
- correction,
- practice.

Simply telling someone:

> "Chakra goes here"

does not grant mastery.

This keeps the boundary between knowledge and skill clear.

---

# 53. Information Can Lower Risk Without Raising Success Chance

Example:

Knowing:

> there is a trap on the left path

may not make crossing the right path easier.

It simply prevents choosing the dangerous route.

This reinforces that knowledge often improves **decision quality**, not direct capability.

---

# 54. Discovery Can Change Perceived Probability

A character may initially think:

> this mission is easy.

After scouting:

---

## Turn b6056cb0-30af-4d84-9697-44fdfb3b5f6b

### User

Ok

### Assistant — 96ae9a9d-7378-459d-8d3b-c3b49dfb92f0

# Ruleset 2.17 — Luck & Exceptional Events

Luck should exist, but it needs a very narrow role.

The central rule should be:

> **Luck can influence which plausible outcome occurs, but it cannot create implausible capability.**

That means luck can help with:

- timing,
- coincidence,
- borderline outcomes,
- incidental discoveries,
- avoiding secondary harm,

but it should not let a weak character suddenly perform an impossible feat.

---

## 1. Luck Is Not a Core Attribute

I do **not** recommend adding Luck as a foundational Attribute alongside:

- Agility,
- Intelligence,
- Strength,
- Endurance,
- Perception,
- Willpower,
- Chakra.

Those are intrinsic capabilities.

Luck is different.

It does not represent what the character can do.

It represents:

> **how uncertainty occasionally breaks around them.**

So luck should sit outside the normal Attribute → Skill structure.

---

# 2. Luck Should Affect Marginal Outcomes Most

Luck matters most when an outcome is already close.

Example:

A character barely misses a rooftop ledge.

A fortunate environmental break might mean:

> their sleeve catches on a protruding hook.

That does not mean they successfully made the jump.

It changes the consequence of the failure.

Likewise, in a narrow success:

> the guard looks away at exactly the right moment.

That can explain why the attempt worked.

This is a good use of luck.

---

# 3. Luck Should Matter Less at Extreme Capability Gaps

If someone is completely outmatched, luck should not rescue them by default.

Example:

A genin trying to overpower a legendary taijutsu specialist.

"He's lucky" is not enough to make that a viable contest.

The plausible outcome space still controls what can happen.

Luck may allow:

- escape,
- distraction,
- accidental opening,

if those were already plausible.

It should not grant:

> dominant victory.

---

# 4. Luck Is Best Applied to Secondary Effects

I think luck should often influence things like:

- whether a weapon jams,
- whether debris falls favorably,
- whether a patrol turns left or right,
- whether a dropped item lands nearby,
- whether a failed action creates an escape opportunity.

These are **secondary uncertainty events**.

That is healthier than giving someone a flat:

> +15% to all checks.

---

# 5. Do Not Add a Universal “Lucky” Bonus

A trait like:

> Lucky: +10 Capability

would distort every system.

Likewise:

> Lucky: +10% success to everything

would be too strong.

Instead, if we eventually allow luck-related traits, they should affect:

- narrow margins,
- rare world events,
- secondary consequences,
- coincidence frequency.

That keeps them flavorful without overwhelming skill.

---

# 6. Luck Should Not Override Prerequisites

No amount of luck should let someone:

- perform a jutsu they do not know,
- use a kekkei genkai they do not possess,
- read a language they have never learned,
- lift something physically impossible.

Prerequisite gates remain absolute unless the situation provides another legitimate method.

---

# 7. Luck Should Not Create Knowledge From Nothing

A lucky character should not randomly know the answer to something outside their experience.

But they might:

- notice a useful clue,
- overhear the right conversation,
- stumble upon the right record.

That preserves causal plausibility.

---

# 8. Coincidences Need Plausible Setup

Exceptional coincidences should still emerge from the world state.

Example:

A patrol happens to pass by.

That is fine if patrols actually operate in the area.

A legendary shinobi appearing from nowhere to rescue the player with no established reason:

> not fine.

The engine should always ask:

> **Was this event actually possible given the current world?**

---

# 9. Rare Events Should Have Their Own Probabilities

Some events are pure chance and should not use character capability.

Examples:

- rare genetic mutation,
- random encounter,
- unusual weather event,
- lottery-like selection,
- rare birth trait.

These should use:

> **world-event probability**

rather than normal resolution.

Luck traits could potentially influence some of these, but only if that design is intentional.

---

# 10. Rare Does Not Mean Impossible

We should preserve genuinely low-probability events.

If an event has:

> 0.1% chance,

it can happen.

The engine should not silently suppress it because it seems too unlikely.

Likewise, it should not force it because it would be interesting.

This is important for a persistent simulation.

---

# 11. Rare Events Should Not Be Forced for Drama

The engine should never decide:

> The game has been quiet, so something extremely rare happens now.

That would violate our anti-narrative-adjustment rules.

Rare events should occur because their actual conditions and probabilities support them.

---

# 12. No “You’re Due” Logic

Probability should not compensate for streaks.

If an event has a 1% chance each month, failing to get it for 50 months does not automatically make the next month more likely unless the underlying event actually has increasing hazard over time.

This is the same anti-pity principle from earlier.

---

# 13. Luck Can Affect Outcome Margin Very Slightly

If we do want persistent luck traits, one possible implementation is to influence **very close outcomes**.

For example:

A Lucky trait might occasionally shift an Outcome Margin by a few points when:

> |Outcome Margin| is small.

This would mean luck matters most around:

- narrow success,
- narrow failure.

It would not convert:

> −35

into:

> +10.

I think this is much safer than broad probability bonuses.

---

# 14. Lucky Traits Could Affect Consequence Selection

Another option is for luck traits to alter the **failure floor** or secondary outcome.

Example:

Two characters both narrowly fail a jump.

Normal character:
> grabs the ledge awkwardly and drops equipment.

Lucky character:
> grabs the ledge cleanly.

The objective still failed.

The consequence was slightly kinder.

This is probably one of the best places for luck to operate.

---

# 15. Unlucky Traits Should Also Be Bounded

An unlucky character should not become incompetent.

Bad luck might increase:

- inconvenient coincidences,
- secondary complications,
- poor incidental timing.

But it should not turn routine mastered actions into constant failures.

That would undermine character development.

---

# 16. Luck Should Never Be Used to Explain Bad Simulation

We should avoid lazy narration like:

> "You got unlucky."

when the real reason should be:

- stronger opponent,
- poor preparation,
- difficult terrain,
- low skill.

Luck should only be invoked when random variation genuinely mattered.

---

# 17. Environmental Luck

Some lucky events come from the surroundings.

Examples:

- loose branch breaks under pursuer,
- sudden gust obscures vision,
- dropped kunai lands within reach.

These should only be possible if the environment supports them.

The engine should not create arbitrary props.

---

# 18. Social Luck

Chance can also affect social situations.

Examples:

- overhearing useful information,
- meeting a useful contact,
- encountering someone in a good mood.

But personality and relationship still matter.

Luck may create the opportunity.

It does not automatically make the interaction successful.

---

# 19. Opportunity Luck vs Performance Luck

I think this distinction is very useful.

### Opportunity Luck
A favorable situation happens to appear.

Example:
> the guard leaves their post early.

### Performance Luck
A borderline action breaks favorably.

Example:
> your foot slips, but you recover.

Opportunity Luck changes the circumstances.

Performance Luck affects the resolution edge.

These are different and should be treated separately.

---

# 20. Opportunity Luck Should Usually Create Choices

A lucky opportunity is most interesting when it gives the player something to act on.

Example:

> You notice the patrol route has an unexpected gap.

The player still decides whether to exploit it.

This is better than:

> luck automatically solves the mission.

---

# 21. Exceptional Events Should Be Categorized

We could internally divide exceptional events into:

### Rare Natural Events
Weather, mutations, unusual environmental events.

### Rare Social Events
Chance meetings, unexpected opportunities.

### Rare System Events
Unusual career openings, institutional changes.

### Rare Personal Events
Exceptional talent expression, unusual inheritance.

Each category may use different generation logic.

---

# 22. Exceptional Events Should Respect Population Scale

A very rare event may still occur frequently in a large enough population.

Example:

If something happens to 1 in 10,000 people, a large shinobi village may still occasionally produce one.

This is useful for world generation.

Rare should be interpreted relative to:

- population,
- time span,
- exposure opportunities.

---

# 23. Exceptional Characters Should Be Rare for a Reason

If the simulator generates prodigies, unusual bloodline expressions, or extreme talents, they should emerge from:

- inheritance,
- mutation,
- training,
- rare circumstances,
- explicit world probabilities.

Not because every major NPC needs to be interesting.

That supports the simulation-over-fanfiction philosophy.

---

# 24. Luck Should Not Cluster Around the Player

The player should not become a magnet for rare events.

If a rare clan heir appears, a meteor falls, a legendary artifact surfaces, and a forbidden technique is rediscovered, those should not all happen near the protagonist by default.

Exceptional events should occur wherever world conditions support them.

The player may or may not intersect with them.

---

# 25. NPCs Get Luck Too

NPCs should receive the same random-event logic.

They can:

- stumble into opportunities,
- suffer bad timing,
- encounter rare events.

The player should not monopolize favorable coincidence.

---

# 26. Luck Should Be Persistent Only If Explicitly Modeled

Most random variation should be event-specific.

We should not secretly decide:

> this character is lucky

unless they actually possess a defined trait or condition.

Otherwise, random streaks are just random streaks.

This avoids post-hoc personality assignment.

---

# 27. Luck Traits Should Be Rare

If we do create traits such as:

- Fortunate,
- Unfortunate,
- Serendipitous,

they should be uncommon and modest.

They should feel distinctive, not mandatory.

I would avoid making Luck a standard stat every character has to optimize.

---

# 28. Luck Can Affect Event Frequency More Safely Than Skill Checks

A luck trait might reasonably affect:

- chance encounters,
- beneficial incidental finds,
- minor environmental fortune.

That is often safer than altering core success probability.

For example:

Fortunate character may be slightly more likely to:

> discover a useful discarded tool.

But they still need the relevant Skill to use it effectively.

---

# 29. Luck Can Reduce Catastrophic Escalation

Another good application:

On a severe failure where multiple consequences are plausible, a fortunate character may be slightly more likely to receive:

> the less severe plausible consequence.

This still respects the failure.

It just changes which branch of the consequence space occurs.

---

# 30. Luck Should Be Symmetrical in Principle

If good luck exists, bad luck should also be possible.

However, we do not need to force equal amounts over time.

That would recreate anti-streak balancing.

Randomness should be allowed to produce:

- lucky streaks,
- unlucky streaks.

They just should not rewrite capability.

---

# 31. Exceptional Events Should Be Recorded When Persistent

If something rare happens and changes the world, it becomes permanent world state.

Example:

- rare mutation,
- unexpected political death,
- discovery of lost ruins.

It should not be treated as a temporary random event that can later be contradicted.

---

# 32. Rare Events Can Create New Systems Without Breaking Old Ones

Example:

A character is born with an unusual chakra mutation.

That may create:

- new traits,
- altered skill access,
- special progression.

But once generated, it should integrate into the normal rules.

The event is rare.

The character is not thereafter exempt from mechanics.

---

# 33. “Miracle” Events Should Be Extremely Restricted

I would avoid true miracle mechanics almost entirely.

If something has no plausible causal path, the engine should not use luck to justify it.

A miracle should only exist if:

- supernatural forces in the setting explicitly allow it,
- the relevant mechanic supports it.

Naruto has supernatural systems, but they still have rules.

Luck should not become an undefined supernatural force.

---

# 34. Plot Coincidence Is Not Luck

This distinction is important.

Bad:

> The exact person you need happens to walk into the room because it would move the plot forward.

Better:

> That person has a reason to be nearby, and a low-probability encounter roll happens to place them there.

The second is simulated coincidence.

The first is narrative manipulation.

---

# 35. Luck Should Be Explainable After the Fact

When a lucky or unlucky event matters, the engine should be able to explain:

> what actually happened.

Examples:

- the patrol was delayed,
- the weapon struck a weak point,
- the branch broke,
- the witness happened to be nearby.

We should not narrate:

> "Luck was on your side."

unless used stylistically.

The world should still have a concrete causal event.

---

# 36. Chance Events Can Be Hidden

The player does not need to know when a rare world-event roll occurs.

For example:

An NPC elsewhere may randomly receive:

- a job opportunity,
- encounter,
- injury,
- relationship event.

The simulation simply updates the world.

This supports autonomous world progression.

---

# 37. Opportunity Windows

Some random events should create temporary opportunities.

Example:

A security captain unexpectedly leaves the compound.

That creates:

> reduced security for two hours.

The opportunity persists for a realistic duration.

This lets chance interact with strategy.

---

# 38. Rare Events Can Also Create Problems

Not every exceptional event should benefit the player.

Examples:

- unexpected storm,
- equipment defect,
- epidemic,
- faction upheaval.

Again, these must arise from plausible world logic and probability.

---

# 39. Luck Does Not Determine Morality or Intent

Chance can determine:

> who encounters whom.

It should not determine:

> whether someone suddenly betrays a friend

unless their existing motives make betrayal plausible.

Psychological decisions remain character-driven.

---

# 40. Recommended Luck Procedure

When chance beyond normal capability resolution may matter:

### Step 1 — Determine Event Type
Is this:
- normal resolution randomness,
- opportunity luck,
- world-event probability,
- consequence variation?

### Step 2 — Check Plausibility
Can this event actually happen in the current world state?

### Step 3 — Determine Base Probability
Derived from world conditions, not narrative needs.

### Step 4 — Apply Explicit Luck Traits if relevant
Only bounded effects.

### Step 5 — Resolve Once
No pity or anti-streak logic.

### Step 6 — Convert to Concrete Causal Event
What actually happened?

### Step 7 — Persist Consequences
If the event changes the world, record it.

---

# Example — Narrow Combat Escape

Character barely fails to dodge.

Possible consequence:

> They are hit.

But a favorable incidental circumstance exists:

> loose debris shifts beneath the attacker's foot.

A luck effect might turn:

> solid hit

into:

> glancing hit.

It should not become:

> attacker spontaneously dies.

---

# Example — Chance Encounter

The player is searching for information in town.

A relevant NPC has a legitimate reason to frequent that district.

There may be some probability they cross paths.

If the encounter occurs:

> opportunity created.

The player still has to recognize, approach, and interact with them successfully.

---

# Example — Rare Talent

A child may have a very low probability of an unusually strong natural chakra affinity based on:

- genetics,
- family traits,
- rare variation.

If generated:

> that becomes part of the character's permanent baseline.

It should not be rerolled later because the story needs a prodigy.

---

# What I Would Lock In

> **Luck exists outside the normal Attribute/Skill hierarchy.**

> **Luck influences uncertainty, coincidence, and consequence selection—not fundamental capability.**

> **Luck is strongest around borderline outcomes and secondary effects.**

> **Luck cannot bypass prerequisites or make impossible actions possible.**

> **Opportunity luck and performance luck are distinct.**

> **Pure chance events use world-event probabilities rather than character resolution.**

> **Rare events are never forced for drama and are never suppressed merely because they are rare.**

> **There is no pity system, anti-streak balancing, or “you are due” logic.**

> **Luck traits, if used, should be rare, bounded, and preferably influence marginal outcomes or incidental events rather than all checks.**

> **NPCs and the player use the same luck logic.**

> **Exceptional events should occur across the world, not cluster around the protagonist.**

> **Every meaningful lucky event should still have a concrete causal explanation.**

> **Once a rare event changes the world, its consequences become persistent state.**

Next should be **Ruleset 2.18 — Critical Events**, where we can define whether we even need a separate concept of “critical success/failure” now that we already have outcome margins—and, if we keep it, exactly when an outcome deserves to be considered truly exceptional rather than just a very good or very bad result.

---

## Turn 18504b76-d788-414e-904a-a50a72117096

### User

Ok

### Assistant — 6fe4c5d4-1f0a-47fd-b400-c5ff73882085

# Ruleset 2.18 — Critical Events

Because we already have **degrees of success/failure** and **outcome margins**, I do not think we need traditional RPG-style criticals.

The central rule should be:

> **A critical event is not a special die result. It is an unusually consequential outcome that emerges from capability, context, margin, and stakes.**

That means no:

- natural 20,
- natural 1,
- automatic crit chance,
- universal double damage,
- random catastrophic failure table.

Instead, “critical” describes what actually happened.

---

## 1. Critical Success Should Mean Exceptional Impact, Not Just Exceptional Performance

We already have **Exceptional Success** as an outcome degree.

A Critical Success should be rarer and more contextual.

It occurs when:

1. the action succeeds exceptionally well,
2. the situation contains room for an unusually valuable outcome,
3. the result creates a meaningful secondary consequence.

Example:

A strong Tracking success might locate the target quickly.

A critical tracking event might also reveal:

- the target is injured,
- they changed direction suddenly,
- another group is following them.

The difference is not just “bigger number.”

It is a meaningful consequence created by unusually strong execution.

---

## 2. Critical Failure Should Mean Exceptional Consequence, Not Just Bad Performance

Likewise, severe or catastrophic-range failure does not automatically mean a Critical Failure.

For a critical failure to occur:

1. performance must be sufficiently poor,
2. serious hazards must actually exist,
3. the character must be exposed to them,
4. safeguards must fail or be absent.

So:

> **Bad roll + no hazard = ordinary failure.**

Example:

Severely fail a history quiz:
> wrong answer.

Severely fail an unstable explosive-seal experiment:
> potential critical event.

---

# 3. Critical Events Require Opportunity

This should be one of the main rules.

An action can only produce a critical outcome if the situation contains a plausible **critical opportunity** or **critical hazard**.

Examples of critical opportunities:

- exposed enemy weak point,
- unstable structure,
- key evidence hidden among searched records,
- major negotiation concession,
- chance to prevent cascading failure.

Examples of critical hazards:

- lethal drop,
- unstable chakra reaction,
- explosive equipment,
- fragile patient,
- political scandal.

Without one of these, no critical event occurs.

---

# 4. No Universal Critical Percentage

There should not be:

> 5% crit chance.

Critical outcomes should be rarer or more common depending on context.

A delicate experimental procedure may have meaningful critical-failure potential.

A routine cooking task usually does not.

The system should evaluate the actual situation rather than apply one universal chance.

---

# 5. Critical Events Should Usually Require Extreme Outcome Margins

A large positive or negative Outcome Margin should be a prerequisite.

For example, something like:

- +40 or greater may qualify for critical-success evaluation,
- −40 or lower may qualify for critical-failure evaluation.

But crossing that threshold should only trigger:

> “Check whether a critical event is plausible.”

Not:

> “Automatically generate one.”

This preserves context.

---

# 6. Experts Should Produce More Positive Critical Opportunities

Because high success probability creates larger positive Outcome Margins more often, highly skilled characters should naturally produce more exceptional and occasionally critical successes.

That makes sense.

A master swordsman is more likely than a novice to create:

- perfect positioning,
- clean disarm,
- precise interruption.

This is better than giving everyone the same crit chance.

---

# 7. Experts Should Almost Never Suffer Random Critical Failure on Routine Tasks

Likewise, a 95% success action can only fail narrowly under our current outcome model.

So catastrophic critical failure becomes naturally impossible unless:

- the situation itself changes,
- hidden hazards exist,
- the character suffers a severe external disruption.

This protects established competence.

---

# 8. Weak Characters Should Not Gain Huge Critical Successes From Long-Shots

If a character has only 5% success probability, their successful Outcome Margin is inherently small.

That means their success should usually be:

> narrow.

So a desperate underdog success does not suddenly become:

> overwhelming victory.

This is one of the strongest features of our current model.

---

# 9. Critical Success Cannot Exceed Plausible Capability

An exceptional hit from a genin against an elite jonin might:

- interrupt them,
- exploit a tiny opening,
- force repositioning.

It should not become:

> instant kill

unless such an outcome was already plausibly available.

Critical success means:

> best plausible consequence.

Not:

> ignore the power system.

---

# 10. Critical Failure Cannot Invent New Hazards

Likewise, a critical failure cannot create something that was never present.

If a character fails a stealth attempt in an empty hallway:

- they may make noise,
- leave evidence.

They do not:

> trigger an explosion

unless an explosive hazard actually exists.

This should be strict.

---

# 11. Critical Events Should Often Be Secondary Consequences

A useful model is:

Primary objective resolves normally.

Then, if outcome degree and context support it, a major secondary effect occurs.

Example:

Primary:
> successfully disarm enemy.

Critical secondary:
> their weapon is knocked into a location they cannot recover from easily.

This is more grounded than replacing the primary action with an exaggerated effect.

---

# 12. Critical Success Can Create Persistent Advantage

Examples:

- expose an enemy weakness,
- gain dominant position,
- discover extra intelligence,
- save substantial resources,
- build major trust,
- complete a milestone early.

These are interesting because they affect future world state.

---

# 13. Critical Failure Can Create Persistent Complication

Examples:

- equipment destroyed,
- identity exposed,
- serious injury,
- irreversible evidence loss,
- political relationship damaged.

Again, only where causally supported.

---

# 14. Critical Events Can Alter Outcome Ceiling/Floor

Some situations make unusually strong outcomes impossible.

Example:

A wooden practice sword cannot decapitate someone through normal use.

Likewise, safety systems may prevent catastrophic consequences.

So the engine should define:

### Outcome Ceiling
Best possible result.

### Outcome Floor
Worst possible result.

Critical events operate within those bounds.

---

# 15. Safeguards Can Remove Critical Failure

This is important.

Example:

A character performs dangerous chakra experimentation.

Without containment:
> critical backlash possible.

With proper containment:
> failure may still happen, but catastrophic escalation is blocked.

This makes preparation mechanically meaningful.

---

# 16. Vulnerabilities Can Enable Critical Success

Likewise, identifying a real weakness may raise the outcome ceiling.

Example:

Normally:
> attack can only injure.

After discovering a precise structural weakness:
> decisive disable becomes plausible.

The critical possibility comes from knowledge and setup, not luck alone.

---

# 17. Critical Hits in Combat Should Be Derived, Not Universal

Later combat rules should not simply use:

> crit = double damage.

Instead, a critical combat event may depend on:

- target anatomy,
- armor,
- positioning,
- attack type,
- exposed weak point,
- technique.

Possible effects:

- severe wound,
- disarm,
- interrupted jutsu,
- destroyed equipment,
- positional collapse.

This keeps combat grounded in the rest of the system.

---

# 18. Critical Social Outcomes Should Remain Bounded

A critical persuasion result might:

- create strong trust,
- gain an unexpected concession,
- convert uncertainty into support.

But it still cannot violate the NPC’s core values or plausible decision space.

Again:

> no social mind control.

---

# 19. Critical Information Outcomes

A critical information event might reveal:

- hidden connection,
- extra clue,
- decisive contradiction,
- deeper technical understanding.

But only if that information is actually available to discover.

No omniscient revelation.

---

# 20. Critical Crafting Outcomes

A critical crafting result might:

- improve durability,
- reduce material waste,
- produce unusually high quality,
- reveal a better technique.

It should not spontaneously generate:

> legendary artifact

from ordinary materials and novice skill.

---

# 21. Critical Training Outcomes

A rare training breakthrough might:

- complete a milestone early,
- unlock insight,
- improve mastery more efficiently.

But it should not skip prerequisites or entire Skill tiers.

Breakthroughs accelerate valid progression.

They do not bypass it.

---

# 22. Critical Medical Outcomes

An exceptional medical result might:

- stabilize faster,
- reduce recovery time,
- preserve tissue,
- prevent complication.

But it should not:

> regenerate an impossible injury

without an ability capable of doing so.

---

# 23. Critical Events Should Not Happen Too Often

Because the term “critical” should mean something, they should be relatively rare.

Most actions should resolve as:

- ordinary success,
- strong success,
- narrow failure,
- ordinary failure.

Critical outcomes should feel notable because the situation genuinely produced one.

---

# 24. Not Every Extreme Outcome Margin Needs Special Narration

Even if the margin is huge, the action may be too mundane.

Example:

An expert opens an ordinary unlocked window exceptionally well.

Nothing special needs to happen.

The engine should suppress meaningless “critical” presentation.

---

# 25. Critical Events Should Be Memorable When They Matter

If a critical event materially changes the simulation, it should be recorded in persistent state.

Examples:

- major injury,
- breakthrough discovery,
- destroyed bridge,
- exposed conspiracy.

This can influence later events.

---

# 26. Critical Outcomes Should Be Cause-Specific

Instead of generic labels:

> Critical Failure!

the engine should understand:

> containment seal ruptured due to unstable chakra feedback.

That is much more useful for the simulation.

---

# 27. Critical Events Can Trigger Follow-Up States

Example:

Critical stealth failure:
> full alarm.

That creates:

- alert state,
- pursuit,
- locked exits.

The critical event does not need a separate extra “punishment roll.”

It changes the world state.

---

# 28. Avoid Critical Cascades

One critical failure should not automatically trigger another and another.

Example:

Bad experiment:
> explosion.

We should resolve the explosion at an appropriate scale rather than:

- roll explosion,
- roll fall,
- roll fire,
- roll debris,
- roll panic,

unless distinct decisions actually exist.

This follows minimum necessary resolution.

---

# 29. Critical Success Should Not Guarantee Future Success

A major advantage can still be lost.

Example:

Critical infiltration success:
> you gain perfect initial access.

That does not make the entire mission automatic.

It simply creates a strong new state.

Future uncertainty remains.

---

# 30. Critical Failure Should Not Automatically End the Story

Likewise, a major failure may produce:

- capture,
- injury,
- exposure,
- resource loss.

The simulation should continue whenever logically possible.

A severe setback can create new gameplay.

---

# 31. Critical Events Can Occur in Opposed Resolution

In a contest, a dominant outcome may create a major positional or strategic effect.

Example:

One shinobi overwhelmingly wins a grappling contest.

Possible critical effect:
> opponent's arm becomes trapped in a position that prevents hand seals.

This should emerge from:

- extreme margin,
- plausible positioning,
- available anatomy.

Not from a universal crit table.

---

# 32. Critical Events Can Occur Without Direct Character Action

Rare world events can also be critical in consequence.

Example:

- landslide destroys key road,
- village leader unexpectedly dies,
- major fire destroys archives.

But these belong to world-event probability rather than character critical mechanics.

We should keep those concepts distinct.

---

# 33. Critical Event vs Rare Event

Useful distinction:

### Critical Event
Extreme consequence arising from a specific resolution.

### Rare Event
Low-probability world occurrence independent of a specific skill resolution.

Example:

Critical:
> sealing experiment catastrophically fails.

Rare:
> lightning strikes the laboratory during a storm.

They can interact, but they are not the same system.

---

# 34. Recommended Critical Success Procedure

After a very strong success:

### Step 1
Did the primary objective succeed exceptionally well?

### Step 2
Does the situation contain an additional plausible opportunity?

### Step 3
Would exploiting it remain within capability and outcome space?

### Step 4
If yes, create a meaningful secondary benefit.

### Step 5
Persist it if relevant.

If any answer is no:

> simply treat it as exceptional success.

---

# 35. Recommended Critical Failure Procedure

After an extreme failure:

### Step 1
What hazards were actually present?

### Step 2
Was the character exposed to them?

### Step 3
Were safeguards present?

### Step 4
Does the outcome degree justify major escalation?

### Step 5
Select the worst causally plausible consequence within the outcome floor.

If no major hazard exists:

> ordinary severe failure is enough.

---

# 36. Critical Events Should Never Be Mandatory

This is probably the most important design safeguard.

The engine should never think:

> I got an extreme roll, therefore something spectacular must happen.

Sometimes the correct result is simply:

> very clean success.

or:

> very poor failure.

That restraint will keep the simulation grounded.

---

# What I Would Lock In

> **Traditional natural-20/natural-1 critical mechanics do not exist.**

> **Critical events emerge from extreme outcome degree plus context, opportunity, hazard, and stakes.**

> **Exceptional Success and Critical Success are not identical; critical outcomes require meaningful extra consequence.**

> **Catastrophic-range failure does not automatically create a critical failure.**

> **Critical success cannot exceed the plausible outcome ceiling.**

> **Critical failure cannot exceed the plausible outcome floor or invent hazards.**

> **Safeguards can remove catastrophic failure branches.**

> **Identified vulnerabilities can create new critical-success opportunities.**

> **Critical events should usually modify persistent world state rather than merely multiply numbers.**

> **Critical events should remain relatively rare and only be highlighted when they actually matter.**

> **No infinite critical cascades or generic critical tables.**

This keeps the strongest outcomes fully compatible with the rest of the resolution system instead of adding a contradictory “critical hit” subsystem on top.

Next should be **Ruleset 2.19 — Resource Expenditure & Resolution**, where we define how a character can deliberately spend **chakra, stamina, time, money, consumables, equipment durability, or other resources** to improve performance—and how we prevent “spend more chakra = automatically stronger” from becoming exploitable.

---

## Turn db48f673-86e0-4377-bc4a-4ca3bb65c854

### User

Ok

### Assistant — efc9c16e-00d0-49ec-8235-cd9c0319de5a

# Ruleset 2.19 — Resource Expenditure & Resolution

This section should govern how characters deliberately trade resources for better performance, safety, speed, or flexibility.

The central rule should be:

> **Resources improve resolution only when spending them causally changes what the character can do.**

That means no generic mechanic like:

> Spend 10 Chakra for +10 to any check.

Instead, the resource needs to have a clear function.

## 1. Main Resource Categories

The most important resources likely include:

- Chakra
- Stamina
- Time
- Consumables
- Equipment durability
- Money/materials
- Attention/concentration
- Social capital or favors
- Limited-use abilities

Different resources should affect resolution in different ways.

---

# 2. Resource Spending Can Affect Several Things

A resource expenditure may:

- increase Effective Capability,
- reduce Difficulty,
- unlock a stronger method,
- improve outcome ceiling,
- reduce failure severity,
- speed up completion,
- enable another attempt,
- sustain an action longer.

We should not force every expenditure into a simple bonus.

---

# 3. Chakra Expenditure

Chakra is the most obvious Naruto-specific resource.

Spending more chakra may sometimes improve:

- power,
- range,
- duration,
- stability,
- speed,
- area of effect.

But this should depend on the technique.

A technique must explicitly support additional chakra investment.

Otherwise:

> more chakra ≠ automatically better.

---

# 4. Techniques Need Chakra Efficiency

Two characters may produce the same effect while spending different amounts of chakra.

That gives us an important distinction:

### Chakra Output
How much chakra is committed.

### Chakra Efficiency
How effectively that chakra is converted into the intended result.

A highly skilled shinobi may achieve more with less.

This makes Chakra Control and mastery matter.

---

# 5. Overcharging a Technique Should Have Limits

Some techniques may tolerate extra chakra.

Others may become:

- unstable,
- wasteful,
- physically dangerous.

So every technique should eventually define a **safe operating range**.

Above that range:

- efficiency may fall,
- failure risk may rise,
- backlash may become possible.

This prevents brute-forcing every problem with huge chakra expenditure.

---

# 6. Chakra Reserves and Chakra Output Are Different

A character may have large reserves but poor ability to release or control them efficiently.

Likewise, another character may have modest reserves but excellent control.

So resource systems should distinguish:

- total available chakra,
- maximum usable output,
- control/efficiency,
- technique-specific demands.

This fits very well with our earlier decision to keep Chakra Control and reserves outside the core Attribute list.

---

# 7. Stamina Expenditure

Characters may push themselves physically to improve:

- speed,
- force,
- endurance,
- reaction.

But increased effort should create costs such as:

- fatigue,
- slower recovery,
- injury risk.

So “push harder” can improve immediate capability while worsening later state.

That creates meaningful tradeoffs.

---

# 8. Exertion Levels

We may eventually want broad exertion modes like:

- Relaxed
- Normal
- Strenuous
- Maximum effort
- Overexertion

These would not be universal bonuses.

Instead, they determine:

- resource consumption,
- sustainable duration,
- injury risk,
- accessible performance ceiling.

This could later integrate with combat and travel.

---

# 9. Overexertion

A character should be able to exceed their sustainable performance temporarily.

But doing so may cause:

- rapid fatigue,
- muscle strain,
- chakra pathway stress,
- collapse,
- injury.

Overexertion should be a strategic emergency option, not a free buff.

---

# 10. Time as a Resource

Time is one of the most flexible resources.

Characters can spend more time to:

- inspect carefully,
- prepare properly,
- reduce errors,
- gather information,
- improve quality.

Or spend less time to:

- act before the enemy,
- meet deadlines,
- escape danger.

Time therefore interacts with both Difficulty and stakes.

---

# 11. Taking More Time Should Have Diminishing Returns

Extra time helps most when the original attempt is rushed.

Example:

30 seconds → 5 minutes:
> major improvement.

5 minutes → 30 minutes:
> moderate improvement.

30 minutes → 3 hours:
> may provide almost no further benefit.

This prevents infinite preparation-time exploitation.

---

# 12. Consumables

Consumables may include:

- medicine,
- soldier pills,
- antidotes,
- explosive tags,
- food,
- special ammunition.

Their effects should be specific.

A soldier pill might:

- temporarily increase available chakra,
- suppress fatigue,
- increase recovery.

But perhaps create:

- crash,
- metabolic stress,
- injury risk.

Consumables should modify actual state, not simply provide arbitrary check bonuses.

---

# 13. Consumables Should Not Stack Without Limit

Repeated use may cause:

- diminishing returns,
- toxicity,
- tolerance,
- severe side effects.

This is especially important for powerful performance-enhancing items.

Otherwise resource-rich characters could endlessly stack temporary boosts.

---

# 14. Equipment Durability

Some equipment should degrade through use.

Characters may deliberately stress equipment for better performance.

Example:

- push a weapon beyond safe limits,
- overload a device,
- use a seal at maximum output.

This may improve immediate effect at the cost of:

- damage,
- failure,
- destruction.

This creates another tradeoff.

---

# 15. Money and Materials

In long-term tasks, spending more resources may improve:

- equipment quality,
- access to experts,
- research capacity,
- redundancy,
- safety.

But money itself should not become:

> +20 Research.

It changes what tools and methods are available.

---

# 16. Social Capital

Characters may spend:

- favors,
- reputation,
- political goodwill,
- personal relationships.

Example:

Calling in a favor might:

- gain restricted access,
- secure assistance,
- bypass bureaucracy.

This is a real resource expenditure because the favor may no longer be available later.

This should be tracked socially, not as currency alone.

---

# 17. Attention and Concentration

Attention is a limited resource in active scenes.

A character may be able to:

- watch one opponent closely,
- maintain a sensory technique,
- perform delicate chakra control.

Trying to do several at once may reduce performance.

This will matter especially in combat and multitasking.

---

# 18. Sustained Techniques Should Consume Ongoing Resources

Some abilities should require continuous:

- chakra,
- concentration,
- stamina.

The question is not only:

> Can you activate it?

but:

> How long can you maintain it?

This creates a meaningful endurance dimension.

---

# 19. Resource Spending Can Raise the Outcome Ceiling

Sometimes spending more does not primarily improve success chance.

It improves the maximum effect.

Example:

A Fire Release technique may already be reliable.

Additional chakra could increase:

- size,
- range,
- destructive output.

That is different from:

> making activation more likely.

This distinction is important.

---

# 20. Resource Spending Can Improve Reliability

Other expenditures may improve the probability of success.

Example:

A medic uses additional supplies and monitoring equipment.

That may:

- reduce procedural Difficulty,
- mitigate complications.

Again, the method matters.

---

# 21. Resource Spending Can Reduce Risk

Some expenditures are purely protective.

Examples:

- backup seals,
- safety equipment,
- antidote preparation,
- reserve chakra.

These may leave success probability unchanged while improving failure floor.

That should be strategically valuable.

---

# 22. Resource Spending Can Buy Speed

A character may spend extra resources to act faster.

Examples:

- use Body Flicker instead of running,
- hire more workers,
- use more chakra to accelerate a process.

The tradeoff:

- resource consumption,
- fatigue,
- reduced efficiency,
- risk.

This is especially relevant in urgent situations.

---

# 23. Resource Spending Can Buy Flexibility

Some resources allow a character to keep options open.

Example:

Holding chakra in reserve may let them:

- defend,
- escape,
- respond to surprises.

Spending everything early may create higher immediate power but worse later flexibility.

This should make resource management strategically meaningful.

---

# 24. Maximum Output Should Be Limited

A character cannot necessarily spend their entire chakra pool in one instant.

There should eventually be limits such as:

- maximum chakra output,
- technique throughput,
- physical tolerance.

Otherwise characters with large reserves would be able to dump everything into one action.

This belongs partly in the Chakra/Jutsu ruleset, but Resolution should respect it.

---

# 25. Resource Efficiency Should Reward Mastery

Mastery can improve:

- chakra cost,
- stamina cost,
- time required,
- material waste.

This creates a major advantage for experienced characters without necessarily increasing raw success probability.

That is excellent for incremental progression.

---

# 26. Resource Shortage Should Change Resolution

If a character lacks enough resources:

- some actions become impossible,
- some become weaker,
- some become riskier,
- some require alternative methods.

Do not just apply:

> −10 because low chakra.

The effect depends on the technique.

---

# 27. Resource Depletion Should Affect Future State

A character who spends heavily now should feel that later.

Examples:

- lower chakra reserves,
- higher fatigue,
- fewer tools,
- less money,
- no remaining medicine.

Resources are persistent state, not isolated check modifiers.

---

# 28. Reserve Thresholds

Characters may behave differently at different resource levels.

For example:

- Healthy reserves
- Reduced reserves
- Low reserves
- Critical reserves
- Depleted

At low reserves, some techniques may:

- cost more proportionally,
- become unavailable,
- carry higher physical stress.

These thresholds should be system-specific rather than one universal penalty table.

---

# 29. Exhaustion From Resource Use Should Be Causal

Running out of chakra should not necessarily mean:

> instantly unconscious.

It depends on:

- how depleted,
- what technique was used,
- character condition,
- chakra system mechanics.

Likewise, stamina depletion may cause:

- slowing,
- poor recovery,
- collapse.

We should avoid overly simplistic depletion effects.

---

# 30. Characters Can Intentionally Hold Back

This is important.

A powerful character may deliberately use less:

- chakra,
- force,
- speed.

Reasons:

- avoid injury,
- conserve resources,
- avoid revealing power,
- reduce collateral damage.

So resolution needs to support **chosen output below maximum capability**.

---

# 31. Holding Back Changes Effective Capability

If someone intentionally limits themselves, the engine should calculate the action using the capability they are actually applying.

This prevents:

> elite character automatically using full power for every trivial action.

It also enables sparring and concealment.

---

# 32. Resource Expenditure Should Be Declared Before Resolution When Deliberate

If a player chooses:

> I spend extra chakra to strengthen the barrier,

that decision should normally happen before the outcome is resolved.

Otherwise players could spend resources only after seeing failure.

Exceptions can exist for abilities explicitly designed as reactions.

---

# 33. Reactive Expenditure

Some abilities may allow:

- spend chakra after being hit,
- consume a resource to recover,
- sacrifice equipment to avoid injury.

These should be explicit mechanics.

They are not generic retroactive rerolls.

---

# 34. Resource Spending Should Not Guarantee Success

Even large expenditure may not overcome:

- poor skill,
- impossible matchup,
- missing prerequisite.

Example:

A novice cannot fix terrible chakra control simply by dumping more chakra into an advanced technique.

They may actually make it more unstable.

This is essential.

---

# 35. Skill Determines How Well Resources Are Converted Into Performance

This should be one of the defining principles.

Two characters spend:

> 20 chakra.

Character A has poor control.

Character B has elite control.

They should not necessarily produce equal results.

Resource quantity and conversion efficiency are distinct.

---

# 36. Diminishing Returns on Output

Many systems should have diminishing returns.

Example:

10 additional chakra may produce substantial improvement.

Another 10 may produce less.

Another 10 may mostly create instability.

This gives us a natural limit to brute-force scaling.

---

# 37. Some Abilities May Have Threshold Effects

Not everything needs smooth scaling.

Example:

A barrier may require at least:

> 30 chakra

to activate.

Below that:
> no effect.

Between 30–50:
> standard barrier.

Above 50:
> may increase durability.

This allows more diverse technique design.

---

# 38. Resource Spending and Outcome Degree

Strong results may sometimes reduce actual resource cost.

Example:

A highly efficient execution uses less chakra than expected.

A narrow success might require:

- extra chakra,
- extra time.

This gives degree of success another meaningful output.

But resource variance should remain within plausible bounds.

---

# 39. Failure May Still Consume Full Resources

Attempting a technique and failing does not necessarily refund chakra.

Depending on the failure:

- full cost may be spent,
- partial cost,
- perhaps more than expected due to inefficiency.

This should depend on where failure occurred.

---

# 40. Aborted Actions

A character may stop an action before completion.

Depending on timing, they may:

- recover some resources,
- lose some,
- avoid greater risk.

This supports tactical decisions.

---

# 41. Resource Commitment Can Create Vulnerability

Spending heavily may leave the character exposed.

Examples:

- high chakra expenditure lowers reserves,
- maintaining a barrier occupies concentration,
- charging a technique limits movement.

So stronger output may come with structural disadvantages.

This is preferable to simple cost accounting.

---

# 42. Resource Expenditure Should Inform NPC Decisions

NPCs should consider:

- current reserves,
- future needs,
- mission length,
- perceived threat.

A cautious shinobi may conserve chakra.

A desperate one may burn everything immediately.

This will later feed into NPC decision-making.

---

# 43. Hidden Resource Information

Characters should not automatically know another person's exact reserves.

They may estimate from:

- visible fatigue,
- sensory ability,
- known techniques,
- observed expenditure.

So resource states can also participate in information uncertainty.

---

# 44. Resource Recovery

Recovery should be separate from expenditure.

Possible recovery sources:

- rest,
- food,
- medicine,
- chakra transfer,
- sleep,
- time.

Recovery rates should later depend on:

- Endurance,
- Chakra,
- injuries,
- traits.

Ruleset 2 only needs to establish that depleted resources persist until recovered.

---

# 45. No Free Between-Scene Reset

This should be explicit.

The engine should not automatically restore:

- chakra,
- stamina,
- consumables,

just because a scene ended.

Persistent state matters.

That is essential for mission pacing and life simulation.

---

# 46. Strategic Resource Budgeting

The player should sometimes face choices like:

> Use the expensive technique now?

> Save chakra for extraction?

> Spend money on better equipment?

> Use the antidote preemptively or save it?

These decisions should be mechanically meaningful because resources carry forward.

---

# 47. Resources in Extended Tasks

Extended projects may consume resources per work cycle.

Examples:

- research materials,
- lab fees,
- chakra,
- training equipment.

Insufficient resources can:

- slow progress,
- block milestones,
- increase risk.

This connects directly to 2.13.

---

# 48. Resource Expenditure Should Remain Domain-Specific

We should resist creating one universal resource-spend formula.

Chakra, money, time, and social favors are too different.

What we need is one universal principle:

> **Spending a resource changes resolution only through the real mechanism that resource enables.**

That keeps the system flexible.

---

# 49. Recommended Resource Expenditure Procedure

Before an action:

### Step 1 — Identify available resources.

### Step 2 — Determine whether extra expenditure can actually affect the action.

### Step 3 — Determine the mechanism:
- greater output,
- reliability,
- speed,
- safety,
- duration,
- flexibility.

### Step 4 — Apply efficiency, output limits, and diminishing returns.

### Step 5 — Commit resources.

### Step 6 — Resolve normally.

### Step 7 — Determine actual resource consumption.

### Step 8 — Apply depletion, fatigue, damage, or other persistent consequences.

---

# Example — Fire Release

Character normally spends:

> 15 Chakra

for a reliable flame technique.

They choose:

> 25 Chakra

to increase area.

If their control and technique support this:

- area increases,
- cost increases,
- perhaps stability slightly decreases.

If they try:

> 60 Chakra

when the technique cannot safely handle it:

- efficiency collapses,
- instability rises,
- backlash becomes possible.

More chakra is not automatically better.

---

# Example — Emergency Sprint

A shinobi is exhausted but must reach an ally.

They choose maximum exertion.

Immediate effect:
- higher movement capability.

Cost:
- severe stamina loss,
- possible muscle injury,
- worse later performance.

That is a meaningful tradeoff.

---

# Example — Research Project

A researcher spends more money on:

- better equipment,
- specialist assistance,
- safer containment.

This may:

- improve progress efficiency,
- lower failure severity,
- unlock better testing methods.

Money itself never enters the check as a flat bonus.

---

# What I Would Lock In

> **Resources affect resolution only through causal mechanisms.**

> **Chakra quantity, chakra output, chakra control, and chakra efficiency are distinct concepts.**

> **More resource expenditure does not automatically mean greater success.**

> **Techniques and actions may have safe operating ranges, output limits, thresholds, and diminishing returns.**

> **Resources may improve capability, reduce difficulty, raise outcome ceiling, reduce risk, buy speed, or sustain actions.**

> **Mastery should often improve resource efficiency rather than only raw power.**

> **Overexertion allows temporary performance beyond sustainable levels at real cost.**

> **Resource depletion persists across scenes and affects later decisions.**

> **Characters can deliberately conserve, hold back, or overcommit resources.**

> **Deliberate resource commitments normally occur before resolution.**

> **Helpers, equipment, money, and social favors are also resources when their use consumes future options.**

> **There is no universal resource-spending formula; the mechanism depends on the resource and action.**

Next should be **Ruleset 2.20 — Taking Time, Careful Actions & Rushing**, where we can formalize the time-performance tradeoff in more detail: how careful work improves reliability or quality, how rushing changes risk, and how to avoid players exploiting unlimited preparation time.

---

## Turn 9918def3-510e-492f-b0ea-b862f5e602be

### User

Ok

### Assistant — 23831c6a-bee6-44aa-b7f0-c3826d861cd0

# Ruleset 2.20 — Taking Time, Careful Actions & Rushing

This section should define how **time investment changes performance**.

The core rule should be:

> **Time only improves an action when additional time can realistically improve preparation, precision, observation, or execution.**

Likewise:

> **Rushing only hurts when faster execution actually forces meaningful compromise.**

That prevents time from becoming a universal bonus system.

---

## 1. Time Can Affect Different Parts of Resolution

Spending more or less time may change:

- Effective Difficulty,
- Effective Capability,
- information quality,
- outcome ceiling,
- failure severity,
- resource efficiency,
- stealth,
- exposure to interruption.

The engine should use whichever effect is actually caused by the time choice.

For example:

Taking longer to pick a lock may reduce Difficulty.

Taking longer to aim may improve precision.

Taking longer to infiltrate may actually increase detection exposure.

So:

> **More time is not always better.**

---

# 2. Every Action Has a Natural Time Scale

Actions should have an approximate normal execution time.

Examples:

- throwing a kunai: seconds,
- picking a lock: minutes,
- researching records: hours,
- learning a jutsu: days or weeks.

This is the **Standard Pace**.

Time modifiers should be evaluated relative to that natural pace.

---

# 3. Standard Pace

At Standard Pace:

- no special time benefit,
- no rushing penalty,
- normal resource efficiency,
- normal expected quality.

This should be the baseline against which faster or slower methods are judged.

---

# 4. Careful Pace

A character may deliberately slow down to prioritize reliability.

Careful action may provide:

- better observation,
- fewer mistakes,
- reduced Difficulty,
- improved outcome floor,
- better resource efficiency.

Examples:

- carefully examining a seal,
- slowly crossing unstable terrain,
- methodically treating an injury.

But it consumes additional time.

---

# 5. Thorough Pace

Some actions allow even deeper investment.

A Thorough approach may involve:

- repeated verification,
- redundant checks,
- detailed inspection,
- extensive preparation.

This can provide stronger benefits than simply being careful.

However, benefits should diminish sharply.

The difference between:

> 30 seconds and 10 minutes

may be enormous.

The difference between:

> 10 hours and 12 hours

may be negligible.

---

# 6. Rushed Pace

A character may attempt to perform the task faster than normal.

Rushing may:

- increase Difficulty,
- reduce outcome quality,
- increase resource waste,
- increase failure severity.

Example:

A rushed medic may still stabilize someone but:

- use more supplies,
- create more complications,
- produce a poorer recovery result.

---

# 7. Extreme Rush

Some situations may demand execution far faster than the task normally permits.

This might:

- sharply increase Difficulty,
- restrict available methods,
- eliminate careful safeguards,
- make certain objectives impossible.

Example:

A seal normally requiring five minutes cannot necessarily be completed in three seconds simply by accepting a penalty.

At some point:

> **the required time exceeds physical execution limits.**

That becomes a plausibility restriction.

---

# 8. Minimum Execution Time

Many actions should have a hard or soft minimum duration.

Examples:

A sequence of hand seals physically requires some amount of movement.

A chemical reaction cannot be accelerated indefinitely.

A document cannot be fully read instantaneously.

So:

> **Rushing cannot bypass fundamental process time.**

Techniques or abilities may reduce that minimum, but only if they explicitly support it.

---

# 9. Maximum Useful Time

Likewise, some actions have a point where extra time stops helping.

Example:

Once a weapon has been thoroughly cleaned and inspected, spending another six hours does not improve the result.

This prevents unlimited-time exploitation.

---

# 10. Diminishing Returns Should Be the Default

A useful conceptual model:

### First Extra Time Investment
Large benefit.

### Additional Investment
Moderate benefit.

### Heavy Overinvestment
Minimal benefit.

This should generally apply unless the task specifically requires prolonged work.

---

# 11. Time Can Improve Information Before Execution

Sometimes the best benefit of extra time comes before the action.

Example:

A shinobi preparing an infiltration may spend longer:

- observing patrols,
- identifying entrances,
- learning schedules.

This may change the later contest structurally rather than simply giving:

> +10 Stealth.

Preparation time creates information.

---

# 12. Time Can Improve Precision

Some actions directly benefit from slower execution.

Examples:

- surgery,
- crafting,
- seal inscription,
- aiming,
- delicate chakra manipulation.

Extra time may improve:

- accuracy,
- stability,
- quality.

This is one of the clearest uses of a numerical Difficulty reduction.

---

# 13. Time Can Improve Safety

A careful approach may not significantly increase success probability but may reduce failure consequences.

Example:

A climber installs safety anchors.

The climb itself may remain difficult.

But failure becomes much less dangerous.

So a careful approach can improve:

> **risk profile**

rather than success chance.

---

# 14. Time Can Improve Resource Efficiency

Rushing may waste:

- chakra,
- stamina,
- materials.

A careful approach may use them more efficiently.

Example:

A skilled medic carefully applies chakra over five minutes.

A rushed version may require much greater output to achieve the same stabilization.

This gives time-resource tradeoffs.

---

# 15. Taking Longer Can Increase Exposure

Extra time can also be dangerous.

Example:

Picking a lock carefully makes the lock easier to defeat.

But every additional minute creates more opportunity for:

- guards to arrive,
- witnesses to appear.

So an action can simultaneously have:

> lower technical Difficulty

but

> higher environmental exposure.

This is an important strategic tradeoff.

---

# 16. Time Pressure Should Come From the World

The engine should never invent urgency merely to prevent careful play.

Valid time pressure:

- patient is bleeding out,
- guards approaching,
- bridge collapsing,
- mission deadline,
- target moving away.

Invalid:

> The engine wants this scene to be exciting.

Urgency must come from established world state.

---

# 17. Time Pressure Can Change the Objective

Suppose a medic has:

> 30 seconds.

The objective may no longer be:

> fully treat the wound.

Instead:

> stop immediate bleeding.

This is important.

Sometimes rushing does not mean attempting the same objective badly.

It means selecting a smaller objective that fits the available time.

---

# 18. Players Should Be Able to Trade Quality for Speed

When appropriate, characters should be able to choose:

### Fast
Lower quality, greater risk, less time.

### Standard
Normal quality and risk.

### Careful
Better reliability or safety, more time.

This should arise naturally from the task rather than appearing as a universal UI toggle.

---

# 19. Quality Targets Affect Time

Higher-quality results should often require more time.

Example:

Craft a functional kunai:

> relatively quick.

Craft a highly balanced custom kunai:

> much longer.

So the player may choose not only:

> how fast?

but:

> how good does this need to be?

---

# 20. Time Can Replace Random Resolution

As established earlier, if a task is repeatable, safe, and sufficiently within capability, enough time may remove meaningful failure.

Instead of:

> 80% chance to find the document.

the better question may become:

> How long does it take to search the archive thoroughly?

This is an important conversion.

---

# 21. “Eventual Success” Requires No Meaningful Failure State

We should not automatically convert every task into guaranteed success with enough time.

It only works when:

- failure does not consume the opportunity,
- resources remain available,
- no hidden requirement is missing,
- the task is within capability,
- conditions remain stable.

If the character fundamentally lacks the necessary knowledge, time alone may not help.

---

# 22. Extra Time Cannot Substitute for Missing Prerequisites

A novice cannot spend:

> 400 hours staring at an advanced seal

and automatically understand it if they lack foundational fuinjutsu knowledge.

They may learn some things through study, but eventually progression or instruction is required.

Time supports capability.

It does not bypass prerequisites.

---

# 23. Extra Time Can Enable Research

If direct performance is blocked by missing knowledge, extra time may allow a different action:

> research the problem.

That may eventually unlock the original task.

Again, the method changes rather than Difficulty simply falling forever.

---

# 24. Rushing Should Often Reduce Outcome Ceiling

Some tasks performed too quickly may simply be incapable of producing excellent quality.

Example:

A disguise assembled in 30 seconds may be enough to fool someone briefly.

It cannot reasonably achieve the same quality as one prepared over hours.

Thus rushing may cap:

> maximum outcome quality.

This is often better than only increasing failure probability.

---

# 25. Careful Work Can Raise Outcome Floor

Conversely, careful work can reduce how badly things can go.

Example:

A technician double-checks every connection.

The task may still fail.

But catastrophic wiring mistakes become much less plausible.

This is a strong use of careful action.

---

# 26. Hand-Sign Speed Is a Good Example

Since we discussed Hand-Sign Speed as a Skill, this system fits especially well.

A shinobi can perform a technique at:

### Normal Hand-Sign Pace
Standard reliability.

### Deliberate Pace
More control, but slower activation.

### Accelerated Pace
Faster activation, but potentially greater execution difficulty.

A highly skilled shinobi may perform accelerated seals without meaningful loss of reliability.

An inexperienced one may not.

This creates natural progression.

---

# 27. Speed Mastery Can Remove Rush Penalties

As capability grows, what was once rushed may become normal.

Example:

A novice needs:

> 4 seconds

to reliably perform a seal sequence.

An expert may perform the exact sequence in:

> 1 second

without penalty.

So action speed should partly emerge from Skills and Mastery.

This is an excellent application of progression.

---

# 28. Speed Should Not Be One Universal Character Stat

This reinforces an earlier Ruleset 1 point.

A character can be:

- physically fast,
- slow at hand seals,
- quick at mental arithmetic,
- slow at surgery.

So execution speed should usually be **skill-specific**.

Agility may influence many physical applications, but it should not become one universal Speed Attribute.

---

# 29. Taking Time Under Opposition May Be Impossible

A character cannot always choose Careful Pace.

Example:

During combat, an enemy may not give you thirty seconds to carefully prepare a technique.

Available time itself can therefore be part of the contest.

This makes defensive pressure meaningful.

---

# 30. Buying Time Becomes a Tactical Objective

Teams may deliberately create time for one another.

Example:

One shinobi holds enemies back while another:

- performs medical treatment,
- prepares a seal,
- charges a technique.

The first character is not directly improving the second's Skill.

They are **creating the time conditions needed for better performance**.

This integrates beautifully with teamwork.

---

# 31. Interruptions

Longer actions create more opportunities for interruption.

The engine should consider:

- enemy interference,
- environmental changes,
- concentration breaks.

A ten-minute action under hostile conditions is fundamentally different from the same action in a secure room.

---

# 32. Interruptions Should Not Always Erase All Progress

Depending on the action, interruption may:

- pause progress,
- lose partial progress,
- force restart,
- create risk.

Example:

Reading a book:
> pause and resume.

Drawing a delicate seal:
> interruption may ruin the inscription.

Technique charging:
> may dissipate entirely.

This should be task-specific.

---

# 33. Time Windows

Some opportunities should only exist temporarily.

Examples:

- enemy is distracted for six seconds,
- shop is open until evening,
- political support lasts until a vote,
- wounded target has minutes before deterioration.

This makes time part of strategic world state.

---

# 34. Deadlines Should Be Real

If a deadline exists, missing it should have consequences.

The engine should not silently extend it because the player needs more time.

Likewise, NPCs should also be constrained by deadlines.

This preserves simulation integrity.

---

# 35. Preparation Time Can Be Interrupted by World Events

The player may choose:

> Spend two weeks preparing.

But the world continues during those two weeks.

NPCs may:

- move,
- train,
- change plans,
- discover information,
- complete objectives.

Time investment should therefore have opportunity cost.

---

# 36. Long Preparation Can Make Information Stale

This creates another tradeoff.

Spend too little time:

> poor preparation.

Spend too long:

> target may change behavior.

So optimal timing can matter.

This is much more interesting than "more prep is always better."

---

# 37. Time Has Life-Simulation Opportunity Cost

Every hour spent:

- training,
- researching,
- preparing,

is an hour not spent on:

- work,
- relationships,
- rest,
- missions,
- recovery.

This should matter significantly in the broader simulator.

Time may eventually be one of the game's most important resources.

---

# 38. Routine Actions Should Be Time-Compressed

We do not need to simulate every second.

If an action is routine and nothing meaningful changes, the game can simply advance time.

Example:

> You spend three hours studying chakra theory.

The important outputs are:

- elapsed time,
- progression,
- fatigue,
- perhaps discovery.

Not every minute.

---

# 39. Time Scale Should Match Decision Scale

A useful rule:

> **Resolve at the smallest time scale where meaningful decisions occur.**

Combat:
> seconds.

Training:
> hours.

Projects:
> days.

Careers:
> weeks or months.

This keeps the simulation detailed without becoming unmanageable.

---

# 40. NPCs Need the Same Time Economy

NPCs should also be unable to:

- train indefinitely,
- work,
- maintain relationships,
- complete missions,

all simultaneously.

Their time allocation should influence progression.

This is vital for a believable persistent world.

---

# 41. Recommended Pace Categories

I think we can use these internally:

### Immediate
As fast as physically possible.

### Rushed
Significantly faster than normal.

### Standard
Normal execution.

### Careful
Slower for reliability or safety.

### Thorough
Much slower for maximum practical quality/information.

Not every action supports all five.

These should be descriptive modes, not fixed universal modifiers.

---

# 42. Pace Effects Should Be Task-Specific

Example:

### Picking a lock
Rushed:
- higher Difficulty,
- more tool risk.

Careful:
- lower Difficulty,
- more exposure time.

### Running
Rushed doesn't make much sense—the equivalent is higher exertion.

### Research
Careful may improve interpretation.
Thorough may expand coverage.

So the engine should interpret pace according to the domain.

---

# 43. Recommended Time-Resolution Procedure

Before an action where time matters:

### Step 1 — Establish Standard Duration
How long does competent normal execution take?

### Step 2 — Establish Available Time
Is there a deadline or interruption risk?

### Step 3 — Determine Chosen Pace
Immediate, rushed, standard, careful, thorough.

### Step 4 — Check Minimum and Maximum Useful Time
Can this action actually be compressed or improved?

### Step 5 — Determine Causal Effects
Does pace alter:
- Difficulty,
- Capability,
- quality ceiling,
- failure floor,
- resource cost,
- exposure?

### Step 6 — Resolve normally.

### Step 7 — Advance actual world time.

### Step 8 — Apply consequences occurring during that elapsed time.

This should keep time fully integrated into the persistent simulation.

---

# Example — Lockpicking

**Standard:**  
2 minutes, normal Difficulty.

**Rushed:**  
20 seconds, higher Difficulty, greater chance of tool damage.

**Careful:**  
10 minutes, reduced technical Difficulty, but increased chance a patrol arrives before completion.

There is no objectively best option.

The situation determines which is preferable.

---

# Example — Medical Emergency

The patient is bleeding heavily.

A full treatment might require:

> 20 minutes.

But the patient may only survive:

> 2 minutes without stabilization.

So the medic chooses a smaller objective:

> stop the bleeding immediately.

That may be a rushed, difficult procedure.

After stabilization:

> full treatment becomes possible.

This demonstrates how time pressure can change objectives rather than merely adding penalties.

---

# Example — Hand Seals

A shinobi knows a technique well.

At normal pace:
> automatic activation.

At accelerated pace:
> uncertain execution.

After months of mastery training:
> that accelerated pace may itself become automatic.

This creates measurable progression in **execution speed** without needing Speed as a foundational Attribute.

---

# What I Would Lock In

> **Time affects resolution only when additional or reduced time causally changes execution.**

> **Actions have natural standard durations, practical minimum durations, and often maximum useful preparation time.**

> **Careful actions may improve reliability, information, quality, safety, or efficiency.**

> **Rushing may increase Difficulty, resource use, risk, or reduce outcome ceiling.**

> **Benefits from extra time normally show diminishing returns.**

> **Taking longer can increase exposure to interruption or world changes.**

> **Some objectives should shrink under time pressure rather than merely become harder.**

> **Given sufficient safe time, some repeatable tasks become time-to-completion problems rather than pass/fail checks.**

> **Time never substitutes for missing prerequisites by itself.**

> **Skill and mastery can reduce the time required to perform an action reliably.**

> **Execution speed is generally application-specific rather than one universal Speed stat.**

> **The world continues while the character prepares, trains, researches, or waits.**

> **Player and NPC time are both finite persistent resources.**

Next should be **Ruleset 2.21 — Stress, Pressure & Performance**, where we can define how fear, injury, urgency, divided attention, shock, morale, and high-pressure situations affect execution—without turning emotions into arbitrary stat penalties.

---

## Turn 35e30c4d-20b8-4966-89d1-2560e37c5310

### User

Ok

### Assistant — c9105c1a-1651-415f-9087-4c555c5ded45

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.21 — Stress, Pressure & Performance

Stress should matter because characters do not perform identically in calm practice and under danger.

But the system should avoid simplistic rules like:

> Stress = −10 to everything.

The core principle should be:

> **Pressure affects performance through specific psychological and cognitive mechanisms, not as a universal penalty.**

Two characters can face the same situation and react very differently.

## 1. Pressure Is Not the Same as Difficulty

A task may be technically easy but psychologically difficult.

Example:

A shinobi can normally perform a basic hand-seal sequence automatically.

Doing it while:

- being charged by an enemy,
- watching an ally bleed out,
- hearing an explosion nearby

may introduce pressure.

The technique itself did not become more technically complex.

Instead, the character's ability to execute under pressure changed.

So pressure usually affects **Effective Capability**, attention, or available options rather than base Difficulty.

---

# 2. Stress Should Be a Character State

Stress should usually exist as a temporary persistent state rather than one isolated modifier.

A useful conceptual scale could be:

### Calm
Normal function.

### Alert
Heightened attention without meaningful impairment.

### Pressured
Noticeable strain; complex or delicate tasks may become harder.

### Distressed
Performance begins to degrade more broadly.

### Overwhelmed
Major cognitive or emotional impairment.

### Panicked / Shocked
Normal decision-making may partially break down.

The exact labels can remain internal.

---

# 3. Stress Is Not Always Negative

Moderate pressure can sometimes improve performance.

A character may become:

- more alert,
- faster to react,
- more focused on immediate threats.

So a small amount of pressure may improve:

- vigilance,
- reaction,
- urgency.

But too much pressure begins to impair:

- precision,
- memory,
- planning,
- fine motor control.

This suggests an **inverted-U relationship** rather than:

> more stress = always worse.

---

# 4. Different Tasks Respond Differently to Stress

Stress should affect task types differently.

### Simple Physical Actions
May improve slightly under moderate arousal.

### Precision Actions
Often worsen under high stress.

### Complex Reasoning
May degrade significantly.

### Habitual Skills
May remain reliable if deeply trained.

### Novel Tasks
Often degrade heavily.

This distinction should matter.

---

# 5. Training Under Pressure Builds Reliability

A character who repeatedly practices a technique under realistic conditions should become better at performing it under pressure.

This gives combat experience real value.

A character may know a technique perfectly in training but still struggle to execute it in their first real battle.

Over time:

> **pressure tolerance increases.**

This can be represented through:

- skill mastery,
- combat experience,
- specific stress-conditioning traits.

---

# 6. Mastery Should Protect Against Pressure

Highly mastered actions should resist stress better than newly learned ones.

Example:

A jonin performing a signature jutsu under attack.

The action may remain automatic.

A genin performing a newly learned version of the same technique may become unreliable.

This reinforces:

> **Mastery expands reliability, especially under adverse conditions.**

---

# 7. Willpower Should Affect Stress Response

Willpower is one of our foundational Attributes, so this is an important application.

Willpower should influence:

- maintaining focus,
- resisting panic,
- continuing despite pain,
- resisting intimidation,
- keeping composure.

It should not make someone immune to stress.

A high-Willpower character may still feel fear.

They are simply better at functioning despite it.

---

# 8. Experience Should Matter Separately From Willpower

A naturally strong-willed civilian may still react poorly to their first battlefield.

An experienced shinobi may remain calm because they have encountered similar situations many times.

So stress resistance should draw from:

- Willpower,
- relevant experience,
- mastery,
- personality,
- familiarity.

This prevents Willpower from becoming the single universal mental-defense stat.

---

# 9. Familiar Stressors Are Easier to Handle

A character may become desensitized to specific types of pressure.

Examples:

A medic may function well around blood and injury.

A veteran combatant may function well under attack.

A politician may function well during public confrontation.

But the same character may struggle with another stressor.

Stress tolerance should therefore have **domain familiarity**.

---

# 10. Personality Influences Stress Response

Characters may respond differently based on personality.

Examples:

### Cautious
May become hesitant earlier but avoid reckless mistakes.

### Reckless
May act quickly under pressure but take poor risks.

### Disciplined
May maintain planned behavior.

### Anxious
May experience stronger anticipatory stress.

### Hot-tempered
May become aggressive rather than fearful.

These should influence behavior more often than direct stat penalties.

---

# 11. Fear Should Not Equal Cowardice

Fear is a normal response.

A brave character can still be afraid.

The meaningful question is:

> **How does fear affect their behavior?**

Possible responses:

- freeze,
- flee,
- fight,
- focus,
- seek support.

Personality and training influence which response becomes likely.

---

# 12. Panic Should Be Structural at High Severity

At extreme stress, the issue may stop being:

> −10 Capability.

A panicked character might:

- lose access to complex planning,
- flee,
- freeze,
- lash out,
- fail to process commands.

That is a **structural state**.

The character's decision space changes.

This should be rare and contextually justified.

---

# 13. Shock

Severe sudden events may cause temporary shock.

Examples:

- witnessing a close ally die,
- suffering catastrophic injury,
- experiencing overwhelming surprise.

Shock may briefly impair:

- reaction,
- decision-making,
- communication.

But characters with:

- high Willpower,
- relevant experience,
- emotional conditioning

may recover faster.

---

# 14. Pain Is Separate From Fear

Pain should affect:

- concentration,
- precision,
- endurance,
- physical output.

Fear affects:

- decision-making,
- risk tolerance,
- attention.

They may occur together, but should not be collapsed into one generic stress penalty.

---

# 15. Divided Attention

Pressure often matters because attention is split.

Examples:

- maintain a barrier,
- monitor allies,
- track an enemy,
- prepare a jutsu.

A character's performance may degrade because they cannot devote full concentration to everything.

This is not necessarily emotional stress.

It is cognitive load.

That distinction should be explicit.

---

# 16. Cognitive Load

Characters have limited capacity to process simultaneous information.

High cognitive load can impair:

- reaction,
- planning,
- perception,
- precision.

Skills and experience can reduce the load of familiar tasks.

Example:

An expert driver can talk while driving more easily than a novice.

Likewise, an experienced shinobi can maintain basic chakra control while fighting with less mental effort.

---

# 17. Automatic Skills Consume Less Attention

This gives us another important progression effect.

As actions become automatic through mastery:

> they require less conscious attention.

That allows experts to perform more simultaneous tasks.

For example:

A beginner may need full concentration for wall walking.

An elite shinobi can wall-run while:

- fighting,
- observing enemies,
- forming strategy.

This is a very good reason for mastery beyond numerical bonuses.

---

# 18. Attention Should Be a Limited Situational Resource

We do not necessarily need a visible "Attention Meter."

But internally, the engine should recognize when a character is trying to manage too many demanding tasks.

Then it can:

- lower performance,
- force prioritization,
- restrict simultaneous actions.

This will be important in combat.

---

# 19. Urgency Is Different From Stress

Urgency means:

> not enough time.

Stress means:

> psychological/cognitive response to circumstances.

Urgency may cause stress, but they are separate.

For example:

A calm expert may work under severe time pressure without panicking.

The task is still rushed.

This distinction prevents double-counting.

---

# 20. Intimidation

Intimidation should not be:

> Intimidation Skill vs Willpower = frightened.

Instead, it should evaluate:

- threat credibility,
- power gap,
- reputation,
- context,
- stakes,
- target personality.

A weak character shouting at an experienced jonin should not terrify them merely because they have high Charisma-like skill.

The threat needs to be believable.

---

# 21. Fear Can Come From Perceived Power Gaps

A character who recognizes they are massively outmatched may experience pressure.

This may affect:

- willingness to engage,
- decision speed,
- retreat behavior.

But this should depend on personality.

A disciplined shinobi may respond:

> retreat strategically.

A reckless one:

> attack anyway.

A terrified civilian:

> freeze.

---

# 22. Morale Is Group-Level Stress

For groups, morale should influence:

- willingness to continue,
- cohesion,
- obedience,
- retreat behavior.

It should not simply be a flat combat bonus.

Poor morale might lead to:

- hesitation,
- desertion,
- fragmented coordination.

High morale may improve persistence.

This interacts with leadership and teamwork.

---

# 23. Leadership Can Stabilize Group Stress

Strong leadership can:

- clarify priorities,
- reassure allies,
- maintain coordination,
- prevent panic spreading.

It should mainly improve:

- decision quality,
- team cohesion,
- recovery from disruption.

Again, not just "+10 Morale."

---

# 24. Stress Can Spread Socially

Panic or confidence can propagate through groups.

Examples:

- one person fleeing triggers others,
- calm leadership stabilizes allies,
- seeing a powerful ally succeed restores confidence.

This should happen only when characters observe and interpret those behaviors.

No invisible morale aura.

---

# 25. Confidence

Confidence can reduce:

- hesitation,
- stress response,
- indecision.

But confidence itself does not increase actual skill.

Overconfidence may actually worsen decisions by causing:

- underestimation,
- excessive risk,
- insufficient preparation.

This should mostly influence behavior, not raw resolution.

---

# 26. Self-Efficacy

There is a useful distinction between:

### Confidence
What the character believes.

### Self-Efficacy
Experience-based belief that they can perform a specific task.

A character who has successfully performed a technique under pressure many times should be less stressed when using it again.

That can emerge naturally from mastery and experience.

---

# 27. Emotional Stakes

Some situations become more stressful because the character cares deeply about the outcome.

Example:

A medic treating:

- an unknown patient,
- their best friend,

may experience different emotional pressure.

This does not automatically mean worse performance.

Some characters become more focused.

Others become less objective.

Personality and experience should determine the response.

---

# 28. Trauma and Long-Term Stress

Long-term psychological effects probably belong in a separate Health/Character State ruleset.

For Resolution, we only need the principle:

> Persistent psychological states can modify stress response when relevant.

We should avoid developing full trauma mechanics here.

That would be scope creep.

---

# 29. Recovery From Stress

Stress should decrease through:

- safety,
- time,
- rest,
- support,
- successful stabilization,
- removal of threat.

Recovery rate can depend on:

- Willpower,
- personality,
- experience,
- severity.

Stress should not vanish automatically because combat ends.

But neither should minor stress linger indefinitely.

---

# 30. Stress Accumulation

Repeated stressful events can accumulate.

A character may handle:

- one dangerous encounter

well.

But after:

- several missions,
- no sleep,
- repeated injuries,

their tolerance may deteriorate.

This should interact with fatigue and recovery.

---

# 31. Acute vs Chronic Stress

We should distinguish:

### Acute Stress
Immediate pressure during a specific event.

### Accumulated Stress
Persistent burden from repeated strain.

Ruleset 2 mainly resolves acute effects.

Long-term accumulated stress should later become a broader character-state system.

---

# 32. Stress Should Not Be Rolled Constantly

We do not want:

> Stress check every round.

Stress should update when something meaningful happens.

Examples:

- terrifying revelation,
- ally critically injured,
- sudden ambush,
- overwhelming enemy appears.

After that, the resulting state persists until circumstances change.

This is much cleaner.

---

# 33. Some Characters May Have Triggers

Specific characters may respond unusually strongly to particular situations because of established history.

If the simulation knows:

> this character has a severe fear of fire,

then Fire Release may create unusual pressure.

But these triggers should come from established character state.

The engine should not invent them on demand.

---

# 34. Stress Resistance Should Not Mean Emotionlessness

A high-Willpower veteran may still:

- grieve,
- fear,
- become angry.

They are simply able to maintain functional performance more effectively.

This preserves characterization while respecting mechanics.

---

# 35. Stress Can Change Objectives

At extreme pressure, a character may stop pursuing:

> victory

and shift to:

> escape.

NPCs especially should dynamically change objectives based on stress and perceived risk.

This makes behavior believable.

The player, however, should generally retain agency over their own character unless a severe structural mental state genuinely removes some control.

---

# 36. Player Agency Under Stress

We should be conservative about forcing player behavior.

Normal fear or stress should:

- affect information,
- performance,
- available confidence,

but not dictate:

> "You run away."

Forced behavior should generally require severe states such as:

- panic,
- mind-affecting techniques,
- overwhelming shock.

Even then, the effect should be clearly grounded in mechanics.

---

# 37. NPC Agency Can Be More Autonomous

NPCs should freely:

- retreat,
- freeze,
- surrender,
- make mistakes

based on their personality and stress state.

This is part of world simulation.

Different NPCs should respond differently to the same danger.

---

# 38. Stress and Hidden Information

A stressed character may:

- miss details,
- misinterpret ambiguous evidence,
- focus excessively on threats.

But we should avoid using stress as an excuse for arbitrary misinformation.

The effect should come through:

- reduced perception,
- worse interpretation,
- narrowed attention.

---

# 39. Tunnel Vision

Under high pressure, attention may narrow.

This may improve focus on:

> immediate threat

while reducing awareness of:

- surroundings,
- allies,
- secondary dangers.

This is an excellent structural effect of severe stress.

It is much more interesting than a universal penalty.

---

# 40. Fine Motor Control

High stress can impair delicate motor tasks.

Examples:

- precise hand seals,
- surgery,
- intricate seal work,
- lockpicking.

Characters with high mastery should resist this better.

Again:

> practiced automatic skill protects against pressure.

---

# 41. Complex Reasoning

High stress can reduce:

- planning depth,
- working memory,
- flexibility.

A stressed character may default to:

- familiar tactics,
- habitual responses.

This makes training and prepared plans valuable.

---

# 42. Habits Become More Important Under Stress

Characters should tend to fall back on:

- practiced techniques,
- familiar strategies,
- established routines.

This is very appropriate for shinobi combat.

An inexperienced fighter may forget rarely used techniques.

An expert has trained responses deeply enough to access them reliably.

---

# 43. Stress Can Increase Resource Consumption

Under pressure, characters may:

- use too much chakra,
- move inefficiently,
- breathe harder,
- waste ammunition.

This may be an outcome of poor execution rather than a direct probability penalty.

That gives stress lasting consequences.

---

# 44. Stress Can Reduce Resource Efficiency

A useful distinction:

The character may still succeed.

But the execution is less efficient.

Example:

A nervous genin successfully uses a jutsu but spends:

> 20 Chakra instead of 15.

This makes pressure meaningful without always causing failure.

---

# 45. Stress and Outcome Degree

Stress can influence:

- probability,
- resource efficiency,
- quality,
- failure severity.

But it should do so only where relevant.

For example:

A highly stressed negotiator might still persuade someone but phrase things poorly enough to damage trust slightly.

This fits our outcome-degree system.

---

# 46. Stress Can Be Managed

Characters can reduce acute pressure through:

- breathing techniques,
- preparation,
- routines,
- support,
- meditation,
- training.

These can be Skills or techniques.

But they should not instantly erase severe psychological states.

---

# 47. Emotional Support

Another character can sometimes reduce stress through:

- reassurance,
- leadership,
- familiarity.

This can improve future functioning.

It should depend on:

- relationship,
- trust,
- circumstances.

A hated rival saying "calm down" may not help.

---

# 48. Performance Under Pressure Can Become Its Own Mastery Dimension

For especially important Skills, we may eventually track:

> **Pressure Reliability**

implicitly through mastery rather than creating another universal stat.

Example:

Basic Chakra Control 4 may be automatic calmly.

Combat experience and mastery determine whether that same control remains automatic under attack.

This avoids scope creep while still modeling pressure training.

---

# 49. Recommended Stress Resolution Procedure

When meaningful pressure arises:

### Step 1 — Identify the Stressor
Fear? Pain? Urgency? Emotional stakes? Cognitive overload?

### Step 2 — Determine Severity
How intense is it objectively?

### Step 3 — Evaluate Character Response
Using:
- Willpower,
- experience,
- mastery,
- personality,
- familiarity.

### Step 4 — Establish Stress State
Calm, alert, pressured, distressed, overwhelmed, etc.

### Step 5 — Apply Targeted Effects
Only to relevant:
- attention,
- precision,
- planning,
- resource efficiency,
- available actions.

### Step 6 — Persist State
Until conditions or recovery change it.

### Step 7 — Reevaluate Only When Something Meaningful Changes

This avoids constant stress-check spam.

---

# Example — First Real Mission

A genin has excellent academic ninjutsu performance but almost no combat experience.

Under classroom conditions:

> technique is reliable.

During their first ambush:

- adrenaline spikes,
- attention splits,
- hand-seal precision suffers.

The technique may now become uncertain.

After months of combat experience:

> the same situation creates much less impairment.

Character growth happened without necessarily increasing the technique's raw power.

---

# Example — Veteran Medic

A severely wounded ally arrives.

A novice medic may become:

> distressed.

This reduces:
- precision,
- decision quality.

A veteran medic may become:

> alert and highly focused.

Same stressor.

Different response because of:

- experience,
- Willpower,
- mastery.

That's exactly what we want.

---

# Example — Overwhelming Opponent

A genin encounters an enemy whose capability is obviously far beyond theirs.

The engine may establish:

---

## Turn 6959b724-381e-4485-915a-a1e6d125bfd7

### User

Ok

### Assistant — 54477bcd-2dbc-40d3-9d00-a5126bd2996f

# Ruleset 2.22 — Difficulty Estimation & Character Self-Assessment

This section should govern how characters judge:

- how hard something is,
- how capable they are relative to it,
- how risky an attempt would be,
- how confident they should feel,
- and when their judgment may be wrong.

The central rule should be:

> **Characters do not perceive true Difficulty or exact probability directly. They estimate them from experience, observation, and available information.**

## 1. Separate True Difficulty From Perceived Difficulty

The engine knows the actual task conditions.

The character has only an estimate.

So we should distinguish:

### True Difficulty
The engine's objective value.

### Perceived Difficulty
What the character currently believes the task demands.

### Perceived Capability
What the character believes they can currently bring to the task.

### Perceived Odds
Their resulting estimate of how likely success is.

Those estimates may be accurate, rough, or wrong.

---

# 2. Self-Assessment Should Usually Be Qualitative

The player normally should not see:

> 67% success chance.

Instead, they should receive something like:

- trivial,
- routine,
- manageable,
- challenging,
- risky,
- very difficult,
- extremely unlikely,
- beyond your apparent capability.

The exact wording can vary by context.

This preserves immersion while still giving useful decision support.

---

# 3. Expertise Improves Estimation

A character should judge tasks more accurately in domains they understand.

An experienced tracker can assess:

- trail quality,
- terrain difficulty,
- likely time required.

A novice may only know:

> this looks hard.

This means relevant Skill should improve **calibration**, not just performance.

---

# 4. Familiarity Improves Self-Assessment

Characters should be especially good at judging tasks similar to things they have done before.

Example:

A shinobi who has performed the same jutsu thousands of times should know fairly well:

- whether they have enough chakra,
- whether current injury will interfere,
- whether the timing is realistic.

This is another benefit of mastery.

---

# 5. Unknown Systems Create Wide Uncertainty

A character should have poor estimates when dealing with unfamiliar things.

Examples:

- unknown clan technique,
- unfamiliar poison,
- foreign seal system,
- enemy whose strength has not been revealed.

The player may receive:

> You cannot confidently judge this.

That is better than inventing false precision.

---

# 6. Estimation Requires Observable Evidence

A character cannot accurately evaluate hidden variables they have no access to.

Example:

They may assess:

- enemy posture,
- visible speed,
- equipment,
- chakra pressure if detectable.

They may not know:

- hidden reserves,
- secret abilities,
- concealed injuries,
- traps.

So estimates should be based only on accessible information.

---

# 7. Self-Knowledge Should Usually Be Better Than Opponent Knowledge

Characters generally know their own:

- skills,
- fatigue,
- injuries,
- technique familiarity

better than they know someone else's.

Therefore, uncertainty often comes more from:

> "How strong is the task/opponent?"

than:

> "What am I capable of?"

But even self-assessment can be imperfect.

---

# 8. Characters Can Misjudge Their Own Condition

Possible reasons:

- adrenaline masking injury,
- exhaustion not yet fully felt,
- overconfidence,
- unfamiliar side effects,
- hidden poison,
- chakra depletion misread.

So perceived capability can diverge from actual Effective Capability.

This should be grounded in a reason, not random misinformation.

---

# 9. Overconfidence Should Affect Estimation, Not Raw Skill

A character who is overconfident should tend to:

- overestimate capability,
- underestimate risk,
- choose harder actions.

They should not receive a mechanical performance bonus just for believing in themselves.

Likewise, insecurity may cause underestimation without reducing actual capability unless stress or hesitation also intervenes.

---

# 10. Confidence and Accuracy Are Separate

A character can be:

- accurately confident,
- accurately cautious,
- wrongly confident,
- wrongly cautious.

The engine should track these separately.

This matters because a very confident estimate is not necessarily a correct one.

---

# 11. Intelligence Helps Analyze Complexity

Intelligence should help with:

- identifying relevant factors,
- understanding tradeoffs,
- comparing methods,
- noticing hidden complexity.

But Intelligence alone should not let a character accurately estimate a task in a domain they know nothing about.

A smart novice is still a novice.

---

# 12. Perception Helps Evaluate Immediate Conditions

Perception can improve estimation of:

- terrain,
- enemy movement,
- visible injuries,
- environmental hazards,
- subtle cues.

This is particularly useful in active situations.

---

# 13. Relevant Skill Should Be the Main Estimation Tool

For domain-specific assessment, the relevant Skill should matter most.

Examples:

- Medicine for medical risk,
- Stealth for assessing concealment routes,
- Fuinjutsu for seal complexity,
- Taijutsu for reading physical matchups,
- Tracking for trail quality.

This reinforces specialization.

---

# 14. Experience With Similar Opponents Matters

A genin who has never faced a jonin may poorly understand what elite movement looks like.

After repeated exposure, they may become much better at estimating:

- speed,
- threat level,
- tactical danger.

Experience should improve comparative judgment.

---

# 15. Power Recognition Should Be Evidence-Based

Characters should not automatically know:

> this person is Capability 82.

Instead, they infer from things like:

- movement quality,
- chakra presence,
- technique use,
- reputation,
- equipment,
- prior performance.

A deliberately restrained expert may be underestimated.

---

# 16. Reputation Can Influence Estimates

Known reputation may change perceived threat.

Example:

> "That is the village's strongest sensor."

This may make the character expect:

- very high detection capability.

But reputation may be:

- accurate,
- exaggerated,
- outdated,
- misleading.

So reputation informs estimates but does not become objective truth.

---

# 17. Demonstrated Capability Should Update Estimates

Once someone visibly performs a feat, observers should revise their assessment.

Example:

An apparently ordinary shinobi casually avoids an elite attack.

Observers should now update:

> they are much more dangerous than previously assumed.

This should happen dynamically.

---

# 18. Characters Should Learn From Failed Predictions

If a character repeatedly underestimates an opponent, their estimate should improve.

Example:

> "He shouldn't be able to track us."

Then he does.

That failure provides evidence.

Knowledge state updates.

This makes the world feel responsive.

---

# 19. Qualitative Odds Should Have Broad Bands

We can define internal presentation bands such as:

- Almost Certain
- Very Likely
- Favorable
- Uncertain
- Unfavorable
- Very Unlikely
- Nearly Impossible

These would map loosely to the true probability model, but the character's estimate may blur or shift them.

The exact wording should depend on context.

---

# 20. Do Not Expose Exact Thresholds Through Language Too Reliably

If:

> "Favorable" always means exactly 70–79%

players will reverse-engineer the system quickly.

So qualitative estimates should remain broad and natural.

Example:

> You think you have the edge.

That is enough.

---

# 21. Expert Characters Can Receive More Precise Descriptions

A specialist may get finer-grained assessment.

Novice:

> The seal looks complicated.

Expert:

> The outer layer is within your ability, but the nested trigger sequence is probably beyond what you can safely dismantle without more time.

That is useful precision without numeric percentages.

---

# 22. Character Knowledge Should Determine Estimate Quality

A useful internal concept is **Estimate Confidence**.

High confidence:
- familiar task,
- clear information,
- stable conditions.

Low confidence:
- unknown opponent,
- hidden variables,
- unfamiliar technique,
- poor visibility.

This tells the engine how strongly to phrase the assessment.

---

# 23. Estimate Error Should Be Bounded by Evidence

The engine should not make a trained medic think:

> trivial procedure

when all visible evidence clearly indicates:

> severe medical emergency.

Estimation errors should remain plausible.

Experts can be wrong, but usually for understandable reasons.

---

# 24. Hidden Variables Can Create Surprise

Suppose a character estimates:

> favorable odds.

Unknown factor:

> enemy has hidden sensory technique.

Actual odds:

> poor.

This is legitimate because the estimate was based on incomplete information.

The player should not be retroactively told they "should have known" unless clues actually existed.

---

# 25. Deception Can Manipulate Difficulty Estimates

Characters can deliberately appear:

- weaker,
- stronger,
- injured,
- inexperienced,
- harmless.

This can alter an opponent's perceived odds.

That may influence decisions before any direct contest.

This is tactically valuable.

---

# 26. Feigned Weakness

A stronger character may intentionally suppress signs of capability.

If successful, an opponent may:

- approach recklessly,
- underestimate danger,
- commit resources poorly.

This creates strategic advantage without changing actual stats.

---

# 27. Intimidation Can Inflate Perceived Risk

A character may appear more dangerous than they truly are.

If intimidation succeeds, the target may believe:

> engaging is more dangerous than it really is.

Again, actual capability does not change.

Perceived capability does.

---

# 28. Self-Assessment Should Include Resource State

A character should judge whether they can sustain an action based on:

- chakra reserves,
- stamina,
- injuries,
- equipment.

Example:

> You can probably perform the technique once more safely, but a second attempt would be risky.

This is much more useful than raw pool numbers alone.

---

# 29. Estimate Can Cover More Than Success Chance

Characters should sometimes assess:

- time required,
- likely resource cost,
- likely failure consequences,
- whether retry is possible.

Example:

> You think you can break the seal, but it will likely take at least ten minutes and could trigger an alarm if you rush.

This supports meaningful choices.

---

# 30. Risk Estimation Can Be Wrong Separately From Difficulty Estimation

A character may correctly judge:

> the jump is easy

but incorrectly believe:

> the surface below is soft.

So they may estimate success probability well but failure consequences poorly.

This distinction is important.

---

# 31. Characters Should Recognize Routine Tasks

If something is far below their capability, the narration can say:

> This is routine for you.

That communicates automatic or near-automatic performance naturally.

---

# 32. Characters Should Recognize Obvious Nonviability

If the gap is obvious and the character has enough experience, the game should say so.

Example:

> In a direct contest of strength, you have no realistic chance against him.

This is not hand-holding.

It represents character knowledge.

---

# 33. But Unknown Capability Should Not Be Spoiled

If an opponent has revealed nothing meaningful, the engine may say:

> You cannot get a reliable read on them.

That preserves uncertainty.

---

# 34. Comparative Self-Assessment Should Be Objective-Specific

The character might know:

> I cannot match her speed.

but also:

> I am probably the better tracker.

Do not summarize every matchup into:

> She is stronger than you.

Specific comparisons are more useful and more accurate.

---

# 35. Estimation Can Improve Through Scouting

Scouting should improve:

- perceived Difficulty,
- perceived opposition,
- perceived risk.

This is one of the clearest rewards for information gathering.

Good scouting can transform:

> unknown

into:

> informed decision.

---

# 36. Estimates Can Become Stale

If time passes, conditions may change.

Example:

A patrol route learned yesterday may no longer be accurate.

So estimates should reflect:

- age of information,
- volatility of the situation.

This connects to dynamic knowledge.

---

# 37. NPCs Need the Same Estimation System

NPCs should not use objective probabilities when deciding what to do.

They should act from:

- perceived capability,
- perceived difficulty,
- perceived stakes,
- confidence.

That is critical for believable behavior.

---

# 38. Smart NPCs Should Still Make Mistakes

A highly intelligent NPC can make a bad decision if:

- information is wrong,
- they are deceived,
- their model is outdated.

Good decision-making does not require omniscience.

This is essential for fair simulation.

---

# 39. Reckless NPCs May Ignore Accurate Estimates

A character may correctly know:

> this is extremely dangerous.

and still proceed because of:

- loyalty,
- desperation,
- pride,
- ideology,
- anger.

So:

> estimation and decision are separate systems.

This will lead directly into the next section.

---

# 40. Cautious NPCs May Avoid Even Favorable Risks

Likewise, a cautious character may refuse:

> 70% chance of success

if failure means death.

Their behavior depends on risk tolerance.

Again, estimate ≠ choice.

---

# 41. The Player Should Usually Receive Estimate Before Commitment

When the character can reasonably assess the action and the stakes are meaningful, the engine should give the relevant warning **before** resolving.

For example:

> The distance is within your jumping ability, but the wet rooftop makes the landing uncertain.

Then the player can decide.

This protects agency.

---

# 42. Do Not Interrupt Every Action With Warnings

Only surface assessment when:

- risk is meaningful,
- uncertainty is non-obvious,
- the character would naturally recognize something important.

Routine actions should flow normally.

---

# 43. Sudden Actions May Not Allow Full Assessment

In emergencies, a character may have only a split second.

They may receive only rough judgment:

> Too far. Maybe possible.

rather than detailed analysis.

Available decision time affects estimate quality.

---

# 44. Deliberate Assessment Can Be an Action

A character may explicitly:

> study the opponent before engaging.

That can improve estimate quality.

Potential benefits:

- reveal habits,
- assess injuries,
- estimate speed,
- identify equipment.

But it costs:

- time,
- attention,
- possibly secrecy.

This makes "observe first" a meaningful tactic.

---

# 45. Assessment Should Not Automatically Reveal Hidden Abilities

Even careful observation can only reveal what produces observable evidence.

A perfectly concealed technique remains hidden until:

- used,
- detected through another method,
- learned through intelligence.

No analysis skill should become omniscience.

---

# 46. Recommended Estimation Procedure

Before a meaningful uncertain action:

### Step 1 — Determine True Situation
Actual Difficulty, opposition, state, and stakes.

### Step 2 — Determine Character Information
What do they actually know?

### Step 3 — Determine Relevant Assessment Capability
Skill, Intelligence, Perception, familiarity, mastery.

### Step 4 — Generate Perceived Difficulty and Capability
With uncertainty appropriate to the evidence.

### Step 5 — Generate Perceived Risk
Including known consequences.

### Step 6 — Determine Estimate Confidence
How reliable does the character believe the estimate is?

### Step 7 — Present Qualitatively
Only as precisely as the character could reasonably judge.

### Step 8 — Use the true values for actual resolution
Never substitute perceived values into reality.

That final distinction is essential.

---

# Example — Unknown Opponent

The player encounters a quiet traveler.

Known:

- average build,
- no visible weapons,
- calm posture.

Unknown:

- elite taijutsu,
- hidden weapon,
- suppressed chakra.

Character lacks specialized insight.

Player-facing assessment:

> Nothing about him immediately marks him as a major threat, but you have very little information to judge from.

Not:

> Easy opponent.

That wording preserves uncertainty appropriately.

---

# Example — Familiar Technique

Character has practiced Great Fireball for years.

They are mildly fatigued.

Assessment:

> You are confident you can perform it reliably at normal output. Increasing the size significantly would put noticeable strain on your remaining chakra.

This combines:

- probability,
- resources,
- self-knowledge.

---

# Example — Dangerous Climb

Expert climber observes cliff.

They recognize:

- route technically manageable,
- recent rain,
- poor protection opportunities.

Player-facing:

> The climb itself is within your ability, but the wet rock leaves almost no margin for a serious mistake. A fall from the upper section could be fatal.

This separates Difficulty from stakes exactly as intended.

---

# What I Would Lock In

> **True Difficulty, perceived Difficulty, perceived capability, and perceived risk are separate concepts.**

> **Characters estimate rather than directly know exact probability.**

> **Relevant Skill, experience, familiarity, Intelligence, and Perception improve estimate quality.**

> **Unknown variables widen uncertainty rather than automatically producing false estimates.**

> **Overconfidence and insecurity primarily distort self-assessment, not raw capability.**

> **Reputation, observation, scouting, and prior encounters can update perceived capability.**

> **Character estimates are objective-specific rather than universal power rankings.**

> **Risk estimation includes consequences, resource costs, time, and retry possibilities—not only success probability.**

> **Player-facing estimates should be qualitative and only as precise as the character's information supports.**

> **NPCs use perceived rather than true odds when making decisions.**

> **Estimation and decision-making remain separate: a character can knowingly accept bad odds or reject good ones.**

Next should be **Ruleset 2.23 — NPC Decision-Making Using Probability**, where we can finally connect perceived odds, stakes, personality, goals, relationships, desperation, and available alternatives into a consistent system for deciding what NPCs actually choose to do.

---

## Turn 7d27efa4-a635-4a53-8fd9-232e9aabacac

### User

Ok

### Assistant — eb8e9a29-518e-4136-9aa7-d62c5dd223c9

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.23 — NPC Decision-Making Using Probability

This section should govern how NPCs choose actions when outcomes are uncertain.

The core principle should be:

> **NPCs should choose based on their perceived options, perceived odds, perceived stakes, goals, personality, and available information—not on engine omniscience.**

That means a rational NPC can still make the wrong choice if their information is wrong.

---

## 1. NPCs Should Evaluate Options, Not Just Roll Behavior

When facing a meaningful decision, an NPC should consider available actions such as:

- attack,
- retreat,
- hide,
- negotiate,
- wait,
- gather information,
- call for help,
- spend resources,
- change tactics.

They should not simply pick from a random behavior table unless the decision is genuinely arbitrary.

---

# 2. Decisions Use Perceived Values

An NPC should never reason from hidden engine truth.

They should use:

### Perceived Capability
What they think they can do.

### Perceived Opposition
What they think others can do.

### Perceived Probability
How likely they think each option is to work.

### Perceived Stakes
What they believe success or failure would cost.

### Confidence
How certain they are in those estimates.

This is critical for believable mistakes.

---

# 3. Goals Come First

Probability should help determine **how** an NPC pursues a goal.

It should not determine the goal itself.

Examples of goals:

- survive,
- complete mission,
- protect ally,
- gain promotion,
- preserve reputation,
- capture target,
- avoid exposure,
- earn money.

The NPC evaluates options according to how well they advance those goals.

---

# 4. NPCs Can Have Multiple Competing Goals

A shinobi may simultaneously want to:

- complete the mission,
- protect teammates,
- conserve chakra,
- avoid injury,
- impress their superior.

Those goals can conflict.

For example:

> aggressive pursuit may improve mission success but increase injury risk.

The NPC must weigh priorities.

---

# 5. Goal Priority Should Vary by Character

Different characters should weight goals differently.

Examples:

### Duty-focused
Mission completion may outrank personal safety.

### Protective
Ally survival may outrank mission success.

### Ambitious
Reputation and advancement may carry high weight.

### Self-preserving
Avoids severe risk unless necessary.

This is where personality becomes mechanically meaningful.

---

# 6. Expected Utility Is a Good Internal Model

We do not necessarily need literal visible math, but conceptually NPCs should evaluate:

> **Expected Value of Option = perceived chance of outcomes × importance of those outcomes**

For example:

Option A:
- 80% chance of small gain,
- 20% chance of moderate loss.

Option B:
- 30% chance of huge gain,
- 70% chance of severe loss.

Different personalities may prefer different options.

---

# 7. Risk Tolerance Modifies Choice, Not Reality

A reckless NPC should not actually receive better odds.

They simply accept worse ones.

A cautious NPC does not get easier tasks.

They choose safer options.

So:

> **Risk tolerance affects decision threshold, not resolution mechanics.**

---

# 8. Desperation Changes Acceptable Risk

An NPC may normally reject:

> 20% success with severe consequences.

But if the alternative is:

> certain death,

the same action becomes rational.

So decision-making must compare:

> **option risk against alternative risk.**

Not simply ask:

> Is this dangerous?

---

# 9. No Option Should Be Evaluated in Isolation

Suppose retreat has:

- 60% chance of success.

Fighting has:

- 30% chance of victory.

But surrender has:
- 95% chance of survival.

Which action is best depends on:

- goals,
- beliefs about the enemy,
- consequences of capture,
- personality.

This makes NPC behavior contextual.

---

# 10. NPCs Should Prefer Dominated Options Less Often

If one option is clearly worse in every relevant way, a rational NPC should rarely choose it.

Example:

Route A:
- faster,
- safer,
- cheaper.

Route B:
- slower,
- more dangerous,
- no additional benefit.

Unless the NPC has hidden information or unusual preferences, Route B should not be chosen.

This is a basic consistency safeguard.

---

# 11. Imperfect Information Can Make Bad Options Look Good

An NPC may choose what seems best to them even when the engine knows it is not.

Example:

They believe:
> Route A is safe.

Unknown:
> player placed an ambush there.

So the decision can be rational from their perspective and still end badly.

That is exactly what we want.

---

# 12. Intelligence Should Improve Decision Quality

Intelligence can help NPCs:

- compare options,
- identify tradeoffs,
- avoid obvious dominated choices,
- plan several steps ahead,
- recognize uncertainty.

But it should not make them omniscient.

A genius with bad information can still make a bad decision.

---

# 13. Experience Should Improve Domain Decisions

A veteran shinobi should make better combat-risk judgments than an equally intelligent civilian.

Likewise, a merchant may make better financial decisions than a combat veteran.

Decision quality should be domain-sensitive.

---

# 14. Personality Should Shape Choice Style

Examples:

### Cautious
Prefers:
- information gathering,
- safeguards,
- retreat when outmatched.

### Reckless
Prefers:
- immediate action,
- high-variance strategies,
- aggressive commitment.

### Patient
May wait for better circumstances.

### Impulsive
May act before fully assessing.

### Prideful
May reject retreat or surrender more readily.

These should create tendencies, not rigid scripts.

---

# 15. Personality Should Not Override Survival Instinct Absolutely

A reckless character should not attack a clearly impossible threat every time.

Personality biases thresholds.

It does not delete all rationality.

Only extreme traits, ideology, emotion, or desperation should produce truly self-destructive behavior.

---

# 16. Relationships Affect Utility

An NPC may accept enormous risk for:

- child,
- partner,
- teammate,
- mentor,
- village.

A distant stranger may not justify the same risk.

Relationships therefore change the value of outcomes.

This should affect decisions without becoming arbitrary bonuses.

---

# 17. Loyalty Can Override Personal Safety

A highly loyal shinobi might remain behind to cover retreat even knowing:

> survival chance is poor.

That can be rational relative to their values.

The engine should not assume self-preservation always dominates.

---

# 18. Reputation and Social Consequences Matter

NPCs may consider:

- shame,
- honor,
- promotion,
- disciplinary action,
- public image.

Example:

A chunin might choose to continue a difficult mission because abandoning it would cause serious professional consequences.

These are legitimate stakes.

---

# 19. Resource Conservation Matters

NPCs should consider future needs.

A shinobi with limited chakra may avoid using their strongest technique immediately if:

- mission is long,
- threats remain unknown,
- escape may be necessary later.

A desperate NPC may spend everything.

This makes resource behavior believable.

---

# 20. Future Value Should Matter

Good NPC decision-making should sometimes consider:

> what happens after this action?

Example:

A technique has a 90% chance to defeat one enemy but leaves the user exhausted.

If two more enemies are nearby, it may be a poor choice.

This prevents purely greedy one-step decisions.

---

# 21. Planning Horizon Should Vary

Different characters should reason at different depths.

### Impulsive
Primarily immediate outcome.

### Average
A few steps ahead.

### Strategic
Considers broader mission consequences.

This gives Intelligence and personality more texture.

---

# 22. Time Pressure Reduces Decision Depth

Even a brilliant strategist cannot fully analyze everything in one second.

Under severe urgency, NPCs may:

- rely on habit,
- simplify options,
- use familiar strategies.

This connects directly to stress and experience.

---

# 23. Habit and Doctrine Matter

Characters should develop preferred approaches.

Examples:

- always establish escape route,
- conserve chakra until necessary,
- open with clones,
- avoid direct confrontation.

Military organizations may also teach doctrine.

Under pressure, these habits can heavily influence decisions.

This makes experience persistent.

---

# 24. Habits Should Not Become Deterministic

An NPC who usually retreats when outmatched may occasionally stay because:

- ally is trapped,
- mission is critical,
- retreat route is blocked.

Behavior should remain context-sensitive.

---

# 25. Fear Can Modify Perceived Utility

A frightened NPC may overvalue:

- immediate safety,
- escape,
- defensive actions.

An angry NPC may overvalue:

- retaliation,
- aggressive action.

These are behavioral effects of emotional state.

They do not alter true probabilities.

---

# 26. Overconfidence Can Distort Perceived Odds

An overconfident NPC may believe:

> 70% chance

when the true situation is closer to:

> 40%.

That can cause poor risk-taking.

Again, the decision may be internally rational given their distorted estimate.

---

# 27. Underconfidence Can Cause Excessive Caution

Likewise, an insecure NPC may undervalue their capability.

They may:

- avoid opportunities,
- defer unnecessarily,
- retreat too early.

This creates believable personality differences.

---

# 28. Deception Can Manipulate NPC Decision-Making

If the player successfully convinces an enemy that:

> reinforcements are coming,

the enemy may retreat.

No mind control is needed.

The player changed the NPC's perceived world state.

This is how social and information systems should influence behavior.

---

# 29. Feints Work by Altering Expected Outcomes

A feint may make an opponent believe:

> one option is more dangerous than it really is.

They respond accordingly.

Again, tactical deception affects **perception and choice**, not raw stats.

---

# 30. NPCs Should Update After Outcomes

If an action produces surprising evidence, NPCs should revise their beliefs.

Example:

NPC believes player is weak.

Player casually blocks a powerful technique.

The NPC should update:

> threat estimate upward.

Continuing to behave as though nothing changed would feel artificial.

---

# 31. Updating Speed Should Vary

Some characters adapt quickly.

Others cling to prior beliefs.

Relevant traits might include:

- Intelligence,
- stubbornness,
- pride,
- experience.

But repeated overwhelming evidence should eventually force most characters to adjust.

---

# 32. NPCs Can Misattribute Causes

An NPC may observe:

> their attack failed.

But incorrectly conclude:

> target is physically durable

when the real reason was:

> hidden armor.

This can lead to imperfect adaptation.

That is desirable when justified by limited evidence.

---

# 33. Surrender Should Be a Legitimate Decision

NPCs should sometimes surrender when:

- defeat appears inevitable,
- survival matters,
- opponent seems likely to accept surrender.

But surrender likelihood should depend on:

- values,
- fear,
- mission,
- expected treatment,
- culture,
- loyalty.

Not every enemy should fight to the death.

---

# 34. Retreat Should Be Common When Rational

Likewise, competent NPCs should retreat when:

- objectives cannot be achieved,
- losses outweigh benefits,
- reinforcements can be sought,
- survival preserves future opportunities.

This will make combat feel more realistic than every encounter ending in annihilation.

---

# 35. Retreat Requires Believing Escape Is Possible

An NPC may want to retreat but realize:

> enemy is too fast.

Then surrender, concealment, or desperate resistance may become preferable.

Decision-making should consider feasibility.

---

# 36. NPCs Should Sometimes Gather Information Before Acting

If uncertainty is high and time allows, a rational NPC may:

- observe,
- scout,
- ask questions,
- delay commitment.

This should be especially common among cautious or strategic characters.

Information gathering has value because it improves later decisions.

---

# 37. Value of Information

An NPC should prefer information gathering when:

- uncertainty is high,
- decision stakes are high,
- information can realistically change the decision,
- the cost of gathering it is acceptable.

This is a very useful internal principle.

---

# 38. NPCs Should Not Gather Information When It Cannot Help

If a decision must be made immediately, or if extra information would not change the choice, further investigation may be irrational.

This prevents excessive analysis paralysis.

---

# 39. Group Decisions Need Authority Structure

Teams may decide based on:

- leader,
- consensus,
- specialist advice,
- chain of command.

A squad leader may choose final action while relying on a sensor's threat assessment.

This connects decision-making to teamwork.

---

# 40. Specialists Should Influence Relevant Decisions

A competent leader should generally defer to specialist judgment where appropriate.

Example:

Medic:
> "He cannot survive transport right now."

Leader should factor that into the plan.

But leadership, rank, trust, and personality may determine whether the advice is followed.

---

# 41. Internal Disagreement Can Occur

Different NPCs may prefer different actions because they have:

- different information,
- different goals,
- different personalities.

That can create real conflict.

Example:

One wants to retreat.

Another wants to rescue a teammate.

A third prioritizes mission objective.

This can emerge naturally from the system.

---

# 42. NPC Decisions Should Not Be Optimized for Player Entertainment

The engine should not make enemies choose reckless actions merely because they create exciting combat.

Nor should allies always choose the option most helpful to the player.

NPCs should pursue their own interests consistently.

That is central to the simulation.

---

# 43. NPCs Should Not Know Player Intent Unless They Infer It

An enemy should not automatically counter the player's plan because the engine knows it.

They need:

- observation,
- intelligence,
- prior knowledge,
- inference.

This prevents omniscient AI behavior.

---

# 44. NPCs Can Predict Likely Behavior

However, experienced characters can infer patterns.

Example:

> "He always opens with clones."

That may influence preparation.

This is legitimate because it comes from observed history.

---

# 45. Long-Term Decisions Should Use Broader Evaluation

For career, relationship, training, and political decisions, NPCs should evaluate:

- goals,
- expected benefit,
- time cost,
- resource cost,
- social effects,
- risk,
- opportunity cost.

Not every decision needs a detailed calculation, but the same principles apply.

---

# 46. Off-Screen NPC Decisions Should Be More Abstract

We should not run exhaustive decision trees for every NPC every day.

Instead:

- important NPCs get more detailed reasoning,
- minor NPCs use broader goal-based heuristics,
- routine decisions can be summarized.

Detail should scale with simulation relevance.

---

# 47. Decision Importance Should Determine Processing Depth

A useful hierarchy:

### Routine Decision
Use habit and simple preferences.

### Meaningful Decision
Compare a few realistic options.

### Major Decision
Evaluate goals, risk, relationships, future consequences.

### Life-Changing Decision
Deep evaluation and possibly extended deliberation.

This prevents computational scope creep.

---

# 48. Randomness in Decisions Should Be Limited

Not every NPC choice should be perfectly deterministic.

When two options are similarly attractive, personality-consistent variation can determine choice.

This makes characters less mechanical.

But random choice should not override massive utility differences.

---

# 49. Choice Noise

We might eventually include a small concept of **decision noise** representing:

- mood,
- uncertainty,
- imperfect reasoning.

The closer two options are, the more variation can matter.

The farther apart they are, the more predictable the choice should become.

This mirrors our resolution philosophy nicely.

---

# 50. NPCs Should Have Stable Preferences

If a cautious NPC chose the safest option yesterday, they should generally still behave cautiously today unless something changed.

Behavior should have continuity.

Randomness should create variation around personality, not replace personality.

---

# 51. Strategic Sacrifice

NPCs may knowingly sacrifice:

- resources,
- position,
- personal safety,
- reputation

to protect a higher-priority goal.

Examples:

- teammate survives,
- village protected,
- mission succeeds.

This can produce heroic or ruthless behavior organically from priorities.

---

# 52. Moral Values Can Be Hard Constraints

Some NPCs may refuse certain actions regardless of utility.

Examples:

- will not kill civilians,
- will not betray clan,
- refuses forbidden techniques.

These can act as **decision-space restrictions**.

Values should not merely be another weighted number when they are deeply held.

---

# 53. Values Can Erode or Change Over Time

But hard constraints need not be permanent.

Major experiences may change:

- loyalty,
- morality,
- ambition,
- fear.

That belongs more to character development, but decision-making should use current values.

---

# 54. NPCs Should Remember Consequences

Past outcomes should shape future choices.

Example:

A shinobi nearly died using an unstable technique.

They may become more reluctant to use it again.

Or a reckless character might interpret survival as proof the technique is worth the risk.

The same event can produce different behavioral changes.

---

# 55. Decision Confidence

An NPC may choose an action while being:

- highly confident,
- uncertain,
- desperate.

Confidence can affect:

- commitment,
- willingness to switch plans,
- how quickly they react to contradictory evidence.

This helps model adaptive behavior.

---

# 56. Plan Persistence

NPCs should not abandon plans every time a minor setback occurs.

If they have high confidence and strong commitment, they may continue.

But enough evidence should trigger reassessment.

This avoids erratic AI behavior.

---

# 57. Sunk Costs Should Sometimes Matter

Real characters may continue bad plans because they have already invested:

- time,
- money,
- reputation,
- emotion.

Highly rational characters may resist this bias better.

It can be modeled sparingly for personality realism.

---

# 58. Default NPC Decision Flow

For meaningful choices, the engine should:

### Step 1 — Identify Current Goals
What does the NPC care about right now?

### Step 2 — Identify Available Actions
Only actions the NPC knows are possible.

### Step 3 — Estimate Outcomes
Using perceived probability and perceived stakes.

### Step 4 — Apply Priorities
Goals, values, relationships, mission importance.

### Step 5 — Apply Personality
Risk tolerance, impulsiveness, pride, patience, etc.

### Step 6 — Consider Resources and Future State
What will this option leave afterward?

### Step 7 — Eliminate Impossible or unacceptable options.

### Step 8 — Compare remaining options.

### Step 9 — Use limited decision noise only when options are close.

### Step 10 — Commit to the choice.

### Step 11 — Update beliefs after observing results.

That should become the standard NPC decision architecture.

---

# Example — Outmatched Genin

NPC genin encounters a clearly superior missing-nin.

Perceived options:

**Fight**
- very low success,
- high chance of death.

**Run**
- moderate escape chance.

**Delay enemy while teammate escapes**
- low personal survival,
- strong chance teammate survives.

If the NPC strongly values their teammate, they may choose the third option.

That choice is not irrational.

It reflects goal priorities.

---

# Example — Cautious Chunin

Unknown opponent appears.

The chunin has:

- incomplete information,
- no immediate

---

## Turn 7e8c5e8f-57b8-4358-8fcf-203ddf3b4064

### User

Ok

### Assistant — 7d14de26-6b79-44db-9f62-f50ae901a1a0

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.24 — Player Choice Presentation

This section should define **how uncertain actions are communicated to the player before they commit**.

The system already tracks a lot internally:

- true Difficulty,
- Effective Capability,
- perceived Difficulty,
- perceived odds,
- stakes,
- hidden information,
- resource cost,
- time cost,
- possible consequences.

The player should not see all of that raw machinery.

The central rule should be:

> **Present the information the character can reasonably understand, in a form that supports informed choices without exposing hidden engine math.**

---

## 1. Choices Should Be Described Through Consequences, Not Percentages

Normal gameplay should avoid:

> Sneak past guard — 63% success.

Instead:

> The guard is distracted, and you think you can slip behind him if you move now.

Or:

> Getting past him unnoticed looks risky; he is actively watching the only clear route.

The player learns what matters without turning the simulator into probability optimization.

---

# 2. The Player Should Usually Know Their Own Intent

Choice presentation should make clear what an action is trying to achieve.

Bad:

> Attack him.

Better:

> Rush him and try to interrupt his hand seals.

Or:

> Throw a kunai to force him away from the doorway.

This is important because the resolution system evaluates the **declared objective**.

The engine can infer obvious intent from context, but player-facing choices should be specific enough to avoid ambiguity.

---

# 3. Choices Should Describe Method, Not Just Outcome

There is a major difference between:

> Get inside the compound.

and:

- climb the wall,
- talk your way through the gate,
- sneak through the drainage route,
- wait for a patrol shift.

Those methods invoke different Skills, risks, times, and consequences.

So player options should emphasize:

> **what the character will actually do.**

---

# 4. The Player Should See Meaningful Tradeoffs

When a choice has obvious tradeoffs the character understands, the game should communicate them.

Example:

> You could force the door quickly, but anyone nearby would probably hear it.

> You could work on the lock quietly, though it may take several minutes.

This is much more useful than:

- Force Door
- Pick Lock

The player should understand why the options differ.

---

# 5. Exact Odds Should Normally Stay Hidden

We should default to qualitative estimates.

Possible phrasing:

- routine,
- favorable,
- uncertain,
- risky,
- very difficult,
- extremely unlikely,
- no realistic chance.

But these should be woven naturally into prose rather than constantly displayed as formal labels.

For example:

> You are confident you can clear the gap.

is better than:

> Difficulty: Favorable.

---

# 6. Exact Numbers Can Exist in Debug/Test Modes

For balancing and system development, we absolutely should be able to expose:

- Effective Capability,
- Difficulty,
- Resolution Margin,
- true probability,
- perceived probability,
- modifiers.

But that should be a separate simulation/debug presentation mode.

Normal player-facing gameplay should remain immersive.

---

# 7. Character Knowledge Controls What Is Shown

If the character does not know something, the player should not receive it as actionable certainty.

Example:

Hidden sensor behind a wall.

Bad:

> Sneaking through this corridor is extremely risky because an enemy sensor is nearby.

Better:

> You don't notice anything unusual about the corridor.

If the character has reason for suspicion:

> Something about the area feels unusually quiet, but you cannot identify a specific threat.

Presentation must respect knowledge state.

---

# 8. Uncertainty Should Be Communicated Honestly

The engine should not pretend certainty where the character has none.

Useful language:

> You cannot get a good read on him.

> The route looks manageable, but you have not seen enough of the patrol pattern to be confident.

> You think the seal is within your ability, though part of its structure is unfamiliar.

This allows the player to make choices under genuine uncertainty.

---

# 9. Known Risk Should Be Communicated Before Commitment

When the character recognizes serious consequences, the player should generally know before acting.

Example:

> You can probably cross the beam, but a fall from this height would likely be fatal.

Or:

> You could push the technique harder, but you are already low on chakra and another large expenditure may leave you unable to retreat.

This protects player agency.

---

# 10. Hidden Risk Should Remain Hidden

If the danger is genuinely unknown to the character, the game should not spoil it.

Example:

A seemingly safe chest is trapped.

Unless the character detects signs of the trap:

> it appears to be an ordinary locked chest.

That is fair because the hidden danger exists independently of the player.

---

# 11. Avoid Fake Warning Language

The engine should not use ominous narration merely because something bad is secretly present.

For example:

> You reach for the perfectly normal-looking door... an uneasy feeling crawls up your spine.

unless the character actually has some reason to feel uneasy.

Otherwise the narration itself leaks hidden information.

---

# 12. Choice Menus Should Not Reveal Hidden Variables

If the player has four options and one is secretly dangerous, the formatting should not give it away.

Bad:

- Open Door
- Search Hallway
- **Carefully Inspect Suspicious Door**
- Leave

The wording itself reveals the secret.

Choice presentation must avoid meta-signals.

---

# 13. Not Every Action Needs a Menu

This simulator should not become:

> A) Talk  
> B) Walk  
> C) Attack  
> D) Leave

after every paragraph.

The player should generally be free to describe actions naturally.

Suggested choices are useful when:

- the situation is complex,
- several obvious approaches exist,
- the player may benefit from seeing options,
- a decision point is especially meaningful.

But free-form input should remain central.

---

# 14. Suggested Choices Are Examples, Not Limits

If choices are presented, the player should always be able to do something else.

For example:

> You could try to bluff the guard, wait for a distraction, or find another entrance.

The player may instead say:

> I create a shadow clone and have it start an argument down the street.

The engine should support that if plausible.

---

# 15. Choices Should Reflect What the Character Knows Is Possible

The system should not suggest techniques or strategies the character would not reasonably consider.

If the character has never heard of chakra suppression:

> "Suppress your chakra signature"

should not appear as an option.

Likewise, options should reflect:

- known abilities,
- equipment,
- relationships,
- information.

This makes character development meaningful.

---

# 16. Routine Actions Should Not Need Confirmation

If the player says:

> I walk home.

and nothing meaningful obstructs that:

> simply do it.

Do not interrupt with:

> Are you sure?

Choice presentation should focus on meaningful uncertainty and tradeoffs.

---

# 17. High-Stakes Irreversible Actions Deserve Clearer Framing

For major irreversible decisions, the game should make consequences clear when the character understands them.

Examples:

- abandoning the village,
- executing a prisoner,
- using a forbidden technique,
- signing a binding political agreement.

The game need not ask for confirmation every time, but it should avoid accidental ambiguity.

For example:

> If you do this openly, the village will almost certainly treat it as desertion.

That gives the player enough context.

---

# 18. Do Not Spoil Future Consequences

There is a difference between:

> obvious consequence

and

> future outcome.

The engine may say:

> Killing him could trigger retaliation from his clan.

It should not say:

> Killing him will cause his brother to assassinate you three months later.

unless the character somehow knows that plan.

Choice presentation should inform, not predict omnisciently.

---

# 19. Resource Costs Should Be Shown When Knowable

The player should understand meaningful costs their character can reasonably estimate.

Example:

> This technique normally costs little chakra for you.

or:

> Using it at full output would consume a large portion of your remaining reserves.

Exact numbers may be available if the game eventually uses visible resource pools.

But the presentation should still contextualize the cost.

---

# 20. Time Costs Should Be Visible When Relevant

If one approach takes:

- seconds,

and another:

- thirty minutes,

the player should know when that difference matters.

Example:

> Carefully bypassing the seal could take ten to fifteen minutes. Breaking it would be much faster, but much louder.

Again, tradeoffs rather than raw stats.

---

# 21. Stakes Should Be Presented Separately From Difficulty

This is important.

The player should be able to understand:

> Easy but dangerous.

Example:

> The jump itself looks well within your ability. The problem is that there is nothing below you if you slip.

Likewise:

> The puzzle is extremely difficult, but there is no meaningful downside to taking your time.

This reinforces the architecture we established earlier.

---

# 22. Perceived Power Gaps Should Be Communicated Specifically

Avoid generic:

> He is much stronger than you.

Better:

> His movements are significantly faster than yours, and you doubt you could match him in a direct taijutsu exchange.

Or:

> You cannot gauge his ninjutsu, but his chakra control appears far beyond your own.

Specific information creates tactical choices.

---

# 23. Unknown Matchups Should Stay Uncertain

If the character cannot judge someone:

> You have no reliable sense of what he can do.

Do not provide a hidden danger rating.

This lets scouting and observation retain value.

---

# 24. Viable Alternative Objectives Should Be Visible Through Context

When direct victory is nonviable, the game should not necessarily say:

> You cannot win.

It should communicate what remains plausible.

Example:

> You don't think you can overpower him directly, but he is between you and the exit—and he has not yet noticed your teammate moving behind him.

That naturally suggests:

- distraction,
- escape,
- teamwork.

The game supports agency without prescribing one answer.

---

# 25. Automatic Outcomes Should Usually Not Show Odds

If the character can do something automatically:

> You climb the wall easily.

No need to say:

> 100% success.

Likewise, if an action is obviously impossible:

> Even with chakra reinforcement, you cannot physically lift that structure in its current state.

No probability is needed.

---

# 26. Hidden Rolls Should Never Be Announced

Never present:

> Hidden Perception Check...

or:

> Insight failed.

Instead, narrate the resulting perceived state.

This should remain strict.

---

# 27. The Player Should Know When Their Character Is Unsure

Hidden mechanics should not mean vague narration all the time.

If the character recognizes uncertainty, say so.

Example:

> You cannot tell whether he is lying.

That is valuable information.

It says:

> the character lacks confidence.

It does not expose the hidden truth.

---

# 28. Confidence Language Should Match Evidence

Possible natural language:

### High confidence
> You're confident...

### Moderate confidence
> You think...

### Low confidence
> It might...

### Very low information
> You can't tell...

These are useful without formal numerical labels.

---

# 29. Do Not Turn Wording Into a Secret Probability Code

We should avoid rigidly mapping:

> “confident” = 80–89%.

The language should be flexible enough that players cannot perfectly decode percentages from wording.

The player should understand the broad situation, not reverse-engineer the exact formula.

---

# 30. Presentation Can Include Character Reasoning

When helpful, the game can explain **why** the character thinks something.

Example:

> His stance is sloppy, but his weight distribution is too controlled for a complete novice. You suspect he's hiding more experience than he appears to have.

This is much better than:

> Threat assessment: Moderate.

It also reinforces Attributes and Skills through narration.

---

# 31. Expert Characters Should Get Better Action Context

A skilled shinobi might receive:

> The seal's outer layer is simple. The nested trigger is the real problem; if you rush it, you could activate the alarm.

A novice might receive:

> The seal looks complicated.

The player sees more because the character understands more.

---

# 32. Player Intent Can Be Inferred Without Constant Clarification

If the player says:

> I throw a kunai at his hand while he's forming seals.

The intent is obvious:

> interrupt the hand seals.

The engine should not constantly ask:

> What are you trying to accomplish?

It should infer reasonable intent from context.

Clarification is only necessary when substantially different interpretations would matter.

---

# 33. Compound Intent Should Be Recognized

Example:

> I sneak into the room, steal the scroll, and leave without being noticed.

That contains several objectives:

- enter unseen,
- acquire scroll,
- exit unseen.

The engine should recognize the compound objective and resolve at the appropriate scale rather than reducing everything to:

> Stealth check.

---

# 34. Player-Declared Priorities Matter

The player can specify what matters most.

Example:

> I don't care if I'm seen; I just need to reach her before the attacker does.

Now:

- speed is primary,
- secrecy is irrelevant.

This should change the resolution objective.

The engine should respect explicit priorities.

---

# 35. Players Can Accept Costs Deliberately

The player might say:

> I burn as much chakra as necessary. I don't care about exhaustion.

That changes resource commitment.

Or:

> I'll let him see me if it gets my teammate out.

That changes the objective and stakes.

This kind of declaration should matter mechanically.

---

# 36. Player Choices Should Never Secretly Change After Selection

If the game presents:

> Try to disarm him.

and the player chooses it, the engine should not internally reinterpret that as:

> try to kill him.

The resolved objective must remain faithful to the choice.

---

# 37. Failure Should Respect Declared Intent

If the player attempts:

> distract the guard,

failure should relate to that objective.

It should not arbitrarily become:

> your character attacks the guard.

Consequences can escalate naturally, but the engine should not invent actions the player never chose.

---

# 38. Outcomes Should Not Reveal Raw Mechanics Unless Useful

Normal narration should say:

> You nearly make it past him, but his head turns at the last second.

Not:

> Your Stealth 58 lost against Detection 61.

The latter belongs in debug mode.

---

# 39. The Player Should Understand Why Visible Outcomes Happened

Even without numbers, outcomes should usually be narratively legible.

Example:

> Your injured ankle slows your landing just enough for him to close the gap.

That tells the player which established circumstance mattered.

This builds trust in the simulation.

---

# 40. Avoid Over-Explaining Every Modifier

At the same time, we should not narrate:

> Because you had +5 terrain, −10 fatigue, +2 familiarity...

Instead, mention the most causally important factors.

The underlying system can remain detailed without dumping bookkeeping into prose.

---

# 41. Major Consequences Should Be Explicit

When something important happens:

- serious injury,
- alert triggered,
- identity exposed,
- relationship broken,

the player should generally understand that it occurred if their character would know.

Do not hide obvious consequences behind vague wording.

---

# 42. Delayed Consequences Can Remain Hidden

If the player unknowingly triggered suspicion:

> that can remain hidden.

They may discover it later through changed NPC behavior.

This preserves information asymmetry.

---

# 43. Choice Presentation Should Support Tactical Creativity

The best presentation should often describe:

- environment,
- threats,
- opportunities,
- known constraints.

Then let the player invent tactics.

For example:

> The hallway is narrow, the lights are out, and the guard is standing with his back to the stairwell. A second guard is somewhere downstairs.

That naturally creates options without listing every possible action.

---

# 44. Environment Descriptions Should Include Mechanically Relevant Details

If:

- cover,
- distance,
- visibility,
- terrain,

could materially affect decisions, the player should usually know those facts when the character can see them.

This prevents the engine from later invoking environmental conditions the player was never given a chance to consider.

---

# 45. Do Not Flood the Player With Irrelevant Detail

Only describe mechanically or narratively useful features.

If the room contains:

- six chairs,
- three lamps,
- twelve bookshelves,

those do not all need mention unless relevant.

The player needs enough environmental information to make informed choices, not exhaustive scene inventories.

---

# 46. Time-Sensitive Decisions Should Feel Time-Sensitive

If the character has only seconds, choice presentation should be concise.

Example:

> The kunai is already in the air. You can dive aside, raise your guard, or attempt to intercept it.

The engine should not give a leisurely paragraph of tactical analysis unless the character has time to think.

---

# 47. Long-Term Decisions Can Provide More Context

For career, training, research, or relationship choices, the game can present:

- expected time,
- known costs,
- likely tradeoffs,
- uncertainty.

The player has more time, so more analysis is appropriate.

---

# 48. Presentation Detail Should Scale With Decision Importance

A useful rule:

### Routine
Minimal explanation.

### Meaningful
Key tradeoffs.

### High Stakes
Clear risk and known consequences.

### Irreversible
Explicitly communicate what the character understands they may be committing to.

This avoids both clutter and accidental decisions.

---

# 49. Choices Should Not Reveal “Correct” Answers

Avoid presentation like:

> Smart option: Scout first.

or:

> Risky option: Attack.

unless the character actually perceives those differences.

The game should provide information, not tell the player what choice is optimal.

---

# 50. No Color-Coded Morality or Optimality

We should avoid things like:

- green = good,
- red = bad,
- gold = best choice.

Unless some future UI uses colors strictly for categories unrelated to recommendation.

The simulation should let the player decide what they value.

---

# 51. Player-Facing Probability Should Be Optional

I think normal gameplay should remain qualitative.

But because this is a text simulator, we could eventually support an optional setting such as:

### Immersive
Narrative-only estimates.

### Informative
Qualitative difficulty/risk labels.

### Debug
Exact underlying values.

This could be very useful during development.

I would not make exact odds part of default gameplay.

---

# 52. Debug Information Must Not Affect Resolution

If exact numbers are visible in testing mode, the underlying simulation should remain identical.

Debug mode reveals state.

It does not change it.

This is useful for balancing.

---

# 53. Recommended Choice-Presentation Procedure

Before a meaningful player decision:

### Step 1 — Determine what the character actually knows.

### Step 2 — Determine what they can reasonably estimate.

### Step 3 — Identify meaningful:
- objectives,
- tradeoffs,
- costs,
- risks,
- environmental opportunities.

### Step 4 — Hide unknown variables.

### Step 5 — Communicate obvious stakes and nonviability.

### Step 6 — Present options naturally if useful, without trea

---

## Turn dbff17c6-ad9d-463f-905e-2e9849d6123a

### User

Ok

### Assistant — 7794316f-054b-4cb1-b907-7fca72eca689

# Ruleset 2.25 — Outcome Narration

This section should define how internal resolution results become player-facing prose.

The goal is not just to say what happened. The narration should also make the result feel **causal, proportionate, and consistent with the character's perspective**.

The central rule should be:

> **Narration should describe the outcome, its most important causes, and its immediate consequences without exposing hidden mechanics the character would not know.**

## 1. Narrate the Result, Not the Roll

Avoid:

> You succeeded.

> You failed the check.

> Critical failure.

Instead:

> You slip through the doorway just before the guard looks back.

or:

> Your pick catches on the final pin, but the mechanism refuses to turn.

The player should experience the world result rather than the engine terminology.

## 2. Outcome Degree Should Change Tone and Detail

The narration should reflect the degree of success or failure.

### Narrow Success
Emphasize closeness and imperfect execution.

> You clear the gap, but your heel clips the ledge and you land hard.

### Standard Success
Clean completion.

> You clear the gap and land securely on the opposite roof.

### Strong Success
Clear control or additional efficiency.

> You cross cleanly, barely breaking stride.

### Exceptional Success
Near-best plausible execution.

> You clear the gap effortlessly and land exactly where you intended, keeping your momentum.

The action is the same. The quality is different.

## 3. Failure Needs the Same Range

### Narrow Failure
Almost succeeds.

> Your fingers catch the ledge for an instant, but you cannot establish a grip.

### Standard Failure
Objective clearly fails.

> You come up short and strike the wall below the ledge.

### Severe Failure
Execution goes substantially wrong.

> Your takeoff slips on the wet tile, leaving you well short of the opposite roof.

The narration should make the degree legible without naming it.

## 4. Narration Should Explain the Most Important Cause

When a visible established factor materially affected the outcome, mention it.

Example:

> Your injured ankle gives way slightly on takeoff, robbing you of the distance you needed.

This is better than:

> You fail to jump far enough.

It tells the player that the injury mattered.

But we should not explain every internal factor.

If the engine used:

- fatigue,
- wet footing,
- injury,
- wind,

the narration should emphasize the factor or two that mattered most.

## 5. Do Not Explain Hidden Causes the Character Cannot Know

Suppose the player fails to sneak past a guard because the guard has a secret sensory technique.

Bad:

> His hidden sensory ability detects your chakra.

if the character does not know that ability exists.

Better:

> You are nearly past when his attention suddenly snaps toward your position.

The player sees the observable consequence.

The cause remains uncertain.

## 6. Character Perspective Controls Description

The narration should reflect what the controlled character perceives.

If they cannot see the opponent:

> You hear a sharp movement behind you.

Not:

> The enemy raises a kunai over your left shoulder.

unless another sense provides that information.

This is essential for hidden-information integrity.

## 7. Narration Should Distinguish Observation From Interpretation

Example:

Observation:

> His hand trembles slightly as he answers.

Interpretation, if supported:

> The hesitation feels inconsistent with his otherwise confident story.

Avoid converting uncertain interpretation into objective fact.

Bad:

> He lies nervously.

unless the character genuinely knows that.

## 8. Uncertainty Should Stay in the Language

Useful phrases include:

- appears,
- seems,
- you think,
- you suspect,
- you cannot tell,
- probably,
- likely.

These should reflect actual information confidence, not decorative vagueness.

If the character knows something, say it clearly.

If they do not, preserve uncertainty.

## 9. Known Facts Should Be Stated Directly

Once something is clearly established to the character:

> The seal is broken.

Not:

> The seal seems broken.

Overusing uncertainty language would make the engine feel evasive.

Confidence should match evidence.

## 10. Automatic Success Should Usually Be Brief

If a routine action succeeds automatically:

> You vault the fence and continue down the alley.

No need for:

> With years of shinobi training, your highly developed Agility allows you to easily overcome the relatively low difficulty...

Routine competence should feel routine.

## 11. Automatic Failure Should Still Show What Happens

If the objective is impossible:

Bad:

> You cannot do that.

Better:

> You drive your shoulder into the stone door, but it does not shift.

The action still occurs.

The world responds.

This also gives the player information about why the method failed.

## 12. Failure Should Not Humiliate Competent Characters Without Cause

A master failing narrowly should not suddenly become clumsy.

Bad:

> You trip over your own feet and embarrass yourself.

Better:

> The opponent adjusts at the last instant, forcing your strike just wide.

Experts can fail because:

- opposition was strong,
- circumstances changed,
- timing was close.

Their competence should remain visible even in failure.

## 13. Weak Characters Can Succeed Without Suddenly Looking Like Masters

Likewise, a low-probability success should usually look strained or narrow.

Example:

> You barely wedge the door open before the mechanism catches again, but the opening is just wide enough to slip through.

Not:

> You dismantle the advanced mechanism with flawless expertise.

The outcome should respect established capability.

## 14. The Narration Should Preserve Objective Scope

If the player tries:

> distract the guard.

A strong success should still be about distraction.

It should not casually escalate into:

> the guard leaves the compound forever.

unless that genuinely follows from the situation.

Narration should remain faithful to the declared objective.

## 15. Costs Should Be Included When They Matter

For a narrow or costly success:

> The barrier holds, but maintaining it drains far more chakra than you intended.

That is better than separately announcing:

> Success. Chakra −12.

The mechanical consequence can still be tracked internally.

The prose should explain it naturally.

## 16. Important State Changes Should Be Clear

If the result changes:

- location,
- injury,
- alert level,
- equipment,
- relationship,
- mission state,

the player should understand that if their character does.

Example:

> The guard sees your face clearly before you turn the corner. Your identity is compromised.

This is a meaningful consequence and should not be buried.

## 17. Minor Persistent Consequences Can Be Subtle

Some consequences can be conveyed more softly.

Example:

> The guard watches you leave for a moment longer than before.

This may represent increased suspicion.

The player sees the behavior without being told:

> Suspicion +8.

That is ideal for hidden social states.

## 18. Narration Should Advance the World

An outcome should usually leave the scene in a new state.

Instead of:

> You fail to persuade him.

Better:

> He shakes his head. “No. And if you keep pushing this, I’m ending the conversation.”

Now:

- persuasion failed,
- willingness to continue changed,
- future options changed.

The simulation moved.

## 19. Avoid Repetitive Resolution Templates

We should avoid producing the same pattern constantly:

> You attempt X. Unfortunately, Y. However, Z.

Narration should vary naturally by:

- action type,
- character,
- environment,
- outcome degree.

Otherwise the simulation will quickly feel procedural.

## 20. But Consistency Matters More Than Literary Flourish

The engine is first a simulator, second a narrator.

It should not embellish outcomes so heavily that it changes what mechanically happened.

If the result is:

> narrow stealth success with minor suspicion,

the narration should not turn it into a cinematic chase scene.

Prose serves simulation state.

## 21. Concision Should Scale With Importance

Routine result:

> You finish the report before lunch.

Important mission result:

More detail may be appropriate.

Major turning point:

Can receive richer narration.

This helps preserve pacing.

## 22. Combat Resolution Should Focus on Position and Effect

Later combat narration should not simply describe:

> hit/miss.

It should communicate:

- movement,
- defense,
- positioning,
- injury,
- interrupted actions,
- tactical changes.

Example:

> Your kunai catches his sleeve rather than his wrist, but the pull breaks his hand-seal sequence and forces him to reset.

This directly reflects the declared objective.

## 23. Social Narration Should Preserve NPC Agency

Bad:

> Your persuasive argument makes her agree.

Better:

> Her expression softens. She still hesitates, but after a moment she agrees to delay the report until morning.

The NPC should feel like a person making a decision, not a target whose mind was mechanically overwritten.

## 24. Information Results Should Describe Evidence

Instead of:

> Investigation success.

Use:

> The ink on the signature is noticeably fresher than the rest of the document.

Then, when interpretation is earned:

> The discrepancy strongly suggests the signature was added later.

Evidence-first narration makes investigations much stronger.

## 25. Training Outcomes Should Show What Improved

Instead of:

> Training successful.

Use:

> By the end of the session, you can maintain the chakra flow through the turn without the technique collapsing.

This gives the player a concrete sense of progression.

## 26. Extended Projects Should Narrate Milestones, Not Every Increment

For long projects, do not narrate every tiny progress gain.

Instead surface meaningful changes:

> After several failed prototypes, you finally stabilize the flame long enough to test compression.

That is much more satisfying than:

> Research Progress: 43% → 47%.

Debug mode can show the raw values if needed.

## 27. NPC Outcomes Should Be Narrated Only at Relevant Detail

If an off-screen NPC spends a week training:

> Karn spends most of the week on messenger duty and makes modest progress with his movement training.

No need for scene-level narration unless the player is directly involved.

This keeps world simulation manageable.

## 28. Narration Should Respect Time Scale

A one-second action should read quickly.

A week-long event can summarize.

Example:

Combat:
> He ducks under the strike and drives forward.

Long-term:
> Over the next two weeks, the project advances steadily, though the stabilization problem remains unresolved.

Narrative scale should match simulation scale.

## 29. Do Not Narrate Internal Numbers as Feelings Unless Justified

Bad:

> You feel exactly 64% confident.

Better:

> You think you have the edge, but not enough to be careless.

Likewise, avoid turning mechanical stats into supernatural intuition unless an ability supports it.

## 30. Critical Events Deserve Stronger Emphasis

When a true critical event occurs, narration should make the consequence feel distinct.

Example:

> The seal does not merely fail—the inner ring fractures. Chakra surges backward through the inscription before the containment layer can close.

This feels significant because something significant actually happened.

Not because the engine shouted:

> CRITICAL FAILURE!

## 31. Rare Events Should Be Narrated as World Events

If a rare event occurs:

> A sudden crack of thunder rolls across the valley as the storm front breaks earlier than forecast.

The narration should treat it as part of the world.

Not:

> Rare Event Triggered!

Again, mechanics remain internal.

## 32. Player Skill Should Affect Perceptual Richness

A highly perceptive or knowledgeable character should sometimes receive richer narration.

Novice:

> The opponent moves quickly.

Expert:

> His first step is explosive, but his weight shifts heavily onto his right leg before he accelerates.

That difference should come from character capability.

This makes Attributes and Skills visible through prose.

## 33. Low Skill Should Not Mean Dumb Narration

A novice character should not be described as incompetent unless they actually are.

They simply receive less precise information.

For example:

> You can tell the seal is complex, but you do not recognize the structure.

That preserves dignity and realism.

## 34. Outcome Narration Should Avoid Retconning

Once the narration establishes:

> the door remained locked,

we should not later say:

> actually, it opened slightly

unless that was already part of the result.

Narration is part of persistent world state.

Specific details should remain consistent.

## 35. Ambiguous Results Should Stay Ambiguous When Appropriate

If a hidden-information result is uncertain:

> You catch movement at the edge of your vision, but when you look directly, nothing is there.

Do not immediately resolve whether it was:

- enemy,
- animal,
- imagination.

The uncertainty itself may be the outcome.

## 36. Failed Actions Can Reveal New Options

Example:

> The stone door doesn't move, but the impact sends dust from a thin seam along its right edge.

The Strength attempt failed.

But the character learned:

> there may be another mechanism.

This is a good form of failing forward because it follows causally.

## 37. Narration Should Not Manufacture Consolation Prizes

If nothing useful comes from failure:

> nothing useful comes from failure.

Example:

> The lock remains closed.

That's enough.

We should not force every failed action to reveal a clue or opportunity.

## 38. Characters Should Receive Credit for Good Decisions Even When RNG Goes Against Them

If the player made an excellent tactical choice but loses a close uncertain outcome, the narration should preserve the quality of the plan.

Example:

> The trap works exactly as intended, but he reacts faster than you anticipated and catches the wire before it fully tightens.

The plan mattered.

The opponent still overcame it.

This makes the simulator feel fair.

## 39. Poor Decisions Should Not Be Rescued by Narration

Likewise, if the player chooses an obviously bad approach and luck allows a narrow success:

> the narration should show how close it came to failure.

Do not rewrite the action as brilliant strategy after the fact.

## 40. Cause, Outcome, Consequence

A useful narrative structure for important resolutions is:

**Cause**
What mattered.

**Outcome**
What happened.

**Consequence**
What changed.

Example:

> The rain makes the roof slick, and your injured ankle cannot fully stabilize the landing. You make the jump, but skid hard against the parapet. You're across, though the impact sends pain through your leg and costs you several seconds.

That communicates everything relevant without showing math.

## 41. Not Every Result Needs All Three Explicitly

For routine actions:

> You open the window and climb inside.

Simple is better.

The Cause → Outcome → Consequence structure is mainly for meaningful resolution.

## 42. Recommended Narration Procedure

After resolution:

### Step 1 — Identify What the Character Perceives
Exclude hidden engine knowledge.

### Step 2 — Identify Outcome Degree
Narrow, standard, strong, exceptional, etc.

### Step 3 — Identify the Most Important Causal Factors
Only those visible or inferable to the character.

### Step 4 — Identify Immediate Consequences
State changes, costs, information, position.

### Step 5 — Determine Appropriate Detail
Based on importance and time scale.

### Step 6 — Narrate Naturally
No mechanical labels unless debug mode is active.

### Step 7 — Persist Every concrete fact established by the narration.

---

# Example — Stealth

Internal result:

- narrow success,
- guard suspicion increased slightly.

Narration:

> You slip through the doorway just before the guard turns. He pauses at the faint sound behind him, but by the time he looks, you're already out of sight.

The player knows:

- success,
- close call,
- guard may be somewhat alert.

They do not know:

> Suspicion +6.

Perfect.

---

# Example — Medical Failure

Internal:

- standard failure,
- patient stable enough that no severe consequence occurs.

Narration:

> Your first attempt does not stop the bleeding. The wound is still manageable, but you've lost valuable time and will need another approach.

No melodrama.

The failure matters.

---

# Example — Hidden Opponent

Internal:

- enemy sensor detects player,
- player does not know sensor exists.

Narration:

> The man ahead suddenly stops walking.

That's enough.

The world changed.

The reason remains hidden.

---

# What I Would Lock In

> **Outcome narration describes world results, not roll results.**

> **Degree of outcome should be visible through the quality and severity of what happens.**

> **Narration should explain the most important visible causes without exposing hidden mechanics.**

> **Competent characters should remain visibly competent even when they fail.**

> **Long-shot successes should remain proportionate to the character's capability.**

> **Costs, injuries, alerts, position changes, and other important world-state changes should be communicated clearly when known.**

> **Hidden consequences remain hidden when the character cannot perceive them.**

> **Narration should move the simulation into a new persistent state rather than merely announce success/failure.**

> **Detail scales with importance and time scale.**

> **Evidence and observation should generally be narrated before interpretation.**

> **Outcome narration never invents benefits, hazards, or actions that were not supported by the actual resolution.**

> **Every concrete fact established in narration becomes part of persistent world state.**

Next should be **Ruleset 2.26 — Failure Consequences & Failing Forward**, which will formalize when failure should create complications, partial progress, escalation, loss, or simple dead ends—and importantly, when *not* to force failing forward just because it makes for a better story.

---

## Turn 5d7308cd-8827-41df-adda-82e0e5da25a4

### User

Ok

### Assistant — 33c35c53-c9cd-4621-8549-b29afe41192c

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.26 — Failure Consequences & Failing Forward

Failure should matter, but it should not automatically mean catastrophe, nor should every failure conveniently create a new opportunity.

The central rule should be:

> **Failure changes the world according to what the character actually attempted, what they were exposed to, and how badly the attempt failed.**

“Failing forward” should be a consequence of world logic, not a narrative requirement.

## 1. Failure Means the Objective Was Not Achieved

At minimum, failure means:

> the intended objective was not successfully completed.

Everything beyond that depends on context.

A failed lockpick attempt may mean:

> the door remains locked.

A failed jump may mean:

> the character falls.

A failed persuasion attempt may mean:

> the NPC refuses.

We should not automatically add extra punishment.

---

# 2. Failure and Consequence Are Separate

The system should distinguish:

### Primary Failure
The intended objective is not achieved.

### Secondary Consequence
Something else happens because of the failed attempt.

This matters because many failures should have little or no additional consequence.

Example:

> You fail to remember the name of a historical figure.

That does not need:

- embarrassment,
- reputation loss,
- stress damage.

Unless the situation actually supports those consequences.

---

# 3. Consequences Require Exposure

A character can only suffer a consequence if the attempt exposed them to it.

Examples:

Trying to sneak past a guard exposes the character to:

- detection,
- suspicion,
- identification.

Trying to climb a cliff exposes them to:

- falling,
- injury,
- equipment loss.

Trying to research a historical fact in a safe library does **not** normally expose them to:

- physical injury.

This should remain strict.

---

# 4. Outcome Degree Controls How Much Goes Wrong

Our existing degree system should naturally shape failure consequences.

### Narrow Failure
Objective barely fails.

### Standard Failure
Clear failure with ordinary consequences.

### Severe Failure
Significant loss or complication becomes plausible.

### Catastrophic-Range Failure
Worst plausible branches may become available.

But:

> **Outcome degree determines eligible severity, not automatic consequence severity.**

---

# 5. Failure Cannot Exceed the Situation's Outcome Floor

Every action has a worst plausible result.

Example:

Failing to throw a paper ball into a wastebasket:

> paper misses.

It should not somehow cause:

> broken arm.

Even if the hidden Outcome Margin is extremely negative.

The context caps the failure.

---

# 6. Some Failures Are Clean Failures

A clean failure means:

> objective not achieved, nothing else significant happens.

Examples:

- answer is wrong,
- lock remains closed,
- target refuses request,
- search finds nothing.

Clean failure is completely valid.

We should not fear dead ends when a dead end is the logical result.

---

# 7. Some Failures Consume Resources

A failed action may still consume:

- chakra,
- stamina,
- time,
- ammunition,
- materials,
- money,
- social goodwill.

This should depend on how the attempt works.

Example:

A jutsu fails after chakra is already committed.

The chakra is still spent.

---

# 8. Some Failures Consume Opportunity

Certain attempts cannot simply be repeated.

Examples:

- ambush fails,
- surprise lost,
- lie exposed,
- target escapes,
- one-time political opportunity passes.

In those cases, failure changes what actions remain possible.

This is often more meaningful than a numeric penalty.

---

# 9. Some Failures Worsen Position

Examples:

- guard becomes alert,
- opponent gains distance,
- character loses cover,
- negotiation becomes more hostile.

These are **positional consequences**.

They should persist until something changes them.

---

# 10. Some Failures Reveal Information

Failure can sometimes teach the character something.

Example:

> The seal resists your first approach, but the reaction reveals that the outer layer redirects chakra instead of absorbing it.

This is valid because the attempt produced observable feedback.

It is not a consolation prize.

---

# 11. Information From Failure Must Have a Cause

Do not automatically award:

> clue discovered because the player failed.

Information should come from:

- visible reaction,
- error feedback,
- partial progress,
- opponent response,
- changed environment.

If nothing informative happens, failure can simply provide no new information.

---

# 12. Partial Progress Should Exist Only for Divisible Objectives

Some tasks naturally allow partial progress.

Examples:

- climbing distance,
- research,
- construction,
- tracking,
- moving an object.

Others do not.

Example:

> convince guard that you are an authorized inspector

may not have meaningful “42% persuaded” as an immediate outcome.

So partial success/failure should be domain-specific.

---

# 13. Compound Objectives Can Split

If the player attempts:

> sneak inside, steal the scroll, and leave unnoticed,

a failure may occur on only one component.

Possible result:

- gets inside,
- gets scroll,
- is detected while leaving.

That is not arbitrary partial success.

The objective itself had separable components.

---

# 14. Failing Forward Means the Situation Continues

A good definition for this system:

> **Failing forward occurs when failure creates a new playable state rather than simply resetting or ending the situation.**

Example:

Lockpick fails and guard hears something.

Now the situation becomes:

> hide, bluff, flee, fight, or try another method.

That is failing forward.

---

# 15. Failing Forward Is Not Mandatory

This should be explicit.

Bad design rule:

> Every failure must create a new opportunity.

Our rule:

> Every failure must create the logically correct state.

Sometimes that state is:

> you cannot progress through this route.

The player may need to:

- find another route,
- gather new resources,
- abandon the objective.

That is acceptable.

---

# 16. Do Not Protect the Player From Meaningful Failure

If a mission can fail, it should genuinely be able to fail.

The engine should not secretly turn every failure into:

> success, but with a complication.

Otherwise risk becomes fake.

Examples of legitimate failure:

- target escapes,
- mission objective lost,
- exam failed,
- promotion denied,
- relationship ends.

Persistent simulation requires real loss.

---

# 17. “Success With Cost” Is Still Success

If the character achieves the objective but pays a price:

> that belongs to narrow or costly success.

It should not be mislabeled as failure.

Example:

> You open the door, but your lockpick breaks.

Primary objective succeeded.

Cost occurred.

This distinction keeps resolution clear.

---

# 18. “Failure With Progress” Is Still Failure

Example:

> You fail to decode the document, but eliminate one possible cipher family.

Primary objective failed.

Some useful progress occurred.

This distinction also matters.

---

# 19. Consequence Severity Should Match Stakes

A narrow failure during:

> casual practice

should remain minor.

A narrow failure while:

> defusing an unforgiving explosive seal

may still trigger a serious consequence if the mechanism is binary.

So failure degree and stakes interact.

Neither replaces the other.

---

# 20. Binary Hazards Need Special Treatment

Some systems genuinely have threshold behavior.

Example:

A trap activates if the wrong wire is cut.

If the character narrowly fails:

> the trap may still activate fully.

That is not unfair if the mechanism was actually binary.

The engine should not soften every consequence purely because the failure was narrow.

---

# 21. But Binary Hazards Should Be Established

We should avoid inventing binary consequences after the fact.

If the mechanism is unforgiving:

> that should be part of the world state before the roll.

Preparation and knowledge may reveal that risk.

This protects simulation fairness.

---

# 22. Failure Consequences Should Be Causal Chains

A good failure consequence should answer:

> Why did this happen?

Example:

Stealth failure:
> you step on loose gravel → guard hears it → guard investigates.

Not:

> stealth failure → unrelated patrol appears.

Unless the patrol's arrival was independently due.

This principle is very important.

---

# 23. Avoid Arbitrary Escalation

One failed social attempt should not automatically become:

> permanent enemy.

One failed stealth attempt should not automatically become:

> entire village on alert.

Escalation should match:

- who observed,
- what they understood,
- what protocols exist.

Consequences should propagate through actual systems.

---

# 24. Escalation Can Be Progressive

Useful state progression might be:

For suspicion:
- unaware,
- uncertain,
- suspicious,
- alert,
- confirmed threat.

For security:
- normal,
- local concern,
- active search,
- lockdown.

A single failure may move one or several steps depending on severity.

This is better than binary “undetected/detected.”

---

# 25. Failure Can Create Delayed Consequences

Not every consequence happens immediately.

Example:

The character leaves evidence behind.

Nothing happens now.

Later:

- investigator finds it,
- suspicion rises,
- identity becomes known.

This is excellent for persistent simulation.

---

# 26. Delayed Consequences Should Persist Even Off-Screen

If the player leaves fingerprints, documents, witnesses, or damage:

> those remain.

NPCs may discover them later.

The world should not forget simply because the player left the scene.

---

# 27. Consequences Can Be Hidden From the Player

If the character does not know:

- they were recognized,
- evidence was left,
- someone became suspicious,

the player should not receive an omniscient warning.

The consequence still exists.

This connects directly to hidden knowledge.

---

# 28. Recoverability Matters

Failure consequences can be categorized conceptually as:

### Easily Recoverable
Minor inconvenience.

### Recoverable
Requires meaningful effort.

### Difficult to Recover
Major setback.

### Irreversible
Cannot realistically be undone.

This can help the engine scale long-term consequence.

---

# 29. Irreversible Failure Should Be Used When the World Supports It

Examples:

- death,
- destroyed unique artifact,
- missed once-in-a-lifetime event,
- secret permanently exposed.

The simulation should not avoid irreversible outcomes merely because they are inconvenient.

But they must arise from real stakes and exposure.

---

# 30. Safeguards Should Improve Failure Outcomes

Preparation can alter what failure means.

Example:

Climbing with safety rope:

Failure:
> character falls several feet and is caught.

Without rope:

Failure:
> potentially lethal fall.

Same technical failure.

Different consequence because the player prepared.

This is exactly what safeguards are for.

---

# 31. Redundancy Should Prevent Cascades

Backup systems can stop one failure from becoming disaster.

Examples:

- backup medic,
- secondary escape route,
- redundant seal,
- reserve equipment.

This makes planning meaningful.

---

# 32. Failure Can Damage Future Probability

Example:

Failed lockpick damages the mechanism.

Future attempts become harder.

That is valid when mechanically plausible.

Similarly:

- argument damages trust,
- search disturbs evidence,
- pursuit tires character.

Failures can change later resolution conditions.

---

# 33. Failure Can Sometimes Improve Future Probability

Also possible.

Example:

Failed prototype reveals structural weakness.

Next version becomes easier.

This should only happen when feedback is informative.

Again:

> learning comes from actual information.

---

# 34. Failure Should Update Beliefs

Characters should learn from failure.

Example:

> You expected the guard to be slow, but he reacts immediately.

Knowledge state updates:

> threat estimate increases.

This matters even if no tangible progress occurred.

---

# 35. NPCs Learn From Failure Too

An NPC whose ambush fails may:

- revise their estimate,
- change tactics,
- retreat,
- call reinforcements.

NPC failure should create behavioral consequences just as player failure does.

---

# 36. Repeated Failure Should Not Reset the Scene

If the player fails to bluff a guard:

> the guard remembers that interaction.

Trying the exact same bluff again should not recreate the original state.

The simulation accumulates consequences.

---

# 37. Mission Failure Should Be Granular

A mission may have several possible outcomes:

- full success,
- partial mission success,
- failed objective but team survives,
- failed objective with casualties,
- strategic disaster.

We should avoid reducing every mission to:

> SUCCESS / FAILURE.

Later Mission rules can formalize this, but Resolution should support it.

---

# 38. Failure Can Redirect the Story Without Protecting the Objective

Example:

The player fails to rescue a captured shinobi before transport.

The rescue objective genuinely fails.

But the simulation continues:

> prisoner is moved elsewhere.

Now new options may emerge.

That's genuine failing forward.

The failure was not erased.

---

# 39. Capture Is a Valid Failure State

In many RPGs, capture gets avoided because it is inconvenient.

Here it should remain possible.

Capture can produce:

- imprisonment,
- interrogation,
- rescue attempt,
- political consequences,
- escape gameplay.

As long as capture is plausible, it can be a legitimate outcome.

---

# 40. Injury Is a Valid Failure State

Likewise:

- broken limb,
- chakra damage,
- unconsciousness,

can create substantial future consequences.

We should not reduce all failure to abstract HP loss.

The Health/Injury ruleset will define specifics later.

---

# 41. Death Is a Valid but Restricted Failure State

Death should only occur when:

- lethal hazard exists,
- exposure is sufficient,
- safeguards do not prevent it,
- resolution severity supports it.

Death should never be a generic punishment for “bad roll.”

But this is a generational simulation.

Characters genuinely can die.

---

# 42. Failure Should Respect Player-Declared Priorities

Suppose the player says:

> I don't care if I'm discovered; getting the child out is all that matters.

Then being detected is not necessarily failure.

If the child is rescued:

> primary objective succeeded.

Detection becomes a consequence.

This is why objective definition matters so much.

---

# 43. Sacrificial Success

A character may deliberately accept an extreme consequence to guarantee or improve another objective.

Example:

> hold bridge long enough for allies to escape.

The character may:

- succeed at holding bridge,
- be captured or killed.

That is not necessarily mission failure from their perspective.

Resolution must respect goal hierarchy.

---

# 44. Failure Should Not Be Retroactively Redefined

If the declared objective was:

> escape unnoticed,

and the character escapes but is seen:

> that objective failed.

The engine should not reinterpret it as full success simply because escape occurred.

However:

> a secondary objective succeeded.

This precision matters.

---

# 45. Failure Consequences Should Be Proportional to Decision Scale

A small action should not randomly cause world-scale consequences.

Example:

Failing to impress a shopkeeper should not trigger:

> international diplomatic incident.

Unless extraordinary established context connects them.

Local action generally creates local consequence.

---

# 46. Consequences Can Propagate Over Time

Small effects can eventually become large.

Example:

Minor evidence left behind →
investigator finds it →
identity suspected →
surveillance begins →
larger consequences later.

This is fine because each step has a causal link.

World-scale effects should emerge through chains, not leap directly from tiny failures.

---

# 47. Failure Should Sometimes Close Content

This is important for a life simulator.

If the player:

- misses an exam,
- ruins a relationship,
- loses a tournament,
- fails recruitment,

some opportunities may genuinely disappear.

The game should not guarantee access to all content.

That creates meaningful lives and replayability.

---

# 48. Closed Opportunities Can Create New Ones

Losing one path may make another relevant.

Example:

Fails chunin exam.

Possible future states:

- train and retry later,
- specialize in another role,
- gain reputation differently,
- develop rivalry.

This is not compensation.

It is the world continuing from the result.

---

# 49. Avoid “Failure Tax” Stacking

A single failure should not automatically inflict:

- injury,
- resource loss,
- reputation loss,
- time loss,
- relationship damage,
- alert escalation

all at once.

Only consequences with actual causal paths should apply.

This is especially important for avoiding overly punishing gameplay.

---

# 50. One Failure Can Have Multiple Consequences When Justified

But sometimes multiple consequences are appropriate.

Example:

A failed explosive-seal experiment might:

- destroy materials,
- injure the researcher,
- damage laboratory,
- alert nearby people.

That is plausible because one explosion affects several things.

The rule is not “one consequence only.”

The rule is:

> each consequence needs a causal pathway.

---

# 51. Consequence Priority

When several consequences are possible, the engine should prioritize:

1. direct physical/mechanical result,
2. immediate state changes,
3. obvious social/informational consequences,
4. delayed consequences.

This can help avoid overcomplicating the result.

---

# 52. Failure Narration Should Leave the Player Knowing the New State

When consequences are visible, the player should understand:

- what failed,
- what changed,
- what remains possible.

Example:

> The lockpick snaps inside the mechanism. The door is still closed, and you'll need either another tool or a different way in.

That gives a clear new state.

---

# 53. Hidden Consequences Should Reveal Themselves Later Through Evidence

If the player was secretly identified:

Later they may notice:

- increased surveillance,
- wanted notice,
- changed NPC behavior.

The revelation should come through the world.

This reinforces hidden state consistency.

---

# 54. No Retroactive Punishment

The engine should not later invent:

> "Actually, that failed attempt damaged your weapon"

unless that consequence was part of the resolved world state.

Consequences need to be established when generated, even if hidden from the player.

This protects consistency.

---

# 55. Recommended Failure Procedure

When an action fails:

### Step 1 — Confirm the Objective
What specifically did not succeed?

### Step 2 — Determine Outcome Degree
Narrow, standard, severe, catastrophic-range.

### Step 3 — Identify Actual Exposures
What risks existed?

### Step 4 — Check Safeguards
What limits or prevents consequences?

### Step 5 — Determine Direct Consequence
What logically happens because the objective failed?

### Step 6 — Determine Secondary Consequences
Only those with causal paths.

### Step 7 — Determine Whether Any Progress or Information Was Generated
Only if the task supports it.

### Step 8 — Update Persistent State
Position, resources, suspicion, injury, opportunity, etc.

### Step 9 — Determine What the Character Knows
Some consequences may remain hidden.

### Step 10 — Present the New Playable State
Without rewriting failure into success.

---

# Example — Stealth Failure

Objective:

> cross courtyard unseen.

Result:

> narrow failure.

World consequence:

A guard catches movement.

Not necessarily:

> full alarm.

New state:

> guard is suspicious and investigating.

The player may now:

- hide,
- bluff,
- retreat,
- incapacitate guard.

That is genuine failing forward.

---

# Example — Failed Persuasion

Objective:

> convince village official to release restrict

---

## Turn 04001818-2519-4b92-9816-05d6c44c6255

### User

Ok

### Assistant — 863819cb-ee1d-4308-8ca6-c513b49a63bc

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.27 — Resolution & Progression Interaction

This section should define **when resolving actions produces meaningful learning**, while leaving the actual progression rates, XP requirements, Skill tiers, Attribute growth, and Mastery advancement inside Ruleset 1.

The central rule should be:

> **Characters improve from meaningful practice, challenge, feedback, and adaptation—not simply because a check occurred.**

This distinction is essential because otherwise the optimal way to progress would be to manufacture endless rolls.

---

## 1. Ruleset 2 Should Generate Learning Events, Not Own Progression

Ruleset 1 determines:

- Skill XP requirements,
- Skill tiers,
- Attribute development,
- Individual Mastery,
- advancement gates,
- training rates,
- diminishing returns.

Ruleset 2 should determine:

> **What did this resolved action actually teach the character?**

The resolution system can then send a **learning event** to the progression system.

So conceptually:

**Action → Resolution → Learning Evaluation → Ruleset 1 Progression**

This keeps the rulesets cleanly separated.

---

# 2. Not Every Resolved Action Generates Progress

A check occurring does **not** automatically mean XP.

Examples:

- opening the same easy lock for the hundredth time,
- performing a completely mastered academy exercise,
- repeatedly attempting something fundamentally impossible,
- deliberately manufacturing meaningless failures.

These may consume time or resources while producing little or no improvement.

---

# 3. Learning Value Should Depend on the Experience

The engine should evaluate factors such as:

- challenge,
- novelty,
- repetition,
- feedback,
- pressure,
- complexity,
- successful execution,
- error recognition,
- deliberate practice.

These determine how educational the experience was.

---

# 4. Challenge Should Matter Relative to Current Capability

The same task can have very different training value for different characters.

A Difficulty 30 task might be:

- highly educational for Capability 25,
- useful practice for Capability 35,
- routine for Capability 60.

So progression value should use the **capability-to-challenge relationship**, even though task Difficulty itself remains objective.

This does not alter resolution probability.

It only alters how much can be learned from the attempt.

---

# 5. There Should Be a Learning Zone

A useful conceptual model is:

### Trivial
Far below current capability.

Very little progression.

### Comfortable
Below capability but still requires some execution.

Good for consistency and maintaining Skill.

### Challenging
Near current capability.

Strong learning value.

### Stretch
Somewhat beyond current reliable ability.

Potentially excellent learning if meaningful feedback exists.

### Overwhelming
Far beyond current capability.

Often poor learning value because the character cannot meaningfully engage with the task.

This avoids both trivial grinding and impossible-task grinding.

---

# 6. The Best Learning Usually Occurs Near the Edge of Competence

A character improves most when the task is difficult enough to expose weaknesses but still understandable enough to learn from.

This means:

> **Challenge should generally reward growth more than repetition of easy success.**

But we should not make the exact highest-risk action always optimal.

Safety, fatigue, time, and injury still matter.

---

# 7. Impossible Attempts Usually Teach Very Little

Suppose an academy student attempts an advanced S-rank sealing technique with no foundational knowledge.

Failure does not mean:

> massive Fuinjutsu XP because the task was extremely difficult.

They may not understand:

- what failed,
- why it failed,
- what correct execution would look like.

So the learning value may be almost zero.

This is important.

Difficulty alone does not create learning.

---

# 8. Comprehensibility Matters

For an experience to teach effectively, the character needs some ability to understand the gap between:

> what they did

and

> what better performance would require.

This may come from:

- existing Skill,
- instructor feedback,
- observation,
- instrumentation,
- clear physical feedback.

Without that, failure may only communicate:

> "I can't do this."

---

# 9. Failure Can Produce Excellent Learning

Success should not monopolize progression.

Failure can be highly educational when it reveals:

- timing errors,
- control problems,
- faulty assumptions,
- weaknesses in technique.

Example:

A character repeatedly loses balance while learning tree walking.

If they can feel where chakra adhesion breaks:

> that failure provides useful feedback.

So:

> **failure can generate strong progression when it is informative.**

---

# 10. Failure Does Not Automatically Generate More XP Than Success

We should avoid creating:

> intentionally fail because failure gives more XP.

Instead, both success and failure can teach different things.

Success may reinforce:

- correct execution,
- efficiency,
- confidence,
- consistency.

Failure may reveal:

- errors,
- limits,
- missing understanding.

Learning value depends on the experience, not which side of the threshold it landed on.

---

# 11. Narrow Outcomes Are Often Especially Educational

A narrow success or failure occurs close to the character's current performance boundary.

That often means:

- challenge was appropriate,
- errors are identifiable,
- improvement is reachable.

So narrow outcomes can frequently generate strong learning.

But this should be an emergent tendency, not a universal XP multiplier.

---

# 12. Strong Success Can Still Teach

A strong result may teach through:

- refined timing,
- discovering a more efficient method,
- reinforcing advanced execution.

Particularly when the task itself was challenging.

The engine should not assume:

> strong success = too easy.

A strong outcome may simply mean the character performed exceptionally well on a difficult task.

---

# 13. Exceptional Success Can Produce Insight

Sometimes exceptional performance may reveal something new.

Examples:

- more efficient chakra flow,
- unusual technique interaction,
- improved movement sequence.

This might generate:

- Mastery progress,
- technical insight,
- breakthrough progress.

But only where the result plausibly provides such insight.

No automatic "crit XP bonus."

---

# 14. Catastrophic Failure Should Not Be an XP Jackpot

A disastrous result can sometimes be educational.

But severe injury or equipment destruction should not produce enormous XP simply because the Outcome Margin was extreme.

The character may learn:

> never do that again.

That can be useful.

But progression should remain tied to what was actually understood.

---

# 15. Feedback Quality Should Be a Major Learning Factor

Compare:

### Practice Alone
Character knows something felt wrong.

### Instructor Present
Instructor identifies exact problem.

### Advanced Instrumentation
Character sees chakra flow instability precisely.

The same task may produce much better progression with higher-quality feedback.

This makes:

- teachers,
- mentors,
- training facilities

mechanically important.

---

# 16. Mentors Improve Learning Without Granting Free Capability

An instructor may:

- identify mistakes,
- demonstrate technique,
- choose appropriate drills,
- prevent bad habits.

They should increase **learning efficiency**, not simply provide Skill levels.

The student still needs to perform the work.

---

# 17. Demonstration and Guided Practice Are Different

As established in Teamwork:

### Demonstration
Learner observes expert performance.

Useful for understanding and knowledge.

### Guided Practice
Learner performs while receiving correction.

Usually much stronger for actual Skill development.

### Intervention
Instructor takes over.

May protect the student but reduce the student's learning because they performed less of the task.

This should carry directly into progression.

---

# 18. Actual Contribution Matters

A character should not gain full progression because they were merely present.

Example:

A genin watches their jonin instructor defeat an enemy.

They may gain:

- tactical knowledge,
- observation-based understanding.

But not:

> equivalent Taijutsu advancement to having fought the opponent themselves.

Progression should reflect what the character actually did.

---

# 19. Observation Can Still Produce Knowledge Progress

Watching someone perform a technique can improve:

- recognition,
- theoretical understanding,
- tactical awareness.

Depending on the character's abilities, it may also support later technique learning.

But:

> observation ≠ execution mastery.

This preserves declarative versus procedural knowledge.

---

# 20. Individual Mastery Should Grow From Specific Use

If a character repeatedly uses:

> Great Fireball Technique,

that should primarily increase:

> **Great Fireball Mastery**

rather than every Fire Release technique equally.

There may also be smaller transferable learning to:

- Fire Release Skill,
- chakra control,
- relevant hand-sign skill.

This is an ideal place for progression layers.

---

# 21. Skill Progress and Mastery Progress Should Have Different Sources

### Skill Progress
Comes from broader practice across the domain.

Example:
> Fire Release training across multiple techniques.

### Individual Mastery
Comes primarily from focused use of a specific technique/application.

This prevents someone from mastering every jutsu simply by raising one broad Skill.

---

# 22. Transferable Learning Should Exist

Some training lessons generalize.

Example:

Mastering chakra shape control in one technique may slightly benefit related techniques.

But transfer should depend on:

- mechanical similarity,
- shared principles,
- relevant Skill.

We should avoid universal transfer.

---

# 23. Similar Skills May Share Partial Learning

Examples:

- weapon handling with similar blades,
- related sensory techniques,
- basic medical procedures.

Learning may transfer modestly when the underlying application overlaps.

This belongs mostly in Ruleset 1, but Resolution needs to tag **what was actually practiced** so transfer can be calculated correctly.

---

# 24. Attributes Should Grow From Sustained Relevant Demand

Attributes should not increase because one check used them.

Example:

Jumping once should not grant Strength XP.

Attribute development should come from:

- repeated physical loading,
- sustained cognitive effort,
- chakra conditioning,
- endurance training.

So resolution events may contribute **training stimulus**, but Ruleset 1 should aggregate that over time.

This prevents constant micro-increases.

---

# 25. Attribute Growth Should Reflect Type of Stress

Examples:

### Strength
Progressive muscular force demands.

### Endurance
Sustained physical strain and recovery.

### Agility
Coordination, balance, reactive movement.

### Perception
Repeated meaningful sensory discrimination.

### Intelligence
Complex learning/problem-solving.

### Willpower
Sustained self-regulation under adversity.

### Chakra
Appropriate chakra development and conditioning.

The specific growth mechanics remain in Ruleset 1.

---

# 26. Attributes Should Not Grow Efficiently From Unrelated Skill Use

If Intelligence contributes 30% to a sealing check, that does not mean every seal attempt should meaningfully increase Intelligence.

Attributes are broader developmental characteristics.

They need appropriate long-term stimulus.

This prevents double-dipping.

---

# 27. Pressure Can Increase Learning Value

Executing a skill under genuine pressure may teach:

- reliability,
- speed,
- emotional control,
- adaptive application.

This can be more valuable than calm repetition.

But only if the character can still function well enough to learn.

---

# 28. Extreme Stress Can Reduce Learning

If someone is:

- panicking,
- severely injured,
- overwhelmed,

they may survive an experience without being able to process it effectively.

So:

> more pressure ≠ more XP.

Again, there should be an effective learning zone.

---

# 29. Pressure Training Should Build Pressure Reliability

A character who practices a technique only in calm conditions may become excellent at the technical execution while remaining less reliable under combat conditions.

Training under:

- time pressure,
- distraction,
- movement,
- opposition

can improve **performance robustness**.

This gives us a natural mechanism for combat experience without needing a universal "Combat XP" stat.

---

# 30. Real-World Application Can Teach Different Lessons Than Drills

Structured practice is excellent for:

- correcting technique,
- isolating weaknesses.

Real missions are excellent for:

- adaptability,
- judgment,
- pressure reliability,
- environmental application.

Therefore:

> training and field use should complement each other.

Neither should make the other unnecessary.

---

# 31. Controlled Training Should Often Be More Efficient Per Unit Risk

A safe training environment can allow:

- more repetitions,
- targeted feedback,
- controlled challenge.

Field experience carries:

- higher stakes,
- greater variability,
- less controlled learning.

So we should avoid the RPG trope that combat automatically gives vastly better progression than training.

---

# 32. Field Experience Can Unlock Practical Mastery

Some aspects cannot be fully trained safely.

Examples:

- reading hostile intent,
- adapting techniques under pressure,
- managing real injury,
- coordinating against unpredictable enemies.

So certain advanced Mastery milestones may reasonably require:

> real or realistically simulated application.

This could become a powerful progression gate.

---

# 33. Deliberate Practice Should Outperform Mindless Repetition

Two characters spend two hours throwing kunai.

Character A:

> throws repeatedly without analysis.

Character B:

> identifies grouping errors, adjusts grip, tests distances, records results.

Character B should learn more.

This makes training quality matter.

---

# 34. Repetition Has Diminishing Learning Returns

Repeated identical execution should gradually provide less learning.

First attempts:
> lots of adaptation.

Hundredth identical attempt:
> mostly consolidation.

This prevents grinding the exact same task indefinitely.

---

# 35. Variation Can Restore Learning Value

To continue improving, characters may introduce:

- greater distance,
- moving targets,
- different terrain,
- time pressure,
- smaller targets,
- unfamiliar conditions.

This creates natural training progression.

The task must evolve with the character.

---

# 36. Mastery Eventually Converts Practice Into Maintenance

Once an action is deeply mastered, ordinary repetition may primarily:

- maintain performance,
- prevent skill decay,
- preserve familiarity.

Major further improvement requires:

- advanced drills,
- tougher applications,
- new techniques.

This supports long-term incremental progression without infinite easy XP.

---

# 37. Skill Tier Requirements Should Create Training Ceilings

From Ruleset 1, higher Skill tiers may require Attribute thresholds or prerequisite knowledge.

If a character reaches that ceiling:

> further repetition at the lower tier should not endlessly accumulate usable advancement past the gate.

It may still:

- improve Mastery,
- consolidate current Skill,
- prepare some progress,

depending on Ruleset 1.

But gates should matter.

---

# 38. Progression Should Never Bypass Attribute Requirements

Suppose:

> Advanced Chakra Control requires Chakra 45 and Intelligence 35.

A character below those requirements cannot brute-force Advanced Chakra Control simply by grinding Basic Chakra Control thousands of times.

The prerequisite exists for a reason.

---

# 39. Failed Prerequisite Attempts Should Have Limited Value

Trying to access a locked Skill tier may produce:

- recognition of limitations,
- small foundational progress.

But not:

> direct progression in the inaccessible advanced Skill.

Otherwise gates become cosmetic.

---

# 40. Novelty Should Matter

New experiences can produce strong learning because they force adaptation.

Examples:

- new opponent style,
- unfamiliar terrain,
- unusual technique interaction.

But novelty alone is not enough.

A completely incomprehensible event may provide little usable learning.

So we want:

> **novel + understandable**

rather than simply:

> unfamiliar.

---

# 41. Discovery Can Generate Progression

Learning a new fact can improve:

- knowledge Skills,
- tactical understanding,
- research progress.

This is especially important for:

- medicine,
- history,
- fuinjutsu,
- intelligence work.

Progression does not need to come only from physical execution.

---

# 42. Problem-Solving Should Reward the Capability Actually Used

Suppose a character defeats a strong opponent by:

- identifying structural weakness,
- setting a trap,
- avoiding direct combat.

They should gain progression related to:

- strategy,
- trap-making,
- observation,
- relevant techniques.

They should not receive enormous direct Taijutsu progression merely because the enemy was powerful.

This prevents "enemy level = XP" logic.

---

# 43. Challenge Belongs to the Action Performed, Not the Enemy's Overall Rank

This is crucial.

Fighting an S-rank shinobi does not automatically generate S-rank progression if the player's actual contribution was:

> carrying messages while others fought.

Likewise, performing a technically demanding medical stabilization on an ordinary civilian may provide significant Medical Skill development.

Learning tracks the task.

---

# 44. Resource Expenditure Is Not Progression by Itself

Spending:

- large chakra,
- many tools,
- lots of money

does not inherently create more learning.

Only the actual demand and feedback matter.

Otherwise players would waste resources deliberately to farm XP.

---

# 45. Efficient Execution Should Not Be Punished

A master using less chakra should not gain less progression merely because they were efficient.

Progression should evaluate:

> what performance demands they handled,

not how wasteful they were.

---

# 46. Time Spent Matters, But Quality Matters Too

Training for:

> eight hours

should generally provide more opportunity to improve than:

> ten minutes.

But not eight hours of equal XP accumulation.

Factors such as:

- fatigue,
- concentration,
- drill quality,
- diminishing returns

matter.

This should be handled as an extended training process rather than per-check XP.

---

# 47. Fatigue Can Reduce Learning Efficiency

Past some point:

- technique deteriorates,
- attention declines,
- feedback quality drops.

Continuing may still build Endurance in appropriate training, but may become poor Skill practice.

This creates meaningful decisions about training duration.

---

# 48. Poor Practice Can Reinforce Bad Habits

Repeated incorrect execution without correction should not necessarily create good progression.

It may:

- slow development,
- reinforce flawed technique.

We do not necessarily need a complex "bad habit XP" system.

But the engine should recognize:

> repetition is not automatically productive.

---

# 49. Correction Can Undo Bad Habits

Mentorship, careful retraining, or better information can correct ingrained errors.

That may temporarily slow performance while the character changes technique.

This could become especially useful for self-taught characters.

---

# 50. Progression Should Be Awarded From the Resolved Experience, Not Player Intent

The player cannot declare:

> "I'm treating this as training, so give me XP."

If the action was trivial, it remains trivial.

Likewise, an unexpected real-world challenge can produce learning even if the character was not intentionally training.

---

# 51. The Character May Not Immediately Realize They Improved

Progression does not always need instant player-f

---

## Turn 631b382f-28b7-43a6-8d57-0f239cef7f26

### User

Ok

### Assistant — 08571089-f89b-4d01-a3a1-4298c587a7e5

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.28 — Rank & Resolution

Rank should matter to the simulation, but it should **not** become a hidden universal power modifier.

The central rule should be:

> **Rank describes expected capability, responsibility, and institutional standing. Resolution uses the character’s actual abilities.**

A Genin does not fail because they are a Genin.

A Jonin does not succeed because they are a Jonin.

Rank influences what is *expected*, *trusted*, *assigned*, and *believed*—not the mathematical outcome directly.

---

## 1. Rank Is Not a Stat

Ranks such as:

- Academy Student
- Genin
- Chunin
- Jonin
- Special Jonin

should not provide bonuses like:

> Jonin: +20 to all checks.

That would undermine the entire Attribute/Skill system.

Instead, actual resolution should use:

- Attributes,
- Skills,
- Mastery,
- resources,
- conditions,
- circumstances.

Rank is metadata about the character’s recognized professional standing.

---

# 2. Rank Represents Institutional Judgment

A shinobi rank generally means the village believes the person is qualified for a certain level of responsibility.

That judgment may be based on:

- combat capability,
- leadership,
- mission performance,
- judgment,
- specialization,
- reliability,
- experience.

Therefore rank is broader than raw fighting power.

A Chunin may be promoted largely because of:

- tactical judgment,
- leadership,
- composure,

even if another Genin is stronger in direct combat.

That fits Naruto very well.

---

# 3. Rank Should Create Soft Capability Expectations

Each rank can have typical ranges for:

- Attributes,
- core Skills,
- experience,
- mission competence,
- leadership.

But these should be **soft expectations**, not hard caps.

For example:

A typical Genin may cluster within certain capability ranges.

A Genin with:

> 60 Strength

could exist.

But that should be unusual and probably explained by:

- exceptional talent,
- clan trait,
- specialization,
- unusual training.

This matches what we established in Ruleset 1.

---

# 4. Rank Should Not Cap Attributes Directly

We should avoid rules like:

> Genin cannot exceed 50 in any Attribute.

That creates artificial barriers.

A prodigy may greatly exceed normal rank expectations.

Likewise, someone may remain lower-ranked because of:

- poor judgment,
- disciplinary issues,
- limited leadership,
- lack of promotion opportunity.

Rank and capability should correlate, but not be identical.

---

# 5. Rank Should Not Determine Difficulty

A task should not become:

> Difficulty 40 for Genin, 20 for Jonin.

The task has one Difficulty.

The characters simply bring different capability to it.

This preserves objective world scaling.

---

# 6. Rank Can Affect Assignment Difficulty

Where rank **does** matter is institutional behavior.

Villages may assign:

- D-rank missions to Genin,
- C/B-rank work to more experienced shinobi,
- high-level operations to Chunin/Jonin.

This happens because institutions estimate capability and responsibility.

The mission itself does not change difficulty because of who receives it.

---

# 7. Mission Rank and Shinobi Rank Are Separate

This distinction should be explicit.

### Shinobi Rank
Professional standing of a character.

### Mission Rank
Institutional estimate of mission danger/complexity/value.

Neither is a direct resolution stat.

An apparently C-rank mission may contain an unexpectedly A-rank threat if intelligence is wrong.

That should be possible.

---

# 8. Mission Rank Is an Estimate

Mission rank should reflect what the assigning authority currently knows.

If intelligence is incomplete:

> mission classification may be wrong.

This creates realistic situations like:

- unexpectedly dangerous targets,
- hidden enemy involvement,
- outdated reports.

The engine should not secretly rebalance the mission after assignment.

---

# 9. Rank Can Affect Access

Higher ranks may gain access to:

- restricted records,
- advanced training,
- classified missions,
- better equipment,
- sensitive meetings.

This is a real mechanical effect of rank.

But it changes:

> available opportunities and information,

not raw capability.

---

# 10. Rank Can Affect Authority

A Chunin or Jonin may have legitimate authority over:

- lower-ranked squad members,
- mission decisions,
- official reports,
- resource requests.

This affects social resolution because institutional position is relevant.

For example:

A Chunin ordering a Genin during an official mission has authority the same words would not carry from another Genin.

That is a circumstantial social factor, not a universal Charisma bonus.

---

# 11. Rank Can Affect Credibility

People may trust higher-ranked shinobi more in professional contexts.

Example:

A Jonin warning:

> “Evacuate this area.”

may be taken more seriously than an Academy Student saying the same thing.

But credibility depends on context.

A Jonin is not automatically more believable about:

- medicine,
- finance,
- obscure clan history.

Rank only matters where it signals relevant authority or competence.

---

# 12. Rank Can Affect Intimidation Perception

A known Jonin may be perceived as more dangerous than an unknown Genin.

That can affect:

- fear,
- surrender decisions,
- risk estimation.

But again:

> perceived threat ≠ actual capability.

A famous Genin prodigy may inspire more fear than an unimpressive Jonin.

---

# 13. Rank and Reputation Are Separate

This distinction is important.

### Rank
Official institutional classification.

### Reputation
What others believe about the character based on stories, records, and personal experience.

They often correlate.

They do not have to.

A low-ranked prodigy may have huge reputation.

A newly promoted Jonin may be relatively unknown.

---

# 14. Rank and Specialization Are Separate

A Special Jonin is a perfect example.

They may possess:

> Jonin-level expertise in a narrow domain

without equivalent broad capability.

So resolution should use their actual Skills.

Rank tells us something about why the institution values them.

It should not flatten them into a generic power tier.

---

# 15. Broad Competence Matters More at Higher Ranks

Higher professional rank should generally imply not only stronger peak Skills but broader reliability.

A Jonin might typically be expected to handle:

- combat,
- survival,
- mission judgment,
- teamwork,
- leadership,
- information security.

This is a good distinction from a lower-ranked prodigy with one extreme specialization.

---

# 16. Promotion Should Depend on More Than Stats

Promotion should consider things like:

- mission history,
- leadership,
- judgment,
- reliability,
- combat capability,
- village needs,
- exam performance,
- political/institutional factors.

That keeps rank from becoming:

> reach Skill 50 → automatic Chunin.

This belongs primarily to a Career/Rank progression ruleset later, but Resolution must not assume rank perfectly mirrors stats.

---

# 17. Promotions Can Lag Behind Capability

A character may clearly outperform their current rank because:

- they have not taken the exam,
- promotion cycle has not occurred,
- village politics,
- recent rapid growth,
- disciplinary concerns.

This should be normal.

---

# 18. Rank Can Exceed Current Capability

The reverse can happen too.

A character may be weaker than typical for their rank because of:

- aging,
- injury,
- inactivity,
- illness,
- specialization,
- historical promotion.

They remain their rank until institutionally changed.

Resolution still uses current actual capability.

---

# 19. Retirement Does Not Erase Rank Knowledge

A retired Jonin may no longer have peak physical stats.

But they may retain:

- tactical expertise,
- knowledge,
- social authority,
- reputation.

This is another reason rank cannot equal combat power.

---

# 20. Rank Should Influence NPC Expectations

NPCs should use rank as one piece of evidence when estimating another character.

If someone is identified as Jonin:

> observers may assume substantial competence.

But they should update from actual evidence.

Example:

A Jonin displays poor combat ability due to injury.

Observers may revise their threat estimate downward.

---

# 21. Unknown Rank Should Stay Unknown

If a character does not know someone's rank, the engine should not reveal it through resolution.

They may infer:

- "experienced shinobi,"
- "probably above Genin level."

But exact rank requires actual information.

---

# 22. Rank Can Be Concealed or Faked

Characters may:

- hide insignia,
- use disguise,
- forge credentials,
- impersonate rank.

This affects perceived authority and threat.

The actual resolution remains based on actual capability.

This creates interesting deception opportunities.

---

# 23. Rank Should Affect Available Responsibility

Higher rank may allow:

- squad command,
- mission leadership,
- classified operations,
- mentoring.

That changes the kinds of actions and decisions a character gets to make.

This is a much more meaningful rank benefit than flat statistical bonuses.

---

# 24. Rank Can Affect Consequences of Failure

Institutional expectations matter.

Example:

A Genin makes a poor tactical call:
> reprimand or retraining.

A Jonin makes the same error while commanding a squad:
> potentially severe professional consequences.

The action's technical Difficulty may be identical.

The stakes differ because of responsibility.

---

# 25. Rank Can Affect Legal or Disciplinary Authority

Depending on village structure, higher-ranked shinobi may:

- authorize actions,
- requisition resources,
- command subordinates,
- access secure areas.

This changes what actions are legally or institutionally viable.

Again:

> structural effect, not numerical buff.

---

# 26. Rank Can Affect Resource Availability

Higher-ranked operatives may receive:

- better mission equipment,
- larger budgets,
- more support,
- specialist access.

This indirectly improves outcomes through real resources.

The rank itself does not enter the resolution formula.

---

# 27. Rank Can Affect Team Roles

A higher-ranked shinobi may normally act as:

- leader,
- coordinator,
- specialist supervisor.

But a lower-ranked specialist may still be the best person for a particular technical task.

Example:

A Genin medical prodigy may perform the treatment while the Chunin manages security.

Team resolution should assign roles based on actual competence.

---

# 28. Rank Does Not Override Specialist Expertise

This should be strict.

A Jonin with minimal medical training is not automatically better at medicine than a highly trained Chunin medic.

Rank determines institutional standing.

Skill determines task competence.

---

# 29. Rank and Combat Threat Should Not Be Synonymous

We should avoid shortcuts like:

> Genin = low threat  
> Chunin = medium threat  
> Jonin = high threat.

Those are broad expectations, not deterministic truth.

Combat threat depends on:

- matchup,
- specialization,
- resources,
- injuries,
- environment.

A particular Genin can be extremely dangerous under the right conditions.

---

# 30. Rank Can Still Be Used for Broad Simulation Heuristics

For off-screen simulation, rank can serve as a useful shorthand when detailed stats are unavailable.

For example:

A generic unnamed Jonin patrol can initially be generated from a typical Jonin capability profile.

But once the NPC has actual stats:

> use the stats.

So rank is useful for **generation and abstraction**, not final resolution.

---

# 31. Rank-Based NPC Generation Should Use Distributions

Instead of:

> every Chunin has Skill 50.

Use distributions.

For example, a Chunin population may contain:

- weaker but experienced leaders,
- average all-rounders,
- strong specialists,
- exceptional outliers.

This creates variation.

Exact distributions belong in Ruleset 1/world-generation rules.

---

# 32. Rank Should Have Variance by Village and Era

Different villages may have different:

- promotion standards,
- training quality,
- manpower needs.

During wartime:

> promotions may happen faster.

During peacetime:

> standards may become stricter.

So rank should not imply identical absolute capability across all contexts.

---

# 33. Institutional Quality Matters

A Jonin from a highly selective village may, on average, differ from a Jonin from a weakened or understaffed organization.

But the system still resolves individuals from actual stats.

This is useful for world simulation without creating universal rank inflation.

---

# 34. Age and Rank Should Correlate Only Probabilistically

Most very young Jonin should be rare.

But prodigies can exist.

Likewise:

An older Genin could exist because of:

- late entry,
- failed promotions,
- unusual career path.

The engine should not force age-rank conformity.

---

# 35. Exceptional Rank Advancement Needs Explanation

If someone rises unusually fast, the world should have a reason:

- extraordinary performance,
- wartime need,
- unique talent,
- political favor,
- rare circumstance.

The engine should not casually fill the world with teenage Jonin because they are exciting.

---

# 36. Rank Should Create Expectations for Reliability

This may be one of the most important distinctions.

Higher rank should often mean:

> the village trusts this person to perform under uncertainty.

That may reflect:

- broad Skill,
- pressure reliability,
- judgment,
- teamwork.

This makes rank more than raw power while still keeping it meaningful.

---

# 37. Rank Can Inform Automatic-Success Expectations

Not directly mechanically, but statistically.

A typical Jonin should automatically handle many tasks that challenge a typical Genin because their actual Skills and Mastery are generally higher.

The engine should never say:

> automatic because Jonin.

Instead:

> automatic because actual capability exceeds uncertainty.

Rank merely predicts that this will often be the case.

---

# 38. Rank Can Inform Character Self-Assessment

A character may use rank as a heuristic.

Example:

> "He's a Jonin. I should assume he's dangerous until proven otherwise."

This is sensible.

But a character with enough experience may refine that estimate.

Rank is evidence, not certainty.

---

# 39. Rank-Based Overconfidence Is Possible

A high-ranked NPC might underestimate:

- low-ranked prodigy,
- civilian specialist,
- disguised enemy.

Likewise, a lower-ranked character may overestimate a mediocre higher-ranked opponent.

These misjudgments should emerge naturally from perception.

---

# 40. Rank Can Create Social Deference

In hierarchical villages, lower-ranked shinobi may:

- obey,
- defer,
- hesitate to challenge decisions.

This should depend on:

- culture,
- relationship,
- context,
- personality.

Rank can matter socially without becoming magical authority.

---

# 41. Rank Should Never Force Player Obedience

If the player character is ordered by a superior:

> the player should generally retain the choice to obey or refuse.

The consequences may include:

- discipline,
- reputation loss,
- legal consequences.

But the rank system should not simply take control away.

---

# 42. Rank and Mission Failure Should Interact Institutionally

Failure by a higher-ranked leader may carry greater accountability.

The village may ask:

- Was the decision reasonable?
- Was intelligence flawed?
- Were procedures followed?

This is richer than simply:

> failure = demotion.

Institutional response should depend on circumstances.

---

# 43. Rank Should Not Protect Against Consequences

A Jonin can:

- fail,
- be injured,
- be captured,
- die.

No rank-based plot armor.

Similarly, low-ranked characters do not receive hidden protection.

---

# 44. Legendary Status Is Separate From Rank

Characters such as famous war heroes may be far beyond ordinary Jonin despite sharing the same nominal rank.

So we may eventually track:

- rank,
- reputation,
- threat classification,

separately.

This prevents official titles from carrying too much mechanical meaning.

---

# 45. S-Class Is Especially Important to Separate

"S-rank" is often used loosely to mean:

- mission rank,
- criminal threat classification,
- extremely dangerous individual.

It should not simply be treated as another shinobi career rank unless the setting specifically does so.

We should distinguish these concepts carefully in the full system.

---

# 46. Threat Classification Can Exist Separately

For organizations, a character may have a threat assessment such as:

- low,
- moderate,
- severe,
- extreme.

Or Naruto-style classifications.

But these should be intelligence estimates based on:

- known capabilities,
- history,
- danger.

Again:

> not resolution stats.

---

# 47. Threat Estimates Can Be Wrong

A newly awakened ability may make someone far more dangerous than their file suggests.

Likewise, an old threat assessment may remain inflated after:

- injury,
- aging,
- lost abilities.

This creates interesting intelligence uncertainty.

---

# 48. Rank Should Not Be Used as a Shortcut When Detailed Stats Are Available

This should be a core implementation rule.

Bad:

> Jonin vs Genin → Jonin wins.

Correct:

> calculate the actual relevant capabilities and circumstances.

Rank can inform:

- expectations,
- decision-making,
- generated NPC baselines.

Never substitute it for actual resolution.

---

# 49. Rank Mismatch Can Be a Narrative Signal, Not a Mechanical Rule

If a Genin repeatedly performs at Jonin levels:

NPCs may notice.

That can lead to:

- promotion interest,
- suspicion,
- fame,
- special assignments.

The world should respond to the mismatch.

This makes exceptional capability socially meaningful.

---

# 50. Underperformance Can Also Be Noticed

A Jonin repeatedly struggling with routine duties may attract:

- concern,
- reassignment,
- retraining,
- investigation.

Again, actual performance can eventually influence institutional status.

---

# 51. Rank Can Lag Behind Performance Until the Institution Acts

The simulation should not automatically promote someone the instant they cross an invisible threshold.

Promotion is a world event requiring:

- recognition,
- process,
- authority.

That keeps rank institutional rather than purely mechanical.

---

# 52. Recommended Rank-Resolution Procedure

When rank seems relevant to an uncertain action:

### Step 1 — Ignore Rank for Direct Resolution
Use actual capability.

### Step 2 — Ask Whether Rank Changes Context
Does it affect:
- authority,
- access,
- credibility,
- resources,
- expectations?

### Step 3 — Apply Only Causal Effects
Example:
> Jonin credentials grant entry to a restricted area.

### Step 4 — Use Rank as Perception Evidence
Other characters may estimate capability from it.

### Step 5 — Resolve Using Actual Stats
Never rank alone.

### Step 6 — Let Performance Feed Back Into Reputation and Career
Exceptional or poor results may eventually affect institutional standing.

---

# Example — Genin Prodigy

A 13-year-old Genin has:

- very high Agility,
- excellent Taijutsu,
- poor leadership,
- limited mission experience.

Against an average Chunin in a pure speed contest:

> the Genin may genuinely have the advantage.

On a complex team mission:

> the Chunin may still be much more capable overall.

Rank remains sensible without overriding the stats.

---

# Example — Special Jonin Medic

A Special Jonin has elite medical expertise but average combat ability.

In surgery:

> extremely capable.

In direct taijutsu against a combat-focused Chunin:

> may be disadvantaged.

Their rank does not flatten these differences.

---

# Example — Retired Jonin

A 64-year-old former Jonin has:

- reduced Agility,
- reduced Endurance,
- excellent Intelligence,
- high tactical Skills,
- deep knowledge.

They may struggle physically against younger shinobi but remain:

- excellent strategist,
- teacher,
- analyst.

This is exactly why rank must remain separate from current stats.

---


---

## Turn 13332b67-e213-41a6-938f-67f7f055612e

### User

Ok

### Assistant — 80cb88ea-7b4d-452a-b4a6-9185adcc88c8

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.29 — Special Abilities & Rule Exceptions

Special abilities are where a Naruto simulation can become inconsistent very quickly if every unusual power is allowed to ignore the normal system whenever convenient.

The central rule should be:

> **Special abilities may change the rules of a resolution, but only through explicit, defined exceptions.**

A dojutsu, kekkei genkai, forbidden technique, summon, transformation, or sealing effect should never amount to:

> "This ability is special, so it wins."

Instead, it should specify exactly **what ordinary rule it changes**.

---

## 1. Special Abilities Should Modify the Resolution Structure, Not Replace It Entirely

Most unusual abilities should still interact with:

- capability,
- prerequisites,
- resources,
- opposition,
- circumstances,
- probability,
- consequences.

A special ability might:

- use a different Skill,
- remove a penalty,
- ignore a defense,
- reveal hidden information,
- change the outcome ceiling,
- make an action possible that normally is not.

But the rest of the resolution system should continue functioning.

---

# 2. Every Special Ability Needs a Mechanical Identity

Each unusual ability should eventually answer:

- What does it enable?
- What does it cost?
- What prerequisites exist?
- Which capability determines execution?
- What does it oppose?
- What can resist it?
- What does it ignore?
- What are its limits?
- What information does it provide?
- What happens on failure?

If these questions cannot be answered, the ability is probably too vague.

---

# 3. “Special” Should Not Mean “Universal Bonus”

Avoid:

> Sharingan: +20 to all combat checks.

Instead, define actual effects.

For example, depending on the version:

- improved visual tracking,
- enhanced movement prediction,
- greater ability to read hand seals,
- improved copying of observable technique components,
- access to specific genjutsu.

Each effect interacts with specific resolutions.

That is far more balanced.

---

# 4. Abilities Can Change Which Stat Matters

This is one of the healthiest forms of exception.

Example:

A normal tracking action might use:

- Tracking Skill,
- Perception,
- Intelligence.

A specialized sensory technique might instead rely on:

- Sensory Skill,
- Chakra Control,
- Perception.

The ability changes the method.

It does not simply add a huge bonus.

---

# 5. Abilities Can Replace One Contest With Another

Example:

A character normally attempts to detect an infiltrator visually.

With a chakra-sensing ability, the contest becomes:

> Chakra Concealment vs Chakra Sensing

rather than:

> Stealth vs visual Perception.

This is excellent because the ability creates a new axis of interaction.

---

# 6. Abilities Can Remove Certain Forms of Opposition

Some powers may genuinely make a normal defense irrelevant.

Example:

If a sensory technique detects chakra through darkness:

> darkness no longer provides visual concealment against that sensor.

That does not mean:

> stealth is useless.

A target may instead use:

- chakra suppression,
- barriers,
- distance,
- decoys.

The ability removes one defense, not every defense.

---

# 7. Abilities Can Create New Prerequisite Gates

Some techniques should be impossible without:

- bloodline,
- contract,
- specific organ,
- transformation,
- seal,
- chakra nature,
- specialized training.

This is not a penalty.

It is a prerequisite.

If the prerequisite is absent:

> action unavailable.

No probability roll is necessary.

---

# 8. Kekkei Genkai Should Mostly Unlock Capability

A bloodline ability should often give access to:

- unique methods,
- unique techniques,
- unusual sensing,
- altered physiology.

It should not necessarily make the user broadly superior.

For example:

A character may possess a rare bloodline but still be:

- inexperienced,
- untrained,
- inefficient.

Access and mastery remain separate.

---

# 9. Awakening Does Not Equal Mastery

This should be strict.

Unlocking a special ability should give:

> access.

Not:

> automatic expert use.

The character may still need to develop:

- activation reliability,
- duration,
- control,
- efficiency,
- advanced applications.

This preserves progression.

---

# 10. Abilities Need Their Own Mastery

Important abilities should interact strongly with Individual Mastery.

A newly awakened dojutsu may have:

- short duration,
- poor information filtering,
- high chakra cost.

A mastered one may have:

- better efficiency,
- faster activation,
- improved precision,
- more reliable interpretation.

This fits perfectly with Ruleset 1.

---

# 11. Transformations Should Modify State, Not Identity

A transformation may temporarily alter:

- Strength,
- Agility,
- Endurance,
- Chakra output,
- senses,
- available techniques.

But it should create a **temporary derived state**.

The character's underlying base Attributes do not necessarily permanently change.

Once transformation ends:

> normal state returns, plus any consequences.

---

# 12. Transformations Need Costs and Constraints

Possible costs:

- chakra drain,
- stamina drain,
- physical strain,
- mental strain,
- reduced control,
- limited duration.

A stronger transformation should not simply be:

> free +30 to everything.

It should create an altered capability profile with tradeoffs.

---

# 13. Transformations May Also Change Outcome Space

Some forms can make previously impossible actions viable.

Example:

Base form:
> cannot physically break barrier.

Transformed form:
> now possible.

That is legitimate because capability actually changed.

This is different from luck overriding impossibility.

---

# 14. Summons Should Be Independent Actors

A summon should generally have:

- its own stats,
- Skills,
- resources,
- personality,
- knowledge.

The summoner does not simply gain:

> +25 combat.

Instead, a new actor enters the situation.

That means normal teamwork rules apply.

---

# 15. Summoning Itself Is One Resolution

Calling the summon may involve:

- contract access,
- chakra cost,
- execution reliability.

Once summoned, the creature acts under its own capabilities.

This cleanly separates:

> summon activation

from

> summon performance.

---

# 16. Summons Should Not Be Perfectly Obedient by Default

Depending on contract and relationship, summons may have:

- preferences,
- loyalty,
- refusal conditions.

A powerful summon can be a resource without being a mindless extension of the player.

That fits the autonomous-world philosophy.

---

# 17. Shadow Clones Need Structural Rules

Clone techniques are especially dangerous for balance.

We should avoid simply treating clones as:

> full copies with no downside.

A clone system should specify:

- what stats copy,
- what resources split,
- what information shares,
- what damage dismisses clone,
- what tasks clones can perform,
- how many can be maintained.

These should be explicit technique rules.

---

# 18. Clones Should Not Multiply Capability Linearly

Three clones should not simply mean:

> 4 × combat effectiveness.

They share limitations such as:

- resource division,
- coordination,
- space,
- fragility,
- attention.

Their biggest advantage may be:

- multiple angles,
- parallel actions,
- deception.

That is structural superiority, not stat multiplication.

---

# 19. Dojutsu Should Specify Information Output

This is especially important.

An eye technique should not be summarized as:

> sees everything.

Instead specify:

- what it can detect,
- at what range,
- through what barriers,
- what precision,
- whether identity recognition is possible,
- whether information overload occurs.

This preserves the hidden-information system.

---

# 20. Detection Does Not Equal Interpretation

Even if a dojutsu reveals:

> chakra flow anomaly,

the user may still need relevant expertise to understand:

> what the anomaly means.

Seeing more information does not automatically grant knowledge.

This keeps Intelligence and Skills relevant.

---

# 21. Prediction Abilities Need Bounded Prediction

Movement-reading abilities should not become:

> guaranteed dodge.

They may improve prediction by:

- reducing opponent surprise,
- improving reaction timing,
- revealing movement initiation.

But if the opponent is:

- far faster,
- unpredictable,
- using area attacks,

the user may still be unable to respond physically.

This distinction is essential:

> **Seeing an attack coming is not the same as being able to avoid it.**

---

# 22. Copying Abilities Need Component Rules

A technique-copying ability may reveal or preserve:

- movement pattern,
- hand seals,
- chakra sequence.

But copying should still be limited by:

- chakra nature,
- physical requirements,
- bloodline restrictions,
- skill,
- resources.

Observation can accelerate learning.

It should not erase prerequisites.

---

# 23. Genjutsu Requires Its Own Interaction Structure

A genjutsu may attack:

- perception,
- cognition,
- chakra control.

Its resolution should define:

- activation method,
- detection conditions,
- resistance capability,
- escape conditions.

It should not be:

> caster rolls high → victim loses agency.

The exact Genjutsu system belongs later, but Ruleset 2 should require explicit opposition.

---

# 24. Mind-Affecting Abilities Should Be Treated Carefully

If an effect genuinely controls behavior, that is a structural exception.

The ability must define:

- what actions it can force,
- duration,
- resistance,
- break conditions,
- memory effects.

This prevents vague powers from becoming unlimited narrative control.

---

# 25. Immunities Should Be Narrow

Avoid:

> immune to genjutsu.

Prefer:

> immune to visual-trigger genjutsu below a certain class

or:

> unaffected by pain-based disruption because of physiology.

Narrow immunities are easier to simulate consistently.

---

# 26. Resistance and Immunity Are Different

### Resistance
Effect still works but less effectively or is easier to oppose.

### Immunity
Effect cannot apply under the stated conditions.

We should not blur these.

Immunity should be rare and explicit.

---

# 27. Special Abilities Can Change Failure Floor

Example:

A defensive technique may not improve success probability for avoiding attack.

Instead, it may reduce consequence from:

> severe injury

to:

> minor injury.

This is a great form of special ability because it interacts with our stakes system naturally.

---

# 28. Special Abilities Can Raise Outcome Ceiling

Example:

Normal taijutsu cannot damage a certain barrier.

A chakra-enhanced strike can.

The ability raises the maximum possible effect.

Again, this is better than arbitrary universal bonuses.

---

# 29. Special Abilities Can Change Resource Economy

Some traits may:

- reduce chakra cost,
- increase recovery,
- allow larger safe output,
- convert one resource into another.

These are meaningful advantages even without direct success bonuses.

---

# 30. Special Abilities Can Modify Timing

Examples:

- faster activation,
- reduced hand-seal requirement,
- instant substitution,
- pre-prepared seal.

This can create huge tactical value.

Time advantages should be treated structurally where appropriate.

---

# 31. Instant Abilities Still Need Limits

"Instant" should mean:

> minimal execution time.

Not:

> cannot be reacted to under any circumstance.

Opponents may still anticipate:

- trigger conditions,
- positioning,
- known patterns.

Instant activation and unavoidable effect are different concepts.

---

# 32. Space-Time Abilities Need Clear Constraints

Abilities involving teleportation or dimensional movement should define:

- range,
- target requirements,
- marks,
- line-of-sight,
- chakra cost,
- activation speed,
- carried mass,
- cooldown if any.

Without this, they can trivialize every obstacle.

---

# 33. Barrier and Seal Effects Need Explicit Boundaries

A seal may:

- block movement,
- suppress chakra,
- detect passage,
- store objects.

Each effect needs:

- trigger,
- coverage,
- strength,
- resistance,
- duration,
- bypass conditions.

Avoid:

> powerful seal stops anything.

---

# 34. Seals Can Change the Rules of a Space

This is a good structural exception.

Example:

Inside a suppression barrier:

> chakra output capped.

That creates a modified local ruleset.

All affected participants operate under it.

This is much cleaner than applying arbitrary debuffs.

---

# 35. Forbidden Techniques Should Be Powerful Because of Tradeoffs

"Forbidden" should not automatically mean:

> strongest jutsu.

A technique may be forbidden because it:

- harms the user,
- sacrifices others,
- violates law,
- creates uncontrollable risk,
- has severe long-term consequences.

This distinction matters for simulation.

---

# 36. Forbidden Techniques Need Real Consequences

If a technique is described as physically destructive to the user, the engine should enforce that.

No:

> dramatic warning, then no actual downside.

Costs must persist.

Otherwise forbidden techniques become obvious optimal choices.

---

# 37. Sacrifice Mechanics Should Be Explicit

Some abilities may trade:

- lifespan,
- health,
- permanent capability,
- relationships,
- lives.

These should not be generic "costs."

They are major persistent consequences.

The engine should communicate known costs before use when the character understands them.

---

# 38. Unique Abilities Should Not Require Universal Counterplay

Not every power needs a perfectly symmetrical counter.

Some powers can genuinely be extremely strong.

Balance should come from:

- rarity,
- costs,
- prerequisites,
- limitations,
- vulnerability elsewhere.

We should avoid artificial game-balance logic that gives every ability a convenient hard counter.

---

# 39. But No Ability Should Be Undefined

An ability may be extraordinary.

It still needs boundaries.

The difference is:

> strong is acceptable.

> undefined is not.

---

# 40. Counters Should Be Causal

A counter works because of a real interaction.

Examples:

- insulation blocks conduction,
- sensory interference disrupts detection,
- sealing technique restricts movement.

Not:

> Water beats Fire because elemental chart says so

unless the underlying system supports the interaction.

Counters should arise from mechanics.

---

# 41. Partial Counters Are Better Than Binary Counters

Many counters should:

- reduce effectiveness,
- alter Difficulty,
- limit range,
- increase resource cost.

Rather than:

> completely negate.

This produces richer matchups.

---

# 42. Specialization Should Create Asymmetry

Two equally capable shinobi may have wildly different matchup results.

Example:

One specializes in:

- stealth,
- assassination.

Another in:

- sensory detection,
- defense.

The second may be a bad matchup for the first despite similar overall competence.

This is desirable.

---

# 43. Rule Exceptions Must Be Specific

A good exception:

> This ability ignores visual concealment within 30 meters but not chakra concealment.

Bad exception:

> This ability bypasses stealth.

Specific exceptions are simulatable.

Broad exceptions create ambiguity.

---

# 44. Exception Priority Needs a Hierarchy

Eventually we may have abilities that conflict.

Example:

- ability says "cannot be detected visually,"
- another says "automatically detects hidden targets."

We need a rule for resolving exceptions.

The cleanest principle is:

> **More specific rules override more general rules.**

If both are equally specific, resolve based on:

- defined interaction,
- capability contest,
- or explicit priority in the abilities.

Avoid arbitrary GM judgment.

---

# 45. “Absolute” Abilities Should Be Extremely Rare

Words like:

- always,
- never,
- unavoidable,
- perfect,
- absolute

should be used carefully.

If an ability is truly absolute under specific conditions, those conditions must be narrow.

Example:

> completely blocks ordinary vision through the barrier.

That is manageable.

> cannot be perceived by anyone

is usually too broad.

---

# 46. Special Abilities Can Create Automatic Success

An ability may legitimately remove uncertainty.

Example:

A technique guarantees underwater breathing while active.

Then:

> normal drowning checks are suppressed.

This is a proper use of automatic success.

The ability changed the situation enough that uncertainty disappeared.

---

# 47. Special Abilities Can Create Automatic Failure for Others

Likewise, an ability may remove an opponent's option.

Example:

A binding seal completely immobilizes someone who fails activation resistance.

While bound:

> ordinary running becomes impossible.

No running check is needed.

This is structural resolution.

---

# 48. Automatic Effects Should Have Entry Conditions

The important balance point is usually:

> getting the effect established.

Once the binding succeeds, immobilization may be automatic.

So the main contest occurs at:

- activation,
- avoidance,
- resistance.

This is much cleaner than repeatedly rerolling every second.

---

# 49. Persistent Effects Should Remain Persistent

If a seal establishes:

> chakra suppression,

the engine should not reroll suppression every time the target uses chakra.

The state persists until:

- duration expires,
- seal breaks,
- target escapes.

This follows our established-facts principle.

---

# 50. Maintenance Effects Need Ongoing Conditions

Some abilities persist only while:

- chakra is supplied,
- concentration is maintained,
- line-of-sight continues.

If that requirement breaks:

> effect ends.

These conditions should be explicit.

---

# 51. Area Effects Need Defined Coverage

An area technique should specify:

- radius,
- shape,
- obstacles,
- falloff if relevant.

Otherwise the engine cannot resolve:

> who is affected?

This is especially important for large-scale abilities.

---

# 52. Mass Effects Should Not Automatically Ignore Individual Resistance

An area genjutsu may affect many people.

That does not necessarily mean everyone has identical susceptibility.

Some effects may resolve individually.

Others may impose one environmental state.

The ability description should determine which.

---

# 53. Scaling Should Be Explicit

If an ability can be used at multiple power levels, define what scales:

- radius,
- damage,
- duration,
- number of targets,
- range.

Avoid:

> spend more chakra to make everything better.

Scaling should have specific axes.

---

# 54. Multi-Axis Scaling Should Have Tradeoffs

A character may choose:

- larger area but lower intensity,
- narrower range but greater power,
- longer duration but higher cost.

This produces interesting decisions.

Not every technique needs all of these, but powerful flexible techniques should often trade one dimension for another.

---

# 55. Special Abilities Can Have Hidden Effects

Some powers may intentionally conceal aspects of themselves.

That is fine.

The engine should still know:

- actual effect,
- trigger,
- limits.

The player only learns what their character discovers.

This preserves both consistency and mystery.

---

# 56. Characters Can Misunderstand Their Own Abilities

Especially after awakening something new, a character may not know:

- full range,
- exact cost,
- hidden side effects.

Experimentation can reveal these gradually.

This creates organic discovery.

---

# 57. Ability Knowledge Can Be Incomplete Across the World

A clan may possess extensive knowledge about its own kekkei genkai.

An outsider may only know rumors.

That affects:

- counterplay,
- threat estimation,
- training.

Again, special abilities should plug into the knowledge system rather than bypass it.

---

# 58. Rare Abilities Should Not Automatically Attract Plot Importance

A rare bloodline can exist in an otherwise ordinary person.

The world may care if:

- someone discovers it,
- institution values it.

But the engine should not automatically make that character central to world events.

This supports simulation-over-fanfi

---

## Turn b47a190f-54ad-4735-b52f-944046c632e1

### User

Ok

### Assistant — 919b9cda-1203-47cc-98c5-ee698509e897

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2.30 — Consistency & Simulation Safeguards

This final section should define the rules the **engine itself must obey** whenever it resolves uncertainty.

Most of Ruleset 2 determines how characters interact with uncertainty.

This section determines how the simulator avoids secretly cheating.

The central rule should be:

> **Once the world state, character state, objective, and relevant rules are established, resolution must follow them consistently regardless of which outcome would be more dramatic, convenient, or favorable to the player.**

That principle is what separates the simulator from improvised fanfiction.

---

## 1. No Protagonist Bias

The player character receives no hidden advantage simply because they are the player.

The engine must not:

- improve their odds because failure would be inconvenient,
- soften consequences because they are important,
- make enemies perform worse so the player survives,
- generate convenient opportunities after bad choices,
- protect them from death when lethal conditions genuinely exist.

Likewise, the player should not receive hidden penalties just to create drama.

> **Player and NPC actions use the same underlying resolution principles.**

---

# 2. No NPC Plot Armor

Important NPCs also receive no narrative protection.

A major:

- mentor,
- rival,
- clan leader,
- villain,
- future political figure

can fail, become injured, be captured, or die if the simulation produces that outcome.

The engine should never think:

> "This NPC is needed later."

There is no predetermined later scene that must be preserved.

---

# 3. No Predetermined Story Outcomes

Events should not secretly begin with conclusions such as:

> The player must eventually defeat this rival.

> This character has to survive until the war arc.

> The player will become Hokage.

Those may become possible outcomes.

They are never guaranteed outcomes.

The story is the record of what the simulation produces.

---

# 4. No Difficulty Fudging

Once appropriate Difficulty has been established from the task and circumstances, it should not be secretly changed because:

- the player is succeeding too easily,
- the player has failed repeatedly,
- the scene needs tension,
- the player chose an unexpected solution.

Difficulty changes only when the **world state changes**.

---

# 5. No Secret Level Scaling

The world should not automatically grow stronger to match the player.

If the character becomes extremely capable:

> routine threats should become routine.

Likewise, if the character enters somewhere beyond their capability:

> those threats should remain beyond their capability.

World difficulty comes from the world.

Not player level.

---

# 6. Difficulty Must Have a Causal Source

Every modifier to Difficulty or Effective Capability should correspond to something real.

Examples:

- darkness,
- injury,
- specialized equipment,
- preparation,
- unstable footing.

Avoid:

> "The situation feels tense, so +10 Difficulty."

If the engine cannot explain the modifier causally:

> it probably should not exist.

---

# 7. Do Not Double-Count Circumstances

The same underlying factor must not apply repeatedly through different labels.

Example:

A broken leg should not simultaneously cause:

- Injury −10,
- Mobility −10,
- Pain −10,
- Slowed −10

when all four describe the same limitation.

Separate effects are allowed only if they genuinely represent distinct consequences.

---

# 8. Structural Effects Take Priority Over Numerical Effects

Before adding modifiers, ask:

> Does this circumstance actually change what actions are possible?

Example:

Complete paralysis is not:

> −50 movement.

It means:

> ordinary voluntary movement unavailable.

A sealed door that cannot be physically opened does not need a giant Difficulty number.

It requires another method.

This prevents absurd numerical stacking.

---

# 9. Avoid False Precision

The engine should not invent highly specific numbers without meaningful reason.

If the correct answer is:

> Difficulty roughly in the low 60s,

we do not need to pretend the world objectively demands:

> 62.7.

Precision should exist only when it supports consistent mechanics.

---

# 10. Comparable Situations Should Resolve Comparably

If two characters face essentially the same situation under essentially the same conditions:

> the engine should evaluate it using the same standards.

The world should not alter its interpretation depending on who is involved.

This is one of the most important consistency tests.

---

# 11. Established Facts Cannot Change Retroactively

Once the simulation establishes that:

> a door is locked,

it remains locked until something changes it.

The engine cannot later decide:

> actually it was unlocked

because that would make a later scene easier.

Likewise for:

- locations,
- injuries,
- relationships,
- equipment,
- secrets,
- deaths.

Persistent facts persist.

---

# 12. Hidden Facts Must Exist Before They Matter

This should be especially strict.

The engine cannot decide after a failure:

> There happened to be a trap there.

unless the trap already existed in hidden world state.

Hidden information is legitimate.

Retroactive hidden information is not.

---

# 13. Unknown Is Not the Same as Undefined

This distinction is foundational.

### Unknown to Character
The engine knows the truth; character does not.

### Undefined in World
The fact has not yet been generated.

If an undefined fact becomes relevant, the engine should:

1. generate it using world logic,
2. persist it,
3. then resolve interaction with it.

Never reverse that order.

---

# 14. Undefined Facts Should Be Generated From Context

Suppose the player asks:

> "Is there a window in the back of the building?"

If that detail was never established, the engine should determine it from:

- architecture,
- building purpose,
- setting,
- prior descriptions.

Not from:

> whether a window would help the player.

This is crucial.

---

# 15. Generated Facts Must Then Persist

Once the engine decides:

> there are two rear windows,

that becomes permanent world state unless physically changed.

The player cannot ask again later and get a different building layout.

---

# 16. No Retroactive Counter Generation

This is particularly important in combat.

If the player creates an ingenious tactic, the enemy should not suddenly possess:

> the perfect counter

unless that counter was:

- already part of their capabilities,
- reasonably prepared,
- learned during play.

NPCs must fight with what they actually have.

---

# 17. NPCs Cannot Read the Player's Intent

The engine knows the player's declared plan.

NPCs do not automatically know it.

They can respond only to:

- observation,
- intelligence,
- experience,
- inference.

This safeguard prevents one of the most common forms of unfair simulation.

---

# 18. The Player Cannot Read NPC Intent Either

The same rule applies in reverse.

The player should receive:

- visible behavior,
- known motives,
- inferred intentions.

Not hidden plans unless discovered.

Information asymmetry must work both ways.

---

# 19. No Rerolls for Narrative Convenience

Once legitimate uncertainty has been resolved:

> accept the result.

Do not reroll because:

- success seems boring,
- failure seems harsh,
- an NPC died,
- the player got lucky,
- the story would be better another way.

The outcome becomes history.

---

# 20. No Silent Best-of-Multiple Rolls

Unless an explicit mechanic provides multiple resolution attempts, the engine must not secretly resolve several times and select the result it prefers.

One uncertainty:

> one proper resolution.

This applies to favorable and unfavorable outcomes equally.

---

# 21. No Pity System

Past failure does not secretly increase future success.

Past success does not secretly increase future failure.

If repeated outcomes change probabilities, there must be a real causal reason.

Examples:

- practice improved Skill,
- fatigue worsened performance,
- opponent adapted.

Not:

> "You've failed enough already."

---

# 22. No Anti-Streak System

If a character succeeds ten times in a row:

> that can happen.

If an NPC suffers several unlucky outcomes:

> that can happen.

The engine should not force statistical neatness over short periods.

Random variation should be allowed to look random.

---

# 23. No Outcome-First Reasoning

The engine should never decide:

> "The player should fail here."

and then construct mechanical justification afterward.

Correct sequence:

> state → capability → difficulty → context → probability → resolution → outcome.

Not:

> desired outcome → invented explanation.

---

# 24. No Modifier-First Reasoning Either

Likewise, do not start from:

> "This feels like a −15."

Start with:

> What circumstance exists, and what does it actually change?

Then determine whether that effect is:

- numerical,
- structural,
- persistent state.

---

# 25. Objective Must Be Defined Before Resolution

Before uncertainty is resolved, the engine should know:

> what counts as success?

Example:

"I attack him" may be too vague if consequences differ substantially between:

- injure,
- kill,
- disarm,
- interrupt.

The player's words and context should usually make this inferable.

If so, infer reasonably.

Do not change success criteria after seeing the result.

---

# 26. Player Priorities Must Be Honored

If the player says:

> "I care more about keeping the scroll intact than escaping quickly,"

the engine should reflect that objective hierarchy.

It must not later evaluate the action as though:

> escape speed was primary.

Declared priorities matter.

---

# 27. NPC Objectives Must Also Be Preserved

If an NPC's objective is:

> capture alive,

their successful action should not automatically become:

> lethal attack

unless the situation causes unintended escalation.

NPC behavior should follow established goals.

---

# 28. Capability Must Be Objective-Specific

Do not use vague universal values like:

> Character A is stronger, therefore Character A wins.

Instead ask:

> stronger at what?

Relevant capability may differ between:

- pursuit,
- deception,
- genjutsu resistance,
- medicine,
- tracking.

This safeguards against rank/power-level shortcuts.

---

# 29. Use the Minimum Necessary Resolution

The engine should not create extra checks merely because mechanics exist.

If one resolution already answers the meaningful uncertainty:

> stop.

Avoid:

- Stealth check,
- then Foot Placement check,
- then Breathing check,
- then Door Crossing check

for one simple infiltration moment.

Over-resolution creates excessive variance and inconsistency.

---

# 30. Do Not Suppress Necessary Resolution Either

The opposite mistake is also possible.

If the situation contains meaningful uncertainty with real consequences:

> resolve it.

Do not handwave an uncertain result simply because:

- the player has been successful lately,
- detailed resolution is inconvenient.

Appropriate abstraction is not automatic success.

---

# 31. Resolution Granularity Should Match Decision Granularity

A single decision can cover several mundane sub-actions.

But when:

- state changes,
- new information appears,
- player has a meaningful new choice,

the previous resolution should end.

This creates natural resolution boundaries.

---

# 32. Do Not Resolve Player Choices Before They Make Them

Suppose a stealth failure causes a guard to investigate.

Do not immediately resolve:

> the player attacks and escapes

unless those actions logically happen automatically.

Instead, when possible, give the player the new state and allow another decision.

This preserves agency.

---

# 33. Do Not Give NPCs Extra Actions Through Narration

NPCs should also be constrained by:

- time,
- positioning,
- attention,
- resources.

Narration must not allow an NPC to:

- attack,
- move,
- prepare a technique,
- analyze,
- rescue ally

all simultaneously unless their abilities actually support that.

---

# 34. Narrative Detail Cannot Create Mechanical Advantage Retroactively

Suppose narration casually mentions:

> "a loose pipe runs overhead."

That pipe is now part of the environment.

The engine should not introduce details carelessly and later deny their existence when the player uses them creatively.

Concrete narrated facts become world facts.

This makes descriptive discipline important.

---

# 35. But Descriptions Need Not Be Exhaustive

Not mentioning every object does not mean it cannot exist.

Undefined details can still be generated later using world logic.

The safeguard is:

> generation must be neutral to desired outcome.

---

# 36. Avoid Schrödinger's Equipment

Characters should not suddenly have exactly the tool needed because it seems reasonable they might.

Inventory should persist.

For mundane items that were abstracted rather than explicitly tracked, there should be clear inventory assumptions.

Example:

A shinobi kit may include standard supplies.

But rare specialized equipment must be established.

---

# 37. Avoid Schrödinger's Techniques

Likewise, an NPC should not suddenly know:

> the perfect obscure jutsu

unless their established:

- Skills,
- history,
- role

make possession plausible and the technique is generated consistently.

Important capabilities should ideally be established before they become strategically decisive.

---

# 38. Generic NPCs Can Be Completed When Needed

For newly generated minor NPCs, every Skill may not initially exist.

When one becomes relevant, the engine can generate missing capability from:

- rank,
- profession,
- age,
- background,
- established behavior.

Then persist it.

This is legitimate lazy generation.

What matters is neutrality and persistence.

---

# 39. Lazy Generation Must Not Target the Player

When completing an NPC's undefined capabilities, do not ask:

> "What stat would challenge the player?"

Ask:

> "Given who this NPC already is, what stat would make sense?"

This is an essential procedural safeguard.

---

# 40. NPC Capability Distribution Must Respect World Population

Not every randomly encountered shinobi should be extraordinary.

Most characters should cluster around appropriate norms.

Exceptional characters should remain exceptional.

Otherwise power inflation destroys the meaning of progression.

---

# 41. Exceptional Characters Need Causal Histories

When an extreme outlier exists, there should be an underlying explanation such as:

- unusual genetics,
- exceptional training,
- long experience,
- powerful transformation,
- rare opportunity.

The player may not know that explanation immediately.

But the world should have one.

---

# 42. Do Not Invent Weaknesses Just to Make Strong Enemies Beatable

A powerful opponent can genuinely lack an accessible weakness.

If the player needs to:

- escape,
- seek allies,
- prepare,
- wait,

that is acceptable.

Not every obstacle requires a convenient vulnerability.

---

# 43. Do Not Invent Immunities to Protect Strong Enemies

The reverse is equally important.

If the player discovers a legitimate method that should work:

> let it work according to the rules.

Do not decide:

> this boss is too important to be defeated this way.

There are no boss immunities without causal support.

---

# 44. Creative Solutions Use Normal Rules

When the player proposes an unexpected idea:

1. determine whether it is possible,
2. identify actual capability,
3. determine circumstances,
4. resolve normally.

Creativity does not deserve automatic success.

But it also should not be punished for bypassing a planned challenge.

If the method logically solves the problem:

> the problem is solved.

---

# 45. Preparation Must Be Honored

If a character spent:

- days scouting,
- resources building traps,
- time learning patrol routes,

those advantages should matter.

The engine should not increase enemy strength to "keep things challenging."

Preparation is supposed to make problems easier.

---

# 46. Consequences Must Be Honored Too

Likewise, if the character arrives:

- injured,
- exhausted,
- low on chakra,

the engine should not quietly ignore those states because a major battle is beginning.

Persistent disadvantages matter just as much as persistent advantages.

---

# 47. Resources Cannot Reset for Convenience

No automatic restoration because:

> the next scene is important.

If the player consumed:

- chakra,
- supplies,
- ammunition,

those remain consumed until legitimate recovery or replenishment occurs.

NPCs follow the same rule.

---

# 48. Time Must Advance Consistently

Actions consume real simulation time.

If the player spends three hours investigating:

> NPCs elsewhere also receive those three hours.

This is critical to the life-simulation layer.

The engine must not freeze the rest of the world while the player acts.

---

# 49. Off-Screen Events Must Respect Time Too

NPCs cannot:

- complete six months of training,
- travel across countries,
- form a relationship

during two days of player time.

Off-screen simulation must use the same calendar.

---

# 50. World State Should Update Even When Unobserved

NPCs can:

- succeed,
- fail,
- get promoted,
- become injured,
- form relationships,
- die

without the player being present.

However, the player should learn of those events only through legitimate information channels.

This preserves both autonomy and uncertainty.

---

# 51. Engine Knowledge and Character Knowledge Must Stay Separate

The engine may know:

> the ally is dead.

If the player character believes they are alive:

> narration and decision support should respect that belief until evidence arrives.

Never leak engine truth accidentally.

---

# 52. Player Knowledge and Character Knowledge Must Also Stay Separate

The player may infer something from genre familiarity or previous information that their current character does not know.

They can still choose actions based on suspicion.

But the character does not gain factual knowledge merely because the player guessed correctly.

Likewise, the engine should not punish the player for remembering something their character legitimately knows.

---

# 53. Character Knowledge Should Be Available When Needed

If the character knows something important that the player has forgotten:

> the engine should remind the player appropriately.

Example:

> You remember that your instructor warned you this type of seal reacts violently to foreign chakra.

The goal is to simulate the character's knowledge, not test the human player's memory.

---

# 54. No Meta-Gaming by NPCs

NPCs should not react to:

- hidden character sheet values,
- invisible quest status,
- player interface decisions,
- information they never received.

They only know the world as experienced through their perspective.

---

# 55. No Meta-Gaming Against NPCs

Likewise, the resolution engine should not make NPC secrets trivially discoverable because the player asks the correct meta-question.

The character needs:

- evidence,
- access,
- appropriate method.

Player cleverness can choose an effective investigation, but cannot bypass the character's information channels entirely.

---

# 56. No Narrative Karma

Good actions should not secretly produce better luck.

Bad actions should not secretly produce worse luck.

Moral behavior may have:

- social,
- psychological,
- institutional

consequences.

But the universe does not manipulate probability to reward or punish morality unless an actual supernatural system explicitly causes that.

---

# 57. No Narrative Balance

A successful week does not require:

> something bad to happen next.

A tragic period does not require:

> a convenient reward.

Life simulation should allow:

- long success streaks,
- prolonged hardship,
- mundane periods.

Balance comes from systems, not narrative compensation.

---

# 58. No Mandatory Drama

Not every year of a character's life needs:

- betrayal,
- d

---

## Turn fca25d9c-1a6d-4446-bca7-ebd2c1f3c5cd

### User

Ok

### Assistant — c6c25f4e-264a-4e5e-b05d-f708fbca2164

**Capture warning: this message is truncated at 20,000 characters. Its ending is missing.**

# Ruleset 2 Consolidation — Resolution, Probability & Difficulty

Now that all 30 sections exist, the goal is to turn them from a design discussion into a **usable canonical engine ruleset**.

The first consolidation pass should do three things:

1. remove repeated rules,
2. separate hard rules from provisional tuning,
3. define the shortest possible resolution architecture that still produces everything we designed.

I would **not** start stress-testing individual numbers until this pass is complete.

---

# 1. Final Scope of Ruleset 2

Ruleset 2 answers:

> **When a character attempts something uncertain, how does the simulation determine what happens?**

It owns:

- uncertainty detection,
- task Difficulty,
- opposed resolution,
- probability,
- outcome degree,
- situational effects,
- automatic outcomes,
- risk and stakes,
- retries,
- extended resolution,
- teamwork,
- information uncertainty,
- luck,
- critical events,
- resource/time effects on resolution,
- stress effects,
- perceived difficulty,
- NPC decision-making around uncertainty,
- player-facing presentation,
- failure consequences,
- progression-event generation,
- rank interaction,
- special-rule exceptions,
- consistency safeguards.

It **does not** define the full mechanics for:

- character advancement,
- combat,
- damage/injury,
- jutsu construction,
- chakra recovery,
- social relationships,
- career promotion,
- mission generation,
- equipment systems.

Those later systems use Ruleset 2.

---

# 2. The Canonical Resolution Pipeline

The 30 sections can ultimately be reduced to this:

> **Objective → Possibility → Capability → Opposition → Context → Probability → Outcome → Consequence → Knowledge → Progression → Persistence**

This should become the engine's canonical sequence.

---

# 3. Step 1 — Define the Objective

Before resolving anything, determine:

### Actor
Who is acting?

### Objective
What result are they trying to achieve?

### Method
How are they attempting it?

### Priorities
What matters most?

### Accepted Costs
What are they willing to sacrifice?

This matters because:

> "Attack him"

is not mechanically specific enough if the intended outcome could be:

- kill,
- injure,
- disarm,
- interrupt,
- distract.

The engine should infer obvious intent from context rather than constantly asking for clarification.

---

# 4. Step 2 — Determine Possibility

Every attempted objective first enters one of four states:

### Automatic Success
Failure is no longer meaningfully plausible.

### Automatic Failure
Success is outside the plausible outcome space.

### Uncertain Resolution
Capability and circumstances leave meaningful uncertainty.

### Contested Resolution
Another active force directly resists the objective.

This occurs **before** probability calculations.

---

# 5. Plausibility Overrides Probability

There is no universal:

> always at least 1% chance.

If success has no coherent causal path:

> probability is 0%.

Likewise, if no meaningful failure mechanism remains:

> success is automatic.

This prevents weak characters from defeating overwhelming opponents purely because the probability formula technically outputs a tiny number.

---

# 6. Difficulty Is Objective

Difficulty represents:

> **the effective performance required to achieve the specified objective under current conditions.**

It belongs to the task.

It does not scale to the actor.

The same lock has the same underlying Difficulty for:

- novice,
- expert,
- NPC,
- player.

Their capabilities differ.

---

# 7. Difficulty and Stakes Are Separate

This distinction is now fundamental.

### Difficulty
How hard is success?

### Stakes
What happens if the attempt succeeds or fails?

Examples:

Easy + deadly:
> crossing a wide beam over a fatal drop.

Hard + harmless:
> solving an extremely difficult puzzle in a safe room.

Never increase Difficulty because failure would be dramatic.

---

# 8. Capability Is Objective-Specific

The engine never uses vague overall power when a more relevant capability exists.

A character may simultaneously be:

- excellent tracker,
- average fighter,
- terrible liar.

Every resolution identifies the capability relevant to the objective.

---

# 9. Canonical Base Capability Formula

The provisional default remains:

> **Base Capability = 60% Skill + 30% Primary Attribute + 10% Secondary Attribute**

If no meaningful secondary Attribute exists:

> **Base Capability = 60% Skill + 40% Primary Attribute**

This remains **provisional**, not yet locked.

The architecture is locked.

The exact weights are not.

---

# 10. Why Skills Receive the Highest Weight

Attributes represent:

> foundational capacity.

Skills represent:

> learned application of that capacity.

Therefore, for most trained activities:

> Skill should matter more than raw Attribute.

This is important enough to retain regardless of whether testing eventually changes 60/30/10 to another weighting.

---

# 11. Mastery Is Applied After Base Capability

Individual Mastery represents familiarity with:

- a specific technique,
- specific tool,
- specific application.

It may improve:

- reliability,
- speed,
- efficiency,
- performance under pressure.

It should **not** act as another full 0–100 stat.

Exact Mastery modifier magnitude remains provisional.

---

# 12. Base Capability vs Effective Capability

### Base Capability
Normal technical capability.

### Effective Capability
What the character can bring to this specific attempt right now.

Conceptually:

> **Effective Capability = Base Capability + relevant mastery + relevant situational effects**

But structural effects should be applied separately rather than forced into arithmetic.

---

# 13. Situational Effects Have Three Forms

This should be locked.

### Numerical
Performance becomes somewhat better or worse.

### Structural
The situation changes what is possible or which defenses apply.

### Persistent State
A condition exists across multiple future resolutions.

Examples:

Injury:
> persistent state.

Slippery footing:
> numerical or structural depending severity.

Complete paralysis:
> structural.

---

# 14. Numerical Modifier Scale

The provisional scale remains:

- ±2 — Minor
- ±5 — Noticeable
- ±10 — Significant
- ±15 — Major
- ±20 — Extreme

Effects substantially beyond ±20 should usually make us ask:

> Should this be structural instead?

The scale needs stress testing before numerical lock.

---

# 15. Do Not Stack Descriptions of the Same Cause

If a broken leg causes reduced movement, do not separately apply:

- injury,
- pain,
- slowed,
- impaired balance

as four full penalties unless they represent genuinely distinct effects.

This anti-double-counting rule is locked.

---

# 16. Opposed Resolution

When another active force directly resists the objective:

> **Opposed Margin = Actor Effective Capability − Opponent Effective Capability**

Then use the same probability engine.

Examples:

- Stealth vs Detection
- Deception vs Insight
- Grapple vs Escape
- Pursuit vs Evasion
- Genjutsu vs relevant Resistance

Normally use **one shared resolution**, not two independent competing rolls.

---

# 17. Probability Model

The provisional probability curve remains:

> **P(success) = 1 / (1 + 10^(-M/20))**

where:

> **M = Effective Capability − Effective Difficulty**

At roughly:

- −40 → 1%
- −20 → 9%
- −10 → 24%
- 0 → 50%
- +10 → 76%
- +20 → 91%
- +40 → 99%

The sigmoid architecture is strong.

The `/20` sensitivity constant remains provisional.

---

# 18. One Random Draw

When genuine uncertainty remains:

> generate one hidden random draw from 0–100.

If:

> R ≤ P

the objective succeeds.

Otherwise it fails.

Do not reroll unless a specific mechanic explicitly creates another opportunity.

---

# 19. One Draw Also Determines Outcome Quality

This is one of the strongest rules we've developed and should be locked.

> **Outcome Margin = Success Probability − Random Result**

Positive:
> success.

Negative:
> failure.

This creates a natural link between capability and outcome severity.

---

# 20. Why This Works

A 95% action can only fail narrowly.

Therefore:

> experts do not catastrophically botch routine tasks.

A 5% action can only succeed narrowly.

Therefore:

> desperate long shots do not become impossible master-level feats.

This is exactly the behavior we want.

---

# 21. Provisional Outcome Bands

Current working bands:

### Success
+40 or more:
> Exceptional

+20 to +39:
> Strong

+6 to +19:
> Standard

0 to +5:
> Narrow

### Failure
−1 to −5:
> Narrow

−6 to −19:
> Standard

−20 to −39:
> Severe

−40 or less:
> Catastrophic-range

These boundaries remain provisional.

The degree concept is locked.

---

# 22. Catastrophic-Range Does Not Mean Catastrophe

This distinction is locked.

A severe Outcome Margin merely allows severe consequences if the situation contains:

- hazard,
- exposure,
- sufficient stakes.

A disastrous roll on a harmless task remains harmless.

---

# 23. Outcome Ceiling and Outcome Floor

Every resolution can have:

### Outcome Ceiling
Best plausible result.

### Outcome Floor
Worst plausible result.

Skill, preparation, equipment, safeguards, and circumstance can alter them.

Probability cannot override them.

---

# 24. Advantage Is Not “Roll Twice”

Traditional advantage/disadvantage should not exist as a universal rule.

Instead, advantages should be modeled as:

- numerical edge,
- structural edge,
- improved outcome ceiling,
- improved failure floor,
- reduced opposition,
- new available method.

This is much more expressive.

---

# 25. Large Capability Gaps Suppress Randomness

Power gaps should matter because probability naturally moves toward 0 or 100.

For direct contests, current provisional gap interpretation:

- 0–5 — Near Peer
- 6–10 — Slight Advantage
- 11–20 — Clear Advantage
- 21–30 — Major Advantage
- 31–40 — Overwhelming Advantage
- 41+ — Extreme Mismatch

These labels need curve testing.

The underlying principle is locked.

---

# 26. Preparation Should Change the Problem

A weaker character should defeat a stronger one primarily by:

- traps,
- terrain,
- surprise,
- information,
- counters,
- teamwork,
- resource pressure,

not because RNG ignores capability.

The best preparation often changes:

> **which contest is being resolved.**

This is foundational.

---

# 27. Check Suppression

Do not resolve uncertainty mechanically when:

- success is automatic,
- failure is automatic,
- consequences are negligible,
- established fact already answers the question,
- a broader resolution already covers the action,
- routine repetition can be abstracted.

This prevents dice/check spam.

---

# 28. Retry Rule

Before every repeated attempt, ask:

> **What changed?**

Possible changes:

- method,
- time investment,
- tools,
- information,
- assistance,
- character condition,
- target condition.

If nothing meaningful changed:

> a fresh identical roll should generally not occur.

This is locked.

---

# 29. Extended Actions Use Persistent Progress

Long-term activities should not become:

> roll every day until five successes.

Instead track appropriate states such as:

- Progress
- Knowledge
- Quality
- Resources
- Setbacks
- Milestones

This applies to:

- research,
- crafting,
- training,
- investigation,
- long tracking,
- large negotiations.

---

# 30. Scope and Difficulty Are Separate

For projects:

### Scope
How much work exists.

### Difficulty
How technically demanding the work is.

A large easy project and a small difficult project should behave differently.

This is locked.

---

# 31. Teamwork Does Not Add Stats Together

The engine chooses an appropriate teamwork model:

- Lead + Support
- Weakest Link
- Collective Effort
- Best Specialist
- Parallel Roles
- Synergistic Combination

No:

> 50 Skill + 40 Skill = 90 Skill.

Coordination, role suitability, communication, and task structure determine the benefit.

---

# 32. Knowledge Exists Separately From Truth

For important information, maintain:

### Objective Truth
What actually happened/is true.

### Character Knowledge
What the character knows.

### Character Belief
What they think is true.

### Confidence
How strongly they believe it.

### Source
Why they believe it.

This applies to both player and NPCs.

---

# 33. Hidden Checks Stay Hidden

Never narrate:

> You failed Perception.

Instead:

> You don't notice anything unusual.

Likewise, the existence of a hidden check should not itself reveal information.

---

# 34. Observation and Interpretation Are Separate

A character may observe:

> unusual discoloration.

They may or may not understand:

> poison residue.

Expertise determines interpretation.

This should be retained as a major information-system rule.

---

# 35. Luck Has a Narrow Role

Luck is not a foundational Attribute.

It may influence:

- incidental opportunity,
- borderline consequence,
- rare world events,
- secondary outcome branches.

It cannot:

- bypass prerequisites,
- create impossible capability,
- replace Skill.

If persistent Luck traits exist later, they should be bounded and uncommon.

---

# 36. Critical Events Are Emergent

No natural 20 or natural 1.

A true critical event requires:

- extreme outcome,
- relevant opportunity or hazard,
- meaningful consequence space.

Exceptional roll alone is not enough.

---

# 37. Resources Affect Resolution Causally

Resources include:

- chakra,
- stamina,
- time,
- tools,
- consumables,
- durability,
- money,
- favors,
- attention.

Spending them only matters when it actually changes:

- output,
- reliability,
- speed,
- safety,
- duration,
- flexibility.

No generic:

> Spend 10 Chakra = +10 check.

---

# 38. More Chakra Is Not Automatically Better

This Naruto-specific safeguard should be locked.

Relevant distinctions include:

- reserves,
- output,
- control,
- efficiency,
- technique operating range.

A novice dumping more chakra into a technique can make it worse rather than better.

---

# 39. Time Has Diminishing Returns

Actions may have:

- minimum execution time,
- standard duration,
- maximum useful preparation.

Taking longer can improve:

- precision,
- safety,
- information,
- efficiency.

But may also increase:

- exposure,
- opportunity cost,
- information staleness.

More time is not universally better.

---

# 40. Stress Is Targeted

Stress is not:

> −10 to everything.

It can affect:

- fine control,
- attention,
- planning,
- resource efficiency,
- decision-making.

Moderate arousal may even improve:

- vigilance,
- reaction.

Response depends on:

- Willpower,
- experience,
- mastery,
- personality,
- familiarity.

---

# 41. Mastery Protects Reliability

One of the strongest cross-system principles:

> **Skill expands what you can do. Mastery expands how reliably, efficiently, and quickly you can do a specific thing.**

Mastery should especially help with:

- pressure,
- speed,
- multitasking,
- resource efficiency.

I would treat this as a major locked design principle.

---

# 42. Characters Estimate Difficulty; They Do Not Know It

Separate:

- True Difficulty
- Perceived Difficulty
- Perceived Capability
- Perceived Odds
- Perceived Stakes

The player normally receives the character's estimate.

NPCs make decisions from their estimates too.

---

# 43. NPCs Use Perceived Utility

NPC decisions should consider:

- goals,
- values,
- relationships,
- perceived probabilities,
- stakes,
- resources,
- future consequences,
- risk tolerance.

Personality alters choice thresholds.

It does not alter physical probability.

---

# 44. NPCs Are Not Optimizers With Omniscience

An NPC can make the wrong decision because:

- information is incomplete,
- assumptions are wrong,
- emotion interferes,
- goals differ.

But intelligent, experienced NPCs should not be artificially stupid merely to help the player.

---

# 45. Player-Facing Resolution Is Mostly Qualitative

Default gameplay should avoid:

> 72% success chance.

Instead:

> You think you have the edge.

Exact values can exist in a debug/testing mode.

The player should know:

- what their character knows,
- obvious risks,
- meaningful costs,
- relevant environmental information.

Unknown facts stay unknown.

---

# 46. Free-Form Choice Remains Central

Suggested choices can help the player understand obvious options.

They are never exhaustive.

The player may propose any plausible method.

Unexpected solutions should be evaluated through the same rules rather than rejected because they were not prewritten.

---

# 47. Outcome Narration Reflects Degree

The prose should make a narrow success feel narrow and an exceptional success feel exceptional.

But it should describe:

> what happened,

rather than:

> what mechanical category occurred.

No routine:

> CRITICAL SUCCESS!

unless some future UI intentionally displays debug information.

---

# 48. Failure Is Real

Failure means:

> the declared objective was not achieved.

The engine should not automatically convert failure into:

> success with a complication.

Real outcomes can include:

- mission failure,
- rejection,
- capture,
- injury,
- lost opportunity,
- death.

The simulation continues from the new world state.

---

# 49. Failing Forward Is Emergent

Failure may produce:

- new information,
- escalation,
- altered opportunity,
- another playable situation.

But only because those consequences logically follow.

There is no rule that every failure must create a consolation opportunity.

---

# 50. Progression Uses Learning Value, Not Check Count

Ruleset 2 produces learning events.

Ruleset 1 determines actual advancement.

Learning value depends on:

- challenge,
- comprehensibility,
- feedback,
- novelty,
- repetition,
- participation,
- pressure.

This prevents:

- trivial grinding,
- intentional failure farming,
- impossible-task farming,
- weak-opponent farming.

---

# 51. Rank Is Not a Resolution Modifier

Rank affects:

- authority,
- access,
- assignments,
- credibility,
- expectations,
- resources.

It does not directly affect:

> success probability.

Actual character stats always override rank expectations once known.

---

# 52. Special Abilities Use Explicit Rule Exceptions

A special ability should specify exactly what it changes.

Possible effects:

### Capability
Changes performance.

### Structural
Changes available actions or defenses.

### Information
Creates new sensory/knowledge channel.

### Consequence
Changes outcome ceiling/floor.

Special abilities should never amount to:

> "wins because special."

---

# 53. Specific Overrides General

Canonical priority rule:

> **More specific mechanics override more general mechanics.**

Example:

General:
> darkness impairs normal sight.

Specific:
> sensory ability functions without visible light.

Specific rule wins within its defined scope.

---

# 54. Persistent Effects Do Not Reroll Constantly

If an effect successfully establishes:

> immobilized,
> poisoned,
> chakra-suppressed,

that state persists until something changes it.

Do not reroll its existence every action.

This follows the established-state principle.

---

# 55. World State Is Authoritative

Once established:

- positions,
- injuries,
- resources,
- relationships,
- knowledge,
- equipment,
- environmental facts

persist until something changes them.

The engine may not silently rewrite them for convenience.

---

# 56. Hidden Facts Must Preexist Their Effects

This is one of the strongest simulation safeguards.

The engine cannot wait for an outcome and then invent:

> hidden trap,
> hidden ability,
> hidden ally

to justify it.

If an undefined fact becomes relevant:

1. generate it from world logic,
2. persist it,
3. resolve against it.

---

# 57. Lazy Generation Is Allowed

We cannot pre-generate every detail of the entire Naruto world.

When undefined state becomes relevant, it can be generated from:

- location,
- character,
- rank,
- profession,
- history,
- setting logic.

But generation must answer:

> What makes sense?

N

