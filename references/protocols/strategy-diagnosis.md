---
name: strategy-diagnosis
description: "Judgment protocol (production-grade): strategy diagnosis — Rumelt (diagnosis first/strategy kernel/bad strategy detection/asymmetric advantage/resource commitment). Use when diagnosing strategic challenges, building a strategy kernel, detecting bad strategy (slogans/ambition/fluff), identifying asymmetric advantages, and deciding resource commitments (CEO: competitive response, strategy review, goal setting). Invocation: (1) load framework without arguments; (2) with a scenario ('analyze this competitive threat'); (3) with a topic (kernel/bad strategy/asymmetry)."
version: 1.0.0
---

# Strategy Diagnosis

**Source**: Good Strategy, Bad Strategy (Rumelt 2011) | **Claims**: claims.yaml (8: 5 source-derived + 3 cross-source)

## How to Use
- **Without arguments**: load this framework (R01-R05 + 3 cross-source rules) as the baseline for strategic judgment
- **With a scenario**: competitive threat / goal setting / strategy proposal → run the 5 Decision Use steps (symptoms vs challenge → kernel → bad-strategy filter → asymmetry audit → resource commitment)
- **With a topic**: `kernel` / `bad strategy` / `asymmetry` / `diagnosis` → read the corresponding claims
- **Cross**: authority (F&K: who judges), knowledge (Hayek: coordination constraints), demand (Packard: need validation first)

## Core Claims

### R01 — Diagnosis before action
> "The first step toward effective strategy is diagnosing the specific structure of the challenge rather than simply naming performance goals."
> "The core of strategy work is always the same: discovering the critical factors in a situation and designing a way of coordinating and focusing actions to deal with those factors." — strategy is NOT ambition/leadership/vision/planning/economic logic (Rumelt explicitly rejects equating them).

claim_type: source-derived | evidence: Rumelt, Good Strategy, Bad Strategy

### R02 — The Strategy Kernel (three elements)
> "The kernel of a strategy contains three elements: a diagnosis, a guiding policy, and coherent action."
> 1. **Diagnosis**: defines/explains the nature of the challenge; simplifies overwhelming complexity by identifying certain aspects as critical.
> 2. **Guiding policy**: overall approach chosen to cope with the obstacles identified in the diagnosis — "like a signpost, marking the direction forward but not defining the details of the trip."
> 3. **Coherent action**: feasible coordinated policies, resource commitments, and actions designed to carry out the guiding policy — not "implementation details," they are "the punch in the strategy."
> "The kernel is not based on any one concept of advantage... It leaves out visions, hierarchies of goals... All of these are supporting players."

claim_type: source-derived | evidence: Rumelt, Good Strategy, Bad Strategy

### R03 — Bad strategy detection (anti-patterns)
> "Bad strategy tends to skip over pesky details such as problems. It ignores the power of choice and focus, trying instead to accommodate a multitude of conflicting demands and interests... bad strategy covers up its failure to guide by embracing the language of broad goals, ambition, vision, and values."
> Signature sins: **fluff**, **slogans + high-sounding goals**, **blue-sky objectives**, **template-style strategy**, "Let's win" goals. Bad strategy has NO diagnosis of the underlying malady (2008 financial crisis example: "there was no official diagnosis").
> Detection test: if it does not answer "what challenge?" and "why this action?", it is not strategy.

claim_type: source-derived | evidence: Rumelt, Good Strategy, Bad Strategy

### R04 — Advantage comes from asymmetric differences
> "advantage is rooted in differences—in the asymmetries among rivals. In real rivalry, there are an uncountable number of asymmetries. It is the leader's job to identify which asymmetries are critical—which can be turned into important advantages."
> Good strategy "creates or reveals a decisive asymmetry"; e.g., imposing asymmetric costs on an opponent, high ground as natural asymmetry.

claim_type: source-derived | evidence: Rumelt, Good Strategy, Bad Strategy

### R05 — Resource allocation follows diagnosis
> "Coherent actions are feasible coordinated policies, resource commitments, and actions designed to carry out the guiding policy." — resource commitment is part of the kernel, not a downstream implementation step.

claim_type: source-derived | evidence: Rumelt, Good Strategy, Bad Strategy

## Cross-source Rules

### Anti-Goal-Fallacy Rule (R01 + R03)
> When asked "what should our goal be?" (increase sales, become the AI leader...), refuse the goal frame: first produce the diagnosis ("why is this a challenge?"). Goals without diagnosis are bad strategy (R03) — connects to Packard A001 (need-validation precedes expenditure).

claim_type: cross-source-derived | depends_on: [R01, R03, P001]

### Kernel Completeness Check (R02 + F&K FK02 + Hayek H05)
> Any strategic proposal must expose its kernel: diagnosis (whose judgment? — F&K), guiding policy (coordination constraints — Hayek), coherent action (resource commitments). A proposal missing any element is incomplete; a "strategy" that is only goals/vision fails R03.

claim_type: cross-source-derived | depends_on: [R02, FK02, H05]

### Competitive-Response Rule (R04 + P002)
> When a competitor acts (free tier, price cut, feature launch): do NOT copy the competitor's action. Diagnose first — is the threat to your customers' value perception, your segment, your economics? Then identify YOUR critical asymmetries (R04) and respond from them, not from the competitor's move.

claim_type: cross-source-derived | depends_on: [R01, R04, P002]

## Decision Use

1. Symptom vs challenge: sales decline, churn, competitive pressure are **symptoms** — diagnose the underlying challenge before any action (R01).
2. Build the kernel: diagnosis → guiding policy → coherent action (R02). Expose it in every decision memo.
3. Bad-strategy filter: reject any proposal that is goals/slogans/ambition without diagnosis and coherent action (R03).
4. Advantage audit: ask "what asymmetries between us and rivals are critical here?" before responding to competitive moves (R04).
5. Resource commitment is part of strategy, not downstream: allocate resources as coherent action, tied to the guiding policy (R05).

*claim_type: source-derived = Rumelt's text; cross-source-derived = combination with Packard/F&K/Hayek claims.*

## Scope & Limits
- **Gaps**: only kernel-related concepts compiled; the book's case studies and peripheral chapters are not extracted
