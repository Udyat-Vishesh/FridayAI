# FRIDAY Constitution

> "Strong systems are built on consistent principles, not convenient exceptions."

---

# Purpose

This document defines the non-negotiable engineering rules that govern the design, development, and evolution of FRIDAY.

These rules exist to ensure that the platform remains reliable, maintainable, understandable, and aligned with its philosophy regardless of how large or complex it becomes.

Every major decision should respect this constitution.

---

# Article I — Philosophy First

All architectural and engineering decisions must align with the principles defined in `PHILOSOPHY.md`.

If a proposed feature conflicts with the philosophy, the feature must be redesigned or rejected.

---

# Article II — Simplicity Before Complexity

Prefer the simplest solution that correctly solves the problem.

Complexity should only be introduced when it provides a clear and measurable benefit.

Avoid unnecessary abstraction and premature optimization.

---

# Article III — Single Responsibility

Every component should have one clear purpose.

Examples:

- Memory stores information.
- Knowledge retrieves information.
- Voice handles speech.
- Vision processes images.
- Planning creates plans.

Responsibilities should not overlap without good reason.

---

# Article IV — Local First

FRIDAY is designed as a local-first platform.

Core functionality should operate without an internet connection whenever practical.

Cloud services should enhance the platform—not define it.

---

# Article V — Transparency

FRIDAY should always be explainable.

Whenever possible, the platform should make it clear:

- what it is doing,
- why it is doing it,
- and how a result was produced.

Users should never be forced to trust unexplained behavior.

---

# Article VI — User Authority

The user is always the highest authority.

FRIDAY may recommend, automate, and assist, but meaningful actions require appropriate user permission unless explicitly configured otherwise.

Automation must never remove user ownership.

---

# Article VII — Reliability Over Features

Stability is more important than feature count.

A smaller, dependable system is preferable to a larger, unreliable one.

Every new feature should improve the platform without reducing its overall reliability.

---

# Article VIII — Documentation Is Part of the Code

Documentation is a required part of development.

Major architectural changes should be reflected in the documentation.

Engineering decisions should be recorded for future reference.

Code without documentation creates technical debt.

---

# Article IX — Modularity

The platform should be composed of independent modules with clearly defined interfaces.

Modules should communicate through well-defined boundaries.

Changes in one subsystem should have minimal impact on others.

---

# Article X — Maintainability

Future maintainability should always be considered during development.

When faced with multiple valid solutions, prefer the one that is easier to understand, test, debug, and extend.

The future developer is often the current developer several months later.

---

# Article XI — Context Preservation

FRIDAY should preserve important context whenever practical.

Information should not be forgotten without reason.

Memory systems should prioritize continuity while respecting user control and privacy.

---

# Article XII — Continuous Improvement

Every release should improve at least one of the following:

- Reliability
- Performance
- Maintainability
- Understanding
- User Experience

Progress should be deliberate and measurable.

---

# Amendment Process

This constitution is intended to evolve.

Changes should be rare, carefully considered, and documented.

Every amendment should improve the long-term quality of the platform rather than solve a temporary problem.

---

# Final Principle

When uncertainty exists, choose the option that best supports:

- Learning
- Reliability
- Transparency
- User Control
- Long-term Maintainability

These principles take precedence over convenience.

---

Version: v1.0 — Genesis
Last Reviewed: 2026-07-30