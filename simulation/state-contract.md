# Persistent state and event contract

Status: Provisional implementation proposal, derived from Established persistence and consistency requirements in S0/S2. Track implementation in [issue #4](https://github.com/SirSparxs/Naruto-Shinobi-Life/issues/4).

## Boundaries

| Layer | Contents |
|---|---|
| Rules | Versioned design decisions and explicitly selected provisional rules |
| Setting | Reusable world foundations and setting references |
| Campaign truth | Actual characters, resources, location, world events and consequences |
| Character knowledge | Observations, beliefs, confidence and sources per actor |
| GM state | Hidden facts, potential, motives, unresolved information and RNG state |
| Event history | What changed, why mechanically, when, and under which rule version |

Player-facing views must be projections of knowledge, not copies of unrestricted truth. NPC decision-making also uses each NPC's information.

## Proposed minimum record fields

A campaign manifest identifies campaign ID, schema version, rules revision/commit, current checkpoint, simulation date and latest event ID. Entity records have stable IDs and references; display names can change without breaking relationships.

An event contains stable event ID, simulation time, actor/target IDs, objective, relevant rule version, preconditions, costs, outcome, state changes, knowledge changes and any learning event. A consequential uncertain resolution also references its recorded RNG evidence.

A hidden fact carries its identity, establishment event/time, actual value, who knows/believes it and revelation conditions. A retcon is an explicit corrective event with reason, not silent replacement.

Unknown, zero, absent and not applicable must remain distinguishable. Illustrative names, sample seeds and dates from the source conversations are not actual campaign facts.

## Proposed update procedure

1. Read current campaign revision and the relevant rules, entities, encounter and RNG state.
2. Check whether the event ID has already been committed; if so, return the prior result.
3. Establish and record relevant undefined facts before using them to determine outcomes.
4. Resolve the objective with the selected rule version and RNG convention.
5. Validate resource bounds, entity references, time, knowledge visibility and resulting conditions.
6. Save the event, resulting state, learning evidence and advanced RNG state together in one commit.
7. If the branch advanced since the read, reread/reconcile instead of overwriting it.
8. Only after confirmed persistence, treat the turn as saved and narrate the permitted view.

These are proposed reliability requirements. There is no implemented transaction manager. On an ambiguous write result, inspect history for the event ID before generating another draw.

## Checkpoints and migrations

Use compact current state plus bounded event history/checkpoints, with older events retained in archives. A checkpoint references its event boundary and rules/schema versions. Correcting a rule does not silently replay or reinterpret old campaign events.

A future schema migration needs source/target versions, prerequisites, field mapping, invariants and a recoverable prior checkpoint. Game-state migration is separate from the design-import tracker in migration/.

## Ruleset 3 integration — Provisional persistence details

Persist resource movement at the stage where it occurs. An interrupted technique can have already consumed chakra or materials; success is not the only event that changes state. Keep pre-commit computation distinct from committed game-state facts.

Represent technique instances with source/owner, lifecycle, maintenance/tether conditions, resource allocation, effect state and ending conditions. Do not delete independent seals, released matter, environmental hazards or injuries merely because the caster becomes unconscious or dies.

Keep personal and external pools, clone allocations/returns and entity-owned resources separate. Summons and tailed beasts remain persistent entities. Track resource origins/conversion and actual availability so return/transfer events cannot duplicate supply.

Learning events need recipient, technique/version, provenance, novelty and any clone-return/assimilation linkage. Acquired knowledge, current execution capability and personal mastery are distinct. Biological inheritance, teaching/archives and institutional transmission must remain separately traceable.

See [Ruleset 2's interface](../rules/02-resolution-probability/technique-resolution.md). Atomicity, event IDs and replay remain implementation work, not guaranteed behavior of this documentation.
