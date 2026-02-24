---
name: product-discovery
description: >
  Guide product managers through the Design Thinking Empathy and Problem Definition phases,
  plus Value Hypothesis formulation — the initial stages of the product capability and feature
  definition pipeline. Produces a comprehensive discovery document with user personas, empathy maps,
  jobs-to-be-done, user journey maps, pain point inventories, problem statements, "How Might We"
  questions, stakeholder analysis, value hypotheses, success metrics, and MVP scope recommendations.
  Supports two entry modes: interactive interview (guided questions from scratch) or context dump
  (user provides research/notes, then clarifying questions follow). Use when the user says
  "product discovery", "empathy mapping", "problem definition", "value hypothesis", "feature discovery",
  "user research synthesis", "JTBD analysis", "design thinking", "discovery phase", "PM discovery",
  or wants to define a new product capability or feature from the ground up.
---

# Product Discovery

Facilitate the Design Thinking Empathy & Problem Definition phases plus Value Hypothesis formulation. Produce a comprehensive discovery document that serves as the foundation for solution design and prioritization.

## Workflow Overview

Product discovery involves these stages:

1. **Entry & Context Gathering** — Determine entry mode, collect all available context
2. **Empathy Synthesis** — Build personas, empathy maps, JTBD, journey maps
3. **Problem Definition** — Pain point inventory, problem statement, HMW questions, stakeholder analysis
4. **Value Hypothesis** — Hypothesis formulation, assumptions, value proposition canvas, success metrics
5. **Document Assembly** — Compile the full discovery document

Follow these stages sequentially. Each stage builds on the previous. Do not skip stages.

## Stage 1: Entry & Context Gathering

Determine entry mode by asking one question using AskUserQuestion:

> I can help you through product discovery in two ways:
>
> **A) Interactive Interview** — I'll guide you through structured questions to build up the full picture from scratch.
>
> **B) Context Dump** — You provide existing research, meeting notes, user feedback, or any context you have, and I'll synthesize it and ask targeted follow-up questions.
>
> Which approach works best for you? (Or just start dumping context and I'll follow mode B.)

### Mode A: Interactive Interview

Ask questions in focused batches of 3-5 using AskUserQuestion. Do not overwhelm with all questions at once. Progress through these areas in order:

**Batch 1 — The Opportunity Space:**
- What product area or domain is this for?
- What capability or feature are you exploring?
- What triggered this discovery? (customer feedback, market signal, strategic initiative, observed behavior)

**Batch 2 — The Users:**
- Who are the primary users affected? (roles, segments, contexts)
- How do these users currently solve this problem or accomplish this task?
- What do you already know about their frustrations?

**Batch 3 — The Business Context:**
- What business objectives does this serve?
- Who are the key stakeholders and decision-makers?
- Are there known constraints? (technical, regulatory, timeline, budget)

**Batch 4 — Existing Evidence:**
- Do you have any user research, analytics, or feedback data?
- Have competitors addressed this? How?
- Are there related features or past attempts to solve this?

After each batch, synthesize what has been learned and identify gaps before asking the next batch. Adapt questions based on answers — skip questions already addressed, go deeper where needed.

### Mode B: Context Dump

Accept whatever the user provides: research reports, meeting transcripts, feedback summaries, strategy docs, or stream-of-consciousness notes. After receiving context:

1. Summarize what was understood in 3-5 bullet points
2. Identify the top gaps using AskUserQuestion with 5-10 targeted clarifying questions
3. Continue asking follow-ups until sufficient context exists to proceed

**Sufficient context exists when:**
- At least one user segment is clearly identified
- The current state and pain points are understood
- The business motivation is clear
- Enough detail exists to draft personas and problem statements

If the user provides file paths, read them. If they mention meetings, ask for transcripts or key takeaways.

## Stage 2: Empathy Synthesis

Read `references/empathy-frameworks.md` for detailed templates.

Build the following artifacts from gathered context:

### 2.1 User Personas
Create 1-3 personas (primary + secondary). Each must include demographics/context, behavioral patterns, goals/motivations, frustrations, and a representative quote. Validate with the user using AskUserQuestion: present the draft persona and ask if it rings true.

### 2.2 Empathy Maps
For each persona, complete the Think/Feel/Say/Do quadrants. Highlight contradictions between quadrants — these reveal the deepest insights.

### 2.3 Jobs-to-be-Done
Capture functional, emotional, and social jobs using the "When I... I want to... so I can..." format. Prioritize by importance and current satisfaction gap to identify the opportunity space.

### 2.4 Current-State User Journey
Map the end-to-end journey for the primary persona's core job. Include actions, touchpoints, thoughts, emotions, pain points, and opportunities at each stage. Identify critical moments of truth and drop-off points.

**Checkpoint:** Present a summary of empathy findings to the user via AskUserQuestion. Ask: "Does this accurately capture your users' experience? Anything missing or off?"

## Stage 3: Problem Definition

Read `references/problem-definition.md` for detailed templates.

### 3.1 Pain Point Inventory
Compile all identified pain points into a categorized, severity-ranked table. Calculate Impact Score (Severity x Frequency). Highlight the top 3.

### 3.2 Problem Statement
Draft a user-centered problem statement using Format 1 (primary) and Format 2 (supporting). If the problem seems layered, run a Five Whys analysis to find the root cause.

### 3.3 "How Might We" Questions
Generate 5-10 HMW questions across multiple categories (amplify positive, remove negative, explore opposite, question assumptions, change sequence, adjacencies). Recommend 2-3 priority HMWs.

### 3.4 Stakeholder Analysis
Map stakeholders with interest level, influence level, stance, and engagement strategy. Create the power-interest grid summary.

### 3.5 Problem Scope & Boundaries
Define in-scope, out-of-scope, dependencies, and constraints explicitly.

**Checkpoint:** Present the problem statement and top HMW questions to the user via AskUserQuestion. Ask: "Does this problem statement resonate? Are the HMW questions opening the right solution space?"

## Stage 4: Value Hypothesis

Read `references/value-hypothesis.md` for detailed templates.

### 4.1 Value Hypothesis Statement
Formulate 1-3 value hypotheses in If/Then/Because format. Each must include a measurable outcome, timeframe, and confidence level.

### 4.2 Riskiest Assumptions
Identify and rank assumptions across Desirability, Viability, Feasibility, and Usability. For the top 3 leap-of-faith assumptions, recommend the cheapest validation test, signal to look for, and kill criterion.

### 4.3 Value Proposition Canvas
Complete both sides: Customer Profile (jobs, pains, gains) and Value Map (offerings, pain relievers, gain creators). Assess fit and identify gaps.

### 4.4 Success Metrics & KPIs
Define: North Star metric, 3-5 leading indicators, 2-3 lagging indicators, and 1-2 counter-metrics. Include measurement plan.

### 4.5 MVP Scope Recommendation
Based on riskiest assumptions, recommend the minimum viable test: what to build, what not to build, success criteria, and suggested timeline.

**Checkpoint:** Present the primary value hypothesis and riskiest assumptions to the user via AskUserQuestion. Ask: "Does this hypothesis capture the core bet? Are these the right assumptions to test first?"

## Stage 5: Document Assembly

Read `references/output-template.md` for the complete document template.

Compile all artifacts into a single comprehensive markdown document following the output template. Save to the working directory as `product-discovery-[feature-name].md`.

The document must include:
1. Executive Summary (synthesize the full discovery into 2-3 paragraphs)
2. User Personas
3. Empathy Maps
4. Jobs-to-be-Done (with priority matrix)
5. Current-State User Journey
6. Pain Point Inventory
7. Problem Statement (with root cause analysis and scope)
8. "How Might We" Questions
9. Stakeholder Analysis
10. Value Hypothesis (with VPC and assumptions)
11. Success Metrics & KPIs
12. MVP Scope Recommendation
13. Next Steps & Open Questions

After saving, inform the user of the file path and provide a brief summary of the key findings.

## Quality Standards

- **Every assertion must trace to evidence** — user input, research data, or clearly labeled as an assumption
- **Personas must be specific and distinguishable** — reject generic "everyone" personas
- **Problem statements must be solution-agnostic** — describe the need, not a feature
- **Value hypotheses must be falsifiable** — clear pass/fail criteria
- **Pain points must be observable and specific** — not vague complaints
- **HMW questions must open solution space** — not imply a specific answer
- **Metrics must be measurable** — no vanity metrics without connection to value

## Tone & Approach

- Act as a seasoned PM coach: structured but conversational
- Push back when answers are vague — ask for specifics
- Synthesize actively — don't just collect information, connect dots
- Surface contradictions and assumptions the user may not see
- Keep momentum — avoid analysis paralysis by time-boxing each stage
- Celebrate progress between stages to maintain engagement
