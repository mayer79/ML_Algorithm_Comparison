# Features of Major ML Algorithms

Compares properties of some of the most important classes of supervised ML algorithms applicable to both regression and classification problems. We are not thinking about a specific implementation but rather about the "typical" implementation.

- **GLM**: Generalized linear model (e.g. logistic regression and the normal linear model) with optional L1/L2 penalties.
- **Neural Net**: Artificial neural net fitted by the backpropagation algorithm.
- **Decision Trees**: Recursive binary partitioning. Often called CART ("classification and regression trees").
- **Boosting**: A combination of sequentially fitted weak learners, usually shallow decision trees. Each learner tries to correct the "errors" from the previous ones. Well-known implementations are AdaBoost, XGBoost, LightGBM, and CatBoost.
- **Random Forest**: A combination of deep randomized decision trees fitted in parallel. There are two sources of randomness: (1) In each split, only a small subset of features are considered at random. (2) Each tree is fitted on a bootstrap sample.
- **k-Nearest Neighbour**

Aspect                | GLM                        | Neural Net             | Decision Tree      | Boosting           | Random Forest      | k-Nearest Neighbour
:------------         | :-------------             | :-------------         | :-------------     | :-------------     | :-------------     | :-------------
Scalable              | :heart_eyes:               | :heart_eyes:           | :smiley:           | :smiley:           | :neutral_face:     | :unamused:
Easy to tune          | :neutral_face:             | :neutral_face:         | :neutral_face:     | :neutral_face:     | :smiley:           | :neutral_face:
Flexible losses       | :smiley:                   | :heart_eyes:           | :smiley:           | :smiley:           | :neutral_face:     | :neutral_face:
Regularization        | :heavy_check_mark:         | :heavy_check_mark:     | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Case weights          | :heavy_check_mark:         | :heavy_check_mark:     | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Missing input allowed | :unamused:                 | :unamused:             | :heavy_check_mark: | :heavy_check_mark: | :unamused:         | :unamused:
Interpretation        | :heart_eyes:               | :neutral_face:         | :heart_eyes:       | :neutral_face:     | :neutral_face:     | :neutral_face:
Space on disk         | :heart_eyes:               | :heart_eyes:           | :heart_eyes:       | :smiley:           | :unamused:         | :unamused:
Birth date (approx.)  | 1972 (Nelder & Wedderburn) | 1974 Backprop (Werbos) | 1984 (Breiman et al.)    | 1990 (Schapire)    | 2001 (Breiman)     | 1951 (Fix & Hodges)

This compilation as per September 7, 2020 is neither complete nor does it claim to be correct.

