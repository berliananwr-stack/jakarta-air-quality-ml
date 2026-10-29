# Jakarta Air Quality Analysis Using Machine Learning

## Overview

This project explores air quality data in Jakarta using data analysis and machine learning techniques. It focuses on analyzing air pollution patterns, estimating missing PM2.5 values, and examining air quality categories.

This project was developed as part of a university Machine Learning / Data Science assignment.

## Objectives

- Explore and understand Jakarta's air quality data.
- Identify and estimate missing PM2.5 measurements.
- Compare different regression models for PM2.5 estimation.
- Analyze air quality categories based on the ISPU classification implemented in the notebook.

## Machine Learning Models

The project uses the following regression models:

- **Extra Trees Regressor** — an ensemble model based on randomized decision trees.
- **ElasticNet Regression** — a linear regression model combining L1 and L2 regularization.
- **Support Vector Regression (SVR)** — a regression model that uses support vector techniques.

The models are used to estimate missing PM2.5 values.

## Dataset

The notebook uses a Jakarta air quality dataset.

**Expected filename:** `ispu_dki1.csv`

**Dataset source:** Add the original dataset URL here.

Please ensure that the dataset is properly attributed and that its license permits the intended use.

## Tools and Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Repository Structure

```text
jakarta-air-quality-ml/
├── README.md
├── DSA_Code_Final_Project.ipynb
└── ispu_dki1.csv
```

The CSV file is optional in the repository if the dataset is obtained separately. Make sure the notebook can access the dataset before running it.

## How to Run

1. Open `DSA_Code_Final_Project.ipynb` in Google Colab.
2. Upload `ispu_dki1.csv` or update the notebook's dataset path.
3. Run the notebook cells in order.
4. Review the analysis, model evaluation results, PM2.5 estimates, and air quality categories.

## Limitations

- Estimated PM2.5 values are predictions, not actual measurements.
- Model performance depends on data quality and the evaluation method.
- Air quality categories depend on the ISPU calculation implemented in the notebook.
- Results should be validated before being used for real-world decisions.

## Academic Project

This repository contains the notebook and supporting materials for an academic project on Jakarta air quality using machine learning.
