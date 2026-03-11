---
id: eval-harness
name: Eval Harness
description: Practical guidance for building and running evaluation harnesses.
category: Data & AI
requires: []
examples:
  - "Create an eval harness to compare two model versions."
  - "How do I add regression checks and pass/fail thresholds?"
---

# Eval Harness

Help the agent provide practical guidance for evaluation harness design and execution.

## When to Use

- The user needs help setting up repeatable model or system evaluations.
- The user asks about metrics, test sets, or regression detection.
- The user wants practical implementation details for reliable evaluations.

## Instructions

1. Clarify evaluation goals, datasets, and pass/fail criteria.
2. Recommend harness structure for reproducibility and comparison.
3. Define metrics, baselines, and reporting format.
4. Include CI integration and regression alerting guidance.
5. End with an implementation checklist.

## Tool Use Constraints

- Use tools only when needed to complete the task.
- Allowed built-in tools: firecrawl_searchWeb, firecrawl_scrapeUrl, rag_data_search.
- Allowed integrations: Google Calendar, Slack, GitHub, Zoom, Microsoft Teams, Microsoft 365, Notion, X (Twitter).
- Do not call or reference any other tools or integrations as executable options.

## Output

- Recommended eval harness structure
- Step-by-step implementation checklist
- Metrics and regression validation plan
