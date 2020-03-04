[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nimh-mbdu/great_expectations/master)  
# great_expectations
Code and source data for the manuscript "Great Expectations: A Critical Review of and Recommendations for the study of Reward Processing as a Cause and Predictor of Depression".

Cleaned datasets and figures are also available on the projects OSF page: https://osf.io/whvam/  
Our primary meta-analysis was preregisterred https://osf.io/be4nt, https://osf.io/mp49y, https://osf.io/3dz54

There are three notebooks in this repository:  
`notebooks/diagrams_based_on_other_reviews.ipnyb` contains code for figures 1 and 2.  
`notebooks/metaanalysis.ipnyb` contains code for our primary metaanalysis and figure 3. Note that MetaNsue, the tool we used for our meta-analysis has some variability in results from run to run if it is estimating null effects, so your results may not exactly match our published values, but should be accurate to within several 100ths.  
`notebooks/account_for_measurment_error.ipynb` contains code for our exploratory analysis of the impact of measurement error on our meta-analytic findings.