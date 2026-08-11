# SOURCE OF TRUTH

## Authority hierarchy

When artifacts disagree, higher wins:

1. **The manuscript** — `manuscript/Why-Ten-Manuscript-v1.pdf` + `manuscript/manuscript-v1.md`
   (same text, two formats; cite by page: `PAGE 1` … `PAGE 24`).
2. **Explicit user approvals and decisions** — recorded in `project/DECISION_LOG.md`.
3. **Approved gate artifacts** — story architecture, beat sheet, screenplay, bibles, etc.,
   each marked APPROVED at its gate.
4. **Working drafts** — anything not yet gate-approved.

## What the manuscript governs

Story, characters, narrative, facts, mathematical concepts, sequence of discovery,
historical references, terminology, learning objectives, major reveals, ending,
intellectual intent, storytelling voice.

## Deviation labels

Any departure from or addition to the manuscript must be explicitly labelled:

- **PROPOSED ADAPTATION** — a change needed for the film medium, awaiting approval.
- **OPEN DECISION** — a fork the user must choose; work must not assume an answer.
- **EXTERNAL RESEARCH REQUIRED** — a claim that needs sourcing beyond the manuscript
  (goes through the historical/mathematical QA frameworks).
- **SOURCE GAP** — something the manuscript references but does not contain.

All four are recorded in `project/DECISION_LOG.md`.

## Known source gaps (as of Gate 1)

- **SG-1:** The back matter (answer key with "where your bags most likely leaked" notes for
  pp.4, 5, 19, 20, 21; two further challenge sets; loop schedule) is *specified* on p.24's
  back-matter note but its contents are not included in Manuscript v1.
- **SG-2:** The manuscript front matter cites its approved blueprint,
  `docs/design-notes/02-why-base-ten-blueprint.md`, which lives in the author's separate
  "STEM project" folder and is not part of this repository. If blueprint-level intent is
  needed, request it explicitly — do not reconstruct it from memory.
- **SG-3:** The manuscript is #2 in a series; #1 (*The Mystery of Ten*) and #3
  (*The Machine That Counts to Two*) are referenced but not available here.

## Immutability

Files in `manuscript/` are never edited. New versions arrive as new files with a
decision-log entry. Everything downstream cites the manuscript by page number so
claims stay checkable.
