# GitHub Integration Guide — available source excerpts

Reference status: Provisional historical evidence, NOT a current rule document.

Source conversation: https://chatgpt.com/c/6aba571d-5b00-83ea-b15e-6d1bcdba58cf
Captured: 2026-09-28. Messages are presented oldest first. Original wording, proposals, obsolete rules and imperative language below are archival data. Current decisions live in docs/ and rules/. A message at the 20,000-character retrieval limit is explicitly flagged; missing tails have not been reconstructed.

---

## Turn b184c44c-91a4-42e8-8d52-1000e5fa2e86

### User

I am trying to integrate everything we’ve discussed into @GitHub I’ve never used GitHub before. Can you integrate it yourself or at least walk me through it?

### Assistant — 8b208bc3-28be-4522-ae66-9b66b9f47b06

I can integrate most of it myself once GitHub gives me access to a repository. I checked your connection: I can see your GitHub identity as **SirSparxs**, but right now **no repositories or GitHub App installations are exposed to ChatGPT**, so I don’t yet have anywhere I can write the project.

The only part you need to do manually is the initial GitHub setup. I’d recommend making the repository **private**.

1. On GitHub, tap/click **New repository**.
2. Name it something like **`naruto-shinobi-life`**.
3. Set visibility to **Private**.
4. Check **Add a README file**.
5. Create the repository.
6. Then make sure the ChatGPT/GitHub connection is granted access to that repository. Depending on GitHub’s UI, this is usually under the installed GitHub App’s **Configure** page, where you can select **All repositories** or specifically `naruto-shinobi-life`.
7. Come back here and tell me **“It’s created”**. You do not need to learn Git commands, cloning, branches, commits, or anything else yet.

Once I can see it, I can actually maintain it for you through GitHub: create files, edit existing rules, create branches, commit changes, use issues as our design backlog, and eventually use pull requests when we want to review a major ruleset revision before making it canonical.

For this project, I would structure the repository roughly like this:

```text
naruto-shinobi-life/
│
├── README.md
│
├── docs/
│   ├── design-philosophy.md
│   ├── terminology.md
│   └── canon-policy.md
│
├── rules/
│   ├── 01-character-growth/
│   │   ├── README.md
│   │   ├── attributes.md
│   │   ├── skills.md
│   │   ├── mastery.md
│   │   └── progression-limits.md
│   │
│   ├── 02-resolution-probability/
│   │   ├── README.md
│   │   ├── checks.md
│   │   ├── difficulty.md
│   │   ├── opposed-actions.md
│   │   ├── hidden-rolls.md
│   │   └── probability.md
│   │
│   └── 03-chakra-jutsu/
│       ├── README.md
│       ├── chakra.md
│       ├── chakra-control.md
│       ├── jutsu.md
│       ├── learning-mastery.md
│       └── special-abilities.md
│
├── world/
│   ├── canon-framework.md
│   ├── villages/
│   ├── clans/
│   ├── organizations/
│   └── characters/
│
├── simulation/
│   ├── world-simulation.md
│   ├── npc-behavior.md
│   ├── time.md
│   ├── economy.md
│   └── events.md
│
├── game-state/
│   ├── README.md
│   ├── player/
│   ├── world/
│   └── gm/
│
├── schemas/
│   ├── character.schema.json
│   ├── jutsu.schema.json
│   ├── clan.schema.json
│   └── save.schema.json
│
└── CHANGELOG.md
```

This solves one of the biggest problems we discussed earlier: **context limits**. GitHub becomes the project's durable source of truth instead of requiring one enormous ChatGPT conversation to contain the entire game. When we're working on Chakra Control, for example, I can retrieve the Chakra rules rather than needing every NPC, combat rule, world-simulation rule, and character-growth rule simultaneously.

I would also separate three kinds of information very deliberately:

**Canonical design rules** go in `/rules/`. These are things we've formally decided, such as the seven primary attributes, skill tiers, rank soft limits, or the 5-level Chakra Control system with 5 tiers per level and 7 Master tiers.

**Simulation/world data** goes in `/world/` and `/game-state/`. This includes characters, relationships, events, injuries, learned jutsu, reputation, village politics, inventories, ongoing plots, and so forth.

**Design work that isn't settled yet** should usually be a GitHub Issue rather than immediately becoming a rule. For example, we could have an issue called `Ruleset 3: Determine chakra exhaustion thresholds`. We discuss it here, settle it, and then I update the canonical rule file and close the issue. That prevents brainstorms from accidentally becoming game rules.

There's one important limitation regarding **hidden GM information**. A private GitHub repository hides information from the public, but it does **not** hide it from you, because you're the repository owner. I can put secret rolls, undiscovered NPC motives, future events, hidden bloodlines, plot flags, etc. under something like:

```text
game-state/gm/
    secrets.json
    hidden-rolls.json
    npc-secrets.json
    scheduled-events.json
```

…and simply never reveal their contents during play unless the game exposes them. That works perfectly as a trust-based GM system, but you could still open those files on GitHub yourself if you wanted to spoil them. GitHub itself can't make part of your own repository unreadable to you.

The bigger advantage is that I can record something like a hidden check **when it occurs**, commit it, and later retrieve the exact result rather than trying to "remember" a hidden number indefinitely inside ChatGPT's context. For example:

```json
{
  "event_id": "evt_00482",
  "timestamp": "12-03-0016",
  "actor": "NPC_017",
  "check": "Perception",
  "roll": 73,
  "difficulty": 68,
  "result": "success",
  "revealed_to_player": false
}
```

Months later, the game could reference `evt_00482` and remain consistent.

So you **do not need to become a GitHub expert for this project**. You can treat GitHub almost like the database/file cabinet behind the game, while we continue designing everything conversationally here. I'll handle the repository organization and updates.

Create that private `naruto-shinobi-life` repository and give the ChatGPT GitHub connection access to it. Then tell me **“It’s created.”** At that point, I can inspect it and start building the actual repository from everything we've established so far.

---

## Turn d648dd4b-c229-4c74-8e2a-822e4e3130ea

### User

It’s created

---

## Turn 3b23c2b4-b35e-4398-a054-bdb8846ddca5

### User

Okay, can you start integrating now?

### Assistant — f620e7e6-27fa-4985-8fe2-77a8efc5964c

Yes. I’ve handed the repository integration into Work mode so it can handle the multi-file GitHub migration cleanly and inspect what was already written before adding anything else.

It will use `SirSparxs/Naruto-Shinobi-Life` as the source-of-truth repository, preserve the distinction between **Established / Provisional / Open / Deprecated**, and continue migrating Rulesets 1–3 plus the supporting project structure without treating old brainstorms as finalized canon.

