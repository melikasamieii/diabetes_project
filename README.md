# Diabetes Data Imputation and Model Evaluation

## Overview
This project analyzes the impact of different data imputation strategies on machine learning model performance.
Using the Diabetes dataset, multiple imputation approaches are applied and evaluated through classification models and confusion matrices.

The main goal is to demonstrate how data quality and preprocessing decisions directly affect model outcomes.

## Files in Repository
- `diabetes_imputation_model_evaluation.ipynb`

## Features
- Load and inspect the Diabetes dataset
- Detect missing or invalid values
- Apply multiple data imputation strategies
- Train classification models using SVM with multiple kernels
- Evaluate each strategy using confusion matrices
- Compare model performance across different data-cleaning approaches

## Methodology
1. Identify missing or invalid feature values
2. Apply multiple imputation strategies (A, B, C)
3. Prepare features for modeling (encoding and scaling if required)
4. Train SVM classifiers with different kernels
5. Evaluate results using confusion matrices
6. Compare outcomes to assess the impact of data quality on model performance

## Requirements
- Python 3.9+
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn
- jupyter (or VS Code Jupyter extension)

## Setup (Windows 11)
```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
How to Run
Open diabetes_imputation_model_evaluation.ipynb in Jupyter Notebook or VS Code.
Run all cells from top to bottom.
Compare confusion matrices across different imputation strategies.
Notes / Limitations
The dataset is relatively small compared to real-world medical or banking datasets.
The focus is on understanding the impact of data quality rather than achieving maximum predictive performance.
The methodology can be directly generalized to financial, insurance, and fraud detection datasets.
