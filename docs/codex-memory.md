# Codex Memory — ExamsNim

Last updated: 2026-06-18

## Product memory

ExamsNim is an exam-prep platform. The repo needs Codex helpers for paper generation, testing workflows, SEO, sitemap checks, UI/UX, motion UI, and reliable learner/admin experiences.

## Repository goals

- Keep Codex helper plugins in GitHub.
- Maintain reusable helpers for `/superpower`, `/ui/ux pro max`, SEO, sitemap, testing, memory, multi-agent review, security, performance, deployment and ExamsNim-specific work.
- Make the repo installable as a Codex plugin marketplace.

## Stable conventions

- Keep product logic explicit and testable.
- Prioritize correctness over flashy UI.
- Use safe motion and respect `prefers-reduced-motion`.
- Treat SEO as code: test sitemap, robots and metadata behavior.
- Keep memory updates concise and dated.
- Never store secrets, tokens or private credentials in repo memory.
