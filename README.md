# Claude PRD Template System

Create professional Product Requirement Documents (PRDs) using Claude Code with contextual intelligence and interactive workflows.

> **📁 For Your Projects**: When you clone this template into your project, you'll get a clean setup with minimal documentation focused on your work. This README serves as the comprehensive guide for understanding and using the template system.

## Quick Start

1. **Clone this repository into your project folder:**
   ```bash
   git clone https://github.com/ilPicc0ne/claude-prd-template.git .
   ```

2. **Add your project context:**
   - Edit `context/initial.md` with your basic project idea (2-3 sentences)
   - Add any additional context files to the `context/` directory (user research, requirements, existing specs, etc.)

3. **Create your PRD:**
   ```bash
   # Generate initial one-page PRD
   /prd_create_base
   
   # Expand to detailed specifications
   /prd_expand
   ```

## What You Get

### 📋 PRD Templates
- **One-Pager**: Quick stakeholder alignment (5 focused sections)
- **Detailed PRD**: Comprehensive 5-chapter specifications
- **Context-Aware**: Uses your project information for tailored questions

### ⚠️ What's NOT Included: Business Requirements Brief (BRB)

This system focuses on **Product** Requirements Documents, not Business Requirements. A **Business Requirements Brief (BRB)** may be needed as an earlier step for strategic planning:

**BRB typically contains:**
- Market analysis and opportunity sizing
- Business case and ROI projections
- Strategic objectives and success criteria
- Competitive landscape analysis
- Go-to-market strategy
- Resource and budget requirements

**When you need a BRB first:**
- New product category or market entry
- Significant strategic initiatives
- Products requiring executive/board approval
- Complex business model validation

**Our PRD system assumes** you've already validated the business opportunity and focuses on **what to build** and **how users will interact** with the solution.

### 🤖 Claude Commands
- `/prd_create_base` - Interactive PRD creation with immediate file updates
- `/prd_expand` - Item-by-item expansion from one-pager to detailed specs

### ⚡ Key Features
- **Immediate Updates**: PRD files created/updated after each input
- **Diff Previews**: See exactly what changes with each step
- **Item-by-Item**: Process user stories, features, personas one at a time
- **Context Intelligence**: Smart questions based on your project details

## How It Works

### Stage 1: One-Pager Creation
1. **Context Analysis**: Reads your `initial.md` and scans `context/` folder for additional files
2. **Smart Questioning**: Asks only relevant, non-redundant questions based on existing context
3. **Immediate Building**: Updates PRD file with each input
4. **5 Core Sections**: Problem, Metrics, Users, Scope, Release Plan

### Stage 2: Detailed Expansion
1. **Foundation Preservation**: Builds on validated one-pager decisions
2. **Progressive Development**: Expands one item at a time
3. **Real-Time Evolution**: Watch your document grow incrementally
4. **9 Comprehensive Chapters**: Complete development specifications

## File Structure

```
├── .claude/
│   └── commands/
│       ├── prd_create_base.md        # One-pager creation workflow
│       └── prd_expand.md             # Detailed expansion process
├── context/
│   └── initial.md                    # Your project description
│   └── [additional context files]    # User research, specs, requirements, etc.
├── templates/
│   ├── prd_onepager_template.md      # One-pager structure
│   ├── prd_expansion_template.md     # Detailed PRD structure
│   └── questioning_process.md        # Systematic requirements gathering
└── README.md                         # This file
```

## Output Examples

### One-Pager PRD Sections:
1. **Problem & Opportunity** - User pain points and business context
2. **Success Metrics** - North Star KPI + key sub-metrics
3. **Target Users & Critical Journeys** - Personas and core workflows
4. **Solution Scope** - MVP features and non-functional requirements
5. **Release Plan** - MVP, Phase 2, and dependencies

### Detailed PRD Chapters:
1. Problem Definition & Strategic Context
2. User Context & Personas
3. Critical User Journeys
4. Solution Boundaries & Scope
5. Non-Functional Requirements
6. User Stories & Acceptance Criteria
7. Success Metrics & Measurement
8. Technical Architecture Guidance
9. Release Planning & Roadmap

## Benefits

### For Product Teams
- **Faster PRD Creation**: Hours reduced to minutes
- **Consistent Quality**: Structured templates ensure completeness
- **Stakeholder Alignment**: Clear, focused documentation
- **Iterative Refinement**: Easy updates and expansions

### for Development Teams
- **AI-Ready Context**: PRDs optimized for Claude Code development
- **Clear Specifications**: Detailed acceptance criteria and technical guidance
- **Measurable Success**: Defined metrics for feature validation
- **Progressive Disclosure**: Start simple, add detail as needed

### for IDE Integration
- **Real-Time Feedback**: See changes as they happen
- **Diff Previews**: Transparent update process
- **Item-by-Item Flow**: Manageable, non-overwhelming interface
- **Context Awareness**: Smart suggestions based on existing project files

## Requirements

- Claude Code CLI installed
- Basic project description in `context/initial.md`
- (Optional) Additional context files in `context/` directory:
  - User research and interviews
  - Existing requirements or specifications
  - Technical constraints or architecture docs
  - Business goals and success criteria
  - Competitive analysis or market research

## After Cloning

Once you clone this template into your project:

1. **Your CLAUDE.md will be minimal** - focused on your project, not template documentation
2. **Edit `context/initial.md`** with your project description  
3. **Add relevant context files** to the `context/` directory
4. **Run `/prd_create_base`** to start creating your PRD

The cloned version keeps your project clean while giving you access to all the PRD creation capabilities.

## Support

- **Template Documentation**: This README (bookmark this page!)
- **Issues**: Report bugs or feature requests on GitHub
- **Templates**: See templates folder for detailed structures

## License

Open source - feel free to adapt for your team's needs.

---

🚀 **Ready to create your PRD?** Clone this template and run `/prd_create_base` to get started!