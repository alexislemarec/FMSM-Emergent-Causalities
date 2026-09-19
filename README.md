# FMSM — Emergent Causalities Analysis Protocol

**A structured protocol for causal, multidomain, and epistemically conservative analysis with language models.**

FMSM is an experimental analytical protocol designed to help language models explore complex causal situations while preserving the distinction between observations, mechanisms, strategies, motivations, hypotheses, and uncertainty.

Its purpose is not to turn a language model into a truth engine or predictor. It provides a structured procedure intended to make the reasoning process more explicit and to reduce premature causal or motivational conclusions.

**Creator:** Alexis Le Marec
**Public version:** 1.0
**Year:** 2026

---

## Overview

Language models can produce highly coherent explanations even when some of the relationships supporting those explanations remain uncertain.

FMSM addresses this problem by organizing analysis around four complementary levels:

**Facts → Mechanisms → Strategies → Motivations**

* **Facts** — Observable or documented elements relevant to the analysis.
* **Mechanisms** — Processes, interactions, constraints, and levers that may explain how a situation evolves.
* **Strategies** — Combinations of mechanisms that may produce a trajectory or contribute to an objective.
* **Motivations** — Stated or inferred motivations compatible with the observed or reconstructed strategies.

Motivations that are not directly established remain hypotheses.

---

## Core Analytical Controls

FMSM supplements this decomposition with several analytical controls.

### Premise qualification

The content of a source or question is not automatically treated as an accurate description of reality. Facts, interpretations, attributed intentions, causal claims, predictions, and hypothetical conditions should remain distinguishable.

### Distance from the premise

Derived propositions can be represented according to their inferential distance:

* **D0** — directly contained in or established by the input;
* **D1** — relatively direct inference;
* **D2** — inference requiring additional mechanisms or intermediate conditions;
* **D3+** — more distant propagation depending on multiple intermediate elements.

Distance is not a probability or confidence score. A distant inference may be strongly documented, while a nearby inference may remain uncertain.

### Epistemic-status preservation

A reported claim, inference, or hypothesis cannot silently become a fact, established mechanism, or certain intention merely because subsequent reasoning has been built around it.

### Competing hypotheses

When several explanations remain compatible with the available information, FMSM preserves the principal alternatives rather than requiring premature selection of a single explanation.

### Sufficiency test

When an actor or source provides a causal explanation or justification, the protocol examines whether that explanation is sufficient to account for the action, its timing, and its form.

An insufficient explanation does not by itself establish a hidden intention.

### Counter-evidence and missing information

The protocol distinguishes between information that is unavailable and information that actively weakens an interpretation.

### Conservative synthesis

The final synthesis must preserve the epistemic status established during the analysis. Hypotheses and inferences cannot be promoted into facts or certain conclusions during summarization.

---

## Public Version 1.0

This repository contains the public reference version of FMSM.

The public protocol is intentionally compact. The accompanying white paper explains its conceptual foundations, exploratory tests, observed failure modes, limitations, and possible research directions.

FMSM remains experimental. The exploratory tests described in the white paper do **not** constitute formal experimental validation or establish superiority over other reasoning frameworks.

Controlled evaluation across models, identical test sets, repeated runs, and predefined evaluation criteria remains future work.

---

## Related Book

FMSM and the Emergent Causalities framework were originally developed alongside the book ***Causalités Émergentes***, by Alexis Le Marec.

The book explores the broader conceptual foundations behind the project, including cross-domain mechanisms, causal interactions, transmission, feedback, cognition, social and economic dynamics, and the relationships between individual and systemic processes.

FMSM was developed as an experimental analytical implementation of part of this broader approach.

***Causalités Émergentes* — Alexis Le Marec (2026)**
French and English editions.

---

## Documents

### English

* [**FMSM — Emergent Causalities Analysis Protocol — Public Version 1.0**](FMSM%20Protocol%20English.pdf)
* [**Emergent Causalities — White Paper**](White%20Paper%20Emergent%20Causalities%20EN.pdf)

### Français

* [**FMSM — Protocole d'analyse des causalités émergentes — Version publique 1.0**](FMSM%20Protocole%20VF.pdf)
* [**Causalités Émergentes — Livre blanc**](White%20Paper%20CAUSALIT%C3%89S%20%C3%89MERGENTES.pdf)

PDF versions of the public protocol and accompanying white paper are provided in both English and French.

---

## How to Use FMSM

FMSM is model-independent at the protocol level.

A simple experimental workflow is:

1. Provide the FMSM protocol to a language model as analytical instructions.
2. Provide the situation, question, dataset, or scenario to be analyzed.
3. Allow the model to explore relevant actors, mechanisms, relationships, and trajectories.
4. Examine whether the resulting analysis preserves uncertainty, competing explanations, counter-evidence, and the distinction between established and inferred information.

Performance will depend on the capabilities, knowledge, context handling, and behavior of the underlying model.

FMSM does not correct an inaccurate knowledge base and does not guarantee factual accuracy.

---

## What FMSM Does Not Claim

FMSM is **not**:

* a truth engine;
* a prediction system;
* a substitute for domain expertise;
* a guarantee of impartiality;
* a guarantee of textual reproducibility;
* a formally validated benchmark result.

Its narrower objective is to make the analytical procedure more identifiable and to make visible where conclusions depend on assumptions, inferred mechanisms, missing information, or uncertain causal relationships.

---

## Research and Evaluation

The public protocol is provided so that researchers and other users can independently examine, test, evaluate, and critique its behavior.

Relevant research directions include:

* controlled comparison between models with and without the protocol;
* evaluation across different domains and levels of causal complexity;
* repeated-run stability;
* systematic analysis of failure modes;
* measurement of epistemic-status preservation;
* evaluation of long causal chains and dependency propagation.

Independent evaluation, including negative results and criticism, is welcome.

---

## Citation

Suggested citation:

**Le Marec, Alexis. (2026). *FMSM — Emergent Causalities Analysis Protocol, Public Version 1.0.***

Repository:
https://github.com/alexislemarec/FMSM-Emergent-Causalities

---

## License

FMSM — Emergent Causalities Analysis Protocol © 2026 Alexis Le Marec.

Licensed under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0).**

You may share the licensed material for non-commercial purposes, provided appropriate credit is given to Alexis Le Marec as the creator of the FMSM protocol.

The license does not grant permission to distribute modified or adapted versions of the protocol.

Official license:

https://creativecommons.org/licenses/by-nc-nd/4.0/

See `License.md` for repository licensing information.

---

## Why this license?

FMSM is published openly so that researchers and other users can examine, test, evaluate, and critique the protocol while working from a stable reference version.

The NoDerivatives restriction is intended to preserve a clearly identifiable canonical version of FMSM and to prevent modified implementations from being redistributed as variants of the protocol without prior permission.

This restriction does not prevent independent research, evaluation, criticism, or experimentation within the scope permitted by the license and applicable law.

Researchers wishing to distribute an adaptation, or organizations interested in commercial use, may contact the author to discuss additional permissions.

---

## Contact

For research questions, commercial licensing inquiries, or permissions beyond the scope of CC BY-NC-ND 4.0:

**Alexis Le Marec**
[AlexisLeMarec1@protonmail.com](mailto:AlexisLeMarec1@protonmail.com)

---

**FMSM — Public Version 1.0 — © 2026 Alexis Le Marec**
