# Mathematics subject brief

This file records decisions specific to this learner and collection. Reusable
domain-wide authoring guidance belongs in `templates/guides/mathematics.md`
when that maintained guide exists, or in this subject's `DOMAIN_GUIDE.md` for a
new domain. The explained deck sequence belongs in `ROADMAP.md`; its executable
curriculum belongs in `subject.toml`.

The repository's maintained `templates/guides/mathematics.md` is the reusable
domain guide for this subject and is deliberately **not** copied here.

## Learner and destination

- Intended learner: not specified. The route is therefore designed for a
  motivated adult self-learner with no confirmed prior mathematics, working
  independently with spaced repetition plus written practice. **Needs
  confirmation** (see "Decisions awaiting confirmation").
- Current mathematical/tool mastery: none confirmed. No programming language,
  computer algebra system, typesetting system, or proof assistant is assumed to
  be installed or known.
- Current domain mastery: none unless explicitly confirmed here.
- Requested destination and use horizon: **whole-field**. The horizon is doing
  mathematics across the field — computing reliably, reasoning from definitions,
  writing and evaluating proofs, modeling real situations, and reading current
  literature in at least one representative branch — rather than passing a
  specific exam or serving one applied application.
- Graduate or research focus branches: none requested. Because no branch was
  named, the roadmap carries a balanced set of five representative research
  routes — arithmetic geometry, geometric topology, topological and geometric
  data analysis, formalization, and high-dimensional probability — chosen to
  span algebraic, geometric, applied, foundational, and probabilistic styles of
  current work. This is a coverage decision, not a claim about the learner's
  interests. **Needs confirmation.**
- Deck granularity: course. Each deck is one coherent course-sized capability,
  estimated at 6–14 chapters. The 52 proposed decks range from 8 to 13.
- Durable capabilities: fluent symbolic and numerical computation; the function
  concept across representations; proof construction and evaluation; the
  analysis, algebra, geometry, and probability cores that every advanced route
  consumes; computational experimentation with honest error awareness;
  disciplined modeling with stated conditions of validity; and literature-facing
  competence in a chosen branch.
- Deliberate exclusions: no deck is created for control theory, several complex
  variables, K-theory, order and universal algebra, special functions,
  non-Euclidean and projective geometry, mathematical physics, mathematical
  biology, game theory and mathematical finance, history and philosophy of
  mathematics, or mathematics education. These are recorded as `deferred` in the
  coverage matrix with the graph position each would attach to. Physical-science
  and earth-science application areas classified under mathematics are
  `out-of-scope` because the collection's physics subject owns that content.

Because the destination is whole-field rather than a named endpoint, the route
starts at `number-sense-and-arithmetic`. Destination controls the current route,
not who may learn the subject and not the permanent ceiling of the roadmap.

## Conventions and boundaries

- Preferred notation, terminology, language, or jurisdiction: English-language,
  internationally standard mathematical notation. Where conventions genuinely
  differ, decks state the convention in use and name the alternative rather than
  silently picking one — for example whether the natural numbers include zero,
  row versus column vector conventions, the sign and normalization of the
  Fourier transform, whether "ring" presumes unity, and open versus closed
  interval conventions in measure statements. Decimal point, SI units, and
  ISO 8601 dates. **The default is standard notation with alternatives named;
  a different house convention needs confirmation.**
- Simplifications that must be labeled: any statement proved only under stronger
  hypotheses than the theorem's usual form; any result quoted without proof
  (regularity estimates in the geometry and PDE decks, deep classification
  results in the research decks); heuristic or physical arguments used before a
  rigorous version exists; finite-dimensional intuition transferred to infinite
  dimensions; and every place where a foundational subtlety (choice, measurability,
  convergence mode) is deferred rather than resolved.
- Claims requiring current verification: the status of named open problems and
  recent theorems in the research-specialization decks; the contents and API of
  proof-assistant libraries, which change continuously; sizes and contents of
  computational databases; and anything described as "recently proved" or
  "state of the art", which must carry an access date.
- Accessibility or device constraints: none stated. Figures are authored to the
  general standard — TikZ source compiled to SVG, `viewBox` present, meaningful
  `<title>` and `<desc>`, phone-width legibility, high contrast, and a redundant
  cue beyond color. Mathematical notation is written so a screen reader can
  render it from the source. **Confirm whether a specific screen reader, phone
  screen size, or color-vision constraint should tighten these defaults.**

Do not infer domain knowledge from the target level. Anything not explicitly
confirmed above is treated as unseen during cold-start review.

## Evidence authorities

Consulted 2026-08-06. Curricular sources shaped the domain map and deck
boundaries; they are not used to verify individual mathematical claims, which
are verified against standard texts and primary literature at authoring time.

- Consensus or professional frameworks:
  - **Mathematics Subject Classification 2020** (MSC2020), maintained jointly by
    zbMATH Open and Mathematical Reviews — <https://msc2020.org/>,
    <https://zbmath.org/classification/>. Authority: the two abstracting and
    reviewing services of record. License: CC BY-NC-SA 4.0, so the scheme
    informs the domain map but its text is not reproduced. Used as the primary
    check that the coverage matrix names material domains rather than course
    titles, including the newer machine-assisted and homotopical headings.
  - **International Mathematical Union / ICM section structure** —
    <https://www.mathunion.org/>, <https://icm2026.org/>. Authority: the
    field's international body. Used to confirm which areas the research
    community currently treats as top-level sections, which shaped the graduate
    and research layers.
  - **MAA Committee on the Undergraduate Program in Mathematics (CUPM)
    Curriculum Guide** — <https://maa.org/> (CUPM guide and course-area study
    group reports). Authority: the US professional society for collegiate
    mathematics. Used for the undergraduate core, for the cognitive
    recommendations (proof, communication, technology), and for Content
    Recommendation 5 — experience mathematics from another discipline's
    perspective — which motivates the single external `recommended_after` edge.
  - **QAA Subject Benchmark Statement, Mathematics, Statistics and Operational
    Research** — <https://www.qaa.ac.uk/quality-code/subject-benchmark-statements>.
    Authority: the UK degree-standards body. Used as a non-US cross-check that
    the undergraduate core is not a national artifact.
  - **Common Core State Standards for Mathematics** —
    <https://www.thecorestandards.org/Math/>. Authority: widely adopted US
    school standards. Used only to sequence the foundational layer and its
    practice standards.
  - **CBMS survey of undergraduate mathematical sciences programs** —
    <https://www.ams.org/cbms-survey>. Authority: AMS/CBMS statistical survey.
    Used to check which courses are actually offered and required, as a guard
    against designing an idealized curriculum.
  - **SIAM guidance on computational science and data science education** —
    <https://www.siam.org/>. Authority: the applied and computational
    mathematics society. Used to justify treating computing, numerical analysis,
    optimization, and the mathematics of learning as first-class decks.
  - **Published PhD qualifying-exam syllabi from research mathematics
    departments.** Authority: primary statements of what graduate programs
    require. Used to fix the graduate core as measure theory, functional
    analysis, complex analysis, algebra, topology, and probability, and to size
    those decks.
- Preferred primary sources or public agencies: peer-reviewed research
  literature and preprint servers for research-layer claims (arXiv,
  <https://arxiv.org/>, primarily as a discovery surface — the published version
  is cited when one exists); NIST Digital Library of Mathematical Functions,
  <https://dlmf.nist.gov/>, for special-function identities and conventions;
  the L-functions and Modular Forms Database, <https://www.lmfdb.org/>, for
  arithmetic-geometry data; and IEEE 754 for floating-point behavior.
- Open educational sources and license constraints: openly licensed texts and
  lecture notes may be consulted for pedagogical sequencing, and a source is
  used only when its license permits the intended use. Freely viewable is not
  the same as reusable, and no source is ingested or reproduced merely because
  it is publicly readable. Each deck records the URL, authority, license or
  terms, and access date of every source it relies on in its own README, and
  distinguishes curricular sources from claim-verifying sources.

## Authentic practice outside SRS

Record projects, extended problems, laboratories, writing, conversation, field
work, or other practice needed for competence that cards cannot replace.

- **Untimed written problem sets** alongside every deck from
  `mathematical-reasoning-and-proof` onward. Cards secure definitions,
  mechanisms, and short discriminations; sustained multi-step computation and
  full proof construction cannot be compressed into one grading decision.
- **Proof writing with external critique.** Producing a complete argument and
  having a competent reader challenge it is the core practice of
  `mathematical-reasoning-and-proof`, `real-analysis`, `abstract-algebra`, and
  `mathematical-research-practice`.
- **Programming and numerical experiments** with real, runnable code and
  reproducible artifacts, required by `mathematical-computing-and-experimentation`,
  `numerical-analysis`, `theory-of-computation-and-complexity`,
  `dynamical-systems-and-ergodic-theory`,
  `numerical-methods-for-differential-equations`,
  `topological-and-geometric-data-analysis`, and
  `formalization-and-proof-assistants`.
- **Open-ended modeling and data projects** for
  `mathematical-modeling-and-asymptotic-methods`,
  `statistical-inference-and-data-analysis`,
  `mathematics-of-machine-learning-and-data-science`, and
  `topological-and-geometric-data-analysis`, including defending modeling
  choices and reporting what failed.
- **Reading papers end to end, seminar presentation, and question formulation**
  for `mathematical-research-practice` and all five research-specialization
  decks. Cards can hold definitions and landmark results; they cannot hold the
  practice of getting stuck productively.
- **Formalization practice** in an installed proof assistant with its library,
  since the feedback loop for `formalization-and-proof-assistants` is the
  assistant itself.
- **Explaining mathematics aloud and being questioned**, which exposes gaps that
  recognition-level review conceals.

## Decisions awaiting confirmation

These are genuinely personal choices. They have been given defensible defaults
above so the curriculum is executable, but they should be confirmed rather than
treated as settled.

1. **Starting point.** The route currently begins at
   `number-sense-and-arithmetic` because no prior mastery was confirmed. If the
   learner already has school algebra, calculus, or a degree, confirm the true
   entry deck — ideally after a placement check — so mastered material is not
   rehearsed. Confirmed knowledge should be recorded in "Learner and
   destination" above; unconfirmed knowledge stays unseen.
2. **Pure versus applied emphasis.** The graph is balanced. If the learner
   leans pure or applied, tiers should shift — for example promoting
   `optimization-and-operations-research` and `stochastic-processes`, or
   `mathematical-logic-and-set-theory` and
   `category-theory-and-homological-algebra`, from `recommended` to `core`.
3. **Which research branches matter.** Five representative branches are
   proposed. A learner with a real target may want one of them replaced by a
   currently deferred domain (control theory, mathematical finance, several
   complex variables, mathematical physics).
4. **Available tooling.** `mathematical-computing-and-experimentation` needs a
   chosen programming environment (Python with a scientific stack, a computer
   algebra system, or both), and `formalization-and-proof-assistants` needs a
   specific assistant and library. Naming these changes what those decks can
   assume and test.
5. **Notation conventions.** If the learner has a house style or a target
   textbook tradition, fixing it now avoids per-deck drift.
6. **Time budget and pace.** Fifty-two course-sized decks is a multi-year
   commitment. If the horizon is shorter, the coverage matrix should be
   narrowed deliberately rather than each deck thinned.
7. **Accessibility and device constraints.** Confirm any screen reader, screen
   size, or color-vision requirement that should tighten the figure defaults.
