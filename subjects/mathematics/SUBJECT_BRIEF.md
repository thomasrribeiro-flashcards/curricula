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
  estimated at 6–14 chapters. The 53 proposed decks range from 8 to 13.
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

Consulted 2026-08-16. Curricular sources shaped the domain map, deck boundaries,
and maturity transitions; they are not used to verify individual mathematical
claims, which must be verified against authoritative texts, direct derivation,
or primary literature at authoring time. Except where a license is stated, the
sources below were consulted under their publishers' website terms and no source
text, table, or figure is reproduced.

- Consensus or professional frameworks:
  - **Mathematics Subject Classification 2020** (MSC2020), maintained jointly by
    zbMATH Open and Mathematical Reviews — <https://msc2020.org/> and
    <https://zbmath.org/classification/>. Authority: the two mathematical
    reviewing services of record. License: CC BY-NC-SA. Used as the principal
    literature-domain inventory, including computation, higher categories,
    low-dimensional topology, rough analysis, topological data analysis, and
    computer support for mathematical research.
  - **2023 Report of the ICM Structure Committee for ICM 2026** —
    <https://www.mathunion.org/fileadmin/IMU/Publications/CircularLetters/2023/IMU%20AO%20CL%208_2023_StructureCommitteeReport2023.pdf>
    and the IMU's <https://www.mathunion.org/icm/icm-2026>. Authority: the
    International Mathematical Union committee charged with defining the
    Congress's scientific sections. Terms: IMU copyright/site terms; consulted,
    not reproduced. Its 20-section structure confirms separate contemporary
    homes for logic, algebra, number theory, geometry, topology, analysis,
    dynamics, PDE, probability, combinatorics, computing, numerics, control,
    statistics/machine learning, modeling, education, and history. It supports
    both the included domains and the explicit deferred rows; section headings
    were not converted mechanically into decks.
  - **MAA CUPM 2015 Curriculum Guide to Majors in the Mathematical Sciences** —
    <https://maa.org/wp-content/uploads/2024/06/2015-CUPM-Curriculum-Guide.pdf>
    and <https://maa.org/resource/cupm-guide/>. Authority: the Mathematical
    Association of America's undergraduate curriculum committee; still the
    guide linked by MAA at the access date. Terms: MAA copyright/site terms;
    consulted, not reproduced. Used for proof, communication, technology,
    modeling, depth, project work, and course-area boundaries, including the
    expectation that at least one area be studied through a sustained sequence.
  - **QAA Subject Benchmark Statement: Mathematics, Statistics and Operational
    Research (2023)** — <https://www.qaa.ac.uk/the-quality-code/subject-benchmark-statements/subject-benchmark-statement-mathematics-statistics-and-operational-research>.
    Authority: UK sector-owned degree benchmark. Terms: QAA terms and conditions;
    consulted, not reproduced. Used as a non-US cross-check for proof,
    statistics, operational research, modeling, computation, communication, and
    the overlap among these areas.
  - **Common Core State Standards for Mathematics and Standards for Mathematical
    Practice** — <https://www.thecorestandards.org/Math/> and
    <https://www.thecorestandards.org/Math/Practice/>. Authority: CCSSO/NGA
    school standards. Terms: publisher website terms; consulted, not reproduced.
    Used only for the foundational sequence and for the recurring practices of
    reasoning, representation, modeling, tool choice, and checking.
  - **2021 CBMS Survey of Undergraduate Programs in the Mathematical Sciences** —
    <https://www.ams.org/cbms/cbms2021-Report.pdf>. Authority: the AMS/CBMS
    national program survey. Terms: AMS copyright/site terms; consulted, not
    reproduced. Used to compare the proposed undergraduate layer with courses
    departments actually offered in 2020–22, rather than treating an idealized
    taxonomy as a curriculum.
  - **SIAM Education Subcommittee Report on Undergraduate Degree Programs in
    Applied Mathematics** — <https://doi.org/10.1137/15M1008002>. Authority:
    SIAM Education Committee report, free to read under SIAM publication terms.
    Used to confirm the independent roles of modeling, computation, numerical
    analysis, optimization, and application-facing project work.
  - **Current graduate entry and qualifying materials:** Harvard's
    <https://www.math.harvard.edu/graduate/study-the-qualifying-exam/the-qualifying-exam-syllabus/>
    and Berkeley's
    <https://math.berkeley.edu/graduate/phd-program/preliminary-exam>.
    Authority: primary departmental statements; institutional website terms;
    consulted, not reproduced. Harvard's six-area breadth syllabus and
    Berkeley's honors-undergraduate diagnostic were used together so that one
    institution's local exam structure would not be mistaken for a universal
    graduate core. They support distinct advanced algebra, analysis, geometry,
    topology, and complex-analysis capabilities and expose the need to audit
    each maturity transition explicitly.
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
6. **Time budget and pace.** Fifty-three course-sized decks is a multi-year
   commitment. If the horizon is shorter, the coverage matrix should be
   narrowed deliberately rather than each deck thinned.
7. **Accessibility and device constraints.** Confirm any screen reader, screen
   size, or color-vision requirement that should tighten the figure defaults.
