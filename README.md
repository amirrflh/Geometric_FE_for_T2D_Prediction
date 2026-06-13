# Geo+ML: Geometric Feature Engineering for Type 2 Diabetes Prediction

## Overview

This repository provides the implementation of the Geo+ML framework developed for Type 2 Diabetes prediction from clinical data. The framework introduces a set of geometric feature engineering techniques that transform conventional clinical measurements into geometric representations, enabling machine learning models to capture additional structural relationships within the data.

The proposed approach combines traditional clinical attributes with engineered geometric features and evaluates their effectiveness across multiple machine learning algorithms. The repository contains all code required to reproduce the experiments, model training procedures, evaluation metrics, and explainability analyses presented in the study.

## Dataset

Experiments were conducted using the publicly available Pima Indians Diabetes Dataset, a widely used benchmark dataset for diabetes prediction research.

The dataset contains diagnostic measurements collected from female patients and includes features such as glucose concentration, blood pressure, body mass index (BMI), insulin level, age, and diabetes pedigree function.

## Repository Contents

```text
Geo.ipynb                 # Main notebook containing the complete workflow
README.md                 # Project documentation
```

## Methodology

The workflow implemented in this repository includes:

1. Data preprocessing and quality assessment.
2. Generation of geometric features from clinical variables.
3. Feature integration and dataset preparation.
4. Training and evaluation of machine learning models.
5. Comparative performance analysis.
6. Model interpretation using SHAP explainability techniques.

## Machine Learning Models

The framework supports several machine learning algorithms, including:

* Support Vector Machine (SVM)
* Random Forest (RF)
* Gradient Boosting (GB)
* XGBoost
* LightGBM
* Additional baseline classifiers

## Usage

Open and execute the notebook:

```bash
jupyter notebook Geo.ipynb
```

The notebook contains the complete experimental pipeline, from data preprocessing and feature engineering to model evaluation and explainability analysis.

## Results

The experimental results demonstrate that incorporating geometric feature engineering can improve predictive performance for Type 2 Diabetes classification. The engineered geometric descriptors provide complementary information to traditional clinical variables and contribute to improved model discrimination and interpretability.

## Reproducibility

All experiments reported in the study can be reproduced using the code provided in this repository. Random seeds and model configurations are included within the notebook to facilitate consistent evaluation.

## License

This repository is intended for academic and research purposes.
