# HDB Resale Price Analysis

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on Singapore's HDB Resale Flat Prices from [data.gov.sg](https://data.gov.sg/collections/189/view) repository.

For detailed walkthrough of the code, [View the full Jupyter Notebook here](https://github.com/your-username/your-repo-name/blob/main/SC1015_Project_Final.ipynb)


## Contributors
- Lim Wei Jian David (LIMW0234@e.ntu.edu.sg)
  - Data Cleaning
  - Data Visualization
  - Linear Regression

- See Pei Jin, Ernest (ESEE003@e.ntu.edu.sg)
  - Data Cleaning
  - Data Visualization
  - Random Forest Regression and Classification


## Problem Definition 
- Are we able to predict the fair price of HDB resale prices based on relevant features?

- Are we able to determine if the price of a HDB resale flat is fair?


## Models Used

- Linear Regression

- Random Forest Regression

- Random Forest Classifier

## Conclusion
- We were able to develop a predictive model for HDB Resale prices using a Random Forest Regression model which performed significantly better than Multivariate Linear Regression
- We then successfully implemented a Random Forest Classification model that assessed the fairness of our price predictions
- Floor area and remaining lease years were the strongest predictors of resale price
- About 78% of homebuyers pay a fair price for their HDB resale flat, suggesting that the real estate market is relatively efficient
- According to our model, the mean absolute difference between predicted and actual resale price was $27,000
- Certain towns such as Bukit Merah and Queenstown were shown to have a noticeable impact on resale prices, likely due to their premium location


## What did we learn from this project?
- Random Forest Regression and Classification
- Collaborating using GitHub
- Concepts about Precision, Recall, and F1 Score

## References
- https://data.gov.sg/collections/189/view
- https://www.geeksforgeeks.org/ml-one-hot-encoding/
- https://www.geeksforgeeks.org/random-forest-regression-in-python/
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
- https://create.microsoft.com/en-us/template/light-modernist-design-fd6c6e3e-ccdc-4ba4-b6a2-3dbf5a4b5e68
