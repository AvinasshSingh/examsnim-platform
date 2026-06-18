# AGENTS.md — ExamsNim Codex Helper Instructions

## Mission

Use this repository as the Codex helper-plugin home for ExamsNim. The goal is to give Codex reusable helper modes for memory, code instructions, multi-agent review, SEO, testing, sitemap, UI/UX Pro Max, motion UI, performance, security and ExamsNim platform work.

## Default Codex behavior

1. Read this file and `docs/codex-memory.md` before major work.
2. Prefer small, safe, reviewable changes.
3. Preserve user data and avoid destructive operations unless explicitly requested.
4. Run available tests, lint, type checks and build checks when possible.
5. For frontend work, include accessibility, responsive design, loading states, empty states, error states and reduced-motion behavior.
6. For SEO work, check metadata, canonical URLs, robots.txt, sitemap.xml, structured data where useful and index safety.
7. For ExamsNim paper features, preserve correctness, scoring integrity, traceability and auditability.

## Helper skills

Use these custom helper skills when the user invokes the matching wording:

- `$superpower` for end-to-end planning, implementation, review and testing.
- `$uiux-pro-max` for UI/UX, premium frontend polish, accessibility and motion UI.
- `$seo-sitemap-pro` for SEO, robots.txt, sitemap.xml, metadata and indexing checks.
- `$test-pro` for test generation, regression coverage and CI repair.
- `$memory-pro` for durable memory and repo instruction updates.
- `$multi-agent-squad` for parallel specialist Codex review.
- `$code-review-pro` for maintainability, refactor and bug review.
- `$security-pro` for safe defensive security review.
- `$performance-pro` for speed, Core Web Vitals, API and database performance.
- `$examsnim-pro` for ExamsNim product, backend and paper-engine correctness.
- `$deploy-pro` for production readiness and release safety.

## Slash-style aliases

If the user writes `/superpower`, `/ui/ux pro max`, `/seo`, `/sitemap`, `/test`, `/memory`, `/agents`, `/security`, `/performance`, `/examsnim`, `/deploy`, or similar, interpret it as a request to use the closest helper skill. These are prompt aliases for the skills, not native Codex slash commands.

## Output checklist

Before finishing a task, report:

- What changed.
- Files touched.
- Checks/tests run.
- Remaining risks or follow-ups.
