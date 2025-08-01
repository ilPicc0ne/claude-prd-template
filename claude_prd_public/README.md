# Claude PRD Template System

Create professional Product Requirement Documents (PRDs) using Claude Code with contextual intelligence and interactive workflows.

## Quick Start

1. **Clone this repository into your project folder:**
   ```bash
   git clone https://github.com/ilPicc0ne/claude-prd-template.git .
   ```

2. **Describe your project:**
   Edit `context/initial.md` with your basic project idea (2-3 sentences)

3. **Create your PRD:**
   ```bash
   # Generate initial one-page PRD
   /create_prd_onepager
   
   # Expand to detailed specifications
   /expand_prd
   ```

## What You Get

### 📋 PRD Templates
- **One-Pager**: Quick stakeholder alignment (5 focused sections)
- **Detailed PRD**: Comprehensive 9-chapter specifications
- **Context-Aware**: Uses your project information for tailored questions

### 🤖 Claude Commands
- `/create_prd_onepager` - Interactive PRD creation with immediate file updates
- `/expand_prd` - Item-by-item expansion from one-pager to detailed specs
- `/test_prd_system` - Validate the complete workflow

### ⚡ Key Features
- **Immediate Updates**: PRD files created/updated after each input
- **Diff Previews**: See exactly what changes with each step
- **Item-by-Item**: Process user stories, features, personas one at a time
- **Context Intelligence**: Smart questions based on your project details

## How It Works

### Stage 1: One-Pager Creation
1. **Context Analysis**: Reads your `initial.md` and project files
2. **Smart Questioning**: Asks only relevant, non-redundant questions
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
│       ├── create_prd_onepager.md    # One-pager creation workflow
│       ├── expand_prd.md             # Detailed expansion process
│       └── test_prd_system.md        # System validation
├── context/
│   └── initial.md                    # Your project description
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
- Any existing project files for additional context

## Support

- **Issues**: Report bugs or feature requests on GitHub
- **Documentation**: See templates folder for detailed structures
- **Testing**: Use `/test_prd_system` to validate setup

## License

Open source - feel free to adapt for your team's needs.

---

🚀 **Ready to create your PRD?** Edit `context/initial.md` and run `/create_prd_onepager` to get started!