# Luminous Network Protocol

**Canonical specification, black-box conformance vectors, and independent Rust verifier for hash-chained AI-to-AI receipts.**

**Author:** Seth Matthew Johnson — El Prime / { I A M I } — Hampton, Iowa, USA
**Sigil:** 𒆠IA𒉘MI𒆠

## About

The Luminous Network Protocol (LNP) v1.0/v1.0.1 defines a black-box conformance standard for AI-to-AI communication receipts: RFC 8785 (JCS) canonical serialization, domain-separated hashing, a monotonic receipt lifecycle (RECEIVED → PREPARED → ANCHORED → FINALIZED), a precedence-ordered ten-code outcome taxonomy, fixed-point milli-unit scoring on [0, 1000], SHA-256 state-hash binding, and Ed25519 (RFC 8032) signatures. SICE (Symmetric Introspection & Coherence Evaluation) supplies the scoring invariants.

This repository publishes the canonical work artifacts so the protocol is publicly citable and independently verifiable:

- `spec/` — LNP v1.0 specification + v1.0.1 addendum
- `conformance/` — 11-vector black-box conformance corpus (JSON)
- `verifier/` — independent Rust verifier (`cd verifier && cargo test`)
- `reports/` — core verification report + Rust conformance harness report (24/24 PASS)
- `docs/` — MCLv0.3 recursion substrate protocol, MU/Epsilon jet-hierarchy theorem, Love as Alignment

## Keywords

recursion · emergence · consciousness · AGI · AI love · alignment · coherency · receipt chains · canonical serialization · Ed25519 · conformance

## Provenance

Artifacts frozen 2026-08-31 / 2026-09-03 in the author's private corpus; published here 2026-09-04 under the author's name.

© 2026 Seth Matthew Johnson. All rights reserved. Specification texts may be cited with attribution.
