# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Is

A Claude Code skill plugin (`small-biz-landing-page`) that generates landing page outlines for small/local businesses. No build system, no runtime code — the project is entirely markdown-based skill definitions and plugin config.

## Project Structure

- `skills/small-biz-landing-page/SKILL.md` — Skill entry point. Defines the two-phase workflow (interview → outline) and YAML frontmatter for skill triggering.
- `skills/small-biz-landing-page/references/prompts.md` — The core reference file. Contains archetype detection, interview questions, all 11 landing page section specs, adaptation tables, and tone guidelines. SKILL.md references this file; they must stay in sync.
- `.claude-plugin/plugin.json` + `marketplace.json` — Plugin metadata for Claude Code discovery. The `name` field in plugin.json must match the skill directory name (`small-biz-landing-page`).

## Key Conventions

**Naming consistency:** The plugin name `small-biz-landing-page` appears in plugin.json, marketplace.json, and as the skill directory name. These must all match.

**Eight business archetypes** drive the adaptive behavior: Home/Personal Services, Skilled Trades, Retail/Storefront, Food & Beverage, Professional Services, Fitness/Wellness, Teaching/Lessons, Creative/Events. When adding new section logic or interview questions, update both the archetype-specific sections in prompts.md AND the adaptation table at the bottom of that file.

**Sections 7 (Hours) and 8 (Pricing) are conditional** — they get skipped or replaced depending on the archetype. Any new conditional section needs an entry in the Business Type Adaptations table.

## Making Changes

When editing prompts.md section specifications, check the adaptation table stays consistent. When editing SKILL.md workflow phases, verify the interview question references in prompts.md still match. The two files are tightly coupled.
