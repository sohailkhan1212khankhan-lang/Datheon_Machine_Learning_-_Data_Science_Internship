Datheon_Machine_Learning_&_Data_Science_Internship
# Iris Flower Classification

## Project Description
This project classifies Iris flowers using Machine Learning.

## Dataset
- Total samples: 150
- Features: 4

## Models Used
- Logistic Regression
- Decision Tree Classifier

## Accuracy Results
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

1. **OLS (Linear Regression)** — used as the baseline model.
2. **Ridge Regression** — used L2 regularization.
3. **Lasso Regression** — used L1 regularization.

 Results

| Model | RMSE | MAE | R² Score |
|---|---:|---:|---:|
| OLS | 70060.52 | 50670.74 | 0.6254 |
| Ridge | 70031.31 | 50646.17 | 0.6257 |
| Lasso | 70053.90 | 50664.70 | 0.6255 |

Ridge Regression gave the best results among the three models, with the lowest RMSE and MAE and the highest R² score. However, the difference between the models was small.

## How to Run

1. Download or clone this repository.
2. Open the `.ipynb` notebook in Jupyter Notebook or Google Colab.
3. Install the required libraries if they are not already installed.
4. Run the cells in order.
5. Check the model results and plots.

## Conclusion

In this project, I learned how to prepare a dataset for regression, create new features, handle missing values, and compare different regression models. Ridge performed slightly better than OLS and Lasso on the test data.

This project helped me practice the main steps of a machine learning regression workflow.




- Scikit-learn
- Matplotlib
- Seaborn

## Conclusion
Both Machine Learning models performed well on the Iris dataset.
