# T003 - Final UI and interaction polish

**Status:** READY  
**Created:** 2026-08-30

## Goal

Polish the completed Agent Learning Roadmap webpage into a clear, responsive, accessible, and visually finished static page without changing the approved six-stage learning content or introducing unnecessary dependencies.

## Context

T001 created the static webpage foundation. T002 added the complete approved six-stage Agent learning roadmap and source attribution.

Before implementation, read:

- `AGENTS.md`
- `docs/PROJECT.md`
- `docs/DECISIONS.md`
- `tasks/completed/T001-initialize-webpage.md`
- `tasks/completed/T002-add-agent-roadmap.md`

Relevant decisions: D001, D002, D003, and D004.

This is the final planned implementation task for the current `workflow-test` project scope. After T003 is accepted, the project should proceed to final project/workflow review rather than adding new feature scope by default.

## Scope

### Must do

- Improve the overall visual hierarchy of the existing page while preserving its approved content.
- Refine the hero/header area, stage headings, descriptions, topic labels, spacing, typography, and section rhythm for easier scanning.
- Strengthen the visual sense of progression from Stage 1 through Stage 6 without turning the page into a complex diagram.
- Add sensible lightweight hover and keyboard-focus states where appropriate.
- If motion or entrance effects are used, keep them lightweight and respect `prefers-reduced-motion`.
- Improve responsive behavior for desktop, tablet, and narrow mobile widths, including approximately 320px wide screens.
- Prevent unintended horizontal scrolling or clipped roadmap content.
- Preserve or improve semantic HTML and keyboard accessibility.
- Ensure external links have clear interaction feedback and appropriate safe behavior when opening a new tab.
- Review CSS and JavaScript for obvious unused placeholders, duplication, or unnecessary code introduced during T001/T002; clean them only when doing so is safe and directly supports final polish.
- Keep the existing static-site approach and reuse the current structure where reasonable.

### Must not do

- Do not change the approved six-stage roadmap structure or learning topics unless required to fix an obvious presentation typo.
- Do not add new learning stages or perform new roadmap research.
- Do not introduce React, Vue, Bootstrap, Tailwind, npm, or another framework/build system.
- Do not add a backend, database, authentication, search system, or unrelated product feature.
- Do not add third-party libraries solely for visual effects.
- Do not perform broad architectural refactoring unrelated to UI polish.
- Do not change accepted decisions in `docs/DECISIONS.md`.

## Acceptance Criteria

- [ ] The six approved roadmap stages and their core content remain intact and in the correct order.
- [ ] The page has a clear visual hierarchy and looks intentionally finished rather than like a scaffold.
- [ ] The progression from Stage 1 to Stage 6 is visually easy to follow.
- [ ] Hover and keyboard-focus states are clear where applicable.
- [ ] Any motion respects `prefers-reduced-motion`.
- [ ] The page remains readable and usable at common desktop, tablet, and mobile widths, including approximately 320px.
- [ ] No unintended horizontal page scrolling or clipped primary content is present at the tested widths.
- [ ] The GitHub source attribution remains visible and functional.
- [ ] External links that open a new tab use appropriate safe attributes.
- [ ] Browser developer tools show no missing local assets or JavaScript errors.
- [ ] No framework, package manager, backend, or unnecessary third-party dependency is introduced.
- [ ] The final diff contains no unrelated feature or architecture changes.

## Verification

- Open `index.html` in a browser and review the full page visually.
- Verify all six stages and source attribution remain present and correct.
- Test representative desktop, tablet, mobile, and approximately 320px viewport widths.
- Check for horizontal overflow and clipped content.
- Test keyboard focus on interactive elements.
- Verify hover states with a pointer device where available.
- If animation/motion is present, test or inspect the `prefers-reduced-motion` behavior.
- Verify external source links still open correctly and safely.
- Confirm browser developer tools show no missing local assets or JavaScript errors.
- Review the final diff for unrelated changes or unnecessary dependencies.

## Delivery

Implement this task on a dedicated branch and open a Pull Request to `main` for human review. Do not merge the Pull Request yourself.

## Notes

T003 is the final planned implementation task for the current test project. After acceptance, perform project-state cleanup and a separate retrospective of the ChatGPT -> GitHub -> Codex -> PR workflow before deciding which lessons should be incorporated into `workflow_freamwork v2`.
