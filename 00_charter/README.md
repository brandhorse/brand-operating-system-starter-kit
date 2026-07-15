# Charter & Truth Set

> The non-negotiables. Decision rights, charter docs, and the rules of engagement that govern every downstream choice.

**Stage:** `governance`  ·  **OS surface:** /app/brand-profile

> ⚠️ **This folder is numbered `00` for authority, not build order. Do NOT author your charter cold, first.** The charter is the constitutional layer everything downstream inherits from — which is exactly why it has to be *derived from evidence*, not invented at a blank page. Build order is: populate [`01_evidence/`](../01_evidence/README.md) → synthesize `02` → **then** come back and derive this. A charter written before the evidence is opinion wearing a constitution's clothes, and it's the single most common reason a brand falls apart under challenge.

## How to populate this folder

Run the **charter-drafting pass** *after* your research pass. It reads the evidence you collected in `01_evidence/` and turns it into **draft** charter clauses — mission, values, non-negotiables, excluded audiences, decision rights — plus an **open-questions** list and **thin-evidence flags** so you know what's still soft.

- **charter-drafting-pass prompt** — linked from the pre-os quickstart ([`00_START_HERE.md`](../00_START_HERE.md)) and the [starter-kit page](https://brandhorse.com/resources/brand-operating-system-starter-kit). View-only — make your own copy and run it in the same named project as your research pass.

Then **ratify**: review the drafts, answer the open questions, and lock it. Everything downstream (`03`–`07`) inherits from the ratified charter, so it has to be settled before you build further.

## What goes here

- `truth-set/` — Core market truths the brand commits to operating against.
- `decision-rights/` — Who decides what, how decisions get unblocked, escalation paths.
- `charter/` — Mission, vision, operating principles, brand promise.

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
