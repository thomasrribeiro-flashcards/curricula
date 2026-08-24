# Computer Science learning roadmap

## Learner and destination

- Long-term capabilities: build and reason about software and computing systems;
  translate among code, traces, mathematics, data, diagrams, protocols, experiments,
  and human evidence; make defensible design choices; diagnose failures and
  misconceptions; evaluate societal consequences; and enter selected research
  literatures without hidden maturity gaps.
- Requested destination: `whole-field`. The roadmap is a layered map, not a demand
  that one learner complete all 45 courses and not a permanent ceiling.
- Focus branches: none specified. Representative advanced routes cover theory,
  programming languages/software, systems/networking, AI, human-centered computing,
  security/privacy, data/information retrieval, robotics, HPC/scientific computing,
  and quantum computing.
- Deck granularity: `course`, with every proposal estimated at 6–14 chapters.
- Cold-start rule: no computer-science, mathematics, tool, or research knowledge is
  assumed unless a direct prerequisite closure establishes it. Personal defaults
  needing confirmation are listed in `SUBJECT_BRIEF.md`.

## Design basis

The field map starts from all 17 CS2023 knowledge areas, uses CC2020 to police the
boundary with neighboring computing disciplines, uses the ACM data-science and
CSEC2017/NICE frameworks for data and security breadth, and checks representative
research routes against the current NSF CISE portfolio. Framework headings are not
treated as equal-sized courses. Each deck instead has one practice portfolio,
representation grammar, and culminating capability.

The core route establishes programming, program/data structure, machine models,
software construction, algorithms, and professional judgment. Recommended
undergraduate courses expose the major CS2023 domains without making every survey a
hard prerequisite. Learner-selected upper-division branches then feed explicit
graduate foundations. A branch-neutral research-methods deck supplies literature,
method selection, reproducibility, communication, and ethics; each technical branch
supplies the formal or empirical depth its research specialization actually needs.

## Field coverage

This matrix is synchronized with `subject.toml`. Included rows name only decks owned
by this subject. External capabilities are explained after the deck table.

| Domain | Disposition | Decks | Rationale |
|---|---|---|---|
| software-development-fundamentals | included | programming-and-software-development-foundations, data-structures-and-program-design | A cold-start programming course establishes executable mental models and tools; a second course develops abstract interfaces, invariants, and larger program structure. |
| algorithmic-foundations | included | data-structures-and-program-design, algorithm-design-and-analysis, advanced-algorithms-and-complexity, algorithms-and-complexity-research | The route progresses from representations and invariants to proof-based design, graduate methods, and research claims without merging independent application branches. |
| architecture-and-organization | included | computer-systems-foundations, computer-architecture-and-organization, embedded-and-real-time-systems | A shared machine bridge precedes a coherent architecture course and an optional constrained-platform application. |
| systems-fundamentals | included | computer-systems-foundations, computer-architecture-and-organization, operating-systems, parallel-and-distributed-computing | Representation, execution, resource, and concurrency models recur with increasing depth across the systems spine. |
| operating-systems | included | operating-systems, parallel-and-distributed-computing, advanced-systems-and-distributed-computing, scalable-systems-and-networking-research | A course-scale OS capability supports concurrency and later systems research while avoiding an all-systems monolith. |
| networking-and-communication | included | networks-and-communication, parallel-and-distributed-computing, web-and-cloud-application-engineering, advanced-systems-and-distributed-computing, scalable-systems-and-networking-research | Protocol reasoning is independently learnable, then reused in distributed, application, and research settings. |
| parallel-and-distributed-computing | included | parallel-and-distributed-computing, advanced-systems-and-distributed-computing, high-performance-and-scientific-computing, advanced-parallel-and-high-performance-computing, scalable-systems-and-networking-research, high-performance-and-scientific-computing-research | The shared concurrency/distribution course branches into service systems and numerical high-performance work with distinct practices and capstones. |
| data-management | included | data-management-and-databases, machine-learning-and-data-science, information-retrieval-and-language-technologies, advanced-data-systems-and-information-retrieval, data-management-and-information-retrieval-research | Database guarantees, analytical data practice, and information access remain separate but reconnect in an advanced data-systems route. |
| foundations-of-programming-languages | included | programming-language-concepts, compiler-construction-and-language-implementation, advanced-programming-languages-and-formal-methods, programming-languages-and-software-research | Language meaning is taught before implementation and formal research, preventing a compiler project from serving as the learner's first semantics course. |
| software-engineering | included | programming-and-software-development-foundations, software-engineering, compiler-construction-and-language-implementation, web-and-cloud-application-engineering, programming-languages-and-software-research | Foundational tools lead to team-scale lifecycle competence and later platform or research applications. |
| human-computer-interaction | included | human-computer-interaction, human-centered-computing-research-methods, human-ai-interaction-and-accessible-computing-research | Design and evaluation precede graduate human-subjects methods and a focused contemporary human-AI/accessibility route. |
| graphics-and-interactive-techniques | included | graphics-and-interactive-techniques, computer-vision-and-visual-computing | Graphics owns synthesis and interaction pipelines; vision owns inference from images, with optional two-way preparation rather than a false hard edge. |
| artificial-intelligence | included | artificial-intelligence-foundations, machine-learning-and-data-science, robotics-and-autonomous-systems, information-retrieval-and-language-technologies, computer-vision-and-visual-computing, advanced-ai-and-machine-learning, advanced-robotics-and-perception, trustworthy-ai-and-learning-systems-research, human-ai-interaction-and-accessible-computing-research, embodied-ai-and-robotics-research | A broad AI foundation branches into statistically mature learning, language, vision, and embodied systems before graduate and research specialization. |
| security | included | security-and-privacy-foundations, cybersecurity-engineering, advanced-security-and-privacy, security-and-privacy-research | Threat and protection concepts precede operating/network practice, advanced assurance, and research evaluation. |
| society-ethics-and-the-profession | included | society-ethics-and-professional-practice, software-engineering, human-computer-interaction, cybersecurity-engineering, computer-science-research-methods, trustworthy-ai-and-learning-systems-research | One coherent professional-judgment course anchors obligations, while technical decks must contextualize those obligations rather than outsourcing them. |
| mathematical-and-statistical-foundations | included | algorithm-design-and-analysis, artificial-intelligence-foundations, machine-learning-and-data-science, advanced-algorithms-and-complexity, advanced-ai-and-machine-learning | Canonical mathematics decks supply broad proof, discrete, probability, linear-algebra, statistics, and optimization capabilities; CS-owned decks teach their computational transfer instead of duplicating them. |
| specialized-platform-development | included | web-and-cloud-application-engineering, embedded-and-real-time-systems, robotics-and-autonomous-systems | Independent web/cloud, embedded/real-time, and embodied platforms remain separate courses because their constraints, representations, and capstones differ. |
| data-science-and-machine-learning | included | machine-learning-and-data-science, advanced-ai-and-machine-learning, trustworthy-ai-and-learning-systems-research | The route separates empirical data competence from broad AI, then reconnects them for advanced learning systems and trustworthy research. |
| robotics-and-intelligent-physical-systems | included | robotics-and-autonomous-systems, advanced-robotics-and-perception, embodied-ai-and-robotics-research | A physical sensing-planning-control spine receives its own laboratory and representation grammar rather than being hidden inside general AI. |
| computational-science-and-high-performance-computing | included | high-performance-and-scientific-computing, advanced-parallel-and-high-performance-computing, high-performance-and-scientific-computing-research | Numerical validity, scientific modeling, and performance scaling form a coherent route distinct from service-oriented distributed systems. |
| research-methods-and-reproducibility | included | computer-science-research-methods, human-centered-computing-research-methods | A branch-neutral research-practice layer precedes literature-facing work, with an additional human-subjects layer where representational and ethical transfer requires it. |
| quantum-computing | included | quantum-algorithms-and-computing-research | The established physics quantum-information deck supplies the physical and information-theoretic base; CS owns the later algorithms, complexity, language, and systems research transfer. |
| mobile-ubiquitous-and-immersive-platforms | deferred | None | Valuable specialized-platform extensions, but web/cloud and embedded/real-time provide representative initial routes without forcing several independent platform courses into the first whole-field map. |
| computing-education-research | deferred | None | A legitimate human-centered research branch requiring learning-science and education-method transfer; deferred until an owning education capability and learner interest are confirmed. |
| bioinformatics-health-and-domain-computing | deferred | None | Application domains require substantial owning-domain knowledge; future routes should reuse established biology, health, science, or humanities decks rather than teach them superficially inside CS. |
| additional-applied-computing-microfields | deferred | None | Computational social science, digital humanities, fintech, games, geospatial computing, and other applications are future extensions selected by learner goals, not one incoherent survey deck. |
| computer-engineering-and-device-fabrication | out-of-scope | None | Logic-to-architecture interfaces are included, but circuits, electronics, semiconductor devices, and fabrication belong to computer engineering and physics. |
| enterprise-information-systems-and-it-operations | out-of-scope | None | Databases, networks, cloud systems, security, and operations concepts are included where they serve CS; organization-specific IS/IT administration is a neighboring professional discipline under CC2020 boundaries. |
| vendor-certification-and-product-training | out-of-scope | None | The durable curriculum targets transferable models and decisions, not certification objectives or volatile product menus. |

## Deck sequence

Orders are topological identifiers, not a demand for linear completion. Hard
prerequisites license the target deck to assume the full declared outcome;
`recommended_after` entries improve readiness or fit a conventional sequence but
are not inherited knowledge.

| Order | Deck | Level | Tier | Hard prerequisites | Recommended after | Est. chapters | Durable capabilities | Status |
|---:|---|---|---|---|---|---:|---|---|
| 1 | programming-and-software-development-foundations | foundational | core | None | mathematics/elementary-algebra-and-functions | 14 | Build, trace, test, debug, document, and version small programs while explaining variables, control, functions, data, state, decomposition, and abstraction. | proposed |
| 2 | data-structures-and-program-design | undergraduate-core | core | programming-and-software-development-foundations | mathematics/discrete-mathematics-and-combinatorics | 10 | Choose, implement, test, and trace core data structures while maintaining representation invariants and designing modular programs around abstract interfaces. | proposed |
| 3 | computer-systems-foundations | undergraduate-core | core | programming-and-software-development-foundations | None | 10 | Translate among bits, data representations, logic, instructions, memory, processes, storage, and communication to explain how programs execute on layered machines. | proposed |
| 4 | software-engineering | undergraduate-core | core | programming-and-software-development-foundations | data-structures-and-program-design | 10 | Elicit requirements and collaboratively design, test, review, evolve, release, and maintain reliable software with explicit quality and process tradeoffs. | proposed |
| 5 | algorithm-design-and-analysis | undergraduate-core | core | data-structures-and-program-design, mathematics/discrete-mathematics-and-combinatorics | None | 12 | Design and justify algorithms with invariants, recurrences, graph models, paradigms, reductions, and precise worst-case, expected, and amortized analyses. | proposed |
| 6 | computer-architecture-and-organization | undergraduate-core | recommended | computer-systems-foundations | data-structures-and-program-design | 10 | Analyze instruction sets, datapaths, pipelining, memory hierarchies, I/O, and multicore organization to predict correctness and performance from programs to hardware. | proposed |
| 7 | operating-systems | undergraduate-core | recommended | computer-systems-foundations | computer-architecture-and-organization | 12 | Reason about processes, threads, scheduling, synchronization, virtual memory, files, I/O, protection, virtualization, recovery, and competing resource policies. | proposed |
| 8 | networks-and-communication | undergraduate-core | recommended | computer-systems-foundations | operating-systems | 10 | Trace layered protocols and packet paths while reasoning about naming, routing, transport, congestion, wireless links, measurement, failures, and end-to-end tradeoffs. | proposed |
| 9 | data-management-and-databases | undergraduate-core | recommended | data-structures-and-program-design | software-engineering | 10 | Model, query, index, transact over, recover, govern, and evaluate structured and semi-structured data with explicit integrity and performance guarantees. | proposed |
| 10 | programming-language-concepts | undergraduate-core | recommended | data-structures-and-program-design | mathematics/mathematical-reasoning-and-proof | 10 | Compare syntax, semantics, scope, types, evaluation, state, abstraction, modularity, and functional, object-oriented, and logic paradigms through small interpreters and traces. | proposed |
| 11 | human-computer-interaction | undergraduate-core | recommended | programming-and-software-development-foundations | software-engineering | 10 | Investigate people and contexts, prototype accessible interfaces, run ethical evaluations, and connect interaction evidence to defensible design decisions. | proposed |
| 12 | security-and-privacy-foundations | undergraduate-core | recommended | computer-systems-foundations | software-engineering, networks-and-communication | 10 | Model assets, adversaries, trust boundaries, vulnerabilities, cryptographic goals, authentication, authorization, privacy, risk, and layered defensive limits. | proposed |
| 13 | society-ethics-and-professional-practice | undergraduate-core | core | programming-and-software-development-foundations | software-engineering, human-computer-interaction, security-and-privacy-foundations | 8 | Analyze stakeholders, power, access, privacy, safety, bias, sustainability, law, evidence, professional duties, and sociotechnical consequences throughout a system life cycle. | proposed |
| 14 | artificial-intelligence-foundations | undergraduate-core | recommended | data-structures-and-program-design | algorithm-design-and-analysis, mathematics/probability, mathematics/linear-algebra, society-ethics-and-professional-practice | 12 | Formulate and evaluate intelligent-agent problems using search, constraint satisfaction, logic, probabilistic reasoning, planning, learning foundations, and responsible evaluation. | proposed |
| 15 | parallel-and-distributed-computing | undergraduate-advanced | specialization | algorithm-design-and-analysis, operating-systems, networks-and-communication | computer-architecture-and-organization | 12 | Design and analyze concurrent, parallel, and distributed programs under explicit memory, ordering, communication, synchronization, consistency, and failure models. | proposed |
| 16 | graphics-and-interactive-techniques | undergraduate-advanced | specialization | data-structures-and-program-design, mathematics/linear-algebra | algorithm-design-and-analysis, human-computer-interaction | 10 | Build and critique geometric, rendering, animation, visualization, and interaction pipelines while translating among scene, image, transformation, and perceptual representations. | proposed |
| 17 | compiler-construction-and-language-implementation | undergraduate-advanced | specialization | computer-systems-foundations, programming-language-concepts | computer-architecture-and-organization | 10 | Implement and test a language processor across lexing, parsing, semantic analysis, intermediate forms, optimization, code generation, runtime support, and diagnostics. | proposed |
| 18 | web-and-cloud-application-engineering | undergraduate-advanced | specialization | software-engineering, networks-and-communication, data-management-and-databases | security-and-privacy-foundations | 10 | Engineer observable, secure, accessible web and cloud applications across client, service, data, deployment, scaling, failure, and operations boundaries. | proposed |
| 19 | embedded-and-real-time-systems | undergraduate-advanced | specialization | computer-architecture-and-organization, operating-systems | networks-and-communication, physics/electronics-and-instrumentation | 10 | Design resource-constrained hardware-software systems with interrupts, peripherals, timing, real-time scheduling, concurrency, sensing, actuation, safety, and validation. | proposed |
| 20 | machine-learning-and-data-science | undergraduate-advanced | specialization | algorithm-design-and-analysis, mathematics/linear-algebra, mathematics/statistical-inference-and-data-analysis | artificial-intelligence-foundations, mathematics/optimization-and-operations-research | 12 | Acquire, clean, explore, model, validate, communicate, and govern data while diagnosing leakage, confounding, uncertainty, distribution shift, and social consequences. | proposed |
| 21 | cybersecurity-engineering | undergraduate-advanced | specialization | operating-systems, networks-and-communication, security-and-privacy-foundations | society-ethics-and-professional-practice | 12 | Threat-model, test, harden, monitor, and recover software, hosts, networks, and services while evaluating cryptographic, human, organizational, and risk controls. | proposed |
| 22 | robotics-and-autonomous-systems | undergraduate-advanced | specialization | computer-systems-foundations, artificial-intelligence-foundations, mathematics/probability, mathematics/differential-equations | embedded-and-real-time-systems, machine-learning-and-data-science | 10 | Integrate sensing, estimation, kinematics, control, planning, uncertainty, and safety to predict and evaluate autonomous behavior in physical environments. | proposed |
| 23 | information-retrieval-and-language-technologies | undergraduate-advanced | specialization | machine-learning-and-data-science | data-management-and-databases, artificial-intelligence-foundations | 10 | Represent, retrieve, rank, classify, and generate text and language data while evaluating relevance, meaning, bias, uncertainty, and human consequences. | proposed |
| 24 | computer-vision-and-visual-computing | undergraduate-advanced | specialization | machine-learning-and-data-science | artificial-intelligence-foundations, graphics-and-interactive-techniques | 10 | Form and test image and video representations for geometry, recognition, motion, and generation while tracing dataset, metric, robustness, and deployment limits. | proposed |
| 25 | high-performance-and-scientific-computing | undergraduate-advanced | specialization | parallel-and-distributed-computing, mathematics/numerical-analysis | computer-architecture-and-organization | 10 | Translate scientific models into validated numerical programs and reason about floating-point error, parallel decomposition, locality, scaling, performance, and reproducibility. | proposed |
| 26 | computer-science-research-methods | graduate | core | society-ethics-and-professional-practice | software-engineering, algorithm-design-and-analysis, mathematics/statistical-inference-and-data-analysis | 10 | Search, read, reproduce, design, measure, review, write, and present computer-science research while matching claims to proof, empirical, systems, human-subjects, reproducibility, and ethical standards. | proposed |
| 27 | advanced-algorithms-and-complexity | graduate | specialization | algorithm-design-and-analysis, mathematics/probability, mathematics/theory-of-computation-and-complexity | computer-science-research-methods, mathematics/optimization-and-operations-research | 10 | Develop advanced exact, approximation, online, randomized, algebraic, and parameterized algorithms and connect reductions and lower bounds to complexity assumptions. | proposed |
| 28 | advanced-programming-languages-and-formal-methods | graduate | specialization | programming-language-concepts, mathematics/mathematical-logic-and-computability | compiler-construction-and-language-implementation, computer-science-research-methods | 10 | Use operational and denotational semantics, type systems, logics, model checking, theorem proving, and verified transformations to specify and reason about programs. | proposed |
| 29 | advanced-systems-and-distributed-computing | graduate | specialization | parallel-and-distributed-computing | data-management-and-databases, cybersecurity-engineering, computer-science-research-methods | 12 | Analyze advanced operating, storage, networked, and distributed systems through concurrency, fault tolerance, consensus, consistency, virtualization, measurement, and scale. | proposed |
| 30 | advanced-ai-and-machine-learning | graduate | specialization | artificial-intelligence-foundations, machine-learning-and-data-science, mathematics/optimization-and-operations-research | computer-science-research-methods | 12 | Derive, implement, and critique modern probabilistic, representation-learning, generative, sequential-decision, and foundation-model methods under rigorous evaluation. | proposed |
| 31 | human-centered-computing-research-methods | graduate | specialization | human-computer-interaction, computer-science-research-methods, mathematics/statistical-inference-and-data-analysis | machine-learning-and-data-science | 10 | Design and critique qualitative, quantitative, mixed-method, participatory, accessibility, and field research on people interacting with computing systems. | proposed |
| 32 | advanced-security-and-privacy | graduate | specialization | cybersecurity-engineering, computer-science-research-methods | None | 10 | Analyze modern cryptography, systems and network security, privacy technologies, side channels, usable security, formal assurance, and adversarial evaluation. | proposed |
| 33 | advanced-data-systems-and-information-retrieval | graduate | specialization | data-management-and-databases, information-retrieval-and-language-technologies, computer-science-research-methods | advanced-systems-and-distributed-computing | 10 | Study scalable data engines, learned and distributed data systems, retrieval and recommendation, provenance, governance, and evaluation across changing workloads. | proposed |
| 34 | advanced-robotics-and-perception | graduate | specialization | robotics-and-autonomous-systems, computer-vision-and-visual-computing, advanced-ai-and-machine-learning, computer-science-research-methods | embedded-and-real-time-systems | 10 | Integrate probabilistic perception, mapping, planning, learning, control, embodiment, human interaction, safety, and experimental validation in autonomous systems. | proposed |
| 35 | advanced-parallel-and-high-performance-computing | graduate | specialization | high-performance-and-scientific-computing, advanced-systems-and-distributed-computing, computer-science-research-methods | None | 10 | Design and evaluate advanced multicore, accelerator, cluster, and heterogeneous computations using performance models, numerical fidelity, communication, scheduling, and reproducibility. | proposed |
| 36 | algorithms-and-complexity-research | research-specialization | specialization | computer-science-research-methods, advanced-algorithms-and-complexity | None | 8 | Read and critique frontier algorithms and complexity research by reconstructing models, proof ideas, reductions, bounds, assumptions, and open-problem structure. | proposed |
| 37 | programming-languages-and-software-research | research-specialization | specialization | computer-science-research-methods, advanced-programming-languages-and-formal-methods | None | 8 | Evaluate frontier language, verification, program-analysis, synthesis, and software-engineering claims using formal guarantees, artifacts, benchmarks, and human evidence. | proposed |
| 38 | scalable-systems-and-networking-research | research-specialization | specialization | computer-science-research-methods, advanced-systems-and-distributed-computing | None | 8 | Interrogate research on operating, networked, storage, cloud, edge, and distributed systems through models, prototypes, workloads, fault injection, and reproducible measurement. | proposed |
| 39 | trustworthy-ai-and-learning-systems-research | research-specialization | specialization | computer-science-research-methods, advanced-ai-and-machine-learning | None | 8 | Critique frontier AI and learning systems through data provenance, scaling, evaluation validity, robustness, interpretability, privacy, safety, governance, and social impact. | proposed |
| 40 | human-ai-interaction-and-accessible-computing-research | research-specialization | specialization | advanced-ai-and-machine-learning, human-centered-computing-research-methods | None | 8 | Investigate human-AI collaboration, agency, explanation, accessibility, participation, deployment, and longitudinal effects with defensible technical and human evidence. | proposed |
| 41 | security-and-privacy-research | research-specialization | specialization | advanced-security-and-privacy | None | 8 | Assess frontier security and privacy research by matching attacker, asset, trust, proof, experiment, disclosure, and deployment claims to the evidence provided. | proposed |
| 42 | data-management-and-information-retrieval-research | research-specialization | specialization | advanced-data-systems-and-information-retrieval | None | 8 | Read research on data systems, retrieval, recommendation, and information quality through workload assumptions, system design, relevance evidence, governance, and reproducibility. | proposed |
| 43 | embodied-ai-and-robotics-research | research-specialization | specialization | advanced-robotics-and-perception | None | 8 | Critique embodied-AI and robotics research across perception-action loops, simulation and reality, benchmarks, safety cases, human contexts, hardware limits, and field evidence. | proposed |
| 44 | high-performance-and-scientific-computing-research | research-specialization | specialization | advanced-parallel-and-high-performance-computing | None | 8 | Evaluate frontier architectures, programming systems, simulations, and scientific workflows through performance portability, numerical trust, scaling evidence, energy, and reproducibility. | proposed |
| 45 | quantum-algorithms-and-computing-research | research-specialization | specialization | computer-science-research-methods, advanced-algorithms-and-complexity, physics/quantum-information-and-computation | None | 8 | Analyze quantum algorithms, complexity, programming, compilation, error correction, resources, and advantage claims using both computational and physical models. | proposed |

## Sequencing, coherence, and false-prerequisite audit

### Layered routes

1. **Entry:** `programming-and-software-development-foundations` starts from no
   confirmed CS knowledge and includes the execution, testing, debugging,
   documentation, shell/tool, and version-control bridge needed by later decks.
2. **Shared undergraduate spine:** data structures, systems, software engineering,
   algorithms, and professional practice establish capabilities used by several
   branches. Architecture, OS, networks, databases, language concepts, HCI,
   security, and AI are recommended breadth with hard edges only where later work
   truly assumes them.
3. **Upper-division branches:** systems, graphics, compilers, platforms, ML/data,
   security, robotics, language technologies, vision, and HPC have different source
   registers, representations, laboratories, and capstones; they remain distinct.
4. **Graduate foundations:** `computer-science-research-methods` is branch-neutral;
   nine technical/method graduate decks supply the formal, empirical, or systems
   maturity needed by their research descendants.
5. **Research specializations:** each literature-facing deck has both research
   practice and an advanced technical base in its direct prerequisite closure.

### Coherence decisions

- Introductory programming and everyday development tools are merged at the
  14-chapter upper bound because tools, testing, debugging, and version control are
  part of one small-program performance. Data structures split off when abstract
  interfaces, invariants, and larger designs become a new course-scale capability.
- The systems sequence is split into machine foundations, architecture, OS,
  networks, concurrency/distribution, and embedded/HPC branches. An “all systems”
  deck would exceed 14 chapters and force unrelated prerequisites and capstones.
- AI foundations does **not** hard-require ML/data science, the complete
  algorithm-design course, or a calculus-based probability course: data structures
  are sufficient, and its opening units establish the bounded search and
  conditional-probability bridges they use.
  ML/data science independently requires algorithms, linear algebra, and statistics;
  advanced AI is where the two routes intentionally converge.
- Graphics likewise needs data structures and linear algebra, not every algorithm
  paradigm and proof technique; algorithm design is recommended preparation. In the
  other direction, graphics is recommended, not required, before vision because
  image inference can be learned without a rendering course.
- Databases and broad AI are recommended, not required, before information
  retrieval/language technologies because that course can establish its bounded
  storage and agent context without assuming either complete survey.
- Web/cloud, embedded/real-time, and robotics are not combined as “specialized
  platforms”: their constraints, representation grammars, laboratories, and final
  performances are independent.
- Service-oriented distributed systems and numerical HPC share concurrency but
  split because their correctness evidence, workload models, numerical issues, and
  performance capstones differ.
- No separate local discrete mathematics, statistics, numerical analysis, or
  quantum-information bridge is created. The global catalog already supplies each
  broad capability. The receiving CS deck must teach the **contextual transfer**—for
  example, turning a graph theorem into an algorithmic invariant or a statistical
  estimand into an ML evaluation—inside its opening chapters. That transfer is too
  narrow to justify another 6–14 chapter deck.

### Reused external capabilities

| External capability | Use in this roadmap | Why hard versus recommended |
|---|---|---|
| mathematics/discrete-mathematics-and-combinatorics | algorithm-design-and-analysis | Hard: proof, recurrences, graphs, trees, and counting are freely used from chapter 1. Recommended for data structures, which can teach its needed finite structures operationally. |
| mathematics/probability | AI foundations; robotics; advanced algorithms | Recommended for introductory AI, which needs only a bounded conditional-probability bridge; hard for robotics estimation and graduate randomized analysis, where the complete capability is working language. |
| mathematics/linear-algebra | graphics, ML/data science, robotics | Hard where vectors, matrices, transformations, and decompositions are working representations; merely recommended for broad AI foundations. |
| mathematics/statistical-inference-and-data-analysis | ML/data science; human-centered-computing research methods; computer-science research methods | Hard for ML/data science and quantitative human research, where sampling, uncertainty, regression, effect size, and inferential limits may be assumed; recommended for the branch-neutral research-methods course. |
| mathematics/differential-equations | robotics-and-autonomous-systems | Hard for dynamical models and control; the robotics deck owns translation into sensing and actuation. |
| mathematics/numerical-analysis | high-performance-and-scientific-computing | Hard for floating-point, conditioning, stability, and validation; the CS deck owns implementation and scaling. |
| mathematics/optimization-and-operations-research | advanced-ai-and-machine-learning | Hard for objective, constraint, duality, and iterative-optimization maturity; recommended for introductory ML/data science. |
| mathematics/theory-of-computation-and-complexity | advanced-algorithms-and-complexity | Hard because automata, reductions, decidability, and standard complexity classes are assumed rather than duplicated. |
| mathematics/mathematical-logic-and-computability | advanced-programming-languages-and-formal-methods | Hard for formal syntax, deduction, models, computability, and soundness/completeness language. |
| physics/quantum-information-and-computation | quantum-algorithms-and-computing-research | Hard graduate base for qubits, channels, measurement, circuits, algorithms, error correction, and physical limitations. The CS research deck adds algorithms/complexity/language/systems critique. |
| physics/electronics-and-instrumentation | embedded-and-real-time-systems | Recommended only: useful laboratory preparation, but the CS course can provide bounded peripheral and signal bridges without making a full physics instrumentation course mandatory. |

## Graduate and research maturity-transition audit

Every row states what the first chapter may assume and how the complete direct
prerequisite closure establishes it. Anything else must be taught before use.

| Deck | First-chapter technical and representational assumptions | Closure check |
|---|---|---|
| computer-science-research-methods | Small tested/versioned programs and artifacts plus stakeholder and research-ethics judgment. Team-scale software engineering, formal proof technique, statistical inference, literature search, paper anatomy, peer review, and research design are **not** assumed. | society-ethics-and-professional-practice closes over the foundational programming/tool deck and supplies duties and sociotechnical analysis. The deck teaches literature, method selection, reproducibility, and communication, while branch-specific prerequisites supply software, proof, or statistical depth. This avoids false software-engineering and statistics prerequisites for theory research. |
| advanced-algorithms-and-complexity | Mathematical proofs, graph/recurrence representations, asymptotic and randomized analysis, automata/Turing models, reductions, and complexity classes. | algorithm-design-and-analysis supplies design/proof/analysis; mathematics/probability supplies random variables and expectation; mathematics/theory-of-computation-and-complexity supplies formal machines, decidability, reductions, and complexity. Research conventions are not assumed, so research methods remains recommended. |
| advanced-programming-languages-and-formal-methods | Abstract syntax, environments/stores, evaluation traces, types, interpreters, formal languages, deduction, models, computability, soundness, and completeness. | programming-language-concepts supplies language representations and interpreters; mathematics/mathematical-logic-and-computability supplies the formal logic and computability grammar. Compiler construction and research methods are useful but not logically required by chapter 1. |
| advanced-systems-and-distributed-computing | Processes/threads, synchronization, memory and failure models, packet/protocol traces, graph algorithms, concurrency histories, consistency, and partial failure. | parallel-and-distributed-computing closes over OS, networks, algorithms, data structures, systems foundations, programming, and discrete mathematics, and itself establishes ordering/communication/failure representations. Sufficient despite skipping a separate immediately preceding systems survey. |
| advanced-ai-and-machine-learning | Search/planning/probabilistic-agent models; vectors, matrices, probability, statistical estimation and evaluation; supervised/unsupervised models; objectives, constraints, gradients, and optimization diagnostics. | AI foundations supplies symbolic/probabilistic AI; ML/data science closes over algorithms, linear algebra, probability/statistics, data practice, and evaluation; optimization supplies the mathematical optimization layer. Research methods is recommended because chapter 1 need not assume literature practice. |
| human-centered-computing-research-methods | Interface/prototype representations, usability/accessibility concepts, study questions, sampling and uncertainty, research ethics, reproducible artifacts, and critical paper reading. | HCI supplies design and basic ethical evaluation; statistical-inference supplies quantitative inference; computer-science-research-methods supplies literature, study-design, reproducibility, and ethics practice. The deck adds qualitative, mixed, participatory, and field methods before independent use. |
| advanced-security-and-privacy | Threat/asset/trust models; OS and protocol traces; authentication/authorization; cryptographic goals; vulnerability testing; empirical and formal research evidence; responsible disclosure and ethics. | cybersecurity-engineering closes over OS, networks, systems, and security foundations; computer-science-research-methods supplies method selection, reproducibility, literature, communication, and ethics conventions. Formal or empirical techniques are introduced before use. No undergraduate survey-to-literature jump remains. |
| advanced-data-systems-and-information-retrieval | Relational/query/index/transaction models; ranking and language representations; ML/statistical evaluation; experimental workloads, provenance, reproducibility, and paper critique. | databases supplies data-system guarantees; information-retrieval-and-language-technologies closes over ML, statistics, linear algebra, algorithms, and programming; research methods supplies literature and experimental practice. Advanced distributed systems is useful, not necessary for the first chapter. |
| advanced-robotics-and-perception | Coordinate frames, dynamical/control models, probabilistic estimation, search/planning, image/ML representations, optimization, experimental design, safety, and reproducibility. | robotics supplies systems, AI, linear algebra, differential equations, planning/control; vision supplies ML/statistical image inference; advanced AI supplies optimization and modern learning; research methods supplies experimental and ethical practice. Complete closure supports the level jump. |
| advanced-parallel-and-high-performance-computing | Parallel/distributed execution histories; numerical conditioning/error; performance and scaling models; advanced systems failures; reproducible benchmarks and scientific claims. | HPC supplies PDC and numerical-analysis closure; advanced systems supplies scale/fault/system models; research methods supplies measurement, reproducibility, and literature conventions. Sufficient graduate foundation for heterogeneous and accelerator work. |
| algorithms-and-complexity-research | Advanced algorithms, reductions, upper/lower bounds, probabilistic arguments, formal proof reading, literature search, scholarly writing, and open-question framing. | advanced algorithms supplies the full technical language; research methods supplies literature, review, reproducibility where relevant, communication, and ethics. No missing advanced theory layer. |
| programming-languages-and-software-research | Semantics, type/logical judgments, verification artifacts, program-analysis benchmarks, tested software, empirical and formal evidence, and literature conventions. | advanced PL/formal methods supplies formalism; research methods closes over software engineering and supplies empirical design, artifact evaluation, review, writing, and ethics. Compiler construction is not falsely required. |
| scalable-systems-and-networking-research | Distributed histories, fault and consistency models, OS/network/storage mechanisms, workloads, prototypes, measurement design, artifact reproduction, and paper critique. | advanced systems closes over PDC, OS, networks, algorithms, and systems foundations; research methods supplies experimental framing, reproducibility, and literature practice. Statistical claims must be introduced before use. Complete technical and research layers are present. |
| trustworthy-ai-and-learning-systems-research | Advanced learning/probabilistic/generative models, optimization, datasets and statistical evaluation, robustness and social-risk vocabulary, reproducible experiments, and research critique. | advanced AI closes over AI, ML/data science, linear algebra, statistics, algorithms, and optimization; research methods supplies study validity, literature, reproducibility, communication, and ethics. Sufficient for literature-facing work. |
| human-ai-interaction-and-accessible-computing-research | Advanced AI model/evaluation representations plus qualitative, quantitative, participatory, accessibility, deployment, and longitudinal human-research methods. | advanced AI supplies technical model maturity; human-centered-computing-research-methods already closes over HCI and research methods/statistics/ethics. Adding research methods directly would be redundant. |
| security-and-privacy-research | Advanced cryptographic, systems, network, privacy, side-channel, usable-security, and assurance models together with adversarial experiments, literature, disclosure, and ethics. | advanced-security-and-privacy already hard-requires cybersecurity engineering and research methods, so its closure supplies both advanced technical and research-practice layers. No extra edge is needed. |
| data-management-and-information-retrieval-research | Advanced data-engine, retrieval, recommendation, workload, relevance, provenance, governance, statistical-evaluation, and research representations. | advanced-data-systems-and-information-retrieval already closes over databases, IR/language, ML/statistics, and research methods. The single direct edge is sufficient and minimal. |
| embodied-ai-and-robotics-research | Graduate perception, learning, mapping, planning, control, embodiment, safety, hardware/field experiments, reproducibility, and literature critique. | advanced-robotics-and-perception closes over robotics, vision, advanced AI, mathematics, systems, and research methods. The first chapter need not backfill an undergraduate survey or research-method layer. |
| high-performance-and-scientific-computing-research | Graduate parallel/heterogeneous models, numerical trust, performance portability, scaling/energy experiments, scientific reproducibility, and paper/artifact evaluation. | advanced parallel/HPC closes over undergraduate HPC, advanced systems, numerical analysis, PDC, and research methods. The single edge is both sufficient and minimal. |
| quantum-algorithms-and-computing-research | Advanced classical algorithms/complexity; qubit, state, measurement, circuit, channel, entropy, error-correction, and hardware representations; literature/reproducibility conventions. | advanced algorithms supplies classical theory; physics/quantum-information-and-computation supplies the graduate quantum formalism and physical limits; research methods supplies literature and evidence practice. This justified cross-subject closure prevents an undergraduate-to-quantum-research jump. |

## Cross-deck concepts

- **Abstraction and representation:** values → data structures → interfaces →
  instruction/memory models → protocols → formal semantics → research models.
- **State and transition:** program traces, machine state, processes, transactions,
  protocols, distributed histories, agent states, dynamical systems, and experiments.
- **Invariant, specification, and guarantee:** representation invariants, loop and
  proof invariants, type and interface contracts, consistency/security properties,
  statistical assumptions, and research claims.
- **Cost and resources:** time/space, amortization, latency/throughput, communication,
  energy, numerical error, data/compute budgets, human effort, and environmental cost.
- **Uncertainty and failure:** exceptions and bugs, nondeterminism, partial failure,
  adversaries, sampling uncertainty, distribution shift, human variability, and
  threats to validity.
- **Evidence and evaluation:** tests, proofs, counterexamples, traces, benchmarks,
  measurements, user studies, statistical inference, replications, and peer review.
- **Responsibility:** privacy, security, accessibility, fairness, power, safety,
  sustainability, professional duty, governance, and affected-community participation
  must recur inside technical contexts rather than appear only in deck 13.
- **Authentic representations:** prose, code, pseudocode, equations, graphs/trees,
  memory diagrams, automata, packet and timing diagrams, database schemas/query
  plans, execution histories, geometric scenes/images, datasets/plots, threat
  models, study protocols, and research papers/artifacts.

## Practice outside SRS

Every route needs substantial non-card work. The foundational route requires frequent
programming, execution, testing, debugging, source control, and small projects.
Algorithms and theory require original proof and counterexample writing. Systems,
networks, security, embedded, robotics, graphics, data, AI, and HPC require
laboratories, profiling/measurement, failure injection, datasets or hardware, and
open-ended projects. HCI and human-centered routes require ethical participant-facing
research and design iteration. Graduate and research routes require paper reading,
replication, artifact evaluation, seminars, peer review, technical writing, and a
sustained supervised investigation. SRS supports durable access to models and
decisions; it cannot certify engineering or research competence.

## Future extension points

Deferred does not mean prohibited. Learner interest and new owning-domain
capabilities can add mobile/ubiquitous/XR, computing education research,
bioinformatics or health computing, games, computational social science, digital
humanities, geospatial computing, fintech, or other applied routes without renaming
approved deck IDs. Any extension must repeat the domain map, course-coherence test,
external-capability reuse check, and maturity-transition audit before it becomes an
executable branch.
