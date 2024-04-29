# Student Grade Prediction and Recommendation System

## Overview
This repository contains the implementation of a student grade prediction and recommendation system aims to address the challenge of student dropout rates in higher education by leveraging machine learning techniques to predict student grades and offer personalized recommendations for academic improvement.

## Key Features
1. Exploratory Data Analysis (EDA): Discusses how EDA was conducted to gain insights from the dataset and understand the relationships between variables. Mention visualization techniques used, such as histograms, bar plots, and correlation matrices.
2. Model Evaluation Metrics: Describes the evaluation metrics used to assess the performance of regression and classification models, such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), Mean Squared Error (MSE), and R-squared (R^2) for regression, and test accuracy and train accuracy for classification.
3. Predictive Modeling: Utilizes various regression and classification algorithms such as Lasso Regression and Bagging Classifier to predict student grades and classify instances.
4. Feature Importance Analysis: Identifies significant factors influencing student performance, including academic history, attendance, parental support, and socioeconomic background.
5. Personalized Recommendations: Generates tailored suggestions for students based on their academic profiles, leveraging Large Language Models (LLMs) and SHAP values for individualized insights.

## Dataset
The system utilizes the "Student Performance in Secondary Education" dataset obtained from the University of Minho in Portugal. This dataset contains student data from two Portuguese schools, including demographic information, academic performance, and family-related attributes. The dataset has been sourced from Kaggle.
Dataset Link : https://archive.ics.uci.edu/ml/datasets/student+performance

##Proposed Solution
Key Components:
1. Data Preprocessing and Exploratory Data Analysis (EDA): The dataset undergoes preprocessing to handle missing data and convert categorical variables into numerical format. EDA is conducted to gain insights and visualize relationships between variables, helping identify patterns and trends in the data.
2. Model Selection and Evaluation: Various regression and classification models are compared, including Lasso Regression and Bagging Classifier, to determine the most effective for grade prediction and classification. Evaluation metrics such as MAE, RMSE, and R-squared are used to assess model performance.
3. Feature Importance Analysis: SHAP values are employed to determine the significance of individual features in predicting student performance. This analysis provides critical insights into influential factors such as prior academic performance, attendance, and socioeconomic background.
4. Personalized Recommendations: Utilizing Large Language Models (LLMs), personalized recommendations are generated for students based on their academic profiles and predicted grades. These recommendations include study strategies, time management techniques, and resources aimed at improving academic performance.

##Conclusion
In conclusion, the student grade prediction and recommendation system developed in this research project offers a comprehensive solution to tackle the issue of student dropout rates in higher education. Through the integration of machine learning models, thorough data analysis, and personalized recommendation generation, the system effectively identifies influential factors like academic history, attendance, and socioeconomic background to predict student grades accurately. The incorporation of personalized recommendations, driven by Large Language Models (LLMs) and SHAP values, empowers students to address specific areas of improvement and enhance their academic outcomes. Overall, this solution provides actionable strategies for educators and institutions to intervene effectively, contributing to the broader goal of fostering inclusive education and promoting lifelong learning opportunities for all students.
