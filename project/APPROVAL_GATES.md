# APPROVAL GATES

Development is iterative and gated. **No gate advances without explicit user approval.**
Every completed task reports: what was created, what changed, what remains pending,
and what approval is required before continuing.

| Gate | Stage | Primary artifacts | Status |
|---:|---|---|---|
| 1 | Project initialization | Repo structure, master context, frameworks, this file | ✅ COMPLETE — 2026-08-11 (this commit) |
| 2 | Story architecture | `project/STORY_ARCHITECTURE.md` approved | ⏳ DRAFT SUBMITTED — awaiting approval |
| 3 | Detailed story beat sheet | `story/beat-sheet/` | Not started |
| 4 | Screenplay | `story/screenplay/`, `story/dialogue/` | Not started |
| 5 | Visual bible | `visual/visual-style/` | Not started |
| 6 | Character bible | `visual/character-bible/` | Not started |
| 7 | Asset architecture | `assets/` populated per `assets/ASSET_STRATEGY.md` | Not started |
| 8 | Storyboard | `visual/storyboards/` | Not started |
| 9 | Animatic | `animatic/` | Not started |
| 10 | Production prompts/assets | `prompts/`, generated assets | Not started |
| 11 | Animation assembly | `video/`, `scenes/` | Not started |
| 12 | QA | `qa/` sign-offs (mathematics, historical, visual, final) | Not started |
| 13 | Final render | `final/` | Not started |

## Gate rules

1. A gate's artifacts are drafted, reviewed, and only then marked APPROVED with a date
   and a decision-log entry.
2. Approved artifacts are not silently changed. Revisions after approval require a new
   decision-log entry and re-approval of what changed.
3. Do not generate large volumes of downstream artifacts before the current gate is approved.
4. QA (mathematics, historical) applies continuously from Gate 3 onward, with formal
   sign-off at Gate 12.
