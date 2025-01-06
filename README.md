# Wine-Quality-Prediction
README

Overview

This project analyzes wine quality using two machine learning models: Random Forest and Decision Tree. The dataset used is the "Wine Quality Dataset," which contains various physicochemical properties of red wine samples and their quality scores. The project demonstrates how to train, test, and evaluate these models on this dataset.

Dataset

Source: UCI Machine Learning Repository - Wine Quality Dataset

Features:

fixed acidity

volatile acidity

citric acid

residual sugar

chlorides

free sulfur dioxide

total sulfur dioxide

density

pH

sulphates

alcohol

quality (Target variable: Integer score representing wine quality)

Missing Values:

No missing values were found in the dataset.

Dependencies

Python 3.10+

Libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

Install dependencies using:

pip install pandas numpy matplotlib seaborn scikit-learn

Code Description

Data Preprocessing

Data Loading:

The dataset is loaded from the UCI Machine Learning Repository.

The separator used is ;.

Missing Values Check:

Confirmed that there are no missing values in the dataset.

Feature Matrix and Target Vector:

The quality column is used as the target variable (y).

All other columns are used as features (X).

Train-Test Split:

Data is split into 80% training and 20% testing subsets.

Feature Scaling:

Performed optional standard scaling, though Random Forest and Decision Tree models do not require it.

Models Used

Random Forest Classifier:

Ensemble method with 100 estimators.

Decision Tree Classifier:

Single tree model.

Evaluation

The models are evaluated using:

Accuracy: The proportion of correct predictions.

Precision (weighted): The ratio of correctly predicted positive observations to the total predicted positives.

Recall (weighted): The ratio of correctly predicted positive observations to all observations in the actual class.

Confusion Matrix: A visualization of prediction performance.

Results

Random Forest:

Accuracy: 65.94%

Precision: 63.09%

Recall: 65.94%

Decision Tree:

Accuracy: 56.25%

Precision: 55.33%

Recall: 56.25%

Visualizations

Confusion matrices for both models are displayed using Seaborn heatmaps.

How to Run

Clone the repository or copy the code into a Python IDE or notebook.

Install the required libraries.

Run the script to load the dataset, preprocess it, and evaluate the models.

Limitations

Class Imbalance: Precision warnings indicate potential issues with class imbalance in the dataset.

Performance: Basic models are used; tuning hyperparameters or trying other algorithms might improve results.

Future Work

Explore techniques to handle class imbalance, such as oversampling or undersampling.

Experiment with hyperparameter tuning using GridSearchCV or RandomizedSearchCV.

Test other models such as Gradient Boosting or Neural Networks.

Implement cross-validation to ensure robust evaluation.

Acknowledgments

UCI Machine Learning Repository for providing the dataset.

scikit-learn for the machine learning tools used.

Author

Name: Aabid Mohamed

Email: aabidmohamed2003@gmail.com
