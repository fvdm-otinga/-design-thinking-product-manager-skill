# Product Discovery Skill

A Claude Code skill that guides product managers through the **Design Thinking Empathy & Problem Definition** phases plus **Value Hypothesis** formulation — the initial stages of the product capability and feature definition pipeline.

## What It Does

This skill facilitates structured product discovery by walking you through five stages:

1. **Context Gathering** — Interactive interview or context dump with targeted follow-ups
2. **Empathy Synthesis** — User personas, empathy maps, jobs-to-be-done, user journey mapping
3. **Problem Definition** — Pain point inventory, problem statements, "How Might We" questions, stakeholder analysis
4. **Value Hypothesis** — If/Then/Because hypotheses, riskiest assumptions, value proposition canvas, success metrics
5. **Document Assembly** — Compiles everything into a comprehensive 13-section discovery document

### Two Entry Modes

- **Interactive Interview** — Guided questions in focused batches to build the full picture from scratch
- **Context Dump** — Provide existing research, meeting notes, or feedback; the skill synthesizes and asks targeted follow-ups

### Output

A comprehensive markdown document covering:

| Section | Contents |
|---------|----------|
| Executive Summary | Synthesized overview of the discovery |
| User Personas | 1-3 detailed personas with behaviors, goals, frustrations |
| Empathy Maps | Think/Feel/Say/Do quadrants per persona |
| Jobs-to-be-Done | Functional, emotional, social jobs with priority matrix |
| User Journey | Current-state journey with pain points and opportunities |
| Pain Point Inventory | Categorized, severity-ranked with impact scores |
| Problem Statement | User-centered with root cause analysis and scope |
| "How Might We" Questions | 5-10 opportunity-framing questions |
| Stakeholder Analysis | Power-interest grid with engagement strategies |
| Value Hypothesis | If/Then/Because with VPC and riskiest assumptions |
| Success Metrics | North star, leading/lagging indicators, counter-metrics |
| MVP Scope | Minimum viable test recommendation |
| Next Steps | Action items and open questions |

## Installation

Copy the skill folder to your Claude Code skills directory:

```bash
cp -r product-discovery ~/.claude/skills/
```

Or install from the packaged `.skill` file:

```bash
# The .skill file is a zip archive — extract it to your skills directory
unzip product-discovery.skill -d ~/.claude/skills/
```

## Usage

Once installed, trigger the skill by saying things like:

- "Let's do product discovery for [feature]"
- "Help me define the problem space for [capability]"
- "I need to build a value hypothesis for [idea]"
- "Run me through empathy mapping for [user segment]"
- "I have some user research — help me synthesize it into a discovery doc"

Or invoke directly with `/product-discovery`.

## Skill Structure

```
product-discovery/
├── SKILL.md                                  # Main workflow (5 stages)
└── references/
    ├── empathy-frameworks.md                 # Persona, empathy map, JTBD, journey templates
    ├── problem-definition.md                 # Pain points, problem statement, HMW, stakeholders
    ├── value-hypothesis.md                   # Hypothesis, assumptions, VPC, metrics, MVP
    └── output-template.md                    # Complete 13-section deliverable template
```

## License

MIT
