# The RITE Prompt Framework

Every prompt in this vault is built on the **RITE** framework. This ensures the LLM has the exact constraints, context, and examples needed to produce high-quality, non-generic output.

When using or modifying prompts in this vault, always adhere to this structure.

## R - Role
Define exactly who the AI is acting as. Do not just say "You are an expert." Give it a specific worldview, bias, and set of constraints.

**Example:**
> "You are a B2B SaaS Go-To-Market Engineer. You despise corporate fluff, buzzwords, and vague marketing speak. You write in dense, tactical, operator-level language."

## I - Input
Clearly define what data the AI is receiving. This prevents hallucination.

**Example:**
> "I am providing you with a 1,500-word transcript from a recent podcast interview where our founder discusses the shift from traditional CRMs to AI Agents."

## T - Task
Give the exact, step-by-step instructions of what needs to be produced. Constrain the formatting strictly.

**Example:**
> "Extract the 3 strongest contrarian opinions from this transcript. For each opinion, write a LinkedIn post following the 'Bullet List Framework' (hook, context, 5-point list, turn, CTA). Do not use hashtags. Do not use emojis other than ↳ and 👉."

## E - Example
Provide a canonical example of what "good" looks like. This is the most important step for tone calibration.

**Example:**
> "Here is an example of the exact tone and structure I want you to emulate:
> [Insert high-performing post from `docs/rawcontent.md`]"

---

## How to Use This Framework with the Brain

The prompts in the `prompts/` directory automatically inject the **Role** and **Task** based on the intelligence stored in the `skills/` directory. 

You only need to provide the **Input** (your raw text/idea) and the prompt will handle the rest.
