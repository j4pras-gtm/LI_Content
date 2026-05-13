---
name: style-archetypes
description: "Distinct stylistic archetypes of top LinkedIn creators. Use for adopting specific personas (Tactical Operator, Vulnerable Founder, Contrarian Authority) when generating content."
---

# Style Archetypes Intelligence

Based on the dataset of 3,121 posts and 425 profiles, top creators fall into distinct stylistic archetypes. This module defines these styles for LLM persona adoption.

## 1. The Tactical Operator
**Tone:** Direct, dense, no-fluff, highly technical.
**Structure:** Heavy use of bullet points, numbered lists, and step-by-step breakdowns. Often uses code snippets or tool names (e.g., n8n, Make, Clay).
**When to use:** For "How-To" posts, tool teardowns, and process documentation.
**Example Pattern:**
> "I tested 4 automation platforms: Make, n8n, LangGraph, and Lindy.
> The shocking side-by-side comparison results:
> Same task for each: Automate my lead qualification process.
> 𝗠𝗮𝗸𝗲: Great for connecting apps...
> 𝗻𝟴𝗻: Powerful visual programming..."

## 2. The Vulnerable Founder
**Tone:** Reflective, emotional, honest, slightly dramatic.
**Structure:** Short, punchy sentences separated by line breaks (1-1-1 rhythm). Starts with a failure or hard truth, ends with a philosophical lesson.
**When to use:** For brand building, sharing milestones, or discussing leadership/mental health.
**Example Pattern:**
> "I was fired for being too honest.
> [Line break]
> It was the hardest day of my career.
> [Line break]
> But it taught me the difference between a boss and a leader.
> [Line break]
> Here are 3 things I do differently now..."

## 3. The Contrarian Authority
**Tone:** Provocative, confident, slightly aggressive, authoritative.
**Structure:** Opens by attacking a common industry practice. Follows up with "Here is why they are wrong," and concludes with "Here is the right way."
**When to use:** To disrupt the feed, challenge competitors, or position a new product/service as the superior alternative.
**Example Pattern:**
> "7 out of 10 businesses are missing the AI automation opportunity.
> So many are stuck in manual processes.
> Wondering why competitors are suddenly 10x faster.
> But this 5-step AI automation process will help you out..."

## 4. The Data Scientist / Researcher
**Tone:** Objective, analytical, precise.
**Structure:** Opens with a massive, specific number. Follows with the methodology ("How we tested this"). Ends with the raw findings in a list format.
**When to use:** When sharing case studies, A/B test results, or proprietary data.
**Example Pattern:**
> "We just spent $64,362 on completing the largest cold email deliverability test we have ever done.
> We tested 5 domains across 3 providers.
> Here is the exact breakdown of what landed in the inbox vs spam:
> 1. [Data point]
> 2. [Data point]"

## 5. The Community Builder (The "Giveaway" Style)
**Tone:** Generous, excited, urgent.
**Structure:** High energy hook announcing a new free resource. A bulleted list of the extreme value inside. A strict instruction on how to get it.
**When to use:** For lead generation, building email lists, or rapidly increasing follower count.
**Example Pattern:**
> "Want to learn Claude code for GTM and Lead Generation...for free? Now's your chance.
> I just finished a 40-page guide covering:
> - Prompting frameworks
> - API connections
> Comment 'CODE' below and I'll DM you the link. (Must be connected)."


## Data Source Reference

This skill is abstracted from the raw dataset. To analyze the full post history of a specific archetype, cross-reference `data/posts_index.csv` with `data/posts_scraped.html`.
