# Menstrual blood loss is an important determinant of Hb and ferritin levels in premenopausal blood donors

This repository contains R code to reproduce the analyses for the manuscript _Menstrual blood loss 
is an important determinant of Hb and ferritin levels in premenopausal blood donors_ by Ekroos S., 
Karregat J., Toffol E., Castrén J., Arvas M. and van den Hurk K.

The code is included in three separate .Rmd files. The first part, _menstruation_data.Rmd_, allows
the user to describe the DIS III cohort, filter participants based on eligibility, preprocess data, produce figures for the manuscript 
and build a summary table to be used in further regression analysis. The second part, _menstruation_linear_regression.Rmd_, can be used to 
run Bayesian linear regression analyses as well as relative importance analyses on ferritin and Hb. The third part, 
_menstruation_logistic_regression3.Rmd_, allows the user to run Bayesian logistic regression analyses
on iron deficiency and anaemia. 

Information on packages needed to run the code is included in the .Rmd:s. The appropriate version of 
the relaimpo package is available to download directly from the package's author's  
[webpage](https://prof.bht-berlin.de/groemping/software/relaimpo/). Please note that the code requires 
the non-US version of the package to run the pmvd analyses.

For questions regarding the code or manuscript, please contact S Ekroos (sofie (dot) ekroos (at)
helsinki (dot) fi).
