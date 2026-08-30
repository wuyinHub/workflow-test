# Decisions

This file records decisions that should remain stable across future ChatGPT discussions and Codex tasks.

Do not copy full conversations here. Record only the final decision, its reason, and relevant consequences.

---

## Accepted Decisions

### D001 - Use a lightweight static web stack

**Status:** Accepted  
**Date:** 2026-08-30

**Decision**

Build the initial website with HTML, CSS, and vanilla JavaScript only.

**Reason**

The project is intentionally small and is primarily being used to validate the ChatGPT -> GitHub -> Codex -> Pull Request workflow. A framework or build system would add unnecessary complexity.

**Consequences / Constraints**

- No frontend framework is required.
- No package manager or build step should be introduced unless a future approved decision changes this.
- The page should be runnable as a simple static website.

---

### D002 - Present the roadmap as six concise learning stages

**Status:** Accepted  
**Date:** 2026-08-30

**Decision**

Present the Agent learning roadmap as six core stages: Foundations, LLM Basics, Prompt & Tool Use, Agent Engineering, Context & Multi-Agent, and Advanced Interfaces.

**Reason**

The source roadmap contains substantially more detail than is appropriate for a simple overview page. Six stages preserve the main learning progression while keeping the page easy to scan.

**Consequences / Constraints**

- The page should emphasize the six-stage progression rather than exhaustive resource lists.
- Detailed learning resources may be added only through later approved tasks.

---

### D003 - Derive and summarize content instead of copying source text

**Status:** Accepted  
**Date:** 2026-08-30

**Decision**

Use `WenyuChiou/awesome-agentic-ai-zh` as the planning reference for the learning structure, but summarize and reorganize the content rather than copying substantial source text verbatim. The webpage should visibly acknowledge the source.

**Reason**

The goal is to produce a concise learning roadmap tailored to this project while preserving clear attribution.

**Consequences / Constraints**

- Keep roadmap descriptions concise and original.
- Include a visible source/reference area on the finished webpage.
- Do not reproduce large sections of the source README.

---

### D004 - Use a roadmap-oriented single-page presentation

**Status:** Accepted  
**Date:** 2026-08-30

**Decision**

Use a single-page layout with clear sequential roadmap/timeline-style visual hierarchy.

**Reason**

The primary content is a learning progression, so a roadmap-oriented presentation communicates sequence better than an ordinary article layout.

**Consequences / Constraints**

- Keep navigation and interaction lightweight.
- The layout should remain readable on both desktop and mobile.
