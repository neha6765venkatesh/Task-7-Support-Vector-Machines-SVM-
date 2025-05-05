Breast Cancer Classification Using SVM
This project demonstrates how to use Support Vector Machines (SVM) to classify breast cancer tumors as Malignant (M) or Benign (B) based on medical features extracted from digitized images of a breast mass.

Features
Loads and preprocesses a real-world dataset (breast-cancer.csv)

Encodes the target variable (diagnosis)

Standardizes input features

Reduces feature dimensions using PCA (for visualization)

Trains SVM classifiers with:

Linear kernel

RBF (Radial Basis Function) kernel

Visualizes decision boundaries in 2D

Tunes hyperparameters (C and gamma) using GridSearchCV

Evaluates model performance using cross-validation

Requirements
Python 3.x

Libraries:

pandas

numpy

scikit-learn

matplotlib
