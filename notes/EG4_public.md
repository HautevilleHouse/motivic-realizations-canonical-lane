# EG4 Public Note

The `EG4` package establishes rigidity exclusion of bad limits and transfer to the intended endpoint class.

Raw transfer constant:

`regulator_transfer^(raw) := c_regulator_raw * transfer_gain_raw - e_regulator_raw`.

Closure criterion:

- bad limits violate rigidity and are excluded,
- extracted admissible limits transfer to the endpoint class,
- the final scalar margin remains positive.
