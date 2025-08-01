---
description: Test PRD System with this project
allowed-tools: Read, Write, Edit, LS, Grep, Glob
---

# Test PRD System

Test the complete PRD creation system using this project as a sample case.

## Instructions

You are testing the PRD system using this project itself as the test case. Follow this process:

### Test Setup
**Product Name:** "PRD Template System for Claude Code"
**Test Context:** Use this project's existing files as context:
- `initial.md` - Requirements and approach documentation  
- `context/research_prd.md` - Modern PRD best practices research
- `templates/` folder - Actual template implementations

### Phase 1: Test One-Pager Creation
1. **Simulate `/create_prd_onepager` process:**
   - Skip asking for product name (use "PRD Template System for Claude Code")
   - Analyze existing context in initial.md and context folder
   - Walk through each of the 5 sections demonstrating how you would:
     - Discover relevant context
     - Ask contextual questions
     - Provide intelligent propositions based on existing information

2. **Create test one-pager PRD:**
   - Use template structure from `/templates/prd_onepager_template.md`
   - Populate with information from this project's context
   - Name file: `PRD_Template_System_prd.md`

### Phase 2: Test Expansion Process
1. **Simulate `/expand_prd` process:**
   - Use the created one-pager as foundation
   - Demonstrate how expansion maintains consistency
   - Show how 5 sections become 9 chapters
   - Highlight what additional questions would be asked

2. **Create expanded version outline:**
   - Don't create full expanded PRD (too long for test)
   - Show structure and key expansions for first 3 chapters
   - Demonstrate consistency with one-pager foundation

### Phase 3: Interactive Testing Validation
**Test item-by-item processing:**
- Test ONE user story creation and immediate file update with diff
- Test ONE persona development and immediate file update with diff  
- Test ONE feature expansion and immediate file update with diff
- Validate that each item is processed individually, not in batches
- Confirm diff preview shows exactly what changed after each input

**System Integration Testing:**
- ✅ Immediate file creation/updates after each input
- ✅ Diff preview functionality for transparency
- ✅ Item-by-item progression instead of long lists
- ✅ Context discovery effectiveness
- ✅ Template structure completeness

### Success Criteria
Demonstrate that the system:
- Updates PRD file immediately after each individual input
- Shows clear diff of what was added/changed
- Processes items one-by-one rather than presenting long lists
- Maintains real-time document evolution for user visibility
- Creates actionable PRDs for both human and AI use

**Output:** Working demonstration of the complete PRD creation workflow using this project's own context as test data.