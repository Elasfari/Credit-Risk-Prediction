# Credit Risk Prediction

This project aims to leverage machine learning algorithms to enhance the accuracy and efficiency of credit risk assessment. By analyzing various borrower characteristics and loan features, the models predict the likelihood of loan default, aiding lenders in making informed decisions.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
  - [Data Collection](#data-collection)
  - [Data Preprocessing](#data-preprocessing)
  - [Model Training and Evaluation](#model-training-and-evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [Authors](#authors)
- [References](#references)

## Introduction

Traditional credit scoring methods rely on manual evaluation, which can be time-consuming and potentially inaccurate. This project explores AI-powered credit scoring models that utilize machine learning algorithms to analyze a broader spectrum of data, providing more accurate and efficient credit decisions.

## Dataset

The dataset used in this study is the Credit Risk Dataset obtained from Kaggle. It includes features related to individuals applying for loans, such as employment length, interest rates, and loan status.

## Methodology

### Data Collection

The dataset comprises various features related to loan applicants, such as their financial history, personal information, and loan features.

### Data Preprocessing

1. **Initial Exploration**: Assess data dimensions, types, and missing values.
2. **Missing Value Handling**: Impute missing values using appropriate strategies.
3. **Transformation**: Encode categorical variables numerically and separate the target variable from features.

### Model Training and Evaluation

1. **Data Splitting**: Split the dataset into training and testing sets using stratified sampling to maintain the distribution of the target variable.
2. **Standardization**: Standardize feature variables using the `StandardScaler` for models requiring normalization.
3. **Modeling**:
   - Logistic Regression
   - Naive Bayes
   - Decision Tree
   - Support Vector Machine (SVM)
   - XGBoost

Models were evaluated using accuracy, precision, recall, F1-score, confusion matrix, and ROC curve.

## Results

The performance of the Logistic Regression, Naive Bayes, SVM, and XGBoost models was compared. XGBoost outperformed the other models, achieving the highest F1-score and recall, making it the most effective model for credit risk assessment.

## Conclusion

This project demonstrates the potential of machine learning models in improving credit risk assessment. XGBoost emerged as the best-performing model, providing accurate and reliable predictions of loan defaults.

## References

1. Rahman M. S., Islam M. S., & Shakil A. H. (2023). AI-powered credit scoring and risk assessment models: A review. [ResearchGate](https://www.researchgate.net/publication/336240486_Credit_scoring_using_machine_learning_algorithims)
2. Huang Y., Chen Y., & Huang D. (2023). Credit Risk Assessment of Commercial Bank Customers Based on Machine Learning. International Journal of Pattern Recognition and Artificial Intelligence, 37(1), 2350002. [ResearchGate](https://www.researchgate.net/publication/379224853_Credit_Risk_Assessment_of_Commercial_Bank_Customers_Based_on_Machine_Learning)
3. Liu W., Li W., & Zeng Y. (2023). Credit risk assessment using the factorization machine model with feature interactions. Knowledge and Information Systems, 65(1).
4. Agarwal S., Agarwal A., & Bhagat S. (2023). Machine Learning in Credit Risk Assessment: Analyzing How Machine Learning Models Are Transforming the Assessment of Credit Risk for Loans and Credit Cards. International Journal of Financial Research, 14(2), 1-19. [ResearchGate](https://www.researchgate.net/publication/380732622_MACHINE_LEARNING_IN_CREDIT_RISK_ASSESSMENT_ANALYZING_HOW_MACHINE_LEARNING_MODELS_ARE_TRANSFORMING_THE_ASSESSMENT_OF_CREDIT_RISK_FOR_LOANS_AND_CREDIT_CARDS)

