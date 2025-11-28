# 📘 **Customer Churn Prediction**

This project focuses on predicting customer churn using various machine learning models to help businesses retain customers by identifying those who are most likely to discontinue their services. Customer churn prediction is a critical business problem, particularly in subscription-based industries such as telecommunications, banking, and SaaS, where retaining existing customers is often more cost-effective than acquiring new ones. This notebook implements and compares three supervised learning algorithms — **Logistic Regression, Random Forest Classifier,** and **XGBoost Classifier** — to build a robust predictive system.



The project begins with an exploratory data analysis **(EDA)** phase, where the dataset is inspected to understand its structure, identify missing values, detect outliers, and analyze correlations between features. Visualizations are used to understand patterns related to customer demographics, tenure, service usage, and billing details. During the preprocessing phase, categorical variables are encoded using appropriate techniques such as one-hot encoding, and numerical variables are scaled when necessary. Missing or inconsistent values are handled carefully to ensure that the models receive clean and consistent data for training.



After preprocessing, feature selection and engineering are performed to enhance the model’s predictive capability. Columns that are redundant, non-informative, or highly correlated are dropped to avoid multicollinearity. New meaningful features, such as total service count or customer engagement metrics, may be engineered to improve model interpretability and performance. The cleaned and processed dataset is then split into training and testing subsets to evaluate model generalization.



Three classification algorithms are then trained and compared. **Logistic Regression** serves as both the baseline and, ultimately, the best-performing model. Its simplicity, interpretability, and ability to provide well-calibrated probability outputs make it an excellent choice for binary classification problems such as churn prediction.

