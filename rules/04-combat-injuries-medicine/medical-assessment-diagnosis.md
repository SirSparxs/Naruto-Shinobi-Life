# 4.18 — Medical Assessment & Diagnosis

Status: Provisional design section pending explicit approval.

This section defines how characters discover, interpret, and communicate injuries and medical danger.

The simulation may know the true internal state of a patient.
Characters should only know what they can reasonably observe, examine, sense, infer, or diagnose.

Medical assessment should therefore bridge:
- hidden injury state;
- observable symptoms;
- medical knowledge;
- diagnostic tools and ninjutsu;
- uncertainty;
- treatment decisions.

## 4.18.1 Medical Truth and Character Knowledge Are Separate

The engine may know:
- exact injury;
- internal bleeding;
- damaged organ;
- fracture type;
- toxin;
- chakra-network injury;
- deterioration rate.

The patient or observer may know far less.

A character should never automatically receive the engine's complete medical record.

## 4.18.2 Assessment Is an Information Process

Medical assessment does not heal the patient.

It attempts to determine:
- what is injured;
- how severe it is;
- what is immediately dangerous;
- whether the condition is stable;
- what treatment is needed;
- what additional information remains uncertain.

Ruleset 2 resolves uncertainty in observation, examination, and diagnosis.

## 4.18.3 Assessment Depth Should Scale With Need

A useful assessment spectrum may include:

### Glance
Very quick visual impression.

### Rapid Combat Assessment
A short assessment under pressure to identify immediate threats.

### Focused Examination
Closer examination of one injury or symptom.

### Full Medical Examination
Systematic assessment of the patient.

### Diagnostic Technique / Advanced Testing
Specialized medical ninjutsu, tools, imaging-equivalent methods, laboratory methods, or specialist evaluation.

The system should only use the depth required by the situation.

## 4.18.4 Glance-Level Information

A glance may reveal:
- visible bleeding;
- obvious deformity;
- unconsciousness;
- severe burns;
- missing limb;
- obvious breathing difficulty;
- inability to stand;
- visible foreign object.

It should not reliably reveal hidden internal injury.

## 4.18.5 Rapid Combat Assessment

Under combat conditions, a medic may prioritize:
- catastrophic bleeding;
- airway problem;
- breathing impairment;
- consciousness;
- severe shock signs;
- immediate mobility needs.

The purpose is:
**What will kill or disable this person first?**

It is not a complete diagnosis.

## 4.18.6 Focused Examination

A focused exam may inspect:
- one limb;
- one wound;
- breathing;
- neurological symptoms;
- suspected fracture;
- suspected poison;
- chakra-flow abnormality.

It can provide much better information than a glance while remaining faster than a full examination.

## 4.18.7 Full Medical Examination

A complete exam may evaluate:
- vital signs;
- neurological status;
- circulation;
- breathing;
- wounds;
- bones/joints;
- pain;
- hidden bleeding signs;
- sensory function;
- chakra system where relevant.

This should require time and a reasonably safe environment.

## 4.18.8 Medical Skill Affects Interpretation

Two observers can see the same signs and reach different conclusions.

Medical expertise affects:
- recognition;
- prioritization;
- differential diagnosis;
- treatment planning;
- certainty.

A civilian may notice:
“She looks pale and weak.”

A trained medic may infer:
“Possible significant blood loss and early shock.”

## 4.18.9 Perception Still Matters

Medical knowledge cannot interpret signs that were never noticed.

Assessment can depend on:
- Perception;
- lighting;
- concealment;
- patient position;
- battlefield pressure;
- equipment;
- sensory abilities.

Ruleset 2 should combine observation and expertise appropriately.

## 4.18.10 Intelligence and Medical Knowledge

Intelligence can support:
- pattern recognition;
- remembering medical information;
- integrating symptoms;
- forming hypotheses.

However, Intelligence alone does not grant medical training.

A brilliant untrained character should not automatically diagnose rare internal injuries.

## 4.18.11 Medical Skills Should Be Distinct From General Intelligence

Relevant medical skills may eventually include:
- first aid;
- anatomy;
- diagnosis;
- medical ninjutsu;
- surgery;
- toxicology;
- pharmacology;
- field medicine.

The exact skill structure belongs to Ruleset 1 or later medical implementation.

Ruleset 4.18 defines what those skills are used to discover.

## 4.18.12 Observable Signs

Medical signs may include:
- visible wounds;
- bleeding;
- swelling;
- deformity;
- skin color;
- breathing pattern;
- pupil response;
- tremor;
- confusion;
- weakness;
- pain response;
- pulse;
- temperature;
- chakra irregularity.

The engine should reveal only signs the observer can perceive.

## 4.18.13 Symptoms Are Patient-Reported Information

A conscious patient may report:
- pain;
- numbness;
- dizziness;
- nausea;
- shortness of breath;
- weakness;
- visual disturbance;
- loss of sensation;
- abnormal chakra sensation.

Patient reports can be useful but imperfect.

## 4.18.14 Patients May Be Unreliable Sources

A patient may:
- misunderstand symptoms;
- minimize injury;
- exaggerate pain;
- be confused;
- be unconscious;
- conceal information;
- have impaired sensation.

Medical assessment should not assume self-report is always accurate.

## 4.18.15 Pain Location Does Not Always Equal Injury Location

Pain may:
- radiate;
- be referred;
- be absent despite injury;
- be masked by adrenaline;
- be reduced by numbness.

A medic should not automatically equate “where it hurts” with the exact damaged structure.

## 4.18.16 Visible Wound Does Not Equal Full Injury

A stab wound may reveal an entry point without revealing:
- depth;
- organ involvement;
- internal bleeding;
- retained object.

The assessment system should preserve that uncertainty.

## 4.18.17 Hidden Injury

Some conditions may require inference or diagnostic techniques.

Examples:
- internal bleeding;
- organ trauma;
- concussion;
- nerve injury;
- early toxin effects;
- chakra-pathway damage;
- small fracture.

The engine can keep these hidden until discovered.

## 4.18.18 Diagnostic Confidence

A diagnosis should have a confidence level when uncertainty remains.

Useful broad categories may include:
- suspected;
- likely;
- confirmed.

A medic may also explicitly record:
- ruled out;
- unresolved.

This is preferable to pretending every examination provides certainty.

## 4.18.19 Differential Diagnosis

When several explanations fit the available evidence, the medic may maintain multiple possibilities.

Example:
- weakness and dizziness could result from blood loss;
- toxin;
- heat exhaustion;
- neurological injury.

Further examination or testing narrows the possibilities.

## 4.18.20 Ruleset 2 Resolves Diagnostic Uncertainty

Diagnosis should not create a separate probability engine.

Ruleset 2 receives:
- medical skill;
- symptom visibility;
- examination quality;
- time;
- equipment;
- rarity;
- complexity;
- interference.

Ruleset 4 records the resulting information.

## 4.18.21 Poor Assessment Can Miss Injury

A failed assessment may result in:
- overlooked wound;
- underestimated bleeding;
- missed fracture;
- unrecognized internal injury;
- failure to notice deterioration.

Failure should remain constrained by what was difficult to detect.

## 4.18.22 Misdiagnosis Is Possible

In some cases, poor evidence or incorrect interpretation may produce a wrong conclusion.

Misdiagnosis should be more likely when:
- symptoms overlap;
- injury is hidden;
- examiner lacks training;
- time is limited;
- conditions are chaotic;
- rare disorders are involved.

It should not occur randomly when the evidence is obvious.

## 4.18.23 Uncertainty Is Often Better Than False Certainty

A competent medic should sometimes conclude:
“I cannot determine the exact internal injury here.”

That is better than forcing an incorrect precise diagnosis.

The system should allow:
- unknown;
- suspected;
- uncertain.

## 4.18.24 Reassessment Matters

Medical state can change.

A patient assessed as stable may later develop:
- worsening bleeding;
- neurological symptoms;
- respiratory distress;
- toxin effects.

Reassessment can detect this change.

## 4.18.25 Monitoring

A medic may monitor:
- consciousness;
- breathing;
- pulse/circulation;
- bleeding;
- neurological signs;
- pain;
- chakra stability.

Monitoring can reveal deterioration earlier.

## 4.18.26 Medical Triage

When several casualties exist, assessment must prioritize who needs attention first.

Triage should consider:
- immediate threat to life;
- rate of deterioration;
- treatment responsiveness;
- resources;
- battlefield safety.

Detailed triage procedure belongs later, but diagnosis supplies the information needed.

## 4.18.27 Battlefield Conditions Reduce Assessment Quality

Assessment may be harder because of:
- darkness;
- smoke;
- rain;
- enemy fire;
- loud explosions;
- moving patient;
- lack of time;
- lack of tools.

This should create real information constraints.

## 4.18.28 Treating Without Full Diagnosis

A medic may begin treatment before knowing the exact diagnosis.

Examples:
- control visible catastrophic bleeding;
- protect airway;
- immobilize an obviously unstable limb;
- remove ongoing exposure.

Immediate lifesaving treatment may take priority over diagnostic precision.

## 4.18.29 Assessment Can Reveal Treatment Contraindications

Diagnosis may identify that a seemingly helpful action would be dangerous.

Examples:
- moving a patient may worsen instability;
- removing an embedded object may increase bleeding;
- certain medication may conflict with poison or physiology;
- aggressive exertion may worsen internal injury.

Knowledge changes available safe choices.

## 4.18.30 Diagnostic Ninjutsu

Medical ninjutsu may allow a user to sense or inspect:
- internal tissue;
- blood flow;
- chakra pathways;
- organ condition;
- foreign material;
- toxin effects.

The exact capability belongs to the technique record.

Ruleset 4.18 determines what medical information the technique reveals.

## 4.18.31 Diagnostic Ninjutsu Has Resolution Limits

A diagnostic technique should define:
- range;
- contact requirements;
- chakra cost;
- time;
- anatomical resolution;
- conditions it can detect;
- conditions it cannot detect.

No generic medical scan should reveal everything unless a specific technique explicitly has that capability.

## 4.18.32 Chakra Sensing Is Not Automatically Medical Diagnosis

General chakra sensing may detect:
- unusual flow;
- weak chakra signature;
- disruption.

It does not automatically reveal:
- torn tendon;
- internal bleeding;
- exact organ injury.

Medical interpretation requires relevant skill or specialized technique.

## 4.18.33 Dōjutsu and Sensory Abilities

Certain dōjutsu or sensory abilities may provide extraordinary diagnostic information.

Their ability records must specify:
- what structures can be perceived;
- accuracy;
- limitations;
- whether medical knowledge is required to interpret the image.

Seeing more information does not guarantee understanding it.

## 4.18.34 Equipment-Assisted Diagnosis

Tools may assist assessment through:
- magnification;
- measurement;
- sampling;
- monitoring;
- specialized medical devices.

Equipment improves information access but does not replace knowledge.

## 4.18.35 Poison Identification

Toxin diagnosis may rely on:
- symptoms;
- wound type;
- residue;
- known enemy tactics;
- laboratory testing;
- medical ninjutsu.

The medic may identify:
- toxin class;
- likely effects;
- exact toxin;
- antidote compatibility.

Detailed poison rules belong to 4.23.

## 4.18.36 Chakra-Network Diagnosis

Medical assessment may identify:
- blocked tenketsu;
- disrupted pathways;
- abnormal circulation;
- damaged chakra structures.

This may require specialized medical or chakra-control expertise.

## 4.18.37 Injury History Matters

Diagnosis should consider:
- previous injuries;
- surgeries;
- chronic conditions;
- prosthetics;
- known physiology;
- recent treatment.

A symptom may mean something different in a previously injured body region.

## 4.18.38 Known Exceptional Physiology

If the medic knows the patient has:
- regeneration;
- unusual bloodline anatomy;
- implanted tissue;
- jinchūriki physiology;
- modified organs,

assessment can incorporate that knowledge.

Unknown physiology may lead to uncertainty or mistaken assumptions.

## 4.18.39 Medical Records

If available, records may provide:
- blood type;
- prior injuries;
- allergies;
- chronic conditions;
- implants;
- known reactions;
- baseline chakra or physiology.

The world-system details of records belong elsewhere.

## 4.18.40 Communication of Medical Findings

A medic should be able to communicate findings at an appropriate level.

Examples:
- “Bleeding is controlled. He is stable for transport.”
- “Likely internal bleeding. We need advanced care immediately.”
- “Her right hand is structurally intact, but chakra flow is severely disrupted.”

This translates hidden mechanics into actionable information.

## 4.18.41 Non-Medic Information Should Be Less Precise

An untrained teammate may receive:
- obvious symptoms;
- broad danger cues.

They should not receive:
“Grade III splenic laceration”
unless they possess relevant knowledge.

## 4.18.42 Patient Knowledge

The patient has privileged access to subjective symptoms but not necessarily internal diagnosis.

They may know:
- severe pain;
- numbness;
- loss of control;
- difficulty breathing.

They may not know why.

## 4.18.43 Diagnostic Failure Should Affect Decisions, Not Rewrite Truth

If a medic misses internal bleeding, the internal bleeding still exists.

The engine does not alter the patient's true condition to match the diagnosis.

This is essential.

## 4.18.44 Treatment Can Provide New Diagnostic Information

During treatment, a medic may discover:
- deeper wound path;
- damaged vessel;
- retained fragment;
- unexpected tissue injury;
- toxin characteristics.

Diagnosis can therefore improve while care is underway.

## 4.18.45 Autopsy / Postmortem Examination

After death, medical examination may determine:
- cause of death;
- wound sequence;
- toxin involvement;
- hidden injuries;
- approximate mechanism.

This can support investigations and world simulation.

Detailed forensic systems can remain lightweight unless relevant.

## 4.18.46 Diagnosis Record

A meaningful assessment should be able to store:
- observer/examiner;
- time;
- assessment depth;
- observed signs;
- reported symptoms;
- suspected injuries;
- confirmed injuries;
- ruled-out possibilities;
- diagnostic confidence;
- known urgency;
- treatment recommendations;
- remaining uncertainty.

## 4.18.47 Observer-Specific Medical Knowledge

Different observers may hold different medical beliefs about the same patient.

Example:

**Engine Truth**
- internal abdominal bleeding.

**Patient**
- severe abdominal pain and dizziness.

**Teammate**
- thinks patient is exhausted.

**Medic**
- suspects internal bleeding.

**Hospital Specialist**
- confirms liver injury.

All can coexist.

## 4.18.48 Suggested Assessment Pipeline

1. Determine assessment depth.
2. Determine what signs are physically observable.
3. Apply observer perception.
4. Apply patient-reported symptoms where available.
5. Apply medical knowledge and skill.
6. Apply equipment or diagnostic techniques.
7. Ruleset 2 resolves remaining uncertainty.
8. Generate suspected/likely/confirmed findings.
9. Determine known urgency and treatment priorities.
10. Store observer-specific medical knowledge.
11. Reassess later if state changes or more information becomes available.

## 4.18.49 Compression

For routine injuries, assessment may be summarized.

Examples:
- superficial cut, no major concern;
- obvious ankle sprain;
- severe bleeding requiring immediate control.

The system should zoom in when:
- hidden injury is plausible;
- treatment choice depends on diagnosis;
- deterioration is unexplained;
- specialized medical care is required.

## Core Design Rule

Medical diagnosis should reveal the body's hidden state **only to the degree justified by observation, skill, time, tools, and diagnostic techniques**.

The simulation knows the truth.
Characters must discover it.
