![eFESTA](images/2019-07-29/sde.png)

Ensemble simulations are becoming prevalent in various scientific and
engineering domains, such as climate, weather, aerodynamics, and computational
fluid dynamics. An ensemble is a collection of data produced by simulations for
the same physical phenomenon conducted with different initial conditions,
parameterizations, or phenomenological models. Ensemble simulations are used to
simulate complex systems, study sensitivities to initial conditions and
parameters, and mitigate uncertainty. For example, in numerical weather
prediction, ensemble forecasts with different fore- cast models and initial
conditions are widely used to indicate the range of possible future states of
the atmosphere.

We propose surface density estimate (SDE) to model the spatial distribution of
surface features—isosurfaces, ridge surfaces, and streamsurfaces—in 3D ensemble
simulation data. The inputs of SDE computation are surface features represented
as polygon meshes, and no field datasets are required (e.g., scalar fields or
vector fields). The SDE is defined as the kernel density estimate of the
infinite set of points on the input surfaces and is approximated by
accumulating the surface densities of triangular patches. We also propose an
algorithm to guide the selection of a proper kernel bandwidth for SDE
computation. An ensemble Feature Exploration method based on Surface densiTy
EstimAtes (eFESTA) is then proposed to extract and visualize the major trends
of ensemble surface features. For an ensemble of surface features, each surface
is first transformed into a density field based on its contribution to the SDE,
and the resulting density fields are organized into a hierarchical
representation based on the pairwise distances between them. The hierarchical
representation is then used to guide visual exploration of the density fields
as well as the underlying surface features. We demonstrate the application of
our method using isosurface in ensemble scalar fields, Lagrangian coherent
structures in uncertain unsteady flows, and streamsurfaces in ensemble fluid
flows.

*Wenbin He, Hanqi Guo, Han-Wei Shen, Tom Peterka*

[Link to paper in IEEE
Xplore](https://ieeexplore.ieee.org/abstract/document/8525340)
