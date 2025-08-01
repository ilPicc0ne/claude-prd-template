---
description: Expand PRD to detailed version
allowed-tools: Read, Write, Edit, LS, Grep, Glob
---

# Expand PRD

Expands an existing one-pager PRD into a comprehensive 9-chapter detailed PRD for development planning.

## Instructions

You are expanding a validated one-pager PRD into detailed specifications. Follow this process:

### 1. Prerequisites Check
- Verify existing `{productName}_prd.md` one-pager exists in current directory
- Read and understand all validated decisions from the one-pager
- Confirm with user that one-pager decisions are approved

### 2. Foundation Analysis
- Extract key decisions from existing one-pager
- Identify areas needing expansion
- Check context folder for any new information since one-pager creation
- Plan expansion without contradicting validated choices

### 3. Expansion Process
Transform the 5 one-pager sections into 9 comprehensive chapters:

**Expand into:**
1. **Problem Definition & Strategic Context** (from Problem & Opportunity)
2. **User Context & Personas** (from Target Users)  
3. **Critical User Journeys** (from Critical Journeys)
4. **Solution Boundaries & Scope** (from Solution Scope)
5. **Non-Functional Requirements** (from Key Non-Functional Requirements)
6. **User Stories & Acceptance Criteria** (from MVP Features)
7. **Success Metrics & Measurement** (from Success Metrics)
8. **Technical Architecture Guidance** (new section)
9. **Release Planning & Roadmap** (from Release Plan)

### 4. Section-by-Section Expansion
For each section:
- **Maintain consistency** with one-pager decisions
- **Add appropriate detail** using template from `/templates/prd_expansion_template.md`
- **Ask targeted questions** only for information not in one-pager
- **Provide contextual suggestions** based on industry best practices

### 5. Progressive Questioning
- Build on validated content, don't re-question basics
- Focus on details needed for development
- Offer to skip sections if not needed yet
- Maintain 3-option approach: user input, Claude suggestion, skip

### 6. Final Integration
- Create comprehensive PRD maintaining logical flow
- Ensure all 9 chapters support original success metrics
- Generate AI development context for Claude Code
- Validate technical feasibility against constraints

### 7. Output Options
Ask user preference:
- Replace existing `{productName}_prd.md` with expanded version
- Create `{productName}_prd_detailed.md` to keep both versions

Remember: The one-pager is your validated foundation. Build on it, don't change it. Add depth and detail while preserving all original decisions.