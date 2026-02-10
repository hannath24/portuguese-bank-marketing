# portuguese-bank-marketing
Machine learning classification project to predict term deposit subscription using the Portuguese Bank Marketing dataset.

# overview
This project aims to predict whether a customer will subscribe to a term deposit based on marketing campaign data from a Portuguese bank. The task is formulated as a binary classification problem with a focus on handling class imbalance and evaluating models using appropriate metrics.

Marketing campaigns in the banking sector often suffer from low response and high operational cost due to ineffective customer targeting.Banks often spend long time in contacting to find the clients for their product.This project used portugese banking dataset by portuguese banking institute from may 2008 to november 2010.Multiple classification algorithms were evaluated like, Logistic regression,Decision tree,Random Forest,Gradient Boosting and XGBoost and best model is selected to help banks to find high probablity customers,increase efficiency in marketing,reduce unnecessary outreach.

A term deposit is a banking product where customers invest a fixed amount of money for a predetermined period in return for higher interest. In this project, the objective is to predict whether a customer will subscribe to such a product when contacted by the bank.

# problem statement
initially bank have to contact every customer about the subscription to a term deposit,and most customer reject the plan causing waste of time ,large no:of calls and less subscription.The objective is to build a machine learning model that can accurately predict customer responses to marketing campaigns, helping banks improve targeting efficiency and decision-making.

# Dataset
This dataset is about the direct phone call marketing campaigns, which aim to promote
term deposits among existing customers, by a Portuguese banking institution from May
2008 to November 2010.
- Type: Structured tabular data
- Target Variable: y (term deposit subscription: yes/no)
- Mixed categorical and numerical features
- Imbalanced target classes

# workflow
- Basic checks
- Exploratory data analysis
- preprocessing
- Model training
- Evaluation and selection
- Hyperparameter tuning
- feature importance
- probablity threshold tuning

# Techniques used
- SMOTE - class imbalance
- One-Hot Encoding - Categorical features
- Scaling - numerical features

-Evaluated models using precision, recall, F1-score, and ROC-AUC
-Performed threshold tuning to balance business trade-offs

# Modeling
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- KNN
- Naive Bayes
- XGBoost(selected model)

# Metrics used:
- Precision
- Recall
- F1-score
- ROC-AUC

