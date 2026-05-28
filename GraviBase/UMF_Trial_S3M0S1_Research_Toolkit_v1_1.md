# UMF Trial S3M0S1 — Research Toolkit v1.1

**Document version:** v1.1 (supersedes v1.0; CD-OP-040 filename updates + Index v1→v2 references + Amendment 13 audit-trail anchor)
**Date:** 28 May 2026 (AEST)
**Working language:** Australian English (per standing rule v0.35)
**Page format target:** A4 when converted to DOCX/PDF
**Trial:** UMF Trial S3M0S1
**Author of trial:** Stephen L Browne
**Drafter:** Claude Opus 4.7 Adaptive (Anthropic)
**Audit-trail anchor:** VC v0.35 Amendment 13 (filename alignment cycle + CD-OP-040 convention registration); Amendment 14 (hyperlink completeness cycle) pending registration
**Predecessor:** UMF_Trial_S3M0S1_Research_Toolkit_v1_0.md (retained unchanged per CD-OP-004); upstream predecessors UMF_Trial_S3M0S1_Research_Toolkit_v0_1_Draft.md and UMF_Trial_S3M0S1_Research_Toolkit_v0_2_Draft.md also retained
**Companion document:** [UMF_Trial_S3M0S1_Research_Toolkit_Addendum_v1_1.md](companion-documents/UMF_Trial_S3M0S1_Research_Toolkit_Addendum_v1_1.md) (in `companion-documents/` subfolder; supersedes v1.0)

**Status:** Second release. Supersedes v1.0 with: (i) CD-OP-040 filename updates throughout (Samaddar, Pereira, Whittingham, Liu paths no longer carry `Paper{N}` element; reference labels updated correspondingly); (ii) Index 1/2/3 references updated v1 → v2 (25 instances); (iii) Companion document reference updated v1.0 → v1.1; (iv) §9 version history extended with v1.1 entry. v1.0 retained as predecessor per CD-OP-004 audit-trail integrity. Companion to Index 1 v2 + Index 2 v2 + Index 3 v2 + Toolkit Addendum v1.1 + Scaffold v9 (this thread's hyperlink completeness cycle).

**Substantive scope unchanged from v1.0:** This is a navigation-layer / cross-reference update only. No changes to methodology specification (§2), protocols (§3), navigation-layer architecture (§4), VC workflow (§5), cross-program portability provisions (§6), or format/deployment conventions (§7).

**Deployment layout:** Toolkit, three Indexes, and VC Amendments deployed in parent directory (`/GIRT/` folder). Specifications (Spec v3), substantive corpus (Scaffold, Research Plan, Introduction Letter, Thread Handoff), and Toolkit Addendum deployed in `companion-documents/` subdirectory. Deep-review reports deployed in `deep-review-reports/` subdirectory. Master VC running file and individual VC Amendment files deployed in `version-control/` subdirectory. All cross-references use Spec v3 §7 hyperlinking conventions. From this file's location (`/GIRT/`), relative paths to `deep-review-reports/` use `./deep-review-reports/...` (per Stephen 28 May AEST GitHub deployment verification on Index 1 v2).

---

## Abstract

This document is the Research Methodology Toolkit developed across the UMF Trial S3M0S1 research programme. The Toolkit specifies the operational methodology, protocols, three-index navigation-layer architecture, version-control workflow, cross-program portability provisions, and deployment conventions developed in the trial work. It serves two purposes: as the consolidated reference for the methodology layer that governs UMF Trial S3M0S1; and as a reusable methodology framework deployable to other research programs.

The Toolkit covers what to do — the disciplines (§2), protocols (§3), navigation layer (§4), version-control workflow (§5), cross-program portability provisions (§6), and format/deployment conventions (§7). UMF-program-specific content — postulate registry, substantive findings summary, trial-state counts at Amendment 12 close, selected headline findings, Stephen direction history, pending items requiring author input, substantive-corpus listing and pointers — is in the companion document [UMF_Trial_S3M0S1_Research_Toolkit_Addendum_v1_1.md](companion-documents/UMF_Trial_S3M0S1_Research_Toolkit_Addendum_v1_1.md) in the `companion-documents/` subfolder.

The methodology in §2 + §3 + §4 + §5 + §6 + §7 is generic and program-portable in schema; per the LLM-context discipline (§6.3), readers operating in non-UMF contexts treat the Toolkit content as operative and the Addendum content as illustrative only. Cross-program forking procedure is at §6.2. The Toolkit is a covering document, not a substitute for the substantive corpus (Scaffold, Research Plan, Amendments, Introduction Letter, deeppass reports), which remains in the trial corpus per audit-trail integrity (§2.4).

---

## §1 Purpose and scope

This Toolkit specifies the operational methodology, protocols, and navigation-layer architecture developed across the UMF Trial S3M0S1 research programme. The Toolkit serves two functions:

1. **For UMF Trial S3M0S1:** consolidated reference for the methodology layer that governs trial work. UMF-program-specific content — postulate registry, substantive findings summary, trial-state counts, headline findings, Stephen direction history, pending items, substantive-corpus listing — is in the companion [Toolkit Addendum](companion-documents/UMF_Trial_S3M0S1_Research_Toolkit_Addendum_v1_1.md). Substantive UMF findings remain in Scaffold v8, Research Plan v0.7, Amendments 7–12, deeppass reports, and Introduction Letter v2; all referenced from the Addendum.

2. **For other research programs:** reusable methodology framework. The disciplines, protocols, index design, and audit-trail conventions are program-portable in schema; the UMF-specific instance (presented in the Addendum) demonstrates one full deployment.

The Toolkit is the *covering document* — the entry point that organises the rest of the corpus. It does not duplicate substantive content; it indexes it.

The Toolkit is **not** a draft of any substantive research output. It is not a substitute for the Scaffold (synthesis-paper structural outline), Research Plan v0.7 (substantive corpus deliverable), or any Amendment (audit-trail anchor).

**Audience:** researchers running corpus-bounded, audit-trailed, modal-status-preserving research programs, with or without LLM drafting support. Specific deployment patterns assume LLM-context discipline (controlled-synthesis-injection vs uncontrolled-synthesis-creep) but core methodology applies independently.

---

## §2 Methodology framework

### §2.1 Corpus-bounded discipline (Stream 3 instance)

The trial operates under a corpus-bounded methodology designated Stream 3 in the UMF deployment. Generic schema:

- Confined to a defined document corpus
- No adjacent literature search unless explicitly authorised (modified per CD-OP-016 corpus-currency due-diligence standing rule, §3.6)
- Honest reporting of negative findings required
- Significance thresholds defined (UMF instance: 5σ / 4σ / 2σ–3σ)
- Specific framework elements may be designated as permanently rejected (UMF instance: variable speed of light)
- Parallel-track concepts tracked separately and not conflated with active modules

Departures from any element require explicit authorisation from the trial author. Modal status preserved per §2.2.

Generic schema; UMF instance is one realisation. See Index 1 [CD-OP-001](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-001).

### §2.2 Modal-status preservation

Standing-rule requirement that the modal status of statements (committed / possible / open / disclaimed, etc.) is preserved when translating engineering language to scientific language, or when integrating new corpus content into deliverables.

Failure mode: promoting hedged claims ("may," "by some means," "possibly") to commitments ("does," "via," "predicts"); promoting candidate consequences to mechanisms; promoting possibilities to predictions. Recorded in UMF Trial as framing-bias correction #4.

Convention table (Index 1 [CD-OP-021](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-021) through CD-OP-026):

| Convention term | Usage |
|---|---|
| committed | Formally adopted at postulate or assumption level |
| possible candidate territory | Plausible but not committed |
| open question | Flagged for future technical development |
| held aside | Flagged for review but not currently in active scope |
| disclaimed | Explicitly rejected by framework |
| informative | Included for context but not load-bearing on framework |

Other phrasings permitted where corpus introduces them; this table records established usage for cross-entry consistency.

Required action: at every integration of new content, self-check whether modal status of source has been preserved. Where overreach detected, correct and log as framing-bias correction (§2.3). When in doubt, use the weaker (more honest) interpretation.

Generic discipline. See Index 1 [CD-OP-002](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-002).

### §2.3 Framing-bias correction

Logged correction to a framing failure mode in trial work. Self-check for framing-bias **bidirectionality** at every integration cycle: both pro-framework and anti-framework framing are symmetric failure modes of the same pre-judging-by-framing structure. Distinguish *verified absence* / *verification pending* / *verified presence*; promoting "pending" to "verified absence" requires actual body access.

Four corrections in the UMF Trial demonstrate the failure-mode taxonomy:

1. **Pro-framework framing of external source** — pre-judging an external paper as supportive on framing grounds before body verification
2. **Anti-prior-thread framing without body verification** — pre-judging prior-thread content as wrong before body verification
3. **Over-extension of trial-author position scope** — extending the trial author's stated position beyond what was actually said
4. **Modal-status promotion in translation** — promoting hedged claims to commitments during corpus integration

The four share structure: *over-specification of the trial-author's position* but differ in axis (interpretive stance; prior-thread content correctness; content scope; modal status).

Generic discipline; the failure-mode taxonomy is portable. See Index 1 [CD-OP-003](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-003).

### §2.4 Audit-trail integrity

Standing rule that all trial deliverables are versioned with no in-place edits. Superseded documents retain original content unchanged; successors carry new version numbers. Historical filenames retained verbatim. The trial directory grows monotonically.

Required action: before any document change, produce a new versioned document. Never edit a published deliverable in place. Mark superseded deliverables with status pointer to replacement. Applies equally to Toolkit, Toolkit Addendum, Indexes, Scaffold, Research Plan, Amendments, deeppass reports, Handoff.

Generic discipline. See Index 1 [CD-OP-004](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-004).

### §2.5 Controlled-synthesis-injection vs uncontrolled-synthesis-creep

Distinction operative for any research programme where the trial author introduces specific framework commitments (postulates, assumptions, working positions) that other readers — particularly LLMs in adjacent contexts — should not adopt by default.

**Controlled synthesis injection** (Index 1 [CD-OP-005](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-005)): explicit, transparent, recorded addition of new framework commitments by the trial author. Documented in an introduction-letter-class document and/or VC amendment. Audit-trail captures the addition with date and provenance.

**Uncontrolled synthesis creep** (Index 1 [CD-OP-006](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-006)): inadvertent introduction of framework commitments into work without explicit transparent recording. Failure mode to be actively guarded against. Active guard required at every integration cycle.

**Portable meta-instruction pattern:** the introduction-letter-class document carries a NOTICE binding readers as follows: an LLM working in the trial's framework treats injected commitments as operative; an LLM working in a non-trial or adjacent framework ignores them. The NOTICE travels with the corpus. This is the mechanism by which corpus content can be transferred to adjacent contexts (e.g., methodology lifted into this Toolkit) without dragging framework commitments with it.

UMF deployment: Introduction Letter v2 NOTICE binds LLMs working in UMF framework vs non-UMF context. Pattern is generic and reusable.

### §2.6 Honest-disclosure correction

Logged correction to a corpus content claim that, on review, was found to be insufficiently neutral, insufficiently caveated, or insufficiently nuanced relative to underlying source material.

Standing rule: empirical findings positive or negative are welcome. When review identifies that prior content overstated, understated, or omitted material caveats, produce a correction with version stamp.

Distinct from provenance correction (§2.7), which addresses attribution errors rather than substance.

Generic discipline. UMF Trial currently records 5 honest-disclosure corrections; specific corrections enumerated in the Addendum §4.

See Index 1 [CD-OP-012](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-012).

### §2.7 Provenance gate

Verification check before any verbatim citation is deployed: attribution must trace to a specific verified source. Failed provenance gates result in declined deployment.

Before deploying any verbatim citation: verify attribution against actual source. If provenance unverifiable, decline deployment or downgrade to paraphrase with explicit "attribution unverifiable" flag.

Provenance corrections (logged corrections to attribution error or provenance gap) tracked separately from honest-disclosure corrections. Labelling clarifications (nomenclature shorthand that could be misread but underlying content remains correct) tracked separately again.

Generic discipline. See Index 1 [CD-OP-013](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-013), [CD-OP-014](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-014), [CD-OP-015](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-015).

### §2.8 Scope-expansion authorisation

Explicit trial-author authorisation required for trial scope to expand beyond previously-defined boundaries. Distinct from corpus-currency due-diligence (§3.6), which does not require fresh authorisation per cycle.

Required action: when work would extend beyond current trial scope, request explicit direction. Routine corpus-currency cycles on author-supplied review lists are not scope-expansion events.

Generic discipline. See Index 1 [CD-OP-007](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-007).

---

## §3 Operational protocols

### §3.1 Mandatory bundle for thread initialisation

When the research is run with LLM drafting support across multiple sessions, a mandatory bundle of documents must be loaded at any session initialisation:

- Current Thread Handoff (trial-state recovery)
- Introduction-Letter-class document (controlled-synthesis-injection NOTICE)
- Current VC Amendment + prior anchor Amendments
- Current Scaffold (synthesis paper structural outline)
- Current Toolkit (this document) + current Addendum (companion document)
- Three Indexes (current versions)
- Relevant deeppass reports
- Predecessor Research Plan (substantive corpus content)

Initial response on resumption: acknowledge reading complete; report any provenance concerns surfacing during read; confirm awareness of current trial-state; do not initiate new work absent author direction.

Generic discipline. UMF Trial mandatory bundle 18 items per Handoff v8 §3. See Index 1 [CD-OP-011](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-011).

### §3.2 Per-paper deeppass-report convention

Any future body-access deep-pass treatment of a paper produces a standalone deeppass report **before** consumer-document integration.

Naming convention: `F-{matrix-entry-ID}_Paper{N}_{Author}{year}_{ReviewLabel}_deeppass.md` or trial-specified alternative.

Deployment: in subfolder `deep-review-reports/`.

The deeppass report serves as the proof-of-research-provenance artefact for any future thread or external reviewer to verify independently of consumer documents what was read, what was extracted, what was inferred, and at what depth.

Deeppass report content typically: paper provenance; reading status; paper structure; mechanism; numerical results; honest-disclosure observations; corpus mapping; open-item implications; modal-status preservation self-check; new cross-references identified.

UMF deployment: 5 deeppass reports currently in trial corpus (Paper 2 Pereira; Paper 3 Samaddar-Singh + Addendum; Paper 5 Whittingham; Paper 8 Liu-Qin-Bian).

See Index 1 [CD-OP-009](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-009).

### §3.3 Deeppass-addendum convention

For supplementary or corrective deeppass content needed after the anchor deeppass is produced: generate a deeppass addendum rather than retroactively editing the anchor. Preserves audit-trail integrity.

Naming convention: anchor filename + `_Addendum`. Cross-reference between anchor and addendum maintained.

UMF deployment: Paper 3 Samaddar-Singh deeppass + Addendum demonstrates the pattern. The Addendum captured peer-review-status verification finding without modifying the anchor.

See Index 1 [CD-OP-010](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-010).

### §3.4 Peer-review-status verification protocol

Web-search-based verification of journal-publication status for preprint papers in corpus. Performed when quality concerns or "suspect data" signals arise from manuscript-internal observations.

Triggering condition: body-access deeppass surfaces ≥2 substantive quality concerns. Procedure: perform peer-review-status verification; record search queries used; results; absence of journal publication record after meaningful interval flagged.

Joint characterisation: manuscript-internal concerns + absence of independent peer-review correction supports "preprint-only with quality concerns" tier.

UMF deployment: applied to Samaddar-Singh 2025 (arXiv:2512.06009). Six manuscript-internal concerns + ~5 months on arXiv without journal publication = preprint-with-quality-concerns characterisation.

See Index 1 [CD-OP-008](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-008).

### §3.5 Source-quality tiering

Source-quality classification operative for corpus content:

| Tier | Definition | Index 1 entry |
|---|---|---|
| Peer-reviewed | Paper published in peer-reviewed journal of record | CD-OP-017 |
| Preprint-only | Available on arXiv or similar but not yet peer-reviewed | CD-OP-018 |
| Preprint-with-strong-internal-quality | Preprint + strong internal quality indicators (length, classification, self-consistency checks, institutional affiliation, clear submission trajectory) | CD-OP-019 |
| Preprint-with-quality-concerns | Preprint + manuscript-internal quality concerns + absence of peer-review correction after meaningful interval | CD-OP-020 |

Downstream deployment of preprint-only content carries the preprint-status caveat. Tier characterisation does not validate or invalidate framework claims; informs corpus-discipline awareness of source heterogeneity.

Generic; portable to any program tracking literature.

### §3.6 Corpus-currency due-diligence

Routine research-hygiene activity: periodic verification on author-supplied review lists that corpus is current with relevant published / preprinted work.

Web-search access for this purpose implicitly authorised (per standing rule established in UMF Amendment 9 Addendum §7.5). Does NOT require fresh scope-expansion authorisation per cycle.

When author supplies a review list or PDFs for verification: treat as routine due-diligence; no fresh scope-expansion authorisation requested. Triage outcomes recorded per cycle.

Generic discipline. UMF Trial currently has two complete cycles (post-Jan 2026 reading layer per Amendment 9; AdjacencyReview2026 per Amendment 10). See Index 1 [CD-OP-016](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-016).

### §3.7 ESCALATE matrix discipline

New substantive scope additions (new framework / paper / concept entries beyond current corpus) require explicit scope-expansion authorisation. Sub-list updates and reference-list extensions under corpus-currency due-diligence are not ESCALATE-class events.

Generic discipline. UMF Trial holds substantive matrix at 26 entries; no ESCALATE additions across last several cycles. See Index 1 [CD-OP-029](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-029), [CD-OP-030](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-030).

---

## §4 Three-index navigation layer

The Toolkit deploys a three-index navigation layer over the substantive corpus. Indexes do not duplicate substantive prose; they organise it under typed structures for decision-aid lookup.

**Canonical design contract:** [UMF_Trial_S3M0S1_Indexes_Design_Spec_v3.md](companion-documents/UMF_Trial_S3M0S1_Indexes_Design_Spec_v3.md) (in `companion-documents/` subfolder) — read this for full schema definitions, scope boundaries, hyperlinking provisions, and cross-program portability rules. Summary architecture follows.

### §4.1 Index 1 — Context Definition

Consolidated lookup of operational AND theoretical context terms used across the research program. Schema covers:

- **OP entries** — operational context terms (methodology, governance, conventions, source-quality tiers, modal-status conventions, cluster taxonomy, series taxonomy)
- **TH entries** — theoretical context terms (physics-of-the-topic-domain terms operative for cross-paper comparability)
- **OP-Adj sub-subdivision** — trial-author adjudications registry (discrete decision-points constraining downstream work; date, scope, decision content, downstream effect, verbatim where preserved)
- **OP-Item sub-subdivision** — open follow-up items registry (substantive open questions tracked across versions, each with own evolution)

Each entry stable ID format: `CD-OP-NNN`, `CD-TH-NNN`, `CD-OP-Adj-NNN`, `CD-OP-Item-NNN`.

Current UMF deployment: [Index 1 v2](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md) — 86 entries (39 OP + 21 TH + 19 OP-Adj + 7 OP-Item).

### §4.2 Index 2 — Context Relationships

Typed edge list of relationships between papers, frameworks, and concepts. Architecture choice: edge list (filterable, extensible) over n×n adjacency matrix (sparse, hard to maintain).

Edge type families: Foundational, Programme-coordinated, Framework-class, Structural (extends / refines / contests / parallel / orthogonal), Citational, Parameter-regime, Modal-tier.

Sub-section **§4.8 Joint-citation clusters (CR-JC-NNNN)**: hyperedges of ≥2 member nodes deployed together against a single framework commitment. These cannot be cleanly decomposed to bilateral edges without losing cluster identity.

Each entry stable ID format: `CR-NNNN` for bilateral edges; `CR-JC-NNNN` for joint-citation clusters.

Current UMF deployment: [Index 2 v2](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md) — 65 relational entries (52 bilateral + 13 joint-citation clusters).

### §4.3 Index 3 — Metric Units

Inventory of typed measurable / parameterised quantities used across the program. Each entry: quantity → mathematical type (scalar / vector / tensor / function / operator) → value-domain (simple-scalar / set-based / discrete / function-form / tensor-field) → physical dimension → definition pointer to Index 1 → values across corpus papers/frameworks → comparability notes → naturalness/tuning status.

Each entry stable ID format: `MU-NNN`.

Current UMF deployment: [Index 3 v2](UMF_Trial_S3M0S1_Index3_MetricUnits_v2.md) — 32 metric-unit entries (cluster-comparability scalars, geometric/tensorial quantities, gravity-modifying functions, fundamental constants, paper-specific tuning parameters, constraint scales, set-based parameters).

### §4.4 Cross-index linkage

Index 3 entries reference Index 1 for definitions; Index 2 edges and clusters reference Index 1 terms and Index 3 quantities; Index 1 modal-status and adjudication entries are referenced from Index 2 annotations. Each entry stands on its own; circular references permitted.

**Worked navigation example** (decision-aid lookup):
1. Open Index 1 → relevant OP-Item or OP-Adj entry → see current statement, status, awaited direction, modal status
2. Follow cross-reference to Index 3 → row for relevant quantity → see all values assigned across corpus with paper/framework provenance
3. Open Index 2 → filter by edges referencing the quantity → see parameter-regime / framework-class / modal-tier edges
4. Open Index 2 §4.8 → joint-citation clusters that deploy frameworks against the relevant commitment
5. Navigate to substantive corpus prose (Scaffold / Research Plan / Amendments / deeppass reports) for full substantive content

---

## §5 VC Amendment workflow

Version Control (VC) Amendments are the audit-trail anchors for trial state at successive cycles. The Amendment series is append-only; prior Amendments retain original content per audit-trail integrity (§2.4).

### §5.1 Cycle pattern

Each substantive deliverable cycle follows the pattern:

1. **Scope direction** from trial author (e.g., authorise new reading layer; authorise body-access on paper N; authorise new deliverable type)
2. **Production** of cycle deliverables (Scaffold update, Research Plan / Toolkit / Addendum update, deeppass reports, Index updates as relevant)
3. **VC Amendment anchor** capturing the cycle outcome: material changes; trial state at close; standing-rule updates; self-checks performed; items rolled forward
4. **Handoff update** capturing new trial state for any future thread initialisation

### §5.2 Amendment content schema

Each Amendment typically covers:
- §1 Amendment scope + production reason
- §2 Source documents added / updated
- §3 Material changes captured (substantive findings; corrections; integrations)
- §4 Trial state at close (identity; counts; status of phases; postulate registry; standing rules)
- §5 Standing rules (reaffirmed; newly established; clarifications)
- §6 Self-checks performed (provenance gate; audit-trail integrity; framing-bias bidirectionality; modal-status preservation; scope-discipline)
- §7 Items rolled forward to next cycle

### §5.3 Addendum pattern

When supplementary or corrective Amendment content is needed: generate an Amendment Addendum rather than editing the anchor Amendment. UMF deployment: Amendment 9 Addendum demonstrates this for the deeppass-report convention re-affirmation + framing correction (corpus-currency due-diligence vs scope-expansion).

UMF Trial currently has Amendments 7 through 12 in the series; Amendment 12 is the current anchor (Toolkit v1.0 + Addendum v1.0 release).

---

## §6 Cross-program portability

### §6.1 Dual-tagging

Index 1 entries carry per-entry **Cross-program portability** field with values:

- **Generic** — schema-level entry has program-portable structure; entry content is reusable as-is
- **Program-specific** (UMF-specific in this deployment) — entry contains program-specific content not portable as-is
- **Both** — schema is Generic, instance content is program-specific (e.g., Stream 3 methodology schema is Generic; UMF instantiation is UMF-specific)

This supports fair and honest disclosure of what is reusable as-is vs what requires adaptation.

### §6.2 Forking procedure

For deployment of the Toolkit + Indexes to a different research program (per Spec v3 §9.2):

1. Fork the Toolkit + Indexes
2. Retain entries marked Generic and the schema-level of entries marked Both
3. Remove entries marked program-specific
4. Adapt instance content of entries marked Both
5. Adapt Index 2 controlled vocabulary as required
6. Adapt Index 2 §4.8 joint-citation cluster names as required
7. Populate program-specific terms, papers, and metric units
8. Replace the Toolkit Addendum (UMF-specific) with a program-specific Addendum

One instance per program; cross-program ID-level references only if explicitly authorised.

### §6.3 LLM-context discipline

When the research is run with LLM drafting support, an introduction-letter-class document carries a NOTICE meta-instruction (§2.5). The NOTICE distinguishes:

- LLM working in the program's framework: treats program commitments as operative
- LLM working in a non-program or framework-neutral context: ignores program commitments

The NOTICE travels with the corpus and is portable. For the Toolkit specifically: the methodology layer in §2 + §3 + §4 + §5 + §6 + §7 is presented as Generic and should be treated as operative by any program using the Toolkit; the worked-example content in the Addendum is UMF-specific and should be treated as illustrative only by non-UMF readers.

---

## §7 Format and deployment

### §7.1 Markdown as working source

All Toolkit, Addendum, and Index documents are markdown. Markdown supports native hyperlinking, integrates with the existing trial corpus (which is largely markdown), and is portable across editors and renderers.

DOCX is an optional delivery format generated from markdown. Where DOCX is the delivery format, hyperlinking convention degrades per §7.2 below.

### §7.2 Hyperlinking conventions

Per Spec v3 §7:

- **Within-file links** (§7.3): `[CD-OP-001](#cd-op-001)`
- **Between-file links inter-index** (§7.4): `[CD-OP-001](UMF_Trial_S3M0S1_Index1_ContextDefinition_v{N}.md#cd-op-001)` with `{N}` the actual referenced version
- **Toolkit ↔ Addendum links** (parent/subfolder): from Toolkit, use `companion-documents/UMF_Trial_S3M0S1_Research_Toolkit_Addendum_v{N}.md#anchor`; from Addendum, use `../UMF_Trial_S3M0S1_Research_Toolkit_v{N}.md#anchor`
- **External corpus markdown documents** (§7.8): filename + heading-text-anchor where stable; section-number text reference + filename link where heading-text-fragile
- **External corpus DOCX documents** (§7.8): filename-only link; section number provided as inline text reference; reader opens DOCX and navigates manually

### §7.3 Stable IDs

Every entry carries a stable ID. IDs survive folder restructure, filename changes, and version increments. ID-only headings used in Indexes for clean auto-generated anchors.

### §7.4 Version pinning

Cross-reference target version is hard-coded per audit-trail integrity. Updates only when referenced content changed. Mechanical bulk-update scriptable via cross-reference manifest (§7.5).

### §7.5 Cross-reference manifest per index

Each index document ends with an outgoing-cross-reference manifest table recording: From | Target file | Target version | Target anchor | Purpose. Two purposes: audit-trail traceability; deployment-readiness (scriptable bulk update).

### §7.6 Deployment layout (UMF Trial S3M0S1 instance)

```
{deployment-root}/
  UMF_Trial_S3M0S1_Research_Toolkit_v1_0.md (this document)
  UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md
  UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md
  UMF_Trial_S3M0S1_Index3_MetricUnits_v2.md
  VC_v0_35_Amendment7_*.md
  VC_v0_35_Amendment8_*.md
  VC_v0_35_Amendment9_*.md (main + Addendum)
  VC_v0_35_Amendment10_*.md
  VC_v0_35_Amendment11_*.md
  VC_v0_35_Amendment12_research_toolkit_v1_0_release.md
  companion-documents/
    UMF_Trial_S3M0S1_Research_Toolkit_Addendum_v1_1.md
    UMF_Trial_S3M0S1_Indexes_Design_Spec_v3.md
    UMF_Trial_S3M0S1_Synthesis_Paper_Scaffold_v8_consolidated.md
    UMF_Trial_S3M0S1_Research_Plan_v0_7_Draft.docx
    UMF_Trial_S3M0S1_Thread_Handoff_v8.md
    UMF_Research_Program_Introduction_27May2026_v2.md
    UMF_Trial_S3M0S1_Research_Toolkit_v0_1_Draft.md (Toolkit predecessor; retained)
    UMF_Trial_S3M0S1_Research_Toolkit_v0_2_Draft.md (Toolkit predecessor; retained)
    UMF_Trial_S3M0S1_Research_Toolkit_Addendum_v0_1_Draft.md (Addendum predecessor; retained)
    UMF_Trial_S3M0S1_Thread_Handoff_v7.md (Handoff predecessor; retained)
  deep-review-reports/
    F-05_Pereira2026_PostJan2026_deeppass.md
    F-05_Samaddar2025_AdjacencyReview2026_deeppass.md
    F-05_Samaddar2025_AdjacencyReview2026_deeppass_Addendum.md
    F-05_Whittingham2026_PostJan2026_deeppass.md
    F-02_Liu2026_PostJan2026_deeppass.md
```

Parent directory contains: Toolkit, three Indexes, and VC Amendments (per Stephen direction 27 May AEST).

`companion-documents/` subdirectory contains: Toolkit Addendum, Indexes Design Spec v3, substantive corpus deliverables (Scaffold, Research Plan, Introduction Letter, Thread Handoff v8), and predecessor Toolkit + Addendum + Handoff Draft files retained per audit-trail integrity.

`deep-review-reports/` subdirectory contains: body-access deeppass reports + addenda.

Hyperlinks from Toolkit to:
- Indexes / VC Amendments (same folder): direct filename
- Addendum + companion-documents (subfolder): `companion-documents/{filename}`
- Deep-review reports (subfolder): `deep-review-reports/{filename}`

Hyperlinks from Addendum to:
- Toolkit / Indexes / VC Amendments (parent folder): `../{filename}`
- Same-folder companion documents: direct filename
- Deep-review reports (sibling subfolder): `../deep-review-reports/{filename}`

---

## §8 References and standing rules registry

### §8.1 Indexes (canonical)

- [Index 1 v2: Context Definition](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md) — 86 entries
- [Index 2 v2: Context Relationships](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md) — 65 relational entries
- [Index 3 v2: Metric Units](UMF_Trial_S3M0S1_Index3_MetricUnits_v2.md) — 32 metric-unit entries

### §8.2 Indexes Design Spec (canonical design contract)

- [UMF_Trial_S3M0S1_Indexes_Design_Spec_v3.md](companion-documents/UMF_Trial_S3M0S1_Indexes_Design_Spec_v3.md) — full schema definitions, scope boundaries, hyperlinking provisions, cross-program portability rules

### §8.3 Standing rules in effect

All standing rules registered in Index 1 OP entries. Selected list:

- Stream 3 corpus-bounded methodology (CD-OP-001)
- Modal-status preservation (CD-OP-002; framing-bias correction #4)
- Framing-bias bidirectionality discipline (CD-OP-003)
- Audit-trail integrity (CD-OP-004)
- Controlled-synthesis-injection / Uncontrolled-synthesis-creep (CD-OP-005, CD-OP-006)
- Scope-expansion authorisation (CD-OP-007)
- Peer-review-status verification protocol (CD-OP-008)
- Per-paper deeppass-report convention (CD-OP-009)
- Deeppass-addendum convention (CD-OP-010)
- Mandatory bundling at thread initialisation (CD-OP-011)
- Honest-disclosure correction (CD-OP-012)
- Provenance gate / provenance correction / labelling clarification (CD-OP-013, CD-OP-014, CD-OP-015)
- Corpus-currency due-diligence (CD-OP-016)
- Source-quality tiering (CD-OP-017 through CD-OP-020)
- Modal-status convention (CD-OP-021 through CD-OP-026)
- ESCALATE matrix discipline (CD-OP-030)
- Indexes-as-navigation-layer (per Spec v3 §1; Amendment 11 §5)
- Hyperlinking deployment-readiness (per Spec v3 §7)
- Indexes audit-trail integrity (per Spec v3 §8)
- Cross-program portability dual-tagging (per Spec v3 §9.1)
- Introduction Letter v2 mandatory bundling (per Amendment 8 §K)
- Toolkit + Addendum split deployment (per Amendment 12; this Toolkit v1.0 release)

UMF Trial substantive corpus listing is in Addendum §7.

---

## §9 Status and version history

### §9.1 Toolkit status at v1.0

First release. Approved by Stephen 27 May AEST. Audit-trail anchor: VC v0.35 Amendment 12. Companion document Addendum v1.0 released jointly.

### §9.2 Predecessor relationship

- Toolkit v0.1 Draft (`UMF_Trial_S3M0S1_Research_Toolkit_v0_1_Draft.md`) — initial production; retained unchanged per audit-trail integrity (§2.4)
- Toolkit v0.2 Draft (`UMF_Trial_S3M0S1_Research_Toolkit_v0_2_Draft.md`) — split implementation; retained unchanged per audit-trail integrity

Both predecessors retained in `companion-documents/` subfolder for audit-trail preservation.

Research Plan v0.7 Draft remains a distinct deliverable in `companion-documents/`. The Toolkit replaces only the covering-document function of the Research Plan. Substantive UMF findings in Research Plan v0.7 + Scaffold v8 + Amendments + deeppass reports + Introduction Letter v2 remain operative.

### §9.3 Future cycles

- Future Toolkit revisions produce new versioned documents (v1.1, v2.0, etc.) per audit-trail integrity (§2.4)
- DOCX format recovery available if Stephen directs (per Stephen direction 27 May AEST: "We will recover docx formatting later")
- Cross-program forking procedure available per §6.2 if Stephen authorises non-UMF program deployment
- v1.0 status was "first release" not "final"; v1.1 produced 28 May 2026 AEST per CD-OP-040 filename alignment cycle + Amendment 13 anchor

### §9.4 Drafting choices history

Full drafting-choices history (v0.1 Draft, v0.2 Draft, v1.0 release, v1.1 navigation-layer update production cycles) is in Addendum §9. Summary for v1.0 release:

1. Promoted from v0.2 Draft to v1.0 per Stephen direction 27 May AEST ("documents are approved. We can move both to V1.0 as a first release")
2. Filename pattern: `UMF_Trial_S3M0S1_Research_Toolkit_v1_0.md` (drops "Draft" suffix)
3. Addendum promoted jointly to v1.0
4. v0.1 Draft and v0.2 Draft predecessors retained unchanged in `companion-documents/`
5. VC Amendment 12 produced as audit-trail anchor
6. Handoff v8 produced; supersedes Handoff v7; updates mandatory bundle to 18 items (adds Toolkit v1.0 + Addendum v1.0; retains Research Plan v0.7 as substantive corpus)
7. Folder layout per Toolkit v0.2 Draft §7.6 unchanged; v1.0 file names updated; predecessor v0.1 + v0.2 Drafts retained in `companion-documents/`
8. Modal-status preservation re-applied throughout; no new substantive scope; no new ESCALATE matrix entries
9. Toolkit/Addendum split-deployment elevated to standing rule per Amendment 12

Summary for v1.1 navigation-layer update (28 May 2026 AEST):

1. CD-OP-040 filename convention applied: all `F-0[25]_Paper[0-9]_*_deeppass.md` references updated to convention-compliant filenames (Paper{N} element removed)
2. All Index 1/2/3 references updated v1 → v2 (25 instances) to point at current Indexes from sub-cycle A production
3. Companion document reference updated v1.0 → v1.1 to point at current Addendum from sub-cycle B production
4. No substantive scope changes; v1.0 retained as predecessor per CD-OP-004 audit-trail integrity
5. VC Amendment 13 (filename alignment cycle + CD-OP-040 registration) is the audit-trail anchor; Amendment 14 (hyperlink completeness cycle covering Indexes v2 + Addendum v1.1 + Scaffold v9 + Toolkit v1.1) pending registration in this thread
6. Master VC v1.2 (incorporating Amendment 14) pending production in this thread
7. Modal-status preservation re-applied; no new ESCALATE matrix entries; no new framing-bias correction logged (mechanical-update cycle; methodology functioning correctly)

### §9.5 Version history

| Version | Date | Author | Notes |
|---|---|---|---|
| v0.1 Draft | 27 May 2026 (AEST) | Claude Opus 4.7 Adaptive (Anthropic) | First production; single-document architecture; markdown source; same-folder indexes + `deep-review-reports/` subfolder layout; UMF worked example consolidated at v0.1 §8 |
| v0.2 Draft | 27 May 2026 (AEST) | Claude Opus 4.7 Adaptive (Anthropic) | Split into Toolkit + Addendum per Stephen direction; Abstract added; folder layout revised (companion-documents/ subfolder for specifications and substantive corpus; deep-review-reports/ stays as top-level subfolder); independent versioning for Toolkit and Addendum |
| v1.0 | 27 May 2026 (AEST) | Claude Opus 4.7 Adaptive (Anthropic) | First release. Approved by Stephen 27 May AEST. Anchored at VC Amendment 12. Addendum v1.0 released jointly. v0.1 Draft + v0.2 Draft predecessors retained in `companion-documents/` per audit-trail integrity |
| v1.1 | 28 May 2026 (AEST) | Claude Opus 4.7 Adaptive (Anthropic) | Navigation-layer update. Supersedes v1.0. CD-OP-040 filename updates applied throughout (5 Paper{N} references converted); Index 1/2/3 references updated v1 → v2 (25 instances); companion document reference updated to Addendum v1.1; §9.5 version history extended. No substantive content changes. Anchored at VC Amendment 13; Amendment 14 (hyperlink completeness cycle) pending. v1.0 retained as predecessor per CD-OP-004 |

---

*End of UMF_Trial_S3M0S1_Research_Toolkit_v1_1.md*
