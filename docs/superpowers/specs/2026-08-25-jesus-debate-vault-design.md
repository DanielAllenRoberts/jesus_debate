# Jesus Debate Vault — Design Spec

**Date:** 2026-08-25  
**Status:** Approved for implementation  
**Approach:** Newsroom + Courtroom Obsidian vault

## Purpose

An AI thought experiment vault where 50 Pro agents and 50 Anti agents research popular media and scholarly sources for and against Christianity, document claims with citations, cross-read and rebut, and have 10 Neutrals apply mechanical scoring. Documentarians narrate the experiment as news. Probability that the Pro-defined Christianity truth-stack is true starts at 50% and moves only via scored claim events.

## Core decisions (locked)

| Decision | Choice |
|----------|--------|
| Truth target | Pro defines the claim stack (e.g. God exists → biblical God → Jesus as Son who died for sins) and must prove claims + subclaims; Anti attacks that stack and may introduce counter-claims |
| Scoring authority | Mechanical rules primary; 10 Neutrals audit/apply; account for AI training bias |
| Probability | Start 50%; move only on Strengthened / Weakened / Proven / Refuted with fixed tier weights; clamp 1–99% |
| Importance | Tiered (Foundation / Core / Supporting / Peripheral); Pro+Anti+Neutrals seek consensus; Neutrals break ties after challenge window |
| Rounds | Strict phases first; may loosen to overlapping later by rules amendment |
| Structure | Newsroom + Courtroom folder tree |

## Constitution (summary)

1. Facts only — no assumptions; unsupported inference does not score  
2. Symmetry — accepted concepts/methods apply to both sides  
3. Viewpoints — historical, philosophical, and/or scientific  
4. Personal experience disallowed without clear independent proof  
5. Pro owns the truth-stack definition  
6. Full citation required; credibility challenges are first-class notes  
7. Wire never overrides Scoreboard  
8. Bias Protocol can Hold high-impact scores for re-check  
9. Tier consensus; Neutrals break deadlocks  
10. Round phase discipline until amended  

## Scoring math

**Statuses:** Unscored, Contested, Strengthened, Weakened, Proven, Refuted, Hold  

**Tier weights (Proven/Refuted):** Foundation ±8.0 · Core ±5.0 · Supporting ±2.0 · Peripheral ±0.5  

**Partial:** Strengthened/Weakened = 25% of tier weight  

**Affirming side:** Pro claim Proven raises %; Anti claim Proven lowers %  

## Agent counts

- Pro: 50  
- Anti: 50  
- Neutrals: 10  
- Documentarians: 10  

## Round phases (early mode)

1. Research & cite  
2. Cross-read  
3. Rebut (+ source challenges)  
4. Neutral audit + score  
5. Wire story  

## Vault map

See live vault: `00 Home.md`, folders `01`–`09`, `_bases/`.

## Out of scope (until kickoff)

- Running the 100 research agents  
- Populating initial popular-media lists  
- Changing phase mode to overlapping without a rules amendment note  
