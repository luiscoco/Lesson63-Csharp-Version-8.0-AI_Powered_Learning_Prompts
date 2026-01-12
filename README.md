# Lesson 63 - C# Version 8.0 AI-Powered Learning Prompts

Role framing: Your AI assistant acts as a Language–Runtime Integrator and Correctness Architect.

The goal is not memorization, but reshaping how you think about correctness, APIs, and evolution.
________________________________________

## Section 1 - Historical & Strategic Understanding

### Practice Prompt 1: The .NET Core Turning Point

Ask your AI assistant:

“Why is C# 8.0 the first release that can only be fully understood in the context of .NET Core?”

Focus on:

•	Why earlier C# versions could evolve mostly independently

•	What changed architecturally with .NET Core

•	Why coordinated evolution (language + runtime + libraries) became necessary

Outcome:

You should be able to explain why C# 8.0 marks a phase shift, not just a feature release.
________________________________________

### Practice Prompt 2: Correctness as a Design Goal

Ask:

“How does C# 8.0 redefine correctness compared to earlier versions of the language?”

Focus on:

•	What “correctness” meant before (discipline, tests, runtime checks)

•	How C# 8.0 moves correctness into compiler analysis

•	Why this is a philosophical change, not just tooling improvement

Outcome:

You should see correctness as a first-class language concern, not a best practice.
________________________________________

## Section 2 - Nullable Reference Types (Mental Models)

### Practice Prompt 3: The Null Problem Reframed

Ask:

“Why was NullReferenceException such a persistent problem in C#, and why couldn’t discipline or documentation solve it?”

Focus on:

•	The mismatch between intent and enforcement

•	The limits of comments and conventions

•	Why scaling teams made this worse over time

Outcome:

You should understand nulls as a semantic gap in the language.
________________________________________

### Practice Prompt 4: Nullable Reference Types Without Syntax

Ask:

“Explain nullable reference types without showing any syntax. Focus only on the mental model and compiler behavior.”

Focus on:

•	How intent is encoded

•	How the compiler reasons about code flow

•	Why warnings matter more than runtime failures

Outcome:

You should clearly understand nullable references as a contract system, not a syntax feature.
________________________________________

### Practice Prompt 5: Why Library Annotations Matter

Ask:

“Why are nullable reference types only truly effective when libraries participate?”

Focus on:

•	Caller vs callee responsibilities

•	How annotated APIs improve downstream correctness

•	Why this required updates to .NET Core libraries

Outcome:

You should grasp language–library cooperation as essential to correctness.
________________________________________

## Section 3 - API Evolution & Runtime Changes

### Practice Prompt 6: The Interface Versioning Trap

Ask:

“Why were interfaces historically hard to evolve, and how did that constrain framework design?”

Focus on:

•	Binary compatibility

•	Breaking changes

•	Why adding a single method could be catastrophic

Outcome:

You should be able to explain why interfaces were effectively ‘frozen’.
________________________________________

### Practice Prompt 7: Default Interface Members

Ask:

“Why did default interface members require runtime changes, and why couldn’t they be added earlier?”

Focus on:

•	The role of the CLR

•	Dispatch and versioning mechanics

•	Why this feature only became possible in .NET Core 3.0

Outcome:

You should understand this as a runtime-enabled language feature, not a compiler trick.
________________________________________

### Practice Prompt 8: API Evolution Thinking

Ask:

“How do default interface members change how we design public APIs over time?”

Focus on:

•	Backward compatibility

•	Incremental evolution

•	Framework and SDK stability

Outcome:

You should see interfaces as evolvable contracts, not brittle definitions.
________________________________________

## Section 4 - Control Flow Becomes Declarative

### Practice Prompt 9: Pattern Matching as a Model

Ask:

“How does pattern matching in C# 8.0 move control flow from imperative logic to declarative intent?”

Focus on:

•	Exhaustiveness

•	Shape-based matching

•	Reduced nesting and clearer intent

Outcome:

You should see pattern matching as a control-flow system, not a convenience feature.
________________________________________

### Practice Prompt 10: From if/else to Switch Expressions

Ask:

“Rewrite a complex if/else decision tree using C# 8.0 switch expressions and explain what becomes clearer.”

Focus on:

•	Missing cases

•	Readability

•	Compiler enforcement

Outcome:

You should feel how declarative control flow improves reasoning.
________________________________________

## Section 5 - Async Becomes Compositional

### Practice Prompt 11: Async Before C# 8.0

Ask:

“What was awkward about combining async programming with iteration before C# 8.0?”

Focus on:

•	Async returning single values

•	Streaming data limitations

•	Workarounds and complexity

Outcome:

You should see the gap between async and iteration clearly.
________________________________________

### Practice Prompt 12: Async Streams as a Design Tool

Ask:

“How do async streams change how we design IO-heavy or event-driven APIs?”

Focus on:

•	Streaming data

•	Backpressure

•	Natural async composition

Outcome:

You should understand async streams as enabling scalable, compositional pipelines.
________________________________________

## Section 6 - Safer Data Access & Smaller Features

### Practice Prompt 13: Indices and Ranges

Ask:

“Why are indices and ranges about correctness, not just nicer slicing syntax?”

Focus on:

•	Off-by-one errors

•	Expressive intent

•	Compiler and library collaboration

Outcome:

You should recognize slicing as a correctness problem, not a syntax one.
________________________________________

### Practice Prompt 14: Shared Direction of Smaller Features

Ask:

“What common design philosophy connects features like using declarations, ??=, readonly members, and static local functions?”

Focus on:

•	Reduced ambiguity

•	Stronger intent

•	Fewer error-prone patterns

Outcome:

You should see C# 8.0 as a cohesive correctness release, not a grab-bag of features.
________________________________________

## Section 7 - Evaluation & Synthesis

### Practice Prompt 15: Applying the Evolution Framework

Ask:

“Evaluate C# 8.0 using the evolution framework: problems solved, semantic impact, and ecosystem effects.”

Focus on:

•	Problems eliminated

•	Semantic vs syntactic change

•	Language–runtime–library alignment

Outcome:

You should be able to defend why C# 8.0 is one of the most consequential releases in the language’s history.
________________________________________

## Final Reflection Prompt

Practice Prompt 16: The Philosophy Shift

Ask:

“How does C# 8.0 change the relationship between the developer and the compiler?”

Focus on:

•	Compiler as partner

•	Correctness as default

•	Productivity through safety

Outcome:

You should internalize this principle:

After C# 8.0, correctness is not optional — it is designed in.

