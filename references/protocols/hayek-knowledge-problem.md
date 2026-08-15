---
name: hayek-knowledge-problem
description: "Judgment protocol (production-grade): the knowledge problem — Hayek (dispersed knowledge/tacit knowledge/central impossibility/price mechanism/local judgment allocation). Use when analyzing why knowledge cannot be centralized, why central plans or reporting chains distort, whether a decision should be local or central, and the limits of aggregated information (CEO/CTO: organization design, reporting chains, delegated decisions). Invocation: (1) load framework without arguments; (2) with a scenario ('should this decision be delegated?'); (3) with a topic (H01-H05/dispersed knowledge/man on the spot)."
version: 1.0.0
---

# Hayek Knowledge Problem

**Source**: "The Use of Knowledge in Society", AER XXXV(4), 1945, repr. Individualism and Economic Order (1948) | **Claims**: claims.yaml (7: 5 source-derived + 2 cross-source)

## How to Use
- **Without arguments**: load this framework (H01-H05 + 2 cross-source rules) as the baseline for knowledge-distribution judgment
- **With a scenario**: give the decision context → run the 4 Decision Use steps (depends on time-and-place knowledge? → aggregable? → delegate + coordinate → report sampling)
- **With a topic**: `dispersed knowledge` / `tacit knowledge` / `central impossibility` / `man on the spot` → read the corresponding claims
- **Cross**: authority (F&K: decision-rights configuration), strategy (Rumelt: kernel completeness), uncertainty (Taleb: root cause of pseudo-prediction)

## Core Claims

### H01 — Knowledge of circumstances is dispersed
> "the knowledge of the circumstances of which we must make use never exists in concentrated or integrated form but solely as the dispersed bits of incomplete and frequently contradictory knowledge which all the separate individuals possess."
> "It is rather a problem of how to secure the best use of resources known to any of the members of society... a problem of the utilization of knowledge which is not given to anyone in its totality."

claim_type: source-derived | evidence: Hayek, The Use of Knowledge in Society

### H02 — Relevant knowledge is often tacit / local / time-specific
> "there is beyond question a body of very important but unorganized knowledge which cannot possibly be called scientific...: the knowledge of the particular circumstances of time and place."
> "practically every individual has some advantage over all others because he possesses unique information of which beneficial use might be made, but of which use can be made only if the decisions depending on it are left to him or are made with his active co-operation."
> Examples: the shipper (empty tramp-steamer journeys), the estate agent (temporary opportunities), the arbitrageur (local price differences).

claim_type: source-derived | evidence: Hayek, The Use of Knowledge in Society

### H03 — Central impossibility: a central planner cannot reconstruct all relevant knowledge
> "the 'data' from which the economic calculus starts are never for the whole society 'given' to a single mind which could work out the implications and can never be so given."
> "the sort of knowledge with which I have been concerned is knowledge of the kind which by its nature cannot enter into statistics and therefore cannot be conveyed to any central authority in statistical form." — statistics abstract away location, quality, and other particulars that may be significant for the specific decision.
> "central planning based on statistical information by its nature cannot take direct account of these circumstances of time and place and that the central planner will have to find some way or other in which the decisions depending on them can be left to the 'man on the spot.'"

claim_type: source-derived | evidence: Hayek, The Use of Knowledge in Society

### H04 — Coordination mechanisms (price system) work WITHOUT central possession
> "We must look at the price system as such a mechanism for communicating information... The most significant fact about this system is the economy of knowledge with which it operates, or how little the individual participants need to know in order to be able to take the right action."
> Tin example: tens of thousands of people adjust correctly "without an order being issued, without more than perhaps a handful of people knowing the cause."
> "Civilization advances by extending the number of important operations which we can perform without thinking about them" (Whitehead).

claim_type: source-derived | evidence: Hayek, The Use of Knowledge in Society

### H05 — Organizations need local judgment allocation (decentralization + coordination)
> "the ultimate decisions must be left to the people who are familiar with these circumstances, who know directly of the relevant changes and of the resources immediately available to meet them... We must solve it by some form of decentralization."
> But the "man on the spot" still needs communication to fit decisions into the larger pattern — decentralization + coordination signals, not isolation.
> Anti-Schumpeter: "To assume all the knowledge to be given to a single mind... is to assume the problem away and to disregard everything that is important and significant in the real world."

claim_type: source-derived | evidence: Hayek, The Use of Knowledge in Society

## Cross-source Rules

### Anti-Central-Planning Rule (H01-H03 + F&K FK11)
> Reporting chains produce filtered, lagging, second-hand knowledge at HQ. Any decision input that arrives as an aggregate/statistic has already abstracted away the time-and-place detail that H02 says is decision-relevant. Therefore: **do not let central decisions rest on centrally-aggregated information alone — sample the raw periphery (information anti-filtering).**

claim_type: cross-source-derived | depends_on: [H01, H02, H03, FK11]

### Local Knowledge Recognition Rule (H02 + H05)
> When a decision depends on time-and-place knowledge, the decision right should sit with the person closest to the facts ("man on the spot"), with central authority limited to coordination constraints (boundaries, not scripts).

claim_type: cross-source-derived | depends_on: [H02, H05, FK02, FK10]

## Decision Use

1. Before centralizing a decision, ask: does it depend on knowledge of particular circumstances of time and place? (H02)
2. If yes, can that knowledge be conveyed in statistical/aggregate form without losing the decision-relevant detail? (H03)
3. If no → leave the decision to the man on the spot; central authority sets constraints and coordination signals, not the content of the decision. (H05)
4. When evaluating any centrally-produced report, treat it as an abstraction: verify against raw periphery samples. (H03 + anti-central-planning rule)

*claim_type: source-derived = Hayek's text; cross-source-derived = combination with F&K claims (FK11/FK02/FK10).*

## Scope & Limits
- **Gaps**: only the essay's core passages compiled (p1-7); the surrounding essays of Individualism and Economic Order are not covered
