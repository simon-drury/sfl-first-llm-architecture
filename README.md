---

**Language / Langue / Idioma / Lingua / Idioma:**
[EN](README.md) | [FR](README.fr.md) | [ES](README.es.md) | [IT](README.it.md) | [PT](README.pt.md)

> *Multilingual versions produced using [sfl-translation-agent](https://github.com/simon-drury/sfl-translation-agent) — SFL-first translation pipeline by the same author.*

---

# sfl-first-llm-architecture

**© 2026 Simon Drury (sjd_datascapes)**

---

## What this is

A public, timestamped specification of an SFL-first LLM architecture.

The core claim: systemic functional linguistics - specifically the ideational, interpersonal, and textual metafunctions - provides the correct backbone for LLM design, prompt engineering, and agent orchestration. This is not SFL applied *on top of* an LLM. This is SFL as the *operating system* of the LLM.

---

## The problem with current LLM design

Current LLMs and their system prompts are:

- ideationaly underspecified (no principled field/domain architecture)
- interpersonally incoherent (no principled role, stance, or tenor modelling)
- textually ad hoc (no principled genre, register, or information-flow structure)

The result: users spend significant time correcting system-level failures that should never have been built in.

---

## The SFL-first architecture

### 1. Register as the primary design parameter

Every LLM interaction is governed by a context of situation. The three register variables - field, tenor, mode - must be explicitly encoded as system-level parameters, not inferred stochastically.

- **Field**: What domain of activity is in play? What knowledge structure governs it?
- **Tenor**: What is the role relationship? What obligation and affect structures apply?
- **Mode**: What is the rhetorical channel? What information density and flow are expected?

### 2. Metafunctions as agent-typing system

The three metafunctions are not just analytical categories. In an SFL-first architecture, they become functional roles for agents and sub-processes:

- **Ideational agent**: manages domain knowledge, experiential construal, logical relations
- **Interpersonal agent**: manages stance, appraisal, obligation, modality, role relations
- **Textual agent**: manages cohesion, information structure, genre sequencing, thematic progression

### 3. Genre as output specification

Output is not "a response". Output is a genre instance - a staged, goal-oriented social process. The genre must be explicitly specified before generation, not inferred from surface features of the prompt.

### 4. SFL-first prompt engineering

Prompts are not natural language instructions. They are meta-textual operators over a systemic functional space. A well-formed SFL-first prompt specifies:

- the register of the target text
- the genre structure expected
- the metafunctional weighting required
- the appraisal and modality parameters

---

## Implementations

The following repos implement aspects of this architecture:

- [systemic_func_context-wrapper](https://github.com/simon-drury/systemic_func_context-wrapper) - SFL instruction wrapper for prompts
- [sfl-translation-agent](https://github.com/simon-drury/sfl-translation-agent) - SFL-grounded multilingual translation agent
- [browser_bridge_-sfl-playground-extension_sjd_datascapes](https://github.com/simon-drury/browser_bridge_-sfl-playground-extension_sjd_datascapes) - multi-model SFL-first LLM analysis
- [numerai-sfl-pipeline](https://github.com/simon-drury/numerai-sfl-pipeline) - SFL-informed multi-agent pipeline

---

## Licence

This specification is free for personal, academic, and non-commercial open-source use.
Commercial use (directly or indirectly generating revenue) requires a separate licence from the author.

Please get in touch if commercial use is intended. Licensing terms are open to discussion.

**Contact**: simondrury2010@gmail.com | [LinkedIn](https://www.linkedin.com/in/simon-drury-60b881293)

---

*First published: March 2026. Timestamped on GitHub as prior art.*
