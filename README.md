# TOR Specification

**tor-spec** is an early open specification project for structured, machine-readable, and AI-friendly Terms of Reference (TOR).

Its role is practical, but also foundational:

- to improve how TOR documents are structured
- to reduce ambiguity in project specification
- to support future validation and automation
- to prepare a bridge toward more traceable intent-centered models

---

## Why this repository exists

Many TOR documents are readable only as static narrative text. They are often difficult to compare, validate, reuse, or analyze consistently.

In practice, this can contribute to problems such as:

- unclear project scope
- weak linkage between objectives and deliverables
- inconsistent evaluation logic
- compliance-oriented documents that are hard to reason about
- limited machine support for review and analysis

`tor-spec` exists to define a clearer baseline.

---

## Current scope

Version **v0.1** focuses on the minimum conceptual layer needed for a structured TOR model.

Current work includes:

- terminology
- core sections
- minimum conformance rules

This repository intentionally stays small at this stage.

---

## Position in the ecosystem

This repository should be understood as an **application-level specification** within a larger emerging direction.

Today, it focuses on TOR.
Over time, its concepts may connect to broader work on:

- intent traceability
- structured governance documents
- machine-readable specifications
- validation and analysis tooling

In other words, `tor-spec` is not the final theory of the ecosystem. It is one of the first practical building blocks.

---

## Specification documents

| Document | Description |
| --- | --- |
| [`docs/01-terminology.md`](docs/01-terminology.md) | Definitions and baseline concepts used in this repository |
| [`docs/02-tor-core-model.md`](docs/02-tor-core-model.md) | Canonical TOR sections and their role in the model |
| [`docs/03-conformance.md`](docs/03-conformance.md) | Minimum conditions for a TOR document to conform to this specification |

---

## Design principles

1. **Clarity first** — the structure should reduce ambiguity rather than add ceremony.
2. **Vendor neutrality** — the model must not assume a specific product, provider, or implementation path.
3. **Agency neutrality** — the structure should remain useful across institutions and jurisdictions.
4. **Machine readability** — the model should support future automation, validation, and AI-assisted analysis.
5. **Human usability** — the specification must remain understandable to practitioners, not only machines.

---

## What this repository does not do yet

This repository does **not yet** define:

- JSON schemas
- formal validation tooling
- example corpora
- scoring models
- intent traceability graphs
- anti-vendor-lock review patterns

Those may be introduced later in separate repositories or later phases.

---

## Roadmap direction

Near-term evolution may include:

- richer terminology
- stronger linkage between objectives, scope, deliverables, and acceptance criteria
- extension sections for constraints, dependencies, and evaluation logic
- examples and conformance profiles
- compatibility with future intent-centered modeling work

---

## Contributing

Contributions are welcome.

Please use issues and pull requests to propose:

- terminology improvements
- structural refinements
- conformance clarifications
- implementation-neutral extensions

For organization-level guidance, see:

- [ThaiOpenGovLab CONTRIBUTING.md](https://github.com/thaiopengov-lab/.github/blob/main/CONTRIBUTING.md)
- [ThaiOpenGovLab GOVERNANCE.md](https://github.com/thaiopengov-lab/.github/blob/main/GOVERNANCE.md)

---

## License

See [`LICENSE`](LICENSE).
