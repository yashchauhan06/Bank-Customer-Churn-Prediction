# Bank-Customer-Churn-Prediction

This repository presents a machine learning project aimed at predicting customer churn for a bank using the Churn Modeling Dataset. The focus is on identifying customers likely to leave, leveraging Logistic Regression and K-Nearest Neighbors (KNN) models.

## Project Overview
Customer churn refers to the loss of clients or subscribers. The goal of this project is to minimize false negatives, ensuring high recall to capture potential churners.

## Key Steps
1. Data Loading and Preprocessing:
   - Handled missing values and encoded categorical variables.
   - Scaled numerical features for consistency.
2. Model Training:
   - Logistic Regression for probabilistic classification.
   - K-Nearest Neighbors for similarity-based classification.
3. Model Evaluation:
   - Confusion Matrix, Precision, Recall, F1 Score, and Accuracy.
   - Visualizations: Precision-Recall and ROC Curves.
4. Optimization:
   - Focused on improving recall to mitigate costly false negatives.

## Results
- The model results highlight the trade-offs between Logistic Regression and KNN in predicting customer churn, with emphasis on scenarios where recall is prioritized.

## Technologies Used
- **Programming**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

