# Austrian Judgment Protocol

**English** | [简体中文](README.zh-CN.md)

![License](https://img.shields.io/github/license/gootf/austrian-judgment-protocol)
![Release](https://img.shields.io/github/v/release/gootf/austrian-judgment-protocol)
![Stars](https://img.shields.io/github/stars/gootf/austrian-judgment-protocol)

**A production-grade judgment framework for founders, CEOs, and CTOs — six executable protocols from the Austrian school of economics, designed to be run by AI agents as a decision advisor.**

Most business frameworks answer *how to plan*. This one answers the harder questions: **who should decide, when, and on what evidence** — before you commit capital, respond to a competitor, delegate a decision, or bet on a new market.

## Who this is for

| You are | Your decisions | What the protocol does |
|---|---|---|
| **Founder** | Is this opportunity real? Is the demand there? Should I commit capital now or stage it? | Demand-side three-stage test; capitalist's three judgments; uncertainty staging with kill criteria |
| **CEO** | Competitive response, strategy review, goal setting, org design | Diagnose before acting; kernel check; asymmetry audit; reject goal-fallacy framing |
| **CTO / tech lead** | Tech debt vs. feature velocity, delegation to teams/agents, architecture vs. business exploration | Judgment classification (original vs. derived); knowledge distribution; capability-boundary check |
| **AI agent builder** | Embedding judgment into agent workflows | Executable decision procedures + anti-patterns + traceable evidence coordinates — not free-text advice |

## What it solves

| The situation | The common move (and the trap) | The protocol move |
|---|---|---|
| Sales declining | Attribute it to the market | Weak-signal check first (K04/KX03) |
| Competitor launches a free tier | Copy them immediately | Diagnose the real threat; respond from your own asymmetries (R01/R04) |
| New venture before committing money | Full commit, or endless "more data" | Three-stage demand test; stage the commitment, predefine kill criteria (P003, UX01) |
| Innovation stalled in a strong technical team | Hire more experts | Einstellung audit: one-sided knowledge actively *reduces* innovativeness (P006/P007) |
| "Who should decide this?" | By title, or by whoever shouts loudest | Original vs. derived judgment classification (FK02) |
| Head-office reports keep missing the real picture | More dashboards, more aggregation | Information anti-filtering: sample the raw periphery (HX01) |

## Why this framework

1. **Not another planning framework.** SWOT, OKR, and Porter answer "how do we plan?" They assume judgment is given. This framework makes judgment itself the object: who holds it, what evidence it rests on, how it fails.
2. **Not a book summary.** Theory is compressed into executable procedures and anti-patterns. All **84 claims are traceable** to 9 primary sources (Kirzner, Mises, Hayek, Taleb, O'Driscoll & Rizzo, Rumelt, Foss & Klein, Packard, Christensen) with evidence tier marked — *high* = directly from the author's text, *medium* = framework inference.
3. **A chain, not a grab bag.** Six protocols form one judgment chain: opportunity discovery → demand validation → strategy diagnosis → knowledge distribution → judgment authority → uncertainty design. Using any one alone is incomplete by design.
4. **Production-grade.** Versioned (v1.0.0), machine-checkable claim ledger, cross-referenced dependencies, explicit scope and gaps per protocol.

## How it works

The direct user is an **AI agent** (Hermes skill format): you describe a scenario, the agent routes to the relevant protocol and returns structured checks, anti-pattern audits, and evidence coordinates.

- **Install**: load `SKILL.md` as a skill; `references/protocols/` holds the six protocols.
- **Ask with a scenario**: "analyze this competitive threat", "should we delegate this decision?", "evaluate this opportunity" → routing table in SKILL.md.
- **Ask with a topic**: `alertness`, `case probability`, `strategy kernel`, `man on the spot`, `original judgment`, `three-stage process`.

## Quick start

```bash
# 1. Get the skill
git clone https://github.com/gootf/austrian-judgment-protocol.git
# 2. Copy SKILL.md + references/ into your agent's skills directory
#    (e.g. ~/.claude/skills/austrian-judgment-protocol/ or your agent's equivalent)
```

Then ask your agent — three ways it routes:

| You say | What you get |
|---|---|
| "A competitor just launched a free tier. Analyze this threat." | strategy-diagnosis: symptom vs challenge, kernel check, asymmetry audit (R01/R04) |
| "Should we commit capital to this new venture now?" | consumer-sovereignty: three-stage demand test, staging + kill criteria (P003, UX01) |
| "Can we delegate this decision to the team?" | hayek-knowledge-problem: time-and-place? aggregable? delegate + coordinate (HX01) |

## What it deliberately does NOT do

- **No prediction.** Case probability is not computable (Mises); anyone selling you forecasts where the future is unique is selling a narrative fallacy (Taleb).
- **No replacement of human judgment.** Original judgment cannot be outsourced (Foss & Klein); the framework's own boundary is stated in its uncertainty protocol: AI handles puzzles, the *mystery* stays with the human decision-maker.
- **No legal, financial, or investment advice.**

## Structure

```
SKILL.md        umbrella: routing table + usage
claims.yaml     84 claims, each traceable (author, book, evidence tier)
references/     protocols ×6 · glossary · patterns ×10 · cheatsheet
```

## Sources

Kirzner · Mises · Taleb (×2) · O'Driscoll & Rizzo · Rumelt · Hayek · Foss & Klein · Packard · Christensen

## License

MIT — see [LICENSE](LICENSE).
