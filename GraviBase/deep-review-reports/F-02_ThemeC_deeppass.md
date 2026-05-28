### F-02 — Mazumdar-White 2019 — Review of cosmic phase transitions: their significance and experimental signatures — **THEME C T1 DEEP-PASS**

**Date of entry:** 25 May 2026 (AEST)
**Theme C deep-pass on F-02 (originally Theme F triage in RPA).**
**arXiv:** [1811.01948](https://arxiv.org/abs/1811.01948) [hep-ph]
**Journal:** Rep. Prog. Phys. 82 (2019) 076901. DOI: 10.1088/1361-6633/ab1f55
**First posted:** 5 Nov 2018 (v1). **Revisions:** 6 May 2019 (v2); 18 Dec 2019 (v3, accepted version).
**Length:** 87 pages, 35 figures.
**Format consulted (Theme C deep-pass):**
- arXiv abstract page (HTML) — verified verbatim
- ResearchGate verbatim text snippet from arXiv:1811.01948 PDF — Section 2 content on topological defects and Q-balls; Section 2.4.1 reheating/thermalization opening (verified verbatim from arXiv PDF rendering)
- Verbatim text snippet from arXiv:1811.01948 PDF — Section on post-inflation preheating cross-connections (verified verbatim)
- Secondary citing literature for Section structure (Caprini et al. 2020 arXiv:1910.13125; Hindmarsh et al. 2021 arXiv:2008.09136; Croon-Gould-Schicho-Tenkanen-White 2020 arXiv:2009.10080)
- PDF not bulk-loaded per RP §10 thread efficiency rule

**Provenance gate result:** PASS (re-verified from F-02 triage). 7 years cumulative engagement; 87-page comprehensive Reports on Progress in Physics review (top-tier IOP review venue, impact factor among the highest in physics); Mazumdar a leading reheating/SUSY-cosmology figure (also co-author of F-01); White a leading electroweak-baryogenesis/GW figure. Three v3 revisions over 13 months indicate substantive iteration; v3 accepted by IOP. Substantial follow-up literature including a direct critical refinement on theoretical uncertainties by White himself (Croon et al. 2020 arXiv:2009.10080, JHEP 04:055).

---

## Theme C deep-pass outputs

### (a) UMF compatibility nuances at full PDF read

**Auto-exclude triggers (per RP §6 step 3 v0.7):**
- **Variable c:** ABSENT. Standard QFT in expanding background. The paper uses natural units c = ℏ = k_B = 1 throughout (standard hep-ph convention). **PASS.**

**Strippability tests for fundamental constants (per RP §6 step 3 v0.7):**

| Constant | Treatment in paper | UMF v0.7 compatibility |
|---|---|---|
| G | Constant. Enters via cosmological background through Friedmann equation; never varied. Phase transitions take place against a fixed-G FRW background. | **Compatible with UMF v0.7 stable-geometry regime.** Paper does not engage UMF v0.7 variant-geometry G-coupling but does not exclude it. |
| h (ℏ) | Constant; implicit via natural units. Required for QFT formalism. | **Compatible with UMF v0.7 stable-geometry regime.** |
| ε₀, μ₀ | Implicit; gauge-theoretic background (SU(3)×SU(2)×U(1) and various BSM extensions). Photon kinematics inside symmetric/broken phases governed by gauge field content, not by direct ε₀, μ₀ variation. | **Compatible (silent).** |

**Trans-Planckian classification:** Paper operates at EW (~100 GeV), QCD (~150 MeV), and various BSM PT scales (typically 10⁴–10¹⁶ GeV); the paper's explicit focus per abstract is "phase transitions above [EW/QCD] scales". Even the highest BSM PT scales considered are at most ~10¹⁶ GeV, well below the Planck scale ~10¹⁹ GeV. No trans-Planckian regime engaged. Under UMF v0.7 regime-relativity, this all lies in stable-geometry territory. **Compatible.**

**CDM scaffolding:** Plug-in, not load-bearing. DM is discussed as one of many applications/consequences of cosmic PT; the PT machinery itself does not structurally require CDM. **Strippable.**

**BBN dependence:** Timeline-flexible at apparatus level (PTs at T_EW ~ 100 GeV and above all precede BBN at T ~ MeV); BBN is downstream of PT mechanism. Apparatus would translate into any cosmological-timeline framework providing pre-BBN epochs. **Strippable at apparatus level; rigid at cosmological-timeline level** insofar as the paper assumes t=0 → reheating → high-T plasma → PT → BBN sequence.

**Equation of state w(x):** Paper treats radiation domination w = 1/3 during/post-PT; PT itself involves a brief vacuum-energy-release episode (essentially w = -1 instantaneously in the false vacuum, then w = 1/3 in the released radiation). No engagement with non-linear w(x) of UMF T_G type. **Silent; does not contribute to UMF T_G structural assessment.**

**H₀ tension treatment:** Silent. Paper is concerned with very early universe (T ≳ MeV), pre-recombination by many orders of magnitude. The H₀ tension question does not arise at this epoch.

**Structural commitments:**
- **T_G as pressure-dimensioned scalar field:** Inflaton φ (in §2 reheating context) and Higgs / BSM scalars (in PT context) all have scalar-field stress-energy. **Orthogonal**: paper's scalar fields are dynamical matter fields with potentials V(φ); T_G in UMF is geometric pressure. Different physical content; same dimensional category.
- **Bounded universe / reflective wavefront:** **Silent / incompatible at cosmological-timeline level**. Paper assumes standard FRW.
- **Variable ε₀, μ₀ with c invariance:** **Silent.**
- **Gravitoelectric DM:** **Incompatible at framework level**. Paper's DM applications (Q-balls per references [136,137]; baryogenesis-linked DM; PT-produced DM candidates) all involve particles. UMF's gravitoelectric DM has no particles.
- **Finite cosmic lifecycle:** **Silent / incompatible**. Paper assumes infinite-time-extension FRW.

**Result:** **Partial-import compatible.** Stable-geometry mathematical apparatus (bubble nucleation theory, effective potential at finite T, Kibble-Zurek topological-defect formation, GW production from bubble dynamics) is compatible with UMF stable-geometry regime. Cosmological-timeline framework is incompatible with UMF bounded-universe timeline. Particle-DM applications structurally incompatible with UMF gravitoelectric DM.

### (b) Time-measurement determination

**Source-literature framework time-measurement:** **T=0**. Confirmed verbatim from paper's own abstract: "In the standard model of cosmology the Universe begins in a very hot state, right after at the end of inflation via the process of reheating/preheating, and cools to its present temperature as the Universe expands." The paper's entire framework is referenced to a t=0 inflationary-cosmology timeline; PTs are placed at specific cosmological epochs (EW at T ~ 100 GeV, QCD at T ~ 150 MeV, BSM at higher T).

**Transfer into UMF bounded-universe timeline (per RP §3.1 working assumption 3):** **NEGATIVE at framework level; PARTIAL at apparatus level.**

- *Framework-level:* The paper's full sequence (inflation → reheating → PT(s) → BBN → recombination) is committed to t=0 cosmology and does not transfer into UMF bounded-universe breach-to-SMBH timeline as a whole.
- *Apparatus-level:* The bubble-nucleation / Kibble-Zurek defect-formation / GW-production mathematical apparatus is mathematically epoch-agnostic. It could in principle be invoked in UMF's bounded-universe context if UMF were to identify a vacuum-state-transition event corresponding to G-shock. Stephen-led integration decision required to specify whether a UMF G-shock event has thermal-bath precursor (required by F-02 apparatus) or operates differently.

**Recommended Time code update for ESCALATE matrix:** **PLC → T=0** (refining the PLC placeholder per matrix). Per the matrix's "T=0 / CYC / BND / FLEX / PLC / N/A" legend, F-02 commits to T=0 inflationary cosmology in framework but with apparatus-level epoch-agnosticism.

### (c) Specific apparatus / methodology UMF can import

Five classes of importable apparatus identified; each requires Stephen-led integration decision:

**1. Bubble nucleation framework.** Coleman bounce action, thin-wall approximation, Euclidean tunneling rate Γ = A exp(-S_E). For first-order transitions where false-vacuum bubbles nucleate, expand, and collide, this is the standard machinery. Applicable if UMF G-shock involves any first-order-transition-like vacuum-state change.

*Caveat (important honest disclosure):* Croon-Gould-Schicho-Tenkanen-White 2020 (arXiv:2009.10080, JHEP 04:055, **co-authored by F-02's White**) showed that "in the usual daisy-resummed approach, we find large uncertainties due to renormalisation scale dependence, which amount to two to three orders-of-magnitude uncertainty in the peak gravitational wave amplitude" — i.e., the standard apparatus for predicting GW signatures has known systematic uncertainty of factor ~100–1000. Dimensional-reduction methods reduce this significantly. UMF should be aware that bubble-nucleation calculations have this known systematic uncertainty if importing the apparatus for any quantitative G-shock GW prediction.

**2. Finite-temperature effective potential V_eff(φ, T).** Computed via daisy/super-daisy resummation (4d approach) or dimensional reduction (3d approach). Provides the potential landscape against which bubble nucleation rate is calculated. Standard reference is Quiros 1999 review (Les Houches lectures) and the 1990s daisy-resummation literature; Mazumdar-White 2019 is the modern entry point.

**3. Kibble-Zurek topological-defect formation mechanism (Section 2).** Verbatim from arXiv PDF: "Topological defects are another consequences of phase transitions, it was Kibble [...] and Zurek [...] who independently postulated the formation of topological defects during cosmic phase transition. The topological defect is also known as a solitonic solution in quantum field theory which are homotopically distinct from the vacuum solution." Mechanism: causal disconnection of horizon-sized patches during phase transition leads to uncorrelated vacuum choices in different patches; topological mismatch at patch boundaries produces stable defects (strings, walls, monopoles, textures depending on broken symmetry's homotopy group). **Connection to F-04 (Copeland-Kibble 2010 cosmic strings) is direct:** F-02 establishes the formation mechanism; F-04 provides the cosmic-string-specific deep dive. Topological defects are a "rearrangement" matter formation mechanism per RP §6 step 5.

**4. Three GW-production mechanisms from first-order PT.** Bubble collisions, sound waves in plasma, MHD turbulence (per standard 1st-order PT GW literature consolidated in F-02 and updated in Hindmarsh et al. 2021 arXiv:2008.09136, Croon et al. 2020 arXiv:2009.10080, Caprini et al. 2020 arXiv:1910.13125 LISA-update). Spectral shape predictions: low-frequency ω³ envelope-approximation rise; bubble-collision peak ω⁻¹ above peak; sound-wave-dominated long-lasting source; MHD turbulence k^-2 or k^-3 high-frequency tails depending on flow type. *Caveat as above on systematic uncertainty.*

**5. Non-topological soliton (Q-ball) formation as PT consequence (Section 2 references [135-137]).** Verbatim from PDF: "Besides, topological solitons, there are also non-topological solutions in any interacting field theory where the boundary conditions at infinity are the same as that of the vacuum state, for example Q-ball, a detailed review of Q-balls, see [136,137]." **This directly cross-references A-05 (boson stars / Q-balls / oscillons / oscillatons / Proca stars).** F-02 is the upstream PT-mechanism reference for Q-ball formation; A-05 is the specific boson-star/Q-ball deep dive.

### (d) Specific divergences from UMF to acknowledge in published paper

Six clean divergences:

**1. Thermal-bath precursor required.** F-02 PT mechanisms operate against pre-existing thermal radiation bath (set up by F-01-class reheating). UMF G-shock matter creation does not have an obvious thermal-bath precursor; the breach event itself is the matter-creation event, not a transition within an already-thermalized universe. **Published-paper position:** UMF positions its G-shock mechanism as a non-thermal creation event, distinct from PT-class asymmetry generation / rearrangement which require thermal precursor.

**2. Particle-field vacuum structure.** F-02 mechanisms operate on field-theoretic V_eff(φ, T) with potential minima corresponding to broken-symmetry vacuum states. UMF's geometry-primary commitments do not have an obvious analogue to a particle-physics vacuum potential. **Published-paper position:** UMF acknowledges its mechanism operates in a different framework category (geometry-primary vs field-theoretic).

**3. Particle-DM vs gravitoelectric-DM.** F-02 DM applications all involve particles (Q-balls, asymmetric DM, sneutrino DM, etc.). UMF's gravitoelectric DM has no particles. **Same as F-01 divergence 3.**

**4. Standard t=0 inflationary cosmology vs UMF bounded-universe timeline.** **Same structural divergence as F-01 divergence 2.** F-02 PTs are placed at specific cosmological epochs incompatible with UMF bounded-universe timeline at the framework level.

**5. Asymmetry generation / rearrangement mechanism categories vs UMF non-thermal creation.** F-02 covers "asymmetry generation" (baryogenesis at bubble walls per Sakharov conditions) and "rearrangement" (e.g., QCD confinement transition reorganising existing quark/gluon content into hadrons; topological defect formation from existing field configurations). UMF G-shock matter creation is non-thermal creation from gravitational/geometric energy — a different mechanism category entirely. **Published-paper position:** UMF cites F-02 as the modern reference for the alternative non-creation PT mechanisms (asymmetry generation, rearrangement) against which UMF's non-thermal-creation mechanism is positioned.

**6. Honest disclosure of known systematic uncertainty.** Per Croon-Gould-Schicho-Tenkanen-White 2020 (White is F-02 co-author), GW amplitude predictions from 1st-order PT have 2-3 orders of magnitude uncertainty under daisy-resummation. UMF should acknowledge this when comparing its own (if it has any) G-shock GW predictions against the F-02-class PT GW predictions: the latter are not currently precise to within an order of magnitude. **Published-paper position:** any quantitative claim by UMF about G-shock GW signatures vs PT GW signatures must be made with reference to the established theoretical uncertainty in the comparison baseline.

### Empirical-requirement assessment

F-02 is a review paper with substantial observational engagement (one of the most observationally-engaged framings in Theme F).

Per RP §4 three-category framework:
- **Lab tests:** None directly. PT phenomena are not lab-accessible at cosmological scales. Heavy-ion collisions probe QCD-PT physics partially.
- **Observational tests:** Substantial.
  - **Stochastic GW background from cosmological PTs**: LIGO/Virgo/KAGRA in current observation; LISA targeted (eLISA in F-02's abstract, now LISA; expected launch ~2035 per ESA timeline). No 5σ detection of cosmological-PT GW signal as of cutoff date (Jan 2026); NANOGrav 15-yr (2023) reported evidence of stochastic GW background consistent with supermassive-BH binary inspirals OR with cosmological sources including 1st-order PT (per Croon et al. 2023 and others); statistical significance ~3-4σ depending on analysis. Notable-only per RP §9 standing rules (2σ-3σ threshold not crossed cleanly into 4σ correlation).
  - **CMB constraints on topological defects**: Planck 2013/2015 constraints set defect contribution to CMB anisotropies ≲ few % of total (specifically Gμ ≲ 1.5×10⁻⁷ for cosmic strings, per Planck XXV 2013); these are upper bounds, not detections.
  - **Magnetic-field-from-PT**: primordial magnetic fields at nG scale constrained by CMB and structure formation; no detection.
  - **Baryogenesis link**: η_B = n_B/n_γ ≈ 6×10⁻¹⁰ from BBN and CMB (Planck 2018), measured at 5σ, but this is a constraint that PT-baryogenesis mechanisms must satisfy, not a confirmation of any specific PT mechanism.
- **Theoretical consistency:** Substantial — bubble nucleation theory, effective potential at finite T, Kibble-Zurek mechanism, GW production from bubble dynamics all well-established. Partial satisfaction of RP §4 requirement 2 via theoretical-consistency category. **However**: Croon et al. 2020 (White co-authored) demonstrates the daisy-resummation calculation has 2-3 orders of magnitude systematic uncertainty in peak GW amplitude — substantial methodological caveat to record.

**Empirical-requirement waiver:** Granted on standard grounds (cosmological-epoch phenomenon; observational tests in progress but no 5σ confirmation of cosmological PT detection as of cutoff). Per RP §4 standard, theoretical consistency substitutes as partial satisfaction with the explicit caveat that 2-3 orders of magnitude systematic uncertainty is documented in the standard apparatus.

### Cross-references

- **F-02 ↔ F-01:** F-01 (Allahverdi et al. 2010 reheating) sets up the thermal bath in which F-02 PTs operate. F-02 cites F-01 directly in introduction. Pipeline: reheating (F-01) → thermal plasma → cooling → PT (F-02).
- **F-02 ↔ F-04 cosmic strings:** F-02 establishes the Kibble-Zurek topological-defect formation mechanism; F-04 (Copeland-Kibble 2010) is the cosmic-string-specific deep dive. F-02 → F-04 is the natural "framework → specific defect type" link. **Both are NOTABLE or candidate-NOTABLE entries in the Theme F matter-creation cluster** (F-04 NOTABLE; F-02 not flagged NOTABLE per current matrix but earns it on the topological-defect-formation-as-rearrangement-matter-mechanism axis).
- **F-02 ↔ A-05 boson stars / Q-balls:** F-02 explicitly references Q-ball formation as PT consequence (Section 2 references [135-137]); A-05 (Liebling-Palenzuela 2023 + Visinelli 2021 + Zhang-Jain-Amin 2025) is the deep dive on the resulting non-topological-soliton states. F-02 is the upstream PT-formation reference; A-05 is the steady-state-soliton reference.
- **F-02 ↔ F-05 gravitational baryogenesis:** F-02 covers electroweak baryogenesis (Sakharov-condition asymmetry generation at PT bubble walls); F-05 (Davoudiasl et al. 2004 gravitational baryogenesis) is the gravitational-coupling-driven alternative. Both target the same observable (η_B) via different mechanism categories.
- **F-02 ↔ B-02 Brill-wave critical collapse:** F-02 produces GWs as a byproduct of PT bubble dynamics; B-02 has gravitational waves as primary matter mechanism. The two are at opposite ends of the "GW production from matter dynamics" vs "matter production from GW dynamics" spectrum, useful contrast for UMF positioning.
- **F-02 ↔ D-01/D-02 trans-Planckian:** F-02 operates entirely in sub-Planckian regime (highest PT scales ~10¹⁶ GeV); trans-Planckian question does not arise. Useful for verifying UMF's regime-relativity position holds in F-02 case.

### Outside-corpus markers

- arXiv abstract page and metadata (citation info, page count, revision history) — **verified verbatim from arXiv abstract page.**
- Section 2 verbatim text on topological defects (Kibble, Zurek, cosmic strings, monopoles, Q-balls) — **verified verbatim from ResearchGate text snippet of arXiv:1811.01948 PDF.**
- Section 2.4.1 verbatim opening on perturbative decay and thermalization — **verified verbatim from ResearchGate text snippet of arXiv:1811.01948 PDF.**
- Verbatim text on inflation-end → reheating → preheating → topological defects + GW + Q-ball pipeline — **verified verbatim from arxiv.org PDF rendering snippet** (document 79 in this session search).
- Three GW production mechanisms (bubble collisions, sound waves, MHD turbulence) characterisation — **drawn from standard background and secondary citing literature** (Hindmarsh et al. 2021 arXiv:2008.09136; Croon et al. 2020 arXiv:2009.10080; Kahniashvili et al. 2008 arXiv:0809.1899; Gould-Sukuvaara-Weir 2021 arXiv:2107.05657); not directly verified verbatim from the 1811.01948 PDF for this entry.
- Spectral shape predictions (ω³ low-frequency rise, ω⁻¹ above bubble-collision peak, k^-2 / k^-3 high-frequency tails) — **drawn from standard background and secondary literature** (Kahniashvili et al. 2018 arXiv:1803.02271; Jinno-Takimoto 2017 arXiv:1707.03111); not directly verified from 1811.01948 for this entry.
- Croon-Gould-Schicho-Tenkanen-White 2020 arXiv:2009.10080 2-3 orders of magnitude uncertainty finding — **verified verbatim from multiple sources** including arXiv abstract, JHEP 04 (2021) 055 publication record, ADS, Semantic Scholar.
- Planck XXV 2013 constraint on cosmic-string Gμ ≲ 1.5×10⁻⁷ — **drawn from standard background**; specific values not separately verified for this entry.
- NANOGrav 15-yr (2023) stochastic GW background detection at ~3-4σ for cosmological sources — **drawn from standard background**; specific significance levels not separately verified for this entry.
- BBN/CMB-measured baryon-to-photon ratio η_B ≈ 6×10⁻¹⁰ at 5σ (Planck 2018) — **drawn from standard background.**
- Coleman bounce / Euclidean tunneling / thin-wall approximation / Mathieu-equation-related apparatus framing — **drawn from standard background**; not separately verified verbatim from 1811.01948 for this entry.

### Theme C T1 deep-pass disposition

**Sustain ESCALATE.** **Update flag to add NOTABLE on (c)+empirical-engagement** — F-02 is the modern review entry-point for the entire cosmic-PT matter-formation tradition with substantial observational engagement (most observationally engaged Theme F entry); should be added to the headline-findings list as the standard reference for PT-class matter-formation mechanisms (asymmetry generation, rearrangement, topological defect formation). Original Theme F triage was correct on substance but understated F-02's role as the principal modern reference.

**Methodology for synthesis paper:** F-02 to be cited as:
1. The standard modern reference for PT-class matter formation (asymmetry generation, rearrangement, topological defect formation, non-topological soliton formation as PT consequence)
2. The bridge between F-01 (reheating) and F-04 (cosmic strings) in the mainstream picture; also bridge to A-05 (Q-balls/boson stars) at the non-topological-soliton end
3. The modern reference for GW production from cosmological PTs (three-mechanism cluster: bubble collisions, sound waves, MHD turbulence)
4. With explicit honest disclosure of Croon et al. 2020 2-3 orders of magnitude systematic uncertainty in daisy-resummed GW predictions

F-02 should NOT be cited as supporting evidence for UMF mechanisms — the divergences (especially divergence 5, mechanism-category mismatch) are too substantial — but as the principal mainstream reference for the PT-mechanism tradition against which UMF's G-shock mechanism is positioned. The honest acknowledgement of the 2-3 orders of magnitude systematic uncertainty in PT-GW predictions is also methodologically useful: it sets the baseline against which any UMF G-shock-GW prediction would need to be compared.

---

**Drafter:** Claude. Deep-pass entry follows Theme C scope per Research Plan v0.1 Draft and per-entry output requirements per Handoff §9. Open to Stephen-directed PDF-page requests for any element flagged as "drawn from standard background" or "verified from secondary snippet" if higher confidence is required for the synthesis-paper citation — specifically the spectral shape predictions in Section 5/6 of the PDF and the explicit Q-ball discussion location.
