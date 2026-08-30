# Project

## Name

Agent Learning Roadmap Webpage

## Purpose

Build a simple single-page website that presents a concise AI Agent learning roadmap distilled from a highly starred GitHub learning-roadmap resource.

The project is also used to validate the human-in-the-loop workflow:

ChatGPT planning -> GitHub project state -> human approval -> Codex implementation -> Pull Request -> human review -> merge.

## Users

Learners who want a compact overview of the main skills and concepts needed to learn AI Agents.

## Scope

### In scope

- A simple single-page website.
- A concise six-stage AI Agent learning roadmap.
- Clear visual hierarchy suitable for roadmap/timeline presentation.
- A visible attribution/reference to the GitHub source used to derive the roadmap.
- Lightweight responsive behavior for desktop and mobile.

### Out of scope

- Backend services.
- Database storage.
- User accounts.
- Complex frameworks or build systems.
- Copying large portions of the source repository verbatim.

## Technology Stack

- HTML
- CSS
- Vanilla JavaScript

No frontend framework or package manager is required for the initial version.

## Content Source

The roadmap content is derived and simplified from the GitHub repository `WenyuChiou/awesome-agentic-ai-zh`, selected during planning as a highly starred Agent learning-roadmap resource.

The webpage should summarize the learning structure rather than reproduce source text verbatim.

## Planned Roadmap Structure

1. Foundations — Python, CLI, Git, APIs, JSON
2. LLM Basics — tokens, model usage, APIs, local models
3. Prompt & Tool Use — prompting, few-shot, function calling, ReAct
4. Agent Engineering — CLI agents, MCP, skills, plugins, subagents
5. Context & Multi-Agent — RAG, memory, multi-agent systems, evaluation, observability
6. Advanced Interfaces — browser use, computer use, code sandbox, practical projects

## Current Stage

Implementation preparation

## Current Priorities

1. Initialize the webpage structure and base styling.
2. Add the approved six-stage Agent learning roadmap.
3. Polish visual hierarchy, responsiveness, and lightweight interaction.

## Notes

Keep this document concise. It describes the current project state rather than preserving full chat history.
