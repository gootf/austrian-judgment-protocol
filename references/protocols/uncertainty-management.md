---
name: uncertainty-management
description: "Judgment protocol (production-grade): uncertainty classification and design — Mises (case probability) + Taleb (black swans/antifragility) + O'Driscoll-Rizzo (time and ignorance). Use when judging under conditions where probabilities are unreliable and the future is unpredictable: the uncertainty layer of investment, pricing, pivots, and capital allocation. Invocation: (1) load framework without arguments; (2) with a scenario ('analyze the uncertainty of this capital commitment'); (3) with evidence coordinates ('case probability source text')."
version: 1.0.0
---

# Uncertainty Management — Uncertainty Judgment Protocol

**Sources**: Mises *Human Action* ch.VI | Taleb *Black Swan* + *Antifragile* | O'Driscoll & Rizzo *Time and Ignorance* | **Claims**: claims.yaml (13: 11 source-derived + 1 cross-source + 1 agent)

## How to Use
- **Without arguments**: load this framework (5 procedures + anti-patterns) as the baseline for uncertainty judgment
- **With a scenario**: give the decision context → run the 5 procedures in order (classification → pseudo-prediction → narrative → design → reversibility)
- **With a question**: `case probability` / `black swan` / `barbell` / `optionality` / `kill criterion` → read the corresponding claims + coordinates
- **Cross**: combine with other skills (authority for decision rights, diagnosis for time structure, knowledge for information location)

## Core Thesis
Uncertainty cannot be eliminated, but it can be classified, detected, and designed for: **case probability is not computable (Mises) → extreme tails are unpredictable but manageable (Taleb) → systems can benefit from volatility (Antifragile)**.

## Key Concepts
- **Class vs Case Probability** (M02/M03): class probability is computable by frequency (natural science); case probability is not computable (unique events/entrepreneurial judgment) — AI boundary: it can handle puzzles, not mysteries
- **Black Swan** (B01): rarity + extreme impact + retrospective (not prospective) predictability
- **Ludic Fallacy** (B02): gamified models ≠ real-world uncertainty — model-based certainty is an illusion
- **Narrative Fallacy** (B03): the mind forces patterns — "the Black Swan is what we leave out of simplification"
- **Triad** (AF01): fragile / robust / antifragile — systems that suffer from, withstand, or benefit from volatility
- **Barbell Strategy** (AF03): extreme conservatism + extreme aggressiveness (not the middle)
- **Optionality** (AF05): benefiting without knowing what will happen (Thales)
- **Fundamental Asymmetry** (AF04): antifragile systems require upside > downside
- **Time and Ignorance** (TI01): the passage of time makes knowledge obsolete — the temporal dimension of uncertainty

## Decision Procedures (5, executable)
1. **Uncertainty classification**: class vs case (M02-M04) → computable part goes to data/models, non-computable part goes to judgment (never substitute expected value for case probability — anti-pattern 1)
2. **Pseudo-prediction detection** (B02/B06): quantification preconditions = rejection signal ("demand market data when none exists") → switch to small experiments
3. **Narrative audit** (B03): does the current "story" pattern-simplify? no rewriting history after the decision (Decision Log discipline)
4. **System design** (AF03/AF05): barbell configuration (conservative core + exploratory aggression) + preserved optionality + asymmetry check (upside > downside)
5. **Reversibility assessment** (UX01): irreversible actions require the highest evidence bar → stage the commitment + predefine kill criteria

## Anti-patterns
1. Substituting expected-value computation for case-probability judgment (false precision)
2. "More data" as an excuse to delay decisions (ludic fallacy)
3. Betting everything on a single irreversible path (no barbell)
4. Rewriting what was known/unknown at decision time (retrospective distortion)

## CEO/CTO Translation
| Scenario | Application |
|---|---|
| Capital commitment | Staging + kill criteria (UX01) |
| Competitive shock | Distinguish computable risk from non-computable change |
| Pricing | Pseudo-prediction detection (reject "we need more data") |
| Innovation | Barbell: conservative core + exploratory aggression |

## Connections (cross-skill)
- entrepreneurial-judgment-authority (F&K): who judges in case-probability situations (judgment cannot be outsourced — M04)
- strategy-diagnosis (Rumelt): diagnosis before action on irreversible moves + time structure (UX01)
- hayek-knowledge-problem: root cause of pseudo-prediction (the center lacks time-and-place knowledge — H03)
- discovery-alertness: optionality = preserving the capacity to discover (AF05 ↔ K01)

## Provenance
- claims.yaml (13 claims; sources: Mises, Human Action; Taleb, The Black Swan & Antifragile; O'Driscoll & Rizzo, The Economics of Time and Ignorance)

## Scope & Limits
- **Boundaries**: provides no probability values; does not replace quantitative risk models (class probability goes to the data layer)
- **Gaps**: Kahneman bias catalog not yet incorporated (decision hygiene = separate evidence layer)
