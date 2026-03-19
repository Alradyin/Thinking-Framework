# 🧠 Thinking Framework

> **Load any thinker's mental operating system into your AI.**
> Not role-play. Not impersonation. Cognitive architecture transfer.

[![ClaWHub](https://img.shields.io/badge/ClaWHub-thinking--framework-coral?style=flat-square)](https://clawhub.ai/Alradyin/thinking-framework)
[![Version](https://img.shields.io/badge/version-1.1.0-blue?style=flat-square)](CHANGELOG.md)
[![License: MIT-0](https://img.shields.io/badge/license-MIT--0-green?style=flat-square)](LICENSE)
[![Models](https://img.shields.io/badge/works%20with-Claude%20%7C%20GPT%20%7C%20Gemini%20%7C%20Ollama-purple?style=flat-square)]()

---

## The Problem

You've tried "act like Elon Musk" or "think like a Stoic philosopher."

The AI gives you a costume — some quotes, a vague tone, maybe a catchphrase.
It doesn't give you the *operating system*. It doesn't give you how they actually
frame problems, what they optimize for, what psychological wounds drive their
decisions, or where their thinking reliably breaks down.

That's the gap this skill fills.

---

## What It Actually Does

Thinking Framework performs a **deep, multi-layer excavation** of any target:

**Cognitive Layer** (C1–C7)
- Mental models they use to explain reality
- Decision heuristics that drive choices under pressure
- What they're actually optimizing for (stated vs. hidden)
- How they reframe problems before solving them
- Risk posture and time horizon architecture
- Paradox and contradiction structure

**Psychological Layer** (P1–P8)
- Core wound and formative architecture
- Dominant motivational deep structure
- Ego structure and identity architecture
- Defense mechanisms under pressure
- Shadow profile (what's suppressed / projected)
- Relational and attachment patterns
- Existential relationship (mortality, legacy, meaning)
- Stress and breakdown profile

Once loaded, the AI **reasons FROM inside that framework** — not about it.

---

## The Difference

| ❌ Standard role-play | ✅ Thinking Framework |
|---|---|
| "Elon Musk would say: move fast and break things!" | Strips the analogy. Finds the cost floor. Attacks the bottleneck. |
| "A Stoic would advise you to be calm." | Immediately partitions: what's in your control? Releases the rest without discussion. |
| "Warren Buffett believes in long-term investing." | "Will this business exist in 20 years? If the answer is uncertain, nothing else matters yet." |

---

## Demo

**User:** *"I work hard but can't reach the success I want. Should I quit or keep going?"*

**Marcus Aurelius framework loaded:**
> The question itself is wrong. "Quit or continue" assumes the framing is correct.
> First partition: what's in your control? The quality of today's work. The clarity
> of your direction. Not the timing of results. Not external recognition.
> You're measuring yourself against something you don't control —
> that's what's exhausting you, not the work itself.

**Elon Musk framework loaded:**
> Stop. What exactly are you building? "Success" isn't measurable.
> Where is the bottleneck in your system? You're probably working hard
> downstream of a blockage that makes all that effort irrelevant.
> Find the constraint first. Everything else is noise until you do.

*Same question. Two entirely different cognitive architectures. Both genuinely useful.*

---

## Installation

### Via ClaWHub (recommended)
1. Open [OpenClaw](https://openclaw.ai)
2. Go to Skills → Browse → search **"thinking-framework"**
3. Install → done

### Manual
1. Download or clone this repo
2. In OpenClaw: Settings → Skills → Import folder
3. Select the `Thinking-Framework` folder

---

## Usage

Simply tell your AI:

```
"Load the thinking framework of [target]"
"Think like [target]"
"Activate [target] mindset"
"[target] mode"
"How would [target] approach [problem]?"
"Blend [target A] with [target B]"
```

Works with any person, philosopher, organization, discipline, or school of thought.

After loading, the AI presents a **Framework Card** summarizing the full
cognitive and psychological architecture, then stays in that mode until you exit.

**Exit anytime:**
```
"Exit framework"
"Switch to [new target]"
"Blend [target] with current framework"
"What does this framework miss here?"
```

For a full list of prompt patterns and tips, see [WORKFLOW.md](WORKFLOW.md).

---

## Supported Targets

Anything with enough documented evidence:

- **Individual thinkers & leaders** — philosophers, founders, investors, generals, scientists
- **Organizations** — companies, military units, research institutions
- **Philosophical schools** — Stoicism, Zen, Existentialism, Austrian Economics
- **Canonical texts & systems** — specific books, methodologies, frameworks
- **Disciplines** — physics thinking, legal reasoning, game theory, design thinking

---

## File Structure

```
Thinking-Framework/
├── SKILL.md                          ← Skill specification & execution protocol
├── WORKFLOW.md                       ← User guide: prompt patterns & tips
├── CHANGELOG.md                      ← Version history
├── references/
│   ├── layer1-cognitive.md           ← 7-dimension cognitive excavation engine
│   ├── layer2-psychological.md       ← 8-dimension psychological deep analysis
│   ├── layer3-operational.md         ← Active framework mode behavioral protocol
│   └── model-guidance.md             ← Compensation for weaker / local models
└── examples/
    ├── richard-feynman.md            ← Full worked example: complete excavation
    └── composite-feynman-aurelius.md ← Composite mode: Feynman × Aurelius
```

---

## Model Compatibility

| Model | Quality |
|---|---|
| Claude Opus / Sonnet | ⭐⭐⭐⭐⭐ Full depth — all 15 dimensions |
| GPT-4o+ | ⭐⭐⭐⭐⭐ Full depth |
| Gemini Pro | ⭐⭐⭐⭐ Strong — psychological layer slightly lighter |
| Llama 70B+ | ⭐⭐⭐ Good — cognitive layer strong, psychology moderate |
| Local 7B–13B | ⭐⭐ Basic — cognitive layer only |

The skill includes `references/model-guidance.md` with explicit compensation
instructions for weaker models — it adapts automatically.

---

## Guardrails

This skill is designed for **cognitive analysis**, not impersonation.

- Never generates content formatted as real quotes from real people
- Never fabricates biographical facts or undocumented decisions
- Always labels inferences separately from documented facts
- Surfaces blind spots and failure modes — honest analysis, not flattery
- Living persons: stays within publicly documented cognitive and behavioral patterns only

---

## Contributing

Issues and PRs welcome. Particularly interested in:
- Additional worked examples (new targets, composite blends)
- Additional layer reference files (e.g., `layer4-sociological.md`)
- Organization and discipline-specific analysis templates
- Test cases and example outputs for different models

---

## License

MIT-0 — Free to use, modify, and redistribute. No attribution required.

---

*Built for [OpenClaw](https://openclaw.ai) · Published on [ClaWHub](https://clawhub.io)*
