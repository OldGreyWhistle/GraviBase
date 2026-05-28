# UMF Trial S3M0S1 — Index 3: Metric Units v2

**Document version:** v2 (supersedes v1; deep-review hyperlinks added; CD-OP-040 filename updates)
**Date:** 28 May 2026 (AEST)
**Working language:** Australian English (per standing rule v0.35)
**Page format target:** A4
**Trial:** UMF Trial S3M0S1
**Author of trial:** Stephen L Browne
**Drafter:** Claude Opus 4.7 Adaptive (Anthropic)
**Audit-trail anchor:** VC v0.35 Amendment 13 (filename alignment cycle + CD-OP-040 convention registration)
**Predecessor:** UMF_Trial_S3M0S1_Index3_MetricUnits_v1.md (retained unchanged per CD-OP-004)

**Status:** Second populated instance of Index 3. Supersedes v1 with: (i) Source provenance lines updated to CD-OP-040-compliant filenames; deeppass references now markdown hyperlinks; (ii) deep-review hyperlinks added in-entry for key metric units (cluster-comparability scalars, Λ Sorkin pre-discovery prediction, paper-specific parameters); (iii) §4 cross-reference manifest expanded with full 31-file enumeration table; (iv) §5 version history extended; (v) §6 honest-disclosure caveats updated. v1 retained as predecessor per CD-OP-004 audit-trail integrity. Companion to Index 1 v2 + Index 2 v2. Comprehensive hyperlinking applied per Stephen direction 28 May 2026 AEST ("comprehensive — circular navigation is very valuable to a human").

**Schema reference:** Indexes Design Spec v3 §5.

---

## §1 Purpose

Inventory of typed measurable / parameterised quantities used across UMF Trial S3M0S1. Per Stephen direction 27 May AEST, "metric unit" framing means a typed quantity (scalar / vector / tensor) characterised by value-domain (simple-scalar / set-based / discrete / function-form / tensor-field). Each entry: quantity → mathematical type → value-domain → physical dimension → definition (Index 1) → values across corpus → comparability + naturalness/tuning status.

Cross-references implemented per Spec v3 §7; external corpus links per §7.8.

---

## §2 Counts and breakdown at v1 close

| Group | Count | IDs |
|---|---|---|
| Cluster-comparability scalars | 3 | MU-001 to MU-003 |
| Geometric / tensorial quantities | 10 | MU-004 to MU-013 |
| Gravity-modifying functions | 1 | MU-014 |
| Fundamental constants (UMF A4 territory) | 8 | MU-015 to MU-022 |
| Paper-specific parameters | 2 | MU-023, MU-024 |
| Constraint scales | 3 | MU-025 to MU-027 |
| Set-based F-02 parameters (Liu-Qin-Bian) | 4 | MU-028 to MU-031 |
| HL constraint parameter | 1 | MU-032 |
| **Total** | **32** | |

Type breakdown:

| Type | Count |
|---|---|
| Scalar | 22 |
| Vector | 2 |
| Rank-2 tensor | 4 |
| Higher-rank tensor | 1 |
| Function | 1 |
| Operator | 0 |
| Hybrid (scalar / set-based) | 4 |

---

## §3 Metric unit entries

### MU-001

**Quantity name:** Baryon-to-entropy ratio
**Symbol:** η_B/s (also n_B/s, η_B, η)
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** Dimensionless
**Definition pointer:** [CD-TH-016](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-016) — gravitational baryogenesis
**Values across corpus:**

| Paper / source | Value | Error |
|---|---|---|
| Davoudiasl 2004 (corpus verbatim) | 9.2 × 10⁻¹¹ | +0.6 / −0.4 |
| Pereira 2026 | 8.8 × 10⁻¹¹ | ± 0.6 |
| Whittingham 2026 CMB | 8.65 × 10⁻¹¹ | ± 0.09 |
| Whittingham 2026 BBN range | (8.2–9.4) × 10⁻¹¹ | range |
| Samaddar-Singh 2025 | 9.42 × 10⁻¹¹ | (not explicitly stated) |
| Liu-Qin-Bian 2026 | 8.8 × 10⁻¹¹ | (target value) |
| CPV-operator-alone (Liu-Qin-Bian) | 1.8 × 10⁻¹⁴ | (~7 OoM below observed, EDM-constrained) |

**Comparability notes:** Directly comparable across cluster as dimensionless scalar. Cross-cluster observational-target evolution: corpus retains Davoudiasl 2004 9.2 verbatim per audit-trail integrity; current Planck-era values 8.6–8.8 × 10⁻¹¹. Samaddar-Singh choice 9.42 is highest in cluster; within Davoudiasl 9.2 + 0.6 = 9.8 upper bound; above Pereira 8.8 + 0.6 = 9.4 upper bound.
**Naturalness / tuning status:** Observational target; mechanisms vary in how naturally they hit this target. Whittingham f(R) GB with M* = M_Pl undershoots by factor 5–8; Pereira STB requires ε ≈ O(10⁻⁶) at M* = M_Pl; Samaddar-Singh f(T, T_G) reaches at M* ≈ 10⁻⁷ M_Pl with parameter coefficients 10²⁰–10¹¹⁰.
**Source provenance:** Davoudiasl 2004 *PRL* 93:201301; Scaffold §5.2; honest-disclosure correction #3
**First introduced:** Pre-trial; observational-target evolution flagged v7
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [CR-0045](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-0045), [CR-0046](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-0046), [CD-TH-016](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-016), [CD-OP-012](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-012), [CD-OP-Item-005](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-item-005). Deep-review files (F-05 cluster + F-02 Liu, in `./deep-review-reports/`): [F-05 Pereira 2026](./deep-review-reports/F-05_Pereira2026_PostJan2026_deeppass.md) (8.8 × 10⁻¹¹ target); [F-05 Whittingham 2026](./deep-review-reports/F-05_Whittingham2026_PostJan2026_deeppass.md) (CMB 8.65 × 10⁻¹¹; honest-disclosure correction #4 documenting M*=M_Pl undershoot); [F-05 Samaddar 2025](./deep-review-reports/F-05_Samaddar2025_AdjacencyReview2026_deeppass.md) (9.42 × 10⁻¹¹ choice with M*≈10⁻⁷ M_Pl) + [Addendum](./deep-review-reports/F-05_Samaddar2025_AdjacencyReview2026_deeppass_Addendum.md); [F-02 Liu-Qin-Bian 2026](./deep-review-reports/F-02_Liu2026_PostJan2026_deeppass.md) (CPV-operator-alone 1.8 × 10⁻¹⁴ EDM-constrained rule-out; CME amplification essential).

### MU-002

**Quantity name:** Gravitational baryogenesis cutoff scale
**Symbol:** M*
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** GeV
**Definition pointer:** [CD-TH-016](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-016) (operationally embedded in GB mechanism); [CD-TH-013](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-013) (Planck scale reference)
**Values across corpus:**

| Paper / source | Value | Ratio to M_Pl |
|---|---|---|
| Davoudiasl 2004 (natural choice) | ≈ 1.22 × 10¹⁹ GeV | M_Pl |
| Pereira 2026 STB | ≈ 1.22 × 10¹⁹ GeV | M_Pl (with ε ≈ O(10⁻⁶) tuning) |
| Whittingham 2026 standard with M* = M_Pl | M_Pl | undershoots η_obs by factor 5–8 |
| Whittingham 2026 resolution | ≈ 4.9 × 10¹⁸ GeV | ≈ 0.4 M_Pl (for agreement) |
| Samaddar-Singh 2025 | 2 × 10¹² GeV | ≈ 10⁻⁷ M_Pl |

**Comparability notes:** Directly comparable across cluster as scalar in GeV. Cross-cluster spread approximately 7 orders of magnitude (M_Pl per Pereira; ~0.4 M_Pl per Whittingham resolution; ~10⁻⁷ M_Pl per Samaddar-Singh). F-05 cluster does NOT converge on uniform M* choice.
**Naturalness / tuning status:** **Central naturalness question** for Item 5. Davoudiasl natural choice M_Pl; Pereira retains M_Pl with ε-tuning; Whittingham resolution requires factor-2.4 reduction; Samaddar-Singh substantially reduced. Cluster as a whole is NOT M_Pl-naturalness-uniform.
**Source provenance:** Davoudiasl 2004; Scaffold §5.2 [v7+v8 additions]; §11.3 Item 5; Amendment 10 §3.E
**First introduced:** Pre-trial; cross-cluster spread documented v7; extended v8
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [CR-0042](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-0042), [CR-0043](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-0043), [CR-0044](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-0044), [CD-TH-013](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-013), [CD-TH-014](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-014), [CD-OP-Item-005](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-item-005). Deep-review files (F-05 cluster M* spread, in `./deep-review-reports/`): [F-05 Pereira 2026](./deep-review-reports/F-05_Pereira2026_PostJan2026_deeppass.md) (M_Pl with ε ≈ O(10⁻⁶)); [F-05 Whittingham 2026](./deep-review-reports/F-05_Whittingham2026_PostJan2026_deeppass.md) (M*=M_Pl undershoots; resolution at ≈0.4 M_Pl); [F-05 Samaddar 2025](./deep-review-reports/F-05_Samaddar2025_AdjacencyReview2026_deeppass.md) (M* ≈ 10⁻⁷ M_Pl with parameter coefficients 10²⁰–10¹¹⁰ across formalisms; honest-disclosure correction #5 quality-concerns context per [Addendum](./deep-review-reports/F-05_Samaddar2025_AdjacencyReview2026_deeppass_Addendum.md)).

### MU-003

**Quantity name:** Decoupling temperature
**Symbol:** T_D
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** GeV
**Definition pointer:** [CD-TH-012](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-012) — GUT scale (conventional choice)
**Values across corpus:**

| Paper / source | Value |
|---|---|
| Davoudiasl 2004 | ~ 10¹⁶ GeV (GUT scale, conventional) |
| Pereira 2026 STB | ≈ 8.5 × 10¹³ GeV (below GUT scale) |
| Samaddar-Singh 2025 | 2 × 10¹⁶ GeV (GUT scale) |
| Whittingham 2026 | (GUT-scale, model-dependent) |

**Comparability notes:** Directly comparable across cluster. Pereira's 8.5 × 10¹³ GeV is the outlier — below conventional GUT scale by ~2.5 orders of magnitude.
**Naturalness / tuning status:** GUT scale is conventional, motivated by parallel with grand-unification expectations. Pereira choice below GUT scale corresponds to the ε ≈ O(10⁻⁶) tuning regime.
**Source provenance:** Scaffold §5.2; §11.3 Item 5
**First introduced:** Pre-trial; cross-cluster values documented v7
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [CR-0047](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-0047), [CR-0048](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-0048), [CD-TH-012](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-012)

### MU-004

**Quantity name:** Spacetime metric tensor
**Symbol:** g_μν
**Type:** Rank-2 symmetric tensor
**Value-domain:** Tensor-field
**Physical dimension:** Dimensionless components (signature convention dependent)
**Definition pointer:** [CD-TH-004](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-004) — FRW background (most common context); standard GR
**Values across corpus:** Tensor-field over the manifold; background-dependent. FRW form prevalent across F-05 cluster: ds² = -dt² + a²(t)[dr²/(1-kr²) + r² dΩ²]. Samaddar-Singh uses power-law a(t) = a_0 t^m with m > 1.
**Comparability notes:** All cluster members assume metric-signature conventions; (−, +, +, +) standard. Frame choice (Einstein vs Jordan vs scalar-tensor) affects which g_μν is the "physical" metric.
**Naturalness / tuning status:** N/A (fundamental geometric object)
**Source provenance:** Standard GR; Scaffold §3, §5, §7
**First introduced:** Pre-trial
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [CD-TH-005](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-005), [CD-TH-006](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-006), [CD-TH-008](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-008)

### MU-005

**Quantity name:** Ricci scalar
**Symbol:** R
**Type:** Scalar
**Value-domain:** Simple-scalar (per event) / Function-form (cosmological)
**Physical dimension:** GeV² (natural units)
**Definition pointer:** [CD-TH-010](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-010) — curvature-based gravity
**Values across corpus:** FRW form dependent on a(t). Radiation-dominated GR Ṙ = 0 (Davoudiasl 2004 GB inflation-regime-lock). Modified gravity allows Ṙ ≠ 0 even in radiation-dominated regime.
**Comparability notes:** Standard across curvature-based F-05 branch. Distinct from teleparallel branch which uses T (torsion scalar).
**Naturalness / tuning status:** Determined by background and matter content per Einstein/modified-gravity field equations.
**Source provenance:** Standard GR; Scaffold §5.2
**First introduced:** Pre-trial
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [CD-TH-010](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-010), [CD-TH-002](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-002), [CD-TH-003](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-003)

### MU-006

**Quantity name:** Ricci tensor
**Symbol:** R_μν
**Type:** Rank-2 tensor
**Value-domain:** Tensor-field
**Physical dimension:** GeV²
**Definition pointer:** [CD-TH-010](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-010); standard GR
**Values across corpus:** Tensor-field. Central to B-01 Misner-Wheeler Rainich already-unified construction (EM field tensor F_μν derived from R_μν via Rainich algebraic conditions).
**Comparability notes:** Standard across curvature-based gravity formulations.
**Naturalness / tuning status:** N/A (geometric object)
**Source provenance:** Standard GR; Scaffold §4.3 (Rainich); Misner-Wheeler 1957
**First introduced:** Pre-trial
**Status:** Active
**Cross-program portability:** Generic

### MU-007

**Quantity name:** Einstein tensor
**Symbol:** G_μν
**Type:** Rank-2 tensor
**Value-domain:** Tensor-field
**Physical dimension:** GeV²
**Definition pointer:** Standard GR; G_μν = R_μν - (1/2) g_μν R
**Values across corpus:** Tensor-field. Central to Malakar Paper 2 (Malakar-Mazumdar-Bhuyan 2026 arXiv:2605.14377) f(R, G_μν T^μν) gravity — EMSG-adjacent class via Einstein-tensor-stress-energy contraction.
**Comparability notes:** Standard across GR + modified-gravity formulations.
**Naturalness / tuning status:** N/A
**Source provenance:** Standard GR; Scaffold §5.2 [v8 addition] (Malakar Paper 2)
**First introduced:** Pre-trial; specific deployment v8 (Malakar Paper 2)
**Status:** Active
**Cross-program portability:** Generic

### MU-008

**Quantity name:** Riemann tensor
**Symbol:** R^μ_{νρσ}
**Type:** Higher-rank tensor (rank-4)
**Value-domain:** Tensor-field
**Physical dimension:** GeV²
**Definition pointer:** Standard GR
**Values across corpus:** Tensor-field. Not directly deployed as cluster-comparison object but underlies all curvature-based formulations.
**Comparability notes:** Standard.
**Naturalness / tuning status:** N/A
**Source provenance:** Standard GR
**First introduced:** Pre-trial
**Status:** Active
**Cross-program portability:** Generic

### MU-009

**Quantity name:** Teleparallel torsion scalar
**Symbol:** T
**Type:** Scalar
**Value-domain:** Simple-scalar (per event) / Function-form (cosmological)
**Physical dimension:** GeV² (natural units)
**Definition pointer:** [CD-TH-009](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-009) — teleparallel gravity
**Values across corpus:** FRW form dependent on a(t). Samaddar-Singh 2025 deploys T in f(T, T_G) extension. Cruz-Pereira-Lobo 2025/2026 deploys in f(T, L_m).
**Comparability notes:** Teleparallel-branch alternative to curvature-based R. Equivalent to GR at the level of TEGR (Maluf 2013) but distinct extensions f(T) vs f(R).
**Naturalness / tuning status:** N/A (geometric object)
**Source provenance:** Maluf 2013; Scaffold §5.2 [v8 addition]; [F-05 Samaddar 2025](./deep-review-reports/F-05_Samaddar2025_AdjacencyReview2026_deeppass.md)
**First introduced:** v8 (Amendment 10); earlier reference via Cruz-Pereira-Lobo v7
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [CD-TH-009](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-009)

### MU-010

**Quantity name:** Teleparallel Gauss-Bonnet topological invariant
**Symbol:** T_G
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** GeV⁴ (natural units)
**Definition pointer:** Kofinas-Saridakis 2014 foundational; via [CD-TH-009](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-009)
**Values across corpus:** Samaddar-Singh 2025 deploys in two models: f(T, T_G) = αT + β√T_G and f(T, T_G) = −T + δ T_G log(T_G).
**Comparability notes:** Teleparallel-specific quantity; analogue of Gauss-Bonnet topological invariant in curvature-based gravity (which is total derivative in 4D). f(T, T_G) extension enables non-trivial dynamics.
**Naturalness / tuning status:** N/A as quantity; specific coefficient choices (β, δ in Samaddar-Singh) span 10²⁰–10¹¹⁰ across models (extreme tuning).
**Source provenance:** Kofinas-Saridakis 2014 *Phys. Rev. D* 90:084044; Scaffold §5.2 [v8 addition]; [F-05 Samaddar 2025](./deep-review-reports/F-05_Samaddar2025_AdjacencyReview2026_deeppass.md)
**First introduced:** v8 (Amendment 10)
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [CD-TH-009](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-009), [CR-0001](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-0001)

### MU-011

**Quantity name:** Stress-energy tensor
**Symbol:** T^μν
**Type:** Rank-2 tensor
**Value-domain:** Tensor-field
**Physical dimension:** GeV⁴
**Definition pointer:** Standard GR
**Values across corpus:** Tensor-field. Central to f(R, G_μν T^μν) gravity (Malakar Paper 2) and f(R, L_m, T) gravity (Malakar Paper 4 of original review list).
**Comparability notes:** Standard.
**Naturalness / tuning status:** N/A
**Source provenance:** Standard GR; Scaffold §5.2
**First introduced:** Pre-trial; specific deployment in EMSG-adjacent class v8
**Status:** Active
**Cross-program portability:** Generic

### MU-012

**Quantity name:** B-L current 4-vector
**Symbol:** J^μ_{B-L}
**Type:** Vector (4-vector)
**Value-domain:** Tensor-field-like
**Physical dimension:** GeV³ (in natural units; current density)
**Definition pointer:** Standard particle physics; GB mechanism via [CD-TH-016](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-016)
**Values across corpus:** Central to Davoudiasl 2004 GB operator (1/M*²) ∂_μ R · J^μ_{B-L}. Pereira 2026 STB extends to ∇_μ f(φ_i) J^μ_{B-L} with derivative coupling.
**Comparability notes:** Standard across F-05 cluster.
**Naturalness / tuning status:** N/A (current 4-vector)
**Source provenance:** Davoudiasl 2004; Scaffold §5.2 [v7 addition Pereira]; [F-05 Pereira 2026](./deep-review-reports/F-05_Pereira2026_PostJan2026_deeppass.md)
**First introduced:** Pre-trial; STB extension v7
**Status:** Active
**Cross-program portability:** Generic

### MU-013

**Quantity name:** Ricci scalar 4-gradient
**Symbol:** ∂_μ R
**Type:** Vector (4-vector)
**Value-domain:** Tensor-field-like
**Physical dimension:** GeV³
**Definition pointer:** Standard differential geometry
**Values across corpus:** Central to GB operator. Vanishes in radiation-dominated GR (Ṙ = 0); non-zero in modified gravity and matter-dominated epoch (Malakar Paper 1 examines matter-dominated GB).
**Comparability notes:** Standard across curvature-based GB cluster.
**Naturalness / tuning status:** N/A
**Source provenance:** Davoudiasl 2004; Scaffold §5.2
**First introduced:** Pre-trial
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [CD-TH-002](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-002), [CD-TH-003](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-003)

### MU-014

**Quantity name:** Gravity-modifying functions
**Symbol:** f(R), f(T, T_G), f(R, L_m, T), f(R, G_μν T^μν)
**Type:** Function
**Value-domain:** Function-form
**Physical dimension:** GeV² (typically; depends on functional choice)
**Definition pointer:** [CD-TH-009](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-009), [CD-TH-010](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-010)
**Values across corpus:** Specific functional choices across F-05 cluster:

| Paper | Function form |
|---|---|
| Starobinsky | f(R) = R + αR² |
| Pereira 2026 STB | F(R) = R^(1+ε) with ε ≈ O(10⁻⁶) |
| Whittingham 2026 | f(R) = Starobinsky and Odintsov-Oikonomou 2025 power-law |
| Malakar Paper 1 (Nojiri-Odintsov class) | (i) f(R) = −α/R^m + R/(2k²) + βR²; (ii) f(R) = αR^γ + βR^δ; (iii) f(R) = (αR^(2m) − βR^m)/(1 + γR^m) |
| Malakar Paper 2 (EMSG-adjacent) | f(R, G_μν T^μν) |
| Malakar Paper 4 | f(R, L_m, T) |
| Cruz-Pereira-Lobo 2025/2026 | f(T, L_m) |
| Samaddar-Singh 2025 Model 1 | f(T, T_G) = αT + β√T_G |
| Samaddar-Singh 2025 Model 2 | f(T, T_G) = −T + δ T_G log(T_G) |
| Goodarzi 2026 | F(R) gravity's rainbow |
| Marciu 2026 | EMSG scalar-tensor representation |
| Lambiase-Scarpetta 2006 | f(R) extension |

**Comparability notes:** Each functional choice is a discrete model selection. Function-form is the unit of choice; comparability is via the model class (curvature-based vs teleparallel vs EMSG-adjacent) and via parameter choices within the form.
**Naturalness / tuning status:** Each form involves model-selection plus parameter-tuning. The cluster does NOT converge on a single uncontested functional form. Selection-rule constraints (Pereira 2026 three rules: branch existence, local invertibility, spectator validity) restrict admissible operator space.
**Source provenance:** Scaffold §5.2 [v7+v8 additions]; deeppass reports
**First introduced:** Pre-trial; cluster substantively extended v7+v8
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [CD-TH-009](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-009), [CD-TH-010](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-010), [CR-0014](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-0014), [CD-OP-Item-005](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-item-005)

### MU-015

**Quantity name:** Planck mass
**Symbol:** M_Pl
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** GeV
**Definition pointer:** [CD-TH-013](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-013) — Planck scale
**Values across corpus:** M_Pl = (ℏc/G)^(1/2) ≈ 1.22 × 10¹⁹ GeV (standard). Reference scale for M* naturalness (MU-002).
**Comparability notes:** Standard fundamental scale. Under UMF v0.7 §3.1 assumption 4 with G variable via ADD V_n-dependent mechanism, M_Pl is itself regime-relative ("Planck values themselves variable" per Scaffold §5.3 Trans-Planckian dissolution path 1).
**Naturalness / tuning status:** Reference scale for naturalness arguments.
**Source provenance:** Standard physics; Scaffold §5.3
**First introduced:** Pre-trial
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [CD-TH-013](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-013), [CD-TH-014](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-014), [MU-002](#mu-002)

### MU-016

**Quantity name:** Fine-structure constant
**Symbol:** α
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** Dimensionless
**Definition pointer:** Standard physics; UMF v0.7 §3.1 assumption 4 territory
**Values across corpus:** α ≈ 1/137.036 (standard). Under UMF v0.7 §3.1 assumption 4, variable under variant geometry. α = e²/4πε₀ℏc relates α to ε₀ and ℏ (CD-OP-Item-001 mechanism question).
**Comparability notes:** Standard.
**Naturalness / tuning status:** **Conditional under UMF assumption 4** — variable per Stephen 26 May AEST position (CD-OP-Item-001).
**Source provenance:** Standard physics; Scaffold §4; Item 1 substantive position
**First introduced:** Pre-trial; UMF-conditional position 26 May 2026
**Status:** Active
**Cross-program portability:** Generic (constant); UMF-specific (conditional variability position)
**Cross-references:** [CD-OP-Item-001](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-item-001), [CD-OP-Adj-003](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-adj-003), [CD-OP-Adj-017](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-adj-017)

### MU-017

**Quantity name:** Vacuum permittivity
**Symbol:** ε₀
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** F/m (or natural units)
**Definition pointer:** Standard physics; UMF v0.7 §3.1 assumption 4 territory
**Values across corpus:** ε₀ ≈ 8.854 × 10⁻¹² F/m (standard). Under UMF v0.7 §3.1 assumption 4, variable per Stephen Q3 (CD-OP-Adj-003) and Item 1 (CD-OP-Item-001). Joint B-01 Rainich + B-03 ADD mainstream-precedent backing per Scaffold §4.3.
**Comparability notes:** Standard.
**Naturalness / tuning status:** **Conditional under UMF assumption 4** — variable.
**Source provenance:** Standard physics; Scaffold §4.3 Rainich-ADD joint defence
**First introduced:** Pre-trial; UMF-conditional Q3 25 May 2026; Item 1 position 26 May 2026
**Status:** Active
**Cross-program portability:** Generic (constant); UMF-specific (conditional variability)
**Cross-references:** [CD-OP-Adj-003](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-adj-003), [CD-OP-Item-001](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-item-001), [CR-JC-0004](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-jc-0004)

### MU-018

**Quantity name:** Vacuum permeability
**Symbol:** μ₀
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** H/m
**Definition pointer:** Standard physics; UMF v0.7 §3.1 assumption 4 territory
**Values across corpus:** μ₀ ≈ 1.257 × 10⁻⁶ H/m (standard). Under UMF v0.7 §3.1 assumption 4, variable jointly with ε₀ via B-01 Rainich + B-03 ADD precedent.
**Comparability notes:** Coupled to ε₀ via c² = 1/(μ₀ ε₀) and to α via standard relations.
**Naturalness / tuning status:** **Conditional under UMF assumption 4** — variable jointly with ε₀.
**Source provenance:** Standard physics; Scaffold §4.3
**First introduced:** Pre-trial; UMF-conditional Q3 25 May 2026
**Status:** Active
**Cross-program portability:** Generic (constant); UMF-specific (conditional variability)
**Cross-references:** [MU-017](#mu-017), [CD-OP-Adj-003](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-adj-003)

### MU-019

**Quantity name:** Speed of light
**Symbol:** c
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** m/s
**Definition pointer:** Standard physics; **UMF foundational commitment: INVARIANT under all conditions**
**Values across corpus:** c = 2.998 × 10⁸ m/s (standard, exact). **UMF foundational commitment per Stream 3 methodology and Handoff v6 §5: c invariance under all conditions.** Variable speed of light is **disclaimed** modal-status per CD-OP-025.
**Comparability notes:** Held invariant in UMF; contrast with F-09 Hořava-Lifshitz UV violation. F-07 CST preserves Lorentz invariance and is the precedent UMF aligns with on c-invariance per Scaffold §4.1.
**Naturalness / tuning status:** **Disclaimed as variable** per Stream 3 methodology (CD-OP-025 disclaimed modal status).
**Source provenance:** Standard physics; Stream 3 methodology; Handoff v6 §5; Scaffold §4.1
**First introduced:** Pre-trial; standing rule
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [CD-OP-001](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-001), [CD-OP-025](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-025)

### MU-020

**Quantity name:** Reduced Planck constant
**Symbol:** ℏ
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** J·s (or eV·s; natural units)
**Definition pointer:** Standard physics; UMF v0.7 §3.1 assumption 4 territory (separate treatment)
**Values across corpus:** ℏ ≈ 1.055 × 10⁻³⁴ J·s (standard). Under UMF v0.7 §3.1 assumption 4 working position, variable. Excluded from GWM core formalism (Scaffold §5.4 two-face structure: Face 1 elementary-particle regime no mainstream support for ℏ-free particle physics; Face 2 gravity-only-matter regime substantially supported by four classical ℏ-free precedents).
**Comparability notes:** Coupled to α via standard relations. ℏ-exclusion in GWM honest-disclosed per Scaffold §5.4.
**Naturalness / tuning status:** Variable per UMF working position; ℏ-exclusion in GWM core formalism honest-disclosed.
**Source provenance:** Standard physics; Scaffold §4.1, §5.4
**First introduced:** Pre-trial
**Status:** Active
**Cross-program portability:** Generic (constant); UMF-specific (working position + GWM ℏ-exclusion)
**Cross-references:** [CR-JC-0008](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-jc-0008)

### MU-021

**Quantity name:** Newton's gravitational constant
**Symbol:** G
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** m³/(kg·s²)
**Definition pointer:** Standard physics; UMF v0.7 §3.1 assumption 4 territory (central commitment)
**Values across corpus:** G ≈ 6.674 × 10⁻¹¹ m³/(kg·s²) (standard). **UMF central commitment: G variable under variant geometry per ADD V_n-dependent mechanism (G₄ = G_(4+n)/V_n).** Mainstream-precedent: B-03 ADD 1998. 27+ years cumulative literature; 2024 *MNRAS* 536:816 compact-star empirical engagement; LHC null results constraining parameter space; Eot-Wash + Stanford torsion balance sub-mm gravity tests.
**Comparability notes:** Standard. UMF treats as variable.
**Naturalness / tuning status:** **Variable under variant geometry** — UMF central commitment per assumption 4.
**Source provenance:** Standard physics; Scaffold §4.1, §4.2
**First introduced:** Pre-trial; UMF central commitment
**Status:** Active
**Cross-program portability:** Generic (constant); UMF-specific (central variability commitment)
**Cross-references:** [CR-0009](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-0009), [CR-JC-0004](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-jc-0004)

### MU-022

**Quantity name:** Strong-nuclear coupling
**Symbol:** α_s
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** Dimensionless
**Definition pointer:** Standard particle physics; UMF Item 1 / Q3 context territory
**Values across corpus:** α_s = g_s²/4π (running with energy scale; ≈ 0.118 at M_Z). Per Stephen Q3 25 May AEST: under ADD-style dimensional reduction with effective compactification volume V_n, α_s reduces under same V_n-dependent mechanism as G (just as significant as ε₀/μ₀ variation per Stephen Q3 direction). Item 1 sub-question (v) on whether bounded-spacetime endpoint mechanism drives α_s variation remains open.
**Comparability notes:** Running coupling; energy-scale dependent in standard QCD.
**Naturalness / tuning status:** **Conditional under UMF assumption 4** — variable in correlated fashion with G; specific UMF technical development required.
**Source provenance:** Scaffold §4.3 Stephen Q3 strong-nuclear-force discussion
**First introduced:** Pre-trial; UMF-conditional Q3 25 May 2026
**Status:** Active
**Cross-program portability:** Generic (constant); UMF-specific (conditional variability + open Item 1 sub-question)
**Cross-references:** [CD-OP-Adj-003](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-adj-003), [CD-OP-Item-001](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-item-001)

### MU-023

**Quantity name:** Pereira STB tuning parameter
**Symbol:** ε (in F(R) = R^(1+ε))
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** Dimensionless
**Definition pointer:** Pereira 2026 STB construction; via [CD-TH-007](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-th-007) scalar-tensor frame
**Values across corpus:** ε ≈ O(10⁻⁶) per Pereira 2026 §4 application. At ε = 0, recovers GR; F(R) = R^(1+ε) parameterises deviation from GR.
**Comparability notes:** Paper-specific tuning parameter. Pereira's Starobinsky-limit self-consistency check (ε → 0) recovers GR baseline.
**Naturalness / tuning status:** **Tuning parameter** — set at O(10⁻⁶) to reproduce observed η_obs with M* = M_Pl and T_D ≈ 8.5 × 10¹³ GeV.
**Source provenance:** Pereira 2026 *Phys. Lett. B* 875:140312; Scaffold §11.3 Item 5; [F-05 Pereira 2026](./deep-review-reports/F-05_Pereira2026_PostJan2026_deeppass.md)
**First introduced:** v7 (Amendment 9)
**Status:** Active
**Cross-program portability:** UMF-specific (relevant only to Pereira-class STB framework)
**Cross-references:** [CD-OP-Item-005](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-item-005)

### MU-024

**Quantity name:** Samaddar-Singh power-law exponent
**Symbol:** m (in a(t) = a_0 t^m)
**Type:** Scalar
**Value-domain:** Simple-scalar (with internal text-Table-2 inconsistency)
**Physical dimension:** Dimensionless
**Definition pointer:** Samaddar-Singh 2025 power-law expansion as inflation surrogate
**Values across corpus:** m > 1 for inflation-surrogate behaviour. Specific values:

| Model | Text-stated | Table 2 displayed |
|---|---|---|
| Model 1 generalised | 1.2996 / 1.3117 / 1.3235 (page 9) | 1.9053 / 1.8728 / 1.8413 (Table 2 — identical to Model 1 standard Table 1) |

**Comparability notes:** **Internal text-Table-2 inconsistency identified as honest-disclosure observation** (Samaddar-Singh deeppass §7.4). Unverifiable in this populator's thread context (Paper 3 PDF not loaded in current thread); claim sits at deeppass-report level. m > 1 as inflation surrogate without inflaton field is dynamically less rigorous than Einstein-frame scalaron treatment (Whittingham 2026).
**Naturalness / tuning status:** **Tuning parameter** with paper-internal inconsistency on Model 1 generalised values.
**Source provenance:** Samaddar-Singh 2025 arXiv:2512.06009v1; [F-05 Samaddar 2025](./deep-review-reports/F-05_Samaddar2025_AdjacencyReview2026_deeppass.md) §7.4, §7.7
**First introduced:** v8 (Amendment 10)
**Status:** Active; **Internal text-Table-2 inconsistency unverifiable in this thread; deeppass-report level claim**
**Cross-program portability:** UMF-specific (relevant only to Samaddar-Singh-class framework)
**Cross-references:** [CD-OP-020](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-020)

### MU-025

**Quantity name:** CPV cutoff scale (Liu-Qin-Bian)
**Symbol:** Λ_CPV
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** TeV
**Definition pointer:** Liu-Qin-Bian 2026 dimension-6 CPV operator scale
**Values across corpus:** Λ_CPV ≳ 338 TeV per Roussy 2023 electron EDM constraint. At this scale, η_B ≃ 1.8 × 10⁻¹⁴ — about 7 orders of magnitude below observed 8.8 × 10⁻¹¹ baryon-asymmetry. **CPV-operator-alone sub-mechanism therefore ruled out by current EDM bounds as a sufficient explanation.** CME amplification essential per Liu-Qin-Bian for reaching observed BAU.
**Comparability notes:** F-02 cluster constraint scale. Substantive EDM-derived honest-disclosure observation (honest-disclosure correction #4 component).
**Naturalness / tuning status:** Lower bound from observational EDM constraint; tighter constraint as EDM bounds improve.
**Source provenance:** Liu-Qin-Bian 2026 *EPJC* arXiv:2409.16091v2; Roussy 2023; [F-02 Liu-Qin-Bian 2026](./deep-review-reports/F-02_Liu2026_PostJan2026_deeppass.md); Scaffold §5.2 [v7 addition]
**First introduced:** v7 (Amendment 9)
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [CR-0027](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-0027), [MU-026](#mu-026), [CD-OP-012](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-012)

### MU-026

**Quantity name:** Electron EDM constraint
**Symbol:** d_e / e (electron electric dipole moment / charge)
**Type:** Scalar
**Value-domain:** Simple-scalar (upper bound)
**Physical dimension:** cm (or e·cm in natural form)
**Definition pointer:** Standard particle physics; Roussy 2023 experimental bound
**Values across corpus:** d_e/e < 4.1 × 10⁻³⁰ cm per Roussy et al. 2023 measurement. Sets Λ_CPV ≳ 338 TeV constraint on Liu-Qin-Bian 2026 dimension-6 CPV operator.
**Comparability notes:** Standard experimental constraint; tightens over time as measurements improve.
**Naturalness / tuning status:** Observational upper bound; informs F-02 mechanism viability.
**Source provenance:** Roussy et al. 2023; Liu-Qin-Bian 2026 deployment; Scaffold §5.2 [v7 addition]
**First introduced:** v7
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [MU-025](#mu-025), [CD-OP-012](UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md#cd-op-012)

### MU-027

**Quantity name:** Cosmological constant
**Symbol:** Λ
**Type:** Scalar
**Value-domain:** Simple-scalar
**Physical dimension:** 1/length² (or GeV² in natural units)
**Definition pointer:** Standard cosmology; Sorkin 1990 prediction context
**Values across corpus:** Observed Λ ≈ 1.1 × 10⁻⁵² m⁻² (current standard). **Sorkin 1990 F-07 CST prediction Λ ~ 1/√V_universe predates 1998 dark-energy discovery and matches observed scale at order-of-magnitude level** — strongest successful pre-discovery prediction in audit corpus per Scaffold §10.2 (not 5σ but notable).
**Comparability notes:** Order-of-magnitude prediction-match for Sorkin 1990; finer comparison requires specifying V_universe.
**Naturalness / tuning status:** Sorkin 1990 derives Λ scale from causal-set first principles; cosmological-constant problem of standard physics is precisely the naturalness gap (~120 OoM mismatch between vacuum-energy QFT prediction and observed Λ). Sorkin 1990 partially resolves at order-of-magnitude.
**Source provenance:** Sorkin 1990; Scaffold §9.3, §10.2
**First introduced:** Pre-trial
**Status:** Active
**Cross-program portability:** Generic
**Cross-references:** [CR-0011](UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md#cr-0011). Deep-review file (Theme C foundational, in `./deep-review-reports/`): [F-07 causal-set theory](./deep-review-reports/F-07_ThemeC_deeppass.md) (Sorkin 1990 prediction context; strongest successful pre-discovery prediction in audit corpus).

### MU-028

**Quantity name:** Inverse PT duration to Hubble rate
**Symbol:** β/H
**Type:** Scalar
**Value-domain:** Set-based
**Physical dimension:** Dimensionless
**Definition pointer:** Standard cosmology of phase transitions; Liu-Qin-Bian 2026 deployment
**Values across corpus:** β/H ∈ [10², 10⁸] across Liu-Qin-Bian CME-amplified parameter scan.
**Comparability notes:** Standard F-02 cluster parameter. Wide range explored to find regimes that reproduce observed BAU.
**Naturalness / tuning status:** Set-based exploration spanning 6 orders of magnitude reflects parameter-space search for viable CME-amplification regimes.
**Source provenance:** Liu-Qin-Bian 2026; [F-02 Liu-Qin-Bian 2026](./deep-review-reports/F-02_Liu2026_PostJan2026_deeppass.md); Scaffold §5.2 [v7 addition]
**First introduced:** v7
**Status:** Active
**Cross-program portability:** Generic

### MU-029

**Quantity name:** Bubble wall velocity
**Symbol:** v_w
**Type:** Scalar
**Value-domain:** Set-based
**Physical dimension:** Dimensionless (in units of c)
**Definition pointer:** Standard cosmology of first-order phase transitions
**Values across corpus:** v_w ∈ [10⁻², 1] across Liu-Qin-Bian parameter scan.
**Comparability notes:** Standard F-02 cluster parameter.
**Naturalness / tuning status:** Set-based exploration; values approaching c are deflagration/detonation regime.
**Source provenance:** Liu-Qin-Bian 2026
**First introduced:** v7
**Status:** Active
**Cross-program portability:** Generic

### MU-030

**Quantity name:** Chemical potential difference
**Symbol:** Δμ
**Type:** Scalar
**Value-domain:** Set-based
**Physical dimension:** Various (dimensionless or GeV depending on normalisation)
**Definition pointer:** Liu-Qin-Bian 2026 CME mechanism
**Values across corpus:** Δμ ∈ [10⁻¹⁰, 1] across Liu-Qin-Bian parameter scan.
**Comparability notes:** F-02 cluster parameter for CME mechanism.
**Naturalness / tuning status:** Set-based; wide range explored.
**Source provenance:** Liu-Qin-Bian 2026
**First introduced:** v7
**Status:** Active
**Cross-program portability:** Generic

### MU-031

**Quantity name:** Magnetic field strength scale
**Symbol:** B_0
**Type:** Scalar
**Value-domain:** Set-based
**Physical dimension:** m²_W (W boson mass squared; or equivalent natural-unit GeV²)
**Definition pointer:** Liu-Qin-Bian 2026 helical magnetic field generation
**Values across corpus:** B_0 ∈ [10⁻⁷, 10⁻³] m²_W across Liu-Qin-Bian parameter scan. Fully helical magnetic fields from EWPT fall below current observational bounds (Blazar/MHD evolution).
**Comparability notes:** F-02 cluster parameter for helical MF generation in two-bubble collisions.
**Naturalness / tuning status:** Set-based; constrained from above by observational bounds.
**Source provenance:** Liu-Qin-Bian 2026; [F-02 Liu-Qin-Bian 2026](./deep-review-reports/F-02_Liu2026_PostJan2026_deeppass.md)
**First introduced:** v7
**Status:** Active
**Cross-program portability:** Generic

### MU-032

**Quantity name:** Hořava-Lifshitz constraint parameter
**Symbol:** |1 − √β|_HL
**Type:** Scalar
**Value-domain:** Simple-scalar (upper bound)
**Physical dimension:** Dimensionless
**Definition pointer:** F-09 Hořava-Lifshitz gravity; GW170817 multimessenger constraint
**Values across corpus:** |1 − √β|_HL < 10⁻¹⁹–10⁻¹⁸ per GW170817 + GRB 170817A multimessenger bound. Strongest direct empirical-parameter constraint across audit corpus per Scaffold §10.1 spectrum.
**Comparability notes:** 5σ-class constraint rules out HL gravity parameter range; does NOT positively detect HL.
**Naturalness / tuning status:** Observational upper bound; tight constraint on HL UV violation of Lorentz invariance.
**Source provenance:** Scaffold §10.1 (F-09 trial-leading entry)
**First introduced:** Pre-trial
**Status:** Active
**Cross-program portability:** Generic

---

## §4 Cross-reference manifest

Outgoing cross-references from this index document, per Spec v3 §7.6:

| From | Target file | Target version | Target anchor | Purpose |
|---|---|---|---|---|
| All MU-* entries | UMF_Trial_S3M0S1_Index1_ContextDefinition_v2.md | v2 (current) | various CD-* anchors | Definition pointers; Item / Adjudication cross-references |
| MU-001, MU-002, MU-003, MU-010, MU-014, MU-023 | UMF_Trial_S3M0S1_Index2_ContextRelationships_v2.md | v2 (current) | CR-NNNN and CR-JC-NNNN | Parameter-regime edges; foundational edges; clusters referencing these quantities |
| MU-001, MU-002, MU-014, MU-024 | UMF_Trial_S3M0S1_Synthesis_Paper_Scaffold_v8_consolidated.md | v8 (v9 pending sub-cycle B) | §5.2; §11.3 Item 5; §14.1 | Source provenance for cluster values + honest-disclosure context |
| MU-001 to MU-031 (cluster + F-02 entries) | VC_v0_35_Amendment10_adjacency_review_2026.md | (prior anchor) | §3.E; §3.G; §3.K | Source provenance for AdjacencyReview2026 cycle + cluster characterisation |
| All MU-* entries with CD-OP-040 deeppass updates | VC_v0_35_Amendment13_filename_alignment_cycle.md | (current anchor) | §2, §4, §6 | Source provenance for filename alignment cycle + CD-OP-040 convention registration |
| MU-016, MU-017, MU-018, MU-021, MU-022 | Introduction Letter v2 | (current) | Postulate sections | Source provenance for UMF v0.7 §3.1 assumption 4 territory |

**Deep-review files cross-reference manifest** (all 31 files in `./deep-review-reports/` enumerated comprehensively per CD-OP-040; bidirectional navigation from metric units to deep-review files):

| File | Class | Linked from Index 3 entries |
|---|---|---|
| `A-01_ThemeC_deeppass.md` | Theme C foundational (A-series) | (referenced in Index 1 CD-OP-031; quantitative parameters not surfaced at MU level — Wheeler 1955 mass range ~10³⁹–10⁵⁷ g could be added v3) |
| `A-02_ThemeC_deeppass.md` | Theme C foundational (A-series) | (no MU-level parameters surfaced in v1) |
| `A-04_ThemeC_deeppass.md` | Theme C foundational (A-series) | (no MU-level parameters surfaced in v1) |
| `A-05_ThemeC_deeppass.md` | Theme C foundational (A-series) | (boson-star mass range / scalar-field self-coupling could be added v3; LIGO/Virgo/EHT/HSC/PTA constraint values out of MU scope per v1 §6 caveat 1) |
| `A-06_ThemeC_deeppass.md` | Theme C foundational (A-series) | (analogue-laboratory parameters out of MU scope per v1 §6 caveat 1) |
| `A-08_ThemeC_deeppass.md` | Theme C foundational (A-series) | (no MU-level parameters surfaced in v1) |
| `A-09_ThemeC_deeppass.md` | Theme C foundational (A-series) | (no MU-level parameters surfaced in v1) |
| `A-10_ThemeC_deeppass.md` | Theme C foundational (A-series) | (BEC analogue parameters; Belgiorno horizon-analogue constraint values out of MU scope per v1 §6 caveat 1) |
| `B-01_ThemeC_deeppass.md` | Theme C foundational (B-series) | (referenced in Index 1 CD-OP-032; Rainich already-unified construction — no MU-level parameters surfaced) |
| `B-02_ThemeC_deeppass.md` | Theme C foundational (B-series) | (Brill 1959 ADM positive-mass theorem context for MU-008 if extended v3) |
| `B-03_ThemeC_deeppass.md` | Theme C foundational (B-series) | (ADD 1998 large extra dimensions; G₄ = G_(4+n)/V_n context for MU-018 if extended v3) |
| `B-04_ThemeC_deeppass.md` | Theme C foundational (B-series) | (referenced in Index 1 CD-OP-032; It-from-Bit programme — no MU-level parameters surfaced) |
| `D-01_D-02_ThemeC_deeppass.md` | Theme C foundational combined pair (D-series) | (trans-Planckian / TCC; MU-019 Planck scale + MU-013 trans-Planckian regime could be linked v3) |
| `F-01_ThemeC_deeppass.md` | Theme C foundational (F-series) | (no MU-level parameters surfaced in v1) |
| `F-02_ThemeC_deeppass.md` | Theme C foundational (F-series) | (referenced in Index 1 CD-OP-034; EWPT energy scale could be linked v3) |
| `F-02_Liu2026_PostJan2026_deeppass.md` | Post-cycle paper deeppass (F-02) | **MU-001** (CPV-operator-alone 1.8 × 10⁻¹⁴ rule-out); **MU-025** (Λ_CPV ≥ 338 TeV via Roussy 2023); **MU-026** (d_e/e < 4.1 × 10⁻³⁰ cm); **MU-028 to MU-031** (set-based F-02 parameters β/H, α_strength, τ_SW, latent heat) |
| `F-03_ThemeC_deeppass.md` | Theme C foundational (F-series) | (no MU-level parameters surfaced in v1) |
| `F-04_ThemeC_deeppass.md` | Theme C foundational (F-series) | (cosmic-string tension μ_string flagged in v1 §6 caveat 1; could be added v3) |
| `F-05_ThemeC_deeppass.md` | Theme C foundational (F-series) | (aggregating reference for F-05 cluster; quantitative values distributed across MU-001, MU-002, MU-003, MU-014, MU-023, MU-024) |
| `F-05_Pereira2026_PostJan2026_deeppass.md` | Post-cycle paper deeppass (F-05) | **MU-001** (η_B/s = 8.8 × 10⁻¹¹ target); **MU-002** (M_Pl with ε ≈ O(10⁻⁶)); **MU-003** (T_D ≈ 8.5 × 10¹³ GeV); **MU-014** (gravity-modifying function form); **MU-023** (Pereira ε parameter) |
| `F-05_Whittingham2026_PostJan2026_deeppass.md` | Post-cycle paper deeppass (F-05) | **MU-001** (CMB 8.65 × 10⁻¹¹; BBN range 8.2–9.4 × 10⁻¹¹); **MU-002** (M*=M_Pl undershoot; resolution at ≈0.4 M_Pl); **MU-014** (Einstein-frame scalaron form) |
| `F-05_Samaddar2025_AdjacencyReview2026_deeppass.md` | Post-cycle paper deeppass (F-05) | **MU-001** (9.42 × 10⁻¹¹); **MU-002** (M* ≈ 10⁻⁷ M_Pl); **MU-003** (T_D = 2 × 10¹⁶ GeV); **MU-009** (T_G); **MU-010** (β/H structural); **MU-014** (f(T, T_G) form); **MU-024** (power-law exponent m with text-Table-2 inconsistency) |
| `F-05_Samaddar2025_AdjacencyReview2026_deeppass_Addendum.md` | Post-cycle paper deeppass Addendum (F-05) | All Samaddar MU references above carry peer-review-status finding context per Addendum |
| `F-06_ThemeC_deeppass.md` | Theme C foundational (F-series) | (LQG; no MU-level parameters surfaced in v1) |
| `F-07_ThemeC_deeppass.md` | Theme C foundational (F-series) | **MU-027** (Λ Sorkin 1990 pre-discovery prediction Λ ~ 1/√V_universe) |
| `F-08_ThemeC_deeppass.md` | Theme C foundational (F-series) | (Verlinde EG entropic-gravity parameters flagged in v1 §6 caveat 1; a_M = c·H_0/6 vs Yoon 2019/2024 c·H_0/9 could be added v3) |
| `F-09_ThemeC_deeppass.md` | Theme C foundational (F-series) | **MU-032** (HL constraint parameter; Hořava-Lifshitz GW170817 constraint) |
| `F-10_ThemeC_deeppass.md` | Theme C foundational (F-series) | (Refracted Gravity parameters flagged in v1 §6 caveat 1; could be added v3) |
| `Item-007_Rusakov2026_LRDcocoon_substantive_review_v1.md` | Item-phenomenon substantive review (superseded for framing-bias per CD-OP-003 #1) | (LRD cocoon parameters not yet surfaced at MU level; v3 could add black-hole-cocoon mass scale + redshift range) |
| `Item-007_Rusakov2026_LRDcocoon_substantive_review_v2.md` | Item-phenomenon substantive review (current canonical) | (same as v1; v3 may add LRD parameters) |
| `Item-007_Rusakov2026_LRDcocoon_substantive_review_annotation.md` | Audit-trail annotation | (CD-OP-040 annotation convention exemplar; no MU-level content) |

All external corpus links per Spec v3 §7.8 (markdown filename pattern; version pinning; bulk find-and-replace at deployment). Comprehensive hyperlinking introduced at v2 per Stephen direction 28 May 2026 AEST: "comprehensive — circular navigation is very valuable to a human."

---

## §5 Version history

| Version | Date | Author | Notes |
|---|---|---|---|
| v1 | 27 May 2026 (AEST) | Claude Opus 4.7 Adaptive (Anthropic) | First populated instance per Spec v3 §11 Step 2c; 32 MU entries; anchored at Amendment 11; retained per CD-OP-004 |
| v2 | 28 May 2026 (AEST) | Claude Opus 4.7 Adaptive (Anthropic) | Supersedes v1. CD-OP-040 filename updates applied to Source provenance fields (Samaddar, Pereira, Whittingham, Liu paths); markdown hyperlinks now wrap deeppass references. Deep-review hyperlinks added in-entry for MU-001 (η_B/s cluster + F-02 Liu), MU-002 (M* ~7 OoM spread), MU-027 (Λ Sorkin pre-discovery prediction). Index 1 / Index 2 cross-references updated from v1 to v2 throughout. §4 cross-reference manifest expanded with full 31-file enumeration table mapping each deep-review file to its Index 3 linked-from entries. §6 honest-disclosure caveats updated. Anchored at Amendment 13. Companion to Index 1 v2 + Index 2 v2 |

---

## §6 Honest-disclosure caveats at v2 close

Per modal-status preservation (CD-OP-002), the following caveats apply:

1. **Coverage scope.** Unchanged from v1. 32 MU entries comprehensive for F-05 / F-02 cluster comparability + UMF assumption 4 fundamental constants + major constraint scales. Under-coverage of A-series, F-04, F-08, F-10 parameters preserved as v3 candidates (per §4 manifest enumeration table "available for v3 wiring" entries).

2. **Internal text-Table-2 inconsistency in MU-024.** Unchanged from v1; claim remains at deeppass-report level per [F-05 Samaddar 2025 deeppass](./deep-review-reports/F-05_Samaddar2025_AdjacencyReview2026_deeppass.md) §7.4.

3. **Set-based notation.** Unchanged from v1.

4. **Naturalness/tuning status entries.** Unchanged from v1.

5. **Dual-tagging applied.** Unchanged from v1.

6. **Comparability notes mandatory.** Unchanged from v1.

7. **Forward and back-references.** All Index 1 + Index 2 cross-references updated from v1 → v2 (36 instances). All deep-review file references in Source provenance now markdown hyperlinks per CD-OP-040. Cross-reference manifest §4 expanded with 31-file table.

8. **MU-002 M* spread is central to Item 5 open question.** Unchanged from v1; now hyperlinked to three of the four F-05 cluster deeppass files (Pereira, Whittingham, Samaddar + Addendum).

9. **Hyperlink completeness scope at v2.** Comprehensive deep-review hyperlinks added inline to: MU-001, MU-002, MU-027 (highest decision-relevance entries). Source provenance hyperlinks added to all entries referencing deeppasses (8 MU entries). **Not yet hyperlinked in v2:** MU entries for fundamental constants (MU-015 to MU-022) and constraint scales (MU-025 to MU-031) that don't currently reference deeppasses in their main fields — readers navigate via the §4 manifest table. v3 production cycle may extend per-entry hyperlinks if Stephen directs.

10. **Deep-review reflexive cross-references.** The 31 deep-review files themselves carry internal "Cross-references" sections pointing to other deep-review files via plain-text matrix codes. These have NOT been converted to markdown hyperlinks at v2; reflexive update deferred to a later cycle per Stephen direction 28 May 2026 AEST ("work down to cold reviews" — top-down sequence).

---

## §7 Status at v2 close

Second populated instance of Index 3 ready for Stephen review. 32 MU entries unchanged in count; comprehensively re-pointed to v2 of Indexes 1 and 2; deep-review hyperlinks added for key entries; CD-OP-040-compliant filenames throughout. Anchored at Amendment 13. v1 retained per CD-OP-004.

Sub-cycle A (Indexes 1+2+3 v2) now complete:
- Index 1 v2: 87 entries (39 OP + CD-OP-040 + 21 TH + 19 OP-Adj + 7 OP-Item)
- Index 2 v2: 65 relational entries (52 bilateral + 13 clusters)
- Index 3 v2: 32 metric-unit entries

**Total Sub-cycle A output: 184 indexed entries across three navigation-layer v2 documents (Index 1 v2 added one entry: CD-OP-040).**

Awaiting direction:
- Approve sub-cycle A → proceed to sub-cycle B (Toolkit Addendum v1.1 + Scaffold v9)
- Revise sub-cycle A → identify changes for v2.1
- Defer

---

*End of UMF_Trial_S3M0S1_Index3_MetricUnits_v2.md*
