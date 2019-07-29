![Uncertainty visualizations using Copula-based
Analysis](images/2019-07-29/copula.png)

Distributions are often used to model uncertainty in many scientific datasets.
To preserve the correlation among the spatially sampled grid locations in the
dataset, various standard multivariate distribution models have been proposed
in visualization literature.  These models treat each grid location as a
univariate random variable which models the uncertainty at that location.
Standard multivariate distributions (both parametric and nonparametric) assume
that all the univariate marginals are of the same type/family of distribution.
But in reality, different grid locations show different statistical behavior
which may not be modeled best by the same type of distribution.  In this paper,
we propose a new multivariate uncertainty modeling strategy to address the
needs of uncertainty modeling in scientific datasets.

Our proposed method is based on a statistically sound multivariate technique
called *Copula*, which makes it possible to separate the process of estimating
the univariate marginals and the process of modeling dependency, unlike the
standard multivariate distributions.  The modeling flexibility offered by our
proposed method makes it possible to design distribution fields which can have
different types of distribution (Gaussian, Histogram, KDE etc.) at the grid
locations, while maintaining the correlation structure at the same time.
Depending on the results of various standard statistical tests, we can choose
an optimal distribution representation at each location, resulting in a more
cost efficient modeling without significantly sacrificing on the analysis
quality.  To demonstrate the efficacy of our proposed modeling strategy, we
extract and visualize uncertain features like isocontours and vortices in
various real world datasets.  We also study various modeling criterion to help
users in the task of univariate model selection.

*Subhashis Hazarika, Ayan Biswas, Han-Wei Shen*

[Link to paper in IEEE
Xplore](https://ieeexplore.ieee.org/abstract/document/8017601)
