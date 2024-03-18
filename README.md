# credit-card-approval-prediction
This project include Statistics, Data Analysis, feature engineering and Machine Learning Approach for Credit Card Approval 
Commercial banks get a lot of requests for credit cards. But, they often reject many of them because of reasons like having too much debt,low income, or too many inquiries on a person's credit history. Analyzing these requests manually takes a lot of time and can lead to mistakes.Thankfully, we can use machine learning to automate this process, just like most banks do. In this guide, we'll make a credit card approval predictor using machine learning techniques
Section 1. Why is your proposal important in today’s world? How predicting a good client is worthy for a bank?

Predicting good client is crucial for banks to minimize creditr risk and make informed lending decisions in today's world where DATA SCIENCE & ML are becoming integral to financial institution accurate credit card approvalpredictions can significantly impact a bank's profitability and customer satisfaction

2. How is it going to impact the banking sector?

Accurate credit card approval predictions can lead to reduced default rates, lower financial losses, and improved customer experiences. This can positively impact a bank's profitability, reputation, and competitiveness in the market.

3. If any, what is the gap in the knowledge or how your proposed method canbe helpful if required in the future for any bank in India?

The proposed method can address the gap in credit assessment by incorporating advanced data analysis and machine learning techniques. Its adaptability makes it valuable for banks in India and beyond, as it can continuously evolve to consider new data sources and enhance creditworthiness assessments.

Section 2: Initial Hypotheses

In the Data Analysis (DA) track, we will aim to identify patterns in the data and important features that may impact a Machine Learning (ML) model. Our initial hypotheses are:

Hypothesis 1: Income type, annual income, and education level are crucial factors in predicting credit card approval.

Hypothesis 2: Car ownership, property ownership, and family size may influence credit card approval decisions.

Hypothesis 3: The length of employment and the presence of a mobile phone or email address could be relevant features.

Hypothesis 4: Gender, marital status, and housing type may also play a role in credit card approval.

Section 3: Data Analysis Approach

Our data analysis approach will involve: Exploratory Data Analysis (EDA) to identify important patterns, correlations, and outliers in the data. Feature engineering techniques to create relevant features that can improve model performance. Utilizing visualization tools to justify our findings and provide insights into the relationships within the data.

Feature Engineering

This Project required some feature Engineering techniques like onehot encoding,label encoding to transform the categorical variable into numerical variable and feature engineering like standard scaler to normalize the data for machine learning

justification of data analysis approach

Here we used visulisation tools like boxplot to determine the outlier and histogram to show the distribution of data. Replace the null value with median and mode to make the data more suitable for machine learning

Section 4: Machine Learning Approach

We will use various machine learning models, including but not limited to logistic regression, decision trees, random forests,SVM and XGBoost, to predict credit card approval based on customer information.

Justification for Model Selection:

Logistic Regression: A simple yet interpretable model to establish a baseline. Decision Trees and Random Forests: To capture non-linear relationships and feature interactions. XGBoost: To improve predictive accuracy by combining multiple weak models

Steps to Improve Model Accuracy:

Feature selection to identify the most relevant variables. Hyperparameter tuning for model optimization. Cross-validation to assess model performance. Evaluation metrics, such as accuracy, precision, recall, and F1-score, to justify the chosen model.

Comparison of Models:

We compared the performance of at least four machine learning models using classification_report, accuracy_score, confusion_matrix and cross valiation to determine the most suitable model for credit card approval prediction. XGBoost Model is giving highest accuracy of 90 %, hence we will use XGBoost Model for predicion among the four model.

########

A number of applications for credit cards are received by commercial banks. For various factors, many of them are refused, such as high debt balances, low income levels, or too many questions into an individual's credit report, for instance. It is mundane, error-prone, and time-consuming and time is money! to manually analyze these applications. Luckily,with the power of machine learning, this activity can be automated and almost every commercial bank does so nowadays.In this notebook, we will create an automated credit card approval predictor using machine learning techniques, just like the real banks do.

This notebook follows the some instructions

At first , we load and view the dataset.

Here, we could see some numerical and categorical values.This valus are some missing , attributes are not relevant.

We will have to preprocesses the data to ensure before implementing machine learning model and so that we can get better performance from my model.

We will make visualize on the data cause visualize data can say a thousands of word in insights.

We will evaluate performance the model.

Then we will do hyperparameter tuning and optimization so that we can get better performance.

We will also do comparison some machine learning model which model will give a better result.
