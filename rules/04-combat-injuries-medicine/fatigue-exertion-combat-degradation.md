# 4.13 — Fatigue, Exertion & Combat Degradation

Status: Provisional design section pending explicit approval.

This section defines physical fatigue, exertion, short-term recovery, prolonged combat degradation, and the relationship between bodily stamina and combat performance.

It must remain distinct from:
- injury and trauma;
- chakra reserves and chakra exhaustion;
- medical deterioration;
- morale or fear.

A character can therefore be:
- physically fresh but chakra-depleted;
- physically exhausted but uninjured;
- badly injured but not yet exhausted;
- both exhausted and chakra-depleted;
- medically unstable while still possessing substantial physical energy.

## 4.13.1 Physical Fatigue Is a Separate Resource State

Physical fatigue represents the body's reduced ability to sustain continued exertion.

It may result from:
- sprinting;
- prolonged taijutsu;
- repeated jumps;
- climbing;
- carrying weight;
- grappling;
- repeated explosive movements;
- prolonged evasive movement;
- fighting in difficult terrain;
- extended combat without recovery.

Fatigue should not be treated as injury unless the exertion causes actual tissue damage.

## 4.13.2 Do Not Collapse Fatigue Into Chakra

Chakra and physical exertion interact, but they are not the same thing.

Ruleset 3 governs:
- chakra reserves;
- chakra expenditure;
- chakra recovery;
- chakra-control costs;
- chakra exhaustion.

Ruleset 4.13 governs:
- muscular exertion;
- cardiovascular strain;
- physical work capacity;
- short-term fatigue;
- recovery between bursts.

A character may have abundant chakra but be physically exhausted.

## 4.13.3 Do Not Collapse Fatigue Into Endurance

Endurance is a foundational attribute from Ruleset 1.

Fatigue is a temporary state.

Endurance influences:
- how quickly fatigue accumulates;
- how much exertion can be sustained;
- how quickly short-term fatigue clears;
- how well performance is preserved under strain.

High Endurance does not mean fatigue never occurs.

## 4.13.4 Exertion Has Intensity

Physical activity should be classified by relative intensity rather than only duration.

Useful broad categories include:

### Light
Walking, cautious movement, low-effort positioning.

### Moderate
Sustained running, climbing, routine combat movement.

### Heavy
Repeated attacks, fast evasions, grappling, high-speed pursuit.

### Extreme
Maximum sprinting, continuous explosive taijutsu, severe load carrying, fighting at personal physical limits.

Intensity is relative to the character's capability.

## 4.13.5 Exertion Has Duration

The same activity can have very different consequences depending on how long it continues.

Examples:
- five seconds of maximum sprinting;
- one minute of sustained pursuit;
- twenty minutes of continuous combat.

The simulation should consider both:
**intensity × duration**

rather than treating all strenuous actions equally.

## 4.13.6 Burst Capacity and Sustained Capacity Are Different

A character may be excellent at short explosive movement while having only average prolonged endurance.

Likewise, another character may sustain moderate effort for a very long time without having exceptional burst speed.

The system should preserve the distinction between:
- explosive output;
- sustained work capacity.

Speed belongs primarily to Agility and specific skills.
Sustained physical capacity belongs primarily to Endurance.

## 4.13.7 Fatigue Accumulation Is Continuous

Fatigue should accumulate as exertion exceeds recovery.

The engine may use hidden numerical values internally, but the player-facing state should normally remain descriptive.

Fatigue increases faster when:
- effort intensity is high;
- recovery opportunities are denied;
- the character is injured;
- breathing is impaired;
- heat or environment is unfavorable;
- heavy equipment or another person is carried;
- the character is repeatedly forced into explosive movement.

## 4.13.8 Fatigue Can Be Local or Systemic

Some fatigue affects the whole body.

Other fatigue is localized.

Examples:
- forearms tiring from weapon use;
- legs tiring from repeated sprinting;
- hands tiring from extended climbing;
- shoulders tiring from carrying someone.

Localized fatigue may reduce specific actions before overall exhaustion becomes severe.

## 4.13.9 Local Fatigue Is Not Structural Injury

A fatigued muscle may feel weak or shaky without being torn.

The system should distinguish:
- ordinary fatigue;
- strain;
- actual injury.

Continuing through extreme local fatigue may increase injury risk, but fatigue itself is not automatically tissue damage.

## 4.13.10 Oxygen Debt and Recovery

Short periods of extreme exertion may create temporary breathing demand even in an otherwise healthy character.

After an intense burst, a character may need time to:
- restore breathing rhythm;
- clear local fatigue;
- regain fine coordination;
- restore full burst capacity.

This creates natural recovery windows after maximum-effort actions.

## 4.13.11 Recovery Can Occur During Combat

A character may recover some fatigue by:
- reducing movement;
- taking cover;
- switching to lower-intensity actions;
- allowing an ally to take pressure;
- disengaging temporarily;
- controlling breathing.

Recovery does not require combat to end.

This creates tactical value in rotating pressure between teammates.

## 4.13.12 Recovery Is Not Instant

A few seconds may restore some short-term burst capacity.

More serious accumulated fatigue may require:
- minutes;
- extended rest;
- food;
- hydration;
- sleep.

The required recovery depends on the depth and cause of fatigue.

## 4.13.13 Fatigue States

A useful descriptive summary may be:

### Fresh
No meaningful fatigue.

### Warmed / Lightly Taxed
Some exertion has accumulated but performance is essentially normal.

### Winded
Breathing and recovery demands are noticeable; repeated explosive actions become harder to sustain.

### Fatigued
Meaningful reduction in sustained performance, reaction recovery, and repeated high-output actions.

### Exhausted
Major physical degradation; only limited high-intensity action can be maintained.

### Spent
The character cannot continue ordinary high-intensity combat without substantial recovery or severe risk.

These are functional summaries, not HP-like meters.

## 4.13.14 Fatigue States Are Derived

A character should become Fatigued because of accumulated exertion and insufficient recovery.

The label summarizes:
- breathing demand;
- muscular fatigue;
- reduced burst recovery;
- declining sustained capacity.

It should not independently impose unexplained penalties.

## 4.13.15 Performance Degradation Should Be Specific

Fatigue may affect:
- acceleration;
- repeated sprinting;
- recovery between actions;
- reaction speed;
- strike power;
- grip;
- balance;
- fine motor control;
- concentration under exertion.

The exact effect should depend on what is fatigued and how severe it is.

## 4.13.16 Repeated High-Output Actions Become Harder

A character may perform one maximum-effort burst effectively.

Repeating that burst many times without recovery should become progressively harder.

Examples:
- repeated Body Flicker-like physical bursts where technique rules permit;
- continuous high-speed taijutsu;
- repeated maximum jumps;
- repeated heavy weapon swings.

This prevents maximum output from being treated as an indefinitely sustainable default.

## 4.13.17 Maximum Output and Sustainable Output Are Different

Every character should conceptually have:
- a maximum short-term physical output;
- a lower sustainable combat output.

A character can exceed sustainable output temporarily.

Doing so creates faster fatigue accumulation.

This creates meaningful pacing decisions.

## 4.13.18 Fighting Efficiently Saves Energy

Skill and mastery can reduce unnecessary exertion.

An experienced fighter may:
- use smaller evasive movements;
- maintain better posture;
- avoid wasted attacks;
- move along efficient paths;
- use timing instead of raw force.

Therefore, superior combat skill may improve stamina indirectly without increasing Endurance.

## 4.13.19 Poor Technique Wastes Energy

Inexperienced characters may tire faster because they:
- overcommit;
- tense unnecessarily;
- sprint when controlled movement would suffice;
- make inefficient jumps;
- use excessive force;
- recover poorly.

This gives skill progression another meaningful benefit.

## 4.13.20 Injury Increases Fatigue Cost

Injuries may make ordinary actions more physically expensive.

Examples:
- injured leg forces compensation;
- rib injury makes breathing less efficient;
- shoulder injury increases effort during weapon use;
- blood loss reduces sustained capacity.

This does not mean injury and fatigue are the same state.

Injury changes the cost of continuing activity.

## 4.13.21 Blood Loss and Respiratory Injury Accelerate Exhaustion

Reduced circulation or breathing can sharply reduce physical endurance.

A character with:
- significant blood loss;
- impaired lung function;
- airway compromise

may become exhausted much faster than normal.

This connects 4.11 deterioration to 4.13 fatigue.

## 4.13.22 Fatigue Can Increase Injury Risk

As fatigue becomes severe:
- movement becomes less controlled;
- joints stabilize less effectively;
- landings worsen;
- reaction quality declines;
- overextension becomes more likely.

Therefore, pushing hard while exhausted may increase the chance of strains, falls, or aggravated injuries.

Ruleset 2 handles uncertainty where needed.

## 4.13.23 Fatigue Can Affect Precision

Fine motor performance may degrade under severe exertion.

This can affect:
- hand seals;
- precise weapon work;
- medical treatment;
- puppet control;
- delicate tool use.

The severity depends on the character's conditioning, skill, and fatigue state.

## 4.13.24 Fatigue and Hand-Seal Speed

A character may know how to perform hand seals quickly but be less able to maintain peak speed when:
- forearms are exhausted;
- fingers are trembling;
- breathing is uncontrolled;
- injuries interfere.

This should modify effective performance without reducing the underlying learned skill.

## 4.13.25 Fatigue and Tempo

Fatigue can shift combat tempo by:
- lengthening recovery;
- reducing chaining ability;
- making reactions slower;
- reducing pursuit capacity;
- making aggressive pressure harder to maintain.

An initially dominant fighter may lose tempo if they overexert.

## 4.13.26 Fatigue and Movement

Movement degradation may include:
- reduced acceleration;
- lower maximum sustainable speed;
- slower directional changes;
- more frequent recovery needs;
- shorter effective pursuit distance.

Peak speed may remain briefly available even when sustained speed has fallen.

## 4.13.27 Fatigue and Defense

A fatigued defender may still execute a single strong dodge.

The difficulty comes from repeating demanding defenses.

Repeated:
- evasions;
- blocks;
- recoveries;
- rapid repositioning

may eventually exhaust the defender even if they are never struck.

This gives sustained offensive pressure real physical consequence.

## 4.13.28 Fatigue and Grappling

Grappling can be highly exhausting because:
- continuous muscular tension is required;
- leverage changes rapidly;
- both fighters resist movement;
- breathing may be restricted.

A prolonged grapple may fatigue characters faster than brief striking exchanges.

## 4.13.29 Carrying Casualties

Carrying or dragging an injured person increases exertion.

The effect depends on:
- relative body mass;
- carry method;
- terrain;
- speed;
- distance;
- assistance.

This makes casualty extraction physically meaningful.

## 4.13.30 Equipment Load

Heavy equipment may increase fatigue during:
- long movement;
- climbing;
- repeated jumping;
- extended combat.

Routine shinobi equipment should not require constant encumbrance accounting.

Only unusual or significant loads need explicit treatment.

## 4.13.31 Environment Can Alter Fatigue

Relevant environmental factors may include:
- extreme heat;
- extreme cold;
- altitude;
- deep water;
- mud;
- unstable terrain;
- smoke.

The system should model these only when they materially change exertion.

## 4.13.32 Heat Stress and Dehydration

During long missions or extended battles, heat and dehydration may reduce:
- endurance;
- cognition;
- recovery;
- physical coordination.

These should not dominate ordinary short encounters but can matter during prolonged operations.

## 4.13.33 Sleep Deprivation and Prior Exhaustion

A character may enter combat already fatigued because of:
- previous battles;
- long travel;
- lack of sleep;
- training;
- illness;
- prior mission demands.

Combat should inherit existing fatigue state rather than reset everyone to Fresh.

## 4.13.34 Chakra Use Can Indirectly Affect Physical Fatigue

Ruleset 3 governs chakra exhaustion directly.

However, chakra techniques may indirectly affect physical fatigue by:
- amplifying movement;
- requiring strenuous body motion;
- allowing movement that would otherwise require muscular effort;
- creating physiological strain depending on technique.

Technique records should state such interactions.

## 4.13.35 Physical Fatigue Can Affect Chakra Use

Severe physical exhaustion may make chakra techniques harder to execute accurately because of:
- poor concentration;
- trembling;
- breathing difficulty;
- slower seals;
- unstable posture.

The character may still possess ample chakra.

This creates two-way interaction without merging the systems.

## 4.13.36 Restoring Chakra Does Not Automatically Restore Physical Fatigue

A chakra-recovery item or technique should not automatically remove muscular exhaustion unless it explicitly also restores physical condition.

Likewise, resting the body does not necessarily refill chakra at the same rate.

This preserves resource separation.

## 4.13.37 Soldier Pills and Stimulants

Items or techniques may temporarily:
- suppress perceived fatigue;
- increase available output;
- accelerate chakra access;
- extend combat performance.

They should not necessarily erase underlying physical strain.

When the effect ends, consequences may include:
- rebound exhaustion;
- worsened dehydration;
- aggravated injuries;
- metabolic crash.

Specific item rules belong to equipment/consumable systems.

## 4.13.38 Overexertion

A character can intentionally push beyond safe sustainable output.

Overexertion may cause:
- rapid fatigue escalation;
- loss of coordination;
- collapse;
- muscle strain;
- worsening injuries;
- delayed recovery.

This should remain an available choice when stakes justify it.

## 4.13.39 Exhaustion-Related Collapse

A character may become physically unable to continue even without major injury.

Collapse should emerge from extreme fatigue and physiological demand.

It should not be mistaken for death or critical medical trauma unless additional problems exist.

## 4.13.40 Recovery After Collapse

Exhaustion-related incapacity may improve relatively quickly compared with structural injury if:
- the character rests;
- breathing normalizes;
- hydration and nutrition are adequate;
- no serious medical condition exists.

The exact recovery time depends on exertion depth and prior condition.

## 4.13.41 Long-Duration Missions

Outside direct combat, fatigue should accumulate from:
- forced marches;
- repeated engagements;
- inadequate sleep;
- carrying supplies or casualties;
- difficult terrain.

This allows mission endurance to matter without requiring every minute to be simulated.

## 4.13.42 Fatigue Compression

For low-detail simulation, the engine may summarize:
- fresh;
- lightly taxed;
- fatigued;
- exhausted.

If fatigue begins affecting a critical combat decision, the system can expand the underlying causes.

## 4.13.43 Hidden Numerical Model Is Allowed

The engine may internally track:
- exertion load;
- recovery rate;
- local muscle fatigue;
- systemic fatigue;
- burst reserve.

These do not need to be player-facing.

Their purpose is to keep repeated activity consistent.

## 4.13.44 Suggested Fatigue Pipeline

For relevant exertion:

1. Determine activity intensity relative to the character.
2. Determine duration.
3. Apply Endurance and conditioning.
4. Apply efficiency from skill/mastery.
5. Apply injury, environment, load, and breathing/circulatory modifiers.
6. Accumulate local and/or systemic fatigue.
7. Apply ongoing recovery if intensity is low enough.
8. Update functional consequences.
9. Update descriptive fatigue state.
10. Feed meaningful limitations into combat capacity and timing.

## 4.13.45 Minimum Fatigue State

When fatigue matters, the engine should be able to represent:
- current systemic fatigue;
- relevant local fatigue;
- recent high-intensity exertion;
- recovery status;
- current sustainable output;
- temporary burst capacity;
- relevant environmental or injury-related modifiers.

## Core Design Rule

Physical fatigue should answer:

**How much demanding physical work has this character performed, how well can their body recover from it, and what actions can they still sustain efficiently?**

It should not answer:
**How injured are they?**
or:
**How much chakra do they have left?**

Those remain separate systems.
