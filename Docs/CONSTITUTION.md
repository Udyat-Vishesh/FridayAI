# FRIDAY Constitution

> "Strong systems are built on consistent principles, not convenient exceptions."

---

# Purpose

This document defines the non-negotiable engineering rules that govern the design, development, and evolution of FRIDAY.

These rules exist to ensure that the platform remains reliable, maintainable, understandable, and aligned with its philosophy regardless of how large or complex it becomes.

Every major engineering and architectural decision should respect this constitution.

---

# Article I — Philosophy First

All architectural and engineering decisions must align with the principles defined in `PHILOSOPHY.md`.

If a proposed feature conflicts with the philosophy, the feature must be redesigned or rejected.

The philosophy defines *why* FRIDAY exists.

The constitution defines *how* it is built.

---

# Article II — Simplicity Before Complexity

Prefer the simplest solution that correctly solves the problem.

Complexity should only be introduced when it provides a clear and measurable benefit.

Avoid unnecessary abstraction, unnecessary dependencies, and premature optimization.

Every new layer should justify its existence.

---

# Article III — Single Responsibility

Every component should have one clear purpose.

Examples:

- Memory preserves context.
- Research acquires information.
- Learning teaches.
- Planning creates plans.
- Voice handles speech.
- Vision processes images.
- Actions execute tasks.

Responsibilities should not overlap without good reason.

When responsibilities become unclear, the architecture should be reconsidered.

---

# Article IV — Local First

FRIDAY is designed as a local-first platform.

Core functionality should operate without an internet connection whenever practical.

External services, online APIs, and cloud models may be used when they provide meaningful value, provided they do not compromise user control, transparency, or ownership of data.

Cloud services should enhance the platform—not define it.

---

# Article V — Transparency

FRIDAY should always be explainable.

Whenever practical, the platform should make it clear:

- What it is doing.
- Why it is doing it.
- Which components were involved.
- What information was used.
- Where important information originated.

Users should never be forced to trust unexplained behavior.

---

# Article VI — User Authority

The user is always the highest authority.

FRIDAY may recommend, automate, and assist, but meaningful actions require appropriate user permission unless explicitly configured otherwise.

Automation must never remove user ownership.

The user owns their data, memories, workflows, and decisions.

---

# Article VII — Reliability Over Features

Stability is more important than feature count.

A smaller, dependable system is preferable to a larger, unreliable one.

Every new feature should improve the platform without reducing its overall reliability.

Features should never be added simply because they are impressive.

---

# Article VIII — Documentation Is Part of the Code

Documentation is a required part of development.

Major architectural changes should be reflected in the documentation.

Engineering decisions should be recorded for future reference.

Code without documentation creates technical debt.

Documentation should evolve alongside implementation.

---

# Article IX — Modularity

The platform should be composed of independent modules with clearly defined interfaces.

Modules should communicate through well-defined boundaries.

Changes in one subsystem should have minimal impact on others.

Large systems should emerge from small, well-designed components.

---

# Article X — Maintainability

Future maintainability should always be considered during development.

When faced with multiple valid solutions, prefer the one that is easier to understand, test, debug, and extend.

The future developer is often the current developer several months later.

Optimize for clarity before cleverness.

---

# Article XI — Context Preservation

FRIDAY should preserve important context whenever practical.

Information should not be forgotten without reason.

Memory systems should prioritize continuity while respecting user control and privacy.

Remembering useful information is a feature.

Remembering unnecessary information is technical debt.

---

# Article XII — Continuous Improvement

Every release should improve at least one of the following:

- Reliability
- Performance
- Maintainability
- Understanding
- User Experience

Progress should be deliberate, measurable, and documented.

---

# Article XIII — Research and Knowledge

FRIDAY should never assume that all useful knowledge exists locally.

When appropriate, the platform should intelligently combine:

- Personal memory
- Local documents
- User knowledge
- Trusted online resources
- Documentation
- Research papers
- APIs

to produce accurate, current, and useful answers.

The source of important information should remain transparent whenever practical.

---

# Article XIV — Architectural Integrity

Every subsystem must justify its existence.

Before introducing a new module, service, or layer, ask:

1. Does this solve a real problem?
2. Can an existing component responsibly handle it?
3. Does it reduce complexity rather than increase it?
4. Will it remain valuable as FRIDAY grows?

If the answer is no, the component should not exist.

Architecture should grow through necessity—not imagination.

---

# Article XV — Documentation Consistency

No document should knowingly contradict another.

When a significant architectural decision changes the platform, existing documentation should be updated before new documentation is created.

The documentation should always describe one coherent system—not multiple competing visions.

---

# Amendment Process

This constitution is intended to evolve.

Changes should be rare, carefully considered, and documented.

Every amendment should improve the long-term quality of the platform rather than solve a temporary problem.

Major architectural changes should be accompanied by an Architecture Decision Record (ADR).

---

# Final Principle

When uncertainty exists, choose the option that best supports:

- Learning
- Reliability
- Transparency
- User Control
- Maintainability
- Modularity
- Long-term Growth

These principles take precedence over convenience.

---

Version: v1.1 — Foundation
Last Reviewed: 2026-07-30