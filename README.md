# E-Commerce-Customer-Churn-Analysis

## Project Overview
This project is focused on analyzing customer churn in an ecommerce setting. The goal is to understand the factors that contribute to customer churn and to develop predictive models to identify customers who are likely to churn. The analysis is performed using a Jupyter Notebook and includes data exploration, feature engineering, and model development.

## File Description
- FINAL - Ecommerce Customer Churn Analysis.ipynb: The main Jupyter notebook that contains the entire analysis, including:
  - Data Loading and Exploration: Initial inspection of the dataset, understanding data structure, and basic statistics.
  - Data Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.
  - Exploratory Data Analysis (EDA): Visualizing data distributions, correlations, and patterns.
  - Feature Engineering: Creating new features to improve model performance.
  - Modeling: Developing and evaluating machine learning models to predict customer churn.
  - Conclusion: Summary of findings and recommendations.
- confusion matrix - ecommerce churn.png
- data_ecommerce_customer_churn.csv
- LightGBM_Churn_saved
  - Saved model for future use. Need 10 features to operate. find details of the features in either `.pptx` or `.ipynb` file.
- PPT - Ecommerce Churn Analysis.pptx

## Installation
To run the `.ipynb` file locally, ensure you have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- You can install the required packages using pip:
  - pip install pandas numpy matplotlib seaborn scikit-learn

## Usage
- Clone this repository to your local machine.
- Navigate to the project directory.
- Open the Jupyter Notebook:
  - jupyter notebook "FINAL - Ecommerce Customer Churn Analysis.ipynb"
- Run the notebook cells sequentially to reproduce the analysis.

## Dataset
The dataset used in this analysis includes customer information and various features related to their behavior and interactions with the ecommerce platform. It contains the following columns:

- Tenure: Tenure of a customer in the company.
- WarehouseToHome: Distance between the warehouse to the customer’s home.
- NumberOfDeviceRegistered: Total number of deceives is registered on a particular customer.
- PreferedOrderCat: Preferred order category of a customer in the last month.
- SatisfactionScore: Satisfactory score of a customer on service.
- MaritalStatus: Marital status of a customer.
- NumberOfAddress: Total number of added on a particular customer.
- Complaint: Any complaint has been raised in the last month.
- DaySinceLastOrder: Day since last order by customer.
- CashbackAmount: Average cashback in last month
- Churn: Churn flag.

## Results
The analysis led to the development of a LightGBM model with the following performance metrics :

- mean F2 Score : 78.5%

## Conclusion
This analysis provides insights into customer churn behavior and identifies potential strategies to retain customers. Future work could involve enhancing the model with additional features or testing different machine learning algorithms.
