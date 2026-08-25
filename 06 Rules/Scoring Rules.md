---
title: Scoring Rules
tags:
  - rules
  - scoring
status: locked
---

# Scoring Rules

Linked from [[Constitution]]. Mechanical rules are the **primary** scorer; 10 Neutrals apply and audit them.

## Probability

- Starts at **50.0%** — confidence that the Pro-defined truth-stack in [[Christianity Truth Stack]] is true.
- Updated only by Score Events (`SE-###`).
- Clamp to **1.0%–99.0%**.

## Claim statuses

| Status | Meaning | Moves %? |
|--------|---------|----------|
| `Unscored` | Not through audit | No |
| `Contested` | Both sides engaged; no decision | No |
| `Strengthened` | Support raised, not decisive | Yes (partial) |
| `Weakened` | Support lowered, not decisive | Yes (partial) |
| `Proven` | Meets evidence threshold | Yes (full) |
| `Refuted` | Fails under rules | Yes (full) |
| `Hold` | Bias audit or deadlock pending | No until released |

## Importance tiers

| Tier | Examples | Proven / Refuted Δ |
|------|----------|--------------------|
| **Foundation** | God exists; biblical God; Jesus as Son who died for sins | ±8.0 |
| **Core** | Historical Jesus; crucifixion; resurrection | ±5.0 |
| **Supporting** | Manuscripts; early creeds; key archaeology | ±2.0 |
| **Peripheral** | Side debates; minor textual issues | ±0.5 |

**Strengthened / Weakened** = **25%** of the tier’s Proven/Refuted weight  
(e.g. Core Strengthened = ±1.25).

## Direction

- A **Pro-affirming** claim: Proven/Strengthened → % **up**; Refuted/Weakened → % **down**.
- An **Anti-affirming** (disconfirming) claim: Proven/Strengthened → % **down**; Refuted/Weakened → % **up**.

## Tier assignment process

1. Pro proposes tier when registering the claim (or Anti for counter-claims).  
2. Challenge window: **one full round phase set** (or until all three parties reply).  
3. Pro + Anti + Neutrals seek consensus.  
4. If no consensus after the window → **Neutrals break the tie** and lock `tier_locked: true`.

## Proven / Refuted threshold (checklist)

A claim may be marked Proven only if Neutrals document **all** of:

1. At least one accepted (not rejected) primary or high-quality secondary source set linked  
2. Opponent had opportunity to rebut in the current or prior round  
3. No open upheld Source Challenge that undercuts the decisive sources  
4. Symmetry rule not violated in the winning argument  
5. Viewpoints are historical / philosophical / scientific as required  
6. For Foundation or Core: [[Bias Protocol]] completed by ≥2 Neutrals with no unresolved Hold  

Refuted: same checklist applied to showing the claim fails (not merely “we disagree”).

## Score Event required fields

See template [[T - Score Event]]. Every event logs: claim id, from→to status, old→new %, neutrals, bias_audit, rule_refs.

## Hottest debates

Operational definition for Wire/Scoreboard:

- `status: Contested`
- Tier Foundation or Core (or high rebuttal count)
- Multiple rebuttal / challenge links

Tracked in [[Hottest Debates]].
