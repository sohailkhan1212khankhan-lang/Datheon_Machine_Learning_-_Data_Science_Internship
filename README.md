Datheon_Machine_Learning_&_Data_Science_Internship
# Iris Flower Classification

 Project Description
This project classifies Iris flowers using Machine Learning.

 Dataset
- Total samples: 150
- Features: 4

 Models Used
- Logistic Regression
- Decision Tree Classifier

 Accuracy Results
- Logistic Regression: 96.67%
- Decision Tree: 100%

## Libraries
- Pandas
- NumPy

                                                    Task 2


  # California Housing Price Prediction

 About the Project

This project is about predicting house prices using the California Housing dataset. I used different regression models to see how accurately they can predict median house values.

The main goal was to prepare the data, train the models, and compare their results.

 Dataset

I used the California Housing dataset, which contains information about housing in different areas of California.

 Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

 Work Done

- Loaded and explored the dataset.
- Checked and handled missing values.
- Created correlation heatmaps to understand relationships between features.
- Created new features using existing columns.
- Converted categorical data into numerical values.
- Standardized the features.
- Trained three regression models separately.
- Used GridSearchCV to find the best alpha values for Ridge and Lasso.
- Evaluated the models using RMSE, MAE, and R² score.
- Created predicted vs. actual plots and residual distribution plots.

 Models Used

1. OLS (Linear Regression) — used as the baseline model.
2. Ridge Regression— used L2 regularization.
3. Lasso Regression — used L1 regularization.

 Results

| Model | RMSE | MAE | R² Score |
|---|---:|---:|---:|
| OLS | 70060.52 | 50670.74 | 0.6254 |
| Ridge | 70031.31 | 50646.17 | 0.6257 |
| Lasso | 70053.90 | 50664.70 | 0.6255 |

Ridge Regression gave the best results among the three models, with the lowest RMSE and MAE and the highest R² score. However, the difference between the models was small.

 How to Run

1. Download or clone this repository.
2. Open the `.ipynb` notebook in Jupyter Notebook or Google Colab.
3. Install the required libraries if they are not already installed.
4. Run the cells in order.
5. Check the model results and plots.

 Conclusion

In this project, I learned how to prepare a dataset for regression, create new features, handle missing values, and compare different regression models. Ridge performed slightly better than OLS and Lasso on the test data.

This project helped me practice the main steps of a machine learning regression workflow.




- Scikit-learn
- Matplotlib
- Seaborn

                                               Task 3
   Telecom Customer Churn Prediction

 Project Overview
This project predicts whether a telecom customer is likely to leave the company (churn) using machine learning. Two classification models, Random Forest and XGBoost, are trained and compared to identify the better-performing model.

 Dataset
- **Source:** IBM Telco Customer Churn Dataset
- **Target Variable:** `Churn`
- **Target Classes:** Yes (customer churned) and No (customer did not churn)

 Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook / Google Colab

 Project Workflow
1. Load and explore the dataset.
2. Clean the data and handle missing values.
3. Encode categorical features using OneHotEncoder.
4. Split the dataset into training and testing sets.
5. Handle class imbalance using class weights.
6. Train Random Forest and XGBoost classifiers.
7. Evaluate models using ROC-AUC and classification reports.
8. Perform 5-fold stratified cross-validation.
9. Plot ROC curves to compare model performance.
10. Identify the top 10 important features.

 Model Performance

| Model | Test ROC-AUC | Mean CV ROC-AUC |
|---|---:|---:|
| Random Forest | 0.7753 | 0.7813 |
| XGBoost | 0.8258 | 0.8191 |

 Results
XGBoost achieved a test ROC-AUC score of **0.8258**, outperforming Random Forest, which achieved 0.7753. Based on these results, XGBoost was the better-performing model for distinguishing between customers who churn and those who do not.

 How to Run
1. Clone or download this repository.
2. Open the project notebook in Jupyter Notebook or Google Colab.
3. Install the required libraries:

 
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
 

4. Run the notebook cells in order.
5. Review the model evaluation results, ROC curve, and feature importance plot.

 Future Improvements
- Tune model hyperparameters.
- Optimize the churn classification threshold.
- Improve recall for customers likely to churn.
- Use feature importance to understand the main factors associated with churn.



