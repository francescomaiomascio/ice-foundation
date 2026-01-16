# ICE Foundation — Glossary

This glossary defines the **controlled terminology** of the ICE Foundation.

Its purpose is to prevent semantic drift, ambiguity, and reinterpretation
of foundational concepts across the ICE ecosystem.

All terms defined here are **authoritative** within the scope of the Foundation.
Downstream projects may extend vocabulary, but must not redefine these terms.

---

## Purpose

The glossary exists to:

- ensure consistent meaning across repositories and projects
- prevent implicit redefinition of foundational concepts
- provide a shared semantic reference for reasoning and documentation
- separate *terminology* from *implementation language*

The Foundation governs meaning.
Implementations consume meaning.

---

## Scope

This glossary includes:

- core conceptual terms used in axioms, invariants, and boundaries
- terms that define authority, execution, state, and governance
- epistemic distinctions critical to ICE correctness

It intentionally excludes:

- implementation-specific terms
- technology or framework names
- runtime, tooling, or API vocabulary
- domain-specific extensions

---

## Canonical Terms

### Axiom

A foundational assumption taken as true by definition and not derived from
lower-level mechanisms.

Axioms constrain what ICE is allowed to mean.
They are non-configurable, non-derivable, and authoritative.

---

### Structural Invariant

A non-negotiable constraint that must always hold for a system to be considered
a valid instance of ICE.

Structural invariants derive authority from axioms and make them enforceable
over time.

---

### Foundation

The conceptual layer of ICE that defines axioms, structural invariants,
epistemic boundaries, and authoritative meaning.

The Foundation defines truth, not behavior.

---

### Execution

The act of carrying out actions, transitions, or effects within a system.

In ICE, execution is constrained by axioms and invariants but never defines them.

---

### Runtime

The domain responsible for executing actions, managing lifecycle, and enforcing
constraints during operation.

The Runtime implements behavior within limits defined by the Foundation.

---

### Authority

The property by which actions, decisions, or state transitions are considered
valid and enforceable within ICE.

Authority must be explicit, traceable, and never inferred implicitly.

---

### Inference

The process of deriving conclusions, intentions, or proposals from information.

Inference may inform decisions but never grants authority to act.

---

### Control

The enforcement of authority over execution.

Control determines what is allowed to happen, independent of inference quality.

---

### State

A derived, inspectable artifact representing the outcome of execution.

State is not a cause, configuration, or source of authority.

---

### Traceability

The property by which actions, decisions, and state transitions can be
attributed, reconstructed, and reasoned about after execution.

Traceability is a structural invariant.

---

### Determinism

The property by which system behavior, given the same conditions and constraints,
produces equivalent outcomes within a defined scope.

Determinism enables reconstruction, not prediction.

---

### Reproducibility

The ability to re-execute or reconstruct system behavior and obtain
behaviorally equivalent results.

Reproducibility is required for governance and accountability.

---

### Governance

The invariant by which authority, responsibility, and control remain enforceable
over time, across system evolution.

Governance is structural, not procedural.

---

### Consciousness

The domain responsible for long-term memory, historical continuity,
and retrospective reasoning.

Consciousness preserves context over time but does not define truth or authority.

---

### Boundary

An explicit conceptual separation defining what the Foundation does and does not
govern with respect to other domains.

Boundaries prevent semantic overreach.

---

## Terminology Governance

- Terms defined here may not be redefined downstream
- New foundational terms require explicit inclusion
- Ambiguous or overloaded terms must be clarified or rejected

Terminology changes are **conceptual changes**.

---

## Final Note

Language shapes architecture.

A stable system requires stable meaning.
This glossary exists to ensure ICE remains coherent as it evolves.
