# LI_Content — The Prompt Vault & AI Brain

This repository is a complete, fully mapped `.prompt-vault` for LinkedIn content generation and Go-To-Market (GTM) operations. 

It is built on top of a data-grounded "Brain" extracted from **3,121 high-performing LinkedIn posts** and **425 creator profiles**.

## Vault Architecture

```
LI_Content/
├── README.md                          ← How to use this vault
├── rite-framework.md                  ← Role, Input, Task, Example — universal prompt wrapper
├── brand-voice-bible.md               ← Tone, anti-tone, style — loaded on demand
│
├── data/                              ← Raw data sources (JSON profiles, CSV index, HTML posts)
├── skills/                            ← 6 SKILL.md brain modules (patterns, archetypes, mechanics)
├── docs/rawcontent.md                 ← Raw pattern vault (swipe file)
│
└── prompts/                           ← Canonical home for all GTM prompts
    ├── positioning/                   ← ICP, messaging, VOC (Partially built)
    ├── content-linkedin/              ← Posts, repurposing, angles (Fully built)
    ├── email-ads-pr/                  ← Outbound, ads, PR (TODO)
    ├── dashboards/                    ← Live GTM artifacts (TODO)
    ├── sales-prospecting/             ← Research, audit, scraping (TODO)
    └── ai-skills-setup/               ← Skills, migration, build (TODO)
```

## How to Use This Vault

1. **The Brain (`/skills/` & `/data/`)**: This is the intelligence layer. It contains the structural patterns, psychological triggers, and raw data that make the prompts work.
2. **The Framework (`rite-framework.md`)**: Every prompt follows the Role, Input, Task, Example structure.
3. **The Prompts (`/prompts/`)**: These are the actual copy-paste prompts you feed to Claude, ChatGPT, or Manus. They automatically call upon the Brain to ensure high-quality, non-generic output.

## Current Status (Phase 1)

- **Fully Built:** `/prompts/content-linkedin/` (Grounded in the 3,121 post dataset)
- **Partially Built:** `/prompts/positioning/` (Grounded in the 425 profile dataset)
- **TODO:** The remaining folders are currently stubs. They require your specific business data (email sequences, sales pipelines, ad copy) to be built out properly without relying on generic AI templates. See the `TODO.md` in each folder for instructions.
