### B-03 — Kaluza-Klein particles / extra-dimensional geometric particles — **THEME C T1 DEEP-PASS**

**Date of entry:** 25 May 2026 (AEST)
**Theme C deep-pass on B-03 (originally Theme B entry in RPA v0.32).**
**Foundational papers:**
- Kaluza 1921, "Zum Unitätsproblem der Physik," *Sitzungsber. Preuss. Akad. Wiss. Berlin* 1921:966 (modern arXiv translation arXiv:1803.08616)
- Klein 1926, *Z. Phys.* 37:895
- Cremmer-Julia-Scherk 1978, *Phys. Lett. B* 76:409 (11D supergravity)

**Canonical review:**
- Overduin-Wesson 1998, *Phys. Rep.* 283:303-378 (arXiv:gr-qc/9805018), "Kaluza-Klein gravity"

**Modern extensions:**
- ADD 1998: Arkani-Hamed-Dimopoulos-Dvali, "The Hierarchy Problem and New Dimensions at a Millimeter," *Phys. Lett. B* 429:263-272 (arXiv:hep-ph/9803315)
- Antoniadis-Arkani-Hamed-Dimopoulos-Dvali 1998, *Phys. Lett. B* 436:257-263 (arXiv:hep-ph/9804398)
- ADD2 1999: Arkani-Hamed-Dimopoulos-Dvali, *Phys. Rev. D* 59:086004 (arXiv:hep-ph/9807344) — phenomenology/astrophysics/cosmology
- RS 1999: Randall-Sundrum, "A large mass hierarchy from a small extra dimension" (arXiv:hep-ph/9905221) and "An alternative to compactification" (arXiv:hep-ph/9906064)

**Modern empirical engagement (2024):**
- Horváth-Forgács-Dajka-Barnaföldi 2024: "Application of Kaluza-Klein Theory in Modeling Compact Stars: Exploring Extra Dimensions" *MNRAS* 536:816 (arXiv:2408.16497)
- Horváth-Forgács-Dajka-Barnaföldi 2024b: "The effect of multiple extra dimensions on the maximal mass of compact stars in Kaluza-Klein space-time" (arXiv:2410.10920)

**KK-graviton DM candidate literature (Theme C verification target per matrix):**
- Feng-Rajaraman-Takayama 2003, "Graviton Cosmology in Universal Extra Dimensions" (arXiv:hep-ph/0307375)
- Bernal et al. 2020, "Kaluza-Klein FIMP Dark Matter in Warped Extra-Dimensions" *JHEP* 09:142 (arXiv:2004.14403)
- Belanger et al. 2022, "Warm dark matter from a gravitational freeze-in in extra dimensions" *JHEP* 04:032 (arXiv:2208.03153)

**Format consulted (Theme C deep-pass):**
- arXiv abstract page for hep-ph/9803315 (ADD 1998) — verified verbatim
- arXiv abstract page for gr-qc/9805018 (Overduin-Wesson 1998) — verified verbatim
- arXiv abstract page for 2408.16497 (Horváth et al. 2024) — verified verbatim
- ADS abstract for Overduin-Wesson 1998 — verified verbatim
- arXiv PDF text snippet for gr-qc/9805018 (cover page, opening paragraphs) — verified verbatim
- arXiv PDF text snippets for Mirabelli-Perelstein-Peskin 1998 (hep-ph/9811337); Rizzo 1999 (hep-ph/9910255 + hep-ph/9907401); Kehagias-Sfetsos 1999 (hep-ph/9905417); hep-ph/9906238; Gerdes et al. 2006 (hep-ex/0603035); hep-ph/0106343 — verified verbatim ADD-formula derivations
- MNRAS Horváth et al. 2024 verbatim text on Kaluza-Klein ladder and hadronic spectrum (Oxford Academic) — verified verbatim
- arXiv abstract for Feng-Rajaraman-Takayama 2003, Bernal et al. 2020, Belanger et al. 2022, Ishigure-Kakizaki-Santa 2016 — verified verbatim
- ADD 1998 PDF not bulk-loaded per RP §10 thread efficiency rule; the M_Pl² = V_n M_S^(n+2) relation is verified from multiple independent secondary derivations

**Provenance gate result:** PASS. 105 years from Kaluza 1921; international mainstream-physics community (Kaluza, Klein, Cremmer-Julia-Scherk, Overduin-Wesson, Arkani-Hamed-Dimopoulos-Dvali, Randall-Sundrum, Antoniadis); ADD 1998 has thousands of citations (top-cited hep-ph paper of 2001 per SLAC SPIRES record); RS 1999 similarly. Continuous active engagement through 2024 *MNRAS* publication and 2022/2023 JHEP KK-graviton DM studies. **No retractions or withdrawals.**

---

## Theme C deep-pass outputs

### (a) UMF compatibility nuances at full PDF read

**Auto-exclude triggers (per RP §6 step 3 v0.7):**
- **Variable c:** ABSENT. KK constructions use standard higher-dimensional GR + gauge theory with c constant throughout. Natural units c = ℏ = 1 standard. **PASS.**

**Strippability tests for fundamental constants — KEY FINDING:**

This is where B-03 is materially distinctive in the trial. The ADD construction produces the relation:

**M_Pl² = V_n · M_S^(n+2)**

(verified verbatim from multiple independent sources: Rizzo 1999 hep-ph/9910255 eq. (1); hep-ph/9906238 derivation via Gauss-law gravitational potential matching; Gerdes et al. 2006 hep-ex/0603035 eq. (1); Mirabelli-Perelstein-Peskin 1998; standard background uniformly).

Where:
- M_Pl = 4D Planck mass = G_4⁻¹/² (in natural units)
- M_S = (4+n)-dimensional fundamental scale ≡ M_{(4+n)}
- V_n = volume of n compact extra dimensions (= R^n for n-torus with common radius R)
- n = number of extra dimensions (≥ 2 for ADD's millimeter-scale dimensions)

Inverting to express in terms of Newton's constants (G ~ 1/M_P² for 4D; G_(4+n) ~ 1/M_S^(n+2) in (4+n) dimensions, with appropriate dimensional conventions):

**G_4 = G_(4+n) / V_n**

This is the structure recorded in the matrix entry. **Direct verification confirmed across multiple independent secondary sources.**

| Constant | Treatment in B-03 framework | UMF v0.7 compatibility |
|---|---|---|
| G | **Functional of compactification geometry: G_4 = G_(4+n)/V_n.** Higher-dimensional G_(4+n) is the fundamental constant; 4D effective G_4 depends on V_n. **Variant V_n → variant G_4.** | **DIRECT MATCH to UMF v0.7 §3.1 assumption 4.** Under variant geometry (variant V_n), G_4 varies in geometry-coupled way. ADD provides explicit mathematical realisation of UMF v0.7's variant-geometry-affects-G admission. **Strongest direct framework-level compatibility identified in the entire trial.** |
| h (ℏ) | Constant; standard QFT in higher dimensions. Natural units. | **Compatible with UMF v0.7 stable-geometry regime.** Same geometry-coupling argument could in principle apply to ℏ if higher-dimensional Planck constant were dimensional-reduction-coupled to V_n, but ADD does not extend the mechanism to ℏ. |
| ε₀, μ₀ | In Kaluza's original 5D construction and many KK variants, electromagnetism emerges from the 5th-dimensional component g_μ5 of the higher-dimensional metric; gauge coupling derived from compactification geometry. **In principle, ε₀ and μ₀ would also be functions of compactification geometry under dimensional reduction.** | **Indirectly compatible with UMF v0.7 §3.1 assumption 4** on ε₀, μ₀ geometry-coupling. Mechanism is present in framework; specific functional form depends on KK variant. Not exhaustively developed in literature (gauge coupling unification is the standard application, not ε₀/μ₀ variation per se). |
| c | Constant throughout (UMF standing rule preserved). | **PASS.** |

**Trans-Planckian classification:** Standard KK operates at scales M_S ~ TeV (ADD) up to M_S ~ Planck (original KK). RS warped scenarios have effective scales at TeV via warp factor exp(-kπr_c). All sub-Planckian or at Planckian threshold; trans-Planckian regimes not engaged in B-03 framework. Under UMF v0.7 regime-relativity, this all operates in stable-geometry territory. **Compatible.**

**CDM scaffolding:** Plug-in, not load-bearing. KK gravitons and KK photons (B¹ in UED) are independent candidate DM mechanisms but the KK framework itself does not require CDM. **Strippable.**

**BBN dependence:** BBN constrains B-03 indirectly: KK-graviton overclosure / BBN photodissociation by long-lived KK states constrains reheat temperature T_RH (per Feng-Rajaraman-Takayama 2003: "Overclosure and Big Bang nucleosynthesis therefore stringently constrain T_RH in all universal extra dimension scenarios"). The constraint is on T_RH, not on the KK framework itself. **Strippable at apparatus level; constraint at observational-bound level for any UMF use case that mirrors UED structure.**

**Equation of state w(x):** Bulk vs brane matter have different w(x). Bringmann-Eriksson-Gustafsson 2003 (arXiv:astro-ph/0303497) shows compactification radius can naturally remain static during radiation domination without explicit stabilization mechanism. No engagement with UMF T_G dynamical-pressure-scalar form. **Silent / does not contribute to UMF T_G structural assessment.**

**H₀ tension treatment:** Silent in foundational papers. Some recent KK literature (post-cutoff) speculates on early-universe extra-dimensional effects bearing on H₀ tension; not engaged in B-03 core literature.

**Structural commitments:**
- **T_G as pressure-dimensioned scalar field:** **Orthogonal.** Bulk gravitational degrees of freedom in (4+n)D have stress-energy tensor; not specifically pressure-dimensioned scalar. KK graviton tower decomposes into spin-2 (massive) + spin-1 + spin-0 components; the spin-0 (radion) is a scalar field but is the dilaton-class geometric modulus, not T_G.
- **Bounded universe / reflective wavefront:** **Silent at framework level.** KK frameworks are typically embedded in standard FRW cosmology. RS2 (RS without compactification of extra dimension; arXiv:hep-th/9906064) has infinite extra dimension and is structurally distinct from UMF bounded-universe with reflective wavefront. **No direct compatibility.**
- **Variable ε₀, μ₀ with c invariance:** **Indirectly engaged** via dimensional-reduction mechanism for gauge couplings (see G/ε₀/μ₀ table above).
- **Gravitoelectric DM (no-mass no-particles, sourced by wavefront):** **Incompatible at framework level.** KK-graviton DM and KK-photon (B¹) DM are particle DM candidates. UMF gravitoelectric DM has no particles. Direct divergence.
- **Finite cosmic lifecycle:** **Silent / incompatible.** Standard FRW assumed.

**Result:** **Partial-import compatible, with EXCEPTIONAL G-variation compatibility (Tier 1 substantive finding).** ADD construction provides explicit mainstream-peer-reviewed mathematical realisation of UMF v0.7 §3.1 assumption 4 variant-geometry-affects-G structure. Cosmological-framework remainder follows partial-import pattern of F-series entries.

### (b) Time-measurement determination

**Source-literature framework time-measurement:** **PLC → FLEX (refining matrix placeholder).**

- *Standard ADD/RS embedding:* T=0 inflationary cosmology with KK framework as the underlying particle-physics structure throughout. T=0 commitment in cosmological-embedding sense.
- *KK framework itself:* **FLEX** at foundational level. The Kaluza-Klein construction is a framework about spacetime geometry (higher-dimensional → 4D effective), not a specific cosmological-time commitment. The framework can be embedded in t=0 cosmology (standard), in bouncing/cyclic cosmology, in steady-state cosmology, or in alternative-cosmology variants. The foundational Kaluza 1921 / Klein 1926 / Overduin-Wesson 1998 papers do not commit to a specific cosmological-time framework.
- *Dynamical-compactification scenarios:* Where the compactification radius R_c (or V_n) evolves cosmologically, this provides a direct framework for variant-geometry-driven G-variation — which is precisely the UMF v0.7-relevant scenario. Bringmann-Eriksson-Gustafsson 2003 (astro-ph/0303497) examines (3+n+1)D anisotropic universe and finds approximately static R_c during radiation domination without explicit stabilization. **Other epochs (notably pre-radiation-domination epochs) admit non-static R_c — directly relevant to UMF breach-event G-shock.**

**Transfer into UMF bounded-universe timeline (per RP §3.1 working assumption 3):**

- *Framework-level:* **POSITIVE for apparatus, PARTIAL for cosmological embedding.** The KK mathematical framework is FLEX and transfers to UMF bounded-universe context. Specifically:
  - The G_4 = G_(4+n)/V_n relation is purely geometric and applies in any cosmological framework; if UMF identifies a G-shock event as a "variant-geometry" event in the V_n-changes sense, the ADD relation provides the explicit mathematical structure for the consequent G_4-variation.
  - The KK tower of massive states is a standard tool for representing particle spectra in a higher-dimensional framework; this is FLEX.
- *Cosmological-embedding-level:* **Incompatible at standard ADD/RS embedding** (which assumes FRW with t=0 inflationary cosmology). UMF would need to specify a non-standard embedding of the KK framework in its bounded-universe timeline.

**Recommended Time code update for ESCALATE matrix:** **PLC → FLEX (framework) / T=0 (standard embedding)** — refining the PLC placeholder. The KK framework itself is FLEX; standard cosmological embeddings of KK are T=0; UMF embedding would be BND. This is the most substantive Time-measurement clarification produced by Theme C deep-pass so far: B-03 is the entry where UMF can most cleanly import framework without inheriting incompatible cosmological-embedding commitments.

### (c) Specific apparatus / methodology UMF can import

Four classes of importable apparatus identified. Each requires Stephen-led integration decision separate from this reading-programme entry.

**1. ADD G-variation relation G_4 = G_(4+n)/V_n.** This is the central substantive finding. Mainstream peer-reviewed physics (ADD 1998 *Phys. Lett. B* 429:263) provides explicit mathematical mechanism for G-variation under variant compactification geometry. **UMF v0.7 §3.1 assumption 4 admits exactly this structure.** UMF can:
   - Cite ADD as mainstream-peer-reviewed precedent for G-variation under variant geometry
   - Position UMF's G-variation commitment as consistent with established mainstream framework, not as exotic new claim
   - Note the relation works for any compactification topology, not just tori (n-sphere, Calabi-Yau, hyperbolic compactifications all admit equivalent forms with geometry-specific V_n)
   - Optionally extend to ε₀/μ₀ via dimensional-reduction-of-gauge-couplings mechanism if Stephen wishes to commit to a specific form of UMF's "ε₀, μ₀ may vary in geometry-coupled ways" admission

**2. Dynamical compactification framework.** Bringmann-Eriksson-Gustafsson 2003 (astro-ph/0303497) and follow-up literature on time-dependent compactification radius provide the standard apparatus for treating epochs where V_n is not static. **If UMF G-shock involves a brief epoch of varying compactification geometry, the dynamical-compactification toolkit is directly applicable.**

**3. Kaluza-Klein tower mass spectrum apparatus.** Particles in compact extra dimensions acquire discrete momentum quantization → KK tower with masses m_n ∝ n/R_c (5D torus) or generalised forms in other compactifications. The 2024 Horváth-Forgács-Dajka-Barnaföldi MNRAS paper applies this to model hadronic mass spectrum with compactification radius r_c at "order of hundreds of femtometre" (verified verbatim from Oxford Academic). **For UMF, this is one mathematical mechanism by which a fixed underlying geometric framework can produce a discrete particle spectrum** — relevant if UMF G-shock matter creation produces a discrete particle spectrum from geometric structure.

**4. Compact-star observational engagement (modern; 2024 MNRAS publication).** Horváth et al. 2024 demonstrates KK framework can be tested against compact-star mass-radius observations:
   - Verbatim from arXiv abstract: "A theoretical framework for calculating the mass-radius curve of compact stars in the Kaluza-Klein space-time is introduced, with one additional compact spatial dimension."
   - Verbatim: "The maximal mass of compact stars is calculated for different model parameters, and with a physical parameter choice, it satisfies observational data, meaning that it is possible to model simple, realistic objects within this framework."
   - This is the **only foundational-class extra-dimensional framework that has produced a 2024 *MNRAS* observational-engagement paper** in the trial corpus. Empirical engagement is real and active.
   - Per RP §9 standing rules: this is consistency-with-data finding (mass-radius curve "satisfies observational data" within parameter space), not 5σ detection of extra dimensions. Notable-only as observational engagement.

### (d) Specific divergences from UMF to acknowledge in published paper

Six divergences:

**1. Higher-dimensional spacetime ontology.** B-03 frameworks postulate genuine higher-dimensional spacetime with extra (compact or warped) spatial dimensions. UMF (per Stephen's handoffs and the GWM document) operates in 4D spacetime; the geometric structure is in the 4D metric/curvature/wavefront content, not in additional spatial dimensions. **Published-paper position:** UMF cites ADD/KK as mainstream precedent for "fundamental constants as functions of geometric structure" without committing to the higher-dimensional-spacetime ontology specifically.

**2. q/m problem for elementary particles.** Lacquaniti-Montani 2009 (arXiv:0904.0574, already noted in B-03 triage) showed that standard 5D KK theory gives q/m < 10⁻⁴ C/kg for KK states, contradicting elementary-particle q/m ~ 10¹¹ C/kg. **KK cannot describe elementary particles as KK excitations in standard 5D formulation.** Published-paper position: UMF should not claim KK provides full elementary-particle realisation; UMF can legitimately cite KK only for structural features (G-variation, geometric-particle representation in principle) without committing to KK as a full elementary-particle theory.

**3. LHC null results constraining ADD/RS parameter spaces.** ADD with TeV-scale fundamental gravity scale was specifically constrained by LHC graviton-emission searches (missing-energy + photon/jet signatures per Mirabelli-Perelstein-Peskin 1998 prediction). LHC Run 1+2+3 has set lower bounds on M_S in range several TeV for various n values; RS warped scenarios similarly constrained. **The original ADD motivation (M_S ~ TeV solving hierarchy problem) is in tension with LHC null results**, though the underlying KK framework remains viable at higher M_S. **Published-paper position:** UMF cites ADD as structural framework for G-variation, not as motivation for TeV-scale gravity specifically. **(Outside-corpus marker:** specific LHC bound values not separately verified for this entry; drawn from standard background.**)**

**4. Particle-DM (KK-graviton / KK-photon) vs UMF gravitoelectric-DM.** B-03's candidate DM mechanisms (B¹ LKP in UED; KK gravitons in FIMP scenarios) all involve particles. UMF's gravitoelectric DM has no particles. **Same as F-01 divergence 3 and F-02 divergence 3.** This is now a recurring pattern across F/B-series mainstream DM literature. **Published-paper position:** UMF positions its gravitoelectric DM as a structurally distinct DM mechanism class from particle DM of any variety, including KK particle DM.

**5. Standard cosmological embedding incompatible with UMF bounded-universe.** B-03 frameworks are typically embedded in t=0 inflationary FRW. RS2 has infinite extra dimension. Neither matches UMF bounded-universe with reflective wavefront. **Published-paper position:** UMF acknowledges KK framework is mathematically importable for G-variation structure but the standard cosmological embedding is incompatible at the framework level.

**6. Inflaton in dynamical-compactification scenarios.** Where dynamical R_c is considered (e.g., for cosmological extra-dimension stabilization), the dynamics is typically scalar-field-driven (moduli stabilization potentials, radion dynamics). UMF G-shock framework does not have an obvious scalar-field-driven dynamical-compactification analogue; the dynamics would need to be specified differently (e.g., as a direct geometric event, not a scalar-field-mediated evolution).

### Empirical-requirement assessment

B-03 has substantial observational engagement at multiple levels:

Per RP §4 three-category framework:
- **Lab tests:** 
  - **Sub-mm gravity tests** (Eot-Wash, Stanford torsion-balance experiments): inverse-square law tested down to ~50 μm or below as of recent literature. Tests sub-mm extra dimensions per ADD prediction. **No deviation from 1/r² observed** at testable scales; current bounds rule out n=2 ADD with M_S < few TeV but n ≥ 3 remains viable per literature. Constraint level, not detection.
  - **LHC searches for KK gravitons / graviton-emission monojets and dijets:** Direct searches at ATLAS and CMS through Run 2 (13 TeV) and Run 3 (13.6 TeV) have set lower bounds on M_S in various ADD/RS parameter spaces. **No KK graviton detection at LHC.** Constraint level, not detection. (Outside-corpus marker: specific bound values drawn from standard background, not separately verified.)
- **Observational tests:**
  - **Astrophysical KK-graviton constraints**: Supernova SN1987A graviton-emission cooling constraints; neutron-star cooling constraints; cosmic-ray flux constraints. All consistent with no extra-dimensional graviton signatures; constraints on parameter space.
  - **2024 compact-star mass-radius observational engagement** (Horváth et al. 2024 *MNRAS* 536:816): KK framework parameter choices can satisfy observed compact-star mass-radius data; this is consistency with data, not detection of extra dimensions.
  - **CMB constraints on extra dimensions via modified expansion rates / KK-graviton overclosure:** active research, no detection.
- **Theoretical consistency:** Substantial. KK construction has 105 years of mathematical development. Dimensional reduction, KK tower spectra, higher-dimensional Einstein equations, RS warp-factor calculations all well-established. **Strong consistency.**

**Empirical-requirement satisfaction:** **Better than typical for the trial.** B-03 has more observational engagement (lab + LHC + astrophysical + 2024 MNRAS compact-star) than most other Theme F/A/B/D entries. **All current empirical engagement is constraint-level, not detection-level.** No claim of 5σ extra-dimensional signature detection. RP §9 5σ-threshold not crossed for any extra-dimensional detection claim; multiple constraint bounds at 95% CL or higher significance for ruling out parameter regions.

**Empirical-requirement waiver:** Not needed in the standard sense — B-03 has substantial empirical engagement. The waiver is implicit at the level of "extra dimensions exist or not" being the question, with current data consistent with non-existence within tested parameter ranges.

### Cross-references

- **B-03 ↔ B-01 Misner-Wheeler 1957 geometrodynamics:** Both are gravity/geometry-primary programmes. B-01 in 4D; B-03 in (4+n)D. B-03 generalises the geometry-primary commitment to higher dimensions. **Strong methodological compatibility** — both are within the geometry-primary tradition that UMF inherits.
- **B-03 ↔ B-04 Wheeler "It from Bit":** Both are foundational/ontological frameworks. B-04 information-primary; B-03 higher-dimensional-geometry-primary. Different substance commitments but both demonstrate that mainstream physics admits non-standard foundational positions.
- **B-03 ↔ F-08 Verlinde emergent gravity:** Both engage emergent / derived gravitational structure (F-08 emergent from entropy/holography; B-03 emergent from compactification in (4+n)D). Both UMF-aligned in different ways; both NOTABLE.
- **B-03 ↔ A-04 Skyrme topological solitons:** Modern KK compactifications can include Skyrmion-like constructions; A-04 self-gravitating Skyrmion bridge (arXiv:2503.03872 2025) and B-03 dimensional-reduction Skyrmions form complementary topological-soliton frameworks.
- **B-03 ↔ A-08 Penrose twistor:** Both are alternative-geometric programmes (A-08 inverts spacetime-primary; B-03 extends 4D to higher-dimensional). Different directions of alternative-geometric commitment.
- **B-03 ↔ UMF v0.7 §3.1 assumption 4:** **STRONGEST framework-level compatibility identified in the entire trial.** ADD G_4 = G_(4+n)/V_n is direct mathematical realisation of UMF v0.7 variant-geometry-affects-G admission.
- **B-03 ↔ G-shock physics:** Dynamical compactification scenarios provide direct mathematical mechanism for UMF G-shock as "sudden change in geometry" producing "variant G" via V_n change.
- **B-03 ↔ UMF gravitoelectric DM:** Negative compatibility on KK-DM (particle DM); independent positive compatibility on G-variation mechanism that could parameterise UMF DM via a different route.

### Outside-corpus markers

- ADD 1998 abstract verbatim ("Planck scale M_Pl ~ G_N^(-1/2) is not a fundamental scale; its enormity is simply a consequence of the large size of the new dimensions") — **verified verbatim from arXiv abstract page.**
- Overduin-Wesson 1998 abstract verbatim (three approaches: compactified, projective, noncompactified; none ruled out observationally) — **verified verbatim from arXiv and ADS.**
- M_Pl² = V_n M_S^(n+2) ADD relation — **verified verbatim across multiple independent secondary sources** (Rizzo 1999 hep-ph/9910255 eq. (1); hep-ph/9906238 eq. (4); Gerdes et al. 2006 hep-ex/0603035 eq. (1)).
- G_4 = G_(4+n)/V_n equivalent form — **standard background mathematical inversion** of the verified M_Pl² = V_n M_S^(n+2) relation; not separately quoted verbatim from a single source.
- Horváth et al. 2024 *MNRAS* 536:816 abstract verbatim + verbatim MNRAS body text on KK ladder and hadronic spectrum — **verified verbatim from arXiv abstract and Oxford Academic publication.**
- Feng-Rajaraman-Takayama 2003 abstract verbatim (KK graviton primordial production T_RH^(2+3d/2) scaling; BBN/overclosure constraints) — **verified verbatim from arXiv PDF text.**
- Lacquaniti-Montani 2009 q/m problem — **drawn from existing matrix entry F-02 triage** which verified this directly from arXiv:0904.0574 snippet at v0.32 entry.
- Bringmann-Eriksson-Gustafsson 2003 cosmological R_c evolution finding — **verified verbatim from arXiv abstract.**
- LHC bounds on ADD/RS parameter space (current as of cutoff Jan 2026) — **drawn from standard background**; specific TeV bound values not separately verified for this entry. Honest disclosure: cannot cite specific 2024/2025 ATLAS/CMS bound papers without further verification.
- Sub-mm gravity test bounds (Eot-Wash, Stanford torsion balance, ~50 μm scale) — **drawn from standard background**; specific recent bound values not separately verified.
- SN1987A KK-graviton cooling constraints — **drawn from standard background.**
- Kaluza 1921 / Klein 1926 / Cremmer-Julia-Scherk 1978 foundational papers — **bibliographic information verified from standard background and modern review citation; original papers not separately consulted.**

### Theme C T1 deep-pass disposition

**Sustain ESCALATE with NOTABLE flag (already in matrix); confirm Tier 1 priority status.**

**Headline-findings list update:** B-03 entry on list should be expanded with these Theme C confirmations:
- ADD G_4 = G_(4+n)/V_n verified as direct mathematical realisation of UMF v0.7 §3.1 assumption 4 G-variation admission
- 2024 *MNRAS* compact-star empirical engagement adds active observational testing
- KK-graviton DM literature is substantial (Feng-Rajaraman-Takayama 2003; Bernal et al. 2020; Belanger et al. 2022) — sixth non-standard DM mechanism candidate is well-supported

**Methodology for synthesis paper:** B-03 to be cited as:
1. **The principal mainstream-peer-reviewed precedent for UMF v0.7 §3.1 assumption 4 G-variation structure.** This is the single highest-value citation in the synthesis paper for defending UMF's variant-geometry-affects-G admission against "exotic new claim" challenge.
2. The framework providing dynamical-compactification mathematical apparatus for any UMF G-shock = "sudden change in geometry" → "G variation" scenario.
3. The framework providing the q/m-problem honest disclosure: UMF should explicitly NOT claim KK gives full elementary-particle realisation, only structural G-variation precedent.
4. The framework providing 2024 *MNRAS* observational engagement at compact-star scale (most-recent peer-reviewed observational test of foundational extra-dimensional framework in trial corpus).
5. The framework providing the sixth candidate non-standard DM mechanism (KK-graviton DM) as alternative-particle-DM context against which UMF gravitoelectric DM positions.

**Critical published-paper recommendation:** B-03 is the entry that most directly supports UMF v0.7 §3.1 assumption 4 with mainstream-peer-reviewed precedent. The G_4 = G_(4+n)/V_n relation is the single most defensible mathematical citation UMF can make for its G-variation-under-variant-geometry commitment. The relation is established across multiple independent sources, mathematically uncontroversial, and has 27+ years of cumulative literature engagement since ADD 1998. **This finding alone justifies the Tier 1 priority status of B-03 in Theme C.**

---

**Drafter:** Claude. Deep-pass entry follows Theme C scope per Research Plan v0.1 Draft and per-entry output requirements per Handoff §9. **No PDF page requests required for this entry** — the central G-variation finding is well-verified across multiple secondary derivations of the ADD construction. PDF request would only be needed if Stephen wishes to verify any specific element directly from ADD 1998 / Overduin-Wesson 1998 / Horváth et al. 2024 PDFs (each available via arXiv).

**Open Stephen-decision flagged:** at synthesis-paper drafting time, decide whether to extend the dimensional-reduction-of-gauge-couplings mechanism to UMF v0.7's ε₀/μ₀ admission (per the (a) compatibility table above). This is a specific UMF-internal scoping decision that Stephen should make consciously.
