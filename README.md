# WHY TEN?

**The Great STEM Mysteries — Mystery #2: The Number That Has Been Following You**

Production repository for a cinematic animated STEM mystery (~22 min) in which
Nia and Sam put the number ten on trial — and discover that we count in tens
because we count on our hands.

## Repository map

| Path | Contents |
|---|---|
| `manuscript/` | **Immutable source of truth** — Why-Ten-Manuscript-v1 (PDF + text) |
| `project/` | Master context, source-of-truth rules, story architecture, approval gates, decision log, status, interaction framework |
| `story/` | Beat sheet, screenplay, dialogue (Gates 3–4) |
| `visual/` | Visual worlds, character/environment bibles, style, storyboards (Gates 5–8) |
| `assets/` | Reusable asset strategy and asset library (Gate 7+) |
| `scenes/` | Per-scene production files |
| `prompts/` | Approved generation prompts (image / video / voice / music, Gate 10) |
| `audio/`, `video/`, `animatic/`, `final/` | Production outputs (Gates 9–13) |
| `qa/` | Mathematics, historical, visual, and final QA frameworks and sign-offs |

## Working on this repo

Start with `CLAUDE.md` (operating rules) and `project/MASTER_CONTEXT.md`
(authoritative context). Development is gated — see `project/APPROVAL_GATES.md`.
Current state: `project/PROJECT_STATUS.md`.
