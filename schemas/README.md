# Data schema readiness

Status: Open — no executable schemas are claimed complete.

[Issue #4](https://github.com/SirSparxs/Naruto-Shinobi-Life/issues/4) owns implementation. Start from the [state contract](../simulation/state-contract.md), then define versioned schemas for campaigns, characters, skill tracks, jutsu, knowledge, events and RNG records.

Requirements to preserve:

- Exactly seven primary attributes, with natural base and temporary effective values distinct.
- Skill-track identity, level where applicable, tier and progress separate from technique mastery.
- Chakra Control's 5/5/5/5/7 structure validated without forcing all skills into that track.
- Current/maximum resources distinct from foundational attributes and safe output.
- Stable IDs, valid references, explicit rule/schema versions and chronological event linkage.
- Knowledge and GM visibility separate from objective facts.
- Unknown values distinct from zero; no placeholder campaign mistaken for real state.
- Costs, output and time units explicit.
- Provenance/status for authored design records.

A schema must not freeze an Open mechanic by inventing a default. Examples should live separately from real saves and be clearly labeled when introduced.
