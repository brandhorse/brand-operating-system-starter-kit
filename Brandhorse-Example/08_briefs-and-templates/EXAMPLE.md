# 08_briefs-and-templates — Brandhorse populated example

> Briefs anchor every campaign. Templates and asset blueprints are the specs and master files that govern shipped output. Briefs without governance inheritance can't ship.

---

## campaign-briefs/

**Brief: BOS Starter Kit launch — April 2026**

**Brief ID:** BR-2026-04-BOS-LAUNCH
**Owner:** Brand Lead
**Stage:** Approved
**Inherits from:**
- `00_charter/charter/` — operating principles
- `04_positioning-and-messaging/positioning/` — category claim
- `04_positioning-and-messaging/message-map/` rows 1, 4
- `05_voice-and-anti-voice/voice/` — full register
- `06_rules-and-guardrails/rule-library/` — BH-V-001, BH-V-002, BH-V-003, BH-C-001, BH-C-002

**Campaign goal:** Drive sign-ups for the BOS Starter Kit (free, email-gated). 500 downloads in 30 days.

**Audience:** Primary ICP from `03_personas-and-profiles/icp/`. Secondary: agency owners from `03_personas-and-profiles/secondary-personas/`.

**Channel mix:**
- Long-form blog post (3 articles in cluster)
- LinkedIn (8 posts over 30 days)
- X (thread + 5 tweets)
- Email nurture sequence (6 touches over 21 days)
- Podcast outreach (10 pitches)

**Disqualification copy:** Must explicitly note this is not for pre-PMF startups or solo creators. (Anti-personas 1 and 2.)

**Success metrics:** Downloads, secondary email open rate ≥35%, click-through on Day 9 product CTA ≥3%.

**Compliance pre-flight:** Required against rules BH-V-001, BH-V-002, BH-V-003, BH-C-001, BH-C-002 before any copy ships.

---

## asset-blueprints/

**Blueprint: Email — long-form nurture**

| Field | Spec |
|---|---|
| Format | HTML rendered via `_shared/canonicalEmailBuilder.ts` |
| Archetype | `email.structured` |
| Sender | `races@os.brandhorse.com` ("Brandhorse OS") |
| Heading rule | BH-V-002 (italic, lowercase) |
| Body rule | BH-V-001 (lowercase, proper nouns preserved) |
| Required sections | header, hero, valuePillars OR card, primaryCTA, footer (with unsubscribe) |
| Banned sections | None — but custom HTML blocks must be reviewed by Brand Lead |
| Linked master file | `_shared/canonicalEmailBuilder.ts` (versioned) |

**Blueprint: LinkedIn — operator-to-operator post**

| Field | Spec |
|---|---|
| Length | 100–250 words |
| Persona | Brandhorse marketing voice (`07_approved-canon/brand-personas/`) |
| Required move | Open with concrete operator pain (no rhetorical question) |
| Required element | One claim from `04_positioning-and-messaging/claims-library/` with provenance check |
| Banned moves | Performative humility, hype-y language (BH-V-003) |

**Blueprint: Podcast pitch**

| Field | Spec |
|---|---|
| Format | Email |
| Length | <200 words |
| Persona | Founder voice (`07_approved-canon/brand-personas/founder-voice`) |
| Required element | Specific reference to host + show (no copy-paste templates) |
| Required CTA | "Happy to send a one-pager if useful" |

---

## story-arcs/

**Story arc: "Brand Operating System" pillar**

Multi-touch narrative that compounds across surfaces. Reusable across years.

| Beat | Where |
|---|---|
| Hook | "Most brand work fails downstream because the upstream chain is missing." |
| Reveal | "Brand decisions aren't a publication. They're an operating system." |
| Proof | Customer evidence + Brandhorse internal-proof |
| Pivot | "Compliance is the wedge most brand strategy ignores." |
| Close | "The system, not the document." |

Used as the spine for: long-form blog, podcast pitches, founder LinkedIn, sales decks.

---

## How this folder feeds upstream

Shipped instances in `09_execution/channel-shipped/` must reference the brief ID they were built from. Compliance runs in `09_execution/compliance-runs/` check the shipped instance against the brief's declared rule list.
