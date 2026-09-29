# Probability and numerical tuning

Status: Provisional throughout. Source: S2 consolidation, sections 9–25; original sections 2–9. Work: [issue #2](https://github.com/SirSparxs/Naruto-Shinobi-Life/issues/2).

## Capability

Working default:

`Base Capability = 0.60 × Skill + 0.30 × Primary Attribute + 0.10 × Secondary Attribute`

When no meaningful secondary attribute exists:

`Base Capability = 0.60 × Skill + 0.40 × Primary Attribute`

Then apply only relevant technique-profile mastery effects and situational effects. Mastery may change cost, timing, concentration or available execution rather than adding a generic numeric bonus; count the resulting advantage once. A high mastery value is not an additional full score. Structural conditions stay structural. The conversion from tiered skill records to the formula's Skill input is **Open**; do not substitute within-tier progress. This includes the 25/27-tier tracks and optional ability proficiency in [the progression index](../01-character-growth/progression-tracks.md). Where an action needs several disciplines, prerequisite checks and the role of each skill/bottleneck must be defined; do not silently add or average all available skills.

Working modifiers: ±2 minor, ±5 noticeable, ±10 significant, ±15 major, ±20 extreme. Larger effects may warrant a structural change. These are not automatic bonuses for naming more advantages.

## Probability curve

`M = Effective Capability − Effective Difficulty`

For opposition, use the other actor's effective capability in place of task difficulty.

`p = 1 / (1 + 10^(−M/20))`

This returns a fraction from 0 to 1. To compare with a 0–100 random draw, convert to `P_percent = 100 × p`. This explicit unit conversion clarifies the source notation; it does not finalize the RNG convention.

| Margin | Approximate success |
|---:|---:|
| −40 | 0.99% |
| −20 | 9.09% |
| −10 | 24.03% |
| 0 | 50% |
| +10 | 75.97% |
| +20 | 90.91% |
| +40 | 99.01% |

The sensitivity constant 20 is unvalidated. Plausibility gates precede the curve; its nonzero tails never authorize impossible outcomes.

## One draw and degree

The source proposes one hidden draw R on a 0–100 scale, success when R ≤ P, and:

`Outcome Margin = P_percent − R`

Use the same draw for degree rather than an independent critical roll. One draw applies to one meaningful uncertain objective; it does not force unrelated simultaneous effects into a winner/loser contest. Stage checks are justified only by distinct consequential uncertainty, not by every listed execution component. The recorded draft bands are:

| Outcome margin in source | Draft degree |
|---|---|
| +40 or more | Exceptional success |
| +20 to +39 | Strong success |
| +6 to +19 | Standard success |
| 0 to +5 | Narrow success |
| −1 to −5 | Narrow failure |
| −6 to −19 | Standard failure |
| −20 to −39 | Severe failure |
| −40 or less | Catastrophic-range failure |

These integer-style boundaries leave fractional gaps if used literally with continuous draws. Do not implement them unchanged. Integer versus continuous sampling, endpoint inclusion, equality, rounding and exhaustive non-overlapping bands are **Open**.

A high-probability action can only fail by a small probability margin under this model; a low-probability action can only succeed narrowly. Actual consequences remain bounded by hazards and the task's plausible outcomes.

## Validation still needed

Resolve skill-track conversion, probability units, RNG interval/comparison, rounding and band coverage together. Validate symmetry for peers, mismatch gates, no duplicate penalties, no harmless catastrophes and no free repeated attempts. No mathematical stress test has yet established these proposed constants as balanced.
