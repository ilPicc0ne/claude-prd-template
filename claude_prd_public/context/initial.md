# Project Description

**Instructions for Users:** Replace this content with a basic description of your project. Include your product idea, target users, key problems you're solving, and any constraints or requirements you already know. This file will be read by Claude Code commands to create contextual PRDs tailored to your specific project.

## Example Content (Replace with Your Project):

I want to build a template for claude code that will create a solid but simple prd that can be used by claude code as an input to build the product. It can also be used by humans.

approach

Two-stage PRD creation system:

**Stage 1: /create_prd_onepager**
- Creates a single-page PRD for quick stakeholder alignment and MVP planning
- Context-aware questioning that reads existing initial.md and scans context folder
- 5 focused sections: Problem & Opportunity, Success Metrics, Target Users & Critical Journeys, Solution Scope, Release Plan

**Stage 2: /expand_prd** 
- Expands the validated one-pager into comprehensive 9-chapter detailed PRD
- Maintains consistency with one-pager decisions while adding depth
- Supports detailed development planning and technical specifications

**Context-Aware Questioning Process:**
- Pre-analysis: Reads initial.md (if exists) and scans context folder for relevant information
- Tailored questions: Avoids redundancy by building on existing context
- Smart proposals: Claude generates better suggestions based on project context
- Three options per question: 1. (user provides context), 2. (Claude makes contextual proposition), 3. (leave open for later)
- Validation: Checks for contradictions with existing project information before presenting final PRD

requirements

1. Template scope: Generic template supporting any software product type
   - Different platforms (web, mobile, desktop, API, etc.) will be specified within the PRD sections
   - Template should be flexible enough to accommodate various product categories

2. Technical detail level: High-level business requirements with non-functional requirements
   - Focus on business requirements and user needs (stakeholder-focused)
   - Include non-functional requirements (performance, cost, scalability, security, etc.)
   - Concrete technical decisions and architecture to be addressed in subsequent technical design phase

3. User personas and stakeholders: Predefined persona templates with examples
   - Provide persona examples (e.g., ride-sharing app: rider, driver, admin, customer support agent, fleet manager)
   - Include service roles (e.g., service technician: field worker with mobile access, diagnostic tools, work order management)
   - Allow flexible customization based on product domain

4. User stories and feature requirements: Traditional user stories format
   - Use "As a [persona], I want [goal], so that [benefit]" structure
   - Include acceptance criteria for each user story
   - Organize stories by feature areas or user journeys

5. Prioritization and roadmap planning: Release phases approach
   - Categorize features into MVP, Phase 2, Future releases
   - Clear definition of what constitutes each phase
   - Focus on value delivery and user impact for phase sequencing

6. Validation and success metrics: North star KPI with feature-level sub-KPIs
   - Define one primary north star KPI (overall product success measure)
   - Critical features must have measurable sub-KPIs tied to the north star
   - Include technical metrics only when critical for product viability (e.g., storage per user in photo app) or user experience (uptime, speed)
   - Focus on business impact and user value measurement

template structures

**One-Pager Template (Stage 1):**

1. **Problem & Opportunity** (2-3 sentences)
   - User pain points with concrete examples
   - Business impact and strategic context
   - Why this matters now

2. **Success Metrics**
   - North Star KPI: Single primary success measure
   - Key Sub-Metrics: 2-3 feature-level KPIs that drive the north star
   - Leading indicators of success/failure

3. **Target Users & Critical Journeys**
   - Primary Personas: Key user types with examples (rider/driver/admin, service technician, etc.)
   - Core User Journey: End-to-end flow for main use case
   - Critical Success Path: What must work perfectly for user value

4. **Solution Scope**
   - MVP Features: User stories in "As a [persona], I want [goal], so that [benefit]" format
   - Key Non-Functional Requirements: Performance, cost, security constraints that matter
   - Explicit Non-Goals: What we're NOT doing and why

5. **Release Plan**
   - MVP: Core features for initial release with success criteria
   - Phase 2: Enhancement features based on MVP learnings
   - Dependencies: Critical factors that could impact timeline

**Expansion Template (Stage 2):**

1. **Problem Definition & Strategic Context** (expanded from one-pager)
2. **User Context & Personas** (detailed personas and stakeholder analysis)
3. **Critical User Journeys** (comprehensive end-to-end flows and edge cases)
4. **Solution Boundaries & Scope** (detailed feature specifications)
5. **Non-Functional Requirements** (comprehensive technical constraints)
6. **User Stories & Acceptance Criteria** (detailed stories organized by journey)
7. **Success Metrics & Measurement** (expanded KPI framework)
8. **Technical Architecture Guidance** (high-level system design)
9. **Release Planning & Roadmap** (detailed timeline and dependencies)
