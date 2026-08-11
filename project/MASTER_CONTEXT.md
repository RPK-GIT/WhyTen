# MASTER CONTEXT — THE GREAT STEM MYSTERIES: WHY TEN?

**Read this file first in every working session.**
It is the authoritative working context for the production. When it conflicts with
memory or assumption, this file (and the manuscript it points to) wins.

---

## 1. Project identity

- **Series:** The Great STEM Mysteries
- **Episode:** Mystery #2 — *Why Ten?* (The Number That Has Been Following You)
- **Form:** Cinematic animated STEM mystery — a single self-contained episode
- **Repository:** https://github.com/RPK-GIT/WhyTen.git (canonical backup and version history)
- **Status tracking:** `project/PROJECT_STATUS.md` · **Gates:** `project/APPROVAL_GATES.md` · **Decisions:** `project/DECISION_LOG.md`

## 2. Source of truth

The manuscript in `manuscript/` (**Why-Ten-Manuscript-v1**, 24 pages, PDF + markdown)
is the authoritative source for story, characters, facts, mathematics, history,
terminology, sequence of discovery, reveals, ending, and voice.
See `project/SOURCE_OF_TRUTH.md` for the full authority hierarchy and citation rules.

Never silently change the manuscript's meaning or add unsourced factual claims.
Deviations must be labelled **PROPOSED ADAPTATION**, **OPEN DECISION**,
**EXTERNAL RESEARCH REQUIRED**, or **SOURCE GAP**, and logged in `project/DECISION_LOG.md`.

## 3. Creative objective

Adapt the interactive manuscript into a character-led animated mystery film in which
the audience investigates alongside Nia and Sam and *discovers* — rather than is told —
that base ten is a human convention, not a mathematical necessity.

- **Core takeaway:** *"We count in tens because we count on our hands."* (manuscript p.13)
- **Deeper takeaway / reusable lens:** *"Did the universe insist, or did we?"* (pp.16, 24)
- The viewer should leave with a transferable habit: sorting claims into
  **necessity** vs **convention**, and demanding that a hypothesis make a prediction (p.9).

## 4. Target audience

- Manuscript-specified core audience: **ages 11–15** (manuscript front matter).
- Production intent: school-age audience with genuine adult appeal.
- Tone: playful detective mystery — never a narrated slideshow, never a conventional maths lesson.

## 5. Characters

Full character bibles are a later gate (`visual/character-bible/`). Foundation:

### Nia
Curious, observant, imaginative. Notices patterns, asks the questions that "ruin afternoons."
An active investigator, never a passive student. Signature question: **"What if…?"**
Manuscript anchors: notices ten following her (p.1); poses the reset-the-world question (p.3);
names and draws Pentaria (p.4); runs the game show (p.19). She/her.

### Sam
Skeptical, analytical, evidence-driven. "Never believed anything without proof" (p.2).
Demands testability; checks Pentarian arithmetic against ordinary maths expecting it to snap (p.5);
crosses out his own YES "like an apology" (p.6). Signature question: **"How would we know?"**
Delighted, not embarrassed, to be proven wrong (p.18). He/him.

### Zib
Friendly eight-fingered alien (four fingers per hand, p.21). Writes in base eight;
owns 34₈ gleeps of treasure. Appears late as the audience's final application of base conversion.

### The dynamic
Nia and Sam together model scientific thinking: guess in ink, predict, test, hunt evidence,
accept being wrong as the road to discovery. Their relationship is natural, playful, believable —
never two people reading a textbook at each other.

## 6. Story premise

A number has been following you your whole life. Nia and Sam put ten on trial:
they build a world where ten never existed (Pentaria, base five), prove mathematics
doesn't care, run a detective case with suspects and predictions, follow anthropological
evidence to five/ten/twenty clusters, crack the exceptions (Yuki eight = finger gaps;
Babylon sixty = 12 finger segments × 5), and reveal the culprit was at the end of
every human arm all along. Then the deeper lesson: necessity vs convention, why twelve
might have been better, why Babylon still lives on your wrist, how Zib and computers
turn the same dial — and a lens the viewer keeps forever.

## 7. Core story architecture

Approved at Gate 2 candidate level in `project/STORY_ARCHITECTURE.md` — eleven acts
(Mystery → Break Ten → Detective Case → Evidence → Answer → Necessity vs Convention →
The Better Number → Old Choices Survive → Zib → Binary → The Lens), each mapped to
manuscript pages. The architecture file is the working source; do not restate it from memory.

## 8. Visual worlds

Four structural categories (classification only — no final designs yet;
see `visual/visual-style/VISUAL_WORLDS.md`):

1. **REAL WORLD** — Nia's bedroom, school, streets, clocks, phones, everyday tens.
2. **IMAGINED WORLD** — Pentaria and conceptual spaces the characters invent.
3. **HISTORICAL WORLD** — Babylon, ancient civilisations, anthropological investigation.
4. **ABSTRACT MATHEMATICAL WORLD** — base dial, grouping/carrying, number representations, binary, necessity/convention bins.

## 9. Production philosophy

- Character-led, not narrator-led. Mathematics demonstrated visually, not over-explained verbally.
- Cinematic mystery pacing; the p.13 reveal is the emotional summit and is treated as such.
- Interactive manuscript moments transform into screen-native interaction
  (see `project/INTERACTION_FRAMEWORK.md`).
- Iterative gated development: no gate is advanced without explicit approval
  (`project/APPROVAL_GATES.md`).
- Reusable assets over one-off generations (`assets/ASSET_STRATEGY.md`).
- Everything traceable: source fact → adaptation decision → artifact.

## 10. Mathematical accuracy requirements

All on-screen mathematics must validate against the controlled registry in
`qa/mathematics/MATH_QA_FRAMEWORK.md` (visual representation, terminology, notation,
calculation, narration, on-screen text). Manuscript examples are canonical;
ambiguities are filed as issues, never silently corrected. Bases in scope:
2, 5, 8, 10, 12, 20, 60, plus grouping, carrying, and base conversion.

## 11. Historical accuracy requirements

All historical references (Babylon, Maya, Egypt, China, India, Rome, Yuki people of
California, anthropological evidence) follow `qa/historical/HISTORICAL_QA_FRAMEWORK.md`.
Every historical claim carries one of four markers: manuscript-supported fact,
externally researched fact (approved), proposed visual interpretation, or
unresolved historical question. No unsourced historical embellishment.

## 12. Approval-gate workflow

Thirteen gates, Gate 1 (initialization) through Gate 13 (final render), defined in
`project/APPROVAL_GATES.md`. **Never advance to the next gate automatically.**
Every task ends by reporting: what was created, what changed, what is pending,
and what approval is required.

## 13. Asset-reuse philosophy

Recurring characters (Nia, Sam, Zib), environments (bedroom, school, Pentaria,
detective board, Babylon, abstract spaces) and props (hands, bags, beans, clock,
phone, number graphics, base dial, necessity/convention bins, detective badge)
are built once as canonical reusable assets and referenced everywhere.
See `assets/ASSET_STRATEGY.md`.

## 14. Approved working assumptions — v1

Recorded 2026-08-11 (Gate 1). Working assumptions, not immutable requirements;
changes go through the decision log.

1. Single self-contained episode.
2. Target duration ≈ 22 minutes; acceptable working range ≈ 18–25 minutes.
3. Cinematic animated mystery; character-led rather than narrator-led.
4. Audience: ages 11–15 core (per manuscript), with school-age reach and adult appeal.
5. Interactive learning moments used selectively (transformed for video per the interaction framework).
6. Mathematics demonstrated visually rather than excessively explained verbally.
7. Four visual worlds as classified in §8.
8. Reusable-asset architecture as in §13.
9. English language production (manuscript language).

## 15. Open decisions

Live list maintained in `project/DECISION_LOG.md`. As of Gate 1:

- **OD-1 — Series references.** The manuscript references a previous book (*The Mystery of Ten*, pp.4, 20)
  and a next one (*The Machine That Counts to Two*, p.23). How should a standalone episode handle these:
  keep as light series hooks, adapt into self-contained lines, or drop?
- **OD-2 — Back-matter answer key (SOURCE GAP).** The manuscript's back matter (answer key,
  "where your bags most likely leaked", challenge sets) is specified but not included in v1.
  Needed before the maths QA registry can mark reader-challenge answers as manuscript-confirmed.
- **OD-3 — Interaction depth.** How far video interaction goes (pure linear film with pause
  prompts vs. platform-interactive) — affects the beat sheet.
- **OD-4 — Large media storage.** Whether to adopt Git LFS before binary-heavy gates (8+),
  since the repo is the canonical backup.
- **OD-5 — Fifth suspect.** Manuscript p.8 leaves a blank suspect card "for the reader."
  How the film handles the reader-authored suspect moment.
