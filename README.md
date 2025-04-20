# HDB Resale Price Analysis

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on Singapore's HDB Resale Flat Prices from [data.gov.sg](https://data.gov.sg/collections/189/view) repository.

For detailed walkthrough of the code, [View the full Jupyter Notebook here](https://github.com/ernestshh/SC1015_MiniProject/blob/main/SC1015%20Mini%20Project.ipynb)


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

## Data Cleaning and Extraction
-  Dropping Irrelevant Columns 
- Formatting Remaining Lease  
-  Creating Price per Square Meter (PSM) 
-  One-Hot Encoding of Categorical Variables


## Exploratory Data Analysis
We explored the relationship between predictors and the target variable (Resale Price):

- **Overview of Resale Flat Distribution (Univariate Analysis):**
  - Categorical and numerical distributions

- **Bivariate Analysis with Respect to Resale Price:**
  - Comparisons between individual predictors and Resale Price
  - Correlation Matrix to better visualise the correlation coefficients of variables with Resale Price

We did this using Histograms, Box and Whisker Plots, Scatter plots and a Correlation Matrix Heat Map

## Models Used

Linear Regression: Explore the linear relationship of each feature with resale price.

Random Forest Regression: Able to capture non-linear relationships in the data, reveal feature importance and predict resale price with higher accuracy than linear regression.

Random Forest Classifier: Determine whether the resale price is "fair" or "unfair" based on predefined thresholds, enhancing decision-making for homebuyers and sellers.

## Evaluation Metrics

To evaluate the performance of our models, we used:

- **Root Mean Squared Error (RMSE)**: Measures the average magnitude of prediction errors in the same unit as the target variable. Lower RMSE indicates better fit.
- **R² Score (Explained Variance)**: Indicates how much of the variation in resale prices can be explained by the model. Ranges from 0 to 1.
- **Precision, Recall, and F1 Score** (for classification): Used to assess the ability of the classifier to correctly identify whether a resale price is “fair” or “unfair”.

## Conclusion
- We were able to develop a predictive model for HDB Resale prices using a Random Forest Regression model which performed significantly better than Multivariate Linear Regression
- We then successfully implemented a Random Forest Classification model that assessed the fairness of our price predictions

## Findings
- Floor area and remaining lease years were the strongest predictors of resale price
- About 78% of homebuyers pay a fair price for their HDB resale flat, suggesting that the real estate market is relatively efficient
- According to our model, the mean absolute difference between predicted and actual resale price was $27,000
- Certain towns such as Bukit Merah and Queenstown were shown to have a noticeable impact on resale prices, likely due to their premium location

## What did we learn from this project?
- Handling categorical data using One-Hot Encoding
- Random Forest Regression and Classification
- Concepts about Precision, Recall, and F1 Score
- Identifying overfitting by evaluating train-test performance gaps
- Collaborating using GitHub

## Future Improvements

- Include more granular location data such as postal sectors or distance to MRT  
- Incorporate economic indicators like interest rates or inflation
- Possibly implement other Machine Learning like XGBoost to improve model performance

## References
- https://data.gov.sg/collections/189/view
- https://www.geeksforgeeks.org/ml-one-hot-encoding/
- https://www.geeksforgeeks.org/random-forest-regression-in-python/
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
- https://create.microsoft.com/en-us/template/light-modernist-design-fd6c6e3e-ccdc-4ba4-b6a2-3dbf5a4b5e68
- https://developers.google.com/machine-learning/crash-course/classification/accuracy-precision-recall
- https://create.microsoft.com/en-us/template/light-modernist-design-fd6c6e3e-ccdc-4ba4-b6a2-3dbf5a4b5e68
- https://developers.google.com/machine-learning/crash-course/classification/accuracy-precision-recall
