# F-05 sub-list addition — Paper 5 (Whittingham 2026) — Post-January-2026 deep-pass report

**Document version:** Deeppass v1.0
**Date:** 27 May 2026 (AEST)
**Working language:** Australian English (per standing rule v0.35)
**Trial:** UMF Trial S3M0S1
**Drafter:** Claude Opus 4.7 Adaptive (Anthropic)
**Audit-trail anchor:** VC v0.35 Amendment 9 §3.D, §3.E, §3.K
**Sub-list placement:** F-05 modified-gravity-extensions sub-list

---

## §1 Paper provenance

- **Title:** Gravitational baryogenesis in f(R) cosmologies
- **Author:** Ian B. Whittingham (single author)
- **Affiliation:** College of Science and Engineering, James Cook University, Townsville, Queensland, Australia 4811
- **Corresponding e-mail:** Ian.Whittingham@jcu.edu.au
- **arXiv:** 2602.19075v2 [astro-ph.CO], submitted 24 May 2026 (v2)
- **Published journal:** Not visible in arXiv front matter at v2 stage; preprint format; presumably submitted to *JCAP* given referencing pattern and section formatting
- **Length:** 36 pages
- **Subject classification:** astro-ph.CO (primary)
- **Funding / acknowledgements:** None visible
- **Author location relevance:** JCU Townsville (Australian researcher; consistent with Stephen's working context; noted for completeness only, no analytic implication)

## §2 Reading status

**Full body access.** PDF uploaded by Stephen to /mnt/user-data/uploads/Whittingham__2026__Gravitational_baryogenesis_in_f_R__cosmologies_2602_19075v2.pdf in this thread, 27 May 2026. All 36 pages read in full, including all references and Tables 1 and 2.

## §3 Paper structure

§1 Introduction (η definition; Sakharov conditions; original Davoudiasl 2004 framework derivation in GR). §2 f(R) cosmologies (basic equations; equivalence with scalar-tensor models via Jordan-to-Einstein conformal transformation; Starobinsky R²; R²-corrected models). §3 Inflation and reheating in f(R) cosmologies (CGPP cosmological gravitational particle production; Starobinsky reheating dynamics). §4 Existing calculations of gravitational baryogenesis (Davoudiasl 2004 three scenarios; Lambiase-Scarpetta 2006; Pizza 2015; Ramos-Páramos 2017; Odintsov-Oikonomou Gauss-Bonnet, LQC, f(T); Pereira et al. 2025; Pereira 2026 STB). §5 Implications of recent CMB measurements (Planck; ACT 2025 Louis et al.; SPT-3G 2025 Camphuis et al.; BICEP/Keck; Ketov-Pozdeeva-Vernov 2025; Odintsov-Oikonomou 2025 power-law model). §6 Scalaron calculations of gravitational baryogenesis (§6.1 framework; §6.2 Starobinsky model; §6.3 new power-law model). §7 Summary and conclusions.

## §4 Mechanism + methodological distinction

**Methodological distinction from prior F-05 sub-list entries:** Whittingham computes gravitational baryogenesis using the **Einstein-frame scalaron approach** (scalaron field φ = κ⁻¹√6 ln Ω introduced via conformal transformation g^J_{μν} = Ω⁻² g^E_{μν}, Ω² = df/dR) rather than the more common Jordan-frame approach used in Lambiase-Scarpetta 2006 and most prior corpus references. Stated motivation (paper §2.2): "Studying the evolution of the scalaron in the Einstein frame clarifies the physical picture and understanding the dynamics."

**Mechanism:** Standard gravitational-baryogenesis action S_GB = (1/M²*) ∫ d⁴x √(-g) (∂_μ R) j^μ_B (Davoudiasl 2004 baseline). For an expanding spatially uniform homogeneous universe ∂_0 R ≠ 0 and ∂_i R = 0; baryon asymmetry factor:

  η = -[15 g_B / (4π² k_B g*(T))] · (∂_0 R) / (M*² T) | at T=T_D

with g_B = 2 (baryon spin states), g*(T) = 106.75 for k_B T ≫ m_t c².

The two specific f(R) models computed are:

**Model 1 — Starobinsky R²:** f(R) = R + R²/(6M̃²). Scalar potential U(φ) = (3M̃²/(4κ²)) · [e^(-√(2/3)κφ) - 1]² (paper Eq. 2.38). M̃/M_Pl ≃ 1.3 × 10⁻⁵ for N* ≃ 55 e-folds compatible with Planck 2018 ns ≈ 0.965 (paper §5).

**Model 2 — Odintsov-Oikonomou 2025 power-law:** f(R) = (16 c_1 / ((4+k)(8+k))) R^(2+k/4) + c_2 R + c_3, constructed from slow-roll inflation parameters of f(R) gravity (paper §5 / Eq. 5.19). Compatible with Planck for k ∈ [-0.038, -0.03]; compatible with ACT for k ∈ [-0.0282, -0.022].

For the more general power-law f(R_J) = λ R_J^(2+ε) + c_2 R + c_3 (paper §6.3 Eq. 6.47, generalising the Odintsov-Oikonomou form), Whittingham derives a new analytic approximate solution for the slow-roll era under the assumptions Ω² ≫ c_2 and c_2 Ω⁻² ≫ |α| where α = ε/(1+ε). The Starobinsky case (ε = 0, λ = 1/(6M̃²), c_2 = 1, c_3 = 0) is recovered as a limit; the author explicitly verifies the consistency-with-Starobinsky-limit checks (Eq. 6.111 reduces to standard Starobinsky form when α → 0).

## §5 Analytic-approximation derivation (paper §6.2 Starobinsky; §6.3 power-law)

**Slow-roll field equations (paper §6.1):** H_E = κ √(U(φ)/3); dH_E/dt_E = -(κ²/2) (dφ/dt_E)²; dφ/dt_E = -(dU/dφ)/(κ √(3U(φ))).

**Starobinsky scalaron solution (paper §6.2):**
- φ(t_E) = (1/κ) √(3/2) ln [d²_init - (2M̃/3)(t_E - t_E,init)] (Eq. 6.9)
- H_E(t_E) = (M̃/2) · [1 - 1/(d²_init - (2M̃/3)(t_E - t_E,init))] (Eq. 6.11)
- a_E(t_E) = a_E(t_E,init) · e^((t_E - t_E,init) M̃/2) · [1 - (2M̃/(3d²_init))(t_E - t_E,init)]^(3/4) (Eq. 6.12)
- R_J(t_E) = 3M̃² [e^(√(2/3)κφ(t_E)) - 1] (Eq. 6.15)

Conversion t_E → t_J via Eq. 6.17-6.18. Defining τ(t_J) ≡ d_init - (M̃/3)(t_J - t_J,init), the Jordan-frame quantities are:
- H_J(t_J) = τ(t_J) (M̃/2) · [1 - (1/3) τ(t_J)⁻²]
- dR_J/dt_J = -2 M̃³ τ(t_J)
- Energy density of created radiation given by integral I_τ (paper Eq. 6.29-6.30, analytically evaluable)

**Power-law analytic solution (paper §6.3, claimed new):**
- φ(t_E) = (2/((α+2)κ)) √(3/2) ln [d̂²_init - γ(t_E - t_E,init)] (Eq. 6.64) where γ ≡ (2/3) κ c_2 (α+2) √(β/3)
- Similar τ̂(t_J) ≡ [d̂^(2α̂)_init - γα̂(t_J - t_J,init)]^(1/(α+1)) with α̂ ≡ (α+1)/(α+2)
- dR_J/dt_J = -ζ [τ̂²(t_J) - c_2]^(-α) τ̂^(1-α)(t_J) where ζ is a paper-defined prefactor (Eq. 6.95)
- Energy density integral I_τ(a, b, c, d, e) (paper Eq. 6.102) — requires numerical quadrature; no analytic form

**Self-consistency check:** for ε = 0 (Starobinsky limit), the integral I_τ(3, 2, 2, 1, 2) = I_τ, and Eq. 6.108 / 6.109 reduce to Eq. 6.40 / 6.42 (Starobinsky cases). Author explicitly checks.

## §6 Numerical results (paper Tables I and II)

**Adopted observational target:** η_obs = (8.65 ± 0.09) × 10⁻¹¹ (CMB) per refs [2, 3]; (8.2 – 9.4) × 10⁻¹¹ (BBN range).

**Model parameters fixed:** M̃/M_Pl = 1.2 × 10⁻⁵; M* = M_Pl; d_init = d̂_init = 10.0 (giving φ̃_init = √6 ln d_init = 5.6).

**Table I (Starobinsky, paper §6.2):** η computed at 14 time points across the slow-roll era (equal log-spaced in t̃_J), giving η ∈ {1.463, 1.455, 1.453, 1.444, 1.435, 1.424, 1.411, 1.393, 1.369, 1.337, 1.295, 1.235, 1.149, 1.051} × 10⁻¹¹.

**Range:** η = (1.05 – 1.46) × 10⁻¹¹.

**Table II (Odintsov-Oikonomou power-law, k = -0.03, paper §6.3):** η ∈ {1.527, 1.519, 1.513, 1.506, 1.497, 1.485, 1.469, 1.449, 1.422, 1.387, 1.339, 1.273, 1.177, 1.063} × 10⁻¹¹.

**Range:** η = (1.06 – 1.53) × 10⁻¹¹.

**Slow-roll endpoint:** t̃_J,SR - t̃_J,init = 3(d_init - 1) = 27 for Starobinsky model; same for power-law (paper Eq. 6.117).

## §7 Critical honest-disclosure finding (paper §7 Summary)

**For both models with M* = M_Pl, η falls approximately 5–8× below observed value η_obs = 8.65 × 10⁻¹¹.**

Whittingham's stated resolution (paper §7, repeated in abstract and §6.2/§6.3 conclusions):

> "The values of η for both models have been calculated for M* = M_Pl and are quite close to the observed value η_obs = 8.65 × 10⁻¹¹. Since η ∝ (1/M*)², reducing M* slightly from M_Pl to 0.4 M_Pl would bring the calculated values into agreement with the observed value."

[Verbatim quote >15 words, flagged per trial methodology; paper §7 second-last paragraph and abstract abstract paragraph; one quote per source under copyright discipline]

Whittingham does NOT characterise this M* ≈ 0.4 M_Pl reduction as fine-tuning. He presents it as the parameter adjustment required for observational agreement. The framing-neutral characterisation is: **state-of-the-art CMB-data-tuned f(R) models with the EFT cutoff at the natural Planck scale undershoot observed η by factor 5–8; M* must be sub-Planckian (≈ 0.4 M_Pl) for agreement.**

This is a substantive new finding for the F-05 cluster honest-disclosure block alongside:
- existing Ṙ=0 radiation-domination caveat (corpus baseline)
- Arbuzova et al. 2023 stability concerns (surfaced via Pereira 2026 bibliography)

## §8 §5 CMB-data update integration

Paper §5 brings post-cutoff CMB measurements relevant to F-05 cluster phenomenology:

**Planck 2018:** ns = 0.9649 ± 0.0042 at 68% CL; with BICEP/Keck: ns = 0.9652 ± 0.0042; current 95% CL upper bound on r is 0.036.

**ACT 2025 (Louis et al., Calabrese et al. arXiv:2503.14454):** ns = 0.9666 ± 0.0077 at 68% CL (ACT alone); ACT + Planck + lensing: ns = 0.9713 ± 0.0037 at 68% CL (in tension with Planck-only); with DESI BAO: P-ACT-LB gives ns = 0.9743 ± 0.0034 at 68% CL; running index α_s = 0.0062 ± 0.0052.

**SPT-3G 2025 (Camphuis et al. arXiv:2506.20707):** ns = 0.951 ± 0.011 at 68% CL (below Planck/lensing); Planck + ACT + SPT combined: ns = 0.9684 ± 0.0030 at 68% CL.

These post-cutoff CMB measurements were NOT in the UMF corpus prior to this reading layer. They drive the Ketov-Pozdeeva-Vernov 2025 (arXiv:2508.08927) extended Starobinsky form f₅(R) with R³, R⁴, R⁵ corrections, and the Odintsov-Oikonomou 2025 (arXiv:2509.06251) power-law form that Whittingham 2026 §6.3 computes. These references are now in the v7 §13.2 §5 reference list per Amendment 9 §3.H.

## §9 §4 review of existing GB literature (substantive corpus-touching content)

Whittingham §4 reviews:

- **Davoudiasl et al. 2004 [8]** — three scenarios (radiation-dominated with trace anomaly; matter-dominated reheating w=0; non-thermal component w > 1/3). Trace anomaly gives 1 - 3w ~ 10⁻² – 10⁻¹; δn_b/s ≈ 4.6 × 10⁻¹⁰ (1 - 3w) for TD ~ M_inf ~ 10¹⁶ GeV (Eq. 4.5).
- **Lambiase-Scarpetta 2006 [30]** — f(R) = (R/A)ⁿ power law; assumes a(t) ~ tᵅ; requires n = 2α; constraints 0.46 ≤ α ≤ 0.49 for BBN compatibility; preferred α = 0.4645 corresponds to n ≈ 0.97 (f nearly linear in R).
- **Pizza 2015 [32]** — Starobinsky model with modified radiation-dominated ansatz a(t) = a_0 t^(1/2) + λ(t). Whittingham explicitly states (paper §4 last paragraph of Pizza review): "the Pizza model is unable to generate the observed asymmetry of ≈ 10⁻¹⁰."
- **Ramos-Páramos 2017 [33]** — nonminimally coupled f(R) with action S = ∫d⁴x √(-g) [(1/(2κ²)) f_1(R) + f_2(R) ℒ_m]. Power-law forms; minimum coupling n=0 case generalises Lambiase-Scarpetta with -0.07 ≃ m ≃ 0.19 for T_D = 2 × 10¹⁶ GeV; modified Starobinsky form with M_1 ~ 10¹² GeV.
- **Odintsov-Oikonomou Gauss-Bonnet [34]** — coupling j^μ_B ∂_μ G where G is the Gauss-Bonnet invariant; second model with R + f(G) gravity, f(G) = f_0 G^γ; asymmetry ~ T^(5/γ - 1).
- **Odintsov-Oikonomou LQC [35]** — Einstein-Hilbert with Loop Quantum Cosmology corrections; additional term ∝ (1 + 3w) ρ²/ρ_c in R-dot expression.
- **Oikonomou-Saridakis f(T) [36]** — torsion-based; f(T) = T case not compatible with observed asymmetry; f(T) ~ (-T)ⁿ with coupling to ∂_μ f(T) can produce compatible values.
- **Pereira et al. [37]** = Pereira-Lobo-Mimoso 2025 *Phys. Lett. B* 866:139521 arXiv:2504.21504 — f(R, T²) gravity, T² ≡ T_{μν} T^{μν}; asymmetry ~ Ṫ²; for perfect fluid T² = ρ²(1 + 3w).
- **Pereira [38] = Paper 2 of Stephen's review list** — STB framework. Whittingham summarises: "viable baryogenesis obtained for ε = O(10⁻⁶) with T_D = 8.5 × 10¹³ GeV." Independent cross-reference from second 2026 author to Paper 2 of the review list.

**Independent cluster-confirmation observation:** the fact that Whittingham 2026 (Paper 5) cites Pereira 2026 (Paper 2) in §4 confirms the active 2026 cluster characterisation. Both papers are part of the same research domain and reference each other.

## §10 Honest-disclosure observations

**§10.1 η-undershoot in current f(R) models with M* = M_Pl:** Detailed in §7 above. Affects both Starobinsky and Odintsov-Oikonomou 2025 power-law forms.

**§10.2 Observational target adopted by Whittingham 2026:** η_obs = (8.65 ± 0.09) × 10⁻¹¹ (CMB) per refs [2, 3]; differs from corpus F-05 verbatim (Davoudiasl 2004) of 9.2⁺⁰·⁶₋₀.₄ × 10⁻¹¹. Difference reflects 22 years of CMB-precision improvement, not corpus correction.

**§10.3 Approximation validity:** Whittingham §7 notes that the analytic approximation for the power-law model assumes Ω² ≫ c_2 and c_2 Ω⁻² ≫ |α|. The validity is checked numerically by integrating the slow-roll equation over the slow-roll region using equally-spaced log grid; differences < 1% for most of the range, but approximation breaks down near end of slow-roll (φ → 0). Slow-roll approximation strictly no longer valid when φ ≈ 0.

**§10.4 Pizza model "unable to generate observed asymmetry" verbatim observation:** Whittingham §4 review of Pizza 2015 explicitly states the model fails. This is honest-disclosure content for the F-05 cluster — prior f(R) modifications cannot reach observed value in some attempted formulations.

**§10.5 Slow-roll vs reheating sub-dominance assumption:** Whittingham §7 documents that beginning of radiation dominance ρ̃_grav = ρ̃_rad occurs "well into the fast-roll oscillation regime" at t ≈ 2.2 × 10¹⁶ M̃ and T_RD = 1.4 × 10⁷ GeV. This is significantly later than the slow-roll era used for the η computation; the analytic results are valid for the slow-roll era but the model dynamics extend further.

## §11 Corpus mapping

**Existing matrix entry engaged:** F-05 (gravitational baryogenesis), anchor Davoudiasl-Kitano-Kribs-Murayama-Steinhardt 2004 *PRL* 93:201301.

**Sub-list placement:** F-05 modified-gravity-extensions sub-list. Whittingham 2026 sits alongside Lambiase-Scarpetta 2006, Fukushima-Mizuno-Maeda 2016, McDonald-Shore 2015-2017, Goodarzi 2026, Pereira 2026, Cruz-Pereira-Lobo 2025/2026, Malakar-Mazumdar-Gohain-Bhuyan 2026. Methodologically distinct from these via the Einstein-frame scalaron approach.

**Adjacent §10.4 empirical-engagement engagement:** The §5 CMB-data update (ACT, SPT-3G, BICEP/Keck) is partially adjacent to the existing §10.4 empirical-engagement framework (JWST + ASKAP focus). The Roman / DESI DR3 / SKA forward-looking timeline in §10.4.5 is now complemented by CMB-cluster forward-looking observations.

**NO new ESCALATE matrix entry created** per Amendment 9 §3.C corpus-discipline maintenance.

## §12 Open-item implications

**Item 5 (UMF G-shock baryon-asymmetry positioning vs F-02 + F-05 class):** SUBSTANTIVE. Whittingham 2026 contributes one specific structural observation to the F-05 cluster picture: state-of-the-art f(R) GB models (both Starobinsky and the CMB-data-tuned Odintsov-Oikonomou 2025 power-law form) require M* ≈ 0.4 M_Pl to reach observed η; with M* = M_Pl they undershoot by factor 5–8. This sits alongside the Pereira 2026 observation that STB with ε ≈ 10⁻⁶ reaches observed η. UMF positioning under Item 5 needs to confront: does UMF G-shock naturally produce η_obs without f(R) M* tuning? Modal status preserved. Integrated into Scaffold v7 §11.3 Item 5.

**Item 1 / Postulate 2:** No direct relevance. Whittingham focuses on forward inflationary-era baryogenesis only; does not address reverse-baryogenesis or endpoint phenomenology.

**Item 7 (UMF-specific predicted observational signatures):** The §5 CMB-data update (ACT, SPT-3G) provides relevant context for UMF empirical engagement on inflationary-era observables, though Whittingham does not propose UMF-specific predictions. Could inform forward-looking-test timeline for any UMF inflationary signatures (separate from JWST/ASKAP focus).

## §13 Modal-status preservation self-check (per framing-bias correction #4)

Self-check performed for this paper's integration:

- "Strengthens / enriches" F-05 cluster — ✓ used in Scaffold v7 + Amendment 9 + Research Plan v0.5
- "Validates UMF" — ✗ explicitly avoided
- "Shows f(R) GB problematic and therefore UMF needed" — ✗ explicitly avoided; η-undershoot is a finding about specific f(R) models with M* = M_Pl, not a claim about UMF G-shock
- "η-undershoot ⇒ UMF G-shock advantage" — ✗ explicitly avoided; UMF G-shock has not been computed in comparable framework
- "Whittingham Einstein-frame approach ⇒ UMF Einstein-frame approach" — ✗ explicitly avoided; UMF positioning is open

Modal-status preservation **confirmed** at integration time and re-confirmed at this deeppass production time.

## §14 New cross-references identified from Whittingham 2026 bibliography

The following references appear in Whittingham's bibliography and were not previously in the UMF corpus. All flagged for v0.5 / v7 reference-list integration per Amendment 9 §3.H and integrated into Scaffold v7 §13.2 §5:

1. Ramos, Páramos 2017 nonminimally coupled f(R) GB, *Phys. Rev. D* 96:104024, arXiv:1709.04442 [gr-qc]
2. Pizza 2015 baryo-leptogenesis modified gravities, arXiv:1506.08321 [gr-qc] — **honest-disclosure: Whittingham explicitly notes Pizza model "unable to generate observed asymmetry"**
3. Motohashi, Nishizawa 2012 reheating after f(R) inflation, *Phys. Rev. D* 86:083514, arXiv:1204.1472 [astro-ph.CO] — **foundational Einstein-frame scalaron approach for Starobinsky model**
4. Ketov, Pozdeeva, Vernov 2025 inflation in F(R) gravity revisited after ACT, *JCAP* 12:040, arXiv:2508.08927 [gr-qc]
5. Odintsov, Oikonomou 2025 rectifying power-law f(R) gravity in view of ACT, arXiv:2509.06251 [gr-qc] — **basis of Whittingham §6.3 model**
6. Louis et al. (ACT) 2025 DR6 power spectra, arXiv:2503.14454 [astro-ph.CO]
7. Calabrese et al. (ACT) 2025 DR6 extended cosmological models, arXiv:2503.14454 [astro-ph.CO]
8. Camphuis et al. (SPT-3G) 2025, arXiv:2506.20707 [astro-ph.CO]
9. BICEP/Keck 2021, arXiv:2110.00483 [astro-ph.CO]
10. Kolb, Long 2024 cosmological gravitational particle production, *Rev. Mod. Phys.* 96:045001, arXiv:2312.09042 [astro-ph.CO]
11. Appleby, Battye, Starobinsky 2010 gR²-AB model, *JCAP* 1006:005, arXiv:0909.1737 [astro-ph.CO]
12. Ellis et al. 2020 building inflation in no-scale supergravity, arXiv:2009.01709 [hep-ph]
13. Ellis et al. 2025 deformations of Starobinsky in no-scale SU(5) SO(10) GUTs, arXiv:2508.13279 [hep-ph]

## §15 What I can verify from this paper

- Bibliographic provenance and submission timeline (front matter; arXiv version 24 May 2026)
- Mathematical structure of slow-roll analytic derivation (paper §6.1 Eq. 6.2-6.4)
- Starobinsky analytic solutions (paper §6.2 Eq. 6.6-6.42)
- Power-law model analytic solutions (paper §6.3 Eq. 6.46-6.115) — internal-consistency checks performed by author (reduction to Starobinsky in ε → 0 limit confirmed)
- Numerical Tables I and II — values are stated; internal consistency with stated equations is plausible but I have not re-run the numerical evaluation
- Review of existing GB literature in §4 — bibliographic citations cross-reference correctly with corpus and other Stephen-list papers
- §5 CMB-data values (Planck, ACT, SPT-3G) cross-reference correctly with cited references
- Cross-reference to Pereira 2026 (ref [38]) confirming Paper 2 cluster membership
- Author's stated honest-disclosure observations (η-undershoot; approximation validity range)

## §16 What I cannot verify from this paper alone

- Numerical values in Tables I and II (η values to 4 significant figures) — would require re-running the numerical evaluation from the stated equations
- BBN bound ε ≲ 4 × 10⁻⁶ — cited from Kusakabe et al. 2015 [31]; not independently verified
- Empirical observational target η_obs = (8.65 ± 0.09) × 10⁻¹¹ — cited from refs [2, 3]; not independently verified
- The claim that the power-law model analytic approximate solutions are "new" — would require literature search to verify novelty
- Whether the analytic approximation Ω² ≫ c_2 and c_2 Ω⁻² ≫ |α| is satisfied at the stated parameter values (paper §7 reports numerical check; not independently verified)
- The factor-0.4 reduction of M* required for agreement (consequence of stated η ∝ (M̃/M*)² scaling combined with computed central η ~ 1.5 × 10⁻¹¹ vs observed 8.65 × 10⁻¹¹: √(8.65/1.5) ≈ 2.4, so M* / M_Pl ≈ 1/2.4 ≈ 0.42 — consistent with paper's "0.4 M_Pl" rounded down; not a precise verification)

## §17 Recommended corpus treatment (now integrated)

- **Scaffold v7 §5.2:** F-05 modified-gravity-extensions sub-list expanded with Whittingham 2026 in cluster paragraph; η-undershoot finding included as honest-disclosure observation. Integrated. ✓
- **Scaffold v7 §11.3 Item 5:** substantively updated with cluster content including Whittingham 2026 η-undershoot finding for joint structural picture. Integrated. ✓
- **Scaffold v7 §13.2 §5:** reference entry added with full attribution; new antecedent references and post-cutoff CMB measurements added. Integrated. ✓
- **Research Plan v0.5 §3:** F-05 cluster sub-list update paragraph for Whittingham 2026 with body-access summary and η-undershoot honest-disclosure. Integrated. ✓
- **Research Plan v0.5 §5.1:** Item 5 substantive update text. Integrated. ✓
- **Research Plan v0.5 §8.2:** η-undershoot honest-disclosure observation. Integrated. ✓
- **Amendment 9 §3.D:** body-access summary including the critical honest-disclosure finding. Integrated. ✓
- **Amendment 9 §3.E:** F-05 cluster updates summary. Integrated. ✓

## §18 End of Paper 5 deeppass

Deeppass report for Whittingham 2026 arXiv:2602.19075v2 complete. Provenance verified. Findings integrated into corpus deliverables per Amendment 9 cycle. Modal-status preservation confirmed. Critical η-undershoot honest-disclosure observation documented as new addition to F-05 cluster honest-disclosure block.

---

*End of F-05_Paper5_Whittingham2026_PostJan2026_deeppass.md*
