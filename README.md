# Features of Major ML Algorithms

Compares properties of some of the most important classes of supervised ML algorithms applicable to both regression and classification problems. We are not thinking about a specific implementation but rather about the "typical" implementation.

- **GLM**: Generalized linear model (linear regression, logistic regression, multinomial, Poisson, Gamma, ...) with optional Elastic-Net penalties
- **Neural Net**: Artificial neural net fitted by backprop
- **Gradient boosting**: Boosted trees (Ada Boost, XGBoost, LightGBM, CatBoost,...)
- **Random Forest**
- **k-Nearest Neighbour**

Aspect         | GLM       | Neural Net      | Gradient Boosting | Random Forest  | k-Nearest Neighbour
:------------ | :-------------| :-------------| :------------- | :------------- | :-------------
Scalable  | :smiley:  | :smiley: | :relaxed: | :neutral_face: |  :unamused:
Easy to tune  | :relaxed:  | :neutral_face: | :neutral_face: | :smiley: |  :neutral_face:
Flexible losses |:relaxed: | :smiley: | :relaxed: | :neutral_face: | :relaxed:
Regularization | :heavy_check_mark:| :heavy_check_mark:| :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Case weights | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Missing input allowed | :unamused: | :unamused: | :heavy_check_mark: | :unamused: | :unamused:
Interpretation | :smiley: | :neutral_face: | :neutral_face: | :neutral_face: | :neutral_face:
Space on disk |  :smiley: |  :smiley: |  :smiley: | :unamused: | :unamused:
Birth date (appox.)| 1972 | 1975 | 1990 | 2001 | 1951

This compilation as per August 19, 2020 is neither complete nor does it claim to be correct.

