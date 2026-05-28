# F-05 sub-list addition — Paper 2 (Pereira 2026) — Post-January-2026 deep-pass report

**Document version:** Deeppass v1.0
**Date:** 27 May 2026 (AEST)
**Working language:** Australian English (per standing rule v0.35)
**Trial:** UMF Trial S3M0S1
**Drafter:** Claude Opus 4.7 Adaptive (Anthropic)
**Audit-trail anchor:** VC v0.35 Amendment 9 §3.D, §3.E, §3.K
**Sub-list placement:** F-05 modified-gravity-extensions sub-list

---

## §1 Paper provenance

- **Title:** Scalar–tensor baryogenesis: a scalar–tensor completion of gravitational baryogenesis
- **Author:** David S. Pereira (single author)
- **Affiliations:** (a) Departamento de Física, Faculdade de Ciências da Universidade de Lisboa, Edifício C8, Campo Grande, 1749-016 Lisboa, Portugal; (b) Instituto de Astrofísica e Ciências do Espaço, Edifício C8, Campo Grande, 1749-016 Lisboa, Portugal
- **Corresponding e-mail:** djpereira@fc.ul.pt
- **Journal:** *Physics Letters B* 875 (2026) 140312
- **DOI:** 10.1016/j.physletb.2026.140312
- **arXiv:** 2412.06984 [gr-qc] (preprint of same paper)
- **Editor:** P. Brax
- **Submission timeline:** Received 23 January 2026; revised 22 February 2026; accepted 24 February 2026; online 26 February 2026
- **Length:** 10 pages
- **Funding:** SCOAP³
- **Licence:** CC BY 4.0 open access
- **Acknowledgements:** José Pedro Mimoso, Francisco Lobo, Miguel Pinto, Jess Rutschi; FCT grants UIDB/04434/2020, UIDP/04434/2020

## §2 Reading status

**Full body access.** PDF uploaded by Stephen to /mnt/user-data/uploads/Pereira__2026__Scalar_tensor_baryogenesis__A_scalar_tensor_completion_of_gravitational_baryogenesis_1-s2_0-S0370269326001668-main.pdf in this thread, 27 May 2026. All 10 pages read in full, including all 78 bibliographic references.

## §3 Paper structure

§1 Introduction (motivation; observational target n_b/s = (8.8 ± 0.6) × 10⁻¹¹; original Davoudiasl 2004 GB review). §2 Scalar-tensor gravity (Brans-Dicke baseline; F(R) to scalar-tensor mapping per Teyssandier-Tourrenc; Einstein-frame conformal transformation). §2.1 General N-field scalar-tensor representation. §3 Scalar-tensor baryogenesis (STB) mechanism. §3.1 Baryon asymmetry generation. §3.2 Einstein-frame formalism. §3.3 Relation between GB and STB (subsections 3.3.1 GB→STB map with Proposition 1; 3.3.2 STB→GB map with Proposition 2). §4 Application to F(R) = M_Pl^(2-2ε) R^(1+ε). §5 Summary and discussion.

## §4 Mechanism

The mechanism proposed is **Scalar-Tensor Baryogenesis (STB)**. The CP-violating bias needed for baryogenesis is sourced by the gravitational scalars that appear in scalar-tensor representations of modified gravity. The defining interaction is the derivative coupling:

  ℒ_int = (c_STB / M*^d) ∇_μ f(φ_i) J^μ_{B-L}

where c_STB is a dimensionless coupling, M* is the EFT cutoff (Λ_EFT = M*), d is the mass dimension of f, and J^μ_{B-L} is the anomaly-free B−L current. In a homogeneous FRW background, this acts as an effective chemical potential μ_{B-L} ∝ ḟ, driving the plasma to a nonzero equilibrium B−L density while B−L-violating reactions are active. The asymmetry freezes in at the decoupling temperature T_D defined by Γ_{B-L}(T_D) = H(T_D).

The choice of B−L current is justified on two grounds: (i) anomaly cancellation in SM gauge backgrounds means ∇_μ J^μ_{B-L} = 0 while ∇_μ J^μ_{B,L} ∝ W^a_{μν} W̃^{aμν} (Adler-Bell-Jackiw anomaly), preventing the boundary-term reduction problem; (ii) electroweak sphalerons violate B+L but conserve B−L, so any surviving asymmetry tracks B−L.

The general yield for the interaction ∇_μ f(φ_1, ..., φ_N) J^μ in the equilibrium regime T ≫ m, T ≫ μ is:

  n_b/s ≃ (15 ĝ c_STB c_s) / (4π² g*) · ∂_t f(φ_1, ..., φ_N) / (M*^d T) | at T_D

where ĝ = Σ_i g_i q_i² (ĝ = 13 in SM with three families, no ν_R; 16 with three right-handed neutrinos); c_s = 28/79 in SM (sphaleron conversion factor); g* = 106.75.

## §5 Structural result (the paper's central contribution)

**Two formal propositions establish an on-shell/background dictionary between curvature-based geometric GB operators and scalar-tensor counterparts via the Legendre relations x_i = V_{φ_i}.**

**Proposition 1 (GB → STB, paper §3.3.1):** Let a modified-gravity theory with action S = (1/2)∫d⁴x √(-g) F(x_1, ..., x_N) admit a scalar-tensor representation with x_i = χ_i following from auxiliary-field equations (det M ≠ 0), and assume the Legendre map is locally invertible so that V(φ_1, ..., φ_N) is well-defined. Then any geometric baryogenesis interaction of the form:

  ℒ_int^(geo) = (c_EFT / M*^d) ∇_μ G(x_1, ..., x_N) J^μ_{B-L}

admits the on-shell/background rewriting:

  ℒ_int^(geo) =[on-shell] (c_EFT / M*^d) ∇_μ G(V_{φ_1}, ..., V_{φ_N}) J^μ_{B-L}

i.e. it can be expressed in scalar-tensor language with f(φ_1, ..., φ_N) ≡ G(V_{φ_1}, ..., V_{φ_N}).

**Proposition 2 (STB → GB pull-back, paper §3.3.2):** Assume that in the regime of interest the inverse map φ_i = φ_i(x_1, ..., x_N) exists locally. Then the STB operator admits the local pull-back:

  ℒ_int^(STB) =[bg/on-shell] (c_STB / M*^d) ∇_μ G(x_1, ..., x_N) J^μ_{B-L}

with the equality understood locally in field space and evaluated along the spectator background.

**Three selection rules** restrict admissible operator space:
1. **Branch existence** — the scalar-tensor representation must exist (det M ≠ 0)
2. **Local invertibility of the Legendre map** — the map φ_i(x) must be locally invertible
3. **Validity of the spectator regime** — the interaction must induce negligible backreaction on the homogeneous cosmological background

The selection rules tie μ_{B-L} ∝ ḟ to the modified-gravity dynamics once F is specified. **Pereira's explicit framing (paper §3.3 prose):** STB is not "merely GB with a more complicated functional form"; the chain-rule rewriting is only available after restricting to the scalar-tensor branch, and the resulting geometric combination is not freely specifiable.

## §6 Application: F(R) = M_Pl^(2-2ε) R^(1+ε)

Power-law F(R) model with ε > 0 reducing to Einstein-Hilbert in the limit ε → 0. Scalar potential V(φ) = ε(1+ε)^(-(1+ε)/ε) M_Pl^(2-2/ε) φ^((1+ε)/ε).

B−L violation source: dimension-5 Weinberg operator (SM EFT).

  ℒ_W = -(λ_{αβ}/Λ) ℓ^i_{αL} ε^{ij} H_j C ℓ^k_{βL} ε^{kl} H_l + h.c.

This mediates ΔL = 2 scatterings LL ↔ HH with thermally-averaged rate Γ_W(T) = (3/(4π³)) · (m̄²_ν / v⁴_H) · T³ where m̄²_ν = Σ m²_{ν_i}.

Decoupling condition Γ_W(T_D) = H(T_D) gives:

  T_D = [ (2π³ v⁴_H (1+ε)) / (3 m̄²_ν) · (π² g* / (30 ρ_0))^(1/(2ε+2)) ]^((1+ε)/(1+3ε))

Background expansion exponent η = (1+ε)/2 from consistency between energy-density expressions.

**Spectator-approximation consistency check (paper §4 backreaction analysis):** δ_STB(T) ≲ (ĝ c²_STB / 9) · (φ(T)/M*²) · (T/M*)² · (T/T_D)^((1+3ε)/(1+ε)). For M* ≃ M_Pl, T_max ~ 10¹⁴ GeV, the spectator approximation holds throughout the baryogenesis epoch (δ_STB ≪ 1).

**Final compact yield expression (paper Eq. 84):**

  n_b/s ≃ -(ĝ c_STB c_s ε φ_0 π³ v⁴_H (1+ε)) / (6 M*² ρ_0 m̄²_ν)

**Numerical reproduction of observed BAU (paper §4 Fig. 1):** With M* = M_Pl, c_STB = -3, minimal normal-ordering neutrino mass m̄²_ν ≃ 2.6 × 10⁻³ eV² (Δm²_{21} + Δm²_{31}):

| ε | n_b/s | T_D (GeV) |
|---|---|---|
| 3.484770 × 10⁻⁶ | 8.2 × 10⁻¹¹ | 8.51023 × 10¹³ |
| 3.739751 × 10⁻⁶ | 8.8 × 10⁻¹¹ | 8.51029 × 10¹³ |
| 3.994731 × 10⁻⁶ | 9.4 × 10⁻¹¹ | 8.51034 × 10¹³ |

Background expansion exponent η at central value: 0.50000186 (vs GR radiation value 1/2). BBN bound ε ≲ 4 × 10⁻⁶ (Kusakabe et al. 2015) satisfied.

## §7 Honest-disclosure observations

**§7.1 Observational target adopted by Pereira 2026:** n_b/s = (8.8 ± 0.6) × 10⁻¹¹. This differs from the corpus F-05 verbatim (Davoudiasl 2004) of 9.2⁺⁰·⁶₋₀.₄ × 10⁻¹¹. The difference reflects approximately 22 years of CMB precision improvement, not a corpus correction.

**§7.2 Spectator-approximation consistency:** Pereira honestly discloses that the GB↔STB dictionary is only available "on the scalar-tensor branch (auxiliary-field solution χ_i = x_i and local invertibility of the map φ_i(x))" — "a local/background statement rather than an identity at the level of the action." The propositions provide a controlled, branch-dependent equivalence, not an off-shell identity.

**§7.3 Stability concerns flagged via reference [32]:** Pereira's bibliography cites Arbuzova, Dolgov, Dutta, Rangarajan 2023 *Symmetry* 15(2):404 ("Gravitational baryogenesis: problems and possible resolution"), arXiv:2301.08322. This is a critical honest-disclosure reference for the F-05 cluster: original Davoudiasl 2004 GB has known instability problems. STB claims to partially address these. NOT currently in corpus; flagged for v0.5 / v7 reference-list extension (and integrated there per Amendment 9 §3.H).

**§7.4 Einstein-frame caveat:** Pereira (paper §3.2) honestly discloses that the Einstein-frame rewriting "induces non-minimal couplings between the matter sector and the scalar field. Hence, the B−L (or B) interaction, the associated chemical-potential interpretation, and other intermediate quantities are modified in form and are not to be compared term-by-term with their Jordan-frame counterparts." This is a methodologically important caveat — frame-equivalence is at the level of final physical predictions, not intermediate quantities.

## §8 Corpus mapping

**Existing matrix entry engaged:** F-05 (gravitational baryogenesis), anchor Davoudiasl-Kitano-Kribs-Murayama-Steinhardt 2004 *PRL* 93:201301. Pereira 2026 is a 2026 sub-list addition under F-05 modified-gravity-extensions.

**Sub-list placement:** F-05 modified-gravity-extensions sub-list (Scaffold v6 line 301: "Lambiase-Scarpetta 2006 f(R); Fukushima-Mizuno-Maeda 2016 anisotropic; McDonald-Shore 2015-2017 quantum-loop; 2026 *JHEP* 02:029 F(R)-rainbow"). Pereira 2026 sits alongside these but provides a **structural organising result** (Propositions 1 and 2 + selection rules) rather than another single specific-model extension. In Scaffold v7 §5.2 the paper is treated as a methodological reference for the cluster, not just a citation in the existing line.

**Adjacent §7.3 framework engagement:** Pereira 2026's scalar-tensor representation framework underpins the broader Lobo/Lisbon group programme (Papers 3, 7 on Stephen's review list; antecedents Pereira-Lobo-Mimoso 2024 EMSG, Pereira-Lobo-Mimoso 2025 PLB). NOT engaged with the §7.3 gravity-mass-spatial-offset five-framework joint citation directly.

**NO new ESCALATE matrix entry created** per Amendment 9 §3.C corpus-discipline maintenance.

## §9 Open-item implications

**Item 5 (UMF G-shock baryon-asymmetry positioning vs F-02 + F-05 class):** SUBSTANTIVE. Pereira 2026 provides the reusable analytical framework (Propositions 1 + 2; selection rules) for evaluating whether candidate gravity-baryogenesis mechanisms — including UMF G-shock — admit scalar-tensor completion. UMF positioning under Item 5 will need to engage three sub-classes including STB. **Open question for UMF v0.7 / v2.3 technical development:** does UMF G-shock admit scalar-tensor representation per Propositions 1 + 2, or does it sit outside the scalar-tensor-completable class? Integrated into Scaffold v7 §11.3 Item 5.

**Item 1 / Postulate 2 (reverse baryogenesis at endpoint of bounded spacetime):** MINOR FLAG (modal-status preserved). STB-class derivative-coupling mechanisms (∇_μ f(φ_i) J^μ_{B-L}) are *forward* baryogenesis in the standard early-universe direction. Whether STB-class mechanisms support *reversal* under endpoint conditions (e.g., if ḟ or Ṙ changes sign at geometric collapse) is **NOT addressed in Pereira 2026** and would require UMF-specific technical development. This connection is "possible candidate territory" only, NOT a committed mechanism. Integrated into Scaffold v7 §11.3 Item 1 minor flag.

**Items 2, 3, 6, 7:** No direct relevance.

## §10 Modal-status preservation self-check (per framing-bias correction #4)

Self-check performed for this paper's integration:

- "Strengthens / enriches" F-05 cluster — ✓ used in Scaffold v7 + Amendment 9 + Research Plan v0.5
- "Validates UMF" — ✗ explicitly avoided; cluster activity does not validate UMF
- "Provides UMF mechanism" — ✗ explicitly avoided; UMF positioning under Item 5 remains open
- "STB = reverse baryogenesis" — ✗ explicitly avoided; characterised as "possible candidate territory" only
- "STB supports Postulate 2" — ✗ explicitly avoided; the structural framework exists for any future UMF technical work, not as evidence for Postulate 2

Modal-status preservation **confirmed** at integration time and re-confirmed at this deeppass production time.

## §11 New cross-references identified from Pereira 2026 bibliography

The following references appear in Pereira's bibliography and were not previously in the UMF corpus. All flagged for v0.5 / v7 reference-list integration per Amendment 9 §3.H and integrated into Scaffold v7 §13.2 §5:

1. Pereira, Lobo, Mimoso 2024 EMSG baryogenesis, arXiv:2409.04623 (direct cluster antecedent)
2. Pereira, Lobo, Mimoso 2025, *Phys. Lett. B* 866:139521, arXiv:2504.21504 (direct cluster antecedent)
3. Odintsov, Oikonomou 2016 Gauss-Bonnet GB, *Phys. Lett. B* 760:259-262, arXiv:1607.00545
4. Oikonomou, Saridakis 2016 f(T) GB, *Phys. Rev. D* 94:124005, arXiv:1607.08561
5. Odintsov, Oikonomou 2016 LQC GB, *EPL* 116(4):49001, arXiv:1610.02533
6. Arbuzova, Dolgov, Dutta, Rangarajan 2023 *Symmetry* 15(2):404, arXiv:2301.08322 — **critical honest-disclosure reference**
7. De Felice, Nasri, Trodden 2003 quintessential baryogenesis, *Phys. Rev. D* 67:043509 — STB Einstein-frame reduces to this form
8. Pereira, Ferraz, Lobo, Mimoso 2024 thermodynamics of primordial universe, *Entropy* 26(11):947, arXiv:2411.03018

## §12 What I can verify from this paper

- Bibliographic provenance and submission timeline (front matter)
- Mathematical structure of Propositions 1 and 2 (paper §3.3 prose + equations 39–48)
- Mathematical structure of selection rules (paper §3.3 prose)
- Mechanism formulation (Eq. 20, 24, 28, 29)
- Einstein-frame reduction structure (Eq. 33–35)
- Application to F(R) = R^(1+ε) structure (Eq. 51–84)
- Internal consistency of equations (e.g., Eq. 84 reduces correctly to standard GB in ε → 0 limit; spectator-approximation expressions reduce to GR radiation at ε → 0)
- Cross-references to bibliography
- Author's stated honest-disclosure observations (frame-equivalence caveat; selection-rule branch-dependence; stability-issue acknowledgement via ref [32])

## §13 What I cannot verify from this paper alone

- Numerical claims in Table-like Fig. 1 caption (T_D ≈ 8.5 × 10¹³ GeV for ε ≈ 3.7 × 10⁻⁶) — I have not re-derived them from the equations
- BBN bound ε ≲ 4 × 10⁻⁶ — cited from Kusakabe et al. 2015 [66]; I would need that paper's body to verify
- Backreaction estimates δ_STB ≪ 1 throughout baryogenesis epoch — derived from Eq. 81 with stated parameter values; not independently re-derived
- The empirical observational target (8.8 ± 0.6) × 10⁻¹¹ — cited from refs [3-5] in Pereira; not independently verified
- Whether the spectator approximation remains valid beyond the stated parameter ranges (non-spectator regime corrections explicitly left to future work by author)

## §14 Recommended corpus treatment (now integrated)

- **Scaffold v7 §5.2:** F-05 modified-gravity-extensions sub-list expanded with Pereira 2026 as structural organising reference (cluster paragraph). Integrated. ✓
- **Scaffold v7 §11.3 Item 5:** substantively updated with cluster content including Pereira 2026 propositions and selection rules as analytical framework. Integrated. ✓
- **Scaffold v7 §11.3 Item 1:** minor flag added for possible STB-reverse-baryogenesis candidate-territory connection (modal-status preserved). Integrated. ✓
- **Scaffold v7 §13.2 §5:** reference entry added with full attribution; antecedents and adjacent references added. Integrated. ✓
- **Research Plan v0.5 §3:** F-05 cluster sub-list update paragraph for Pereira 2026 with body-access summary. Integrated. ✓
- **Research Plan v0.5 §5.1:** Item 5 substantive update text. Integrated. ✓
- **Amendment 9 §3.D:** body-access summary. Integrated. ✓
- **Amendment 9 §3.E:** F-05 cluster updates summary. Integrated. ✓

## §15 End of Paper 2 deeppass

Deeppass report for Pereira 2026 *Phys. Lett. B* 875:140312 complete. Provenance verified. Findings integrated into corpus deliverables per Amendment 9 cycle. Modal-status preservation confirmed.

---

*End of F-05_Paper2_Pereira2026_PostJan2026_deeppass.md*
