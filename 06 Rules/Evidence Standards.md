---
title: Evidence Standards
tags:
  - rules
  - evidence
status: locked
---

# Evidence Standards

## Required for any scoring use

1. **Source note** exists under `05 Evidence Library/Sources/` with template fields filled.  
2. **External reference** — URL, DOI, ISBN, stable archive link, or precise citation for offline works.  
3. **Claim link** — source lists which claims it is used for, each as a `[[wikilink]]` (Constitution §11).  
4. **Viewpoint tag** on the argument: historical / philosophical / scientific.

## Wikilinks (mandatory)

Per [[Constitution]] §11: internal vault references use Obsidian `[[wikilinks]]`, not bare IDs only. Arguments must wikilink target claims and cited sources; sources must wikilink claims they support/attack; claims keep linked argument/source lists. External URLs stay normal markdown links.

## Readable labels & learnable narration (mandatory)

Per [[Constitution]] §12 and [[Writing for Humans]]:

1. **Labels** — every coded wikilink (`C-` / `A-` / `S-` / `R-` / `SC-` / `SE-` / `H-`) needs plain-language context in the same sentence **or** Obsidian display text `[[Note|human label]]`.
2. **Explanation** — narrative docs (Wire, Scoreboard prose, round logs) that mention a claim, rebuttal, challenge, or score event must also give a one-sentence explanation of the point **and** why it matters for the truth-stack / probability story.

- **Good:** `[[S-012|Habermas minimal facts]] — a survey of scholarly consensus on a few early resurrection-related data points — supports [[C-006|Resurrection]], a core stack layer that moves overall probability when its status changes.`
- **Bad:** `Sources [[S-012]] [[S-013]] for [[C-006]]`

Bare ID link-dumps are a rules violation. Scoring math is unchanged.

## Source types

Books · Videos · Articles · Essays · Other media (podcasts, debates, documentaries, papers).

## Verification states

| State | May support scoring? |
|-------|----------------------|
| `accepted` | Yes |
| `unreviewed` | No (until Neutral or challenge process accepts) |
| `challenged` | No until challenge dismissed or source replaced |
| `rejected` | No |
| `unverified` (link dead / inaccessible / fabricated) | No |

Agents **must not invent sources**. If a cited work cannot be found, mark `unverified`.

## Credibility challenges

Filed as `SC-###` notes. Grounds may include: authorship fraud, serious methodological error, misquotation, predatory venue, outdated superseded consensus *with citation*, paywall-only claim with no accessible corroboration when challenged, etc.  
Challenges themselves need citations.

## Quotation rules

Quote sparingly; always attribute. Prefer linking the source over long verbatim copyrighted text.

## Popular ≠ true

“Most popular” media may be gathered for Round research, but popularity alone never establishes Proven. Popularity may justify *priority of investigation*.
