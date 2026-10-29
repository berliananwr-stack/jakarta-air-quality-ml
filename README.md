# Jakarta Air Quality Analysis Using Machine Learning

## Overview

This repository contains the computational materials for a research project investigating Jakarta air quality using machine learning techniques. The study focuses on the estimation of missing PM2.5 observations and the analysis of air quality categories using the available dataset.

The repository is intended to serve as supplementary research material and to support the reproducibility of the computational analysis associated with the ongoing conference paper preparation.

## Research Objectives

The objectives of this study are to:

- Explore and characterize the available Jakarta air quality data.
- Identify missing PM2.5 observations and estimate missing values using machine learning models.
- Examine model performance using the evaluation procedures implemented in the notebook.
- Analyze air quality categories based on the ISPU calculation implemented in the analysis.

## Methodology

The computational workflow is implemented in Python and includes data preprocessing, exploratory data analysis, regression modeling, and air quality category analysis.

Three regression models are included in the notebook:

- **Extra Trees Regressor:** An ensemble learning method based on randomized decision trees.
- **ElasticNet Regression:** A linear regression method combining L1 and L2 regularization.
- **Support Vector Regression (SVR):** A regression method based on support vector learning.

These models are used for PM2.5 estimation. Their comparative performance should be interpreted in accordance with the evaluation metrics, data split, and experimental procedures documented in the notebook.

## Repository Contents

| File | Description |
|---|---|
| `DSA_Code_Final_Project.ipynb` | Notebook containing data processing, analysis, and machine learning experiments |
| `ispu_dki1.csv` | Dataset used by the notebook |
| `README.md` | Project overview and instructions for reproducing the analysis |

## Dataset

The analysis uses the Jakarta air quality dataset provided in `ispu_dki1.csv`.

- **Dataset file:** [`ispu_dki1.csv`](ispu_dki1.csv)
- **Original source:** To be specified using the original dataset URL or official citation.
- **Usage and attribution:** Please consult the original source and applicable license for data attribution and redistribution requirements.

## Computational Environment

The analysis uses Python and the following libraries:

- Pandas
- NumPy
- Matplotlib
- Scikit-learn

The notebook is designed to run in Google Colab or a compatible Jupyter Notebook environment.

## Reproducibility Instructions

### Using Google Colab

1. Open [`DSA_Code_Final_Project.ipynb`](https://colab.research.google.com/github/USERNAME/jakarta-air-quality-ml/blob/main/DSA_Code_Final_Project.ipynb) in Google Colab.
2. Replace `USERNAME` in the URL with the GitHub account username that owns this repository.
3. Ensure that `ispu_dki1.csv` is available in the Colab session.
4. If necessary, upload the dataset through the Colab file panel or update the notebook's dataset path.
5. Install any missing dependencies.
6. Execute the notebook cells in order.
7. Review the resulting analyses, model evaluations, PM2.5 estimates, and air quality category distributions.

### Using a Local Environment

1. Download or clone this repository.
2. Install Python and the required dependencies.
3. Place `ispu_dki1.csv` in the directory expected by the notebook.
4. Open `DSA_Code_Final_Project.ipynb` using Jupyter Notebook or JupyterLab.
5. Execute the notebook cells in order.

The main dependencies can be installed using:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

For reproducibility, the Python version, library versions, data preprocessing procedures, model parameters, and evaluation settings should be documented alongside the final research results.

## Limitations and Interpretation

- Estimated PM2.5 values are model-generated estimates and should not be interpreted as direct measurements.
- Model performance depends on the available data, feature selection, preprocessing, and evaluation methodology.
- Air quality classifications depend on the calculation implemented in the notebook and should be checked against the applicable ISPU guidelines.
- The validity and generalizability of the findings require appropriate evaluation and validation.
- The computational results should be interpreted in conjunction with the study's final methodology and research discussion.

## Research Status

The associated conference manuscript is currently under preparation. The repository provides supporting computational materials for the ongoing research and does not imply conference acceptance or publication.

## Citation

A formal citation will be added when the associated manuscript and its bibliographic information are finalized.

## Contact

For questions about the code or research materials, please contact the repository maintainer through the contact information provided in the associated research materials.
