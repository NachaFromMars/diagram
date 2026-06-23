# diagram — Generate diagrams from text descriptions

> Turn system descriptions, flows, and data models into clean Mermaid, PlantUML, ASCII, or SVG diagrams. Minimal first, detailed on request.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
diagram generates visual diagrams from natural language descriptions. It defaults to Mermaid for broad compatibility, falls back to PlantUML for complex cases, and supports ASCII for inline use and SVG for custom output. The guiding principle is clarity over complexity — it drafts a minimal version first and adds detail only when you ask. Supports rendering to PNG/SVG via `mmdc` CLI or interactive HTML with Mermaid.js.

## Features
| Type | Mermaid syntax |
|---|---|
| Flowchart / process | `flowchart` |
| Sequence / API calls | `sequenceDiagram` |
| Architecture / C4 | `flowchart` or `C4` |
| ER / data model | `erDiagram` |
| Class / OOP | `classDiagram` |
| State / lifecycle | `stateDiagram-v2` |
| Timeline | `timeline` |
| Mindmap | `mindmap` |

**Rendering:**
```bash
npx -y @mermaid-js/mermaid-cli mmdc -i diagram.mmd -o diagram.png -b transparent
```

## Trigger Keywords (OpenClaw)
draw diagram, create flowchart, sequence diagram, architecture diagram, ER diagram, mindmap, state diagram

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
