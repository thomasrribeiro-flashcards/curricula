# Mathematics learning roadmap

## Learner and destination

Summarize the destination from `SUBJECT_BRIEF.md`; keep detailed learner and
convention decisions there.

- Long-term capabilities: do mathematics rather than recall it — compute
  reliably, reason with definitions, write and evaluate proofs, translate among
  symbolic, graphical, numerical, geometric, and computational representations,
  model real situations and state the conditions under which a model holds, and
  read current mathematical literature well enough to follow, criticize, and
  extend it in at least one representative branch.
- Requested destination: whole-field — a faithful map of mathematics from first
  contact through representative graduate and research branches, not a route to
  one applied endpoint.
- Focus branches: none specified. No branch is privileged, so the graph carries
  a balanced set of representative research routes (arithmetic geometry,
  geometric topology, applied topological inference, formalization, and
  high-dimensional probability) instead of over-committing to one.
- Deck granularity: course. Each deck is a coherent course-sized capability with
  6–14 estimated chapters.

Destination controls the current route, not the permanent ceiling. Deferred
domains in the coverage matrix are named extension points, and every deck below
is `proposed` until a learner or maintainer approves it.

## Field coverage

Inventory the major domains before naming decks. Keep this matrix synchronized
with the `[[coverage]]` entries in `subject.toml`; every material domain must be
included, deliberately deferred, or explicitly out of scope.

| Domain | Disposition | Decks | Rationale |
|---|---|---|---|
| number-sense-and-quantitative-literacy | included | number-sense-and-arithmetic | First contact requires operational number reasoning before any symbolic or analytic work; nothing else in the graph is learnable without it. |
| school-algebra-and-elementary-functions | included | elementary-algebra-and-functions, precalculus-and-trigonometry | Symbolic fluency and the function concept are the shared entry point for calculus, linear algebra, and every modeling route, and are the capability neighboring subjects import. |
| euclidean-geometry-trigonometry-and-measurement | included | geometry-and-measurement, precalculus-and-trigonometry | Metric and transformational geometry supply the spatial vocabulary and first deductive arguments used throughout analysis, geometry, and applications. |
| mathematical-logic-and-foundations | included | mathematical-reasoning-and-proof, mathematical-logic-and-set-theory | Proof competence gates every advanced deck; the formal study of languages, models, and computability is then a distinct upper-division capability. |
| single-variable-calculus-and-real-functions | included | single-variable-differential-calculus, single-variable-integral-calculus | Split into two decks because differentiation and integration have different capstone performances, and neighboring subjects depend on the integral deck specifically. |
| multivariable-and-vector-calculus | included | multivariable-and-vector-calculus | Fields, flux, and the classical integral theorems form one coherent course and are the prerequisite that geometry, complex analysis, and continuum applications actually need. |
| linear-and-multilinear-algebra | included | linear-algebra | Named by every surveyed framework as invariant core, and required by algebra, differential equations, numerics, optimization, and data-facing routes. |
| real-analysis-measure-and-integration | included | real-analysis, measure-theory-and-lebesgue-integration | Rigorous single-variable analysis and abstract measure theory are separate courses with different prerequisites; measure theory is the universal graduate gate. |
| complex-analysis | included | complex-analysis | A recurring qualifying-exam cluster and a working tool for number theory, PDE, and applied transforms. |
| functional-analysis-and-operator-theory | included | functional-analysis | Infinite-dimensional linear analysis is the shared graduate language of modern PDE, probability, and numerical approximation. |
| harmonic-analysis-and-integral-transforms | included | harmonic-and-fourier-analysis | Fourier and singular-integral methods are a distinct analytic area rather than an appendix to PDE, and support signal, dispersive, and number-theoretic work. |
| ordinary-differential-equations | included | differential-equations | The central deterministic modeling course, and the specific capability that neighboring physical-science decks import. |
| partial-differential-equations | included | partial-differential-equations, modern-pde-and-sobolev-theory | Classical solution methods and modern weak-solution theory require different maturity, so the classical route is not gated on functional analysis. |
| dynamical-systems-and-ergodic-theory | included | dynamical-systems-and-ergodic-theory | Qualitative long-run behavior of flows, maps, and invariant measures is a standing research area in its own right. |
| groups-rings-fields-and-galois-theory | included | abstract-algebra, advanced-algebra-and-galois-theory, commutative-algebra | Three ordered capabilities: first structures, then modules and the Galois correspondence, then the ring theory that algebraic geometry and number theory consume. |
| category-theory-and-homological-algebra | included | category-theory-and-homological-algebra | Now a working language rather than a coda; recent growth in higher-categorical and homotopical classification headings supports a standalone deck. |
| representation-theory-and-lie-theory | included | representation-theory-and-lie-theory | A named research section and a recurring departmental group, unified by decomposing actions on vector spaces from finite groups through Lie algebras. |
| number-theory | included | number-theory, algebraic-number-theory, analytic-number-theory, arithmetic-geometry-and-modern-number-theory | An elementary proof-rich entry, separate graduate algebraic and analytic routes with different prerequisites, and a literature-facing branch avoid forcing either graduate route through the other's tools. |
| algebraic-geometry | included | algebraic-geometry, arithmetic-geometry-and-modern-number-theory | A top-level research section whose graduate entry is well defined once commutative algebra is in place. |
| general-topology | included | general-topology | Point-set topology is the shared language of convergence and continuity for analysis, geometry, and algebraic topology. |
| algebraic-and-geometric-topology | included | algebraic-topology, low-dimensional-topology-and-geometric-topology | Algebraic invariants form the graduate core; low-dimensional and geometric topology is the representative frontier branch. |
| differential-geometry-and-global-analysis | included | differential-geometry-and-manifolds, riemannian-geometry-and-geometric-analysis | Manifolds, forms, and first metrics are separable from comparison geometry and analytic methods on manifolds, which need real-analysis maturity. |
| convex-and-discrete-geometry | included | optimization-and-operations-research, discrete-mathematics-and-combinatorics | Convexity, polyhedra, and separating hyperplanes are taught where they do work; deeper packing, lattice, and rigidity theory is a future extension. |
| combinatorics-and-graph-theory | included | discrete-mathematics-and-combinatorics, advanced-combinatorics-and-graph-theory | A proof-based undergraduate entry and a graduate extremal, probabilistic, and spectral branch match how the area is taught and researched. |
| probability-and-stochastic-processes | included | probability, stochastic-processes, measure-theoretic-probability, stochastic-analysis-and-sdes, random-matrices-and-high-dimensional-probability | Probability spans four maturity levels with genuinely different tools, so it is staged rather than compressed into one oversized deck. |
| statistics-machine-learning-and-data-analysis | included | statistical-inference-and-data-analysis, mathematics-of-machine-learning-and-data-science, topological-and-geometric-data-analysis | Statistical inference is framework-mandated undergraduate core; the mathematics of learning and applied topological inference are current, separately staffed research directions. |
| numerical-analysis-and-scientific-computing | included | mathematical-computing-and-experimentation, numerical-analysis, numerical-methods-for-differential-equations | Computing literacy, error and stability analysis, and discretization of differential equations are three distinct capabilities with different prerequisites. |
| approximation-and-expansions | included | single-variable-integral-calculus, numerical-analysis | Taylor and series expansions are established in calculus and extended into interpolation and best-approximation error analysis in numerics. |
| sequences-series-and-difference-equations | included | single-variable-integral-calculus, discrete-mathematics-and-combinatorics | Convergence of series belongs with integral calculus; recurrences and generating functions belong with discrete structures. |
| optimization-and-operations-research | included | optimization-and-operations-research | Linear, convex, and combinatorial optimization share one conceptual spine of feasibility, optimality conditions, and duality. |
| information-and-communication-theory | included | information-theory | Entropy and coding limits are a coherent probabilistic capability that neighboring subjects import directly. |
| mathematics-of-computation-and-computer-science | included | theory-of-computation-and-complexity, formalization-and-proof-assistants | Computability and complexity form the classical mathematical core of the interface; machine-checked mathematics is the current growth edge recognized by a new classification heading. |
| mathematical-modeling-and-asymptotic-analysis | included | mathematical-modeling-and-asymptotic-methods | Framework guidance requires deliberate modeling practice; scaling, nondimensionalization, and perturbation methods give it a real conceptual spine instead of a label. |
| mathematical-research-practice-and-scholarship | included | mathematical-research-practice | Literature navigation, exposition, refereeing, and problem formulation are taught skills; without them a research-specialization deck would be a level jump. |
| control-theory-and-systems | deferred | None | Optimal control shares the optimization deck's optimality-condition spine, but feedback, observability, and stabilization deserve their own deck in a later extension. |
| several-complex-variables-and-potential-theory | deferred | None | A genuine domain that presupposes one-variable complex analysis plus manifold or PDE maturity; a visible extension point rather than an initial route. |
| k-theory | deferred | None | Requires algebraic topology and homological algebra to already be durable; scheduled after those decks exist. |
| order-lattices-and-general-algebraic-systems | deferred | None | Partial orders appear inside discrete mathematics, but lattice theory and universal algebra as fields are postponed. |
| special-functions | deferred | None | Orthogonal polynomials and classical special functions arise inside differential equations and harmonic analysis; a dedicated treatment is a later extension. |
| non-euclidean-and-projective-geometry | deferred | None | Axiomatic, projective, and synthetic hyperbolic geometry form a distinct route; hyperbolic structures currently appear only through the geometric-topology branch. |
| mathematical-physics | deferred | None | Operator algebras, integrable systems, and field-theoretic mathematics need functional analysis, Lie theory, and geometry first; physical content is already reachable through the physics subject. |
| mathematical-biology | deferred | None | The modeling, dynamics, and stochastic tools are built here, while biological application decks already exist in the biology subject. |
| game-theory-economics-and-mathematical-finance | deferred | None | Equilibrium theory and arbitrage pricing build directly on optimization and stochastic analysis; a deliberate later branch rather than a hidden appendix. |
| history-and-philosophy-of-mathematics | deferred | None | Valuable for perspective and named in curriculum guidance, but a distinct scholarly register that is postponed rather than diluted into technical decks. |
| mathematics-education | deferred | None | A real research domain of the field, but its practice horizon is teaching rather than doing mathematics; postponed until requested. |
| mechanics-continua-optics-and-thermodynamics-applications | out-of-scope | None | Classified under mathematics only as application headings; the physical content is owned by the physics subject and reachable through cross-subject references. |
| astronomy-geophysics-and-earth-system-applications | out-of-scope | None | Outside this subject's declared boundary; owned by physical-science subjects rather than duplicated here. |

## Audit against the supplied baseline

The staged curriculum was treated as a baseline, not accepted by inertia. Fifty-one
of its 52 deck identities remain valid and are preserved. Three corrections follow
from the course-coherence and prerequisite-closure stress tests:

- `algebraic-and-analytic-number-theory` is replaced by
  `algebraic-number-theory` and `analytic-number-theory`. The former needs advanced
  algebra but not complex analysis; the latter needs complex analysis but not the
  graduate algebra sequence. Keeping them together created two false prerequisites,
  two source registers, and two independent capstone performances.
- `numerical-analysis` keeps its identity but no longer claims initial-value-problem
  methods. That material belongs to `numerical-methods-for-differential-equations`,
  whose closure actually contains differential equations; the correction preserves
  a coherent error, stability, and algebraic-algorithm course without adding a broad
  ODE prerequisite for one internal topic.
- `random-matrices-and-high-dimensional-probability` now directly requires
  `linear-algebra`. Measure-theoretic probability does not establish eigenvalues,
  singular values, matrix norms, or spectral decompositions, and recommended
  sequencing cannot repair a missing hard capability.

The field dispositions, the one soft external reference, and all other deck
identities survived the audit. Orders after the number-theory split move by one;
orders are topological presentation values, not identities.

## Deck sequence

Define a prerequisite graph rather than an arbitrary textbook chapter list.
This table explains the learner-facing sequence. Keep it synchronized with
`subject.toml`, which is the executable source of truth for the subject graph.
Each created deck then records its inherited direct edges in `deck.toml`.
Hard prerequisites are required inbound knowledge; recommended sequencing is
helpful but is not inherited as a prerequisite.

| Order | Deck | Level | Tier | Hard prerequisites | Recommended after | Est. chapters | Durable capabilities | Status |
|---:|---|---|---|---|---|---:|---|---|
| 1 | number-sense-and-arithmetic | foundational | core | None | None | 9 | Reason with whole numbers, integers, fractions, decimals, ratio, percent, place value, and estimation, and justify why each operation applies. | proposed |
| 2 | elementary-algebra-and-functions | foundational | core | number-sense-and-arithmetic | None | 12 | Manipulate symbolic expressions, solve equations, inequalities, and systems, and model with linear, quadratic, polynomial, rational, exponential, and logarithmic functions and their graphs. | proposed |
| 3 | geometry-and-measurement | foundational | core | elementary-algebra-and-functions | None | 10 | Reason about congruence, similarity, transformations, circles, right-triangle trigonometry, coordinate geometry, area, volume, units, and short deductive geometric arguments. | proposed |
| 4 | mathematical-computing-and-experimentation | foundational | core | elementary-algebra-and-functions | geometry-and-measurement | 9 | Use a programming environment, symbolic and numeric tools, plotting, floating-point awareness, and reproducible notebooks to explore mathematical objects and test conjectures. | proposed |
| 5 | precalculus-and-trigonometry | foundational | core | geometry-and-measurement | None | 10 | Work fluently with circular trigonometric functions and identities, conic sections, polar and parametric descriptions, plane vectors, sequences, and limit-ready behavior of functions. | proposed |
| 6 | mathematical-reasoning-and-proof | undergraduate-core | core | elementary-algebra-and-functions | geometry-and-measurement, precalculus-and-trigonometry | 10 | Read, evaluate, and write correct proofs using logic, quantifiers, sets, relations, functions, induction, contradiction, contraposition, and elementary cardinality. | proposed |
| 7 | single-variable-differential-calculus | undergraduate-core | core | precalculus-and-trigonometry | None | 9 | Use limits, continuity, and derivatives to model rates, approximate locally, and analyze extrema, concavity, and optimization in one variable. | proposed |
| 8 | linear-algebra | undergraduate-core | core | elementary-algebra-and-functions | mathematical-reasoning-and-proof, single-variable-differential-calculus | 11 | Reason with vector spaces, linear maps, matrices, rank, determinants, eigenstructure, inner products, orthogonality, and matrix factorizations across algebraic, geometric, and computational views. | proposed |
| 9 | single-variable-integral-calculus | undergraduate-core | core | single-variable-differential-calculus | None | 11 | Use Riemann sums, the fundamental theorem, integration techniques, improper integrals, accumulation applications, and infinite series including Taylor expansions. | proposed |
| 10 | discrete-mathematics-and-combinatorics | undergraduate-core | core | mathematical-reasoning-and-proof | linear-algebra | 10 | Count with bijections, inclusion-exclusion, recurrences, and generating functions, and analyze graphs, trees, orders, and discrete structures with proof. | proposed |
| 11 | multivariable-and-vector-calculus | undergraduate-core | core | single-variable-integral-calculus | linear-algebra | 11 | Differentiate and integrate functions of several variables, use gradients and Jacobians, change coordinates, and apply the line, surface, Green, Stokes, and divergence theorems. | proposed |
| 12 | probability | undergraduate-core | core | single-variable-integral-calculus | discrete-mathematics-and-combinatorics | 11 | Model uncertainty with sample spaces, conditioning, independence, discrete and continuous random variables, joint behavior, expectation, and limit laws. | proposed |
| 13 | differential-equations | undergraduate-core | core | single-variable-integral-calculus, linear-algebra | multivariable-and-vector-calculus, mathematical-computing-and-experimentation | 11 | Formulate, solve, and qualitatively analyze ordinary differential equations and linear systems using analytic methods, transforms, eigenstructure, phase planes, and numerical schemes. | proposed |
| 14 | statistical-inference-and-data-analysis | undergraduate-core | core | probability | mathematical-computing-and-experimentation, linear-algebra | 11 | Summarize data honestly, reason about sampling distributions, estimate with uncertainty, test hypotheses, fit and criticize regression models, and state the limits of an inference. | proposed |
| 15 | number-theory | undergraduate-core | recommended | mathematical-reasoning-and-proof | discrete-mathematics-and-combinatorics | 10 | Prove and apply results about divisibility, primes, congruences, multiplicative functions, primitive roots, quadratic reciprocity, and Diophantine equations. | proposed |
| 16 | real-analysis | undergraduate-advanced | core | mathematical-reasoning-and-proof, single-variable-integral-calculus | None | 11 | Prove theorems about completeness, sequences, series, limits, continuity, differentiation, Riemann integration, and uniform convergence, and construct counterexamples. | proposed |
| 17 | abstract-algebra | undergraduate-advanced | core | mathematical-reasoning-and-proof | linear-algebra, number-theory | 12 | Reason with groups, subgroups, cosets, homomorphisms, quotients, group actions, rings, ideals, polynomial rings, and first field extensions. | proposed |
| 18 | complex-analysis | undergraduate-advanced | core | multivariable-and-vector-calculus, mathematical-reasoning-and-proof | real-analysis | 10 | Use holomorphy, the Cauchy-Riemann equations, contour integration, Cauchy theory, power and Laurent series, residues, and conformal mapping. | proposed |
| 19 | general-topology | undergraduate-advanced | core | real-analysis | None | 9 | Work with topological spaces, bases, continuity, homeomorphism, connectedness, compactness, separation axioms, product and quotient constructions, and metrization. | proposed |
| 20 | differential-geometry-and-manifolds | undergraduate-advanced | recommended | multivariable-and-vector-calculus, linear-algebra | real-analysis, general-topology | 13 | Analyze curves and surfaces with curvature and fundamental forms, then work on smooth manifolds with tangent spaces, vector fields, differential forms, Stokes' theorem, and first Riemannian metrics. | proposed |
| 21 | partial-differential-equations | undergraduate-advanced | core | differential-equations, multivariable-and-vector-calculus | real-analysis | 11 | Classify and solve first-order, heat, wave, and Laplace equations using characteristics, separation of variables, Fourier methods, Green's functions, and maximum principles. | proposed |
| 22 | numerical-analysis | undergraduate-advanced | core | linear-algebra, single-variable-integral-calculus, mathematical-computing-and-experimentation | differential-equations, real-analysis | 11 | Analyze floating-point error, conditioning, and stability while designing and assessing algorithms for roots, interpolation, quadrature, linear and nonlinear systems, least squares, and eigenvalues. | proposed |
| 23 | optimization-and-operations-research | undergraduate-advanced | recommended | multivariable-and-vector-calculus, linear-algebra | numerical-analysis, mathematical-computing-and-experimentation | 11 | Formulate and solve linear, convex, and constrained optimization problems using duality, optimality conditions, descent and Newton methods, network models, and integer formulations. | proposed |
| 24 | stochastic-processes | undergraduate-advanced | recommended | probability, linear-algebra | differential-equations, mathematical-computing-and-experimentation | 10 | Model systems evolving randomly in time with Markov chains, Poisson and renewal processes, queues, branching processes, elementary martingales, and Brownian motion. | proposed |
| 25 | information-theory | undergraduate-advanced | recommended | probability | discrete-mathematics-and-combinatorics, linear-algebra | 10 | Quantify information with entropy, relative entropy, and mutual information, and derive source-coding, channel-capacity, and error-correcting limits. | proposed |
| 26 | mathematical-logic-and-set-theory | undergraduate-advanced | recommended | mathematical-reasoning-and-proof | discrete-mathematics-and-combinatorics, abstract-algebra | 11 | Reason about formal languages, deduction, models, soundness, completeness, compactness, axiomatic set theory, ordinals and cardinals, computability, and incompleteness. | proposed |
| 27 | theory-of-computation-and-complexity | undergraduate-advanced | recommended | discrete-mathematics-and-combinatorics | mathematical-computing-and-experimentation, mathematical-logic-and-set-theory | 10 | Analyze automata, formal languages, Turing machines, decidability, reductions, complexity classes, NP-completeness, and randomized computation. | proposed |
| 28 | mathematical-modeling-and-asymptotic-methods | undergraduate-advanced | recommended | differential-equations, mathematical-computing-and-experimentation | partial-differential-equations, multivariable-and-vector-calculus, physics/measurement-and-physical-reasoning | 10 | Build, nondimensionalize, approximate, and validate models using scaling, dimensional analysis, perturbation and asymptotic expansions, compartment and continuum formulations, and sensitivity checks. | proposed |
| 29 | measure-theory-and-lebesgue-integration | graduate | core | real-analysis | None | 10 | Build sigma-algebras, measures, measurable functions, and the Lebesgue integral, and use convergence theorems, L^p spaces, product measures, and differentiation of measures. | proposed |
| 30 | advanced-algebra-and-galois-theory | graduate | core | abstract-algebra, linear-algebra | None | 12 | Use group actions and Sylow theory, modules over a PID with canonical forms, field extensions, and the Galois correspondence to settle solvability and constructibility questions. | proposed |
| 31 | mathematical-research-practice | graduate | core | mathematical-reasoning-and-proof | real-analysis, abstract-algebra, mathematical-computing-and-experimentation | 8 | Search and read the mathematical literature, write and typeset rigorous exposition, referee and present seminars, manage collaboration and attribution, and formulate tractable open questions. | proposed |
| 32 | functional-analysis | graduate | core | measure-theory-and-lebesgue-integration, linear-algebra | general-topology | 11 | Analyze normed, Banach, and Hilbert spaces, bounded and compact operators, the Hahn-Banach, open-mapping, closed-graph, and uniform-boundedness theorems, duality, weak topologies, and spectra. | proposed |
| 33 | measure-theoretic-probability | graduate | core | measure-theory-and-lebesgue-integration, probability | None | 11 | Ground probability in measure theory: independence, modes of convergence, laws of large numbers, characteristic functions, central limit theorems, conditional expectation, and martingales. | proposed |
| 34 | algebraic-topology | graduate | core | general-topology, abstract-algebra | None | 11 | Compute and interpret fundamental groups, covering spaces, CW structures, simplicial and singular homology, exact sequences, cohomology, and duality. | proposed |
| 35 | harmonic-and-fourier-analysis | graduate | recommended | measure-theory-and-lebesgue-integration | functional-analysis, complex-analysis | 10 | Analyze Fourier series and transforms on the circle and Euclidean space, convergence and summability, distributions, maximal functions, and singular integral operators. | proposed |
| 36 | category-theory-and-homological-algebra | graduate | recommended | advanced-algebra-and-galois-theory | algebraic-topology | 9 | Use categories, functors, natural transformations, limits, adjunctions, abelian categories, chain complexes, derived functors, and first spectral sequences as working tools. | proposed |
| 37 | commutative-algebra | graduate | recommended | advanced-algebra-and-galois-theory | number-theory | 10 | Work with Noetherian rings, modules, localization, primary decomposition, integral extensions, Hilbert basis and Nullstellensatz results, and dimension theory. | proposed |
| 38 | representation-theory-and-lie-theory | graduate | specialization | advanced-algebra-and-galois-theory | general-topology, differential-geometry-and-manifolds | 11 | Decompose representations of finite groups with characters and orthogonality, induce and restrict, and extend to Lie algebras, root systems, weights, and their classification. | proposed |
| 39 | algebraic-number-theory | graduate | specialization | advanced-algebra-and-galois-theory, number-theory | commutative-algebra | 10 | Study number fields, rings of integers, norms and traces, ramification, ideal factorization, class groups, units, local methods, and the arithmetic of extensions. | proposed |
| 40 | analytic-number-theory | graduate | specialization | complex-analysis, number-theory | harmonic-and-fourier-analysis | 10 | Use Dirichlet series, zeta and L-functions, character sums, Tauberian ideas, and sieve and circle methods to analyze primes and arithmetic functions. | proposed |
| 41 | modern-pde-and-sobolev-theory | graduate | specialization | functional-analysis, partial-differential-equations | harmonic-and-fourier-analysis | 11 | Use distributions, Sobolev spaces, weak formulations, variational and energy methods, elliptic regularity, and semigroup techniques to establish existence, uniqueness, and regularity. | proposed |
| 42 | algebraic-geometry | graduate | specialization | commutative-algebra | complex-analysis, category-theory-and-homological-algebra, algebraic-topology | 11 | Relate ideals to affine and projective varieties, work with morphisms, sheaves, and first schemes, and analyze curves through divisors and Riemann-Roch. | proposed |
| 43 | riemannian-geometry-and-geometric-analysis | graduate | specialization | differential-geometry-and-manifolds, real-analysis | general-topology, functional-analysis | 11 | Use connections, curvature tensors, geodesics, Jacobi fields, and comparison theorems, and connect curvature to topology through Laplacians, heat flow, and minimal surfaces. | proposed |
| 44 | dynamical-systems-and-ergodic-theory | graduate | specialization | measure-theory-and-lebesgue-integration, differential-equations | mathematical-computing-and-experimentation, functional-analysis | 11 | Analyze flows and maps through invariant sets, stability, bifurcation, hyperbolicity, symbolic dynamics, invariant measures, ergodic theorems, mixing, and entropy. | proposed |
| 45 | stochastic-analysis-and-sdes | graduate | specialization | measure-theoretic-probability | stochastic-processes, partial-differential-equations | 10 | Construct the Ito integral, apply Ito's formula, solve and approximate stochastic differential equations, and connect diffusions to parabolic equations and changes of measure. | proposed |
| 46 | advanced-combinatorics-and-graph-theory | graduate | specialization | discrete-mathematics-and-combinatorics, probability, linear-algebra | theory-of-computation-and-complexity, abstract-algebra | 10 | Prove extremal, Ramsey, and probabilistic-method results, analyze random graphs and thresholds, and use spectral and algebraic methods on combinatorial structures. | proposed |
| 47 | numerical-methods-for-differential-equations | graduate | specialization | numerical-analysis, partial-differential-equations | functional-analysis, optimization-and-operations-research | 10 | Design and analyze finite difference, finite element, and spectral discretizations with consistency, stability, convergence, conservation, and modern solver strategies. | proposed |
| 48 | mathematics-of-machine-learning-and-data-science | graduate | specialization | statistical-inference-and-data-analysis, optimization-and-operations-research, measure-theoretic-probability | numerical-analysis, functional-analysis | 11 | Establish learning guarantees with concentration, complexity measures, and empirical risk minimization, and analyze kernels, high-dimensional estimation, and optimization for modern learning models. | proposed |
| 49 | arithmetic-geometry-and-modern-number-theory | research-specialization | specialization | algebraic-number-theory, analytic-number-theory, algebraic-geometry, mathematical-research-practice | representation-theory-and-lie-theory | 10 | Read current work on elliptic curves, modular forms, Galois representations, rational points, L-functions, computational databases, and arithmetic statistics. | proposed |
| 50 | low-dimensional-topology-and-geometric-topology | research-specialization | specialization | algebraic-topology, riemannian-geometry-and-geometric-analysis, mathematical-research-practice | representation-theory-and-lie-theory | 10 | Engage literature on knots and links, surfaces and mapping class groups, three- and four-manifolds, hyperbolic structures, geometrization, and quantum and gauge-theoretic invariants. | proposed |
| 51 | topological-and-geometric-data-analysis | research-specialization | specialization | algebraic-topology, statistical-inference-and-data-analysis, mathematical-computing-and-experimentation, mathematical-research-practice | mathematics-of-machine-learning-and-data-science, category-theory-and-homological-algebra | 9 | Compute and interpret persistent homology and related invariants, justify stability and statistical guarantees, and critique applied topological and geometric inference in the literature. | proposed |
| 52 | formalization-and-proof-assistants | research-specialization | specialization | mathematical-logic-and-set-theory, mathematical-computing-and-experimentation, mathematical-research-practice | abstract-algebra, real-analysis, category-theory-and-homological-algebra | 9 | Formalize definitions, theorems, and proofs in a dependent-type proof assistant, navigate a mathematical library, and assess what machine-checked mathematics does and does not certify. | proposed |
| 53 | random-matrices-and-high-dimensional-probability | research-specialization | specialization | measure-theoretic-probability, linear-algebra, mathematical-research-practice | functional-analysis, harmonic-and-fourier-analysis, mathematics-of-machine-learning-and-data-science | 10 | Work with concentration of measure, empirical processes, spectral limits, universality, and free probability, and read current high-dimensional probability literature. | proposed |

## Sequencing decisions and rejected alternatives

The graph is deliberately narrow at the hard-edge level. Conventional course
catalogs encode scheduling habits as prerequisites; only genuine knowledge
dependencies appear in the `prerequisites` column.

- **Linear algebra is not gated on calculus.** Vector spaces, rank, and
  eigenstructure need symbolic fluency, not limits. Calculus appears as
  recommended sequencing because motivating examples and later applications read
  better with it, and proof exposure makes the abstract chapters easier.
- **Abstract algebra requires only proof.** Linear algebra and number theory are
  the two richest example sources, so they are recommended, but neither is
  needed to define a group or prove Lagrange's theorem.
- **Complex analysis does not hard-require real analysis.** Its actual
  dependencies are planar vector calculus (line integrals, Green's theorem,
  parametrized curves) plus proof literacy. A real-analysis-first ordering is
  common but is a maturity preference; it is recorded as recommended.
- **Probability does not hard-require discrete combinatorics.** Continuous
  probability rests on integration; the counting arguments in the discrete
  chapters make early chapters faster, so combinatorics is recommended.
- **Classical PDE is not gated on functional analysis.** Separation of variables,
  characteristics, and Green's functions are reachable from ODE plus
  multivariable calculus. Weak solutions live in a separate later deck, which is
  why the domain has two decks rather than one oversized one.
- **Single-variable calculus is split in two.** Differentiation and integration
  have different capstone performances (local approximation and optimization
  versus accumulation, techniques, and series), each fills a course-sized deck,
  and neighboring subjects import the integral capability specifically.
- **Differential geometry is kept as one 13-chapter deck.** The classical
  curves-and-surfaces half is the motivating source of curvature for the smooth
  manifolds half; splitting them would create a deck whose first chapter defines
  charts with no geometric reason to want them. Thirteen chapters stays inside
  the course granularity band.
- **`mathematical-computing-and-experimentation` sits in the foundational layer.**
  Its prerequisites are only symbolic algebra, and placing it early means
  conjecture-testing, plotting, and floating-point awareness are available
  throughout rather than being retrofitted at the numerical-analysis stage.
- **`mathematical-research-practice` is a real deck, not a preface.** It is a
  hard prerequisite of all five research-specialization decks. Without it, a
  learner would move from a graduate theory course directly into reading and
  critiquing current papers, which is exactly the level jump the workflow
  forbids.

## Cross-subject reuse

Mathematics declares **no hard external prerequisites**. It is the root subject
of the collection: the staged catalog shows biology and physics decks depending
on mathematics rather than the reverse, and every capability this subject needs
inbound is either universal literacy or supplied by an earlier deck here.
Twelve mathematics deck ids referenced by physics decks in the catalog —
`elementary-algebra-and-functions`, `precalculus-and-trigonometry`,
`single-variable-differential-calculus`, `single-variable-integral-calculus`,
`multivariable-and-vector-calculus`, `linear-algebra`, `differential-equations`,
`partial-differential-equations`, `probability`, `numerical-analysis`,
`mathematical-computing-and-experimentation`, and
`differential-geometry-and-manifolds` — are defined here under exactly those ids
so the collection-wide graph resolves.

One external edge exists, and it is deliberately soft:
`mathematical-modeling-and-asymptotic-methods` lists
`physics/measurement-and-physical-reasoning` under recommended sequencing.
Modeling improves markedly when a learner has already reasoned about units,
measurement, and idealization in a discipline that owns the phenomena, but the
deck teaches nondimensionalization and perturbation methods from mathematical
first principles and must remain learnable without leaving the subject. No
subject-local bridge deck duplicates physics content, because the transfer being
taught is mathematical abstraction of a situation, not physics itself.

## Maturity transitions

Every graduate and research-specialization deck is audited below: what its first
chapter is permitted to assume, and where the direct prerequisite closure
establishes it. No deck's opening assumptions exceed its closure.

### Graduate layer

- **measure-theory-and-lebesgue-integration** (29) — assumes epsilon-delta
  arguments, suprema and completeness, sequences and series of functions,
  uniform convergence, and the failure modes of the Riemann integral. All from
  `real-analysis`, which is itself gated on proof and integral calculus. The
  deck opens by exhibiting a Riemann-integration failure, so the motivating
  object is inbound rather than assumed.
- **advanced-algebra-and-galois-theory** (30) — assumes groups, quotients,
  actions, rings, ideals, polynomial rings, and first field extensions from
  `abstract-algebra`, plus bases, dimension, linear maps, and characteristic
  polynomials from `linear-algebra`. Both are direct hard prerequisites; modules
  are introduced here as the generalization of vector spaces, using established
  linear-algebra language.
- **mathematical-research-practice** (31) — assumes only the ability to read and
  write a correct proof, from `mathematical-reasoning-and-proof`. Deliberately
  the lightest closure in the graduate layer, because the deck teaches
  scholarship skills and must be reachable early enough to precede the research
  branches. Prior contact with a substantial theory course
  (`real-analysis`, `abstract-algebra`) and with computational tooling makes the
  literature examples richer, so those are recommended, not required.
- **functional-analysis** (32) — assumes measurable functions, L^p spaces,
  dominated convergence, and completeness of L^p from
  `measure-theory-and-lebesgue-integration`, and inner products, orthogonality,
  duality of finite-dimensional spaces, and adjoints from `linear-algebra`.
  Open sets, compactness, and continuity in metric spaces arrive through
  `measure-theory-and-lebesgue-integration` → `real-analysis`; abstract
  topological spaces are only needed for weak topologies, so `general-topology`
  is recommended and the weak-topology chapters self-bridge.
- **measure-theoretic-probability** (33) — assumes sigma-algebras, integration,
  and convergence theorems from `measure-theory-and-lebesgue-integration`, and
  the probabilistic vocabulary of random variables, independence, expectation,
  distributions, and informal limit laws from `probability`. Both are hard.
  The first chapter re-founds an already-familiar object rather than introducing
  probability for the first time.
- **algebraic-topology** (34) — assumes spaces, continuity, homeomorphism,
  compactness, connectedness, and quotient constructions from
  `general-topology`, and groups, homomorphisms, quotients, and abelian groups
  from `abstract-algebra`. Both are hard; exact sequences and the functorial
  framing are built here.
- **harmonic-and-fourier-analysis** (35) — assumes L^p spaces, dominated
  convergence, Fubini, and approximation by simple functions from
  `measure-theory-and-lebesgue-integration`. Hilbert-space language and contour
  methods sharpen several chapters, so `functional-analysis` and
  `complex-analysis` are recommended; the deck develops the Hilbert-space facts
  it needs for L^2 theory directly from the inner product.
- **category-theory-and-homological-algebra** (36) — assumes modules,
  homomorphisms, quotients, and enough structural experience for abstraction to
  be motivated rather than empty, from `advanced-algebra-and-galois-theory`.
  Exact sequences are introduced here before they support homological algebra.
  Topological examples make the derived-functor chapters concrete, so
  `algebraic-topology` is recommended; every mandatory example is algebraic.
- **commutative-algebra** (37) — assumes rings, ideals, quotients, polynomial
  rings, modules, and field extensions from `advanced-algebra-and-galois-theory`.
  Number-theoretic examples such as rings of integers motivate integrality, so
  `number-theory` is recommended.
- **representation-theory-and-lie-theory** (38) — assumes group actions, Sylow
  theory, modules, canonical forms, and field extensions from
  `advanced-algebra-and-galois-theory`, which also carries the required linear
  algebra transitively. Matrix Lie groups are introduced concretely, so
  topology and manifolds are recommended rather than required; the deck states
  which smooth-structure claims it takes on faith and which it proves.
- **algebraic-number-theory** (39) — assumes fields, extensions, Galois
  language, modules, and canonical forms from
  `advanced-algebra-and-galois-theory`, plus divisibility, congruences, and
  quadratic reciprocity from `number-theory`. Both are hard. The first chapter
  constructs number fields and introduces norms, traces, and rings of integers;
  localization and dimension theory from `commutative-algebra` are helpful later
  but are not needed to begin, so that deck is recommended.
- **analytic-number-theory** (40) — assumes holomorphic and meromorphic
  functions, contour integration, residues, and power and Laurent series
  from `complex-analysis`, plus multiplicative functions, congruences, and prime
  arithmetic from `number-theory`. Both are hard. Analytic continuation,
  Dirichlet characters, Tauberian arguments, and sieve language are introduced
  here; Fourier methods enrich the circle-method chapters, so
  `harmonic-and-fourier-analysis` is recommended rather than required.
- **modern-pde-and-sobolev-theory** (41) — assumes Banach and Hilbert spaces,
  bounded operators, duality, and weak convergence from `functional-analysis`,
  and the classical equations,
  boundary conditions, and maximum principles from
  `partial-differential-equations`. Both are hard. The opening variational
  sequence establishes Riesz-representation and Lax-Milgram machinery before
  using it; `harmonic-and-fourier-analysis` sharpens the regularity chapters and
  is recommended.
- **algebraic-geometry** (42) — assumes Noetherian rings, localization, primary
  decomposition, integral extensions, and the Nullstellensatz from
  `commutative-algebra`, which transitively supplies all needed algebra. Sheaf
  cohomology, Riemann surfaces, and homological tools appear as recommended
  companions; the first chapters stay with varieties and morphisms so the
  closure is sufficient.
- **riemannian-geometry-and-geometric-analysis** (43) — assumes smooth
  manifolds, tangent spaces, vector fields, differential forms, Stokes'
  theorem, and first metrics from `differential-geometry-and-manifolds`, and
  rigorous limit, compactness, and convergence arguments from `real-analysis`.
  The geometric-analysis chapters use elliptic estimates; those are stated with
  precise hypotheses and referenced, with `functional-analysis` recommended for
  learners who want the proofs.
- **dynamical-systems-and-ergodic-theory** (44) — assumes measures and the
  Lebesgue integral from `measure-theory-and-lebesgue-integration`, and
  flows, linearization, equilibria, and phase-plane analysis from
  `differential-equations`. Both hard, matching the deck's two halves.
  Invariant measures are introduced here. Numerical experimentation and operator
  methods are recommended.
- **stochastic-analysis-and-sdes** (45) — assumes filtrations, conditional
  expectation, martingale convergence, and modes of convergence from
  `measure-theoretic-probability`, which is the only genuinely required inbound
  deck since it transitively supplies both measure theory and elementary
  probability. Brownian motion is constructed here rather than assumed, so
  `stochastic-processes` is recommended; the Feynman-Kac chapter is where
  `partial-differential-equations` helps.
- **advanced-combinatorics-and-graph-theory** (46) — assumes counting,
  generating functions, and graph fundamentals from
  `discrete-mathematics-and-combinatorics`; expectation, variance, independence,
  and limit-law vocabulary from `probability`; and eigenvalues and rank arguments
  from `linear-algebra`. All three are used from the early chapters onward;
  probabilistic-method tail bounds and graph spectra are developed here.
- **numerical-methods-for-differential-equations** (47) — assumes conditioning,
  stability, convergence analysis, interpolation, quadrature, and linear solvers
  from `numerical-analysis` (which transitively carries the computing deck), and
  equation classification, classical solution behavior, and boundary conditions
  from `partial-differential-equations`. Well-posedness criteria and the weak
  formulation are introduced here before discretization; `functional-analysis`
  is recommended for the abstract convergence theory.
- **mathematics-of-machine-learning-and-data-science** (48) — assumes
  estimation, risk, bias-variance reasoning, and model criticism from
  `statistical-inference-and-data-analysis`; convexity, duality, and gradient
  and Newton methods from `optimization-and-operations-research`; and rigorous
  conditional expectation, martingales, and convergence modes from
  `measure-theoretic-probability`. Concentration inequalities are developed here.
  The third edge is what separates this deck from an undergraduate methods course
  and is why the deck is graduate rather than undergraduate-advanced.

### Research-specialization layer

Each of these decks is literature-facing: chapters read, situate, and criticize
current work. Every one therefore lists `mathematical-research-practice` as a
hard prerequisite in addition to its technical closure, so no route reaches a
paper without first learning to read one.

- **arithmetic-geometry-and-modern-number-theory** (49) — first chapter assumes
  number fields, ramification, class groups, and local methods from
  `algebraic-number-theory`; Dirichlet series, L-functions, and analytic estimates
  from `analytic-number-theory`; varieties, morphisms, divisors, and Riemann-Roch
  from `algebraic-geometry`; and literature navigation and exposition from
  `mathematical-research-practice`. These four capabilities are independently
  needed by the deck, so none is redundant. Galois representations build on the
  algebraic route's transitive Galois theory; deeper representation theory remains
  recommended.
- **low-dimensional-topology-and-geometric-topology** (50) — assumes fundamental
  groups, covering spaces, homology, and cohomological duality from
  `algebraic-topology`; curvature, geodesics, comparison arguments, and
  constant-curvature model spaces from
  `riemannian-geometry-and-geometric-analysis`; and research practice from
  `mathematical-research-practice`. Hyperbolic structures and geometrization
  need both the topological invariants and the metric geometry, which is why the
  deck sits after both rather than after topology alone.
- **topological-and-geometric-data-analysis** (51) — assumes simplicial and
  singular homology and functoriality from `algebraic-topology`; sampling,
  estimation, confidence statements, and model criticism from
  `statistical-inference-and-data-analysis`; working computational practice from
  `mathematical-computing-and-experimentation`; and paper-reading from
  `mathematical-research-practice`. Four hard edges are unusual, but the deck's
  first chapter genuinely computes a persistence diagram from sampled data and
  asks whether the feature is real — which requires topology, statistics, and
  computation simultaneously. Category-theoretic framing of persistence modules
  is recommended and self-bridged where used.
- **formalization-and-proof-assistants** (52) — assumes formal languages,
  deduction, models, and the syntax-semantics distinction from
  `mathematical-logic-and-set-theory`; practical programming and environment
  fluency from `mathematical-computing-and-experimentation`; and
  literature and library navigation from `mathematical-research-practice`.
  Version control and dependent type theory are developed here against the
  learner's existing tooling and first-order background. The deck formalizes
  mathematics the learner already knows, so `abstract-algebra` and
  `real-analysis` are recommended to widen the pool of formalizable targets
  rather than required.
- **random-matrices-and-high-dimensional-probability** (53) — assumes
  characteristic functions, martingales, conditional expectation, and
  convergence in distribution from `measure-theoretic-probability`; eigenvalues,
  inner products, orthogonality, and matrix factorizations from the direct
  `linear-algebra` edge; and literature practice from
  `mathematical-research-practice`. Operator-theoretic and Fourier refinements
  remain recommended companions for the free-probability and universality
  chapters.

No level jump is retained anywhere in the graph without a stated closure above.
The one transition that would otherwise be a jump — undergraduate theory
directly into literature-facing research — is bridged by
`mathematical-research-practice`.

## Cross-deck concepts

List ideas and representations that should recur with increasing depth rather
than being duplicated independently.

- **Function.** Rule and table (2) → graph and transformation (2, 3) → local
  linear approximation (7) → operator on a vector space (8) → measurable map
  (29) → point of a function space (32) → morphism in a category (36).
- **Linearity and approximation.** Proportional reasoning (1) → linear models
  (2) → tangent lines and Taylor polynomials (7, 9) → Jacobians and
  differentials (11) → best approximation and conditioning (22) → weak
  formulations and Galerkin projection (41, 47).
- **Limit and convergence.** Informal end behavior (5) → limits and continuity
  (7) → series convergence (9) → epsilon-delta proof and uniform convergence
  (16) → topological convergence (19) → almost-everywhere and L^p convergence
  (29) → convergence in distribution and weak-* convergence (32, 33).
- **Invariance and symmetry.** Rigid motions (3) → trigonometric identities (5)
  → eigenvectors and invariant subspaces (8) → group actions (17) → Galois
  correspondence (30) → topological invariants (34) → invariant measures (44).
- **Uncertainty.** Counting and proportion (1, 10) → probability models (12) →
  sampling distributions and inference (14) → processes in time (24) →
  measure-theoretic foundation (33) → stochastic calculus (45) →
  high-dimensional concentration (53).
- **Proof standards.** Deductive geometric argument (3) → formal proof technique
  (6) → analysis and algebra proof idioms (16, 17) → literature-grade exposition
  (31) → machine-checked proof (52).
- **Computation as evidence.** Exploration and conjecture (4) → numerical error
  and stability (22) → algorithmic feasibility and complexity (27) →
  discretization and simulation (47) → computational databases and experiment in
  research (49, 51).
- **Geometry of space.** Measurement and coordinates (3) → vectors and
  parametrization (5, 11) → curvature of curves and surfaces (20) → abstract
  spaces (19) → curvature-topology interaction (43, 50).

## Practice outside SRS

Record skills that require projects, extended problems, laboratories, writing,
conversation, or other practice that flashcards cannot replace.

- **Multi-step problem sets.** Retrieval cards secure definitions, mechanisms,
  and short discriminations; sustained computation and long proof construction
  need untimed written problems. Every deck from 6 onward should be paired with
  a problem source.
- **Proof writing under critique.** Writing a full proof and having it read is
  not reproducible on a card. Decks 6, 16, 17, and 31 depend on it most.
- **Programming and numerical experiments.** Decks 4, 22, 27, 44, 47, 51, and 52
  require a working environment, real code, and reproducible artifacts.
- **Modeling projects.** Deck 28 and the data-facing decks (14, 48, 51) need
  open-ended projects with real or realistic data, including defending modeling
  choices and reporting failure.
- **Reading a paper end to end.** Decks 31 and 49–53 require sustained reading,
  seminar presentation, and question formulation. Cards can hold definitions and
  landmark results; they cannot hold the practice of getting stuck productively.
- **Formalization practice.** Deck 52 requires an installed proof assistant and
  library, since the feedback loop is the assistant itself.
- **Mathematical conversation.** Explaining an argument aloud and being
  questioned exposes gaps that recognition-level review hides.

## Extension points

Deferred domains in the coverage matrix are the intended growth directions and
are ordered by how ready the current graph is to support them: control theory
and systems (after 23), several complex variables and potential theory
(after 18 and 20), game theory and mathematical finance (after 23 and 45),
special functions (after 13 and 35), non-Euclidean and projective geometry
(after 3 and 20), K-theory (after 34 and 36), order and universal algebra
(after 10 and 17), mathematical physics (after 32, 38, and 43), mathematical
biology (after 13 and 28), and the history, philosophy, and education of
mathematics as a distinct scholarly register.
