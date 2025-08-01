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

### Phase 3: System Validation
**Test and report on:**
- ✅ Context discovery effectiveness
- ✅ Question relevance and contextual intelligence
- ✅ Template structure completeness
- ✅ Cross-section consistency checking
- ✅ One-pager to expansion workflow
- ✅ AI development context generation

### Success Criteria
Demonstrate that the system:
- Properly discovers and uses existing project context
- Asks intelligent, non-redundant questions
- Creates actionable PRDs for both human and AI use
- Maintains consistency between one-pager and expanded versions
- Generates useful development context for Claude Code

**Output:** Working demonstration of the complete PRD creation workflow using this project's own context as test data.