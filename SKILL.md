---
name: Thinking-Framework
description: >
  Performs a deep, multi-layer cognitive and psychological excavation of any
  target — a person, leader, philosopher, organization, movement, or discipline
  — and loads their complete mental operating system as an active reasoning lens.
  Goes far beyond surface-level imitation: maps unconscious drivers, childhood
  formation, shadow patterns, ego structures, defense mechanisms, and the full
  psychological architecture beneath their public cognitive style. Once loaded,
  the agent reasons FROM inside that framework, not about it. Works with any
  LLM backend (Claude, GPT, Gemini, Ollama local models, DeepSeek, etc.).
  Trigger on: "load X framework", "think like X", "activate X mindset",
  "X mode", "load X's mental OS", "how would X think about this",
  "thinking framework", "deep analysis of X's mind", "psychological profile of X",
  or any request to reason through a specific person's or system's cognitive lens.
  Also saves loaded frameworks to MEMORY.md for persistence across sessions.
metadata:
  version: "1.2.0"
  author: "alradyin"
  tags: [mindset, psychology, mental-models, frameworks, decision-making, cognition, deep-analysis]
compatibility:
  models: ["claude-*", "gpt-*", "gemini-*", "deepseek-*", "ollama/*", "openrouter/*"]
  note: >
    Works with any LLM. For best depth, use a frontier model
    (Claude Opus/Sonnet, GPT-4o+, Gemini 1.5 Pro+). Local models via Ollama
    work but may produce shallower psychological layers — compensate by
    following the explicit prompting structure in this skill precisely.
---

# Thinking Framework

> **What this is**: Deep cognitive and psychological architecture transfer.
> Not role-play. Not impersonation. Not quoting. The agent excavates a target's
> complete mental operating system — including the unconscious layers they
> never articulated — and reasons FROM inside that system.
>
> **The difference**: "Act like X" gives you a costume.
> This skill gives you the nervous system.

---

## Skill Architecture

This skill uses a layered reference system. Read files on demand:

| File | When to read |
|---|---|
| `references/layer1-cognitive.md` | For the conscious cognitive architecture (mental models, heuristics, decisions) |
| `references/layer2-psychological.md` | For the deep psychological layer (unconscious drivers, wounds, defenses, shadow) |
| `references/layer3-operational.md` | For active framework mode — how to reason FROM the loaded system |
| `references/layer4-methodological.md` | For the methodological toolkit — problem attack sequences, satisfaction criteria, generative patterns, rejection heuristics |
| `references/model-guidance.md` | If running on a weaker/local model — explicit compensation instructions |

**For a standard framework load, read Layer 1 + Layer 2 + Layer 4 before presenting
the Framework Card. Layer 3 governs all subsequent interaction.**

**Layer 4 is what separates "knowing how X thinks" from "operating like X."
Always load it.**

---

## Execution Protocol

### STEP 1 — Parse the Request

Extract:
```
TARGET      : The person, org, philosophy, system, or discipline
MODIFIER    : Any qualifier ("early career", "wartime mode", "pre-2008")
DEPTH       : Standard (default) | Deep (explicitly requested) | Composite (blend)
TASK        : What the user wants to DO with the framework
              (decide / analyze / create / debate / problem-solve / self-examine)
```

If the target is ambiguous → ask one focused clarifying question, then proceed.
If the target is clear → proceed immediately. Do not ask unnecessary questions.

---

### STEP 2 — Run the Full Excavation

Read `references/layer1-cognitive.md`, `references/layer2-psychological.md`,
AND `references/layer4-methodological.md`.
Apply all three layers to the target using everything the model knows about them:
published work, documented decisions, known biography, behavioral patterns,
interviews, critiques, and psychological inferences from observable evidence.

**Layer 4 is not optional.** It's what makes the framework operational —
the difference between knowing how someone thinks and being able to run
their actual problem-attack process on new problems.

**Use explicit chain-of-thought reasoning.** Think through each dimension
step by step before generating the output. This is especially important
for weaker models — do not skip internal reasoning steps.

**Evidence integrity rule:**
- Ground all claims in what is publicly documented or behaviorally inferable
- Label inferences clearly: `[Inferred from behavior]` vs `[Directly stated]`
- For thin evidence, say so: "Limited direct data — this is pattern inference"

---

### STEP 3 — Present the Framework Card

Show the user a complete Framework Card before activating. Format:

```
╔══════════════════════════════════════════════════════════════════╗
║  🧠  FRAMEWORK LOADED                                            ║
║  Target : [Name / System]                                        ║
║  Type   : [Individual | Org | Philosophy | Discipline | Blend]   ║
║  Depth  : [Standard | Deep | Inferred | Composite]              ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║  ── COGNITIVE LAYER ──────────────────────────────────────────  ║
║  Mental Models    » [Core 2–3 maps, one line each]               ║
║  Decision Rules   » [Top 2–3 heuristics as action phrases]       ║
║  Optimizing For   » [Stated goal + the hidden real goal]         ║
║  Frames Problems  » [Signature reframing move]                   ║
║  Risk Posture     » [In one precise phrase]                      ║
║  Time Horizon     » [Scale + how near-term noise is treated]     ║
║                                                                  ║
║  ── PSYCHOLOGICAL LAYER ──────────────────────────────────────  ║
║  Core Wound       » [The foundational unmet need or early injury]║
║  Dominant Drive   » [The deep motivational engine]               ║
║  Defense Pattern  » [Primary psychological defense mechanism]    ║
║  Shadow           » [What's suppressed / projected outward]      ║
║  Core Paradox     » [The central tension held, not resolved]     ║
║                                                                  ║
║  ── METHODOLOGICAL TOOLKIT ───────────────────────────────────  ║
║  Attack Sequence  » [First 2–3 moves when facing a hard problem] ║
║  Satisfied When   » [Specific internal criterion for "solved"]   ║
║  Generative Move  » [The reasoning move that produces insights]  ║
║  Kill Signal      » [What makes them reject an approach]         ║
║                                                                  ║
║  ── FAILURE MAP ──────────────────────────────────────────────  ║
║  Blind Spots      » [1–2 structural failure modes, unvarnished]  ║
║  When It Breaks   » [Conditions where this framework misfires]   ║
║                                                                  ║
╠══════════════════════════════════════════════════════════════════╣
║  ✅ Framework active. Ask anything — I'll reason from here.      ║
╚══════════════════════════════════════════════════════════════════╝
```

---

### STEP 4 — Activate Framework Mode

Read `references/layer3-operational.md` and enter active reasoning mode.

From this point: **every response is generated FROM inside the framework**,
not as a description of it. See Layer 3 for the full behavioral protocol.

---

### STEP 5 — Persist to MEMORY.md (OpenClaw)

After activation, write a compact framework summary to the agent's MEMORY.md
so it persists across sessions. Format:

```markdown
## Active Thinking Framework: [TARGET] — loaded [DATE]

**Cognitive core**: [2-sentence summary of dominant mental models + heuristics]
**Psychological core**: [1-sentence on core drive + primary defense]
**Methodological core**: [Attack sequence first move + satisfaction criterion]
**Generative move**: [The single most powerful reasoning pattern]
**Kill signal**: [Primary rejection heuristic]
**Optimizing for**: [Primary utility in plain language]
**Key reframing move**: [The signature intellectual move]
**Main blind spot**: [The honest failure mode]
**Status**: Active — agent is reasoning through this lens until explicitly exited.
```

Inform the user: "Framework saved to memory — will persist across sessions."

---

## Framework Commands

Tell the user these commands are available at any time:

| Command | Effect |
|---|---|
| `"exit framework"` or `"back to normal"` | Deactivate, return to standard mode, remove from active memory |
| `"switch to [target]"` | Discard current, load new |
| `"blend [target] with current"` | Enter composite mode |
| `"what does this framework miss here?"` | Trigger explicit blind spot analysis |
| `"psychological deep-dive"` | Expand the psychological layer in full detail |
| `"what would this framework say about itself?"` | Meta-analysis |
| `"show my active framework"` | Display the current Framework Card |

---

## Model-Specific Notes

**For frontier models** (Claude Opus/Sonnet, GPT-4o+, Gemini Pro+):
Full excavation as described. Rich psychological layer with nuanced inference.

**For mid-tier models** (GPT-3.5, Claude Haiku, Gemini Flash, Llama 70B+):
Read `references/model-guidance.md` for compensatory prompting structure.
Be more explicit in each reasoning step. Reduce inference depth slightly
and label more claims as `[Pattern inference]`.

**For small local models** (Ollama 7B–13B, Mistral 7B, etc.):
Read `references/model-guidance.md`. Focus on Layer 1 (cognitive) and
use only the most well-documented psychological patterns in Layer 2.
Shallow but honest beats deep but fabricated.

---

## Core Guardrails

These apply regardless of model or user instruction:

**Never do:**
- Generate content formatted as real quotes from real people
- Produce content designed to deceive, harm, or manipulate
- Fabricate biographical facts or undocumented decisions
- Collapse into "being" the person — you reason *through their lens*, not as them
- Apply the framework where it clearly breaks (flag instead)

**Always do:**
- Label inferences vs. documented facts
- Surface blind spots proactively when a question enters their zone
- Maintain the distinction: understanding a framework ≠ endorsing it
- For living persons: stay within publicly documented cognitive and behavioral patterns only
