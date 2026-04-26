# Brand Operating System Starter Kit

A starter file system for founders whose brand decisions, evidence, messaging,
and assets are scattered across docs, chats, drives, and decks. 12
top-level folders ordered by the chain of command — evidence, patterns,
insights, rules, canon — with assets sitting where they belong: downstream.

The same scaffold we run at Brandhorse, open-sourced. MIT licensed.

## Why this scaffold

Most brand asset libraries start with `Logos / Fonts / Colors / Templates` at
the top. That order teaches the wrong thing — it implies that assets are the
product of brand work, when they're the downstream artifact of decisions made
earlier in the chain.

This scaffold inverts that. The top-level folders mirror the chain of command:
**evidence → patterns & insights → personas → positioning & messaging → voice
→ rules → canon → briefs → execution**. Logos and fonts are still here — they
live under `09_execution/assets/` where they belong: downstream of the
decisions that make them defensible.

## The structure

```
brand-operating-system/
├── 00_charter/                  # The non-negotiables
│   ├── truth-set/
│   ├── decision-rights/
│   └── charter/
├── 01_evidence/                 # Raw signals — quotes, observations, competitive proof, market data
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
│   ├── assets/
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

Each top-level folder has a `README.md` explaining what belongs there, why,
and how it relates to the rest of the chain. 39 subfolders
in total.

## Getting started

See [USAGE.md](USAGE.md) for the five-step adoption guide. Short version:

1. **Fork or clone this repo** — create your own copy
2. **Open `00_charter/`** — write your truth set, decision rights, and charter
3. **Populate `01_evidence/`** — drop in customer quotes, competitive proof, market signals
4. **Work upstream** — patterns and insights come from evidence, not the other way
5. **Document ownership** — someone needs to be the brand guardian

## Who this is for

- Founders setting up brand operations for the first time
- Operators tired of "where does this live?" being a daily question
- Agencies and consultants shipping brand systems as deliverables
- Brand ops / design ops teams who want a version-controlled source of truth

## What's NOT in here (and why)

- **Licensed fonts** — you need distribution rights
- **Client-sensitive or proprietary brand assets** — this is structure, not your content
- **Large binaries** — use Git LFS for anything over ~10 MB
- **Finished brand strategy docs** — this is the file system; the content is yours

## When you need more than structure

This repo is the free, standalone scaffold. It fits inside a larger system:

| Tier | What you get |
| --- | --- |
| **Free** | This repo + the [companion article](https://brandhorse.com/insights/creating-brand-assets-templates-tools-workflow) + the [Starter Kit bundle](https://brandhorse.com/resources/brand-operating-system-starter-kit) |
| **Notion Dashboard** | Notion-native search, approval, and ownership on top of the scaffold |
| **Visual Identity System** | Production-ready templates, frameworks, and workflows |
| **Complete R.A.C.E.S.™ System** | The whole methodology in a Notion ecosystem |
| **Brandhorse OS** | Governed operating system with R.A.C.E.S. built in |

## License

MIT — see [LICENSE](LICENSE). Use it for personal brands, client brands,
commercial work, anything. Attribution appreciated but not required.

## Maintained by

[Brandhorse](https://brandhorse.com) — we help founders and operators turn
brand positioning into a governed, repeatable operating system. This repo is
one piece of that system, open-sourced.

If the scaffold saves you time, give the repo a ⭐ and let us know.
