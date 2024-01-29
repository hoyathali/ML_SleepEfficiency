
### 1.  Sleep Efficiency Prediction Project

- **Description:** This project focuses on predicting sleep efficiency using machine learning. Sleep efficiency is a critical metric for understanding the quality of sleep, and the goal of this project is to develop a model that can accurately predict sleep efficiency based on various demographic and lifestyle factors.
  
# Sleep Efficiency Prediction

## Overview

This project utilizes machine learning to predict sleep efficiency based on a comprehensive dataset encompassing various sleep-related parameters and lifestyle choices. The goal is to offer personalized insights into sleep patterns and contribute to the field of sleep science.

## Key Steps

### Data Exploration and Cleaning

- Explored and cleaned a diverse dataset containing sleep patterns, lifestyle choices, and demographic information.
- Applied one-hot encoding to non-numeric columns like gender and smoking status.

### Feature Engineering

- Extracted the hour component from date-time columns to simplify the analysis.
- Performed one-hot encoding for gender and smoking status.

### Outlier Handling

- Identified and handled outliers using the Interquartile Range (IQR) method.
- Visualized outliers through box plots for various features.

### Model Selection and Training

- Utilized Random Forest, LightGBM, AdaBoosted LightGBM, and Linear Regression for model comparison.
- Selected Random Forest as the best-performing model based on Mean Squared Error.

### Hyperparameter Tuning

- Fine-tuned Random Forest hyperparameters using GridSearchCV.

### Normalizing Data

- Employed Min-Max scaling to normalize the dataset.

### Evaluation and Validation

- Evaluated model performance using Mean Squared Error.
- Validated predictions through violin plots comparing actual vs. predicted values.

### Feature Importance

- Visualized feature importance using bar plots.

## Usage

- Execuate the Forecasting_Sleep_Efficiency_Random_Forest.pynb file sequentially

## Dependencies

- Python 3.x
- Jupyter Notebooks
- Libraries: pandas, matplotlib, seaborn, scikit-learn, lightgbm

## Author

Hoyath Ali

## Acknowledgments

- Dataset source: Kaggle

Feel free to reach out for any questions or feedback!


