# Claude PRD Template System

## What This Is

A set of Claude Code commands and templates for creating professional Product Requirement Documents (PRDs) quickly and intelligently.

## Quick Start

1. **Add your project context:**
   - Edit `context/initial.md` with your basic project idea
   - Add any additional context files to `context/` directory

2. **Create your PRD:**
   ```
   /prd_create_base    # Creates initial one-page PRD
   /prd_expand         # Expands to detailed specifications
   ```

## What You Get

### Interactive PRD Creation
- **Context-aware questioning** - Reads your project files to ask smart questions
- **Immediate file updates** - See your PRD building in real-time
- **Item-by-item processing** - Handle user stories, features one at a time
- **Diff previews** - See exactly what changes with each step

### Two-Stage Process
1. **One-Pager PRD** - Quick stakeholder alignment (5 sections)
2. **Detailed PRD** - Comprehensive specifications (9 chapters)

## File Structure

```
.claude/commands/           # Claude Code commands
├── prd_create_base.md      # One-pager creation
└── prd_expand.md          # Detailed expansion

context/                   # Your project information
└── initial.md            # Basic project description
                          # Add more context files here

templates/                 # PRD structures
├── prd_onepager_template.md
├── prd_expansion_template.md
└── questioning_process.md
```

## Commands

### `/prd_create_base`
Creates a focused one-page PRD with:
- Problem & Opportunity
- Success Metrics  
- Target Users & Critical Journeys
- Solution Scope
- Release Plan

### `/prd_expand`
Expands your one-pager into detailed specifications:
- Problem Definition & Strategic Context
- Solution Architecture & Scope
- User Context & Personas  
- Critical User Journeys
- Implementation & Success


## Key Features

### Context Intelligence
- Automatically discovers relevant information from your project files
- Asks only necessary questions by building on existing context
- Suggests solutions based on your project type and constraints

### Progressive Building
- Updates PRD file immediately after each input
- Shows diff of changes for transparency
- Processes complex items (user stories, personas) one at a time
- No overwhelming lists or information dumps

### IDE Integration
- Real-time file updates work seamlessly with Cursor and other IDEs
- Diff previews show exactly what changed
- Progressive document evolution provides immediate feedback

## Getting Started

1. **Describe your project** in `context/initial.md`
2. **Add any existing context** (requirements, research, etc.) to `context/` folder
3. **Run `/prd_create_base`** to start building your PRD
4. **Use `/prd_expand`** when ready for detailed specifications

## Tips

- **Start minimal** - Just describe your basic idea in `initial.md`
- **Add context files** - User research, existing specs, constraints help create better PRDs
- **Build progressively** - Start with one-pager, expand when validated
- **Use for any project** - Templates work for web, mobile, API, enterprise software

---

Ready to create your PRD? Edit `context/initial.md` and run `/prd_create_base`!