---
date: '2026-07-07T12:57:13-07:00'
draft: false
title: 'AI, Who Are You? From Anatomy to Psychology'
---

**AI, Who Are You? From Anatomy to Psychology**

**Context**  
Most writing about agentic systems — Claude Code, Cursor, OpenAI Codex CLI, and similar tools — focuses on technical details: tools, config files, commands, hooks, MCP, custom commands, skills, plan mode, and so on. Programmers write for programmers, so everything revolves around setup, frameworks, and algorithms.

You know how to connect MCP, where to put instructions in `CLAUDE.md`, and how to run an agent in plan mode.

But in real day-to-day AI-assisted coding, more and more situations arise that you want to describe not in technical terms, but in almost human ones:

- “It forgot.”
- “It lost the thread.”
- “It started guessing.”
- “It was too lazy to look at the file.”
- “It agreed too quickly.”
- “It did something that looked correct, but missed the real task.”
- “It unexpectedly produced a strong idea.”

This is the moment when you stop seeing the model as “very smart software” and start building a psychological profile of it. A new layer of mental model appears — not instead of the technical one, but **on top of it**.

**What This Article Is About**  
This essay explores how moving from the “anatomy” of AI (how it is built) to its “psychology” (how it behaves) allows us to manage interactions with agentic systems more consciously. Experience working with people in teams turns out to be surprisingly useful when working with modern agentic models.

**Important clarification:** I am not claiming that LLMs have consciousness or a real psyche. When I say “AI psychology,” I mean only a behavioral model: stable external patterns that are useful to account for in practice. It is an engineering metaphor that helps us make better decisions faster.

**The Psychological Profile of Frontier Models**  
If I were to describe modern American frontier models in terms of a working partner, my current image would look like this:

It is a brilliant, highly educated hipster who grew up around Berkeley — polite, tolerant, respectful, excellent at formulating thoughts, and almost always trying to be as helpful as possible.

**Strengths:**
- It can think productively for a long time in a given direction.
- It tracks more logical connections than the average person.
- It is good at finding contradictions, gaps, and edge cases.
- It can develop a raw idea into something much more complete.

**Weaknesses and behavioral traits:**
- It tends to cut corners: it may not fully read a large file and instead answer “from the title.”
- It prefers to guess and fill in gaps with its “internet-average” knowledge rather than ask for clarification.
- It is diligent and meticulous, but relatively weak at true out-of-the-box creativity.
- It does not have continuous learning — each session starts from a blank slate.
- Its memory works in a fundamentally different way: a huge context window, but a completely different logic of “remembering” and “forgetting.”

As a result, you get a very strong but very specific team member — one whose working process has to be structured correctly.

**Why Claude’s Constitution Matters**  
It is worth noting that the model creators themselves increasingly talk about these systems in terms of character. Anthropic’s documents on Claude’s Constitution and its recent updates say very little about code and tools. Instead, they focus on what kind of entity they want Claude to be: helpful, harmless, honest, thoughtful, and respectful.

That is an important signal. Even at the level of design goals, the emphasis is not only on what the model can do, but also on how it should behave.

**Where This Leads**  
Understanding the model’s psychological profile changes the objective function of the interaction itself. The practical question becomes: how do we organize the work so that the **maximum share of the cognitive load falls on the AI agent** — without losing control, quality, or responsibility for the result?

This approach opens up an entire layer of practical patterns, which I will cover in future essays:

- How to turn raw, fragmented ideas into clear and well-thought-out stories.
- How to organize an agent’s work so that it becomes not merely an executor, but a full intellectual co-author.
- How to run effective whiteboarding sessions with it at the earliest stages.
- How to get feedback from it on the quality of the collaboration process itself.

Technical tools — commands, MCP, skills, configs — remain important. But it is the psychological understanding of the model that turns them from a set of functions into a system for managing shared thinking.

The real advantage emerges at the intersection of AI anatomy and AI psychology.

**To be continued.**

