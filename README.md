# Rheumatoid Arthritis Flare Prediction – Model Comparison
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![XGBoost](https://img.shields.io/badge/Model-XGBoost-red)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-yellow)
![Status](https://img.shields.io/badge/Project-Research%20Study-green)

## Overview

This project explores the use of machine learning models to predict **Rheumatoid Arthritis (RA) flares** using a synthetic dataset representing simulated patient clinical features.

The objective of this study is to compare the performance of different machine learning algorithms and identify which model performs best for early RA flare prediction.

## Models Used

The following models were trained and evaluated:

* Logistic Regression
* Random Forest
* XGBoost

These models were selected to compare traditional statistical methods with more advanced ensemble learning techniques.

## Dataset

Since real clinical datasets are difficult to access due to privacy and ethical constraints, a **synthetic dataset** representing simulated RA patient clinical features was generated for experimentation and model comparison.

The dataset includes variables such as:

* Age
* Gender
* Disease duration
* Inflammation markers
* Clinical symptoms
* Other simulated patient health indicators

## Methodology

The project workflow includes:

1. Synthetic dataset generation for simulated RA patients
2. Data preprocessing and feature preparation
3. Training machine learning models
4. Evaluating model performance
5. Comparing results to identify the best performing model

## Results

The performance of the models was evaluated using common classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-score

Among the tested models, **XGBoost showed the best performance** in predicting potential RA flares on the synthetic dataset.

## Tools and Technologies

* Python
* Google Colab
* Scikit-learn
* XGBoost
* Pandas
* NumPy

## Repository Structure

```
RA-Flare-Prediction
│
├── RA_model_comparison.ipynb
├── README.md
└── results/
```

## Purpose

This repository was created as part of an experimental study to explore **machine learning approaches for early prediction of rheumatoid arthritis flares** and to understand model performance on simulated healthcare data.

## Author

Rashmi Rathnayake
Final Year Software Engineering Student
General Sir John Kotelawala Defence University
