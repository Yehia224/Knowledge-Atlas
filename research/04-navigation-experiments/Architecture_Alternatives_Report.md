# Knowledge Atlas — Architecture Alternatives & Navigation Experiments v0.1

**Status:** PRIVATE WORKING DRAFT / PENDING OWNER APPROVAL. 27 November 2026.
**Role:** Information Architect / Product Architect.

## 1. Evidence boundary
The frozen experiment input is `source_snapshot.json`, a byte-for-byte copy of Evidence Recovery v0.2's isolated dataset. It contains 145 Atlas records (93 concept records and 52 navigation records), six local REF Stage02 records and six candidate diagram catalogue entries. The 157 entries are not 157 verified concepts. The 238 original internal Atlas links, five candidate relationships, two local prerequisite proposals and 343 boundary relationships are retained. The wider REF snapshot and computing locators are context, not additions to this comparison sample. All original IDs, payloads and source statuses remain unchanged; the prior 22 PASS / five FAIL gates remain unchanged. No public deployment, canonical integration, ID replacement or owner approval occurred.

## 2. Four architectural alternatives / formation rules
Each path is a navigation overlay, not an ontology assertion. A leaf is a terminal position in a particular view, not necessarily an atomic concept. A record can simultaneously be a displayed destination and have descendant groups. Garden names below are provisional labels for the experiment, not final sections. The source overlay is a comparator, not a proposed new hierarchy.

| Model | Garden / top group | Tree | Branch | Leaf | Growth rule |
|---|---|---|---|---|---|
| A — Original forest | Original source namespace | Recovered root or first original group | Original browse parent chain | Original record reference | Follow original parent links only; keep missing parents unresolved; retain REF historical hierarchy separately |
| B — Domain gardens | Subject domain anchored in recovered source trees | Source lineage | Immediate historical parent label, if available | Original record reference | Add an access path when documented domain membership or explicitly scoped case warrants it; do not duplicate identities |
| C — Entity-type catalogue | Record kind / typing status | Existing candidate type or unresolved original type | Optional refinement after type review; none forced in experiment | Original record reference | Resolve identity and entity type before proposing subdivisions; unknown types stay in holding group |
| D — Six inquiry views | Recovered V01–V06 lenses | Source lineage | Immediate original parent label | Original record reference | Reuse recovered view anchor; supplemental REF/CAT/G access is a new candidate overlay; unmatched records go to unplaced holding group |

Formation conditions: define intended question, grouping criterion, included/excluded scope and evidence; check overlapping groups; avoid promoting a collection to an entity class. A new branch must provide meaningful distinctions beyond repeated labels. New leaves reuse a source identity or a catalogue locator; no new semantic ID generated here. Recursive research: discover terms within USSP scopes, check existing IDs and senses, record alias/related/child/hold outcomes, search independently; research queues and learning journeys remain separate. New nodes are not created by clicking an existing node.

## 3. Comparison with historical models
A preserves the source-specific World of Work and Energy Forest browse structures. B revisits September Forest's domain logic, retaining original source lineage as a deliberately conservative intermediate level rather than pretending the integration is complete. C revisits Energy Forest's entity-based separation but uses record-kind guards and unresolved typing rather than treating every candidate class as verified. D directly reuses six recovered Unified Atlas views. V04 is empty in this sample because no Research Atlas records were sampled; it is shown, not deleted. Two historical root records have no matching anchor and are explicitly unplaced. The REF, CAT and G access assignments in D are new proposals, not historical decisions.

## 4. Quantitative evaluation
Read `comparison_metrics.csv` and `task_paths.csv`. Counts include populated top groups and structural path selections (one per displayed segment, including selecting the record). They are not human clicks or elapsed time measured in a usability study. A includes explicit provenance/source root segments, so comparing its depth directly with compressed models favors the latter. B/D retain a source segment to reduce context loss. Groups count distinct path prefixes, not semantic classes. All 157 records remain accessible in all four. 32 task routes (eight targets × four models) were generated, with executable data checks and 15 Chromium interaction checks. The structural tests passed 19/19. Browser tests passed 15/15 using set_content in Chromium, not a public URL. Neither test constitutes independent human evaluation or accessibility certification.

| Model | Populated top groups | Browse group prefixes | Placements | Mean shortest depth | Max shortest depth | Largest top group |
|---|---:|---:|---:|---:|---:|---:|
| A | 8 | 72 | 157 | 4.56 | 6 | 69 |
| B | 13 | 101 | 159 | 3.97 | 4 | 55 |
| C | 5 | 41 | 157 | 3.00 | 3 | 64 |
| D | 6 | 80 | 157 | 3.97 | 4 | 83 |

D has five populated historical views, one empty historical view (V04), and a populated fallback. C has 29 unresolved typing records. B has two records placed twice; references do not duplicate payloads. A, C and D have one placement per record in this particular sample. 32 task routes are deterministic reachability checks, not measured independent user task completion. Four of the 32 task routes (Temperature in each model) were exercised in a browser; four additional search checks verified duplicate-role visibility in each model, plus link/journey/gap and display checks.

## 5. Strengths, weaknesses, complexity, migration
| Model | Strength | Weakness | Implementation/migration consequence |
|---|---|---|---|
| A | Traceable provenance and historical context | Source fragmentation, long paths and inconsistent grouping | Low transformation; preserve existing parent structure; cannot unify discovery by itself |
| B | Familiar domain-based exploration; HVAC work and engineering accessible together | 13 populated groups, 101 prefixes, competing criteria and shared subject boundaries | Medium/high curation; explicit multi-membership rules and domain crosswalk; retain old IDs |
| C | Short type-focused paths and explicit category differences | 29 unresolved types; user must know what kind of thing they want; loses context | High semantic review burden; no type upgrades on migration; type catalogue useful as auxiliary lens |
| D | Preserves six historical question lenses and simpler first level | Work view holds 83 entries; empty research view in sample; 2 unplaced roots | Medium mapping effort; anchor mapping + documented supplements; test balance at broader scale |

No overall weighted score used: weighting browsing, semantics, learning and maintenance without owner preferences would be arbitrary. No model is adopted. Shared search, relationships and learning are held constant; this experiment measures organizational differences, not independent backend designs. Same-label groups are displayed by path labels; a future production system needs stable collection IDs to avoid conflating labels. Domain mapping is manually authored, not independently validated.

## 6. Concrete task results
- HVAC Design Engineer: same-label records remain separate in every model. B places them under MEP, C under different candidate types, D under Work, A in different source trees. Neither equivalence nor occupation scope has been settled.
- Diagrams: Flowchart retains its candidate catalogue locator, not an invented ID. C foregrounds representation form; B puts it under Design, D under Standards/Documents; these are browse proposals, not ontology.
- Temperature: REF3-A01 and REF3-A06 stay distinct; A uses recovered Stage02 hierarchy, other models project it. Learning journey still marked illustrative; no prerequisite certification.
- Programming: API / System Integration resolves, but HTTP, API as interface, programming language and Python retain curriculum locator status only. Search does not invent semantic records.
- Historical Events: Faraday experiment remains an event, with historical links accessible; person, institution and phenomenon are not subclasses of the event.
- HVAC Engineering → Thermodynamics: preserved source relation accessible in the record panel, not converted to browse containment.

## 7. Limits / next bounded experiment
All five inherited FAIL gates (T21–T25) remain open. The sample is purposeful, not statistically representative; no Research Atlas records in this sample, and no claim about complete historical archives or full domain coverage. Next compare blind user tasks on a broader sample including the 87 Research Atlas records and recovered computing curriculum as a separate route. Preserve evidence and log any change in sample. Run keyboard, mobile, screen reader and learner comprehension tests before proposing navigation choices. No requirement to recover the same blocked archives repeatedly without a new access method.
