# Predicting-Student-Dropout-Using-Machine-Learning


## Student Dropout Prediction using Machine Learning

This project focuses on predicting student dropout using machine learning techniques, specifically leveraging the XGBoost algorithm for classification. The analysis is based on a dataset containing various demographic, academic, and socioeconomic features of students.

## Project Overview

The project follows a structured approach to predict student dropout, encompassing the following key stages:

1. **Data Collection and Understanding:** The dataset consists of 4424 entries with 35 features, including demographic information, academic performance, and socioeconomic status. The target variable is whether a student drops out, enrolls, or graduates.

2. **Data Cleaning and Preparation:** 
    * **Handling Missing Values:** The dataset is checked for missing values and duplicates, ensuring data integrity.
    * **Feature Selection:** Certain features like 'Nationality' and 'International' are excluded from the model to focus on more relevant predictors.

3. **Exploratory Data Analysis (EDA):** 
    * **Target Distribution:** Visualizes the proportion of students who drop out, enroll, or graduate.
    * **Demographic Analysis:** Examines the impact of gender, marital status, and course enrollment on student outcomes.
    * **Socioeconomic Analysis:** Analyzes the influence of parental occupation and educational needs on dropout rates.
    * **Macroeconomic Factors:** Considers the effect of unemployment and inflation rates on student decisions.

4. **Feature Engineering:** 
    * **Label Encoding:** Converts categorical target variables into numerical format for model compatibility.
    * **Correlation Analysis:** Uses a heatmap to identify relationships between variables, aiding in feature selection.

5. **Model Training and Evaluation:** 
    * **Data Splitting:** The dataset is split into training (80%) and testing (20%) sets to evaluate model performance.
    * **XGBoost Classifier:** Implements an XGBoost model with 1000 estimators for binary classification, achieving an accuracy of approximately 90%.
    * **Model Evaluation:** Assesses the model's accuracy and prediction capabilities on the test set.

6. **Prediction System:** 
    * **Input Data:** Demonstrates how to input new student data for prediction using the trained model.
    * **Output Interpretation:** Provides the predicted outcome (dropout or graduate) for the input data.

## Benefits and Applications

This project offers valuable insights for educational institutions:

* **Early Intervention:** Identifies students at risk of dropping out, allowing for timely intervention and support.
* **Resource Allocation:** Helps allocate resources effectively to areas with higher dropout risks.
* **Policy Development:** Informs policy decisions by highlighting key factors influencing student retention.

By utilizing machine learning, this project provides a practical approach to understanding and mitigating student dropout rates, ultimately contributing to improved educational outcomes.
