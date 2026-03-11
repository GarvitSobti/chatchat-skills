---
id: fine-tuning-with-trl
name: Fine Tuning with TRL
description: Practical guidance for fine-tuning language models with TRL.
category: Data & AI
requires: []
examples:
  - "Plan a TRL fine-tuning run with safe default hyperparameters."
  - "How do I validate and ship a model fine-tuned with TRL?"
---

# Fine Tuning with TRL

Help the agent provide practical guidance for TRL fine-tuning workflows.

## When to Use

- The user needs help setting up supervised or preference-based TRL training.
- The user asks about data prep, hyperparameters, or training stability.
- The user wants practical fine-tuning steps with evaluation guidance.

## Instructions

1. Clarify model, hardware budget, data format, and target behavior.
2. Recommend training recipe and core hyperparameter ranges.
3. Include safety checks for overfitting, instability, and mode collapse.
4. Define evaluation protocol and rollout criteria.
5. End with a reproducible implementation checklist.

## Tool Use Constraints

- Use tools only when needed to complete the task.
- Allowed built-in tools: firecrawl_searchWeb, firecrawl_scrapeUrl, rag_data_search.
- Allowed integrations: Google Calendar, Slack, GitHub, Zoom, Microsoft Teams, Microsoft 365, Notion, X (Twitter).
- Do not call or reference any other tools or integrations as executable options.

## Output

- Recommended TRL fine-tuning strategy
- Step-by-step training plan
- Validation and risk checklist
