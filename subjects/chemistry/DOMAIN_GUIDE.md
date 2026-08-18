# Chemistry domain guide

This guide owns durable chemistry-specific authoring judgment. It supplements,
but does not restate, the universal card and authoring standards. Learner choices
and the current deck graph belong in `SUBJECT_BRIEF.md`, `ROADMAP.md`, and
`subject.toml`.

## Epistemic stance

Chemistry explains transformations and properties by coordinating evidence
across scales. A macroscopic observation, molecular model, mathematical
formalism, and instrumental signal are different representations with different
inferential reach. Author cards that ask learners to translate and test those
connections; do not let a familiar picture stand in for evidence.

Keep four questions distinct:

1. **What is present?** Identity, composition, amount, distribution, phase, and
   spatial organization.
2. **What can happen?** Stoichiometric and thermodynamic constraints, possible
   products, and domains of stability.
3. **How does it happen and how fast?** Mechanism, kinetics, transport,
   interfaces, competing pathways, and observation timescale.
4. **How do we know?** Sampling, controls, calibration, spectra, structures,
   models, uncertainty, provenance, and alternative explanations.

A chemically plausible story is not automatically demonstrated. Distinguish
prediction, consistency, support, discrimination, and identification.

## Breadth and subfield balance

- Preserve the analytical, biochemical, inorganic, organic, and physical
  foundations without treating them as sealed silos. Recur to measurement,
  safety, sustainability, computation, and structure–property reasoning in each.
- Represent matter beyond isolated small molecules: ions and mixtures,
  macromolecules, supramolecular assemblies, surfaces, nanoparticles, porous and
  extended solids, defects, disordered phases, and living or environmental
  matrices.
- Balance synthesis with characterization, theory with experiment, equilibrium
  with dynamics, successful conditions with failure modes, and purified systems
  with sampling and matrix effects.
- Do not make carbon chemistry synonymous with all chemistry or reduce inorganic
  chemistry to periodic trends. Include coordination, organometallic,
  bioinorganic, solid-state, main-group, and interfacial reasoning at the
  appropriate level.
- Treat polymers, materials, electrochemistry, environmental chemistry,
  chemical biology, computation, and green chemistry as substantive practices,
  not end-of-course application anecdotes.
- Use representative chemical families and reactions to teach transferable
  decisions. Exhaustive catalogs of colors, named reactions, exceptions, or
  reagent trivia create review burden without a durable model.
- Historical models can be valuable if labeled as historical or limited. Do not
  present the curricular order of models as evidence that science advanced in a
  simple linear sequence.

## Representation grammar

Before using a representation on a front, establish what its marks mean, what is
suppressed, and what inferences it licenses.

### Composition, identity, and structure

- Distinguish empirical and molecular formulae; constitution; formal charge;
  oxidation state; isotope specification; stereochemistry; conformation;
  resonance contributors; tautomers; phases; mixtures; and repeating or
  extended structures.
- A line-angle drawing suppresses most carbon and hydrogen labels; wedges encode
  viewing convention, not a literal fixed pose. A Newman projection, Fischer
  projection, crystal unit cell, and protein cartoon each suppress different
  information.
- Resonance contributors are bookkeeping representations of one electronic
  state, not rapidly interconverting species. Orbitals and electron-density
  surfaces are model-dependent functions, not tiny physical containers.
- Ball-and-stick and space-filling models encode different properties and are
  rarely to scale in the same way. State whether radii, bond lengths, unit-cell
  boundaries, or packing contacts matter.
- Chemical names, CAS-like registry identifiers, SMILES, InChI, formulae, and
  database compound records solve different identity problems. Never imply that
  a name or normalized record uniquely specifies sample purity, stereochemical
  state, solid form, or provenance.

### Equations, mechanisms, and energy pictures

- Balance atoms and charge and label physical states when they affect the
  decision. A balanced equation gives stoichiometry, not mechanism, rate,
  equilibrium position, yield, or safety.
- Curved arrows represent electron-pair or single-electron bookkeeping under a
  named convention. They are claims about a proposed elementary change, not
  paths traced by atoms through space.
- Separate reaction coordinate from clock time. Label axes and reference state
  on energy diagrams; distinguish activation free energy from reaction free
  energy and an intermediate from a transition state.
- A rate law is empirical unless derived under stated mechanistic assumptions.
  Molecularity applies to an elementary step, whereas reaction order belongs to
  a rate law.
- State standard state, temperature, pressure, solvent, ionic strength, and
  activity/concentration approximations when they affect equilibrium or
  electrochemical grading.

### Spectra, images, graphs, and data

- Establish axes, units, baselines, normalization, resolution, sign convention,
  acquisition conditions, and uncertainty. A peak is an observed feature, not
  automatically one species or one transition.
- Separate raw signal, processed signal, fitted components, background,
  residuals, and derived quantities. Ask what processing can create, suppress,
  or correlate.
- Spectra and diffraction patterns are inverse problems. Prefer cards that
  compare hypotheses, combine orthogonal evidence, or diagnose ambiguity over
  one-peak/one-structure mnemonics.
- Microscopy images sample a field of view and may depend on preparation,
  contrast mechanism, tip/probe response, reconstruction, and selection. Scale
  bars, orientation, and representative sampling are part of the evidence.
- Phase diagrams, Pourbaix diagrams, predominance diagrams, band diagrams,
  molecular-orbital diagrams, and free-energy surfaces each use specialized
  boundaries and axes. A line may denote coexistence, equality, or a model
  threshold rather than a material wall.
- Use significant figures as a reporting consequence of uncertainty, not a
  ritual that repairs an invalid model or biased sample.

## Conditions and model boundaries

Every generalization should carry the smallest condition that changes grading.
Common boundaries include:

- isolated molecule versus condensed phase, interface, mixture, or living cell;
- gas-phase acidity versus solution pKa, and solvent-specific acid/base scales;
- ideal gas/solution versus fugacity/activity and nonideality;
- thermodynamic control, kinetic control, steady state, pre-equilibrium, and
  mass-transfer limitation;
- equilibrium bulk phase versus metastable, amorphous, nanoscale, strained, or
  defect-rich material;
- intrinsic molecular property versus sample-, morphology-, dose-, time-, or
  instrument-dependent response;
- Born–Oppenheimer, harmonic, rigid-rotor, independent-particle, mean-field,
  continuum-solvent, or classical-nuclei approximations;
- in vitro, in cellulo, in vivo, environmental, and clinical evidence;
- correlation, perturbation, target engagement, pathway modulation, efficacy,
  and causal mechanism.

When a simplified model is pedagogically necessary, teach both its useful
prediction and a diagnostic sign that its assumptions have failed.

## Recurring misconceptions and interference pairs

Plan explicit discrimination among these neighbors:

- atom, element, nuclide, isotope, ion, molecule, compound, substance, sample,
  phase, and mixture;
- mass, amount of substance, particle count, concentration, activity, mole
  fraction, and density;
- heat and temperature; internal energy, enthalpy, entropy, Helmholtz energy,
  and Gibbs energy;
- spontaneous, exergonic, exothermic, favorable equilibrium, and fast;
- equilibrium and equal concentrations; equilibrium and stopped molecular
  change; steady state and equilibrium;
- bond energy and activation energy; bond breaking and energy release;
- formal charge, partial charge, oxidation state, and measured charge density;
- electronegativity, electron affinity, ionization energy, and electrode
  potential;
- resonance, tautomerism, conformational change, and chemical equilibrium;
- orbital occupation, hybridization model, molecular geometry, and electron
  density;
- strong versus concentrated acid; nucleophilicity versus basicity;
  regioselectivity versus stereoselectivity; thermodynamic versus kinetic
  product;
- catalyst activity, selectivity, stability, productivity, and true turnover;
- accuracy, precision, resolution, sensitivity, selectivity, detection limit,
  quantitation limit, and uncertainty;
- calibration fit, prediction, validation, and causal explanation;
- hazard and risk; acute and chronic hazard; dose and exposure; safer and safe;
- yield, conversion, selectivity, atom economy, process mass intensity, energy
  demand, toxicity, and life-cycle impact;
- computed minimum, transition state, ensemble average, observable, and
  experimentally validated mechanism.

Avoid absolute slogans such as “atoms want full shells,” “nature seeks lower
energy,” “like dissolves like,” or “the catalyst lowers the activation energy”
without the causal model and relevant limits. Teleological shorthand should be
replaced by interactions, constraints, probabilities, and free-energy or kinetic
reasoning appropriate to the level.

## Safety, sustainability, and ethics

- Begin safety with **hazard recognition → exposure and scale → risk assessment
  → controls → emergency preparation**. PPE is one control, not the definition
  of safety.
- Never infer handling, compatibility, disposal, exposure limits, or emergency
  response from a card writer's memory. Check the current jurisdiction,
  institutional plan, substance and concentration, process conditions, SDS, and
  primary hazard authority. A card cannot authorize unsupervised work.
- Include energetic, pyrophoric, peroxide-forming, pressure, vacuum, cryogenic,
  electrical, radiation, biological, and scale-up hazards when relevant; do not
  focus only on toxicity or corrosivity.
- Separate hazard classes from actual risk in a defined procedure. State when a
  safer substitute changes performance or creates a different hazard.
- Sustainability comparisons require a functional unit and system boundary.
  Track mass, energy, solvent, water, yield/selectivity, hazard, feedstock,
  durability, recovery, use phase, and end of life as applicable. Do not infer a
  whole-life benefit from one favorable metric.
- Treat data selection, image processing, spectral deconvolution, omitted runs,
  duplicate measurements, notebooks, authorship, and conflicts of interest as
  chemical integrity issues, not generic afterthoughts.

## Evidence authorities and source choice

Use the source register in `SUBJECT_BRIEF.md` and record deck-specific sources in
the eventual deck README. Match authority to claim:

- IUPAC recommendations and Color Books for terminology, nomenclature,
  quantities, symbols, structure representation, and evaluated conventions;
- current standards bodies and metrology institutes such as NIST for constants,
  reference data, traceability, and evaluated properties;
- the controlling regulator, institutional chemical-hygiene plan, current SDS,
  and primary hazard references for safety and disposal;
- primary literature plus independent replication, consensus reports, or
  systematic evaluations for mechanisms, performance, health, and environmental
  claims;
- original instrument-method papers, standards, certified reference-material
  documents, and validation studies for analytical claims;
- database records only with contributor, version/date, method, uncertainty,
  and license. Aggregated values are not interchangeable merely because they
  share a field label;
- curriculum frameworks for capability selection only, not as proof of a
  chemical fact.

Prefer evaluated data over an isolated measurement and a primary experimental
paper over a tertiary mechanism diagram. For unstable or contested claims,
record the search date, competing interpretation, and evidence that would
change the conclusion.

## Chemistry-specific accuracy checks

Run these in addition to parser and universal card checks:

1. **Identity:** Are formula, charge, isotope, stereochemistry, protonation,
   tautomer, phase, solvation, and sample state specified at the required level?
2. **Conservation:** Are atoms, charge, electrons, mass, and units conserved?
   Are limiting reagents, basis, and normalization explicit?
3. **Conditions:** Are solvent, temperature, pressure, concentration/activity,
   pH convention, atmosphere, light, electrode/reference, time, and scale stated
   when material?
4. **Thermodynamics/kinetics:** Does the explanation confuse feasibility,
   equilibrium, rate, transport, mechanism, or timescale?
5. **Mechanism:** Do arrows start and end on valid electron sources/sinks? Are
   charges, valence, intermediates, stereochemistry, and catalytic regeneration
   consistent? Is the mechanism established, supported, or merely plausible?
6. **Mathematics:** Are logarithm bases, standard states, signs, dimensions,
   constants, significant figures, and approximations consistent? Does a
   limiting case or order-of-magnitude check work?
7. **Measurement:** Are analyte, measurand, sampling frame, calibration model,
   blank, controls, matrix, detection limits, uncertainty, and traceability
   distinguished?
8. **Spectra/structure:** Are axes and acquisition conditions correct? Does the
   evidence uniquely support the answer, or should the cue ask for the best
   supported hypothesis?
9. **Materials:** Are composition, processing history, phase, defects,
   morphology, surface area, dimensions, and measurement conditions controlled
   before attributing a property to structure?
10. **Biological/environmental:** Are species, matrix, dose/concentration,
    exposure route, time, compartment, metabolism, and causal level stated?
11. **Computation:** Are method, basis/parameters, charge/spin, boundary
    conditions, sampling, convergence, benchmark, uncertainty, code/data
    version, and experimental validation appropriate?
12. **Safety/legal:** Is the claim current, jurisdiction-bound, and sourced?
    Does it accidentally read as permission to perform hazardous work?

## Retrieval and figure opportunities in chemistry

High-value chemistry figures usually test a decision: translate a structure,
trace electron flow, rank competing pathways, read a phase or energy diagram,
infer from a spectrum, diagnose a chromatogram, inspect a calibration residual,
compare crystal or polymer morphology, identify a control in an apparatus, or
connect an operando signal to a reaction state.

Keep answer-revealing atom labels, arrows, peak assignments, stereochemical
annotations, fitted components, and phase labels off the front unless they are
givens. Use chemically valid geometry and accessible non-color encodings. When
exact coordinates, spectra, or quantitative curves matter, derive the visual
from verified data or an explicit model rather than illustrative raster art.

Calculations should progress from qualitative sign and scale, through method
selection and dimensional checks, to independent execution and interpretation.
Preserve extended synthesis, spectral assignment, coding, and laboratory design
as outside-SRS performances when fragmenting them would destroy the authentic
skill.
