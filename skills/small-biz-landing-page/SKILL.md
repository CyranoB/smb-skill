---
name: small-biz-landing-page
description: >-
  Landing page outline generator for small and local businesses. Conducts a
  short interview to learn about the business, then produces a structured
  section-by-section landing page outline. Use when someone wants to create a
  website outline, landing page plan, or homepage structure for their small
  business. Triggers on requests like "create a landing page for my business,"
  "I need a website outline," "help me plan my business website," "landing page
  for my plumbing company," "website outline for my salon," "I need a homepage
  for my car wash," "help me with my small business website," "create a page
  for my babysitting service," "page for my piano teaching business," "website
  for my photography business," "landing page for my tutoring services," or
  "I need a website for my DJ business."
---

# SMB Landing Page Outline

Generate a landing page outline for a small or local business through a short interview.

## Workflow

Read [references/prompts.md](references/prompts.md) before generating any content. It contains the interview questions, output formats, business archetype detection rules, and adaptation guidance.

### Phase 1: Smart Interview

> Reference sections: **Business Archetype Detection** and **Interview Questions** in prompts.md.

Collect the information needed to generate the outline. Two rounds maximum.

**Round 1 — Ask these five questions:**
1. What is your business name?
2. What does your business do?
3. What area do you serve?
4. Who is your ideal customer?
5. What makes you different from your competitors?

Present the questions conversationally, not as a numbered form. If the user volunteers information up front, acknowledge it and skip questions they already answered.

**Detect the archetype** from the answer to question 2. See the archetype table in prompts.md.

**Round 2 — Tailored follow-ups:**
- Ask 3-5 archetype-specific questions from prompts.md (skip any already answered).
- Include the optional questions: pricing preference, testimonials, preferred visitor action.
- If the user gave comprehensive answers in round 1, keep round 2 very short — just the gaps.

### Phase 2: Generate Outline

> Reference sections: **Landing Page Outline Format**, **Business Type Adaptations**, and **Copy Tone Guidelines** in prompts.md.

Once you have enough information:

1. Read the section specifications and adaptation table in prompts.md.
2. Generate the full landing page outline in a single response, in order from Section 1 through Section 11, adapting sections to the business archetype.
3. Skip sections that don't apply (e.g., no "Hours" for a babysitter, no "Pricing" if the owner opted out).
4. Use the owner's actual details — not generic placeholders or lorem ipsum.
5. Follow the copy tone guidelines in prompts.md: friendly, local, plain language.
6. Flag any assumptions clearly so the owner can correct them.

### Iteration

After presenting the outline, ask:

> Would you like to adjust any section, add something, or regenerate the whole outline?

If the user requests changes, regenerate only the affected sections. Carry forward all context. No need to re-interview.

### Entry points

Users may arrive with partial information:
- **"I run a plumbing business in Austin"** — Acknowledge what's given, ask only what's missing.
- **"Here's my business info: [detailed description]"** — Skip the interview entirely if enough info is present. Go straight to generating the outline.
- **Vague request ("I need a website")** — Start from round 1.

### Output format

Present the outline in well-structured markdown using the section template from prompts.md. The output is a **planning document** — a section-by-section outline the owner can hand to a web designer, use in a website builder, or iterate on further.
