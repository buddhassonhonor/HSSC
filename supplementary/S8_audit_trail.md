# S8. Audit trail (compact)

## What this supplement is
This supplement operationalizes the manuscript’s transparency claim by providing:
- An explicit coding scheme (`S5_codebook.csv`) aligned with the mechanism-tracing protocol described in the manuscript.
- A reform-episode test-case matrix (`S6_reform_episode_matrix.csv`) aligned with the manuscript’s reform-wave discussion.
- Two indices to support traceability:
  - `S2_secondary_evidence_inventory.csv` (secondary peer-reviewed sources)
  - `S7_citation_index.csv` (where each citation occurs in `HSSC.TEX`)

## How files were produced
- `S2_secondary_evidence_inventory.csv` is exported from `references.bib` using `supplementary/tools/bib_to_csv.py`.
- `S7_citation_index.csv` is exported from `HSSC.TEX` using `supplementary/tools/extract_citations.py`.
- `S5_codebook.csv` and `S6_reform_episode_matrix.csv` are drafted directly from the manuscript’s “Materials and Analytic Strategy” and “Reform Absorption” sections to match the analytic constructs and test cases reported.

## Items that require author completion (because the manuscript does not enumerate them exhaustively)
- `S3_policy_documents_index.csv`: please fill exact policy document titles/issuing bodies/URLs and access dates used in the analysis.
- `S4_public_narratives_index.csv`: please fill the specific media reports/speeches/discourse items coded for semiotic imaginaries, with URLs and access dates.

## Recommended pre-submission checks
- Confirm that any pasted URLs are accessible to editors/referees (no login walls).
- Ensure supplementary PDFs (if you export any) have anonymized document properties/metadata.
- If you move these files to a repository (e.g., OSF/Zenodo), update the Data Availability statement to point to that stable link.

