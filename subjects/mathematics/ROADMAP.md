# Mathematics learning roadmap

## Learner and destination

This is a cold-start, whole-field map. It does not assume that the learner has
mastered arithmetic, algebra, proof, calculus, programming, or any named
branch. Personal background and priorities remain awaiting confirmation in
`SUBJECT_BRIEF.md`.

- Long-term capabilities: calculate and estimate with understanding; translate
  among authentic representations; select, justify, and check methods; write
  and critique proofs; formulate and validate models; reason about uncertainty
  and numerical error; compute reproducibly; communicate mathematics; and
  enter selected research literature.
- Requested destination: `whole-field`, from quantitative literacy through
  representative research-specialization routes.
- Focus branches: none specified; pure, applied, computational, probabilistic,
  statistical, and interdisciplinary branches remain visible.
- Deck granularity: `course`, with 6–14 estimated chapters per coherent deck.

Orders below are unique topological labels, not a command to finish every lower
number before starting a higher one. The first deck is deliberately
`quantitative-reasoning-and-arithmetic`: every other route can rely on an
explicit cold-start foundation rather than guessed school knowledge.

## Field coverage

The map was checked against foundational proficiency frameworks, undergraduate
mathematical-sciences guidance, applied and statistical curriculum guidance,
and the current MSC2020 research taxonomy. Framework headings were grouped by
coherent learning capability rather than converted mechanically into decks.
This matrix is synchronized with `subject.toml`.

| Domain | Disposition | Decks | Rationale |
|---|---|---|---|
| quantitative-literacy-and-arithmetic | included | quantitative-reasoning-and-arithmetic | The mandatory cold-start deck establishes number sense, estimation, proportional reasoning, and usable arithmetic. |
| elementary-algebra-and-functions | included | elementary-algebra-and-functions | A dedicated foundation prevents later decks from silently assuming symbolic and functional fluency. |
| geometry-measurement-and-spatial-reasoning | included | geometry-and-measurement; modern-geometry | Foundational spatial reasoning is separated from proof-based study of geometric structures and invariants. |
| precalculus-and-trigonometry | included | precalculus-functions-and-trigonometry | A coherent functions-and-trigonometry bridge supports calculus without burdening unrelated foundational decks. |
| mathematical-computing-and-experimentation | included | mathematical-computing-and-experimentation; numerical-analysis; numerical-pde-and-scientific-computing | Computation begins as a general mathematical practice and later develops into numerical analysis and scalable scientific computing. |
| logic-proof-and-foundations | included | logic-sets-and-proof; mathematical-logic-and-computability; set-theory-and-model-theory | The route separates proof literacy from formal logic and from graduate foundational specialization. |
| calculus-and-continuous-change | included | single-variable-differential-calculus; single-variable-integral-calculus; multivariable-and-vector-calculus | Three course-scale decks develop local change, accumulation and series, then several-variable and vector structure. |
| discrete-mathematics-combinatorics-and-graphs | included | discrete-mathematics; combinatorics-and-graph-theory; probabilistic-and-extremal-combinatorics; networks-and-complex-systems | The sequence moves from shared discrete tools to structural theory and representative advanced probabilistic and network routes. |
| linear-multilinear-and-representation-structures | included | linear-algebra; graduate-algebra; representation-theory | Linear reasoning is established early, deepened algebraically, and applied to symmetry without making representation theory universal. |
| probability-and-stochastic-processes | included | probability; stochastic-processes; measure-theoretic-probability; stochastic-analysis | Finite and calculus-based probability precedes processes, measure-theoretic foundations, and stochastic calculus. |
| statistics-data-analysis-and-learning | included | statistical-inference-and-data-analysis; regression-and-multivariate-statistics; statistical-learning-and-high-dimensional-inference; topological-and-geometric-data-analysis | Statistical investigation and ethics precede model families, advanced learning theory, and a representative geometric data branch. |
| ordinary-differential-equations-dynamics-and-control | included | differential-equations; nonlinear-dynamics-and-chaos; systems-and-control-theory; networks-and-complex-systems | A shared ODE course supports distinct qualitative, control, and complex-systems branches. |
| mathematical-modeling-and-interdisciplinary-methods | included | mathematical-modeling; mathematical-biology-and-network-models; financial-mathematics-and-risk; inverse-problems-and-uncertainty-quantification; networks-and-complex-systems | Model formulation and validation form a core practice, with representative biological, financial, inverse, and network applications. |
| real-analysis-measure-and-integration | included | real-analysis; measure-theory-and-integration | Proof-based real analysis supplies the direct foundation for modern measure and integration theory. |
| groups-rings-fields-and-modules | included | abstract-algebra; graduate-algebra; commutative-algebra; category-theory-and-homological-algebra | The algebra spine progresses from core structures to modules, commutative methods, and categorical or homological organization. |
| number-theory-and-cryptography | included | number-theory; coding-theory-and-cryptography; analytic-number-theory; algebraic-number-theory; arithmetic-geometry | Elementary number theory branches honestly into computational, analytic, algebraic, and arithmetic-geometric directions. |
| complex-and-harmonic-analysis | included | complex-analysis; harmonic-analysis | A classical complex course and a graduate harmonic course provide distinct coherent analysis capabilities. |
| general-and-algebraic-topology | included | topology; algebraic-topology; differential-topology-and-global-analysis; topological-and-geometric-data-analysis | Point-set foundations support algebraic and differential invariants and one contemporary computational application. |
| geometry-manifolds-and-geometric-analysis | included | modern-geometry; differential-geometry-and-manifolds; differential-topology-and-global-analysis; geometric-analysis | Synthetic and transformation viewpoints precede smooth manifolds, global topology, and analysis on geometric structures. |
| history-and-philosophy-of-mathematics | included | history-and-philosophy-of-mathematics | A dedicated course keeps historical and philosophical reasoning visible without scattering decontextualized anecdotes across technical decks. |
| partial-differential-equations | included | partial-differential-equations-and-fourier-methods; graduate-pde-and-distributions; numerical-pde-and-scientific-computing; geometric-analysis; inverse-problems-and-uncertainty-quantification | Classical methods lead to weak theory, computation, geometric equations, and inverse problems through separate branches. |
| numerical-analysis-and-scientific-computing | included | numerical-analysis; numerical-pde-and-scientific-computing; inverse-problems-and-uncertainty-quantification | Core error and stability reasoning supports specialized discretization and computation under uncertainty. |
| continuous-optimization-and-variational-methods | included | convex-and-continuous-optimization; statistical-learning-and-high-dimensional-inference; systems-and-control-theory; variational-methods-and-mathematical-physics | Optimization fundamentals support learning, control, and variational physics without forcing those branches on one another. |
| operations-research-and-discrete-optimization | included | combinatorial-optimization-and-networks; systems-and-control-theory; networks-and-complex-systems | Network and discrete optimization form a coherent course and feed selected systems and network applications. |
| information-coding-and-quantum-information | included | information-theory; coding-theory-and-cryptography; quantum-information-mathematics | Information measures, algebraic coding, and quantum information remain separate because their prerequisite structures differ. |
| game-theory-economics-and-social-choice | included | game-theory-and-social-choice | A bounded course represents strategic and collective-decision mathematics without assuming a full economics curriculum. |
| mathematical-biology | included | mathematical-biology-and-network-models | A representative interdisciplinary course integrates dynamical, stochastic, spatial, and network models with explicit biological assumptions. |
| financial-actuarial-and-risk-mathematics | included | financial-mathematics-and-risk | A coherent stochastic risk course provides a branch point for finance, insurance, and actuarial extensions. |
| functional-analysis-and-operator-theory | included | functional-analysis-and-operator-theory; harmonic-analysis; graduate-pde-and-distributions; variational-methods-and-mathematical-physics; quantum-information-mathematics | The foundational graduate course supports distinct analytic, PDE, physics, and information-theoretic uses. |
| commutative-algebra-and-algebraic-geometry | included | commutative-algebra; algebraic-geometry; arithmetic-geometry | Commutative algebra is the minimal hard bridge to algebraic geometry and its arithmetic research route. |
| category-homological-and-algebraic-topological-methods | included | algebraic-topology; category-theory-and-homological-algebra; topological-and-geometric-data-analysis | Topological invariants and categorical machinery are taught in distinct courses before a selected data application. |
| lie-theory-representations-and-symmetry | included | representation-theory; lie-groups-and-lie-algebras; variational-methods-and-mathematical-physics | Algebraic representation theory and smooth Lie theory are separated, then reused in mathematical physics. |
| analytic-and-algebraic-number-theory | included | analytic-number-theory; algebraic-number-theory; arithmetic-geometry | The roadmap exposes both principal graduate approaches and their arithmetic-geometric synthesis. |
| special-functions-transforms-and-approximation | included | complex-analysis; partial-differential-equations-and-fourier-methods; numerical-analysis; harmonic-analysis | These methods recur where they are operationally coherent instead of being isolated as a survey deck. |
| mechanics-continuum-and-mathematical-physics | included | partial-differential-equations-and-fourier-methods; variational-methods-and-mathematical-physics; geometric-analysis; quantum-information-mathematics | The mathematics side is represented through PDE, variational, geometric, spectral, and quantum-information routes. |
| systems-information-and-communications | included | information-theory; systems-and-control-theory; quantum-information-mathematics | Information and systems mathematics receive independent foundations with a visible quantum extension. |
| several-complex-variables-and-potential-theory | deferred | None | Visible future analysis branches after complex, harmonic, functional, and PDE foundations; omitted from the initial representative route. |
| k-theory-higher-categories-and-derived-geometry | deferred | None | Visible future extensions after algebraic topology, homological algebra, and algebraic geometry rather than premature survey material. |
| order-lattices-and-universal-algebra | deferred | None | A visible algebra extension after proof and abstract algebra; a dedicated course is preferable to a few disconnected survey chapters. |
| specialized-fluids-solids-relativity-and-materials | deferred | None | The mathematical foundations are present, but each domain requires science-specific assumptions and a separate course-scale source base. |
| earth-space-climate-and-other-domain-science-models | deferred | None | Modeling, dynamics, PDE, probability, and numerics provide extension points; discipline-specific verification is postponed. |
| mathematics-education-research-and-teacher-preparation | out-of-scope | None | Teaching practice and education research form a neighboring professional subject, not a branch of mathematical content in this workspace. |
| general-computer-science | out-of-scope | None | Only mathematical computing, algorithms, logic, coding, information, optimization, and learning overlaps are included here. |
| discipline-specific-science-engineering-and-economics | out-of-scope | None | The roadmap covers mathematical methods and model critique, while substantive domain curricula belong in their own subject workspaces. |

## Deck sequence

Each row is a course-scale capability. `Core` identifies the cold-start
foundation or a deck shared by several major branches for this whole-field
destination. `Recommended` adds broad field structure. `Specialization` is a
learner-selected branch. Every entry is `proposed`; approval and deck creation
are later operations.

Hard prerequisites authorize the target deck to assume the predecessor's full
outcomes. Recommended order is only helpful sequencing. An earlier order by
itself grants no inbound knowledge.

| Order | Deck | Level | Tier | Hard prerequisites | Recommended after | Est. chapters | Durable capabilities | Status |
|---:|---|---|---|---|---|---:|---|---|
| 1 | quantitative-reasoning-and-arithmetic | foundational | core | None | None | 10 | Reason fluently with whole, signed, rational, decimal, percent, proportional, and estimated quantities in authentic contexts. | proposed |
| 2 | elementary-algebra-and-functions | foundational | core | quantitative-reasoning-and-arithmetic | None | 12 | Translate among situations, expressions, equations, inequalities, tables, and graphs and solve elementary algebraic models. | proposed |
| 3 | geometry-and-measurement | foundational | core | quantitative-reasoning-and-arithmetic | elementary-algebra-and-functions | 10 | Reason with Euclidean shape, congruence, similarity, coordinates, units, area, volume, scale, and spatial representations. | proposed |
| 4 | precalculus-functions-and-trigonometry | foundational | core | elementary-algebra-and-functions | geometry-and-measurement | 12 | Analyze polynomial, rational, exponential, logarithmic, and trigonometric functions as preparation for continuous mathematics. | proposed |
| 5 | mathematical-computing-and-experimentation | foundational | core | elementary-algebra-and-functions | None | 8 | Use code, symbolic and numerical tools, visualization, testing, and reproducible experiments to investigate mathematics responsibly. | proposed |
| 6 | logic-sets-and-proof | undergraduate-core | core | quantitative-reasoning-and-arithmetic | elementary-algebra-and-functions | 10 | Read and construct proofs using logic, sets, functions, relations, induction, contradiction, counterexamples, and precise quantifiers. | proposed |
| 7 | single-variable-differential-calculus | undergraduate-core | core | precalculus-functions-and-trigonometry | None | 10 | Interpret limits, continuity, derivatives, approximation, and optimization across symbolic, graphical, numerical, and applied forms. | proposed |
| 8 | discrete-mathematics | undergraduate-core | core | logic-sets-and-proof; elementary-algebra-and-functions | None | 12 | Reason with finite structures, counting, recurrence, graphs, algorithms, invariants, and discrete proof methods. | proposed |
| 9 | linear-algebra | undergraduate-core | core | elementary-algebra-and-functions | logic-sets-and-proof | 12 | Use vectors, matrices, linear maps, subspaces, eigenstructure, inner products, and decompositions to solve and explain linear problems. | proposed |
| 10 | single-variable-integral-calculus | undergraduate-core | core | single-variable-differential-calculus | None | 12 | Connect accumulation and change through integration, differential equations, parametric curves, sequences, series, and approximation. | proposed |
| 11 | multivariable-and-vector-calculus | undergraduate-core | core | single-variable-integral-calculus | linear-algebra | 12 | Differentiate and integrate scalar and vector fields in several variables and interpret the major integral theorems. | proposed |
| 12 | probability | undergraduate-core | core | single-variable-integral-calculus | discrete-mathematics | 12 | Model uncertainty with random variables, conditioning, independence, distributions, expectation, transforms, and limit reasoning. | proposed |
| 13 | differential-equations | undergraduate-core | core | single-variable-integral-calculus; linear-algebra | None | 12 | Classify, solve, approximate, and interpret ordinary differential equations and linear systems while checking model assumptions. | proposed |
| 14 | statistical-inference-and-data-analysis | undergraduate-core | core | probability; mathematical-computing-and-experimentation | None | 12 | Carry out an ethical statistical investigation from question and study design through estimation, testing, uncertainty, and communication. | proposed |
| 15 | mathematical-modeling | undergraduate-core | core | mathematical-computing-and-experimentation | differential-equations; statistical-inference-and-data-analysis | 10 | Formulate, analyze, validate, compare, and communicate models while making assumptions, scales, sensitivity, and limitations explicit. | proposed |
| 16 | real-analysis | undergraduate-core | core | logic-sets-and-proof; single-variable-integral-calculus | None | 12 | Prove and apply the foundations of limits, continuity, differentiation, integration, sequences, series, and metric-space reasoning. | proposed |
| 17 | abstract-algebra | undergraduate-core | core | logic-sets-and-proof; elementary-algebra-and-functions | None | 12 | Reason structurally with groups, rings, fields, homomorphisms, quotients, actions, and polynomial constructions. | proposed |
| 18 | combinatorics-and-graph-theory | undergraduate-advanced | recommended | discrete-mathematics | None | 12 | Use structural, enumerative, extremal, algebraic, and algorithmic methods on graphs and finite configurations. | proposed |
| 19 | number-theory | undergraduate-advanced | recommended | logic-sets-and-proof; elementary-algebra-and-functions | abstract-algebra | 10 | Prove and compute with divisibility, congruences, Diophantine equations, arithmetic functions, quadratic residues, and prime structure. | proposed |
| 20 | complex-analysis | undergraduate-advanced | recommended | real-analysis | multivariable-and-vector-calculus | 12 | Analyze holomorphic functions through complex differentiation, contour integration, series, residues, conformal maps, and harmonic links. | proposed |
| 21 | topology | undergraduate-advanced | recommended | real-analysis | None | 12 | Work with topological spaces, continuity, products, quotients, compactness, connectedness, separation, and elementary homotopy. | proposed |
| 22 | modern-geometry | undergraduate-advanced | recommended | logic-sets-and-proof; linear-algebra | topology | 10 | Compare Euclidean, affine, projective, spherical, hyperbolic, and transformation geometries through invariants and constructions. | proposed |
| 23 | history-and-philosophy-of-mathematics | undergraduate-advanced | recommended | logic-sets-and-proof | real-analysis; abstract-algebra | 10 | Relate major mathematical ideas to their historical development, foundational debates, proof cultures, and changing standards of rigor. | proposed |
| 24 | nonlinear-dynamics-and-chaos | undergraduate-advanced | recommended | differential-equations | multivariable-and-vector-calculus | 10 | Analyze phase portraits, stability, bifurcations, oscillations, maps, chaos, and qualitative behavior of nonlinear systems. | proposed |
| 25 | partial-differential-equations-and-fourier-methods | undergraduate-advanced | recommended | differential-equations; multivariable-and-vector-calculus | real-analysis | 12 | Classify and solve canonical partial differential equations using characteristics, separation, Fourier methods, energy, and boundary data. | proposed |
| 26 | numerical-analysis | undergraduate-advanced | recommended | mathematical-computing-and-experimentation; single-variable-integral-calculus; linear-algebra | differential-equations | 12 | Design and assess numerical algorithms using approximation, conditioning, stability, convergence, error bounds, and reproducible experiments. | proposed |
| 27 | convex-and-continuous-optimization | undergraduate-advanced | recommended | mathematical-computing-and-experimentation; multivariable-and-vector-calculus; linear-algebra | None | 10 | Formulate and solve linear, convex, constrained, and smooth optimization problems using duality, optimality conditions, and algorithms. | proposed |
| 28 | combinatorial-optimization-and-networks | undergraduate-advanced | recommended | mathematical-computing-and-experimentation; discrete-mathematics; linear-algebra | None | 10 | Model and solve network, matching, flow, scheduling, integer, and combinatorial optimization problems with exact and approximate methods. | proposed |
| 29 | stochastic-processes | undergraduate-advanced | recommended | probability; linear-algebra | differential-equations | 12 | Analyze discrete- and continuous-time random processes, Markov chains, Poisson processes, martingales, queues, and long-run behavior. | proposed |
| 30 | regression-and-multivariate-statistics | undergraduate-advanced | recommended | statistical-inference-and-data-analysis; linear-algebra | None | 12 | Build, diagnose, interpret, and communicate regression and multivariate models with principled uncertainty and validation. | proposed |
| 31 | mathematical-logic-and-computability | undergraduate-advanced | recommended | discrete-mathematics | None | 12 | Analyze formal languages, deduction, semantics, computability, undecidability, incompleteness, and the limits of formal methods. | proposed |
| 32 | differential-geometry-and-manifolds | undergraduate-advanced | recommended | multivariable-and-vector-calculus; linear-algebra; logic-sets-and-proof | topology | 12 | Study curves, surfaces, manifolds, tangent structures, metrics, curvature, differential forms, and geometric integration. | proposed |
| 33 | information-theory | undergraduate-advanced | recommended | probability | linear-algebra | 10 | Quantify information, compression, channel capacity, divergence, coding limits, and statistical decision tradeoffs. | proposed |
| 34 | coding-theory-and-cryptography | undergraduate-advanced | specialization | number-theory; abstract-algebra; probability | combinatorics-and-graph-theory | 10 | Construct and analyze error-correcting codes and classical cryptosystems using finite algebra, number theory, probability, and adversarial models. | proposed |
| 35 | game-theory-and-social-choice | undergraduate-advanced | specialization | elementary-algebra-and-functions | probability; discrete-mathematics; linear-algebra | 10 | Analyze strategic interaction, equilibrium, bargaining, voting, allocation, incentives, and the assumptions behind social-choice results. | proposed |
| 36 | mathematical-biology-and-network-models | undergraduate-advanced | specialization | mathematical-modeling; differential-equations; probability | stochastic-processes | 10 | Build and critique dynamical, stochastic, spatial, and network models of biological systems across scales. | proposed |
| 37 | financial-mathematics-and-risk | undergraduate-advanced | specialization | probability | statistical-inference-and-data-analysis; stochastic-processes | 10 | Model interest, contingent claims, portfolios, insurance losses, dependence, and risk while stating market and actuarial assumptions. | proposed |
| 38 | measure-theory-and-integration | graduate | recommended | real-analysis | None | 12 | Reason with sigma-algebras, measures, measurable functions, Lebesgue integration, convergence theorems, product measures, and signed measures. | proposed |
| 39 | functional-analysis-and-operator-theory | graduate | recommended | measure-theory-and-integration; linear-algebra | None | 12 | Analyze normed, Banach, and Hilbert spaces and bounded, compact, and spectral operators with applications to analysis. | proposed |
| 40 | measure-theoretic-probability | graduate | recommended | measure-theory-and-integration; probability | None | 12 | Develop probability on measure spaces through conditional expectation, modes of convergence, laws of large numbers, and central limit theory. | proposed |
| 41 | graduate-algebra | graduate | recommended | abstract-algebra; linear-algebra | None | 12 | Develop groups, rings, modules, fields, tensor constructions, canonical forms, and Galois theory at graduate depth. | proposed |
| 42 | commutative-algebra | graduate | specialization | graduate-algebra | None | 12 | Use ideals, localization, modules, chain conditions, dimension, primary decomposition, and homological tools in commutative rings. | proposed |
| 43 | algebraic-topology | graduate | specialization | topology; abstract-algebra | None | 12 | Compute and interpret fundamental groups, covering spaces, homology, cohomology, products, and exact sequences as topological invariants. | proposed |
| 44 | differential-topology-and-global-analysis | graduate | specialization | differential-geometry-and-manifolds; topology | None | 10 | Use transversality, degree, intersection, Morse ideas, vector bundles, and elliptic viewpoints to derive global conclusions. | proposed |
| 45 | category-theory-and-homological-algebra | graduate | specialization | graduate-algebra | algebraic-topology | 12 | Reason with categories, universal properties, adjunctions, limits, abelian categories, complexes, derived functors, and spectral sequences. | proposed |
| 46 | algebraic-geometry | graduate | specialization | commutative-algebra | topology | 12 | Study affine and projective varieties and schemes through coordinate rings, morphisms, sheaves, dimension, smoothness, and cohomological ideas. | proposed |
| 47 | representation-theory | graduate | specialization | graduate-algebra | None | 10 | Analyze symmetries through group and algebra representations, characters, modules, decomposition, induction, and structural examples. | proposed |
| 48 | lie-groups-and-lie-algebras | graduate | specialization | differential-geometry-and-manifolds; graduate-algebra | representation-theory | 12 | Connect continuous symmetry, manifolds, Lie algebras, exponential maps, roots, weights, and representations. | proposed |
| 49 | analytic-number-theory | graduate | specialization | number-theory; complex-analysis | None | 10 | Study primes and arithmetic functions using Dirichlet series, complex methods, sieves, exponential sums, and asymptotic reasoning. | proposed |
| 50 | algebraic-number-theory | graduate | specialization | number-theory; graduate-algebra | None | 12 | Analyze number fields, rings of integers, ideals, ramification, valuations, local fields, and class and unit structures. | proposed |
| 51 | probabilistic-and-extremal-combinatorics | graduate | specialization | combinatorics-and-graph-theory; probability | None | 10 | Use probabilistic, extremal, algebraic, and asymptotic methods to prove existence and structure in large discrete systems. | proposed |
| 52 | set-theory-and-model-theory | graduate | specialization | mathematical-logic-and-computability | None | 12 | Study axiomatic set theory, ordinals, cardinals, choice, models, compactness, types, and independence phenomena. | proposed |
| 53 | harmonic-analysis | graduate | specialization | functional-analysis-and-operator-theory | complex-analysis | 12 | Analyze functions and operators through Fourier series and transforms, convolution, maximal estimates, distributions, and function spaces. | proposed |
| 54 | graduate-pde-and-distributions | graduate | specialization | functional-analysis-and-operator-theory; partial-differential-equations-and-fourier-methods | None | 12 | Treat weak solutions, distributions, Sobolev spaces, elliptic, parabolic, and hyperbolic equations, regularity, and variational methods. | proposed |
| 55 | stochastic-analysis | graduate | specialization | measure-theoretic-probability; stochastic-processes | None | 12 | Work with martingales, Brownian motion, stochastic integration, stochastic differential equations, change of measure, and diffusion generators. | proposed |
| 56 | statistical-learning-and-high-dimensional-inference | graduate | specialization | regression-and-multivariate-statistics; convex-and-continuous-optimization | None | 12 | Analyze prediction, regularization, generalization, resampling, sparsity, kernels, ensembles, and high-dimensional uncertainty. | proposed |
| 57 | systems-and-control-theory | graduate | specialization | differential-equations | convex-and-continuous-optimization; combinatorial-optimization-and-networks | 12 | Analyze state-space systems, stability, controllability, observability, feedback, estimation, optimal control, and robustness. | proposed |
| 58 | numerical-pde-and-scientific-computing | graduate | specialization | numerical-analysis; partial-differential-equations-and-fourier-methods | None | 12 | Discretize and solve differential equations with finite difference, finite element, spectral, iterative, adaptive, and scalable methods. | proposed |
| 59 | variational-methods-and-mathematical-physics | graduate | specialization | functional-analysis-and-operator-theory; partial-differential-equations-and-fourier-methods | differential-geometry-and-manifolds | 12 | Use variational principles, symmetries, conservation laws, spectral methods, and field equations across continuum and quantum models. | proposed |
| 60 | arithmetic-geometry | research-specialization | specialization | algebraic-geometry; algebraic-number-theory | None | 10 | Enter literature on rational and integral points, elliptic curves, heights, reduction, moduli, and arithmetic invariants. | proposed |
| 61 | geometric-analysis | research-specialization | specialization | differential-topology-and-global-analysis; graduate-pde-and-distributions | None | 10 | Enter literature connecting curvature, geometric variational problems, elliptic and parabolic PDE, flows, compactness, and singularities. | proposed |
| 62 | topological-and-geometric-data-analysis | research-specialization | specialization | algebraic-topology; regression-and-multivariate-statistics | None | 10 | Enter literature on persistent homology, shape summaries, manifold methods, stability, algorithms, and statistical validation for data. | proposed |
| 63 | inverse-problems-and-uncertainty-quantification | research-specialization | specialization | graduate-pde-and-distributions; stochastic-analysis; numerical-pde-and-scientific-computing | None | 12 | Enter literature on identifiability, regularization, Bayesian inversion, sensitivity, uncertainty propagation, and computational inference. | proposed |
| 64 | networks-and-complex-systems | research-specialization | specialization | probabilistic-and-extremal-combinatorics; nonlinear-dynamics-and-chaos; stochastic-processes | combinatorial-optimization-and-networks | 10 | Enter literature on random, temporal, and multilayer networks, spreading, synchronization, emergence, inference, and intervention. | proposed |
| 65 | quantum-information-mathematics | research-specialization | specialization | information-theory; functional-analysis-and-operator-theory | representation-theory | 10 | Enter literature on quantum states, channels, entanglement, entropy, coding, algorithms, and operator-theoretic limits. | proposed |

## Coherence and prerequisite stress test

The proposed boundaries were tested against course scale, source grammar,
culminating performance, and false prerequisites:

- arithmetic, elementary algebra, geometry, precalculus, and mathematical
  computing stay separate because each can be learned and practiced
  independently;
- differential and integral single-variable calculus are separate course-scale
  capabilities, while integral calculus and series remain together because
  accumulation, approximation, and convergence form one conventional spine;
- proof literacy, formal logic, and set/model theory are different maturity
  levels rather than one oversized foundations deck;
- statistics is not hidden inside probability: probability models uncertainty,
  while statistics runs an investigative and inferential cycle with data,
  ethics, and diagnostics;
- continuous and combinatorial optimization are separate because their
  representations, algorithms, and prerequisites differ;
- information theory, algebraic coding/cryptography, and quantum information
  remain distinct rather than forcing algebra, probability, and operator theory
  on every learner at once;
- topology, algebraic topology, differential topology, and geometric analysis
  are layered by actual inbound structures;
- undergraduate PDE methods, graduate weak-solution theory, and numerical PDE
  are separate analytic, theoretical, and computational capabilities; and
- research-specialization decks integrate multiple mature branches only where
  that integration is the point of the field, such as inverse problems with
  uncertainty quantification.

Hard edges are intentionally sparse. For example, geometry is recommended
before trigonometry rather than imposed as a full-deck prerequisite;
linear algebra is recommended before multivariable calculus; game theory does
not require an entire probability course; financial mathematics can begin from
probability while stochastic processes remains recommended; and control theory
does not require all of convex optimization before its own foundations.

## Cross-deck concepts

These ideas recur with increasing depth. Later decks should retrieve a new use
or distinction, not duplicate an earlier target:

| Recurring concept | Progression |
|---|---|
| Quantity, units, scale, and approximation | Arithmetic estimation → algebraic modeling → calculus linearization → numerical error → asymptotic and uncertainty analysis. |
| Function, relation, and transformation | Tables and graphs → mappings and linear maps → operators, morphisms, functors, and dynamical evolution. |
| Proof, counterexample, and quantifier | Informal justification → proof methods → analysis/algebra rigor → formal logic → literature-facing reconstruction. |
| Structure, invariant, and symmetry | Algebraic properties → graph and geometric invariants → groups and representations → topology, Lie theory, and physics. |
| Local versus global | Derivatives and neighborhoods → manifolds and topology → global analysis, PDE, and geometric analysis. |
| Discrete versus continuous | Counting and graphs → calculus and differential equations → discretization, limits, stochastic processes, and hybrid models. |
| Randomness, dependence, and evidence | Probability models → statistical investigation → stochastic processes → measure probability, learning, and uncertainty quantification. |
| Optimization, duality, and tradeoff | Elementary extrema → convexity and network optimization → control, inference, variational principles, and inverse problems. |
| Algorithm, conditioning, and reproducibility | Foundational computing → numerical stability → optimization and simulation → scalable scientific computing and research replication. |
| Model, assumption, validation, and ethics | Quantitative word models → dedicated modeling cycle → statistics and domain models → uncertainty, stakeholder impact, and limitations. |

## Practice outside SRS

Flashcards may maintain definitions, hypotheses, method triggers, proof ideas,
representation translations, error checks, and discriminations. They do not
replace:

- sustained mixed problem solving and complete derivations;
- proof discovery, full proof writing, critique, and revision;
- geometric construction and exploratory visualization;
- reproducible programming, numerical experiments, simulation, and testing;
- statistical studies with authentic data, design, diagnostics, and ethics;
- open-ended model formulation, calibration, validation, and sensitivity work;
- oral and written exposition, seminars, collaboration, and peer review; or
- capstones, research experiences, literature reviews, and consultation with
  application-domain experts.

## Future extension points

Deferred rows are visible branch points, not ceilings. Several complex
variables and potential theory can follow complex, harmonic, functional, and
PDE analysis. K-theory, higher categories, and derived geometry can follow
algebraic topology, homological algebra, and algebraic geometry. Specialized
fluid, solid, material, relativity, climate, earth, and space models can grow
from PDE, geometry, dynamics, probability, numerics, and modeling once each has
its own authoritative domain source base.

Mathematics education, general computer science, and discipline-specific
science, engineering, and economics are out of this subject workspace, but
their mathematical intersections remain explicit. A later learner decision can
add those neighboring routes without renaming or deleting approved deck
identities.
