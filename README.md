# JCODE Design System

The official design system for **JCODE** — an AI coding agent for your terminal. This repository contains the visual language, component specifications, and design files that define the JCODE brand and product interface.

## What's Inside

| File | Description |
|------|-------------|
| [`design.md`](design.md) | Complete design system specification — colors, typography, components, layout, and usage guidelines |
| [`landing-page.pen`](landing-page.pen) | Landing page and documentation page design files (Penpot format) |
| [`jcode-web.pen`](jcode-web.pen) | Web application UI design files (Penpot format) |

## Design Philosophy

JCODE embodies **"developer tooling elegance."** The interface draws from terminal aesthetics and code editors — monospaced accents, structured layouts, and a palette that signals precision. Every surface is clean, every action is visible, and nothing is hidden behind decorative abstractions.

- **Terminal-inspired** — dark code blocks, monospace fonts, structured command-line previews
- **Developer-first** — dense information layout, minimal decoration, functional color coding
- **Engineering minimalism** — surfaces earn their place through utility, not ornamentation

## Key Tokens

### Brand Accent

`#FF8400` — The signature orange. Represents action, progress, and the "live" state of the terminal. Used sparingly for maximum impact: badges, primary CTAs, and status indicators.

### Typography

| Role | Font |
|------|------|
| Primary / Display | **JetBrains Mono** — logo, code blocks, terminal previews |
| Secondary / UI | **Geist** — headings, body text, navigation |

### Light & Dark Mode

| Token | Light | Dark |
|-------|-------|------|
| Background | `#F2F3F0` | `#111111` |
| Surface (Card) | `#FFFFFF` | `#1A1A1A` |
| Foreground | `#111111` | `#FFFFFF` |
| Muted Text | `#666666` | `#B8B9B6` |
| Border | `#CBCCC9` | `#2E2E2E` |

## Design Files

The `.pen` files are [Penpot](https://penpot.app/) design files containing:

- **Landing Page** — Hero section, terminal preview, feature cards, workflow steps, agent team visualization, and footer
- **Documentation Page** — Navbar with search, sidebar navigation, content area with breadcrumbs
- **Web Application** — Full app shell with sidebar, topbar, chat interface, terminal panel, file tree, code editor, changes panel, and multi-agent views

## Quick Reference for Implementers

Read [`design.md`](design.md) for the full specification including:

- Complete color palette with semantic tokens
- Typography scale (display → tiny, 12 levels)
- 20+ component specs (buttons, badges, cards, terminal, chat bubbles, etc.)
- Layout grid system and spacing scale
- Web app shell layout (3-pane and 2-pane views)
- Depth and elevation system
- Responsive breakpoints
- Agent prompt guide with ready-to-use prompts

## License

MIT
