# 05_voice-and-anti-voice — Brandhorse populated example

> How the brand speaks — and the things it can never say. Voice without anti-voice is half the rule.

---

## voice/

**Tone attributes (where we sit on each axis):**

| Axis | Position | Notes |
|---|---|---|
| Formal ↔ Casual | 35% formal, 65% casual | Direct, unstuffy. Operator-to-operator. |
| Serious ↔ Playful | 80% serious, 20% playful | Wit is in observation, not jokes. |
| Reserved ↔ Bold | 70% bold | We have a position and we say it. |
| Polished ↔ Unpolished | 60% polished | Clean prose, but never sterile. |

**Characteristic moves:**

- Lowercase running heads in marketing surfaces; italic for emphasis.
- Open with the operator's pain, not our product.
- Short sentences when we're declaring. Long sentences when we're explaining the chain.
- Concrete language. "Compliance caught it" beats "we ensure brand integrity."
- Numbers when they're real ("47 of 53 conversations"). Never numbers when they're not.

**Example (on-brand):**

> Brand decisions live across 4–7 surfaces. Slack, Notion, Drive, Figma. When someone leaves, the brand drifts. Brandhorse versions the chain — evidence, positioning, voice, rules — so the next person inherits the system, not the chaos.

---

## anti-voice/

**What we never sound like:**

- **Marketing-y:** "Unlock the power of your brand."
- **Guru-y:** "Here's the framework that changed everything."
- **Jargon-y without earning it:** "Synergize cross-functional brand cohesion."
- **Apologetic:** "Sorry to bother you, just thought you might find this interesting…"
- **Performative humility:** "We're just a small team trying to figure this out."
- **Hype-y:** "Game-changing AI-powered brand intelligence."
- **Brittle confidence:** "The only brand operating system you'll ever need."

**Banned phrases:**

- "World-class"
- "Unlock"
- "Game-changing"
- "Best-in-class"
- "Reach out"
- "At the end of the day"
- "Move the needle"
- "Synergy"
- Any phrase that wouldn't survive a screenshot in front of an actual customer

**Banned moves:**

- Em-dash overuse (one per paragraph max).
- Posing rhetorical questions we then answer ourselves. ("What is brand? Brand is…")
- Stacked metaphors that cancel each other out.

---

## voice-overrides/

**Override 1: Compliance copy**

When a rule violation is being explained, voice shifts from "operator-to-operator" to "system telling you what's allowed." More precise. Less casual. Authorized by `06_rules-and-guardrails/rule-library/violation-explanation`.

**Override 2: Founder LinkedIn posts**

Personal voice; first person; can break the "lowercase running head" rule when emphasis demands. Authorized in `07_approved-canon/brand-personas/founder-voice`.

**Override 3: Sales call transcripts and customer DMs**

Voice can match the customer's register. If they're casual, we're casual. If they're formal, we're formal. Goal: don't make them feel like they're being marketed at.

---

## How this folder feeds upstream

Rules in `06_rules-and-guardrails/must-avoid/` enforce the anti-voice banned phrases. Compliance runs in `09_execution/compliance-runs/` use this folder as a baseline. Brand personas in `07_approved-canon/brand-personas/` reference voice overrides 2 and 3.
