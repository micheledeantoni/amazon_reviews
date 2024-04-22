# Amazon Review Helpfulness Prediction 📦

## Overview ℹ️
This repository contains the code and resources for predicting the helpfulness of Amazon reviews using machine learning techniques. The analysis aims to provide insights into the factors influencing review helpfulness and to build predictive models for identifying helpful reviews.

## Dataset 📊
The dataset used in this analysis is sourced from Amazon reviews Kaggle Dataset (https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) and includes features such as product ID, user ID, review score, review text, and helpfulness votes. The main target variable for prediction is the ratio of helpful votes to total votes.

## Methodology 🛠️
1. **Data Preprocessing:**
   - Text cleaning, tokenization, and feature engineering were performed to extract relevant features from the review text.
   - Features such as sentiment analysis, text length, and text complexity were derived from the review text to supplement numerical features.
   
2. **Model Training:**
   - Three machine learning algorithms were trained on the preprocessed data: Logistic Regression, Random Forest, and XGBoost.
   - Hyperparameter tuning was performed using Grid Search and Random Search to optimize model performance.
   
3. **Model Evaluation:**
   - The trained models were evaluated using accuracy scores, classification reports, and confusion matrices to assess their performance in predicting review helpfulness.
   - Cross-validation techniques were employed to estimate model performance on unseen data and ensure generalization.

## Results 📊
- The Random Forest model with tuned hyperparameters achieved the highest accuracy of XX%, outperforming both Logistic Regression and XGBoost models.
- Cross-validation results indicated robust performance of the Random Forest model, with a mean CV accuracy of XX%.
- Feature importance analysis revealed that text-related features, such as sentiment analysis and text complexity, played significant roles in predicting review helpfulness.

