### CostTrajectory: fits two-dimensional P-splines estimating equations for mean cost trajectory estimation.

#### Description

Medical claims data has become an increasingly important tool in cancer diagnosis, treatment and costs given its longitudinal assessment of clinical outcomes associated with cancer care and resourceful information based on large population.
The aim of this research is to develop an estimating equation approach to integrate massive cost and survival data to access the mean medical cost trajectory in population level, allowing for unignorable heterogeneity and right-censoring. 
Such adjustment is motivated by investigating the association between medical costs and survival in state-wide medical claims data, for which the cost data are right-skewed with a large proportion of zero values and heavily censored. 
Ignoring such data features may distort the accuracy of statistical inference and produce misleading results. To address these issues, we propose a two-part marginal model to depict the censoring mechanism and incorporate flexible mean and variance models to account for heteroskedasticity followed by a P-spline framework with sandwich variance estimator to conduct statistical inference. 
This approach is verified in simulation studies as presented in the example page. 

### Installing the development version from GitHub:

install.packages("devtools")

devtools::install_github("ShikunW/CostTrajectory")
