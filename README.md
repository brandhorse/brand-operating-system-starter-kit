# Brand Asset Library Template

A clean, public-ready folder structure for organizing brand assets across design, marketing, web, and operations.

This repository is meant to be used as a **starter template**. It gives teams a simple, scalable place to store approved brand files, working files, usage guidance, and supporting documentation.

## Who this is for

- Small teams building a brand system from scratch
- Agencies handing off assets to clients
- Marketing teams that need a cleaner source of truth
- Designers and developers who want predictable file organization

## What is included

- A practical folder structure for common brand assets
- Placeholder `.gitkeep` files so empty folders stay in Git
- Starter documentation for naming, ownership, and usage
- A lightweight asset index in CSV format

## What is not included

- Real client assets
- Licensed font files
- Finished logo files
- Proprietary brand strategy documents

## Folder structure

```text
brand-asset-library-template/
├── 00_Start-Here/
├── Logos/
├── Fonts/
├── Colors/
├── Templates/
├── Photography/
├── Icons-and-Graphics/
├── Messaging/
├── Guidelines/
└── Archive/
```

## Recommended usage

1. Duplicate this repo into your own workspace.
2. Replace placeholder files with your real assets.
3. Keep only one approved version of each asset.
4. Archive outdated or deprecated files instead of deleting blindly.
5. Document ownership and update rules before the library grows.

## Suggested naming convention

Use a simple, consistent pattern like:

```text
brand-area-asset-purpose-version-date.ext
```

Example:

```text
brand-logo-primary-horizontal-v01-20260415.svg
```

## Git tips

- Keep large binaries out of Git when possible
- Use Git LFS if you plan to version large design files
- Do not commit licensed fonts unless you have distribution rights
- Do not store client-sensitive assets in a public repo

## License

This template is released under the MIT License. See `LICENSE`.
