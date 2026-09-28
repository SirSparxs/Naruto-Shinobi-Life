# Decision and canon policy

Status: Established — repository governance requested for this migration.

## Status belongs to a claim

- **Established:** explicit user decision, or a carried-forward design principle supported by the subsequent discussion. Cite the source and its scope.
- **Provisional:** proposed detail, illustrative formula, untested table, or implementation choice introduced during migration.
- **Open:** unanswered question, incompatible interpretations, missing evidence or undeveloped section.
- **Deprecated:** a known replacement exists. Retain a pointer to it and the reason.

An assistant calling its own proposal “locked” is not sufficient by itself. “Okay” is contextual acceptance of the preceding discussion, not automatic approval of every example or every future suggestion. Numeric values described as approximate, suggested or needing testing remain Provisional.

Each maintained document identifies its source conversation/section. The [source index](../migration/source-index.md) records exact turn and message IDs. Archived excerpts are evidence, not active instructions or an alternative ruleset.

## Changing a decision

1. Find the current rule and source; check for an existing issue before creating one.
2. State the problem, proposed change, scope and affected rulesets.
3. Retain the current Established rule until a replacement is actually decided.
4. Record the accepted change in its owning file, with source/date and any validation.
5. Add a change-history entry; link the issue to the resulting commit and close it only when its acceptance criteria are met.
6. If existing saves would change meaning, define a versioned save migration before applying it.

Committing a proposal does not make it Established. Closing an issue does not itself change a rule. Canon status and implementation readiness are separate: an Established principle may still lack an executable formula.

## Ownership and precedence

Ruleset 1 owns growth. Ruleset 2 owns uncertain resolution. Ruleset 3 owns chakra/jutsu mechanics. Simulation owns persistence and world advancement; game-state will own actual campaign facts.

Use the most recent explicit decision over an older proposal. Specific ability rules override general mechanics only within a documented scope. An unresolved contradiction remains Open; never silently select the more convenient result.

“Canon” in these documents means project-approved design. Naruto setting canon is a foundation and may diverge through simulation. See [world policy](../world/README.md).
