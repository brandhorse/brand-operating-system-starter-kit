# Naming Convention

Every file in this library follows one pattern:

```
brand-area-asset-purpose-version-date.ext
```

## Parts

- **brand** — lowercase brand identifier (e.g., `brandhorse`, `roatan`, `acme`)
- **area** — top-level category (e.g., `logo`, `font`, `color`, `template`, `photo`, `icon`)
- **asset** — specific asset name (e.g., `primary`, `icon`, `headline-inter`, `swatches`)
- **purpose** — use context when relevant (e.g., `rgb`, `cmyk`, `web`, `print`, `social-feed`)
- **version** — `v1`, `v2`, etc.
- **date** — `YYYY-MM` for the month it was finalized (or `YYYY-MM-DD` for precision)

## Examples

✅ `brandhorse-logo-primary-rgb-v2-2026-04.svg`
✅ `roatan-font-headline-inter-v1-2025-11.otf`
✅ `acme-template-social-feed-post-v3-2026-03.fig`

❌ `logo_final_v3_FINAL.png`
❌ `Logo Copy 2 (use this one).ai`
❌ `brand_2026.pdf`

## Exceptions

- Fonts can use the foundry's original filename if licensing requires it (document in `Fonts/Licensing-and-Usage/`)
- Vendor-provided stock photography keeps its original filename (log it in the asset index)

## Rules

1. Lowercase everything. No spaces — use hyphens.
2. No "final," "FINAL," "v3-final," "use-this-one." Version with numbers.
3. Date format is `YYYY-MM` or `YYYY-MM-DD`. No `Apr-2026`, no `04-17-26`.
4. If you update an asset, bump the version and archive the old one. Don't overwrite.

## Enforcement

The brand guardian (see `Contacts-and-Ownership.txt`) reviews PRs/uploads for naming compliance. Non-compliant files can be renamed before merging.
