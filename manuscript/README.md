# Manuscript — Immutable Source Material

This folder contains the authoritative source of truth for the entire production.

| File | Role |
|---|---|
| `Why-Ten-Manuscript-v1.pdf` | The supplied manuscript **Why-Ten-Manuscript-v1** (authoritative source). |
| `manuscript-v1.md` | The plain-text source of the same manuscript, imported alongside the PDF for searchability and citation by page number. |

## Provenance

Both files were imported on 2026-08-11 from the author's local folder
`My AI Agent projects/STEM project/manuscript/book-02-why-ten/`.
The markdown is the text source from which the PDF was built (`build_pdf.py` in the
same origin folder); the two are the same manuscript in two formats.

The manuscript's front matter references its approved blueprint,
`docs/design-notes/02-why-base-ten-blueprint.md`, which lives in the origin project
and is **not** part of this repository. Recorded in `project/SOURCE_OF_TRUTH.md`.

## Rules

1. **Do not modify these files.** They are immutable source material.
2. All creative work cites the manuscript by page number (`PAGE 1` … `PAGE 24`).
3. Any deviation from the manuscript must be recorded in `project/DECISION_LOG.md`
   and labelled PROPOSED ADAPTATION, OPEN DECISION, EXTERNAL RESEARCH REQUIRED, or SOURCE GAP.
4. New manuscript versions, if ever supplied, are added as new files (e.g. `manuscript-v2.md`) —
   never overwritten — with the change recorded in the decision log.
