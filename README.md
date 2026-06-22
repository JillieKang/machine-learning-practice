# machine-learning-practice

## Overview
This repository contains machine learning practices focused on developing analytical skills applicable to quantitative social science research. The repository is primarily based on *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems* by Aurélien Géron and documents the development of machine learning techniques, model evaluation methods, and computational approaches to data analysis.

The repository is organised into the following section:

**practices**: Exercises and methodological implementations based on textbook materials and tutorials

Jupyter Notebook (`.ipynb`) files are available in the `practices` folder.

The datasets used throughout the repository are synthetic datasets generated with the assistance of large language models (LLMs) based on examples and scenarios presented in the textbook. The repository focuses on methodological learning and implementation rather than substantive empirical analysis.


## Skills Developed

- Machine learning pipeline design
- Supervised learning for continuous value prediction
- Supervised learning for categorical classification
- Unsupervised learning for data clustering
- Feature selection and regularization
- Model evaluation and diagnostic metrics
- Data visualization

## Tools

- Python
- Jupyter Notebook

## Python Packages

- `pandas`
- `numpy`
- `matplotlib.pyplot`
- `sklearn.model_selection` (`train_test_split`)
- `sklearn.linear_model` (`LinearRegression`, `Ridge`, `Lasso`, `LogisticRegression`)
- `sklearn.metrics` (`mean_squared_error`, `r2_score`, `classification_report`, `confusion_matrix`, `accuracy_score`, `roc_curve`, `auc`, `silhouette_score`)
- `sklearn.cluster` (`KMeans`)
- `sklearn.decomposition` (`PCA`)
- `sklearn.tree` (`DecisionTreeClassifier`, `plot_tree`)
- `sklearn.ensemble` (`RandomForestClassifier`)

## Topics Covered

## 1. Machine Learning Based on Linear Regression

### Functions

- `train_test_split()`
- `LinearRegression()`
- `fit()`
- `predict()`
- `mean_squared_error()`
- `r2_score()`

### Key Operations

- Splitting dataset into training and testing sets
- Fitting Ordinary Least Squares (OLS) Linear Regression models
- Predicting continuous target variables
- Evaluating predictive models using Mean Squared Error (MSE) and R-squared ($R^2$) metrics
- Visualizing actual vs. predicted values with scatter plots

## 2. Regularization

### Functions

- `Ridge()`
- `Lasso()`
- `fit()`
- `predict()`
- `mean_squared_error()`
- `r2_score()`

### Key Operations

- Implementing Ridge Regression with L2 regularization to prevent overfitting
- Implementing Lasso Regression with L1 regularization for simultaneous regularization and feature selection
- Varying the regularization strength ($\alpha$/$\lambda$) to evaluate impact on model parameters
- Extracting and analyzing model coefficients from Lasso models to identify dropped features
- Evaluating and comparing MSE and $R^2$ metrics across different lambda settings

## 3. Logistic Regression

### Functions

- `train_test_split()`
- `LogisticRegression()`
- `fit()`
- `predict()`
- `predict_proba()`
- `accuracy_score()`
- `confusion_matrix()`
- `classification_report()`
- `roc_curve()`
- `auc()`

### Key Operations

- Splitting classification dataset into training and testing sets
- Fitting binary Logistic Regression models for decision prediction
- Generating class predictions and prediction probabilities
- Evaluating classification performance using prediction accuracy
- Computing confusion matrices to inspect true positives, true negatives, false positives, and false negatives
- Generating classification reports to inspect precision, recall, and F1-score per class
- Plotting Receiver Operating Characteristic (ROC) curves and calculating Area Under the Curve (AUC)

## 4. Decision Tree

### Functions

- `DecisionTreeClassifier()`
- `fit()`
- `predict()`
- `accuracy_score()`
- `confusion_matrix()`
- `classification_report()`
- `plot_tree()`
- `plt.figure()`
- `plt.show()`

### Key Operations

- Fitting non-linear Decision Tree Classification models
- Handling categorical and continuous features automatically for partition mapping
- Generating class predictions on evaluation test data
- Evaluating classification performance metrics against baseline models
- Visualizing decision trees graphically with split nodes, Gini criteria, and leaf samples

## 5. Random Forest

### Functions

- `RandomForestClassifier()`
- `fit()`
- `predict()`
- `accuracy_score()`
- `confusion_matrix()`
- `classification_report()`

### Key Operations

- Implementing ensemble learning via bagging with Random Forest classifiers
- Configuring model parameters such as the number of estimators for forest construction
- Training multiple decision trees on random subsets of data to reduce model variance
- Generating robust ensemble class predictions
- Evaluating performance gains compared to a single standalone decision tree

## 6. K-Means Clustering

### Functions

- `range()`
- `KMeans()`
- `fit()`
- `silhouette_score()`
- `zip()`
- `print()`

### Key Operations

- Implementing distance-based, centroid-based unsupervised clustering algorithms
- Iterating through a range of cluster numbers ($K$ values) to evaluate model quality
- Calculating inertia (distortion) values across $K$ values for the Elbow Method
- Computing Silhouette Scores to measure cluster separation and cohesion
- Printing and evaluating performance metrics to guide the choice of optimal $K$

## 7. Principal Component Analysis (PCA)

### Functions

- `KMeans()`
- `fit()`
- `PCA()`
- `fit_transform()`
- `plt.figure()`
- `plt.scatter()`
- `legend_elements()`

### Key Operations

- Fitting a final K-Means model based on the optimal number of clusters discovered
- Reducing multi-dimensional feature space down to two principal components using PCA
- Transforming high-dimensional data into PC1 and PC2 score spaces
- Appending PCA projection components and cluster assignments to the working DataFrame
- Visualizing multi-dimensional clusters in a 2D PCA scatter plot space with color-coded labels
