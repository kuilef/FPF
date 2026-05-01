# First Principles Framework (FPF) — Condensed AI-Ready Kernel

Source: `FPF-Spec.md`, April 2026, Anatoly Levenchuk with AI-agent assistance.

This compressed version is designed for fast human/AI orientation. It is **not** a normative replacement for the full specification. Use the original when exact conformance, pattern wording, evidence rules, boundary obligations, or publication authority matter.

## 1. One-sentence definition

FPF is an operating system for thought: a pattern language and working-form discipline for turning vague, high-stakes, multi-context reasoning into bounded contexts, explicit vocabularies, lawful comparisons, evidence gaps, responsibility boundaries, and durable outputs.

## 2. When FPF is worth using

Use FPF when at least one of these is true:

- work is split across specialists, teams, copilots, or AI agents;
- the real-world oracle is slow, expensive, noisy, risky, or delayed;
- different audiences need aligned views of the same underlying reasoning;
- vocabulary is unstable or overloaded;
- decisions need explicit criteria, alternatives, evidence, and auditability;
- state-of-the-art work must be handled as a portfolio, not a one-shot recommendation;
- solo or small-team reasoning still needs durable publication.

FPF is usually too heavy when the task is small, feedback is cheap, vocabulary is already stable, and no reusable reasoning form is needed.

## 3. What one pass should produce

A useful first pass should produce concrete artifacts, not only better intuition:

1. bounded-context map;
2. local vocabulary / starter UTS;
3. responsibility-boundary map;
4. decision criteria and comparison characteristics;
5. small lawful alternative set;
6. evidence/test gap list;
7. starter DRR, ADR, UTS, Claim Register, portfolio, selected set, or another burden-specific output;
8. aligned outputs for engineering, management, research, and assurance/audit readers.

## 4. Non-negotiable kernel ideas

- **Local meaning, explicit translation.** Terms live inside bounded contexts; cross-context reuse needs explicit bridges.
- **One reasoning body, many projections.** Engineering, management, research, and assurance outputs should be projections of the same underlying work.
- **Strict distinctions.** Object ≠ description ≠ carrier; role ≠ holder ≠ work; method ≠ method description ≠ work plan ≠ actual work.
- **Trust has structure.** Claims need formality, scope, reliability, evidence, carriers, and freshness.
- **Comparison is lawful only after characteristics/scales are declared.** Avoid hidden scalarization, illegal averaging, and premature total ordering.
- **Keep search wide before selection.** Use portfolios/fronts/sets before choosing a winner.
- **Build new concepts when categories break.** FPF is not just organizing existing terms; it supports first-principles synthesis.
- **Closure is local.** Bounded contexts create reliable islands inside an open world.

## 5. First practical entry families

| Situation | Typical first stabilizing result | First inspect |
|---|---|---|
| Project alignment | Separate responsibility, method, plan, and actual execution | `A.1.1`, `A.15`, `A.15.2`, `A.15.3`, `B.5.1`; optionally `F.11`, `F.9`, `F.17` |
| Partly-said / early language-state | Preserve cue, maturity, and routing burden before turning it into a claim | `C.2.2a`, `C.2.LS`, `C.2.4–C.2.7`, `A.16`, `A.16.1`, `A.16.2`, `B.4.1`, `B.5.2.0` |
| Boundary unpacking | Claim Register / atomic routed claims | `A.6`, `A.6.B`, `A.6.C`; add `A.6.RSIG`, `A.6.P`, `A.6.Q`, `A.6.A` as needed |
| Lawful comparison / selection | Declared characteristics, comparison frame, candidate-pool policy, selected-set publication | `A.17–A.19`, `A.19.CN`, `G.0`, `C.18`, `C.19`, `G.5`; `C.11` for local choice |
| Generator / SoTA / portfolio kit | Reusable search, harvest, generator, or portfolio scaffold | `A.0`, `G.0`, `G.1`, `G.2`, `G.5`; optionally `B.5.2.1`, `C.17–C.19` |
| Same-entity rewrite / explanation / comparative reading | Rewrite, explanation, repair note, or comparison without changing object-of-talk | `A.6.3.CR`, `A.6.3.RT`, `E.17.EFP`, `E.17.ID.CR`, `E.17.AUD.LHR`, `E.17.AUD.OOTD` |

## 6. Practical operating loop

Use this as a default work pattern; it is a useful scaffold, not a mandatory workflow.

1. **Frame the burden.** What must be decided, stabilized, compared, published, or delegated?
2. **Declare contexts.** Which bounded contexts use different meanings, criteria, or responsibilities?
3. **Separate object types.** Do not mix systems, roles, method descriptions, methods, plans, work, evidence, and publications.
4. **Name characteristics.** Define characteristics, scales, indicators, comparability, normalization, scoring, and aggregation rules before selection.
5. **Keep alternatives alive.** Generate a small portfolio, not a premature single winner.
6. **Route claims.** Boundary/legal/promise/evidence statements must be decomposed into atomic routed claims.
7. **Expose evidence gaps.** Mark missing tests, stale evidence, weak bridges, and unsupported assumptions.
8. **Publish a durable form.** Choose UTS, DRR, ADR, Claim Register, portfolio, selected set, or review note.
9. **Project views.** Render the same underlying reasoning differently for engineers, managers, researchers, and auditors without changing semantics.
10. **Reopen lawfully.** If evidence or language state changes, respecify, back off, or retire the earlier claim explicitly.

## 7. Minimal AI-assistant starter prompt

```text
You have the FPF specification as a file.
Help me structure [project/problem/programme].
Use plain language for an engineer-manager.
Propose:
1. bounded contexts / specialisations,
2. decision criteria,
3. key alternatives,
4. responsibility boundaries,
5. missing evidence or tests before commitment.
Introduce internal FPF names only when they add precision.
```

## 8. High-value AI prompt templates

### 8.1 Turn a vague project into decision criteria

```text
Using FPF, propose a step-by-step chain for characterising the objects of [project], normalising measurements, defining indicators, scoring alternatives, and choosing design decisions. Include omitted steps. Write for engineer-managers, not in FPF jargon.
```

### 8.2 Build a disciplined vocabulary / UTS

```text
Using FPF Part F, produce a Unified Term Sheet for [domain]: at least 10 rows. Distinguish Tech vs Plain names, show SenseCells for 2-3 bounded contexts, and flag risky aliases.
```

### 8.3 Name ambiguous roles/programmes/artifacts

```text
Using FPF naming-card discipline, develop a complete Name Card for [entity]. Do not assume current names are correct. Search the local Pareto front of candidate names and explain trade-offs.
```

### 8.4 Make principles-to-work explicit

```text
Using E.TGA and TEVB, unpack the canonical principles-to-work flow for [project]. Give nodes, kinds, and engineer-manager explanations. Then produce a mini Flow specification table.
```

### 8.5 Organise mixed humans + AI agents

```text
Using FPF, organise a mixed team of humans and AI agents for [project]. Propose contexts, local vocabularies, roles, bridges, responsibility-boundary artifacts, decision gates, autonomy budgets, escalation paths, and human approval points.
```

### 8.6 Build a state-of-the-art portfolio

```text
Using FPF Part G, search the state of the art in [discipline]. Extract competing schools of thought, operator/update rules, scope boundaries, evidence, failure modes, and a selector-ready portfolio. Start with TraditionCards only.
```

## 9. Compression boundary

This file preserves orientation, entry selection, core invariants, AI-use patterns, and a compact pattern index. It deliberately removes most normative clauses, archetypal groundings, conformance checklists, anti-pattern details, rationale sections, and SoTA-echoing evidence tables. For exact pattern use, reopen the full `FPF-Spec.md`.

---

# Compact Pattern Index

Format: `ID — Title [Status] — high-signal reminder/keywords`.

## Preface

- What this specification is (and how to use it) [full text] — A practical orientation to the Core Conceptual Specification: what FPF is, what kinds of artefacts/patterns it defines, how Parts A–K fit together, and where to start for different reader roles.
- Creativity in Open-Ended Evolution and Assurance* [full text] — FPF integrates assurance (audits, evidence) and creativity (generating novel ideas) as complementary engines for responsible innovation, providing a structured choreography for creative work from abduction to operation.
- Navigating Uncertainty: Building Closed Worlds within an Open World [full text] — Explains how FPF reconciles Open-World and Closed-World assumptions, using Bounded Contexts to create reliable 'islands of closure' for engineering decisions within an inherently open world.
- FPF as an Evolutionary Architecture for Thought [full text] — Positions FPF as an architecture for the reasoning process itself, designed to sustain key characteristics like auditability, evolvability, and falsifiability by applying architectural thinking to the dynamics of reas…
- Architectural Characteristic of Thought [full text] — Details the key characteristics of rigorous thought (e.g., Auditability, Evolvability, Composability) and the specific FPF mechanisms designed to preserve them.
- Beyond Cognitive Biases: FPF as a Generative Architecture for Thought [full text] — Contrasts FPF's generative, structural approach to avoiding cognitive errors with the traditional corrective, diagnostic approach of hunting for biases, framing FPF as a scaffold that makes errors harder to commit.
- Thinking Through Writing: The FPF Discipline of Conceptual Work [full text] — Describes how FPF uses a discipline of "thinking through writing" with conceptual forms (Cards, Tables, Records) to make thought tangible, shareable, and auditable, while remaining tool-agnostic.
- Descriptive Ontologies vs. A Thinking-Oriented Architecture [full text] — Differentiates FPF's goal of orchestrating reasoning from classical ontologies' goal of cataloging existence, emphasizing FPF's focus on objectives, trust, and dynamics.
- The "Bitter Lesson" trajectory — compute, data, and freedom over hand‑tuned rules (FPF stance) [full text] — How FPF operationalizes the contemporary trend: prefer general models + data + compute + minimal constraints; autonomy budgets; rule‑of‑constraints vs instruction‑of‑procedure; continuous adaptation.
- From Flat Documents to High-Dimensional Truth: The Multi-View Architecture [full text] — Shows how FPF replaces flat documents with a multi-view architecture: epistemes as slot graphs, engineering views as projections, and MVPK as typed publication surfaces that keep dashboards lawfully tethered to work a…
- Boundary Statements: Where Language Becomes a System Boundary [full text] — Introduces the A.6 boundary cluster: why certain sentences behave like contracts, and how routing (laws vs gates vs duties vs evidence) keeps them evolvable and multi-view safe.
- Raising Semantic Precision: From Triggers to Math‑Backed Ontics [full text] — Describes the precision-upgrade workflow behind A.6.P: detect umbrella words, unpack the local ontology, choose a stable mathematical substrate, refactor the model, and mint precise lexemes + guardrails (Tech/Plain tw…
- The “big storylines” unique to FPF (load‑bearing commitments) [full text] — Lists the nine core, load-bearing commitments that define FPF's unique architectural and philosophical stance, from its holonic kernel to its explicit treatment of creativity and assurance.
- Transdisciplinarity as a Meta‑Theory of Thinking [full text] — Explains how FPF treats transdisciplinarity as a meta-theory for designing reasoning, using FPF patterns as generative scaffolds grounded in physical reality to bridge disciplinary silos.
- FPF as a Culinary Architecture for Collective Thought: Why We Formalize “Obvious” Ideas [full text] — Uses the 'culinary architecture' analogy to explain FPF's role in synthesizing 'obvious' ideas into a robust framework for complex, generative problems.
- Intellect Stack (informative Overview) [full text] — Presents a five-layer pedagogical map of cognitive skills (Structure → Knowledge → Action → Strategy → Governance) and links them to FPF patterns.
- Purpose, Scope, and Explicit Non‑Goals [full text] — Clarifies FPF's mission as a generative scaffold for thought, its scope as tool-agnostic normative patterns, and what it explicitly is not (e.g., a domain encyclopedia or a specific methodology).

## Part A - Kernel Architecture Cluster

- `A.0` — Onboarding Glossary (NQD & E/E‑LOG) [Stable] — novelty, quality-diversity (NQD), explore/exploit (E/E-LOG), declared set surface, typed portfolio publication, SearchSpaceRef, OutcomeSpaceRef, CrossSurfaceSupportView, TypedSetViews, ParetoOnly default, scale-probe,…

### Cluster A.I - Foundational Ontology

- `A.1` — Holonic Foundation: Entity → Holon [Stable] — part-whole composition, system boundary, entity, holon, U.System, U.Episteme
- `A.1.1` — U.BoundedContext: The Semantic Frame [Stable] — local meaning, context, semantic boundary, domain, invariants, glossary, DDD
- `A.2` — Role Taxonomy [Stable] — role, assignment, holder, context, function vs identity, responsibility, U.RoleAssignment
- `A.2.1` — U.RoleAssignment: Contextual Role Assignment [Stable] — Standard, holder, role, context, RoleEnactment, RCS/RSG
- `A.2.2` — U.Capability: System Ability (dispositional property) [Stable] — ability, skill, performance, action, work scope, measures
- `A.2.3` — U.PromiseContent: Consumer‑facing Promise Clause [Stable] — promise content, promise content, accessSpec, acceptanceSpec, SLO, SLA, claim scope (G), Work evidence, provider/consumer roles
- `A.2.4` — U.EvidenceRole: The Evidential Stance [Stable] — evidence, claim, support, justification, episteme
- `A.2.5` — U.RoleStateGraph: The Named State Space of a Role [Stable] — state machine, RSG, role state, enactability, lifecycle
- `A.2.6` — Unified Scope Mechanism (USM): Context Slices & Scopes [Stable] — scope, applicability, ClaimScope (G), WorkScope, set-valued
- `A.2.7` — U.RoleAlgebra: In-Context Role Relations (≤, ⊥, ⊗) [Stable] — role algebra, specialization (≤), incompatibility (⊥), bundles (⊗), separation of duties (SoD), requiredRoles substitution
- `A.2.8` — U.Commitment: Deontic Commitment Object [Stable] — commitment, deontics, obligation/permission/prohibition, modality normalization, scope+validity window, adjudication hooks, evidenceRefs, BCP‑14 (RFC 2119/8174)
- `A.2.9` — U.SpeechAct: Communicative Work Object [Stable] — speech act, communicative work, approval/authorization/publication/revocation, provenance, act≠utterance≠carrier, judgement context, window/freshness, institutes.*

### Cluster A.II - Transformation Engine

- `A.3` — Transformer Constitution (Quartet) [Stable] — action, causality, change, System-in-Role, MethodDescription, Method, Work
- `A.3.1` — U.Method: The Abstract Way of Doing [Stable] — recipe, how-to, procedure, abstract process
- `A.3.2` — U.MethodDescription: The Recipe for Action [Stable] — specification, recipe, SOP, code, model, epistemic artifact
- `A.3.3` — U.Dynamics: The Law of Change [Stable] — state evolution, model, simulation, state space

### Cluster A.III - Time & Evolution

- `A.4` — Temporal Duality & Open-Ended Evolution Principle [Stable] — design-time, run-time, evolution, versioning, lifecycle, continuous improvement

### Cluster A.IV - Kernel Modularity

- `A.5` — Open-Ended Kernel & Extension Layering [Transitional stub] — FPF architecture, specialization vs dependancy hierarhies, modularity, extensibility

### Cluster A.IV.A - Signature Stack & Boundary Discipline (A.6.)

- `A.6` — Signature Stack & Boundary Discipline [Stable] — boundary, signature stack, boundary route fields, laws, admissibility, deontics, evidence, probe/order/frame/export claims, state-reading claims
- `A.6.RSIG` — Recognition Signatures for Descriptions [Stable] — description-recognition signature; encountered carrier vs authoritative home; API/access description not promise; method applicability note; false neighboring description
- `A.6.B` — Boundary Norm Square (Laws / Admissibility / Deontics / Work-Effects) [Stable] — boundary norm square, atomic claims, L/A/D/E routing, laws vs gates vs commitments vs evidence, supported use, unsupported use, claim IDs, triangle decomposition
- `A.6.C` — Contract Unpacking for Boundaries [Stable] — contract bundle unpacking, SLA/guarantee routing, promise content (promise content) ≠ work, promise-act/utterance/commitment separation, Boundary Norm Square (L/A/D/E), MVPK faces “no new semantics”
- `A.6.0` — U.Signature — Universal, law‑governed declaration [Stable] — signature, vocabulary, laws, applicability, bounded context
- `A.6.1` — U.Mechanism - Law‑governed application to a SubjectKind over a BaseType [Stable] — Mechanism, OperationAlgebra, LawSet, AdmissibilityConditions, Transport, Bridge‑only. Queries: "How to define a mechanism like USM/UNM?", "Where do operational guards live?", "How to handle cross‑context transport?"
- `A.6.2` — U.EffectFreeEpistemicMorphing — Effect-Free Morphisms of Epistemes [Stable] — episteme, effect-free, morphism, functoriality, describedEntity, lenses, reproducibility
- `A.6.3` — U.EpistemicViewing — describedEntity-Preserving Morphism [Stable] — episteme, view, EpistemicViewing, describedEntity preservation, ClaimGraph, Viewpoint, RepresentationScheme, CorrespondenceModel, Direct vs Correspondence Viewing, optics, displayed fibration
- `A.6.3.CSC` — Controlled Semantic Coarsening [Stable] — controlled semantic coarsening, stronger source, weaker rendering, narrower supported use, unsupported heavier use, reopen trigger, redaction, dashboard tile, lookup handle, state-representation shortcut
- `A.6.3.CR` — ConservativeRetextualization - same-described-entity textual re-expression [Stable] — retextualization, summary, report rewrite, translation, filtering, same-described-entity textual re-expression, direct vs correspondence-mediated rewrite, source tether
- `A.6.3.RT` — RepresentationTransduction - same-described-entity representation-scheme transition [Stable] — representation transduction, table, diagram, notation shift, reasoning medium, recoverability, same-described-entity representation change, source tether, state-representation shortcut
- `A.6.4` — U.EpistemicRetargeting — describedEntity-Retargeting Morphism [Stable] — retargeting, subject retargeting, describedEntity shift, KindBridge, SquareLaw-retargeting, StructuralReinterpretation
- `A.6.P` — U.RelationalPrecisionRestorationSuite — Relational Precision Restoration (RPR) — Kind-Explicit Qualified Relation Discipline [Stable] — relation precision restoration, under-specified relational language, RelationKind, QualifiedRelationRecord, coupling, probe, measurement, export, endpoint referential compression, lexical guardrails, language-state seam
- `A.6.Q` — U.QualityTermPrecisionRestoration — Quality Term Precision Restoration (Q-TERM) [Stable] — quality-term precision restoration, evaluative ascription, quality senses, endpoint routing, bridge reading, language-state seam
- `A.6.A` — U.ActionInvitationPrecisionRestoration — Affordance / Action-Invitation Precision Restoration (ACT-INV) [Stable] — affordance, action invitation, action-first language, post-threshold routing, A.15 docking, language-state seam
- `A.6.5` — U.RelationSlotDiscipline - SlotKind / ValueKind / RefKind discipline for n‑ary relations (with slot‑operation lexicon) [Stable] — slot, argument position, value, reference, signature, substitution, pass-by-value, pass-by-reference
- `A.6.6` — U.BaseDeclarationDiscipline - Kind-explicit, scoped, witnessed base declaration discipline (with base-change lexicon) [Stable] — base declaration, basedness, baseRelation, SWBD, witnesses, scope, Γ_time, anchoring, rebase, retime, rescope
- `A.6.7` — MechSuiteDescription — Description of a set of distinct mechanisms [Stable] — mechanism suite, distinct mechanisms, suite obligations, contract pins, CN-Spec, CG-Spec, P2W, planned baseline, crossing visibility
- `A.6.8` — Service Polysemy Unpacking (RPR-SERV) [Stable] — service polysemy, service situation, interface semantics, promise content, provider principal, service/cell analogy, boundary exchange, viability envelope, API read/export
- `A.6.9` — U.CrossContextSamenessDisambiguation — Repairing cross-context “same / equivalent / align” via explicit Bridges (RPR-XCTX) [Stable] — cross-context sameness, bridge, alignment, mapping, direction, substitution licence, loss notes, CL, SenseCells, weakest-link
- `A.6.S` — U.SignatureEngineeringPair — Constructive signature engineering (ConstructorSignature + TargetSignature) [Stable] — signature engineering, TargetSignature, ConstructorSignature, two-signature arrangement, EFEM, editioning, retargeting, slot/base change lexicon, MVPK views (no new semantics), claim register, no epistemic agency
- `A.6.H` — Wholeness Language Unpacking (RPR-WHOLE) [Stable] — wholeness, integrity, part-of, boundary, environment, mereology, completeness, order/time, artefact–referent level, role–method–work

### Cluster A.V - Constitutional Principles of the Kernel

- `A.7` — Strict Distinction (Clarity Lattice) [Stable] — category error, Object ≠ Description, Role ≠ Work, ontology
- `A.8` — Universal Core (C-1) [Stable] — universality, transdisciplinary, domain-agnostic, generalization
- `A.9` — Cross-Scale Consistency (C-3) [Stable] — composition, aggregation, holarchy, invariants, roll-up
- `A.10` — Evidence Graph Referring (C-4) [Stable] — evidence, traceability, audit, provenance, evidence carrier, claim support, probe evidence, distributed-state evidence, export evidence, viability evidence, SCR/RSCR
- `A.11` — Ontological Parsimony (C-5) [Stable] — minimalism, simplicity, Occam's razor, essential concepts
- `A.12` — External Transformer & Reflexive Split (C-2) [Stable] — causality, agency, self-modification, external agent, control loop
- `A.13` — The Agential Role & Agency Spectrum [Stable] — agency as role, agency spectrum, contextual role assignment, autonomy grading, substrate-neutral autonomy
- `A.14` — Advanced Mereology: Components, Portions, Aspects & Phases [Stable] — mereology, part-of, ComponentOf, PortionOf, PhaseOf, composition
- `A.15` — Role-Method-Work Alignment (Contextual Enactment) [Stable] — role-method-work split, U.WorkPlan vs U.Work, contextual enactment, coordinated-work evidence, distributed-state reading, checkpoint return, weakened briefing, work authority
- `A.15.1` — U.Work: The Record of Occurrence [Stable] — execution, event, run, actuals, log, occurrence
- `A.15.2` — U.WorkPlan: The Schedule of Intent [Stable] — plan, schedule, intent, forecast
- `A.15.3` — SlotFillingsPlanItem — Planned Slot-Fillings Baseline (WorkPlanning PlanItem) [Stable] — planned baseline, slot owner, planned filler, edition pins, Γ_time selector, guard pins, WorkPlanning, P2W seam, variance trail
- `A.16` — Language-State Transduction Coordination [Stable] — language-state, transduction, lawful moves, reopen, sketch-backoff, respecify, retire, handoff
- `A.16.0` — U.LanguageStateTransductionTrajectory — Optional trajectory-account normal form [Stable] — trajectory account, lineage, fork, merge, supersedes, handoff, heavy history
- `A.16.1` — U.PreArticulationCuePack [Stable] — cue pack, pre-articulation, early publication, cue nucleus, primary witness, route pressure
- `A.16.2` — Reopen / SketchBackoff / Respecify [Stable] — reopen, backoff, respecify, retire, retreat, branch withdrawal, authority withdrawal
- `A.17` — A.CHR-NORM — Canonical “Characteristic” & rename (Dimension/Axis → Characteristic) [Stable] — characteristic, measurement, property, attribute, dimension, axis
- `A.18` — A.CSLC-KERNEL — Minimal CSLC in Kernel (Characteristic/Scale/Level/Coordinate) [Stable] — CSLC, Characteristic, Scale, Level, Coordinate, polarity, ordinal vs cardinal scale, one-characteristic-one-scale rule, lawful comparability, no illegal averaging, measurement interpretability
- `A.19` — CharacteristicSpace & Dynamics Hook (A.CHR-SPACE) [Stable] — CharacteristicSpace, U.Dynamics.stateSpace, state trajectories, declared Characteristics and Scales, subspace, embedding, product, structural overlays, coordinatewise comparability, role-specific space refs stay outsi…
- `A.19.SURF-SPACE` — Cross-Surface / Cross-Space Substrate [Stable] — source surface, search-side space ref, outcome-side space ref, cross-surface substrate, SpaceRefRelationKind, SourceToOutcomeRelation, DistortionPosture, SourceSurfaceId, sameDeclaredSpaceAs, distinctDeclaredSpaceFrom
- `A.19.SUPPORT-VIEW` — Cross-Surface Support View [Stable] — support view, thin support, atlas support, CrossSurfaceSupportView, CrossSurfaceAtlasView, TraditionAtlasView, TypedSetViews, support qualifiers, support-only reading
- `A.19.CN` — CN-frame (comparability & normalization) [Stable] — CN-frame, CN-Spec, chart, comparability modes, normalization refs, indicator policy refs, Γ-fold governance, registry, bridges, CL/loss notes, WLNK discipline, conformance checklist, SCR/RSCR harness, RSG admission hooks
- `A.19.CHR` — CHRMechanismSuite — CHR mechanism-suite anchor (suite obligations + P2W planned baseline) [Stable] — CHR suite, characterization core, CN-Spec, CG-Spec, legality gate, suite obligations, set-return selection, tri-state guard decision, crossing visibility, Bridge-only transport, penalties→R_eff, planned baseline, Slot…
- `A.19.UNM` — Unified Normalization Mechanism (UNM) [Stable] — normalization, CV→NCV, ≡_UNM, NormalizationMethodId, NormalizationMethodInstanceId, NormalizationInvariant[*], NormalizationFixSpec, validity window (no implicit “latest”), fail-closed tri-state guard (pass
- `A.19.UINDM` — Unified Indicatorization Mechanism (UINDM) [Stable] — indicatorization, indicator set, IndicatorChoicePolicy, CN-Spec.indicator_policy, CHR suite stage indicatorize, tri-state admissibility (pass
- `A.19.USCM` — Unified Scoring Mechanism (USCM) [Stable] — scoring, score profile, ScoringMethodDescription, ScaleComplianceProfile (SCP), CSLC-lawful transforms, CG-Spec.MinimalEvidence, tri-state admissibility (pass
- `A.19.ULSAM` — Unified Lawful Scale Aggregation Mechanism (ULSAM) [Stable] — lawful aggregation, scale-lawful fold, fold_Γ?, ΓFoldRef, CG-Spec.Γ_fold, CG-Spec.SCP, MinimalEvidence, tri-state guard (pass
- `A.19.CPM` — Unified Comparison Mechanism (CPM) [Stable] — comparison, comparator, ComparatorSpecRef, ComparatorSet, set-valued comparison outcome, partial order, tri-state admissibility (pass
- `A.19.SelectorMechanism` — Unified Selection Kernel (SelectorMechanism) [Stable] — selection kernel, set-returning selection, selected set, SelectEligibility, tri-state guard (pass
- `A.20` — U.Flow.ConstraintValidity — Eulerian [Stable] — flow, ConstraintValidity, Eulerian, TransductionFlow, GateFit, MVPK, SquareLaw, Sentinel, PathSlice
- `A.21` — GateProfilization: OperationalGate(profile) (GateFit core) [Stable] — OperationalGate, GateFit, GateProfile, GateChecks, join-semilattice, GateDecision, DecisionLog, EquivalenceWitness, LaunchGate, CV⇒GF

## Part B — Trans-disciplinary Reasoning Cluster

- `**B.1**` — Universal Algebra of Aggregation (Γ) [Stable] — aggregation, composition, holon, invariants, IDEM, COMM, LOC, WLNK, MONO, gamma operator
- `B.1.1` — Dependency Graph & Proofs [Stable] — dependency graph, proofs, structural aggregators, sum, set, slice
- `B.1.2` — System-specific Aggregation Γ_sys [Stable] — system aggregation, physical systems, mass, energy, boundary rules, Sys-CAL
- `B.1.3` — Γ_epist — Knowledge-Specific Aggregation [Stable] — knowledge aggregation, epistemic, provenance, trust, KD-CAL
- `B.1.4` — Contextual & Temporal Aggregation (Γ_ctx & Γ_time) [Stable] — temporal aggregation, time-series, order-sensitive, composition
- `B.1.5` — Γ_method — Order-Sensitive Method Composition & Work Enactment [Stable] — method composition, workflow, sequential, concurrent, plan vs run
- `B.1.6` — Γ_work — Work as Spent Resource [Stable] — work, resource aggregation, cost, energy consumption, Resrc-CAL
- `**B.2**` — Meta-Holon Transition (MHT): Recognizing Emergence and Re-identifying Wholes [Stable] — emergence, MHT, meta-system, new whole, synergy, system of systems
- `B.2.1` — BOSC Triggers [Draft] — BOSC, triggers for emergence, boundary, objective, supervisor, complexity
- `B.2.2` — MST (Sys) — Meta-System Transition [Stable] — system emergence, super-system, physical emergence
- `B.2.3` — MET (KD) — Meta-Epistemic Transition [Stable] — knowledge emergence, meta-theory, paradigm shift, scientific revolution
- `B.2.4` — MFT (Meta-Functional Transition) [Stable] — functional emergence, capability emergence, adaptive workflow, new process
- `B.2.5` — Supervisor–Subholon Feedback Loop [Stable] — control architecture, feedback loop, supervisor, stability, layered control
- `B.3` — Trust & Assurance Calculus (F–G–R with Congruence) [Stable] — trust, assurance, reliability, F-G-R, formality, scope, congruence, evidence, claim-strength posture, probe/distributed/export assurance
- `B.3.1` — Components & Epistemic Spaces [Draft] — F-G-R components, measurement templates, epistemic space
- `B.3.2` — Evidence & Validation Logic (LOG-use) [Draft] — verification, validation, confidence, logic, proof
- `B.3.3` — Assurance Subtypes & Levels [Stable] — assurance levels, L0-L2, TA, VA, LA, typing, verification, validation
- `B.3.4` — Evidence Decay & Epistemic Debt [Stable] — evidence aging, decay, freshness, epistemic debt, stale data
- `B.3.5` — CT2R-LOG — Working-Model Relations & Grounding [Stable] — grounding, constructive trace, working model, assurance layer, CT2R, Compose-CAL
- `**B.4**` — Canonical Evolution Loop [Stable] — evolution loop, design/run feedback, observe-notice-stabilize-route, drift repair, open-ended evolution
- `B.4.1` — Observe -> Notice -> Stabilize -> Route [Draft] — routed cue set, route plurality, route selection, pre-abductive seam, task-family specialization route
- `B.4.2` — Knowledge Instantiation [Stub] — theory refinement, knowledge evolution, scientific method
- `B.4.3` — Method Instantiation [Stub] — adaptive workflow, process improvement, operational evolution
- `**B.5**` — Canonical Reasoning Cycle [Stable] — reasoning, problem-solving, Abduction-Deduction-Induction, scientific method
- `B.5.1` — Explore → Shape → Evidence → Operate [Stable] — development cycle, lifecycle, state machine, Explore, Shape, Evidence, Operate
- `B.5.2` — Abductive Loop [Stable] — abduction, explanatory prompt, candidate hypotheses, plausibility filters, origin trace, route-to-hypothesis
- `B.5.2.0` — U.AbductivePrompt [Draft] — abductive prompt, prompt species, rival-set discipline, threshold crossing, explanation-ready cue
- `B.5.2.1` — Creative Abduction with NQD [Stable] — creative abduction, NQD binding, Γ_nqd.generate, Creativity-CHR, Q-front, declared Q components, retained exploration/archive evidence, Novelty@context, ΔDiversity_P, E/E-LOG, DecisionSubject note
- `B.5.3` — Role-Projection Bridge [Stable] — domain-specific vocabulary, concept bridge, mapping, terminology
- `**B.6**` — Characterisation Families (CHR-use) [Draft] — characterization, templates, CHR patterns, measurement
- `**B.7**` — Common Logic Suite (LOG-use) [Draft] — logic, inference, trust propagation, LOG-CAL

## Part C — Kernel Extension Specifications


### Cluster C.I – Core CALs / LOGs / CHRs

- `C.1` — Sys‑CAL [Draft] — physical system, composition, conservation laws, energy, mass, resources, U.System
- `C.2` — KD‑CAL [Stable] — knowledge, epistemic, evidence, trust, assurance, F-G-R, Formality, ClaimScope, Reliability, provenance
- `C.2.1` — U.Episteme — Epistemes and their slot graph [Stable] — episteme, EpistemeSlotGraph, DescribedEntitySlot, GroundingHolonSlot, ClaimGraphSlot, ViewpointSlot, ReferenceScheme, RepresentationScheme, View/Viewpoint
- `C.2.2` — Reliability R in the F–G–R triad [Stable] — Reliability (R), warrant, evidence-bound, F–G–R, ClaimScope (G), Bridge-only reuse, Congruence Level (CL / CL^k / CL^plane), weakest-link, pathwise justification (PathId), TA/VA/LA lanes, no implicit averaging
- `C.2.2a` — U.LanguageStateSpace — Language-state chart over U.CharacteristicSpace [Stable] — language-state chart, characteristic space, position claim, partial coordinates, thresholds, governed episteme publication
- `C.2.3` — Unified Formality Characteristic F [Stable] — Formality, F-scale, F0-F9, rigor, proof, specification, language-state separation
- `C.2.LS` — U.LanguageStateFacetProfile — Thin owner for language-state facets [Stable] — facet profile, articulation, closure, anchoring, representation factors, threshold package
- `C.2.4` — U.ArticulationExplicitness [Draft] — articulation explicitness, semantic shape, weak cue, explicitness, early repair readiness
- `C.2.5` — U.LanguageStateClosureDegree [Draft] — closure degree, candidate-space closure, reopen, rival routes, settledness
- `C.2.6` — U.LanguageStateAnchoringMode [Draft] — anchoring mode, embodiment, trace, model state, document, operator loop
- `C.2.7` — U.LanguageStateRepresentationFactorBundle [Draft] — representation factors, locality, sparsity, symbolicity, factor bundle, representation organization
- `C.3` — Kind‑CAL — Kinds, Intent/Extent, and Typed Reasoning [Stable] — kind, type, intension, extension, subkind, typed reasoning, classification, vocabulary
- `C.3.1` — U.Kind & U.SubkindOf (Core) [Stable] — kind, subkind, partial order, type hierarchy
- `C.3.2` — KindSignature (+F) & Extension/MemberOf [Stable] — KindSignature, intension, extension, MemberOf, Formality F, determinism
- `C.3.3` — KindBridge & CL^k — Cross‑context Mapping of Kinds [Stable] — KindBridge, type-congruence, CL^k, cross-context mapping, R penalty
- `C.3.4` — RoleMask — Contextual Adaptation of Kinds (without cloning) [Stable] — RoleMask, context-local adaptation, constraints, subkind promotion
- `C.3.5` — KindAT — Intentional Abstraction Facet for Kinds (K0…K3) [Stable] — KindAT, abstraction tier, K0-K3, informative facet, planning
- `C.3.A` — Typed Guard Macros for Kinds + USM (Annex) [Stable] — Typed guard, ESG, Method-Work, USM, Kind-CAL, regulatory profile
- `C.4` — Method‑CAL [Draft] — method, recipe, procedure, workflow, SOP, MethodDescription, operator
- `C.5` — Resrc‑CAL [Draft] — resource, energy, material, information, cost, budget, consumption, Γ_work
- `C.6` — LOG‑CAL – Core Logic Calculus [Draft] — logic, inference, proof, modal logic, trust operators, reasoning
- `C.7` — CHR‑CAL – Characterisation Kit [Draft] — characteristic, property, measurement, metric, quality

### Cluster C.II – Domain‑Specific Patterns

- `C.9` — Agency‑CHR [Draft] — agency, agent, autonomy, decision-making, active inference
- `C.10` — Norm‑CAL [Draft] — norm, constraint, ethics, obligation, permission, deontics
- `C.11` — Decision Theory (Decsn-CAL) [Stable] — decision theory, DecisionSubject, OptionSet, comparison basis, ChoiceRule, ChoiceResult, question order, probe-worthiness, non-shared comparison frame, ValueOfInformation, ValueOfComputation, choose now, reject curren…

### Cluster C.III – Meta‑Infrastructure CALs

- `C.12` — ADR‑Kind-CAL [Draft] — versioning, rationale, DRR, architecture decision record
- `C.13` — Compose‑CAL — Constructional Mereology [Stable] — mereology, part-whole, composition, sum, set, slice, extensional identity

### Cluster C.IV – Composite & Macro‑Scale

- `C.14` — M‑Sys‑CAL [Draft] — system-of-systems, infrastructure, large-scale systems, orchestration
- `C.15` — M‑KD‑CAL [Draft] — paradigm, scientific discipline, meta-analysis, knowledge ecosystem
- `C.16` — MM-CHR — Measurement & Metrics Characterization [Stable] — measurement, measurement template, U.DHCMethod(Ref), U.Measure, U.Unit, U.EvidenceStub, polarity, direct comparability, scoring method disclosure, probe-changing-state, shared-frame check, CSLC
- `C.17` — Creativity‑CHR — Characterising Generative Novelty & Value [Stable] — Creativity-CHR, Novelty@context, Use-Value / ValueGain, Surprise, ConstraintFit, Diversity_P, Originality, ResourceEfficiency, MM-CHR measurement templates, ReferenceBase, evidence, portfolio composition
- `C.18` — NQD‑CAL — Open‑Ended Search Calculus [Stable] — NQD-CAL, Γ_nqd.generate, Γ_nqd.updateArchive, Γ_nqd.illuminate, Γ_nqd.selectFront, DescriptorMapRef, DistanceDefRef, NQDArchive, CandidateSet, Front vs ExplorationArchive, IlluminationSummary report-only telemetry, Em…
- `C.18.1` — SLL — Scaling‑Law Lens (binding) [Stable] — scaling law, scale variables (S), compute‑elasticity, data‑elasticity, resolution‑elasticity, exponent class, knee, diminishing returns
- `C.19` — Explore–Exploit Governor (E/E‑LOG) [Stable] — explore-exploit, live candidate pool, pool-policy result, widen, keep frontier, narrow to subset, sunset line, reroute, EmitterPolicy, InsertionPolicy, lens id, dominance default routing, DecisionSubject clarification
- `C.19.1` — Bitter‑Lesson Preference (BLP) [Stable] — Bitter Lesson, scale-audit, BLP-waiver, α/δ tolerances, task-family specialization
- `C.20` — Discipline‑CAL — Composition of U.Discipline [Stable] — discipline, U.AppliedDiscipline, U.Transdiscipline, episteme corpus, standards, institutions, Γ_disc
- `C.21` — Discipline‑CHR - Field Health & Structure [Stable] — discipline, field health, reproducibility, standardisation, alignment, disruption
- `C.22` — Problem Typing & TaskSignature Assignment (Problem‑CHR) [Stable] — Problem‑CHR, TaskSignature, TaskKind, ScopeSlice(G), unknown handling, specialization anchor
- `C.22.1` — Task-family adaptation signature [Stable] — adaptation signature, time-to-threshold, budget-to-threshold, prior exposure, corridor entry, stepping stone
- `C.23` — Method‑SoS‑LOG — MethodFamily Evidence & Maturity [Stable] — MethodFamily, evidence, maturity, SoS-LOG, admit, degrade, abstain, selector
- `C.24` — Agentic Tool‑Use & Call‑Planning (C.Agent‑Tools‑CAL) [Stable] — agential tool use, CallRouteDescription, CallPlan, CallGraph, CheckpointReturn, enactment budget, tool-call budget, stop/replan condition, budget and harm gates, BLP tolerances, route-vs-plan-vs-work distinction
- `C.25` — Q-Bundle: Authoring "-ilities" as Structured Quality Bundles [Stable] — quality bundle, -ility, quality family, characteristic plus scope, mechanism/status slots, endpoint routing, viability envelope, proxy metric, supported use, failure mode
- `C.26` — Quantum-Like Modeling Lens [Stable] — quantum-like, QL-lite, QL-NQ, probe frame, order effect, incompatible probes, instrument update, state export, supported coarsening, weakest supported output
- `C.26.1` — Probe-Coupled Boundary Interaction [Stable] — probe-coupled boundary, passive read, dashboard as instrument, workshop as state-changing interaction, API read, survey, bridge result, export loss, evidence window
- `C.26.2` — Enacted Distributed State Evidence [Stable] — distributed-state evidence, coordinated work, enacted state, weak state reading, evidence carrier, window, rival explanation, no group mind, report/export loss
- `C.26.3` — Viability-Envelope Boundary Regulation [Stable] — viability envelope, homeostasis, allostasis, boundary regulation, sensor/probe/actuator split, metric-induced distortion, service viability, quality bundle, failure mode
- `C.27` — Temporal Claim Adequacy: State Readings, Temporal Trends, and Intervention-Sensitive Temporal Change [Stable] — temporal claim adequacy, temporal claim, state reading, rate reading, temporal trend, rate-change, intervention-sensitive temporal change, effort window, resistance/inertia, rhythm/cadence, throughput, recovery, braki…

## Part D – Multi-scale Ethics & Conflict-Optimisation

- `**D.1**` — Axiological Neutrality Principle [Stub] — axiology, values, ethics, neutrality, morals, preference lattice, objective function
- `**D.2**` — Multi-Scale Ethics Framework [Stub] — ethics, scale, levels, scope, responsibility, agent, team, ecosystem, planet
- `D.2.1` — Local-Agent Ethics [Stub] — individual ethics, duties, permissions, agent, system
- `D.2.2` — Group-Ethics Standards [Stub] — collective norms, team ethics, veto, subsidiarity
- `D.2.3` — Ecosystem Stewardship [Stub] — externalities, tragedy of the commons
- `D.2.4` — Planetary-Scale Precaution [Stub] — catastrophic risk, long-termism, precautionary principle
- `**D.3**` — Holonic Conflict Topology [Stub] — conflict, clash, disagreement, resolution, resource conflict, goal conflict, epistemic conflict
- `D.3.1` — Conflict Detection Logic (LOG-use) [Stub] — conflict detection, logic, predicates, conflictsWith
- `D.3.2` — Conflict Routing Protocol [Stub] — routing, mediation, negotiation, DRR, appeals
- `**D.4**` — Trust-Aware Mediation Calculus [Stub] — mediation, negotiation, conflict resolution, trust score, assurance, algorithm
- `D.4.1` — Fair-Share Negotiation Operator [Stub] — fair division, negotiation, Nash bargaining, bias correction
- `D.4.2` — Assurance-Driven Override [Stub] — safety override, assurance, utility, risk management
- `**D.5**` — Bias-Audit & Ethical Assurance [Stable] — bias, audit, ethics, assurance, fairness, review cycle, taxonomy, AI ethics, responsible AI
- `D.5.1` — Taxonomy-Guided Audit Templates [Stub] — bias taxonomy, audit checklist, template
- `D.5.2` — Assurance Metrics Roll-up [Stub] — ethical risk index, metrics, evidence, roll-up

## Part E – The FPF Constitution and Authoring Guides


### Cluster E.I — The FPF Constitution

- `E.1` — Vision & Mission [Stable] — vision, mission, operating system for thought, purpose, scope, goals, non-goals
- `E.2` — The Eleven Pillars [Stable] — principles, constitution, pillars, invariants, core values, rules, P-1 to P-11
- `E.3` — Principle Taxonomy & Precedence Model [Stable] — taxonomy, precedence, conflict resolution, hierarchy, principles, classification, Gov, Arch, Epist, Prag, Did
- `E.4` — FPF Artefact Architecture [Stable] — artifact, families, architecture, conceptual core, tooling, pedagogy, canon, tutorial, linter
- `E.5` — Four Guard-Rails of FPF [Stable] — guardrails, constraints, architecture, rules, safety, GR-1 to GR-4
- `E.5.1` — DevOps Lexical Firewall [Stable] — lexical firewall, jargon, tool-agnostic, conceptual purity, DevOps, CI/CD, yaml
- `E.5.2` — Notational Independence [Stable] — notation, syntax, semantics, tool-agnostic, diagram, UML, BPMN
- `E.5.3` — Unidirectional Dependency [Stable] — dependency, layers, architecture, modularity, acyclic, Core, Tooling, Pedagogy
- `E.5.4` — Cross-Disciplinary Bias Audit [Stable] — bias, audit, ethics, fairness, trans-disciplinary, neutrality, review

### Cluster E.II — The Author’s Handbook

- `E.6` — Didactic Architecture of the Spec [Stable] — didactic, pedagogy, structure, narrative flow, on-ramp, learning
- `E.7` — Archetypal Grounding Principle [Stable] — grounding, examples, archetypes, U.System, U.Episteme, Tell-Show-Show
- `E.8` — FPF Authoring Conventions and Style Guide [Stable] — Problem-frame recognition surface; recognition surface / assurance surface; no route-shaped pattern tops; reader-time usability
- `E.9` — Design-Rationale Record (DRR) Method [Stable] — DRR, design rationale, decision record, context, consequences, conceptual auditability
- `E.10` — LEX-BUNDLE: Unified Lexical Rules for FPF [Stable] — lexical rules, naming, registers, rewrite rules, process, function, service
- `E.10.P` — Conceptual Prefixes (policy & registry) [Stable] — prefixes, U., Γ_, ut:, tv:, namespace, registry
- `E.10.D1` — Lexical Discipline for “Context” (D.CTX) [Stable] — context, U.BoundedContext, anchor, domain, frame
- `E.10.D2` — Intension–Description–Specification Discipline (I/D/S) [Stable] — intension, description, specification, I/D/S, testable, verifiable
- `E.11` — First-Practical Entry and Pattern-Use Discoverability Discipline [Stable] — which pattern first; first honest burden; tempting wrong pattern; lawful entry stop; thin echo not source of truth
- `E.12` — Didactic Primacy & Cognitive Ergonomics [Stable] — didactic, cognitive load, ergonomics, usability, Rationale Mandate, HF-Loop
- `E.13` — Pragmatic Utility & Value Alignment [Stable] — pragmatic, utility, value, Goodhart's Law, Proxy-Audit Loop, MVE
- `E.14` — Human-Centric Working-Model [Stable] — working model, human-centric, publication surface, grounding, assurance layers
- `E.15` — Lexical Authoring & Evolution Protocol (LEX-AUTH) [stable] — lexical authoring, evolution protocol, LAT, delta-classes
- `E.16` — RoC‑Autonomy Budget & Enforcement [Stable] — autonomy budget, guarded enactment, autonomy ledger, override speech act, scout/probe/commit checkpoint
- `E.17.0` — U.MultiViewDescribing — Viewpoints, Views & Correspondences [New] — multi-view describing, viewpoint, view, entity-of-interest, description families, correspondence model, ISO 42010 alignment, view vs viewpoint, engineering vs publication viewpoints. Queries: “How to organise multiple…
- `E.17.1` — U.ViewpointBundleLibrary — Reusable Viewpoint Bundles [Stable] — viewpoint bundle, reusable viewpoint family, import discipline, alias discipline, governance, engineering/management/research bundles
- `E.17.2` — TEVB — Typical Engineering Viewpoints Bundle [Stable] — engineering viewpoints, holon, Functional/Procedural/Role-Enactor/Module-Interface views, EoIClass = U.Holon, ISO 42010 mapping, E.TGA bindings. Queries: “What are canonical engineering viewpoints over a holon?”, “How…
- `E.17` — Multi‑View Publication Kit (for Morphisms) [Stable] — publication, U.View/U.EpistemeView, multi-view, viewpoints, PublicationScope (USM), PlainView/TechCard/InteropCard/AssuranceLane, functorial views, reindexing (PromoteView[s→t]), Publication characteristics (PC.Number…
- `E.17.EFP` — ExplanationFaithfulnessProfile - explanation classification over existing MVPK faces [Stable] — explanation, rendering, source-pinned, reconstruction, didactic retelling, speculative retelling, evidence binding, admissible faces, source anchors
- `E.17.ID.CR` — ComparativeReading - bounded comparative reading over comparative review units [Stable] — comparative reading, comparative review unit, bounded comparison, source-pinned material, same object of talk, bounded lift, forbidden stronger uptake, InterpretationDiscipline branch
- `E.17.AUD` — AuthoredUnitDiscipline — umbrella routing for one authored unit that is starting to drift [Stable] — authored unit, primary object of talk, carried move, outside-work boundary, umbrella routing, authored-unit stability
- `E.17.AUD.LHR` — AuthoredUnitDiscipline / Local Head Restoration — repair the pressured local head before the authored unit inherits it [Stable] — pressured head, head kind, active lane, local repair, governed object, outside-work boundary, local wording repair
- `E.17.AUD.OOTD` — AuthoredUnitDiscipline / AuthoredUnit Object-of-Talk Discipline — authored-unit stability over one primary object of talk [Stable] — authored unit, object of talk, authored-unit drift, carried move, outside-work boundary, explicit transition
- `E.18` — Transduction Graph Architecture (E.TGA) [Stable] — transduction graph, nodes=morphisms, edge=U.Transfer (single-edge kind), OperationalGate(profile), CV⇒GF (ConstraintValidity → GateFit), MVPK faces, SquareLaw, UNM single-writer, CSLC normalize-then-compare, Set-retur…
- `E.19` — Pattern Quality Gates: Review and Refresh Profiles [Stable] — PCP-ENTRY; entry review trigger; wrong-pattern check; support-role parity; retrieval-facing entry fixture
- `E.20` — Mechanism Introduction Protocol (MIP) [Draft] — mechanism introduction, authoring protocol, owner routing, MIP-run manifest, canonical card-first, no dangling …IntensionRef, suite boundary hygiene, P2W seam, SlotKind lexicon discipline, alias docking, typed RSCR tr…

## Part F — The Unification Suite (U‑Suite): Concept‑Sets, SenseCells & Contextual Role Assignment

- `F.0.1` — Contextual Lexicon Principles [Stable] — local meaning, context, semantic boundary, bridge, congruence, lexicon, U.BoundedContext

### Cluster F.I — context of meaning & Raw Material

- `F.1` — Domain‑Family Landscape Survey [Stable] — domain‑family survey, context map, canon, scope notes, versioning, authoritative source
- `F.2` — Term Harvesting & Normalisation [Stable] — term harvesting, lexical unit, normalization, provenance, surface terms
- `F.3` — Intra‑Context Sense Clustering [Stable] — sense clustering, disambiguation, Local-Sense, SenseCell, counter-examples

### Cluster F.II — Concept-Sets & Role Assignment/Description (definition, naming, decision)

- `F.4` — Role Description (RCS + RoleStateGraph + Checklists) [Stable] — role template, status template, invariants, RoleStateGraph (RSG), Role Characterisation Space (RCS)
- `F.5` — Naming Discipline for U.Types & Roles [Stable] — naming conventions, lexical rules, morphology, twin registers, U.Type naming
- `F.6` — Role Assignment & Enactment Cycle (Six-Step) [Stable] — role assignment, enactment, conceptual moves, asserting status
- `F.7` — Concept‑Set Table Construction [Stable] — concept-set, table, row, columns, differences, comparisons
- `F.8` — Mint or Reuse? (U.Type vs Concept-Set vs Role Description vs Alias) [Stable] — decision lattice, type explosion, reuse, minting new types, parsimony

### Cluster F.III — Cross‑Context Alignment & Applied Bindings

- `F.9` — Alignment & Bridge across Contexts [Stable] — bridge, cross-context alignment, CL, direction, loss notes, supported use, bridge reading, weakest-link scope, state export
- `F.9.1` — Bridge Stance Overlay [Stable] — bridge stance, stance overlay, interpretive gloss, projection note, rename note, language-state comparisons, overlay annotation
- `F.10` — Status Families Mapping (Evidence • Standard • Requirement) [Stable] — status, evidence, standard, requirement, polarity, applicability windows
- `F.11` — Method Quartet Harmonisation [Stable] — Method, MethodDescription, Work, Actuation, Role–Method–Work alignment
- `F.12` — Service Acceptance Binding [Stable] — Service Level Objective (SLO), Service Level Agreement (SLA), acceptance criteria, binding, observation

### Cluster F.IV — Lexical Development Cycle, Growth Control, Tests & Examples

- `F.13` — Lexical Continuity & Deprecation [Stable] — evolution, deprecation, renaming, splitting terms, merging terms
- `F.14` — Anti‑Explosion Control (Roles & Statuses) [Stable] — vocabulary growth, guard-rails, separation-of-duties, bundles, reuse
- `F.15` — SCR/RSCR Harness for Unification [Stable] — static checks, regression tests, acceptance tests, validation, SenseCell testing
- `F.16` — Worked‑Example Template (Cross‑Domain) [Stable] — didactic template, example, pedagogy, cross-domain illustration
- `F.17` — Unified Term Sheet (UTS) [Stable] — Unified Term Sheet, UTS, summary table, glossary, publication, human-readable output
- `F.18` — Local-First Unification Naming Protocol [Stable] — local-first naming, Name Card, Context, Kind, Purpose/use-domain, Sense anchor, guarded-head note, NQD-front label candidates, support-view wording, atlas alias docking, lifecycle actions, Bridge talk

## Part G – Discipline SoTA Patterns Kit

- `G.Core` — Part G Core Invariants [Stable] — Part‑G invariants, delegation-first core, RSCR trigger kinds, default ownership index, ID continuity, core linkage
- `G.0` — CG-Spec — Frame Standard & Comparability Governance [Stable] — CG-Spec, CG-Frame, legality gate, ComparatorSet, ScaleComplianceProfile (SCP), MinimalEvidence, Γ-fold, Φ(CL), Φ_plane, CL-routing, ReferencePlane, edition pins, RSCRTriggerKindId
- `G.1` — CG-Frame-Ready Generator [Stable] — generator chassis, generator / selector / set-surface scaffold, six-card kit (M1-M6), CGKitId manifest, SoTA_SetId, VariantPoolId, ShortlistId, CGFrameLibraryId, RefreshReadinessCardId, set-return selection, set-surfa…
- `G.2` — SoTA Harvester & Synthesis [Stable] — SoTA harvest, synthesis, SoTA Synthesis Pack@CG-Frame, SoTAPaletteDescription, Tradition, TraditionAtlasView, CrossSurfaceAtlasView, TypedSetViews, BridgeMatrix, GammaEpistSynthId, FlowRecord, palette-first
- `G.3` — CHR Authoring: Characteristics - Scales - Levels - Coordinates [Stable] — CHR authoring, characteristics, scales, levels, coordinates, CSLC legality, typed measurement, CHR Pack@CG-Frame, ReferencePlane, Φ/CL policy pins, edition pins, RSCRTriggerKindId
- `G.4` — CAL Authoring: Calculi - Acceptance - Evidence [Stable] — CAL authoring, operators, acceptance clauses, evidence profiles, tri-state admissibility, Γ-fold hooks, Φ/Ψ/Φ_plane policy pins, legality gates, edition pins, RSCRTriggerKindId
- `G.5` — Multi‑Method Dispatcher & MethodFamily Registry [Stable] — method-family registry, generator-family registry, dispatcher, SelectorOutcomeKind, selected-set publication, set-surface outcome, Shortlist, RankedShortlist, ShortlistId, SpecialistHandoff, abstain/escalation result,…
- `G.6` — Evidence Graph & Provenance Ledger [Stable] — EvidenceGraph, provenance, PathId, PathSliceId, lane tags (TA/VA/LA), SCR/RSCR, GateCrossing, CrossingBundle, UTS PathCard, TriggerAliasMap, Γ-fold pinning
- `G.7` — Cross-Tradition Bridge Calibration Kit (BridgeMatrix → BridgeCards + BCT/Sentinels) [Stable] — bridge calibration, BridgeCard, BridgeCalibrationTable (BCT), RegressionSet, SentinelSet, BridgeSentinel, Congruence Level (CL/CL^k/CL^plane), loss notes, waivers, ReferencePlane, Φ(CL)/Ψ(CL^k)/Φ_plane policy pins, Pa…
- `G.8` — SoS-LOG Bundles & Maturity Ladders [Stable] — SoS-LOG, rule ids, admissibility ledger, tri-state {pass
- `G.9` — Parity / Benchmark Harness [Stable] — parity harness, benchmark plan, adaptation parity, freshness windows, comparator pins, selected-set outcomes
- `G.10` — SoTA Pack Shipping (pack-boundary owner; SoTA-Pack(Core)) [Stable] — shipping, SoTA-Pack(Core), pack-boundary owner, selector-ready publication surface, AuditPins, MOOManifest, PortfolioRosterId, UTS publication, PathId/PathSliceId, CrossingBundle, edition pins, telemetry pins, RSCR wi…
- `G.11` — Telemetry-Driven Refresh & Decay Orchestrator [Stable] — telemetry, refresh, decay, RSCR, PathSlice, Bridge Sentinels, edition-aware, epistemic debt, deprecation, edition bumps, re-shipping
- `G.12` — DHC Dashboards — Discipline-Health Time-Series (lawful telemetry, generation-first) [Stable] — dashboard, DHC, discipline health, time-series, lawful telemetry, view-only slices, PathId/PathSliceId, edition pins, UTS twins, RSCR/refresh wiring
- `G.13` — External Interop Hooks for SoTA Discipline Packs (conceptual; normative when used) [Stable] — interop, external index, claim mapper, mapping policy, plane map, embedding spec, ExternalIndexCard@Context, ClaimMapperCard@Context, InteropSurface@Context, CHR-typed SoS features, edition pins, UTS twins, RSCRTrigge…

## Part H – Glossary & Definitional Pattern Index

- `H.1` — Alphabetic Glossary [stub] — Every U.Type, relation & operator with four‑register naming.
- `H.2` — Definitional Pattern Catalogue [stub] — One‑page micro‑stubs of every definitional pattern for quick lookup.
- `H.3` — Cross‑Reference Maps [stub] — Bidirectional links: Part A ↔ Part C ↔ Part B terms.

## Part I – Annexes & Extended Tutorials

- `I.1` — Deprecated Aliases [stub] — Legacy names kept for backward compatibility.
- `I.2` — Detailed Walk-throughs [Stable] — Worked entry readings for high-risk or compact-insufficient entry neighborhoods; compact-index-only is a complete lawful posture when enough.
- `I.3` — Change‑Log (auto‑generated) [stub] — Version history keyed to DRR ids.
- `I.4` — External Standards Mappings [stub] — Trace tables to ISO 15926, BORO, CCO, Constructor‑Theory terms.

## Part J – Indexes & Navigation Aids

- `J.1` — Concept‑to‑Pattern Index [stub] — Quick jump from idea (“boundary”) to pattern (§, id).
- `J.2` — Pattern‑to‑Example Index [stub] — Table listing every archetypal grounding vignette.
- `J.3` — Principle‑Trace Index [Stub] — Maps each Pillar / C‑rule / P‑rule to concrete clauses.
- `J.4` — First Practical Entry Neighborhood Index [Stable] — Compact six-row entry-neighborhood index matching the public entry families without route/owner/output columns.

## Part K - Lexical Debt

- `K.1` — Mandatory Replacement of Measurement Terms [Stub] — Retires "axis/dimension" in favor of "Characteristic" and aligns other measurement terms.
- `K.2` — Migration Debt from A.2.6 (USM) [Stub] — Specifies the required edits across the FPF to align with the new Unified Scope Mechanism (USM).
- `K.3` — Temporal Claim Lexical Debt from C.27 [Stable] — Retires untyped velocity, acceleration, cadence, agility, rhythm, inertia, and dynamics language when it is used outside a named C.27, C.16, or A.3.3 reading.
