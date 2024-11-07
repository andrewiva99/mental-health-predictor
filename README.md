# Depression Prediction Project

This project, built entirely with **PySpark**, focuses on predicting depression in individuals based on various features such as age, job or study satisfaction, workload, academic performance, and more. The best model achieves an accuracy of 94%.


## Project Overview
The goal of this project is to predict the likelihood of depression using machine learning models trained on a large dataset with over 140,000 records and 20 features. The dataset was sourced from a Kaggle competition and contains both training and testing data:

- **Dataset link**: [Kaggle - Playground Series S4E11](https://www.kaggle.com/competitions/playground-series-s4e11/data)

## Approach
1. **Data Analysis & Preprocessing**:
   - Conducted exploratory data analysis (EDA).
   - Applied data cleaning, missing value imputation, and feature selection.
   
2. **Modeling**:
   - Trained multiple models including Random Forest and Gradient Boosting Tree.
   - The Gradient Boosting Tree model achieved the best performance with 94% accuracy on the training set.

## Notebook
All analysis and modeling work is documented in `mh_class.ipynb`.

## Dataset Notes
- The dataset was synthetically generated based on a depression survey dataset.
- Contains artifacts and slight distribution differences from the original dataset, making it useful for model evaluation and visualization techniques.

## Files
- **train.csv** - Training dataset with a binary target for depression prediction.
- **test.csv** - Testing dataset used to evaluate model performance.
- **test_prediction.csv** - Model predictions on the test dataset.
