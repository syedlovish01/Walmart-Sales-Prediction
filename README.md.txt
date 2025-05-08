🛒 Walmart Sales Prediction

📌 Objective
Predict Walmart's weekly sales using historical data and evaluate multiple machine learning models for accuracy.

🧰 Tools & Libraries
1. Python
2. Pandas, NumPy, Matplotlib, Seaborn
3. Scikit-learn
4. Jupyter/Kaggle Notebooks

🧪 Steps Followed

1. Data Cleaning
   1.1 Converted 'Date' to datetime format.
   1.2 Checked for null values and cleaned them.

2. Feature Engineering
   2.1 Extracted Year, Month, Week from Date.
   2.2 Selected relevant features for model training.

3. Model Building & Evaluation
   3.1 Tried Linear Regression, Random Forest, and Gradient Boosting Regressor.
   3.2 Compared performance using MAE and R² score.

4. Best Model
  
    ## Gradient Boosting Regressor gave the best results:
     # MAE: ~54,820
     # R²: ~0.97

📈 Key Learnings

1. Data preprocessing significantly improves model performance.

2. Model evaluation is crucial before selecting the best one.
.
3. Gradient Boosting worked best for this dataset.

## License:
MIT License