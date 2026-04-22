# Usage Guide

How to turn this empty scaffold into your brand's live asset library.

## 1. Fork or clone

Click **"Use this template"** on the GitHub repo page (recommended — it starts you clean without the full commit history) or fork it. If you're working solo, cloning is fine too.

```bash
git clone https://github.com/<your-org>/brand-asset-library.git
cd brand-asset-library
```

## 2. Start in `00_Start-Here/`

This folder is your documentation layer. Before you upload a single asset, fill in:

- **Brand-Asset-Index.csv** — a row per asset. This becomes the searchable index your team uses when "where's the logo" happens for the hundredth time.
- **Naming-Convention.txt** — pick a pattern and commit to it. The default (`brand-area-asset-purpose-version-date.ext`) works for most teams.
- **Contacts-and-Ownership.txt** — who owns brand? Who approves new assets? Who onboards new team members?

Three decisions documented here will save you fifty arguments later.

## 3. Populate the folders

Replace the `.gitkeep` placeholder files with your actual assets. A few notes:

- **Use Git LFS** for anything over ~10 MB (raw Photoshop files, full-resolution photography, InDesign packages). See [Git LFS docs](https://git-lfs.com).
- **Don't commit licensed fonts** to a public repo. Keep them in `Fonts/Desktop/` for private forks only.
- **Archive, don't delete.** When a logo gets updated, move the old one to `Logos/Archive/` with a date. Future-you will need it.
- **One approved version, many drafts.** Keep drafts in `Working-Files/` subfolders. Only promote to the top level when approved.

## 4. Delete what you don't need

Not every brand needs every folder. If you don't have team photography, delete `Photography/Team/`. If you don't send email newsletters, delete `Templates/Email/`. Lean beats comprehensive.

## 5. Document brand ownership

Assign a brand guardian (even if that's you, solo). Their responsibilities:

- Maintain this library
- Review high-visibility assets for consistency
- Update templates when the brand evolves
- Train new team members
- Answer "where's the logo" questions

Add their name to `00_Start-Here/Contacts-and-Ownership.txt` and commit.

## Maintenance cadence

- **Monthly** — file any new assets created into the right folders. Don't let `Downloads/` become your library.
- **Quarterly** — audit for outdated assets and archive them. Check that your naming convention is still being followed.
- **Annually** — review the whole library. Refresh templates. Consider whether the brand itself needs evolution.

## Pulling upstream improvements

We ship updates to the scaffold occasionally. If you used the "Use this template" button, pulling them in is manual — diff against the upstream repo and cherry-pick what you want. If you forked, you can add the upstream as a remote:

```bash
git remote add upstream https://github.com/brandhorse/brand-asset-library.git
git fetch upstream
git merge upstream/main  # resolve conflicts as needed
```

## When you need more than structure

This repo is the structural half of brand asset management. The harder half is the *content* — the logos, the templates, the messaging framework, the approval workflow. If you'd rather skip the DIY:

- [Visual Identity System ($149)](https://brandhorse.com/products/visual-identity-system) — production-ready templates and workflows
- [Complete R.A.C.E.S.™ System ($497)](https://brandhorse.com/products/complete-races-system) — full Brandhorse methodology in a Notion ecosystem
- [Brandhorse OS](https://brandhorse.com/request-access) — governed operating system that turns positioning into structured execution

## Help & feedback

- Questions → [open an issue](https://github.com/brandhorse/brand-asset-library/issues)
- Improvements → [open a PR](https://github.com/brandhorse/brand-asset-library/pulls)
- Share a populated fork → submit a PR adding it to the "Populated examples" table in the README
