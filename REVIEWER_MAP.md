# Reviewer Map

## Claim Scope

- Canonical-lane claim: inside the `manifold_constrained` routed lattice, if the theorem chain in this repository holds and the guard certificate passes, the repository-level super-lane closure claim is satisfied.
- Standard target claim: carried by the in-repo bridge theorems tying the lane to the target statement.
- External-strengthening rule: any statement beyond the admissible class must retain the explicit remainder carried by the defect/coherence ledgers; see `notes/GEOMETRIC_GALOIS_BRIDGE.md`.

## Super-Lane Families

1. `realization and fiber-functor compatibility packages`
2. `cycle-class, weight, and filtration transport packages`
3. `regulator and special-value compatibility packages`
4. `support, vanishing, and correspondence transport packages`
5. `local-global stitching of the declared motivic-realization endpoint package`

## Theorem Dependency Chain

1. `EG1`: coercive response and active control floor.
2. `EG2`: capture and admissible continuation.
3. `EG3`: compactness and no-collapse spacing.
4. `EG4`: rigidity and transfer.
5. Identification bridge: strict coherence on the determining class.
6. Scalar closure: `MRF_G1`, `MRF_G2`, `MRF_G3`, `MRF_G4`, `MRF_G5`, `MRF_G6`, `MRF_GM` all `PASS`.

Primary files:

- `paper/MOTIVIC_REALIZATIONS_PREPRINT.md`
- `notes/EG1_public.md`
- `notes/EG2_public.md`
- `notes/EG3_public.md`
- `notes/EG4_public.md`
- `notes/IDENTIFICATION_BRIDGE.md`
- `notes/GEOMETRIC_GALOIS_BRIDGE.md`

## Closure Gates

| Gate | Constant | Description |
|------|----------|-------------|
| `MRF_G1` | `kappa_realization` | projected realization response has a strict positive floor |
| `MRF_G2` | `sigma_filtration` | filtration defect stays above capture floor across admissible regulator and support losses |
| `MRF_G3` | `kappa_compact` | normalized near-failure families are precompact and admissible windows do not collapse |
| `MRF_G4` | `rho_rigidity` | bad motivic countermodels are excluded |
| `MRF_G5` | `regulator_transfer` | rigid limit transfers to the motivic endpoint package |
| `MRF_G6` | `eps_coh` | strict coherence / identification closure |
| `MRF_GM` | derived | final strict margin |

## Falsification Conditions

- `repro/certificate_runtime.json` has any non-`PASS` gate.
- `lane.active_lane != "manifold_constrained"`.
- `all_pass != true`.
- Any manifest hash mismatch under `repro/repro_manifest.json`.
- A verified counterexample to any EG theorem statement used in the paper.
