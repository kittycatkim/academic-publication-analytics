PROJECT OVERVIEW
----------------
This project develops and evaluates advanced statistical count models using 
Maximum Likelihood Estimation (MLE) to understand factors driving academic 
publication productivity. It addresses unobserved heterogeneity, structural 
zero-inflation, and data overdispersion.

MODELS IMPLEMENTED
------------------
1. Poisson Regression: Evaluates covariate baselines but remains restricted 
   by the equidispersion property.
2. NBD Regression: Integrates a mathematical dispersion parameter alongside 
   demographic traits to successfully account for variance spikes.
3. Zero-Inflated & Finite Mixture Models: Account for the distinct structural 
   segments of individuals who face zero probability of a count event.

KEY FINDINGS
------------
* Model Selection: The NBD Regression model significantly outperformed the 
  alternatives across Log-Likelihood, AIC, and BIC verification metrics.
* Critical Predictors: Gender (female), Marital Status (married), and the 
  number of young children (kids) emerged as statistically significant 
  drivers influencing academic productivity metrics.

FILE MANIFEST
-------------
* project-II-group07.docx  : Comprehensive business analytics report.
* project_II_group07.ipynb : Jupyter implementation containing code, MLE 
                             solvers, data visualizations, and metrics.
* articles.csv             : Primary dataset detailing publication counts, 
                             prestige indices, and demographic attributes.
* candy.csv & radio.csv    : Replicated benchmarking data for baseline counts.
========================================================================