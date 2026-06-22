# machine-learning-practice

## Overview

This repository contains machine learning practices and methodological exercises implemented in Python using scikit-learn. It documents the development of foundational machine learning skills, including supervised learning, unsupervised learning, predictive modelling, classification, clustering, model evaluation, and data preprocessing.

The repository focuses on core machine learning algorithms commonly used in data science and computational social science research. Through hands-on exercises, it demonstrates the complete machine learning workflow from data preparation and train-test splitting to model fitting, prediction, evaluation, and interpretation.

The repository is organised into the following section:

- **practice**: Exercises and methodological implementations of machine learning algorithms and evaluation techniques

Jupyter Notebook files are available in the `practice` folder.

---

## Skills Developed

- Supervised machine learning
- Unsupervised machine learning
- Regression analysis
- Classification analysis
- Clustering analysis
- Predictive modelling
- Data preprocessing
- Feature selection
- Train-test splitting
- Stratified sampling
- Model fitting and prediction
- Model evaluation
- Data visualisation

---

## Tools

- Python
- Jupyter Notebook
- scikit-learn

---

## Python Libraries

### Data Manipulation

- pandas
- numpy

### Data Visualisation

- matplotlib

### Machine Learning

- scikit-learn

---

## Practices: Topics Covered

### 1. Supervised Machine Learning for Prediction

#### Algorithm

- Linear Regression

#### Dataset

- Narcissism and Facebook Usage Dataset

#### Functions

- `train_test_split()`
- `LinearRegression()`
- `fit()`
- `predict()`
- `mean_squared_error()`
- `r2_score()`

#### Key Operations

- Importing and managing structured tabular data
- Defining feature and target variables
- Splitting data into training and test sets
- Training linear regression models
- Generating predictions on unseen data
- Evaluating predictive performance using Mean Squared Error (MSE)
- Evaluating explanatory power using R-squared (R²)
- Interpreting relationships between behavioural and demographic variables

#### Concepts Covered

- Supervised learning
- Prediction
- Regression modelling
- Continuous outcome variables
- Model evaluation

---

### 2. Supervised Machine Learning for Classification

#### Algorithm

- Logistic Regression

#### Dataset

- Admission Decision Dataset

#### Functions

- `train_test_split()`
- `LogisticRegression()`
- `fit()`
- `predict()`
- `classification_report()`
- `confusion_matrix()`
- `accuracy_score()`
- `roc_curve()`
- `auc()`

#### Key Operations

- Preparing binary classification datasets
- Defining predictors and outcome variables
- Performing stratified train-test splitting
- Training logistic regression models
- Predicting class membership
- Evaluating classification accuracy
- Constructing confusion matrices
- Calculating precision, recall, and F1 scores
- Generating ROC curves
- Calculating Area Under the Curve (AUC)

#### Concepts Covered

- Binary classification
- Logistic regression
- Classification performance metrics
- Sensitivity and specificity
- ROC analysis
- Model validation

---

### 3. Unsupervised Machine Learning for Clustering

#### Algorithm

- K-Means Clustering

#### Functions

- `KMeans()`
- `silhouette_score()`

#### Key Operations

- Preparing multivariate datasets
- Applying K-Means clustering
- Determining the optimal number of clusters
- Implementing the Elbow Method
- Calculating Silhouette Scores
- Comparing clustering solutions across different values of K
- Assigning observations to clusters
- Evaluating clustering quality

#### Concepts Covered

- Unsupervised learning
- Cluster analysis
- Pattern discovery
- Cluster validation
- Similarity and group structure

---

## Machine Learning Workflow

### Data Preparation

- Importing datasets
- Selecting predictor and outcome variables
- Preparing feature matrices
- Handling structured tabular data

### Model Training

- Train-test splitting
- Stratified sampling
- Model fitting
- Prediction generation

### Model Evaluation

#### Regression

- Mean Squared Error (MSE)
- R-squared (R²)

#### Classification

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve
- Area Under the Curve (AUC)

#### Clustering

- Elbow Method
- Silhouette Score

---

## Skills Developed

This repository was developed to build a practical understanding of the core machine learning paradigms:

- Predicting continuous outcomes using regression models
- Classifying categorical outcomes using supervised learning algorithms
- Discovering hidden group structures using unsupervised learning techniques
- Evaluating model performance using appropriate statistical metrics
- Implementing reproducible machine learning workflows in Python
