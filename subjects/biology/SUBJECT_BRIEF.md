# Biology subject brief

This file records decisions specific to this learner and collection. Reusable
biology authoring guidance remains in the supplied domain guide. The explained
deck graph belongs in `ROADMAP.md`; its executable copy belongs in
`subject.toml`.

## Learner and destination

- Intended learner: a cold-start adult or independent learner; no previous
  biology course is confirmed.
- Current mathematical/tool mastery: none confirmed. Arithmetic, algebra,
  logarithms, probability, statistics, laboratory reasoning, field practice,
  and programming must be taught before a dependent deck assumes them.
- Current domain mastery: none unless explicitly confirmed here.
- Requested destination and use horizon: `whole-field`—a navigable, layered map
  of the major domains of biology from first contact through representative
  graduate and research-facing extensions. This is a route, not a ceiling or a
  claim that every learner must complete every branch.
- Graduate or research focus branches: none requested. The roadmap therefore
  shows balanced representative extensions rather than privileging one
  laboratory, organism, health, or environmental branch.
- Deck granularity: `course`; each coherent deck is estimated at 6–14 chapters.
- Durable capabilities: explain biology's crosscutting principles across
  scales; reason from evidence and uncertainty; interpret quantitative,
  graphical, molecular, cellular, organismal, phylogenetic, and ecological
  representations; design and critique investigations; and enter a chosen
  advanced branch without a hidden chemistry, mathematics, statistics,
  laboratory, field, or programming prerequisite.
- Deliberate exclusions: card authoring and deck creation in this run; clinical
  diagnosis or treatment training; professional licensure; and exhaustive
  coverage of every taxon, technique, or active research microfield.

Anything not explicitly confirmed above is treated as unseen during cold-start
review.

## Conventions and boundaries

- Language and terminology: English is the working proposal, with current
  international biological nomenclature, SI units, scientific names where they
  disambiguate organisms, and common names where they improve accessibility.
  The learner should confirm language and terminology preferences before deck
  construction.
- Organismal balance: use comparative examples across microbes, plants, fungi,
  animals, and other eukaryotes; do not make humans or a single model organism
  the unstated default.
- Scale and representation: identify organism, compartment, spatial scale,
  timescale, axes, units, sampling unit, and uncertainty whenever they affect
  interpretation. Diagrams must not imply false relative scale.
- Simplifications that must be labeled: equilibrium and steady-state models;
  one-gene/one-trait and strictly Mendelian models; linear “central dogma”
  summaries; tree-like histories where horizontal transfer or reticulation
  matters; single species concepts; optimality and adaptation stories;
  homeostatic set-point models; model-organism generalizations; and binary or
  population-average descriptions of variable human traits.
- Claims requiring current verification: taxonomy and nomenclature; genome and
  biodiversity databases; conservation status; climate and epidemiological
  measurements; health and disease claims; gene-editing, sequencing, imaging,
  single-cell, spatial, AI, and computational methods; biosafety and biosecurity
  guidance; and ethical or legal requirements.
- Accessibility and device constraints: personal needs and laboratory/field
  access are not confirmed. Until clarified, future decks should use phone-width
  legibility, alt text, non-color cues, keyboard-readable notation, captions or
  transcripts, and equivalent nonvisual descriptions. Hands-on work must offer
  accessible alternatives without claiming that a simulation is identical to
  physical practice.
- Programming convention needing confirmation: the curriculum is language
  neutral. Choose an R-first, Python-first, or paired pathway with the learner
  before building `computational-biology-foundations`.
- Jurisdiction needing confirmation: no legal or regulatory jurisdiction is
  assumed. Decks may teach general ethical and safety principles, but must
  verify local rules when built.

## Evidence policy

Curriculum frameworks determine capabilities and coverage; they do not verify
individual biological claims. Consequential or unstable claims require current
primary literature, consensus bodies, or public scientific agencies at deck
build time. Source prose and figures are not copied merely because they are
viewable. Original explanations and figures remain the default, with explicit
attribution and license review for any external material.

### Curriculum and field-structure source register

Accessed 2026-07-18. “Reference only” means the source informed the map through
paraphrase; no permission to redistribute its prose or figures is assumed.

| Source | Authority and role | License or terms used here |
|---|---|---|
| [AAAS/NSF, *Vision and Change in Undergraduate Biology Education*](https://aaas-iuse.org/) | Consensus framework for five crosscutting concepts and six scientific competencies. | Publicly accessible AAAS material; reference only under site terms. |
| [Brownell et al., BioCore Guide](https://doi.org/10.1187/cbe.13-12-0233) | Nationally validated elaboration of the five concepts across biological scales and subdisciplines. | CC BY-NC-SA 3.0; used for curricular alignment, not copied text. |
| [Clemmons et al., BioSkills Guide](https://doi.org/10.1187/cbe.19-11-0259) | Nationally validated, measurable undergraduate outcomes for process of science, quantitative skills, modeling, interdisciplinarity, communication/collaboration, and science–society reasoning. | CC BY-NC-SA 3.0; used for curricular alignment, not copied text. |
| [QAA, *Subject Benchmark Statement: Biosciences* (2023)](https://www.qaa.ac.uk/docs/qaa/sbs/sbs-biosciences-23.pdf) | Broad external benchmark spanning molecular-to-ecosystem knowledge, practical work, computation, statistics, literature, ethics, sustainability, accessibility, and independent inquiry. | QAA copyright and website terms; reference only. |
| [NSF BIO, 2026 organizational update](https://www.nsf.gov/bio/updates/supporting-exciting-biological-sciences-ideas-impacts-ai) | Current cross-check for the field's research structure: Foundations of Life, Living Systems, and Bioinnovation & Infrastructure, including interdisciplinary AI and biotechnology interfaces. | U.S. government web source; reference only and verify item-specific rights before reuse. |
| [NSF BIO programs](https://www.nsf.gov/bio/programs) | More granular inventory of molecular/cellular, organismal, evolutionary, ecological, biodiversity, systems, and infrastructure programs. The page itself warns that reorganization updates are in progress, so it is not treated as the current hierarchy. | U.S. government web source; reference only. |
| [Ecological Society of America, 4DEE Framework](https://esa.org/4DEE/framework/) | Society-endorsed undergraduate ecology map integrating organisms through biosphere, ecological practice, human–environment interactions, and crosscutting concepts. | ESA site copyright; reference only. |
| [American Society for Microbiology, 2024 Curriculum Guidelines](https://asm.org/guideline/asm-curriculum-guidelines-for-undergraduate-microb) | Current professional framework for microbiological concepts, scientific thinking, laboratory skills, and societal context. | ASM copyright; reference only. |
| [American Physiological Society, physiology core concepts](https://doi.org/10.1152/advan.00188.2019) | Community framework emphasizing transferable physiological reasoning such as homeostasis, gradients, mass balance, membranes, and cell communication. | APS copyright; free-to-read material used as reference only. |
| [OpenStax, *Biology 2e*](https://openstax.org/details/books/biology-2e) | Open educational scope check for a two-semester majors sequence and a possible future explanatory source, not the roadmap's organizing template. | CC BY-NC-SA 4.0; attribution and ShareAlike required for any adapted content. |

## Authentic practice outside SRS

Cards can maintain concepts, decisions, representations, and checks, but
competence requires additional practice:

- sustained laboratory work with real instruments, samples, calibration,
  contamination control, notebooks, waste handling, risk assessment, and
  troubleshooting;
- field observation, natural history, sampling design, species identification,
  geospatial context, permitting, and low-impact conduct;
- extended analysis of authentic messy datasets using spreadsheets and then
  reproducible code, with versioning and data documentation;
- multi-step modeling, parameter estimation, simulation, sensitivity analysis,
  and comparison of predictions with observations;
- reading primary literature, tracing claims to evidence, writing reports and
  reviews, peer critique, oral and visual communication, and collaboration;
- open-ended investigations or course-based research that include failed
  approaches, iteration, uncertainty, ethics, and resource constraints.

The learner should confirm available equipment, field access, computing setup,
accessibility needs, preferred programming path, and desired first advanced
branch before any deck is built.
