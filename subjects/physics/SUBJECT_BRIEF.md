# Physics subject brief

This file records decisions specific to this learner and collection. Reusable
domain-wide authoring guidance belongs in `templates/guides/physics.md`
when that maintained guide exists, or in this subject's `DOMAIN_GUIDE.md` for a
new domain. The explained deck sequence belongs in `ROADMAP.md`; its executable
curriculum belongs in `subject.toml`.

## Learner and destination

- Intended learner: not specified by the request. The curriculum is designed for
  a learner starting from **first contact with physics** — no confirmed physics
  vocabulary of any kind — who wants a navigable map of the whole field rather
  than one course. **Needs confirmation:** whether this learner is a self-studier,
  a student shadowing formal coursework, or a professional re-entering the field.
  The deck graph does not depend on the answer, but chapter register and
  worked-example choice do.
- Current mathematical/tool mastery: **unconfirmed, therefore treated as none.**
  The roadmap consequently imports every mathematical capability explicitly from
  the `mathematics` subject rather than assuming it. If the learner confirms
  existing mathematics mastery, the corresponding external prerequisite edges are
  satisfied immediately without any change to this roadmap.
- Current domain mastery: none unless explicitly confirmed here. Nothing is
  confirmed. Force, energy, velocity, vectors, fields, and oscillators are all
  treated as unseen technical vocabulary, not as common knowledge.
- Requested destination and use horizon: **whole-field**. The route must map the
  major domains and contemporary branches of physics across learning levels,
  from pre-calculus literacy through representative graduate and
  research-specialization branches, with deliberate future extension points.
  Destination controls the current route, not a ceiling: later extensions may add
  branches without renaming or deleting approved decks.
- Graduate or research focus branches: **none specified.** Because no focus slug
  was supplied, the roadmap terminates in seven *representative* research
  branches chosen from evidence of current field activity (see evidence
  authorities below), not from preference. **Needs confirmation:** if the learner
  has a real target subfield, that branch should be promoted and the others
  demoted to `deferred` rather than all seven being pursued.
- Deck granularity: **course**. One deck is one coherent course-scale capability,
  planning-estimated at 6–14 ordered chapters.
- Durable capabilities: describe and measure physical situations with explicit
  units, uncertainty, and stated idealizations; choose a system, frame, and sign
  convention; predict qualitatively before calculating; select among competing
  physical models and state each model's regime of validity; translate among
  situations, diagrams, graphs, words, equations, and code; reason about
  evidence, systematic error, and what data can and cannot support; and navigate
  the contemporary literature of at least one research branch. At the research
  layer this includes provenance-aware, critical use of AI-assisted tools rather
  than treating generated text, code, or analysis as evidence.
- Deliberate exclusions: accelerator and beam physics, medical physics, physics of
  climate and Earth systems, geophysics/space/atmospheric physics, energy science
  and technology, chemical physics, quantum gravity and string theory, and the
  history and philosophy of physics are **deferred** — visible future extension
  points, not judgments about the learner. Physics education research and the
  general theory of networks and complex systems are **out of scope** for this
  subject; `ROADMAP.md` records where each is handled instead.

## Conventions and boundaries

- Preferred notation, terminology, language, or jurisdiction: SI units
  throughout, using the post-2019 SI in which the base units are fixed by exact
  defining constants. Prefer BIPM/IUPAP symbol conventions. English. Where a
  convention is genuinely not universal — the metric signature, the sign of the
  Fourier kernel, the direction of the thermodynamic work convention, the
  handedness of a coordinate system — the card must state its choice rather than
  assume one.
- Simplifications that must be labeled: point-particle and rigid-body
  idealizations; frictionless, inviscid, incompressible, and non-relativistic
  limits; the ideal-gas and harmonic approximations; mean-field treatments;
  semiclassical light–matter models; single-particle band theory; the Bohr atom
  as a superseded model retained for historical and heuristic use; and every
  perturbative expansion. Each is introduced with its regime of validity and at
  least one breakdown case.
- Claims requiring current verification: values and uncertainties of physical
  constants (CODATA/NIST at authoring time); particle properties and limits
  (Particle Data Group); astronomical and cosmological parameters (the current
  mission data release, not a textbook table); gravitational-wave catalog
  contents and event counts; fusion energy-gain records; and any claim about
  "the current state" of a research frontier. These decay quickly and must carry
  an access date in the deck source register.
- Accessibility or device constraints: **needs confirmation.** Assume phone-width
  study by default. Figures must be legible at phone width, must not rely on
  color alone, and must carry meaningful alt text that does not leak the answer.
  Mathematics renders through KaTeX, so notation must stay within KaTeX support.

Do not infer domain knowledge from the target level. Anything not explicitly
confirmed above is treated as unseen during cold-start review.

## Evidence authorities

- Consensus or professional frameworks:
  - APS **PhySH** (Physics Subject Headings), the current successor to PACS,
    used as the authoritative map of the field's disciplines and research areas —
    https://physh.org (accessed 2026-08-17; vocabulary released CC0 1.0, concepts
    carry DOIs under `10.29172/`).
  - APS **divisions and topical groups**, used as a current community-structure
    check rather than a course sequence — https://www.aps.org/membership/units
    (accessed 2026-08-17; APS website terms, no open content license asserted).
  - **QAA Subject Benchmark Statement: Physics, Astronomy and Astrophysics**
    (published 2025-04-07), the newest broad outcome framework consulted —
    https://www.qaa.ac.uk/docs/qaa/sbs/subject-benchmark-statement-physics-astronomy-and-astrophysics-2025.pdf
    (accessed 2026-08-17; © QAA, no open license asserted). It confirms the common
    fundamental areas and makes experiment, computation, data visualization,
    professional practice, accessibility, sustainability, and critical ethical
    use of generative AI explicit curriculum concerns.
  - **Phys21: Preparing Physics Students for 21st-Century Careers**, the APS/AAPT
    Joint Task Force on Undergraduate Physics Programs report —
    https://www.compadre.org/jtupp/docs/J-Tupp_Report.pdf (accessed 2026-08-06;
    **CC BY 4.0**, so it may be quoted and adapted with attribution).
  - **AAPT Recommendations for the Undergraduate Physics Laboratory Curriculum**
    (Board-endorsed 2014-11-10) —
    https://www.aapt.org/resources/upload/labguidlinesdocument_ebendorsed_nov10.pdf
    (accessed 2026-08-06; © AAPT, no open license — use the outcomes, do not copy prose).
  - **AAPT Recommendations for Computational Physics in the Undergraduate Physics
    Curriculum** (Undergraduate Curriculum Task Force, 2016) —
    https://www.aapt.org/resources/upload/aapt_uctf_compphysreport_final_b.pdf
    (accessed 2026-08-17 through AAPT's current undergraduate-curriculum index;
    © AAPT).
  - **IOP Degree Accreditation Framework, July 2022** (current in 2026) —
    https://www.iop.org/sites/default/files/2022-09/IOP-Degree-Accreditation-Framework-July-2022.pdf
    (accessed 2026-08-17; © IOP). The current IOP accreditation page still links
    this July 2022 framework. The IOP's older prescriptive "Core of Physics" is
    explicitly no longer in use and must not be cited as a mandated syllabus.
  - APS/AAPT **EP3 Guide** (Effective Practices for Physics Programs), for its
    ethics, computational-skills, undergraduate-research, and capstone sections —
    https://ep3guide.org/ (accessed 2026-08-06; the site returned HTTP 403 to
    automated fetch and section titles were confirmed only indirectly —
    **re-verify manually** before citing any specific text).
  - APS **Guidelines for Professional Conduct**, for research results and data
    retention, publication and authorship, peer review, and conflict of interest —
    https://www.aps.org/about/governance/statements/guidelines-professional-conduct
    (accessed 2026-08-06; returned HTTP 403 to automated fetch — **re-verify the
    current revision manually**; a widely repeated "October 2025 update" could not
    be confirmed and must not be asserted as fact).
- Preferred primary sources or public agencies:
  - NIST/CODATA fundamental constants — https://physics.nist.gov/cuu/Constants/
  - BIPM SI Brochure — https://www.bipm.org/en/publications/si-brochure
  - Particle Data Group, *Review of Particle Physics* — https://pdg.lbl.gov/
  - NSF Division of Physics program areas, as a breadth check —
    https://www.nsf.gov/mps/physics (accessed 2026-08-17; US Government work,
    public domain). The live program list includes AMO, elementary-particle,
    gravitational, nuclear, particle-astrophysics, living-systems, plasma, quantum
    information, and cross-cutting instrumentation and information-frontier work.
  - US National Academies decadal and strategic reports, used to choose
    representative research branches (all accessed 2026-08-06 via
    nationalacademies.org / nap.nationalacademies.org): Astro2020 *Pathways to
    Discovery in Astronomy and Astrophysics for the 2020s*; *Elementary Particle
    Physics: The Higgs and Beyond* (EPP-2024, published 2025); the 2023 P5 report
    *Exploring the Quantum Universe*; the 2023 NSAC *Long Range Plan for Nuclear
    Science*; the 2021 plasma decadal *Plasma Science: Enabling Technology,
    Sustainability, Security, and Exploration*; the 2022 *Physics of Life*
    report; and the 2020 AMO decadal *Manipulating Quantum Systems*.
  - NASEM, *Reproducibility and Replicability in Science* (2019), for the
    operative distinction the research-practice deck must encode —
    https://nap.nationalacademies.org/catalog/25303/ (accessed 2026-08-06).
  - arXiv category taxonomy and submission statistics, as a reality check on
    where the field's activity actually is — https://arxiv.org/category_taxonomy
    and https://info.arxiv.org/about/reports/submission_category_by_year.html
    (accessed 2026-08-17; taxonomy metadata CC0; the submission report is a
    dynamic descriptive source, so no exact volume ranking is used as a deck or
    dependency criterion).
  - **Current graduate-transition checks** (curriculum metadata only, not content
    sources): MIT's January 2026 doctoral guidelines and graduate requirements —
    https://physics.mit.edu/academic-programs/graduate-students/doctoral-guidelines/
    and https://physics.mit.edu/academic-programs/graduate-students/information-on-graduate-course-requirements/;
    Berkeley's Fall 2026 preliminary-examination structure —
    https://physics.berkeley.edu/node/833; and Cambridge Part III preparation for
    relativity and high-energy physics —
    https://www.maths.cam.ac.uk/postgrad/part-iii/prospective/preparation/resources/relativity-and-gravitation
    and https://www.maths.cam.ac.uk/postgrad/part-iii/node/70 (all accessed
    2026-08-17; institutional website terms, no open license asserted). These
    sources corrected the prior claim that advanced classical mechanics is
    generally absent from graduate cores and verified the formalism expected at
    the GR and QFT transitions.
- Open educational sources and license constraints:
  - **PhysPort** research-based teaching methods — https://www.physport.org/
    (accessed 2026-08-06; © AAPT, all rights reserved — use for design decisions,
    do not reproduce).
  - **OpenStax** physics titles — https://openstax.org/subjects/science — openly
    licensed, but the exact license and edition **must be re-checked per title**
    at authoring time before any reuse.
  - **PICUP** computational exercise collection — https://www.compadre.org/PICUP/
    (accessed 2026-08-06; © AAPT/ComPADRE, all rights reserved).
  - Policy: free access is not permission. No proprietary textbook prose or
    figures. All technical figures are original TikZ compiled to SVG.

## Authentic practice outside SRS

Spaced retrieval maintains concepts, representations, and method triggers. It
cannot produce physics competence on its own. This subject explicitly depends on:

- **Laboratory work.** The six AAPT laboratory outcomes — constructing knowledge,
  modeling, designing experiments, developing technical and practical skills,
  analyzing and visualizing data, and communicating physics — require real
  apparatus, real troubleshooting, and real failure. Cards can maintain the
  reasoning; they cannot substitute for aligning an interferometer or chasing
  down a ground loop.
- **Extended multi-step problems.** Long synthesis problems, full derivations,
  and qualifying-exam-style problem sets stay outside SRS; fragmenting them into
  cards destroys the skill they build.
- **Computation as a practice, not a topic.** AAPT is explicit that computation
  should be introduced in the introductory course and reinforced throughout, and
  that relying entirely on a dedicated computational course is not sufficient.
  Every deck from `computational-physics` onward should carry accompanying code
  work — simulation, numerical solution, data reduction, visualization — done
  outside the card set.
- **Estimation and Fermi problems** worked aloud or on paper.
- **Reading the literature.** Preprint reading, journal club, and referee-style
  critique are the actual entry to any research branch.
- **Scientific writing and speaking.** Lab reports, a paper draft, a poster, a
  talk, and teaching an idea to someone else (Phys21 §C).
- **Instrumentation and shop practice.** Electronics, vacuum, optics, cryogenics,
  sensors, and data acquisition (Phys21 §B.3). The
  `electronics-and-instrumentation` deck maintains the coherent signal-chain
  concepts; hands-on vacuum, cryogenic, machining, alignment, and safety
  competence requires apparatus practice and may later justify technique-specific
  decks rather than one miscellaneous repository.
- **Professional practice.** Teamwork, project management, safety culture, and
  research ethics including authorship, peer review, conflict of interest, and
  data retention (Phys21 §D; APS Guidelines for Professional Conduct).
