# Colors

The brand color system — swatches, tokens, and documentation.

## Subfolder guide

- **`Swatches/`** — Adobe Swatch Exchange files (ASE), Sketch palettes, Figma styles.
- **`Tokens/`** — design tokens as JSON / YAML / CSS variables for engineering handoff.
- **`Documentation/`** — hex/RGB/CMYK codes, accessibility pairings, usage rules.

## What to document

Every color needs:

- **Hex** (digital)
- **RGB** (digital)
- **CMYK** (print)
- **Pantone** (if used for brand-critical print)
- **CSS variable name** (e.g., `--color-brand-primary`)
- **Role** (primary, secondary, accent, neutral, semantic)
- **Accessibility** — which colors pair with AA contrast for text

## Design tokens

Keep `Tokens/colors.json` (or similar) as the single source of truth for any code that consumes brand colors. Example:

```json
{
  "color": {
    "brand": {
      "primary": { "value": "#3B5AD6" },
      "secondary": { "value": "#9D4EDD" }
    }
  }
}
```

## Naming

```
brand-color-[swatches|tokens|docs]-v[n].ext
```
