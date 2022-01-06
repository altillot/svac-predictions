# svac-predictions

**Overview:** Predicting sexual violence prevalence in armed conflicts using the SVAC dataset and World Bank indicators (in R)

**Description:** This was my final project for Data Mining for the Social Sciences (graduate course). In it, I recode several variables in the Sexual Violence in Armed Conflict (SVAC) and World Bank indicators datasets. I then use both data sets to perform two types of supervised learning tasks: (1) fitting a regression model to predict the sexual violence prevalence score in a given conflict-actor dyad and (2) fitting a classification model to predict sexual violence typology by country. For the first task, I additionally use the model that performed the best to predict sexual violence prevalence for countries that have *not yet had* an armed conflict in recent years.

**Models Used**:
- Random Forest Regression Model
- Elastic Net Regression Model
- MARS (Multivariate Adaptive Regression Splines) Regression Model
- Random Forest Classification Model
- Elastic Net Classification Model
- BART (Bayesian Additive Regression Trees) Classification Model

**Packages Used:** 
- tidyverse
- tidymodels
- countrycode
