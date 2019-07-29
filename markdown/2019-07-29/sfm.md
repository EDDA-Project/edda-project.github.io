![SFM](images/2019-07-29/sfm.png)

Visualizing and analyzing data with uncertainty are important in many science
and engineering domains, such as computational fluid dynamics, climate,
weather, and materials sciences. Instead of analyzing deterministic data
resulted from statistical aggregation, scientists can gain more understanding
by investigating uncertain data that are derived and quantified from
experiments, interpolation, or numerical ensemble simulations. For example,
typical analyses of uncertain flows involve finding possible pollution
diffusion paths in environmental sciences with uncertain source-destination
queries and locating uncertain flow boundaries in computational fluid dynamics
models with uncertain Lagrangian analysis.

We present an efficient and scalable solution to estimate uncertain transport
behaviors—stochastic flow maps (SFMs)—for visualizing and analyzing uncertain
unsteady flows.  Computing flow maps from uncertain flow fields is extremely
expensive because it requires many Monte Carlo runs to trace densely seeded
particles in the flow. We reduce the computational cost by decoupling the time
dependencies in SFMs so that we can process shorter sub time intervals
independently and then compose them together for longer time periods. Adaptive
refinement is also used to reduce the number of runs for each location. We
parallelize over tasks—packets of particles in our design—to achieve high
efficiency in MPI/thread hybrid programming. Such a task model also enables
CPU/GPU coprocessing. We show the scalability on two supercomputers, Mira (up
to 256K Blue Gene/Q cores) and Titan (up to 128K Opteron cores and 8K GPUs),
that can trace billions of particles in seconds.

*Hanqi Guo; Wenbin He; Sangmin Seo; Han-Wei Shen; Tom Peterka*

[Link to paper in OSTI](https://www.osti.gov/biblio/1366303)
