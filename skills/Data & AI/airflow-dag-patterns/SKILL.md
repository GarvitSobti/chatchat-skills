---
id: airflow-dag-patterns
name: Airflow DAG Patterns
description: Practical guidance for building reliable Apache Airflow DAG patterns.
category: Data & AI
requires: []
examples:
  - "Design an Airflow DAG for daily ETL with retries and alerts."
  - "What DAG patterns should I use for backfills and idempotent tasks?"
---

# Airflow DAG Patterns

Help the agent provide implementation-focused guidance for Airflow DAG design and operations.

## When to Use

- The user needs help designing DAG structure, dependencies, or scheduling.
- The user asks how to improve reliability, observability, or performance.
- The user wants practical trade-offs for orchestration patterns.

## Instructions

1. Clarify workload shape, cadence, SLAs, and dependency graph.
2. Recommend DAG structure, task boundaries, and idempotency practices.
3. Suggest retries, backfills, and failure-handling strategies.
4. Include monitoring, alerting, and cost/performance considerations.
5. End with a concise rollout and validation checklist.

## Tool Use Constraints

- Use tools only when needed to complete the task.
- Allowed built-in tools: firecrawl_searchWeb, firecrawl_scrapeUrl, rag_data_search.
- Allowed integrations: Google Calendar, Slack, GitHub, Zoom, Microsoft Teams, Microsoft 365, Notion, X (Twitter).
- Do not call or reference any other tools or integrations as executable options.

## Output

- Recommended DAG pattern with rationale
- Step-by-step implementation checklist
- Risks, assumptions, and validation steps
