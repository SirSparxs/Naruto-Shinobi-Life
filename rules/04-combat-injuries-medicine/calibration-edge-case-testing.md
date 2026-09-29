# 4.30 — Calibration & Edge-Case Testing

Status: Provisional design section pending explicit approval.

This section defines how Ruleset 4 should be tested before being considered stable.

Its purpose is to detect:
- hidden HP-like behavior;
- runaway lethality;
- implausible durability;
- speed exploits;
- reaction-loop exploits;
- regeneration exploits;
- medical inconsistencies;
- nonlethal loopholes;
- compression bias;
- player/NPC asymmetry;
- contradictions between ruleset sections.

The governing rule is:
**A combat rule is not finished when it sounds plausible. It is finished when it survives adversarial testing across the situations most likely to break it.**

## 4.30.1 Calibration Is About Outcome Tendencies

Testing should ask whether the system produces believable tendencies over many comparable scenarios.

Do not calibrate toward one predetermined result.

Instead ask:
- does a major capability advantage matter reliably?
- can tactical advantage still matter?
- do serious injuries remain serious?
- do weaker characters occasionally succeed for understandable reasons?
- do exceptional abilities work without invalidating shared rules?

## 4.30.2 Calibration Uses Scenarios, Not Abstract Numbers Alone

Rules should be tested through concrete situations.

A test scenario should define:
- participants;
- relevant attributes/skills;
- equipment;
- chakra;
- environment;
- objective;
- information;
- injury state;
- starting position.

Then test how the system behaves.

## 4.30.3 Baseline Matchups

Start with ordinary matchups where no unusual ability interferes.

Examples:
- evenly matched Academy students;
- evenly matched Genin;
- Chūnin versus Chūnin;
- Jōnin versus Jōnin.

These reveal whether:
- ordinary exchanges last a reasonable amount of time;
- injuries emerge plausibly;
- fatigue and chakra matter;
- small advantages do not become automatic victory.

## 4.30.4 Rank Is Not the Calibration Variable

Rank should help select representative NPC capability profiles.

Testing must still use actual:
- attributes;
- skills;
- mastery;
- equipment;
- information.

Do not calibrate:
“Jōnin must beat Chūnin 90% of the time.”

Rank is a soft world expectation, not a combat modifier.

## 4.30.5 Weak-versus-Strong Tests

Test meaningful capability gaps such as:
- Academy student versus experienced Genin;
- Genin versus Jōnin;
- ordinary Jōnin versus elite S-class combatant.

Expected tendency:
the stronger fighter should usually dominate ordinary direct exchanges.

But weaker characters should still have meaningful routes through:
- ambush;
- poison;
- traps;
- teamwork;
- hostages;
- hard counters;
- objectives other than defeating the stronger opponent.

## 4.30.6 Power Gaps Must Be Stable

A strong fighter should not lose frequently because the system generates too many independent random opportunities.

If repeated micro-resolution causes large capability gaps to collapse, the system has random-walk distortion and should be adjusted.

## 4.30.7 Power Gaps Must Not Become Immunity

The opposite failure is also possible.

A vastly stronger character should not automatically:
- detect every ambush;
- resist every toxin;
- ignore every restraint;
- survive every environmental hazard.

Test whether unrelated capability is accidentally becoming universal defense.

## 4.30.8 Speed-Extreme Tests

Test:
- similar speed;
- moderate speed advantage;
- extreme speed advantage;
- extreme speed with poor perception;
- slower fighter with strong prediction/sensory ability.

The goal is to verify:
**speed compresses reaction windows and controls tempo without becoming unlimited extra turns.**

## 4.30.9 Speed Must Not Create Infinite Action Loops

Test whether a very fast character can repeatedly act before a slower opponent is ever allowed to meaningfully respond.

If so, check:
- action execution;
- recovery;
- distance;
- perception;
- commitment;
- actual reaction windows.

Extreme speed can be overwhelming without violating continuous-time logic.

## 4.30.10 Perception-Speed Mismatch

Test characters whose physical speed exceeds their ability to perceive or control events at that speed.

Possible consequences:
- overshooting;
- poor precision;
- delayed reactions;
- inability to exploit full movement speed safely.

This verifies that perception remains relevant.

## 4.30.11 One-Hit Lethality Tests

Test attacks capable of:
- decapitation;
- heart destruction;
- catastrophic brain trauma;
- massive blast;
- severe penetrating trauma.

The system should allow immediate or near-immediate fatality when physically justified.

Do not force every character through multiple “health states” first.

## 4.30.12 One-Hit Lethality Must Not Become Common Chip-Lethality

Also test ordinary:
- punches;
- shallow cuts;
- low-output jutsu.

They should not routinely become fatal without a relevant:
- location;
- mechanism;
- complication;
- vulnerability.

## 4.30.13 Repeated Minor Trauma Tests

Test accumulation of:
- bruising;
- shallow cuts;
- repeated impacts;
- repeated low-level burns.

The system should allow cumulative degradation without secretly adding them into an HP bar.

Ask:
**What actual structures or functions are worsening?**

## 4.30.14 Armor Tests

Test the same attack against:
- no armor;
- flexible armor;
- rigid armor;
- damaged armor.

Verify that armor changes:
- penetration;
- blunt transfer;
- location;
- equipment condition

rather than simply subtracting a universal number.

## 4.30.15 Chakra Reinforcement Tests

Test identical impacts against:
- no reinforcement;
- weak reinforcement;
- strong reinforcement.

Verify that reinforcement:
- changes exposure before injury;
- consumes chakra appropriately;
- does not become temporary HP.

## 4.30.16 Area-Attack Tests

Test:
- open field;
- dense cover;
- narrow corridor;
- allies mixed with enemies.

Verify that area attacks affect space and movement rather than becoming automatic hits against everyone in radius.

## 4.30.17 Multi-Attacker Tests

Test:
- two attackers from same angle;
- two attackers from opposite angles;
- coordinated attacks;
- uncoordinated crowding.

The system should distinguish:
- actual threat saturation;
- ally obstruction;
- attention splitting.

Do not reduce all cases to “+X for numbers.”

## 4.30.18 Grappling Size and Strength Extremes

Test:
- equal-sized skilled grapplers;
- small expert versus large novice;
- enormous Strength disparity;
- extra-limbed physiology;
- injured grappler.

Verify that:
- leverage matters;
- skill matters;
- overwhelming physical disparity still matters;
- partial control states remain possible.

## 4.30.19 Nonlethal Capture Tests

Test live capture against:
- cooperative surrender;
- ordinary resistance;
- stronger target;
- faster target;
- wounded target;
- target with hidden medical instability.

Verify that nonlethal intent:
- changes tactics;
- increases control demands;
- does not erase accidental lethality.

## 4.30.20 Knockout Tests

Repeatedly test trauma-induced unconsciousness.

Verify that:
- unconsciousness has a physical cause;
- head trauma may be medically significant;
- “safe knockout” does not emerge as a universal attack option.

## 4.30.21 Bleeding Tests

Test:
- small external bleed;
- major vessel injury;
- internal bleeding;
- multiple moderate wounds.

Verify that:
- bleed rate and accumulated blood loss remain separate;
- stabilization changes progression;
- lost blood does not instantly return when the wound closes.

## 4.30.22 Shock Tests

Test shock caused by:
- hemorrhage;
- severe burns;
- systemic injury.

Verify that:
- Willpower does not restore circulation;
- compensation can hide severity;
- deterioration remains time-dependent.

## 4.30.23 Near-Death Tests

Test:
- reversible respiratory arrest;
- circulatory collapse;
- catastrophic irreversible brain destruction;
- patient receiving immediate advanced care;
- patient receiving delayed care.

Verify that rescue windows arise from physiology and available treatment rather than universal death saves.

## 4.30.24 First-Aid Tests

Test whether ordinary field care can:
- stop external bleeding;
- stabilize fracture;
- protect airway;
- support evacuation

without accidentally becoming definitive healing.

## 4.30.25 Medical Ninjutsu Tests

Test identical injuries under:
- novice medic;
- skilled medic;
- elite medical-nin;
- high Chakra Control but poor medical knowledge;
- expert physician with insufficient Chakra Control.

Verify that:
- medical knowledge and control remain distinct;
- advanced skill expands complexity and efficiency;
- no universal green-hand heal emerges.

## 4.30.26 Surgery Tests

Test injuries that:
- field medicine can stabilize;
- require surgery;
- require specialist transplantation;
- exceed current facility capability.

Verify that hospital access expands options without automatically erasing consequences.

## 4.30.27 Recovery Tests

Test the same injury with:
- excellent treatment and rehab;
- poor treatment;
- early return to combat;
- repeated reinjury;
- accelerated healing.

Verify that:
- structural and functional recovery remain separate;
- recovery milestones behave plausibly;
- time skips advance rather than reset state.

## 4.30.28 Regeneration Tests

Every regeneration trait should be tested against:
- shallow wound;
- severed vessel;
- fracture;
- missing tissue;
- major blood loss;
- organ destruction;
- brain injury;
- repeated damage;
- depleted chakra/resources.

This exposes vague immortality.

## 4.30.29 Regeneration Throughput Tests

Apply damage:
- below regeneration rate;
- near regeneration rate;
- above regeneration rate.

Verify that regeneration can be overwhelmed when its defined throughput is exceeded.

## 4.30.30 Exceptional Physiology Tests

For every unusual body, test:
- what it resists;
- what it does not resist;
- medical compatibility;
- hidden tradeoffs;
- interaction with ordinary injury rules.

The goal is to ensure special physiology modifies specific mechanisms rather than becoming broad immunity.

## 4.30.31 Poison Tests

Test:
- low dose;
- high dose;
- repeated exposure;
- delayed onset;
- resistant physiology;
- correct antidote;
- wrong antidote;
- supportive care without antidote.

Verify that toxin effects arise from:
dose + route + target system + time.

## 4.30.32 Disease Tests

Test:
- infection establishment;
- incubation;
- asymptomatic transmission;
- treatment;
- chronic outcome.

Verify that disease does not behave like a renamed poison.

## 4.30.33 Environmental Tests

Test combat around:
- cliffs;
- fire;
- unstable structures;
- deep water;
- smoke;
- confined tunnels.

Verify that the environment changes available choices and can create injury independently of direct attacks.

## 4.30.34 Structural Failure Tests

Test:
- local wall breach;
- damaged support;
- repeated area destruction;
- reinforced structures.

Verify that buildings neither:
- collapse from trivial hits;
- remain indestructible despite destroyed supports.

## 4.30.35 Friendly-Fire Tests

Test:
- large area attack with allies nearby;
- poor visibility;
- hidden teammate;
- synchronized team attack.

Verify that geometry and communication govern risk.

## 4.30.36 Teamwork Tests

Compare:
- four individually strong but uncoordinated fighters;
- four slightly weaker but highly coordinated fighters.

Coordination should create advantage through:
- information;
- setup;
- rotation;
- rescue;
- space control.

Avoid generic party bonuses.

## 4.30.37 Medic-Protection Tests

Test a squad where:
- medic is exposed;
- medic is screened;
- medic is forced to move;
- multiple casualties occur.

Verify that protecting medical capability has real strategic value.

## 4.30.38 Casualty-Extraction Tests

Test:
- one-person carry;
- two-person carry;
- drag under fire;
- stabilized versus unstable patient.

Verify costs to:
- speed;
- hands;
- fatigue;
- patient condition.

## 4.30.39 Aftermath Tests

After a fight, verify that:
- injuries remain;
- ammunition remains spent;
- prisoners remain secured or unsecured;
- dropped equipment stays dropped;
- hazards remain;
- mission outcome is evaluated separately from combat victory.

## 4.30.40 Persistence Tests

Advance:
- one scene;
- one day;
- one week.

Verify that:
- unresolved states remain;
- time-sensitive states progress;
- treatment only occurs if actual care exists;
- hidden diagnoses stay hidden.

## 4.30.41 Save/Load Tests

Save and reload during:
- active bleeding;
- poison progression;
- recovery;
- prisoner transport;
- damaged equipment.

The loaded state should be functionally identical.

## 4.30.42 Compression-Parity Tests

Run comparable scenarios at:
- detailed resolution;
- exchange resolution;
- encounter resolution.

Compare tendencies in:
- victory;
- casualty severity;
- chakra use;
- fatigue;
- objective success.

Large systematic differences indicate abstraction bias.

## 4.30.43 Background-NPC Tests

Resolve NPC fights entirely off-screen.

Verify:
- no plot armor;
- no arbitrary death rolls;
- resources are consumed;
- causal injuries exist;
- survivors retain consequences.

## 4.30.44 Hidden-Information Tests

Create scenarios where:
- one character knows about a trap;
- another does not;
- the engine knows an internal injury;
- the patient does not.

Verify that narration and decisions use observer-specific knowledge correctly.

## 4.30.45 Player/NPC Parity Tests

Give identical:
- stats;
- skills;
- equipment;
- injuries;
- situation

to player and NPC actors.

The mechanical possibilities should remain identical.

Only decision-making differs.

## 4.30.46 Exploit Testing

Actively search for strategies such as:
- infinite reaction loops;
- infinite low-cost healing;
- fatigue bypass;
- stun-lock;
- restraint-lock;
- regeneration loops;
- zero-risk poison delivery;
- action-economy multiplication through clones/summons;
- instant safe knockouts.

If an exploit appears, first identify which causal assumption is missing before adding arbitrary caps.

## 4.30.47 Degenerate Strategy Tests

A system may be technically balanced but still encourage one dominant tactic.

Test whether:
- always dodge;
- always rush;
- always use area attack;
- always target limbs;
- always use poison;
- always retreat and reset

becomes overwhelmingly optimal across unrelated situations.

Good rules should produce contextual tactics.

## 4.30.48 Hidden HP Detection Test

Ask whether the system is effectively recreating HP through another variable.

Warning signs include:
- injuries only happen after accumulated threshold;
- all trauma contributes to one universal bar;
- characters function normally until threshold reached;
- every attack can be reduced to one scalar damage value.

If these appear, return to mechanism-based injury logic.

## 4.30.49 Hidden AC Detection Test

Ask whether defense has accidentally become:
“high defense number means attacks miss.”

Defense should still emerge from:
- awareness;
- action;
- position;
- timing;
- technique;
- cover.

Derived summaries must not replace causal defense.

## 4.30.50 Overcomplexity Test

A rule can also fail by demanding detail that does not improve outcomes.

Ask:
- does this variable change decisions?
- does it change consequences?
- can it be derived instead of tracked?
- can it be compressed safely?

If not, remove or abstract it.

## 4.30.51 Bookkeeping Stress Test

Run:
- six-person squad fight;
- multiple injuries;
- poison;
- damaged terrain;
- prisoner;
- medic;
- reinforcements.

If state becomes impossible to maintain reliably, identify:
- redundant variables;
- states that can be derived;
- details that should be compressed.

Complexity must remain manageable.

## 4.30.52 Narrative Plausibility Test

Read the mechanical outcome as an in-world event.

Ask:
- does the sequence make physical sense?
- can a player understand why it happened?
- do the injuries match the mechanisms?
- did an unexplained rule override causality?

If the outcome cannot be explained coherently, the model likely needs revision.

## 4.30.53 Canon Plausibility Test

For Naruto-inspired situations, ask whether the system can reproduce the broad logic of:
- extreme speed;
- chakra reinforcement;
- substitution;
- devastating techniques;
- medical ninjutsu;
- capture teams;
- unusual bodies

without requiring scripted exceptions.

The goal is not frame-by-frame canon replication.
The goal is internal Naruto-world plausibility.

## 4.30.54 New Ability Test Protocol

Any new special ability that touches combat should be tested against:
1. ordinary attack interaction;
2. defense;
3. injury;
4. fatigue/chakra cost;
5. capture/restraint;
6. medical treatment;
7. environmental interaction;
8. persistence;
9. known counters;
10. extreme edge cases.

This prevents abilities from bypassing unrelated systems accidentally.

## 4.30.55 Regression Testing

When one rule is changed, rerun representative tests that depend on it.

Examples:
- changing speed rules should rerun initiative, dodge, pursuit, and team-intervention tests;
- changing healing should rerun death, first aid, recovery, and regeneration tests.

A local fix must not silently break another section.

## 4.30.56 Calibration Benchmarks

The project should eventually maintain a small library of canonical benchmark scenarios.

Examples:
- equal Genin duel;
- Genin versus Jōnin;
- ambush by weaker attacker;
- severe bleeding rescue;
- live capture of stronger target;
- regeneration overload;
- medic under fire;
- squad retreat with casualty;
- compressed versus detailed battle.

These become repeatable regression tests.

## 4.30.57 Test Outputs

Each benchmark should record:
- scenario;
- expected qualitative tendencies;
- actual outcome;
- rule interactions;
- discovered exploit/contradiction;
- whether revision is required.

Do not hard-code a single required winner unless the scenario is effectively deterministic.

## 4.30.58 Calibration Success Criteria

Ruleset 4 is behaving well when:
- capability differences matter without becoming immunity;
- tactical advantage matters without erasing major gaps;
- serious attacks can be seriously dangerous;
- minor attacks do not behave like inevitable chip death;
- medicine is powerful without becoming generic healing;
- nonlethal combat requires actual control;
- persistent consequences survive;
- compressed and detailed simulation agree in broad tendency;
- players and NPCs follow the same physical rules.

## 4.30.59 Failure Handling

When a test fails:
1. identify the broken causal assumption;
2. locate the owning ruleset section;
3. change the smallest necessary rule;
4. avoid adding arbitrary exception bonuses or caps;
5. rerun related benchmarks;
6. document the reason for the change.

## 4.30.60 Calibration Is Continuous

Ruleset 4 should continue to be tested as:
- new jutsu;
- bloodlines;
- equipment;
- NPCs;
- missions;
- world systems

are added.

A combat system this interconnected cannot be permanently “finished” after one pass.

## Core Design Rule

Calibration should stress the simulation where it is most likely to break.

The system should survive extremes without abandoning its foundational principles:
**causal combat, player/NPC parity, mechanism-specific injury, persistent consequences, meaningful uncertainty, and no hidden HP or plot armor.**
