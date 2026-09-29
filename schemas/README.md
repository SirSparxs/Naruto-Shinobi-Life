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

## Ruleset 3 audit additions — Provisional contract requirements

- Separate acquisition state, within-tier progress, optional ability proficiency and technique/version-specific mastery. Use the [track index](../rules/01-character-growth/progression-tracks.md); no generic tier-to-capability default.
- Preserve variant/base relationships and explicit shared versus independent mastery; transfer-learning benefits are not copied mastery scores.
- Model personal, stored, beast, external and Senjutsu resources separately, with access, allocation, ownership, source, conversion and throughput. Suppressed supply is not necessarily depleted supply.
- Distinguish an ability's source/capacity, expression/access, proficiency, active form and persistent biological changes. Heritability and teaching lineage are separate records.
- Model stage-sensitive resource investment, interruption, maintained/tethered/autonomous effects and ending conditions; material and environmental consequences can outlive their caster.
- Link clone experiences to their recipient/assimilation event to avoid counting the same returned experience repeatedly; physical adaptations stay with the body that underwent them.
- Keep knowledge carriers, source completeness, local access, restrictions and confidence distinct from engine truth and learned capability.

These are schema requirements to implement under #4, not a claim that runnable validators now exist.
