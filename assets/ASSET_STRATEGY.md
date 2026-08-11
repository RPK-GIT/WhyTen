# REUSABLE ASSET STRATEGY — v1

The production favours a small library of canonical, reusable assets over hundreds of
unrelated generations. Every recurring character, environment, and prop is designed
once (Gates 5–7), approved, and then *referenced* by every scene that uses it.

## Asset registry (foundation — design comes later)

### Characters (`assets/characters/`)
| Asset | Notes | Manuscript anchors |
|---|---|---|
| Nia | Protagonist; consistent across all four visual worlds | pp.1–24 |
| Sam | Co-lead; pen/notebook as signature props | pp.2–24 |
| Zib | Eight-fingered alien (four per hand); appears via letter/doodle first | p.21 |
| Pentarian citizens | One hand, five fingers; background population | pp.4–5 |

### Environments (`assets/environments/`)
| Asset | World | Manuscript anchors |
|---|---|---|
| Nia's bedroom | REAL (also hosts noir + game-show dressings) | pp.1, 7, 19, 24 |
| School | REAL | p.22 |
| Pentaria (market, streets) | IMAGINED | pp.4–5 |
| Detective board / corkboard | IMAGINED (recurring set piece) | pp.8, 9, 18, 24 |
| Babylon (ziggurat, night sky) | HISTORICAL | pp.2, 17 |
| Abstract mathematics spaces | ABSTRACT (dial machine, binary cathedral) | pp.12, 23 |

### Props (`assets/props/`)
| Asset | Notes | Manuscript anchors |
|---|---|---|
| Hands | The single most important visual motif; must read identically everywhere | pp.1, 11, 13, 24 |
| Bags | Snap-shut grouping bags, parameterized by base size (5, 10, 20, 60, 2) | pp.4–5, 12, 20 |
| Beans / berries | Countable units | pp.4–5, 20, 21 |
| Wall clock / wristwatch | Sixty's hiding place | pp.1–2, 17 |
| Phone | Binary's hiding place | pp.1, 23 |
| Number graphics | Digits, positional layouts, per-base numerals | throughout |
| Base dial | Brass dial marked 2 · 5 · 8 · 12 · 20 · 60, pointer on 10 | p.12 |
| Necessity / convention bins | Two painted wooden bins | pp.16, 24 |
| Detective badge | The closing artifact; blank third signature line | p.24 |
| YES/NO signature box | Set up p.2, cracks p.6, crossed out, re-signed p.24 | pp.2, 6, 24 |

### Mathematics visuals (`assets/mathematics/`)
Reusable animation components: bagging action, carry ("snap shut"), positional
notation build, base-conversion sequence, binary switch field. Each validated once
against `qa/mathematics/MATH_QA_FRAMEWORK.md`, then reused.

### `assets/reusable/`
Cross-cutting elements: transitions between visual worlds, recurring UI for
interaction moments (per `project/INTERACTION_FRAMEWORK.md`), title/typography components.

## Rules

1. A scene may not introduce a new recurring element without adding it to this registry.
2. Assets are versioned: `<asset>-v<N>` with the approved version noted here.
   Approved versions change only via the decision log.
3. Continuity props (YES/NO box, corkboard, badge) must track their story state —
   they change across the film and each state is an asset variant, not a redesign.
4. Restyling per visual world (e.g. hands in noir vs. abstract space) derives from the
   canonical asset; silhouette and proportions stay fixed.
