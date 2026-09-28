# RNG and resolution evidence

Status: Provisional implementation specification; the need to preserve hidden results and persistent consequences is Established.

Source: S0 persistence discussions, S2 one-draw design. [Issue #4](https://github.com/SirSparxs/Naruto-Shinobi-Life/issues/4).

## Proposed deterministic stream

A seed and advancing counter are useful only with a specified algorithm, version, state representation, draw order and sampling convention. These remain Open. Do not claim replayability from a seed alone or substitute an improvised number for an actual generated draw.

Persist algorithm/version, seed or internal state, stream identity if used, and current counter/state. Store state before and after consequential draws, or sufficient exact evidence to replay them under the selected algorithm.

## Consequential resolution record

Record event/resolution ID, rules revision, actor/objective, relevant inputs, difficulty/opposition, causal modifiers, plausibility gate, probability units, RNG index/result, outcome degree, costs and final state changes.

Secret checks remain outside the ordinary player view. Preserve consequential hidden outcomes so facts cannot be retroactively rerolled. Trivial actions can preserve resulting state without a verbose roll record when no random audit evidence is needed.

The later S0 GitHub proposal favors exact records for consequential checks; its earlier suggestion to retain mainly consequences is retained as historical context, not a reason to discard needed audit evidence.

## Open before play

Select algorithm and endpoint conventions with Ruleset 2. Test replay after save/reload, duplicate event submission, interrupted writes, hidden discovery failures and unrelated off-screen draws. Decide whether one stream or multiple named streams best preserves reproducibility.

No random seed or RNG implementation is created by this documentation.
