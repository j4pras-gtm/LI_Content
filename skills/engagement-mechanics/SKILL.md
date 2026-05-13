---
name: engagement-mechanics
description: "Psychological triggers, formatting tricks, and retention tactics that drive high engagement on LinkedIn. Use for optimizing posts for virality and readability."
---

# Engagement Mechanics Intelligence

This module breaks down the psychological triggers, formatting tricks, and retention tactics that drive high engagement (likes, comments, reposts) based on the dataset.

## 1. Psychological Triggers

### The "Curiosity Gap"
Top posts create a gap between what the reader knows and what they want to know.
- **Implementation:** "Most people using AI don't know these 7 parameters exist. Yet they control everything about your AI..."
- **Why it works:** The brain naturally wants to close open loops. The reader *must* click "see more" to find out what the 7 parameters are.

### The "In-Group" Signal
Using highly specific industry jargon or calling out a specific role immediately.
- **Implementation:** "GTM Engineers & Agency Owners:" or "Hey Sales Cold Emailers,"
- **Why it works:** It triggers identity-based reading. If the reader identifies as a GTM Engineer, they feel compelled to read because the content is "for them."

### The "Authority by Specificity"
Using exact, non-rounded numbers instead of estimates.
- **Implementation:** "We just spent $64,362..." instead of "We spent over $60k..."
- **Why it works:** Exact numbers imply rigorous tracking and truthfulness.

## 2. Virality Drivers

### The "Comment-to-DM" Loop (The Algorithm Hack)
The most consistent driver of massive engagement (posts with 500+ comments) is the gated resource.
- **The Mechanic:** Offer a high-value asset (cheat sheet, prompt library, n8n workflow). Require a specific comment (e.g., "Comment 'MCP'") to receive it.
- **The Result:** The algorithm sees a massive spike in comments in the first hour, categorizes the post as "highly engaging," and pushes it to a broader network, creating a viral loop.

### The "Us vs. Them" Framing
- **The Mechanic:** Positioning a new way of doing things against the old, outdated way.
- **Implementation:** "Everyone's rushing to build AI agents, but 90% are just building glorified chatbots. It's about architecting systems..."

## 3. Formatting Patterns

Data from the top 191 high-engagement posts reveals strict formatting rules:

- **High Emoji Usage (63% of top posts):** Emojis are not used for emotion; they are used as structural elements.
  - `↳` or `👉` for sub-bullets.
  - `🚨` or `⚠️` for urgent CTAs.
  - `♻️` for repost requests.
- **Number Density (78% of top posts):** High-performing posts are incredibly dense with numbers (metrics, steps, dollars, percentages).
- **List Formatting (35% of top posts):** The brain processes lists faster than paragraphs. Top posts almost always break complex ideas into 3-7 bullet points.
- **Bold Text for Skimmability:** 2.3% of posts use unicode bold text (e.g., 𝗠𝗮𝗸𝗲, 𝗻𝟴𝗻) to create visual hierarchy within the plain-text constraints of LinkedIn.

## 4. Retention Tactics (The "See More" Click)

LinkedIn truncates posts after roughly 3-5 lines. The sole purpose of the first 3 lines is to earn the "see more" click.

- **Tactic 1: The Cliffhanger:** End line 3 mid-thought.
- **Tactic 2: The Promise:** Line 3 states exactly what the reader will get if they expand the post ("Here is the exact 5-step framework:").
- **Tactic 3: Visual Spacing:** Use double line breaks between the first three sentences to push the actual content below the "see more" fold, forcing the click.


## Data Source Reference

This skill is abstracted from the raw dataset. For raw engagement metrics (likes, comments, reposts) on specific posts, reference `data/posts_scraped.html`.
