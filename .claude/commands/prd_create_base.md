---
description: Create PRD One-Pager
allowed-tools: Read, Write, Edit, LS, Grep, Glob
---

# Create PRD One-Pager

Creates a single-page Product Requirements Document for quick stakeholder alignment and MVP planning using context-aware iterative questioning.

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

**1. Problem & Opportunity** (2-3 sentences)
- What user problem are we solving?
- Why does this matter to business/users now?
- Based on context, propose specific problem if available

**2. Success Metrics** 
- North Star KPI: Single primary success measure
- 2-3 Key Sub-Metrics that drive the north star
- Use context to suggest relevant metrics for product type

**3. Target Users & Critical Journeys**
- Primary Personas with needs and frustrations
- Core User Journey: end-to-end flow for main use case
- Critical Success Path: what must work perfectly

**4. Solution Scope**
- MVP Features using "As a [persona], I want [goal], so that [benefit]" format
- Key Non-Functional Requirements (performance, cost, security)
- Explicit Non-Goals: what we're NOT doing

**5. Release Plan**
- MVP: core features with success criteria
- Phase 2: enhancement features
- Critical Dependencies

### 4. Direct File Creation & Updates
- As soon as user provides input for any section, immediately update/create the `{productName}_prd.md` file
- Show diff of changes made (what was added/modified)
- Continue iteratively building the document section by section
- Each input should result in immediate file modification with visible changes

Remember: Build on existing context, avoid redundant questions, and ensure all sections support each other logically.