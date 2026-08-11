# WHY TEN? — Claude Code operating rules

Production repository for *The Great STEM Mysteries — Mystery #2: Why Ten?*,
an animated educational mystery film.

## Read order (every session)

1. `project/MASTER_CONTEXT.md` — authoritative working context. Read it first.
2. `project/PROJECT_STATUS.md` — current gate and what's blocked.
3. The relevant source/approved artifact for the task at hand, before modifying it.

## Rules

1. The manuscript in `manuscript/` is **immutable source material** — never edit it.
2. Do not silently change approved decisions; changes go through `project/DECISION_LOG.md`.
3. Distinguish source facts from adaptation decisions using the labels in
   `project/SOURCE_OF_TRUTH.md` (PROPOSED ADAPTATION / OPEN DECISION /
   EXTERNAL RESEARCH REQUIRED / SOURCE GAP).
4. Keep creative decisions traceable — cite manuscript pages.
5. Mathematics on screen must validate against `qa/mathematics/MATH_QA_FRAMEWORK.md`.
6. Historical claims must carry markers per `qa/historical/HISTORICAL_QA_FRAMEWORK.md`.
7. Prefer reusable assets (`assets/ASSET_STRATEGY.md`) over one-off generations.
8. Respect the gates (`project/APPROVAL_GATES.md`): do not generate downstream artifacts
   before the current gate is approved, and never advance a gate without explicit instruction.
9. Avoid unnecessary complexity; this is a documentation-and-assets repo, not an app.
10. Never commit secrets, credentials, API keys, `.env` files, tokens, or
    machine-specific configuration — and never put secrets in docs, prompts, or scripts.
11. Inspect repository state before modifying files; don't overwrite existing work unnecessarily.
12. **GitHub sync is mandatory:** after every completed task that changes project files —
    review status/diff, check for secrets, stage, commit with a meaningful message, push to
    `https://github.com/RPK-GIT/WhyTen.git` (default branch `main`), verify the push, and
    report the commit SHA. Never claim a sync succeeded without verifying it.
13. End every task by reporting: what was created, what changed, what remains pending,
    and what approval is required before continuing.
