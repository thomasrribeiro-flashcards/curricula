# Mathematics curriculum structural diff

Identity matching is exact, not semantic: an added/removed ID may represent a rename or split. See the reviewed comparison for interpretation.

| Metric | Current baseline | Astra candidate |
|---|---:|---:|
| decks | 55 | 86 |
| hardEdges | 92 | 150 |
| recommendedEdges | 79 | 60 |
| estimatedChapters | 568 | 818 |

Shared IDs: 35.

## Added IDs

- **data-and-chance** (foundational; prerequisites: elementary-algebra-and-functions): Read data displays and reason about variability, sampling, association, and elementary chance without calculus.
- **elementary-number-theory** (undergraduate-core; prerequisites: mathematical-reasoning-and-proof): Prove divisibility and congruence results and solve elementary integer equations.
- **group-theory** (undergraduate-core; prerequisites: mathematical-reasoning-and-proof): Use group actions, homomorphisms, quotients, and structure theorems to analyze symmetry.
- **rings-and-polynomials** (undergraduate-core; prerequisites: mathematical-reasoning-and-proof): Reason with rings, ideals, quotient constructions, polynomial arithmetic, divisibility, and fields as coefficient systems.
- **mathematical-modeling** (undergraduate-core; prerequisites: differential-equations, mathematical-computing-and-experimentation): Build, scale, analyze, validate, and communicate deterministic models with explicit assumptions and failure tests.
- **advanced-linear-algebra** (undergraduate-advanced; prerequisites: linear-algebra, mathematical-reasoning-and-proof): Prove finite-dimensional structure results using duality, canonical forms, bilinear forms, and tensor constructions.
- **metric-and-general-topology** (undergraduate-advanced; prerequisites: mathematical-reasoning-and-proof): Prove continuity, compactness, connectedness, separation, and product or quotient properties using topological definitions.
- **graph-theory** (undergraduate-advanced; prerequisites: discrete-mathematics-and-combinatorics): Prove structural graph results and use connectivity, matching, coloring, and extremal methods.
- **fields-and-galois-theory** (undergraduate-advanced; prerequisites: rings-and-polynomials, group-theory, linear-algebra): Relate field extensions and polynomial solvability to automorphism groups and Galois correspondence.
- **modules-and-linear-structures** (undergraduate-advanced; prerequisites: rings-and-polynomials, linear-algebra): Analyze modules and module maps through quotients, generators, exact sequences, tensor products, and PID structure.
- **category-theory** (undergraduate-advanced; prerequisites: mathematical-reasoning-and-proof): Recognize universal properties and reason with categories, functors, natural transformations, limits, and adjunctions.
- **euclidean-and-non-euclidean-geometry** (undergraduate-advanced; prerequisites: geometry-and-measurement, mathematical-reasoning-and-proof): Compare axiomatic, synthetic, and model-based geometry through incidence, congruence, parallelism, and invariants.
- **measure-and-integration** (undergraduate-advanced; prerequisites: real-analysis): Construct measures and Lebesgue integrals and justify convergence, product integration, differentiation of measures, and Lp estimates.
- **fourier-analysis-and-transforms** (undergraduate-advanced; prerequisites: single-variable-integral-calculus, linear-algebra, mathematical-reasoning-and-proof): Translate functions and signals into orthogonal expansions, Fourier transforms, convolution, and sampling with bounded convergence claims.
- **nonlinear-dynamics** (undergraduate-advanced; prerequisites: differential-equations): Analyze deterministic maps and flows using stability, phase portraits, bifurcations, and controlled chaos examples.
- **regression-and-statistical-models** (undergraduate-advanced; prerequisites: statistical-inference-and-data-analysis, linear-algebra): Fit and diagnose linear and generalized linear models and communicate model uncertainty and limitations.
- **mathematical-statistics** (undergraduate-advanced; prerequisites: probability, mathematical-reasoning-and-proof): Derive properties of estimators and tests using likelihood, sufficiency, information, decision criteria, and asymptotic arguments.
- **experimental-design-and-causal-inference** (undergraduate-advanced; prerequisites: statistical-inference-and-data-analysis): Distinguish causal identification from estimation and design randomized or observational comparisons with explicit assumptions.
- **algebraic-coding-theory** (undergraduate-advanced; prerequisites: rings-and-polynomials, linear-algebra): Construct and decode finite-field error-correcting codes and prove distance and correction guarantees.
- **mathematical-cryptography** (undergraduate-advanced; prerequisites: elementary-number-theory, theory-of-computation-and-complexity, probability): Distinguish mathematical cryptographic guarantees from assumptions using adversarial games, reductions, modular constructions, and probability bounds.
- **mathematical-writing-and-research-practice** (undergraduate-advanced; prerequisites: mathematical-reasoning-and-proof): Find mathematical sources, reconstruct arguments, manage notation and citations, and produce a checked expository investigation.
- **game-theory-and-mathematical-economics** (undergraduate-advanced; prerequisites: probability, optimization-and-operations-research): Analyze strategic interaction and economic allocation with equilibria, convexity, incentives, and welfare assumptions.
- **financial-and-actuarial-mathematics** (undergraduate-advanced; prerequisites: probability, linear-algebra): Value deterministic and discrete stochastic cash flows and reason about survival, loss, reserves, and no-arbitrage pricing.
- **mathematical-biology-models** (undergraduate-advanced; prerequisites: mathematical-modeling, probability): Derive and test population and epidemic models using demographic, interaction, stochastic, and identifiability reasoning.
- **homological-algebra** (graduate; prerequisites: modules-and-linear-structures): Compute homological invariants with chain complexes, projective and injective resolutions, and derived functors.
- **algebraic-geometry-of-varieties** (graduate; prerequisites: commutative-algebra, metric-and-general-topology): Translate polynomial equations into affine and projective varieties, morphisms, dimension, and local geometric structure.
- **schemes-and-sheaves** (graduate; prerequisites: algebraic-geometry-of-varieties, category-theory): Construct schemes by gluing locally ringed spaces and use sheaves, morphisms, divisors, and cohomology in controlled examples.
- **harmonic-analysis** (graduate; prerequisites: functional-analysis, fourier-analysis-and-transforms): Prove Fourier and convolution estimates and use maximal functions, interpolation, and singular-integral methods.
- **weak-solutions-and-sobolev-spaces** (graduate; prerequisites: partial-differential-equations, functional-analysis): Formulate PDEs distributionally and prove weak existence, uniqueness, and basic regularity using Sobolev and energy methods.
- **nonlinear-pde-and-variational-methods** (graduate; prerequisites: weak-solutions-and-sobolev-spaces): Use direct methods, compactness, monotonicity, and regularity estimates to analyze nonlinear variational PDEs.
- **stochastic-calculus** (graduate; prerequisites: measure-theoretic-probability): Construct and use Brownian stochastic integration, Ito calculus, stochastic differential equations, and measure change.
- **riemannian-geometry** (graduate; prerequisites: differential-geometry-and-manifolds, differential-equations): Compute and reason about metrics, connections, geodesics, curvature, completeness, and comparison on Riemannian manifolds.
- **advanced-algebraic-topology** (graduate; prerequisites: algebraic-topology, homological-algebra): Compute cohomological and homotopical invariants using products, duality, bundles, and spectral-sequence methods.
- **convex-and-nonlinear-optimization** (graduate; prerequisites: optimization-and-operations-research, real-analysis): Prove convergence and duality results for convex and constrained nonlinear optimization under explicit regularity conditions.
- **control-theory** (graduate; prerequisites: differential-equations, optimization-and-operations-research, mathematical-reasoning-and-proof): Analyze controllability, observability, feedback stability, estimation, and deterministic optimal control.
- **inverse-problems-and-regularization** (graduate; prerequisites: functional-analysis, numerical-analysis): Analyze identifiability and ill-posedness and construct stable regularized solutions with quantitative error diagnostics.
- **asymptotic-statistical-theory** (graduate; prerequisites: mathematical-statistics, measure-theoretic-probability, linear-algebra): Establish consistency, asymptotic distributions, efficiency, and resampling validity under explicit model and convergence conditions.
- **bayesian-inference-and-computation** (graduate; prerequisites: mathematical-statistics, mathematical-computing-and-experimentation): Build Bayesian models and audit posterior computation using conjugacy, hierarchical models, simulation, and predictive checks.
- **time-series-analysis** (graduate; prerequisites: stochastic-processes, regression-and-statistical-models): Model dependent observations using stationarity, autoregression, moving averages, spectra, and forecasting diagnostics.
- **probabilistic-and-extremal-combinatorics** (graduate; prerequisites: graph-theory, probability): Prove existence and extremal bounds with probabilistic, concentration, dependent-event, and structural methods.
- **model-theory** (graduate; prerequisites: mathematical-logic-and-computability): Analyze structures and theories using elementary maps, types, quantifier elimination, and saturation.
- **type-theory-and-formal-proof** (graduate; prerequisites: mathematical-logic-and-computability, computer-science/programming-and-software-development-foundations): Translate mathematical proofs into typed terms and checked formal developments while distinguishing kernel guarantees and axioms.
- **continuum-modeling-and-asymptotics** (graduate; prerequisites: partial-differential-equations, mathematical-modeling): Derive continuum balance models and analyze scale separation, perturbations, boundary layers, and reduced equations.
- **algebraic-geometry-research** (research-specialization; prerequisites: schemes-and-sheaves, mathematical-writing-and-research-practice): Read and reconstruct focused research arguments on curves and their deformations using scheme and sheaf methods.
- **geometric-topology-research** (research-specialization; prerequisites: advanced-algebraic-topology, mathematical-writing-and-research-practice): Evaluate focused research on topological invariants by reconstructing constructions, computations, and obstruction arguments.
- **nonlinear-analysis-research** (research-specialization; prerequisites: nonlinear-pde-and-variational-methods, mathematical-writing-and-research-practice): Reconstruct and critique research proofs for nonlinear elliptic variational problems using compactness and regularity estimates.
- **stochastic-analysis-research** (research-specialization; prerequisites: stochastic-calculus, mathematical-writing-and-research-practice): Read and verify focused diffusion research through stochastic representations, stopping, measure change, and pathwise assumptions.
- **scientific-computing-research** (research-specialization; prerequisites: numerical-methods-for-differential-equations, weak-solutions-and-sobolev-spaces, mathematical-writing-and-research-practice): Evaluate research on elliptic PDE discretization by connecting weak formulations, error arguments, and reproducible refinement studies.
- **statistical-learning-research** (research-specialization; prerequisites: mathematics-of-machine-learning-and-data-science, asymptotic-statistical-theory, mathematical-writing-and-research-practice): Critique focused statistical-learning research by reconstructing risk bounds, asymptotic arguments, and assumption-sensitive counterexamples.
- **combinatorics-research** (research-specialization; prerequisites: probabilistic-and-extremal-combinatorics, mathematical-writing-and-research-practice): Read and reconstruct finite extremal and probabilistic graph research through constructions, inequalities, and sharpness tests.
- **formal-mathematics-research** (research-specialization; prerequisites: type-theory-and-formal-proof, mathematical-writing-and-research-practice): Evaluate formal-mathematics research by auditing specifications, proof artifacts, trusted assumptions, and reproducible verification.

## Removed IDs

- **number-theory**: Prove and apply results about divisibility, primes, congruences, multiplicative functions, primitive roots, quadratic reciprocity, and Diophantine equations.
- **abstract-algebra**: Reason with groups, subgroups, cosets, homomorphisms, quotients, group actions, rings, ideals, polynomial rings, and first field extensions.
- **general-topology**: Work with topological spaces, bases, continuity, homeomorphism, connectedness, compactness, separation axioms, product and quotient constructions, and metrization.
- **mathematical-modeling-and-asymptotic-methods**: Build, nondimensionalize, approximate, and validate models using scaling, dimensional analysis, perturbation and asymptotic expansions, compartment and continuum formulations, and sensitivity checks.
- **measure-theory-and-lebesgue-integration**: Build sigma-algebras, measures, measurable functions, and the Lebesgue integral, and use convergence theorems, L^p spaces, product measures, and differentiation of measures.
- **advanced-algebra-and-galois-theory**: Use group actions and Sylow theory, modules over a PID with canonical forms, field extensions, and the Galois correspondence to settle solvability and constructibility questions.
- **mathematical-research-practice**: Search and read the mathematical literature, write and typeset rigorous exposition, referee and present seminars, manage collaboration and attribution, and formulate tractable open questions.
- **harmonic-and-fourier-analysis**: Analyze Fourier series and transforms on the circle and Euclidean space, convergence and summability, distributions, maximal functions, and singular integral operators.
- **category-theory-and-homological-algebra**: Use categories, functors, natural transformations, limits, adjunctions, abelian categories, chain complexes, derived functors, and first spectral sequences as working tools.
- **mathematical-statistics-and-asymptotic-inference**: Derive and compare likelihood, sufficiency, exponential-family, decision-theoretic, Bayesian, and asymptotic methods, and prove when estimators and tests achieve their guarantees.
- **modern-pde-and-sobolev-theory**: Use distributions, Sobolev spaces, weak formulations, variational and energy methods, elliptic regularity, and semigroup techniques to establish existence, uniqueness, and regularity.
- **algebraic-geometry**: Relate ideals to affine and projective varieties, work with morphisms, sheaves, and first schemes, and analyze curves through divisors and Riemann-Roch.
- **riemannian-geometry-and-geometric-analysis**: Use connections, curvature tensors, geodesics, Jacobi fields, and comparison theorems, and connect curvature to topology through Laplacians, heat flow, and minimal surfaces.
- **stochastic-analysis-and-sdes**: Construct the Ito integral, apply Ito's formula, solve and approximate stochastic differential equations, and connect diffusions to parabolic equations and changes of measure.
- **advanced-combinatorics-and-graph-theory**: Prove extremal, Ramsey, and probabilistic-method results, analyze random graphs and thresholds, and use spectral and algebraic methods on combinatorial structures.
- **arithmetic-geometry-and-modern-number-theory**: Read current work on elliptic curves, modular forms, Galois representations, rational points, L-functions, computational databases, and arithmetic statistics.
- **low-dimensional-topology-and-geometric-topology**: Engage literature on knots and links, surfaces and mapping class groups, three-manifolds, hyperbolic structures, geometrization, and geometric invariants, while identifying where four-dimensional and gauge-theoretic work needs further analysis.
- **topological-and-geometric-data-analysis**: Compute and interpret persistent homology and related invariants, justify stability and statistical guarantees, and critique applied topological and geometric inference in the literature.
- **formalization-and-proof-assistants**: Formalize definitions, theorems, and proofs in a dependent-type proof assistant, navigate a mathematical library, and assess what machine-checked mathematics does and does not certify.
- **random-matrices-and-high-dimensional-probability**: Work with concentration of measure, empirical processes, nonasymptotic random-matrix bounds, spectral limits, and universality, and read current high-dimensional probability literature.

## Changes to shared IDs

### number-sense-and-arithmetic

- estimatedChapters: 9 → 10
- description: Reason with whole numbers, integers, fractions, decimals, ratio, percent, place value, and estimation, and justify why each operation applies. → Reason and calculate with integers, fractions, decimals, ratios, percentages, units, and estimates.

### elementary-algebra-and-functions

- estimatedChapters: 12 → 11
- description: Manipulate symbolic expressions, solve equations, inequalities, and systems, and model with linear, quadratic, polynomial, rational, exponential, and logarithmic functions and their graphs. → Use algebraic laws, expressions, equations, inequalities, graphs, and elementary functions to represent and solve constraints.

### geometry-and-measurement

- tier: core → recommended
- estimatedChapters: 10 → 9
- description: Reason about congruence, similarity, transformations, circles, right-triangle trigonometry, coordinate geometry, area, volume, units, and short deductive geometric arguments. → Reason about shape, congruence, similarity, coordinates, area, and volume with defensible diagrams.
- prerequisites: elementary-algebra-and-functions → number-sense-and-arithmetic
- recommendedAfter: none → elementary-algebra-and-functions

### mathematical-computing-and-experimentation

- order: 4 → 18
- level: foundational → undergraduate-core
- description: Use a programming environment, symbolic and numeric tools, plotting, floating-point awareness, and reproducible notebooks to explore mathematical objects and test conjectures. → Translate mathematical objects into tested symbolic and numerical computations, plots, simulations, and reproducible data workflows.
- prerequisites: elementary-algebra-and-functions → elementary-algebra-and-functions, computer-science/programming-and-software-development-foundations
- recommendedAfter: geometry-and-measurement → none

### precalculus-and-trigonometry

- order: 5 → 4
- estimatedChapters: 10 → 11
- description: Work fluently with circular trigonometric functions and identities, conic sections, polar and parametric descriptions, plane vectors, sequences, and limit-ready behavior of functions. → Translate exponential, logarithmic, trigonometric, complex-number, and parametric representations for calculus and wave models.
- prerequisites: geometry-and-measurement → elementary-algebra-and-functions
- recommendedAfter: none → geometry-and-measurement

### mathematical-reasoning-and-proof

- order: 6 → 5
- level: undergraduate-core → foundational
- description: Read, evaluate, and write correct proofs using logic, quantifiers, sets, relations, functions, induction, contradiction, contraposition, and elementary cardinality. → Read and construct quantified arguments using sets, functions, relations, induction, contradiction, and counterexamples.
- prerequisites: elementary-algebra-and-functions → number-sense-and-arithmetic
- recommendedAfter: geometry-and-measurement, precalculus-and-trigonometry → elementary-algebra-and-functions

### single-variable-differential-calculus

- description: Use limits, continuity, and derivatives to model rates, approximate locally, and analyze extrema, concavity, and optimization in one variable. → Use limits and derivatives to explain local change, approximation, shape, and constrained single-variable optimization.
- recommendedAfter: none → mathematical-reasoning-and-proof

### linear-algebra

- order: 8 → 9
- estimatedChapters: 11 → 12
- description: Reason with vector spaces, linear maps, matrices, rank, determinants, eigenstructure, inner products, orthogonality, and matrix factorizations across algebraic, geometric, and computational views. → Solve linear systems and reason with vector spaces, linear maps, bases, eigenstructure, orthogonality, least squares, and singular values.
- recommendedAfter: mathematical-reasoning-and-proof, single-variable-differential-calculus → mathematical-reasoning-and-proof

### single-variable-integral-calculus

- order: 9 → 8
- estimatedChapters: 11 → 10
- description: Use Riemann sums, the fundamental theorem, integration techniques, improper integrals, accumulation applications, and infinite series including Taylor expansions. → Connect accumulation and antiderivatives, evaluate integrals, and control infinite series and Taylor approximations.

### discrete-mathematics-and-combinatorics

- description: Count with bijections, inclusion-exclusion, recurrences, and generating functions, and analyze graphs, trees, orders, and discrete structures with proof. → Model finite structures and justify counting, recurrences, graph arguments, invariants, and elementary asymptotic bounds.
- recommendedAfter: linear-algebra → none

### multivariable-and-vector-calculus

- order: 11 → 14
- description: Differentiate and integrate functions of several variables, use gradients and Jacobians, change coordinates, and apply the line, surface, Green, Stokes, and divergence theorems. → Use multivariable derivatives, multiple integrals, coordinate changes, vector fields, and integral theorems.
- prerequisites: single-variable-integral-calculus → single-variable-integral-calculus, linear-algebra
- recommendedAfter: linear-algebra → none

### probability

- order: 12 → 16
- estimatedChapters: 11 → 12
- description: Model uncertainty with sample spaces, conditioning, independence, discrete and continuous random variables, joint behavior, expectation, and limit laws. → Model discrete and continuous uncertainty using conditioning, random variables, expectations, joint laws, inequalities, and limit approximations.

### differential-equations

- order: 13 → 15
- estimatedChapters: 11 → 10
- description: Formulate, solve, and qualitatively analyze ordinary differential equations and linear systems using analytic methods, transforms, eigenstructure, phase planes, and numerical schemes. → Formulate and solve ordinary differential equations and linear systems, and interpret existence, forcing, and local stability.
- recommendedAfter: multivariable-and-vector-calculus, mathematical-computing-and-experimentation → none

### statistical-inference-and-data-analysis

- order: 14 → 17
- estimatedChapters: 11 → 12
- description: Summarize data honestly, reason about sampling distributions, estimate with uncertainty, test hypotheses, fit and criticize regression models, and state the limits of an inference. → Design and critique studies and perform estimation, testing, simple regression, resampling, and uncertainty communication.
- prerequisites: probability → elementary-algebra-and-functions
- recommendedAfter: mathematical-computing-and-experimentation, linear-algebra → data-and-chance

### real-analysis

- order: 16 → 19
- level: undergraduate-advanced → undergraduate-core
- estimatedChapters: 11 → 10
- description: Prove theorems about completeness, sequences, series, limits, continuity, differentiation, Riemann integration, and uniform convergence, and construct counterexamples. → Prove results about completeness, convergence, continuity, differentiation, integration, and sequences of real functions.

### complex-analysis

- order: 18 → 23
- tier: core → recommended
- description: Use holomorphy, the Cauchy-Riemann equations, contour integration, Cauchy theory, power and Laurent series, analytic continuation, residues, and conformal mapping. → Analyze holomorphic functions using contour integrals, Cauchy theory, series, residues, and conformal maps.
- prerequisites: multivariable-and-vector-calculus, mathematical-reasoning-and-proof → single-variable-integral-calculus, mathematical-reasoning-and-proof
- recommendedAfter: real-analysis → real-analysis, multivariable-and-vector-calculus

### differential-geometry-and-manifolds

- order: 20 → 45
- tier: recommended → specialization
- estimatedChapters: 13 → 11
- description: Analyze curves and surfaces with curvature and fundamental forms, then work on smooth manifolds with tangent spaces, vector fields, differential forms, Stokes' theorem, and first Riemannian metrics. → Use charts, tangent and cotangent spaces, tensors, differential forms, and integration to reason intrinsically on smooth manifolds.
- prerequisites: multivariable-and-vector-calculus, linear-algebra, mathematical-reasoning-and-proof → multivariable-and-vector-calculus, real-analysis, metric-and-general-topology
- recommendedAfter: real-analysis, general-topology → euclidean-and-non-euclidean-geometry

### partial-differential-equations

- order: 21 → 34
- tier: core → recommended
- description: Classify and solve first-order, heat, wave, and Laplace equations using characteristics, separation of variables, Fourier methods, Green's functions, and maximum principles. → Formulate and solve classical PDE initial and boundary problems using characteristics, eigenfunction expansions, and Green functions.
- recommendedAfter: real-analysis → fourier-analysis-and-transforms

### numerical-analysis

- order: 22 → 36
- tier: core → recommended
- description: Analyze floating-point error, conditioning, and stability while designing and assessing algorithms for roots, interpolation, quadrature, linear systems, eigenvalues, and initial-value problems. → Choose and validate finite-dimensional numerical methods using conditioning, stability, approximation, and error estimates.
- recommendedAfter: differential-equations, real-analysis → real-analysis

### optimization-and-operations-research

- order: 23 → 37
- estimatedChapters: 11 → 12
- description: Formulate and solve linear, convex, and constrained optimization problems using duality, optimality conditions, descent and Newton methods, network models, and integer formulations. → Formulate finite-dimensional decision problems and use linear programming, duality, convexity, and optimality certificates.
- prerequisites: multivariable-and-vector-calculus, linear-algebra → linear-algebra, single-variable-differential-calculus
- recommendedAfter: numerical-analysis, mathematical-computing-and-experimentation → none

### stochastic-processes

- order: 24 → 41
- description: Model systems evolving randomly in time with Markov chains, Poisson and renewal processes, queues, branching processes, elementary martingales, and Brownian motion. → Analyze finite or countable-state Markov processes, renewal, branching, and queue models with correct time and conditioning conventions.
- recommendedAfter: differential-equations, mathematical-computing-and-experimentation → differential-equations

### information-theory

- order: 25 → 42
- tier: recommended → specialization
- estimatedChapters: 10 → 9
- description: Quantify information with entropy, relative entropy, and mutual information, and derive source-coding, channel-capacity, and error-correcting limits. → Quantify discrete information and derive source coding, channel coding, mutual information, and rate-distortion bounds.
- recommendedAfter: discrete-mathematics-and-combinatorics, linear-algebra → none

### mathematical-logic-and-computability

- order: 26 → 29
- tier: recommended → specialization
- description: Reason about formal languages, deduction, models, soundness, completeness, compactness, computability, recursive functions, decidability, and incompleteness. → Distinguish formal syntax, semantics, provability, and computability through completeness, compactness, and arithmetic limitations.
- recommendedAfter: discrete-mathematics-and-combinatorics, abstract-algebra → theory-of-computation-and-complexity

### theory-of-computation-and-complexity

- order: 27 → 28
- tier: recommended → specialization
- description: Analyze automata, formal languages, Turing machines, decidability, reductions, complexity classes, NP-completeness, and randomized computation. → Analyze formal languages, machine models, undecidability, reductions, and time or space complexity.
- recommendedAfter: mathematical-computing-and-experimentation, mathematical-logic-and-computability → none

### functional-analysis

- order: 32 → 58
- tier: core → recommended
- estimatedChapters: 11 → 10
- description: Analyze normed, Banach, and Hilbert spaces, bounded and compact operators, the Hahn-Banach, open-mapping, closed-graph, uniform-boundedness, Riesz representation, and Lax-Milgram theorems, duality, weak topologies, and spectra. → Prove operator and function-space results using Banach and Hilbert structure, duality, weak convergence, and compactness.
- prerequisites: measure-theory-and-lebesgue-integration, linear-algebra → measure-and-integration, linear-algebra
- recommendedAfter: general-topology → metric-and-general-topology

### measure-theoretic-probability

- order: 33 → 62
- tier: core → recommended
- estimatedChapters: 11 → 10
- description: Ground probability in measure theory: independence, modes of convergence, laws of large numbers, characteristic functions, central limit theorems, conditional expectation, martingales, and concentration inequalities. → Prove probabilistic limit and conditioning results using measure spaces, independence, conditional expectation, and martingales.
- prerequisites: measure-theory-and-lebesgue-integration, probability → measure-and-integration, probability

### algebraic-topology

- order: 34 → 46
- level: graduate → undergraduate-advanced
- tier: core → specialization
- estimatedChapters: 11 → 10
- description: Compute and interpret fundamental groups, covering spaces, CW structures, simplicial and singular homology, exact sequences, cohomology, and duality. → Compute fundamental groups and homology and use functorial invariants to distinguish spaces.
- prerequisites: general-topology, abstract-algebra → metric-and-general-topology, group-theory

### commutative-algebra

- order: 37 → 52
- tier: recommended → specialization
- estimatedChapters: 10 → 9
- description: Work with Noetherian rings, modules, localization, primary decomposition, integral extensions, Hilbert basis and Nullstellensatz results, and dimension theory. → Analyze commutative rings and modules using localization, finiteness, integral dependence, dimension, and local structure.
- prerequisites: advanced-algebra-and-galois-theory → modules-and-linear-structures
- recommendedAfter: number-theory → fields-and-galois-theory

### representation-theory-and-lie-theory

- order: 38 → 57
- estimatedChapters: 11 → 10
- description: Decompose representations of finite groups with characters and orthogonality, induce and restrict, and extend to Lie algebras, root systems, weights, and their classification. → Analyze linear representations through characters and matrix Lie groups, Lie algebras, and elementary highest-weight examples.
- prerequisites: advanced-algebra-and-galois-theory → group-theory, advanced-linear-algebra
- recommendedAfter: general-topology, differential-geometry-and-manifolds → differential-geometry-and-manifolds

### algebraic-number-theory

- order: 39 → 53
- description: Study number fields, rings of integers, valuations, ideal factorization, class groups, units, local fields, ramification, and first class-field phenomena. → Use number fields, integer rings, ideals, ramification, valuations, and local completions to solve arithmetic structure problems.
- prerequisites: advanced-algebra-and-galois-theory, number-theory → fields-and-galois-theory, elementary-number-theory

### analytic-number-theory

- order: 40 → 54
- estimatedChapters: 10 → 9
- description: Use arithmetic functions, summation methods, Dirichlet series, zeta and L-functions, sieve ideas, and exponential sums to analyze the distribution of primes and other arithmetic sequences. → Use asymptotic sums, Dirichlet series, complex methods, and elementary sieve estimates to study primes and arithmetic functions.
- prerequisites: complex-analysis, number-theory → elementary-number-theory, complex-analysis, real-analysis
- recommendedAfter: real-analysis, harmonic-and-fourier-analysis → none

### axiomatic-set-theory

- order: 42 → 30
- level: graduate → undergraduate-advanced
- description: Work in ZFC with ordinals, cardinals, transfinite recursion, choice principles, combinatorial set theory, constructibility, forcing, and independence arguments. → Reason with axiomatic sets, ordinals, cardinals, choice, and transfinite constructions.
- prerequisites: mathematical-logic-and-computability → mathematical-reasoning-and-proof
- recommendedAfter: general-topology, abstract-algebra → mathematical-logic-and-computability

### dynamical-systems-and-ergodic-theory

- order: 46 → 64
- estimatedChapters: 11 → 9
- description: Analyze flows and maps through invariant sets, stability, bifurcation, hyperbolicity, symbolic dynamics, invariant measures, ergodic theorems, mixing, and entropy. → Connect deterministic dynamics to invariant measures, recurrence, ergodic averages, mixing, and entropy.
- prerequisites: measure-theory-and-lebesgue-integration, differential-equations → nonlinear-dynamics, measure-theoretic-probability
- recommendedAfter: mathematical-computing-and-experimentation, functional-analysis → functional-analysis

### numerical-methods-for-differential-equations

- order: 49 → 67
- description: Design and analyze finite difference, finite element, and spectral discretizations with consistency, stability, convergence, conservation, and modern solver strategies. → Design and verify time-stepping and spatial discretizations with consistency, stability, convergence, and conservation checks.
- recommendedAfter: functional-analysis, optimization-and-operations-research → weak-solutions-and-sobolev-spaces

### mathematics-of-machine-learning-and-data-science

- order: 50 → 74
- estimatedChapters: 11 → 10
- description: Establish learning guarantees with concentration, complexity measures, and empirical risk minimization, and analyze kernels, high-dimensional estimation, and optimization for modern learning models. → Derive statistical learning objectives, generalization bounds, regularization, kernels, low-rank methods, and optimization tradeoffs.
- prerequisites: statistical-inference-and-data-analysis, optimization-and-operations-research, measure-theoretic-probability → convex-and-nonlinear-optimization, mathematical-statistics
- recommendedAfter: numerical-analysis, functional-analysis, mathematical-statistics-and-asymptotic-inference → computer-science/machine-learning-and-data-science

## Validation

```json
{
  "baseline": [],
  "candidate": [],
  "roadmap": [],
  "global": {
    "baseline": [],
    "candidate": []
  }
}
```
