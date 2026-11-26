# Study 001 — Parameter identification in a dynamical system

Status: planned; no implementation or results yet.

**Question:** How do noise and sampling frequency affect estimation of k in dy/dt = -k y?

**Prerequisites:** separable ODEs, least squares, random noise and basic numerical optimization.

## Mission
- Derive the analytic solution; solve a noiseless two-observation example by hand.
- Generate seeded synthetic observations and fit k using nonlinear least squares. Compare against a log-linear estimator, discussing when it is invalid or biased.
- Vary sample frequency, noise and observation horizon; report parameter error and identifiability limitations.
- Test recovery in the noiseless case and distinguish observation error from model error.
- Transfer the formulation to parameter identification in an energy system.

Consult SciPy's least_squares documentation: https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.least_squares.html. Select a suitable theoretical reference before implementation. Introduce automatic differentiation only after the baseline is understood.
