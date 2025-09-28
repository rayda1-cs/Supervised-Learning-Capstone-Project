**Supervised Learning Capstone – Customer Churn Prediction**

This project applies supervised machine learning to predict customer churn using the Telco Customer Churn dataset. The main objective is to identify which customers are likely to cancel their service and understand the key factors that influence churn.
***
**Project Overview**

The project follows the full data science workflow:

- Load and explore the Telco Customer Churn dataset

- Conduct exploratory data analysis (EDA) to understand patterns and distributions

- Preprocess categorical and numerical features for modeling

- Train and evaluate tree-based supervised learning models

- Compare model performance and interpret results
***
**Workflow**
**Data Preprocessing**

- Inspected datatypes and handled missing values

- Converted categorical features into dummy variables

- Scaled numerical features where necessary

- Balanced churn classes for fair evaluation

**Exploratory Data Analysis**

- Count plots of churn vs. non-churn customers

- Box and violin plots of key features such as TotalCharges

- Correlation analysis to identify important predictors

**Model Training and Evaluation**

- Focus on Decision Trees and Random Forests

- Trained models to classify customers as churn vs. non-churn

- Evaluated using accuracy, precision, recall, and F1-score

- Visualized decision tree splits for interpretability
***
**Results and Insights**

- Customers with higher monthly charges showed a greater likelihood of churn

- Contract type was a strong predictor: month-to-month customers were more likely to churn

- Random Forest outperformed a single Decision Tree in terms of accuracy and generalization

- Preprocessing categorical features and scaling improved overall performance
***
**Applications**

- Telecommunications: anticipate which customers are at risk of canceling and apply retention strategies

- Subscription Services: identify at-risk subscribers for targeted offers

- Banking/Insurance: predict policy cancellations or account closures
***
**Skills Demonstrated**

- Data cleaning and preprocessing of mixed categorical/numeric data

- Exploratory data analysis with visualizations

- Implementation of supervised learning methods (Decision Trees, Random Forests)

- Model evaluation with multiple performance metrics

- Interpretation of feature importance in classification models
***
**Technologies Used**

- Python

- Pandas, NumPy, Matplotlib, Seaborn

- Scikit-learn

- Jupyter Notebook
