# World, NPCs and time

## Established — independent persistent world

Source: S0 user brief and S2 information/NPC principles.

Track simulation year, season, relevant month/date and age. Advance time at a scale appropriate to the situation: childhood can span months/years, Academy weeks/months, missions days/weeks, downtime longer periods. An exact starting year belongs to character creation and has not been selected.

NPCs retain personalities, goals, loyalties, fears, abilities, relationships and secrets. They may refuse, lie, misunderstand or oppose the player. Do not redesign them to guarantee the player a preferred relationship or victory.

Maintain world changes such as village relations, political tensions, leadership, wars, economy, crime, careers, births, deaths and marriages. Character knowledge arrives through plausible channels. Generational succession must preserve world history.

## Provisional — bounded simulation

Use detailed updates for active scenes and important NPCs, periodic summaries for relevant regions/factions, and dormant records for distant entities until they matter. This is a practical implementation proposal, not a fixed simulation interval.

A world update should record its previous/next simulation time, affected entity IDs, scheduling conditions, resources and resulting events. Define dependencies so a birth, death, mission or leadership change is not applied twice.

Lazy generation can fill undefined details consistently with world state, but must occur before those facts affect a resolved outcome. Once generated, retain them.

Aggregate off-screen training with Ruleset 1's development commitments. Promote records to greater detail without rerolling established traits. Time jumps must process relevant scheduled events and persistent effects rather than silently skipping them.

## Open

Calendar convention, update cadence, detail thresholds, event hazards, economic equations, NPC utility and succession initialization remain unspecified. Architecture work is in [issue #4](https://github.com/SirSparxs/Naruto-Shinobi-Life/issues/4); these topics do not gain mechanics merely by being listed.

## Ruleset 3 integration — Provisional world records

Sections 3.32–34 refine off-screen growth: preserve finite training opportunity, known arsenals, actual teachers/access and consequential consumption. Instantiating a background NPC may add appropriate detail but cannot retrospectively provide a perfect counter.

Track important technique knowledge through practitioners, teachers, archives, fragments and institutional curricula. Public awareness, complete instructions and an actor's local access are separate. Changes to curricula affect later learning; they do not instantly rewrite existing adults' mastery.

Biological lineage, teaching lineage and institution history are different mechanisms of transmission. A transplant, contract, host relationship or learned art does not become genetic by convenience.
