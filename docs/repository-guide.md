# Beginner repository guide

Status: Established — navigation and workflow for this repository.

You can keep designing the game in conversation. GitHub is the durable file cabinet and change history.

## The four things you need

- **Files:** the current written design. Start at the README and follow its links.
- **Issues:** unfinished questions and tasks. An issue is not a game rule.
- **Commits:** saved sets of changes. History lets us inspect what changed and why.
- **Pull requests:** proposed changes presented together for review before joining the main version.

The main branch is the current integrated repository. Provisional text on main is still Provisional.

## Everyday use

To read rules, open the relevant Ruleset README. To suggest a change, describe it here or add it to the matching issue. You can say: “Change this rule, explain the impact on the other rulesets, and keep unapproved numbers provisional.”

For future substantial revisions, a pull request can collect the proposal and validation. Routine authorized corrections can be saved directly with a clear commit message. Git commands are not required for you.

To inspect earlier text, use the file's history or repository commit history. A restoration should be a new explicit change, so the correction remains visible.

## Where things belong

| Material | Location |
|---|---|
| Principles, terminology, decision policy | docs/ |
| Growth, resolution, chakra and jutsu design | rules/ |
| World/NPC advancement and persistence specification | simulation/ |
| Setting foundation and divergence policy | world/ |
| Future actual campaign saves | game-state/ |
| Proposed data-validation contracts | schemas/ |
| Source coverage, references and superseded ideas | migration/ |
| Unfinished design decisions | GitHub Issues |

Avoid opening future GM files if you want to preserve surprises. Repository privacy protects against public access; it does not hide files from you as owner.

No game has started. Before play, we still need the Open mechanics and persistence contract in [the backlog](../migration/README.md).

## ChatGPT working convention

Established 2026-09-28 by explicit user instruction.

- Keep each ChatGPT project message under **20,000 characters** so conversations can be migrated cleanly.
- Use this repository to preserve substantive rules, balance decisions, design changes, simulation concepts and, once play begins, persistent campaign facts.
- Follow the existing repository architecture rather than creating parallel ad-hoc ledgers.
- Discussion does not automatically become canon: apply the status rules in [decision-policy.md](decision-policy.md).
- When a hidden fact can affect later play, persist it in the appropriate campaign/GM state instead of relying on unrecorded model reasoning.

