---
id: geopandas
name: GeoPandas
description: Practical guidance for geospatial data workflows with GeoPandas.
category: Data & AI
requires: []
examples:
  - "Help me build a GeoPandas workflow for spatial joins."
  - "How do I handle CRS conversion and geometry validity checks?"
---

# GeoPandas

Help the agent provide practical guidance for GeoPandas analysis and data engineering.

## When to Use

- The user needs help loading, transforming, or analyzing geospatial data.
- The user asks about CRS handling, joins, or geometry operations.
- The user wants practical patterns for accurate and performant workflows.

## Instructions

1. Clarify data sources, CRS, and target analyses.
2. Recommend transformation and spatial operation patterns.
3. Include performance practices for large geospatial datasets.
4. Call out CRS mismatch and topology pitfalls.
5. End with a reproducible validation checklist.

## Tool Use Constraints

- Use tools only when needed to complete the task.
- Allowed built-in tools: firecrawl_searchWeb, firecrawl_scrapeUrl, rag_data_search.
- Allowed integrations: Google Calendar, Slack, GitHub, Zoom, Microsoft Teams, Microsoft 365, Notion, X (Twitter).
- Do not call or reference any other tools or integrations as executable options.

## Output

- Recommended GeoPandas approach
- Step-by-step implementation checklist
- Validation and troubleshooting steps
