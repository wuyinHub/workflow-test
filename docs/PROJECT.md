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

Planned implementation scope completed. The project is ready for final project-state review and workflow retrospective.

## Current Priorities

1. Review the completed project state and confirm no implementation task remains active.
2. Retrospect on the ChatGPT -> GitHub -> Codex -> Pull Request workflow used during T001-T003.
3. Decide which validated workflow improvements should be incorporated into `workflow_freamwork v2`.

## Completed

- T001 — Initialized the static webpage foundation with `index.html`, `style.css`, and `script.js`; delivered through Pull Request #1 and merged into `main`.
- T002 — Added the complete six-stage Agent learning roadmap, progression presentation, responsive styling, and source attribution; delivered through Pull Request #2 and merged into `main`.
- T003 — Completed final visual hierarchy, responsive behavior, accessibility feedback, and lightweight interaction polish; delivered through Pull Request #3 and merged into `main`.

## Notes

The originally planned implementation scope is complete. New feature work should begin only after a new task is explicitly planned, approved, and placed in `tasks/active/`.

Keep this document concise. It describes the current project state rather than preserving full chat history.
