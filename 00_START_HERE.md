# start here

**you just downloaded the scaffold. before you open a single folder, read this.**

this is a snapshot of the brandhorse **pre-os quickstart**. the canonical, always-current version is maintained by brandhorse — if anything below is unclear or looks out of date, the maintained version wins:

**canonical source → [brandhorse.com/resources/brand-operating-system-starter-kit](https://brandhorse.com/resources/brand-operating-system-starter-kit)** *(the starter-kit page links the current quickstart, research pass, and charter pass)*

---

## the one rule

**don't write your charter cold, and don't start building until it's ratified.**

`00_charter/` sits at the top of this scaffold because it's the constitutional layer every other folder inherits from — but **that's its authority, not the order you build it in.** you build the charter *from evidence*. author it before you've done the research and you'll produce a brand nobody can defend the moment it's challenged — which is exactly the trap this kit exists to prevent.

so the order is: **research first, charter second, everything else after.** decisions compound — the point is to decide once, on evidence, and not relitigate later.

> if you take one thing from this file: **evidence first. the charter is derived, not invented.**

---

## the path (do these in order)

1. **run the [free brand audit](https://brandhorse.com/brand-audit).** ~5–10 minutes. it scores where your brand stands today and names the gaps to fix first. this is your "you are here."

2. **read [brand mastery essentials](https://brandhorse.com/brand-mastery-essentials)** (free eBook). the mindset and grounding for everything below. ~16 pages. don't skip to the tools.

3. **you already have this scaffold** — the folder system the whole thing runs on. keep it handy; you'll import it in step 4.

4. **set up one named workspace, properly.** create a single persistent, named project for this brand (e.g. `[brand] — brand os`) and run all the research inside it — never a throwaway chat. claude desktop / co-work is the easy default; any tool that holds a persistent project and can run multi-step work is fine (ChatGPT/Codex, Cursor, Perplexity Pro, Manus). import this scaffold folder as its files. *(if your tool can't import a folder, keep the scaffold open beside you and write outputs back into it.)*

5. **make your own copy of the [research-pass prompt](https://docs.google.com/document/d/1s0mQhIoRZyYUefTOjuZGs9u_bvOHj7IFhXx07GEfiwM/edit?usp=sharing).** the shared doc is **view-only on purpose** — File → Make a copy, fill in **only phase 0** (the six scope questions), touch nothing below it.

6. **run the research pass.** paste your copy into the project and let it work. it collects customer quotes, competitive entries, and market signals — roughly **30–50 source-attributed evidence rows**, each with a link back to where it came from, written into `01_evidence/`.

   > **expect zero internal proof on your first pass** if you're pre-revenue with no shipped case studies — that's correct, not a failure. gather any call recordings, demos, or customer conversations you *do* have before you start; that's what closes the gap.

7. **read your own research report.** the pass produces a `research_report.md`. read it — it's yours, not a handoff. this is where you find out whether the thing you want to build is actually validated.

8. **run the [charter-drafting pass](https://docs.google.com/document/d/1iCoFCh0zYCePfg5kfJFgfUTSK_g6YOU9OsmaXM5EBLw/edit?usp=sharing).** run it in the same project. it turns your evidence into **draft** charter clauses (mission, values, non-negotiables, excluded audiences, decision rights) plus an **open-questions** list and **thin-evidence flags**. this is how `00_charter/` gets populated — derived, not authored cold.

9. **ratify.** review the drafts, answer the open questions, lock the charter. if you're taking this into brandhorse os, request access at [brandhorse.com/request-access](https://brandhorse.com/request-access), import your evidence, and ratify there. now you have a grounded foundation — and *only now* do you move down the chain (personas → positioning → voice → rules → canon).

**book any working call after step 8, not before.** show up with drafts and your answers to the open questions. the call is for *ratifying*, not producing your foundation from scratch — that part's already done.

---

## the build order, at a glance

the folder numbers show **authority** (what inherits from what). the arrows show the **order you populate them**:

```
research           01_evidence ──▶ 02_patterns-and-insights
                        │
derive             ─────▼─────
                    00_charter   ◀── the constitutional layer, built FROM the research above
                        │
articulate         ─────▼─────
                   03_personas ──▶ 04_positioning ──▶ 05_voice ──▶ 06_rules ──▶ 07_canon
                        │
execute            ─────▼─────
                   08_briefs ──▶ 09_execution ──▶ 10_scaling
```

**00 is where everything inherits from. 01 is where you start.**

---

## snags we see every time (and the fix)

- **"i lost my research chat."** you ran it in a loose chat. always create a **named project** and run inside it.
- **"the shared doc got modified."** originals are **view-only**; always **make a copy** first.
- **"i ran out of credits halfway."** a full pass is credit-heavy — top up *before* you start, not mid-pass.
- **"i wrote the charter first and now nothing lines up."** that's the cold-charter trap. the charter is derived from evidence — go back, run the research, and let the charter pass build it.
- **"this is overwhelming."** ignore patterns, insights, and frames for now. your only job pre-os is: **audit → read → research pass → charter pass → ratify.** the rest waits for you.

---

*the free rungs — brand audit, brand mastery essentials, this starter kit — get you to a grounded foundation. brandhorse os picks up from a ratified charter.*
