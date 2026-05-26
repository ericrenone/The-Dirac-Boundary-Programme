# The Dirac Boundary Programme
## Chiral Spinor Geometry as the Universal Structure of Electromagnetic Radiation, Compact Representational Manifolds, and Nonlinear Quantum Localization

**Eric Ren · ERI Labs · Jersey City, New Jersey · May 2026**

> *"It seemed natural to me that the same structure which governs the propagation of light through the vacuum should also govern the propagation of meaning through a trained network — because both are consequences of the same first-order operator on a compact manifold whose topology was determined by the data it carries. And when Shi and Wong showed that a cubic nonlinearity traps the walk on the cycle to arbitrary fidelity, the third domain became inescapable: the ker(∂̸) is not only the chiral fermion substrate and the topological winding mode — it is the trapped state, the quantum memory, the fixed point that holds until the boundary releases it."*

---

## Abstract

Two independent programmes, developed in parallel across physics and machine learning theory, have converged on the same mathematical object. A third result — published May 2026 — completes a triangle.

The first programme — **ERIE-LIGHT** — establishes that the photon is the col(F) bilinear of a chiral fermion ker(F), that Pryce's 1938 obstruction is the algebraic non-solvability of the composite chirality boundary rather than a refutation of the bilinear structure, and that the Majorana self-conjugacy condition, the semi-Dirac directional anisotropy, and the 2026 vacuum chirality result are successive manifestations of the same col(F)/ker(F) boundary at the helicity axis of electromagnetic radiation.

The second programme — the **Dirac Representation Hypothesis** — establishes that learned concept representations in deep networks live on a compact spin manifold M_R, that the natural first-order operator on M_R is the Dirac operator ∂̸ satisfying ∂̸² = −Δ_g, that its index via Atiyah-Singer counts the topologically protected cyclic operations the network can perform, and that the spectral gap of the Bakry-Émery Laplacian on M_R controls grokking phase transitions in deep network training.

The third result — **Shi and Wong (arXiv:2605.20464, May 2026)** — proves that a continuous-time quantum walk with cubic nonlinearity on the discrete cycle S¹ is trapped to arbitrary fidelity, contrasting with the free spread of the linear walk. The nonlinearity coefficient controls the trapping fidelity; the trapped state is a fixed point of the nonlinear propagator; the cycle is S¹. This is the ker(∂̸) sector made dynamically explicit: the self-interaction that generates effective mass localizes the walk on exactly the compact manifold M_R whose topology the Dirac Boundary Programme places at the foundation of the computational domain.

The **Dirac Boundary Programme** is the identification: these are not three separate results. They are the same framework instantiated on three domains — Minkowski spacetime M₄, the representational manifold M_R, and the discrete cycle graph Γ(S¹) — carrying the same Dirac operator, the same col(F)/ker(F) partition, the same Atiyah-Singer topology, and the same transition between spreading (massless, col(∂̸)) and trapping (massive, ker(∂̸)) governed by the nonlinearity of self-interaction.

The programme unifies seven prior frameworks — the Linear Representation Hypothesis, the Minkowski Representation Hypothesis, the Anisotropic Representation Hypothesis, the Closed Future Cone, the Jordan–de Broglie–Kronig neutrino-bilinear programme, the Pryce-Berezinskii obstruction taxonomy, and the Shi-Wong nonlinear quantum walk localization — as special cases or projections of a single geometric structure: the Dirac operator on a compact spin manifold with chiral structure, col(F)/ker(F) boundary, and Kakutani-governed fixed points at the boundary.

Thirteen cross-domain correspondences and eleven combined predictions follow.

---

## Part I · The Unifying Object

### I.1 The Dirac Operator as Universal First-Order Operator

Let M be a compact Riemannian spin manifold of signature (p,q), with spinor bundle S(M) and Clifford algebra Cl(p,q) determined by the metric g. The Dirac operator is

$$\not\partial = i\gamma^\mu \nabla_\mu$$

where γ^μ are the Clifford matrices satisfying {γ^μ, γ^ν} = 2g^μν and ∇_μ is the spin connection. The Dirac operator is the unique first-order differential operator on sections of S(M) that:

1. Satisfies ∂̸² = −Δ_g (its square is the negative Laplace-Beltrami operator)
2. Is self-adjoint on L²(M, S(M)) with respect to the L² inner product
3. Has spectrum symmetric about zero: λ_n and −λ_n are simultaneously eigenvalues
4. Has index ind(∂̸) = dim ker(∂̸⁺) − dim ker(∂̸⁻) computable from topological data alone via the Atiyah-Singer index theorem
5. Carries the full metric signature in its Clifford algebra: timelike and spacelike directions are algebraically distinguished by the anticommutation relations

Properties (1)–(5) are jointly satisfied by no other natural operator. The central claim of the Dirac Boundary Programme is that this canonical object governs three superficially distinct domains:

**In the physical domain**, M = M₄ is Minkowski spacetime with signature (−,+,+,+), the spinor fields are physical fermions, and the photon is the col(∂̸) bilinear of chiral fermion sections of S(M₄). The col(∂̸)/ker(∂̸) partition separates the observable electromagnetic radiation (col(∂̸)) from the chiral fermion substrate whose bilinear sources it (ker(∂̸)).

**In the computational domain**, M = M_R is the compact representational manifold of a trained deep network — its topology determined by the symmetry of the training data's co-occurrence statistics (Karkada et al., arXiv:2602.15029, 2026) — and the spinor sections are the network's learned concept representations. The col(∂̸)/ker(∂̸) partition separates the observable linear representation (what SAE dictionary learning finds) from the topologically protected structure (what Atiyah-Singer counts).

**In the quantum walk domain**, M = Γ(S¹) is the discrete cycle graph, the walk is a continuous-time quantum walk with Gross-Pitaevskii cubic nonlinearity, and the col(∂̸)/ker(∂̸) partition separates the spreading sector (linear walk, massless, propagating at the effective graph velocity) from the trapped sector (nonlinear walk, effectively massive, localized to arbitrary fidelity at the initial vertex). The nonlinearity coefficient controls the col-to-ker ratio; the trapped fixed point is the ker(∂̸) sector made directly dynamical.

### I.2 The col(F)/ker(F) Partition

For any operator F acting on a Hilbert space H, the partition H = col(F) ⊕ ker(F⊥) is the canonical decomposition into the range and the orthogonal complement of the null space. In the context of the Dirac operator, this partition carries specific physical and mathematical content:

**col(∂̸):** The image of ∂̸. In the physical domain, this is the propagating sector — the observable photon, carrying energy, momentum, and angular momentum. In the computational domain, this is the observable representation sector — the linear features that are read off by probing, steering vectors, and dictionary learning. In the quantum walk domain, this is the **spreading sector** — the linear walk that delocalizes across the cycle graph, carrying probability amplitude from the source vertex to all other vertices at rate determined by the graph Laplacian.

**ker(∂̸):** The kernel of ∂̸. In the physical domain, this is the zero-mode sector — the chiral fermion substrate, topologically protected. In the computational domain, this is the topologically protected sector — the winding modes of cyclic concept manifolds, counted by the Atiyah-Singer index. In the quantum walk domain, this is the **trapped sector** — the localized state sustained by self-interaction, pinned to the initial vertex to arbitrary fidelity by the cubic nonlinearity, held until the nonlinearity is removed and the walk is released. The trapped state is a Kakutani fixed point of the nonlinear propagator on the compact cycle.

The conditional independence boundary between col(∂̸) and ker(∂̸) is the algebraic object that Pryce's theorem locates in the physical domain, that the Atiyah-Singer index theorem locates in the computational domain, and that the nonlinearity coefficient controls in the quantum walk domain. All three are instances of the same topological fact: on a compact spin manifold, the Dirac operator has a kernel whose dimension is a topological invariant, and the mass term (self-interaction) is the coupling that transfers amplitude from col to ker.

---

## Part II · The Physical Domain: ERIE-LIGHT

### II.1 The Photon as col(∂̸) Bilinear

The Maxwell field A^μ(x) is sourced by the fermion bilinear current j^μ = ψ̄γ^μψ in every quantum-field-theoretic construction. The de Broglie–Jordan programme (1932–1937) identifies this structural fact with a specific proposal: the photon is the col(∂̸) projection of a chiral neutrino-antineutrino bilinear, where the neutrino fields are the ker(∂̸) substrate. Pryce (1938) proved that this composite cannot satisfy exact Bose–Einstein commutation relations; Berezinskii (1966) refined this into five mutually incompatible assumptions (locality, exact Bose statistics, neutrality, Lorentz invariance, transverse polarization) whose conjunction is algebraically unrealizable.

The ERIE-LIGHT re-reading: Pryce's obstruction is the algebraic non-solvability of the composite chirality boundary rather than a refutation of the bilinear identification. The structural identification (photon = col(∂̸) of chiral fermion bilinear) is correct and universal across all gauge bosons. The obstruction is the structure, not the failure.

### II.2 The Four Physical Manifestations

**The Majorana Degeneracy (d=0 degeneration):** The Majorana condition ψ = ψ^c identifies the particle and antiparticle sectors. In the col(∂̸)/ker(∂̸) language: the col(∂̸) and ker(∂̸) of the chirality boundary are identified by the boundary itself. Experimentally tested by neutrinoless double beta decay (0νββ): the LEGEND-200 experiment is currently operating with half-life sensitivity approaching 10²⁷ years for ⁷⁶Ge; LEGEND-1000 targets 10²⁸ years by the early 2030s.

**The Semi-Dirac Anisotropy (directional col(∂̸)/ker(∂̸)):** Semi-Dirac fermions disperse linearly along a given direction in momentum space and quadratically in the orthogonal direction, emerging at the critical point of a topological phase transition from semimetal to insulator. The massless linear direction is col(∂̸); the massive quadratic direction is ker(∂̸). First observed in ZrSiS by Shao et al. (Physical Review X 14, 041057, 2024–2025), with defining experimental signature B^(2/3) cyclotron energy scaling.

**The Chiral Vacuum (ker(∂̸) at the boundary):** The Heinzl–King–Mercuri-Baron result (Physical Review D 113, 036031, February 2026) demonstrates that QED vacuum under a circularly polarized background acquires definite handedness — a chiral medium in which the standard Heisenberg-Euler effective Lagrangian fails. This is the ker(∂̸) made directly measurable.

**The Neutrino Mass Constraint:** The KATRIN Collaboration (Science, 2025) places the upper bound on the electron antineutrino mass at ≤ 0.45 eV from 259 days of tritium β-spectrum data, bounding the Dirac mass contribution and constraining the seesaw scale M_R = m_D² / m_ν.

---

## Part III · The Computational Domain: The Dirac Representation Hypothesis

### III.1 The Representational Manifold M_R

Karkada et al. (arXiv:2602.15029, February 2026) prove analytically that the topology of M_R is forced by the symmetry of co-occurrence statistics: cyclic symmetry Z_n in the data forces topological circle S¹; Z_n × Z_m forces a torus T²; continuous translation symmetry forces a line.

### III.2 The Operator and Its Consequences

**Spectral:** The spectral gap λ₁ of ∂̸ separates dynamical phases of training. Three independent empirical confirmations in March–April 2026 (Xu, arXiv:2603.28964 and arXiv:2604.07380; Acharya and Dhakal, arXiv:2603.15492) establish that spectral gap collapse precedes every grokking event in 24 of 24 weight-decay runs and in 0 of 24 runs without weight decay.

**Topological:** The Atiyah-Singer index theorem computes ind(∂̸) from the topology of M_R alone. On T², the kernel of ∂̸ has dimension |H⁰| + |H¹| + |H²| = 1 + 2 + 1 = 4, predicting four topologically protected cyclic-arithmetic modes for any jointly-learned day-and-month concept.

**Oriented:** The two spin structures on S¹ (Ramond and Neveu-Schwarz sectors) correspond to the two possible consistent orientations of the concept ring under direction reversal, confirmed by Engels et al. (NeurIPS 2024).

**Discrete decisions:** The Kakutani fixed-point theorem governs set-valued operations — argmax decoding, top-k sparse attention, mixture-of-experts routing, beam search — as upper hemicontinuous correspondences on compact convex sets. The trapped state of a nonlinear quantum walk on S¹ is now a third physical realization of this fixed point.

---

## Part IV · The Quantum Walk Domain: Shi-Wong Localization

### IV.1 The Result

Shi and Wong (arXiv:2605.20464, May 2026) prove that a continuous-time quantum walk starting at a single vertex on the discrete path and cycle with a **cubic nonlinearity** — of the form arising in Bose-Einstein condensates described by the Gross-Pitaevskii equation, and in nonlinear optical waveguide arrays — is **trapped to arbitrary fidelity** depending on the coefficient of the nonlinear term. Linear quantum walks spread across the graph; nonlinear quantum walks localize. The trapping coefficient controls the fidelity; the release of the nonlinearity releases the amplitude.

The proposed applications: **quantum state transfer timing** (hold a qubit at a node until transfer is ready; hold it again at the receiving node) and **quantum memory** (trap = storage, release = retrieval).

### IV.2 The Dirac Boundary Reading

The Shi-Wong result is the col(∂̸)/ker(∂̸) partition made explicitly dynamical on the compact cycle S¹:

**The linear walk** is the massless sector: col(∂̸). The Hamiltonian is the graph Laplacian, which is the negative square of the Dirac operator on the graph, −∂̸² = Δ_g. The walk spreads because the propagating sector is not self-interacting — it is the photon-like mode, carrying amplitude from vertex to vertex at the graph's effective speed of light.

**The cubic nonlinearity** is the mass term: the self-interaction that transfers amplitude from col(∂̸) to ker(∂̸). In the Gross-Pitaevskii equation, the nonlinearity arises from the mean-field interaction of the condensate with itself — exactly the self-coupling that distinguishes a massive fermion from a massless propagator. The nonlinearity coefficient g is the mass parameter; the trapping fidelity increasing with g is the amplitude of the ker(∂̸) sector increasing with the effective mass.

**The trapped state** is the Kakutani fixed point: the set-valued correspondence defined by the nonlinear propagator on S¹ has a fixed point — the localized amplitude distribution — and Kakutani's theorem guarantees it on the compact cycle. The Dirac Boundary Programme had invoked Kakutani for discrete computational decisions (argmax, top-k, routing, beam search); Shi and Wong provide its physical realization in continuous quantum dynamics.

**The quantum memory** is the col/ker boundary as a programmable gate: setting g high traps the walk (ker(∂̸) dominant, storage mode); setting g to zero releases it (col(∂̸) dominant, propagation mode). The boundary between col and ker is the boundary between storage and transmission, between inertia and radiation, between concept-winding and concept-propagation. The quantum computer is implementing the Dirac Boundary.

**The cycle graph S¹** is M_R for the computational domain's simplest concept manifold. The topology that Karkada et al. prove is forced by cyclic data symmetry is the same topology that Shi and Wong place their nonlinear walk on. A language model's days-of-week representation lives on S¹; a Bose-Einstein condensate's quantum memory lives on the discrete cycle approximating S¹; both are governed by the same col(∂̸)/ker(∂̸) partition of the same operator on the same compact manifold.

### IV.3 The Semi-Dirac Connection

The semi-Dirac fermion in ZrSiS (Shao et al., Physical Review X 14, 2024–2025) exhibits B^(2/3) cyclotron scaling as a harmonic interpolation between the linear (col(∂̸), massless) and quadratic (ker(∂̸), massive) dispersion relations. The Shi-Wong nonlinear walk is a temporal interpolation of the same boundary: at g = 0, the walk is purely col(∂̸) (linear, spreading); as g increases, ker(∂̸) amplitude grows (localization deepens); at large g, the walk is dominantly ker(∂̸) (trapped, inertial). The exponent that governs semi-Dirac cyclotron scaling in momentum space is the same power-law interpolation that governs Shi-Wong trapping fidelity in time: both are signatures of a system sitting at the col(∂̸)/ker(∂̸) boundary, with a continuous parameter (B-field strength / nonlinearity coefficient) controlling how far the system sits into the ker sector.

---

## Part V · The Thirteen Cross-Domain Correspondences

The following correspondences are identifications of structure, not claims of literal identity.

| Physical Domain (ERIE-LIGHT / M₄) | Computational Domain (DRH / M_R) | Quantum Walk Domain (Shi-Wong / Γ(S¹)) | Common Structure |
|---|---|---|---|
| Photon: col(∂̸), observable, bosonic | Linear representation: col(∂̸), SAE-recoverable | Linear walk: col(∂̸), spreading, delocalizing | Image of ∂̸ on the observable sector |
| Chiral neutrino bilinear: ker(∂̸), hidden, topological | Topological winding modes: ker(∂̸), Atiyah-Singer counted | Trapped state: ker(∂̸), localized, fidelity-controlled | Kernel of ∂̸ on the topological sector |
| Pryce obstruction: algebraic non-solvability | Topological protection: non-contractible winding | Nonlinearity threshold: trapping onset at finite g | ind(∂̸) as topological invariant |
| Majorana condition ν = ν̄: col = ker at d=0 | Trivial topology: no winding protection | g → 0 limit: trapped state released, col = ker | d=0 degeneration of the col/ker boundary |
| Semi-Dirac fermion: massless col, massive ker | Hyperribbon anisotropy: sloppy col, stiff ker | Walk interpolation: g=0 (col) to large g (ker) | Directional anisotropy of the spinor field |
| B^(2/3) cyclotron scaling | Hyperribbon width spectrum | Trapping fidelity power law in g | Spectral interpolation between col and ker modes |
| Chiral vacuum: ker visible only to chiral probe | Topological modes: ker visible to winding intervention | Trapped state: ker visible only to nonlinear probe | ker observable only through boundary coupling |
| Heisenberg-Euler: integrated-out Dirac sea ker | Bakry-Émery Laplacian: integrated-out training dynamics | Gross-Pitaevskii effective action: integrated-out condensate ker | Effective second-order operator from ker |
| Berezinskii's five assumptions: overdetermined boundary | Fixed-point structure: Brouwer (continuous), Kakutani (set-valued) | Kakutani fixed point: trapped state on compact cycle | Boundary conditions on the col/ker partition |
| Lorentzian Clifford algebra: signature encodes causal cone | Minkowski-signature M_R: attention as causal cone | Graph Laplacian = −∂̸²: Clifford algebra on discrete cycle | Clifford algebra signature as physical geometry |
| Chirality operator γ₅: left/right decomposition | Chirality of spinor sections: forward/backward on S¹ | Walk chirality: clockwise/counterclockwise on cycle | Chirality eigenspaces of ∂̸ |
| CPT symmetry: exact mirror at chirality boundary | Concept-direction reversal: orientation reversal on M_R | Walk time-reversal: g → g under t → −t | col(∂̸) ↔ ker(∂̸) symmetry at the boundary |
| Seesaw scale: M_R = m_D² / m_ν (ker(∂̸) mass from col(∂̸) bilinear) | Spectral gap: λ₁ from Atiyah-Singer topology of M_R | Trapping coefficient g: col-to-ker amplitude ratio | Mass parameter as col/ker coupling strength |

---

## Part VI · Combined Predictions

### Established Predictions (confirmed by independent work)

**C1 — Spectral gap controls grokking (DRH).** Spectral gap collapse of the rolling-window operator precedes every grokking event when weight decay is present. Confirmed: 24/24 with weight decay, 1/24 without (Xu, arXiv:2603.28964, March 2026; Acharya and Dhakal, arXiv:2603.15492, March 2026).

**C2 — Data symmetry forces manifold topology (DRH).** Cyclic Z_n symmetry forces S¹; Z_n × Z_m forces T²; translation forces a line. Proved analytically (Karkada et al., arXiv:2602.15029, February 2026).

**C3 — Semi-Dirac B^(2/3) cyclotron scaling (ERIE-LIGHT).** Semi-Dirac fermions exhibit B^(2/3) cyclotron energy scaling. Observed in ZrSiS (Shao et al., Physical Review X 14, 041057, 2024–2025).

**C4 — Chiral vacuum failure of Heisenberg-Euler Lagrangian (ERIE-LIGHT).** Under a circularly polarized background, the standard Heisenberg-Euler effective Lagrangian fails. Proved (Heinzl, King, Mercuri-Baron, Physical Review D 113, 036031, February 2026).

**C5 — Nonlinear quantum walk trapping on S¹ (Shi-Wong).** A cubic nonlinearity traps the continuous-time quantum walk on the discrete cycle to arbitrary fidelity, with the spreading-to-trapping transition controlled by the nonlinearity coefficient. Proved analytically (Shi and Wong, arXiv:2605.20464, May 2026). This is the first direct dynamical demonstration of the col(∂̸)/ker(∂̸) transition on the compact cycle S¹ — the same topology as the simplest representational manifold of a trained language model.

### Near-Term Testable Predictions (2026–2030)

**N1 — Four topologically protected modes for T² concepts (DRH / integer prediction).** Any model that has jointly learned days-of-week and months-of-year as coupled cyclic concepts must exhibit exactly four topologically protected representational modes, corresponding to the four independent homology classes of T².

**N2 — k grokking events for k topological cycles (DRH / integer prediction).** A training run on a task requiring k distinct cyclic concepts exhibits k distinct spectral-gap collapse events.

**N3 — Optimal vacuum chirality probe at η* (ERIE-LIGHT / φ-equilibrium).** The signal-to-noise for detecting chiral derivative corrections to the Heisenberg-Euler Lagrangian is maximised at background helicity ratio η*_helicity = log φ ≈ 0.481. Testable at HIBEF, ELI Beamlines, and SPD.

**N4 — Semi-Dirac φ-corrected exponent (ERIE-LIGHT / φ-equilibrium).** The cyclotron energy scaling exponent satisfies α* = 1/(1 + log φ) ≈ 0.6752 rather than 2/3. Deviation Δα ≈ 0.0085, testable at the National High Magnetic Field Laboratory hybrid magnet (90 T).

**N5 — Identical manifold topology for identical symmetry groups across models (DRH).** Concepts with the same underlying symmetry group produce homeomorphic representational manifolds across different model families, with differences confined to embedding angle and scale.

**N6 — Trapping fidelity power law in nonlinearity coefficient (Shi-Wong / col-ker interpolation).** The interpolation between spreading (g=0) and trapping (large g) in the Shi-Wong nonlinear quantum walk on the discrete cycle follows a power-law analogous to the semi-Dirac B^(2/3) cyclotron scaling: a harmonic-mean exponent of the massless (linear walk, col(∂̸)) and massive (trapped walk, ker(∂̸)) scaling regimes. The Dirac Boundary Programme predicts that this exponent deviates from the simple harmonic-mean value by a factor involving log φ at the same level (approximately 1.3%) as the semi-Dirac cyclotron prediction. Testable by precision measurement of trapping fidelity as a function of nonlinearity coefficient in ultracold atomic or photonic waveguide implementations.

**N7 — Topological protection of quantum memory at S¹ winding number (Shi-Wong / Atiyah-Singer).** The Atiyah-Singer index theorem on the discrete cycle Γ(S¹) predicts an integer count of topologically protected modes for the nonlinear quantum walk. The Dirac Boundary Programme predicts that the trapped state(s) degenerate in number according to this integer count — not one generic trapped state, but a discrete family indexed by the winding modes of S¹ — and that the release of each mode corresponds to a distinct detrapping event. For the simple cycle, the prediction is one protected mode per winding class. Testable by Fourier decomposition of trapping fidelity dynamics across distinct initial conditions on the cycle.

### Decade-Scale Testable Predictions (2030–2035)

**D1 — Majorana condition at 0νββ half-life ~ 10²⁸ years (ERIE-LIGHT / d=0 degeneracy).** If neutrino masses are generated by the canonical Type-I seesaw mechanism, the half-life for ⁷⁶Ge lies within LEGEND-1000 sensitivity.

**D2 — Chirality of attention head decomposition (DRH / spinor prediction).** The positive and negative chirality eigenspaces of ∂̸ on M_R should correlate with causal-only (decoder) and bidirectional (encoder) information flow in transformer models.

**D3 — Composite-photon Pauli-blocking residue bounded at α² log φ (ERIE-LIGHT).** Any residual non-bosonic structure of the photon satisfies Δ_Bose ≤ α² × log φ ≈ 2.6 × 10⁻⁵. Testable by next-generation squeezed-light interferometers.

---

## Part VII · Positioning Against the State of the Art

### VII.1 What the Programme Inherits

**From Geometric Deep Learning (Bronstein, Bruna, Cohen, Veličković, 2021, MIT Press 2026):** The Dirac Boundary Programme inherits the symmetry-group programme and extends it: the spin group Spin(M_R) is the double cover of SO(M_R), and spinor sections carry orientation unavailable to scalar sections. GDL reaches to architecture prescription; the programme reaches further to operator governance of the learned representation.

**From Karkada et al. (arXiv:2602.15029, 2026):** The existence theorem for M_R — co-occurrence symmetry forces manifold topology — is the foundation. The programme places the natural first-order operator on the manifold whose existence is proved.

**From Xu (arXiv:2603.28964, arXiv:2604.07380, 2026) and Acharya-Dhakal (arXiv:2603.15492, 2026):** The three-paper independent validation of spectral gap collapse governing grokking is the empirical confirmation of the spectral structure the programme predicts.

**From Shi and Wong (arXiv:2605.20464, May 2026):** The nonlinear quantum walk result provides the first **dynamical** realization of the col(∂̸)/ker(∂̸) transition on the compact cycle S¹. Prior predictions of this transition were structural (Pryce-Berezinskii in the physical domain) or spectral (Xu/Acharya-Dhakal in the computational domain). Shi and Wong show it happening in time, continuously, with a tunable parameter controlling the col-to-ker ratio. This is the boundary made programmable.

**From the Jordan–de Broglie–Kronig–Pryce corpus (1928–1966):** The historical neutrino-theory-of-light programme is re-read: the programme recovers its structural content while accepting Pryce's obstruction as the algebraic boundary structure.

### VII.2 What No Prior Framework Provides

No prior theoretical synthesis provides all of the following simultaneously:

1. A single first-order operator (∂̸) that produces both the spectral structure (∂̸² = −Δ_g) and the topological invariants (Atiyah-Singer) of every domain it governs
2. An orientation-carrying structure (spinor sections) that distinguishes forward from backward on cyclic concept manifolds, left-handed from right-handed in the physical domain, and clockwise from counterclockwise on the discrete cycle
3. A single partition (col(∂̸)/ker(∂̸)) that simultaneously identifies the observable sector (photon / linear representation / spreading walk) and the topologically protected sector (chiral substrate / winding modes / trapped state)
4. A classical obstruction theorem (Pryce-Berezinskii / Atiyah-Singer) re-read as structural content of the partition rather than as a refutation
5. Integer-valued predictions (four protected modes for T², k grokking events for k cycles, k detrapping events for k winding modes, 0νββ half-life within LEGEND-1000 range) distinguishing the programme from frameworks making only asymptotic predictions
6. A directional anisotropy (semi-Dirac / hyperribbon / Shi-Wong trapping power law) connecting condensed matter physics, information geometry, and quantum walk dynamics
7. A **programmable** col/ker boundary: the nonlinearity coefficient of the Shi-Wong walk is the first experimentally accessible knob that continuously interpolates between the spreading (col) and trapped (ker) sectors of the Dirac operator on S¹

---

## Part VIII · What the Dirac Boundary Programme Does Not Claim

It does not claim that trained transformers are literally spin manifolds. The claim is structural.

It does not claim that the photon is literally a neutrino-antineutrino bound state. The structural identification is compatible with the photon being an elementary gauge boson at the S-matrix level.

It does not claim that M_R is the same manifold as M₄ or Γ(S¹). Three distinct manifolds; one operator structure; one boundary.

It does not claim that the Shi-Wong nonlinear walk is a quantum computer implementing a language model. The claim is that both systems are governed by the same col(∂̸)/ker(∂̸) structure on the same compact topology S¹, and therefore their spectral, topological, and fixed-point properties are related by the correspondence table above.

It does not claim that the φ-equilibrium predictions are exact. The deviation Δα ≈ 0.0085 from the simple harmonic-mean value is a prediction, not a confirmed measurement.

It does not subsume QED. Quantum electrodynamics, confirmed to twelve decimal places, is the quantitative framework. The programme is structural and makes predictions at sensitivity levels beyond current QED tests.

It does not resolve the spin structure existence condition on M_R. For M_R with complex topology, the vanishing of w₂(M_R) is an open question.

It does not provide a learning-dynamics derivation. A complete theory would derive the grokking phase transition from first principles of spectral gap collapse as a function of training dynamics. This requires integrating the operator picture with a renormalisation-group treatment of training.

---

## Part IX · The Synthesis

De Broglie was right that the photon has a chiral fermion bilinear at its structural root. Pryce was right that the literal composite is algebraically obstructed. Atiyah and Singer were right that the index of the Dirac operator computes topological invariants from spectral data. Majorana was right that a fermion can be its own antiparticle. The experimentalists at the National High Magnetic Field Laboratory were right that matter can interpolate between photon-like and matter-like dispersion. Karkada et al. were right that data symmetry forces manifold topology. Xu and Acharya-Dhakal were right that spectral gap collapse governs grokking. **Shi and Wong are right that nonlinearity traps the walk on the cycle — and the trapped walk is the ker(∂̸), and the cycle is S¹, and S¹ is the representational manifold of every cyclically symmetric concept in every trained language model.**

The Dirac Boundary Programme identifies that these are all projections of a single object: the Dirac operator on a compact spin manifold with chiral structure, col(F)/ker(F) partition, and Atiyah-Singer topology. In the physical domain, the manifold is Minkowski spacetime and the chiral fermion fields are physical particles. In the computational domain, the manifold is the representational geometry of a trained network and the chiral sections are learned concept representations. In the quantum walk domain, the manifold is the compact cycle and the nonlinearity coefficient controls how much of the walk lives in each sector.

The light was always the bilinear. The concept was always the spinor section. The trapped walk is the ker. The obstruction was always the structure. The index was always the count. The nonlinearity was always the mass.

**One operator. Three domains. One boundary.**

---

## References

### Foundational Mathematics

Atiyah, M. F. and Singer, I. M. The Index of Elliptic Operators I–V. *Annals of Mathematics* 87 (1968) and following.

Bakry, D. and Émery, M. Diffusions hypercontractives. *Séminaire de Probabilités XIX*, 1985.

Dirac, P. A. M. The Quantum Theory of the Electron. *Proceedings of the Royal Society A* 117, 610–624, 1928.

Kakutani, S. A Generalization of Brouwer's Fixed Point Theorem. *Duke Mathematical Journal* 8, 457–459, 1941.

Schechter, J. and Valle, J. W. F. Neutrinoless double-β decay in SU(2)×U(1) theories. *Physical Review D* 25, 2951, 1982.

### ERIE-LIGHT: Physical Domain

Berezinskii, V. S. Pryce's theorem and the neutrino theory of light. *Soviet Physics JETP* 24, 927–933, 1967.

de Broglie, L. *Une nouvelle conception de la lumière.* Hermann et Cie., Paris, 1934.

Heinzl, T., King, B., Mercuri-Baron, A. Probing the vacuum as a chiral medium. *Physical Review D* 113, 036031, February 2026.

KATRIN Collaboration. Direct neutrino-mass measurement based on 259 days of KATRIN data. *Science*, 2025.

Majorana, E. Teoria simmetrica dell'elettrone e del positrone. *Il Nuovo Cimento* 14, 171–184, 1937.

Pryce, M. H. L. On the neutrino theory of light. *Proceedings of the Royal Society of London A* 165, 247–271, 1938.

Shao, Y. et al. Semi-Dirac Fermions in a Topological Metal. *Physical Review X* 14, 041057, 2024–2025.

### Dirac Representation Hypothesis: Computational Domain

Acharya, P. and Dhakal, H. Grokking as a Variance-Limited Phase Transition. arXiv:2603.15492, March 2026.

Bhalla, U. et al. Do Sparse Autoencoders Capture Concept Manifolds? arXiv:2604.28119, April 2026.

Engels, J., Liao, I., Michaud, E. J., Gurnee, W., Tegmark, M. Not All Language Model Features Are Linear. *NeurIPS 2024*, arXiv:2405.14860.

Karkada, D., Korchinski, D. J., Nava, A., Wyart, M., Bahri, Y. Symmetry in language statistics shapes the geometry of model representations. arXiv:2602.15029, February 2026.

Park, K., Choe, Y. J., Veitch, V. The Linear Representation Hypothesis and the Geometry of Large Language Models. *ICML 2024*, arXiv:2311.03658.

Xu, Y. The Spectral Edge Thesis. arXiv:2603.28964, March 2026.

Xu, Y. The Lifecycle of the Spectral Edge. arXiv:2604.07380, April 2026.

### Quantum Walk Domain

Shi, Y. and Wong, T. G. One-Dimensional Nonlinear Quantum Walks. arXiv:2605.20464, May 2026.

### Cross-Domain: Geometric and Topological Deep Learning

Bianconi, G. The topological Dirac equation of networks and simplicial complexes. *Journal of Physics: Complexity* 2, 035022, 2021.

Bronstein, M. M., Bruna, J., Cohen, T., Veličković, P. *Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges.* MIT Press, 2026.

Mao, J. et al. Analytical characterization of sloppiness in neural networks. *Physical Review E* 113, 015306, January 2026.

Ruhe, D., Brandstetter, J., Forré, P. Clifford Group Equivariant Neural Networks. *NeurIPS 2023 Oral*, arXiv:2305.11141.

Wang, R., Tian, Y., Liò, P., Bianconi, G. Dirac-equation signal processing: Physics boosts topological machine learning. *PNAS Nexus* 4, pgaf139, 2025.

---

*ERI Labs · Eric Ren · Jersey City, New Jersey · May 2026*

*The Dirac Boundary Programme is one framework. The boundary is the structure. The structure is the physics. The physics is the boundary.*
