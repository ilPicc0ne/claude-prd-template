# PRD Template System for Claude Code

## Project Overview

This project provides a comprehensive template system for creating Product Requirement Documents (PRDs) using Claude Code. It enables rapid creation of professional PRDs that serve both human stakeholders and AI development workflows.

## Repository Structure

### Main Repository (prd_claude)
- **Development repo**: Contains all project files for expansion and maintenance
- **Location**: https://github.com/ilPicc0ne/prd_claude
- **Purpose**: Project development, research, and template evolution

### Public Distribution (claude_prd_public)
- **User-facing repo**: Contains only the reusable components
- **Location**: https://github.com/ilPicc0ne/claude-prd-template  
- **Purpose**: Clone into any project to get PRD creation capabilities

## Core Components

### Claude Commands (.claude/commands/)
1. **create_prd_onepager.md** - Creates initial one-page PRD with contextual questioning
2. **expand_prd.md** - Expands one-pager into detailed 9-chapter PRD
3. **test_prd_system.md** - Tests the complete workflow using this project as example

### Templates (templates/)
1. **prd_onepager_template.md** - Structure for concise stakeholder alignment
2. **prd_expansion_template.md** - Framework for detailed development specs  
3. **questioning_process.md** - Systematic approach for gathering requirements

### Context Files (context/)
- **initial.md** - Project requirements and approach documentation
- Supporting research and reference materials

## Key Features

### Interactive File Updates
- **Immediate Creation**: PRD files created/updated immediately after each input
- **Diff Preview**: Shows exactly what was added/changed for transparency
- **Real-time Evolution**: Users see document building progressively

### Item-by-Item Processing
- **User Stories**: Developed one at a time, not in overwhelming lists
- **Features**: Individual processing with acceptance criteria
- **Personas**: Complete development before moving to next
- **Progressive Building**: Each response expands the file incrementally

### Context-Aware Intelligence
- **Auto-Discovery**: Scans existing project files for relevant context
- **Smart Questions**: Avoids redundant questioning by using discovered information
- **Contextual Suggestions**: Proposes solutions based on project type and existing data

## Usage Workflow

### For New Projects
1. Clone the public template: `git clone https://github.com/ilPicc0ne/claude-prd-template`
2. Run `/create_prd_onepager` to build initial PRD
3. Use `/expand_prd` to create detailed specifications
4. Use `/test_prd_system` to validate the workflow

### For Existing Projects
1. Copy the `.claude/commands/` and `templates/` folders to your project
2. Add any existing project context to `context/` folder
3. Follow the workflow above

## Development Approach

### Template Philosophy
- **Human + AI Optimized**: PRDs serve both stakeholder communication and AI development
- **Context-Driven**: Leverage existing project information to minimize questioning
- **Progressive Disclosure**: Build documents incrementally rather than overwhelming users
- **Consistency Validation**: Ensure all sections support each other logically

### Quality Standards
- **Immediate Feedback**: Show changes as they happen for transparency
- **Incremental Progress**: Process one item at a time for better UX
- **Context Intelligence**: Use available information to ask smarter questions  
- **Template Consistency**: Maintain structured approach across all PRDs

## Integration Benefits

### Cursor/IDE Integration
- Real-time diff previews show exactly what changed
- Progressive file building provides immediate visual feedback
- Item-by-item processing prevents overwhelming interfaces
- Context discovery reduces manual input requirements

### Claude Code Workflows  
- PRDs serve as comprehensive context for development tasks
- Structured templates ensure consistent AI interpretation
- Technical sections provide clear development guidance
- Success metrics enable measurable development outcomes

## Testing & Validation

Use `/test_prd_system` to validate:
- Context discovery effectiveness
- Item-by-item processing functionality  
- Immediate file update capabilities
- Diff preview accuracy
- Template structure completeness
- Cross-section consistency

## Contributing

To expand this system:
1. Work in the main development repo
2. Test changes using `/test_prd_system`
3. Update the public distribution repo when ready
4. Maintain separation between development and distribution content

## Success Metrics

The system succeeds when it:
- Reduces PRD creation time from hours to minutes
- Generates PRDs usable by both humans and AI systems
- Maintains consistency across document sections
- Provides transparent, real-time feedback during creation
- Adapts intelligently to existing project context