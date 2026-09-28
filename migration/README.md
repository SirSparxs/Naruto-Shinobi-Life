# Design migration tracker

Status: Established record of this integration; Open source recovery and design completion.

## Repository inspection before writes

Inspected the private repository SirSparxs/Naruto-Shinobi-Life on 2026-09-28.

- Default and only branch: main.
- Initial commit: `6045f727ce6e4d12eaaa2775e8fbb1f6ef4bc0d8`.
- Initial commit's tree: `5f3c600a55e11b5099d223f84331ba617ab25697`.
- Only file: README.md, blob `d6c1581d0bc9f16df256e31de95f9ea70d9c9b32`, 42 bytes.
- Original content: heading “Naruto-Shinobi-Life” and line “ChatGPT AI Campaign”. Both retained at the beginning of the expanded README.
- Commit history contained only “Initial commit”; no prior rules writes were present.
- No issues or pull requests existed at inspection.
- Local synced sources/ contained no reference files; synced project material was not modified.

## Coverage

| Area | Integrated now | Still Open |
|---|---|---|
| Project principles | User brief, agency, fairness, world independence, information boundaries, canon divergence | Detailed later subsystems |
| Ruleset 1 | Seven attributes, skills/mastery, growth/generation principles, Components A–G table reference | Executable growth and calibrated distributions |
| Ruleset 2 | Consolidated pipeline, safeguards, information/context, 30-section map, provisional formulas | Skill-scale conversion, RNG/band conventions, validation |
| Ruleset 3 | Explicit Control revision, non-canon permission, 3.1–3.4 working mechanics, later scope backlog | Full jutsu/special-ability design and tuning |
| Simulation/state | Persistence, RNG evidence, world/NPC/time and save contracts | Implemented engine and validated schemas |
| Beginner guidance | Reading, issues, commits, review and spoiler boundaries | None for current documentation scope |
| Source evidence | Available text from five conversations, exact turn/message IDs | 23 assistant messages capped at 20,000 characters |

All conversation pages were retrieved, including four pages for Ruleset 2. This is **available-evidence integration**, not a claim of complete source export. See [source index](source-index.md), [decision register](decisions.md) and [deprecated ideas](deprecated.md).

## Open work in GitHub

1. [Growth and generation calibration](https://github.com/SirSparxs/Naruto-Shinobi-Life/issues/1)
2. [Resolution scales and probability boundaries](https://github.com/SirSparxs/Naruto-Shinobi-Life/issues/2)
3. [Chakra and jutsu completion](https://github.com/SirSparxs/Naruto-Shinobi-Life/issues/3)
4. [Persistence, schemas and RNG implementation](https://github.com/SirSparxs/Naruto-Shinobi-Life/issues/4)
5. [Recover truncated source tails](https://github.com/SirSparxs/Naruto-Shinobi-Life/issues/5)

## Migration discipline

Each later import should inspect current files and issues first, identify its source revision, classify claims, reconcile conflicts and record what changed. Keep one maintained home for each rule. Reference excerpts may repeat historical text but are never parallel canonical versions.

No draft folder layout from prior conversations is independently canonical. This integration chooses rules/, simulation/, game-state/, world/, schemas/, docs/ and migration/ as one consistent navigation structure.
