# SchwarzschildLorenzGaugeReconstruction
Compute the Lorenz gauge metric perturbation of Schwarzschild spacetime using Berndtson's method of reconstruction from Regge-Wheeler scalars. Supports calculation of both the metric perturbation and its slow time derivative for circular orbits.

To run the code, start a Mathematica kernel and set a value for `r0`, the radius of the cirular orbit, then load the package using `Get["SlowTimeDerivativeOfMetric.m"]`. The package expects a file `grids/radial_grid_rXX.X.h5` and will output to a directory `dr0_h1/r0_XX.X`.
