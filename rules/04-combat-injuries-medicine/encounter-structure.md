# 4.2 — Combat State & Encounter Structure

Status: Provisional design section pending explicit approval.

This section defines when the simulation enters structured combat, who belongs to an encounter, how awareness and surprise are represented, how combatants enter or leave, and when an encounter is considered over.

## 4.2.1 Combat Is a Simulation State, Not a Separate World

Entering combat does not create an artificial arena or suspend the surrounding world. Time, terrain, civilians, reinforcements, weather, ongoing hazards, distant observers, and unrelated events may continue to matter.

Structured combat exists only because the simulation temporarily needs finer sequencing and consequence tracking.

## 4.2.2 Encounter States

The simulation may operate through four broad encounter states:

### Normal State
No immediate hostile interaction requires structured sequencing.

Characters may travel, talk, investigate, train, observe, hide, prepare traps, or perform other normal actions.

### Tension State
At least one character reasonably suspects danger, expects imminent hostility, is stalking a target, is being stalked, or is actively preparing for possible combat.

Tension does not automatically mean everyone knows combat is about to occur.

Examples:
- sensing an unknown chakra signature nearby;
- hearing movement in the trees;
- following a suspected enemy;
- waiting in an ambush position;
- approaching a hostile checkpoint;
- negotiating while both sides expect violence.

### Active Combat State
At least one hostile action, immediate threat, or defensive response requires ordered tactical resolution.

Examples:
- an attack is launched;
- a trap is triggered;
- a character attempts to seize or restrain another;
- a discovered infiltrator attempts to flee while being pursued;
- two sides simultaneously commit to violence.

### Aftermath State
Immediate hostile sequencing is no longer necessary, but consequences still require attention.

Examples:
- checking casualties;
- stabilizing injuries;
- searching the battlefield;
- restraining prisoners;
- tracking fleeing enemies;
- assessing environmental damage.

The simulation may move backward between states if danger re-emerges.

## 4.2.3 Structured Combat Begins Only When Ordering Matters

The engine should not enter detailed combat merely because hostile intent exists.

Structured sequencing begins when the relative timing of actions could materially change the outcome.

A character silently stalking another may remain in normal or tension state for several minutes. The moment the stalker attacks, is detected, triggers a trap, or forces a time-sensitive response, the simulation can enter active combat.

This prevents unnecessary turn-by-turn movement before anything consequential happens.

## 4.2.4 Awareness Is Per-Character and Source-Specific

There is no universal “the encounter has started, therefore everyone knows.”

Each character tracks what threats they are aware of.

A character may be:
- unaware of a threat;
- suspicious that a threat exists;
- aware of danger but not its source;
- aware of a specific hostile actor;
- fully engaged with that actor.

A shinobi can therefore be fighting one opponent while remaining unaware of a second hidden attacker.

Ruleset 2 resolves perception, concealment, deception, sensory techniques, and uncertain information. Ruleset 4 records the resulting combat awareness state.

## 4.2.5 Surprise Is an Opportunity Window, Not a Permanent Condition

Surprise should not function as a universal “lose your first turn” status.

Instead, surprise exists when a hostile action develops before the target has enough awareness and time to mount their normal range of responses.

Possible consequences may include:
- reduced defensive options;
- delayed response;
- inability to use a defense requiring prior awareness;
- poorer positioning;
- loss of prepared actions;
- an attacker acting inside a narrower reaction window.

The exact consequences depend on what the target knew, when they detected the threat, and how quickly they could respond.

Once the target meaningfully recognizes and reacts to the threat, that surprise window ends.

## 4.2.6 Ambushes Can Be Partial

An ambush does not have to surprise an entire team equally.

Example:
- one sensory ninja detects hidden enemies;
- two teammates trust the warning and prepare;
- a fourth teammate is distracted and does not understand the threat in time.

Each participant enters combat with their own awareness and readiness.

This allows sensory skill, communication speed, discipline, and positioning to matter naturally.

## 4.2.7 Readiness Is Separate From Awareness

Knowing danger exists does not always mean being ready to respond optimally.

A character may:
- know an enemy is nearby but have their weapon sheathed;
- expect an attack but be carrying an injured ally;
- recognize a threat while mid-technique;
- be physically prepared but watching the wrong direction;
- have a prepared defense already active.

Readiness should influence the opening exchange when relevant without becoming a permanent combat statistic.

## 4.2.8 Encounter Membership Is Based on Relevance

Combat encounters do not have fixed invisible boundaries.

A character becomes part of the active encounter when they can materially affect it or are directly threatened by it.

Participants may include:
- active attackers and defenders;
- hidden combatants;
- medics;
- summons;
- clones;
- puppets;
- remote technique users;
- civilians requiring protection;
- reinforcements;
- fleeing targets;
- pursuing characters.

Someone can enter or leave the encounter dynamically.

## 4.2.9 Hidden Participants Still Exist in the Encounter State

The simulation may track combatants whom the player character does not know exist.

Hidden attackers, distant observers, concealed reinforcements, underground enemies, disguised enemies, or remote technique users remain part of the underlying simulation when relevant.

Their existence should not be exposed merely because structured combat has begun.

## 4.2.10 Joining an Ongoing Fight Does Not Reset Combat

Reinforcements enter the current battlefield state as it exists.

They do not create a fresh initiative cycle or reset positioning, injuries, prepared actions, hazards, or awareness.

Their entry depends on:
- when they arrive;
- what they can perceive;
- whether either side notices them;
- their current readiness;
- their position and travel path.

A reinforcement can potentially arrive unnoticed.

## 4.2.11 Combatants May Enter With Existing Actions or Commitments

A character entering combat may already be:
- sprinting;
- hiding;
- channeling chakra;
- maintaining a jutsu;
- carrying someone;
- falling;
- restrained;
- wounded;
- exhausted;
- guarding a position;
- preparing an attack.

Structured combat should preserve that state rather than normalizing everyone into a neutral starting pose.

## 4.2.12 Hostility Does Not Require Lethal Intent

Combat state can begin from:
- assassination;
- sparring;
- arrest;
- capture;
- robbery;
- restraint;
- protecting another person;
- forced removal;
- nonlethal dueling;
- preventing escape.

The encounter should record relevant intent because characters attempting capture or restraint behave differently from characters attempting to kill.

Intent does not guarantee outcome: nonlethal actions can still cause serious injury.

## 4.2.13 Multiple Conflicts Can Overlap

One battlefield may contain separate but interacting engagements.

For example:
- two shinobi duel on a rooftop;
- a medic treats an ally below;
- another enemy pursues a fleeing civilian;
- a hidden sniper watches all three.

The engine may resolve these as one encounter state while only applying detailed sequencing to interactions whose timing matters.

This avoids forcing every participant into one artificial turn loop.

## 4.2.14 Disengagement Is an Action, Not a Menu Option

A character does not leave combat merely by declaring that they flee.

Disengagement may require:
- creating distance;
- breaking line of sight;
- escaping pursuit;
- hiding;
- blocking access;
- using terrain;
- forcing the enemy to choose another objective;
- convincing the enemy not to pursue.

Ruleset 2 resolves uncertain contests involved in escape or pursuit.

Ruleset 4 tracks whether the character is still tactically reachable.

## 4.2.15 Separation Does Not Always End the Encounter

Two opponents may temporarily lose contact while still participating in the same broader conflict.

Examples:
- a target escapes around a building while being pursued;
- combatants separate into nearby rooms;
- one fighter retreats underground;
- smoke obscures everyone for several seconds.

Combat may shift back toward tension state rather than fully ending.

## 4.2.16 Combat Ends When Immediate Sequencing No Longer Matters

Active combat ends when no participant currently requires fine-grained hostile sequencing.

This may occur because:
- one side is defeated;
- one side surrenders;
- all hostile parties successfully disengage;
- combatants lose contact with no immediate pursuit;
- both sides intentionally stop fighting;
- all relevant threats are incapacitated or restrained.

The simulation then normally enters aftermath or tension state.

## 4.2.17 Victory and Encounter End Are Different

An encounter can end without anyone “winning.”

Examples:
- both sides retreat;
- weather separates the combatants;
- a third party interrupts the fight;
- the target escapes;
- both sides agree to stop;
- the battlefield becomes too dangerous to continue.

Likewise, one side may accomplish its mission objective before combat itself is over.

Combat resolution should therefore track objectives separately from encounter termination.

## 4.2.18 Combat Does Not Freeze the Wider World

During active combat:
- distant allies may continue traveling toward the scene;
- fires can spread;
- civilians can flee;
- structures can collapse;
- reinforcements can be summoned;
- alarms can propagate;
- mission objectives can move;
- time-sensitive events can continue.

Structured combat is a resolution lens, not a pause function.

## 4.2.19 Encounter Compression Is Allowed

If no meaningful decision or uncertainty would be gained from resolving every exchange, the engine may compress portions of combat.

Examples:
- an elite shinobi rapidly defeats several ordinary bandits;
- two background squads exchange attacks while the player is elsewhere;
- an already-decided pursuit reaches its inevitable conclusion.

Compression must preserve plausible injuries, resource use, elapsed time, positioning, and other consequences when those consequences matter.

## 4.2.20 Minimum Encounter State

During meaningful combat, the engine should be able to track at least:
- who is present and relevant;
- each participant's known position or approximate position;
- awareness of relevant threats;
- readiness/current commitment;
- immediate objective or intent;
- active injuries and conditions;
- major ongoing techniques;
- current engagement/pursuit relationships;
- environmental hazards;
- hidden participants known only to the simulation.

Later sections may add more detailed state, but these are the minimum structural requirements.

## Design Rule

Combat should begin because **timing becomes consequential**, not because the story announces “combat mode.”

Combat should end because **fine-grained hostile sequencing is no longer necessary**, not because every opponent reached zero HP.
