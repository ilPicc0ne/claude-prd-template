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

### 5. Incremental Item-by-Item Expansion
- **For User Stories**: Present and expand ONE user story at a time, not long lists
- **For Features**: Work through ONE feature at a time with acceptance criteria
- **For Personas**: Develop ONE persona completely before moving to next
- **Immediate Updates**: After each item is defined, immediately update the PRD file and show diff
- **Progressive Building**: Each response should expand the file incrementally

### 6. Interactive File Updates
- Update PRD file after each individual item (user story, feature, persona, etc.)
- Show exactly what was added/changed with diff preview
- Build document progressively rather than presenting complete sections
- Allow user to see evolution of document in real-time

### 7. Output Strategy
- Always update existing `{productName}_prd.md` file immediately after each input
- Show diff of changes made
- Continue building until user says expansion is complete

Remember: The one-pager is your validated foundation. Build on it, don't change it. Add depth and detail while preserving all original decisions.