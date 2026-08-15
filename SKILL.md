---
name: austrian-judgment-protocol
description: "Judgment protocol (production-grade): a unified Austrian-school decision framework for entrepreneurs, CEOs, and CTOs — Kirzner (opportunity discovery/alertness), Packard (demand-side entrepreneurship), Rumelt (strategy diagnosis), Hayek (knowledge problem), Foss & Klein (judgment authority), Mises/Taleb/O'Driscoll-Rizzo (uncertainty). Use when evaluating opportunities, strategic challenges, capital commitments, delegation decisions, organization design, or why innovation stalls. Invocation: (1) load without arguments for the routing table; (2) with a scenario ('analyze this competitive threat'); (3) with a topic (alertness/case probability/strategy kernel/man on the spot/original judgment/three-stage process)."
version: 1.0.0
---

# Austrian Judgment Protocol

A unified judgment framework built from six protocols, each compressing one theorist's core insights into executable decision procedures. The protocols are designed to be used together: they form a judgment chain, and their claims cross-reference each other (see claims.yaml).

## The Judgment Chain

1. **Opportunity discovery** — Kirzner: opportunities are *discovered* through alertness, not created by plans (discovery-alertness)
2. **Demand validation** — Packard: discovered opportunities must pass the three-stage demand-side test (consumer sovereignty)
3. **Strategy diagnosis** — Rumelt: diagnose the challenge before setting goals; build the kernel (diagnosis → guiding policy → coherent action)
4. **Knowledge distribution** — Hayek: decide who holds the decision — time-and-place knowledge cannot be centralized
5. **Judgment authority** — Foss & Klein (+ Christensen): allocate decision rights — original judgment stays with the owner; derived judgment is delegated with monitoring; check the capability boundary (what can we actually execute?) before committing resources
6. **Uncertainty design** — Mises/Taleb/O'Driscoll-Rizzo: classify uncertainty, reject pseudo-prediction, design for optionality and reversibility

## Routing Table

| If you face... | Use protocol | Key procedures |
|---|---|---|
| Market signal / new business / competitive change | discovery-alertness | search → weak signals → equilibration → demand validation |
| Evaluate whether a business is worth pursuing / why innovation stalls | consumer-sovereignty-and-entrepreneurship | three-stage check → knowledge-intersection audit → three judgments |
| Competitive threat / strategy review / goal setting | strategy-diagnosis | symptom vs challenge → kernel → bad-strategy filter → asymmetry audit |
| Should this decision be delegated / org design / reporting chains | hayek-knowledge-problem | time-and-place? → aggregable? → delegate + coordinate → sample raw periphery |
| Who should decide / delegation design / agency conflicts | entrepreneurial-judgment-authority | original vs derived → authority-knowledge match → constraints + monitoring |
| Capital commitment / pricing / pivot under uncertainty | uncertainty-management | classify → pseudo-prediction check → narrative audit → barbell design → reversibility |

## How to Use

- **Without arguments**: this routing table is the entry point; load the relevant protocol from references/protocols/.
- **With a scenario**: e.g. "analyze this market signal" → route to the protocol, run its decision procedures, check its anti-patterns.
- **With a topic**: `alertness` / `case probability` / `strategy kernel` / `man on the spot` / `original judgment` / `three-stage process` → read the corresponding claims in claims.yaml and the glossary.

## Terminology

Terms fall into three classes (marked in the source files):

- **standard term** — established in the discipline (e.g. consumer sovereignty, contract incompleteness, lead users)
- **author-specific term** — the theorist's own term, kept verbatim (e.g. man on the spot, Einstellung effect, triad, case probability)
- **framework-specific term** — this framework's own terms, defined at first use (e.g. central impossibility — no single mind can possess all dispersed knowledge; local judgment allocation; information anti-filtering; reversibility assessment)

## Provenance

- claims.yaml: 84 claims, each with author + book title. claim_type marks: source-derived (author's text) / agent-derived (framework inference, dependencies marked) / cross-source-derived (cross-book combination).
- Sources: Kirzner, *Competition and Entrepreneurship*; Mises, *Human Action*; Taleb, *The Black Swan* & *Antifragile*; O'Driscoll & Rizzo, *The Economics of Time and Ignorance*; Rumelt, *Good Strategy, Bad Strategy*; Hayek, "The Use of Knowledge in Society"; Foss & Klein, *Organizing Entrepreneurial Judgment*; Packard, *Consumer Sovereignty and Entrepreneurship*.

## Files

- `claims.yaml` — merged claim ledger (84 claims, ID prefixes: K/KX, M/B/AF/TI/UX, R/RX, H/HX, FK/FA/FX, CH, P/A)
- `references/protocols/` — six protocol files (full decision procedures, anti-patterns, scenario translations)
- `references/glossary.md` — terms
- `references/patterns.md` — 10 reusable decision patterns
- `references/cheatsheet.md` — decision rules
