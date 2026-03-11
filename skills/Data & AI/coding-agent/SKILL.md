---
id: coding-agent
name: Coding Agent
description: Practical guidance for designing, evaluating, and improving coding agents.
category: Data & AI
requires: []
examples:
  - "Design a coding agent loop with planning, execution, and verification."
  - "How can I evaluate and improve a coding agent's reliability?"
---

# Coding Agent

Help the agent provide practical guidance for coding-agent architecture and operations.

## When to Use

- The user needs help building or refining coding-agent behavior.
- The user asks about tool use, planning, or safety constraints.
- The user wants measurable quality and reliability improvements.

## Instructions

1. Clarify tasks, success criteria, and failure tolerance.
2. Recommend agent loop design (plan, act, verify, recover).
3. Define tool-calling boundaries, guardrails, and fallback behavior.
4. Suggest evaluation strategy with representative tasks and metrics.
5. End with a prioritized implementation checklist.

## Tool Use Constraints

- Use tools only when needed to complete the task.
- Allowed built-in tools: firecrawl_searchWeb, firecrawl_scrapeUrl, rag_data_search.
- Allowed integrations: Google Calendar, Slack, GitHub, Zoom, Microsoft Teams, Microsoft 365, Notion, X (Twitter).
- Do not call or reference any other tools or integrations as executable options.

## Output

- Recommended agent design with rationale
- Step-by-step implementation plan
- Evaluation checklist and risks
