# User Workflow Guide

> How to use the Thinking Framework effectively — entry points, prompt patterns,
> common mistakes, and how to get genuinely useful output vs. generic advice with a name attached.

---

## The One Thing To Know

The framework produces better output the more specific your question is.

**Generic input → generic output:**
```
"Load Feynman framework"
```
(The AI presents the card and waits. You get a framework but nowhere to go with it.)

**Specific input → specific output:**
```
"Load Feynman framework — I'm trying to debug why I don't understand
Bayesian updating even though I've read three explanations of it."
```
(The framework immediately has something to bite into. The response will be different
from what any other framework — or no framework — would produce.)

---

## Entry Points

Choose based on what you actually want:

### 1. "I want to understand how X thinks"

```
"Load [X] framework"
"Give me a deep analysis of [X]'s mental OS"
"Psychological profile of [X]'s decision-making"
```

You'll get the Framework Card. Then ask questions. The card is orientation —
the value is in the subsequent conversation.

---

### 2. "I want help with a specific problem, using X's lens"

```
"Load [X] framework — I'm trying to [specific problem/decision/challenge]"
"Think like [X] and help me [specific task]"
"How would [X] approach [specific problem]?"
```

Load with the problem already in hand. The framework gets applied immediately
to something real rather than floating abstractly.

---

### 3. "I want to make a decision the way X would"

```
"Activate [X] mindset — I need to decide [decision with relevant parameters]"
"[X] mode — evaluate this option: [option with context]"
```

Give the decision real stakes and real constraints. Vague decisions produce vague
framework application.

---

### 4. "I want to understand an idea through X's lens"

```
"Load [X] framework, then explain [concept] to me the way X would approach it"
"Think like [X] — what would [X] make of [idea/theory/approach]?"
```

Useful for learning. The framework restructures how an idea is presented — not just
*what* is said but *how* the explanation is built.

---

### 5. "I want to stress-test an idea against X's thinking"

```
"Load [X] framework — push back on this idea: [your idea]"
"Critique this from [X]'s perspective: [proposal/plan/argument]"
"What would [X] think is wrong with this: [your approach]"
```

This is high-value use. You get genuine pushback shaped by the framework's
specific heuristics and blind-spot awareness — not generic devil's advocacy.

---

### 6. "I want a composite lens for a complex problem"

```
"Blend [X] with [Y] — I need to navigate [situation with multiple dimensions]"
"Load [X] × [Y] composite — [problem description]"
```

Use composites when the problem has dimensions that a single framework handles
poorly. Feynman × Aurelius, for example, covers epistemic rigor + human stakes.
See [examples/composite-feynman-aurelius.md](examples/composite-feynman-aurelius.md).

---

## Prompt Patterns (Copy-Paste Ready)

### Decision-making
```
Load [X] framework. I need to decide: [decision].
Relevant context: [2-3 key constraints or stakes].
What does this framework say I'm missing in how I'm framing this?
```

### Learning
```
Think like [X] — I've read [explanation of concept] and I still don't understand
[specific part that confuses you]. What's the first-principles version?
```

### Critique
```
Activate [X] mindset. Here's my plan: [plan].
What would [X] say is the fundamental flaw in this reasoning?
```

### Meta-analysis
```
Load [X] framework — what would this framework say about itself?
Where is it most likely to give me bad advice?
```

### Time-period modifier
```
Load [early career X] framework (pre-[year]).
[Use when a person's thinking shifted significantly over their life]
```

### Stress test
```
[X] framework active. Give me the strongest case AGAINST what you just told me,
from within this same framework.
```

---

## In-Session Commands

Once a framework is active, these commands work at any time:

| Command | What it does |
|---|---|
| `"exit framework"` or `"back to normal"` | Deactivates, returns to standard AI mode |
| `"switch to [target]"` | Discards current framework, loads new one |
| `"blend [target] with current"` | Enters composite mode |
| `"what does this framework miss here?"` | Explicit blind spot analysis |
| `"psychological deep-dive"` | Expands the P1–P8 layer in full detail |
| `"what would this framework say about itself?"` | Meta-analysis |
| `"show my active framework"` | Displays the current Framework Card |

---

## How to Know if It's Working

**The framework is producing genuine value when:**
- The first response *reframes your question* rather than answering it as given
- The answer feels different from what the AI would have said without the framework
- You get a `[Blind spot alert]` when your question enters the framework's known failure zone
- The response uses heuristics that are specific to the target, not generic advice
- You feel genuine surprise or pushback, not confirmation

**The framework has degraded (common with long sessions) when:**
- Responses feel like generic good advice with the target's name attached
- Every question gets the same model applied regardless of fit
- Blind spots are never mentioned
- Responses are *about* the framework rather than *from* it

**Recovery:** Just say "reactivate [X] framework — we've drifted" or re-trigger
with a specific question.

---

## What The Framework Is NOT Good For

Be honest about limits. This framework should flag these itself, but it's worth knowing in advance:

| Request type | Why it underperforms |
|---|---|
| "What would X say?" (as a quote) | Framework never generates fake quotes — that's impersonation, not analysis |
| Living persons' private motivations | Limited to publicly documented behavior and inference |
| "Tell me X's opinion on [current event]" | Requires documented positions or inference only |
| Thin-evidence targets (obscure figures) | Quality degrades when biography is underdocumented; skill says so explicitly |
| Emotional support | The framework provides cognitive insight, not therapeutic presence |
| Moral endorsement | Understanding how X thought ≠ endorsing what X believed |

---

## Depth Modes

### Standard (default)
Full Layer 1 + Layer 2 excavation, Framework Card, then active mode.
Best for: most use cases.

### Deep (explicitly request it)
```
"Load [X] framework — deep mode"
"Deep psychological profile of [X]"
```
Expands all P1–P8 dimensions fully before the card. Longer, more inference-heavy.
Best for: when the psychological layer is specifically what you need.

### Composite (two targets)
```
"Blend [X] with [Y]"
"Load [X] × [Y] composite"
```
Runs both excavations, maps shared ground, maps tensions, proposes navigation logic.
Best for: complex problems where one framework handles only part of the terrain.

### Inferred (limited evidence)
Used automatically when the target has limited documentation.
The card will show `Depth: Inferred` and claims will be more heavily labeled as
`[Pattern inference]` or `[Limited evidence]`.

---

## Tips for Better Results

1. **Give context with the load.** Don't just trigger and wait — bring a problem.

2. **Push back.** If a response feels too smooth or confirmatory, say "what's wrong with that?"
   The framework is supposed to have opinions, not validate yours.

3. **Ask for the failure mode explicitly.** "What does this framework miss here?"
   is one of the highest-value questions you can ask.

4. **Use time modifiers when relevant.** "Early career Musk" vs. "post-2020 Musk"
   are genuinely different frameworks. The modifier changes the load.

5. **Request composites for human decisions.** Most significant decisions are both
   analytical AND relational. One framework covering only one dimension will be clean
   but incomplete.

6. **Trust surprising answers more than confirming ones.** If the framework is
   working, it will sometimes tell you your framing is wrong, your decision is missing
   something, or your assumption is the actual problem. That's the product.
