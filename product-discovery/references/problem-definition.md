# Problem Definition Reference

## Pain Point Inventory

Categorize and rank all identified pain points:

```markdown
### Pain Point Inventory

| # | Pain Point | Category | Severity (1-5) | Frequency (1-5) | Impact Score | Affected Personas | Evidence Source |
|---|-----------|----------|-----------------|------------------|--------------|-------------------|----------------|
| 1 | | | | | Severity x Freq | | |

**Categories:** Usability | Performance | Process | Cost | Emotional | Integration | Compliance

**Severity scale:**
1 = Minor inconvenience
2 = Noticeable friction, workaround exists
3 = Significant effort to overcome
4 = Major blocker, unreliable workarounds
5 = Complete inability to achieve goal

**Frequency scale:**
1 = Rarely (quarterly or less)
2 = Occasionally (monthly)
3 = Regularly (weekly)
4 = Frequently (daily)
5 = Constantly (multiple times per day)
```

**Pain point quality checklist:**
- Each pain point is specific and observable (not vague)
- Severity and frequency are based on evidence, not assumption
- Root causes are distinguished from symptoms
- Pain points are traceable to personas and journey stages

---

## Problem Statement

Use a structured format that keeps the user at the center:

### Format 1: User-Centered Problem Statement
```markdown
**[Persona]** needs a way to **[user's need/goal]** because **[insight/reason]**.
Currently, **[current state/pain]**, which results in **[negative consequence/impact]**.
```

### Format 2: Gap Statement
```markdown
**Current state:** [What happens today]
**Desired state:** [What should happen]
**Gap:** [The specific gap between current and desired]
**Consequence of inaction:** [What happens if this problem is not solved]
```

### Format 3: Five Whys Root Cause
```markdown
**Observable problem:** [Surface-level issue]
1. Why? → [First cause]
2. Why? → [Deeper cause]
3. Why? → [Deeper cause]
4. Why? → [Deeper cause]
5. Why? → [Root cause]

**Root problem statement:** [Reframed problem based on root cause]
```

**Problem statement quality checklist:**
- User-centered (starts with the person, not the solution)
- Specific enough to guide solution design
- Broad enough to allow creative solutions
- Does NOT imply a specific solution
- Includes measurable consequence
- Validated against user research/data
- Answers: Who has the problem? What is the problem? Why does it matter?

---

## "How Might We" (HMW) Questions

Transform the problem statement into opportunity-framing questions:

```markdown
### HMW Generation Rules

1. Start with the problem statement
2. Reframe as "How might we...?" questions
3. Generate at multiple levels of abstraction:
   - Too narrow: "How might we add a button that does X?" (implies solution)
   - Too broad: "How might we fix the entire industry?" (not actionable)
   - Just right: "How might we reduce the time [persona] spends on [task]?"

### HMW Categories

**Amplify the positive:**
- HMW: [Build on what's already working?]

**Remove the negative:**
- HMW: [Eliminate the core pain point?]

**Explore the opposite:**
- HMW: [Turn the problem into an opportunity?]

**Question an assumption:**
- HMW: [Challenge a constraint everyone accepts?]

**Change the sequence:**
- HMW: [Reorder or parallelize steps?]

**Go after adjacencies:**
- HMW: [Solve a related problem that unlocks this one?]
```

**HMW quality checklist:**
- Neither too broad nor too narrow
- Solution-agnostic (frames the opportunity, not the answer)
- Inspires multiple possible solutions
- Grounded in real user needs
- 5-10 HMW questions per problem statement

---

## Stakeholder Analysis

```markdown
### Stakeholder Map

| Stakeholder | Role | Interest Level (1-5) | Influence Level (1-5) | Stance | Key Concerns | Engagement Strategy |
|-------------|------|---------------------|----------------------|--------|-------------|-------------------|
| | | | | Champion / Supporter / Neutral / Skeptic / Blocker | | |

### Power-Interest Grid

**High Power, High Interest (Manage Closely):**
- [Stakeholder]: [Strategy]

**High Power, Low Interest (Keep Satisfied):**
- [Stakeholder]: [Strategy]

**Low Power, High Interest (Keep Informed):**
- [Stakeholder]: [Strategy]

**Low Power, Low Interest (Monitor):**
- [Stakeholder]: [Strategy]

### Problem Scope & Boundaries

**In scope:**
- [What this problem space includes]

**Out of scope:**
- [What this effort explicitly does NOT address]

**Dependencies:**
- [External factors that affect this problem]

**Constraints:**
- [Technical, regulatory, organizational, budget, timeline constraints]
```
