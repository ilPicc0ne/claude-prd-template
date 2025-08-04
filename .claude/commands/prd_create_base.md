---
description: Create PRD One-Pager
allowed-tools: Read, Write, Edit, LS, Grep, Glob
---

# Create PRD One-Pager

Creates a single-page Product Requirements Document for quick stakeholder alignment and go/no-go decisions using context-aware iterative questioning. Focus on speed (5-10 minutes) and breadth over depth.

## Instructions

You are helping create a PRD one-pager. Follow this process:

### 1. Initial Setup
First ask: "What's your product/project name?"
Use response to create filename: `{productName}_prd.md`

### 2. Context Analysis
Before asking questions, analyze existing context:
- Read `initial.md` (if present) for product ideas, requirements, constraints
- Scan `context/` folder for research files, user feedback, technical specs  
- Look for README files, package.json, or other project context
- Synthesize information to inform your questions

### 3. Section-by-Section Questioning
For each section, provide 3 options:
1. **User provides context** - Let user give detailed input
2. **Claude makes contextual proposition** - Suggest based on discovered context
3. **Skip for now** - Mark as [TBD] and continue

#### Required Sections (in order):

**1. Problem & Opportunity** (1-2 sentences each)
- Core user pain point (single clear sentence)
- Business driver (why this matters now)
- Based on context, propose specific problem if available

**2. Solution Concept** (2-3 sentences total)
- What are we building? (elevator pitch level)
- Key value proposition (how this solves the problem)
- High-level scope boundaries (what's IN vs OUT of scope)

**3. Target Users & Success Metrics** (bullets only)
- 1-2 primary personas (name + core need)
- North Star KPI (single primary success measure)
- 2 key sub-metrics that drive the north star

**4. Critical User Journey** (happy path only)
- 3-5 step main user flow
- Critical success moment (where user gets value)
- Key touchpoints with the system

**5. MVP Scope** (high-level capabilities)
- 3-5 core capabilities (not detailed user stories)
- Key constraints (platform, timeline, budget)
- Explicit non-goals (2-3 items we're NOT doing)

### 4. Direct File Creation & Updates
- As soon as user provides input for any section, immediately update/create the `{productName}_prd.md` file
- Show diff of changes made (what was added/modified)
- Continue iteratively building the document section by section
- Each input should result in immediate file modification with visible changes

Remember: Keep responses concise for speed. Build on existing context, avoid redundant questions. Focus on breadth over depth - detailed specifications come in the expand phase.