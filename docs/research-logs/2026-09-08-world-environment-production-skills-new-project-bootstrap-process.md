# World / Environment Production Skills — New Project Bootstrap Process

**Status:** Bootstrap specification  
**Version:** 1.1  
**Date:** 13 September 2026

## 1. Purpose

This process defines how `world-environment-production-skills` moves from a project idea to a **scaffolded, benchmarked, installable open-source Agent Skills repository** for producing coherent worlds and environments from research, spatial constraints, product/game requirements and approved world-state inputs.

The project should help AI agents perform world and environment production as a discipline rather than treating an environment as a single 3D generation prompt, a pile of assets or an unconstrained procedural scene.

The target production loop is expected to resemble:

```text
world / environment intent
→ source and constraint intake
→ spatial model
→ world structure / environment grammar
→ cheapest useful representation
→ blockout / map / procedural proof
→ evaluation and selection
→ modular / procedural production plan
→ asset and system handoffs
→ environment assembly
→ runtime / spatial validation
→ selective fidelity promotion
→ targeted correction
→ production-ready world / environment handoff
```

The exact workflow must be validated through domain research before it becomes a skill contract.

`world-environment-production-skills` owns reusable production expertise for **spatial world design, environment structure, real-world ingestion, modular and procedural environment production, environment assembly, spatial consistency, representation fidelity and environment-level evaluation**.

It does **not** own:

- Worldstack's scientific or social simulation models;
- game mechanics, encounters or progression owned by Game Development Skills;
- detailed individual 3D asset craft owned by 3D Production Skills;
- character, animation, narrative, video, music or sound production;
- generic software/tooling engineering;
- external research as a discipline;
- project-specific world truth or consuming-project state;
- Pactwright lifecycle authority.

The project may specify what adjacent domains must deliver and integrate their outputs into a coherent environment.

---

## 2. Governing Sources

Use the current Production Skills family process as canonical:

- `production-skills/docs/bootstrap/README.md`
- `production-skills/docs/bootstrap/new-project-process.md`
- `production-skills/docs/bootstrap/domain-research-process.md`
- `production-skills/docs/bootstrap/extension-pack-process.md`
- `production-skills/docs/bootstrap/shared-abstraction-process.md`
- `production-skills/docs/specs/01-production-skills-family-system.md`
- `production-skills/docs/specs/02-production-skills-project-contract.md`
- `production-skills/docs/specs/03-production-skills-evaluation-and-extension-packs.md`
- `production-skills/docs/specs/04-cross-domain-orchestration-and-integration.md`

Use mature Video, Narrative and Music Production Skills as evidence for proven family patterns only after the world/environment discipline has been independently understood. Use UI/UX, Game Development, Deep Research, Software Engineering and Legal Skills bootstraps as structural references where their boundaries are relevant.

Use Worldstack as a major consumer and stress-test source, especially:

- `worldstack/docs/specs/01-worldstack-system-and-boundaries.md`
- `worldstack/docs/specs/02-world-model-and-system-integration.md`
- `worldstack/docs/specs/04-game-world-and-representation.md`
- `worldstack/docs/specs/05-production-skills-and-pactwright-integration.md`

Worldstack is a proving ground, not the owner of this project's reusable workflow.

Newer family requirements take precedence:

```text
bootstrap workspace before substantive research
research logs as durable stage outputs
Seed → Five → Challenge
exactly five complementary foundational books
explicit permission before supplied-book substitution
direct-source examination and traceable extraction
evidence-qualified domain model
six canonical specs
5 levels × 3 primary examples
first-class Extension Packs
evidence-led Extension Pack catalogue curation
five justified books per selected Extension Pack
pack-authoring capability
separate pack research / implementation / evaluation status
core-vs-pack differential evaluation
clean external installation smoke tests
```

### v1.1 migration

Version 1.1 explicitly adopts the Production Skills **Seed → Five → Challenge** domain-research process and the evidence-led Extension Pack bootstrap process.

No substantive bootstrap stages had been executed under v1.0 beyond this specification and the research-log README, so stage numbers are updated directly rather than introducing compatibility aliases. Existing Worldstack-derived analysis is retained as seed evidence and input to the new stages.

The migration does **not** imply that corpus selection, direct book examination, broader professional challenge research, Extension Pack research, implementation or evaluation has already occurred.

---

## 3. Initial Domain Evidence and Boundary Hypotheses

The material below is **seed evidence**. It establishes important world/environment production hypotheses and research questions, but does not satisfy the five-book extraction stage or the broader challenge stage.

### World state is not world representation

```text
WORLD STATE ≠ WORLD REPRESENTATION
```

A state such as rainfall, congestion, rent pressure, land use, cultural activity or ecological condition may be represented spatially and visually through roads, surfaces, buildings, vegetation, signage, traffic affordances, density, wear, props or other environment features.

World / Environment Production Skills may **materialise** approved state. They must not silently become the authority for the model that produced that state.

### Breadth and fidelity are independent

Worldstack's representation ladder provides a useful hypothesis:

```text
structured / debug representation
→ primitive representation
→ procedural low-detail representation
→ art-directed prototype
→ production environment
→ selective hero fidelity
```

A broad city may need to exist cheaply before a single street becomes expensive. Higher fidelity is not automatically better.

### Models and environment production have different ownership

Worldstack owns executable models, simulation state and experiment semantics. Production Skills own reusable specialist production technique. Pactwright owns authorised lifecycle and Evidence. Project Intelligence owns Worldstack-specific durable conclusions.

Likely interface:

```text
approved world state / project brief / gameplay constraints / research
→ World / Environment Production Skills
→ spatial/environment production artefacts
→ Game / 3D / Narrative / Audio / other Production Skills handoffs
→ assembled environment
```

### Behavioural contracts should survive representation changes

A location or system should be able to move from primitive to production representation without requiring unrelated systems to be redesigned, provided agreed spatial and behavioural contracts remain stable.

### Worldstack's capability-gap loop remains external

Worldstack may discover production gaps and send them to the Production Skills incubator. One Worldstack-specific problem is not sufficient evidence for a new family abstraction, skill or pack.

---

## 4. Governing Principles

### Spatial structure before surface detail

Resolve topology, scale, circulation, adjacency, hierarchy, access and major environmental relationships before investing in decorative fidelity.

### Cheapest useful spatial representation

```text
written spatial brief
→ annotated map / GIS layer / adjacency graph
→ 2D plan
→ primitive blockout
→ procedural low-detail world
→ art-directed environment slice
→ production environment
→ selective hero treatment
```

Choose representation according to uncertainty, not prestige.

### Breadth before hero fidelity when world architecture is uncertain

For large worlds, prove extent, connectivity, partitions, density and system integration cheaply before authorising expensive local detail.

### Reference is evidence, not instruction to copy blindly

Maps, photographs, scans, street imagery, plans, satellite imagery, open data and creative references must retain provenance, source limitations and uncertainty. Distinguish measured facts, inferred structure, approximations and creative departures.

### World structure and asset craft are separate responsibilities

World / Environment Production Skills decide what spatial systems, modular kits, assets, rules and placement grammar are required. 3D Production Skills owns specialist construction of individual production assets where that work is reusable 3D craft.

Low-fidelity primitives and procedural geometry may remain inside world/environment production when they are the cheapest representation needed to answer a spatial question.

### Environment and gameplay are coupled but not identical

Game Development Skills owns mechanics, encounters, traversal rules, player goals and gameplay acceptance. World / Environment Production Skills translates those constraints into layout, affordances, sightlines, scale, circulation, cover/space requirements, landmarks and environment handoffs.

### Environment state must remain explainable

For procedurally or systemically generated environments preserve:

```text
source inputs
rules / seeds
constraints
manual overrides
selected result
known limitations
```

### Selective fidelity promotion

Promote only locations, systems and assets whose higher fidelity is justified by player experience, simulation representation, visual priority, camera exposure, performance constraints or product requirements.

### Preserve approved spatial work

An accepted road network, district boundary, building footprint, terrain profile, landmark placement or modular rule should not be silently rewritten during unrelated refinement.

### Correct the smallest responsible layer

```text
wrong map alignment
→ source / spatial transform

poor route hierarchy
→ world structure

repetitive district
→ modular / procedural grammar

incorrect building proportions
→ environment layout or 3D asset, depending on ownership

navigation failure
→ environment collision/nav handoff or Game Development, depending on cause

streaming hitch
→ environment partition / asset budget or Software Engineering, depending on cause

world-state mismatch
→ representation mapping if state is correct; upstream Worldstack/model if state is wrong
```

### Runtime constraints are production inputs

Streaming, LOD/HLOD, occlusion, collision, navigation, memory, draw/instance budgets, platform limits and coordinate precision may materially constrain world production. Define environment-level requirements while delegating engine/tool implementation appropriately.

### Legal provenance is not optional for real-world ingestion

Maps, imagery, scans, brands, architecture, public data and third-party assets may carry copyright, database, privacy, trade mark, contractual or licence constraints. Legal Skills owns legal analysis; World / Environment Production Skills preserves provenance and legal constraints through production handoffs.

---

# 5. Bootstrap Flow

```text
PROJECT IDEA
    ↓
0. Create Bootstrap Workspace Repository
    ↓
1. Define Domain Goal and Adjacent Boundaries
    ↓
2. Select Complementary Five-Book World / Environment Corpus
    ↓
3. Extract and Reconcile Five-Book Corpus
    ↓
4. Challenge and Extend Through Professional World / Environment Practice
    ↓
5. Define Spatial, Scale, Coordinate and World-Structure Model
    ↓
6. Define Source Ingestion, Reference and Provenance Model
    ↓
7. Define Representation, Fidelity and Commitment Strategy
    ↓
8. Define Modular, Procedural and Assembly Model
    ↓
9. Define Runtime, Streaming and Cross-Domain Handoffs
    ↓
10. Research AI Skills, DCCs, Engines, GIS and Environment Tools
    ↓
11. Choose Execution Layer and Tool Boundaries
    ↓
12. Gap Analysis + Over-Engineering Guardrails
    ↓
13. Design Core Skills and Commands
    ↓
14. Design Extension Pack Catalogue, Research and Pack Authoring
    ↓
15. Design Progressive Examples
    ↓
16. Design Worldstack + Independent Canonical Stress Tests
    ↓
17. Design Evals, Benchmarks and Regression Fixtures
    ↓
18. Generate Six Canonical Specs
    ↓
19. Design Public README
    ↓
20. Cross-Project Review
    ↓
21. Scaffold Production Repository
    ↓
22. Implement and Prove Core Vertical
    ↓
23. Expand Progressive Coverage and Extension Packs
    ↓
24. Validate Installation and Repository Integrity
    ↓
25. Optional Pactwright Integration + Registry Promotion
    ↓
26. Review Shared-Abstraction Candidates
    ↓
MATURE WORLD / ENVIRONMENT PRODUCTION SKILLS PROJECT
```

The Stage 0 repository is a bootstrap workspace, not the production scaffold created at Stage 21.

Stages 2, 3 and 4 are separate completion gates. Do not collapse corpus selection, direct-source extraction and broader professional challenge merely to progress faster.

---

# 6. Stage 0 — Create Bootstrap Workspace Repository

Create `sb-dev/world-environment-production-skills` before substantive bootstrap research begins.

Initial structure:

```text
world-environment-production-skills/
├── README.md
└── docs/
    └── research-logs/
        ├── README.md
        └── 2026-09-08-world-environment-production-skills-new-project-bootstrap-process.md
```

Do not create `skills/`, `examples/`, `benchmarks/`, `extension-packs/`, tooling, CI or package metadata until later stages justify them.

Every substantive stage should write detailed findings into `docs/research-logs/`. Conversation should carry summaries and decisions rather than becoming the durable research store.

Treat each stage as a standalone task. Read required prior logs, complete substantive work, check exit criteria and commit the detailed research log before dependent work proceeds.

Suggested stage-log pattern:

```text
docs/research-logs/
├── 2026-09-08-world-environment-production-skills-new-project-bootstrap-process.md
├── YYYY-MM-DD-stage-01-domain-boundary.md
├── YYYY-MM-DD-stage-02-five-book-corpus-selection.md
├── YYYY-MM-DD-stage-03-five-book-extraction.md
├── YYYY-MM-DD-stage-04-professional-practice-challenge.md
├── YYYY-MM-DD-stage-05-spatial-world-structure.md
└── ...
```

Later Extension Pack research should also use durable per-pack logs:

```text
YYYY-MM-DD-extension-pack-catalogue-selection.md
YYYY-MM-DD-pack-<name>-01-specialisation.md
YYYY-MM-DD-pack-<name>-02-five-book-selection.md
YYYY-MM-DD-pack-<name>-03-extraction.md
YYYY-MM-DD-pack-<name>-04-challenge.md
```

Creating the repository does **not** make the project `scaffolded`.

**Exit:** the workspace exists and later stages can operate from durable research files.

---

# 7. Stage 1 — Define Domain Goal and Adjacent Boundaries

Resolve ownership across:

```text
world design
environment design
real-world ingestion
city / district production
terrain / landscape production
spatial planning
modular environment systems
procedural environment systems
set dressing / environment composition
environmental storytelling inputs
world-state representation
runtime environment preparation
environment evaluation
```

Define boundaries with Worldstack, Game Development, 3D Production, Deep Research, Legal, Narrative, UI/UX, Character/Animation, Audio/Music, Software Engineering, QA/Evaluation and Pactwright.

Key questions include:

- Does the core own both real-world reconstruction and fictional world production?
- What is world design versus game-level design?
- What geometry remains legitimate inside this project versus 3D Production Skills?
- How are physical/geographic facts separated from creative interpretation?
- How are environment requirements handed to asset-production domains?
- What counts as reusable world-production technique rather than Worldstack/project-specific knowledge?

**Exit:** a defensible domain boundary exists before skill design.

---

# 8. Stage 2 — Select Complementary Five-Book World / Environment Corpus

Apply `production-skills/docs/bootstrap/domain-research-process.md`.

Use bounded reconnaissance only to map the knowledge required by the Stage 1 boundary and compare candidate books. Do not turn this stage into the full professional-practice challenge.

Candidate coverage dimensions include:

```text
spatial / environment design
world structure and circulation
architecture / urban morphology / landscape
modular environment production
procedural world generation
real-world / geospatial reconstruction
environment art and composition
runtime / streaming / technical constraints
environmental storytelling
multi-scale production and fidelity
```

These are candidate dimensions, not fixed book slots.

Select **exactly five distinct foundational books** whose combined contribution best covers the domain. Research a broader candidate pool rather than simply choosing five popular environment books. Useful overlap may add depth; unnecessary duplication should not crowd out major domain responsibilities.

For each selected book record:

```text
title / author
edition / publication year
provided or selected origin
intended contribution
access status
material available for examination
known limitations
```

User-provided books remain unless the user explicitly approves removal, replacement or demotion. Any substitution proposal must explain the overlap/coverage problem, expected gain, potential loss and alternative. Silence is not approval.

Five books are the foundational corpus, not a limit on later papers, talks, standards, documentation, maps, technical sources or additional books.

**Research-log output:** coverage map, candidate comparison, selected corpus, access register, substitution decisions and remaining gaps.

**Exit:** exactly five books are selected, required permissions are resolved, and access needs/gaps are explicit.

---

# 9. Stage 3 — Extract and Reconcile Five-Book Corpus

Meaningfully examine all five books for their intended contribution. Publisher summaries, contents pages and model memory may help selection but are not direct-source extraction.

For material concepts record:

```text
source + location actually examined
spatial / production problem
principle / method / heuristic
applicability and assumptions
production decision affected
representation / artefact implication
failure conditions / misuse risks
repair implications
evaluation criterion
provisional capability
```

Produce:

```text
per-book findings
source-to-capability matrix
overlap analysis
conflict log
provisional World / Environment capability model
```

Do not create one skill per book or assume agreement between architectural, level-design, environment-art and procedural sources means one universal method. Preserve meaningful disagreement and context.

A source may contribute little after examination; record that honestly instead of inventing a capability.

**Exit:** all five books have been meaningfully examined for their intended contributions; material findings are traceable; gaps, conflicts and limitations remain explicit.

---

# 10. Stage 4 — Challenge and Extend Through Professional World / Environment Practice

Use the provisional capability model to guide, not limit, independent domain research.

Answer both questions:

1. Which book-derived principles hold in professional practice, under what conditions and with what limitations?
2. Which important responsibilities, workflows or technical realities are missing from the books?

Study complementary disciplines rather than one studio pipeline:

```text
environment art
world building
level / spatial design
urban design and urban morphology
architecture and landscape architecture
GIS / cartography / geospatial production
real-world reconstruction
photogrammetry / scan-based workflows
modular environment production
procedural content generation
technical art
open-world streaming / optimisation
environmental storytelling / set dressing
digital-twin / city-model production as a comparison domain
historical reconstruction where useful
```

Capture roles, terminology, briefing/reference practice, spatial decomposition, scale/coordinates, blockout methods, modular kits, procedural grammar, environment bills of materials, set dressing, terrain/road/building workflows, review points, performance constraints, failures, repair scopes, handoffs and quality criteria.

Challenge through current non-book evidence where appropriate:

```text
engine and DCC documentation
GIS / geospatial standards
technical-art practice
studio talks / postmortems
procedural-generation research
photogrammetry / reconstruction research
runtime / streaming documentation
professional case studies
```

Do not import one engine's world-building workflow as the universal model. Explicitly test whether the capability model works for both a Worldstack-style simulation-driven real-world consumer and an independently authored fictional world.

Keep source classes distinct:

```text
book-derived production principle
professional-practice evidence
measured spatial source
technical documentation
creative reference
researcher inference
project-specific constraint
```

The output is an **evidence-qualified World / Environment production model**, not a claim that every retained method has been universally validated.

**Exit:** material book-derived findings have been assessed, important gaps are addressed or bounded, and the domain model stands independently of Worldstack and current generation providers.

---

# 11. Stage 5 — Define Spatial, Scale, Coordinate and World-Structure Model

Research the minimum common spatial language needed without inventing a universal world ontology.

Candidate concerns:

```text
extent / bounds
coordinate reference / local origin
scale / units
elevation / terrain datum
regions / districts / zones
routes / networks
parcels / plots / footprints
landmarks
adjacency
access / circulation
vertical layers
interior / exterior relationships
portals / transitions
world partitions / streaming cells
spatial constraints
semantic tags only where production requires them
```

Investigate artefacts such as world briefs, spatial plans, annotated maps, world hierarchies, district sheets, route/circulation maps, landmark maps, scale references, partition plans and environment contracts.

Avoid a universal Event Graph, GIS ontology or scene graph until repeated integrations prove a need.

**Exit:** different tools and fidelity levels can share enough spatial intent to preserve world structure.

---

# 12. Stage 6 — Define Source Ingestion, Reference and Provenance Model

Research worlds derived from maps, geospatial data, satellite/aerial imagery, street imagery, photographs, video, plans, survey/scan data, point clouds, photogrammetry, Gaussian splats/neural reconstruction references, historical maps/archives, concept art, moodboards, written briefs, Worldstack outputs and existing project state.

For each source class capture:

```text
identity / provenance
licence / legal constraints
coordinate / scale reliability
freshness / date
coverage
precision
known distortions
missing areas
confidence / uncertainty
measured vs inferred vs stylistic status
allowed downstream use
```

Preserve:

```text
observed geometry
inferred geometry
approximate geometry
creative substitution
unknown
```

Define how Deep Research and Legal Skills hand evidence and constraints into production without moving those domains into this repository.

**Exit:** reconstruction or inspiration can proceed without losing provenance or confusing approximation with fact.

---

# 13. Stage 7 — Define Representation, Fidelity and Commitment Strategy

Validate a domain-native ladder such as:

```text
L0 structured / annotated spatial state
L1 2D plan / primitive debug representation
L2 greybox / blockout
L3 procedural or modular low-detail environment
L4 art-directed representative slice
L5 production environment
L6 selective hero-quality treatment
```

Map uncertainty to the cheapest representation able to answer it: road hierarchy to maps/networks, density to simple massing, route readability to blockout, terrain to low-resolution heightfields, kit coverage to matrices/sample blocks, procedural rules to seeded low-detail generation, landmarks to primitive massing, state representation to debug views and streaming partition to broad low-detail worlds.

Define commitment points for expensive asset commissioning, large procedural generation, world-wide re-layout and hero production.

**Exit:** fidelity follows uncertainty and cost rather than defaulting to final art.

---

# 14. Stage 8 — Define Modular, Procedural and Assembly Model

Research modular kits, snapping, variation, facade/building/road grammars, parcel generation, terrain/biome rules, vegetation distribution, prop/signage placement, semantic constraints, seeds, manual overrides, art-direction constraints, protected zones, budgets and repeat detection.

For procedural work preserve inputs, seed, rules, constraints, selected outputs, overrides and version. Investigate when to regenerate versus locally repair and ensure approved local work can survive appropriate regeneration.

**Exit:** repeatable environments can be built without turning procedural generation into an opaque one-shot operation.

---

# 15. Stage 9 — Define Runtime, Streaming and Cross-Domain Handoffs

Research environment-level requirements for world partitioning/streaming, LOD/HLOD, occlusion, collision, navigation/traversal handoffs, coordinate precision/origin shifting, instancing, memory/geometry/material budgets, loading boundaries, runtime variation, state-driven representation and platform constraints.

Define handoffs:

```text
Game Development
→ gameplay / traversal / encounter constraints
→ World / Environment
→ spatial environment
```

```text
World / Environment
→ modular kit / asset requirements
→ 3D Production
→ runtime-ready assets
→ World / Environment assembly
```

```text
Worldstack
→ approved model state / behavioural outputs
→ World / Environment
→ representation mapping
```

```text
Deep Research + Legal
→ source evidence + usage constraints
→ World / Environment
→ provenance-aware production
```

```text
Narrative
→ location / environmental-storytelling intent
→ World / Environment
→ spatial / set-dressing requirements
```

**Exit:** adjacent domains collaborate without unclear ownership of the environment or underlying model.

---

# 16. Stage 10 — Research AI Skills, DCCs, Engines, GIS and Environment Tools

Research capabilities across Agent Skills, level-design skills, Blender/Houdini/similar DCC automation, Unreal/Unity/Godot tooling, GIS, OpenStreetMap/Overture/commercial maps, CityEngine/city generation, terrain tools, photogrammetry/scanning, point clouds, reconstruction, text/image-to-3D, procedural frameworks, asset libraries, scene validation, streaming/profiling, navigation/collision inspection and reference tooling.

Evaluate capability, licence, data rights, maturity, automation surface, determinism, provider coupling, cost, scale, engine/DCC coupling, composability, quality and maintenance. Classify `USE`, `ADAPT`, `REFERENCE` or `REJECT`.

**Exit:** the project knows which operations should be delegated to existing environment-production tools.

---

# 17. Stage 11 — Choose Execution Layer and Tool Boundaries

World / Environment Production Skills should own spatial interpretation, world decomposition, representation choice, fidelity/commitment strategy, modular/procedural grammar, source-to-space translation, asset/handoff requirements, assembly strategy, state-to-representation mapping, environment-level quality criteria and repair scope.

Existing tools should execute GIS transforms, terrain processing, procedural generation, mesh/material work, scene editing/import, rendering, streaming builds, collision/nav generation, runtime profiling, map/imagery retrieval and reconstruction where suitable.

Do not build a universal DCC adapter or scene runtime without concrete evidence.

**Exit:** execution tools can change without redesigning reusable production intelligence.

---

# 18. Stage 12 — Gap Analysis and Over-Engineering Guardrails

Test for gaps in reference-to-world translation, approximation discipline, spatial consistency, multi-scale planning, breadth-first production, modular kit planning, procedural rules, manual/procedural coexistence, provenance, state-to-representation mapping, asset handoffs, cross-domain assembly, streaming/budgets, failure diagnosis and selective fidelity.

Defer unless proven necessary: universal world graph, universal GIS schema, custom engine/GIS/map service, universal coordinate abstraction, universal procedural DSL, city simulator, central asset database, custom photogrammetry stack, digital-twin platform, universal streaming engine, provider-neutral DCC runtime and one universal environment-quality score.

**Exit:** native skills address proven production gaps rather than building a world platform inside the repository.

---

# 19. Stage 13 — Design Core Skills and Commands

Lean starting hypothesis:

```text
world-environment-production
world-environment-evaluate
world-environment-pack-create
```

Possible production commands include `frame-environment`, `ingest-references`, `resolve-spatial-context`, `map-world-structure`, `plan-fidelity`, `blockout`, `plan-modular-kit`, `define-procedural-grammar`, `generate-layout`, `map-state-to-representation`, `plan-asset-handoffs`, `assemble-environment`, `prepare-runtime-environment`, `promote-fidelity` and `repair-environment`.

Possible evaluation commands include audits for scale, topology, circulation, reference fidelity, provenance, modularity, procedural consistency, repetition, world-state representation, streaming boundaries, runtime budgets and cross-domain handoffs, plus preservation verification and failure diagnosis.

Retain commands only when they improve isolated evaluation, reuse, composition, diagnosis, targeted repair or benchmark precision.

**Exit:** every core skill and command has a coherent environment-production responsibility.

---

# 20. Stage 14 — Design Extension Pack Catalogue, Research and Pack Authoring

Apply `production-skills/docs/bootstrap/extension-pack-process.md`.

This stage has two responsibilities:

1. curate complementary catalogue coverage;
2. define and schedule the per-pack evidence process for selected specialisations.

## 20.1 Catalogue curation

Do not start from a fixed catalogue. Research or generate a broader candidate pool and assess combined coverage, reuse, distinct production behaviour, evaluation feasibility and overlap with core and neighbouring packs.

Classify each need:

```text
existing pack covers the need → reuse
one-project detail → project instructions
broadly applicable world/environment responsibility → core-improvement candidate
reusable specialised production behaviour → Extension Pack candidate
insufficient value or evidence → defer / reject
```

Candidate profiles worth researching include:

```text
real-world-city-reconstruction
procedural-large-open-world
modular-gameplay-district
historical-place-reconstruction
natural-landscape-and-biome
dense-living-city
simulation-driven-world-representation
```

These are candidates, not a required catalogue. Catalogue size follows useful complementary coverage.

## 20.2 Labels, engines and geographies are not sufficient packs

Do not assume the following are valid packs merely because they are recognisable labels:

```text
Unreal
Unity
Houdini
forest
city
London
realistic
```

Engine/provider choice should normally remain execution configuration unless it materially changes reusable production grammar. A biome or geography alone is not necessarily a production methodology.

A valid pack may alter:

```text
source ecology
spatial decomposition
approximation tolerance
modular / procedural grammar
representation / fidelity strategy
asset commissioning
runtime assumptions
provenance requirements
evaluation criteria
cross-domain handoffs
```

## 20.3 Per-pack research process

Every selected pack follows:

```text
P1 define specialisation and core baseline
P2 select five complementary foundational books
P3 extract and reconcile specialised knowledge
P4 challenge claims and extend coverage
P5 specify behaviour and evaluation
P6 implement and demonstrate
P7 evaluate, clean-install and catalogue
```

Books may be reused across packs after the original direct-source evidence, edition, reading scope and applicability are checked. There is no requirement for five new books per pack and no permission to copy the core corpus blindly.

User-provided pack books retain the same substitution approval rules as domain books.

## 20.4 Source-to-behaviour traceability

Map pack evidence as:

```text
source finding + location
→ applicability to specialisation
→ changed core decision
→ observable artefact / workflow effect
→ evaluation criterion
→ failure / repair case
```

Use additional non-book evidence where required, especially engine/DCC documentation, GIS standards, technical-art guidance, streaming systems, reconstruction research and professional postmortems.

## 20.5 Fair pack evaluation

Before implementation define falsifiable acceptance cases. When implemented, compare core-only and core+pack on the same substantive brief and comparable conditions. The packed run must not receive a richer task brief simply to make the pack look useful.

Use a distinct additional reuse fixture beyond the showcase. Keep research, implementation, evaluation and readiness statuses separate. A catalogue entry, pack directory or showcase prompt is not evidence of demonstrated quality.

Pack precedence remains:

```text
explicit project requirements
→ approved world/environment decisions and source constraints
→ selected Extension Pack
→ core World / Environment defaults
```

**Exit:** selected packs are justified as reusable production specialisations, with explicit research plans and testable behaviour rather than labels or project briefs.

---

# 21. Stage 15 — Design Progressive Examples

Target:

```text
5 levels × 3 primary examples = 15 primary examples
```

Select through a capability matrix.

### Level 1 — one bounded spatial/environment problem

Examples may include a street-corner blockout from map/references, modular room/corridor kit proof and small terrain/trail section.

### Level 2 — one coherent location

Examples may include an urban block/plaza, small natural landscape and interior+exterior venue/compound.

### Level 3 — complete environment slice

Examples may include real-world district reconstruction, procedural settlement/village and fictional gameplay-oriented district.

### Level 4 — scale, systems and repair

Examples may include multi-district streamed city section, large mixed-biome region and state-driven environment reacting to weather/economy/population inputs.

### Level 5 — full world/environment thesis

Examples may include a Worldstack London slice from mixed evidence, a large fictional modular/procedural region and a historical/contemporary reconstruction with uncertainty, provenance and selective fidelity.

Across all 15 cover real/fictional worlds, urban/natural environments, plans/blockouts/procedural/production representations, maps/images/scans/written briefs, modular/procedural production, multi-scale composition, state representation, asset handoffs, streaming/runtime, preservation/repair, packs, legal provenance and cross-domain integration.

Every primary example includes a complete copyable prompt.

**Exit:** examples demonstrate complementary capability rather than fifteen city scenes.

---

# 22. Stage 16 — Design Worldstack and Independent Canonical Stress Tests

## Stress Test A — Worldstack real-world systems representation

Use a recognisable London slice or equivalent Worldstack Delivery to test map/open-data ingestion, provenance, breadth before fidelity, stable spatial contracts, state-to-representation mapping, multiple system inputs, modular/procedural production, selective fidelity, handoffs, Pactwright compatibility and model replacement without unnecessary environment rewrite.

Adversarial cases include stale representation after state change, unsupported inferred facts, hidden source disagreement, map alignment error, premature hero work, lost legal/source restrictions and procedural regeneration destroying approved local edits.

## Stress Test B — Independent fictional world

Use a fictional environment without Worldstack dependency to test written/concept-art briefs, world structure, kit planning, procedural variation, spatial storytelling, Game/3D handoffs, runtime constraints, selective hero treatment and bounded repair.

Stage 4 should explicitly confirm that the evidence-qualified capability model can support both stress-test families.

**Exit:** the architecture works with a simulation-driven real-world consumer and an independently authored fictional world.

---

# 23. Stage 17 — Design Evals, Benchmarks and Regression Fixtures

Separate:

- deterministic repository/artefact validation;
- spatial correctness;
- reference/reconstruction quality;
- modular/procedural quality;
- environment composition quality;
- runtime readiness;
- world-state representation;
- preservation and repair;
- Extension Pack behaviour;
- end-to-end production.

Extension Pack evaluation must include activation/non-activation, precedence, specialised source strategy, changed spatial/procedural behaviour, source-to-behaviour-to-test traceability, fair core-vs-pack comparisons, negative/incompatibility cases, preservation of intentional traits, rejection of actual defects and an additional reuse fixture beyond the showcase.

Priority regressions include wrong scale, coordinate drift, disconnected roads, repeated procedural blocks, state mismatch, provenance loss, asset-handoff mismatch, streaming boundary failure, invalid regeneration scope and hero-fidelity work before structural acceptance.

**Exit:** spatial, provenance, procedural, composition, runtime and pack failures can fail independently.

---

# 24. Stage 18 — Generate Six Canonical Specifications

Generate:

```text
docs/
├── 01-world-environment-production-skills-system-spec.md
├── 02-world-environment-production-skills-workflows-and-artifacts-spec.md
├── 03-world-environment-production-skills-repository-and-contracts-spec.md
├── 04-testing-and-benchmark-spec.md
├── 05-world-environment-production-customisation-packs-spec.md
└── 06-world-environment-production-extension-pack-catalogue.md
```

Responsibilities remain:

1. **System** — mission, boundaries, principles, core skills, execution, fidelity/commitment, world-state boundary and ownership.
2. **Workflows and Artifacts** — ingestion, spatial model, structure, blockout, modular/procedural production, assembly, runtime, preservation, repair and handoffs.
3. **Repository and Contracts** — layout, skills/commands, references/scripts/assets, tool integration, self-containment, installation and CI.
4. **Testing and Benchmark** — spatial, provenance, procedural, composition, runtime, state, preservation, packs, stress tests and installation.
5. **Customisation / Extension Packs** — qualification, dimensions, activation, precedence, production effects, packaging, evidence process, evaluation and authoring.
6. **Catalogue** — curated profiles with selection rationale, five-book foundation and source contributions, research-log references, qualified guidance, showcases/exact prompts, actual outputs when implemented, pack-specific acceptance cases, comparative evidence, clean-install evidence, limitations and separate research/implementation/evaluation/readiness status.

Generate from persisted research logs rather than conversation memory.

**Exit:** implementation can proceed without inventing architecture in code.

---

# 25. Stage 19 — Design Public README

Follow the family README structure adapted to world/environment production: positioning, capabilities, breadth/fidelity control, installation, Level 1 quick start, 5×3 examples, project structure, core skills, Extension Packs, execution tools, world-state boundary, evaluation, stress tests, docs, boundary, contributing and licence.

Do not claim engine/DCC/provider support until implemented and tested.

**Exit:** the public product surface is designed before scaffolding.

---

# 26. Stage 20 — Cross-Project Review

Compare the independently derived model with Game Development, 3D Production, Deep Research, Legal, UI/UX and mature creative Production Skills.

Record repeated concepts such as cheap representation, fidelity promotion, approved-decision preservation, provenance, cross-domain asset requirements, smallest-scope repair, pack semantics and clean installation without prematurely promoting a universal world graph, asset graph, spatial schema or provider runtime.

**Exit:** reusable evidence is captured without weakening domain terminology or boundaries.

---

# 27. Stage 21 — Scaffold Production Repository

Only now expand Stage 0 into the production scaffold justified by the six specs.

Likely baseline:

```text
world-environment-production-skills/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CHANGELOG.md
├── docs/
│   ├── 01-world-environment-production-skills-system-spec.md
│   ├── 02-world-environment-production-skills-workflows-and-artifacts-spec.md
│   ├── 03-world-environment-production-skills-repository-and-contracts-spec.md
│   ├── 04-testing-and-benchmark-spec.md
│   ├── 05-world-environment-production-customisation-packs-spec.md
│   ├── 06-world-environment-production-extension-pack-catalogue.md
│   └── research-logs/
├── skills/
├── examples/
├── benchmarks/
├── tests/
├── tools/                 # only when justified
├── extension-packs/       # once implemented
├── integrations/          # optional
└── .github/
```

Do not create engine-specific trees, GIS databases or asset catalogues for symmetry.

**Exit:** every production directory has an immediate role.

---

# 28. Stage 22 — Implement and Prove Core Vertical

Implement the minimum skill/command set for one meaningful end-to-end environment workflow:

```text
brief + references
→ spatial interpretation
→ cheap blockout
→ evaluation
→ bounded correction
→ modular / asset requirements
→ representative environment assembly
→ environment evaluation
```

Prefer a bounded location rather than a whole city.

**Exit:** installed core skills can produce and evaluate one realistic environment end to end.

---

# 29. Stage 23 — Expand Progressive Coverage and Extension Packs

Expand gradually to the 15 examples and representative packs.

For every implemented pack prove:

```text
core works without pack
core + pack changes intended production behaviour
explicit requirements and approved decisions outrank pack defaults
pack-aware evaluation recognises intentional specialisation without hiding defects
showcase has exact prompt and actual generated artefacts
additional reuse fixture demonstrates generality beyond the showcase
research / implementation / evaluation status is explicit
clean consumer-project installation succeeds
```

**Exit:** breadth and specialisation are demonstrated rather than only specified.

---

# 30. Stage 24 — Validate Installation and Repository Integrity

Validate repository contracts, skill self-containment, command discovery, selective installation, clean consumer-project installation, skill-local references/scripts/assets, tool prerequisites, benchmark entry points, example reproducibility and no undocumented source-checkout dependencies.

Keep local validation separate from clean external installation.

**Exit:** the repository behaves as an installable Agent Skills product.

---

# 31. Stage 25 — Optional Pactwright Integration and Registry Promotion

If useful, add `integrations/pactwright.yml` for compatibility and capability bindings only.

Worldstack's composition boundary remains:

```text
Pactwright
→ selected Agent Pack
→ one or more Production Skills
→ domain production
```

Production Skills owns domain workflow, artefacts, commands, tools and evaluation. Pactwright owns Contract fulfilment, lifecycle authority and Evidence. Consuming-project intelligence owns project-specific conclusions.

Maturity remains evidence-based:

```text
proposed
→ researching
→ specified
→ scaffolded
→ working
→ benchmarked
→ mature
```

Repository creation alone does not promote maturity.

**Exit:** Pactwright can resolve environment-production capability without becoming required by the repository.

---

# 32. Stage 26 — Review Shared-Abstraction Candidates

After implementation evidence exists, apply `shared-abstraction-process.md`.

Possible candidates include fidelity-promotion semantics, source/provenance handoff, asset-requirement handoff, spatial acceptance metadata and representation mapping.

Do not centrally promote a universal world graph, asset graph, spatial ontology, procedural runtime or environment evaluator without repeated independent evidence.

---

# 33. World / Environment Acceptance Gates

Before maturity, demonstrate:

### Research foundation

- a domain knowledge-coverage map exists;
- exactly five foundational books were selected through complementary coverage;
- supplied-book substitution decisions are explicit;
- source access and material actually examined are recorded;
- all five books have traceable per-book extraction;
- source-to-capability and overlap/conflict analysis exists;
- broader professional research challenges the corpus and fills material gaps;
- the resulting model is evidence-qualified and independently useful beyond Worldstack.

### Spatial production

- scale, topology and connectivity are explicitly represented where relevant;
- breadth can be proved before expensive detail;
- approved spatial structure survives unrelated refinements;
- source uncertainty and approximation remain visible;
- modular/procedural rules are inspectable and reproducible;
- manual overrides survive appropriate regeneration;
- environment-level runtime constraints are considered before final production.

### Cross-domain behaviour

- Game Development constraints shape layout without moving gameplay ownership here;
- 3D asset requirements can be handed off and reintegrated;
- Worldstack state can be represented without becoming environment-owned truth;
- Deep Research evidence and Legal provenance constraints survive handoff;
- project-specific world knowledge does not leak into reusable core skills.

### Extension Packs

- a broader candidate pool and catalogue coverage matrix exist;
- selected packs are production specialisations, not engine, biome or geography labels;
- every selected pack has a justified five-book corpus;
- per-pack extraction and challenge evidence is traceable;
- source-to-behaviour-to-test mapping exists;
- fair core-vs-pack comparisons use the same substantive brief and comparable conditions;
- an additional reuse fixture exists beyond each showcase;
- showcase prompts are not treated as implementation evidence;
- research, implementation, evaluation and readiness status remain separate;
- ready packs have clean-install evidence.

### Evaluation and product behaviour

- wrong scale, broken topology, provenance loss, procedural repetition, state mismatch and runtime defects can fail independently;
- local repair preserves unaffected approved world work;
- known failures become regression fixtures;
- both Worldstack and independent-fictional stress tests pass meaningful slices;
- core works without packs;
- 15 primary progressive examples exist with exact prompts;
- six canonical specification responsibilities exist;
- public README reflects implemented capability accurately;
- skills are self-contained;
- local and clean external installation pass;
- engine/provider claims are backed by implementation evidence.

The bootstrap must reject these false completion signals:

```text
five popular books with redundant coverage
bibliography presented as completed research
Worldstack documentation treated as the whole discipline
engine documentation treated as the whole professional workflow
books treated as measured geographic truth
one book → one skill
five books → five packs
city / forest / engine labels treated as sufficient packs
catalogue prompt presented as implementation evidence
pack directory presented as evaluation evidence
```

---

# 34. Initial Non-Goals

Until evidence proves otherwise, `world-environment-production-skills` is not:

- a game engine;
- a GIS platform;
- a digital-twin platform;
- a real-world simulation engine;
- a universal city generator;
- a universal procedural content engine;
- a 3D modelling replacement;
- an asset marketplace or asset database;
- a photogrammetry platform;
- a central world-state database;
- a universal spatial ontology;
- a universal scene graph;
- a provider/model router;
- a replacement for Game Development, 3D Production, Deep Research or Legal Skills;
- a Worldstack-specific implementation repository.

---

# 35. Success Criterion

This bootstrap succeeds if later sessions can execute each stage from persisted research logs without redesigning the project from first principles.

The resulting repository should make world/environment production:

```text
more spatially coherent
more evidence-aware
more provenance-aware
cheaper to validate before high fidelity
more modular and reproducible
more capable of mixing procedural and authored production
more disciplined about world breadth versus hero detail
more robust to changing simulation / project inputs
more precise about cross-domain handoffs
more efficient to diagnose and repair
```

while remaining a lean Agent Skills project rather than becoming a universal world-building platform before repeated production evidence justifies it.
