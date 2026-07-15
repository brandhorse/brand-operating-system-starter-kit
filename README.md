# brand operating system starter kit

a starter file system for founders whose brand decisions, evidence, messaging, and assets are scattered across docs, chats, drives, and decks. 12 top-level folders ordered by the chain of command — evidence, patterns, insights, rules, canon — with assets sitting where they belong: downstream.

the same scaffold we run at brandhorse, open-sourced. MIT licensed.

> **new here? open [`00_START_HERE.md`](00_START_HERE.md) first.** it's the short, ordered path from empty scaffold to a grounded foundation — and it will keep you out of the single most common trap: writing your charter before you have the evidence to back it.

## why this scaffold

most brand asset libraries start with `Logos / Fonts / Colors / Templates` at the top. that order teaches the wrong thing — it implies assets are the product of brand work, when they're the downstream artifact of decisions made earlier in the chain.

this scaffold inverts that. the top-level folders mirror the chain of command: evidence → patterns & insights → personas → positioning & messaging → voice → rules → canon → briefs → execution. logos and fonts are still here — they live under `09_execution/assets/` where they belong: downstream of the decisions that make them defensible.

## authority vs. build order — read this before you start

the folder numbers show **authority** — what inherits from what. `00_charter/` is numbered first because it's the constitutional layer every downstream folder inherits from.

**that is not the order you populate them in.** you build the charter *from evidence* — never author it cold. write a charter before you've done the research and you'll produce a brand nobody can defend the moment it's challenged. so:

```
authority (what inherits from what):   00 → 01 → 02 → 03 → 04 → 05 → 06 → 07 → 08 → 09 → 10
build order (what you populate first): 01 → 02 → 03, then 00 (derived), then 04 → 05 → 06 → 07 → 08 → 09 → 10
```

**00 is where everything inherits from. 01 is where you start.** the full guided path — audit → research pass → charter pass → ratify — is in [`00_START_HERE.md`](00_START_HERE.md).

## the structure

```
brand-operating-system/
├── 00_charter/                  # The non-negotiables — DERIVED from evidence, not authored cold
│   ├── truth-set/
│   ├── decision-rights/
│   └── charter/
├── 01_evidence/                 # ▶ START HERE. Raw signals — quotes, competitive proof, market data
│   ├── customer-quotes/
│   ├── competitive/
│   ├── market-signals/
│   └── internal-proof/
├── 02_patterns-and-insights/    # What the evidence reveals
│   ├── patterns/
│   ├── insights/
│   └── anti-patterns/
├── 03_personas-and-profiles/    # Who you serve, who you don't, who you used to
│   ├── icp/
│   ├── secondary-personas/
│   └── anti-personas/
├── 04_positioning-and-messaging/  # Governed positioning, message map, claims library
│   ├── positioning/
│   ├── message-map/
│   └── claims-library/
├── 05_voice-and-anti-voice/     # How the brand speaks — and the things it can never say
│   ├── voice/
│   ├── anti-voice/
│   └── voice-overrides/
├── 06_rules-and-guardrails/     # The rule library that compliance runs against
│   ├── rule-library/
│   ├── must-avoid/
│   └── must-include/
├── 07_approved-canon/           # The frameworks the brand has committed to
│   ├── storytelling-frameworks/
│   ├── communication-frameworks/
│   └── brand-personas/
├── 08_briefs-and-templates/     # Briefs anchor every campaign
│   ├── campaign-briefs/
│   ├── asset-blueprints/
│   └── story-arcs/
├── 09_execution/                # Shipped work
│   ├── assets/                  # Logos, fonts, colors, photography, icons, rendered guidelines
│   │                            # (templates live upstream in 08; messaging in 04/05/07)
│   ├── campaigns/
│   ├── channel-shipped/
│   └── compliance-runs/
├── 10_scaling-and-learning/     # Experiments, performance reviews, and the decisions log
│   ├── experiments/
│   ├── performance/
│   ├── decisions-log/
│   └── recaps/
└── 99_archive/                  # Deprecated — kept, not deleted
    ├── deprecated-positioning/
    ├── retired-campaigns/
    └── old-assets/
```

each top-level folder has a `README.md` explaining what belongs there, why, and how it relates to the rest of the chain. 39 subfolders in total.

## getting started

the guided path is in **[`00_START_HERE.md`](00_START_HERE.md)** (audit → research pass → charter pass → ratify). if you just want to populate the scaffold directly, here's the short version — **in build order**:

1. **fork or clone this repo** — create your own copy. (details in [USAGE.md](https://github.com/brandhorse/brand-operating-system-starter-kit/blob/main/USAGE.md))
2. **populate `01_evidence/` first** — customer quotes, competitive proof, market signals, and whatever internal proof you have. ~30 rows before you synthesize anything. the [research-pass prompt](01_evidence/README.md) does this for you.
3. **work up to patterns and personas** — `02_patterns-and-insights/`, then `03_personas-and-profiles/`. what recurs? who's it for?
4. **derive your charter** — now, with evidence behind you, populate `00_charter/`. the [charter-drafting pass](00_charter/README.md) turns your evidence into draft clauses. ratify it before you build further.
5. **articulate downstream** — positioning → voice → rules → canon, each inheriting from the ratified charter and citing evidence.
6. **document ownership** — someone needs to be the brand guardian.

## who this is for

- founders setting up brand operations for the first time
- operators tired of "where does this live?" being a daily question
- agencies and consultants shipping brand systems as deliverables
- brand ops / design ops teams who want a version-controlled source of truth

## what's NOT in here (and why)

- licensed fonts — you need distribution rights
- client-sensitive or proprietary brand assets — this is structure, not your content
- large binaries — use Git LFS for anything over ~10 MB
- finished brand strategy docs — this is the file system; the content is yours

## when you need more than structure

this repo is the free, standalone scaffold. it fits inside the brandhorse ladder:

| step | what you get | where |
| --- | --- | --- |
| **find your gaps** (free) | a 5–10-minute brand self-audit that scores you across the chain of command and tells you which folders to fill first. | [brandhorse.com/brand-audit](https://brandhorse.com/brand-audit) |
| **learn the mindset** (free) | brand mastery essentials — the free eBook that grounds everything below. | [brandhorse.com/brand-mastery-essentials](https://brandhorse.com/brand-mastery-essentials) |
| **learn the method** ($79) | the r.a.c.e.s.™ methodology workbook — how to actually run the chain of command from evidence to execution. the thinking behind every folder in this scaffold. | [brandhorse.com/products/races-methodology-workbook](https://brandhorse.com/products/races-methodology-workbook) |
| **run it in the os** | brandhorse os — the scaffold instrumented as a governed operating system. patterns, rules, briefs, compliance runs, performance loop, all version-controlled with r.a.c.e.s. built in. | [brandhorse.com/request-access](https://brandhorse.com/request-access) |

## license

MIT — see **[LICENSE](https://github.com/brandhorse/brand-operating-system-starter-kit/blob/main/LICENSE)**. use it for personal brands, client brands, commercial work, anything. attribution appreciated but not required.

## maintained by

**[brandhorse](https://brandhorse.com/)** — we help founders and operators turn brand positioning into a governed, repeatable operating system. this repo is one piece of that system, open-sourced.

if the scaffold saves you time, give the repo a ⭐ and let us know.
