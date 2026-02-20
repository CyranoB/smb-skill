# SMB Landing Page Skill

A Claude Code skill that helps small business owners create a landing page outline through a short interview.

## What It Does

1. **Interviews you** about your business — name, services, location, customers, differentiators
2. **Detects your business type** and asks targeted follow-up questions
3. **Generates a landing page outline** — section-by-section, with suggested headlines, content, and CTAs

The outline is a planning document you can hand to a web designer, use in a website builder, or iterate on with Claude.

## Supported Business Types

- **Home / Personal Services** — babysitters, house cleaners, dog walkers, nannies, pet sitters, personal organizers
- **Skilled Trades** — plumbers, electricians, HVAC, roofers, handymen, pressure washers
- **Retail / Storefront** — salons, barbershops, bakeries, boutiques, florists
- **Food & Beverage** — restaurants, cafes, food trucks, caterers
- **Professional Services** — accountants, lawyers, consultants, bookkeepers, notaries, translators
- **Fitness / Wellness** — personal trainers, yoga studios, massage therapists, nutritionists
- **Teaching / Lessons** — piano teachers, math tutors, language instructors, driving instructors, dance teachers
- **Creative / Events** — photographers, videographers, DJs, event planners, makeup artists

## Install

### From Claude Code

```
/plugin marketplace add CyranoB/smb-skill
/plugin install smb-landing-page@smb-landing-page-marketplace
```

### Manual install

```bash
git clone https://github.com/CyranoB/smb-skill.git
mkdir -p ~/.claude/skills/smb-landing-page
cp -r smb-skill/skills/smb-landing-page/* ~/.claude/skills/smb-landing-page/
```

## Usage

Ask Claude anything related to creating a small business website:

- "I need a landing page for my plumbing business"
- "Help me create a website outline for my salon"
- "I'm a babysitter and I want a page to advertise my services"
- "Create a homepage for my restaurant in downtown Austin"

## Structure

```
.claude-plugin/
├── plugin.json               # Plugin metadata
└── marketplace.json          # Marketplace manifest
skills/
└── smb-landing-page/
    ├── SKILL.md              # Workflow and interview protocol
    └── references/
        └── prompts.md        # Output formats and business type guidance
```
