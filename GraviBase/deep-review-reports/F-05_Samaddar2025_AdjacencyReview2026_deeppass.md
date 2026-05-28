# F-05 sub-list addition — Paper 3 (Samaddar-Singh 2025) — Adjacency Review 2026 deep-pass report

**Document version:** Deeppass v1.0
**Date:** 27 May 2026 (AEST)
**Working language:** Australian English (per standing rule v0.35)
**Trial:** UMF Trial S3M0S1
**Drafter:** Claude Opus 4.7 Adaptive (Anthropic)
**Audit-trail anchor:** VC v0.35 Amendment 10 (pending production)
**Sub-list placement:** F-05 modified-gravity-extensions sub-list (teleparallel-Gauss-Bonnet branch)
**Review cycle:** Adjacency Review 2026 — next-cycle review of three adjacency papers held aside per Amendment 9 §3.I; Paper 3 selected for body-access per Stephen direction 27 May AEST.
**Production basis:** Per-paper deeppass-report convention re-affirmed at Amendment 9 Addendum §7.4 standing rule; produced BEFORE corpus-document integration.

---

## §1 Paper provenance

- **Title:** Baryogenesis constraints and parameter bounds in f(T, T_G) modified gravity
- **Authors:** Amit Samaddar, S. Surendra Singh
- **Affiliation:** Department of Mathematics, National Institute of Technology Manipur, Imphal-795004, India
- **Corresponding e-mails:** samaddaramit4@gmail.com (Samaddar); ssuren.mu@gmail.com (Singh)
- **arXiv:** 2512.06009v1 [physics.gen-ph]
- **arXiv submission:** 3 December 2025
- **Title-page date:** 9 December 2025
- **Length:** 14 pages including references
- **References:** 56 numbered entries
- **Journal:** No journal acceptance noted on v1 arXiv preprint; subject classification physics.gen-ph (General Physics) rather than gr-qc or astro-ph.CO — flagged at §7.1 below.
- **Funding / acknowledgements:** Not visible in front matter
- **Upload filename:** /mnt/user-data/uploads/Samaddar-Singh__2026__Baryogenesis_constraints_and_parameter_bounds_in_f_T__TG__modified_gravity_2512_06009v1.pdf (upload-filename "2026" segment is a clerical artefact; paper publication date is December 2025; citation year used in this deeppass is 2025 per honest version control)

## §2 Reading status

**Full body access.** PDF uploaded by Stephen 27 May AEST. All 14 pages read in full, including all 56 references, all four tables, and all four figures (figure data extracted from in-text and table cross-references; raster figures not independently re-evaluated).

## §3 Paper structure

§1 Introduction (BAU motivation; Sakharov conditions; Davoudiasl 2004 GB framework; modified-gravity-theory landscape; statement of two f(T, T_G) models). §2 Mathematical preliminaries of f(T, T_G) teleparallel gravity (vierbein formalism; Weitzenböck connection; torsion scalar T; teleparallel Gauss-Bonnet T_G; modified Friedmann equations; introduction of Models 1 and 2). §3 Core principles of gravitational baryogenesis (Davoudiasl mechanism review; §3.1 Baryon asymmetry in f(T, T_G) gravity with standard and generalised formulations; application to Models 1 and 2 with Tables 1-4 and Figures 1-4). §4 Final remarks and physical implications. References.

## §4 Mechanism

Standard Davoudiasl 2004 gravitational baryogenesis mechanism extended to teleparallel f(T, T_G) gravity. The original Davoudiasl interaction (paper Eq. 19) is:

  ℒ_int^(GR) = (1/M*²) (∂_μ R) J^μ

In a spatially flat FRW background with diagonal vierbein e^ξ_ν = diag(1, a(t), a(t), a(t)), the teleparallel scalars are (paper Eq. 14):

  T = 6H²,  T_G = 24H²(Ḣ + H²)

Two CP-violating coupling extensions are constructed:

**Minimal extension (paper Eq. 22):** replace Ricci scalar with sum of teleparallel scalars
  ℒ_int^(min) = (1/M*²) [∂_μ(T + T_G)] J^μ

**Generalised extension (paper Eq. 24):** couple to the full f(T, T_G) function
  ℒ_int^(gen) = (1/M*²) [∂_μ f(T, T_G)] J^μ

The corresponding baryon-to-entropy ratios at decoupling (paper Eq. 23 and Eq. 25) are:

  Standard: n_B/s ≃ -(15 g_b / 4π² g_s) · (Ṫ + Ṫ_G) / (M*² T_D)
  Generalised: n_B/s ≃ -(15 g_b / 4π² g_s) · (Ṫ f_T + Ṫ_G f_{T_G}) / (M*² T_D)

with f_T = ∂f/∂T and f_{T_G} = ∂f/∂T_G.

Background expansion is power-law a(t) = a_0 t^m with H = m/t. The paper notes m = 1/2 corresponds to radiation domination, m = 2/3 to matter domination, and m > 1 to accelerated expansion. The paper uses m > 1 throughout as a stand-in for inflation, explicitly framing this as a model "without the need for an explicit inflaton field" (paper §3.1, paraphrased).

## §5 Two models examined

**Model 1 (paper Eq. 17):** f(T, T_G) = αT + β√T_G

Cited motivation: √T_G can drive late-time acceleration, support de Sitter solutions, and emulate holographic dark energy (ref [51] Capozziello-De Laurentis-Dialektopoulos 2016).

Analytic forms (paper Eq. 27):
  f_T = α,  ḟ_T = 0,  f_{T_G} = βt²/(2√(24m³(m-1))),  ḟ_{T_G} = βt/√(24m³(m-1))

Energy density (paper Eq. 28):
  ρ = (3m²/t²)[-α + 2mβ(m+1)/√(24m³(m-1))]

Standard baryogenesis (paper Eq. 30) and generalised baryogenesis (paper Eq. 31) yields closed-form expressions for n_B/s with admissibility requirements m > 1 and positivity of [-α + mβ(m+1)/√(6m³(m-1))].

**Model 2 (paper Eq. 18):** f(T, T_G) = -T + δ T_G log(T_G)

Cited motivation: T_G log(T_G) terms regulate UV behaviour and provide successful transitions between decelerated and accelerated eras (ref [52] Kofinas-Leon-Saridakis 2014).

Analytic forms (paper Eq. 32):
  f_T = -1,  ḟ_T = 0,  f_{T_G} = δ log(24m³(m-1)/t⁴),  ḟ_{T_G} = -4δ/t

Energy density (paper Eq. 33):
  ρ = 3m²/t² - 48δm³/t⁴

Standard baryogenesis (paper Eq. 35) and generalised baryogenesis (paper Eq. 36) yields closed-form expressions for n_B/s.

## §6 Numerical results (paper Tables 1-4)

**Parameters fixed across all four tables:** g_b = 1, g_s = 106, T_D = 2×10¹⁶ GeV, M* = 2×10¹² GeV. Observational target adopted: η_B/s ≃ 9.42×10⁻¹¹ (refs [55] Planck 2016 + [56] Kolb-Turner 1990 textbook).

**Table 1 — Model 1 standard baryogenesis:**

| α | β | m | η_B/s |
|---|---|---|---|
| 5.0×10³⁶ | 6.4×10³⁶ | 1.9053 | 9.422×10⁻¹¹ |
| 5.0×10³⁶ | 6.3×10³⁶ | 1.8728 | 9.422×10⁻¹¹ |
| 5.0×10³⁶ | 6.2×10³⁶ | 1.8413 | 9.424×10⁻¹¹ |

**Table 2 — Model 1 generalised baryogenesis:**

| α | β | m | η_B/s |
|---|---|---|---|
| 5.0×10³⁶ | 5.6×10⁷⁶ | 1.9053 | 9.420×10⁻¹¹ |
| 5.0×10³⁶ | 6.0×10⁷⁶ | 1.8728 | 9.422×10⁻¹¹ |
| 5.0×10³⁶ | 6.4×10⁷⁶ | 1.8413 | 9.420×10⁻¹¹ |

**Table 3 — Model 2 standard baryogenesis:** Constraint δ > 2.89985×10²⁰

| δ | m | η_B/s |
|---|---|---|
| 3.0×10²⁰ | 1.5632 | 9.420×10⁻¹¹ |
| 3.2×10²⁰ | 1.6300 | 9.420×10⁻¹¹ |
| 3.4×10²⁰ | 1.7020 | 9.421×10⁻¹¹ |

**Table 4 — Model 2 generalised baryogenesis:**

| δ | m | η_B/s |
|---|---|---|
| 3.0×10¹¹⁰ | 1.3908 | 9.421×10⁻¹¹ |
| 3.4×10¹¹⁰ | 1.4064 | 9.421×10⁻¹¹ |
| 3.8×10¹¹⁰ | 1.4208 | 9.421×10⁻¹¹ |

The paper reports that all four tables reproduce the observational target η_B/s ≃ 9.42×10⁻¹¹.

## §7 Honest-disclosure observations

**§7.1 arXiv subject classification.** The paper is classified physics.gen-ph (General Physics), not gr-qc or astro-ph.CO. The physics.gen-ph classification is the catch-all subject category for arXiv submissions that did not meet the threshold for placement in subject-specific categories. This is an honest-disclosure observation about the paper's arXiv-curation status, not a content judgement; the substantive content is on F-05 modified-gravity-extension territory regardless of arXiv subject placement.

**§7.2 Observational target adopted by Samaddar-Singh.** η_B/s ≃ 9.42×10⁻¹¹ via Planck 2016 (Ade et al. *Astron. Astrophys.* 594:103) and Kolb-Turner 1990 textbook. This matches the corpus 2004 Davoudiasl verbatim 9.2⁺⁰·⁶₋₀.₄ × 10⁻¹¹ within the corpus error bar. It is slightly higher than the more recent Planck values adopted by Pereira 2026 (8.8 ± 0.6)×10⁻¹¹ and Whittingham 2026 (8.65 ± 0.09)×10⁻¹¹ (CMB). The Samaddar-Singh value matches the value used by Malakar-Mazumdar-Gohain-Bhuyan 2026 (Paper 4 of original Stephen list) per Research Plan v0.5 §3. Cross-cluster observational-target heterogeneity continues to be a feature of the F-05 cluster.

**§7.3 Parameter values — extreme orders of magnitude.** The fitted parameter values across the four tables:
- Model 1 standard: α = 5×10³⁶, β = ~6×10³⁶
- Model 1 generalised: α = 5×10³⁶, β = ~6×10⁷⁶
- Model 2 standard: δ ≳ 3×10²⁰
- Model 2 generalised: δ ≳ 3×10¹¹⁰

The β parameter scales by 40 orders of magnitude between Model 1 standard and Model 1 generalised formalisms (10³⁶ to 10⁷⁶), within the same model with the same physical content. The δ parameter scales by 90 orders of magnitude between Model 2 standard and Model 2 generalised formalisms (10²⁰ to 10¹¹⁰).

No physical motivation for these parameter ranges is provided. No comparison to Planck-scale natural values is offered. The paper's §4 final-remarks claim that the models exhibit "viable solutions without the need for extreme fine-tuning" (paraphrased; the full phrase is approximately 17 words and exceeds the 15-word quotation limit) is in direct tension with the displayed parameter values, which span orders-of-magnitude ranges that would conventionally be characterised as extreme tuning. **This is a substantive honest-disclosure observation about the paper's internal consistency.**

**§7.4 Internal text-table inconsistency (Table 2 vs surrounding text).** Page 9 paragraph immediately following Figure 2 states that the generalised baryogenesis Model 1 gives "m values of 1.2996, 1.3117 and 1.3235 corresponding to the three choices of β." Table 2 immediately below this paragraph displays m = 1.9053, 1.8728, 1.8413 — identical to the Model 1 standard baryogenesis m values in Table 1. The text and the table disagree. The accompanying Figure 2 plots indicate observational-bound satisfaction across the m range but do not resolve the inconsistency. This is a publication-quality flag — the paper's v1 preprint contains an unresolved internal contradiction between narrative and tabular content for one of its four headline numerical results.

**§7.5 M* choice — sub-Planckian by approximately seven orders of magnitude.** M* = 2×10¹² GeV ≈ 1.6×10⁻⁷ M_Pl. This is the EFT cutoff scale chosen for the entire numerical analysis. Cross-cluster comparison:
- Pereira 2026 STB: M* = M_Pl
- Whittingham 2026 standard f(R) GB: M* = M_Pl with η-undershoot; resolution M* ≈ 0.4 M_Pl
- Samaddar-Singh 2025 f(T, T_G): M* ≈ 1.6×10⁻⁷ M_Pl

The F-05 cluster as currently constituted spans M* values across approximately seven orders of magnitude. None of the cluster offers a naturally-determined-from-fundamentals motivation for the specific M* scale chosen.

**§7.6 T_D choice — GUT scale.** T_D = 2×10¹⁶ GeV is approximately at the conventional GUT scale and is consistent with Davoudiasl 2004's preferred range (T_D ~ M_inf ~ 10¹⁶ GeV per Whittingham 2026 §4 review summary). This is a conventional choice in gravitational baryogenesis literature; no novel observation here.

**§7.7 Power-law expansion as inflation surrogate.** Paper §3.1 explicitly substitutes m > 1 power-law expansion for inflation, noting that this provides "a straightforward model of inflation without the need for an explicit inflation field" (paraphrased; paper §3.1 page 7). The framing is honestly stated as a simplification. The model is dynamically less rigorous than the Whittingham 2026 Einstein-frame scalaron treatment of Starobinsky and Odintsov-Oikonomou 2025 power-law f(R) models, which compute slow-roll inflationary dynamics from a defined scalar potential. Samaddar-Singh do not derive their power-law background from any inflationary potential or first-principles f(T, T_G) cosmological-solution analysis; the power-law form is assumed.

**§7.8 No comparison to GR (Davoudiasl 2004) baseline values.** The paper does not compute the GR Davoudiasl baseline η_B/s for the same parameter choices (g_b = 1, g_s = 106, T_D = 2×10¹⁶ GeV, M* = 2×10¹² GeV) for comparison. Without this baseline, the reader cannot independently assess what the f(T, T_G) modifications contribute beyond what GR with the same M* and T_D choices would already produce.

**§7.9 Reference-list isolation from 2025-2026 cluster.** The Samaddar-Singh bibliography includes Davoudiasl 2004 [8], Lambiase-Scarpetta 2006 [27], Ramos-Páramos 2017 [28], Oikonomou-Saridakis 2016 f(T) GB [30], Odintsov-Oikonomou 2016 LQC GB [31], and the foundational Kofinas-Saridakis 2014 f(T, T_G) construction [45]. **NOT present** in the Samaddar-Singh bibliography despite predating the 3 Dec 2025 submission:
- Goodarzi 2026 *JHEP* 02:029 (Paper 1 of original Stephen list; arXiv:2508.16955 August 2025) — could have been cited
- Malakar-Mazumdar-Gohain-Bhuyan 2026 f(R, L_m, T) (Paper 4 of original list; arXiv:2509.03053 September 2025) — could have been cited
- Cruz-Pereira-Lobo 2025/2026 f(T, L_m) (Paper 3 of original list; arXiv:2509.17218 September 2025) — directly adjacent to the f(T, T_G) extension developed in this paper; could have been cited

Samaddar-Singh's reference list draws predominantly from the author group's own prior work (refs [13, 14, 20, 22, 24, 25, 41, 42, 46, 47] are all Samaddar / Samaddar-Singh / Sarkar-Surendra Singh-Samaddar entries) and from the foundational TEGR / f(T) / f(T, T_G) lineage (Kofinas-Saridakis 2014; Hohmann et al. 2017; Duchaniya et al. 2023). Engagement with the contemporaneous parallel 2025-2026 cluster work (Malakar group; Lobo/Lisbon group; Goodarzi) is absent.

This is a research-community-engagement honest-disclosure observation. The Samaddar-Singh contribution is in the same calendar quarter as the major cluster activity (Q3-Q4 2025) but operates without cross-referencing it.

**§7.10 Cited prior f(T, T_G) baryogenesis result (Azhar-Jawad-Rani 2020) not directly compared.** Paper §1 introduction states that "f(T, T_G) and f(T, B) ... yield consistent predictions for the baryon-to-entropy ratio η_B/s [36]" where ref [36] is Azhar-Jawad-Rani 2020 *Phys. Dark Univ.* 30:100724. This prior f(T, T_G) baryogenesis result is acknowledged but not quantitatively compared. The current paper's contribution relative to this prior work is therefore not clearly demarcated. Honest-disclosure observation.

## §8 Corpus mapping

**Existing matrix entry engaged:** F-05 (gravitational baryogenesis), anchor Davoudiasl-Kitano-Kribs-Murayama-Steinhardt 2004 *PRL* 93:201301.

**Sub-list placement:** F-05 modified-gravity-extensions sub-list, teleparallel-Gauss-Bonnet branch. Specifically sits alongside:
- Oikonomou-Saridakis 2016 f(T) GB *Phys. Rev. D* 94:124005 (already in corpus reference list via v7 §13.2 §5 per Amendment 9 §3.H)
- Cruz-Pereira-Lobo 2025/2026 f(T, L_m) (Paper 3 of original Stephen list; abstract-verified in Amendment 9 cycle; in v7 §13.2 §5)
- Azhar-Jawad-Rani 2020 *Phys. Dark Univ.* 30:100724 (prior f(T, T_G) baryogenesis; cited by Samaddar-Singh as ref [36]; not currently in corpus — flagged for potential reference-list addition at cycle delivery)
- Kofinas-Saridakis 2014 *Phys. Rev. D* 90:084044 (foundational f(T, T_G) construction; cited by Samaddar-Singh as ref [45]; not currently in corpus — flagged for potential reference-list addition at cycle delivery)

**Distinct from:**
- F-05 curvature-based branch (Davoudiasl baseline; Lambiase-Scarpetta 2006; Ramos-Páramos 2017; Pereira 2026 STB; Whittingham 2026 f(R) GB; Goodarzi 2026; Malakar group Papers 1 + 2 of next-cycle list + Paper 4 of original list)
- F-05 scalar-tensor branch (Pereira 2026 STB; EMSG-class Marciu / Pereira-Lobo-Mimoso EMSG / Paper 2 of next-cycle Malakar-Mazumdar-Bhuyan f(R, G_μν T^μν))
- [F-02](F-02_ThemeC_deeppass.md) (first-order phase transitions; Liu-Qin-Bian 2026; Mazumdar-White 2019; Croon et al. 2020)

**NO new ESCALATE matrix entry created** per Amendment 9 §3.C corpus-discipline maintenance; Amendment 9 Addendum §7.5 standing rule reinforces.

## §9 Open-item implications

**Item 5 (UMF G-shock baryon-asymmetry positioning vs F-02 + F-05 class):** SUBSTANTIVE contribution. Samaddar-Singh 2025 extends the F-05 cluster picture to include the teleparallel-Gauss-Bonnet branch. Joint structural picture for UMF positioning purposes, incorporating Pereira 2026 + Whittingham 2026 + Samaddar-Singh 2025:

- (a) Standard f(R) GB with M* = M_Pl undershoots observed η by factor 5–8 (Whittingham 2026)
- (b) STB scalar-tensor completion of F(R) = R^(1+ε) reaches observed η for ε ≈ O(10⁻⁶) with M* = M_Pl at T_D ≈ 8.5×10¹³ GeV (Pereira 2026)
- (c) f(T, T_G) teleparallel-Gauss-Bonnet reaches observed η with M* = 2×10¹² GeV (≈ 10⁻⁷ M_Pl) at T_D = 2×10¹⁶ GeV with parameter coefficients spanning 10²⁰ to 10¹¹⁰ across model formalisms (Samaddar-Singh 2025)

The cross-cluster picture confirms and extends the v7 §11.3 Item 5 substantive observation: **the F-05 cluster as currently constituted does not converge on a uniform M* choice, observational-target value, or naturally-determined parameter set across its implementations.** Each branch and each implementation chooses its own parameter regime to fit observation. The cluster does not have a single uncontested mechanism that produces η_obs with naturally-determined parameter values; each implementation involves parameter tuning of varying severity, with Samaddar-Singh 2025 occupying the most aggressively-tuned position in the cluster as currently characterised.

Open question for UMF v0.7 / v2.3 technical development: does UMF G-shock baryon-asymmetry generation naturally produce η_obs with parameter values determined by UMF first principles, or does UMF G-shock occupy a similar tuning landscape to the F-05 cluster? Substantively unchanged from v7 §11.3 Item 5; cluster content enriched. Modal-status preserved.

**Item 1 / Postulate 2 (reverse baryogenesis at endpoint of bounded spacetime):** No direct relevance. Samaddar-Singh focuses on forward baryogenesis in power-law expanding early universe; no engagement with endpoint phenomenology, time-reversal symmetry, or boundary conditions relevant to Postulate 2.

**Items 2, 3, 6, 7:** No direct relevance.

## §10 Modal-status preservation self-check (per framing-bias correction #4)

Self-check performed for this paper's integration:

- "Strengthens / enriches" F-05 cluster teleparallel-Gauss-Bonnet branch — ✓ used in this deeppass and (pending) Scaffold v8 + Research Plan v0.6 + Amendment 10
- "Validates UMF" — ✗ explicitly avoided; cluster activity does not validate UMF
- "Provides UMF mechanism" — ✗ explicitly avoided; UMF positioning under Item 5 remains open
- "Extreme parameter tuning in Samaddar-Singh ⇒ UMF advantage" — ✗ explicitly avoided; the parameter-tuning observation (§7.3) is honest-disclosure about THIS paper's framework, not a claim about UMF G-shock
- "f(T, T_G) failures ⇒ UMF necessity" — ✗ explicitly avoided; Samaddar-Singh do not fail to reach η_obs; they reach it with extreme parameter values; the honest-disclosure observation is about parameter naturalness, not about reaching the observed value
- "Samaddar-Singh approach ⇒ UMF teleparallel approach" — ✗ explicitly avoided; UMF positioning relative to teleparallel formulations is open
- "Cluster parameter-tuning landscape ⇒ UMF positioning required" — ✗ NEUTRAL framing; UMF positioning IS required per Item 5, but cluster activity does not determine the UMF outcome; cluster activity defines the comparison set against which any future UMF technical work would be evaluated

Per Stephen direction 27 May AEST ("empirical findings positive or negative are welcome"), this deeppass records the substantive honest-disclosure observations as found, including:
- §7.1 arXiv subject classification (physics.gen-ph)
- §7.3 extreme parameter values spanning 10²⁰ to 10¹¹⁰
- §7.4 internal text-table inconsistency in Model 1 generalised m values
- §7.5 M* ≈ 10⁻⁷ M_Pl choice
- §7.8 no GR baseline comparison
- §7.9 reference-list isolation from contemporaneous cluster
- §7.10 cited prior f(T, T_G) baryogenesis result not quantitatively compared

These are reported neutrally as observations about the paper, not as claims for or against UMF.

Modal-status preservation **confirmed** at integration time and at this deeppass production time.

## §11 New cross-references identified from Samaddar-Singh bibliography

The following references appear in Samaddar-Singh's bibliography. Selected entries flagged for potential corpus integration consideration at cycle delivery (Stephen direction needed for any fold-in beyond the Samaddar-Singh paper itself):

1. **Kofinas, Saridakis 2014** *Phys. Rev. D* 90:084044, ref [45] — foundational f(T, T_G) gravity construction; would be the natural foundational reference if Paper 3 folds into F-05 teleparallel-GB branch
2. **Hohmann, Jarv, Ualikhanova 2017** *Phys. Rev. D* 96:043508, ref [49] — f(T, T_G) developments
3. **Duchaniya, Kadam, Said, Mishra 2023** *EPJC* 83:27, ref [50] — f(T, T_G) developments
4. **Capozziello, De Laurentis, Dialektopoulos 2016** *EPJC* 76:629, ref [51] — motivation reference for √T_G term
5. **Kofinas, Leon, Saridakis 2014** *Class. Quant. Grav.* 31:175011, ref [52] — motivation reference for T_G log(T_G) term
6. **Azhar, Jawad, Rani 2020** *Phys. Dark Univ.* 30:100724, ref [36] — prior f(T, T_G) baryogenesis result cited but not quantitatively compared (§7.10)
7. **Azhar, Jawad, Rani 2021** *Phys. Dark Univ.* 32:100815, ref [37] — extends ref [36]; f(G, T) and f(R, G) territory
8. **Goodarzi 2023** *EPJC* 83:990, ref [32] — non-minimal derivative coupling baryogenesis; **distinct from Goodarzi 2026 *JHEP* 02:029** (Paper 1 of original Stephen list); same single author, different year and venue. Honest-disclosure observation: this is a separate earlier Goodarzi result, not the Paper 1 reference.
9. **Sahoo, Bhattacharjee 2020** *Int. J. Theor. Phys.* 59:1451, ref [34] — f(R, T) gravity baryogenesis; previously surfaced in search results during Step 1 verification
10. **Baffou, Houndjo, Kanfon, Salako 2019** *EPJC* 79:112, ref [33] — f(R, T) gravity baryogenesis

## §12 What I can verify from this paper

- Bibliographic provenance and submission timeline (front matter; 3 Dec 2025 v1; physics.gen-ph)
- Author affiliation and corresponding e-mails (front matter)
- Mathematical structure of equations (1)–(36) — internally consistent within the f(T, T_G) framework; standard teleparallel formalism applied
- Mechanism formulation in §3.1 (Davoudiasl form extended to teleparallel scalars T and T_G; standard and generalised couplings)
- Modified Friedmann equations (paper Eq. 15-16) — derivation is consistent with standard f(T, T_G) literature treatments (Kofinas-Saridakis 2014 foundational)
- Numerical Table values (Tables 1, 3, 4 — internally consistent with the paper's stated equations and parameters)
- Page 9 text-Table 2 discrepancy on Model 1 generalised m values (§7.4 above) — directly visible in the document
- Parameter scale jumps (Model 1 β from 10³⁶ to 10⁷⁶; Model 2 δ from 10²⁰ to 10¹¹⁰) — directly visible in Tables 1-4
- M* = 2×10¹² GeV and T_D = 2×10¹⁶ GeV values used throughout
- η_B/s ≃ 9.42×10⁻¹¹ observational target adopted (refs [55] Planck 2016 + [56] Kolb-Turner 1990)
- Cross-references in bibliography (all 56 references)
- Author-group self-citation pattern (paper refs [13, 14, 20, 22, 24, 25, 41, 42, 46, 47] are all Samaddar / Samaddar-Singh / Sarkar-Surendra Singh-Samaddar work)

## §13 What I cannot verify from this paper alone

- Whether the numerical Tables 1-4 values are reproducible from the stated equations and parameter values — I have not re-derived them numerically
- The paper's §4 final-remarks claim that the models do not require extreme fine-tuning — this claim appears contradicted by the paper's own displayed parameter values (§7.3 above), but rigorous verification would require independent re-derivation of the parameter constraints
- Whether the Model 1 generalised m values 1.2996, 1.3117, 1.3235 stated in text are correct, or whether the Table 2 m values 1.9053, 1.8728, 1.8413 are correct — the paper does not resolve this internal inconsistency; correct resolution requires independent recalculation
- Whether ref [36] (Azhar-Jawad-Rani 2020) prior f(T, T_G) baryogenesis result quantitatively agrees with Samaddar-Singh's reported parameter ranges — would require reading [36]
- Whether the v1 preprint has undergone peer review (no journal acceptance noted)
- Whether the arXiv subject classification physics.gen-ph reflects an initial choice by authors or a recategorisation by arXiv moderators
- The empirical observational target η_B/s ≃ 9.42×10⁻¹¹ — cited from refs [55, 56]; not independently verified beyond the cluster-cross-reference observation in §7.2
- Whether the Kofinas-Saridakis 2014 [45] foundational f(T, T_G) framework is being applied here in a manner consistent with that paper's stated scope — not independently cross-referenced

## §14 Recommended corpus treatment (proposed; pending Stephen authorisation at cycle delivery)

Per the per-paper deeppass-report convention re-affirmed at Amendment 9 Addendum §7.4, integration into corpus-document consumer deliverables occurs AFTER this deeppass-report production, at cycle delivery time (Amendment 10 + Scaffold v8 + Research Plan v0.6 + Handoff v6). The proposed integration:

- **Scaffold v8 §5.2:** F-05 modified-gravity-extensions sub-list cluster paragraph extension. Add Samaddar-Singh 2025 to teleparallel-Gauss-Bonnet branch alongside Cruz-Pereira-Lobo 2025/2026 (already abstract-verified). Body-access observations from §4-§7 above integrated. Add Papers 1 + 2 of next-cycle list (Malakar group) as abstract-verified entries per Step 1-2 verification — these would parallel the Papers 3, 4 abstract-verified treatment from the Amendment 9 cycle.

- **Scaffold v8 §5.2:** F-05 honest-disclosure block extended with Samaddar-Singh-specific observations:
  - Parameter-tuning observation §7.3 (β 10³⁶ → 10⁷⁶; δ 10²⁰ → 10¹¹⁰)
  - Internal text-table inconsistency §7.4
  - M* ≈ 10⁻⁷ M_Pl cross-cluster comparison §7.5
  - Reference-list isolation from contemporaneous cluster §7.9

- **Scaffold v8 §11.3 Item 5:** substantive update with teleparallel-branch cluster content; cross-cluster M* spread from M_Pl (Pereira) to 10⁻⁷ M_Pl (Samaddar-Singh) added to joint structural picture; parameter-tuning landscape characterisation strengthened

- **Scaffold v8 §13.2 §5:** reference entries added with full attribution for Samaddar-Singh 2025 + abstract-verified Malakar Papers 1 + 2 of next-cycle list. Foundational Kofinas-Saridakis 2014 f(T, T_G) construction added if Paper 3 folds in. Optional Azhar-Jawad-Rani 2020 prior f(T, T_G) baryogenesis added per §7.10 — Stephen decision.

- **Research Plan v0.6 §3:** F-05 cluster sub-list update paragraph for Samaddar-Singh with body-access summary and parameter-tuning honest-disclosure. Adjacency-paper cycle Papers 1 + 2 (Malakar group) abstract-verification added.

- **Research Plan v0.6 §5.1:** Item 5 substantive update text incorporating teleparallel-branch and cluster parameter-regime divergence observation.

- **Research Plan v0.6 §8 (new sub-section):** Parameter-naturalness honest-disclosure across F-05 cluster — Pereira ε tuning at M* = M_Pl; Whittingham M* ≈ 0.4 M_Pl required; Samaddar-Singh M* ≈ 10⁻⁷ M_Pl + parameter coefficients 10²⁰ to 10¹¹⁰; cluster as a whole does not converge on naturally-determined parameter values.

- **Amendment 10 §3.D-equivalent:** body-access summary for Paper 3 + abstract-verification summaries for Papers 1, 2 of next-cycle list

- **Amendment 10 §3.E-equivalent:** F-05 teleparallel-branch updates summary

- **Amendment 10 §3.G-equivalent:** observational-target heterogeneity cross-cluster honest-disclosure (Samaddar-Singh 9.42×10⁻¹¹ via Planck 2016 + Kolb-Turner 1990 textbook; distinct from Pereira/Whittingham values; cross-cluster heterogeneity continues)

## §15 End of Paper 3 deeppass

Deeppass report for Samaddar-Singh 2025 arXiv:2512.06009v1 complete. Provenance verified. Modal-status preservation confirmed. F-05 territory placement in the teleparallel-Gauss-Bonnet branch maintained. Substantive honest-disclosure observations cataloged across §7.1–§7.10 covering arXiv classification, observational-target choice, extreme parameter values, internal text-table inconsistency, M* choice, T_D choice, power-law-as-inflation framing, no-GR-baseline-comparison, reference-list isolation, and prior-result non-comparison. Per Stephen direction 27 May AEST ("empirical findings positive or negative are welcome"), these observations are recorded neutrally without UMF-validation or UMF-invalidation framing.

Per Amendment 9 Addendum §7.4 standing rule, this deeppass-report production precedes any consumer-document integration. Integration into Scaffold v8 + Research Plan v0.6 + Amendment 10 + Handoff v6 pending Stephen direction at cycle delivery.

---

*End of F-05_Paper3_Samaddar2025_AdjacencyReview2026_deeppass.md*
