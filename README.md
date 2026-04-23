# Continuous Advancement — Marketing Site

A single-page marketing site for [Continuous Advancement](https://continuousadvancement.com), the operating system for mission-driven executive directors.

## What this is

This is the external-facing pitch: what the product does, who it's for, how it's different, and how to request early access. It represents the mature (roughly 5-year) version of the product, not the v0.1 slice being built first. It exists to validate the vision — to prove the direction is worth having before we ship every slice.

## View it

Just open `index.html` in a browser. No build step. Tailwind-free, pure HTML/CSS with Google Fonts (Instrument Sans, Instrument Serif, JetBrains Mono). Designed to match The Nest's design system so it reads as the same product family.

## Structure

- **Hero** — the pitch in one sentence
- **The shape of the job** — the 5-axis role EDs actually play
- **Three surfaces** — Inbox, Pulse, Threads
- **Scenes** — three vignettes from a week
- **Why this** — vs Salesforce, Bloomerang, coordination tools, a chief of staff, and a chat assistant
- **Under the hood** — the vertical object model
- **Who it's for** — ED profile
- **Pricing** — the three tiers, in context
- **FAQ** — the things EDs ask first
- **CTA** — request access

## Editing

All styles are inline in `<style>` in `index.html`. Design tokens live in `:root` — warm paper palette lifted from The Nest. Typography is Instrument Serif (display), Instrument Sans (body), JetBrains Mono (labels).

Edit copy directly. For a significant redesign, consider porting to Next.js + Tailwind when we build the product shell.

## License

© 2026 Continuous Advancement LLC. All rights reserved.
