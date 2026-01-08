📊 Iris Species Classification
Overview
-This project is a machine learning classification task using the classic Iris dataset. The goal is to predict the species of an iris flower (setosa, versicolor, virginica) based on sepal and petal measurements.

The project follows a full ML workflow and demonstrates internship-level practices, including:
-Exploratory Data Analysis (EDA)
-Data preprocessing (handling duplicates, missing values, label encoding, scaling)
-Feature analysis (correlation, feature importance)
-Model training with Logistic Regression and Random Forest
-Hyperparameter tuning using RandomizedSearchCV
-Model evaluation using accuracy, F1-score, ROC-AUC, precision-recall curves, and confusion matrices
-Saving the trained model for deployment

Dataset
-Source: UCI Iris Dataset
Features:
-Sepal Length (cm)
-Sepal Width (cm)
-Petal Length (cm)
-Petal Width (cm)
Target: species (setosa, versicolor, virginica)

Libraries Used:
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib


Project Workflow
1.Exploratory Data Analysis (EDA)
-Summary statistics, data info, null values, duplicate removal
-Visualizations: pairplots, heatmaps, target distribution
2.Preprocessing
-Label encoding for categorical target
-Train-test split (80-20)
-Feature scaling using StandardScaler
3.Model Training & Hyperparameter Tuning
-Logistic Regression: tuned penalty, C, solver
-Random Forest: tuned n_estimators, max_depth, min_samples_split/leaf, max_features, criterion
-Hyperparameter tuning via RandomizedSearchCV
4.Model Evaluation
-Metrics: accuracy, F1-score (weighted), ROC-AUC, classification report
-Visualizations: confusion matrix, ROC-AUC curve, precision-recall curve
-Comparison of Logistic Regression vs Random Forest
5.Feature Importance
-Random Forest feature importances visualized to identify most predictive features
6.Model Saving
Best-trained models saved using joblib for deployment
