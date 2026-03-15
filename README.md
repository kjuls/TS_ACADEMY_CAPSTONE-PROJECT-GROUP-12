# TS_ACADEMY_CAPSTONE-PROJECT-GROUP-12
This project presents a comprehensive end-to-end supervised machine learning pipeline for fraud detection in mobile money transactions, developed using the PaySim simulation dataset comprising 5,420,481 transaction records across 27 features. 

#### PROJECT OVERVIEW

Financial fraud continues to be one of the most significant threats to digital banking systems. As the volume of electronic transactions grows, detecting fraudulent activity quickly and accurately has become essential for financial institutions.

This project develops a machine learning–based fraud detection system that analyzes transaction behavior and identifies suspicious activity in real time. By leveraging historical transaction data and behavioral patterns, the model learns to distinguish between legitimate and fraudulent transactions.

The project applies a complete end-to-end machine learning workflow, including data preprocessing, feature engineering, handling class imbalance, model training, and performance evaluation.

Two machine learning Models were implemented and compared:
- Logistic Regresiion
- Random Forest Classifier

To address the common challenge of imbalanced fraud datasets, undersampling techniques were applied to ensure the model could effectively learn fraud patterns.

Key transaction features such as transaction amount, transaction frequency, account balance behavior, and recent transaction patterns were used to train the models.

The results demonstrate how machine learning can significantly improve fraud detection capabilities by identifying high-risk transactions while minimizing false positives.

This project highlights how data-driven models can support financial institutions in preventing fraud, protecting customers, and improving transaction security.


#### PROJECT SCOPE

The major goal of this capstone project is to build classification models that could be able to identify the patterns in the various transactions and train these models in order to predict the outcome of the transactions if they are fraud transactions or not. These models are built in an attempt to be deployed into real world data especially financial databases and be able to use the models that we build and train to immediately flag transactions who follows the same pattern of the transactions flagged as fraud and prevent future users from falling victims of fraud.

#### PROJECT OBJECTIVE
- Detect fraudulent financial transactions using machine learning
- Analyze transaction behavior and spending patterns
- Handle imbalanced fraud datasets using resampling techniques
- Train and evaluate classification models for fraud. 
- Identify key transaction features that contribute to fraud detection. 

#### DATASET SOURCE

The dataset being used is a fraud detection dataset of users who carried out transactions using paysim. PaySim is a financial simulator that simulates mobile money transactions based on an original dataset. Although the dataset was generated synthetically using paysim, this dataset was chosen because of how good it relates with real world financial transactions and is also a very good dataset that works well with classification models.

The dataset shows transactions that were tagged as fraud and those that were legit. It is a large dataset containing 5,420,481 rows and 27 columns sourced from [kaggle website](https://www.kaggle.com/datasets/chendoytshman/fraud-detection-paysim).

#### DATA PREPARATION

The preprocessing phase focused on ensuring data consistency and reliability. 

Key steps included: 
- Reducing Data Memory Usage for Ease in Analysis.
- Remaining Columns.
- Adressing Duplicate Records: There were no duplicates in the dataset.
- Identifying Missing values: There were no missing values.
- Dropping Insignificant Columns.
- Identify Zero Values.
