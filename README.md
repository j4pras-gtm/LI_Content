# LI_Content — LinkedIn AI Brain

This repository contains the core intelligence layer for a LinkedIn content generation system. It is built from the analysis of **3,121 high-performing LinkedIn posts** and **425 creator profiles**, extracted and structured for LLM reuse.

## Repository Structure

```
LI_Content/
├── skills/                           # Structured intelligence modules (plug-and-play for LLMs)
│   ├── writing-patterns/SKILL.md     # Hook frameworks, post structures, CTA types, flow patterns
│   ├── style-archetypes/SKILL.md     # 5 distinct creator styles with tone, structure, and usage
│   ├── engagement-mechanics/SKILL.md # Psychological triggers, virality drivers, formatting rules
│   ├── profile-intelligence/SKILL.md # Headline formulas, About section frameworks, positioning
│   ├── component-library/SKILL.md    # Atomic hook, transition, and CTA templates
│   └── dataset-insights/SKILL.md     # Quantitative benchmarks from the full dataset
└── docs/
    └── rawcontent.md                 # Raw pattern vault: swipe file, hooks, CTAs, headlines
```

## Skills Overview

| Skill | Purpose |
|---|---|
| `writing-patterns` | Structural blueprints for post construction |
| `style-archetypes` | Persona-based writing styles for tone matching |
| `engagement-mechanics` | Algorithm and psychology-driven engagement tactics |
| `profile-intelligence` | Profile copywriting frameworks for headlines and About sections |
| `component-library` | Reusable atomic writing components |
| `dataset-insights` | Data benchmarks for calibrating post length, format, and style |

## Data Source

- **Posts:** 3,121 scraped LinkedIn posts with likes, comments, and full text
- **Profiles:** 425 LinkedIn profiles with positions, skills, headlines, and summaries
- **Engagement tiers:** High (200+ likes), Mid (50–199), Low (<50)

## Usage

Each `SKILL.md` file contains valid YAML front matter and can be loaded directly into Manus as a skill. The `docs/rawcontent.md` file serves as a raw swipe file and pattern vault for prompt construction.

```yaml
---
name: writing-patterns
description: "Structural writing patterns extracted from high-performing LinkedIn posts..."
---
```

## Last Updated

May 2026 — based on dataset scraped May 10–12, 2026.
