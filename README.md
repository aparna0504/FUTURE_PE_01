# FUTURE_PE_01 — AI Website Copy Generator for Local Businesses

**Track:** Prompt Engineering (PE) · **Task:** 1 · **Tool used:** Claude (Anthropic)

## Objective
Build a reusable, structured prompt system that produces website-ready copy (Homepage + Services + CTAs) for local businesses, and adapt its tone across business types.

## Client Brief (sample client)
- **Business:** Maple & Main Café (fictional placeholder client)
- **Location:** Portland, Oregon
- **Offer:** Specialty coffee, fresh-baked pastries, office catering, private event space
- **Audience:** Neighborhood locals, remote workers, office managers
- **Brand voice:** Warm, unpretentious, community-first
- **Goal:** More walk-ins, catering enquiries, and event bookings

## Prompt Logic
Every prompt uses the same 6-part framework (R-C-T-F-C-V):

| Part | Purpose |
|---|---|
| **R**ole | Sets expertise (conversion copywriter for local businesses) |
| **C**ontext | Business facts, audience, location, goal |
| **T**ask | Exactly one deliverable per prompt |
| **F**ormat | Section headings, word limits, website-ready structure |
| **C**onstraints | Plain language, no clichés, no invented facts, benefit-first |
| **V**oice | Tone descriptors + words to use/avoid |

**Workflow:** Brief → Master prompt → Homepage → Services → CTAs → Tone adaptation → Human edit (fact-check, trim, read aloud).

## Files
- `prompts.md` — all prompts used (reusable template included)
- `outputs/homepage.md` — homepage copy
- `outputs/services.md` — service page descriptions
- `outputs/cta_sections.md` — contact / booking / enquiry CTAs
- `outputs/tone_variants.md` — same framework adapted for salon, clinic, agency

## Learnings
- Specific context (neighborhood, audience, goal) beats long generic instructions.
- Asking for one deliverable per prompt gives cleaner, more editable output.
- Banning clichés ("we pride ourselves…") in constraints noticeably improves copy quality.
- AI output still needs human fact-checking (hours, prices, claims) before going live.

*Content was AI-generated with structured prompts and then human-reviewed. Business details are placeholders.*
