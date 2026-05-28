### F-01 — Allahverdi-Brandenberger-Cyr-Racine-Mazumdar 2010 — Reheating in Inflationary Cosmology: Theory and Applications — **THEME C T1 DEEP-PASS**

**Date of entry:** 25 May 2026 (AEST)
**Theme C deep-pass on F-01 (originally Theme F triage in RPA v0.5).**
**arXiv:** [1001.2600](https://arxiv.org/abs/1001.2600) [hep-th]
**Journal:** Annu. Rev. Nucl. Part. Sci. 60:27–51 (2010). DOI: 10.1146/annurev.nucl.012809.104511
**First posted:** 15 Jan 2010 (v1). **Last revision:** 19 Jan 2010 (v3).
**Format consulted (Theme C deep-pass):**
- arXiv abstract page (HTML) — verified verbatim
- ar5iv HTML rendering (https://ar5iv.labs.arxiv.org/html/1001.2600) — Sections I, II, III.3, VI.2 directly read
- arxiv-vanity rendering snippet — Section VI.2 metric preheating / gravity waves
- Secondary citing literature snippets for Section VI.1.2 DM content (Maleknejad-McDonough 2022 arXiv:2205.12983; Halverson et al. 2025 arXiv:2504.13256; Kolb-Long 2017 arXiv:1708.04293; Kolb-Chung-Riotto 1998 hep-ph/9802238)
- PDF not bulk-loaded per RP §10 thread efficiency rule

**Provenance gate result:** PASS (re-verified from F-01 triage). 16 years continuous engagement; Annual Reviews venue; Brandenberger as foundational author of TB 1990 (the paper that first reframed reheating away from perturbative decay); Allahverdi-Mazumdar leading SUSY reheating community; cited as canonical entry-point in essentially all subsequent reheating reviews including Amin-Hertzberg-Kaiser-Karouby 2014 (arXiv:1410.3808) and Lozanov 2019 (arXiv:1907.04402).

---

## Theme C deep-pass outputs

### (a) UMF compatibility nuances at full PDF read

**Auto-exclude triggers (per RP §6 step 3 v0.7):**
- **Variable c:** ABSENT. The paper uses natural units c = ℏ = k_B = 1 throughout (standard QFT convention; confirmed by m_pl⁻² ≡ G definition in §II and by Lozanov 2019 lecture series explicitly using same conventions when reviewing this paper). c is treated as a fixed dimensional constant set to unity. **PASS.**

**Strippability tests for fundamental constants (per RP §6 step 3 v0.7):**

| Constant | Treatment in paper | UMF v0.7 compatibility |
|---|---|---|
| G | Constant. Enters via m_pl⁻² ≡ G (§II) and via Friedmann equation H² = (8πG/3)ρ; never varied. | **Compatible with UMF v0.7 stable-geometry regime.** Paper does not engage UMF v0.7 variant-geometry G-coupling, but does not exclude it either; the apparatus operates in the stable-G regime UMF v0.7 §3.1 assumption 4 admits. |
| h (ℏ) | Constant. Implicit via natural units ℏ = 1; QFT formalism throughout requires ℏ as basic quantisation parameter. | **Compatible with UMF v0.7 stable-geometry regime.** Same as G. |
| ε₀, μ₀ | Implicit; not engaged. EM is not the focus of preheating; gauge field production via preheating treated abstractly (cross-section / coupling constant level). | **Compatible (silent).** |

**Trans-Planckian classification:** Paper uses absolute Planck scale throughout — inflationary scale H_inf ~ 10¹³–10¹⁴ GeV is sub-Planckian, inflaton mass m ~ 10⁻⁶ m_pl is sub-Planckian, no trans-Planckian regime is engaged. Under UMF v0.7 regime-relativity, the paper operates entirely within a single stable-geometry regime; the trans-Planckian question does not arise. **Compatible.**

**CDM scaffolding:** Plug-in, not load-bearing. Section VI.1.2 discusses DM as one of several post-reheating consequences; preheating produces superheavy candidates (WIMPzilla-class) but the reheating mechanism does not structurally require CDM. **Strippable.**

**BBN dependence:** Timeline-flexible at apparatus level (preheating is pre-BBN by many orders of magnitude in T); rigid only insofar as the standard t=0 cosmological timeline assumes BBN at ~3 minutes post-bang. The matter-creation mechanism itself does not require the BBN epoch. **Strippable at apparatus level; rigid at cosmological-timeline level.**

**Equation of state w(x):** Paper treats matter as scalar-field-dominated during inflation (w ≈ -1) and radiation-dominated post-thermalization (w = 1/3). No engagement with non-linear w(x). **Silent; does not contribute to UMF T_G structural assessment.**

**H₀ tension treatment:** Silent. 2010 paper predates the H₀ tension as a primary research topic. **Silent; acceptable but does not contribute.**

**Structural commitments:**
- **T_G as pressure-dimensioned scalar field:** Inflaton φ has scalar-field stress-energy tensor T_μν = ∂_μφ∂_νφ - g_μν L. **Orthogonal**: inflaton is dynamical matter field; T_G in UMF is geometric pressure. Different physical content; same dimensional category (pressure × volume = energy).
- **Bounded universe / reflective wavefront:** **Silent / incompatible at cosmological-timeline level**. Paper assumes standard FRW asymptotically infinite cosmology.
- **Variable ε₀, μ₀ with c invariance:** **Silent.**
- **Gravitoelectric DM (no-mass no-particles, sourced by wavefront):** **Incompatible at framework level**. Paper's DM mechanism produces particles (WIMPzilla, gravitino, axion DM). UMF's gravitoelectric DM has no particles. Honest divergence to record in synthesis.
- **Finite cosmic lifecycle / gravitational budget conservation:** **Silent / incompatible**. Paper assumes infinite-time-extension FRW.

**Result:** **Partial-import compatible.** Stable-geometry mathematical apparatus (parametric resonance, Floquet analysis, non-adiabatic vacuum production) is fully compatible with UMF stable-geometry regime. Cosmological-timeline framework (FRW, t=0 inflationary cosmology, infinite extension) is incompatible with UMF bounded-universe breach-to-SMBH timeline. Particle-DM mechanism is structurally incompatible with UMF gravitoelectric DM.

### (b) Time-measurement determination

**Source-literature framework time-measurement:** **T=0**. Paper assumes standard t=0 inflationary cosmology: Big Bang at t=0, inflation begins at t ~ 10⁻³⁶ s (or some such inflationary timescale referenced to t=0), inflation ends, reheating occurs, radiation domination, etc. The entire timeline structure is referenced to a finite proper-time origin.

**Transfer into UMF bounded-universe timeline (per RP §3.1 working assumption 3):** **NEGATIVE at framework level; PARTIAL at apparatus level.**

- *Framework-level:* The paper's full create-then-thermalize sequence (inflation → reheating → thermalization → radiation domination → BBN → ...) is committed to a t=0 cosmology and does not transfer into UMF's bounded-universe breach-to-SMBH timeline. UMF places matter creation prior to or concurrent with the breach event; the paper's matter creation is post-inflation and post-end-of-inflation, which is a specific cosmological-epoch commitment incompatible with the UMF timeline structure.
- *Apparatus-level:* The parametric-resonance mechanism (oscillating background field → exponential mode amplification via Mathieu equation → non-adiabatic particle production) is mathematically epoch-agnostic. It could in principle be invoked in UMF's bounded-universe context if UMF were to identify an oscillating background-field analogue (e.g., G-shock oscillation during/after breach). This would require explicit UMF construction; not pre-supplied by the paper.

**Recommended Time code update for ESCALATE matrix:** **T=0** (unchanged from current matrix entry).

### (c) Specific apparatus / methodology UMF can import

Three classes of importable apparatus identified; each requires Stephen-led integration decision separate from this reading-programme entry:

**1. Parametric resonance / Mathieu equation framework (Section III.2).** Coherent classical oscillating background field couples to quantum fluctuation modes; mode equations take the form

  χ̈_k + ω²_k(t) χ_k = 0

with ω²_k(t) = k² + g²Φ²(t) where Φ(t) is the oscillating background. When Φ(t) is periodic, mode equation becomes Mathieu-type with exponentially growing Floquet solutions in instability bands. The KLS2 (Kofman-Linde-Starobinsky 1997) broad-resonance regime (q ≫ 1) produces non-perturbative non-adiabatic particle production at rates vastly exceeding perturbative decay.

*UMF application potential:* if G-shock involves any oscillatory dynamics in the geometric/gravitational background (per Stephen's illustrative visualisations of G-pulse with secondary echoes), parametric-resonance mathematics provides the mechanism by which oscillation amplifies quantum fluctuations into particle production. The mathematical machinery is well-developed (Floquet theory; Mathieu equation; lattice simulations LATTICEEASY, CLUSTEREASY).

*Caveat:* the standard apparatus assumes scalar-field oscillation. UMF's G-shock is not obviously a scalar-field oscillation. Strippability of the mathematics from the scalar-field assumption requires Stephen-led assessment. Brill-wave (B-02) critical-collapse machinery may be the more directly importable gravitational-wave-based analogue.

**2. Non-adiabatic vacuum production concept (Section III.2 throughout).** The core physical insight: when ω_k(t) changes faster than ω_k itself (|ω̇/ω²| > 1), the adiabatic vacuum is not preserved and particle creation occurs from the vacuum. This generalises to any sufficiently rapid change in a background field, not specifically to scalar inflaton fields.

*UMF application potential:* G-shock as "sudden change in geometry, gravity, or both, over time" (Stephen's working definition 24 May 2026) is precisely a non-adiabatic event. The non-adiabatic vacuum production concept is the physically correct framing for matter creation from rapid geometric change. This is the closest conceptual match to UMF G-shock matter creation found in F-01.

**3. Metric preheating concept (Section VI.2).** Resonant amplification of scalar metric perturbations through coupling to oscillating inflaton condensate. Bassett et al. 1999 (hep-ph/9901319) showed metric perturbations can be driven nonlinear, breaking linearised Einstein equations. **Critical for UMF:** this is the only place in F-01 where gravitational/geometric quantities themselves are sourced by the reheating dynamics. Importable conceptually as a gravity-side analogue, but the paper's machinery operates within scalar-field reheating; direct G-shock analogue would need to be constructed.

### (d) Specific divergences from UMF to acknowledge in published paper

Five clean divergences for honest disclosure in synthesis:

**1. Inflaton scalar field as energy source.** F-01 (and the entire reheating tradition since Traschen-Brandenberger 1990) treats the inflaton scalar field as the coherent energy reservoir from which matter particles are created. UMF's G-shock is not a scalar field; the energy source is geometric/gravitational. The mechanism categories overlap conceptually (non-thermal creation from coherent energy reservoir) but the field content differs. **Published-paper position:** UMF cites F-01 for the broader "non-thermal creation from coherent background" mechanism class; explicitly distinguishes its energy source as gravitational/geometric rather than scalar-field.

**2. Standard t=0 inflationary cosmology vs UMF bounded-universe timeline.** F-01 assumes inflation begins at some finite proper time t = t_inflation > 0 and matter creation occurs during reheating at t_RH > t_end_inflation. UMF's bounded universe with breach-to-SMBH timeline has different cosmological-time structure. **Published-paper position:** UMF acknowledges its bounded-universe timeline is incompatible with standard inflationary cosmology at the timeline level, even where individual matter-creation mechanism mathematics may be importable.

**3. Particle-DM vs gravitoelectric-DM.** F-01 Section VI.1.2 surveys particle-DM candidates from preheating (WIMPzilla, axion, gravitino, moduli). UMF's gravitoelectric DM has no particles. **Published-paper position:** F-01 is cited as the modern review of particle-DM creation from preheating; UMF positions its gravitoelectric DM as an alternative DM mechanism class entirely.

**4. No direct preheating of gravitational waves.** F-01 Section VI.2 explicitly: "there is no direct preheating of gravitational waves. Nevertheless, gravitational waves can be produced by secondary processes... from the interaction of the classical matter waves produced during preheating. This is a re-scattering effect." Verified verbatim from arxiv-vanity snippet. **Critical contrast with UMF/GWM:** UMF/GWM treats geometric/gravitational waves as primary matter constituents, not secondary products of matter-field interactions. F-01 confirms that mainstream inflationary reheating is silent on direct GW-as-matter production; UMF's G-shock direct mechanism would be a genuinely novel position relative to the F-01 mainstream framing. **This is a useful disclosable contrast** strengthening UMF's distinctiveness without making any new exotic claim — the gap in mainstream reheating literature is real.

**5. Create-then-thermalize → thermal initial particle distribution after Micha-Tkachev turbulent thermalization.** F-01 Section IV: preheating produces highly non-thermal initial particle distribution; thermalization occurs in two phases (rapid turbulent stage; slower full thermalization). End state is thermal. UMF would need to specify whether its G-shock matter creation produces thermal or non-thermal initial distribution and what thermalization mechanism (if any) operates subsequently.

### Empirical-requirement assessment

F-01 is a review paper. Per RP §4 three-category framework:
- **Lab tests:** None. Reheating phenomena are not lab-accessible.
- **Observational tests:** Indirect via (i) CMB constraints on reheating temperature T_RH (typical bound T_RH < 10¹⁵ GeV from tensor-to-scalar ratio r); (ii) gravitational wave stochastic background from re-scattering (LISA/DECIGO targets at f ~ 10⁻³–10⁻¹ Hz); (iii) primordial black hole formation from metric preheating (Bassett-Tsujikawa 2001 hep-ph/0109212 and subsequent literature). None at 5σ confirmation; all bounded by constraints on inflationary parameters (Planck 2018, BICEP/Keck 2021 r < 0.036 at 95% CL — this is a constraint on tensor amplitude, not a positive detection).
- **Theoretical consistency:** Substantial — Mathieu equation, Floquet theory, Einstein equation coupling to scalar matter, QFT in curved spacetime all well-established and internally consistent. Partial satisfaction of RP §4 requirement 2 via theoretical-consistency category.

**Empirical-requirement waiver:** Granted on standard grounds (cosmological-epoch phenomenon, no direct lab access; observational constraints are upper bounds, not detections; theoretical consistency substantial). Per RP §4 standard, theoretical consistency substitutes as partial satisfaction.

### Cross-references

- **F-01 ↔ A-03 Valentini quantum non-equilibrium:** Both engage inflaton decay; A-03 is the contrasting-branch inflaton-decay framing under pilot-wave/quantum-non-equilibrium statistics (vs F-01's standard QFT statistics). F-01 + A-03 jointly bound the "inflaton-decay matter-creation" mechanism space.
- **F-01 ↔ A-05 oscillons:** Section VI.1.3 of F-01 touches inflaton-field localisation; A-05 (Amin et al., Zhang-Jain-Amin) is the modern oscillon-as-third-non-thermal-mechanism literature. F-01 is the upstream reheating-framework reference; A-05 is the specific oscillon-mechanism descendant.
- **F-01 ↔ A-07 DGTZ Bell-type QFT:** Both produce particles non-thermally; A-07 has explicit Fock-space stochastic jumps (Bell-type beables); F-01 has parametric resonance with adiabaticity-violation creation. Different mechanism types within same broad non-thermal class.
- **F-01 ↔ B-02 Brill-wave critical collapse:** F-01 metric preheating Section VI.2 explicitly notes NO direct GW preheating; B-02 provides the gravity-only matter-creation mechanism F-01 explicitly excludes. F-01 + B-02 jointly demonstrate the gap in mainstream reheating literature that UMF's G-shock mechanism would fill.
- **F-01 ↔ F-02 first-order PT:** F-01 and F-02 are the two standard non-cyclic post-inflation matter-formation mechanisms; F-01 reheating after inflation; F-02 phase-transition asymmetry generation. Often combined (electroweak baryogenesis during reheating at first-order EW PT).
- **F-01 ↔ D-01 trans-Planckian problem:** F-01 sub-Planckian inflationary scale H_inf ~ 10¹³–10¹⁴ GeV stays clear of the D-01 trans-Planckian regime; the trans-Planckian question does not arise for F-01 mechanism per se.

### Outside-corpus markers

- All Section I, II content (V(φ) forms, Klein-Gordon equation, m_pl⁻² ≡ G definition, chaotic inflation m ~ 10⁻⁶ m_pl) — **verified verbatim from ar5iv HTML.**
- Section VI.2 verbatim quote on "no direct preheating of gravitational waves" — **verified from arxiv-vanity snippet** (not directly cross-checked against PDF; secondary HTML rendering of arXiv source).
- Section VI.1.2 DM content characterisation (WIMPzilla, axion, gravitino, moduli) — **derived from secondary citing literature snippets** (Maleknejad-McDonough 2022 arXiv:2205.12983; Halverson et al. 2025 arXiv:2504.13256; Kolb-Long 2017 arXiv:1708.04293; Kolb-Chung-Riotto 1998 hep-ph/9802238), NOT directly verified from the 1001.2600 PDF for this entry; characterisation should be treated as standard-background reconstruction pending PDF verification if Stephen requests.
- Section III.2, III.4, III.5 (preheating mechanism details) — **drawn from standard background** consistent with Kofman-Linde-Starobinsky 1994/1997 (hep-th/9405187, hep-ph/9704452). Specific functional forms (Mathieu q parameter, broad-resonance regime) not separately verified for this entry.
- Section IV thermalization characterisation (turbulent thermalization per Micha-Tkachev 2004 hep-ph/0403101) — **drawn from standard background** consistent with widely-cited turbulent-thermalization result; not separately verified for this entry.
- Natural units c = ℏ = k_B = 1 convention — **confirmed via Lozanov 2019 lecture series** (arXiv:1907.04402, document 21 in Theme C session search) which explicitly uses same conventions when reviewing 1001.2600; not directly cross-checked against 1001.2600 PDF unit-convention statement.
- BICEP/Keck 2021 tensor-to-scalar bound r < 0.036 at 95% CL — **drawn from standard background**; not verified for this entry.

### Theme C T1 deep-pass disposition

**Sustain ESCALATE / NOTABLE-on-(a)+(d).** F-01 remains a valuable mainstream reheating reference for the synthesis: cited as the canonical modern review of post-inflation matter creation; useful contrast for UMF's distinctive G-shock mechanism. The honest disclosure of divergences (especially divergence 4, no direct GW preheating, and divergence 3, particle-DM vs gravitoelectric-DM) strengthens UMF's published-paper defensibility against omission-of-mainstream-context challenges.

**Methodology for synthesis paper:** F-01 to be cited as standard mainstream reference for: (i) post-inflation reheating context, (ii) parametric resonance / Mathieu equation mathematical framework that UMF may partially import for G-shock dynamics, (iii) explicit mainstream gap on direct GW-as-matter creation that UMF G-shock mechanism would fill. F-01 should NOT be cited as supporting evidence for UMF mechanisms — the divergences are too substantial — but as the principal mainstream reference for the alternative tradition against which UMF positions.

---

**Drafter:** Claude. Deep-pass entry follows Theme C scope per Research Plan v0.1 Draft and per-entry output requirements per Handoff §9. Open to Stephen-directed PDF-page requests for any element flagged as "drawn from standard background" or "verified from secondary snippet" if higher confidence is required for the synthesis-paper citation.
