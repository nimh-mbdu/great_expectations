[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nimh-mbdu/great_expectations/master)  
# great_expectations
Code and source data for the manuscript "Great Expectations: A Critical Review of and Suggestions for the study of Reward Processing as a Cause and Predictor of Depression".
Published at: https://www.biologicalpsychiatryjournal.com/article/S0006-3223(20)31700-5/fulltext

Cleaned datasets and figures are also available on the projects OSF page: https://osf.io/whvam/  
Our primary meta-analysis was preregisterred https://osf.io/be4nt, https://osf.io/mp49y, https://osf.io/3dz54

There are four notebooks in this repository:  
`notebooks/diagrams_based_on_other_reviews.ipnyb` contains code for Figure 2D and Supplemental Figure S9.  
`notebooks/metaanalysis.ipnyb` contains code for our primary metaanalysis and Figure 2, as well as Supplemental Figures S2 through S7. Note that MetaNsue, the tool we used for our meta-analysis has some variability in results from run to run if it is estimating null effects, so your results may not exactly match our published values, but should be accurate to within several 100ths.  
`notebooks/account_for_measurment_error.ipynb` contains code for our exploratory analysis of the impact of measurement error on our meta-analytic findings, displayed in Figure 3 and Supplemental Figure S8.  
`notebooks/MID BrainMap.ipynb` contains code for creating the combined visualization of previous meta-analyses in Figures 1A and 1B. This requires AFNI to run and won't work on binder.

The [main text](nielson_et_al_main_text.pdf) and [supplemental materials](nielson_et_al_supp_materials.pdf) are also available in this repository. 