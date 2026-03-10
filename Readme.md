# First Principles Framework (FPF) — Core Conceptual Specification

> **An Operating System for Thought**  
> *Architecting transdisciplinary reasoning for systems, epistemes, and communities.*

**Version:** March 2026  
**Author:** Anatoly Levenchuk (with LLM assistance)  
**Status:** Normative kernel, "eternal alpha" — already used in working projects and increasingly acting in working development programmes, while still evolving.

## 📖 Overview

The **First Principles Framework (FPF)** is a rigorous, transdisciplinary architecture for thinking, written in human- and machine-readable pseudo-code (the informal "language of technical standards" with multiple "May", "Should", "Must"). It provides a generative pattern language to model complex systems, manage knowledge evolution, and ensure auditable assurance across engineering, research, and management domains.

Internally, FPF also serves as a conceptual foundation for rational work that you look at, resonate with, and mine for patterns rather than a narrative textbook.

FPF is not a specific methodology (like Agile or Waterfall) nor a static encyclopedia. It is an **episteme of method** — a structured specification of how to think — packaged as a set of architecture decision records (ADRs) and patterns that can be executed by humans and AI-agents. It bridges the gap between **rigorous assurance** (audits, proofs) and **open-ended creativity** (innovation, novelty) by treating them as complementary engines within a single evolution.

FPF is not mainly a way to make a single model “smarter”. Its main value is to turn raw intelligence — human or machine — into organisationally usable reasoning: explicit bounded contexts, auditable artefacts, multi-view descriptions, and disciplined hand-offs between specialised actors. In practice this matters most when work is done by mixed collectives of humans and AI agents, not by one isolated expert. Its first-principles kernel is meant not only to catalogue current best practice, but also to help grow new conceptual architectures when existing categories stop being adequate.

## What problem FPF solves

FPF is most useful when strong local reasoning is no longer the main bottleneck. It is for situations where the hard part is coordinating specialised people and AI agents, keeping meaning stable across hand-offs, making trade-offs explicit, and publishing the same underlying work to engineers, managers, researchers, and auditors without semantic drift.

In plain language: FPF turns raw intelligence into work that is easier to align, review, evolve, and delegate.

## Where FPF earns its keep

FPF tends to pay off when several of these are true:

* work is split across specialised people, teams, copilots, or AI agents;
* the real-world oracle is delayed, noisy, expensive, or risky;
* different audiences need lawful views of the same underlying work;
* trade-offs between speed, quality, risk, novelty, and compliance must be made explicitly rather than hidden in one opaque score;
* existing categories are breaking down and you need to grow new concepts from first principles instead of reusing local folklore.

FPF is a file (around 5MB, 60000 lines) and should be added only as a file (to the RAG), not pasted into the prompt window. Use it with a prompt in your preferred natural language, for example: “You have FPF in a file. Use it, but avoid FPF-specific terminology in the final answer. Speak as an engineer-manager.”

### Why FPF when AI-agents keep getting stronger?

* **Because coordination, not raw generation, becomes the bottleneck.** Stronger LLMs reduce local reasoning scarcity, but they do not remove the need for selection, auditability, safe delegation, and shared understanding across people, agents, time, and viewpoints.
* **Because bounded context is the unit of specialisation and hand-off.** It lets a very capable but specialised human or agent participate in a larger engineering or research process without pretending everyone shares one universal vocabulary.
* **Because many real projects cannot just “loop until tests pass.”** In product, field engineering, strategy, marketing, safety, or open-ended research, the real-world oracle is delayed, noisy, expensive, or risky. FPF aims to catch anti-patterns before contact with the world.
* **Because the same stack can serve both humans and AI.** AI agents can read the specification directly; humans can learn the same working model through didactic layers and the pedagogical companion.
* **Because FPF pays off past a complexity frontier.** It matters most when the problem becomes simultaneously compositional, collaborative, temporal, assurance-heavy, and generative.
 

### 🧠 FPF as an "Operating System for Thought"

Using the OS metaphor, FPF:

* **Provides a common runtime for reasoning and iteration.**
* **Treats bounded contexts as semantic address spaces and hand-off units.**
* **Separates actors, methods, and executed work.**
* **Keeps claims tied to scope and evidence.**
* **Externalises thought into structured artefacts instead of leaving it tacit.**
* **Publishes one underlying body of work into different lawful views for engineering, management, research, and assurance.**
* **Stays extensible through domain-specific packs instead of hard-coding one discipline's worldview.**

For most readers, the practical point is simpler than the internal vocabulary: FPF gives mixed human/AI teams a shared way to specialise locally, hand work off cleanly, and keep different views of the same work coherent.

Loaded as a file into a RAG-enabled AI assistant (ChatGPT, Gemini, local models, etc.), FPF can act as a *bias-assistant* or “grimoire”, but that understates the point: it is better understood as a coordination and reasoning scaffold for mixed human/AI work. It steers the model toward first-principles, SoTA-oriented reasoning instead of generic marketing/management/pop-psychology boilerplate — but it will not think instead of you, and without good questions you can still get very confident, well-structured nonsense.

## 🎯 Who is this for?

*   **Engineers and systems engineers** building reliable physical or cyber-physical systems.
*   **Researchers** constructing trustworthy knowledge and theories.
*   **Platform teams** designing AI-agent / human-in-the-loop work systems.
*   **Safety, assurance, and regulatory leads** who need auditable boundaries, evidence, and controlled delegation.
*   **Managers and product leaders** orchestrating collective intelligence, budgets, and evolutionary cycles.

## 🔑 Core ideas (plain language first)

FPF is built on a small kernel of non-negotiable ideas. New readers do not need the internal pattern names immediately; the point of this section is to explain what the framework buys you before you dive into its internal map.

1.  **Local meaning, explicit translation.** Terms live inside bounded contexts. Cross-context reuse is never “obvious”; it needs an explicit bridge.
2.  **One underlying reality, many lawful views.** Engineering, management, research, and assurance views should be projections of the same underlying work, not disconnected documents.
3.  **Separate actors, methods, and executed work.** Plans, capabilities, descriptions, and actual occurrences are not the same thing.
4.  **Trust has structure.** A claim should say how formal it is, where it applies, and what evidence supports it.
5.  **Composition matters across scales.** The same logic should survive when parts are aggregated into wholes.
6.  **Keep search wide before selection.** In open-ended work, diversity of options matters before choosing a winner.
7.  **Build from first principles when categories break.** FPF is not only for organising current SoTA; it is also for growing new abstractions.

## ✅ What to expect (and what not to expect)

### Reasonable expectations

* **A coordination fabric for mixed human/AI teams.** FPF helps specialised people and agents participate in one engineering/research process through bounded contexts, bridges, shared artefacts, and multi-view publication surfaces.
* **A way to push some mistakes left, before expensive contact with the world.**
* **A way to keep engineering, management, research, and assurance views coherent.**
* **A SoTA- and first-principles-biased co-thinker.** When loaded into an LLM, FPF acts as a bias-assistant for strong engineering and research thinking: you still think, but you get sharper questions, better comparisons, and far less generic boilerplate.
* **A DDD-style backbone for disciplines and organisations.** FPF can serve as the *DDD (domain-driven design) for science/engineering*: a way to model a discipline (or organisation) with explicit contexts, roles, calculi, and SoTA-packs rather than one more methodology slide-deck.
* **A machine for first-principles synthesis.** Use it not only to recall current best practice, but to grow new conceptual architectures when existing categories are misleading.
* **A kernel for development programmes.** In practice FPF already feeds programmes for engineer-manager development and research skill-building.

### Unreasonable expectations

* **"I'll just read it once and form my opinion."** The spec reads like OS source code, not like a popular book; it is meant to be *used* with tools, not consumed in one sitting.
* **"This is a plug-and-play tool for all work projects."** Today FPF is a research-grade framework that already helps in real projects as an MVP, but it is not yet a shrink-wrapped product; you still need to adapt, localise, and extend it for your discipline and organisation.
* **"It works without good framing and always gives the right answer."** LLM+FPF will not think instead of you. Without good questions, explicit problem frames, and minimal rational literacy you can still get confident nonsense—just more structured nonsense.
* **"A stronger AGI/LLM makes FPF unnecessary."** As models get stronger, the bottleneck often moves from local reasoning to coordination, selection, safe delegation, and cross-role auditability.
* **"Adoption should be decided only by transferable benchmark wins from other organisations."** Frameworks such as Agile or Copilot-like practices are often adopted as architectural bets under high variation. FPF is similar: the justification is usually logical fit to your coordination/problem structure, not a neat benchmark that transfers unchanged across organisations.
* **"If I ignore first principles, FPF will fix everything."** FPF amplifies whatever style of thinking you bring: if you use it to chase fashion, it will help you catalog fashion; if you use it to chase first principles, it will help you do that more systematically.


## 📂 How to approach this repository

There are three sensible entry paths:

1. **Use it now with an AI assistant on a real problem.** Read this README, then jump to the starter prompt and the worked examples.
2. **Use it as a coordination layer for a mixed team.** Read the sections above, then map bounded contexts, hand-offs, decision criteria, and publication surfaces for your programme.
3. **Study the internal architecture.** Start with the vision / kernel material, then use the internal map below as a navigation aid.

<details>
<summary>Advanced: internal map of the specification</summary>

The specification is divided into clusters. Think of this as source code for an evolvable reasoning architecture, not as an expert system and not as a tutorial:

### **Part A: Kernel Architecture Cluster**
The immutable ontological core.
*   **Ontology:** Holons, Systems, Epistemes, and Bounded Contexts.
*   **Transformation:** The `Transformer` quartet (Agent, Method, Description, Work).
*   **State Space:** Characteristics, Scales, and Dynamics.
### **Part B: Trans-disciplinary Reasoning Cluster**
The logic of composition and trust.
*   **$\Gamma$ Algebra:** How to aggregate systems (`Γ_sys`), knowledge (`Γ_epist`), and resources (`Γ_work`).
*   **Assurance:** The `F-G-R` calculus and evidence graphs.
*   **Transduction Graph Architecture (E.TGA):** Eulerian graphs of flows and "from principles to work" (P2W) paths that make architectures of reasoning and work explicit.
*   **Evolution:** The canonical loops for observing, refining, and deploying updates.
### **Part C: Architheory Specifications**
Pluggable domain-specific calculi (CAL), logics (LOG), and characterizations (CHR).
*   **Sys-CAL:** Physics and conservation laws.
*   **KD-CAL:** Knowledge dynamics and truth-maintenance.
*   **NQD-CAL:** Novelty, Quality, and Diversity search.
*   **Kind-CAL:** Typed reasoning and taxonomy.
### **Part D: Ethics & Conflict-Optimisation**
*   Multi-scale ethics (from agent to planetary).
*   Bias audits and trust-aware mediation.
### **Part E: Constitution & Authoring**
The governance of the framework itself.
*   **The 11 Pillars:** Constitutional invariants (e.g., *Cognitive Elegance*, *Didactic Primacy*).
*   **Guard-Rails:** DevOps Lexical Firewall, Notational Independence.
*   **MVPK:** Multi-View Publication Kit for generating consistent views/documents for different roles and surfaces.
### **Part F: The Unification Suite**
Techniques for aligning vocabularies across disciplines and specialised agents using **SenseCells**, **Concept-Sets**, and **Alignment Bridges**.
### **Part G: Discipline SoTA Kit**
Tools for harvesting "State of the Art" (SoTA) knowledge, benchmarking methods, and creating selector-ready portfolios of solutions rather than prematurely collapsing to a single winner.

</details>

> *"A principle that works in only one world is local folklore; a first principle architects every world."* — **Pattern A.8**

## 🚀 Using FPF with an AI assistant

FPF is designed to be loaded as a file into an AI-agent or AI-assistant with LLM and RAG (ChatGPT or Codex, Gemini, local models with RAG infrastructure, etc.). It is too large to paste as a prompt, so load it as a file.

The highest-leverage first sessions are concrete. Ask for plain-language outputs first; pull internal FPF names only when they add precision or help you navigate the spec.

LLM+FPF will not solve everything automatically: you remain the principal, and the model is an agent that follows your problem framing and constraints.

### A starter prompt that usually works

> You have the FPF specification as a file.  
> Help me structure `<project / problem / programme>`.  
> Use plain language for an engineer-manager.  
> Propose: (1) bounded contexts / specialisations, (2) decision criteria, (3) key alternatives, (4) hand-offs, and (5) missing evidence or tests before commitment.  
> Introduce internal FPF names only when they add precision.

In practice the most productive usage is to treat FPF as a design kit and reference model: ask for bounded-context maps, decision criteria, option portfolios, structured reasoning artefacts, publication surfaces, and hand-off contracts for your domain, then iterate.

Below are example prompts that have been used in practice; adapt them to your domain and language.

### 1. Turn a vague project into measurable decision criteria

**Goal:** get a step-by-step chain from “vague idea” to measurable characteristics, indicators, scoring and decision criteria.
**Prompt:** 
> You have the FPF specification loaded as a file.  
> We are starting work on <brief description of project>, design has not yet begun.  
> Propose a step-by-step chain for characterising the objects of our project, normalising measurements, defining indicators, scoring alternatives, and choosing design decisions.  
> Include steps that I may have forgotten.  
> Write in the language of engineer-managers, not in FPF jargon.*

Typical follow-ups:
* “Now take object <X> from this chain and work it through in detail: list 10–15 characteristics, their scales, indicators, and a rough dashboard format for decision-makers.”
* “Show how this chain maps to the principles-to-work route for this project.”

### 2. Build a disciplined vocabulary for a domain (UTS)

**Goal:** build a disciplined vocabulary for a niche field using FPF Part F.
**Prompt:**
> You have the FPF specification loaded.  
> Produce a Unified Term Sheet (UTS) block for the core terms of <your domain>: at least 10 rows.  
> Use the term-sheet discipline from Part F (especially F.17/F.18): distinguish Tech vs Plain names, show SenseCells for 2–3 key bounded contexts, and flag risky aliases.

Follow-up for quantitative structure:
* “For the same domain, propose a Q-bundle that captures the quality of <your object/process> and produce a UTS block for its characteristics (CHR) and indicators.”

### 3. Design better names for ambiguous roles, programmes, and artefacts (Name Cards)

**Goal:** design better names for roles, programs, artefacts when existing labels are misleading.
**Prompt:**
> Using the naming-card discipline (F.18), develop a complete Name Card for what to call <current name of an Entity> in the following situation:  
> <short narrative of current practice and complaints about existing name>  
> Do not assume current names are correct; perform an honest search on the local Pareto-front of candidate names and explain trade-offs.

### 4. Make the route from principles to work explicit (P2W / E.TGA)

**Goal:** make “from principles to work” explicit for a concrete project.
**Prompt:**
> Using E.TGA and TEVB, unpack the canonical P2W flow for my situation <describe your project>.  
> Give the list of nodes (P1…Pn), their Kinds, and explain each node in engineer-manager language.

Follow-up:
* “Now build a mini Flow specification table for this P2W graph”.

### 5. Organise a mixed team of humans and AI agents

**Goal:** turn a set of people, copilots, and specialised agents into a disciplined work architecture.
**Prompt:**
> We have the FPF specification loaded as a file.  
> We need to organise a mixed team of humans and AI agents for <project/programme>.  
> Propose a bounded-context map: contexts, local vocabularies, roles, bridges, hand-off artefacts, decision gates, and where human approval is required.  
> Keep the final answer practical for engineers/managers and avoid FPF jargon.

Typical follow-ups:
* “Now define autonomy budgets, allowed tools, escalation paths, and publication surfaces for each context/agent.”
* “Show which bridges are high-risk because translation loss or ambiguity is likely.”

### 6. Harvest competing schools of thought and build a portfolio (SoTA Pack)

**Goal:** use Part G to organise a frontier discipline around first principles.
**Prompt:**
> We are in search for SoTA of <discipline>.
> Using G.2 and G.4, extract: (a) TraditionCards for competing schools of thought; (b) OperatorCards for their main operators / update rules; (c) a first draft of a SoTA Pack and selector-ready portfolio. This is expected to be a long text, therefore start with only TraditionCards.
 
## Citation

If you use FPF, please cite:

Levenchuk, Anatoly. *First Principles Framework (FPF).* GitHub repository, https://github.com/ailev/FPF
