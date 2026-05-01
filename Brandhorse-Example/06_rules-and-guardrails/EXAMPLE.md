# 06_rules-and-guardrails — Brandhorse populated example

> The rule library compliance runs against. Each row has a severity, a scope, and an upstream source it enforces.

---

## rule-library/

| Rule ID | Severity | Scope | Rule | Source |
|---|---|---|---|---|
| BH-V-001 | High | All public copy | Voice runs lowercase except proper nouns and acronyms | `05_voice-and-anti-voice/voice/` |
| BH-V-002 | High | All headings | Headings are italic | `05_voice-and-anti-voice/voice/` |
| BH-V-003 | High | All copy | Banned phrases not allowed | `05_voice-and-anti-voice/anti-voice/` |
| BH-C-001 | Critical | All public claims | Every numeric claim has provenance row in `01_evidence/` | Charter operating principle: evidence first |
| BH-C-002 | Critical | All public claims | Disallowed claims (e.g. "the only brand operating system") never ship | `04_positioning-and-messaging/claims-library/` |
| BH-V-004 | Medium | Long-form prose | Em-dash usage capped at 1 per paragraph | `05_voice-and-anti-voice/anti-voice/` |
| BH-V-005 | Medium | All copy | No rhetorical-question-then-answer construction | `05_voice-and-anti-voice/anti-voice/` |
| BH-A-001 | High | All visual assets | Logo placement follows clear-space rule (1x logo height all sides) | `09_execution/assets/Logos/README.md` |
| BH-A-002 | High | All visual assets | Approved color tokens only; no off-palette colors | `09_execution/assets/Colors/` |
| BH-L-001 | Critical | Regulated industry copy | Disclaimers required when claims reference financial/health outcomes | Legal counsel + `06_rules-and-guardrails/must-include/` |

**Severity meaning:**
- **Critical:** Compliance run blocks publish. Cannot ship.
- **High:** Compliance run flags. Brand Lead must review.
- **Medium:** Compliance run warns. Author can override with comment.

---

## must-avoid/

**Phrases banned across all surfaces:**

- "World-class"
- "Unlock"
- "Game-changing"
- "Best-in-class"
- "Reach out" (use "email" or "DM")
- "Move the needle"
- "Synergy" / "synergize"
- "At the end of the day"
- "AI-powered" (unless followed by a specific AI feature being referenced)
- "Revolutionary"
- "The only [X]" (use "the governed [X]" or specific differentiator)

**Patterns banned:**

- Stacked metaphors that cancel each other out
- Performative humility ("we're just a small team…")
- Apologetic openings ("sorry to bother you…")

**Format:** Each banned item is enforced by rule BH-V-003 (severity: High).

---

## must-include/

**Required by context:**

| Context | Required element |
|---|---|
| Public claim of customer outcome | Evidence row reference + customer's recorded consent |
| AI feature description | Concrete capability cited (no vague "AI-powered") |
| Email footer | Unsubscribe link, physical mailing address (CAN-SPAM) |
| Regulated industry copy (financial, health) | Compliance-reviewed disclaimer |
| Sponsored or paid content | Disclosure label per FTC guidelines |
| Comparative claim against competitor | Source citation, dated, in `01_evidence/competitive/` |

---

## How this folder feeds upstream

`09_execution/compliance-runs/` runs each shipped asset against this library. `09_execution/assets/Guidelines/` renders these rules into the human-readable PDF. Briefs in `08_briefs-and-templates/` cite specific rule IDs they need to comply with.
