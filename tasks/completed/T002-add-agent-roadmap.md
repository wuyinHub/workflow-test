# T002 - Add six-stage Agent learning roadmap

**Status:** COMPLETED  
**Created:** 2026-08-30  
**Completed:** 2026-08-30

## Goal

Populate the webpage foundation created in T001 with the approved concise six-stage AI Agent learning roadmap and add clear source attribution.

## Context

T001 established the static webpage structure, base styling, roadmap container, and source/footer area.

Relevant decisions: D001, D002, D003, and D004.

The roadmap is derived and simplified from the GitHub repository `WenyuChiou/awesome-agentic-ai-zh`. The implementation uses concise original wording rather than reproducing large source passages verbatim.

## Approved Roadmap Content

1. Foundations — Python, CLI, Git, APIs, JSON
2. LLM Basics — Tokens, model usage, LLM APIs, local models
3. Prompt & Tool Use — Prompt engineering, few-shot prompting, function calling, ReAct
4. Agent Engineering — CLI Agents, MCP, Skills, Plugins, Subagents
5. Context & Multi-Agent — RAG, Memory, Multi-Agent systems, Evaluation, Observability
6. Advanced Interfaces — Browser Use, Computer Use, Code Sandbox, Practical projects

## Acceptance Criteria

- [x] Opening `index.html` shows all six approved Agent learning stages in the correct order.
- [x] Every stage includes its number, name, concise explanation, and approved core topics.
- [x] The page communicates a clear progression from foundations to advanced Agent interfaces.
- [x] A visible clickable attribution to `WenyuChiou/awesome-agentic-ai-zh` is present.
- [x] The attribution makes clear that the displayed roadmap is a simplified/derived version.
- [x] The page remains readable at common desktop and mobile widths.
- [x] Existing T001 structure is reused where reasonable and unrelated changes are avoided.
- [x] No framework, package manager, backend, or build step is introduced.

## Verification

- Pull Request #2 was reviewed and merged into `main` on 2026-08-30.
- The merged diff changed `index.html` and `style.css` only.
- The six approved stages, progression styling, responsive adjustments, and source attribution were present in the reviewed PR.
- No GitHub Actions workflow was configured for automated CI checks.

## Delivery

Delivered through Pull Request #2 and accepted into `main` after review.

## Notes

T002 completed the roadmap content and attribution. T003 remains reserved for final visual hierarchy, interaction, and UI polish.
