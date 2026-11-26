# Study 001 — Battery dispatch as a linear program

Status: planned; no implementation or results yet.

**Question:** When does a price-threshold rule become suboptimal for a finite-capacity battery?

**Prerequisites:** energy balance, linear inequalities, feasible sets and objective functions.

**Reading:** Boyd and Vandenberghe, *Convex Optimization*, section 4.3 (linear optimization), https://web.stanford.edu/~boyd/cvxbook/.

## Mission
- Derive the discrete battery energy balance and units.
- Solve by hand a two-period example with prices 0.10 and 0.40 per kWh, 2 kWh capacity, 1 kW charge/discharge limits, one-hour steps, unit efficiency and zero initial/final energy.
- Formulate a 24-period LP with realistic efficiencies, power limits and matching initial/final state; compare with a feasible heuristic.
- Verify balance, bounds, terminal state and solver status. Examine whether simultaneous charging/discharging must be explicitly excluded.
- Vary prices and efficiencies; explain limitations and transfer the formulation to a water reservoir.

Deliver a derivation, code, tests, baseline comparison and reviewed self-assessment. Do not generate the complete solution before the independent exercise unless requested.
