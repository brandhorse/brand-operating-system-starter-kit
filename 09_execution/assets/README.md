# Assets

> Logos, fonts, colors, icons, photography, and the rendered guidelines doc. Downstream of governance — these files are the artifact, not the source.

**Stage:** `execution`  ·  **OS surface:** /app/assets

## What goes here

- `00_Start-Here/` — asset index CSV, naming convention, and ownership doc. Start here when populating.
- `Logos/` — primary, secondary, icon, monochrome, favicon/app-icon, working files.
- `Fonts/` — desktop, web, licensing.
- `Colors/` — swatches, design tokens, color documentation.
- `Photography/` — lifestyle, product, team, art-direction notes.
- `Icons-and-Graphics/` — icon sets and graphic elements.
- `Guidelines/` — the **published-form** brand guidelines PDF (the rendering of upstream rules into one human-readable document).
- `Archive/` — superseded assets. Keep them — don't delete.

## What doesn't go here

If you're tempted to put something in this folder that doesn't fit any of the
subfolders above, ask whether the artifact actually belongs upstream or
downstream. Most "where does this go?" moments come from skipping a step in
the chain of command.

Specifically:

- **Templates** (campaign briefs, asset blueprints, story arcs) live upstream in `08_briefs-and-templates/` — they're specs, not assets. Master/starter files (e.g., a blank Keynote deck) belong with their blueprint there.
- **Messaging** (positioning, value props, taglines, voice, claims) lives further upstream in `04_positioning-and-messaging/`, `05_voice-and-anti-voice/`, and `07_approved-canon/`. Assets render those decisions; they don't author them.
- **Shipped instances** (the actual Q2 launch deck, the published email, the social post that ran) live in `09_execution/channel-shipped/`, not here. This folder holds reusable building blocks.

## How this folder relates to the chain

The assets in here are not the source of brand decisions — they are the **artifact** of decisions made upstream:

```
00_charter
  → 01_evidence → 02_patterns-and-insights → 03_personas-and-profiles
  → 04_positioning-and-messaging → 05_voice-and-anti-voice
  → 06_rules-and-guardrails → 07_approved-canon → 08_briefs-and-templates
  → 09_execution/assets   ← you are here
  → 09_execution/channel-shipped → 09_execution/compliance-runs
  → 10_scaling-and-learning → 99_archive
```

The Guidelines PDF in this folder is the *published rendering* of decisions in `04`, `05`, `06`, and `07`. The Logos and Fonts here are the artifact form of the brand's visual identity — defensible because the upstream layers exist, not because they're pretty.

## Getting started

See [`USAGE.md`](USAGE.md) and the [Setup & Adoption Guide PDF](Brandhorse-Setup-and-Adoption-Guide.pdf) (published by Brandhorse, brand-agnostic content). The short version:

1. **Open `00_Start-Here/`** — fill in the asset index, naming convention, and ownership doc.
2. **Populate the folders** — replace `.gitkeep` placeholders with your actual files (Git LFS for anything over ~10 MB).
3. **Delete what you don't need** — not every brand needs every folder. Lean beats comprehensive.
4. **Document ownership** — someone has to be the brand guardian.

## What's NOT in here (and why)

- No licensed fonts (you need distribution rights).
- No client-sensitive or proprietary brand assets (this is a public scaffold).
- No large binaries — use [Git LFS](https://git-lfs.com) for anything over ~10 MB.
- No finished brand strategy docs — this is structure, not strategy. Strategy lives upstream.

## Naming convention

All files in this folder follow the convention defined in `00_Start-Here/Naming-Convention.md`. The default is:

```
brand-area-asset-purpose-version-date.ext
```

## When you need more than structure

The Brand Operating System Starter Kit (this scaffold) is open-source and free. If you want the methodology, the running OS, or installation help:

| Tier | What it is |
|---|---|
| [Brand Self-Audit](https://brandhorse.com/brand-audit) — *free* | 10-minute diagnostic that scores your brand across all five r.a.c.e.s.™ phases. |
| [R.A.C.E.S.™ Methodology Workbook](https://brandhorse.com/products/r-a-c-e-s-methodology-workbook) — *$79* | The complete r.a.c.e.s.™ methodology in a single workbook + Notion companion. |
| [Brand Mastery Blueprint](https://brandhorse.com/products/brand-mastery-blueprint-bundle) — *$84.99* | Bundle, available in 3 formats. |
| [Brandhorse OS](https://brandhorse.com/request-access) — *membership* | The governed brand operating system. Run r.a.c.e.s.™ end-to-end with traceable evidence and approved canon. |
| Assisted Installation — *enterprise* | Brandhorse installs and runs the OS inside your team. Hands-on rollout for B2B and DTC operators. |

## License & maintenance

This scaffold is part of the Brand Operating System Starter Kit, MIT-licensed, maintained by [Brandhorse](https://brandhorse.com). Use it for personal brands, client brands, commercial work — anything. Attribution appreciated, not required.
