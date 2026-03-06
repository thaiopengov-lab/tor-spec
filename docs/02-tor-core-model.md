# TOR Core Model

This document defines the canonical baseline structure of a TOR document for **TOR Specification v0.1**.

The goal is not to prescribe every possible section, but to define a minimum model that is clear, reusable, and suitable for future machine-readable extension.

---

## Core Sections

A conforming TOR document should contain the following core sections.

| Section | Description | Required |
| --- | --- | --- |
| Background | Context, rationale, and relevant situation | Yes |
| Objectives | What the project is intended to achieve | Yes |
| Scope of Work | Activities, responsibilities, and work boundaries | Yes |
| Deliverables | Expected outputs, services, or results | Yes |
| Timeline | Milestones, schedule, or expected delivery period | Yes |
| Acceptance Criteria | Conditions for review and acceptance | Yes |
| Assumptions & Constraints | Known dependencies, limitations, or operating conditions | Optional |
| Dependencies | External systems, actors, approvals, or prerequisite work | Optional |
| Budget | Budget envelope or financial constraints where appropriate | Optional |
| Vendor Qualification | Qualification rules when procurement context requires them | Optional |
| Evaluation Criteria | Proposal assessment logic when applicable | Optional |

---

## Modeling Notes

### Background
Background explains why the project exists in its current context.

### Objectives
Objectives state the intended goals of the project.

### Scope of Work
Scope defines what work is included and what responsibilities are expected.

### Deliverables
Deliverables identify what must be produced or provided.

### Timeline
Timeline establishes when work, milestones, or outputs are expected.

### Acceptance Criteria
Acceptance criteria define how completion or adequacy will be judged.

---

## Design Intention

The core model is designed to support the following properties:

- consistent reading by humans
- easier comparison across TOR documents
- future conversion to formal schemas
- a stronger link between objectives, work, deliverables, and acceptance

This version is intentionally compact.
