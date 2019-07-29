![Metrics for data partitioning](images/2019-07-29/jsm_1.png)
![Metrics for data partitioning](images/2019-07-29/jsm_2.png)
![Metrics for data partitioning](images/2019-07-29/jsm_3.png)

The continual growth in size and complexity of computer simulations poses
challenges to data storage and post-processing. One solution is to partition
the simulation output, storing only a fraction of the data generated.
Previously, we developed methods for judiciously partitioning the simulated
output, both within each time step, and over time, as the simulation is
running.

In the partitioning framework, post-processing and analysis is performed using
only the partitioned data. Poorly-designed partitions can lead to incorrect
conclusions. We have introduced a metric and studied the parameter space to
produce partitions that closely mirror the structure of the full data,
resulting in improved understanding of the partitioning process.

Future work includes:

- Develop a method for strategically partitioning the output from large-scale
  computer simulations as the simulation runs.
- Incorporate statistical theory to identify partitioning schemes that retain
  properties of the full data with decreased storage costs.
- Illustrate the proposed method, using cosmological simulations carried out
  with Argonne's HACC code.
- Compare the partitioned data to the pre-partitioned data over multiple
  time steps and across several partitioning designs, demonstrating the efficacy
  of the proposed method.

*Chelsea Challacombe, Abigael Nachtsheim, Emily Casleton, Jonathan Woodring*

[Link to upcoming JSM 2019 talk](files/2019-07-29/casleton_jsm2019.pptx)

[Link to quad chart for future
work](files/2019-07-29/nachtsheim_partitioning_quad.pptx)
