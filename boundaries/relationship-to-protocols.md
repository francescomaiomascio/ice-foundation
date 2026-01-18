# Boundary: Foundation ↔ Protocols

## Purpose

Define and formalize the **conceptual boundary** between the **ICE Foundation**
and the **ICE Protocols** domain.

This document establishes that **communication semantics, message formats,
and interaction contracts** do not possess foundational authority and must
never redefine axioms, structural invariants, or conceptual validity.

The goal is to prevent **interaction mechanisms** from collapsing into
**epistemic or authoritative truth**.

---

## Foundational Position

The ICE Foundation is **pre-communicative** and **non-interactive**.

It defines:

- Axioms that establish what is assumed to be true
- Structural invariants that constrain authority, traceability, and determinism
- Conditions under which interactions are considered valid
- Semantic constraints on what interactions may *mean*

The Foundation does **not** communicate.

The Foundation does **not** encode messages.

---

## Role of the Foundation

The ICE Foundation:

- Defines **semantic validity** of interactions
- Establishes **authority and responsibility constraints**
- Constrains what communication is allowed to represent
- Determines when an interaction is conceptually invalid

The Foundation defines **meaning**,  
not **transport** or **syntax**.

---

## Role of Protocols

ICE Protocols:

- Define message schemas, contracts, and interaction formats
- Encode events, requests, responses, and signals
- Manage serialization, transport, and interoperability
- Handle versioning and compatibility concerns

Protocols answer **how systems communicate**,  
never **what is true** or **what is allowed to occur**.

---

## Explicit Non-Responsibilities of the Foundation

The ICE Foundation does **NOT** define, imply, or govern:

- Message or event schemas
- Wire formats or payload encodings
- Transport layers or networking protocols
- API definitions or endpoint structures
- Version negotiation strategies
- Backward or forward compatibility mechanisms
- Interoperability standards

All such concerns belong **exclusively** to the Protocols domain.

---

## Constraint Relationship

The relationship is asymmetric:

- The Foundation constrains **semantic validity**
- Protocols encode and transmit interactions
- Protocols may evolve independently
- Protocols may not reinterpret axioms or invariants

If a protocol enables interactions that violate
authority, traceability, or determinism,
the protocol is invalid — not the Foundation.

---

## Boundary Violations

The following constitute **boundary violations**:

- Encoding authority rules inside protocol definitions
- Treating protocol acceptance as semantic validity
- Allowing transport success to imply correctness
- Using protocols to bypass invariants or governance
- Redefining meaning through message formats

Such actions invalidate ICE compliance.

---

## Canonical Status

This boundary definition is **canonical and authoritative**.

Any protocol claiming ICE compliance must demonstrate
that its interaction contracts and communication mechanisms
operate strictly within the constraints defined here.

The Foundation constrains Protocols.  
Protocols never redefine the Foundation.