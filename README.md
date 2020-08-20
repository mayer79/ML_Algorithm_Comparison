# Features of Major ML Algorithms

Compares properties of some of the most important classes of supervised ML algorithms applicable to both regression and classification problems. We are not thinking about a specific implementation but rather about the "typical" implementation.

- **GLM**: Generalized linear model (e.g. logistic regression) with optional L1/L2 penalties
- **Neural Net**: Artificial neural net fitted by backprop
- **Gradient boosting**: Boosted trees (AdaBoost, XGBoost, LightGBM, CatBoost,...)
- **Random Forest**
- **k-Nearest Neighbour**

Aspect         | GLM       | Neural Net      | Gradient Boosting | Random Forest  | k-Nearest Neighbour
:------------ | :-------------| :-------------| :------------- | :------------- | :-------------
Scalable  | :heart_eyes:  | :heart_eyes: | :smiley: | :neutral_face: |  :unamused:
Easy to tune  | :neutral_face:  | :neutral_face: | :neutral_face: | :smiley: |  :neutral_face:
Flexible losses |:smiley: | :heart_eyes: | :smiley: | :neutral_face: | :neutral_face:
Regularization | :heavy_check_mark:| :heavy_check_mark:| :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Case weights | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Missing input allowed | :unamused: | :unamused: | :heavy_check_mark: | :unamused: | :unamused:
Interpretation | :heart_eyes: | :neutral_face: | :neutral_face: | :neutral_face: | :neutral_face:
Space on disk |  :heart_eyes: |  :heart_eyes: |  :smiley: | :unamused: | :unamused:
Birth date (appox.)| 1972 (Nelder & Wedderburn) | 1975 Backprop (Werbos) | 1990 (Schapire) | 2001 (Breiman) | 1951 (Fix & Hodges)

This compilation as per August 20, 2020 is neither complete nor does it claim to be correct.

