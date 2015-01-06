As it becomes more difficult to analyze large-scale simulation output at full
resolution, users will have to review and identify regions of interest by
transforming data into compact information descriptors that characterize
simulation results and allow detailed analysis on demand. This is because
exascale architectures will be much more constrained with respect to data
movement, and *in situ* data processing will be the norm, where the goals are to
fit the total amount of output data within a budget, to summarize and triage
data based on content, and to classify and index data to facilitate efficient
offline analysis. In addition, *in situ* analysis must be performed in a time 
and space efficient fashion, not only to avoid slowing down the simulation, but
also to not consume too much memory.  

Among many different feature descriptors,
the statistical information derived from data samples is a promising approach
to taming the big data avalanche, because data distributions computed from a
population can compactly describe the presence and characteristics of salient
features with minimal data movement.  The ability to computationally summarize
and process data using distributions provides an efficient and representative
capture of the information content of a large-scale data set. This
representation can adjust to size and resource constraints, with the added
benefit that uncertainty can be quantified and communicated.  

In this project,
*we posit that with the growing number of cores per node, with increasing memory
and I/O constraints in emerging extreme-scale platforms, it will be feasible
and desirable to compute distributions at simulation time, perform
memory-efficient* in situ *analysis using distributions, and save distributions
as a space-efficient summarization for on-demand, offline visualization and
analysis of salient features.* The key development will be a novel
distribution-based analysis and visualization framework based on in situ pro-
cessing of extreme-scale scientific data. Our goals are to ensure that
scientists can easily obtain an overview of the entire data set regardless of
the size of the simulation; understand the characteristics and locations of the
features; easily interact with the data and select regions and features of
interest; and perform all the analysis tasks with a small memory footprint.
