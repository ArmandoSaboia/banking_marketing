[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io//app.py)
![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]https://colab.research.google.com/github/ArmandoSaboia/banking_marketing/blob/main/notebook/Banking_Marketing_problem.ipynb.ipynb) 
![MIT LICENSE](https://badgen.net//badge/license/MIT/green) ![MAINTAINED BADGE](https://img.shields.io/badge/Maintained%3F-yes-green.svg) 

## Project: Bank Marketing Problem

![28537](https://github.com/ArmandoSaboia/banking_marketing/assets/62614989/63df87f6-2904-4956-a148-3ee25dbf83f2)


### Project Summary:

This project aims to develop a predictive model to determine whether a customer will subscribe to a term deposit with a bank based on various demographic and transactional factors. The dataset used in this project is from the UCI Machine Learning Repository and includes information on over 45,000 customers.

### Introduction:

The banking industry provides various types of services like loans, deposits, etc. In this project, I will analyze data related to a bank`s marketing campaign aimed at encouraging customers to subscribe to a term deposit. The goal of this project is to build a predictive model using machine learning techniques to determine if a customer will subscribe to a term deposit or not, based on various demographic and transactional factors.

### Problem Statement:

I will aim to answer the following question: #Can we predict whether a customer will subscribe to a term deposit with a bank based on various demographic and transactional factors? 

### Dataset Description:

The dataset contains 41188 rows and 21 columns. The columns include information such as age, job, marital status, education, default status (has credit in default?), housing loan, personal loan, contact (contact communication type), day (last contact day of the month), month (last contact month of year), duration (last contact duration), campaign (number of contacts performed during the campaign), number of days that passed by after the client was last contacted from a previous campaign (pdays), number of contacts performed before this campaign and for this client (previous), outcome of the previous marketing campaign (poutcome), and whether or not the customer has subscribed to the term deposit (y).

### Methods and Algorithms:

I will begin by exploring the dataset using EDA, and then perform data wrangling to clean up the data and prepare it for machine learning modeling. I will utilize the Pycaret library and multiple classification algorithms to make predictions on the target variable, which is whether or not a customer will subscribe to the term deposit. I will use multiple Data Profiling Tools, such as, Ydata, Dataprep, Autoviz, Sweetviz and multiple visualization libraries to showcase the results of the models. I will also use Shap, which is an explainability tool, to explain the insights gained from the model. 

### Project Analysis:

I will first import the libraries and dataset, then perform EDA to understand the data and clean the data for modeling. I will then split the data into training and testing sets, deploy the machine learning models using Pycaret library, and select the best model. I will then create a visualizations to showcase the results of the model, and use Shap to explain the insights of the model, and store the project in a GitHub repository. 

### Final Results:

I will present the accuracy, precision and recall for the best-performing model and interpret the results with the help of Shap. I will also present the visualization dashboard.

### Conclusion and Future Scope:

I will conclude the project by summarizing the findings and the success of our predictive model. Future scope includes analyzing more demographic and transactional factors and an iterative approach to the model building process.

### IX. References:

1. https://archive.ics.uci.edu/ml/datasets/Bank+Marketing
2. https://pycaret.org/

## Results

The logistic regression model achieved an accuracy of approximately 89% in predicting whether a customer will subscribe to a term deposit or not. 
The analysis of the data set also revealed several insights, including the importance of follow-up in converting potential customers and the impact of demographic factors on customer behavior.

## Conclusion

The development of a predictive model for term deposit subscription using logistic regression can help banks better target potential customers and improve their marketing effectiveness. Additionally, the insights gained from the analysis of the UCI Banking Marketing Dataset can inform future marketing strategies and help banks identify potential areas for improvement.
