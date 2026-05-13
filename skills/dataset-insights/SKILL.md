---
name: dataset-insights
description: "Quantitative insights derived from 3,121 LinkedIn posts and 425 creator profiles. Use for understanding benchmarks for post length, formatting, and engagement."
---

# Dataset Insights Intelligence

This module provides quantitative insights derived from the analysis of 3,121 LinkedIn posts and 425 creator profiles. These metrics define the boundaries of what "normal" and "high-performing" look like on the platform.

## 1. Post Length Patterns

High-performing posts (200+ likes) are measurably longer than average posts.

| Metric | All Posts | High-Engagement Posts |
|---|---|---|
| **Average Word Count** | 205 words | 238 words (+16%) |
| **Average Line Count** | 19.4 lines | 24.0 lines (+23%) |

**Insight:** The algorithm and audience reward depth. Short, platitude-heavy posts perform worse than detailed, multi-line breakdowns. The 24-line average indicates heavy use of line breaks (the "broetry" format) to make 238 words highly skimmable.

## 2. Formatting Trends

Formatting is not decorative; it is structural. High-engagement posts use specific formatting tools at significantly different rates than average posts.

| Formatting Element | All Posts | High-Engagement Posts |
|---|---|---|
| **Contains Numbers** | 76.3% | 78.0% |
| **Contains Emojis** | 47.5% | 63.3% |
| **Contains Bullet Lists** | 38.8% | 35.6% |
| **Contains Unicode Bold** | 2.3% | (Data sparse, but present in top 10) |

**Insight:** 
- **Numbers are mandatory:** Nearly 80% of top posts use numbers. Specificity is the baseline for credibility.
- **Emojis are structural:** The jump from 47% to 63% in emoji usage among top posts correlates with their use as bullet points (👉, ↳, ✅) rather than emotional expressions (😂, 😢).

## 3. Style Distribution (The "GTM / AI" Niche)

The dataset is heavily skewed toward Go-To-Market (GTM), Sales, and AI Automation professionals.

**Top Job Titles:**
1. Founder (80)
2. Co-Founder (24)
3. Founder & CEO (12)
4. GTM Engineer (10)

**Top Geographies:**
1. London, UK (16)
2. New York, USA (16)
3. Bengaluru, India (13)
4. San Francisco, USA (10)

**Insight:** The dominant voice in this dataset is the "Builder/Founder." The tone is inherently entrepreneurial, focused on revenue, efficiency, and cutting-edge technology (specifically AI agents and outbound sales).

## 4. Common Success Traits

Based on the cross-section of top posts and top profiles:

1. **The "Giveaway" Engine:** The absolute highest comment counts (e.g., 2,749 comments, 1,599 comments) are exclusively driven by "Comment [Word] to get [Resource]" CTAs. This is the primary engine for algorithmic reach.
2. **The "David vs. Goliath" Narrative:** Top posts frequently position a small, agile entity (a 27M parameter AI model, a solo founder using n8n) beating a massive incumbent (GPT-5, a traditional agency).
3. **Extreme Niche Positioning:** Top profiles do not claim to be "Marketers" or "Salespeople." They claim highly specific, newly invented categories like "GTM Engineer" or "AI Automation Agency (AIAA) Founder."


## Data Source Reference

This skill is abstracted from the raw dataset. To run custom queries or extract new benchmarks, parse the raw data in `data/posts_scraped.html` and `data/profiles_425.json.gz`.
