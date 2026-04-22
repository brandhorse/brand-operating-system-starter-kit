# Brand Asset Library Template

> The open-source scaffold we use at [Brandhorse](https://brandhorse.com) to organize brand assets across design, marketing, web, and operations. Fork it, populate it, make it yours.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Maintained by Brandhorse](https://img.shields.io/badge/maintained%20by-brandhorse-3b5ad6)

---

## What this is

Every brand has the same Monday-morning problem: your team needs a social graphic, a pitch deck, an email template — and everyone starts from scratch. Thirty minutes to find the right logo. Guessing at which blue is "the blue." By Friday, your carefully crafted brand looks like five different companies.

This repo is the structural half of the fix: a clean, opinionated folder structure for a brand asset library, ready to populate with your logos, fonts, colors, templates, photography, messaging, and guidelines. It pairs with our in-depth guide — [Creating Brand Assets: Templates, Tools, and Workflow for Consistency](https://brandhorse.com/insights/creating-brand-assets-templates-tools-workflow) — which walks through *what* to put in each folder and *how* to set up the workflow around it.

We eat our own cooking: the Brandhorse brand itself runs on this scaffold, and so do several of our sister brands across the Stroelli portfolio. Populated examples are listed below.

## Who it's for

- Founders and operators setting up brand assets for the first time
- Marketing and design leaders tired of "brand-final-v3-FINAL.png"
- Agencies and consultants shipping brand systems as deliverables
- Brand ops / design ops teams who want a version-controlled source of truth

## The structure

```
Brand-Asset-Library/
├── 00_Start-Here/          # asset index CSV, naming convention, ownership doc
├── Logos/                  # Primary, Secondary, Icon, Monochrome,
│                           # Favicon-App-Icons, Approved, Working-Files, Archive
├── Fonts/                  # Desktop, Web, Licensing-and-Usage
├── Colors/                 # Swatches, Tokens, Documentation
├── Templates/              # Documents, Email, Presentations, Signatures, Social-Media
├── Photography/            # Lifestyle, Product, Team, Usage-Guidelines
├── Icons-and-Graphics/
├── Messaging/              # Boilerplate, Messaging-Framework, Taglines-and-CTAs, Voice-and-Tone
├── Guidelines/             # Full-Guide, Quick-Reference
└── Archive/                # outdated versions — keep, don't delete
```

Each top-level folder has its own `README.md` explaining what belongs there and how to name files.

## Two ways to use it

### Option 1 — Fork or use as a template (recommended)

Click **"Use this template"** above (or fork) to get your own copy. You'll have full git history, collaboration with your team via PRs, and the ability to pull upstream updates when we ship improvements.

### Option 2 — Download the Starter Kit bundle

If you'd rather skip GitHub, grab the [Brand Asset Library Starter Kit](https://brandhorse.com/resources/brand-asset-library-starter-kit) — the repo as a zip, plus a Setup & Adoption Guide PDF and a filled-in Brandhorse example showing what a populated library looks like.

## Getting started in 5 steps

See [USAGE.md](USAGE.md) for the full walkthrough. The short version:

1. **Fork or use this template** — create your own copy
2. **Open `00_Start-Here/`** — start with the asset index, naming convention, and ownership doc
3. **Populate the folders** — replace `.gitkeep` placeholders with your actual files (use Git LFS for large binaries)
4. **Delete what you don't need** — not every brand needs every folder
5. **Document ownership** — someone needs to be the brand guardian

## What's in here already

- `00_Start-Here/Brand-Asset-Index.csv` — starter asset index (populate with your files)
- `00_Start-Here/Naming-Convention.txt` — recommended naming pattern
- `00_Start-Here/Contacts-and-Ownership.txt` — who owns what
- A folder `README.md` in each top-level directory explaining what belongs there

## What's NOT in here (and why)

- No licensed fonts (you need distribution rights)
- No client-sensitive or proprietary brand assets
- No large binaries — use [Git LFS](https://git-lfs.com) for anything over ~10 MB
- No finished brand strategy docs — this is structure, not content

## Populated examples

We run this scaffold at the brands we own. Where possible, we expose populated public forks as proof:

| Brand | Repo | Status |
|---|---|---|
| Brandhorse | *(coming soon)* | Public fork in progress |
| 3 Day Website | *(coming soon)* | Public fork planned |

More examples get added as we roll them out. If you've populated a fork and want to be listed, open a PR against this README.

## The Brandhorse system this fits into

This repo is the free, standalone structure. It fits inside a larger system:

- **Free** — this repo + the [companion article](https://brandhorse.com/insights/creating-brand-assets-templates-tools-workflow) + the [Starter Kit bundle](https://brandhorse.com/resources/brand-asset-library-starter-kit)
- **$29** — [Asset Library Dashboard](https://brandhorse.com/products/asset-library-dashboard): the Notion layer that sits on top of this structure (searchable index, approval tracking, ownership)
- **$149** — [Visual Identity System](https://brandhorse.com/products/visual-identity-system): complete system with all templates, frameworks, and workflows
- **$497** — [Complete R.A.C.E.S.™ System](https://brandhorse.com/products/complete-races-system): the whole methodology
- **Enterprise** — [Brandhorse OS](https://brandhorse.com/request-access): governed brand operating system

## Contributing

Issues and PRs are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md). Ways to contribute:

- Suggest folder-structure improvements (open an issue)
- Add documentation to a folder README that's thin
- Submit a case study of your own populated fork
- Flag a better naming convention, file format, or workflow

## License

MIT — see [LICENSE](LICENSE). Use it for personal brands, client brands, commercial work, anything. Attribution appreciated but not required.

## Maintained by

[**Brandhorse**](https://brandhorse.com) — we help founders and operators turn brand positioning into a governed, repeatable operating system. This repo is one piece of that system, open-sourced.

If the structure saves you time, [give the repo a ⭐](https://github.com/brandhorse/brand-asset-library) and let us know.
