# 6.2 — Shinobi Institutional Statuses & Life Stages

**Ruleset:** 6 — Academy, Training, Missions & Careers  
**Status:** Provisional

## 6.2.1 — Purpose

Institutional status describes where a character currently exists within the shinobi system.

It is distinct from:

- Rank
- Combat strength
- Specialization
- Job title
- Department
- Mission assignment
- Reputation
- Security clearance

A character may share the same rank as another shinobi while occupying a very different institutional status.

Example: two Chūnin may simultaneously be a field team leader, an Academy instructor, an intelligence analyst, or a temporarily restricted-duty shinobi.

Status answers:

> **What is this character's current relationship to the shinobi institution?**

---

## 6.2.2 — Status Is State, Not Identity

Institutional status is not a permanent identity.

Characters may transition between statuses because of:

- Age
- Graduation
- Promotion
- Assignment
- Injury
- Discipline
- Leave
- Career change
- War
- Retirement
- Reinstatement
- Political events
- Department transfer
- Personal choice

The engine must therefore store institutional status as persistent but mutable state.

---

## 6.2.3 — Status Categories

Ruleset 6 uses several broad status families:

1. Pre-service
2. Academy
3. Active shinobi service
4. Specialized or attached service
5. Restricted or interrupted service
6. Former service
7. Civilian or non-shinobi status

A character may sometimes hold more than one compatible descriptor at once.

Example:

> Chūnin + Academy Instructor + Active Duty

But incompatible primary statuses should not overlap.

Example:

> Active Duty and Retired should not normally coexist.

---

## 6.2.4 — Pre-Academy Civilian Child

A child who has not entered formal shinobi education is not yet part of the shinobi institution.

Possible circumstances include:

- Civilian upbringing
- Clan upbringing
- Informal family training
- Private tutoring
- Religious or cultural instruction
- Preparatory physical or chakra exercises

Pre-Academy training can affect later development, but it does not grant institutional standing.

The engine should distinguish:

- Informal preparation
- Recognized Academy enrollment
- Formal shinobi qualification

These are not interchangeable.

---

## 6.2.5 — Academy Applicant

A character seeking Academy admission may temporarily hold Applicant status.

This status can matter where admission is competitive, restricted, politically controlled, or unusual.

Applicant state may track:

- Age
- Sponsorship
- Entrance evaluation
- Eligibility
- Prior education
- Clan recommendation
- Citizenship or village affiliation
- Medical suitability
- Special accommodations
- Admission decision

Not every village or era needs a formal applicant stage.

---

## 6.2.6 — Academy Student

Academy Student is a formal institutional status.

An Academy Student:

- Is enrolled in a recognized shinobi training institution
- Has access to approved curriculum and instructors
- Is subject to attendance and performance standards
- May receive limited access to training facilities
- Is not yet a qualified active-duty shinobi
- Normally lacks independent mission authority
- May participate in supervised field exercises

Academy Student status should carry real obligations and scheduling consequences.

It is not merely a flavor tag attached to a child character.

---

## 6.2.7 — Advanced / Accelerated Academy Student

Exceptional students may receive advanced instruction without changing their underlying institutional status.

Possible labels include:

- Accelerated Student
- Advanced Student
- Senior Student
- Provisional Graduate Candidate

These are modifiers to Academy Student status, not automatic shinobi ranks.

An advanced student may:

- Study higher-level material
- Train with older cohorts
- Receive specialized tutoring
- Attempt early graduation
- Assist instructors
- Receive supervised exposure to advanced techniques

The existence of exceptional Academy students does not make exceptional progress common.

---

## 6.2.8 — Graduation Candidate

A student may enter Graduation Candidate status once eligible to complete the Academy's final requirements.

This may include:

- Final academic review
- Practical examination
- Behavioral evaluation
- Technique demonstration
- Physical assessment
- Field exercise
- Instructor recommendation

Graduation Candidate status does not guarantee successful graduation.

A failed candidate may return to ordinary Academy Student status, enter remediation, repeat a term, or leave the Academy depending on local policy.

---

## 6.2.9 — Academy Graduate

Graduation and team placement should be treated as separate events.

An Academy Graduate has completed minimum institutional training but may not yet be fully assigned to active field service.

This temporary status can cover:

- Awaiting team placement
- Awaiting instructor assignment
- Administrative processing
- Post-graduation evaluation
- Delayed deployment
- Medical or disciplinary hold

Where a village immediately assigns graduates, this status may last only briefly.

---

## 6.2.10 — Provisional Genin

Some villages or instructors may use a probationary period after Academy graduation.

A Provisional Genin:

- Has graduated
- Has not yet fully secured active Genin standing
- May undergo instructor evaluation
- May be returned for remediation
- May be reassigned
- May have limited mission eligibility

The classic post-graduation jōnin-sensei team test is one possible implementation of this concept.

Not every village must use Provisional Genin status.

---

## 6.2.11 — Active-Duty Genin

A Genin is a formally recognized shinobi with limited institutional authority.

Typical characteristics include:

- Eligibility for low-risk missions
- Placement under supervision
- Limited command authority
- Access to basic shinobi infrastructure
- Continued dependence on more senior leadership
- Eligibility for further training and promotion

Genin status should not imply incompetence.

A veteran or unusually capable Genin may possess substantial practical ability despite low institutional rank.

---

## 6.2.12 — Active-Duty Chūnin

A Chūnin is trusted with greater professional independence.

Typical expectations may include:

- Small-unit leadership
- Independent mission responsibility
- Greater tactical judgment
- Responsibility for junior shinobi
- Broader mission eligibility
- Increased administrative trust

A Chūnin's value is not determined solely by direct combat power.

Leadership, reliability, judgment, and mission competence are central.

---

## 6.2.13 — Tokubetsu Jōnin

Tokubetsu Jōnin represents high professional competence in a limited field rather than broad jōnin-level mastery.

Examples might include exceptional:

- Interrogation
- Tracking
- Teaching
- Intelligence
- Barrier work
- Sealing
- Examination administration
- Tactical analysis

Tokubetsu Jōnin status should preserve the distinction between:

> **specialist excellence**

and

> **broad jōnin qualification**

This is not simply "halfway between Chūnin and Jōnin."

---

## 6.2.14 — Active-Duty Jōnin

A Jōnin is generally trusted to operate with substantial independence and responsibility.

Depending on village structure, Jōnin may:

- Lead teams
- Command missions
- Mentor junior shinobi
- Serve in high-risk operations
- Hold sensitive assignments
- Advise leadership
- Exercise significant operational discretion

Jōnin status represents broad professional trust.

It should require more than exceptional combat ability alone.

---

## 6.2.15 — Elite or Senior Jōnin

"Elite Jōnin," "Senior Jōnin," or similar descriptors may exist as informal or local designations.

They should not automatically become a universal rank above Jōnin unless a specific village formally uses such a hierarchy.

Possible uses include:

- Seniority
- Prestige
- High-level command
- Specialized recognition
- Informal reputation

The engine must distinguish formal rank from descriptive prestige labels.

---

## 6.2.16 — Team Member Status

A shinobi may simultaneously possess a team assignment status.

Examples:

- Genin Team Member
- Chūnin Squad Member
- Temporary Mission Attachment
- Specialist Attachment
- Escort Detail
- Reconnaissance Cell

Team membership is an assignment, not a rank.

Changing teams should not inherently change rank or institutional standing.

---

## 6.2.17 — Team Leader / Squad Leader

Leadership assignment is distinct from permanent rank.

A character can be designated:

- Acting Team Leader
- Squad Leader
- Mission Commander
- Field Commander
- Temporary Commanding Officer

Leadership authority may exist only for:

- One mission
- One operation
- A defined team
- A specific crisis

Temporary command does not itself constitute promotion.

---

## 6.2.18 — Instructor Status

Instructor is a professional assignment.

Possible forms include:

- Academy Instructor
- Assistant Instructor
- Jōnin-Sensei
- Specialist Instructor
- Department Trainer
- Guest Instructor

Teaching ability should be tracked separately from subject-matter mastery.

A brilliant shinobi may be a poor teacher.

A less powerful shinobi may be an excellent instructor.

Instructor status can coexist with active-duty rank.

---

## 6.2.19 — Apprentice / Mentorship Status

Characters undergoing long-term specialized instruction may hold an apprenticeship or mentorship status.

This can represent:

- Medical apprenticeship
- Sealing apprenticeship
- Personal mentorship
- Clan tutelage
- Research apprenticeship
- Specialist department training

Mentorship is not necessarily an official village status.

Ruleset 6 should distinguish:

- Formal institutional apprenticeship
- Informal personal mentorship

Both may strongly affect access and training.

---

## 6.2.20 — Specialist Status

A specialist designation describes recognized professional capability.

Examples include:

- Medical-nin
- Sensor
- Tracker
- Interrogator
- Intelligence operative
- Barrier specialist
- Sealing specialist
- Hunter-nin
- Reconnaissance specialist
- Communications specialist

Specialist status does not replace rank.

A character might be:

> Chūnin + Medical-nin

or

> Tokubetsu Jōnin + Interrogation Specialist.

Specialization emerges from qualifications and demonstrated competence rather than being chosen as a character class.

---

## 6.2.21 — Departmental Assignment

A shinobi may belong to a formal department or division.

Examples include:

- Academy
- Hospital
- Intelligence
- Interrogation
- Barrier Corps
- Communications
- Research
- Administration
- Security
- ANBU or equivalent covert division

Department assignment affects:

- Daily schedule
- Available missions
- Training access
- Chain of command
- Security clearance
- Career opportunities
- Professional contacts

It should not automatically alter rank.

---

## 6.2.22 — ANBU / Covert Service Status

ANBU or equivalent covert service is a restricted assignment category, not automatically a separate strength tier.

A covert operative may retain an underlying rank internally while functioning under:

- Classified identity
- Special command structure
- Restricted records
- Compartmentalized assignments
- Special clearance
- Different reporting procedures

Public knowledge of this status may be limited or nonexistent.

---

## 6.2.23 — Reserve / Limited-Duty Status

Some shinobi may remain affiliated with the village while not serving ordinary active-duty schedules.

Possible examples:

- Reserve duty
- Limited field duty
- Part-time instructional duty
- Strategic reserve
- Emergency mobilization pool

This allows experienced personnel to remain institutionally useful without full active deployment.

Exact use depends on village and era.

---

## 6.2.24 — Medical Restricted Duty

Injury or illness may temporarily change a shinobi's allowed duties.

Possible restrictions include:

- No field missions
- No combat missions
- No chakra-intensive activity
- No travel
- Administrative duty only
- Training restrictions
- Reduced hours

Medical restriction does not automatically reduce rank.

It changes what the character is currently cleared to do.

---

## 6.2.25 — Administrative Restricted Duty

A shinobi may also be restricted for non-medical reasons.

Possible causes include:

- Investigation
- Disciplinary action
- Security concerns
- Failed evaluation
- Political review
- Operational negligence
- Pending tribunal

Restrictions may affect:

- Mission access
- Command authority
- Clearance
- Weapons access
- Training access
- Department placement

Restricted duty should have an explicit cause and duration or review condition.

---

## 6.2.26 — Leave Status

Characters may temporarily leave ordinary duty without leaving the shinobi institution.

Examples include:

- Medical leave
- Family leave
- Bereavement
- Personal leave
- Training leave
- Diplomatic assignment
- Research sabbatical

Leave consumes simulation time and may affect ongoing assignments or opportunities.

---

## 6.2.27 — Missing / Captured / Presumed Dead

The institution should track operational uncertainty.

Possible states include:

- Missing in Action
- Captured
- Presumed Dead
- Confirmed Dead

These are distinct.

A missing shinobi may still generate:

- Search missions
- Political pressure
- Family consequences
- Team reassignment
- Intelligence risk
- Succession or replacement decisions

The world should not treat "missing" as automatically equivalent to death.

---

## 6.2.28 — Suspended / Dismissed

A shinobi can lose the right to perform normal service without necessarily becoming a criminal.

Suspension may be temporary.

Dismissal may be permanent or appealable depending on the institution.

Possible causes include:

- Serious misconduct
- Repeated negligence
- Security violations
- Refusal of duty
- Political conflict
- Criminal behavior

Dismissal should remain distinct from voluntary retirement.

---

## 6.2.29 — Retired Shinobi

A retired shinobi has formally left active service.

Retirement may be:

- Voluntary
- Age-related
- Medical
- Political
- Family-driven
- Career-transition based

Retired shinobi may retain:

- Rank titles
- Reputation
- Professional knowledge
- Relationships
- Limited institutional access
- Emergency recall eligibility

Retirement does not erase prior capability or service history.

---

## 6.2.30 — Former Shinobi

Former Shinobi is a broad category for someone who once served but no longer holds active institutional standing.

This may include:

- Retirees
- Resignees
- Dismissed personnel
- Defectors
- Missing-nin
- Individuals whose village no longer exists

These subcategories must remain distinct because their legal and political consequences differ greatly.

---

## 6.2.31 — Missing-Nin / Defector Status

A shinobi who abandons their village under hostile or unauthorized circumstances may become a missing-nin, defector, deserter, or equivalent status.

This is both institutional and legal state.

Possible consequences include:

- Revoked clearance
- Revoked authority
- Active pursuit
- Bounties
- Classified risk assessment
- Hunter-nin assignment
- Family or clan consequences
- Diplomatic implications

Exact treatment depends on village law and severity.

---

## 6.2.32 — Civilian Status

Civilian is not synonymous with unskilled or powerless.

A civilian may possess:

- Chakra
- Combat training
- Academic expertise
- Trade skills
- Medical knowledge
- Wealth
- Political authority
- Clan affiliation

The defining feature is that they are not currently serving as recognized shinobi personnel.

Civilian and shinobi careers should therefore remain separate institutional categories.

---

## 6.2.33 — Status Transitions

Every major status change should have:

- A triggering cause
- An effective date/time
- Institutional authority responsible where applicable
- Consequences
- Any prerequisites
- Any review or expiration condition

Examples:

Academy Student → Graduate  
Genin → Chūnin  
Active Duty → Medical Restricted Duty  
Jōnin → Retired  
Retired → Recalled to Service  
Active Shinobi → Missing-nin

This prevents status changes from occurring as arbitrary narrative conveniences.

---

## 6.2.34 — Temporary vs Permanent Status

Statuses should be classified as:

- Permanent until changed
- Temporary with known end
- Temporary pending review
- Conditional
- Indefinite

This matters for simulation scheduling.

Example:

Medical Leave until June 12 is different from Restricted Duty pending medical clearance.

---

## 6.2.35 — Primary and Secondary Status Fields

For engine purposes, characters should support at least:

**Primary Institutional Status**
- Academy Student
- Active Shinobi
- Restricted Duty
- Leave
- Retired
- Former Shinobi
- Civilian

**Rank**
- Genin
- Chūnin
- Tokubetsu Jōnin
- Jōnin
- Other village-specific rank

**Assignment**
- Genin Team 3
- Academy Instructor
- Intelligence Division
- Hospital
- ANBU
- Unassigned

**Specializations**
- Medical
- Sensor
- Tracking
- Sealing
- etc.

**Modifiers**
- Provisional
- Acting
- Suspended
- Missing
- Captured
- Classified

This avoids trying to store every career fact in one overloaded status label.

---

## 6.2.36 — Core Design Principle

Institutional status should answer:

> **What is this character currently allowed, expected, and obligated to do within the shinobi system?**

Rank answers authority.

Specialization answers expertise.

Assignment answers current role.

Status answers institutional relationship.

Keeping these separate is essential for believable careers and flexible life paths.
