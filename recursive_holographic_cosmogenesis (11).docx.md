  
**RECURSIVE HOLOGRAPHIC COSMOGENESIS**

*Density-Dependent Mirror Formation, T-Duality Mechanism,*

*and a Falsifiable Dark Energy Equation of State*

Lee Hansen

February 2026

**WORKING PAPER**

© 2026 Lee Hansen

Licensed under the GNU Affero General Public License v3.0 (AGPL-3.0)

https://www.gnu.org/licenses/agpl-3.0.html

# **Abstract**

We develop a framework for recursive holographic cosmogenesis in which black hole interiors generate daughter spacetimes through density-dependent topological transitions at holographic boundaries. We identify a physical mechanism for the transition: BKL ultralocality eliminates classical bounce at the singularity, and T-duality maps continued compression into expansion in a temporally reversed dual dimension—with the compactification required by T-duality provided by the collapsing geometry itself, not imported as an external assumption. CPT invariance motivates a reversed temporal orientation in the daughter spacetime. The BKL billiard dynamics and T-duality share the modular group SL(2,ℤ) as a common symmetry, and the fractal structure of the billiard trajectory organizes recursive mirror production across scales. The mirror formation process is formalized via cobordism theory, and we note that exotic smooth structures on 4-manifolds suggest a possible mechanism for variation of effective physical constants across generations, though this connection remains conjectural. We derive a continuous mirror formation rate Γ \= (1/t\_P)(ρ\_local/ρ\_P)^α, with α \= 1 motivated by Hawking–Page mean-field scaling, and show that gravitational, cosmological, and horizon frequency shifts are unified as manifestations of a single rate field. We interpret cosmological expansion as the transverse signature of an underlying gravitational compression in a black hole interior, with the observed accelerating expansion reflecting the rate of approach to the de Sitter mirror boundary. We derive a prediction for the dark energy equation of state w(z) that departs from w \= −1, with a specific rational functional form testable by DESI (combined with CMB and supernova datasets), Euclid, and Roman. The framework replaces two unexplained features of standard cosmology—the initial singularity and the cosmological constant—with a single mechanism: gravitational compression producing daughter spacetimes through T-duality at the mirror boundary.

# **Contents**

# **1\. Introduction**

The proposal that black hole interiors may generate new spacetime regions has a substantial pedigree. Pathria[^1] suggested that our universe may be a black hole interior. Frolov, Markov, and Mukhanov[^2] developed a model replacing the singularity with a de Sitter core giving rise to a baby universe. Smolin[^3] formalized cosmological natural selection, proposing that black holes produce daughter universes with mutated physical constants. Poplawski[^4] showed that Einstein–Cartan gravity with torsion produces a bounce inside black holes generating expanding regions resembling Big Bang cosmologies.

This paper contributes four extensions. First, we formalize the parent-to-daughter transition using cobordism theory, noting that non-unique smooth structures on 4-cobordisms suggest a possible (but unproven) mechanism for variation of physical constants. Second, we identify a physical mechanism for the transition: BKL ultralocality prevents quantum bounce at point-like singularities, and T-duality maps continued compression into expansion in a temporally reversed dual dimension. Third, we replace discrete cosmogenesis with a continuous rate equation. Fourth, we show that this rate field produces observable signatures—specifically, that the dark energy equation of state w(z) carries a specific imprint of the rate field’s evolution, whose qualitative direction is consistent with the mild preference for evolving dark energy reported by recent DESI BAO data combined with external CMB and supernova datasets.

We also address whether mirror formation extends below the astrophysical Planck regime. Using results from asymptotic safety, we show that the effective Planck density is scale-dependent. We map the conditions under which sub-Planckian mirror formation could occur without claiming it is realized—that requires computations not yet performed.

# **2\. Holographic Foundations**

## **2.1 Holographic Principle and Entropy Bounds**

The Bekenstein–Hawking formula[^5] establishes S\_BH \= k\_B A/4ℓ\_P². The holographic principle[^6], realized through AdS/CFT[^7], establishes that (d+1)-dimensional gravity is equivalent to a d-dimensional CFT on its boundary. The Bousso bound[^8] constrains information content to A/4ℓ\_P² bits. These results establish the mathematical prerequisite: holographic boundaries can encode complete bulk physics.

## **2.2 The Mirror Map via Cobordism**

***Definition 2.1 (Mirror Map).*** Let (M, g, T) be a Lorentzian manifold. Let Σ ⊂ M be a closed spacelike 2-surface where ρ\_local ≥ ρ\_P(k). The mirror map Φ\_Σ consists of: (i) Boundary encoding of induced data as |CFT(Σ)⟩ via AdS/CFT, subject to S(Σ) ≤ A/4ℓ\_P². (ii) Topological transition via cobordism W with ∂W \= Σ ∪ Σ′, satisfying the dominant energy condition. In 4D, non-unique smooth structures on W[^9][^10] yield different effective physics in daughter spacetimes. (iii) Initial data generation satisfying the GR constraint equations on Σ′. The daughter spacetime M′ is the maximal Cauchy development.

Recursive application generates a spacetime tree T \= {U₀, Φ₁(U₁), ...}. The Kerr metric’s[^11] maximal analytic extension provides classical precedent: it contains an infinite sequence of spacetime regions connected through the ring singularity, with reversed time orientation in alternating regions—a structural feature whose significance we return to in Section 2.3.

## **2.3 Physical Mechanism: T-Duality and BKL Ultralocality**

Definition 2.1 specifies the mathematical structure of the mirror map but leaves the physical mechanism underdetermined. We now argue that two established results—T-duality in string theory and BKL ultralocality in general relativity—provide the mechanism.

The standard assumption in quantum gravity is that Planck density constitutes a floor: compression reaches ρ\_P and bounces. Loop quantum gravity produces an explicit bounce via holonomy corrections to the Hamiltonian constraint. Asymptotic safety softens the singularity into a de Sitter core. These quantum bounce mechanisms operate through modified dynamics at high curvature and do not require spatial communication. However, they represent one class of singularity resolution. We propose an alternative: in the BKL ultralocal regime, classical bounce mechanisms (pressure rebound, equation-of-state stiffening) cannot operate, and T-duality provides a geometrically distinct completion—not a bounce but a dimensional transmutation—that makes different observational predictions.

**BKL ultralocality.** The BKL conjecture[^12]—now substantially proven for broad classes of spacetimes—establishes that near a spacelike singularity, spatial derivative terms in the Einstein equations become negligible relative to temporal derivatives. Each spatial point evolves independently: the dynamics become ultralocal. The physical consequence is that classical bounce mechanisms—which require spatial structure to push against, neighboring points communicating to generate a pressure gradient—cannot operate. In the BKL regime, they cannot communicate. Classical rebound is eliminated. Compression at each point continues independently past the Planck threshold. Quantum corrections (LQG holonomy, asymptotic safety running) may still modify the dynamics, but T-duality provides an alternative geometric completion that does not invoke a bounce at all: it maps the compression directly to expansion in a dual dimension.

**T-duality as dimensional mirroring.** In string theory, a spatial dimension compactified on a circle of radius R exhibits an exact duality[^13]:

          *R → α′ / R*(T)

where α′ \= ℓ\_s² is the string length squared. Every physical observable computed at radius R equals the corresponding observable at radius α′/R. Winding modes in the small dimension become momentum modes in the large dual dimension, and vice versa. This is not an approximation but an exact equivalence. Compression below the string scale does not produce a bounce—it produces an equivalent expanding dual dimension. The floor is not a wall; it is a mirror.

**Compression as compactification.** A potential objection is that T-duality, as established in string theory, requires a genuinely compactified dimension with winding modes and worldsheet formalism. We do not import compactification as an external assumption. In a collapsing interior geometry—which the present framework identifies with the physical universe—every spatial dimension undergoes compactification as a physical process. The BKL regime makes this ultralocal: each spatial point compresses independently, with spatial dimensions shrinking toward zero radius. T-duality therefore operates not by analogy with string compactification but as a consequence of the same geometric process: a dimension physically shrinking past a critical scale produces an equivalent expanding dual. The compact S¹ that T-duality requires is provided by the collapsing geometry itself. The Kerr interior provides the explicit example: the angular coordinate is an S¹ that compresses as the ring singularity is approached, providing the compact dimension on which T-duality acts. In the BKL regime, this structure generalizes—every spatial direction at every point undergoes independent compression, each providing a potential T-duality channel.

**Combined mechanism.** At an ultralocal point approaching a singularity (BKL regime), spatial derivatives vanish and no bounce operates. As any dimension compresses past the critical scale, T-duality maps the compression to expansion in a dual dimension. Information is preserved: winding modes encode the same data as the original momentum modes. The mirror map of Definition 2.1 is identified with this T-duality transformation: step (i), boundary encoding, corresponds to the winding-momentum exchange that conserves information across the duality; step (ii), the topological transition, is the T-duality map connecting the contracting manifold to the expanding dual; step (iii), initial data generation, inherits its data from the T-dual fields, automatically satisfying the constraint equations because T-duality is an exact symmetry.

**Temporal reversal and CPT structure.** The T-duality map does not merely create an expanding dual dimension. CPT invariance—the requirement that physical laws are unchanged under simultaneous charge conjugation, parity inversion, and time reversal—motivates a reversed temporal orientation in the daughter spacetime: if the T-duality map exchanges winding and momentum modes (a parity-like transformation on the compact dimension) while preserving the overall CPT symmetry, the dual spacetime naturally inherits a reversed time orientation. This is not an automatic consequence of CPT alone but a consistency condition: the combined transformation across the duality must preserve CPT as a symmetry. The Kerr interior[^14] provides independent structural confirmation: alternating spacetime regions in its maximal analytic extension exhibit reversed time orientation. Damour, Henneaux, and Nicolai[^15] showed that BKL oscillations near a singularity exhibit hidden symmetry: the chaotic Kasner transitions map onto a massless particle bouncing off the walls of a hyperbolic billiard table whose walls correspond to spatial dimensions. Each billiard reflection changes which dimension is contracting and which is expanding—a sequence of dimensional mirrorings cycling through the available degrees of freedom. Combined with T-duality, each compression event produces an expanding dual whose temporal orientation is reversed relative to the parent—consistent with CPT invariance across the transition.

**Fractal compactification and the modular group.** The BKL Kasner transitions are not merely chaotic—they follow the Gauss map x → {1/x} (fractional part), which generates continued fraction expansions with self-similar fractal structure at every scale. The billiard trajectory in the Lobachevsky (hyperbolic) plane never repeats, fills the space ergodically, and exhibits sensitive dependence on initial conditions. Each wall hit is a discrete compactification event—a T-duality mirror firing—and the trajectory between hits is the continuous evolution of anisotropy. The fractal structure of the full trajectory means that mirror production is self-similar across scales, directly implementing the recursive structure of the spacetime tree (Section 2.2). A deeper connection exists: the T-duality group for a single compact dimension is the modular group SL(2,ℤ), generated by R → α′/R and discrete shifts. The Gauss map that governs BKL Kasner transitions also generates SL(2,ℤ) through its continued fraction structure. Billiard dynamics and T-duality therefore share the same underlying symmetry group. The billiard trajectory is a path through the space of T-duality transformations, and the fractal geometry of that path organizes the mirror spectrum—producing structured complexity rather than noise.

This temporal reversal is not incidental but structural. Wheeler’s one-electron hypothesis[^16] identified the positron as an electron moving backward in time. Within the T-duality mechanism, each mirror reflection naturally produces a temporally reversed dual—precisely the structure required for the particle-antiparticle symmetry observed in nature. Brandenberger and Vafa[^17] applied T-duality to cosmology, showing it can explain the initial conditions of Big Bang expansion from a prior contracting phase. Their mechanism is a specific instance of the general process described here: compression producing expansion via the duality map.

# **3\. Continuous Mirror Formation**

Previous models treat daughter universe formation as discrete. We propose it is continuous, motivated by the dynamical nature of horizons demonstrated by Hawking radiation[^18]. The mirror formation rate:

          *Γ(x) \= (1/t\_P) × (ρ\_local(x) / ρ\_P)^α*(1)

where t\_P ≈ 5.39 × 10⁻⁴⁴ s, ρ\_P ≈ 5.16 × 10⁹³ kg/m³, and α is a critical exponent of order unity. At ρ\_local \= ρ\_P: Γ \= 1/t\_P (Planck rate). At ρ\_local \<\< ρ\_P: the rate is suppressed. This defines a scalar field Γ(x) over spacetime—the local cosmogenesis rate—determined entirely by local energy density and gravitational coupling.

**The value α \= 1\.** The critical exponent α controls how sharply mirror formation turns on as density approaches the Planck threshold. We argue that α \= 1 (linear scaling) is the natural value, drawing on the Hawking–Page phase transition in AdS gravity[^19]. The Hawking–Page transition is a first-order thermal phase transition between thermal AdS (no black hole) and the AdS–Schwarzschild black hole at a critical temperature T\_HP. Near the transition, the free energy difference scales linearly with the control parameter: ΔF ∝ (T − T\_HP). The rate of black hole nucleation therefore scales linearly with departure from the critical point. In our framework, the mirror formation process is the holographic dual of this nucleation: the density ρ\_local plays the role of the thermal control parameter, and ρ\_P plays the role of the critical threshold. Linear scaling of the rate with the control parameter (α \= 1\) is then the standard mean-field critical behavior near a first-order transition. Higher values of α would correspond to higher-order transitions or anomalous scaling dimensions, which would require additional dynamical justification. We adopt α \= 1 as the simplest physically motivated choice while acknowledging that a first-principles derivation from the full quantum gravity partition function remains an open problem.

# **4\. Scale-Dependent Gravity and the Effective Planck Threshold**

## **4.1 Asymptotic Safety and Running G**

The asymptotic safety program[^20][^21] establishes that Newton’s constant runs with energy scale:

          *G(k) \= G₀ / (1 \+ ω G₀ k²)*(2)

Bonanno and Reuter[^22] showed that an RG-improved Schwarzschild metric replaces the singularity with a de Sitter core—precisely supporting daughter spacetime formation. They applied running G to early-universe cosmology[^23], showing the Planck era is modified by scale dependence.

## **4.2 Scale-Dependent Planck Density**

Since ρ\_P \= c⁵/(ħG²), running G yields:

          *ρ\_P(k) \= ρ\_P(0) × (1 \+ ω G₀ k²)²*(3)

The physically relevant ratio is R(k) \= ρ(k)/ρ\_P(k). Both numerator and denominator run with k. If quantum corrections to the stress-energy tensor grow faster than the Planck density rises, R(k) can approach unity even when the naive ratio is small.

For astrophysical black holes, R(k) ≈ 1 near the core. The rate equation reduces to Γ ≈ 1/t\_P. The new content is the smooth rate dependence along the infall trajectory.

## **4.3 The Sub-Planckian Window**

At nuclear scales (ρ\_nuc ≈ 2.3 × 10¹⁷ kg/m³), the naive ratio R ≈ 10⁻⁷⁶. Two effects could modify this.

First, the Tolman relation[^24] establishes that locally measured energy density is frame-dependent: ρ\_local \= γ²ρ\_external. While gravitational time dilation at nuclear scales is negligible classically, the question of whether effective gravitational phenomena at the nuclear scale—suggested by holographic QCD models mapping confinement to an AdS horizon—could contribute to ρ\_local remains open. We note this connection without claiming it implies literal spacetime curvature: that would require a derivation from full quantum gravity that does not yet exist.

Second, \~98% of hadronic mass is QCD binding energy that genuinely gravitates. At the hadronic scale this is negligible compared to the strong force, but in any theory where G runs, its significance changes with scale. We identify this as a parametric possibility: if G(k) runs sufficiently at nuclear scales, R(k) could be significantly closer to unity. Lattice quantum gravity calculations at hadronic scales can test this.

# **5\. Frequency Shifts as Rate Field Signatures**

## **5.1 The Master Frequency Relation**

A photon emitted at x\_emit and observed at x\_obs has:

          *f\_obs / f\_emit \= Γ(x\_emit) / Γ(x\_obs)*(4)

This is not an independent postulate but a restatement of gravitational redshift in terms of the rate field. The standard result f\_obs/f\_emit \= √(g\_tt(emit)/g\_tt(obs)), confirmed by Pound–Rebka[^25], relates frequency to local clock rates. Since Γ(x) ∝ ρ\_local (Eq. 1), and ρ\_local relates to g\_tt via the Tolman relation, Eq. 4 is a consequence of GR. The interpretive content is that frequency shifts are signatures of differential cosmogenesis rates.

## **5.2 Cosmological Redshift and Interior Geometry**

Inside a black hole, the radial coordinate becomes timelike[^26]. In Painlevé–Gullstrand coordinates[^27], spatial slices expand transversely while compressing radially. An interior observer—which, in this framework, we are—measures Hubble-like expansion in the transverse directions while the actual geometry is collapsing toward the singularity (or, in the T-duality picture, toward the mirror boundary). The observed cosmological expansion is the transverse signature of an underlying compression.

This reframing dissolves the dark energy puzzle. In standard cosmology, accelerating expansion requires a mysterious repulsive energy whose physical origin is unexplained. In interior geometry, the ‘acceleration’ is the increasing rate at which the geometry approaches its de Sitter attractor—the mirror boundary. No repulsive force is needed. The interior geometry relaxes toward its final state, and the rate of relaxation increases as the attractor is approached. What we measure as w(z) departing from −1 is the signature of this approach. Gravity—which is purely attractive—drives the compression, and the apparent acceleration is a consequence of the interior observer’s perspective on that compression.

Cosmological redshift records Γ’s temporal evolution:

          *1 \+ z \= Γ(t\_emit) / Γ(t\_obs)*(5)

The discovery of accelerating expansion[^28][^29] is reinterpreted: the rate field evolves as the interior geometry approaches its future mirror boundary, and the rational form of w(z) derived in Section 6 is the quantitative expression of this approach. The framework thus replaces two unexplained features of standard cosmology—the Big Bang initial singularity and the cosmological constant—with a single mechanism: gravitational compression producing daughter spacetimes through T-duality at the mirror boundary.

# **6\. Prediction: Dark Energy Equation of State**

## **6.1 Derivation of w(z)**

Recent DESI BAO data, when combined with CMB (Planck) and supernova datasets[^30], show a mild preference for evolving dark energy over ΛCDM (note: DESI BAO alone is consistent with ΛCDM within uncertainties; the evolving-DE signal is combination-dependent). Our framework predicts a specific w(z). We now derive it step by step from the rate field through the Friedmann equations.

**Step 1: Effective energy density.** The mirror formation rate Γ(x) \= (1/t\_P)(ρ\_local/ρ\_P)^α defines a scalar field over spacetime. To enter the Friedmann equations, we identify the effective energy density associated with the cosmogenesis process. In the FLRW limit, the rate field is spatially homogeneous and depends only on cosmic time. We define:

          *ρ\_Γ(a) ≡ ρ\_P × \[Γ(a) t\_P\]^(1/α) \= ρ\_local(a)*(6)

This is a tautology by construction—the effective density is the local energy density that sources the rate field. The physical content enters through the time dependence of ρ\_local(a) inside a black hole interior.

**Step 2: Interior density evolution.** For a black hole interior approaching its de Sitter core (as in the RG-improved Schwarzschild metric of Bonanno–Reuter), the effective density evolves as:

          *ρ\_Γ(a) \= ρ₀ \+ Δρ (a\_mirror / a)²*(7)

where ρ₀ is the asymptotic de Sitter density (playing the role of the cosmological constant), Δρ is the excess density from the approach to the mirror boundary, and a\_mirror is the scale factor at which mirror formation dominates. At late times (a \>\> a\_mirror), ρ\_Γ → ρ₀ and the evolution mimics ΛCDM. At early times (a \~ a\_mirror), the Δρ correction becomes significant.

The a⁻² scaling of the correction term has a specific physical origin. In the RG-improved Schwarzschild interior of Bonanno and Reuter, the de Sitter core is not reached instantaneously—the metric interpolates between the Schwarzschild-like regime and the asymptotic de Sitter state. The approach to the de Sitter core is governed by the curvature of the effective potential, which scales as the spatial curvature term k/a² in the Friedmann equation. More precisely: near the de Sitter core, the dominant sub-leading correction to constant vacuum energy is anisotropic shear, which dilutes as a⁻² in an expanding FLRW background (faster than matter at a⁻³, slower than radiation at a⁻⁴). This is a standard result in Bianchi cosmology—shear energy density σ² ∝ a⁻⁶ appears with an a⁻² effective contribution to the Friedmann equation through the combination σ²/H². The a⁻² scaling is therefore not an arbitrary choice but reflects the leading anisotropic correction as an interior geometry relaxes toward its de Sitter attractor. Alternative scalings (a⁻³, a⁻⁴) would correspond to matter-dominated or radiation-dominated corrections and would produce different w(z) functional forms, providing additional testable distinctions.

**Step 3: Continuity equation and equation of state.** Any effective fluid in FLRW cosmology satisfies the continuity equation:

          *dρ\_Γ/dt \+ 3H(1 \+ w)ρ\_Γ \= 0*(8)

Substituting ρ\_Γ(a) from Eq. 7 and using dt \= da/(aH):

          *w(a) \= −1 − (1/3) (a/ρ\_Γ) dρ\_Γ/da*(9)

Evaluating the derivative:

          *dρ\_Γ/da \= −2 Δρ a\_mirror² / a³*(10)

Therefore:

          *w(z) \= −1 \+ (2/3) Δρ(1+z)² / \[ρ₀ \+ Δρ(1+z)²\]*(11)

where we used a\_mirror/a \= (1+z)/(1+z\_mirror) and absorbed the z\_mirror dependence into Δρ for notational clarity.

**Step 4: Friedmann equation.** The full Friedmann equation with the rate-field fluid is:

          *H²(z) \= H₀² \[Ω\_m(1+z)³ \+ Ω\_Γ(z)\]*(12)

where Ω\_Γ(z) \= ρ\_Γ(z)/ρ\_crit. This is a standard dark energy model with a specific, derived w(z) rather than a phenomenological parametrization.

At low z (Δρ(1+z)² \<\< ρ₀): w → −1 \+ O(Δρ/ρ₀), recovering ΛCDM. At high z (Δρ(1+z)² \>\> ρ₀): w → −1 \+ 2/3, a quintessence-like regime. This falls in the direction preferred by DESI+CMB+SN combinations (w₀ \> −1, w\_a \< 0), though we emphasize this is a qualitative comparison, not a fit. The specific functional form (Eq. 11\) is distinguishable from the linear CPL parametrization w \= w₀ \+ w\_a z/(1+z) by its rational (not linear) dependence on (1+z)².

## **6.2 Testability**

Quantitative comparison requires fixing Δρ/ρ₀ (one free parameter, since α \= 1 is fixed by the Hawking–Page scaling argument of Section 3). The qualitative prediction—w \> −1 at moderate z returning toward −1 at low z, with rational rather than linear structure—is testable by DESI (in combination with external datasets), Euclid, and Roman. The framework’s specific functional form provides a template for fitting against BAO and Type Ia supernova data.

# **7\. Discussion**

## **7.1 Additional Predictions**

**CMB Fractal Echoes.** If previous mirror transitions occurred (as in Penrose’s CCC[^31]), the recursive structure should imprint fractal self-similarity in the CMB at multiple angular scales.

**Running G at Nuclear Scales.** The effective Planck density at hadronic scales is computable from asymptotic safety FRG equations. Lattice calculations can test whether G(k) modifies R(k) significantly.

## **7.2 Relationship to Existing Frameworks**

This framework extends Smolin’s cosmological natural selection[^32] (continuous rate replacing discrete reproduction; cobordism geometry replacing random mutation), Penrose’s CCC[^33] (compatible conformal structure across the spacetime tree), and the Bonanno–Reuter RG-improved cosmology[^34] (we derive observable consequences of their de Sitter core for w(z)).

## **7.3 Implications for Quantum Foundations**

The T-duality mechanism and single-entity boundary encoding developed here have implications for the foundations of quantum mechanics that extend beyond the cosmological scope of this paper. In particular, if the particle content of a universe consists of holographic reflections of a single entity, then quantum entanglement acquires a structural explanation in which Bell correlations are forced by purity, observer-induced bipartition, and spin-statistics—without invoking nonlocality. The algebraic approach to quantum subsystems (Zanardi, Lidar, and Lloyd) provides the formal framework for this analysis. We develop this in full in a companion paper.

## **7.4 Limitations**

The critical exponent α \= 1 is motivated by Hawking–Page mean-field scaling but lacks a derivation from the full quantum gravity partition function. The interior density scaling ρ\_Γ ∝ a⁻² is identified with anisotropic shear relaxation toward the de Sitter attractor, but a derivation from the specific RG-improved interior geometry would strengthen the case. The sub-Planckian window is parametric, not demonstrated. The exotic-smooth-structures-to-constants connection lacks a Lagrangian mechanism. The T-duality universality claim is strengthened by two observations—collapsing geometry provides the compactification naturally, and the shared SL(2,ℤ) symmetry between BKL dynamics and T-duality provides a structural connection—but a rigorous derivation showing that T-duality is exact in the BKL regime (beyond its established string-theoretic domain) remains the most technically important open problem in the framework. The paper’s core prediction (w(z) form) is independent of the quantum foundations implications noted in Section 7.3.

# **8\. Conclusion**

We have developed recursive holographic cosmogenesis with five contributions: cobordism-based formalization of parent-to-daughter transitions; identification of T-duality and BKL ultralocality as the physical mechanism, with compactification provided by the collapsing geometry itself rather than imported as an external assumption; the observation that BKL billiard dynamics and T-duality share the modular group SL(2,ℤ), with the fractal structure of the billiard trajectory organizing recursive mirror production; continuous rate-dependent cosmogenesis with α \= 1 from Hawking–Page mean-field scaling; and a falsifiable prediction for w(z). The framework interprets cosmological expansion as the transverse signature of an underlying gravitational compression, with the observed acceleration reflecting the approach to the de Sitter mirror boundary—replacing the initial singularity and the cosmological constant with a single mechanism. The central result—that the dark energy equation of state follows a specific rational form departing from ΛCDM—is testable with current and forthcoming surveys (DESI combined with CMB and supernova datasets, Euclid, Roman), and its specific functional form is distinguishable from standard parametrizations.

# **Appendix: Principal Equations**

**Mirror formation rate:** Γ \= (1/t\_P)(ρ\_local/ρ\_P)^α (Eq. 1\)

**T-duality mirror:** R → α′/R (Eq. T)

**Running G:** G(k) \= G₀/(1 \+ ωG₀k²) (Eq. 2\)

**Scale-dependent Planck density:** ρ\_P(k) \= ρ\_P(0)(1 \+ ωG₀k²)² (Eq. 3\)

**Master frequency relation:** f\_obs/f\_emit \= Γ(x\_emit)/Γ(x\_obs) (Eq. 4\)

**Cosmological redshift:** 1 \+ z \= Γ(t\_emit)/Γ(t\_obs) (Eq. 5\)

**Interior density evolution:** ρ\_Γ(a) \= ρ₀ \+ Δρ(a\_mirror/a)² (Eq. 7\)

**Continuity equation:** w(a) \= −1 − (1/3)(a/ρ\_Γ) dρ\_Γ/da (Eq. 9\)

**Dark energy EoS:** w(z) \= −1 \+ (2/3) Δρ(1+z)²/\[ρ₀ \+ Δρ(1+z)²\] (Eq. 11\)

**Friedmann equation:** H²(z) \= H₀²\[Ω\_m(1+z)³ \+ Ω\_Γ(z)\] (Eq. 12\)

# **References**

All references provided as footnotes. Principal sources: Pathria (1972), Frolov–Markov–Mukhanov (1989), Smolin (1997), Poplawski (2010), Bekenstein (1973), ’t Hooft (1993), Maldacena (1998), Bousso (2002), Donaldson (1983), Freedman (1982), Belinsky–Khalatnikov–Lifshitz (1970), Giveon–Porrati–Rabinovici (1994), Damour–Henneaux–Nicolai (2003), Wheeler (1998), Brandenberger–Vafa (1989), Hawking (1975), Hawking–Page (1983), Reuter (1998, 2012), Bonanno–Reuter (2000, 2002), Tolman (1930), Pound–Rebka (1959), Penrose (1965, 2010), Painlevé (1921), Riess et al. (1998), Perlmutter et al. (1999), DESI (2024), Kerr (1963), and Penrose–Hameroff (2014).

[^1]: R.K. Pathria, Nature 240, 298 (1972).

[^2]: V.P. Frolov, M.A. Markov, V.F. Mukhanov, Phys. Lett. B 216, 272 (1989).

[^3]: L. Smolin, The Life of the Cosmos, Oxford (1997).

[^4]: N. Poplawski, Phys. Lett. B 694, 181 (2010).

[^5]: J.D. Bekenstein, Phys. Rev. D 7, 2333 (1973).

[^6]: G. ’t Hooft, gr-qc/9310026 (1993).

[^7]: J.M. Maldacena, Adv. Theor. Math. Phys. 2, 231 (1998).

[^8]: R. Bousso, Rev. Mod. Phys. 74, 825 (2002).

[^9]: S.K. Donaldson, J. Diff. Geom. 18, 279 (1983).

[^10]: M.H. Freedman, J. Diff. Geom. 17, 357 (1982).

[^11]: R.P. Kerr, Phys. Rev. Lett. 11, 237 (1963).

[^12]: V.A. Belinsky, I.M. Khalatnikov, E.M. Lifshitz, "Oscillatory Approach to a Singular Point in the Relativistic Cosmology," Adv. Phys. 19, 525 (1970).

[^13]: A. Giveon, M. Porrati, E. Rabinovici, "Target Space Duality in String Theory," Phys. Rep. 244, 77 (1994).

[^14]: R.H. Brandenberger and C. Vafa, "Superstrings in the Early Universe," Nucl. Phys. B 316, 391 (1989).

[^15]: T. Damour, M. Henneaux, H. Nicolai, "Cosmological Billiards," Class. Quant. Grav. 20, R145 (2003).

[^16]: J.A. Wheeler, Geons, Black Holes, and Quantum Foam, Norton (1998).

[^17]: R.H. Brandenberger and C. Vafa, "Superstrings in the Early Universe," Nucl. Phys. B 316, 391 (1989).

[^18]: S.W. Hawking, Commun. Math. Phys. 43, 199 (1975).

[^19]: S.W. Hawking and D.N. Page, "Thermodynamics of Black Holes in Anti-de Sitter Space," Commun. Math. Phys. 87, 577 (1983).

[^20]: M. Reuter, Phys. Rev. D 57, 971 (1998).

[^21]: M. Reuter and F. Saueressig, New J. Phys. 14, 055022 (2012).

[^22]: A. Bonanno and M. Reuter, Phys. Rev. D 62, 043008 (2000).

[^23]: A. Bonanno and M. Reuter, Phys. Rev. D 65, 043508 (2002).

[^24]: R.C. Tolman, Phys. Rev. 35, 904 (1930).

[^25]: R.V. Pound and G.A. Rebka, Phys. Rev. Lett. 3, 439 (1959).

[^26]: R. Penrose, Phys. Rev. Lett. 14, 57 (1965).

[^27]: P. Painlevé, C. R. Acad. Sci. Paris 173, 677 (1921).

[^28]: A.G. Riess et al., Astron. J. 116, 1009 (1998).

[^29]: S. Perlmutter et al., Astrophys. J. 517, 565 (1999).

[^30]: DESI Collaboration, arXiv:2404.03002 (2024).

[^31]: R. Penrose, Cycles of Time, Bodley Head (2010).

[^32]: L. Smolin, The Life of the Cosmos, Oxford (1997).

[^33]: R. Penrose, Cycles of Time, Bodley Head (2010).

[^34]: A. Bonanno and M. Reuter, Phys. Rev. D 65, 043508 (2002).