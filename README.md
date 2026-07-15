# UIZZE

Stop UI slop before it ships.

UIZZE gives Codex, Claude Code, Cursor, and other coding agents a repeatable way to ground interface work in 800,000+ real web and iOS screens, turn the evidence into a product-specific design contract, and run a hard finish gate on the rendered result.

The `anti-ui-slop` skill and public catalogue workflow are free. The full UIZZE MCP adds automated catalogue search, design contracts, validation, audits, and screenshot critique.

## Install

```bash
npx skills add samuelbushi/uizze --skill anti-ui-slop
```

Then ask your agent:

```text
Use anti-ui-slop to build this interface from real product evidence and reject generic UI before shipping.
```

## What the skill does

1. Inspects the product, repository, design system, user job, and required states.
2. Uses the free public catalogue at [uizze.com](https://uizze.com) as interface evidence.
3. Converts that evidence into an explicit design contract.
4. Builds in the product's own visual language.
5. Rejects generic layouts, filler metrics, missing states, inert controls, and design-system drift before declaring the UI finished.

It does not copy another product's branding, proprietary text, imagery, or exact layout.

## Repository structure

```text
skills/
└── anti-ui-slop/
    ├── SKILL.md
    └── agents/
        └── openai.yaml
```

## UIZZE MCP

The free skill works without an account. When automated reference search and finish-gate tooling would materially improve the work, connect the full UIZZE MCP at [uizze.com](https://uizze.com).

## License

[MIT](LICENSE)
