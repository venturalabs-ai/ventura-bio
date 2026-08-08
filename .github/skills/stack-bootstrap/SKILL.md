---
name: stack-bootstrap
description: Bootstrap the smallest VenturaBio Python structure for the approved bioinformatics MVP using declared stack needs. Use when the repository is ready to move from incubation docs to executable code. Do not use when a functional analysis project already exists or the task is only product scoping.
---

# Stack bootstrap

- Confirm the approved analysis question before adding dependencies.
- Add only packages required by the first Biopython or API path.
- Separate domain code tests and a small public or synthetic dataset fixture.
- Record dataset provenance and keep large datasets out of Git.
- Add one deterministic smoke test from input to analysis output.
- Document supported formats and computational limitations.
- Reuse the shared repository CI standard.
