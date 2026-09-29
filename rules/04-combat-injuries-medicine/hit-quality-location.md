# 4.7 — Hit Quality & Hit Location

Status: Provisional design section pending explicit approval.

This section defines how successful offensive resolution becomes physical contact. It governs miss quality, grazing versus solid contact, precision, called shots, anatomical targeting, and when exact hit location matters.

## 4.7.1 Resolution Success Does Not Equal Identical Contact

Ruleset 2 determines whether the offensive action succeeds and by what degree.

Ruleset 4 then interprets that result as a quality of contact based on:
- outcome degree;
- attack type;
- defender response;
- positioning;
- precision;
- range;
- movement;
- visibility;
- target size;
- called target;
- weapon or technique behavior.

A successful attack may therefore produce anything from grazing contact to ideal placement.

## 4.7.2 Contact Quality Categories

The simulation may describe contact through broad categories:

### Complete Miss
The harmful path does not contact the target.

### Near Miss
The attack narrowly fails and may still affect position, clothing, equipment, cover, or confidence.

### Graze / Peripheral Contact
The attack touches the target but with limited depth, force, duration, or placement.

### Partial / Compromised Hit
The attack lands, but defense, angle, movement, armor, or poor alignment reduces effectiveness.

### Clean Hit
The attack lands with normal intended contact and useful force transfer.

### Strong Hit
The attacker lands especially favorable force, alignment, timing, or placement.

### Precision / Critical Placement
The attack reaches a particularly vulnerable or deliberately selected location under favorable conditions.

These are descriptive consequence categories, not automatic damage multipliers.

## 4.7.3 Contact Quality Is Derived, Not Randomly Rolled Separately

The system should not routinely make a second unrelated "damage quality roll" after Ruleset 2 already resolved the exchange.

Contact quality should usually derive from:
- outcome degree;
- defense result;
- attack design;
- tactical context.

Additional uncertainty is only needed when a genuinely unresolved physical question remains.

## 4.7.4 Defensive Success Can Alter Hit Quality

A defender may fail to avoid contact but still reduce its quality.

Examples:
- turning a stab into a shallow slash;
- moving the head enough that a strike hits the shoulder instead;
- lowering the torso so a projectile clips the arm;
- blocking part of a blast;
- rotating with a punch to reduce force.

This allows partial defense to matter mechanically.

## 4.7.5 Exact Hit Location Is Conditional

The simulation should not determine an exact anatomical location for every routine hit.

Exact location becomes important when:
- a called shot is attempted;
- the attack is penetrating, cutting, or highly localized;
- the location changes injury severity;
- armor coverage differs by region;
- a limb or sensory organ is specifically targeted;
- the target has a known injury;
- the technique has location-dependent effects;
- medical consequences require precision.

Otherwise, broad regions are sufficient.

## 4.7.6 Broad Body Regions

When location matters but extreme precision does not, the system may use regions such as:
- head;
- neck;
- upper torso;
- lower torso;
- back;
- left/right arm;
- left/right hand;
- left/right leg;
- left/right foot.

More detail can be introduced only when consequence requires it.

## 4.7.7 Anatomical Subregions

When necessary, a broad region may be refined into:
- eye;
- jaw;
- temple;
- throat;
- shoulder;
- upper arm;
- elbow;
- forearm;
- wrist;
- chest;
- abdomen;
- flank;
- spine;
- hip;
- thigh;
- knee;
- shin;
- ankle;
- specific fingers or toes.

This refinement should occur because the distinction matters, not as routine bookkeeping.

## 4.7.8 Called Shots

A called shot occurs when the attacker deliberately targets a specific location.

Examples:
- wrist to disarm;
- knee to reduce mobility;
- eye to impair vision;
- hand to interrupt seals;
- throat for lethal intent.

A called shot generally narrows the acceptable target area and may therefore increase difficulty or reduce available contact quality if execution is imperfect.

The exact probability effect belongs to Ruleset 2.

## 4.7.9 Called Shots Do Not Guarantee Exact Placement

A successful called shot may still vary by outcome degree.

Example:
- narrow success targeting the hand may strike the forearm;
- solid success may hit the hand;
- exceptional success may strike the intended fingers or tendon line.

The attack should preserve intent while allowing imperfect placement.

## 4.7.10 Uncalled Hits Use Contextual Placement

If no location is specified, the engine should choose or infer a plausible location from:
- attack trajectory;
- relative height;
- stance;
- exposed areas;
- defensive movement;
- cover;
- weapon arc;
- outcome degree.

Randomization may be used when multiple locations are equally plausible, but geometry and context should take priority.

## 4.7.11 Vulnerable Locations Are Physically Vulnerable, Not "Critical Zones"

The head, neck, eyes, joints, major blood vessels, organs, and similar locations may be more dangerous because of anatomy.

They should not simply receive arbitrary critical multipliers.

Their increased danger comes from the kinds of injuries that contact there can cause.

## 4.7.12 Vital Areas Increase Consequence, Not Automatic Death

A clean hit to a vital area is more dangerous, but not every contact is instantly fatal.

Severity still depends on:
- attack type;
- force;
- depth;
- angle;
- protection;
- precise structure struck;
- immediate treatment;
- exceptional physiology.

This avoids both unrealistic immunity and excessive instant death.

## 4.7.13 Limb Hits Matter Functionally

Hits to limbs may create:
- reduced grip;
- slower seals;
- impaired running;
- reduced balance;
- inability to bear weight;
- reduced weapon control;
- pain or numbness.

The mechanical effect should follow the actual injury rather than a universal "limb hit penalty."

## 4.7.14 Hands Are Especially Important for Shinobi

Hand and finger injuries can affect:
- hand seals;
- weapon grip;
- climbing;
- grappling;
- medical procedures;
- puppet control;
- tool use.

Because of this, targeting the hands can be tactically significant even when the wound is not life-threatening.

## 4.7.15 Eyes and Sensory Organs

Eye injuries may affect:
- vision;
- depth perception;
- tracking;
- dōjutsu use;
- targeting;
- reading hand seals.

Ear injuries may affect:
- balance;
- hearing;
- directional awareness.

Specific bloodline or technique interactions should be defined in their own ability records.

## 4.7.16 Head and Neck

Head and neck impacts may involve:
- concussion;
- skull injury;
- brain trauma;
- airway damage;
- vascular damage;
- cervical injury;
- sensory impairment.

These regions are high consequence because of anatomy, not because they receive an abstract multiplier.

## 4.7.17 Torso

Torso hits may involve:
- ribs;
- lungs;
- heart;
- liver;
- kidneys;
- abdominal organs;
- spine;
- major vessels.

Penetration depth and attack path matter substantially for serious torso injuries.

The simulation only needs organ-level detail when consequences justify it.

## 4.7.18 Armor Coverage Is Location-Specific

Armor protects only the locations it actually covers.

A chest plate should not protect:
- face;
- throat;
- exposed limbs;
- unarmored joints.

Partial armor coverage therefore makes hit placement relevant without requiring a universal armor score.

## 4.7.19 Defensive Movement Can Redirect Location

A defender may be unable to avoid contact but can deliberately protect a more vulnerable region.

Examples:
- raise forearm to shield face;
- turn torso so a blade hits armor;
- sacrifice shoulder instead of throat;
- place a weapon between attack and hand.

This can convert a potentially catastrophic hit into a more survivable injury at a tactical cost.

## 4.7.20 Cover Can Restrict Available Hit Locations

A character behind waist-high cover may expose only:
- head;
- shoulders;
- arms.

A character peeking around a wall may expose only one side.

Attacks should only threaten locations actually accessible through the attack path.

## 4.7.21 Attack Shape Affects Location Precision

Different attacks have different spatial characteristics.

Examples:
- needle: highly localized;
- sword slash: line/arc;
- punch: localized blunt contact;
- explosion: broad area;
- flame wave: distributed exposure;
- lightning stream: path-based.

A large area attack generally has less precise anatomical targeting than a needle or blade thrust.

## 4.7.22 Penetration and Path Matter

For penetrating attacks, the entry point alone may not determine injury.

The path through the body may affect:
- organs struck;
- blood vessels;
- bones;
- exit wounds;
- depth;
- retained projectile.

Detailed path simulation should only occur for consequential wounds.

## 4.7.23 Multi-Hit Attacks

A technique or weapon sequence may strike multiple locations.

The system should distinguish:
- one attack with broad distributed effect;
- several separate contacts;
- repeated hits to the same region.

Multiple hits should not automatically be collapsed into one location if the difference affects injuries.

## 4.7.24 Repeated Hits to an Existing Injury

Striking an already injured area can:
- worsen tissue damage;
- reopen bleeding;
- destabilize fractures;
- impair function further;
- interrupt healing.

The consequence should depend on the existing injury rather than a generic "weak point" multiplier.

## 4.7.25 Intent Can Influence Placement

Lethal, nonlethal, capture, and disabling intent can change what regions are targeted.

Examples:
- nonlethal strike to torso instead of head;
- disabling attack to leg;
- capture attempt targeting hands;
- assassination attempt targeting throat or vital torso.

Intent influences decisions but does not guarantee safe outcomes.

## 4.7.26 Precision Has Practical Limits

Even highly skilled characters may struggle to hit tiny locations when:
- both combatants are moving rapidly;
- visibility is poor;
- the target is far away;
- the target is partially concealed;
- the attacker is injured;
- the attack has broad spread;
- the target is using unpredictable movement.

Precision should emerge from skill plus circumstances.

## 4.7.27 Extreme Skill Can Make Precision Reliable

At high mastery, a character may consistently:
- target joints;
- cut weapon straps;
- strike chakra points;
- hit moving projectiles;
- avoid vital areas.

This should reflect actual mastery rather than arbitrary cinematic permission.

## 4.7.28 Precision and Force Are Separate

An attack may be:
- highly precise but low force;
- imprecise but extremely powerful;
- both;
- neither.

This distinction matters for:
- senbon;
- medical strikes;
- chakra-point attacks;
- massive area techniques.

Precision should not automatically increase raw damage.

## 4.7.29 Overpenetration and Excess Force

Extremely powerful attacks may pass through or beyond the intended target.

Consequences may include:
- exit wounds;
- secondary targets;
- environmental damage;
- loss of capture opportunity.

This matters when force greatly exceeds what was necessary.

## 4.7.30 Nonlethal Placement Requires Skill

Trying to avoid lethal anatomy while still stopping an opponent may be difficult.

A character attempting a knockout, disabling strike, or capture may need greater control than someone simply attempting maximum harm.

This creates a natural cost for restraint.

## 4.7.31 Location Uncertainty Can Persist

The simulation may know a character was struck in the torso without immediately knowing whether a serious internal structure was damaged.

Medical assessment may later reveal:
- internal bleeding;
- organ injury;
- fracture;
- nerve damage.

This supports hidden medical state.

## 4.7.32 Hidden Injury and Visible Contact Are Separate

Witnessing where an attack landed does not automatically reveal internal severity.

A sword hit to the abdomen is visible.
Whether it damaged the liver or bowel may not be.

Characters know observable evidence, not the full internal injury record.

## 4.7.33 Contact Quality Should Influence Injury Potential

Contact quality may affect:
- penetration depth;
- force transfer;
- duration of exposure;
- stability of strike;
- placement;
- follow-through.

It should feed into the later damage/injury model rather than functioning as a standalone damage multiplier.

## 4.7.34 Critical Success Should Mean Superior Execution, Not Automatic Double Damage

An exceptional offensive resolution may create:
- ideal placement;
- cleaner angle;
- greater penetration;
- stronger force transfer;
- reduced defensive mitigation;
- a tactical opening after contact.

What that means depends on the attack.

There should be no universal "critical hit = double damage."

## 4.7.35 Critical Failure Should Be Contextual

A severe offensive failure might produce:
- overextension;
- weapon loss;
- bad footing;
- collision;
- friendly-fire risk;
- self-exposure.

It should not automatically invent absurd self-injury when the context does not support it.

## 4.7.36 Compressed Combat Can Use Abstract Hit Quality

For minor encounters, the engine may summarize:
- superficial hits;
- one clean hit;
- no meaningful contact;
- decisive precision strike.

If an abstracted hit creates a meaningful injury, the system can zoom into exact location afterward.

## 4.7.37 Minimum Contact Record

For a consequential hit, the engine should be able to identify:
- attack type;
- intended location if any;
- actual location or region;
- contact quality;
- relevant defensive mitigation;
- attack angle/path where important;
- armor or cover interaction;
- whether the hit was deliberate, accidental, or redirected.

## Core Design Rule

Hit location should become detailed only when anatomy changes the consequence.

The system should prefer:
**broad region by default → exact location when tactically or medically important.**

A successful attack should answer not merely "did it hit?" but:
**how cleanly, where, with what alignment, and after what defensive mitigation?**
