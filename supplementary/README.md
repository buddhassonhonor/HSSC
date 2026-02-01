# Supplementary Information (for peer review)

## Anonymity notice
Per the editor’s instruction, these supplementary files do **not** contain any author names, affiliations, emails, ORCID IDs, or other identifying details. Please keep filenames and document properties anonymous when exporting/uploading.

## Contents
- `supplementary/S1_materials_and_scope.md`: materials categories and scope conditions (as described in the manuscript).
- `supplementary/S2_secondary_evidence_inventory.csv`: inventory of peer-reviewed secondary evidence (exported from `references.bib`).
- `supplementary/S3_policy_documents_index.csv`: index of policy documents and authoritative interpretations referenced for the analysis, with stable URLs and access dates.
- `supplementary/S4_public_narratives_index.csv`: index of public reform narratives (e.g., official press releases/press briefings) used to identify semiotic framings, with stable URLs and access dates.
- `supplementary/S5_codebook.csv`: coding scheme used in the mechanism-tracing protocol (semiotic imaginaries + structural selectivities).
- `supplementary/S6_reform_episode_matrix.csv`: reform-wave “test case” matrix (variation → selectivities → adaptation → outcome) aligned with Table 1 and text.
- `supplementary/S7_citation_index.csv`: line-level citation index exported from `HSSC.TEX` (helps audit traceability from claims to cited evidence).
- `supplementary/S8_audit_trail.md`: a compact audit trail describing how the above files were assembled from the manuscript.

## Regeneration (optional)
If you update the manuscript or bibliography and want to regenerate inventories:
- `python supplementary/tools/bib_to_csv.py --bib references.bib --out supplementary/S2_secondary_evidence_inventory.csv`
- `python supplementary/tools/extract_citations.py --tex HSSC.TEX --out supplementary/S7_citation_index.csv`
