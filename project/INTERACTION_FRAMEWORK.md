# INTERACTION FRAMEWORK — v1

The manuscript is interactive by design (sign in ink, bag your own beans, count your
own finger gaps, play the game show, answer Zib). For video, each interactive page
device is transformed into a screen-native interaction. This file defines the
vocabulary; detailed timing and placement belong to Gate 3 (beat sheet) and later.

## Interaction types

Every scene that adapts an interactive manuscript moment must declare exactly one
primary type (secondary types allowed where noted):

| Type | Definition | Manuscript precedents |
|---|---|---|
| `PREDICTION` | Audience commits to an answer before the reveal ("sign it — ink means you mean it"). | pp.2–3 YES/NO box; p.8 blank suspect card; p.9 draw your prediction arrow |
| `PAUSE` | Explicit invitation to stop and try physically (beans, fingers, sweets). | p.4 bag thirteen beans; p.11 count your gaps/segments; p.15 split sweets |
| `COUNTDOWN` | Timed beat giving the audience space to compute before the answer lands. | p.5 market quick-fire; p.20 challenge two; p.21 Zib's 34 |
| `AUDIENCE-QUESTION` | A question addressed straight to the viewer, answered later in the film. | p.3 "would ten win again?"; p.12 "who turned it to ten?" |
| `VISUAL-PUZZLE` | The answer is visible on screen for those who look (no verbal prompt needed). | p.1 hidden tens in the bedroom; p.17 hunt 60/60/360 in your day |
| `REVEAL` | The payoff moment; earlier interactions cash out here. Staged cinematically. | p.13 hands reveal; p.11 "even the exceptions were hands" |

## Declaration format (for future scene files)

```yaml
interaction:
  type: PREDICTION            # one primary type
  secondary: [PAUSE]          # optional
  manuscript_page: 2
  prompt: "Is ten actually special? YES or NO."
  payoff_scene: <scene-id>    # where it cashes out (required for PREDICTION / AUDIENCE-QUESTION)
  fallback: passive           # how the beat plays if the viewer doesn't engage
```

## Rules

1. Every `PREDICTION` and `AUDIENCE-QUESTION` must name its payoff scene — no dangling setups.
2. Interactions are **selective** (approved working assumption): the film must play as a
   satisfying linear experience even if the viewer never engages (`fallback: passive`).
3. Physical `PAUSE` actions must use audience-available objects (hands, everyday items),
   as the manuscript does.
4. Interaction depth overall (linear vs platform-interactive) is **OD-3** — undecided.
   Do not build branching structures until it is resolved.
