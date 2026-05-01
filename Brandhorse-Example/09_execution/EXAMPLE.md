# 09_execution — Brandhorse populated example

> Shipped work. Where the chain produces output. Every shipped instance carries the brief ID it was built from and the compliance run that gated it.

---

## assets/

The asset library lives at `09_execution/assets/` (see that folder's README). Brandhorse's populated state:

- 9 top-level asset folders (Logos, Fonts, Colors, Photography, Icons-and-Graphics, Guidelines, plus 00_Start-Here and Archive)
- Asset index CSV in `00_Start-Here/Brand-Asset-Index.csv` with ~120 indexed assets
- Brand guidelines PDF in `Guidelines/Full-Guide/` rendered against `04`, `05`, `06`, `07`
- Quick-reference one-pagers for visual, voice, and social

The `Templates/` and `Messaging/` folders **do not exist in 09/assets/** by design. Templates live upstream in `08_briefs-and-templates/asset-blueprints/`. Messaging lives upstream in `04`, `05`, and `07`. (See the BOS root README for the full architecture argument.)

---

## campaigns/

**Campaign: BOS Starter Kit launch — April 2026**

| Field | Value |
|---|---|
| Brief | BR-2026-04-BOS-LAUNCH (`08_briefs-and-templates/campaign-briefs/`) |
| Status | Live |
| Launched | 2026-04-22 |
| Channels | Long-form blog, LinkedIn, X, email, podcast outreach |
| Compliance gate | Passed 2026-04-21 (run ID: CR-2026-04-21-001) |
| Performance review | See `10_scaling-and-learning/performance/` (ongoing) |

**Campaign: R.A.C.E.S.™ Methodology Workbook — Q1 2026**

| Field | Value |
|---|---|
| Brief | BR-2026-01-RACES-WORKBOOK |
| Status | Live |
| Launched | 2026-01-15 |
| Channels | Email nurture, LinkedIn, podcast |
| Compliance gate | Passed 2026-01-13 (run ID: CR-2026-01-13-002) |
| Performance review | Live; 487 sales to date |

---

## channel-shipped/

Organized by channel, then by date. Each folder holds the actual shipped artifact (rendered email HTML, posted LinkedIn screenshot, podcast episode link).

```
channel-shipped/
├── email/
│   └── 2026-04-22-bos-launch-delivery.html   (brief: BR-2026-04-BOS-LAUNCH)
├── linkedin/
│   └── 2026-04-22-bos-launch-day1.md
├── x/
│   └── 2026-04-22-bos-launch-thread.md
└── podcast/
    └── 2026-04-15-saas-radio-ep-127.md
```

Every shipped instance includes a frontmatter block citing the brief, the compliance run, and the rule IDs checked.

---

## compliance-runs/

| Run ID | Date | Asset | Brief | Result | Notes |
|---|---|---|---|---|---|
| CR-2026-04-21-001 | 2026-04-21 | BOS Starter Kit launch — full set | BR-2026-04-BOS-LAUNCH | Passed | Caught 2 BH-V-002 violations (non-italic headings); fixed pre-publish |
| CR-2026-04-15-003 | 2026-04-15 | Podcast pitch — SaaS Radio ep 127 | BR-2026-04-PODCAST-MARCH | Passed | No violations |
| CR-2026-04-08-001 | 2026-04-08 | LinkedIn post — "compliance is the wedge" | BR-2026-04-LI-WEEKLY | Failed → revised → passed | Initial draft used "world-class" (BH-V-003); rewritten and re-run |
| CR-2026-03-31-005 | 2026-03-31 | Newsletter — March recap | BR-2026-03-NEWSLETTER | Passed | Caught 1 BH-C-001 violation (claim without provenance); evidence row added |

**Aggregate signal (Q1 2026):**
- 47 compliance runs total
- 11 caught at least one violation pre-publish
- 0 violations shipped to production
- Most-caught rule: BH-V-003 (banned phrases) — 7 catches

---

## How this folder feeds upstream

Performance reviews in `10_scaling-and-learning/performance/` reference shipped campaigns by ID. Decisions log in `10_scaling-and-learning/decisions-log/` references compliance-run patterns to refine the rule library. When a rule fires too often or never, it's reviewed in `06_rules-and-guardrails/rule-library/` and either tightened or retired.
