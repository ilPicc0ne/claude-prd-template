# PRD Creation System

This project uses the Claude PRD Template System for structured product requirements.

## Quick Start

1. **Edit `context/initial.md`** with your project description
2. **Run `/prd_create_base`** to create your initial PRD
3. **Use `/prd_expand`** for detailed specifications

## Commands Available

- **`/prd_create_base`** - Create focused one-page PRD (5-10 minutes)
- **`/prd_expand`** - Expand to comprehensive specifications

## How It Works

The system uses context-aware questioning to build PRDs tailored to your specific project:
- Reads your project files to ask smart questions
- Updates PRD files immediately with each input
- Shows diff previews of changes
- Processes items one-by-one (no overwhelming lists)

## Need Help?

For detailed documentation, examples, and guidance, see the [template documentation](https://github.com/ilPicc0ne/claude-prd-template).

---

**Ready to start?** Edit `context/initial.md` with your project idea and run `/prd_create_base`!