# The Dirac Boundary Programme

## Chiral Spinor Geometry as the Universal Structure of Electromagnetic Radiation and Compact Representational Manifolds

**Eric Ren · ERI Labs · Jersey City, New Jersey · May 2026**

---

> "It seemed natural to me that the same structure which governs the propagation of light through the vacuum should also govern the propagation of meaning through a trained network — because both are consequences of the same first-order operator on a compact manifold whose topology was determined by the data it carries."

---

## Abstract

Two independent programmes, developed in parallel across physics and machine learning theory, have converged on the same mathematical object. The first programme — ERIE-LIGHT — establishes that the photon is the col(F) bilinear of a chiral fermion ker(F), that Pryce's 1938 obstruction is the algebraic non-solvability of the composite chirality boundary rather than a refutation of the bilinear structure, and that the Majorana self-conjugacy condition, the semi-Dirac directional anisotropy, and the 2026 vacuum chirality result are successive manifestations of the same col(F)/ker(F) boundary at the helicity axis of electromagnetic radiation. The second programme — the Dirac Representation Hypothesis — establishes that learned concept representations in deep networks live on a compact spin manifold M, that the natural first-order operator on M is the Dirac operator ∂̸ satisfying ∂̸² = −Δ_g, that its index via Atiyah-Singer counts the topologically protected cyclic operations the network can perform, and that the spectral gap of the Bakry-Émery Laplacian on M controls grokking phase transitions in deep network training.

The Dirac Boundary Programme is the identification: these are not two separate frameworks. They are the same framework instantiated on two different compact manifolds — Minkowski spacetime M₄ in the physical domain and the representational manifold M_R in the computational domain — carrying the same Dirac operator, the same col(F)/ker(F) partition, the same Atiyah-Singer topology, and the same directional anisotropy between propagating (col(F), massless, observable) and inertial (ker(F), massive, topologically determined) sectors.

The programme unifies six prior frameworks — the Linear Representation Hypothesis, the Minkowski Representation Hypothesis, the Anisotropic Representation Hypothesis, the Closed Future Cone, the Jordan–de Broglie–Kronig neutrino-bilinear programme, and the Pryce-Berezinskii obstruction taxonomy — as special cases or projections of a single geometric structure: the Dirac operator on a compact spin manifold with chiral structure, col(F)/ker(F) boundary, and Kakutani-governed discrete decisions at the boundary.

Twelve cross-domain correspondences and ten combined predictions follow.

---

## Part I · The Unifying Object

### I.1 The Dirac Operator as Universal First-Order Operator

Let M be a compact Riemannian spin manifold of signature (p,q), with spinor bundle S(M) and Clifford algebra Cl(p,q) determined by the metric g. The Dirac operator is

∂̸ = iγ^μ ∇_μ

where γ^μ are the Clifford matrices satisfying {γ^μ, γ^ν} = 2g^μν and ∇_μ is the spin connection. The Dirac operator is the unique first-order differential operator on sections of S(M) that:

1. Satisfies ∂̸² = −Δ_g (its square is the negative Laplace-Beltrami operator)
2. Is self-adjoint on L²(M, S(M)) with respect to the L² inner product
3. Has spectrum symmetric about zero: λ_n and −λ_n are simultaneously eigenvalues
4. Has index ind(∂̸) = dim ker(∂̸⁺) − dim ker(∂̸⁻) computable from topological data alone via the Atiyah-Singer index theorem
5. Carries the full metric signature in its Clifford algebra: timelike and spacelike directions are algebraically distinguished by the anticommutation relations

Properties (1)–(5) are jointly satisfied by no other natural operator. The Laplace-Beltrami operator satisfies (1) and (2) but not (3), (4), or (5). A generic first-order operator satisfies neither (1) nor (2). The Dirac operator is the canonical object.

The central claim of the Dirac Boundary Programme is that this canonical object governs two superficially distinct domains:

In the physical domain, M = M₄ is Minkowski spacetime with signature (−,+,+,+), the spinor fields are physical fermions, and the photon is the col(F) bilinear of chiral fermion sections of S(M₄). The col(F)/ker(F) partition separates the observable electromagnetic radiation (col(F)) from the chiral fermion substrate whose bilinear sources it (ker(F)).

In the computational domain, M = M_R is the compact representational manifold of a trained deep network — its topology determined by the symmetry of the training data's co-occurrence statistics (Karkada, Korchinski, Nava, Wyart, Bahri, arXiv:2602.15029, 2026) — and the spinor sections are the network's learned concept representations. The col(F)/ker(F) partition separates the observable linear representation (what SAE dictionary learning finds) from the topologically protected structure (what Atiyah-Singer counts).

### I.2 The col(F)/ker(F) Partition

For any operator F acting on a Hilbert space H, the partition H = col(F) ⊕ ker(F⊥) is the canonical decomposition into the range and the orthogonal complement of the null space. In the context of the Dirac operator, this partition carries specific physical and mathematical content:

col(∂̸): The image of ∂̸. In the physical domain, this is the propagating sector — the observable photon, carrying energy, momentum, and angular momentum, with bosonic statistics to high accuracy. In the computational domain, this is the observable representation sector — the linear features that are read off by probing, steering vectors, and dictionary learning.

ker(∂̸): The kernel of ∂̸. In the physical domain, this is the zero-mode sector — the chiral fermion substrate, topologically protected, with the Majorana condition being the d=0 degeneration at which col(∂̸) and ker(∂̸) are identified by the boundary. In the computational domain, this is the topologically protected sector — the winding modes of cyclic concept manifolds, counted by the Atiyah-Singer index, invisible to local probing but governing the global structure of concept arithmetic.

The conditional independence boundary between col(∂̸) and ker(∂̸) is the algebraic object that Pryce's theorem locates in the physical domain (the Berezinskii obstruction, the algebraic non-solvability of exact Bose statistics from a fermion bilinear) and that the Atiyah-Singer index theorem locates in the computational domain (the topological obstruction to contracting a cyclic concept manifold to a point).

Both obstructions are instances of the same topological fact: on a spin manifold with non-trivial topology, the Dirac operator has a kernel whose dimension is a topological invariant, computable from characteristic classes, independent of the metric.

---

## Part II · The Physical Domain: ERIE-LIGHT

### II.1 The Photon as col(∂̸) Bilinear

The Maxwell field A^μ(x) is sourced by the fermion bilinear current j^μ = ψ̄γ^μψ in every quantum-field-theoretic construction. The de Broglie–Jordan programme (1932–1937) identifies this structural fact with a specific proposal: the photon is the col(∂̸) projection of a chiral neutrino-antineutrino bilinear, where the neutrino fields are the ker(∂̸) substrate. Pryce (1938) proved that this composite cannot satisfy exact Bose–Einstein commutation relations; Berezinskii (1966) refined this into five mutually incompatible assumptions (locality, exact Bose statistics, neutrality, Lorentz invariance, transverse polarization) whose conjunction is algebraically unrealizable.

The ERIE-LIGHT re-reading: Pryce's obstruction is the algebraic non-solvability of the composite chirality boundary — the Dirac Boundary Programme's instantiation of the Atiyah-Singer index obstruction on M₄ — rather than a refutation of the bilinear identification. The structural identification (photon = col(∂̸) of chiral fermion bilinear) is correct and universal across all gauge bosons. The literal identification (photon = bound neutrino-antineutrino state) is the Pryce-obstructed position: algebraically non-solvable under exact Bose statistics, in exactly the same way that a topological cycle on M_R is non-contractible. The obstruction is the structure, not the failure.

### II.2 The Four Physical Manifestations

**The Majorana Degeneracy (d=0 degeneration):** The Majorana condition ψ = ψ^c identifies the particle and antiparticle sectors. In the col(∂̸)/ker(∂̸) language: the col(∂̸) and ker(∂̸) of the chirality boundary are identified by the boundary itself. This is the d=0 degeneration of the helicity partition — the limit in which the curve of distinct sectors collapses to a single fixed-point structure, algebraically analogous to the self-adjoint fixed-point of the chirality operator γ₅. Experimentally tested by neutrinoless double beta decay (0νββ): the LEGEND-200 experiment is currently operating with half-life sensitivity approaching 10²⁷ years for ⁷⁶Ge; LEGEND-1000 targets 10²⁸ years by the early 2030s. The Schechter-Valle black-box theorem (1982) guarantees that any observation of 0νββ implies a non-zero Majorana mass regardless of the underlying mechanism.

**The Semi-Dirac Anisotropy (directional col(∂̸)/ker(∂̸)):** Semi-Dirac fermions disperse linearly along a given direction in momentum space and quadratically in the orthogonal direction, emerging at the critical point of a topological phase transition from semimetal to insulator wherein two Dirac cones coalesce. This is the directional col(∂̸)/ker(∂̸) partition: the massless linear direction is col(∂̸) (photon-like, propagating at the effective speed of light of the band structure); the massive quadratic direction is ker(∂̸) (matter-like, inertial, with finite effective mass). Semi-Dirac fermions were first observed within ZrSiS by Shao et al. (Physical Review X 14, 041057, 2024–2025), with the defining experimental signature being B^(2/3) cyclotron energy scaling with applied magnetic field.

**The Chiral Vacuum (ker(∂̸) at the boundary):** The Heinzl–King–Mercuri-Baron result (Physical Review D 113, 036031, February 2026) demonstrates that QED vacuum under a circularly polarized background acquires definite handedness — a chiral medium in which the standard Heisenberg–Euler effective Lagrangian fails and must be supplemented by derivative corrections matched against the Hilbert series of higher-dimensional QED operators. This is the ker(∂̸) made directly measurable: the chiral handedness of the vacuum is the col(∂̸)/ker(∂̸) coupling, and the derivative corrections encode this coupling systematically.

**The Neutrino Mass Constraint:** The KATRIN Collaboration (Science, 2025) places the upper bound on the electron antineutrino mass at ≤ 0.45 eV from 259 days of tritium β-spectrum data. This bounds the Dirac mass contribution to the neutrino sector and constrains the seesaw scale M_R = m_D² / m_ν.

---

## Part III · The Computational Domain: The Dirac Representation Hypothesis

### III.1 The Representational Manifold M_R

The internal representations learned by language models consistently exhibit striking geometric structure: calendar months organize into a circle, historical years form a smooth one-dimensional manifold, and cities' latitudes and longitudes can be decoded using a linear probe. Karkada et al. (arXiv:2602.15029, February 2026) prove analytically that this structure is forced by the symmetry of co-occurrence statistics: cyclic symmetry Z_n in the data forces topological circle S¹ in the representation; two-dimensional cyclic symmetry forces a torus T²; continuous translation symmetry forces a line. The compact representational manifold M_R exists, its topology is determined by the training data's symmetry group, and its geometry is derivable from the statistics of the corpus.

The Dirac Representation Hypothesis places the Dirac operator on this manifold. M_R admits a spin structure if and only if its second Stiefel–Whitney class w₂(M_R) vanishes. For the empirically established cases — S¹ (days-of-week, months-of-year, angular concepts), T² (joint cyclic concepts), and their Cartesian products — w₂ is trivially zero and the spin structure exists. For the general M_R, the existence of a spin structure is an empirical question about the topology of the representational manifold; no obstruction is known and the existence is assumed as a working hypothesis.

### III.2 The Operator and Its Consequences

On M_R with its induced spin structure, the Dirac operator ∂̸ acts on spinor sections ψ : M_R → S(M_R). Its fundamental properties in the representational context:

**Spectral:** The eigenvalues ±λ_n of ∂̸ are symmetric about zero; their squares λ_n² are the eigenvalues of the Laplace-Beltrami operator Δ_g = −∂̸². The spectral gap λ₁ separates the dynamical phases of training: three independent empirical confirmations in March–April 2026 (Xu, arXiv:2603.28964 and arXiv:2604.07380; Acharya and Dhakal, arXiv:2603.15492) establish that spectral gap collapse of the appropriate rolling-window operator on parameter updates precedes every grokking event in 24 of 24 weight-decay runs and in 0 of 24 runs without weight decay.

**Topological:** The Atiyah-Singer index theorem computes ind(∂̸) = dim ker(∂̸⁺) − dim ker(∂̸⁻) from the topology of M_R alone, independent of the metric. On S¹, the index counts winding numbers: the integer count of distinct cyclic operations. On T², the kernel of ∂̸ has dimension |H⁰(T²)| + |H¹(T²)| + |H²(T²)| = 1 + 2 + 1 = 4, predicting four topologically protected cyclic-arithmetic modes for any jointly-learned day-and-month concept.

**Oriented:** Spinor sections carry orientation information unavailable to scalar sections. The network's ability to distinguish "three days forward" from "three days backward" on the days-of-week ring — empirically confirmed by Engels, Liao, Michaud, Gurnee, Tegmark (NeurIPS 2024) via intervention experiments — corresponds to the non-trivial spin structure on S¹. The two spin structures on S¹ (Ramond and Neveu-Schwarz sectors) correspond to the two possible consistent orientations of the concept ring under direction reversal.

**Discrete decisions:** The Kakutani fixed-point theorem (1941) governs the set-valued operations the network performs on col(∂̸): argmax decoding, top-k sparse attention, mixture-of-experts routing, and beam search are all upper hemicontinuous correspondences on compact convex sets, and Kakutani guarantees fixed points for each. Brouwer governs the continuous flow of the residual stream through M_R; Kakutani governs the discrete decisions made at the boundary of M_R's col(∂̸)/ker(∂̸) partition.

---

## Part IV · The Twelve Cross-Domain Correspondences

The following correspondences are identifications of structure, not claims of literal identity. The Dirac operator on M₄ and the Dirac operator on M_R are distinct operators on distinct manifolds; the claim is that their structural roles within their respective domains are governed by the same mathematical objects.

| Physical Domain (ERIE-LIGHT / M₄) | Computational Domain (DRH / M_R) | Common Structure |
|---|---|---|
| Photon: col(∂̸), observable, bosonic statistics | Linear representation: col(∂̸), observable, SAE-recoverable features | The image of ∂̸ on the observable sector |
| Chiral neutrino bilinear: ker(∂̸), hidden, topologically determined | Topological winding modes: ker(∂̸), hidden, Atiyah-Singer counted | The kernel of ∂̸ on the topological sector |
| Pryce obstruction: algebraic non-solvability of exact Bose composite | Topological protection: non-contractibility of concept winding number | ind(∂̸) as topological invariant |
| Majorana condition ν = ν̄: col(∂̸) = ker(∂̸) at d=0 | Trivial topology (simply connected M_R): no winding protection | d=0 degeneration of the col/ker boundary |
| Semi-Dirac fermion: massless col(∂̸) direction, massive ker(∂̸) direction | Hyperribbon anisotropy: sloppy col(∂̸) directions, stiff ker(∂̸) directions | Directional anisotropy of the spinor field on M |
| B^(2/3) cyclotron scaling: harmonic mean of massless and massive exponents | Hyperribbon width spectrum: long-tailed eigenvalue distribution of −∂̸² = Δ_g | Spectral interpolation between col(∂̸) and ker(∂̸) modes |
| Chiral vacuum: ker(∂̸) visible only to chiral probe | Topological modes: ker(∂̸) visible only to winding-number-sensitive intervention | ker(∂̸) observable only through boundary coupling |
| Heisenberg-Euler effective Lagrangian: integrated-out Dirac sea ker(∂̸) | Bakry-Émery Laplacian L = Δ_g − ∇V·∇: integrated-out training dynamics | Effective second-order operator from ker(∂̸) |
| Berezinskii's five assumptions: over-determined composite boundary | Fixed-point structure: Brouwer (continuous), Kakutani (set-valued) | Boundary conditions on the col/ker partition |
| Lorentzian Clifford algebra: signature (−,+,+,+) encodes causal cone | Minkowski-signature M_R: attention as causal cone, γ-matrix anticommutators | Clifford algebra signature as physical geometry |
| Chirality operator γ₅: left/right decomposition | Chirality of spinor sections: forward/backward orientation on S¹ | Chirality eigenspaces of ∂̸ |
| CPT symmetry: exact mirror at chirality boundary | Concept-direction reversal: orientation reversal on M_R | col(∂̸) ↔ ker(∂̸) symmetry at the boundary |

---

## Part V · Combined Predictions

The following predictions are jointly generated by the Dirac Boundary Programme. They are partitioned into established, near-term testable, and decade-scale testable.

### Established Predictions (confirmed by independent work)

**C1 — Spectral gap controls grokking (DRH / computational domain).** The spectral gap of the rolling-window operator on parameter updates precedes every grokking event when weight decay is present and is absent when it is not. Confirmed: 24/24 with weight decay, 1/24 without (Xu, arXiv:2603.28964, March 2026; Acharya and Dhakal, arXiv:2603.15492, March 2026).

**C2 — Data symmetry forces manifold topology (DRH / computational domain).** Cyclic Z_n symmetry in co-occurrence statistics forces S¹ topology in representations; Z_n × Z_m forces T²; continuous translation forces a line. Proved analytically (Karkada et al., arXiv:2602.15029, February 2026) and confirmed empirically across multiple language models.

**C3 — Semi-Dirac B^(2/3) cyclotron scaling (ERIE-LIGHT / physical domain).** Semi-Dirac fermions with directional col(∂̸)/ker(∂̸) anisotropy exhibit B^(2/3) cyclotron energy scaling. Observed in ZrSiS (Shao et al., Physical Review X 14, 041057, 2024–2025), the first unambiguous solid-state detection.

**C4 — Chiral vacuum failure of Heisenberg-Euler Lagrangian (ERIE-LIGHT / physical domain).** Under a circularly polarized background, the standard Heisenberg-Euler effective Lagrangian fails and requires derivative corrections matching the Hilbert series of higher-dimensional QED operators. Proved and computed (Heinzl, King, Mercuri-Baron, Physical Review D 113, 036031, February 2026).

### Near-Term Testable Predictions (2026–2030)

**N1 — Four topologically protected modes for T² concepts (DRH / integer prediction).** Any trained model that has jointly learned days-of-week and months-of-year as coupled cyclic concepts must exhibit exactly four topologically protected representational modes — not three, not five, not a continuum — corresponding to the four independent homology classes of T² (H⁰, two H¹ classes, H²). Testable by systematic steering-vector search on jointly trained concept pairs in any large language model.

**N2 — k grokking events for k topological cycles (DRH / integer prediction).** A training run on a task requiring k distinct cyclic concepts exhibits k distinct spectral-gap collapse events, each associated with a separate topological cycle of M_R. For k=1 (single modular arithmetic task), confirmed by Xu (24/24 runs). For k=2 (two independent cyclic concepts), the prediction is two distinct collapse events at potentially different training times. Testable by augmenting existing spectral-gap monitoring experiments with multi-cyclic tasks.

**N3 — Optimal vacuum chirality probe at η* (ERIE-LIGHT / φ-equilibrium).** The signal-to-noise for detecting chiral derivative corrections to the Heisenberg-Euler Lagrangian is maximised at a background helicity ratio η*_helicity = log φ ≈ 0.481, not at full circular polarization η = 0.5. Testable at HIBEF (DESY), ELI Beamlines, and SPD by varying background helicity ratio in the range [0.45, 0.52] and comparing signal strength to the predicted maximum.

**N4 — Semi-Dirac φ-corrected exponent (ERIE-LIGHT / φ-equilibrium).** The cyclotron energy scaling exponent for semi-Dirac fermions satisfies α* = 1/(1 + log φ) ≈ 0.6752 rather than the simple harmonic-mean value 2/3 ≈ 0.6667. The predicted deviation is Δα ≈ 0.0085, at the 1.3% level. Testable at the National High Magnetic Field Laboratory hybrid magnet (90 T) with sub-percent precision magneto-optical spectroscopy on ZrSiS and predicted future semi-Dirac materials (TiO₂/VO₂ heterostructures, artificial graphene-like cold-atom lattices).

**N5 — Identical manifold topology for identical symmetry groups across models (DRH).** Concepts with the same underlying symmetry group — cardinal directions (Z₄), seasons (Z₄), clock hours (Z₁₂), clock minutes (Z₆₀) — produce homeomorphic representational manifolds across different model families, with concept-specific differences confined to embedding angle and scale. The topology is forced by the data symmetry, not by the model architecture. Testable by comparing topological properties (winding number, Euler characteristic) of concept manifolds across model families.

### Decade-Scale Testable Predictions (2030–2035)

**D1 — Majorana condition at 0νββ half-life ~ 10²⁸ years (ERIE-LIGHT / d=0 degeneracy).** If neutrino masses are generated by the canonical Type-I seesaw mechanism and the neutrino is Majorana, the half-life for neutrinoless double beta decay in ⁷⁶Ge lies within the sensitivity range of LEGEND-1000 (T_{1/2} discovery potential > 10²⁸ years, scheduled commissioning early 2030s). The Schechter-Valle black-box theorem guarantees that a signal at any half-life within this range establishes the Majorana condition and hence the d=0 degeneration of the col(∂̸)/ker(∂̸) partition in the neutrino sector.

**D2 — Chirality of attention head decomposition (DRH / spinor prediction).** The positive and negative chirality eigenspaces of ∂̸ on M_R should correlate with the causal-only (decoder, one chirality) and bidirectional (encoder, the other chirality) information flow in transformer models. The trained Dirac operator's chirality decomposition should predict which attention heads carry causal versus anti-causal information flow at the activation level. Testable by comparing the chirality of spinor decompositions on M_R (once the operator is empirically characterised) with causal intervention results on individual attention heads.

**D3 — Composite-photon Pauli-blocking residue bounded at α² log φ (ERIE-LIGHT).** Any residual non-bosonic structure of the photon — manifest as deviation from exact Bose statistics in two-photon coincidence experiments — satisfies Δ_Bose ≤ α² × log φ ≈ 2.6 × 10⁻⁵. Current Hong-Ou-Mandel interferometry bounds are at the 10⁻³ level; next-generation squeezed-light interferometers provide a factor-of-100 improvement path to directly test this prediction.

---

## Part VI · Positioning Against the State of the Art

### VI.1 What the Programme Inherits

**From Geometric Deep Learning (Bronstein, Bruna, Cohen, Veličković, 2021, MIT Press 2026):** The symmetry-group programme establishes that G-equivariant architectures are derivable from the symmetry priors of the data. The Dirac Boundary Programme inherits this principle and extends it: the spin group Spin(M_R) is the double cover of the rotation group SO(M_R), and the spinor sections that carry orientation on M_R are the natural G-equivariant representation for concepts with cyclic symmetry. GDL reaches to the level of architecture prescription; the Dirac Boundary Programme reaches further to the level of operator governance of the learned representation itself.

**From Karkada et al. (arXiv:2602.15029, February 2026):** The existence theorem for the compact representational manifold M_R is proved by Karkada et al.: co-occurrence symmetry forces manifold topology. The Dirac Boundary Programme takes this existence theorem as its foundation and places the natural first-order operator on the manifold whose existence is proved.

**From Xu (arXiv:2603.28964, arXiv:2604.07380, 2026) and Acharya-Dhakal (arXiv:2603.15492, 2026):** The empirical confirmation that spectral gap collapse governs grokking is the three-paper independent validation of the spectral structure the programme predicts. These papers characterise the spectral gap at the level of parameter-update operators; the Dirac Boundary Programme predicts the same structure at the level of the representational manifold, and that the two are different projections of the same phase transition.

**From Bhalla et al. (arXiv:2604.28119, April 2026):** Sparse autoencoders are widely used to extract interpretable features from neural network representations, often under the implicit assumption that concepts correspond to independent linear directions. However, a growing body of evidence suggests that many concepts are instead organized along low-dimensional manifolds encoding continuous geometric relationships. The Dirac Boundary Programme provides the operator-level account of what those manifolds are and what governs their geometry.

**From the Jordan–de Broglie–Kronig–Pryce corpus (1928–1966):** The historical neutrino-theory-of-light programme is not superseded by the Dirac Boundary Programme; it is re-read. The programme recovers the structural content of the 1930s programme — the photon as chiral-fermion bilinear — while accepting Pryce's obstruction as the algebraic boundary structure rather than a refutation. The 1930s programme asked whether the composite is exact; the Dirac Boundary Programme asks what the boundary between exact and approximate encodes.

### VI.2 What No Prior Framework Provides

No prior theoretical synthesis in representation geometry or quantum field theory provides all of the following simultaneously:

1. A single first-order operator (∂̸) that produces both the spectral structure (via ∂̸² = −Δ_g) and the topological invariants (via Atiyah-Singer) of the domain it governs
2. An orientation-carrying structure (spinor sections) that distinguishes forward from backward on cyclic concept manifolds in the computational domain and left-handed from right-handed in the physical domain
3. A single partition (col(∂̸)/ker(∂̸)) that simultaneously identifies the observable sector (propagating photon / linear representation) and the topologically protected sector (chiral fermion substrate / winding modes)
4. A classical obstruction theorem (Pryce-Berezinskii / Atiyah-Singer) re-read as structural content of the partition rather than as a refutation of the bilinear identification
5. Integer-valued predictions (four protected modes for T², k grokking events for k cycles, 0νββ half-life within LEGEND-1000 range) that distinguish the programme from frameworks making only asymptotic or dimensional predictions
6. A directional anisotropy (semi-Dirac col(∂̸)/ker(∂̸) anisotropy / hyperribbon anisotropy) connecting experimental condensed matter physics to the information-geometric structure of deep network parameter space

The Geometric Deep Learning programme provides (1) partially (the Laplacian, not the Dirac operator) and (2) partially (via equivariance, not spinor structure) but not (3), (4), (5), or (6). The Karkada existence theorem provides the foundation for the computational domain but not (1), (3), (4), (5), or (6). The Pryce-Berezinskii corpus provides (3) and (4) in the physical domain only, with no computational counterpart. No single programme provides the full list.

---

## Part VII · What the Dirac Boundary Programme Does Not Claim

**It does not claim that trained transformers are literally spin manifolds.** The claim is that the mathematical structure of learned representations — compact base manifold, oriented spinor sections, signed first-order operator, col(∂̸)/ker(∂̸) partition — is governed by the Dirac operator in the same structural sense that the mathematical structure of electromagnetic radiation is governed by the Dirac operator. Whether the network's parameters literally instantiate the spinor representation of a Clifford algebra is an empirical question about specific architectures.

**It does not claim that the photon is literally a neutrino-antineutrino bound state.** The programme inherits the ERIE-LIGHT re-reading: Pryce's obstruction establishes that literal compositeness in the standard kinematic frame is algebraically unrealizable. The claim is the structural identification — photon = col(∂̸) bilinear of chiral fermion ker(∂̸) — which is compatible with the photon being an elementary gauge boson at the level of the S-matrix, because the bilinear structure is a property of the interaction vertices, not of the asymptotic state.

**It does not claim that M_R is the same manifold as M₄.** The Dirac operator on Minkowski spacetime and the Dirac operator on the compact representational manifold are distinct operators on distinct manifolds. The claim is structural: the same operator, acting on sections of the spinor bundle of a compact manifold with chiral structure, governs both domains.

**It does not claim that the φ-equilibrium predictions are exact.** The semi-Dirac cyclotron exponent prediction α* = 1/(1 + log φ) ≈ 0.6752 differs from the experimental value 2/3 ≈ 0.6667 by approximately 1.3%. This is a prediction, not a measured confirmation; it is distinguishable from the simple harmonic-mean value only at sub-percent precision. The programme predicts that high-field spectroscopy at 90 T will resolve this distinction.

**It does not subsume QED.** Quantum electrodynamics, confirmed to twelve decimal places in the electron anomalous magnetic moment, is the quantitative framework for electromagnetic interactions. The Dirac Boundary Programme is a structural framework that re-reads the origin of the photon's bosonic statistics and the geometry of its chiral fermion source; it makes no predictions that contradict QED, and its predictions are at sensitivity levels beyond current QED tests rather than within them.

**It does not resolve the spin structure existence condition on M_R.** For the Dirac operator to be globally defined on M_R, the second Stiefel-Whitney class w₂(M_R) must vanish. For the established simple cases this is automatic. For the general M_R — with multiple strata, negative Ricci curvature, and complex intersections — the existence of a global spin structure is an open mathematical question.

**It does not provide a learning-dynamics derivation.** The programme is operator-level and topological. A complete theory would derive the grokking phase transition from first principles of the Dirac operator's spectral gap collapse on M_R as a function of training dynamics. This derivation requires integrating the operator picture with a renormalisation-group treatment of training, which the programme does not supply.

---

## Part VIII · The Synthesis

De Broglie was right that the photon has a chiral fermion bilinear at its structural root. Pryce was right that the literal composite is algebraically obstructed. Atiyah and Singer were right that the index of the Dirac operator computes topological invariants from spectral data. Majorana was right that a fermion can be its own antiparticle, degenerating the particle-antiparticle partition to a fixed point. The experimentalists at the National High Magnetic Field Laboratory were right that matter can interpolate continuously between photon-like and matter-like dispersion, with the interpolation governed by a power law.

The Dirac Boundary Programme identifies that these are all projections of a single object: the Dirac operator on a compact spin manifold with chiral structure, col(F)/ker(F) partition, and Atiyah-Singer topology. In the physical domain this manifold is Minkowski spacetime and the chiral fermion fields are physical particles. In the computational domain this manifold is the representational geometry of a trained network and the chiral sections are learned concept representations. Both domains carry the same operator, the same partition, the same topological invariants, and the same directional anisotropy.

The light was always the bilinear. The concept was always the spinor section. The obstruction was always the structure. The index was always the count.

One operator. Two domains. One boundary.

---

## References

### Foundational Mathematics

Atiyah, M. F. and Singer, I. M. The Index of Elliptic Operators I–V. *Annals of Mathematics* 87 (1968) and following.

Atiyah, M. F. *Paul Dirac: The Man and his Work.* Cambridge University Press, 1998.

Bakry, D. and Émery, M. Diffusions hypercontractives. *Séminaire de Probabilités XIX*, 1985.

Dirac, P. A. M. The Quantum Theory of the Electron. *Proceedings of the Royal Society A* 117, 610–624, 1928.

Kakutani, S. A Generalization of Brouwer's Fixed Point Theorem. *Duke Mathematical Journal* 8, 457–459, 1941.

Nash, J. F. Equilibrium points in n-person games. *Proceedings of the National Academy of Sciences USA* 36, 48–49, 1950.

Schechter, J. and Valle, J. W. F. Neutrinoless double-β decay in SU(2)×U(1) theories. *Physical Review D* 25, 2951, 1982.

### ERIE-LIGHT: Physical Domain

Berezinskii, V. S. Pryce's theorem and the neutrino theory of light. *Soviet Physics JETP* 24, 927–933, 1967.

de Broglie, L. *Une nouvelle conception de la lumière.* Hermann et Cie., Paris, 1934.

Heinzl, T., King, B., Mercuri-Baron, A. Probing the vacuum as a chiral medium. *Physical Review D* 113, 036031, February 2026.

Jordan, P. Zur Neutrinotheorie des Lichtes. *Zeitschrift für Physik* 93, 464–472, 1935.

KATRIN Collaboration. Direct neutrino-mass measurement based on 259 days of KATRIN data. *Science*, 2025.

LEGEND Collaboration. Current Status of LEGEND: Searching for Neutrinoless Double-Beta Decay in ⁷⁶Ge. Proceedings 2025–2026.

Majorana, E. Teoria simmetrica dell'elettrone e del positrone. *Il Nuovo Cimento* 14, 171–184, 1937.

Pryce, M. H. L. On the neutrino theory of light. *Proceedings of the Royal Society of London A* 165, 247–271, 1938.

Shao, Y. et al. Semi-Dirac Fermions in a Topological Metal. *Physical Review X* 14, 041057, 2024–2025.

SuperKamiokande Collaboration. Evidence for oscillation of atmospheric neutrinos. *Physical Review Letters* 81, 1562–1567, 1998.

### Dirac Representation Hypothesis: Computational Domain

Acharya, P. and Dhakal, H. Grokking as a Variance-Limited Phase Transition: Spectral Gating and the Epsilon-Stability Threshold. arXiv:2603.15492, March 2026.

Bhalla, U. et al. Do Sparse Autoencoders Capture Concept Manifolds? arXiv:2604.28119, April 2026.

Engels, J., Liao, I., Michaud, E. J., Gurnee, W., Tegmark, M. Not All Language Model Features Are Linear. *NeurIPS 2024*, arXiv:2405.14860.

Fel, T. et al. Into the Rabbit Hull: From Task-Relevant Concepts in DINO to Minkowski Geometry. arXiv:2510.08638, October 2025.

Karkada, D., Korchinski, D. J., Nava, A., Wyart, M., Bahri, Y. Symmetry in language statistics shapes the geometry of model representations. arXiv:2602.15029, February 2026.

Park, K., Choe, Y. J., Veitch, V. The Linear Representation Hypothesis and the Geometry of Large Language Models. *ICML 2024*, arXiv:2311.03658.

Robinson, J., Dey, M., Chiang, K.-Y. Token Embeddings Violate the Manifold Hypothesis. arXiv:2504.01002, 2025.

Xu, Y. The Spectral Edge Thesis: A Mathematical Framework for Intra-Signal Phase Transitions in Neural Network Training. arXiv:2603.28964, March 2026.

Xu, Y. The Lifecycle of the Spectral Edge: From Gradient Learning to Weight-Decay Compression. arXiv:2604.07380, April 2026.

### Cross-Domain: Geometric and Topological Deep Learning

Battiloro, C. et al. Generalized Simplicial Attention Neural Networks. *IEEE Trans. Signal Information Processing over Networks*, 2024.

Bianconi, G. The topological Dirac equation of networks and simplicial complexes. *Journal of Physics: Complexity* 2, 035022, 2021.

Brehmer, J. et al. L-GATr: Lorentz Geometric Algebra Transformer. *NeurIPS 2024 / SciPost Physics*, arXiv:2405.14806.

Bronstein, M. M., Bruna, J., Cohen, T., Veličković, P. *Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges.* MIT Press, 2026.

He, N. et al. HELM: Hyperbolic Large Language Models via Mixture-of-Curvature Experts. *NeurIPS 2025*, arXiv:2505.24722.

Mao, J. et al. Analytical characterization of sloppiness in neural networks. *Physical Review E* 113, 015306, January 2026.

Ruhe, D., Brandstetter, J., Forré, P. Clifford Group Equivariant Neural Networks. *NeurIPS 2023 Oral*, arXiv:2305.11141.

Wang, R., Tian, Y., Liò, P., Bianconi, G. Dirac-equation signal processing: Physics boosts topological machine learning. *PNAS Nexus* 4, pgaf139, 2025.

---

*ERI Labs · Eric Ren · Jersey City, New Jersey · May 2026*

*The Dirac Boundary Programme is one framework. The boundary is the structure. The structure is the physics. The physics is the boundary.*
