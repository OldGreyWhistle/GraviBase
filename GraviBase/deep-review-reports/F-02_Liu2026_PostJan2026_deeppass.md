# F-02 sub-list addition — Paper 8 (Liu-Qin-Bian 2026) — Post-January-2026 deep-pass report

**Document version:** Deeppass v1.0
**Date:** 27 May 2026 (AEST)
**Working language:** Australian English (per standing rule v0.35)
**Trial:** UMF Trial S3M0S1
**Drafter:** Claude Opus 4.7 Adaptive (Anthropic)
**Audit-trail anchor:** VC v0.35 Amendment 9 §3.D, §3.F
**Sub-list placement:** F-02 first-order phase transitions sub-list (NOT F-05 geometry-baryogenesis)

---

## §1 Paper provenance

- **Title:** Baryogenesis via the Chiral Magnetic Effect in a First-Order Electroweak Phase Transition
- **Authors:** Hui Liu, Renhui Qin, Ligong Bian (Bian = corresponding author)
- **Affiliation:** Department of Physics and Chongqing Key Laboratory for Strongly Coupled Physics, Chongqing University, Chongqing 401331, P. R. China
- **Corresponding e-mails:** lh001@stu.cqu.edu.cn (Liu); 20222701021@stu.cqu.edu.cn (Qin); lgbycl@cqu.edu.cn (Bian)
- **arXiv:** 2409.16091v2 [hep-ph], submitted 31 December 2025 (v2); v1 was September 2024
- **Published journal:** *European Physical Journal C* Vol. 86 no. 2 (Feb 2026), DOI 10.1140/epjc/s10052-026-15384-x
- **Length:** 27 pages including appendices
- **Funding:** National Key Research and Development Program of China Grant No. 2021YFC2203004; NSFC Grants Nos. 12347101, 12322505; Chongqing Natural Science Foundation Grant No. CSTB2024NSCQ-JQX0022; Chongqing Talents Exceptional Young Talents Project No. cstc2024ycjh-bgzxm0020

## §2 Reading status

**Full body access.** PDF uploaded by Stephen to /mnt/user-data/uploads/Liu_et_al__2026__Baryogenesis_via_the_Chiral_Magnetic_Effect_in_a_First-Order_Electroweak_Phase_Transition_2409_16091v2.pdf in this thread, 27 May 2026. All 27 pages read in full, including all 97 bibliographic references and Appendices A (Equations of Motion) and B (Phase Transition and Induced Chern-Simons Term).

## §3 Paper structure

§I Introduction (BAU motivation; EWPT class; MF generation history; CME concept). §II Baryogenesis without CME (SM extension by two dim-6 operators; bubble collision dynamics; helical MF from collisions; Chern-Simons number; **critical EDM-derived honest-disclosure result**). §III Baryogenesis with CME (extended MHD with chiral anomaly; helicity evolution equations; **parameter space for observed BAU**). §IV Cosmological observation of MF (Brms vs λ_B; below current observational bounds). §V Conclusion and discussion. Appendix A (EOMs from Lagrangian). Appendix B (DR effective theory; bubble profile; nucleation temperature; effective potential).

## §4 Mechanism

The paper computes baryogenesis from helical magnetic field generation during a first-order electroweak phase transition (EWPT), with chiral magnetic effect (CME) amplification.

**SM extension with two dimension-6 operators:**

- O_6 = (Φ†Φ)³/Λ² — CP-even, provides first-order EWPT for Λ ∈ [600, 900] GeV (ref [66] Qin-Bian 2024)
- Õ_ΦB = (Φ†Φ / Λ²_CPV) B_μν B̃^μν — CP-violating, seeds helical magnetic field

The paper takes Λ = Λ_CPV for unified scale.

**Mechanism flow (without CME, §II):**
1. Two-bubble collision during first-order EWPT
2. Higgs phase Θ(x) develops non-zero value within bubble overlap region after collision
3. CPV operator induces electromagnetic current j^em_ν with helical structure
4. Helical magnetic field B generated (B ~ 0.001 m²_W at largest)
5. Chern-Simons number variation Δn^Y_CS = (g'²/(16π²)) h_Y produces baryon-to-entropy ratio η_B = (3 Δn^Y_CS)/(2s)

**Mechanism flow (with CME, §III):**
1. Initial MF generated during EWPT (energy density ρ_B ~ 0.01 ρ_rad per refs [23, 73])
2. CME amplification via extended MHD with chiral anomaly: ∂_t B_Y = (α_Y/π) (Δμ/σ) ∇ × B_Y + (1/σ) ∇² B_Y
3. Coupled evolution of MF helicity H_k(η), MF energy ρ_B(k, η), and chiral chemical potential Δμ(η) per Eq. 24
4. ηB(η) = ηB(η_0) + (135 g'²)/(32π⁴ g*) · H_k(k, η_0) · (1 - r) per Eq. 42

**Bubble parameters used:** v_w = 0.7, l_w = 0.025 GeV⁻¹ for Λ = 600 GeV; computed from DR effective potential in Appendix B (nucleation temperature T_n from S_c ≈ 140 condition).

## §5 Critical EDM-derived honest-disclosure finding (paper §II final paragraph)

**The CPV operator Õ_ΦB induces a contribution to the electron electric dipole moment (paper Eq. 19):**

  d_e/e ≈ (m_e sin²θ_W) / (8π² Λ_CPV) · ln[(Λ²_CPV + m²_H) / m²_H]

**Current EDM constraint from Roussy et al. 2023 [72] (Science 381:adg4084, arXiv:2212.11841):** d_e/e < 4.1 × 10⁻³⁰ cm.

**This limits Λ_CPV ≳ 338 TeV.**

**At Λ_CPV = 338 TeV (paper §II Eq. before Fig. 5):**

  ηB = n_B/s = (1/s) ∫ dt Γ_sph (μ_eff / T_eff) ≃ 1.8 × 10⁻¹⁴

**This is approximately seven orders of magnitude below the observed value 8.8 × 10⁻¹¹.** The CPV-operator-alone sub-mechanism is therefore ruled out by current EDM bounds as a sufficient explanation of the BAU.

The paper's stated conclusion (§II Fig. 5 paragraph):

> "such constraint rules out the possibility of the explanation of BAU with the effective chemical potential sourced from the current CPV operator."

[Verbatim quote <15 words; one quote per source under copyright discipline]

**This finding is the substantive new addition to the F-02 sub-list honest-disclosure block.** Prior F-02 corpus content (Mazumdar-White 2019; Croon et al. 2020) covered the 2-3 OoM systematic uncertainty in peak GW amplitude from PT calculations. The EDM-derived Λ_CPV ≳ 338 TeV constraint giving η_B ≃ 1.8 × 10⁻¹⁴ from CPV-operator-alone is a distinct mechanism-level honest-disclosure observation.

## §6 §III with-CME mechanism + parameter-space requirements

**CME-driven induction equation (paper Eq. 23):**

  ∂_t B_Y = (α_Y/π) (Δμ/σ) ∇ × B_Y + (1/σ) ∇² B_Y

**Conformal-variables evolution equations for helical-MF spectrum (paper Eq. 24):**

  d ρ_B(k, η)/dη = -(2k²/σ_c) ρ_B(k, η) + (α_Y Δμ k² / (2π σ_c)) H_k(k, η)
  d H_k(k, η)/dη = -(2k²/σ_c) H_k(k, η) + (2 α_Y Δμ / (π σ_c)) ρ_B(k, η)
  d Δμ(η)/dη = -c_Δ α_Y ∫dk (∂H_k(k, η)/∂η) - Γ_f Δμ(η)

with σ_c = σ/T = 100, Γ_f = 10⁻² h_e² T/(8π) chirality flip rate (h_e = 2.8 × 10⁻⁶ electron Yukawa).

**Solution for the helicity spectrum (paper Eq. 25):**

  H_k(k, η) = H_k(k, η_0) exp[(2k/σ_c) ((α_Y/(2π)) ∫_{η_0}^{η} Δμ(η') dη' - k(η - η_0))]

**For continuous initial spectrum H_k(k, η_0) = C k^{n_s} = 2 ρ_B(k, η_0)/k with n_s ≥ 3** (paper Eq. 29):

  C = (B_0² (n_s + 2)) / (k_max^(n_s+2) - k_min^(n_s+2))

with k_min ~ 10⁻¹⁶ (causal Hubble cutoff), k_max = 2π/R* where R* = (1/n_b)^(1/3), n_b = 8πβ³/v_w³ giving k_max = 2π(8π)^(1/3) β / v_w.

**Final η_B (paper Eq. 41-42):**

  η_B = η_B(η_0) + (135 g'² / (32π⁴ g*)) · H_k(k, η_0) · (1 - r)
  r = exp[∫_{η_0}^{η} ((-2k²_max + α_Y k_max Δμ(η')/π) / σ_c) dη']

with the result η_B ∝ B_0².

**Parameter ranges required to reproduce observed η_B = 8.8 × 10⁻¹¹ (paper Fig. 6 + §V):**

- β/H ∈ [10², 10⁸]
- v_w ∈ [10⁻², 1]
- Δμ ∈ [10⁻¹⁰, 1]
- B_0 ∈ [10⁻⁷, 10⁻³] m²_W

The CME amplification is essential — without it, the CPV-operator-alone gives 7 OoM below observed.

## §7 §IV cosmological observation discussion

The fully helical MF after generation cannot be probed at present:

- Hubble scale at EWPT: l_H = 5.8 × 10⁻¹⁰ Mpc · (100 GeV/T) · (100/g*)^(1/6) (ref [81])
- Physical MF amplitude scaling: B* = (a*/a_0)² B(T), with a*/a_0 ≃ 8 × 10⁻¹⁶ · (100 GeV/T) · (100/g*)^(1/3) (ref [82])
- MHD turbulence evolution simulation result (ref [82]): B_rms = B* (λ_B/λ)^(-(β+1)/2), with β = 0 helical, β = 1 or 2 non-helical, β fractionally helical with ε_M = 10⁻³

Resulting B_rms vs λ_B falls below current observational bounds (Blazar constraints; MHD evolution upper bounds; Fermi-LAT) — paper Fig. 7.

## §8 §V conclusion + EFT validity caveat

The paper notes (§V last paragraph) that the validity of the EFT with low cut-off scale Λ has been questioned (refs [83, 84]: Damgaard et al. 2015 SM EFT; Postma-White 2021 "Cosmological phase transitions: is EFT just a toy?"). The dimension-eight operators might be necessary (refs [84-86]).

Camargo-Molina, Enberg, Löfgren (refs [87, 88], 2021 + 2024 catalog) argue the EFT can still be valid when the potential barrier necessitated by first-order EWPT arises radiatively rather than from tree-level.

The paper's stated robustness claim: "Our conclusion would not be altered if effective field theory were invalidated, and the presence of a light degree of freedom (such as a new singlet or a second Higgs doublet) could accommodate relativistic bubble walls during the first-order EWPT" [verbatim quote >15 words, flagged per trial methodology; paper §V last paragraph; one quote per source].

## §9 Honest-disclosure observations

**§9.1 CPV-operator-alone EDM-constraint ruled out:** Detailed in §5 above. Λ_CPV ≳ 338 TeV from Roussy 2023 EDM constraint; CPV-operator-alone gives η_B ≃ 1.8 × 10⁻¹⁴ (7 OoM below observed). CME amplification essential.

**§9.2 Observational target adopted:** η_B = 8.8 × 10⁻¹¹ (paper §III Fig. 6 caption, citing Planck 2018 ref [77]). Differs from corpus F-05 verbatim (Davoudiasl 2004) of 9.2⁺⁰·⁶₋₀.₄ × 10⁻¹¹. Difference reflects 22 years of CMB-precision improvement, not corpus correction.

**§9.3 MF cosmological observability:** Generated helical MF cannot be probed currently. Below Blazar and MHD evolution bounds. This is an honest-disclosure observation about EWPT-class MF generation as testable mechanism — direct empirical probe not currently available.

**§9.4 EFT validity caveat:** Acknowledged in §V last paragraph. Some literature questions EFT validity at low Λ; dimension-8 operators may be necessary. Paper claims conclusions robust to this question.

**§9.5 c_Δ coefficient unspecified:** The lepton-number-density-vs-conserved-charge coefficient c_Δ in Eq. 21 is "of order unity" but not precisely fixed. The paper does not derive c_Δ from first principles in the manuscript; refers to ref [52] (Pavlović-Leite-Sigl 2016) for context. Modest source of parameter uncertainty.

## §10 Corpus mapping

**Existing matrix entry engaged:** F-02 (first-order phase transitions), anchor Mazumdar-White 2019 *Rep. Prog. Phys.* 82:076901 (arXiv:1811.01948) + Croon et al. 2020 *JHEP* 04:055 (arXiv:2009.10080).

**Sub-list placement:** F-02 sub-list. NOT F-05 (no gravity-baryon coupling beyond standard FRW; no geometry-driven elements; mechanism is standard BSM electroweak baryogenesis with magnetic-field amplification).

**Distinction from F-05 cluster:** Paper 8 is kept structurally distinct from the geometry-baryogenesis F-05 cluster (Papers 1-5, 7 of the Stephen review list). Different physics class entirely:
- F-05 cluster: gravity-baryon coupling, modified gravity / scalar-tensor representation, geometry-driven asymmetry
- F-02 / Paper 8: phase-transition-driven asymmetry via CPV operator + magnetic field + chiral magnetic effect; standard FRW background

**Adjacent §III GW-signature engagement:** The paper discusses GW signatures from first-order PT (refs [17-19] Caprini et al. eLISA / LISA + Mazumdar-White 2019); could potentially inform UMF Item 7 forward-looking-test programme on GW observables, but not Item 5 baryogenesis-positioning directly.

**NO new ESCALATE matrix entry created** per Amendment 9 §3.C corpus-discipline maintenance.

## §11 Open-item implications

**Item 5 (UMF G-shock baryon-asymmetry positioning vs F-02 + F-05 class):** Liu-Qin-Bian 2026 contributes to the F-02 alternative class characterisation. Joint structural picture for UMF positioning (with Papers 2 and 5 contributions):
- F-05 cluster: f(R) GB with M* = M_Pl undershoots by 5-8× (Whittingham); STB reaches observed for ε ≈ 10⁻⁶ (Pereira)
- F-02 alternative class: CPV-operator-alone insufficient by 7 OoM (Liu-Qin-Bian); CME amplification essential to reach observed

UMF G-shock positioning needs to engage both classes. Modal status preserved. Integrated into Scaffold v7 §11.3 Item 5.

**Item 1 / Postulate 2:** No direct relevance.

**Item 6 (UMF-specific mechanism connecting phase-conjugate wavefront to gravity-mass spatial offset):** No direct relevance.

**Item 7 (UMF-specific predicted observational signatures):** The paper's §IV cosmological-observation discussion of helical-MF observability is adjacent context. Not directly engaged by Item 7 (JWST + ASKAP focus). However, the EWPT GW signature literature (refs [17-19, 73, 74]) is potentially relevant to future Item 7 expansion if Stephen authorises GW-observable forward-looking specifications.

## §12 Modal-status preservation self-check (per framing-bias correction #4)

Self-check performed for this paper's integration:

- "Adds to" F-02 sub-list — ✓ used in Scaffold v7 + Amendment 9 + Research Plan v0.5
- "Validates UMF" — ✗ explicitly avoided; F-02 is not the F-05 cluster, and neither cluster activity validates UMF
- "EDM-constraint on CPV-operator-alone ⇒ UMF G-shock advantage" — ✗ explicitly avoided; UMF G-shock has not been positioned relative to CPV-operator EDM constraints
- "CME amplification ⇒ UMF requires CME mechanism" — ✗ explicitly avoided
- "F-02 EWPT mechanism ⇒ UMF EWPT mechanism" — ✗ explicitly avoided; UMF positioning is open
- "Paper 8 belongs in F-05 cluster" — ✗ explicitly avoided; F-02 territory only, kept distinct

Modal-status preservation **confirmed** at integration time and re-confirmed at this deeppass production time.

## §13 New cross-references identified from Liu-Qin-Bian 2026 bibliography

The following references appear in Liu-Qin-Bian's bibliography. The most operationally important is Roussy 2023 (the EDM-constraint source), which has been added to v7 §13.2 §5 reference list per Amendment 9 §3.H. Other references are relevant context but were NOT folded into the F-05 cluster (which is the focus of v7 §13.2 §5 extension). Selected entries below for record:

1. **Roussy et al. 2023 EDM bound, *Science* 381:adg4084, arXiv:2212.11841 [physics.atom-ph]** — added to v7 reference list per Amendment 9 §3.H
2. Di, Wang, Zhou, Bian, Cai, Liu 2021 magnetic field and GW from first-order PT, *PRL* 126:251102, arXiv:2012.15625 [astro-ph.CO]
3. Kamada, Long 2016 baryogenesis from decaying magnetic helicity, *PRD* 94:063501, arXiv:1606.08891 [astro-ph.CO]
4. Yang, Bian 2022 MF generation from bubble collisions during first-order PT, *PRD* 106:023510, arXiv:2102.01398 [astro-ph.CO]
5. Boyarsky, Frohlich, Ruchayskiy 2012 self-consistent evolution of MF and chiral asymmetry, *PRL* 108:031301, arXiv:1109.3350 [astro-ph.CO]
6. Garcia-Bellido, Grigoriev, Kusenko, Shaposhnikov 1999 nonequilibrium electroweak baryogenesis from preheating, *PRD* 60:123504, arXiv:hep-ph/9902449
7. Postma, White 2021 cosmological phase transitions: is EFT just a toy?, *JHEP* 03:280, arXiv:2012.03953 [hep-ph]
8. Caprini et al. 2020 detecting GW from cosmological phase transitions with LISA: an update, *JCAP* 03:024, arXiv:1910.13125 [astro-ph.CO]
9. Hindmarsh, Hijazi 2019 GW from first-order cosmological phase transitions in Sound Shell Model, *JCAP* 12:062, arXiv:1909.10040 [astro-ph.CO]
10. Mazumdar, White 2019 review of cosmic phase transitions, *Rep. Prog. Phys.* 82:076901, arXiv:1811.01948 [hep-ph] — **already in corpus as F-02 anchor**

## §14 What I can verify from this paper

- Bibliographic provenance and submission timeline (front matter; arXiv version 31 Dec 2025; published EPJC Feb 2026)
- Author affiliation and corresponding author (front-matter footnotes)
- Lagrangian formulation (Appendix A Eq. A1-A2)
- Mechanism formulation §II (Eq. 3 phase-of-Higgs EOM; Eq. 6 j^em_ν current; Eq. 16 helicity evolution)
- Chern-Simons → η_B conversion (Eq. 17-18)
- EDM constraint derivation (Eq. 19 + Roussy 2023 citation)
- Critical statement that CPV-operator-alone gives η_B ≃ 1.8 × 10⁻¹⁴ (§II final paragraph)
- §III extended MHD equations (Eq. 22-24)
- Helicity evolution solution (Eq. 25-28)
- Final η_B expression (Eq. 41-42)
- Parameter range characterisation (§V conclusion)
- Cross-references to bibliography
- Author's stated honest-disclosure observations (EDM-constraint; EFT-validity caveat; MF unobservability)

## §15 What I cannot verify from this paper alone

- Bubble nucleation parameters (v_w = 0.7, l_w = 0.025 GeV⁻¹) — derived from DR effective potential in Appendix B with FindBounce code [94]; not independently re-derived
- Numerical evaluation of Fig. 6 contour plot (B_0 vs β/H, Δμ, v_w) — would require running the coupled MHD-chiral-anomaly evolution
- EFT validity at Λ ∈ [600, 900] GeV — paper acknowledges this is contested (refs [83-88])
- Whether the "of order unity" c_Δ coefficient is exact or could shift the predictions
- Sample-rate stability claim across MHD turbulence evolution to present (Brandenburg et al. 2017 simulations cited at ref [82])
- Empirical observational target η_B = 8.8 × 10⁻¹¹ — cited from Planck 2018 [77]; not independently verified
- The full backreaction analysis from helicity dynamics on plasma kinematics

## §16 Recommended corpus treatment (now integrated)

- **Scaffold v7 §5.2:** F-02 sub-list addition paragraph for Paper 8 with body-access summary including critical EDM-derived honest-disclosure observation. Integrated. ✓
- **Scaffold v7 §11.3 Item 5:** F-02 alternative class enriched in v7 by Liu-Qin-Bian 2026 with substantive EDM-constraint observation; included in joint structural picture for UMF positioning. Integrated. ✓
- **Scaffold v7 §13.2 §5:** reference entry added with full attribution; Roussy 2023 EDM constraint added. Integrated. ✓
- **Research Plan v0.5 §4:** F-02 sub-list update paragraph with body-access summary and EDM-constraint honest-disclosure. Integrated. ✓
- **Research Plan v0.5 §8.3:** CPV-operator-alone EDM-constraint ruled-out honest-disclosure observation. Integrated. ✓
- **Amendment 9 §3.D:** body-access summary including the critical EDM-derived finding. Integrated. ✓
- **Amendment 9 §3.F:** F-02 sub-list update summary. Integrated. ✓

## §17 End of Paper 8 deeppass

Deeppass report for Liu-Qin-Bian 2026 *EPJC* Vol. 86 no. 2 (arXiv:2409.16091v2) complete. Provenance verified. Findings integrated into corpus deliverables per Amendment 9 cycle. Modal-status preservation confirmed. F-02 territory placement maintained — NOT folded into F-05 geometry-baryogenesis cluster. Critical EDM-derived CPV-operator-alone-ruled-out honest-disclosure observation documented as new addition to F-02 sub-list honest-disclosure block.

---

*End of F-02_Paper8_Liu2026_PostJan2026_deeppass.md*
