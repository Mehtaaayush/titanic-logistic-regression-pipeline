# Titanic Logistic Regression Pipeline

A complete machine learning pipeline to predict Titanic passenger survival using Python. Implements data preprocessing, model building, evaluation, and persistence using industry-standard practices.

## Overview

This project uses the Titanic dataset to create an end-to-end predictive model with logistic regression. All steps from data cleaning and feature engineering to model evaluation and cross-validation are performed within a reproducible pipeline.

## Features

- Numeric and categorical data preprocessing
- Missing value imputation (median for numeric, most frequent for categorical)
- One-hot encoding of categorical variables
- Logistic regression classification
- Evaluation with classification report, confusion matrix, and ROC-AUC
- 5-fold cross-validation for robust performance
- Pipeline export/import with `joblib`
- Jupyter Notebook with full documentation

## Dataset

- [Kaggle Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
- The main file used is `train.csv`, included in this repository (or instructions for use below).

## Project Structure

├── train.csv
├── sample.ipynb
├── model.joblib
├── README.md
└── LICENSE

## Usage

1. Clone the repository:
    ```
    git clone https://github.com/yourusername/titanic-logistic-regression-pipeline.git
    cd titanic-logistic-regression-pipeline
    ```
2. Install requirements:
    ```
    pip install pandas numpy scikit-learn matplotlib joblib
    ```
3. Open `sample.ipynb` in Jupyter Notebook or JupyterLab.
4. Run all cells to reproduce results and view evaluation metrics/plots.

## Results

- ROC-AUC (test): ~0.84  
- Key features: Sex, Fare, Pclass  
- Model accuracy, precision, recall, F1-score provided in the notebook

## Next Steps

- Experiment with additional features and more advanced models
- Tune model hyperparameters
- Improve feature engineering and selection

## License

This project is released under the MIT License. See [`LICENSE`](LICENSE) for details.

---

*Author: Aayush Mehta*  
*Internship Project – Maincrafts Technology, Data Science with Python*

