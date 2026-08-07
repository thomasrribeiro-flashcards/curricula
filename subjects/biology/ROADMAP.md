# Biology learning roadmap

## Learner and destination

Detailed learner, convention and evidence decisions live in `SUBJECT_BRIEF.md`.
This file explains the sequence; `subject.toml` is the executable source of
truth for the graph.

- Long-term capabilities: reason causally about living systems across scales
  from molecules to biomes; use evolution, energy flow, information flow,
  structure-function and systems thinking as working analytical tools rather
  than slogans; judge what a biological experiment or figure actually
  establishes; read primary literature in a chosen branch and work at the
  frontier of at least one research area.
- Requested destination: `whole-field`. The route covers the field's material
  domains rather than a single applied endpoint, and continues through
  representative graduate and research-specialization branches.
- Focus branches: none requested. The graduate and research layers therefore
  offer several parallel branches at `specialization` tier instead of committing
  the learner to one.
- Deck granularity: `course`. Each deck is a coherent course-sized unit of
  6-14 ordered chapters.
- Assumed inbound knowledge: none. The learner is treated as a cold start with
  no confirmed biology and no confirmed mathematics beyond what a named
  `mathematics` deck establishes.

Destination controls the current route, not the ceiling. Every deck is
`proposed`; deferred domains listed below can be promoted later without
renumbering the core spine, because deck ids rather than order numbers carry
the prerequisite edges.

## Field coverage

Synchronized with the `[[coverage]]` entries in `subject.toml`.

| Domain | Disposition | Decks | Rationale |
|---|---|---|---|
| scientific-practice-and-biological-literacy | included | biological-literacy-and-scientific-practice, experimental-design-and-data-analysis-in-biology | Entry point for a cold-start learner and the source of the non-teleological causal language, scale fluency and design vocabulary every later deck reuses. |
| chemical-and-energetic-foundations | included | chemistry-of-life | No chemistry subject exists in the collection catalog, so biology owns the minimum chemical substrate its own mechanisms require. |
| cell-biology | included | cell-biology | The cell is the universal structural and functional unit assumed by physiology, genetics, development and disease decks. |
| metabolism-and-bioenergetics | included | bioenergetics-and-metabolism | Pathways and transformations of energy and matter is a crosscutting idea of the field and a prerequisite for physiology, plants, microbes and biochemistry. |
| transmission-and-molecular-genetics | included | genetics-and-heredity, molecular-biology-of-the-gene | Split because chromosome-based transmission reasoning and molecular information flow are separately gradable capabilities that would otherwise exceed a coherent course-sized deck. |
| epigenetics-and-chromatin | included | molecular-biology-of-the-gene, genomics-and-bioinformatics | Chromatin mechanism belongs with gene expression control; genome-scale chromatin assays and their interpretation belong with genomics. |
| biochemistry-and-structural-biology | included | protein-structure-function-and-enzymology, macromolecular-structure-and-mechanism, protein-design-and-computational-structural-biology | Three maturity layers: undergraduate binding and kinetics, graduate mechanism and structural evidence, and research-level prediction and design. |
| evolutionary-biology | included | evolutionary-biology, population-and-quantitative-genetics, evolutionary-and-population-genomics | Evolution is the field's central unifying idea and needs a conceptual deck, a formal population-genetic deck and a genome-scale research deck. |
| systematics-and-biodiversity | included | biological-diversity-and-the-tree-of-life, statistical-phylogenetics-and-comparative-methods | Separates reading and interpreting the tree of life from inferring trees and using them as a statistical framework. |
| microbiology-and-virology | included | microbiology-and-virology | Microbes and viruses dominate biological diversity, drive biogeochemistry and underpin immunology, infectious disease and biotechnology. |
| immunology | included | immunology | A coherent course-sized system with its own selection and recognition logic, required for infection, microbiome and cancer work. |
| animal-physiology | included | animal-physiology-and-homeostasis | Establishes homeostatic regulation, exchange surfaces and scaling constraints that neurobiology and comparative reasoning assume. |
| neurobiology | included | neurobiology, neural-circuits-and-connectomics | Undergraduate membrane-to-circuit mechanism is separable from research-level circuit measurement, connectomics and population modelling. |
| plant-biology | included | plant-biology | Plant function follows different physical and developmental constraints than animals and is required for ecosystem and global-change reasoning. |
| developmental-biology-and-stem-cells | included | developmental-biology | Links genotype to multicellular form and supplies the potency and patterning concepts used in regeneration, cancer and evo-devo. |
| animal-behavior | included | animal-behavior-and-behavioral-ecology | Behaviour is the evolved phenotype that connects neurobiology, evolution and ecology and has its own measurement discipline. |
| population-and-community-ecology | included | population-and-community-ecology | Core quantitative ecology of abundance, interaction and diversity, required for ecosystem, conservation and theoretical decks. |
| ecosystem-ecology-and-biogeochemistry | included | ecosystem-ecology-and-global-change | Extends matter and energy transformation to whole-system and planetary scale, completing the field's crosscutting energy idea. |
| conservation-and-restoration | included | conservation-biology-and-restoration | Applied use of ecological and genetic theory that a whole-field route should reach, kept as a specialization tier rather than a core requirement. |
| global-change-biology | included | ecosystem-ecology-and-global-change, global-change-biology-and-biodiversity-science | Undergraduate exposure to change drivers and consequences, plus a research deck on detection, attribution and biodiversity observation. |
| genomics-and-computational-biology | included | genomics-and-bioinformatics, single-cell-and-spatial-omics | Genome-scale measurement and its computation is now a required literacy across the field, with single-cell and spatial methods as the research frontier. |
| systems-and-quantitative-biology | included | systems-and-quantitative-biology | Supplies dynamical-model, noise and identifiability reasoning that research decks in several branches assume. |
| theoretical-and-mathematical-ecology | included | theoretical-ecology-and-evolutionary-dynamics | The eco-evolutionary branch needs its own formal theory layer so it does not have to route through molecular systems biology. |
| laboratory-and-measurement-methods | included | experimental-methods-in-molecular-and-cell-biology | Interpreting published figures requires knowing what each assay measures and how it fails; kept distinct from design and statistics. |
| research-practice-and-scientific-literature | included | methods-and-logic-of-biological-research | The explicit maturity transition into literature-facing work; a hard prerequisite of every other graduate deck. |
| genome-engineering-and-functional-genomics | included | advanced-genetics-and-genome-engineering | Modern causal genetics at scale is distinct from classical transmission genetics and from method mechanics alone. |
| cancer-biology | included | cancer-biology | A well-defined integrative application of cell biology, genetics and evolution that a whole-field route should include. |
| infectious-disease-and-epidemiology | included | infectious-disease-and-epidemiology | Population-level disease reasoning is a distinct biological capability from host defence mechanism. |
| microbiome-science | included | host-microbiome-and-infection-biology | A fast-moving research area with characteristic inference pitfalls that need explicit training rather than incidental mention. |
| biotechnology-and-synthetic-biology | included | biotechnology-and-synthetic-biology | Applied engineering of biological systems, a major destination of the field and the natural home for biosafety and governance practice. |
| bioethics-biosafety-and-research-governance | included | experimental-design-and-data-analysis-in-biology, biotechnology-and-synthetic-biology, methods-and-logic-of-biological-research | Taught where decisions are actually made rather than as a detached deck: study ethics with design, containment and dual-use with engineering, integrity and authorship with research practice. |
| comparative-anatomy-and-functional-morphology | deferred | None | Partially served by structure-function treatment in physiology, plant biology and diversity; a dedicated morphology and biomechanics deck is a later addition and overlaps physics/biological-physics. |
| taxon-focused-organismal-biology | deferred | None | Entomology, mycology, ornithology and similar units are taxon containers rather than distinct causal capabilities; the tree-of-life deck supplies the organising framework and specific taxa can be added later on request. |
| paleobiology-and-deep-time | deferred | None | Fossil evidence appears within evolution and diversity; a full deck needs geological time, stratigraphy and taphonomy that no staged subject currently supplies. |
| origin-of-life-and-astrobiology | deferred | None | Scientifically active but heavily contested and prebiotic-chemistry dependent; deferred until the chemistry bridge and learner interest justify it. |
| marine-and-freshwater-biology | deferred | None | Habitat-defined rather than mechanism-defined; the ecological and physiological principles are covered, and an aquatic deck would mostly re-teach them in one setting. |
| agricultural-crop-and-animal-science | deferred | None | An adjacent applied field with its own curriculum; its biological core is already supplied by plant biology, quantitative genetics and ecology. |
| pharmacology-and-toxicology | deferred | None | Requires organic chemistry and dose-response pharmacokinetics beyond the current chemistry bridge; receptor and enzyme inhibition logic is covered in enzymology and physiology. |
| aging-and-regenerative-biology | deferred | None | Genuine research area, but its foundations are distributed across cell biology, development and genetics; a dedicated deck is a reasonable later extension. |
| human-genetics-and-precision-medicine | deferred | None | Core inheritance, association mapping and polygenic score limits are taught in genetics, quantitative genetics and population genomics; a clinical-facing deck needs medical context outside this route. |
| clinical-medicine-and-veterinary-practice | out-of-scope | None | Professional practice with its own accreditation and patient-safety obligations; this subject teaches the biology, not diagnosis or treatment decisions. |
| psychology-and-cognitive-science | out-of-scope | None | A separate discipline; biology stops at nervous system mechanism, circuits and evolved behaviour. |
| biological-physics-and-biomechanics | out-of-scope | None | Owned by physics/biological-physics in the collection catalog and referenced as preparation rather than duplicated here. |
| general-mathematical-and-statistical-methods | out-of-scope | None | Owned by the mathematics subject; this curriculum references its probability, statistical inference, computing, differential equations and mathematical biology decks instead of rebuilding them. |

## Deck sequence

The graph, not the numbering, defines the route. Order numbers only give a
valid linear reading; a learner may follow any path that respects the hard
prerequisite edges. Hard prerequisites are required inbound knowledge and are
inherited by created decks; recommended sequencing is helpful preparation that
is not inherited.

| Order | Deck | Level | Tier | Hard prerequisites | Recommended after | Est. chapters | Durable capabilities | Status |
|---:|---|---|---|---|---|---:|---|---|
| 1 | biological-literacy-and-scientific-practice | foundational | core | mathematics/number-sense-and-arithmetic | None | 9 | Distinguish living systems and their levels of organisation; move fluently among biological scales and units; separate observation from inference; state hypotheses and predictions; identify variables and controls; describe biological causes without purpose language. | proposed |
| 2 | chemistry-of-life | foundational | core | biological-literacy-and-scientific-practice | mathematics/elementary-algebra-and-functions | 11 | Predict interactions from bonding and polarity; reason about water, pH and buffering; compute concentrations and dilutions; explain spontaneity and coupled reactions qualitatively; relate biomolecule structure to function. | proposed |
| 3 | experimental-design-and-data-analysis-in-biology | undergraduate-core | core | chemistry-of-life, mathematics/elementary-algebra-and-functions | mathematics/statistical-inference-and-data-analysis | 11 | Design a controlled biological experiment; identify the experimental unit and detect pseudoreplication; choose and justify a model system; read biological data displays and error bars; distinguish effect size from significance; apply rigor and ethics standards. | proposed |
| 4 | cell-biology | undergraduate-core | core | chemistry-of-life | None | 11 | Predict transport across membranes; trace protein targeting and secretion; explain cytoskeletal and motor function; follow a signal transduction cascade; reason about cell cycle control and cell death; interpret microscopy evidence. | proposed |
| 5 | bioenergetics-and-metabolism | undergraduate-core | core | cell-biology | None | 10 | Track carbon, electrons and energy through central pathways; explain chemiosmotic coupling; compare aerobic, anaerobic and photosynthetic strategies; predict the effect of an inhibitor or a nutrient shift on flux. | proposed |
| 6 | genetics-and-heredity | undergraduate-core | core | cell-biology | None | 11 | Predict inheritance from chromosome behaviour; solve crosses including linkage and epistasis; analyse pedigrees; map genes from recombination data; explain chromosomal and non-nuclear inheritance anomalies. | proposed |
| 7 | molecular-biology-of-the-gene | undergraduate-core | core | genetics-and-heredity | bioenergetics-and-metabolism | 12 | Trace information from DNA to functional protein; predict consequences of mutation and repair failure; explain transcriptional and post-transcriptional control; reason about chromatin state; reconstruct the classic experiments behind each mechanism. | proposed |
| 8 | evolutionary-biology | undergraduate-core | core | genetics-and-heredity | molecular-biology-of-the-gene | 11 | Apply Hardy-Weinberg reasoning; attribute allele-frequency change to selection, drift, migration or mutation; explain adaptation without teleology; distinguish homology from analogy; read a phylogeny; evaluate evolutionary evidence. | proposed |
| 9 | animal-physiology-and-homeostasis | undergraduate-core | recommended | bioenergetics-and-metabolism | physics/measurement-and-physical-reasoning | 11 | Analyse feedback regulation in a physiological system; predict exchange and transport limits from surface, volume and gradient; reason about scaling; compare convergent solutions to shared physical constraints across taxa. | proposed |
| 10 | plant-biology | undergraduate-core | recommended | bioenergetics-and-metabolism | evolutionary-biology | 11 | Explain water movement by water potential; analyse the stomatal water-carbon trade-off; relate meristem activity to modular growth; compare C3, C4 and CAM strategies; explain hormonal and light control of development. | proposed |
| 11 | microbiology-and-virology | undergraduate-core | core | bioenergetics-and-metabolism, molecular-biology-of-the-gene | evolutionary-biology | 11 | Interpret growth curves and culture data; compare microbial energy strategies; explain horizontal gene transfer and resistance evolution; describe viral replication strategies; predict microbial roles in an environment. | proposed |
| 12 | biological-diversity-and-the-tree-of-life | undergraduate-core | core | evolutionary-biology | microbiology-and-virology | 10 | Apply and critique species concepts; classify by monophyly rather than resemblance; place major lineages and key transitions on the tree; use correct nomenclature; read and question a published phylogeny. | proposed |
| 13 | population-and-community-ecology | undergraduate-core | core | evolutionary-biology, experimental-design-and-data-analysis-in-biology | mathematics/statistical-inference-and-data-analysis | 11 | Fit and interpret population growth models; analyse life tables and life histories; predict outcomes of competition, predation and mutualism; interpret food-web and succession data; design a defensible sampling scheme. | proposed |
| 14 | protein-structure-function-and-enzymology | undergraduate-advanced | core | bioenergetics-and-metabolism | physics/thermodynamics-and-statistical-mechanics | 10 | Relate folding energetics to stability; derive and apply binding and Michaelis-Menten relations; diagnose inhibition type from kinetic data; explain catalytic strategy and allosteric control; judge structural evidence quality. | proposed |
| 15 | experimental-methods-in-molecular-and-cell-biology | undergraduate-advanced | core | molecular-biology-of-the-gene, experimental-design-and-data-analysis-in-biology | protein-structure-function-and-enzymology | 11 | State what each common assay measures; specify the controls a result requires; recognise characteristic artefacts; choose an appropriate method for a stated question; interpret a multi-panel figure critically. | proposed |
| 16 | developmental-biology | undergraduate-advanced | recommended | molecular-biology-of-the-gene | experimental-methods-in-molecular-and-cell-biology | 10 | Predict patterning outcomes from morphogen gradients and induction; interpret mutant and transplantation phenotypes; explain conserved pathway reuse; reason about potency and regeneration; compare development across taxa. | proposed |
| 17 | neurobiology | undergraduate-advanced | recommended | animal-physiology-and-homeostasis | developmental-biology, physics/electricity-magnetism-and-circuits | 11 | Compute equilibrium and resting potentials; explain action potential generation and propagation; analyse synaptic integration; describe sensory transduction and coding; reason about plasticity; interpret electrophysiological and imaging records. | proposed |
| 18 | immunology | undergraduate-advanced | recommended | microbiology-and-virology | experimental-methods-in-molecular-and-cell-biology | 11 | Trace an immune response from recognition to memory; explain repertoire generation and clonal selection; distinguish MHC class I and II pathways; reason about tolerance failure and evasion; explain vaccine logic. | proposed |
| 19 | ecosystem-ecology-and-global-change | undergraduate-advanced | core | population-and-community-ecology | plant-biology, microbiology-and-virology | 10 | Construct energy and nutrient budgets; explain carbon, nitrogen and phosphorus cycling and its microbial control; predict ecosystem responses to nutrient loading, climate and land-use change; interpret large-scale observational evidence. | proposed |
| 20 | animal-behavior-and-behavioral-ecology | undergraduate-advanced | recommended | evolutionary-biology | population-and-community-ecology, neurobiology | 9 | Separate Tinbergen's four questions for one behaviour; build and apply an ethogram; test optimality and inclusive-fitness predictions; analyse mating systems and parental conflict; assess signal reliability. | proposed |
| 21 | population-and-quantitative-genetics | undergraduate-advanced | core | evolutionary-biology, mathematics/probability | mathematics/statistical-inference-and-data-analysis | 11 | Model allele-frequency dynamics under combined forces; reason about effective population size and drift; compute relatedness and inbreeding coefficients; partition phenotypic variance and predict selection response; critique association studies. | proposed |
| 22 | genomics-and-bioinformatics | undergraduate-advanced | core | molecular-biology-of-the-gene, mathematics/mathematical-computing-and-experimentation | experimental-design-and-data-analysis-in-biology, experimental-methods-in-molecular-and-cell-biology | 12 | Choose a sequencing strategy for a question; reason about alignment, assembly and variant-calling errors; quantify and compare transcriptomes; interpret annotation and enrichment output; apply multiple-testing discipline; build a reproducible workflow. | proposed |
| 23 | statistical-phylogenetics-and-comparative-methods | undergraduate-advanced | recommended | biological-diversity-and-the-tree-of-life, mathematics/probability | genomics-and-bioinformatics, mathematics/statistical-inference-and-data-analysis | 10 | Select substitution and partition models; compare parsimony, likelihood and Bayesian inference; interpret support values correctly; explain gene-tree/species-tree discordance; apply comparative methods that correct for shared ancestry. | proposed |
| 24 | cancer-biology | undergraduate-advanced | specialization | molecular-biology-of-the-gene | immunology, genomics-and-bioinformatics | 10 | Explain tumourigenesis as somatic evolution; classify driver alterations by mechanism; connect hallmark capabilities to underlying pathways; reason about heterogeneity and resistance; evaluate the rationale of a targeted or immune therapy. | proposed |
| 25 | infectious-disease-and-epidemiology | undergraduate-advanced | specialization | microbiology-and-virology, experimental-design-and-data-analysis-in-biology | immunology, mathematics/statistical-inference-and-data-analysis | 10 | Compute and interpret incidence, prevalence and risk measures; identify bias in observational designs; parameterise a compartmental model and interpret the reproduction number; reason about herd immunity; investigate an outbreak. | proposed |
| 26 | conservation-biology-and-restoration | undergraduate-advanced | specialization | population-and-community-ecology | ecosystem-ecology-and-global-change, population-and-quantitative-genetics | 11 | Assess extinction risk from demographic and genetic evidence; run and critique a viability analysis; evaluate fragmentation and connectivity; prioritise areas systematically; design restoration with measurable success criteria and monitoring. | proposed |
| 27 | biotechnology-and-synthetic-biology | undergraduate-advanced | specialization | experimental-methods-in-molecular-and-cell-biology | protein-structure-function-and-enzymology, genomics-and-bioinformatics | 11 | Select an expression host and troubleshoot yield and folding; design a directed-evolution campaign; balance an engineered metabolic pathway; predict genetic circuit failure modes; apply biosafety, biosecurity and dual-use review. | proposed |
| 28 | methods-and-logic-of-biological-research | graduate | core | experimental-design-and-data-analysis-in-biology, molecular-biology-of-the-gene, mathematics/statistical-inference-and-data-analysis | experimental-methods-in-molecular-and-cell-biology, genomics-and-bioinformatics, population-and-community-ecology | 9 | Dissect a primary paper claim by claim; decide whether a design licenses a causal conclusion; generate and test alternative explanations; critique statistical practice and reporting; apply preregistration, reproducibility and integrity norms. | proposed |
| 29 | macromolecular-structure-and-mechanism | graduate | specialization | protein-structure-function-and-enzymology, methods-and-logic-of-biological-research | None | 10 | Design kinetic experiments that resolve mechanism; interpret pre-steady-state and isotope-effect data; reason about conformational ensembles and allostery; explain machine and transporter cycles; assess structural models against their raw evidence. | proposed |
| 30 | advanced-genetics-and-genome-engineering | graduate | specialization | experimental-methods-in-molecular-and-cell-biology, genomics-and-bioinformatics, methods-and-logic-of-biological-research | None | 10 | Choose forward or reverse strategy for a question; interpret suppressor and epistasis results; design a pooled screen with adequate controls; analyse deep mutational scanning data; draw causal conclusions from perturbation experiments. | proposed |
| 31 | systems-and-quantitative-biology | graduate | core | genomics-and-bioinformatics, methods-and-logic-of-biological-research, mathematics/differential-equations | mathematics/dynamical-systems-and-ergodic-theory, physics/biological-physics | 11 | Build and analyse dynamical models of biological networks; find steady states and assess stability; explain bistability and oscillation from feedback structure; model stochastic expression; test identifiability and validate a fitted model honestly. | proposed |
| 32 | theoretical-ecology-and-evolutionary-dynamics | graduate | specialization | methods-and-logic-of-biological-research, population-and-quantitative-genetics, population-and-community-ecology, mathematics/differential-equations | mathematics/dynamical-systems-and-ergodic-theory | 11 | Analyse structured and spatial population models; perform invasion and coexistence analysis; model stochastic demography and extinction; apply adaptive dynamics and evolutionarily stable strategy reasoning; confront theory with time-series data. | proposed |
| 33 | protein-design-and-computational-structural-biology | research-specialization | specialization | macromolecular-structure-and-mechanism, systems-and-quantitative-biology | None | 9 | Evaluate structure predictions and their confidence measures; design a binder or active site computationally; use generative sequence and backbone models critically; detect benchmark leakage; plan the experiments that must validate a design. | proposed |
| 34 | single-cell-and-spatial-omics | research-specialization | specialization | systems-and-quantitative-biology, experimental-methods-in-molecular-and-cell-biology | None | 9 | Choose a single-cell or spatial platform for a question; diagnose dropout, ambient and doublet artefacts; justify normalisation, integration and clustering choices; interpret trajectory and velocity inference against its assumptions; test differential abundance rigorously. | proposed |
| 35 | evolutionary-and-population-genomics | research-specialization | specialization | population-and-quantitative-genetics, genomics-and-bioinformatics, methods-and-logic-of-biological-research | None | 10 | Infer demographic history from genomic variation; distinguish selection from background selection and demography; apply coalescent and admixture methods; interpret ancient DNA evidence; assess polygenic architecture and portability claims. | proposed |
| 36 | neural-circuits-and-connectomics | research-specialization | specialization | neurobiology, systems-and-quantitative-biology | None | 10 | Select recording and perturbation methods that answer a circuit question; interpret large-scale population activity and dimensionality; use connectome data appropriately; relate recurrent network models to neural data; quantify behaviour rigorously. | proposed |
| 37 | host-microbiome-and-infection-biology | research-specialization | specialization | immunology, genomics-and-bioinformatics, methods-and-logic-of-biological-research | None | 10 | Choose amplicon or metagenomic strategies appropriately; handle compositional data correctly; design gnotobiotic and colonisation experiments that establish causation; analyse within-host evolution and resistance emergence; evaluate translational claims. | proposed |
| 38 | global-change-biology-and-biodiversity-science | research-specialization | specialization | ecosystem-ecology-and-global-change, theoretical-ecology-and-evolutionary-dynamics | conservation-biology-and-restoration | 10 | Use monitoring, remote sensing and eDNA data appropriately; perform detection and attribution of biological change; fit and critique distribution models and their extrapolation; assess plastic versus evolutionary responses; evaluate tipping-point and assessment claims. | proposed |

## Design decisions that shape this graph

### Biology owns the chemistry bridge

The staged cross-subject catalog contains only `mathematics` and `physics`.
There is no chemistry subject, so no `chemistry/...` reference may be invented.
Every mechanistic claim in cell biology, metabolism, molecular biology and
biochemistry depends on bonding, water behaviour, pH, concentration and free
energy, so `chemistry-of-life` is owned here. It is deliberately scoped to the
chemistry biology actually uses and is not a general chemistry course: no
reaction mechanisms, spectroscopy, quantum treatment or synthesis. If a
chemistry subject is later added to the collection, this deck should be
re-examined and narrowed, not silently kept.

### Statistics is imported, but a biology-specific design bridge is kept

`mathematics/statistical-inference-and-data-analysis` sits behind
`mathematics/probability`, which sits behind single-variable integral calculus.
Making it a hard prerequisite of ordinary undergraduate biology would be a
false prerequisite: an undergraduate cannot read a controlled experiment only
after a calculus-based inference course, and the whole undergraduate spine
would be gated behind calculus it does not otherwise need.

The split is therefore by capability rather than by subject label.
`experimental-design-and-data-analysis-in-biology` teaches only what is
biological transfer and cannot be learned from a statistics course: the
experimental unit and pseudoreplication, model-organism choice, biological
versus technical variation, dose-response and time-course structure, reading
biological figures, and research ethics. It hard-requires only
`mathematics/elementary-algebra-and-functions` and lists the statistics deck as
recommended. Decks that genuinely need formal inference name it directly:
`population-and-quantitative-genetics` and
`statistical-phylogenetics-and-comparative-methods` hard-require
`mathematics/probability`, and `methods-and-logic-of-biological-research`
hard-requires `mathematics/statistical-inference-and-data-analysis`, because
judging whether a published analysis supports its conclusion is not possible
without it.

Similarly, no programming deck is duplicated:
`genomics-and-bioinformatics` hard-requires
`mathematics/mathematical-computing-and-experimentation`, and quantitative
graduate decks hard-require `mathematics/differential-equations`.
`physics/biological-physics` and
`mathematics/dynamical-systems-and-ergodic-theory` are referenced as
recommended preparation for `systems-and-quantitative-biology` and
`theoretical-ecology-and-evolutionary-dynamics` rather than rebuilt here.

### The molecular and ecological-evolutionary branches fork early

The field forks structurally after `evolutionary-biology`. The molecular route
runs through `molecular-biology-of-the-gene`, methods, genomics and systems
biology; the eco-evolutionary route runs through
`population-and-community-ecology`, `ecosystem-ecology-and-global-change`,
`population-and-quantitative-genetics` and theoretical ecology. Neither is a
prerequisite of the other, and the graph never forces an ecologist through
wet-lab molecular methods or a molecular biologist through community ecology.

The one deliberate junction is `methods-and-logic-of-biological-research`. It
is kept branch-neutral: its hard prerequisites are
`experimental-design-and-data-analysis-in-biology`,
`molecular-biology-of-the-gene` and
`mathematics/statistical-inference-and-data-analysis`, not laboratory methods.
`molecular-biology-of-the-gene` is retained because contemporary papers in
every branch, including ecology and evolution, report sequence and expression
evidence. Wet-lab methods, genomics and community ecology are recommended, not
required, so both branches reach the research layer without a detour.

### Maturity transitions into graduate and research work

Each graduate and research deck lists the technical and representational
capabilities its first chapter assumes, and the direct prerequisite closure
that establishes them.

- **methods-and-logic-of-biological-research** (graduate) assumes: controlled
  design vocabulary and rigor standards (from
  `experimental-design-and-data-analysis-in-biology`); enough molecular
  mechanism to follow the evidence in a modern paper (from
  `molecular-biology-of-the-gene`, itself downstream of genetics, cell biology
  and the chemistry bridge); and estimation, uncertainty, model comparison and
  multiple-testing reasoning (from
  `mathematics/statistical-inference-and-data-analysis`). This is the explicit
  coursework-to-literature transition and is a hard prerequisite of every other
  graduate deck, so no later deck reaches literature-facing work without a
  research-method layer.
- **macromolecular-structure-and-mechanism** assumes binding equilibria,
  steady-state kinetics, inhibition analysis, energetics and structure-determination
  literacy from `protein-structure-function-and-enzymology`, plus paper-level
  critique from the methods deck. Pre-steady-state kinetics and ensemble
  allostery are genuine extensions of established kinetic and thermodynamic
  representations, not a new mathematical layer.
- **advanced-genetics-and-genome-engineering** assumes perturbation mechanics
  and controls from `experimental-methods-in-molecular-and-cell-biology`, high-
  throughput data handling and multiple-testing discipline from
  `genomics-and-bioinformatics`, and causal-inference judgement from the methods
  deck. `genetics-and-heredity` is not listed as a hard edge because it is
  already guaranteed through both named paths; listing it would be redundant.
- **systems-and-quantitative-biology** assumes high-dimensional data structure
  and computing from `genomics-and-bioinformatics`, model criticism from the
  methods deck, and — critically — the ability to formulate and analyse
  dynamical systems, which is why `mathematics/differential-equations` is a hard
  edge rather than an aspiration. Without it, stability, bifurcation and
  parameter estimation would be assumed rather than established.
- **theoretical-ecology-and-evolutionary-dynamics** assumes ecological model
  structure and field-data reality from `population-and-community-ecology`,
  formal allele-frequency and variance reasoning from
  `population-and-quantitative-genetics`, dynamical-systems technique from
  `mathematics/differential-equations`, and literature critique from the methods
  deck. This gives the eco-evolutionary branch its own theory layer so it never
  has to route through molecular systems biology to reach research level.
- **protein-design-and-computational-structural-biology** assumes mechanism and
  structural-evidence judgement from `macromolecular-structure-and-mechanism`
  and model fitting, validation, benchmarking and high-dimensional reasoning
  from `systems-and-quantitative-biology`. The learner therefore evaluates
  learned structure predictors as models with failure modes rather than as
  oracles.
- **single-cell-and-spatial-omics** assumes assay mechanics and artefact
  awareness from `experimental-methods-in-molecular-and-cell-biology` and
  normalisation, dimensionality reduction, latent-structure and model-validation
  reasoning from `systems-and-quantitative-biology` (which carries genomics
  forward, so a genomics edge would be redundant).
- **evolutionary-and-population-genomics** assumes coalescent-adjacent and
  variance-component theory from `population-and-quantitative-genetics`,
  variant data and pipeline reality from `genomics-and-bioinformatics`, and
  inference critique from the methods deck. Selection scans are taught as
  inference problems with known false-positive structure, which requires all
  three.
- **neural-circuits-and-connectomics** assumes biophysical and synaptic
  mechanism from `neurobiology` and population-level, dimensionality and
  network-model reasoning from `systems-and-quantitative-biology`. This is the
  one research deck reachable through the physiology branch, and it is
  deliberately not reachable from `neurobiology` alone, because circuit claims
  are today made with large-scale statistical models.
- **host-microbiome-and-infection-biology** assumes host-defence mechanism from
  `immunology`, community sequencing and compositional data handling from
  `genomics-and-bioinformatics`, and causation-versus-correlation discipline
  from the methods deck, which is the single most common failure mode in this
  literature. `microbiology-and-virology` is guaranteed through `immunology`,
  so it is not restated.
- **global-change-biology-and-biodiversity-science** assumes biogeochemical and
  ecosystem-scale reasoning from `ecosystem-ecology-and-global-change` and
  formal population, spatial and eco-evolutionary dynamics from
  `theoretical-ecology-and-evolutionary-dynamics`, which also carries the
  methods deck forward. Detection, attribution and distribution modelling are
  otherwise assumed rather than established.

No research-specialization deck depends directly on an undergraduate-core deck
alone. Every one passes through at least one graduate deck, and therefore
through `methods-and-logic-of-biological-research`.

### Coherence tests applied when naming decks

Deck boundaries were tested for a single coherent capability, not textbook
convention.

- "Introductory biology" was rejected as one deck: at course granularity it
  would exceed 14 chapters and mix chemistry, cells, genetics, evolution and
  ecology into one unassessable unit. It is split into decks 1-2 and 4-8.
- "Organismal biology" was rejected as a container label rather than a
  teachable unit, and decomposed into `animal-physiology-and-homeostasis`,
  `plant-biology`, `developmental-biology`, `neurobiology` and
  `animal-behavior-and-behavioral-ecology`.
- "Biochemistry" was split by maturity: metabolic pathways and energy flow sit
  in `bioenergetics-and-metabolism` at undergraduate-core level, while
  quantitative binding, kinetics and structure sit in
  `protein-structure-function-and-enzymology`, which needs more mathematical
  comfort.
- "Genetics" was split into transmission (`genetics-and-heredity`) and
  molecular information flow (`molecular-biology-of-the-gene`) because they are
  separately gradable and jointly too large.
- "Ecology" was split into population-and-community and ecosystem levels
  because the second reasons about mass and energy budgets rather than about
  individuals and interactions.
- `microbiology-and-virology` was kept merged: viruses are studied through the
  same host-interaction and molecular-genetics reasoning as their cellular
  hosts, and separating them would duplicate replication and evolution content
  in both.
- `immunology` was kept whole rather than split into innate and adaptive
  because the two are taught through their integration.

## Cross-deck concepts

These ideas recur with increasing depth and must not be independently
re-taught. Each is introduced once at its named home and thereafter reused.

- **Evolution as causal explanation** — introduced in `evolutionary-biology`;
  reused in diversity, microbiology (resistance), immunology (repertoire and
  selection), behaviour, cancer (somatic evolution), infectious disease,
  conservation and every research-level evolutionary deck.
- **Free energy, gradients and coupling** — introduced in `chemistry-of-life`;
  deepened in `bioenergetics-and-metabolism`, applied to membranes and transport
  in `cell-biology`, to physiology and plant water transport, to enzymology, and
  to biophysical reasoning in the graduate layer.
- **Structure determines function** — introduced in `chemistry-of-life` for
  biomolecules; extended in cell biology, physiology, plant anatomy,
  enzymology, structural biology and protein design.
- **Information flow and regulation** — introduced in
  `molecular-biology-of-the-gene`; reused in development, immunology,
  microbiology, cancer, genomics and genome engineering.
- **Feedback and homeostasis** — introduced in
  `animal-physiology-and-homeostasis`; reused in plant hormone control, neural
  circuits, gene circuits, systems biology and ecological regulation.
- **Scale and levels of organisation** — introduced in
  `biological-literacy-and-scientific-practice`; reused whenever a deck moves
  between molecule, cell, organism, population and ecosystem.
- **Sampling, variation and uncertainty** — introduced in
  `experimental-design-and-data-analysis-in-biology`; deepened by the imported
  mathematics decks and applied in ecology, genomics, epidemiology and the
  graduate research deck.
- **Model organisms and generalisation limits** — introduced in
  `experimental-design-and-data-analysis-in-biology`; revisited whenever a
  mechanism is established in one system and extended to another.
- **Non-teleological causal language** — introduced in
  `biological-literacy-and-scientific-practice` and enforced in every deck; a
  standing authoring constraint recorded in `SUBJECT_BRIEF.md`.
- **Tree thinking** — introduced in `evolutionary-biology`, formalised in
  `biological-diversity-and-the-tree-of-life`, made statistical in
  `statistical-phylogenetics-and-comparative-methods`, and reused in genomics,
  virology and comparative research decks.
- **Evidence-to-claim discipline** — begun in deck 1, made explicit for assays
  in `experimental-methods-in-molecular-and-cell-biology`, and made the primary
  target of `methods-and-logic-of-biological-research`.

Recurring representations that should be taught once and reused: labelled
mechanism diagrams, pathway and flux maps, dose-response and kinetic curves,
pedigrees and Punnett squares, gel and blot images, micrographs with scale
bars, phylogenetic trees, population growth and life-table plots, sequence
alignments and genome browser tracks, network and circuit diagrams, and
volcano, heatmap and embedding plots.

## Practice outside SRS

Spaced repetition secures retrieval, not competence. The following must be
practised elsewhere and should be planned alongside the decks.

- **Wet-lab work.** Pipetting, sterile technique, culture maintenance,
  microscopy, electrophoresis, PCR and cloning cannot be learned from cards.
  Pair decks 4-7 and 15 with a teaching laboratory, a summer placement, or at
  minimum with recorded protocol walkthroughs and virtual labs.
- **Field and observational work.** Sampling design, species identification,
  quadrat and transect method, ethogram construction and specimen handling
  require time outdoors. Pair with decks 12, 13, 19, 20 and 26.
- **Computational projects.** Working through a real sequencing dataset end to
  end — quality control, alignment, quantification, differential analysis,
  figure production, and a reproducible script — is required for decks 22, 31,
  34 and 35 and cannot be replaced by retrieval practice.
- **Modelling exercises.** Simulating population, epidemiological and network
  models, and testing parameter sensitivity, supports decks 21, 25, 31 and 32.
- **Reading the primary literature on a schedule.** A weekly paper with written
  critique is the core practice for deck 28 and every deck after it; journal
  club discussion is the intended form.
- **Scientific writing and figure making.** Writing a methods section, a figure
  legend, a graphical abstract and a short review develops capabilities cards
  can only support.
- **Quantitative problem sets.** Extended multi-step problems in genetics,
  enzyme kinetics, population genetics and ecological modelling need worked
  practice beyond single-card retrieval.
- **Ethics and governance deliberation.** Case discussion of dual-use research,
  gene editing, data sharing and animal use requires argument with others.
