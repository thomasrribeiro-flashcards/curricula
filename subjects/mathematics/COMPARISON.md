# Mathematics DAG comparison: current curriculum vs GPT-6 Astra

Review date: 2026-09-05. Candidate generation: UI job **35**, `gpt-6-astra`, **high** reasoning. This compares curriculum plans, not generated flashcards or measured learning outcomes. The current curriculum has not been replaced.

## Recommendation

**Prefer Astra's proposed course boundaries and entry routes as the next design direction, but do not adopt the whole draft unchanged.** It makes several overloaded courses more coherent and documents the small bridges that an entry-level learner actually needs. Keep the current curriculum as the live version until the proposed identity migrations and readiness claims have been reviewed.

This is not evidence that Astra is universally better than Sol. The current baseline's provenance records an **Opus 5 creation followed by a GPT-5.6 Sol High audit**, not a clean Sol-only generation. Astra received a fresh-create task, the newer authoring standards, and the current cross-subject catalog. There is one candidate, no blind scoring, and no learner-outcome test. These are comparisons of the actual artifacts under different conditions.

## The important pedagogical changes

| Area | Current plan | Astra proposal | Assessment |
|---|---|---|---|
| Linear algebra entry | Algebra is hard; proof and calculus are recommended | Algebra remains hard; explicit quantifier, closure, short-proof and complex-scalar bridges | Better documentation, not a newly relaxed hard prerequisite |
| First practical statistics | Probability, and therefore integral calculus, is hard | Algebra is hard; chance and sampling models are taught locally | Better access for practical data analysis; theoretical statistics remains separate |
| Topology | Real analysis is hard | Proof is hard; real analysis is recommended; finite spaces and local real-line facts establish entry | A defensible lower entry barrier if later chapter authoring actually supplies those bridges |
| Complex analysis | Multivariable calculus and proof are hard | Integral calculus and proof are hard; local planar derivatives and contour vocabulary are taught | Avoids a whole-course gate, but the bridge and triangle-based Cauchy treatment need careful authoring |
| Algebra | Groups, rings and initial fields share an abstract-algebra course; advanced algebra bundles further topics | Groups, rings, fields/Galois, modules, advanced linear algebra and homological algebra are distinct courses | Clearer retrieval and course boundaries; requires deliberate ID migration |
| Fourier/PDE/dynamics | Fourier and harmonic analysis share a graduate course; dynamics and ergodic theory share a graduate course | Earlier transform and nonlinear-dynamics courses feed later rigorous analysis | Better staging between computational intuition and advanced theory |
| Algebraic geometry | Varieties, sheaves and initial schemes share one course | Varieties precede schemes/sheaves, which precede a bounded research route | Better progression through genuinely different representations |
| Applied mathematics | A smaller set of broad routes | Separate regression, causal inference, Bayesian computation, time series, control, inverse problems, finance and mathematical biology | Broader choice, not a requirement to study every course |
| Computing | Mathematical computing begins from algebra | Reuses the existing 14-chapter CS programming-foundations course | Avoids duplicate programming instruction, but raises the entry cost for learners who only need plotting or a supplied notebook |

The algebra-only linear-algebra entry is consistent with MIT's distinction between a formal calculus prerequisite and calculus knowledge actually needed for the course. [MIT 18.06SC syllabus](https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/pages/syllabus/). Cambridge's advanced algebraic-geometry preparation also supports distinguishing elementary ring/topology readiness and classical varieties from more advanced scheme work. [Cambridge preparation](https://www.maths.cam.ac.uk/postgrad/part-iii/prospective/preparation/resources/algebraic-geometry).

## What this means for your chapter-4 difficulty jump

The proposed elementary-algebra course explicitly assigns a chapter to **commutativity, associativity and distributivity**. Its linear-algebra plan requires explanations of quantifiers, closure and short direct arguments **before** vector-space axioms. The subject brief also requires an explanation–retrieval–use sequence for each local bridge and explicitly rejects bundling new axioms into one card.

Those are planning requirements, not proof that the existing prerequisite cards already teach them well. This run authors no cards. A chapter plan or a paragraph saying “teach locally” cannot substitute for checking that the resulting flashcards establish each capability before using it. Course splitting likewise does not, on its own, guarantee atomic cards.

## Changes that need human review before adoption

1. **Identity continuity.** Some new IDs are near-renames, not new capabilities: `number-theory` → `elementary-number-theory`, `general-topology` → `metric-and-general-topology`, and `measure-theory-and-lebesgue-integration` → `measure-and-integration`. Prefer retaining a stable existing ID when the scope is substantially the same. Splits such as abstract algebra and algebraic geometry need an explicit mapping, not a bulk rename. Never transfer or regenerate card identities merely because the roadmap changed.
2. **Trade-offs in research coverage.** The current plan explicitly offers arithmetic geometry, low-dimensional topology, topological data analysis, and random matrices/high-dimensional probability. Astra does not preserve those as equivalent standalone routes. It defers arithmetic geometry and narrows its selected research courses. Its broader overall course list is not a strict superset of the old curriculum; TDA and random-matrix coverage deserve explicit decisions.
3. **Bridge realism.** Several reduced prerequisites depend on substantial local teaching: topology without analysis, complex analysis without vector calculus, and control theory's variational methods. The roadmap makes the promises visible, which is good, but chapter-level prerequisite ledgers and pilot reviews must verify them. Fewer hard edges are not automatically better.
4. **No compulsory whole-field marathon.** The larger plan is a menu of branches. Diagnose your retained STEM skills and choose a route. Do not turn the full proposed chapter total into a study requirement or a flashcard quota.
5. **Separate plan from existing content.** Keep the studied decks and chapter/card metadata intact. A regenerated subject DAG does not rewrite the existing linear-algebra deck, establish new prerequisite mastery, or approve a migration.

## Reproducibility and review artifacts

- Baseline registry commit: `95d65dee8bd22ab00ef95832e9826a4217d116c1`.
- Astra was given an empty mathematics scaffold, not the old mathematics roadmap. The external catalog exposed existing canonical mathematics references, so it was not completely blind to all old IDs.
- The generating workflow used local modified authoring standards on top of commit `4577aeefc3bfe498a003ccf8503ab434abfd0db1`. A clean commit alone does not reproduce that context; the staged context hashes identify what was actually supplied.
- The final structural report distinguishes exact-ID additions/removals from semantic renames and splits. Chapter totals are estimates, not authored content or card counts.
- Draft publication and canvas review are separate from applying the DAG. No automatic merge is authorized by this comparison.

## Final structural diff

| Metric | Current baseline | Astra candidate |
|---|---:|---:|
| Course/deck proposals | 55 | 86 |
| Core / recommended / specialization | 26 / 11 / 18 | 18 / 21 / 47 |
| Estimated chapters across every branch | 568 | 818 |
| Direct hard edges | 92 | 150 |
| Direct recommended edges | 79 | 60 |

There are **35 shared IDs, 51 added IDs and 20 removed IDs**. These are identity-level counts, not 51 wholly new subjects or 20 wholly lost capabilities: many are splits and near-renames. Coverage-row counts are not comparable breadth scores because the two authors group domains differently.

Unique hard prerequisite ancestors fall from **7 to 2** for practical statistics, **8 to 2** for topology (matching the renamed course), **8 to 6** for complex analysis, and **8 to 5** for introductory optimization. Linear algebra remains **2 to 2**. These counts describe dependency structure, not time saved or demonstrated learner readiness.

Full field-by-field and edge-declaration changes: [structural diff](structural-diff.md), [machine-readable diff](structural-diff.json). The PR's `subject.toml` diff is the raw executable change.

## Validation and handoff

- The recovered final subject passes the repository's native subject/schema and roadmap-synchronization checks, with no local errors or warnings.
- The complete real registry passes global validation, with no missing references, hard cycles, later-level hard edges or redundant hard edges. All 26 distinct existing external mathematics references still resolve.
- Five global maturity warnings remain in unchanged biology, chemistry, computer-science and physics entries. They are not silently suppressed and are not proof that those courses are defective. The baseline had these same five plus two mathematics warnings.
- The rebuilt catalog retains all six existing materialized decks' chapter data, repository links and materialization flags. `deck-metadata.json` is unchanged. The proposal does not modify card files or review schedules.
- **Runner recovery:** the model emitted a completed turn and passed its final checks, but the local wrapper reported its 60-minute timeout during handoff and removed the isolated workspace. A preserved snapshot plus the exact final edits recorded in log item `item_37` recovered the four publishable curriculum documents. They were then revalidated against the actual registry. This is a recovered local run, not a clean queue-runner success or a second generation. [Context/provenance record](comparison-context.json).

The comparison branch publishes the curriculum, source register, provenance and this review. The generation log and exact staged inputs are retained in the local comparison archive rather than copied into the live authoring guides; the isolated scratch validation scripts are not part of the published proposal.
