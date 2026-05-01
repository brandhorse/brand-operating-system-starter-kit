# 10_scaling-and-learning — Brandhorse populated example

> Experiments, performance reviews, decisions log, recaps. The feedback loop that lets the brand operating system improve without losing coherence.

---

## experiments/

**Experiment: Email subject — "your starter kit" vs. "your brand operating system"**

| Field | Value |
|---|---|
| ID | EXP-2026-04-001 |
| Hypothesis | "your starter kit" reads as more useful (less abstract) than "your brand operating system" and will drive higher open rate |
| Variant A | "your brand asset library starter kit is ready" |
| Variant B | "your brand operating system starter kit is ready" |
| Sample | 50/50 split, n=300 per variant |
| Result | A: 64% open, B: 51% open. A wins. |
| Decision | Default to "your starter kit" framing for delivery emails |
| Logged in | `10_scaling-and-learning/decisions-log/` (DEC-2026-04-007) |

**Experiment: Compliance rule BH-V-004 (em-dash cap) — too tight?**

| Field | Value |
|---|---|
| ID | EXP-2026-03-002 |
| Hypothesis | The 1-em-dash-per-paragraph cap is causing rewrites that hurt cadence |
| Method | Track override rate over 30 days |
| Result | 19 of 24 long-form posts triggered the rule; 17 of those overrode it |
| Decision | Move BH-V-004 from High to Medium severity. Author override allowed without escalation. |
| Logged in | `06_rules-and-guardrails/rule-library/` (rule updated 2026-04-12) |

---

## performance/

**Q1 2026 review — campaigns in market**

| Campaign | Brief | Goal | Actual | Notes |
|---|---|---|---|---|
| R.A.C.E.S. Workbook | BR-2026-01-RACES-WORKBOOK | 300 sales | 487 | Exceeded; pattern: founder-LinkedIn drove 41% of sales |
| Brand Self-Audit | BR-2025-12-AUDIT | 1000 leads | 1342 | Exceeded; aging quotes in nurture sequence underperforming — refresh queued |
| Newsletter | Ongoing | ≥35% open | 38% avg | On target |

**Most-caught compliance rule (Q1):** BH-V-003 (banned phrases). 7 catches; 0 shipped. Suggests rule is doing its job; no change needed.

**Least-caught rule (Q1):** BH-A-001 (logo clear-space). 0 catches in 47 runs. Either the team has internalized it or compliance is missing something. Investigate Q2.

---

## decisions-log/

| ID | Date | Decision | Source | Reversed? |
|---|---|---|---|---|
| DEC-2026-04-001 | 2026-04-22 | Drop `Templates/` and `Messaging/` from `09_execution/assets/` | BOS architecture audit | No |
| DEC-2026-04-007 | 2026-04-26 | Use "starter kit" framing in delivery emails | EXP-2026-04-001 | No |
| DEC-2026-04-012 | 2026-04-12 | Soften BH-V-004 (em-dash) from High to Medium | EXP-2026-03-002 | No |
| DEC-2026-03-018 | 2026-03-15 | Banned "AI-powered" without specific feature | Anti-voice review | No |
| DEC-2026-02-003 | 2026-02-08 | Approved compliance-as-positioning-wedge | Insight 2 in `02_patterns-and-insights/` | No |

---

## recaps/

**Quarterly recap — Q1 2026 (one-paragraph version)**

> Brandhorse closed Q1 with the BOS Starter Kit packaged, the R.A.C.E.S.™ Workbook outperforming target by 62%, and zero compliance violations shipped to production across 47 runs. Two rules were refined based on override rates. Two campaigns are queued for Q2 (BOS launch + Brand Mastery Blueprint update). Strongest signal: the operator-founder ICP responded most reliably to founder-voice LinkedIn posts and the "compliance is the wedge" angle.

Full recap (multi-page) lives in the linked Notion doc — single source for board-style updates that can be referenced without re-derivation.

---

## How this folder feeds upstream

Decisions logged here update the rule library in `06_rules-and-guardrails/`, refine claims in `04_positioning-and-messaging/claims-library/`, and inform the next charter review in `00_charter/`. Recaps surface patterns that update `02_patterns-and-insights/`. The loop closes.
