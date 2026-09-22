# Heavy Equipment Resale Price Prediction — IIT Madras BS MLP Project

## Project Overview
Built an end-to-end machine learning pipeline to predict resale prices of heavy 
industrial machinery and equipment using operational, transactional, and technical 
data, as part of the IIT Madras BS Data Science Machine Learning Practice course. 
Achieved an A grade.

## Dataset & Competition
- **Source:** [Kaggle — Heavy Equipment Selling Price Prediction Challenge]
- **Task:** Regression
- **Evaluation Metric:** RMSLE (Root Mean Squared Log Error)

## Project Workflow
1. **Exploratory Data Analysis (EDA):** Explored numerical, categorical, and 
   high-cardinality technical string features across equipment transaction records.
2. **Feature Engineering:** Encoded categorical and technical specification features, 
   handled missing values and geographic/operational metadata.
3. **Model Exploration:** Tested LightGBM, XGBoost, and Random Forest regressors.
4. **Hyperparameter Tuning:** Tuned each model to minimize RMSLE.
5. **Model Selection:** Compared models by validation RMSLE and selected the 
   best-performing pipeline for final submission.

## Results & Achievements
- **Final Model:** [fill in whichever model you actually used — LightGBM/XGBoost/RF]
- **Grade:** A
- **Leaderboard Rank:** 771 out of 2500 , with a final RMSLE score of 0.19438
