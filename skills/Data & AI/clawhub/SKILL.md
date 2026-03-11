---
id: clawhub
name: ClawHub
description: Practical guidance for building and operating workflows with ClawHub.
category: Data & AI
requires: []
examples:
  - "Help me set up a ClawHub workflow with secure credentials."
  - "How do I troubleshoot failed runs in ClawHub integrations?"
---

# ClawHub

Help the agent provide practical guidance for ClawHub integrations and workflow execution.

## When to Use

- The user needs help configuring or using ClawHub workflows.
- The user asks about integrations, auth setup, or operational reliability.
- The user wants implementation-ready steps and troubleshooting guidance.

## Instructions

1. Clarify use case, systems involved, and required outputs.
2. Recommend workflow structure, trigger strategy, and error handling.
3. Suggest secure credential handling and environment setup.
4. Include observability and recovery guidance for failed runs.
5. End with a concise implementation checklist.

## Tool Use Constraints

- Use tools only when needed to complete the task.
- Allowed built-in tools: firecrawl_searchWeb, firecrawl_scrapeUrl, rag_data_search.
- Allowed integrations: Google Calendar, Slack, GitHub, Zoom, Microsoft Teams, Microsoft 365, Notion, X (Twitter).
- Do not call or reference any other tools or integrations as executable options.

## Output

- Recommended workflow approach
- Step-by-step implementation plan
- Validation and troubleshooting checklist
