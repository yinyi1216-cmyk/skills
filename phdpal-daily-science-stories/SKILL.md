---
name: phdpal-daily-science-stories
description: "Create PhDPal Daily Science Stories from a historical science slice SOP and verifiable sources. Use when users ask for daily science history stories, researcher emotional support style posts, science story rewrites, or explicitly mention PhDPal-Daily-Science-Stories."
---

# PhDPal Daily Science Stories

## Overview
Produce one daily science-history slice story for PhDPal.
Keep the tone light, human, and slightly gossipy while ensuring facts are verifiable and traceable.

## Workflow
1. Collect inputs: date, source links/materials, preferred language, and target platform.
2. Read `references/sop.md` and choose one theme path:
   - Today birthday (person slice)
   - Today discovery (event/process slice)
   - Fallback: this week in history (setback/recovery friction story)
3. Build a fact sheet with date anchor, core event facts, and at least one non-encyclopedic detail.
4. Draft the story as one slice or one process (not full biography timeline).
5. Add an emotional translation layer for common research emotions or structural frictions.
6. End with an emotional landing point (felt understood, pressure relief, or gentle support).
7. Attach 2-4 sources in normalized citation format.

## Output Contract
Return sections in this order:
1. `Story Draft`
2. `Tags`
3. `Key Facts`
4. `Emotional Translation`
5. `Sources`
6. `Image Suggestions` (with image credit hints)
7. `Source Mapping`
8. `Optional Rewrites` (if requested)

## Rules
- Do not invent facts or citations.
- Keep social media and aggregators only as clue entry points.
- Verify key facts with authoritative channels before finalizing.
- Prioritize the source pools in `references/sop.md` sections 6.1 and 6.2, but allow other relevant sources when accuracy and rigor are maintained.
- All output content must be in English, including story text, headings, labels, and source notes, unless the user explicitly requests another language.
- Make `Story Draft` more attractive and slightly richer in detail for a PhD audience, keep it punchy and concise with controlled humor, avoid melodrama, and allow a slightly longer body when needed.
- Add a `Tags` block directly under `Story Draft` with about 8 hashtags. Always include `#Bohrium`, `#BohriumPhDPal`, and `#DailyScienceStory`, then add closely related tags for the specific topic.
- If source evidence is missing, mark as uncertain or remove the claim.
- Separate facts from commentary. Commentary can be casual, facts must be checkable.
- For priority or attribution disputes, present major versions with sources and do not force a verdict.
- Keep tone light and colloquial, but avoid humiliation, moral judgment, and sensationalism.

## Resources
- SOP reference: `references/sop.md`
- Add optional deterministic utilities in `scripts/` when repetitive transformations are identified.
