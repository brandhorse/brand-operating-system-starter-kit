# Guidelines

The compiled, published-form brand guidelines document and its condensed variants. **Source of truth lives upstream** — this folder holds the rendering.

## Important — this folder is not where rules are authored

The Guidelines PDF is the human-readable export of decisions made elsewhere in the operating system:

| What's in the PDF | Authored in… |
|---|---|
| Positioning, value props, claims | `04_positioning-and-messaging/` |
| Voice and anti-voice | `05_voice-and-anti-voice/` |
| Logo rules, color rules, typography rules, must-include / must-avoid | `06_rules-and-guardrails/` |
| Approved storytelling and communication frameworks | `07_approved-canon/` |
| Logo files, color tokens, font files referenced inside | `09_execution/assets/Logos/`, `…/Colors/`, `…/Fonts/` |

If you find yourself updating a rule directly in the Guidelines PDF, stop. Update it upstream first, then re-render. Otherwise the PDF and the operating system fall out of sync and compliance can't trust either one.

## Subfolder guide

- **`Full-Guide/`** — the complete brand guidelines PDF. The single document designers and vendors open. Updated yearly or when the brand evolves at a charter level.
- **`Quick-Reference/`** — condensed one-pagers and cheat sheets for day-to-day use.

## What belongs in the full guide

- Logo usage, clear space, minimum size, color treatments
- Color palette with accessibility pairings
- Typography hierarchy and web/print specs
- Photography direction and art direction
- Voice and tone (rendered from `05_voice-and-anti-voice/`)
- Example applications (social, web, print, swag)
- Do's and don'ts (rendered from `06_rules-and-guardrails/`)

## Quick-reference variants

Most brands need:

- A one-page visual cheat sheet (colors, type, logo)
- A one-page voice cheat sheet (do's, don'ts, examples)
- A one-page social cheat sheet (sizes, templates, caption formula)

Make these for the people who won't read the 60-page full guide.

## Naming

```
brand-guidelines-[full|quick-ref-type]-v[n]-YYYY-MM.pdf
```
