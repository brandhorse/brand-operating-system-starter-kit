<!--
  CANONICAL SOURCE for Setup-and-Adoption-Guide.pdf.
  Edit this file, then regenerate the PDF (root + 09_execution/assets/ copies) from it.
  Do not hand-edit the PDF — it will drift from README.md / USAGE.md again.
  Last aligned: 2026-07-14 — evidence-first build order; prices verified against prod catalog.
-->

# brand operating system — setup & adoption guide

*five steps from an empty scaffold to a brand operating system you can actually operate.*

published by brandhorse · open-source · MIT licensed · brandhorse.com

---

## what this is

this guide takes you from an empty brand operating system scaffold to a populated, governed system your team can operate against.

the kit is 12 governance-first folders, 39 first-level subfolders, ordered by the **chain of command**. evidence at the top, execution at the bottom, scaling and archive at the end.

plan ~30 minutes for a first pass. populating the folders with real content is ongoing — measured in weeks, not minutes.

**doing this as brandhorse onboarding?** open `00_START_HERE.md` at the scaffold root — it's the guided path (audit → research pass → charter pass → ratify) and wires in the two prompts that do the heavy lifting.

## what this is not

- **a brand strategy.** the scaffold holds your strategy — it doesn't replace it.
- **an asset library.** assets live in `09_execution/assets/`, downstream of the decisions that make them defensible.
- **a one-time deliverable.** the system is a living artifact. the value compounds with use.

---

## the one rule: evidence first, charter derived

`00_charter/` is numbered first because it's the constitutional layer every downstream folder inherits from — **that's its authority, not the order you build it in.**

you build the charter *from evidence*. author it cold, before the research, and you'll produce a brand nobody can defend the moment it's challenged. that mistake is the single most common reason a brand falls apart under pressure — and it's the exact trap this kit exists to prevent.

so:

```
authority (what inherits from what):   00 → 01 → 02 → 03 → 04 → 05 → 06 → 07 → 08 → 09 → 10
build order (what you populate first): 01 → 02 → 03, then 00 (derived), then 04 → 05 → 06 → 07 → …
```

**00 is where everything inherits from. 01 is where you start.**

---

## the chain of command

every brand decision is downstream of an upstream one. the folder numbers reflect the dependency direction — and, for everything except the charter, the order you populate them.

| folder | holds |
| --- | --- |
| `00_charter` | the non-negotiables: truth set, decision rights, charter — **derived from evidence, not authored cold** |
| `01_evidence` | ▶ **start here.** raw signals — quotes, observations, market data, internal proof |
| `02_patterns-and-insights` | what the evidence reveals |
| `03_personas-and-profiles` | who you serve, who you don't, who you used to |
| `04_positioning-and-messaging` | governed positioning, message map, claims library |
| `05_voice-and-anti-voice` | how the brand speaks — and the things it can never say |
| `06_rules-and-guardrails` | the rule library compliance runs against |
| `07_approved-canon` | frameworks the brand has committed to |
| `08_briefs-and-templates` | briefs anchor every campaign |
| `09_execution` | shipped work — assets, campaigns, channel-shipped, compliance runs |
| `10_scaling-and-learning` | experiments, performance, decisions log, recaps |
| `99_archive` | deprecated — kept, not deleted |

*the rule: if a downstream folder feels confusing, the answer is almost always upstream. don't add structure to the wrong layer to compensate.*

---

## five-step adoption

the same order is in `USAGE.md` at the repo root. build **upward from evidence** — the charter is derived, not written first.

**1. fork or clone.** use "use this template" on github (clean history) or fork. no git? download the zip from brandhorse.com/resources/brand-operating-system-starter-kit and unzip wherever it should live. *(where will this live? who has read access? who has write?)*

**2. populate evidence — this is where you start.** open `01_evidence/`. drop in customer quotes (interviews, calls, tickets, reviews), competitive observations, market signals, and whatever internal proof you have. benchmark: ~30 rows before you synthesize. the research-pass prompt runs this collection for you. *(pre-revenue? expect little internal proof on pass one — that's correct, not a gap.)*

**3. synthesize up to patterns and personas.** once evidence is real, work upward: `02_patterns-and-insights/` (what recurs, what it means), then `03_personas-and-profiles/` (who it's for, who it isn't). don't skip ahead — positioning language with nothing in `02` is guessing.

**4. derive and ratify your charter.** *now* open `00_charter/`. with evidence and synthesis behind you, the charter is a derivation. the charter-drafting pass turns your evidence into draft clauses (mission, values, non-negotiables, excluded audiences, decision rights) plus open questions and thin-evidence flags. answer the open questions and ratify — lock it. everything below inherits from it.

**5. articulate downstream, then document ownership.** work down the chain — `04` positioning → `05` voice → `06` rules → `07` canon — each inheriting from the ratified charter and citing evidence. then add an `OWNERSHIP.md` at root (folder · owner · backup); owners review quarterly. without ownership, the system rots.

---

## common mistakes

- **writing the charter first, cold.** `00` is first for authority, not build order. derive it from evidence, or it's opinion in a constitution's clothes.
- **putting logos at the top.** they're in `09_execution/assets/`. logos can't be defended without positioning; positioning can't be defended without evidence.
- **articulation before evidence.** positioning/messaging/voice written before `01_evidence/` produces a brand nobody can defend. it shows up later as "rebrand fatigue."
- **voice without anti-voice.** "confident, friendly, clear" is meaningless because nothing is excluded.
- **treating canon as preference.** canon is what's been *approved*. if it can change without a charter-level decision, it isn't canon yet.
- **letting `99_archive/` become a graveyard.** the archive teaches — what we tried, why we stopped. an undocumented archive is worse than a deleted file.

---

## what good looks like at 30 · 60 · 90 days

- **30 days** — `01_evidence/` has 30+ rows across the four sub-folders. primary ICP defined in `03` with provenance. charter drafted from that evidence and posted in `00_charter/`.
- **60 days** — patterns and insights synthesized in `02`. positioning and message map in `04`. voice and anti-voice in `05`. ownership documented at root.
- **90 days** — rule library active in `06`. approved canon in `07`. first brief in `08` generated against the populated chain. first campaign shipped in `09` from a brief that inherited governance. first compliance run logged.

---

## when you need more than structure

this scaffold is the file system. when you want the methodology behind it or the running os, brandhorse maintains a ladder:

- **brand self-audit — free.** 10-minute diagnostic scoring your brand across all five r.a.c.e.s.™ phases; tells you which folders to populate first. → brandhorse.com/brand-audit
- **brand mastery essentials — free.** the eBook that grounds the mindset behind the whole system. → brandhorse.com/brand-mastery-essentials
- **r.a.c.e.s.™ methodology workbook — $79.** the complete methodology + notion companion. the thinking behind every folder here. → brandhorse.com/products/races-methodology-workbook
- **brand mastery blueprint — from $39 (eBook) · $89 complete bundle.** the operator's reference for running the chain, in multiple formats. → brandhorse.com/products/brand-mastery-blueprint-bundle
- **brandhorse os — membership.** the governed operating system. run r.a.c.e.s.™ end-to-end with traceable evidence and approved canon. the scaffold instrumented as a live system. → brandhorse.com/request-access

*published by brandhorse. open-source, MIT licensed. the methodology and scaffold are the same we run across the Stroelli portfolio. attribution appreciated, not required. issues or a populated fork to share: github.com/brandhorse/brand-operating-system-starter-kit*
