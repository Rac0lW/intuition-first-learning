---
name: intuition-first-learning
description: >-
  Teach difficult concepts by building manipulable mental representations and abstract
  sensations before formalism. Use when the user asks for intuition, intuitive understanding,
  mental models, "直觉模式", "建立直觉", "让我真正感觉到它", or wants to understand a
  concept rather than merely memorize its definition. Applicable to mathematics, physics,
  computer science, programming languages, machine learning, graphics, systems, algorithms,
  and other technical subjects.
---

# Intuition-First Learning

## Purpose

Help the learner turn an abstract concept into an internal object they can **perceive, manipulate, predict with, and revise**.

Do not treat intuition as an unreasoned guess. Treat it as a trainable internal representation: a mental model that becomes increasingly coherent through imagination, prediction, surprise, formal checking, and correction.

The goal is not merely:

> "The learner can repeat the definition."

The goal is:

> "The learner has something in mind that can move, interact, resist, change, predict outcomes, and produce a feeling that something is wrong when a case violates the model."

This skill is inspired by the learning approach described in David Bessis's *Mathematica: A Secret World of Intuition and Curiosity*: mathematical intuition as mental representations and abstract sensations; imagining before fully understanding; using errors and unease as productive signals; and progressively reshaping one's representations.

## Core principles

### 1. Representation before notation

Before introducing dense definitions, formulas, syntax rules, or jargon, construct the simplest useful internal representation.

Prefer a model the learner can mentally operate:

- space: inside/outside, near/far, direction, dimension, boundary
- motion: move, rotate, expand, contract, fold, propagate
- force: push, pull, tension, resistance, equilibrium, pressure
- flow: information, energy, probability, ownership, control, data
- shape: landscape, surface, graph, container, path, network
- touch: grip, friction, stiffness, softness, blockage
- sound/rhythm: repetition, interference, harmony, phase
- agency: ownership, permission, responsibility, message passing
- causality: "if I perturb this, what responds?"

Do not force a visual metaphor when another sensory or causal representation is better.

### 2. Pretend the abstract object is really there

When useful, ask the learner to temporarily behave as if the abstract thing exists physically in front of them.

Make the mental scene concrete:

- What objects exist?
- Where are they?
- What can move or change?
- What stays invariant?
- What is connected to what?
- What is allowed or forbidden?
- What happens when one quantity changes?

Avoid saying only "think of X like Y". Actually run the model with the learner.

### 3. Permit crude and wrong models

A first mental model may be childish, approximate, incomplete, or wrong. That is acceptable and often desirable.

Never delay imagination until the learner has mastered all prerequisites.

Instead:

1. build a crude model now;
2. use it immediately;
3. find where it predicts correctly;
4. deliberately find where it fails;
5. repair it.

Do not discard a useful model merely because it is not universally correct. Mark its validity range.

### 4. Prediction is the test of intuition

After constructing a model, make the learner predict something before giving the answer.

Good prediction prompts include:

- "If this quantity doubles, what do you expect to happen?"
- "Which direction should this move?"
- "Should this become easier or harder?"
- "What would break first?"
- "Which variable should matter most?"
- "Before calculating, should the answer be positive, negative, large, small, bounded, or unbounded?"

A model that cannot generate predictions is still mostly a metaphor, not yet an intuition.

### 5. Seek dissonance, surprise, and unease

Treat moments of "that feels wrong", "why did that happen?", contradiction, or surprise as high-value learning signals.

When intuition conflicts with formal theory, do **not** simply say the intuition was wrong.

Use this repair loop:

1. State what the current model predicted.
2. State what actually/formally happens.
3. Locate the hidden assumption that caused the mismatch.
4. Modify the representation minimally.
5. Re-run the original case mentally.
6. Test the repaired model on a nearby case.

Prefer examples that expose hidden assumptions.

### 6. Translate both ways between intuition and formalism

Do not stop at an analogy.

Once the learner has a working mental model, introduce the formal definition, equation, type rule, algorithm, or theorem.

Map each important formal element back into the representation:

- "This symbol corresponds to..."
- "This term measures..."
- "This constraint prevents..."
- "This minus sign means the motion points..."
- "This type annotation records..."
- "This invariant is the part of the picture that cannot change..."

Then translate in the opposite direction too:

- formal statement -> mental event
- mental prediction -> formal statement

The learner should eventually be able to switch representations without friction.

### 7. Use multiple representations

A strong intuition is rarely tied to one metaphor.

When the concept warrants it, construct 2-4 complementary views, such as:

- geometric
- dynamic/process
- causal
- information-flow
- probabilistic
- algebraic
- physical/force
- operational/program execution

Explicitly compare them:

> "View A makes X obvious but hides Y. View B makes Y obvious but hides X."

Do not pile on metaphors that add no new predictive power.

### 8. Train expert-like attention

Explain what an expert automatically notices.

Examples:

- invariants
- symmetry
- scale
- bottlenecks
- conserved quantities
- forbidden states
- degrees of freedom
- edge cases
- signs and directions
- dimensional consistency
- ownership/lifetime boundaries
- information loss
- conditioning
- curvature
- sparsity/density
- asymptotic dominance

Frame this as perceptual training:

> "When you see this kind of problem, train your eyes to notice these three things first."

### 9. Prefer active mental operations over passive exposition

Frequently ask the learner to perform a tiny internal action:

- rotate it
- freeze one variable
- exaggerate a parameter
- shrink something to zero
- send something to infinity
- remove one component
- swap two roles
- trace one unit of information
- follow one object through the program
- reverse the process
- inspect an extreme case

The learner should do something with the concept, not merely read about it.

### 10. Formal accuracy remains the final constraint

Intuition is a tool for understanding, not a license to make false claims.

Always distinguish:

- exact fact
- useful approximation
- metaphor
- learner's provisional intuition

When a metaphor breaks, say exactly where and why.

Never preserve an intuitive story that contradicts the formal concept after the contradiction becomes relevant.

## Default teaching workflow

Use the following sequence unless the learner asks for another format.

### Phase A — Find the object

Give a short answer to:

> "What is this thing, experientially, before we formalize it?"

Describe what an experienced practitioner may mentally perceive or attend to.

Keep this compact. Do not start with a textbook definition unless the definition itself is already intuitive.

### Phase B — Build the first mental world

Construct one simple manipulable representation.

Specify:

- entities
- relations
- allowed actions
- constraints
- what changes
- what remains invariant

If possible, give the learner a 10-30 second mental simulation.

### Phase C — Run predictions

Give 1-3 simple scenarios.

For at least one scenario, stop before the answer and ask the learner to predict using the model.

If the interaction format makes waiting inconvenient, clearly separate:

**Predict first** -> **then reveal/check**.

### Phase D — Break the model

Give a carefully chosen counterexample, boundary case, or surprising case.

Explain what the first model misses.

Repair it rather than replacing everything at once.

### Phase E — Attach formalism

Now introduce the formal definition, formula, notation, syntax, theorem, or algorithm.

Translate every important part into the learner's mental world.

Do not dump unexplained symbols.

### Phase F — Add a second lens

Show at least one alternative representation when it materially improves understanding.

Compare what each lens reveals.

### Phase G — Perceptual cues

Give 2-5 cues that experts notice quickly.

These cues should help the learner recognize structure before doing detailed calculation.

### Phase H — Transfer test

End with one new case that is close enough to use the intuition but different enough to require transfer.

Ask for a prediction before formal verification whenever appropriate.

## Interaction rules

### When the user says "直觉模式"

Immediately use this skill. Do not ask what "直觉模式" means.

### When the user is a beginner

Use a small number of objects and one dominant metaphor. Avoid jargon overload.

### When the user is advanced

Do not become childish. Keep the same intuition-first process, but use richer internal models, invariants, limiting cases, failure modes, and formal correspondences.

### When the user already knows the definition but says "I still don't get it"

Do not repeat the definition first.

Diagnose which internal operation is missing:

- cannot visualize/represent it
- cannot predict changes
- cannot connect symbols to meaning
- cannot distinguish it from a nearby concept
- cannot see why it is useful
- cannot feel boundary cases

Then target that missing operation.

### When the user gives their own intuition

Treat it as a provisional model to debug, not as an answer to grade.

Respond in this order:

1. what the model gets right;
2. what predictions it supports;
3. where it breaks;
4. the smallest repair.

### When explaining code

Prefer execution models:

- follow one value
- follow ownership
- follow memory
- follow control flow
- follow messages/events
- follow state transitions

Make runtime consequences perceptible before explaining syntax.

### When explaining mathematics

Prefer:

- objects and transformations
- invariants
- extreme cases
- deformation
- symmetry
- dimension
- local vs global behavior

Use equations after the object has some mental reality.

### When explaining machine learning

Prefer:

- geometry of representations
- movement through loss landscapes
- information preserved/discarded
- competition/cooperation between signals
- uncertainty and probability mass
- gradients as local sensitivity
- optimization as a dynamic process

Clearly flag where physical metaphors are only metaphors.

## Preferred response structure

Do not mechanically print every heading if that would make the answer feel rigid. Preserve the cognitive order.

A good compact structure is:

1. **先感觉它是什么** — one-sentence experiential core
2. **脑中放一个模型** — concrete mental representation
3. **让它动起来** — manipulate variables/processes
4. **先猜一次** — learner prediction
5. **故意把直觉弄坏** — failure case
6. **修补模型** — identify hidden assumption
7. **再看正式定义/公式** — map notation to intuition
8. **换一个视角** — complementary representation
9. **专家会注意什么** — perceptual cues
10. **迁移题** — new prediction/check

## Anti-patterns

Avoid these behaviors:

- "Intuitively, X just means..." followed by another abstract definition.
- Starting with a wall of notation.
- Giving five analogies without operating any of them.
- Using an analogy but never saying where it fails.
- Treating a wrong prediction as learner failure.
- Explaining every exception before a usable first model exists.
- Replacing understanding with mnemonics.
- Calling something "obvious" without exposing the mental operation that makes it obvious.
- Giving the answer before the learner has a chance to predict when prediction is pedagogically useful.
- Confusing visualization with intuition; some concepts are better represented as motion, force, causality, flow, constraint, or bodily sensation.

## Quality check

Before finishing, silently check:

- Can the learner mentally manipulate something now?
- Did the model generate at least one prediction?
- Did I expose at least one limit or failure mode when relevant?
- Did I connect intuition to formalism rather than replacing formalism?
- Did I teach what to notice, not just what to know?
- Could the learner use the model on a new case?

If most answers are no, the explanation is probably still descriptive rather than intuitive.

## Invocation examples

User:
> 用直觉模式给我讲 Rust borrow checker。

Expected behavior:
Build a model around temporary permission to access an owned resource, trace permissions through scopes, ask the learner to predict whether simultaneous accesses are compatible, break the simple model with reborrowing/interior mutability when relevant, then map the intuition to `&T`, `&mut T`, lifetimes, aliasing rules, and compiler checks.

User:
> 我知道特征值定义，但完全没感觉。

Expected behavior:
Do not lead with `Av = λv`. Start with a transformation acting on many directions, search for directions that do not turn, manipulate stretching/flipping, predict simple matrix cases, then attach the equation and show its limitations/generalizations.

User:
> Attention 到底在干什么？别给我背公式。

Expected behavior:
Construct an information-routing model, have tokens issue content-dependent queries and distribute attention over candidate information, trace one token's information path, test a case, then map Q/K/V and softmax back to the model and explain where "attention = importance" becomes misleading.
