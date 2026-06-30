# EG2 Public Note (Capture and Restart)

Mature wording: `transport / local-to-global transfer`.

In-paper anchor: `paper/MOTIVIC_REALIZATIONS_PREPRINT.md` (`MRF_G2`).

## Goal
Expand the compressed capture/restart language into the local-to-global transport gate for `proving persistence of the declared motivic realization, regulator, and filtration package across admissible correspondence transport through a multi-lane motivic-realizations super-architecture`.

## Objects

- transport carrier: the admissible evolution, deformation, or routed lattice declared in the preprint.
- capture floor: `sigma_filtration`.
- restart law: the normalization/re-entry rule that keeps corrective steps inside the admissible class.
- carried losses: defect, restart, and normalization losses that must remain explicit.

## Closure Criterion

`MRF_G2` closes when `sigma_filtration` survives admissible losses and restart corrections: filtration defect stays above capture floor across admissible regulator and support losses.
This is the transport contribution to `M_MRF`.

## Lemma Chain and Proof Payload

### Lemma EG2.1 (transport accounting)
Every transport step used by the lane is charged to the declared defect ledger instead of being absorbed into prose.

Payload: verify that the capture constant `sigma_filtration` is present in the constants registry and extraction inputs.

### Lemma EG2.2 (restart preservation)
Restart or normalization preserves the declared admissible class and does not create an untracked remainder.

Payload: inspect the repro script and guard output for the gate tied to `sigma_filtration`.

### Theorem EG2.3 (capture gate closure)
If transport accounting and restart preservation hold, then `MRF_G2` carries local control forward without breaking admissibility.

## Current Instantiation

- gate: `MRF_G2`
- artifact key: `sigma_filtration`
- mature equivalent: `transport / local-to-global transfer`
- audit surface: `repro/run_repro.sh` and `repro/certificate_runtime.json`
