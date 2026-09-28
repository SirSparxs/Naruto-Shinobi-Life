# Campaign state

Status: Open — no campaign initialized. Layout below is Provisional.

The current task migrates design, not character creation. No invented player, family, date, village, secret or RNG seed has been saved.

Proposed layout after creation:

```text
game-state/<campaign-id>/
  manifest.json
  player-state.json
  world-state.json
  entities/
  relationships.json
  events/
  checkpoints/
  gm/
    hidden-state.json
    rng-state.json
    resolutions/
```

Names and schemas must be finalized before implementation. Files in this example do not yet exist. The manifest would reference a rules revision and schema version.

Player state contains the permitted knowledge view. GM records contain actual hidden game facts and resolution evidence, not narrative promises or private assistant reasoning. Repository owners can inspect every file; normal play relies on not opening spoiler records.

Use the [state contract](../simulation/state-contract.md) and [RNG contract](../simulation/rng.md). See [issue #4](https://github.com/SirSparxs/Naruto-Shinobi-Life/issues/4).
