# Fonts

Brand typography — files, licensing, and usage notes.

## Subfolder guide

- **`Desktop/`** — installable font files (OTF, TTF) for designers' local machines.
- **`Web/`** — web-optimized formats (WOFF, WOFF2) for CSS `@font-face`.
- **`Licensing-and-Usage/`** — license documents, allowed-usage notes, purchase receipts.

## Important: licensing

**Don't commit licensed fonts to a public repo.** If this fork is public, keep fonts in a private drive and link from `Licensing-and-Usage/`. If this fork is private, make sure the license permits team distribution.

Free/open-source fonts (Google Fonts, Inter, SF Pro, etc.) can be committed — document the source in `Licensing-and-Usage/`.

## What to include

- Every weight and style actually used (don't commit 50 weights you never use)
- Variable font file if available
- Fallback stack documentation (what loads if the brand font fails)
- Installation instructions for the Desktop variants

## Naming

```
brand-font-[role]-[family]-v[n].ext
```

Examples:
- `brandhorse-font-headline-inter-v1.otf`
- `brandhorse-font-body-inter-v1.woff2`
