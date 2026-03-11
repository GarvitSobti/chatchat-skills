---
id: data-quality-frameworks
name: Data Quality Frameworks
description: Practical guidance for data quality frameworks and production checks.
category: Data & AI
requires: []
examples:
  - "Build a data quality framework for my analytics pipeline."
  - "Which checks should I enforce for schema, freshness, and anomalies?"
---

# Data Quality Frameworks

Help the agent provide practical guidance for designing data quality controls.

## When to Use

- The user needs help defining data quality standards and checks.
- The user asks about profiling, validation rules, or quality SLAs.
- The user wants implementation-ready guardrails for pipelines.

## Instructions

1. Clarify data domain, quality requirements, and failure impact.
2. Recommend a layered framework (schema, distribution, business rules).
3. Define alerting, triage, and ownership for failed checks.
4. Include drift and anomaly monitoring strategy.
5. End with a rollout and maintenance checklist.

## Tool Use Constraints

- Use tools only when needed to complete the task.
- Allowed built-in tools: firecrawl_searchWeb, firecrawl_scrapeUrl, rag_data_search.
- Allowed integrations: Google Calendar, Slack, GitHub, Zoom, Microsoft Teams, Microsoft 365, Notion, X (Twitter).
- Do not call or reference any other tools or integrations as executable options.

## Output

- Recommended quality framework
- Step-by-step implementation checklist
- Validation, alerting, and ownership plan
