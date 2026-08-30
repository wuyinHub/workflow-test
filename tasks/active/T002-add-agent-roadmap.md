# T002 - Add six-stage Agent learning roadmap

**Status:** READY  
**Created:** 2026-08-30

## Goal

Populate the webpage foundation created in T001 with the approved concise six-stage AI Agent learning roadmap and add clear source attribution.

## Context

T001 established the static webpage structure, base styling, roadmap container, and source/footer area.

Before implementation, read:

- `AGENTS.md`
- `docs/PROJECT.md`
- `docs/DECISIONS.md`
- `tasks/completed/T001-initialize-webpage.md`

Relevant decisions: D001, D002, D003, and D004.

The roadmap is derived and simplified from the GitHub repository `WenyuChiou/awesome-agentic-ai-zh`. Summarize the learning structure in original concise wording rather than copying large sections verbatim.

## Approved Roadmap Content

### Stage 1 - Foundations

Focus: Build the technical foundation needed to work effectively with Agent systems.

Core topics:
- Python
- CLI
- Git
- APIs
- JSON

### Stage 2 - LLM Basics

Focus: Understand how language models work at the practical level and how applications interact with them.

Core topics:
- Tokens
- LLM/model usage
- LLM APIs
- Local models

### Stage 3 - Prompt & Tool Use

Focus: Learn how to guide models and let them interact with external capabilities.

Core topics:
- Prompt engineering
- Few-shot prompting
- Function calling / tool use
- ReAct

### Stage 4 - Agent Engineering

Focus: Move from isolated model calls to practical Agent workflows and reusable capabilities.

Core topics:
- CLI Agents
- MCP
- Skills
- Plugins
- Subagents

### Stage 5 - Context & Multi-Agent

Focus: Give Agents useful context, memory, coordination, and production-quality feedback loops.

Core topics:
- RAG
- Memory
- Multi-Agent systems
- Evaluation
- Observability

### Stage 6 - Advanced Interfaces

Focus: Apply Agents through richer interfaces and practical end-to-end projects.

Core topics:
- Browser Use
- Computer Use
- Code Sandbox
- Practical projects

## Scope

### Must do

- Populate the existing roadmap section with all six approved stages in order from Stage 1 through Stage 6.
- Give every stage a visible stage number, stage name, concise one-sentence explanation, and its approved core learning topics.
- Make the progression from Stage 1 to Stage 6 visually clear.
- Reuse and extend the structure created in T001 rather than replacing the page unnecessarily.
- Add a visible source/attribution section for `WenyuChiou/awesome-agentic-ai-zh`.
- Make the source repository reference clickable and clearly identify the roadmap as a simplified/derived learning path.
- Keep the content readable at common desktop and mobile widths.
- Preserve the existing lightweight static-site approach.

### Must not do

- Do not copy large passages from the source repository verbatim.
- Do not introduce React, Vue, Bootstrap, Tailwind, npm, or another framework/build system.
- Do not add a backend or database.
- Do not perform unrelated refactoring.
- Do not turn this task into the final visual-polish task; elaborate animation and decorative interaction are reserved for T003.
- Do not change accepted decisions in `docs/DECISIONS.md`.

## Acceptance Criteria

- [ ] Opening `index.html` shows all six approved Agent learning stages in the correct order.
- [ ] Every stage includes its number, name, concise explanation, and approved core topics.
- [ ] The page communicates a clear progression from foundations to advanced Agent interfaces.
- [ ] A visible clickable attribution to `WenyuChiou/awesome-agentic-ai-zh` is present.
- [ ] The attribution makes clear that the displayed roadmap is a simplified/derived version.
- [ ] The page remains readable at common desktop and mobile widths.
- [ ] Existing T001 structure is reused where reasonable and unrelated changes are avoided.
- [ ] No framework, package manager, backend, or build step is introduced.
- [ ] Browser developer tools show no missing local assets or JavaScript errors.

## Verification

- Open `index.html` in a browser.
- Check all six stages for order, required content, and readability.
- Verify the source link opens the intended GitHub repository.
- Inspect the page at desktop and mobile widths.
- Confirm browser developer tools show no missing local asset or JavaScript errors.
- Review the final diff for unrelated changes.

## Delivery

Implement this task on a dedicated branch and open a Pull Request to `main` for human review. Do not merge the Pull Request yourself.

## Notes

T002 focuses on complete roadmap content and attribution. T003 is reserved for visual hierarchy, interaction, and final UI polish.
