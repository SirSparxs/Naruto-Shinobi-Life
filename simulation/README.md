# Simulation architecture

Status: Established persistence requirements; Provisional implementation design.

Source: S0 **Game Design Rules Balance**, initial brief and the two later persistence discussions; S2 resolution safeguards. [Source index](../migration/source-index.md).

The user authorized GitHub as durable project storage, including hidden game facts. The architecture below organizes that requirement; it is not a running engine.

- [State and event contract](state-contract.md)
- [RNG and resolution evidence](rng.md)
- [World, NPCs and time](world-npcs-time.md)
- [Future campaign layout](../game-state/README.md)
- [Schema readiness](../schemas/README.md)

Separate design rules, reusable setting data and actual campaign state. Load only the relevant working set during play, then persist meaningful changes. Conversation prose is not a reliable substitute for structured state.

No storage layout makes the repository owner unable to inspect GM information. Keep game facts, hidden motivations, mechanical results and event records; no private assistant reasoning is required.
