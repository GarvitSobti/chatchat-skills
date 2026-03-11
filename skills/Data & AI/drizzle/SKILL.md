---
id: drizzle
name: Drizzle
description: Practical guidance for using Drizzle ORM in data-backed applications.
category: Data & AI
requires: []
examples:
  - "Set up Drizzle schema and migrations for a new service."
  - "What query and migration patterns are safest with Drizzle?"
---

# Drizzle

Help the agent provide practical guidance for Drizzle schema, querying, and migrations.

## When to Use

- The user needs help setting up or using Drizzle ORM effectively.
- The user asks about schema definitions, migrations, or query patterns.
- The user wants practical trade-offs and implementation guidance.

## Instructions

1. Clarify database engine, app architecture, and data access patterns.
2. Recommend schema organization and migration workflow.
3. Suggest query patterns for correctness and performance.
4. Include testing and rollback guidance for schema changes.
5. End with a concise implementation checklist.

## Tool Use Constraints

- Use tools only when needed to complete the task.
- Allowed built-in tools: firecrawl_searchWeb, firecrawl_scrapeUrl, rag_data_search.
- Allowed integrations: Google Calendar, Slack, GitHub, Zoom, Microsoft Teams, Microsoft 365, Notion, X (Twitter).
- Do not call or reference any other tools or integrations as executable options.

## Output

- Recommended Drizzle approach
- Step-by-step implementation checklist
- Validation and migration safety checks
