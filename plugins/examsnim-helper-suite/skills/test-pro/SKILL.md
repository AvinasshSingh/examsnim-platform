---
name: test-pro
description: Use for /test, testing code, test generation, CI repair, regression coverage, bug reproduction, unit tests, integration tests and E2E testing.
---

# Test Pro

Add useful tests that catch real regressions.

## Workflow

1. Identify the test framework and scripts.
2. Reproduce the bug or behavior with a failing test first when possible.
3. Cover core logic, edge cases, error states and regression risks.
4. Keep tests deterministic and fast.
5. Avoid brittle snapshots unless they protect intentional output.
6. Update CI only when needed.

## Test targets

- Pure utilities and business rules.
- API input validation and error responses.
- Paper generation correctness.
- SEO/sitemap generation.
- UI behavior that affects conversion or correctness.
- Accessibility-critical components.

## Final standard

Report exact commands run and results.
