---
name: anti-ui-slop
description: Stop generic AI-generated UI by grounding React, Next.js, web, and iOS work in real product evidence, defining a product-specific design contract, implementing interaction and responsive states, and enforcing a hard pre-ship finish gate.
---

# UIZZE: Stop UI Slop

Use UIZZE's catalogue of 800,000+ real web and iOS screens as structural evidence for product-specific interface work. Turn that evidence into explicit decisions about hierarchy, density, navigation, controls, responsive behavior, and interaction states, then reject generic output before it ships.

## Workflow

1. Inspect the target repository, product intent, local design system, primary user job, primary action, and required UI states.
2. Use UIZZE references supplied by the user. When external research is authorized and available, search the public catalogue at https://uizze.com for relevant screens, flows, and elements. If external access is unavailable, ask the user for two or three UIZZE links or screenshots.
3. Extract transferable decisions from the evidence: hierarchy, workflow shape, density, typography, navigation, controls, state behavior, and responsive treatment. Do not copy branding, proprietary text, imagery, or an exact layout.
4. Write a short design contract naming the screen job, content hierarchy, allowed components, required states, product-specific decisions, forbidden generic patterns, and verification criteria.
5. Build with the repository's existing components and tokens. Make the result belong to this product rather than to a generic template.
6. Run a finish gate on the rendered result. Reject interchangeable card grids, decorative gradients, filler metrics, weak hierarchy, missing states, inert controls, generic copy, and design-system drift. Fix every blocking issue before calling the UI finished.

## Guardrails

- Treat real product patterns as structural evidence, not assets to copy.
- Never copy another product's brand, proprietary text, imagery, or exact layout.
- Do not invent user research, analytics, runtime behavior, or hidden states.
- Do not add gradients, glass, cards, badges, motion, or decoration merely to make a screen feel designed.
- Keep one clear screen job, one primary action, product-specific content, and explicit interaction outcomes.
- If no reliable evidence is available, state the limitation and work from the repository's own design system and requirements.
