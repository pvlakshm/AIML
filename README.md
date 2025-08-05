## ML Primer
- Gently introduces the various ML models, what they learn, and what they can predict.
- Uses simple datasets that the reader can easily build an intuition around.

| **Model**                                                  | **What It Learns from the Dataset**                                                | **What It Can Predict**                                               |
|------------------------------------------------------------|------------------------------------------------------------------------------------|-----------------------------------------------------------------------|
| [Linear Regression](Learn-a-line.ipynb)                    | A single feature weight (slope) and an intercept that best fit the data points.    | A **continuous numeric value**.                                       |
| [Multivariate Linear Regression](Learn-a-formula.ipynb)    | Multiple feature weights (one per feature) and an intercept.                       | A **continuous numeric value**.                                       |
| [Logistic Regression](LogisticRegression.ipynb) Classifier | Feature weights that map inputs to probabilities using the **sigmoid function**.   | A **probability** of class membership, leading to **classification**. |
| [Decision Tree](DecisionTree.ipynb) Classifier             | A set of **if-then rules** based on feature splits that recursively partition data | A **class label** to which the data belongs.                          |
| [K-NearestNeighbors](KNN.ipynb) Classifier                 | Memorizes the dataset. Does not "learn" anything in the traditional sense.         | A **class label** to which the data belongs.                          |
