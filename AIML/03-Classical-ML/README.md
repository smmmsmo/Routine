# Classical Machine Learning

## Foundations

- Problem framing, target definition, baselines, train/validation/test design
- Data leakage, distribution shift, class imbalance, and reproducibility
- Feature types, missing values, encoding, scaling, transformations, and feature selection
- Bias-variance trade-off, underfitting, overfitting, regularization, and learning curves

## Supervised Learning

- Linear, polynomial, Ridge, Lasso, and Elastic Net regression
- Logistic regression and probabilistic classification
- k-nearest neighbors
- Naive Bayes
- Decision trees and pruning
- Bagging and random forests
- Gradient boosting; XGBoost, LightGBM, and CatBoost concepts
- Support vector machines and kernel methods

## Unsupervised Learning

- k-means and cluster validation
- Hierarchical clustering
- DBSCAN and density-based ideas
- Gaussian mixture models and expectation-maximization intuition
- PCA, t-SNE, and UMAP concepts and limitations
- Anomaly detection

## Evaluation

- Regression: MAE, MSE, RMSE, RMSLE, R², residual analysis
- Classification: accuracy, precision, recall, F1, specificity, ROC-AUC, PR-AUC, log loss
- Threshold selection, calibration, cost-sensitive evaluation, and confusion matrices
- Cross-validation strategies for IID, grouped, temporal, and imbalanced data
- Interpretability: coefficients, permutation importance, partial dependence, SHAP concepts
- Fairness, subgroup evaluation, robustness, and uncertainty

## Required Implementations

- Linear regression using closed form and gradient descent
- Logistic regression from scratch
- k-nearest neighbors
- Decision tree split calculation
- k-means and PCA

## Projects

- House-price prediction with error analysis
- Churn or credit-risk classification
- Customer segmentation
- Recommendation baseline
- Kaggle-style tabular competition with an experiment report

## Mastery Checklist

- [ ] I can select an appropriate validation strategy.
- [ ] I can identify leakage and misleading metrics.
- [ ] I can compare linear, tree-based, and kernel methods.
- [ ] I understand bagging versus boosting.
- [ ] I can tune models without contaminating the test set.
- [ ] I can communicate uncertainty, limitations, and subgroup performance.
