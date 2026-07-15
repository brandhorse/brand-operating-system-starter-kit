# setup & adoption guide

five steps from empty scaffold to a brand operating system you can actually operate. plan ~30 minutes for a first pass; populating the folders with real content is an ongoing exercise — measured in weeks, not minutes.

> **doing this as part of brandhorse onboarding?** follow [`00_START_HERE.md`](00_START_HERE.md) instead — it's the guided path (audit → research pass → charter pass → ratify) and it wires in the two prompts that do the heavy lifting. this file is the tool-agnostic version of the same order.

## the one thing to get right: evidence first, charter derived

`00_charter/` is numbered first because it's the constitutional layer everything inherits from — **that's its authority, not the order you build it.** you populate the charter *from evidence*, never author it cold. the chain runs upward: evidence → patterns → insights → articulation. so you start at `01_evidence/`, and the charter comes *after* you have something real to derive it from.

skip this and you get the most common failure mode there is: a confident-sounding charter that nothing supports, and a brand that falls apart the first time it's challenged.

## step 1 — fork, clone, or download

```bash
git clone https://github.com/brandhorse/brand-operating-system-starter-kit.git
mv brand-operating-system-starter-kit my-brand-os
cd my-brand-os
```

if you'd rather not use git, download the zip from the [brandhorse starter kit page](https://brandhorse.com/resources/brand-operating-system-starter-kit) and unzip wherever you want it to live (drive, dropbox, local disk, all fine).

**questions to answer before moving on:** where will this live? who has read access? who has write access?

## step 2 — populate evidence (this is where you start)

open `01_evidence/` first. the most common mistake is writing positioning, messaging, or a charter before there's any evidence under them. the chain runs upward — evidence first, patterns from evidence, insights from patterns, articulation from insights.

drop into `01_evidence/`:

- **customer quotes** from interviews, calls, support tickets, reviews
- **competitive observations** — screenshots, ad-library exports, positioning shifts
- **market signals** — industry reports, search trends, regulatory moves
- **internal proof** — sales calls, retention data, support-ticket patterns

a good benchmark: **~30 evidence rows** before you start synthesizing patterns. less than that and "patterns" is just confirmation bias. the [research-pass prompt](01_evidence/README.md) runs this collection for you and writes source-attributed rows straight into this folder.

> **if you're pre-revenue, expect little or no internal proof on the first pass — that's correct, not a gap in your work.** gather any call recordings, demos, or customer conversations you already have; that's what closes it.

## step 3 — synthesize up to patterns and personas

once `01_evidence/` has real content, work upward:

1. `02_patterns-and-insights/` — what recurs across the evidence? what does it mean for the business?
2. `03_personas-and-profiles/` — who is the brand built for, who isn't it, who did you used to serve?

don't skip ahead. if you're reaching for positioning language with nothing in `02`, you're guessing.

## step 4 — derive and ratify your charter

**now** open `00_charter/`. with evidence and synthesis behind you, the charter is a derivation, not an invention. fill in:

- **`truth-set/`** — market truths you can defend, each traceable to evidence
- **`decision-rights/`** — who decides what, and how decisions get unblocked
- **`charter/`** — mission, vision, operating principles, brand promise

the [charter-drafting pass](00_charter/README.md) turns your evidence into draft clauses plus an open-questions list and thin-evidence flags. review, answer the open questions, and **ratify** — lock it. everything downstream inherits from this, so it has to be settled before you build further.

## step 5 — articulate downstream, then document ownership

with a ratified charter, work down the chain — each layer inheriting from the charter and citing evidence:

3. `04_positioning-and-messaging/` — category claim, message map, claims library
4. `05_voice-and-anti-voice/` — how the brand speaks, and what it can never say
5. `06_rules-and-guardrails/` — the do/don't list compliance can run against
6. `07_approved-canon/` — frameworks you won't change without a charter-level decision

then give the system a guardian. add an `OWNERSHIP.md` to the root:

| folder | owner | backup |
| --- | --- | --- |
| 01_evidence | (research lead) | (founder) |
| 00_charter | (founder) | (head of brand) |
| ... | | |

owners review their folder once a quarter. the backup steps in if the owner moves on. without ownership, the system rots.

## what good looks like at 30, 60, 90 days

- **30 days** — `01_evidence/` has 30+ rows across the four sub-folders. `03_personas-and-profiles/icp/` has the primary ICP defined with provenance. charter drafted from that evidence and posted in `00_charter/`.
- **60 days** — patterns and insights synthesized in `02`. positioning and message map populated in `04`. voice articulated and anti-voice listed in `05`. ownership documented at root.
- **90 days** — rule library active in `06`. approved canon documented in `07`. first brief in `08_briefs-and-templates/` generated against the populated chain. first campaign shipped in `09_execution/` from a brief that inherited governance. first compliance run logged.

## common mistakes

1. **writing the charter first, cold.** `00_charter/` is numbered first for *authority*, not build order. author it before evidence and it's opinion wearing a constitution's clothes. derive it — evidence → synthesis → charter.
2. **putting logos at the top.** they're in `09_execution/assets/` for a reason. logos can't be defended without positioning; positioning can't be defended without evidence.
3. **skipping anti-voice and anti-personas.** what the brand *won't* do is half the rule.
4. **treating canon as "stuff we like."** canon is what's been **approved**. if it can change without a charter-level decision, it's not canon yet.
5. **letting `99_archive/` become a graveyard.** archive is a teaching tool — what we tried, why we stopped. if you can't say why something was archived, document it before moving it.

## going further

this scaffold is the file system. brandhorse os is the operating system that runs on top of a populated scaffold — evidence is wired into patterns, rules fire as compliance checks, briefs inherit governance, assets ship with audit trails. if you want the wired-up version, request access at [brandhorse.com/request-access](https://brandhorse.com/request-access).
