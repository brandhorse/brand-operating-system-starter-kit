# Usage Guide

How to turn this empty scaffold into your brand's live asset library.

You're already inside the Brand Operating System Starter Kit, so the "fork or clone" step has been done. This guide picks up from there.

## 1. Start in `00_Start-Here/`

This folder is your documentation layer. Before you upload a single asset, fill in:

- **Brand-Asset-Index.csv** — a row per asset. This becomes the searchable index your team uses when "where's the logo" happens for the hundredth time.
- **Naming-Convention.md** — pick a pattern and commit to it. The default (`brand-area-asset-purpose-version-date.ext`) works for most teams.
- **Contacts-and-Ownership.md** — who owns brand? Who approves new assets? Who onboards new team members?

Three decisions documented here will save you fifty arguments later.

## 2. Populate the folders

Replace the `.gitkeep` placeholder files with your actual assets. A few notes:

- **Use Git LFS** for anything over ~10 MB (raw Photoshop files, full-resolution photography, InDesign packages). See [Git LFS docs](https://git-lfs.com).
- **Don't commit licensed fonts** to a public repo. Keep them in `Fonts/Desktop/` for private forks only.
- **Archive, don't delete.** When a logo gets updated, move the old one to `Archive/` with a date. Future-you will need it.
- **One approved version, many drafts.** Keep drafts in `Working-Files/` subfolders. Only promote to the top level when approved.

## 3. Delete what you don't need

Not every brand needs every folder. If you don't have team photography, delete `Photography/Team/`. If you don't have an icon system yet, delete `Icons-and-Graphics/`. Lean beats comprehensive.

## 4. Document brand ownership

Assign a brand guardian (even if that's you, solo). Their responsibilities:

- Maintain this library
- Review high-visibility assets for consistency
- Update templates when the brand evolves (templates live upstream in `08_briefs-and-templates/`, not here)
- Train new team members
- Answer "where's the logo" questions

Add their name to `00_Start-Here/Contacts-and-Ownership.md` and commit.

## Where things actually live

The Brand Operating System Starter Kit deliberately spreads brand work across the chain of command. Some things you might expect to find in `assets/` are upstream:

| You're looking for… | It lives in… |
|---|---|
| The positioning statement | `04_positioning-and-messaging/positioning/` |
| Approved value props or claims | `04_positioning-and-messaging/claims-library/` |
| Voice guide and anti-voice | `05_voice-and-anti-voice/` |
| Do/don't rules and guardrails | `06_rules-and-guardrails/` |
| Approved storytelling or comm frameworks | `07_approved-canon/` |
| Campaign briefs and asset blueprints | `08_briefs-and-templates/` |
| Master/starter files for new content (blank Keynote, email signature template) | `08_briefs-and-templates/asset-blueprints/` |
| Shipped instances of campaigns or content | `09_execution/channel-shipped/` |

This folder (`09_execution/assets/`) holds the **raw building blocks**: logos, fonts, colors, photography, icons, and the rendered guidelines doc.

## Maintenance cadence

- **Monthly** — file any new assets created into the right folders. Don't let `Downloads/` become your library.
- **Quarterly** — audit for outdated assets and move them to `Archive/`. Check that the naming convention is still being followed.
- **Annually** — review the whole library. Refresh the rendered Guidelines PDF (it should reflect the current state of `04`, `05`, `06`, `07`). Consider whether the brand itself needs evolution.

## When you need more than structure

This scaffold is the structural half of brand asset management. The harder half is the *content* — the logos, the rendered guidelines, the approved messaging, the approval workflow. If you'd rather skip the DIY:

- [Brand Self-Audit (free)](https://brandhorse.com/brand-audit) — diagnostic across all five r.a.c.e.s.™ phases
- [R.A.C.E.S.™ Methodology Workbook ($79)](https://brandhorse.com/products/r-a-c-e-s-methodology-workbook) — the methodology in a single workbook + Notion companion
- [Brand Mastery Blueprint ($84.99)](https://brandhorse.com/products/brand-mastery-blueprint-bundle) — bundle, available in 3 formats
- [Brandhorse OS (membership)](https://brandhorse.com/request-access) — the governed operating system, end-to-end
- Assisted Installation (enterprise) — Brandhorse installs and runs the OS inside your team

## Help & feedback

This sub-section is part of the Brand Operating System Starter Kit. For issues, improvements, or to share a populated fork, see the BOS root [README.md](../../README.md) and [CONTRIBUTING.md](../../CONTRIBUTING.md).
