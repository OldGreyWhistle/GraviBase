# UMF Trial S3M0S1 — Indexes Design Specification v3

**Document version:** v3 (design specification; standalone)
**Date:** 27 May 2026 (AEST)
**Working language:** Australian English (per standing rule v0.35)
**Page format target:** A4
**Trial:** UMF Trial S3M0S1
**Author of trial:** Stephen L Browne
**Drafter:** Claude Opus 4.7 Adaptive (Anthropic)

**Status:** v3 supersedes v2 for working use. v2 retained unchanged per audit-trail integrity rule. v3 incorporates five high-priority gap additions surfaced from Scaffold v8 inspection (Stephen 27 May AEST direction to "proceed as recommended"): joint-citation clusters, matrix-entry series taxonomy flagging, external corpus document hyperlinking, Stephen adjudications registry, open follow-up Items registry. Three medium-priority items added as new open questions for Stephen decision (§12). Step 1 of incremental implementation of option (C) — index-centric reorganisation. No Amendment anchor at this stage. Step 2 will populate the indexes under a new Amendment anchor.

**Supersedes:** UMF_Trial_S3M0S1_Indexes_Design_Spec_v2.md (retained unchanged per audit-trail integrity rule).

---

## §0 Delta from v2

Substantive additions in v3:

- **§2** minor — joint-citation clusters and external corpus linking added to architecture summary
- **§3.2** extended — examples list includes matrix-entry series taxonomy (A/B/D/F + Theme A/B/C + Tier 1/2); new sub-subdivisions OP-Adj and OP-Item introduced with example terms
- **§3.3** extended — schema rows added for OP-Adj sub-subdivision (Decision-date, Scope, Downstream effect, Stephen-verbatim) and OP-Item sub-subdivision (Statement, Current status, Awaited direction)
- **§3.5** extended — source rules updated for OP-Adj and OP-Item population
- **§4.8 NEW** — Joint citation clusters sub-section within Index 2 (CR-JC-NNNN cluster IDs; hyperedges of ≥2 member nodes)
- **§7.8 NEW** — External corpus document hyperlinking (links from indexes to Scaffold, Research Plan, Amendments, deeppass reports)
- **§11** extended — Step 2 production plan covers new sub-structures
- **§12** extended — three new open questions for Stephen decision (verbatim citations index; framework-level annotation flags placement; held-aside review cadence)

Sections §1, §5, §6 (except §6 minor cross-ref update), §8, §9, §10, §13, §14 unchanged in substance from v2; numbering only adjusted where insertion required.

---

## §1 Purpose

This document specifies structure, scope, and rules for three cross-referencing indexes intended to provide a decision-aid navigation layer over the existing UMF Trial S3M0S1 corpus and, by design, across adjacent research programs.

The indexes do not introduce new substantive scope. They organise existing corpus content under typed structures. They are not a substitute for the existing scaffold, research plan, deeppass reports, or amendments — those remain the substantive deliverables. The indexes are the navigation layer above them.

The three indexes serve different but linked purposes:

- **Index 1 (Context Definition)** — operational and theoretical terms with definitions and required actions; includes sub-subdivisions for Stephen adjudications (OP-Adj) and open follow-up Items (OP-Item)
- **Index 2 (Context Relationships)** — typed edge list relating papers, frameworks, and concepts; includes §4.8 joint-citation clusters sub-section for hyperedge structures
- **Index 3 (Metric Units)** — typed measurable/parameterised quantities with values across the corpus

The three interlink: Index 3 entries reference Index 1 for their definitions; Index 2 edges and clusters reference Index 1 terms and Index 3 quantities; Index 1 operational terms are referenced from Index 2 modal-tier annotations. Indexes also link to substantive corpus documents per §7.8.

---

## §2 Cross-index architecture

A decision pathway navigates the indexes as follows. Worked illustrative example for Item 5 (UMF G-shock M* naturalness vs F-05 cluster tuning):

1. Open Index 1 → CD-OP-Item-005 → see current statement, status, awaited Stephen direction, modal status
2. Follow cross-reference to Index 3 → row for M* → see all values assigned across the corpus, each with paper/framework provenance
3. Follow definition pointer in Index 3 → Index 1 entry for M* (gravitational baryogenesis cutoff scale; operational meaning and theoretical context)
4. Open Index 2 → filter by edges referencing M* → see parameter-regime-shared / parameter-regime-different edges between cluster members
5. Open Index 2 §4.8 → joint-citation clusters that deploy frameworks against this Item; navigate to Scaffold §11.3 Item 5 prose for substantive content
6. For any edge whose modal tier matters → Index 1 entry for the modal-status term used (e.g., "preprint-with-quality-concerns")

The reader assembles a navigable decision picture without re-reading prose across §5.2, §11.3 Item 5, multiple deeppass reports, and three amendments.

The indexes do not replace prose; they index it.

---

## §3 Index 1 — Context Definition

### §3.1 Purpose

Consolidated lookup of operational AND theoretical context terms used across the research program. Each entry: term → definition → required action / handling rule (operational) or applicable conditions (theoretical), with sub-subdivisions for adjudications (OP-Adj) and follow-up Items (OP-Item).

### §3.2 Subdivisions

Index 1 contains the following subdivisions, sharing the base schema in §3.3 with additional required fields per sub-subdivision:

**1A Operational context (Subdivision = OP)** — terms whose meaning is constituted by the research-program's methodology and governance. Examples expected at Step 2 population:

- Methodology: Stream 3 methodology; modal-status preservation; framing-bias correction; audit-trail integrity; controlled-synthesis-injection; uncontrolled-synthesis-creep; scope-expansion authorisation; peer-review-status verification protocol; deeppass-report convention; deeppass-addendum convention; mandatory-bundling; honest-disclosure correction; provenance gate; provenance correction; labelling clarification.
- Source-quality tiers: preprint-only; preprint-with-quality-concerns; preprint-with-strong-internal-quality; peer-reviewed.
- Modal-status convention terms: committed; possible-candidate-territory; open-question; held-aside; disclaimed; informative.
- Cluster / framework taxonomy: F-02 cluster; F-05 cluster; substantive matrix entry; ESCALATE matrix entry.
- **Matrix-entry series taxonomy:** A-series; B-series; D-series; F-series (definition + placement criteria for each).
- **Theme classification:** Theme A; Theme B; Theme C.
- **Tier classification:** Tier 1; Tier 2.

**1B Theoretical context (Subdivision = TH)** — terms whose meaning is constituted by the physics of the topic-domain under study. Examples expected at Step 2 population: inflationary epoch; matter-dominated epoch; radiation-dominated epoch; FRW background; Einstein frame; Jordan frame; scalar-tensor frame; ADM 3+1 decomposition; teleparallel vs curvature-based gravity; EWPT; GUT scale; Planck scale; M_Pl-natural; naturalness regime; gravitational baryogenesis; reverse baryogenesis; phase-conjugate wavefront; bounded vs cyclic spacetime; CYC; BND.

**1C Stephen adjudications (Sub-subdivision = OP-Adj)** — discrete Stephen decision-points that constrain downstream work. Each is a numbered or labelled adjudication with a date, scope, decision content, and downstream effect. Examples expected at Step 2 population: Q1 (DM landscape honest neutrality, no forced closest-category framing); Q2 (CYC/BND context-dependent positioning); Q3 (ε₀/μ₀ ADD-style extension with strong-nuclear-force context); Q6 (Penrose-Diosi standalone); Q4 and Q5 (provenance corrections); Issue 1 (phase-conjugate-wavefront terminology revision); Issue 2 (five-framework gravity-mass offset joint citation); 26 May scope-expansion; Option A (JWST/ASKAP empirical engagement); Option (a) consolidate-and-stabilise; Option (ii) 10-topic review resumption; Items 1+2 position-taking 26 May AEST; framework-name correction (Universal Mass-energy → Unified Metric); trial renumbering S3M5S1 → S3M0S1; 27 May AEST post-Jan 2026 reading-layer authorisation; 27 May AEST AdjacencyReview2026 cycle authorisation including Step 3 per-paper decisions and sequencing direction. Count at v8 close: 19. Provenance corrections (Q4, Q5) appear here as adjudications and also in the separate-tracker provenance-correction count.

**1D Open follow-up Items registry (Sub-subdivision = OP-Item)** — substantive open questions tracked across versions, each with its own evolution. Examples expected at Step 2 population (Items 1–7 from Scaffold §11.3):

- Item 1: UMF-specific bounded-spacetime endpoint mechanism for ε₀ and α
- Item 2: UMF-specific GW memory predictions per Bieri 2021/2022 framework apparatus
- Item 3: Geon-stability resolution in UMF context
- Item 4: CLOSED by Amendment 8 (UMF Research Programme over-arching framing)
- Item 5: UMF G-shock baryon-asymmetry positioning vs F-02 + F-05 asymmetry-generation class
- Item 6: UMF-specific mechanism connecting phase-conjugate wavefront to gravity-mass spatial offset
- Item 7: UMF-specific predicted observational signatures for JWST high-z anomalies + ASKAP transient-survey detections (8 sub-items)

### §3.3 Schema

**Base schema (all subdivisions):**

| Field | Required | Description |
|---|---|---|
| ID | Y | Stable identifier; format `CD-OP-NNN`, `CD-TH-NNN`, `CD-OP-Adj-NNN`, or `CD-OP-Item-NNN` |
| Term | Y | Canonical term as used in the corpus |
| Synonyms / alt phrasing | N | Aliases that map to this term (improves search) |
| Subdivision | Y | OP, TH, OP-Adj, or OP-Item |
| Definition | Y | One-paragraph definition; verbatim where corpus provides it |
| Required action / handling | Y (OP) | What the term implies for the work — what to do when this context applies |
| Applicable conditions | Y (TH) | When this theoretical context is operative |
| Modal status | N | Free-text per Stephen 27 May AEST; convention table in §3.3.1 |
| Source provenance | Y | Where in corpus first defined / formally introduced |
| First introduced | Y | Version / Amendment / Stephen-direction date |
| Status | Y | Active / Superseded by [pointer] / Held-aside |
| Held-aside reason | Y (if Status=Held-aside) | Brief note explaining why the entry is held aside |
| Cross-program portability | Y | Generic / UMF-specific / both (dual-tag permitted per §9) |
| Cross-references | N | Other CD-NNN entries; Index 2 edges/clusters; Index 3 quantities |

**Additional required fields for Subdivision = OP-Adj:**

| Field | Required | Description |
|---|---|---|
| Decision-date | Y | Date Stephen made the adjudication (AEST) |
| Scope | Y | What the decision affected (e.g., "Item 1 position; ε₀/α variation under bounded-spacetime endpoint") |
| Downstream effect | Y | What changed in the corpus as a result (sections / documents updated; framing tightened; new follow-up items created) |
| Stephen-verbatim | N | Verbatim quote of the adjudication where preserved in corpus |
| Round-marker | N | Which document round captured the adjudication (e.g., "Research Plan v0.3 round") |

**Additional required fields for Subdivision = OP-Item:**

| Field | Required | Description |
|---|---|---|
| Statement | Y | The Item as currently stated in Scaffold §11.3 |
| Current status | Y | Open / Partially supported / Closed / Awaiting UMF technical development / Awaiting Stephen direction |
| Awaited direction | Y (if not Closed) | What specific Stephen direction or technical development is needed to progress |
| Evolution history | N | Brief history of substantive updates across versions (with anchor pointers) |
| Sub-items | N | For items with sub-items (e.g., Item 7 with 8 sub-items), list IDs of sub-items |

#### §3.3.1 Modal-status convention table (free-text but consistent)

| Convention term | Usage |
|---|---|
| committed | Formally adopted at postulate or assumption level |
| possible candidate territory | Flagged as plausible but not committed (Postulate-2-class) |
| open question | Flagged for future technical development |
| held aside | Flagged for review but not currently in scope |
| disclaimed | Explicitly rejected by framework (e.g., variable speed of light) |
| informative | Included for context but not load-bearing on framework |

Other phrasings permitted where corpus introduces them; this table records established usage for cross-entry consistency.

### §3.4 Scope boundaries

IN:
- Terms with operational consequences for how work is performed or reported
- Terms with theoretical context that bears on cross-paper comparability or decision-relevance
- Terms with non-trivial usage conventions within the program
- All Stephen adjudications (OP-Adj)
- All open follow-up Items (OP-Item) from Scaffold §11.3

OUT:
- Ordinary scientific terminology used with standard meaning and without program-specific action implications
- Incidental terms used once with no decision-weight

### §3.5 Source-content rules

- **OP/TH entries:** New entries with explicit Stephen authorisation OR when a substantive corpus deliverable formally introduces a new operationally-loaded or theoretically-loaded term
- **OP-Adj entries:** New entries when Stephen issues a decision that constrains downstream work. Step 2 population produces the full Adj-registry from existing corpus content (target: 19 entries at trial start, matching Handoff v6 §4 count)
- **OP-Item entries:** New entries when Scaffold §11.3 adds a new follow-up Item. Step 2 population produces the full Item-registry from existing corpus content (target: 7 entries at trial start, matching Scaffold §11.3 list; Item 4 marked Closed)
- **Informative-foundational entries permitted** (per Stephen 27 May AEST answer b): foundational references identified in corpus may be included as informative entries with provenance "entered via citation in [paper]"
- No in-place edits to active entries once populated; superseded entries marked Status=Superseded with pointer to replacement entry
- Held-aside entries carry Status=Held-aside with mandatory Held-aside-reason field
- Definitions sourced verbatim from corpus where available; paraphrased definitions noted as such with source pointer

---

## §4 Index 2 — Context Relationships

### §4.1 Purpose

Typed edge list of relationships between papers, frameworks, and concepts across the corpus. Provides navigable structural picture of how corpus elements relate. §4.8 sub-section extends Index 2 to joint-citation clusters (hyperedges).

### §4.2 Architecture choice: edge list, not matrix

Rationale: for ~22 Theme C frameworks + ~26 substantive matrix entries + cluster papers + foundational antecedents + held-aside surfaces, an n × n adjacency matrix per axis is sparse, hard to maintain, and hard to read. A flat edge list with typed edges is more compact, filterable, and extensible. Matrix views can be auto-derived from the edge list at consolidation time if needed.

### §4.3 Schema (bilateral edges)

| Field | Required | Description |
|---|---|---|
| Edge ID | Y | Stable identifier; format `CR-NNNN` |
| Source | Y | Paper / framework / concept identifier |
| Target | Y | Paper / framework / concept identifier |
| Edge type | Y | One of the controlled vocabulary (see §4.4) |
| Edge type family | Y | One of: Structural / Citational / Framework-class / Parameter-regime / Modal-tier / Programme-coordinated / Foundational |
| Annotation | Y | Brief, neutral description; modal status preserved |
| Source provenance | Y | Where in corpus the relationship was established or observed |
| First introduced | Y | Version / Amendment / Stephen-direction date |
| Status | Y | Active / Superseded by [pointer] / Held-aside |
| Held-aside reason | Y (if Status=Held-aside) | Brief explanation for follow-up provision |
| Symmetry | Y | Symmetric / Asymmetric |
| Cross-references | N | Index 1 definitions invoked in annotation; Index 3 quantities involved |

### §4.4 Edge type families and controlled vocabulary

| Family | Edge types | Notes |
|---|---|---|
| Structural | extends, refines, contests, parallel, orthogonal | How Source relates to Target in claim space |
| Citational | cites, is-cited-by | Bibliographic only |
| Framework-class | framework-class-shared | Same model class membership |
| Parameter-regime | parameter-regime-shared, parameter-regime-different | Shared or differing M*, T_D, ε, η_obs target; annotation specifies parameter |
| Modal-tier | modal-tier-comparison | Comparison of peer-review status / quality tier |
| Programme-coordinated | programme-coordinated | Same author group or research programme across multiple papers |
| Foundational | framework-foundational | Source is foundational reference for Target |

Edge types are additive: a Source–Target pair may carry multiple edges of different types.

### §4.5 Scope boundaries

IN:
- Relationships between corpus papers
- Relationships between matrix-entry frameworks
- Relationships between concepts/postulates and frameworks
- Relationships established by corpus content
- Held-aside Source/Target nodes (per Stephen 27 May AEST answer c)
- Informative-foundational Source nodes (per Stephen 27 May AEST answer b)

OUT:
- Trivial relationships ("both cite Einstein 1916")
- Speculative relationships not established in corpus

Modal-status discipline: "contests" requires the source corpus to actually contest; "parallel" requires actual independence.

### §4.6 Source-content rules

- Edges added when corpus content explicitly establishes the relationship OR when a Step 2 population pass identifies a relationship visible from corpus content
- New edges versioned with introduction date
- Superseded edges marked, not removed
- Held-aside edges carry Status=Held-aside with reason
- Annotations brief: one-sentence neutral description with parameter values where applicable

### §4.7 Auto-derivable views

- Per-paper ego-network
- Per-cluster summary (F-02 internal; F-05 internal; cross-cluster)
- Per-edge-type filter
- Adjacency matrix for any chosen subset and edge-type family
- **Per-joint-citation-cluster expansion view** (NEW v3): from any §4.8 cluster, expand to the full set of pairwise edges among member nodes for visual inspection of internal structure

Projections are mechanical; consolidation-time artefacts.

### §4.8 Joint citation clusters (NEW v3)

**Purpose.** The Scaffold deploys 13 joint-citation patterns — multi-framework citation clusters that together support a single UMF commitment. These are hyperedges of ≥2 member nodes that cannot be cleanly decomposed to bilateral edges without losing cluster identity. §4.8 records them as a separate structure within Index 2.

**Schema.**

| Field | Required | Description |
|---|---|---|
| Cluster ID | Y | Stable identifier; format `CR-JC-NNNN` |
| Cluster name | Y | Canonical name (e.g., "Wheeler-tradition lineage bracket"; "G-shock three-pillar precedent"; "Five-framework gravity-mass offset"; "Compound A-06 + A-10 + phase-conjugation analogue") |
| Member nodes | Y | Ordered list of framework / paper / concept IDs (e.g., A-01, B-01, B-02, B-04) |
| UMF commitment supported | Y | Which UMF v0.7 commitment, assumption, or position the cluster deploys to support |
| Deployment context | Y | Where in corpus the cluster is deployed (Scaffold section reference; verbatim citation block where applicable) |
| Annotation | Y | Brief, neutral description; modal status preserved |
| Modal status | N | Free-text per §3.3.1 |
| Source provenance | Y | Where in corpus the cluster was first identified |
| First introduced | Y | Version / Amendment / Stephen-direction date |
| Status | Y | Active / Superseded by [pointer] / Held-aside |
| Held-aside reason | Y (if Status=Held-aside) | Brief explanation |
| Stephen adjudication ref | N | Where applicable, link to OP-Adj entry that triggered the cluster (e.g., Issue 2 → five-framework gravity-mass offset cluster) |
| Cross-references | N | Index 1 definitions; Index 3 quantities; bilateral edges that pair-decompose this cluster (optional, for verbose annotation) |

**Examples expected at Step 2 population:**

| Cluster ID | Name | Member nodes | UMF commitment supported |
|---|---|---|---|
| CR-JC-0001 | Wheeler-tradition lineage bracket | A-01, B-01, B-02, B-04 | Wheeler-tradition lineage adoption (Scaffold §3.1) |
| CR-JC-0002 | Geometric-foundations programme bracket | A-08, A-09, B-01 | Foundational-geometric-programme legitimacy (Scaffold §3.3) |
| CR-JC-0003 | G-shock three-pillar precedent | B-02, F-04, B-03 | UMF G-shock matter-creation mechanism (Scaffold §5.1) |
| CR-JC-0004 | Variant-fundamental-constants joint defence | B-01, B-03 | UMF v0.7 §3.1 assumption 4 (ε₀/μ₀ + G via different geometric mechanisms; Stephen Q3) |
| CR-JC-0005 | Information allowance | B-04, F-08 | UMF information allowance (Scaffold §4.4) |
| CR-JC-0006 | Five-framework gravity-mass offset | F-10, Bullet Cluster, Mashhoon, B-01, F-08 | UMF gravity-mass spatial offset (Scaffold §7.3); Stephen Issue 2 |
| CR-JC-0007 | Compound phase-conjugate-wavefront analogue | A-06, A-10, phase-conjugation literature | UMF phase-conjugate wavefront commitment (Scaffold §7.2); Stephen Issue 1 |
| CR-JC-0008 | Classical ℏ-free gravity-only matter | B-02, B-01, F-04, A-01 | GWM ℏ-exclusion mainstream-precedent (Scaffold §5.4 Face 2) |
| CR-JC-0009 | Pilot-wave class | A-02, A-06 | GWM particle representation A-02 pilot-wave subclass (Scaffold §8.3) |
| CR-JC-0010 | LQG + CST methodological-precedent | F-06, F-07 | Quantum-gravity matter-coupling-open methodological precedent (Scaffold §9.1) |

Count at Step 2 target: 13 clusters matching Scaffold §14.1 enumeration. Three further clusters to be identified during population pass.

**Source-content rules:**

- New clusters added when corpus content deploys ≥2 frameworks together for a single UMF commitment
- Cluster membership is ordered for stability of presentation but not for semantic significance unless explicitly noted
- Superseded clusters marked, not removed
- Cross-reference to OP-Adj entry where the cluster was triggered by Stephen adjudication (e.g., Issue 2 explicitly motivated the five-framework gravity-mass offset cluster)

**Pair-decomposition view.** For analytical purposes, any §4.8 cluster can be projected to the full set of pairwise edges among its members. This is a consolidation-time mechanical operation; the bilateral edges so derived are NOT stored as separate Index 2 entries (avoids edge-list inflation and double-bookkeeping). The cluster remains the primary representation.

---

## §5 Index 3 — Metric Units

(Unchanged from v2.)

### §5.1 Purpose

Inventory of typed measurable / parameterised quantities used across the research program. Each entry: quantity → mathematical type → value-domain → physical dimension → definition (via Index 1) → values across corpus papers/frameworks.

Per Stephen direction 27 May AEST, the "metric unit" framing means a typed quantity (scalar / vector / tensor) characterised by value-domain (simple-scalar value / set-based / discrete / function-form / tensor-field). Theory-internal mathematical type, with physical dimensions also tracked.

### §5.2 Schema

| Field | Required | Description |
|---|---|---|
| ID | Y | Stable identifier; format `MU-NNN` |
| Quantity name | Y | Canonical name |
| Symbol | Y | Mathematical symbol as used in corpus |
| Type | Y | Scalar / Vector / Rank-2 tensor / Higher-rank tensor / Function / Operator |
| Value-domain | Y | Simple-scalar / Set-based / Discrete / Function-form / Tensor-field |
| Physical dimension | Y | E.g., GeV, GeV², dimensionless, cm, F/m; natural-units flag if relevant |
| Definition pointer | Y | Index 1 entry that defines this quantity |
| Values across corpus | N | Per-paper/framework values |
| Comparability notes | Y | Whether directly comparable across papers |
| Naturalness / tuning status | N | M_Pl-natural / requires-tuning / free-parameter / conditional-under-UMF-assumption-4 |
| Source provenance | Y | Where first introduced |
| First introduced | Y | Version / Amendment / Stephen-direction date |
| Status | Y | Active / Superseded / Held-aside |
| Held-aside reason | Y (if Status=Held-aside) | Brief explanation |
| Cross-program portability | Y | Generic / UMF-specific / both |
| Cross-references | N | Related MU-NNN quantities; Index 2 edges/clusters referencing this quantity |

### §5.3 Type taxonomy

- **Scalar** — single-component quantity (M*, η_B/s, R, T, T_G, α, ε₀)
- **Vector** — 4-vector or 3-vector quantity (∂_μ R, J^μ_{B-L})
- **Rank-2 tensor** — g_μν, T^μν, R_μν, G_μν
- **Higher-rank tensor** — R^μ_{νρσ}
- **Function** — f(R), f(T, T_G)
- **Operator** — ∂_μ, □

### §5.4 Value-domain taxonomy

- **Simple-scalar value** — single number with units or dimensionless
- **Set-based** — value drawn from continuous interval
- **Discrete** — value drawn from finite enumeration
- **Function-form** — specific functional choice
- **Tensor-field** — tensor field over the manifold

Notation rule: most compact form available; full math in deep-pass or paper.

### §5.5 Worked examples (illustrative; populated at Step 2)

| ID | Quantity | Type | Value-domain | Dimension | Sample corpus values |
|---|---|---|---|---|---|
| MU-001 | η_B/s | Scalar | Simple-scalar | Dimensionless | 8.65 / 8.8 / 9.2 / 9.42 × 10⁻¹¹ across cluster |
| MU-002 | M* | Scalar | Simple-scalar | GeV | M_Pl, ~0.4 M_Pl, ~10⁻⁷ M_Pl across cluster |
| MU-003 | g_μν | Rank-2 symmetric tensor | Tensor-field | Dimensionless (signature dep.) | Background-dependent |
| MU-004 | R | Scalar | Simple-scalar / Function-form | GeV² | FRW form dependent on a(t) |
| MU-005 | T_G | Scalar | Simple-scalar | GeV⁴ | Teleparallel Gauss-Bonnet |
| MU-006 | Λ_CPV | Scalar | Simple-scalar | TeV | Liu-Qin-Bian ≳ 338 TeV |
| MU-007 | f(R,…) | Function | Function-form | Model-dep. | Multiple specific forms |

### §5.6 Scope boundaries

IN: cross-paper comparability quantities; geometric/tensorial quantities central to framework comparisons; fundamental constants with conditional-variability status in UMF; paper-specific functional forms.

OUT: trivial numerical prefactors unless decision-weighted; standard textbook constants without program-specific context.

### §5.7 Source-content rules

- New entries when a corpus deliverable assigns a value or introduces a typed quantity
- Per-paper value entries when papers report specific assignments
- Superseded values flagged; original retained
- Held-aside entries permitted with reason
- Comparability notes mandatory

---

## §6 Cross-index linkage rules

- Every Index 3 entry has Definition pointer → Index 1 entry (CD-NNN). If no Index 1 entry exists, Step 2 creates one before populating the Index 3 entry.
- Index 2 bilateral edges (§4.3) and joint-citation clusters (§4.8) reference Index 1 terms (by ID) and Index 3 quantities (by ID) where relevant.
- Index 1 entries that carry modal weight are referenced from Index 2 modal-tier edges and from §4.8 cluster modal-status fields.
- OP-Adj entries cross-referenced from Index 2 §4.8 clusters where adjudications triggered the cluster (e.g., Stephen Issue 2 → CR-JC-0006).
- OP-Item entries cross-referenced from Index 2 edges/clusters that bear on the Item's substantive content (e.g., F-05 cluster edges → CD-OP-Item-005).
- Circular references permitted; each entry stands on its own.
- All cross-references implemented as hyperlinks per §7 hyperlinking provisions.

---

## §7 Hyperlinking provisions

### §7.1 Stable IDs as the durable cross-reference target

Every entry carries a stable ID (CD-OP-NNN, CD-TH-NNN, CD-OP-Adj-NNN, CD-OP-Item-NNN, CR-NNNN, CR-JC-NNNN, MU-NNN). IDs survive folder restructure, filename changes, and version increments.

### §7.2 ID-only headings for clean anchor generation

Each entry is headed by its ID only, with term and other fields as field-labelled body content. Auto-generated markdown anchor is stable: `#cd-op-001`, `#cr-jc-0006`, etc.

### §7.3 Within-file links

Format: `[CD-OP-001](#cd-op-001)`

### §7.4 Between-file links (inter-index)

Format: `[CD-OP-001](UMF_Trial_S3M0S1_Index1_ContextDefinition_v{N}.md#cd-op-001)` where `{N}` is the actual referenced version.

### §7.5 Version pinning

Cross-reference target version is hard-coded per audit-trail integrity. Updates only when referenced content changed.

### §7.6 Cross-reference manifest per index

Each index document ends with an outgoing-cross-reference manifest table:

| Outgoing link from | Target file | Target version | Target anchor | Purpose |
|---|---|---|---|---|

Two purposes: audit-trail traceability; deployment-readiness (scriptable bulk update).

### §7.7 Pure markdown; no external HTML

All hyperlinking uses standard markdown link syntax. Renders in GitHub, VS Code, pandoc, and most markdown editors.

### §7.8 External corpus document hyperlinking (NEW v3)

Indexes link not only to each other but also to substantive corpus documents (Scaffold v{N}; Research Plan v{N}.{M} Draft DOCX; VC v0.35 Amendment {N} markdown; Thread Handoff v{N} markdown; deeppass reports; deeppass addenda).

**Markdown corpus documents (Scaffold, Amendments, Handoff, deeppass, deeppass addenda):**

- Format: `[Scaffold §5.2](UMF_Trial_S3M0S1_Synthesis_Paper_Scaffold_v{N}_consolidated.md#section-5-umf-g-shock-matter-creation-mechanism)` — markdown anchor auto-generated from heading text (lowercased, hyphenated, special characters dropped)
- Where heading text is unstable or anchor-fragile (e.g., headings with em-dashes, parentheses, or version annotations), use section-number text reference without anchor: `Scaffold v8 §5.2` as inline text with filename in parenthetical link
- Section-number references preferred over heading-text anchors for resilience to heading-text edits

**DOCX corpus documents (Research Plan v{N}.{M} Draft):**

- DOCX files do not support standard markdown anchors. Link is to filename only: `[Research Plan v0.6 §3](UMF_Trial_S3M0S1_Research_Plan_v0_6_Draft.docx)`
- Section number provided as inline text reference; reader opens DOCX and navigates manually
- Bookmark-based DOCX anchors are technically possible but not portable across markdown renderers; not used

**Cross-reference manifest §7.6 extends to external corpus links.** Each outgoing link to a substantive corpus document recorded in the manifest with target version pinned.

**Version pinning of external corpus links.** Same rule as §7.5: hard-coded target version per audit-trail integrity. When Scaffold advances v8 → v9, index cross-references update only if the referenced section content changed. The mechanical bulk-update is scriptable via the manifest.

---

## §8 Naming convention and audit-trail integrity

Filenames (Stephen-approved 27 May AEST):

- `UMF_Trial_S3M0S1_Index1_ContextDefinition_v{N}.md`
- `UMF_Trial_S3M0S1_Index2_ContextRelationships_v{N}.md`
- `UMF_Trial_S3M0S1_Index3_MetricUnits_v{N}.md`

Each index versioned independently. Per consolidation cycle, only those touched produce new versions. Prior versions retained per audit-trail integrity.

Audit-trail rules:
- No in-place edits to active entries once populated. Versioned supersessions only.
- Superseded entries: Status=Superseded with pointer to replacement.
- Per-entry First-introduced field records the version / Amendment / Stephen-direction date.
- Each index document carries its own audit-trail header listing version history.
- Cross-reference manifest §7.6 maintained per index document.

---

## §9 Cross-program portability provisions

### §9.1 Dual-tagging (per Stephen 27 May AEST answer f)

Entries may carry both Generic AND UMF-specific tags simultaneously when the structural form is generic but a specific instance is UMF-anchored. Tagging rule:

- **Generic** — schema-level entry has program-portable structure
- **UMF-specific** — entry contains UMF-specific content not portable as-is
- **Both** — schema is Generic, instance content is UMF-specific (e.g., Stream 3 methodology is generic; its UMF instantiation is UMF-specific)

This supports fair and honest disclosure of what is reusable as-is vs what requires adaptation.

### §9.2 Cross-program forking procedure

1. Fork the indexes
2. Retain entries marked Generic and the schema-level of entries marked Both
3. Remove entries marked UMF-specific
4. Adapt instance content of entries marked Both
5. Adapt Index 2 controlled vocabulary in §4.4 as required
6. Adapt Index 2 §4.8 joint-citation cluster names as required
7. Populate program-specific terms, papers, and metric units

One instance per program; cross-program ID-level references only if explicitly authorised.

---

## §10 Modal-status and framing-bias handling

- Index 1 entries that carry modal weight populate the Modal-status field per §3.3.1 convention; free-text permitted.
- Index 2 bilateral-edge annotations and §4.8 cluster annotations preserve modal status of underlying corpus claim.
- Index 3 entries with naturalness/tuning status report observed values neutrally.
- Framing-bias correction #4 (modal-status preservation) applies to all index entries.
- OP-Adj entries record Stephen adjudications verbatim where corpus preserves the quote; paraphrase only where verbatim unavailable.

---

## §11 Step 2 production plan

Step 2 produces:

1. **Three populated indexes** as standalone markdown files per §8, with hyperlinking per §7 (including §7.8 external corpus linking)
2. **Index 1 sub-subdivisions populated:**
   - OP entries — methodology, source-quality tiers, modal-status conventions, cluster taxonomy, **matrix-entry series taxonomy (A/B/D/F + Theme A/B/C + Tier 1/2)**, etc.
   - TH entries — theoretical context terms
   - **OP-Adj entries — 19 Stephen adjudications populated from existing corpus**
   - **OP-Item entries — 7 follow-up Items populated from Scaffold §11.3**
3. **Index 2 §4.8 joint-citation clusters populated** — 13 clusters per Scaffold §14.1 count
4. **Cross-reference manifests** within each index document per §7.6
5. **New Amendment** (provisionally Amendment 11) anchoring the populated indexes plus the three corrections from this thread:
   - Document-internal sequencing nuance correction (Amendment 10 §2)
   - Samaddar-Singh η_B/s = 9.42 × 10⁻¹¹ characterisation sharpening
   - Paper 3 Table-2 / text inconsistency claim — unverifiable-in-this-thread acknowledgement
6. **Scaffold v9** if required — may not be necessary if corrections anchored at Amendment 11 only and Scaffold deferred to Step 3
7. **Research Plan v0.7** — captures index-anchoring and corrections
8. **Handoff v7** — supersedes Handoff v6

Step 2 anticipated to fit within a single thread provided no PDFs uploaded (per Handoff v6 §13 thread-load risk).

Step 3 (later cycle) — Scaffold §3–§13 modularisation.

---

## §12 Stephen resolutions + new open questions

### §12.1 Resolutions from v1 (Stephen 27 May AEST)

| ID | Question | Stephen resolution | v3 location |
|---|---|---|---|
| (a) | Naming-convention check | Approved | §8 |
| (b) | Foundational-references scope | Include as informative | §3.5; §4.5 |
| (c) | Held-aside entries | Include with reason note attached; retain for follow-up | §3.3 Held-aside-reason field; §4.5; §5.7; §4.8 |
| (d) | Modal-status field granularity | Free-text with consistency convention | §3.3 Modal-status field + §3.3.1 convention table |
| (e) | Set-based value-domain notation | Most compact notation; math lives in deep-pass or paper | §5.4 notation rule |
| (f) | Cross-program portability dual-tagging | Dual-tagging — fair and honest, do both | §9.1 |
| (g) | Hyperlinking provisions for deployment-readiness | Implemented per 7-point design plus §7.8 external corpus linking | §7 |

### §12.2 New open questions raised in v3 Scaffold inspection (Stephen decision needed)

| ID | Question | v3 default treatment | Awaited Stephen direction |
|---|---|---|---|
| (h) | Verbatim primary-source citations (85+) — separate Citations Index? | Not currently in scope of three indexes; leave in Scaffold §13.2 and Scaffold prose as reference list | Confirm leave-in-Scaffold OR authorise Index 4 production for deployment integrity (e.g., to support copyright-compliance search and fabrication-avoidance audits) |
| (i) | Framework-level honest-disclosure flags (e.g., "A-01 60-80 OoM scale gap"; "F-08 contested empirical engagement"; "A-01 classical-geon stability") — placement? | Default: leave in Scaffold prose; Index 1 OP entries cover the flag *type* definitions; Scaffold prose covers specific *applications* | Confirm leave-in-Scaffold OR authorise Index 1 third subdivision FA (Framework-Annotation) for searchable per-framework flag retrieval |
| (j) | Held-aside entry review cadence | Default: held-aside entries reviewed at each consolidation cycle; reason field updated if status unchanged; no separate standing rule needed | Confirm default OR authorise §4.9-class standing rule with explicit cadence (e.g., per Amendment) |

---

## §13 What this specification IS and IS NOT

**IS:**
- Design contract for three navigation-layer indexes including §4.8 joint-citation clusters sub-section
- Step 1 of incremental implementation of option (C) index-centric reorganisation
- Cross-program-portable in schema, UMF-specific in initial population
- Audit-trail-compliant (versioned supersession; held-aside provisions; cross-reference manifests; version-pinned external corpus links)
- Deployment-ready (hyperlinking provisions support folder restructure via mechanical find-and-replace; both inter-index and external-corpus links)

**IS NOT:**
- A populated index — Step 2 produces the actual entries
- A substitute for any existing corpus deliverable
- An Amendment-anchored substantive deliverable — design work preceding Amendment 11
- A commitment to specific index content or framework-comparison conclusions

---

## §14 Status at v3 close

Design specification ready for Stephen review. All Step 1 open questions resolved (§12.1). Five high-priority gap additions integrated (joint-citation clusters; matrix-entry series taxonomy flagging; external corpus document hyperlinking; Stephen adjudications registry; open follow-up Items registry). Three new open questions surfaced for Stephen decision (§12.2). No corpus content produced. No Amendment anchor. Awaiting Stephen direction:

- Approve v3 with §12.2 default treatments → proceed to Step 2 production
- Approve v3 with §12.2 alternatives → spec v4 minor delta then proceed
- Revise v3 → identify changes; produce v4 design spec
- Defer → park pending other direction

---

*End of UMF_Trial_S3M0S1_Indexes_Design_Spec_v3.md*
