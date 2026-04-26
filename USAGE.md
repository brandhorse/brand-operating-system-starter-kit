# Setup & Adoption Guide

Five steps from empty scaffold to a brand operating system you can actually
operate. Plan ~30 minutes for a first pass; populating the folders with real
content is an ongoing exercise.

## Step 1 — Fork, clone, or download

```bash
git clone https://github.com/brandhorse/brand-operating-system-starter-kit.git
mv brand-operating-system-starter-kit my-brand-os
cd my-brand-os
```

If you'd rather not use Git, download the zip from the [Brandhorse Starter Kit
page](https://brandhorse.com/resources/brand-operating-system-starter-kit)
and unzip wherever you want it to live (Drive, Dropbox, local disk, all fine).

## Step 2 — Write your charter

Open `00_charter/` first. Don't skip this. The charter is the truth set
every downstream folder inherits. If you can't write it in a paragraph,
you don't yet know what you're building.

Three things to fill in:

- **`truth-set/`** — what you believe is true about your market that
  competitors don't act like they believe
- **`decision-rights/`** — who decides what (positioning, messaging,
  voice, rules), and how decisions get unblocked
- **`charter/`** — mission, vision, operating principles, brand promise

If a downstream folder ever feels confusing, the answer is usually that the
charter is incomplete. Come back and tighten it.

## Step 3 — Populate evidence before insights

The most common mistake: writing positioning, messaging, and voice before
populating evidence. The chain of command runs upward — evidence first,
patterns from evidence, insights from patterns, articulation from insights.

Drop into `01_evidence/`:

- **Customer quotes** from interviews, calls, support tickets, reviews
- **Competitive observations** — screenshots, ad library exports, positioning shifts
- **Market signals** — industry reports, search trends, regulatory moves
- **Internal proof** — sales calls, retention data, support ticket patterns

A good benchmark: ~30 evidence rows before you start synthesizing patterns.
Less than that and "patterns" is just confirmation bias.

## Step 4 — Move up the chain

Once `01_evidence/` has real content, work upward folder by folder:

1. `02_patterns-and-insights/` — what recurs across the evidence?
2. `03_personas-and-profiles/` — who is the brand built for, who isn't it?
3. `04_positioning-and-messaging/` — category claim, message map, claims library
4. `05_voice-and-anti-voice/` — how the brand speaks, and what it cannot say
5. `06_rules-and-guardrails/` — the do/don't list compliance can run against
6. `07_approved-canon/` — frameworks you've committed to and won't change without a charter-level decision

Don't skip ahead. If you find yourself in `04_positioning-and-messaging/`
without anything in `02_patterns-and-insights/`, you're guessing.

## Step 5 — Document ownership

Every brand operating system needs a guardian. Someone has to be accountable
for the file structure staying healthy: the README in every folder being
current, the rules library not contradicting itself, the canon being
respected.

Add a `OWNERSHIP.md` to the root with three columns:

| Folder | Owner | Backup |
| --- | --- | --- |
| 00_charter | (founder) | (head of brand) |
| 01_evidence | (research lead) | (founder) |
| ... | | |

Owners review their folder once a quarter. The backup steps in if the owner
moves on. This is not optional — without ownership, the system rots.

## What good looks like at 30, 60, 90 days

- **30 days** — Charter written. `01_evidence/` has 30+ rows. `03_personas-and-profiles/` has the ICP defined.
- **60 days** — Patterns and insights synthesized. Positioning and messaging populated. Voice articulated.
- **90 days** — Rules library active. Canon documented. Briefs in `08_briefs-and-templates/` generated against the populated chain. First campaign in `09_execution/` shipped from a brief that inherited governance.

## Common mistakes

1. **Putting Logos at the top.** They're in `09_execution/assets/` for a reason. Logos can't be defended without positioning; positioning can't be defended without evidence.
2. **Skipping anti-voice and anti-personas.** What the brand WON'T do is half the rule.
3. **Treating canon as "stuff we like."** Canon is what's been **approved**. If it can change without a charter-level decision, it's not canon yet.
4. **Letting `99_archive/` become a graveyard.** Archive is a teaching tool — what we tried, why we stopped. If you can't say why something was archived, document it before moving it.

## Going further

This scaffold is the file system. Brandhorse OS is the operating system that
runs on top of a populated scaffold — evidence is wired into patterns, rules
fire as compliance checks, briefs inherit governance, assets ship with
audit trails. If you want the wired-up version, request access at
[brandhorse.com/request-access](https://brandhorse.com/request-access).
