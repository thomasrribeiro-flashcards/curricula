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
  estimated at 6–14 chapters. The 55 proposed decks range from 8 to 13.
- Durable capabilities: fluent symbolic and numerical computation; the function
  concept across representations; proof construction and evaluation; the
  analysis, algebra, geometry, and probability cores that every advanced route
  consumes; computational experimentation with honest error awareness;
  disciplined modeling with stated conditions of validity; and literature-facing
  competence in a chosen branch.
- Deliberate exclusions: no deck is created for control and inverse problems,
  several complex variables, operator algebras, geometric measure theory,
  symplectic/contact or convex/discrete geometry, geometric group theory,
  stochastic PDE and rough paths, K-theory, order and universal algebra,
  special functions, cryptography, non-Euclidean and projective geometry,
  mathematical physics, mathematical biology, game theory and mathematical
  finance, history and philosophy of mathematics, or mathematics education.
  These are recorded as `deferred` in the coverage matrix with the graph
  position each would attach to. Physical-science and earth-science application
  areas classified under mathematics are `out-of-scope` because the collection's
  physics subject owns that content.

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

## Evidence authorities and source register

Consulted 2026-08-17. Curricular sources shaped the domain map, deck boundaries,
and maturity transitions; they are not claim-verification sources. Mathematical
claims must still be verified against authoritative texts, direct derivation, or
primary literature when a deck is authored. No source text or figure was copied.

- **Mathematics Subject Classification 2020** — <https://msc2020.org/>.
  Authority: maintained jointly by Mathematical Reviews and zbMATH Open, the
  reviewing services that use the classification. Source role: primary taxonomy
  check for material domains and interdisciplinary boundaries. License:
  CC BY-NC-SA 4.0; used for classification only and not reproduced.
- **IMU 2023 ICM Structure Committee report for ICM 2026** —
  <https://www.mathunion.org/fileadmin/IMU/Publications/CircularLetters/2023/IMU%20AO%20CL%208_2023_StructureCommitteeReport2023.pdf>
  and the current <https://www.mathunion.org/icm/icm-2026> page. Authority: the
  International Mathematical Union committee charged with defining the ICM's
  scientific sections. Source role: current research-field structure, including
  distinct sections for number theory, geometry, topology, Lie theory, analysis,
  dynamics, PDE, probability, numerical analysis, optimization/control, and
  statistics/machine learning. Terms: © IMU; consulted for synthesis only.
- **MAA CUPM 2015 Curriculum Guide to Majors in the Mathematical Sciences** —
  <https://maa.org/resource/cupm-guide/> and
  <https://maa.org/wp-content/uploads/2024/06/2015-CUPM-Curriculum-Guide.pdf>.
  Authority: the Mathematical Association of America's undergraduate-program
  committee. Source role: undergraduate common capabilities—calculus, linear
  algebra, progressive proof, data analysis, computing, modeling, breadth, depth,
  and substantial projects—and course-area boundary cross-checks. Terms: MAA
  copyright; publicly accessible for consultation, with no reuse of prose.
- **QAA Subject Benchmark Statement: Mathematics, Statistics and Operational
  Research (March 2023)** —
  <https://www.qaa.ac.uk/the-quality-code/subject-benchmark-statements/subject-benchmark-statement-mathematics-statistics-and-operational-research>
  and the linked statement PDF. Authority: UK sector-owned degree benchmark.
  Source role: non-US confirmation of calculus, linear algebra,
  probability/statistics, proof, programming, modeling, communication, advanced
  projects, and the undergraduate-to-master's maturity transition. Terms: QAA
  copyright; used as a reference point, not reproduced.
- **Common Core State Standards for Mathematics** —
  <https://www.thecorestandards.org/Math/> and
  <https://www.thecorestandards.org/Math/Practice/>. Authority: the CCSS
  Initiative standards maintained by NGA Center and CCSSO. Source role:
  foundational content sequencing and the practices of reasoning, modeling,
  representation, strategic tool use, and precision. Terms: public standards
  site; consulted for mapping only.
- **2021 CBMS Survey of Undergraduate Programs in the Mathematical Sciences** —
  <https://www.ams.org/cbms/cbms2021-Report.pdf>. Authority: the Conference Board
  of the Mathematical Sciences, hosted by the AMS. Source role: empirical check
  against an idealized course map and current departmental offerings. Terms: AMS
  copyright; aggregate findings consulted only.
- **UC Berkeley Mathematics preliminary examination and syllabus** —
  <https://math.berkeley.edu/graduate/phd-program/preliminary-exam>.
  Authority: a current departmental statement of entry-level PhD expectations.
  Source role: maturity audit for the analysis, complex analysis, linear algebra,
  and abstract algebra bridge into graduate work. Terms: university web content;
  consulted for curricular comparison only.
- **SIAM Education Subcommittee report on undergraduate applied mathematics** —
  <https://epubs.siam.org/doi/10.1137/15M1008002>. Authority: the Society for
  Industrial and Applied Mathematics education committee. Source role: applied
  mathematics, modeling, computation, optimization, and scientific-computing
  balance. Terms: SIAM publication terms; abstract and report metadata used for
  curricular synthesis only.
- **Claim-verification authorities for later deck builds.** Peer-reviewed
  publications and primary sources take priority. arXiv
  (<https://arxiv.org/>) is a discovery surface, with a published version cited
  when available; NIST DLMF (<https://dlmf.nist.gov/>) is preferred for
  special-function identities and conventions; LMFDB
  (<https://www.lmfdb.org/>) for arithmetic data; and IEEE 754 for floating-point
  behavior. Each future deck must record URL, authority, license or terms, access
  date, and whether a source sets scope or verifies a claim. Freely viewable is
  not permission to ingest, modify, or redistribute.

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
   `mathematical-logic-and-computability` and
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
6. **Time budget and pace.** Fifty-five course-sized decks is a multi-year
   commitment. If the horizon is shorter, the coverage matrix should be
   narrowed deliberately rather than each deck thinned.
7. **Accessibility and device constraints.** Confirm any screen reader, screen
   size, or color-vision requirement that should tighten the figure defaults.
