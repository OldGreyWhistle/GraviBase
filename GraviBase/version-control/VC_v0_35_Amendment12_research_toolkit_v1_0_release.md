# VC v0.35 — Amendment 12
## Research Toolkit v1.0 + Toolkit Addendum v1.0 release; covering-document conversion complete; Toolkit/Addendum split-deployment standing rule established

**Document version:** VC v0.35 Amendment 12 (markdown)
**Date:** 27 May 2026 (AEST)
**Working language:** Australian English (per standing rule v0.35)
**Page format target:** A4 when converted to DOCX/PDF
**Author of trial:** Stephen L Browne
**Drafter:** Claude Opus 4.7 Adaptive (Anthropic)
**Trial:** UMF Trial S3M0S1

---

## §1 Amendment scope + production reason

Amendment 12 captures the production and v1.0 release of the Research Toolkit (generic operational layer) and Research Toolkit Addendum (UMF-program-specific companion) per Stephen direction 27 May AEST. Amendment 12 anchors the Toolkit/Addendum lineage as a new deliverable type and elevates the Toolkit/Addendum split-deployment pattern to standing rule.

**Production reason (Stephen direction 27 May AEST):** "I want to convert the covering document into a Research Toolkit or Guide... and build a research tool that can be used for UMF and other research as well." Subsequent directions specified single-document v0.1 Draft; then Toolkit + Addendum split at v0.2 + v0.1 Draft; then v1.0 release: "Documents are approved. We can move both to V1.0 as a first release, and update version control accordingly. Can you make me a full handoff to complete the document set."

**Audit-trail anchor status:** Amendment 12 supersedes Amendment 11 as current audit-trail anchor. Amendment 11 retains prior-anchor status for the Step 2 indexes production content it captures.

---

## §2 Source documents added in this cycle

**Produced in this cycle:**

1. **UMF_Trial_S3M0S1_Research_Toolkit_v0_1_Draft.md** (markdown) — first Toolkit production; single-document architecture; superseded by v0.2 Draft (retained in `companion-documents/`)
2. **UMF_Trial_S3M0S1_Research_Toolkit_v0_2_Draft.md** (markdown) — Toolkit/Addendum split implementation; companion to Addendum v0.1 Draft; superseded by v1.0 (retained in `companion-documents/`)
3. **UMF_Trial_S3M0S1_Research_Toolkit_Addendum_v0_1_Draft.md** (markdown) — UMF-specific companion to Toolkit v0.2 Draft; superseded by Addendum v1.0 (retained in `companion-documents/`)
4. **UMF_Trial_S3M0S1_Research_Toolkit_v1_0.md** (markdown) — current Toolkit release; covering document; generic operational layer
5. **UMF_Trial_S3M0S1_Research_Toolkit_Addendum_v1_0.md** (markdown) — current Addendum release; UMF-program-specific companion
6. **VC v0.35 Amendment 12** (this document; markdown) — audit-trail anchor for Toolkit v1.0 + Addendum v1.0 release
7. **UMF_Trial_S3M0S1_Thread_Handoff_v8.md** (markdown) — supersedes Handoff v7; mandatory bundle updated to 18 items

**Predecessor deliverables retained unchanged per audit-trail integrity rule:**

- VC v0.35 Amendment 11 — prior anchor for Step 2 indexes production cycle
- VC v0.35 Amendment 10 — prior anchor for AdjacencyReview2026 cycle
- VC v0.35 Amendment 9 + Addendum — prior anchor for post-Jan 2026 reading layer
- VC v0.35 Amendment 8 — prior anchor; Postulate-2 refinement; mandatory bundle
- VC v0.35 Amendment 7 — prior anchor; framework name + trial renumber
- Synthesis Paper Scaffold v8 consolidated — retained unchanged
- Research Plan v0.7 Draft — retained unchanged; covering-document function superseded by Toolkit v1.0; substantive corpus content retained
- Thread Handoff v7 — superseded by Handoff v8; retained in `companion-documents/`
- All Index v1 documents (Indexes 1, 2, 3) — retained unchanged
- Indexes Design Spec v3 — retained unchanged; relocated to `companion-documents/`
- All deeppass + addendum reports — retained unchanged
- UMF Research Programme Introduction Letter v2 — continues as mandatory bundle per Amendment 8 §K; relocated to `companion-documents/`
- Toolkit v0.1 Draft, v0.2 Draft; Addendum v0.1 Draft — retained in `companion-documents/` per audit-trail integrity

**Trial Introduction Letter v2 continues to be mandatory bundle** per Amendment 8 §K, now alongside Handoff v8, Amendment 12, Toolkit v1.0, Addendum v1.0, Spec v3, the three index v1 documents, prior-anchor Amendments, Scaffold v8, and Research Plan v0.7 Draft.

---

## §3 Material changes captured in Amendment 12

### §3.A Toolkit + Addendum production lineage

A new deliverable line was produced in this cycle covering three production stages:

**Stage 1 (v0.1 Draft):** Stephen direction "convert the covering document into a Research Toolkit or Guide... build a research tool that can be used for UMF and other research as well." Single-document architecture; markdown source; deployment with indexes in same folder + `deep-review-reports/` subfolder. UMF worked example consolidated at §8 of v0.1 Draft.

**Stage 2 (v0.2 Draft + Addendum v0.1 Draft):** Stephen direction to split into Toolkit (generic operational layer) + Toolkit Addendum (UMF-program-specific companion); add Abstract; restructure folder layout to parent directory (Toolkit + Indexes + VC) + `companion-documents/` subdirectory (Spec v3 + Scaffold v8 + Research Plan v0.7 + Handoff v7 + Introduction Letter v2 + Addendum) + `deep-review-reports/` subdirectory. Independent versioning for Toolkit and Addendum per Stephen confirmation.

**Stage 3 (v1.0 release):** Stephen direction "Documents are approved. We can move both to V1.0 as a first release, and update version control accordingly. Can you make me a full handoff to complete the document set." Toolkit and Addendum promoted to v1.0; Amendment 12 produced (this document); Handoff v8 produced.

### §3.B Folder structure restructure

Deployment layout per Stephen direction 27 May AEST:

```
{deployment-root}/
  UMF_Trial_S3M0S1_Research_Toolkit_v1_0.md
  UMF_Trial_S3M0S1_Index1_ContextDefinition_v1.md
  UMF_Trial_S3M0S1_Index2_ContextRelationships_v1.md
  UMF_Trial_S3M0S1_Index3_MetricUnits_v1.md
  VC_v0_35_Amendment7_*.md  (through Amendment 12)
  companion-documents/
    UMF_Trial_S3M0S1_Research_Toolkit_Addendum_v1_0.md
    UMF_Trial_S3M0S1_Indexes_Design_Spec_v3.md
    UMF_Trial_S3M0S1_Synthesis_Paper_Scaffold_v8_consolidated.md
    UMF_Trial_S3M0S1_Research_Plan_v0_7_Draft.docx
    UMF_Trial_S3M0S1_Thread_Handoff_v8.md
    UMF_Research_Program_Introduction_27May2026_v2.md
    [predecessor Drafts: Toolkit v0.1, v0.2; Addendum v0.1; Handoff v7]
  deep-review-reports/
    [5 deeppass reports]
```

Parent directory: Toolkit, three Indexes, VC Amendments.
`companion-documents/` subdirectory: Addendum, Spec v3, Scaffold v8, Research Plan v0.7, Handoff v8, Introduction Letter v2, predecessor Drafts.
`deep-review-reports/` subdirectory: 5 body-access deeppass reports (Papers 2, 3, 5, 8 + Paper 3 Addendum).

### §3.C Covering-document conversion

The Research Plan covering-document function is now served by the Toolkit v1.0 + Addendum v1.0 pair. Research Plan v0.7 Draft is retained in `companion-documents/` as substantive corpus content; its covering-document function is superseded but substantive content remains operative. Future Research Plan revisions (v0.8, v1.0, etc.) are not blocked by this conversion — should Stephen direct continued Plan revision, the Plan would continue alongside the Toolkit + Addendum lineage.

### §3.D Paper 8 body-re-access search (research-hygiene activity)

Stephen requested verification on whether any flag for Paper 8 (Liu-Qin-Bian) body re-access existed in corpus. Comprehensive search performed across all 19 uploaded markdown documents plus session transcript. **No such reference exists in the corpus.** The closest match is Paper 3 (Samaddar-Singh) MU-024 PDF re-verification flag (Handoff v7 line 188; Amendment 11 §3.B.3; Index 3 §6 caveat 2). Paper 8 deeppass §15 enumerates items that cannot be verified from the paper alone (FindBounce-code derivations; numerical Fig. 6 evaluation; EFT validity at low Λ; etc.) — these are external-computation items, not body-re-access requirements. Paper 8 deeppass §17 records "Provenance verified. Findings integrated into corpus deliverables per Amendment 9 cycle." Search logged as research-hygiene activity (consistent with CD-OP-016 standing rule); no new corpus entries created.

### §3.E No new ESCALATE matrix entries; no new framework commitments

Corpus discipline maintained. 26 substantive matrix entries unchanged. No new framework commitments introduced by Toolkit + Addendum production; methodology layer + UMF worked example reference existing corpus content via Index navigation.

### §3.F New Stephen adjudication (pending Index 1 v2 registration)

CD-OP-Adj-021 — Toolkit production cycle (27 May 2026): consolidated adjudication covering (a) direction to convert Research Plan to Toolkit at v0.1 Draft; (b) v0.1 Draft approval; (c) direction to split into Toolkit + Addendum companion document, add Abstract, restructure folder layout (parent + `companion-documents/` subfolder); (d) v0.2 + Addendum v0.1 Draft approval + v1.0 promotion. Downstream effect: Toolkit v1.0 + Addendum v1.0 released; Amendment 12 anchor; Toolkit/Addendum split-deployment standing rule established (§5 below); Handoff v8 supersedes Handoff v7. Modal-status preservation maintained throughout production cycle.

Total adjudication count at Amendment 12 close: 21 (19 in Index 1 v1; 2 pending Index 1 v2 — CD-OP-Adj-020 Step 2 indexes production + CD-OP-Adj-021 Toolkit production cycle).

---

## §4 Trial state at Amendment 12 close

- **Substantive matrix entries:** 26 (unchanged — corpus discipline maintained; NO new entries this cycle)
- **Theme C deep-pass entries:** 22 (unchanged)
- **Joint-citation patterns:** 13 (in Index 2 §4.8 as CR-JC-0001 through CR-JC-0013; unchanged)
- **Headline findings:** 39 (unchanged)
- **Substantive synthesis-paper sections:** 16 (Scaffold v8 unchanged; Scaffold v9 deferred to Step 3)
- **Follow-up items:** 7 (in Index 1 as CD-OP-Item-001 through CD-OP-Item-007; Item 4 Closed; unchanged)
- **Verbatim primary-source citations:** 85+ (unchanged)
- **Stephen adjudications applied:** **21** (19 structurally registered in Index 1 v1; 2 pending Index 1 v2: CD-OP-Adj-020 Step 2 indexes production + CD-OP-Adj-021 Toolkit production cycle)
- **Provenance corrections applied:** 2 (Q4, Q5); labelling-clarification count question still pending Stephen direction (default: count stays at 2)
- **Honest-disclosure corrections:** **5** (unchanged; no new corrections this cycle)
- **Methodology framing-bias corrections:** **4** (unchanged; #4 modal-status preservation re-applied across Toolkit + Addendum production; standing-rule application, not new correction)
- **Identity and scope corrections:** 2 (unchanged)
- **Postulate registry:** unchanged from Amendment 8 §4.2
- **10-topic review status:** CLOSED (unchanged)
- **Empirical-engagement integration phase:** CLOSED (unchanged)
- **Post-January-2026 reading layer:** CLOSED (unchanged)
- **AdjacencyReview2026 cycle:** CLOSED at Amendment 10 (unchanged)
- **Step 2 indexes production:** CLOSED at Amendment 11 (unchanged)
- **Index-centric reorganisation Step 2:** CLOSED; Step 3 (Scaffold modularisation) pending Stephen direction (unchanged)
- **Research Plan covering-document function:** SUPERSEDED by Toolkit v1.0 (this cycle)
- **Research Plan substantive corpus function:** RETAINED at v0.7 Draft in `companion-documents/`
- **Toolkit v1.0 + Addendum v1.0 release:** CLOSED at Amendment 12 (this cycle)
- **Mandatory bundle:** 18 items per Handoff v8 §3 (was 16 per Handoff v7; +2 for Toolkit + Addendum)

---

## §5 Standing rules

All Amendment 11 §5 standing rules reaffirmed unchanged. New standing rule established in this Amendment:

- **Toolkit + Addendum split-deployment standing convention.** The Research Toolkit (generic operational layer) and Research Toolkit Addendum (program-specific companion) constitute the covering-document pair for the trial. Toolkit is deployed in the parent directory; Addendum in `companion-documents/` subdirectory. Toolkit is generic and program-portable; Addendum holds program-specific content. Per the LLM-context discipline (Toolkit §6.3), readers operating in non-UMF contexts treat Toolkit content as operative and Addendum content as illustrative only. (Per Stephen direction 27 May AEST; this Amendment 12.)

No other new standing rules introduced in Amendment 12.

---

## §6 Self-checks performed

**Provenance gate.** Toolkit + Addendum content provenance-traceable to existing corpus deliverables (Scaffold v8, Research Plan v0.7, Amendments 7–11, Indexes 1/2/3 v1, deeppass reports). No new substantive content introduced; methodology layer + UMF worked example reference existing corpus content. Stephen-verbatim direction 27 May AEST captured at §1 production reason. No provenance gate failures.

**Audit-trail integrity.** All prior deliverables (Amendments 7–11; Spec v1, v2, v3; Handoffs v5+addenda, v6, v7; Scaffold v1–v8; Research Plan v0.1–v0.7; deeppass reports; Introduction Letter v1, v2; Index 1, 2, 3 v1; Toolkit v0.1 Draft, v0.2 Draft; Addendum v0.1 Draft) retain original content unchanged. New deliverables (Amendment 12 this document; Toolkit v1.0; Addendum v1.0; Handoff v8) are versioned new artefacts, not in-place edits.

**Framing-bias bidirectionality.** Self-check performed. Toolkit + Addendum production could be framed either as "validating UMF" (pro-UMF: methodology framework now formalised) or as "exposing UMF as just methodology" (anti-UMF: substantive findings still unresolved). Both framings rejected; operative modal characterisation: Toolkit is a research methodology framework usable for UMF + other research; Addendum captures UMF-specific worked example; substantive UMF technical development under Items 1, 5, 6, 7 remains open pending Stephen authorisation. Framing-bias correction #4 re-applied per modal-status preservation; no new framing-bias correction logged.

**Modal-status preservation.** Self-check performed across all Toolkit + Addendum content. Postulate Registry (Addendum §3) preserves 4-level hierarchy and "may or may not" language for possible consequences. Headline findings (Addendum §5) preserve cluster-activity-does-not-validate-UMF framing and Item 5 open-question status. Pending items (Addendum §6) preserve open-question status and awaited-direction language. Toolkit methodology presented as Generic and program-portable; Addendum content presented as UMF-specific and illustrative. Standing-rule application, not new correction.

**No new ESCALATE matrix entries.** Corpus discipline maintained. 26 substantive matrix entries unchanged. Toolkit + Addendum organise and reference existing corpus content; do not introduce new matrix entries.

**No UMF v0.7 / v2.3 source content engagement.** Toolkit + Addendum production worked entirely from existing corpus deliverables. Items 1, 5, 6, 7 substantive UMF technical development remains pending Stephen authorisation.

**Per-paper deeppass-report convention compliance.** No body-access work in Amendment 12 cycle. Existing deeppass reports referenced via cross-reference manifest only. No deeppass-report gap. Paper 8 body-re-access search performed (per §3.D) as research-hygiene activity; no requirement found; no new deeppass work triggered.

**Stephen-verbatim direction captured.** Three Stephen direction events in this cycle:
- Initial direction (Toolkit production initiation): "I want to convert the covering document into a Research Toolkit or Guide... and build a research tool that can be used for UMF and other research as well."
- Split direction (after v0.1 Draft approval): "the document seems destined to be split with a Toolkit Addendum as a companion document containing the specifications, Stephen's actions, and other items not pertaining to active research."
- Release direction (after v0.2 + v0.1 Draft approval): "Documents are approved. We can move both to V1.0 as a first release, and update version control accordingly. Can you make me a full handoff to complete the document set."

All three captured in CD-OP-Adj-021 as consolidated adjudication per the trial pattern for production-cycle direction events.

---

## §7 Items rolled forward to next cycle

**From Amendment 11 §7 unchanged (still pending):**

- Items 1, 5, 6, 7 UMF technical development — pending Stephen authorisation for UMF v0.7 / v2.3 source-content work
- v1.0 Final synthesis pre-writing scaffolding milestone — timing pending
- Module 5 re-initialisation — timing pending
- UMF v0.7 / v2.3 source document update for accumulated corrections — pending (now Amendments 7–12)
- Step 3 Scaffold modularisation — Spec v3 §11; indexes now mature; timing pending Stephen direction
- Index 1 v1 §9 honest-disclosure caveats — Stephen verification on tentative OP-Adj attributions (Q4, Q5, Q7, Q8), series taxonomy placement criteria, Theme A and Theme B definitions; production of Index 1 v2 with corrections + new CD-OP-Adj-020 + CD-OP-Adj-021 entries
- Index 2 v1 §7 caveats — Stephen review on node nomenclature canonicalisation; potential additional bilateral edges
- Index 3 v1 §6 caveats — A-series specific parameters not currently tracked; MU-024 Paper 3 PDF re-verification when PDF available
- Three open questions from Spec v3 §12.2 — default treatments adopted; available for revisit if Stephen wishes
- Papers 1 + 2 (Malakar group) peer-review-status verification extension — declined Amendment 10; available for future-cycle action
- Azhar-Jawad-Rani 2020/2021 prior f(T, T_G) baryogenesis review — held aside; pending direction
- Labelling-clarification count question on Amendment 9 §3.I "Nojiri-Odintsov" shorthand — default count stays at 2; pending direction

**New from Amendment 12 cycle:**

- **DOCX format recovery** for Toolkit + Addendum — per Stephen direction 27 May AEST: "We will recover docx formatting later". Timing pending.
- **Future Toolkit revisions** (v1.1, v2.0, etc.) — produce as content updates warrant; no immediate plan absent Stephen direction
- **Cross-program forking** — procedure per Toolkit §6.2 available if Stephen authorises non-UMF program deployment

---

## §8 End of Amendment 12

This Amendment 12 closes the Research Toolkit conversion phase. Trial S3M0S1 at Amendment 12 close is in clean state with the Toolkit v1.0 + Addendum v1.0 covering-document pair now operative as the entry point for the corpus. Research Plan v0.7 retained as substantive corpus content in `companion-documents/`. Step 3 (Scaffold modularisation) and UMF v0.7 / v2.3 source-content engagement (Items 1, 5, 6, 7) pending Stephen direction.

**Audit-trail anchor:** VC v0.35 Amendment 12 (this document).

**Reading-orientation pointer for any future thread:** read Handoff v8 first (mandatory orientation); Amendment 12 as current audit-trail anchor; Toolkit v1.0 + Addendum v1.0 as covering documents; Spec v3 as design contract for the indexes; Index 1 v1 + Index 2 v1 + Index 3 v1 as navigation layer; prior Amendments 7–11 + Scaffold v8 + Research Plan v0.7 + deeppass reports as substantive corpus.

---

*End of VC_v0_35_Amendment12_research_toolkit_v1_0_release.md*
