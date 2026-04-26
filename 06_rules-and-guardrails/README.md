# Rules & Guardrails

> The rule library that compliance runs against. Do/don't patterns, must-include phrases, regulatory constraints.

**Stage:** `articulation`  ·  **OS surface:** /app/rules

## What goes here

- `rule-library/` — Active governance rules with severity and scope.
- `must-avoid/` — Phrases, claims, formats banned by brand or regulator.
- `must-include/` — Required disclosures, attributions, formatting.

## What doesn't go here

If you're tempted to put something in this folder that doesn't fit any of the
subfolders above, ask whether the artifact actually belongs upstream or
downstream. Most "where does this go?" moments come from skipping a step in
the chain of command.

## Related

This folder is part of the Brand Operating System scaffold. The full chain:

```
00_charter → 01_evidence → 02_patterns-and-insights →
03_personas-and-profiles → 04_positioning-and-messaging →
05_voice-and-anti-voice → 06_rules-and-guardrails →
07_approved-canon → 08_briefs-and-templates →
09_execution → 10_scaling-and-learning → 99_archive
```
