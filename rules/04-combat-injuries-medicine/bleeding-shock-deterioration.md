# 4.11 — Bleeding, Shock & Deterioration

Status: Provisional design section pending explicit approval.

This section defines how injuries can worsen over time after the initial trauma has already occurred.

Ruleset 4.10 records the injury.
Ruleset 4.11 determines whether that injury remains stable, deteriorates, causes systemic failure, or improves after stabilization.

The deterioration system should answer:

**What is getting worse, why is it getting worse, how quickly is it progressing, what signs are visible, and what can stop or slow it?**

## 4.11.1 Deterioration Is Cause-Based

Characters should not lose health every interval simply because they are injured.

Ongoing decline should come from identifiable processes such as:
- external bleeding;
- internal bleeding;
- impaired breathing;
- circulatory failure;
- worsening swelling;
- progressive neurological injury;
- burns;
- toxins;
- untreated crush injury;
- infection;
- technique-specific ongoing effects.

The simulation should preserve the actual cause of deterioration.

## 4.11.2 Stable Versus Unstable Injury

A meaningful injury should be classifiable as:

### Stable
The injury is not currently expected to worsen rapidly without new stress.

### Potentially Unstable
The injury may worsen with exertion, time, movement, or inadequate treatment.

### Unstable
The injury is actively worsening or creating ongoing systemic harm.

### Rapidly Deteriorating
The injury is creating immediate escalating danger and requires urgent intervention.

These are medical-state descriptors, not injury severity grades.

## 4.11.3 Deterioration Uses Time, Not Turns

Bleeding, shock, respiratory failure, and similar processes should progress according to elapsed time.

Combat turns or action windows may be used to approximate elapsed time during detailed combat, but the underlying model is time-based.

This allows deterioration to continue:
- during combat;
- while traveling;
- during pursuit;
- during treatment;
- after combat;
- through time skips.

## 4.11.4 External Bleeding

External bleeding occurs when blood escapes through an open wound.

Relevant factors include:
- vessel size and type;
- wound depth;
- wound location;
- pressure;
- movement;
- clotting;
- existing treatment;
- blood pressure;
- repeated trauma.

External bleeding may be:
- trivial;
- mild;
- moderate;
- severe;
- massive.

The visible amount of blood may help estimate severity but should not perfectly reveal total blood loss.

## 4.11.5 Internal Bleeding

Internal bleeding occurs when blood accumulates inside the body or tissue.

It may result from:
- organ injury;
- vascular injury;
- fracture;
- blunt trauma;
- penetrating trauma.

Internal bleeding is especially dangerous because:
- it may not be visible;
- symptoms can appear gradually;
- the injured character may underestimate severity;
- first aid options may be limited.

## 4.11.6 Bleeding Rate and Total Blood Loss Are Separate

The engine should distinguish:
- current bleeding rate;
- total accumulated blood loss.

A wound can bleed rapidly and then be controlled.

A slow internal bleed may become dangerous because it continues for a long time.

This avoids treating all bleeding as one static severity.

## 4.11.7 Bleeding Can Change Over Time

Bleeding may:
- slow naturally;
- stop through clotting;
- restart with movement;
- worsen after reinjury;
- increase when a temporary clot breaks;
- be reduced by pressure, packing, sealing, or medical ninjutsu.

The system should update bleeding state when circumstances change.

## 4.11.8 Movement Can Worsen Bleeding

High exertion, repeated movement, or use of an injured body region may:
- increase blood flow;
- disrupt clotting;
- reopen wounds;
- aggravate vessel injury.

This creates a meaningful tradeoff between continuing the mission and preserving medical stability.

## 4.11.9 Blood Loss Affects Function Gradually

As blood loss increases, likely functional consequences include:
- reduced endurance;
- weakness;
- dizziness;
- slower reactions;
- impaired concentration;
- pale or cold skin;
- rapid breathing;
- loss of coordination;
- collapse;
- unconsciousness.

Exact presentation depends on severity and physiology.

The simulation should not wait for a binary "bleed out" state before applying consequences.

## 4.11.10 Physiological Shock

Physiological shock represents inadequate tissue perfusion or systemic circulatory failure.

Possible causes include:
- major blood loss;
- severe burns;
- overwhelming trauma;
- other serious systemic injury.

Shock can reduce:
- cognition;
- strength;
- coordination;
- temperature regulation;
- consciousness.

Detailed progression should remain abstract enough for playability while preserving urgency.

## 4.11.11 Shock Severity

A practical hidden progression may be:

### Compensated
The body is maintaining function despite significant stress.

### Early Decompensation
Weakness, confusion, reduced performance, and instability begin to emerge.

### Severe Decompensation
Circulation is failing to sustain normal function.

### Collapse
Consciousness and effective circulation are critically compromised.

These are implementation descriptors, not mandatory player-facing labels.

## 4.11.12 Compensation Can Hide Danger

A trained shinobi may initially appear functional despite serious blood loss or trauma.

Stress response, conditioning, and determination may temporarily preserve performance.

This does not mean the injury is stable.

A character may therefore deteriorate suddenly after:
- the fight ends;
- exertion stops;
- blood loss crosses a threshold;
- compensatory mechanisms fail.

## 4.11.13 Shock and Willpower

Willpower may help a character remain focused or continue acting despite distress.

It cannot maintain blood pressure, restore circulating volume, or reverse organ failure by itself.

This preserves the distinction between mental persistence and physiology.

## 4.11.14 Respiratory Deterioration

Breathing may worsen because of:
- airway swelling;
- smoke inhalation;
- chest trauma;
- lung injury;
- blood in the airway;
- drowning;
- compression;
- progressive fatigue.

Respiratory decline can produce:
- shortness of breath;
- reduced endurance;
- panic or distress;
- impaired concentration;
- bluish discoloration where applicable;
- confusion;
- loss of consciousness.

## 4.11.15 Airway Compromise

Airway problems may be:
- partial;
- worsening;
- complete.

Examples:
- swelling;
- foreign body;
- neck trauma;
- blood;
- inhalation injury;
- strangulation.

Airway compromise may deteriorate rapidly and should be treated as high urgency.

## 4.11.16 Lung and Chest Deterioration

Chest injuries may worsen breathing over time through:
- accumulating air or blood;
- increasing pain;
- swelling;
- fatigue;
- reduced lung expansion.

A character may therefore initially continue fighting before becoming progressively short of breath.

## 4.11.17 Neurological Deterioration

Head injuries may produce delayed worsening.

Possible signs include:
- increasing headache;
- confusion;
- worsening balance;
- vomiting;
- unequal pupils;
- reduced responsiveness;
- seizures;
- loss of consciousness.

The simulation should avoid revealing exact pathology unless assessment supports it.

## 4.11.18 Swelling and Compartment Effects

Some injuries may worsen as swelling increases.

Examples:
- limb trauma;
- crush injury;
- burns;
- head injury.

Swelling may:
- reduce circulation;
- compress nerves;
- increase pain;
- worsen function.

Detailed compartment-pressure simulation is unnecessary unless the injury becomes important.

## 4.11.19 Burns Can Deteriorate Systemically

Large or deep burns may cause:
- fluid loss;
- temperature regulation problems;
- shock;
- infection risk;
- airway swelling if inhalation injury is present.

Burn severity therefore may increase medical danger after the initial attack is over.

## 4.11.20 Crush Injury Can Have Delayed Consequences

Severe prolonged compression may create:
- tissue damage;
- impaired circulation;
- swelling;
- systemic complications after release.

This should be modeled only for significant crush events.

## 4.11.21 Toxins and Ongoing Technique Effects

Poisons, toxins, seals, curses, or persistent chakra effects may create their own deterioration curves.

Ruleset 4.11 provides the general time-based deterioration framework.
The exact progression belongs to the relevant poison, jutsu, or special-ability record.

## 4.11.22 Deterioration Should Use Meaningful Checkpoints

The engine should not require constant second-by-second recalculation.

State should update when:
- enough time passes;
- symptoms cross a meaningful threshold;
- exertion changes;
- treatment occurs;
- the injury is aggravated;
- the character rests;
- the environment changes.

This keeps the system playable.

## 4.11.23 Deterioration Rate

A condition may worsen at a broad rate such as:
- negligible;
- slow;
- moderate;
- rapid;
- immediate/critical.

These rates are descriptive and may correspond to hidden internal timing ranges.

The rate can change as treatment or circumstances change.

## 4.11.24 Stabilization

Stabilization means stopping or slowing the dangerous ongoing process.

Examples:
- controlling hemorrhage;
- opening an airway;
- supporting breathing;
- immobilizing a fracture;
- reducing movement;
- suppressing toxin progression;
- relieving a dangerous pressure condition where medically possible.

Stabilization does not heal the underlying injury.

## 4.11.25 Temporary Stabilization

Some interventions only buy time.

Examples:
- direct pressure controlling bleeding;
- improvised splinting;
- maintaining an airway manually;
- chakra suppression slowing toxin spread.

If the intervention stops, deterioration may resume.

The system should record whether stabilization is:
- temporary;
- conditional;
- durable.

## 4.11.26 Definitive Stabilization

Some treatment may reduce immediate deterioration enough that the injury becomes medically stable.

Examples:
- repaired vessel;
- sealed internal bleeding;
- surgically controlled wound;
- successfully treated airway injury.

The injury may remain serious while no longer actively worsening.

## 4.11.27 Stabilization Windows

Certain injuries create a practical rescue window.

A character may survive if treatment occurs before:
- blood loss becomes irreversible;
- airway compromise becomes complete;
- neurological deterioration becomes catastrophic;
- toxin concentration crosses a critical threshold.

The window should emerge from the injury and deterioration rate rather than a universal countdown timer.

## 4.11.28 Rescue Windows May Be Uncertain

Characters may not know exactly how much time remains.

They may instead observe:
- worsening pulse;
- reduced responsiveness;
- increasing respiratory distress;
- expanding bleeding;
- deteriorating coordination.

This preserves uncertainty and makes medical assessment valuable.

## 4.11.29 Deterioration Can Continue During Treatment

Treatment takes time.

While a medic is working:
- bleeding may continue;
- breathing may worsen;
- shock may deepen;
- toxins may progress.

The treatment action must therefore compete against the deterioration rate.

This creates genuine urgency.

## 4.11.30 Treatment Priority

When multiple dangerous processes are present, treatment should prioritize the most immediate threat.

Examples:
- airway before limb fracture;
- catastrophic bleeding before minor burns;
- severe respiratory compromise before cosmetic wound closure.

Detailed triage belongs to later medical sections, but 4.11 establishes why prioritization matters.

## 4.11.31 Multiple Deteriorating Injuries Can Interact

Several injuries may combine.

Examples:
- bleeding plus chest injury;
- burns plus dehydration;
- head injury plus low blood pressure;
- poison plus respiratory damage.

The system should recognize systemic interaction without simply adding severity points.

## 4.11.32 Secondary Collapse

A character may remain combat-capable until several processes combine.

Example:
- moderate blood loss;
- fatigue;
- heat exposure;
- chest pain.

Individually manageable factors may together push the character into collapse.

This should emerge from functional state, not a scripted threshold detached from cause.

## 4.11.33 Rest Can Slow Some Deterioration

Stopping exertion may:
- reduce bleeding;
- lower oxygen demand;
- improve short-term recovery;
- reduce aggravation risk.

Rest does not solve:
- severe internal bleeding;
- airway obstruction;
- major organ injury;
- progressive toxin effects.

## 4.11.34 Position Can Matter Medically

Body position may affect:
- breathing;
- bleeding control;
- aspiration risk;
- transport safety.

The system should only track this when medically meaningful.

## 4.11.35 Transport Can Worsen Injuries

Moving an injured person may:
- restart bleeding;
- worsen fractures;
- aggravate spinal injury;
- impair breathing;
- increase pain.

Transport method and stabilization therefore matter.

Detailed evacuation rules belong to later medical sections.

## 4.11.36 Unconsciousness From Deterioration

A character may lose consciousness when:
- brain perfusion becomes inadequate;
- oxygen falls too low;
- neurological injury progresses;
- toxin effects deepen.

Loss of consciousness should have a physiological cause.

## 4.11.37 Near-Death State

A near-death condition exists when vital function is failing but rescue may still be possible.

Possible characteristics:
- profound unconsciousness;
- severely impaired circulation;
- critically poor breathing;
- catastrophic bleeding;
- rapidly failing neurological function.

Detailed death thresholds belong to 4.12.

## 4.11.38 No Universal Bleed-Out Timer

There should be no rule such as:
"All bleeding characters die in 5 rounds."

Survival time depends on:
- bleeding rate;
- injury location;
- total blood loss;
- physiology;
- treatment;
- exertion;
- concurrent injuries.

## 4.11.39 No Automatic Death From a Single Status Label

"Critical" or "rapidly deteriorating" should not itself cause death.

Death should follow actual failure of vital systems, as developed in 4.12.

## 4.11.40 Hidden Medical State

The engine may track:
- exact blood-loss trend;
- internal bleeding;
- oxygenation decline;
- shock progression;
- hidden swelling;
- toxin burden.

The injured character may only perceive symptoms.

A medic may uncover more through assessment.

## 4.11.41 Observable Deterioration

Possible visible signs include:
- increasing pallor;
- slower responses;
- confusion;
- heavy breathing;
- worsening bleeding;
- inability to stand;
- trembling;
- collapse.

The simulation should reveal signs appropriate to the observer's knowledge.

## 4.11.42 Deterioration Record

A meaningful ongoing process should be able to store:
- cause;
- current severity;
- progression rate;
- current functional effects;
- current medical urgency;
- whether it is visible or hidden;
- stabilization status;
- what conditions worsen or improve it;
- next meaningful progression threshold.

## 4.11.43 Suggested Deterioration Pipeline

1. Read active injuries and ongoing effects.
2. Identify unstable processes.
3. Determine current progression rate.
4. Account for exertion, movement, environment, physiology, and treatment.
5. Advance elapsed time.
6. Update blood loss, breathing, neurological state, toxin burden, or other relevant process.
7. Apply new functional consequences through 4.9.
8. Update medical urgency and stability.
9. Reveal appropriate symptoms.
10. Check whether treatment, stabilization, near-death state, or death thresholds have been reached.

## 4.11.44 Compression

For low-detail simulation, deterioration may be summarized as:
- stable;
- slowly worsening;
- rapidly worsening;
- stabilized.

If the character approaches collapse, death, or a major treatment decision, the system should zoom in.

## Core Design Rule

Deterioration should be an evolving consequence of a specific ongoing medical process.

The simulation should always be able to answer:

**What is worsening? Why? How quickly? What signs are appearing? What will stop or slow it?**
