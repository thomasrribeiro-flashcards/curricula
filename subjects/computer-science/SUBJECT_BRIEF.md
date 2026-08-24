# Computer Science subject brief

This file records learner-specific assumptions and collection decisions. Reusable
computer-science authoring guidance remains in the supplied domain guide; the
explained curriculum is in `ROADMAP.md`, and the executable graph is in
`subject.toml`.

## Learner and destination

- Intended learner: an interested cold-start learner; no age, credential,
  institution, profession, or prior exposure has been confirmed.
- Current mathematical/tool mastery: unconfirmed. The roadmap therefore imports
  named mathematics or physics capabilities only where they are genuinely hard
  prerequisites and otherwise marks them as recommended preparation.
- Current domain mastery: none confirmed. Programming, command-line use, source
  control, proof, data analysis, and research-literature skills are all treated as
  unseen until established by a declared prerequisite.
- Requested destination and use horizon: `whole-field`—a layered, navigable map
  from first contact through representative graduate and research routes. This is
  the current route, not a statement about the learner and not a permanent ceiling.
- Graduate or research focus branches: none specified. The roadmap samples major
  theory, software, systems, AI, human-centered, security, data, robotics, HPC, and
  quantum routes without claiming to enumerate every active microfield.
- Deck granularity: `course`; every proposed deck is estimated at 6–14 coherent
  chapters.
- Durable capabilities: explain abstractions and their limits; read, write, test,
  and debug programs; trace state and maintain invariants; select and analyze
  algorithms and representations; reason across software, systems, data, networks,
  people, and threats; evaluate evidence and tradeoffs; and enter selected research
  literatures with adequate mathematical, experimental, and professional practice.
- Deliberate exclusions: vendor certification syllabi, rapidly expiring API or
  product trivia, electrical-engineering depth in device fabrication, enterprise
  information-systems administration as a separate profession, and exhaustive
  coverage of every application domain. Visible deferred extensions remain in the
  roadmap.

### Decisions needing learner confirmation

The proposal is usable without answers, but these genuinely personal choices must
not be inferred:

1. preferred first programming language and execution environment;
2. confirmed mathematics, programming, and command-line mastery that could shorten
   the cold-start route;
3. accessibility needs, study-device constraints, and preferred human language;
4. preferred research or professional branches, desired depth, and available time;
5. whether the learner wants hardware laboratories, team projects, or cloud costs
   included in later deck-local contracts.

Until confirmed, deck builders must use platform-neutral concepts, low-cost local
tools where practical, accessible text/code/diagram conventions, and explicit
bridges from no computer-science knowledge.

## Conventions and boundaries

- Preferred notation, terminology, language, or jurisdiction: English prose and
  conventional mathematical/pseudocode notation are provisional defaults pending
  confirmation. Code language, language version, operating system, legal
  jurisdiction, and accessibility profile must be fixed in each deck before cards
  are authored when they affect correctness.
- Simplifications that must be labeled: abstract machine and network models;
  asymptotic cost models; deterministic examples of concurrent or distributed
  behavior; idealized threat and failure models; statistical/ML assumptions;
  hardware timing and memory hierarchies; and social claims that do not transfer
  uniformly across populations or jurisdictions.
- Claims requiring current verification: language and API behavior; standards and
  protocol versions; security advice and threat models; platform defaults; browser,
  operating-system, database, and cloud behavior; AI model capabilities and
  evaluation practice; legal/privacy requirements; and contemporary research
  examples.
- Accessibility or device constraints: unconfirmed. Default to phone-legible,
  high-contrast figures; meaningful alt text; no color-only distinctions; keyboard-
  navigable examples; and code fragments small enough to inspect without horizontal
  scrolling.
- Boundary with adjacent subjects: broad mathematics and quantum-information
  capabilities are reused by canonical `subject/deck` references. Computer science
  owns their transfer into algorithms, systems, data, AI, and software; it does not
  duplicate the external courses. Biology-specific bioinformatics, physical device
  science, and other application-domain knowledge remain with their owning subjects.

## Evidence authorities and source register

Curriculum sources select capabilities and boundaries; they do not automatically
verify individual technical claims. Access date for every source below is
2026-08-23.

| Source | Authority and role | Rights/terms and use here |
|---|---|---|
| [Computer Science Curricula 2023](https://doi.org/10.1145/3664191) | ACM, IEEE-CS, and AAAI endorsed undergraduate framework; primary source for the 17 knowledge areas, competency orientation, professional dispositions, and course-scale scope checks. | Copyright © 2024 ACM, IEEE, AAAI; the report grants use of the curricular guidelines for developing educational materials and programs. Used for original curriculum mapping, not copied prose or figures. |
| [Computing Curricula 2020](https://www.acm.org/binaries/content/assets/education/curricula-recommendations/cc2020.pdf) | ACM/IEEE-CS overview of computing disciplines; used to distinguish computer science from computer engineering, cybersecurity, data science, information systems, information technology, and software engineering while retaining genuine overlaps. | Copyrighted professional-society guidance; consulted for classification and boundary decisions only. No report text or assets are redistributed. |
| [Computing Competencies for Undergraduate Data Science Curricula](https://www.acm.org/binaries/content/assets/education/curricula-recommendations/dstf_ccdsc2021.pdf) | ACM Data Science Task Force; checks computing-specific data acquisition, management, analysis, modeling, reproducibility, and responsibility competencies. | ACM copyrighted report; used as curricular guidance only, with original wording in this workspace. |
| [Cybersecurity Curricular Guidelines 2017](https://www.acm.org/binaries/content/assets/education/curricula-recommendations/csec2017.pdf) | ACM, IEEE-CS, AIS SIGSEC, and IFIP endorsed framework; checks security's technical, human, organizational, ethical, legal, and risk dimensions. | Copyright © 2017 sponsoring societies; permission is granted to use the guidelines to develop educational materials and programs. No source prose or figures are reproduced. |
| [NICE Framework current versions](https://www.nist.gov/itl/applied-cybersecurity/nice/nice-framework-resource-center/nice-framework-current-versions) | NIST's maintained task/knowledge/skill and competency resource; checks current security practice vocabulary without turning the curriculum into job-role certification. | U.S. government source; reuse must still respect any third-party material and attribution notices. Used for scope checking and later claim verification. |
| [NSF CISE](https://www.nsf.gov/cise) | Current U.S. National Science Foundation research portfolio; used as a contemporary branch check for computing/AI foundations, cyber-physical and intelligent systems, human-centered computing, software/systems, cyberinfrastructure, quantum, security, communications, and semiconductors. | U.S. government web source; used as a high-level field map, not as evidence that funding categories are natural course boundaries. |
| [ACM Code of Ethics and Professional Conduct](https://www.acm.org/code-of-ethics) | Professional authority for responsibilities to people, society, quality, privacy, security, leadership, and infrastructure. | Copyright © ACM; principles may guide original scenarios, but later decks must not reproduce substantial commentary without permission. |
| [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) | Consensus-driven public framework for trustworthy AI risk management; a current verification authority for responsible-AI and evaluation practice. | U.S. government source; verify the active version because AI RMF 1.0 is under revision. |

Open educational sources for individual decks must be authoritative and legally
compatible with AI-assisted adaptation and redistribution. “Freely viewable” is not
a license. Each eventual deck must record exact URLs, versions, source roles,
licenses or terms, and access dates in its own source register.

## Authentic practice outside SRS

Competence requires writing and running programs; debugging unfamiliar failures;
designing, implementing, testing, documenting, reviewing, and maintaining projects;
using source control; proving claims and finding counterexamples; measuring and
profiling real systems; conducting user studies and threat models; analyzing data;
reproducing results; reading and critiquing papers; presenting and writing technical
arguments; collaborating ethically; and completing extended laboratories or
research projects. Cards may maintain mental models and high-value decisions, but
they cannot substitute for these performances.
