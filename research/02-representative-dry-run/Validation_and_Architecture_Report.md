# Knowledge Atlas — Representative Data Architecture Dry Run

**Version:** 0.1 | **Date:** 2026-11-27 | **Authority:** private candidate, PENDING | **Release gate:** NO-GO

## 1. Recovery register

| Source | Version / evidence | Authority / limitation |
|---|---|---|
| atlas-data.json | Summary v1.0, 2026-09-07, 287 nodes | Original status retained per record; not an assertion of owner approval. All 287 raw payloads equal embedded W records. |
| Energy Forest JSON | v0.1-draft, v0.2, v0.4 U42 migrated, 2026-11-21 | v0.4 is structurally migrated, taxonomic verification partial; 239 raw payloads equal embedded E records; 96 source relation payloads reconciled. Earlier versions bundled as history only. |
| Atlas_Explorer.html | Original recovered standalone staging explorer; exact bytes pinned in manifest; no explicit package version in embedded JSON | 913 nodes, 1,174 edges; includes 9 editorial candidates. Not assumed to be the v0.3 953-record release. |
| P/G review workbook and historical taxonomy | v2.4, 2026-11-23 | Original standalone files, candidate proposals. Raw PG and G records from Explorer preserved; source workbook bundled, full edge-by-edge external verification not executed. |
| Atlas_Visual_Representations_Placement.json | CANDIDATE_PLACEMENT; points to Loop1200 baseline | Six original placement entries; unnamed IDs represented by source-array locators only. Four referenced artifact/practice IDs are not in recovered W graph. |
| 10_architecture_graph.json | Stage02 v0.1, excerpt only | Six original node fields and two complete proposed prerequisite edges transcribed. P0001, P0003, P0004 are known boundary dependencies but source endpoints not recovered in this excerpt; no assertion of complete local graph. Original raw bytes not available. |
| Foundational Architecture Comparative Study | v0.1 | Prior working study, not canonical; used as input. |
| Recovery ZIP | Knowledge_Atlas_Recovery_2026-11-27.zip located | Materialization denied: This Project file does not have an authorized raw-byte materialization path. |
| Unified integration/ontology ZIPs; Loop1200 ZIP; HVAC 441-node graph | historical references | Exact archives not recovered; original package digests and full historical release sequence cannot be independently verified. |
| Older source/analysis repositories | prior lookup | 404; availability/permissions unresolved. |

Full recovered explorer counts: 287 W + 239 E + 38 N + 106 T + 129 PG + 27 G + 87 R = 913. Edges: 797 navigation + 293 assertion + 75 legacy association + 9 editorial candidate = 1,174. Removing the nine editorial candidates yields 1,165, matching the earlier inherited count. This explains the numerical difference but is not proof that the original ZIP version is identical. Source manifest pins the recovered individual bytes, not absent package bytes.

### Recovered six historical views
V01 Nature, Science & Formal Knowledge; V02 Engineering, Technologies & Resources; V03 Work, Organizations & Economy; V04 Research & Knowledge Organization; V05 History, People & Places; V06 Standards, Documents & Outputs. Original nav.status: `proposal; views not canonical classifications`. Do not rename them as approved Gardens. Prototype computes reachability using the original linked groups and the original special rules for R and PG/G. No reparenting.

## 2. Sampling method and preservation
Purposeful, non-statistical sample of 35 distinct seed records covering six test families. Include all first-hop incident relationships and endpoints, then all navigation ancestors. Induced graph: 145 original records and 238 internal edges; 343 boundary edges are preserved separately and resolve in the full 913-record snapshot. Six REF excerpt records, two REF edges and six original placement rows are a separate review namespace. Exact original IDs, normalized records, raw payloads, authority states and complete source snapshots retained. E relation reason/confidence restored in `original_relation_evidence`; no synthesized evidence. PG evidence source IDs preserved in raw records and workbook. No canonical edits. Crosswalk includes 151 actual graph/REF records, and placement entries retain locators instead of fabricated IDs. Each of 238 induced edges has a decision; 343 boundary edges explicitly held, not silently dropped. Five candidate relationships have distinct dry-run IDs, never replacements.

## 3. Case-by-case comparative results

| Case | Original organization | Domain-based navigation | Type-based candidate classification | Research / learning consequence |
|---|---|---|---|---|
| HVAC | W:energy / W:hvac_design; E engineering, system and work branches | Good unified entry; preserve historical MEP context, not final Garden | Engineering discipline vs organization function vs system family vs work activity | Resolve role scopes; `uses_knowledge` never automatic prerequisite |
| Diagrams | W:information_design and E documents; separate placement catalogue | Existing design anchor is convenient; cross-domain forms can also be found from engineering | Discipline, representation family, document category, artifact instance are distinct | Existing forms preserved as candidates; four referenced IDs not recovered; no invented targets |
| Temperature | E:n_nature_thermal_01 phenomenon; REF3-A01 local state property; REF3-A06 unit | Thermodynamics and measurement access points possible, not approved | Quantity, observable condition, scientific law and unit must not collapse | Review sense of temperature differences; only local P0002/P0005 retrieved, both proposed |
| Programming | W software/automation functions and W:api_integration | Domain access works for practice but lacks core computing records | Integration practice, scripting practice, department/function, workflow vs language/interface | Recover missing Python/HTTP/language/interface sources; don't relabel practice as API |
| Occupations | W:hvac_design_engineer vs E:n_work_roles_01 | Multiple paths allow work/engineering lookup | Role vs occupation category possibly overlap; not auto-equivalent | DR-P01/P02 HOLD for occupational scope; same label search returns both |
| Historical Events | PG person/event/institution, G place, E phenomenon | Access from history, science or institutions may coexist | Event distinct from person, place, organization and natural phenomenon | Existing `conducted`, `observed_phenomenon`, `hosted_event`, `event_site` preserved; external evidence review pending |

### Model comparison (qualitative evidence, no measured ranking)
Domain-only helps navigate HVAC and programming, but mixes work/function/scientific/device categories and makes Diagrams/Temperature cross-domain ownership difficult. Entity-type-only helps distinctions but separates the elements needed to understand a workflow. Six-view approach preserves alternate inquiry paths but views can overlap and miss new/local entries; not a scientific taxonomy. Separated overlays let all three operate without changing original records, but introduce data maintenance and decision complexity. Learning ordering needs its own graph and review; a `browse_contains` or `uses_knowledge` edge is not a verified prerequisite. Prototype is a comparative view of these alternatives, not a final architecture selection.

## 4. Identity and edge decision rules under test
- Preserve source namespace, original ID, source type/status and raw evidence. A sample UID is a source namespace plus original ID; do not replace IDs.
- Same exact ID = reuse; same normalized label with different IDs = review candidate, not merge. Different types or scopes can coexist; alias equivalence must be evidenced.
- A new discovered label opens a scoped research task only after checking existing records. Candidate IDs are overlay-only; unresolved source locators remain unresolved.
- Browse relation is directional for navigation, not class membership. Source assertion retains predicate, direction, provenance and confidence; no automatic class, causal or prerequisite inference.
- Learning prerequisites separately tested for cycle, self-loop, and candidate authority. P0002 and P0005 acyclic only within recovered excerpt; no full local or scientific prerequisite verification.
- Keep raw evidence for rejected/held options. Staged, reviewed, approved and published are separate states.

## 5. Validation
`validation_results.csv`: 27 gates executed/assessed, 22 PASS and 5 FAIL. The PASS count includes structural checks, explicitly labeled synthetic negative fixtures, and restriction compliance; NOT 22 scientific approvals. Full graph has no duplicate IDs or dangling edges and no browse cycle. W/E standalone raw comparisons and all 96 Energy relation payload matches passed. 238 induced relationships have individual decision records. Negative duplicate-ID, semantic-as-navigation, new-ID insertion and prerequisite-cycle fixtures behave as expected. Five failed gates: T21 full REF recovery; T22 core programming vocabulary recovery; T23 diagram artifact resolution; T24 original archive byte/hash recovery; T25 independent scientific and occupational validation. All remain open.

Browser: 11 scripted Chromium checks passed after refining a test expectation: substring search for `hvac design engineer` correctly also returns HVAC Design Engineering, not just the two exact labels. The corrected test checks both exact IDs independently. Direct file:// navigation was blocked by administrator in this environment; tested exact HTML content via set_content instead. No human usability, accessibility, or cross-browser test. Prototype is local, not deployed. See `browser_test_results.json` and `test_browser.py`.

## 6. Risks and unresolved conflicts
| Risk | Actual observation | Control / owner |
|---|---|---|
| False equivalence | HVAC Design Engineer occurs with different role/occupation types | Hold DR-P01; Occupational Analyst |
| Type mixing | HVAC Design Engineering department/function vs engineering field; temperature differences ambiguous | Hold scope review; Ontology Engineer |
| Lost evidence | Missing ZIPs, local REF excerpt, unresolved diagram IDs | No invented records, recovery manifest; Project Historian |
| Misread completeness | 913-record Explorer is not the 953-record candidate | Preserve precise baseline and counts; Integration Editor |
| Boundary loss | 343 crossing edges outside induced graph | Keep complete baseline and boundary register; Integration Editor |
| Prerequisite drift | Candidate REF edges could be misread as verified | Dedicated local status and cycle checks; Scientific Researcher |
| View hierarchy drift | Six proposals could become Gardens by implication | No reparenting and separate view labels; Information Architect |
| Public data leak | Source files include private historical research | Offline-only package; no GitHub write or public deployment; Owner |
| UI overconfidence | Scripted tests only | Human and accessibility review required; UX Researcher |

## 7. Migration diff and owner decisions
Zero canonical add/update/delete/merge/publish operations. Proposed overlay: 151 identity rows, 238 induced edge review rows, 343 boundary holds, two local prerequisite reviews, six placement locators, five candidate edges, six research scopes and two illustrative learning sequences. Nine open owner decision rows in `owner_decisions.csv`; no final Garden selection. The candidate sequences are examples only, not approved curricula.

## 8. Decision and handoff
Dry run structurally useful; integration and release NO-GO. Next role: Evidence Recovery / Subject Review Coordinator with Ontology Engineer. Recover the exact missing source ZIPs and full REF graph; verify artifact locators and programming vocabulary from source, and resolve occupational scope cases. Re-run this exact sample with source hashes, compare changes, and only then seek owner decisions about representation rules. No automatic merge or public release.
