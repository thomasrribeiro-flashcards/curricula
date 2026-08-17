# Physics learning roadmap

## Learner and destination

Detailed learner and convention decisions live in `SUBJECT_BRIEF.md`. This file
explains the deck sequence; `subject.toml` is the executable source of truth.

- Long-term capabilities: describe and measure physical situations with explicit
  units, uncertainty, and stated idealizations; choose a system, frame, and sign
  convention; predict qualitatively before calculating; select among competing
  models and state each model's regime of validity; translate among situations,
  diagrams, graphs, words, equations, and code; reason about evidence and
  systematic error; and navigate the literature of at least one research branch.
- Requested destination: **whole-field** — a navigable map of the major domains
  and contemporary branches of physics across learning levels, from first
  contact through representative graduate and research-specialization work.
- Focus branches: **none specified.** The route therefore ends in seven
  *representative* research branches selected from evidence of current field
  activity, not from preference. If a real target subfield is confirmed later,
  that branch should be promoted and the rest demoted to `deferred`.
- Deck granularity: **course** — one deck is one coherent course-scale
  capability, planning-estimated at 6–14 ordered chapters.
- Assumed inbound knowledge: **none.** Force, energy, velocity, vectors, fields,
  and oscillators are treated as unseen technical vocabulary, and every
  mathematical capability is imported explicitly from the `mathematics` subject.

## How this map was derived

The domain inventory was built before any deck was named, from five independent
partitions of the field rather than from one syllabus:

1. **APS PhySH**, the current successor to PACS, as the field's own authoritative
   discipline vocabulary.
2. **APS divisions and topical groups**, as a current community-structure check.
3. **arXiv's category taxonomy and submission-by-category report**, as a
   non-prescriptive activity check; no exact volume ranking is used to create an
   edge or deck.
4. **NSF Division of Physics program areas**, as a funded-breadth check.
5. **US National Academies decadal and strategic reports** — Astro2020, EPP-2024,
   the 2023 P5 report, the 2023 NSAC Long Range Plan, the 2021 plasma decadal,
   the 2022 *Physics of Life* report, and the 2020 AMO decadal — to choose the
   seven representative research branches.

Curricular shape came from the **QAA Physics, Astronomy and Astrophysics Subject
Benchmark Statement (April 2025)**, **Phys21 (APS/AAPT J-TUPP)**, the **AAPT
laboratory and computational-physics recommendations**, and the **IOP Degree
Accreditation Framework (July 2022, still linked by IOP in 2026)**. These are
outcome-based rather than prescriptive, which is why this roadmap is organized by
capability and prerequisite edge rather than by textbook chapter order. Current
MIT and Berkeley doctoral-core requirements and Cambridge Part III preparation
guidance were used only to stress-test maturity transitions. Full URLs,
authorities, licenses or terms, and access dates are registered in
`SUBJECT_BRIEF.md`.

### Independent redesign audit and identity decisions

The 2026-08-17 audit preserved all 42 proposed deck ids: every deck still names a
coherent retrieval scope, and no approved or active deck exists to constrain a
necessary correction. Three changes repair dependency or coherence defects
without changing identity:

- `analytical-mechanics` remains `undergraduate-advanced`, but is now explicitly
  recognized as the advanced classical-mechanics capability also expected by
  current graduate cores; a duplicate graduate deck would repeat the same
  formalism and practice portfolio.
- `electronics-and-instrumentation` is narrowed to the coherent electronic
  measurement signal chain. Vacuum and cryogenic shop competence remain authentic
  practice outside SRS and may later justify technique-specific decks; they no
  longer share a repository merely because they occur in laboratories.
- `living-and-active-matter-research` now directly requires
  `soft-matter-and-complex-fluids`, because literature-facing active-matter
  hydrodynamics may not assume continuum, rheological, and active-matter grammar
  from `biological-physics` alone. The unrelated gravitational-wave sequencing
  recommendation was removed from the collider branch.

Where a domain appears in the field map but not in a deck, the coverage matrix
below records whether it is deferred (a future extension point) or out of scope
(owned by a different subject or not physics content at all).

## Field coverage

Every material domain is included, deliberately deferred, or explicitly out of
scope. This matrix is generated from the `[[coverage]]` entries in
`subject.toml`.

| Domain | Disposition | Decks | Rationale |
|---|---|---|---|
| measurement-units-and-physical-reasoning | included | `measurement-and-physical-reasoning`, `measurement-uncertainty-and-experimental-physics` | First contact must begin with observable comparison, units, scale, and uncertainty rather than force or energy, because a cold-start learner has no physics vocabulary at all. |
| classical-mechanics | included | `motion-forces-and-energy`, `classical-mechanics` | Split by mathematical maturity rather than topic: the foundational deck establishes the physical vocabulary algebraically, the undergraduate deck rebuilds it with calculus and vectors. |
| analytical-and-hamiltonian-mechanics | included | `analytical-mechanics` | Variational and Hamiltonian structure is the machinery that quantum field theory and general relativity actually reuse, so it is a separate deck rather than trailing chapters of classical mechanics. |
| continuum-mechanics-and-elasticity | included | `continuum-mechanics-and-fluid-dynamics` | Stress, strain, and elasticity share a spine with fluid mechanics and are the prerequisite grammar for soft matter and geophysical applications. |
| fluid-dynamics | included | `continuum-mechanics-and-fluid-dynamics` | QAA names fluids as a major application area and APS maintains a dedicated fluid-dynamics community; the shared continuum balance-law spine warrants course-scale treatment rather than a passing chapter. |
| nonlinear-dynamics-and-chaos | included | `analytical-mechanics`, `continuum-mechanics-and-fluid-dynamics` | These decks own the physical instances—Hamiltonian chaos, instability, and transition to turbulence. The broader rigorous theory remains in mathematics/dynamical-systems-and-ergodic-theory and is not a hard prerequisite for learning those physical cases. |
| oscillations-and-waves | included | `waves-sound-and-light`, `classical-mechanics` | Wave phenomena are named as a fundamental area by the IOP accreditation framework and are the shared representational grammar for optics, quantum mechanics, and field theory. |
| acoustics | included | `waves-sound-and-light` | Sound is covered as the accessible instance of wave propagation. Research-level acoustics, an APS division in its own right, is deferred with the other applied branches. |
| geometrical-and-physical-optics | included | `waves-sound-and-light`, `optics-and-photonics` | Ray and image reasoning belongs at the foundational level; coherence, Fourier diffraction, and polarization require the electromagnetic field description. |
| photonics-lasers-and-laser-science | included | `optics-and-photonics`, `atomic-molecular-and-optical-physics` | QAA names advanced and applied optics among the field's major application areas, while current NSF and APS structures place light-matter control across AMO, quantum information, metrology, and gravitational-wave instrumentation. |
| thermodynamics | included | `matter-fluids-and-thermal-behavior`, `thermodynamics-and-statistical-mechanics` | Temperature, heat, and phase change are introduced phenomenologically before the state-function formalism, because heat and temperature are a documented interference pair. |
| statistical-physics | included | `thermodynamics-and-statistical-mechanics`, `statistical-physics` | PhySH treats Statistical Physics and Thermodynamics as one discipline; the undergraduate deck establishes ensembles and the graduate deck adds criticality and the renormalization group. |
| nonequilibrium-and-stochastic-physics | included | `statistical-physics`, `soft-matter-and-complex-fluids`, `biological-physics` | Langevin and Fokker-Planck dynamics, linear response, and fluctuation theorems are the working tools of soft and living matter, so they are established once and applied in both branches. |
| electricity-magnetism-and-circuits | included | `electricity-magnetism-and-circuits`, `electronics-and-instrumentation` | Circuit reasoning is both an introductory domain and the practical basis of the measurement chain that Phys21 names as instrumentation competency. |
| electromagnetic-fields-and-radiation | included | `electromagnetic-theory`, `advanced-electromagnetic-theory` | Maxwell theory is required by every accreditation framework consulted and is the classical field theory that quantum field theory generalizes. |
| electronics-instrumentation-and-detectors | included | `electronics-and-instrumentation` | Phys21 section B.3 treats instrumentation as a distinct competency and NSF funds Advanced Physics Instrumentation as a cross-cutting program; it is not a byproduct of coursework. |
| special-relativity | included | `special-relativity` | Cambridge Part III and Berkeley preliminary examinations both assume special relativity on entry, and it gates electromagnetic theory, subatomic physics, and general relativity. |
| gravitation-and-general-relativity | included | `general-relativity` | Published prerequisites for graduate general relativity are unusually light, so it forms its own branch off classical field theory rather than sitting behind quantum mechanics. |
| cosmology | included | `astrophysics-and-cosmology`, `relativistic-astrophysics-and-cosmology` | The observational standard model is reachable at undergraduate level; perturbation theory, the Boltzmann hierarchy, and inflation require general relativity and graduate statistical physics. |
| astrophysics-and-astronomy | included | `astrophysics-and-cosmology`, `relativistic-astrophysics-and-cosmology`, `gravitational-wave-and-multimessenger-astrophysics` | QAA treats astrophysical application as a major degree route, NSF maintains gravitational and particle-astrophysics programs, and Astro2020 makes time-domain and multimessenger discovery a headline priority. |
| quantum-foundations-and-quantum-mechanics | included | `quantum-phenomena-and-atomic-structure`, `quantum-mechanics`, `advanced-quantum-mechanics` | Three levels are needed because the evidence for quantization, the wave-mechanical formalism, and the Hilbert-space formalism are genuinely different retrieval capabilities. |
| quantum-field-theory | included | `quantum-field-theory` | Published graduate prerequisites for a first field theory course reduce to graduate quantum mechanics plus Lagrangian field structure, so it is reachable without the whole graduate core. |
| quantum-information-science-and-technology | included | `quantum-information-and-computation`, `quantum-computing-and-simulation-research` | Attested three ways as a first-class field: a PhySH discipline, an APS division, and a standalone NSF PHY program. Treating it as an elective application would misrepresent the current field. |
| atomic-molecular-and-optical-physics | included | `atomic-molecular-and-optical-physics` | The 2020 AMO decadal survey frames the field around coherent control of quantum systems, which also feeds the metrology and quantum-technology branches. |
| condensed-matter-and-solid-state-physics | included | `condensed-matter-and-solid-state-physics`, `condensed-matter-theory` | QAA names hard and soft condensed matter and materials among major application areas, and PhySH and APS maintain distinct research structures for condensed matter, materials, polymers, and quantum materials. |
| quantum-materials-and-topological-phases | included | `condensed-matter-theory`, `quantum-matter-and-materials-research` | PhySH treats topological phases alongside magnetism and superconductivity, and APS maintains dedicated communities for condensed matter, materials physics, and quantum-materials synthesis. |
| soft-matter-and-polymer-physics | included | `soft-matter-and-complex-fluids` | PhySH keeps Polymers and Soft Matter as a distinct discipline with its own APS divisions; it is separated from biological physics because the two have different capstone performances. |
| biological-physics-and-physics-of-living-systems | included | `biological-physics`, `living-and-active-matter-research` | The 2022 National Academies report Physics of Life declares biological physics a fully emerged field of physics, and PhySH renamed the discipline to match the NSF program. |
| nuclear-physics | included | `nuclear-and-particle-physics` | Nuclear structure, decay, reactions, and astrophysical nucleosynthesis are covered at survey depth. A dedicated graduate nuclear deck covering effective field theory, hadronic structure, and the Electron-Ion Collider program is a named extension point rather than part of this route. |
| particle-physics-and-fundamental-interactions | included | `nuclear-and-particle-physics`, `particle-physics-and-the-standard-model`, `collider-and-precision-frontier-particle-physics` | The current NSF structure, the P5 report, and EPP-2024 all treat fundamental interactions as a major research program with a mature undergraduate-to-research progression. |
| plasma-physics-and-fusion | included | `plasma-physics`, `fusion-and-high-energy-density-science` | The 2021 plasma decadal spans low-temperature, high-energy-density, space, and fusion plasmas, and inertial-confinement ignition has made energy-gain claims a live evidential question. |
| computational-physics-and-simulation | included | `computational-physics` | AAPT recommends introducing computation in the introductory course and reinforcing it throughout rather than isolating it, so this deck seeds the practice and every later deck carries code work outside the card set. |
| experimental-design-measurement-and-uncertainty | included | `measurement-uncertainty-and-experimental-physics` | Covers the six AAPT laboratory outcomes to the extent that retrieval practice can, while the roadmap records the apparatus work that cards cannot replace. |
| data-analysis-statistics-and-machine-learning-in-physics | included | `measurement-uncertainty-and-experimental-physics`, `computational-physics`, `physics-research-practice` | General statistical and machine-learning capability is imported from mathematics; these decks own physics-specific transfer such as systematic uncertainty, blinding, the look-elsewhere effect, reproducible pipelines, and critical provenance-aware use of AI-assisted tools. |
| mathematical-methods-of-physics | included | `mathematical-methods-for-physics` | Kept as a subject-specific bridge because the transfer itself needs teaching: index notation, Green functions for physical operators, and symmetry groups as physical statements are not what the mathematics decks deliver. |
| metrology-and-precision-measurement | included | `measurement-and-physical-reasoning`, `precision-measurement-and-quantum-sensing` | The post-2019 constant-based SI is introduced at first contact and revisited as a research frontier; metrology appears in PhySH, an APS topical group, and arXiv instrumentation yet is routinely absent from introductory sequences. |
| research-practice-ethics-and-communication | included | `physics-research-practice` | Explicitly inserted as a required layer so that no undergraduate survey leads directly into literature-facing work; every research-specialization deck depends on it. |
| accelerator-and-beam-physics | deferred | None | A PhySH discipline and an APS division, and NSF funds it as advanced instrumentation, but it needs its own electromagnetic and beam-dynamics treatment. Accelerators appear only as instruments inside the subatomic decks. Named extension point. |
| medical-physics | deferred | None | PhySH places medical physics under Physics of Living Systems and APS maintains a topical group, but competent treatment requires radiobiology, dosimetry, imaging, and clinical regulation that no deck in this route establishes. Named extension point. |
| physics-of-climate-and-earth-systems | deferred | None | An APS topical group and the subject of the 2021 Nobel Prize. Its prerequisite closure is nearly complete once continuum mechanics, fluid dynamics, thermodynamics, and radiative transfer are in place, which makes it a high-value first extension. |
| geophysics-space-and-atmospheric-physics | deferred | None | Well represented in the arXiv physics archive and in plasma space-weather research, but adding it now would broaden the route without strengthening any declared branch. Named extension point. |
| energy-science-and-technology | deferred | None | A genuinely new PhySH discipline that a pre-2020 taxonomy would miss. Fusion energy is covered through the plasma branch; storage, photovoltaics, and grid-scale conversion are not. Named extension point. |
| chemical-physics-and-physical-chemistry | deferred | None | Molecular structure and spectroscopy are covered inside the AMO deck. Reaction dynamics, electronic-structure methods, and statistical thermodynamics of solutions are deferred; biology/chemistry-for-living-systems supplies chemical literacy where a learner needs it sooner. |
| quantum-gravity-and-string-theory | deferred | None | Named in EPP-2024 as a long-horizon driver, but it requires quantum field theory and general relativity together and is not needed by the representative branches selected here. It is a natural later extension once both foundations exist. |
| history-and-philosophy-of-physics | deferred | None | Valuable for judging model status and superseded theories, and partly carried inside decks that label the Bohr atom and other superseded models as such. A dedicated deck is deferred rather than excluded. |
| networks-and-complex-systems | out-of-scope | None | A standalone PhySH discipline, but the general theory is already owned by mathematics/networks-and-complex-systems. Duplicating it here would recreate a broad external capability purely to make this roadmap look self-contained. |
| physics-education-research | out-of-scope | None | A PhySH discipline and an APS topical group, but it is education research about physics rather than physics content. Its findings inform how these decks are authored and are recorded in the subject brief instead. |

## Deck sequence

This is a prerequisite graph, not a textbook chapter list. Hard prerequisites are
required inbound knowledge and are inherited transitively; recommended
sequencing is helpful preparation that is *not* inherited. Each created deck
later records its inherited direct edges in its own `deck.toml`.

| Order | Deck | Level | Tier | Hard prerequisites | Recommended after | Est. chapters | Durable capabilities | Status |
|---:|---|---|---|---|---|---:|---|---|
| 1 | `measurement-and-physical-reasoning` | foundational | core | `mathematics/number-sense-and-arithmetic` | None | 8 | Describe physical situations with operational quantities, SI units, scale, proportional reasoning, graphs, uncertainty, and explicit models. | proposed |
| 2 | `motion-forces-and-energy` | foundational | core | `measurement-and-physical-reasoning`, `mathematics/elementary-algebra-and-functions` | None | 12 | Predict and explain the motion of everyday objects using kinematics, interactions and forces, momentum, energy, torque, and gravitation without calculus. | proposed |
| 3 | `matter-fluids-and-thermal-behavior` | foundational | core | `motion-forces-and-energy` | None | 9 | Explain the macroscopic behavior of solids, liquids, and gases through density, pressure, buoyancy, flow, temperature, heat, phase change, and the kinetic-molecular model. | proposed |
| 4 | `waves-sound-and-light` | foundational | core | `motion-forces-and-energy`, `mathematics/precalculus-and-trigonometry` | `matter-fluids-and-thermal-behavior` | 10 | Analyze oscillation, wave propagation, superposition, resonance, sound, reflection and refraction, image formation, and elementary interference and diffraction. | proposed |
| 5 | `electricity-magnetism-and-circuits` | foundational | core | `motion-forces-and-energy`, `mathematics/precalculus-and-trigonometry` | `waves-sound-and-light` | 11 | Reason about charge, electric and magnetic fields, potential, current, resistance, DC and AC circuits, induction, and electromagnetic waves at an algebra-based level. | proposed |
| 6 | `measurement-uncertainty-and-experimental-physics` | undergraduate-core | core | `measurement-and-physical-reasoning`, `mathematics/statistical-inference-and-data-analysis` | `motion-forces-and-energy`, `electricity-magnetism-and-circuits` | 9 | Design measurements, quantify and propagate uncertainty, separate random from systematic error, fit physical models to data, and report experimental claims honestly. | proposed |
| 7 | `computational-physics` | undergraduate-core | core | `motion-forces-and-energy`, `mathematics/mathematical-computing-and-experimentation`, `mathematics/single-variable-integral-calculus` | `measurement-uncertainty-and-experimental-physics` | 10 | Translate a physical model into code, choose scales and algorithms, integrate equations of motion, sample stochastic systems, visualize results, and validate a simulation against limits and conservation laws. | proposed |
| 8 | `classical-mechanics` | undergraduate-core | core | `motion-forces-and-energy`, `mathematics/differential-equations`, `mathematics/multivariable-and-vector-calculus` | `computational-physics` | 11 | Solve calculus-based dynamics: vector equations of motion, damped and driven oscillation, central forces and orbits, rigid-body rotation, non-inertial frames, and coupled normal modes. | proposed |
| 9 | `special-relativity` | undergraduate-core | core | `motion-forces-and-energy`, `mathematics/linear-algebra`, `mathematics/single-variable-differential-calculus` | `classical-mechanics` | 8 | Reason with relativity of simultaneity, Lorentz transformations, spacetime diagrams, the invariant interval, four-vectors, and relativistic energy and momentum. | proposed |
| 10 | `quantum-phenomena-and-atomic-structure` | undergraduate-core | core | `waves-sound-and-light`, `electricity-magnetism-and-circuits` | `special-relativity`, `classical-mechanics` | 10 | Interpret the experimental evidence for quantization: blackbody and photoelectric results, photons, matter waves, atomic spectra and energy-level diagrams, uncertainty, X-rays, radioactivity, and stimulated emission. | proposed |
| 11 | `thermodynamics-and-statistical-mechanics` | undergraduate-core | core | `matter-fluids-and-thermal-behavior`, `quantum-phenomena-and-atomic-structure`, `mathematics/multivariable-and-vector-calculus`, `mathematics/probability` | `classical-mechanics`, `computational-physics` | 12 | Connect macroscopic thermodynamic laws, entropy, and potentials to microscopic counting through ensembles, partition functions, equipartition, kinetic theory, and quantum statistics. | proposed |
| 12 | `electronics-and-instrumentation` | undergraduate-core | core | `electricity-magnetism-and-circuits`, `measurement-uncertainty-and-experimental-physics` | `computational-physics` | 10 | Build and debug a measurement signal chain: network analysis, filters, diodes and transistors, operational amplifiers, digital logic, sampling and data acquisition, transducers and detectors, grounding, shielding, noise, calibration, and fault isolation. | proposed |
| 13 | `mathematical-methods-for-physics` | undergraduate-advanced | core | `classical-mechanics`, `mathematics/complex-analysis`, `mathematics/partial-differential-equations` | `computational-physics`, `special-relativity` | 11 | Translate mathematical machinery into physics: index and tensor notation, curvilinear coordinates, Green functions, special functions and orthogonal expansions, distributions, contour methods, variational calculus, symmetry groups, and asymptotic approximation. | proposed |
| 14 | `electromagnetic-theory` | undergraduate-advanced | core | `electricity-magnetism-and-circuits`, `special-relativity`, `mathematics/partial-differential-equations` | `classical-mechanics`, `mathematical-methods-for-physics` | 12 | Work with Maxwell's equations as a field theory: boundary-value electrostatics, dielectric and magnetic media, induction, potentials and gauge, energy and momentum flux, wave propagation, and the covariant formulation. | proposed |
| 15 | `quantum-mechanics` | undergraduate-advanced | core | `quantum-phenomena-and-atomic-structure`, `mathematics/partial-differential-equations` | `classical-mechanics`, `mathematical-methods-for-physics`, `computational-physics` | 13 | Solve and interpret non-relativistic quantum mechanics: the Schrodinger equation, bound and scattering states in one dimension, operator formalism and Dirac notation, angular momentum, hydrogen, spin, identical particles, and perturbative and variational approximation. | proposed |
| 16 | `analytical-mechanics` | undergraduate-advanced | core | `classical-mechanics` | `mathematical-methods-for-physics` | 9 | Reformulate mechanics through variational principles: Lagrangians and constraints, Noether symmetry and conservation, Hamiltonians, Poisson brackets, canonical transformations, Liouville flow, action-angle variables, and the onset of Hamiltonian chaos. | proposed |
| 17 | `optics-and-photonics` | undergraduate-advanced | recommended | `electromagnetic-theory` | `quantum-mechanics`, `electronics-and-instrumentation` | 10 | Design and analyze optical systems using polarization, coherence, interference, Fourier diffraction theory, Gaussian beams, resonators, laser gain, detection, and introductory nonlinear optics. | proposed |
| 18 | `continuum-mechanics-and-fluid-dynamics` | undergraduate-advanced | recommended | `classical-mechanics`, `mathematics/partial-differential-equations` | `thermodynamics-and-statistical-mechanics`, `computational-physics` | 11 | Treat matter as a continuum: stress and strain, elasticity, Euler and Navier-Stokes equations, vorticity, potential flow, dimensionless similarity, boundary layers, waves in fluids, instability, and the route to turbulence. | proposed |
| 19 | `condensed-matter-and-solid-state-physics` | undergraduate-advanced | recommended | `quantum-mechanics`, `thermodynamics-and-statistical-mechanics` | `mathematical-methods-for-physics` | 12 | Explain the properties of solids from structure: crystal and reciprocal lattices, diffraction, phonons and thermal behavior, free-electron and band theory, semiconductors, magnetism, superconductivity, and the role of defects and disorder. | proposed |
| 20 | `nuclear-and-particle-physics` | undergraduate-advanced | recommended | `quantum-mechanics`, `special-relativity` | `electronics-and-instrumentation`, `mathematical-methods-for-physics` | 12 | Survey subatomic matter: nuclear size and binding, liquid-drop and shell models, decay and reaction kinematics, cross sections, fission and fusion, detection, conservation laws and symmetries, quarks and leptons, and the Standard Model picture. | proposed |
| 21 | `astrophysics-and-cosmology` | undergraduate-advanced | recommended | `quantum-mechanics`, `thermodynamics-and-statistical-mechanics`, `electromagnetic-theory` | `measurement-uncertainty-and-experimental-physics`, `computational-physics` | 13 | Infer astrophysical properties from light: magnitudes and spectra, radiative transfer, stellar structure and evolution, nucleosynthesis, compact objects, the interstellar medium, galaxies, cosmic expansion, and the standard cosmological model. | proposed |
| 22 | `advanced-electromagnetic-theory` | graduate | core | `electromagnetic-theory`, `mathematical-methods-for-physics` | `analytical-mechanics`, `optics-and-photonics` | 10 | Solve graduate electrodynamics: Green-function boundary-value problems, multipole expansions, waveguides and cavities, dispersion in media, Lienard-Wiechert radiation, scattering and diffraction, radiation reaction, and the Lagrangian field formulation with its stress-energy tensor. | proposed |
| 23 | `advanced-quantum-mechanics` | graduate | core | `quantum-mechanics`, `mathematical-methods-for-physics` | `analytical-mechanics`, `advanced-electromagnetic-theory` | 12 | Use the full quantum formalism: Hilbert-space structure and pictures, symmetry and SU(2) angular momentum, fine and hyperfine structure, gauge invariance and Aharonov-Bohm, Berry phase, density matrices and entanglement measures, second quantization, path integrals, and formal scattering theory. | proposed |
| 24 | `statistical-physics` | graduate | core | `thermodynamics-and-statistical-mechanics`, `quantum-mechanics`, `mathematical-methods-for-physics` | `advanced-quantum-mechanics`, `computational-physics`, `mathematics/stochastic-processes` | 12 | Analyze many-particle systems: quantum ideal gases and condensation, interacting models, phase transitions and critical exponents, mean-field theory and its failures, the renormalization group, fluctuation-dissipation and linear response, the Boltzmann equation, and stochastic and far-from-equilibrium dynamics. | proposed |
| 25 | `general-relativity` | graduate | specialization | `electromagnetic-theory`, `analytical-mechanics`, `mathematical-methods-for-physics` | `advanced-electromagnetic-theory`, `mathematics/differential-geometry-and-manifolds` | 11 | Do gravitational physics geometrically: manifolds and tensor fields, the equivalence principle, covariant derivatives and geodesics, curvature, the Einstein field equations and their variational derivation, Schwarzschild and Kerr solutions, the classic tests, and linearized gravitational waves. | proposed |
| 26 | `quantum-field-theory` | graduate | specialization | `advanced-quantum-mechanics`, `analytical-mechanics`, `electromagnetic-theory` | `advanced-electromagnetic-theory`, `statistical-physics`, `mathematics/representation-theory-and-lie-theory` | 12 | Quantize fields and compute with them: classical field Lagrangians and Poincare symmetry, canonical quantization of scalar, spinor, and gauge fields, the path integral, Feynman rules and QED amplitudes, loop divergences and renormalization, running couplings, spontaneous symmetry breaking, and effective field theory. | proposed |
| 27 | `quantum-information-and-computation` | graduate | specialization | `quantum-mechanics` | `advanced-quantum-mechanics`, `computational-physics`, `mathematics/information-theory` | 12 | Treat quantum systems as information carriers: qubits, density matrices, channels and measurement, entanglement and Bell tests, circuits and universal gate sets, the core algorithms, error correction and fault tolerance, quantum entropy and channel capacity, decoherence and open-system dynamics, and the leading hardware platforms. | proposed |
| 28 | `condensed-matter-theory` | graduate | specialization | `condensed-matter-and-solid-state-physics`, `advanced-quantum-mechanics`, `statistical-physics` | `quantum-field-theory`, `computational-physics` | 12 | Analyze interacting electrons and emergent order: second-quantized many-body Hamiltonians, screening and Fermi-liquid theory, electron-phonon coupling and BCS superconductivity, magnetism and spin models, Green functions and response, broken symmetry and order parameters, Berry curvature and topological phases, and quantum Hall physics. | proposed |
| 29 | `atomic-molecular-and-optical-physics` | graduate | specialization | `advanced-quantum-mechanics`, `optics-and-photonics` | `electronics-and-instrumentation`, `quantum-information-and-computation` | 12 | Control atoms and light coherently: atomic fine and hyperfine structure, semiclassical and quantized light-matter coupling, Rabi dynamics and optical Bloch equations, spontaneous emission and cavity QED, laser cooling and trapping, degenerate quantum gases, molecular structure, precision spectroscopy, frequency combs, and ultrafast dynamics. | proposed |
| 30 | `particle-physics-and-the-standard-model` | graduate | specialization | `quantum-field-theory`, `nuclear-and-particle-physics` | `electronics-and-instrumentation`, `statistical-physics` | 11 | Derive and test the Standard Model: non-abelian gauge structure, QCD and asymptotic freedom, electroweak unification and the Higgs mechanism, flavor mixing and CP violation, neutrino mass and oscillation, hadron-collider cross sections and parton distributions, detector response, and the leading beyond-Standard-Model extensions. | proposed |
| 31 | `relativistic-astrophysics-and-cosmology` | graduate | specialization | `general-relativity`, `astrophysics-and-cosmology`, `statistical-physics` | `quantum-field-theory`, `computational-physics` | 12 | Apply general relativity to the universe: black-hole spacetimes and horizon thermodynamics, gravitational-wave generation and compact binaries, relativistic accretion and jets, FLRW dynamics and thermal history, nucleosynthesis, CMB anisotropy and the Boltzmann hierarchy, inflation and primordial perturbations, and structure formation. | proposed |
| 32 | `plasma-physics` | graduate | specialization | `electromagnetic-theory`, `continuum-mechanics-and-fluid-dynamics`, `thermodynamics-and-statistical-mechanics` | `statistical-physics`, `computational-physics`, `astrophysics-and-cosmology` | 11 | Model ionized matter across regimes: Debye shielding and plasma parameters, single-particle drifts and adiabatic invariants, the Vlasov and Fokker-Planck descriptions, two-fluid and MHD models, plasma waves and Landau damping, instabilities and reconnection, transport and collisions, and confinement in laboratory, space, and astrophysical settings. | proposed |
| 33 | `soft-matter-and-complex-fluids` | graduate | specialization | `statistical-physics`, `continuum-mechanics-and-fluid-dynamics` | `computational-physics`, `condensed-matter-and-solid-state-physics` | 10 | Explain materials governed by thermal energy and entropy: Brownian motion and diffusion, entropic and depletion forces, polymer statistics and scaling, colloidal interactions and stability, amphiphilic self-assembly, liquid-crystal order, interfaces and wetting, viscoelasticity and rheology, and granular jamming and active matter. | proposed |
| 34 | `biological-physics` | graduate | specialization | `statistical-physics` | `soft-matter-and-complex-fluids`, `biology/cell-biology`, `mathematics/stochastic-processes` | 11 | Apply physical reasoning to living systems: the scales and energy budget of the cell, diffusion and low-Reynolds-number transport, macromolecular conformation and folding energetics, molecular motors and free-energy transduction, membrane mechanics, stochastic gene expression, signaling and the physical limits of sensing, neural excitability, collective behavior, and evolutionary dynamics. | proposed |
| 35 | `physics-research-practice` | graduate | core | `measurement-uncertainty-and-experimental-physics`, `computational-physics` | `electronics-and-instrumentation`, `statistical-physics` | 10 | Work the way researchers work: read and situate papers, design an investigation around a falsifiable claim, handle systematic uncertainty, blinding, and the look-elsewhere effect, build reproducible computational and AI-assisted workflows while auditing provenance and outputs, distinguish reproducibility from replicability, and meet professional standards for authorship, peer review, conflicts, data retention, and safety. | proposed |
| 36 | `quantum-matter-and-materials-research` | research-specialization | specialization | `condensed-matter-theory`, `physics-research-practice` | `quantum-information-and-computation`, `soft-matter-and-complex-fluids` | 9 | Enter the literature on correlated and topological materials: symmetry-indicated band topology, unconventional and high-temperature superconductivity, moire and two-dimensional systems, quantum magnetism and spin liquids, materials synthesis and characterization claims, and what spectroscopic and transport evidence can actually establish. | proposed |
| 37 | `quantum-computing-and-simulation-research` | research-specialization | specialization | `quantum-information-and-computation`, `physics-research-practice` | `atomic-molecular-and-optical-physics`, `condensed-matter-theory` | 9 | Read and critique quantum-computing research: benchmarking and randomized characterization, error budgets and threshold claims, surface and LDPC codes toward fault tolerance, analog and digital quantum simulation, classical-simulability arguments, and how to evaluate a quantum-advantage claim. | proposed |
| 38 | `precision-measurement-and-quantum-sensing` | research-specialization | specialization | `atomic-molecular-and-optical-physics`, `physics-research-practice` | `quantum-information-and-computation`, `electronics-and-instrumentation` | 8 | Push measurement to its limits: the constant-based SI and its realization, optical clocks and comparisons, interferometric and atomic sensors, standard quantum limit and squeezing, noise budgets and systematic shifts, and searches for new physics through precision tests of fundamental constants and symmetries. | proposed |
| 39 | `gravitational-wave-and-multimessenger-astrophysics` | research-specialization | specialization | `relativistic-astrophysics-and-cosmology`, `physics-research-practice` | `precision-measurement-and-quantum-sensing`, `mathematics/mathematics-of-machine-learning-and-data-science` | 9 | Work with transient and multimessenger evidence: interferometric detector response and noise, post-Newtonian and numerical-relativity waveform models, matched filtering and Bayesian parameter estimation, population inference and selection effects, electromagnetic and neutrino counterparts, and cosmological and nuclear inferences drawn from compact-binary events. | proposed |
| 40 | `collider-and-precision-frontier-particle-physics` | research-specialization | specialization | `particle-physics-and-the-standard-model`, `physics-research-practice` | `electronics-and-instrumentation` | 9 | Follow the experimental program of fundamental interactions: Higgs property measurements, precision electroweak and flavor tests, Monte Carlo simulation chains and detector unfolding, statistical discovery and exclusion practice, direct and indirect dark-matter searches, and the neutrino-mass and rare-process frontier. | proposed |
| 41 | `living-and-active-matter-research` | research-specialization | specialization | `biological-physics`, `soft-matter-and-complex-fluids`, `physics-research-practice` | `biology/systems-and-quantitative-biology` | 8 | Enter the physics-of-life literature: active-matter hydrodynamics and collective motion, cytoskeletal and tissue mechanics, nonequilibrium thermodynamics of biological energy use, information and inference limits in cellular decision-making, quantitative imaging and single-molecule evidence, and the standards a physical model of a living system must meet. | proposed |
| 42 | `fusion-and-high-energy-density-science` | research-specialization | specialization | `plasma-physics`, `physics-research-practice` | `mathematics/numerical-methods-for-differential-equations` | 9 | Evaluate the fusion and high-energy-density literature: magnetic-confinement equilibrium, stability, and transport, tokamak and stellarator operating limits, inertial-confinement implosion physics and ignition criteria, equations of state and opacity at extreme conditions, diagnostics under extreme flux, and how energy-gain claims are defined and verified. | proposed |

## Why the decks are cut this way

**The foundational layer (1–5) does not begin with mechanics vocabulary.**
Deck 1, `measurement-and-physical-reasoning`, starts from observable comparison,
quantity and unit, scale, ratio, proportionality, uncertainty, and the habit of
stating an idealization — none of which require force, energy, or velocity. This
is the deliberate consequence of treating a first-contact learner as having no
physics vocabulary at all. Every later foundational deck can then be introduced
with a real measurement claim instead of an undefined word.

**Foundational decks 3, 4, and 5 are siblings, not a chain.** Thermal behavior,
waves, and electromagnetism each depend on `motion-forces-and-energy` and on
different mathematics, but not on each other. Forcing them into a line would
create false prerequisites and would block a learner who wants circuits before
optics. The order numbers record a reasonable default reading order; the edges
record what is actually required.

**Experimental and computational capability enter early and stay.** AAPT is
explicit that computation belongs in the introductory course and must be
reinforced throughout, and that a single dedicated computational course is not
sufficient. `measurement-uncertainty-and-experimental-physics` (6) and
`computational-physics` (7) are therefore placed at the front of the
undergraduate layer, before the advanced theory decks, and every later deck is
expected to carry code and data work outside the card set.

**`classical-mechanics` (8) and `analytical-mechanics` (16) are split.** Deck 8
is the calculus-based reworking of Newtonian mechanics — momentum, energy,
rotation, gravitation, oscillation — that a learner needs immediately and that
many later decks depend on. Deck 16 is the Lagrangian and Hamiltonian
reformulation, whose real payoff is symmetry, conserved quantities, canonical
structure, and the action principle that `quantum-field-theory` and
`general-relativity` actually consume. Merging them would produce a deck well
over the granularity ceiling and would force every learner who only needs
rotational dynamics through variational calculus first.

**There is no duplicate graduate classical-mechanics deck.** Current MIT doctoral
requirements name classical mechanics alongside electromagnetism, quantum
mechanics, and statistical mechanics, and Berkeley's 2026 prelim tests the same
four-area foundation. The existing `analytical-mechanics` deck already supplies
the advanced classical capability those structures test: variational and
Hamiltonian mechanics, canonical structure, normal forms, and nonlinear dynamics.
Its `undergraduate-advanced` level describes what it assumes, not whether a
graduate program may use the capability as core preparation. Relabeling or
duplicating it would add no new retrieval scope.

**`quantum-phenomena-and-atomic-structure` (10) precedes
`thermodynamics-and-statistical-mechanics` (11).** Classical thermodynamics
needs no quantum mechanics, but statistical mechanics needs countable microstates
— discrete energy levels, indistinguishability, and the resolution of the Gibbs
paradox. Deck 10 supplies exactly that, at the phenomenological level, which is
why the edge exists and why the much heavier `quantum-mechanics` (15) is *not*
required. The Bohr model is carried in deck 10 explicitly as a superseded model
retained for heuristic use, labeled as such.

**Undergraduate branch surveys (17–21) are separated from graduate branch theory
(22–34).** A learner mapping the field should be able to see condensed matter,
nuclear and particle physics, astrophysics, optics, and fluids without first
completing the graduate core. Each survey deck is `recommended` tier and gates
only on the specific theory it needs. The graduate decks then re-enter the same
domains at the level the research branches actually require.

**`physics-research-practice` (35) is a required deck, not an afterthought.**
Phys21 §D, the EP3 Guide, the APS Guidelines for Professional Conduct, and the
NASEM reproducibility report all treat research conduct — data retention,
authorship, peer review, conflict of interest, and the reproducibility/
replicability distinction — as content to be taught, not absorbed. The 2025 QAA
benchmark additionally requires responsible, critical use of generative-AI tools;
that is integrated here as provenance and output auditing, not spun into a generic
AI deck. `physics-research-practice` is a hard prerequisite of all seven
research-specialization decks.

**Seven terminal branches, one per decadal-scale community.** Quantum materials,
quantum computing and simulation, precision measurement and quantum sensing,
gravitational-wave and multimessenger astrophysics, the collider and precision
frontier, living and active matter, and fusion and high-energy-density science.
These are representative, not exhaustive, and the roadmap is explicitly designed
so that additional branches can be appended without renaming or deleting any
approved deck.

## Coherence and false-prerequisite stress test

Every proposal was rechecked against the 6–14 chapter range, a single conceptual
spine, one authentic representation/practice portfolio, and the rule that a hard
edge must establish a capability the deck may actually assume. The grouped audit
below names every deck; grouping records a shared verdict, not a merged scope.

| Decks audited | Coherence and dependency verdict |
|---|---|
| `measurement-and-physical-reasoning` | One first-contact spine—observable comparison, quantity, unit, scale, graph, and uncertainty. Number sense is used throughout, not for one isolated topic. |
| `motion-forces-and-energy` | One algebraic-mechanics course from kinematics through conserved quantities and rotation. Measurement language and elementary algebra are continuously required. |
| `matter-fluids-and-thermal-behavior`; `waves-sound-and-light`; `electricity-magnetism-and-circuits` | Three independent foundational siblings. Each has its own model and representation grammar; their hard edges stop at mechanics plus the mathematics actually used, while conventional cross-order is only recommended. |
| `measurement-uncertainty-and-experimental-physics`; `computational-physics` | Distinct experimental-inference and model-to-code capabilities. Formal statistics, programming, and calculus are imported only where the named capability requires executing them. |
| `classical-mechanics`; `special-relativity`; `quantum-phenomena-and-atomic-structure`; `thermodynamics-and-statistical-mechanics` | Four different undergraduate-core formalisms/evidence portfolios. Quantum phenomena requires established wave, charge, field, potential, circuit, and electromagnetic-radiation grammar; the thermal/statistical deck requires its discrete-state evidence only for the quantum-statistics part of its integrated micro-to-macro spine. |
| `electronics-and-instrumentation` | After correction, one signal-chain capability from front-end networks through digitization, noise, calibration, and diagnosis. Vacuum and cryogenic shop practice no longer create unrelated internal capstones. |
| `mathematical-methods-for-physics`; `electromagnetic-theory`; `quantum-mechanics`; `analytical-mechanics` | Four non-interchangeable upper-division capabilities: contextual mathematical transfer, Maxwell field reasoning, nonrelativistic quantum formalism, and variational/canonical mechanics. Their shared mathematics is referenced rather than duplicated; recommended parallel study is not encoded as a hard edge. |
| `optics-and-photonics`; `continuum-mechanics-and-fluid-dynamics`; `condensed-matter-and-solid-state-physics`; `nuclear-and-particle-physics`; `astrophysics-and-cosmology` | Five branch surveys with different representations and culminating performances. None requires the graduate theory of another branch merely to provide breadth. Continuum solids and fluids remain together because stress, flux, conservation, and constitutive laws are their shared course spine. |
| `advanced-electromagnetic-theory`; `advanced-quantum-mechanics`; `statistical-physics` | Three graduate-core formalisms with distinct problem portfolios. Each direct closure supplies the undergraduate theory and mathematical-method grammar its first chapter assumes. |
| `general-relativity`; `quantum-field-theory`; `quantum-information-and-computation` | Three graduate branches with distinct capstones. GR develops differential geometry in place; QFT genuinely requires relativistic field, action, and advanced quantum grammar; quantum information deliberately does not require unrelated advanced-QM topics once undergraduate Hilbert-space formalism is established. |
| `condensed-matter-theory`; `atomic-molecular-and-optical-physics`; `particle-physics-and-the-standard-model`; `relativistic-astrophysics-and-cosmology`; `plasma-physics`; `soft-matter-and-complex-fluids`; `biological-physics` | Seven mature branch theories, each with its own sources, representations, and research-facing capability. Biological terminology and low-Reynolds-number transfer are taught in place; broad biology remains recommended, while plasma, soft matter, and relativistic astrophysics retain only the theories they truly consume. |
| `physics-research-practice` | One branch-neutral claim-to-evidence workflow spanning literature, design, uncertainty, reproducible computation, provenance, communication, conduct, and safety. It is not a substitute for any branch theory. |
| `quantum-matter-and-materials-research`; `quantum-computing-and-simulation-research`; `precision-measurement-and-quantum-sensing`; `gravitational-wave-and-multimessenger-astrophysics`; `collider-and-precision-frontier-particle-physics`; `living-and-active-matter-research`; `fusion-and-high-energy-density-science` | Seven distinct literature communities and capstone critiques. Each has both graduate branch theory and research practice; living/active matter additionally needs soft-matter and continuum grammar. Helpful instrumentation, numerical, biology, and data-science routes remain recommendations when not logically required. |

## Cross-subject reuse and the one bridge deck

Every mathematical capability is referenced from the `mathematics` subject as
`subject/deck` rather than rebuilt here, from
`mathematics/number-sense-and-arithmetic` at the very start through
`mathematics/partial-differential-equations` and
`mathematics/complex-analysis` at the advanced layer. `biology/cell-biology` and
`mathematics/stochastic-processes` appear as `recommended_after` on
`biological-physics`, because that deck teaches the physics of living matter and
should not be gated behind a biology sequence.

`mathematical-methods-for-physics` (13) is the **single deliberate
subject-specific bridge**, and it is kept for a reason the mathematics decks do
not cover: contextual transfer is itself the thing being taught. Index and tensor
notation as a physical bookkeeping convention; special functions arriving as
solutions to physically posed boundary-value problems; Green functions attached
to physical operators, sources, and boundary conditions; separation of variables
chosen by the symmetry of an apparatus rather than of an equation; asymptotic and
perturbative reasoning tied to a stated regime of validity; and dimensional
analysis used to guess a result before solving. A learner who has completed the
mathematics decks knows the theorems and still cannot do these things.

The cost of that deck is recorded openly: requiring `mathematics/complex-analysis`
pulls `mathematics/real-analysis` and `mathematics/logic-sets-and-proof` into the
transitive closure. That is accepted because contour integration and analytic
structure are unavoidable in the graduate electromagnetic, quantum, and
statistical decks that depend on it, not because proof-based analysis is thought
generally necessary for physics.

One sequencing note that the executable graph cannot express: in practice
`mathematical-methods-for-physics` and `electromagnetic-theory` are best studied
in parallel, each supplying worked context for the other. The manifest lists only
`computational-physics` and `special-relativity` under `recommended_after`,
because a recommendation pointing at a later-ordered deck is rejected by the
validator as non-topological.

## Maturity transition audit

For every graduate and research-specialization deck, the capabilities its first
chapter may assume are listed against the decks in its direct prerequisite
closure that actually establish them.

| Deck | First chapter assumes | Established by | Verdict |
|---|---|---|---|
| `advanced-electromagnetic-theory` | Maxwell equations in covariant form, boundary-value technique, retarded potentials, Green functions, contour methods | `electromagnetic-theory`, `mathematical-methods-for-physics` | Sufficient |
| `advanced-quantum-mechanics` | State-vector and operator formalism, perturbation theory, angular momentum algebra, special functions, complex analysis | `quantum-mechanics`, `mathematical-methods-for-physics` | Sufficient |
| `statistical-physics` | Ensembles, partition functions, discrete microstates, quantum statistics, saddle-point and asymptotic methods | `thermodynamics-and-statistical-mechanics`, `quantum-mechanics`, `mathematical-methods-for-physics` | Sufficient |
| `general-relativity` | Tensor and index notation, field equations with sources, variational principles, Lorentz covariance | `electromagnetic-theory` (which carries `special-relativity`), `analytical-mechanics`, `mathematical-methods-for-physics` | Sufficient — differential geometry is developed inside the deck, matching published graduate GR prerequisites that list only ODEs, linear algebra, and undergraduate electromagnetism. No quantum prerequisite is imposed. |
| `quantum-field-theory` | Relativistic kinematics, Lagrangian field structure and Noether's theorem, scattering and perturbation theory, gauge fields | `advanced-quantum-mechanics`, `analytical-mechanics`, `electromagnetic-theory` | Sufficient. Group theory is deliberately *not* a hard edge; the representation theory needed is developed in place, as in standard first-year QFT courses. |
| `quantum-information-and-computation` | Hilbert spaces, tensor products, measurement, density matrices, entanglement | `quantum-mechanics` | Deliberate level jump from an undergraduate-advanced deck straight to a graduate deck, retained because published quantum-computation courses gate on undergraduate quantum mechanics plus linear algebra alone. Adding `advanced-quantum-mechanics` would be a false prerequisite. |
| `condensed-matter-theory` | Bloch states, band structure, second quantization, many-body ensembles, response functions | `condensed-matter-and-solid-state-physics`, `advanced-quantum-mechanics`, `statistical-physics` | Sufficient |
| `atomic-molecular-and-optical-physics` | Atomic structure and fine structure, time-dependent perturbation theory, coherent light fields, resonators | `advanced-quantum-mechanics`, `optics-and-photonics` | Sufficient |
| `particle-physics-and-the-standard-model` | Field quantization, Feynman rules, cross sections and decay rates, detector and accelerator vocabulary | `quantum-field-theory`, `nuclear-and-particle-physics` | Sufficient |
| `relativistic-astrophysics-and-cosmology` | Curved-spacetime dynamics, stellar structure and populations, observational pipelines, thermal history and equilibrium statistics | `general-relativity`, `astrophysics-and-cosmology`, `statistical-physics` | Sufficient |
| `plasma-physics` | Fields with sources and boundary conditions, continuum and transport equations, kinetic distributions and collisions | `electromagnetic-theory`, `continuum-mechanics-and-fluid-dynamics`, `thermodynamics-and-statistical-mechanics` | Sufficient. No quantum edge, because the deck is classical and kinetic; degenerate-matter regimes are handled inside `fusion-and-high-energy-density-science`. |
| `soft-matter-and-complex-fluids` | Free energy and phase behavior, fluctuations, viscous and viscoelastic flow, coarse-graining | `statistical-physics`, `continuum-mechanics-and-fluid-dynamics` | Sufficient |
| `biological-physics` | Thermal energy scale, fluctuation and noise, entropy and free energy, and stochastic dynamics | `statistical-physics` | Sufficient for chapter 1. Biological vocabulary and the low-Reynolds-number regime are established inside the deck before application; `biology/cell-biology`, `soft-matter-and-complex-fluids`, and `mathematics/stochastic-processes` are recommended rather than hard edges so a physicist is not gated behind broad biology or soft-matter sequences. |
| `physics-research-practice` | Uncertainty budgets, systematic error, experimental design, reproducible computational workflow, and basic provenance discipline | `measurement-uncertainty-and-experimental-physics`, `computational-physics` | Sufficient. AI-assisted workflow audit is developed inside the deck from those established data and computation practices. The deck is deliberately not gated on any branch theory, so a learner in any branch can reach it. |
| `quantum-matter-and-materials-research` | Many-body and topological language, correlated-electron phenomenology, plus literature reading, error analysis, and research conduct | `condensed-matter-theory`, `physics-research-practice` | Sufficient |
| `quantum-computing-and-simulation-research` | Circuit and error-correction formalism, noise channels, plus literature and research conduct | `quantum-information-and-computation`, `physics-research-practice` | Sufficient |
| `precision-measurement-and-quantum-sensing` | Atomic clocks, coherent control, cavity and laser systems, plus uncertainty budgets and research conduct | `atomic-molecular-and-optical-physics`, `physics-research-practice` | Sufficient |
| `gravitational-wave-and-multimessenger-astrophysics` | Compact-object dynamics and radiation, cosmological observation, plus statistical inference and research conduct | `relativistic-astrophysics-and-cosmology`, `physics-research-practice` | Sufficient |
| `collider-and-precision-frontier-particle-physics` | Standard Model phenomenology, cross sections, detector concepts, plus statistical method and research conduct | `particle-physics-and-the-standard-model`, `physics-research-practice` | Sufficient |
| `living-and-active-matter-research` | Nonequilibrium statistical language, biological force and motility scales, continuum and rheological representations, active-matter hydrodynamics, plus data analysis and research conduct | `biological-physics`, `soft-matter-and-complex-fluids`, `physics-research-practice` | Sufficient after correction: the added soft-matter edge closes the continuum and active-matter gap that recommendation alone did not establish. |
| `fusion-and-high-energy-density-science` | Magnetized and kinetic plasma behavior, confinement and transport, plus diagnostics and research conduct | `plasma-physics`, `physics-research-practice` | Sufficient |

The governing rule behind this table: **no research-specialization deck may
depend on an undergraduate survey alone.** Every terminal branch has a graduate
branch-theory edge and `physics-research-practice`; living and active matter also
requires the separate graduate soft-matter/continuum capability. Thus no route
runs from a survey directly into literature-facing work without both an advanced
theory layer and an explicit research-method layer.

## Cross-deck concepts

These recur with increasing depth and must not be duplicated independently. The
later deck retrieves and extends the earlier treatment rather than restating it.

- **Units, dimensional analysis, and orders of magnitude** — introduced in deck 1
  and used as a first move in every later deck, including as a check on graduate
  results.
- **Uncertainty and systematic error** — deck 1 (stating it), deck 6 (propagating
  and budgeting it), deck 35 (defending it in a research claim).
- **Energy** — deck 2 (bookkeeping), deck 3 (internal energy), deck 11 (free
  energy), deck 16 (Hamiltonian), deck 24 (ensemble averages).
- **Field** — deck 5 (as a map of force), deck 14 (as a dynamical object with its
  own energy and momentum), deck 26 (as an operator-valued quantity).
- **Oscillator and normal mode** — deck 2, deck 4, deck 8, deck 15, deck 19
  (phonons), deck 26 (field quantization). This is the single most reused
  structure in the roadmap and is deliberately introduced once, concretely.
- **Symmetry and conservation** — deck 2 (empirical conservation laws), deck 16
  (Noether), deck 19 (crystal symmetry), deck 30 (gauge and flavor symmetry).
- **Statistical distribution** — deck 6 (measurement error), deck 11
  (Maxwell–Boltzmann and quantum statistics), deck 32 (velocity distributions),
  deck 40 (likelihood and significance).
- **Regime of validity** — every simplification named in `SUBJECT_BRIEF.md` is
  introduced with the conditions under which it fails, and later decks retrieve
  the breakdown case rather than the approximation alone.

**Interference pairs requiring explicit discrimination**, because each pair is
routinely confused and the decks that own them are close together: heat and
temperature; mass and weight; velocity and acceleration; energy and power; series
and parallel; electric field and electric potential; emf and potential
difference; intensity and amplitude; interference and diffraction; wave function
and probability density; phase and group velocity; Fermi energy and Fermi level;
accuracy and precision; systematic and random error; reproducibility and
replicability; entropy as disorder and entropy as microstate counting; proper
time and coordinate time; rest mass and relativistic mass (with the latter
labeled as a discouraged legacy usage); and cross section and probability.

## Practice outside SRS

Spaced retrieval maintains concepts, representations, and method triggers. It
cannot produce physics competence alone. `SUBJECT_BRIEF.md` records the full
list; the load-bearing dependencies are laboratory work against the six AAPT
laboratory outcomes, extended multi-step problems and full derivations kept
whole, computation as a continuing practice from deck 7 onward, estimation and
Fermi problems, reading the literature, scientific writing and speaking,
instrumentation and shop practice, and professional practice including research
ethics.

## Exclusions and extension points

**Deferred** — visible future extensions, not judgments about the learner:
accelerator and beam physics; medical physics; physics of climate and Earth
systems; geophysics, space, and atmospheric physics; energy science and
technology; chemical physics and physical chemistry; quantum gravity and string
theory; and the history and philosophy of physics. Each has a natural attachment
point already present in the graph — for example accelerator physics after
`advanced-electromagnetic-theory`, and quantum gravity after
`quantum-field-theory` and `general-relativity`.

**Out of scope** — handled elsewhere: networks and complex systems belongs to
`mathematics/networks-and-complex-systems` and is referenced rather than
duplicated; physics education research is education research rather than physics
content, and its findings are used to shape card design instead of being taught.

## Open decisions needing confirmation

These are genuinely personal and were not invented:

1. **Who the learner is** — self-studier, student shadowing formal coursework, or
   professional re-entering the field. The deck graph does not change, but
   chapter register and worked-example choice do.
2. **Existing mathematics mastery.** Every mathematical capability is currently
   imported explicitly. Confirmed prior mastery satisfies those external edges
   immediately with no change to this roadmap.
3. **A real target research branch.** If one exists, promote it and demote the
   other six representative branches to `deferred` rather than pursuing all seven.
4. **Accessibility and device constraints.** Phone-width study is assumed by
   default, which constrains figure design.
