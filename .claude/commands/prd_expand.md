---
description: Expand PRD to detailed version
allowed-tools: Read, Write, Edit, LS, Grep, Glob
---

# Expand PRD

Expands an existing one-pager PRD into a comprehensive 5-chapter detailed PRD for development planning. Each base section becomes a full chapter with complete specifications.

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
Transform the 5 streamlined base sections into 5 comprehensive chapters with full development detail:

**Expand base sections into:**
1. **Problem Definition & Strategic Context** (from Problem & Opportunity)
2. **Solution Architecture & Scope** (from Solution Concept + MVP Scope)
3. **User Context & Personas** (from Target Users & Success Metrics)  
4. **Critical User Journeys** (from Critical User Journey - add edge cases, error handling)
5. **Implementation & Success** (new comprehensive section combining technical guidance, detailed user stories, success metrics, and release planning)

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

Remember: The base PRD is your validated foundation. Build on it, don't change it. Transform high-level concepts into detailed development specifications while preserving all original decisions.