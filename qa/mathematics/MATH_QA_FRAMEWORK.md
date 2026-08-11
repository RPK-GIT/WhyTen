# MATHEMATICS QA FRAMEWORK — v1

Every scene containing mathematics must pass validation against this framework
before storyboard (Gate 8) and again at QA (Gate 12). Manuscript examples are
canonical; ambiguities are filed as issues, never silently corrected.

## Scope

Grouping, carrying, base 2, base 5, base 8, base 10, base 12, base 20, base 60,
and base conversion.

## Validation checklist (per mathematical scene)

Each scene is checked on all six axes:

1. **Visual representation** — do the on-screen objects (beans, bags, dial, switches)
   actually depict the stated quantity and operation?
2. **Terminology** — matches the manuscript's controlled vocabulary (below).
3. **Notation** — digits, positional layout, and any base-marking convention are consistent
   film-wide (base-marking convention to be fixed at Gate 5 — see issues).
4. **Calculation** — every computation independently re-derived and confirmed.
5. **Narration** — spoken words claim exactly what the maths shows, no more.
6. **On-screen text** — matches notation rules and the verified calculation.

Record results as one row per scene in `qa/mathematics/` scene check files (from Gate 3 onward).

## Controlled vocabulary (manuscript terms)

| Term | Manuscript meaning | Page |
|---|---|---|
| bag / bagging | grouping units into groups of the base size; "bags first, loose ones after" | 4, 12 |
| loose | ungrouped units after bagging | 4–5 |
| carry / snap shut | a bag closing when a group fills during addition | 5, 19 |
| base | the size of everyone's bag | 16 |
| bedrock / necessity | what no civilisation can escape (grouping itself) | 12, 16 |
| dial / convention | the chooseable bag size | 12, 16 |
| the base dial | dial marked 2 · 5 · 8 · 12 · 20 · 60, pointer on 10 | 12 |

## Canonical example registry

Source status: **M** = manuscript-stated result · **D** = derived (verified here;
manuscript poses the challenge but the answer key is missing — see SG-1).

| ID | Page | Example | Result | Status | Verified |
|---|---|---|---|---|---|
| MX-01 | 4 | 13 beans in bags of five | 2 bags, 3 loose → **23₅** | M | ✓ 2×5+3=13 |
| MX-02 | 5 | 4 loose + 3 loose (base 5) | 1 bag, 2 loose → **12₅** (our 7) | M | ✓ |
| MX-03 | 5 | 3 + 4 (base 5, reader challenge) | **12₅** | D | ✓ same as MX-02 |
| MX-04 | 5 | 14₅ + 3 (reader challenge) | **22₅** | D | ✓ 9+3=12=2×5+2 |
| MX-05 | 15 | 12 split among 2 / 3 / 4 | 6 / 4 / 3 — clean | M | ✓ |
| MX-06 | 15 | 10 split among 2 / 3 / 4 | 5 / uneven / uneven | M | ✓ |
| MX-07 | 11, 17 | Babylonian sixty from hands | 12 segments × 5 fingers = 60 | M | ✓ |
| MX-08 | 17 | Full turn | 360° = 6 × 60 | M | ✓ |
| MX-09 | 11 | Yuki eight from finger gaps | 4 gaps per hand × 2 = 8 | M | ✓ |
| MX-10 | 19 | Our six in Pentarian | **11₅** | M | ✓ 1×5+1=6 |
| MX-11 | 20 | 13 beans, bags of five | **23₅** | M | ✓ (= MX-01) |
| MX-12 | 20 | 28 beans, bags of ten | **28** | M | ✓ |
| MX-13 | 21 | Zib's 34₈ in base ten | **28** | D | ✓ 3×8+4=28 |
| MX-14 | 19 | Game show statements 1–5 | 1 convention · 2 necessity · 3 convention · 4 convention · 5 necessity | M(1,answers implied)/D | see note |

**MX-14 note:** p.19 confirms statement 1 is convention ("ten's shoe… a law's uniform")
and the manuscript's own framework (pp.12, 16) implies the rest; full answers are in
the missing back matter (SG-1). Marked D until back matter is supplied (OD-2).

## Issues (open)

- **MQ-1:** Base-notation convention for on-screen text (subscripts like 23₅ vs.
  the manuscript's contextual "their 23") must be fixed at Gate 5 and used film-wide.
  The manuscript itself never uses subscripts — a film convention is a PROPOSED ADAPTATION.
- **MQ-2:** MX-14 answers pending back matter (SG-1 / OD-2).

## Rules

1. No mathematical example may appear on screen without a registry entry (existing or added).
2. New examples not in the manuscript are allowed only if they follow manuscript method
   (bags-and-loose, dial) and are verified here first; mark status **NEW**.
3. If a manuscript example is ambiguous, file an MQ issue — do not silently repair it.
4. Every base conversion shown must be re-derivable by the audience using only
   techniques the film has already demonstrated (the manuscript's own constraint, p.21).
