# Naruto-Shinobi-Life
ChatGPT AI Campaign

A persistent, choice-driven Naruto life simulation. This private repository holds the durable design record and, later, campaign state.

## Start here

- [Project principles](docs/project-principles.md): what the simulation must preserve.
- [Ruleset 1 — Character growth](rules/01-character-growth/README.md).
- [Ruleset 2 — Resolution, probability and difficulty](rules/02-resolution-probability/README.md).
- [Ruleset 3 — Chakra, jutsu and special abilities](rules/03-chakra-jutsu/README.md).
- [Simulation architecture](simulation/README.md) and [campaign state](game-state/README.md).
- [Beginner guide](docs/repository-guide.md): how to use this repository without learning Git commands.
- [Migration tracker](migration/README.md), [source index](migration/source-index.md), and [change history](CHANGELOG.md).

## How to read status

| Status | Meaning |
|---|---|
| Established | Supported current design decision; usable within its stated scope. |
| Provisional | Working proposal or unvalidated tuning; not finalized canon. |
| Open | Missing decision, unresolved conflict, or incomplete specification. |
| Deprecated | Superseded historical idea; do not use for new design or play. |

Status applies to individual sections, not everything in a folder. See [decision policy](docs/decision-policy.md). Reference excerpts preserve discussion, including obsolete ideas; they never override the current rule files.

## Current coverage

Ruleset 1 has its framework and proposed calibration. Ruleset 2 has a consolidated resolution architecture and provisional mathematics. Ruleset 3 covers all planned sections 3.1–3.35, including the explicitly revised 27-tier Control track. Its learning, mastery, resource and interaction interfaces have been reconciled with Rulesets 1 and 2 in the [2026-09-29 audit](migration/audit-2026-09-29.md). Calibration and implementation remain Open; completed section coverage does not imply finalized numbers.

This is a design repository, not a running game engine. No campaign, player character, timeline, random seed or hidden plot has been initialized. Some long source messages were truncated by the conversation reader; [issue #5](https://github.com/SirSparxs/Naruto-Shinobi-Life/issues/5) tracks full recovery.

Continue designing conversationally. Final decisions go into the relevant rule file; unresolved work stays in [Issues](https://github.com/SirSparxs/Naruto-Shinobi-Life/issues).
