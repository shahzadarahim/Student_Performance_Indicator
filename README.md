# Student Performance Indicator - An End to End Machine Learning Project

This project aims to understand how various factors, such as gender, ethnicity, parental education, lunch type, and test preparation courses, impact students' performance (test scores) in math, reading, and writing. The model can help educators and policymakers analyze patterns in student performance and identify areas for improvement.

## Table of Contents
1. [Problem Statement](#problem-statement)
2. [Project Overview](#project-overview)
3. [Data Collection](#data-collection)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Data Preprocessing](#data-preprocessing)
6. [Model Training and Evaluation](#model-training-and-evaluation)
7. [Choosing the Best Model](#choosing-the-best-model)
8. [Technologies Used](#technologies-used)
9. [Results](#results)
10. [Future Enhancements](#future-enhancements)

## Problem Statement

This project investigates how student test scores are influenced by other factors, such as:
- Gender
- Ethnicity
- Parental level of education
- Lunch type (standard/reduced)
- Completion of test preparation courses

## Project Overview

This project follows the typical lifecycle of a machine learning project, covering:
1. Problem understanding
2. Data collection and checks
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Model training and evaluation
6. Model selection

The goal is to build a predictive model that estimates student test scores based on these various factors.

## Data Collection

The dataset is collected with features such as:
- Gender
- Ethnicity
- Parental level of education
- Lunch type
- Test preparation course completion status
- Math score
- Reading score
- Writing score

## Exploratory Data Analysis (EDA)

EDA helps to identify patterns, relationships, and trends in the data. This step includes:
- Visualizing score distributions and other features using **Seaborn** and **Matplotlib**
- Identifying relationships between target variables and other factors

## Data Preprocessing

This step covers:
- Handling missing values
- Encoding categorical variables
- Normalizing/standardizing numerical features

## Model Training and Evaluation

Models used include:
- **Neighbors**
- **Tree**
- **Ensemble**
- **Linear_model**
- **CatBoost**
- **XGBoost**

Each model is evaluated using **metrics** to identify the best-performing one for this dataset.

## Choosing the Best Model

Based on the evaluation metrics, the model with the highest accuracy and performance consistency is chosen for deployment.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`, `catboost`, `xgboost`, `neighbors`, `tree`, `ensemble`, `linear_model`, `dill`, `Flask`
- **Environment**: Jupyter Notebook, Flask (for deployment)

## Results

The project highlights significant correlations between test scores and specific factors, with the model achieving an **88% accuracy level**.

## Future Enhancements

- Additional data collection to improve model robustness
- Adding more demographic and socioeconomic factors
- Experimenting with advanced model tuning

---