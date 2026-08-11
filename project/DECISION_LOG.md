# DECISION LOG

Chronological record of decisions, adaptations, gaps, and open questions.
Entry types: **DECISION** (approved), **PROPOSED ADAPTATION**, **OPEN DECISION**,
**EXTERNAL RESEARCH REQUIRED**, **SOURCE GAP**, **STRUCTURE CHANGE**.

---

## 2026-08-11 — Gate 1: Project initialization

### D-1 · DECISION — Repository established
Cloned `https://github.com/RPK-GIT/WhyTen.git` (contained only a stub README) and
built the production structure per the initialization brief.

### D-2 · DECISION — Manuscript imported as immutable source
`Why-Ten-Manuscript-v1.pdf` and its text source `manuscript-v1.md` copied unmodified
from the author's local folder
`My AI Agent projects/STEM project/manuscript/book-02-why-ten/` into `manuscript/`.
Both files are the same manuscript; the markdown enables page-cited text search.

### D-3 · STRUCTURE CHANGE — Additions to the suggested layout
Beyond the brief's structure, the following were added, each with a reason:
- `CLAUDE.md` (repo root) — auto-loaded operating rules for future Claude Code sessions,
  pointing to `project/MASTER_CONTEXT.md` first (brief §16 rules need to be discoverable).
- `project/INTERACTION_FRAMEWORK.md` — brief §11 requires an interaction framework; given
  it governs future scene files, it lives with the other project frameworks.
- `qa/mathematics/MATH_QA_FRAMEWORK.md` and `qa/historical/HISTORICAL_QA_FRAMEWORK.md` —
  brief §§9–10 frameworks placed inside their QA folders.
- `visual/visual-style/VISUAL_WORLDS.md` — brief §7 structural classification.
- `assets/ASSET_STRATEGY.md` — brief §8 reuse architecture.
- `manuscript/README.md` — provenance + immutability rules.
- `.gitkeep` files in empty production folders so the structure is versioned.

### D-4 · DECISION — Approved working assumptions v1
Recorded in `project/MASTER_CONTEXT.md` §14 (duration ≈22 min, character-led,
ages 11–15 core audience, four visual worlds, reusable assets, selective interaction).
Working assumptions, not immutable requirements.

### SG-1 · SOURCE GAP — Back matter not included
Manuscript p.24 specifies back matter (answer key, "leak" notes for pp.4, 5, 19, 20, 21,
challenge sets, loop schedule) that is not present in Manuscript v1. Until supplied,
reader-challenge answers in the maths QA registry are marked DERIVED, not manuscript-confirmed.

### SG-2 · SOURCE GAP — Blueprint not in repository
Front matter cites `docs/design-notes/02-why-base-ten-blueprint.md` (lives in the
separate "STEM project" folder). Request it explicitly if blueprint-level intent is needed.

### SG-3 · SOURCE GAP — Companion books unavailable
*The Mystery of Ten* (#1) and *The Machine That Counts to Two* (#3) are referenced
(pp.4, 20, 23) but not available here.

### OD-1 · OPEN DECISION — Series references in a standalone episode
Keep the pp.4/20/23 references as series hooks, adapt into self-contained lines, or drop?

### OD-2 · OPEN DECISION — Supply back matter (resolves SG-1)
Provide the answer key / challenge sets, or approve DERIVED answers computed and
verified within the maths QA framework.

### OD-3 · OPEN DECISION — Interaction depth for video
Linear film with prediction/pause moments vs. platform-interactive branching.
Affects Gate 3 beat sheet. Framework supports both (`project/INTERACTION_FRAMEWORK.md`).

### OD-4 · OPEN DECISION — Large media storage strategy
Repo is the canonical backup; renders/audio will be large binaries. Adopt Git LFS
before Gate 8, or keep heavy media external with manifests? Decide before storyboards.

### OD-5 · OPEN DECISION — The reader's blank suspect card (p.8) and blank badge line (p.24)
The manuscript hands authorship moments to the reader. Decide the film equivalent
(direct-address beat, pause prompt, or visual invitation).

### PA-1..PA-3 · PROPOSED ADAPTATIONS — Act ordering vs manuscript page order
Recorded in `project/STORY_ARCHITECTURE.md` (game-show placement, p.18 placement,
interaction transformation). To be resolved at Gates 2–3.
