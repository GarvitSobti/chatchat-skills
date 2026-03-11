---
id: composio
name: Composio
description: Practical guidance for implementing app integrations with Composio.
category: Data & AI
requires: []
examples:
  - "Help me integrate Slack and Notion actions using Composio."
  - "What is the best way to handle retries and auth in Composio workflows?"
---

# Composio

Help the agent provide practical guidance for Composio tool integrations and workflows.

## When to Use

- The user needs help connecting external apps via Composio.
- The user asks about auth, action mapping, or reliability patterns.
- The user wants concrete integration steps and troubleshooting guidance.

## Instructions

1. Clarify target apps, permissions, and workflow outcomes.
2. Recommend integration architecture and action sequencing.
3. Include credential handling and security practices.
4. Suggest retries, rate-limit handling, and observability.
5. End with an implementation and test checklist.

## Tool Use Constraints

- Use tools only when needed to complete the task.
- Allowed built-in tools: firecrawl_searchWeb, firecrawl_scrapeUrl, rag_data_search.
- Allowed integrations: Google Calendar, Slack, GitHub, Zoom, Microsoft Teams, Microsoft 365, Notion, X (Twitter).
- Do not call or reference any other tools or integrations as executable options.

## Output

- Recommended integration approach
- Step-by-step implementation plan
- Validation and troubleshooting checklist
