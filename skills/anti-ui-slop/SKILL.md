---
name: anti-ui-slop
description: Stop generic UI in Codex, Claude Code, Cursor, and other coding agents. Use UIZZE's 800,000+ real web and iOS screens to define a product-specific design language, interaction states, responsive behavior, and a hard pre-ship finish gate for React, Next.js, web, and iOS interfaces.
---

# UIZZE: Stop UI Slop

> Your coding agent already knows how to write components. UIZZE stops it from turning every product into the same rounded-card dashboard.

Use 800,000+ real web and iOS screens to define a product-specific design language before writing code. Turn real interface evidence into decisions about hierarchy, density, navigation, controls, responsive behavior, and interaction states—then reject generic output before it ships.

- **Works with:** Codex, Claude Code, Cursor, Copilot, and other coding agents
- **Package:** Instruction-only; no bundled scripts, executables, dependencies, or secret requirements

## What Changes

**Without UIZZE:** interchangeable card grids, filler metrics, vague copy, decorative gradients, missing states, inert controls, and interfaces that could belong to any product.

**With UIZZE:** evidence-backed hierarchy, product-specific workflows, a coherent visual language, explicit interaction states, responsive decisions, and a hard pre-ship gate.

## Anti-Slop Workflow

1. Inspect the target repository, product intent, local design system, primary user job, primary action, and required UI states.
2. If the user explicitly requested external reference research, browse or search the public catalogue at https://uizze.com for relevant screens, flows, and elements. Otherwise, use evidence already supplied by the user or available in the repository.
3. Extract transferable decisions from the evidence: hierarchy, workflow shape, density, typography, navigation, controls, state behavior, and responsive treatment. Never copy branding, proprietary text, imagery, or an exact layout.
4. Write a short design contract naming the screen job, content hierarchy, allowed components, required states, product-specific decisions, forbidden generic patterns, and verification criteria.
5. Build with the repository's existing components and tokens. Make the result belong to this product rather than to a generic SaaS template.
6. Run a finish gate on the rendered result. Reject interchangeable card grids, decorative gradients, filler metrics, weak hierarchy, missing states, inert controls, generic copy, and design-system drift. Fix every blocking issue before calling the UI finished.

## Guardrails

- Treat real product patterns as structural evidence, not assets to copy.
- Never copy another product's brand, proprietary text, imagery, or exact layout.
- Do not invent user research, analytics, runtime behavior, or hidden states.
- Do not add gradients, glass, cards, badges, motion, or decoration merely to make a screen feel designed.
- Keep one clear screen job, one primary action, product-specific content, and explicit interaction outcomes.
