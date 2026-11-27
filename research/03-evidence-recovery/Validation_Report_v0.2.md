# Knowledge Atlas — Evidence Recovery & Conflict Resolution v0.2

**Date:** 27 November 2026 | **State:** Private staging / Pending owner approval

## 1. Executive finding

The exact v0.1 sample was reproduced by rerunning its original build script in a temporary copy. Its 35 seeds, 145 selected Atlas records, 238 internal relationships, 343 boundary relationships, source payloads and relation evidence are deeply equal to v0.1. No canonical records, source files, repository content or published pages were changed. The recovered material extends the evidence available to the review, not the canonical dataset.

The 27 original gates still report 22 PASS and 5 FAIL. Fourteen additional bounded structural or recovery checks passed. These checks do not substitute for the five unresolved gates. The historical REF graph is now fully recovered as indexed text, but a later REF baseline and the original complete evidence bibliography remain missing.

## 2. Recovery manifest and exact versions

| Source | Recovery | Limitation |
|---|---|---|
| Representative Dry Run v0.1 | Original local package and source copies available; rerun reproduced exact sample | A staging snapshot, not approved knowledge |
| REF `10_architecture_graph.json`, Stage02 v0.1 | 10,918 indexed lines recovered in 11 contiguous ranges; reconstructed and parsed as JSON | No raw-file SHA match; do not assert byte-identical original |
| REF Stage07 handoff | Records a later baseline of 298 identities and 722 graph records | Complete baseline and original evidence register not recovered; no replacement with Stage02 |
| Computer → AI Master Topic Map v0.3, Saturation Audit Round 2 | Original standalone Markdown recovered | Curriculum topics, not stable semantic identities |
| Atlas Diagrams & Charts Audit | Original standalone HTML recovered; four missing IDs corroborated | Referenced original node/artifact payloads still unavailable |
| Recovery archive 27 November, Loop1200 archive, Foundational Ontology v0.1 and Unified integration v0.1 packages | Prior file names/references retained | Raw package retrieval blocked or not recovered; exact package checksums unknown |
| Original HVAC 441-node dataset | Outstanding | No reconstruction or new historical IDs invented |

See `recovery_manifest.csv` for local checksums and explicit missing files. The input text chunks and exact v0.1 rerun sources are included in the private package for reproduction.

## 3. REF Stage02 historical graph

- 271 unique original node identities.
- 529 prerequisite relationships; all edge IDs and ordered endpoint pairs are unique; no cycles in the directed prerequisite graph.
- 7 causal + 7 functional + 4 information/constraint + 4 accounting + 50 typed relationship records; 601 records across all six relationship arrays, not necessarily 601 distinct logical assertions across all arrays.
- All 601 records resolve to recovered source and target node IDs. The six nodes and two edges present in the old excerpt match exactly.
- 76 source IDs referenced by node records. Across node and relationship evidence fields, 80 distinct pointers are present: 16 with at least one inherited URL, 64 without a recoverable URL in this graph. These are pointer counts, not validated sources or complete bibliography entries.
- The original 50 typed edge records do not carry edge IDs. They are identified by source-array locators, not invented original IDs.
- Every recovered prerequisite retains its original proposed status. DAG validity is not evidence that every edge is a necessary prerequisite.

`ref_evidence_pointer_register.csv` preserves recovered IDs, URLs and inherited statuses. `ref_relationship_review.csv` preserves individual locators and review holds. The JSON in `sources/` preserves original fields and qualifiers.

## 4. Computing recovery

The older topic map explicitly records HTTP (Phase 06, line 347), Programming Foundations with Python (Phase 08, heading line 432), programming language (line 437), library (Phase 09, line 494), API (Phase 12, line 628; also Phase 23, line 1113). Preserve these curriculum locations and use them to scope recovery. None of these headings or bullets supplies an independently verified semantic ID or definition. `computing_recovery.csv` records exact locators; no replacement concepts are inserted. RFC 9110 corroborates HTTP as a protocol, not a language; it is additional external evidence, not proof of an old Atlas identity.

## 5. Diagram reference resolution

Four original identifiers are corroborated by `Atlas_Diagrams_Charts_Audit.html` and the placement record: `data_visualisation`, `art_hw_block_diagram`, `art_infrastructure_architecture_design_diagram`, `art_controls_diagram`. The audit points to `canonical/nodes.jsonl` and `canonical/artifacts.jsonl` in Loop1200. Their raw records have not been recovered; target joins remain blocked. IEC TC3 distinguishes overview, circuit and function diagram document kinds; that supports semantic separation, not identification of a particular Atlas artifact. Information Design remains a proposed browse anchor, not a superclass of every diagram.

## 6. Conflict decisions (bounded source review)

| ID | v0.2 disposition | Why |
|---|---|---|
| DR-P01 | Hold equivalence | W:hvac_design_engineer specifies calculations, system selection and design documents; E:n_work_roles_01 has provisional occupation type but no detailed matching scope. ASHRAE/CIBSE evidence supports domain tasks, not equivalence. |
| DR-P02 | Hold overlap | W:controls_engineer includes BMS points, panels, sequences, programming and integration. E:n_work_roles_02 lacks a full scope definition. ASHRAE controls/BAS evidence supports overlap, not identical scope. |
| DR-P03 | Revise candidate association; no alias | REF3-A01 Temperature, REF-CP-N001 Temperature Difference, REF-CP-N044 Finite Temperature Difference are distinct historical records. E:n_nature_thermal_01 is provisional and its precise sense remains open. |
| DR-P04 | Retain navigation candidate | A cross-domain representation catalogue may provide access; the browse link is not subclass or part-of. |
| DR-P05 | Source-supported candidate | BIPM supports Kelvin as SI unit of thermodynamic temperature. Candidate predicate should be has_SI_unit; approval and scope review still pending. |
| pg24_rel_001 | Source-supported | Royal Institution attributes ring-coil experiment to Faraday. |
| pg24_rel_002 | Source-supported; mapping hold | Electromagnetic induction is supported; the target label “Induction” in Energy Forest is broader/underspecified. |
| pg24_rel_003 | Source-supported | Royal Institution laboratory hosted the work. |
| G-edge-1100 | Source-supported city precision | London context supported; no more precise location inferred. |
| P0002, P0005 | Hold pedagogical depth | Historical graph is acyclic; necessity and appropriate learning depth remain unverified. |

Source URLs, source claims, review scope and status are recorded in `evidence_register.csv`. This is source-grounded review by the same assistant, not independent human specialist sign-off. The old relationship assertions and statuses are retained. No canonical semantic edge added or rewritten.

## 7. Rerun and gate status

The original 27 gates have 22 PASS and 5 FAIL; the new 14 bounded checks all PASS. See `validation_results_v0.2.csv`, `additional_validation.csv` and `baseline_rerun.json`.

| Failed gate | Progress | Remaining condition |
|---|---|---|
| T21 Complete REF graph | Historical Stage02 recovered and structurally tested | Later Stage07 298/722 graph and complete original evidence register |
| T22 Programming semantic coverage | v0.3 curriculum source and exact topic locations recovered | Stable semantic identities, definitions and evidence; no invented old records |
| T23 Diagram targets | All four identifiers corroborated | Exact target payloads and endpoint joins |
| T24 Original archives | Individual source files available and hashed | Raw original packages and exact original version/digest reconciliation |
| T25 Independent subject review | Selected source claims checked and decision holds refined | Independent human scientific/occupational review and approval |

The architecture still supports separate semantic, browse, research and learning overlays on this sample. That is a structural result, not a finding of final usability, coverage, scientific correctness or approved taxonomy.

## 8. Change and migration control

- Updated crosswalk: 416 rows, composed of the unchanged 145 Atlas sample identities plus 271 historical local REF context records (six already in the original excerpt; 265 newly recovered context rows). No enlargement of the original 35-seed sample is implied.
- 305 field/row change-log entries, including candidate disposition updates. These are log entries, not 305 new concepts.
- Original source statuses are retained. All owner decisions remain OPEN.
- Canonical operations: zero additions, updates, deletions, merges, publications or final Garden selections.

## 9. Reproduction

Unzip the private package. With Python 3 and networkx installed, execute `python KA_evidence_v0.2/build_v02.py` from the extracted package. It reruns v0.1 in a temporary copy and rebuilds the v0.2 registers. The external evidence review remains a dated human-readable record, not an automatically reproduced web verification. The build does not connect to GitHub or publish anything.
