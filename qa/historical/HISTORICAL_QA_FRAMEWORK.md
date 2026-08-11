# HISTORICAL QA FRAMEWORK — v1

Governs every reference to real cultures, civilisations, and anthropology:
Babylon, Maya, Egypt, China, India, Rome, the Yuki people of California, and the
anthropological record of counting systems.

## Claim markers

Every historical claim in any artifact (beat sheet, screenplay, storyboard, narration,
on-screen text, visual design) carries exactly one marker:

| Marker | Meaning |
|---|---|
| `[MS p.N]` | **Manuscript-supported fact** — stated in the manuscript at page N. |
| `[EXT ref]` | **Externally researched fact** — sourced beyond the manuscript, with citation, explicitly approved before use. |
| `[VIS]` | **Proposed visual interpretation** — design choice (costume, architecture, artifact look) not asserted as fact; needs visual-bible approval. |
| `[UHQ]` | **Unresolved historical question** — flagged, not yet usable on screen. |

## Manuscript-supported historical claims (baseline register)

| ID | Claim | Page |
|---|---|---|
| H-01 | Babylonians counted in sixties, ~4,000 years ago; invented the minute | 2, 17 |
| H-02 | The Maya counted in twenties | 2 |
| H-03 | Computers count in twos | 2, 23 |
| H-04 | Egypt, China, India, Rome independently landed on base ten | 7 |
| H-05 | Anthropologists recorded counting systems of hundreds of cultures on every continent | 10 |
| H-06 | World counting systems cluster at fives, tens, twenties | 10 |
| H-07 | The Yuki people of California counted in eights, using the gaps between fingers | 11 |
| H-08 | Babylonian sixty connects to 12 finger segments × 5 fingers | 11 |
| H-09 | Babylonian base sixty survives in 60 s / 60 min / 360° | 17 |
| H-10 | Scholars historically argued ten was nature's perfect number; others argued counting spread from one civilisation | 18 |
| H-11 | Bakers' dozens reflect twelve's divisibility | 15 |
| H-12 | Base-change disputes were fought for centuries ("some are still fighting") | 15 |

These are what the film may assert *as coming from the manuscript*. Anything beyond
them — dates, names, imagery specifics (what a ziggurat, tablet, or Maya numeral
actually looked like) — requires `[EXT ref]` research + approval or a `[VIS]` design decision.

## Known sensitivity

The Yuki are a living Native Californian people. Depiction beyond the manuscript's
single counting fact (H-07) requires researched, approved treatment — mark `[UHQ]`
until then. No invented cultural detail.

## Workflow

1. Gate 3+: every historical beat lists its claims with markers.
2. `[EXT ref]` claims go through a research task: claim → sources → proposed wording →
   user approval → logged in `project/DECISION_LOG.md`.
3. `[VIS]` interpretations are approved at Gate 5/6 (visual/character bibles).
4. A scene ships only when it contains no unmarked or `[UHQ]` claims.
5. Scene check files accumulate in `qa/historical/` from Gate 3 onward.
