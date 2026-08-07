# Biology subject brief

This file records decisions specific to this learner and collection. Reusable
domain-wide authoring guidance lives in the maintained `templates/guides/biology.md`
and is deliberately not duplicated here. The explained deck sequence belongs in
`ROADMAP.md`; its executable curriculum belongs in `subject.toml`.

## Learner and destination

- **Intended learner**: not confirmed by the learner. Designed for a
  self-directed adult beginning biology at first contact and intending to reach
  representative graduate and research-frontier branches of the field.
  **Needs confirmation** — see *Decisions awaiting confirmation*.
- **Current mathematical/tool mastery**: none confirmed. The curriculum
  therefore assumes no external mathematics deck has been completed, and names
  every genuinely required mathematics capability as an explicit
  `mathematics/...` prerequisite. **Needs confirmation** — prior mathematics
  work would unlock several advanced decks earlier.
- **Current domain mastery**: none. No biological term, mechanism, organism,
  representation, or laboratory convention may be treated as inbound knowledge
  by the first deck. Level labels such as "introductory" or "college biology"
  do not grant permission to assume vocabulary.
- **Requested destination and use horizon**: `whole-field`. The roadmap is a
  navigable map of biology's major domains and contemporary branches across
  learning levels, with deliberate extension points — not a simulation of one
  degree program, and not an attempt to enumerate every active microfield.
  Destination sets the current route; it is not a ceiling and does not classify
  the learner.
- **Graduate or research focus branches**: none specified. Because no focus was
  requested, the roadmap proposes *representative* graduate and
  research-specialization routes chosen to span structurally distinct branches
  of the field rather than to exhaust any one branch. **Needs confirmation.**
- **Deck granularity**: `course`. One deck is one coherent course-scale
  capability, planning-estimated at 6–14 ordered chapters.
- **Durable capabilities** the whole route should produce:
  1. explain living systems mechanistically across scales from molecule to
     biosphere, with evolution as the unifying explanatory frame;
  2. move fluently among biology's authentic representations — molecular
     structures, pathway and compartment diagrams, chromosome states, pedigrees,
     sequence alignments, phylogenies, dose–response and survival curves,
     demographic matrices, food webs, and biogeochemical flux budgets;
  3. reason about experiments: identify the manipulated variable, name the
     missing control, distinguish direct evidence from inference, and state what
     a dataset does *not* justify;
  4. reason quantitatively and probabilistically about biological variation,
     measurement uncertainty, and scale;
  5. read, critique, and situate primary research literature;
  6. enter a chosen branch's current frontier with an honest account of what is
     established, contested, and unresolved.
- **Deliberate exclusions** (full disposition table in `ROADMAP.md`):
  - clinical medicine, diagnosis, treatment selection, and any individualized
    human or veterinary health advice;
  - hands-on wet-lab and field *technique* proficiency, which cards can support
    but cannot confer;
  - psychology, cognitive science, and biological anthropology beyond the
    cellular and systems neurobiology that sits inside biology;
  - the physics and mathematics of living systems already owned by other
    subjects in this collection (see *Cross-subject boundary*).

## Cross-subject boundary

The generated cross-subject catalog supplies `mathematics` and `physics` only.
Four boundary decisions follow; each is argued in `ROADMAP.md`.

- **Chemistry is supplied by no subject in the catalog.** Biology therefore owns
  a chemistry bridge deck scoped strictly to the chemistry that biological
  explanation depends on — bonding and water, pH and buffers, functional groups,
  macromolecular structure, free energy, equilibrium, and reaction rate. It is
  not a general chemistry course and must not drift into one. Inventing a
  `chemistry/...` reference is forbidden because the catalog contains none.
- **General statistical inference is supplied** by
  `mathematics/statistical-inference-and-data-analysis`, but its prerequisite
  closure runs through calculus-based probability. Making it a hard prerequisite
  for undergraduate biology would be a false prerequisite, so biology owns a
  narrowly scoped experimental-design and biological-data-interpretation deck
  and names the mathematics deck as recommended preparation. Decks that
  genuinely need inference or probability theory — population genetics,
  statistical phylogenetics, quantitative ecology, genomics — name
  `mathematics/probability` or `mathematics/statistical-inference-and-data-analysis`
  as hard prerequisites without apology.
- **Physical biology is supplied** by `physics/biological-physics`, and
  mathematical modelling of biological systems by
  `mathematics/dynamical-systems-and-ergodic-theory`. Biology references
  these rather than duplicating them.
- **Scientific computing is supplied** by
  `mathematics/mathematical-computing-and-experimentation`, which is the hard
  prerequisite for every computational biology deck. Biology does not teach
  programming.

## Conventions and boundaries

- **Language and units**: English (US spelling). SI units with the customary
  biological derived units — molar (M), dalton (Da), base pair (bp), millivolt
  (mV), and °C for growth and incubation temperatures.
- **Nomenclature**: species binomials italicized with capitalized genus
  (*Escherichia coli*); genes italic and proteins roman, with the organism's own
  convention stated whenever grading depends on it (human `TP53` → p53; mouse
  `Trp53` → p53). Every card using a gene, enzyme, taxon, tissue, or disease
  term names the organism or system, because biological generalizations have
  exceptions.
- **Simplifications that must be labeled as simplifications**:
  - the "one gene → one protein → one trait" mapping;
  - the central dogma stated without its documented exceptions;
  - textbook cell and molecule diagrams, which routinely misrepresent relative
    scale and molecular crowding;
  - Mendelian ratios, which assume independent assortment, complete dominance,
    equal viability, and large samples;
  - the three-domain tree — the two-domain (eocyte/Asgard) placement of
    eukaryotes within Archaea is now mainstream, and eukaryotic supergroup
    boundaries and rooting are actively revised;
  - "energy is produced" phrasing — energy is transferred and transformed while
    matter cycles;
  - linear textbook pathway diagrams, which omit branch points and regulation.
- **Teleology ban**: no card may state or imply that a trait arose because an
  organism needed it, or that evolution is directed toward an outcome.
  Evolutionary explanation is population-level and across generations.
- **Claims requiring current verification before authoring**: taxonomy, clade
  names, and tree topology; genome and gene-count figures; anything about
  vaccines, pathogens, antimicrobial resistance, or human disease; conservation
  status and biodiversity statistics; climate and global-change figures;
  research-governance policy; and the current capability limits of methods
  (sequencing read length and cost, cryo-EM resolution, structure-prediction
  accuracy, genome-editing precision, spatial-omics throughput).
- **Accessibility and device constraints**: figures must be legible at phone
  width, must never encode meaning by color alone, and must carry meaningful
  `<title>`/`<desc>` and alt text that does not leak the answer. Diagrams must
  not imply false relative scale between molecules, cells, and organisms.

Do not infer domain knowledge from the target level. Anything not explicitly
confirmed above is treated as unseen during cold-start review.

## Evidence authorities

**Curriculum and competency frameworks.** These choose scope and capabilities;
they do not verify individual biological claims.

- AAAS/NSF, *Vision and Change in Undergraduate Biology Education*, and the
  *Chronicling Change* follow-ups —
  https://www.aaas.org/sites/default/files/content_files/VC_report.pdf ;
  https://www.nsf.gov/news/vision-change-undergraduate-biology-initiative
- BioCore Guide (validated core-concept statements) —
  https://pmc.ncbi.nlm.nih.gov/articles/PMC4041499/
- BioSkills Guide (validated core-competency statements) —
  https://pmc.ncbi.nlm.nih.gov/articles/PMC8693931/
- Ecological Society of America 4DEE framework — the only society-endorsed
  ecology curriculum framework — https://esa.org/4dee/framework/
- NRC, *BIO2010* and *A New Biology for the 21st Century* — the standing calls
  for quantitative, computational, and physical-science integration —
  https://www.nationalacademies.org/publications/10497 ;
  https://nap.nationalacademies.org/catalog/12764/a-new-biology-for-the-21st-century
- MIT OpenCourseWare 7.016 *Introductory Biology* —
  https://ocw.mit.edu/courses/7-016-introductory-biology-fall-2018/pages/syllabus/
- MIT Biology graduate first-year requirements — Methods and Logic, graduate
  biochemistry, graduate genetics, and a required quantitative/computational
  subject — https://biologyopenhouse.mit.edu/requirements
- NASEM, *The Age of AI in the Life Sciences: Benefits and Biosecurity
  Considerations* (2025) — https://www.nationalacademies.org/publications/28868

**Nomenclature, reference-data, and assessment authorities.** These verify
individual claims.

- NCBI (GenBank, RefSeq, PubMed, Taxonomy) — https://www.ncbi.nlm.nih.gov/
- UniProt — https://www.uniprot.org/ ; RCSB Protein Data Bank —
  https://www.rcsb.org/
- IUBMB/IUPAC enzyme and biochemical nomenclature —
  https://iubmb.qmul.ac.uk/enzyme/
- HGNC human gene nomenclature — https://www.genenames.org/
- ICTV virus taxonomy, Master Species List release 40 (ratified 2025) —
  https://ictv.global/
- Catalogue of Life eXtended Release, which replaced the GBIF Backbone
  Taxonomy in 2025, plus GBIF occurrence data —
  https://www.catalogueoflife.org/ ; https://www.gbif.org/
- PhyloCode and the RegNum clade-name registry, which coexist with ICZN/ICN
  rather than replacing them — http://phylonames.org/code/ ;
  https://www.phyloregnum.org/
- IUCN Red List — https://www.iucnredlist.org/
- WHO and US CDC for infectious-disease and public-health claims —
  https://www.who.int/ ; https://www.cdc.gov/
- IPCC and IPBES assessment reports, including the IPBES Nexus and
  Transformative Change assessments (2024) — https://www.ipcc.ch/ ;
  https://www.ipbes.net/nexus-assessment
- US Government Policy for Oversight of Dual Use Research of Concern and
  Pathogens with Enhanced Pandemic Potential, effective 2025-05-06, for
  research-governance claims —
  https://bidenwhitehouse.archives.gov/wp-content/uploads/2024/05/USG-Policy-for-Oversight-of-DURC-and-PEPP.pdf

**Open educational sources whose license permits reuse**: MIT OpenCourseWare
(CC BY-NC-SA), OpenStax *Biology 2e* and *Concepts of Biology* (CC BY), NCBI
Bookshelf items whose individual license permits reuse, and Wikimedia Commons
images with recorded license and attribution. Each created deck's `README.md`
records URL, source role (scope versus claim verification), license or terms,
and access date. Free visibility is not permission to ingest, reproduce, or
redistribute; no proprietary textbook prose or figures may be copied.

Access date for every framework and authority listed above: **2026-08-06**.

## Authentic practice outside SRS

Cards maintain retrievable components and decisions. They cannot produce
competence in the following, which must be practiced directly:

- **Wet-lab technique**: pipetting, sterile technique, cell culture, dissection,
  bench microscopy, gel and blot handling, and troubleshooting a failed
  experiment.
- **Field practice**: identification in situ, sampling design executed on real
  terrain, specimen and collection handling, and long-term monitoring.
- **Extended experimental design**: proposing a multi-step study, choosing the
  model system, and defending the control set under critique.
- **Analysis of real data in code**: sequence and variant pipelines, ecological
  and phylogenetic model fitting, image quantification, and version-controlled
  reproducible workflows.
- **Primary-literature practice**: reading whole papers, journal-club argument,
  and reconstructing a figure's logic from supplementary data.
- **Scientific writing and speaking**: proposals, figures, posters, and talks.
- **Ethics and governance in practice**: institutional review, biosafety
  training, animal-care protocols, and dual-use risk assessment.

## Decisions awaiting confirmation

These are genuinely personal choices. Each has been given a defensible default
so the roadmap is coherent, but none should be treated as settled.

1. **Learner identity and prior biology.** Default: complete cold start.
2. **Prior mathematics.** Default: none completed. Confirming completed
   mathematics decks would remove real gates on the advanced and graduate route.
3. **Which branches to actually pursue.** The roadmap proposes representative
   branches across molecular/structural, genomic/computational, organismal,
   ecological/evolutionary, and infection/immunity biology. A learner with a
   specific interest should promote one branch and defer the others rather than
   attempt all of them.
4. **Whether biomedical application is wanted.** Default: disease mechanism is
   included; clinical practice is excluded.
5. **Whether laboratory or field access exists.** This determines how much of
   the methods decks is authentic practice rather than propositional knowledge.
6. **Whether any currently deferred branch should be promoted** — agricultural
   and crop science, marine and freshwater biology, aging biology, pharmacology
   and toxicology, paleobiology, or astrobiology.
