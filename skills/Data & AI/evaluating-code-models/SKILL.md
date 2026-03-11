---
id: evaluating-code-models
name: Evaluating Code Models
description: Practical guidance for evaluating code-generation and code-understanding models.
category: Data & AI
requires: []
examples:
  - "Design a benchmark to evaluate a code generation model."
  - "How should I score correctness, style, and robustness?"
---

# Evaluating Code Models

Help the agent provide practical guidance for code model evaluation workflows.

## When to Use

- The user needs help measuring code model quality and reliability.
- The user asks about benchmark design, scoring, or failure analysis.
- The user wants actionable recommendations for improving model performance.

## Instructions

1. Clarify task mix (generation, repair, explanation) and target languages.
2. Recommend benchmark construction and sampling strategy.
3. Define automated and human review metrics.
4. Include error taxonomy and regression tracking approach.
5. End with an implementation and reporting checklist.

## Tool Use Constraints

- Use tools only when needed to complete the task.
- Allowed built-in tools: firecrawl_searchWeb, firecrawl_scrapeUrl, rag_data_search.
- Allowed integrations: Google Calendar, Slack, GitHub, Zoom, Microsoft Teams, Microsoft 365, Notion, X (Twitter).
- Do not call or reference any other tools or integrations as executable options.

## Output

- Recommended evaluation strategy
- Step-by-step benchmark plan
- Metrics, risks, and validation checklist
