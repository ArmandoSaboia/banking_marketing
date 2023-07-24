[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io//app.py)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1HH86l2-F3ahl_hWr7X2Kw8TFsoHWZRGa#scrollTo=Ng3rJxpCHiTJ)
![MIT LICENSE](https://badgen.net//badge/license/MIT/green) ![MAINTAINED BADGE](https://img.shields.io/badge/Maintained%3F-yes-green.svg) 
![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/ArmandoSaboia/banking_marketing)
![GitHub pull requests](https://img.shields.io/github/issues-pr/ArmandoSaboia/banking_marketing)
![GitHub contributors](https://img.shields.io/github/contributors/ArmandoSaboia/banking_marketing)




## Project: Bank Marketing Problem

![28537](https://github.com/ArmandoSaboia/banking_marketing/assets/62614989/63df87f6-2904-4956-a148-3ee25dbf83f2)


### Project Summary:

This project aims to develop a predictive model to determine whether a customer will subscribe to a term deposit with a bank based on various demographic and transactional factors. The dataset used in this project is from the UCI Machine Learning Repository and includes information on over 45,000 customers.

### Introduction:

The banking industry provides various types of services like loans, deposits, etc. In this project, I will analyze data related to a bank`s marketing campaign aimed at encouraging customers to subscribe to a term deposit. The goal of this project is to build a predictive model using machine learning techniques to determine if a customer will subscribe to a term deposit or not, based on various demographic and transactional factors.

### Problem Statement:

Targeting potential customers more efficiently by identifying those likely to subscribe to a term deposit, allowing for better allocation of marketing resources. I will aim to answer the following question: Can we predict whether a customer will subscribe to a term deposit with a bank based on various demographic and transactional factors? 

### Dataset Description:

The dataset contains 41188 rows and 21 columns. The columns include information such as age, job, marital status, education, default status (has credit in default?), housing loan, personal loan, contact (contact communication type), day (last contact day of the month), month (last contact month of year), duration (last contact duration), campaign (number of contacts performed during the campaign), number of days that passed by after the client was last contacted from a previous campaign (pdays), number of contacts performed before this campaign and for this client (previous), outcome of the previous marketing campaign (poutcome), and whether or not the customer has subscribed to the term deposit (y).

### Methods and Algorithms:

I will begin by exploring the dataset using EDA, and then perform data wrangling to clean up the data and prepare it for machine learning modeling. I will utilize the Pycaret library and multiple classification algorithms to make predictions on the target variable, which is whether or not a customer will subscribe to the term deposit. I will use multiple Data Profiling Tools, such as, Ydata, Dataprep, Autoviz, Sweetviz and multiple visualization libraries to showcase the results of the models. I will also use Shap, which is an explainability tool, to explain the insights gained from the model. 

### Project Analysis:

I will first import the libraries and dataset, then perform EDA to understand the data and clean the data for modeling. I will then split the data into training and testing sets, deploy the machine learning models using Pycaret library, and select the best model. I will then create a visualizations to showcase the results of the model, and use Shap to explain the insights of the model, and store the project in a GitHub repository. 

### Final Results:

The CatBoost Classifier model achieved an accuracy of approximately 93% in predicting whether a customer will subscribe to a term deposit or not. 
The analysis of the dataset also revealed several insights, including the importance of follow-up in converting potential customers and the impact of demographic factors on customer behavior. The findings were further enhanced with interactive visualizations using Dash and Streamlit.

Due to the complexity and length of the code, I'll provide an outline for using these libraries:

For Dash:

Install Dash: pip install dash

For Streamlit:

Install Streamlit: pip install streamlit

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io//app.py)

## Conclusion

In the bank's marketing strategy, understanding customer behaviors and preferences can have a significant impact. After analyzing the UCI Bank Marketing dataset, I have identified the top 5 features that strongly influence term deposit subscriptions:

1. Contact Duration: The duration of the last contact with the customer plays a vital role. Longer conversations indicate higher interest and engagement, making these customers more likely to subscribe. Targeting them with personalized marketing campaigns can lead to better results.

2. Communication Channels: Using cellular communication has proven to be a successful driver for term deposit subscriptions. By investing more in mobile marketing strategies, the bank can connect with a wider audience and achieve higher subscription rates.

3. Month of Last Contact: The month of the last contact also influences subscription likelihood. Customers contacted during specific months, such as May, July, or August, tend to be more receptive to term deposit offers. Recognizing these seasonal patterns allows the bank to strategize its campaigns and focus on these months for maximum conversion rates.

4. Balance: Customers with higher account balances are more likely to subscribe to a term deposit. The bank can tailor its marketing efforts to engage these financially stable customers effectively.

5. Age: Age is another crucial factor. Middle-aged and older customers are more likely to subscribe compared to younger customers. Understanding this demographic difference allows the bank to target the appropriate age groups with relevant marketing messages.

Understanding customer behaviors and preferences is crucial for the bank's marketing strategy. By applying these insights, the bank can identify potential subscribers and tailor its efforts to increase term deposit subscriptions, leading to better overall performance and success in the market.


### References:

1. https://archive.ics.uci.edu/ml/datasets/Bank+Marketing
2. https://pycaret.org/
