


# Employee Attrition Prediction for Healthcare

**Project Overview**

The goal of this project is to develop predictive models to forecast employee attrition in a healthcare setting. By leveraging employee demographic and job-related features, this analysis aims to assist in the identification of potential attrition risks and aid in the formulation of effective retention strategies.

**Dataset**

The dataset used for analysis is sourced from Kaggle and is titled "Employee Attrition for Healthcare." The [dataset](https://www.kaggle.com/datasets/jpmiller/employee-attrition-for-healthcare) contains synthetic data, modified from the IBM Watson dataset for attrition, tailored to the healthcare domain. It comprises 1676 rows and 35 columns, including various employee-related attributes.

## Project Structure

### 1. Data Preparation and Cleaning
Explains the initial steps involving data importation, examination, and data cleaning techniques used, such as handling missing values, data type checks, and ensuring data consistency.

### 2. Exploratory Data Analysis (EDA)
Details the steps taken in analyzing and selecting relevant features for the predictive model. Describes Bivariate Analysis, Multivariate Analysis, and PCA for feature selection.

### 3. Machine Learning Prediction
Discusses the various machine learning algorithms/models employed for employee attrition prediction, the preprocessing techniques, hyperparameter tuning, and model testing on validation and test data.

### 4. High-Performance Computational Implementation
Highlights the use of Google Colab for high-performance computation, leveraging PySpark for distributed computing, and accelerating model training, and validation processes.

### 5. Performance Evaluation
Evaluate the models based on metrics such as accuracy, precision, recall, F1 score, and AUC ROC score, concluding the model choice for effective attrition prediction.

## Methodology and Results

The README file provides a comprehensive overview of the project's methodology, detailing data processing steps, model implementation, and performance evaluation. It concludes that the Support Vector Machine (SVM) model demonstrates the highest efficacy for predicting employee attrition.

## How to Use

1. **Dataset**: Download the dataset from the provided Kaggle link or pick the modified dataset in the project directory (watson_healthcare_modified.xlsx).
2. **Code**: The code for data preprocessing, model implementation, and evaluation is available in the project's Jupyter Notebooks.
3. **Run**: Execute the notebooks sequentially to replicate the analysis, model building, and evaluation.

## Conclusion

The README summarizes the project objectives, methodology, and outcomes, concluding that the SVM model shows the best performance for predicting employee attrition in the healthcare industry.
