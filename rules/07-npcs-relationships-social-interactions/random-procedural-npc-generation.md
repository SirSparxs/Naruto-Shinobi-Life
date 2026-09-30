# 7.40 — Random & Procedural NPC Generation

Status: Provisional design section pending explicit approval.

Ruleset 7.40 defines how original NPCs are procedurally generated so that their statistics, skills, personality, history, relationships, motives, routines, and social behavior feel causally connected rather than randomly assembled.

The governing principle is:

**Procedural NPCs should be generated from plausible lives, roles, environments, and histories, with randomness creating variation inside causal constraints rather than replacing causality.**

## 7.40.1 Scope

This section governs procedural generation of:
- identity;
- age;
- origin;
- occupation or shinobi role;
- attributes;
- social skills;
- personality;
- values;
- goals;
- relationships;
- routines;
- reputation;
- knowledge;
- secrets;
- romantic baseline;
- adult sexual baseline where relevant;
- major history;
- current pressures.

Ruleset 1 owns mechanical attribute, skill, mastery, and progression validity.

## 7.40.2 Generate Cause Before Detail

The engine should generally generate:

1. life context;
2. role;
3. age and experience;
4. formative history;
5. personality and values;
6. competencies;
7. relationships;
8. current goals;
9. current circumstances;
10. surface details.

Avoid starting with disconnected random statistics and inventing explanations afterward unless necessary.

## 7.40.3 NPC Tier Determines Generation Depth

### Major NPC
Generate:
- detailed identity;
- meaningful history;
- full important relationships;
- goals;
- secrets;
- routines;
- skill rationale;
- social baseline.

### Supporting NPC
Generate:
- strong role identity;
- core personality;
- several important relationships;
- relevant skills;
- current goals.

### Persistent Minor NPC
Generate:
- role;
- simple personality;
- limited relationships;
- relevant competencies;
- routine.

### Background NPC
Generate only what current context requires.

Depth can expand later under Ruleset 7.35.

## 7.40.4 Role First

An NPC's role should strongly constrain plausible generation.

Examples:
- academy instructor;
- genin;
- jonin;
- medic;
- merchant;
- clan elder;
- farmer;
- missing-nin;
- innkeeper;
- messenger;
- bureaucrat.

Role influences:
- routine;
- skills;
- social network;
- income/status;
- knowledge;
- likely goals;
- risks.

## 7.40.5 Age Matters

Age should influence plausible:
- experience;
- rank;
- skill history;
- family status;
- responsibilities;
- worldview.

Age should not mechanically determine personality.

Young characters can be highly capable in narrow areas.
Older characters are not automatically experts.

## 7.40.6 Rank and Experience

Shinobi rank should imply broad expectations, not exact stat templates.

A jonin usually has:
- meaningful field experience;
- substantial combat competence;
- broader responsibility.

But variation remains possible.

Unusual rank/ability combinations require explanation.

## 7.40.7 Attribute Generation

Attributes should reflect:
- age;
- biology;
- training;
- profession;
- history;
- individual potential.

Ruleset 1 validates final values.

Avoid evenly random distributions.

A sedentary administrator and active taijutsu specialist should not be generated from identical attribute assumptions.

## 7.40.8 Skill Generation

Skills should arise from:
- training;
- occupation;
- hobbies;
- responsibilities;
- repeated experience;
- mentorship.

High skill should have a plausible developmental history.

## 7.40.9 Skill Clusters

Related life histories may create coherent skill clusters.

Example:
An experienced squad leader may plausibly have:
- Leadership;
- Insight;
- Teaching;
- tactical knowledge.

But clusters should not make every adjacent skill automatically high.

## 7.40.10 Avoid Omni-Competence

Generated NPCs should normally have:
- strengths;
- ordinary areas;
- weaknesses;
- unfamiliar domains.

Important NPC does not mean exceptional at everything.

## 7.40.11 Exceptional NPCs Need Explanation

Rare exceptional ability may come from:
- unusual training;
- prodigious potential;
- extreme experience;
- specialist upbringing;
- rare opportunity.

Do not assign exceptional mastery merely to make an NPC memorable.

## 7.40.12 Personality Structure

Generate personality from several interacting tendencies rather than one trope.

Possible dimensions include:
- sociability;
- patience;
- impulsiveness;
- openness;
- confidence;
- emotional expressiveness;
- conscientiousness;
- competitiveness;
- risk tolerance.

These should influence behavior without becoming deterministic.

## 7.40.13 Contradictory Traits

NPCs may contain plausible contradictions.

Examples:
- confident professionally, shy romantically;
- generous with friends, stingy with money;
- brave in combat, afraid of abandonment.

This is desirable when grounded in context.

## 7.40.14 Values

Important values may include:
- family;
- village;
- honor;
- autonomy;
- ambition;
- compassion;
- tradition;
- wealth;
- justice;
- loyalty;
- knowledge.

Values should help explain decisions and boundaries.

## 7.40.15 Value Priority

Not every value matters equally.

Generate a small number of especially important values rather than every possible principle.

Conflicting values create richer decisions.

## 7.40.16 Goals

NPCs should usually possess:
- immediate goal;
- medium-term goal;
- long-term aspiration where relevant.

Examples:
- pay debt;
- pass exam;
- protect sibling;
- become jonin;
- leave village;
- open business.

Goals should arise from life circumstances.

## 7.40.17 Needs and Pressures

Generate current pressures such as:
- money;
- family obligation;
- injury;
- loneliness;
- career stress;
- political danger;
- rivalry.

Most NPCs do not need dramatic crises.

## 7.40.18 Formative Events

Major NPCs may have a few formative events.

Examples:
- lost teammate;
- successful apprenticeship;
- clan conflict;
- migration;
- failed promotion;
- major rescue.

Avoid overloading every NPC with tragedy.

## 7.40.19 Ordinary Histories Are Valid

Many NPCs should have mostly ordinary lives.

Examples:
- stable family;
- uneventful academy years;
- modest career;
- several friendships.

Normalcy creates contrast and realism.

## 7.40.20 Trauma Inflation Prohibited

Do not give every significant NPC:
- murdered family;
- secret bloodline;
- betrayal;
- horrific childhood;
- forbidden technique.

Trauma and rarity should remain rare enough to matter.

## 7.40.21 Family

Generate family context where relevant:
- parents;
- siblings;
- spouse;
- children;
- extended family.

Family relationships should vary:
- close;
- distant;
- strained;
- ordinary.

Do not assume every family relationship is dramatic.

## 7.40.22 Existing Social Network

NPCs should enter the world already connected.

Possible ties:
- coworkers;
- teammates;
- relatives;
- friends;
- rivals;
- mentors;
- neighbors.

A socially established adult should not appear with zero connections unless there is a reason.

## 7.40.23 Relationship Density

Network density should depend on:
- sociability;
- age;
- profession;
- stability;
- location.

Not everyone should know everyone.

## 7.40.24 Relationship Quality

Generated ties should use directional relationship state.

Do not reduce them to labels only.

A sibling relationship may contain:
- high Affection;
- low Trust;
- moderate Resentment.

## 7.40.25 Asymmetry

Generated relationships may be asymmetric.

Example:
- student idolizes mentor;
- mentor simply likes student.

This should occur naturally.

## 7.40.26 Reputation

Generate only reputation that plausibly exists.

A local merchant may have:
- neighborhood reliability reputation.

An elite jonin may have broader:
- combat;
- leadership;
- village reputation.

Do not give every NPC widespread fame.

## 7.40.27 Knowledge

Generate knowledge from:
- occupation;
- education;
- location;
- relationships;
- personal history.

NPCs should not know information merely because the simulation generated them near an event.

## 7.40.28 Beliefs and Misbeliefs

NPCs may possess:
- correct knowledge;
- rumor;
- outdated beliefs;
- misconceptions.

These should be plausible consequences of information access.

## 7.40.29 Secrets

Secrets should only be generated when they serve a plausible life function.

Examples:
- concealed debt;
- private relationship;
- hidden fear;
- covert affiliation.

Avoid giving every NPC a dramatic secret.

## 7.40.30 Secret Severity

Possible levels:
- minor private fact;
- meaningful personal secret;
- serious social risk;
- dangerous hidden information.

High-severity secrets should be relatively uncommon.

## 7.40.31 Routine

Generate routine from:
- occupation;
- household;
- hobbies;
- social network;
- responsibilities.

Ruleset 7.36 governs actual scheduling.

## 7.40.32 Hobbies

Hobbies can create:
- personality texture;
- social contacts;
- skill opportunities;
- routine variation.

Examples:
- gardening;
- gambling;
- cooking;
- fishing;
- music;
- collecting.

Avoid treating every hobby as mechanically important.

## 7.40.33 Presentation

Surface traits may include:
- clothing;
- grooming;
- speech style;
- posture;
- mannerisms.

Presentation should reflect:
- culture;
- resources;
- personality;
- profession.

## 7.40.34 Physical Appearance

Appearance may be randomized within:
- ancestry;
- age;
- environment;
- health;
- role.

Avoid equating attractiveness with social competence.

## 7.40.35 Naming

Names should fit:
- culture;
- clan;
- region;
- family.

Avoid excessive gimmick names unless setting-appropriate.

## 7.40.36 Clan Generation

If clan affiliation exists, generate:
- actual connection;
- degree of involvement;
- expectations;
- relevant traditions.

Clan membership should not automatically grant elite clan knowledge or abilities.

## 7.40.37 Kekkei Genkai and Rare Traits

Rare traits should follow world rarity.

They require:
- plausible ancestry;
- inheritance;
- known setting logic.

Do not use rarity to make every procedural NPC special.

## 7.40.38 Jutsu Generation

Jutsu loadout should reflect:
- rank;
- training;
- elemental affinity;
- mentors;
- specialization;
- career history.

Ruleset 3 owns technique validity.

## 7.40.39 Non-Canon Techniques

Original techniques may be generated when:
- plausible;
- balanced;
- consistent with chakra logic;
- connected to training or role.

They should not exist merely for novelty.

## 7.40.40 Social Skill Generation

Social skills should follow life history.

Examples:
- merchant -> Negotiation;
- teacher -> Teaching;
- interrogator -> Interrogation;
- performer -> Performance;
- commander -> Leadership.

Skill weaknesses should also be plausible.

## 7.40.41 Romance Baseline

Generate romantic baseline from:
- orientation;
- personality;
- relationship preferences;
- culture;
- current life context.

This defines potential, not current attraction to specific people.

## 7.40.42 Adult Sexual Baseline

For NPCs age 18+ only, when simulation-relevant, generation may include:
- sexual orientation;
- libido;
- preferred relationship context;
- broad preferences;
- boundaries;
- exclusivity preferences;
- reproductive expectations.

These remain private unless revealed in-world.

## 7.40.43 Adult Baseline Should Not Be Overgenerated

Detailed sexual baseline is unnecessary for:
- background NPCs;
- characters with no current relevance to adult relationship simulation.

Generate only enough information for the current simulation tier.

## 7.40.44 Current Relationship Status

Generate whether appropriate:
- single;
- dating;
- partnered;
- married;
- separated;
- widowed.

Do not default every NPC to single.

## 7.40.45 Attraction Is Person-Specific

Baseline preferences do not determine attraction to any specific character.

Specific attraction should arise through Ruleset 7.25.

## 7.40.46 Compatibility Is Not Pre-Solved

Do not generate:
- "perfect match for player."

Compatibility emerges from actual:
- values;
- lifestyle;
- goals;
- attraction;
- interaction.

## 7.40.47 Player-Centered Generation Prohibited

Do not generate NPC traits specifically to:
- complement player build;
- create guaranteed romance;
- provide needed mentor;
- solve current weakness;

unless there is an independent world reason.

## 7.40.48 Utility NPCs Need Lives Too

An NPC created because the simulation needs:
- healer;
- shopkeeper;
- guide;

should still receive enough:
- personality;
- goals;
- relationships;

to feel like a person rather than a service menu.

## 7.40.49 But Avoid Overdevelopment

A shopkeeper appearing once does not need:
- five-page biography;
- twelve family members;
- hidden political agenda.

Generation depth should match relevance.

## 7.40.50 Local Population Coherence

NPC demographics should reflect:
- village size;
- economy;
- institutions;
- war history;
- culture.

Avoid generating populations that contradict setting scale.

## 7.40.51 Occupation Distribution

Not every shinobi village resident should be a combat ninja.

Generate:
- civilians;
- craftspeople;
- merchants;
- administrators;
- farmers;
- medics;
- service workers;
- shinobi.

World populations need functional diversity.

## 7.40.52 Rank Distribution

High ranks should remain relatively uncommon.

Do not populate every social space with:
- elite jonin;
- ANBU;
- S-rank figures.

Rarity preserves meaning.

## 7.40.53 Skill Distribution

Most people should cluster around:
- ordinary competence;
- profession-relevant skill.

Exceptional skill should be uncommon.

Very low or very high extremes require plausible causes.

## 7.40.54 Social Diversity

NPC populations should include variation in:
- temperament;
- ambition;
- values;
- sociability;
- competence;
- family structure;
- worldview.

Avoid repeatedly generating the same archetypes.

## 7.40.55 Avoid Archetype Lock

Archetypes may guide initial generation.

They should not fully define behavior.

Example:
- "stern mentor" may also enjoy gardening and be terrible with money.

## 7.40.56 Quirks

Minor quirks may add memorability:
- always early;
- collects odd souvenirs;
- hates spicy food;
- speaks quietly.

Quirks should remain secondary to actual personality.

## 7.40.57 Procedural Contradiction Check

Before finalizing an NPC, check for contradictions such as:
- elite medical skill with no medical history;
- child with decades of experience;
- secret recluse with enormous public network;
- low-rank novice with unexplained master-level skills.

Contradictions require explanation or correction.

## 7.40.58 Coherence Pass

Final NPC generation should verify:
- age fits role;
- skills fit history;
- network fits life;
- routine fits occupation;
- goals fit circumstances;
- reputation fits reach;
- secrets fit opportunity;
- relationships fit social access.

## 7.40.59 Rare Combination Check

Unusual combinations may remain if plausible.

Example:
- shy jonin commander;
- elderly genin;
- civilian sealing scholar.

The system should explain unusual states rather than normalize them away.

## 7.40.60 Randomness Should Create Variation

Randomness is appropriate for:
- names;
- minor preferences;
- appearance;
- hobby;
- personality weighting;
- ordinary life events.

It should not freely override:
- chronology;
- world rarity;
- prerequisites;
- institutional logic.

## 7.40.61 Weighted Generation

Generation tables should use:
- context-sensitive weights;
- rarity;
- environment;
- demographics.

Avoid uniform random selection from all possible traits.

## 7.40.62 Dependency Generation

Some traits should depend on earlier generated facts.

Examples:
- profession influences routine;
- mentor influences skills;
- family influences network;
- culture influences etiquette;
- rank influences experience.

This produces causality.

## 7.40.63 Generate Relationships From Shared Context

New NPC relationships should arise from:
- workplace;
- family;
- team;
- neighborhood;
- school;
- clan;
- shared event.

Avoid attaching unrelated NPCs arbitrarily.

## 7.40.64 Historical Anchoring

NPC history should fit major world events.

A character old enough to experience:
- war;
- village disaster;
- political transition;

may have relevant memories.

They do not need personal involvement in every canon event.

## 7.40.65 Canon Proximity

Original NPCs may interact with canon characters only when:
- location;
- role;
- timeline;
- access;

make it plausible.

Avoid making every generated NPC secretly close to major canon figures.

## 7.40.66 Hidden State

Generated NPCs may include hidden:
- motives;
- secrets;
- relationships;
- biases.

These remain subject to Ruleset 7.38.

## 7.40.67 Player-Facing Introduction

On first meeting, reveal only what is observable or known:
- appearance;
- role if known;
- demeanor;
- public reputation if applicable.

Do not dump the generated biography.

## 7.40.68 Expansion on Relevance

If the player repeatedly interacts with a minor NPC:
- promote simulation tier;
- generate deeper history;
- expand relationships;
- preserve all established facts.

## 7.40.69 No Rerolling Personality for Convenience

Once important traits are established, do not regenerate them to fit a later plot need.

Development should occur through experience.

## 7.40.70 Procedural NPC Audit

For a generated persistent NPC, the engine should be able to answer:

1. Why does this person exist in this location?
2. What do they do?
3. How did they gain their important skills?
4. What do they currently want?
5. Who matters to them?
6. What does a normal day look like?
7. What major experiences shaped them?
8. Which traits are ordinary and which are unusual?
9. Are unusual traits properly explained?
10. What information should remain hidden?

## 7.40.71 Design Standard

A procedural NPC system should be rejected or revised if it:
- generates disconnected random stats;
- makes every NPC exceptional;
- gives every NPC tragic backstory;
- makes every NPC single for player convenience;
- creates rare powers without rarity logic;
- gives mastery without training history;
- produces zero-network adults without explanation;
- makes every NPC secretly important;
- overdevelops background characters;
- contradicts established chronology or setting demographics;
- regenerates established personality for narrative convenience.

## Governing Rule

**Procedural NPC generation should create people whose abilities, relationships, motives, routines, and personalities can be traced back to plausible lives, using randomness to create diversity within world, demographic, and progression constraints rather than substituting randomness for cause.**
