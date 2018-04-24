## Release v0.1.0

This is the initial release of the package. It provides a simplified interface over DifferentialEquations.jl. Currently it's interfaced via 5 functions:

- diffeq_setup
- ode.solve
- sde.solve
- dae.solve
- dde.solve

The return is a list with sol$u and sol$t. In future updates this will be backwards compatibly updated to be a full solution object with the interpolation.
