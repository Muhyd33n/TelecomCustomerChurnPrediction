# Customer Churn Prediction in Telecommunications
## Project Overview
This project aims to predict customer churn for a telecommunications company using Decision Tree and Random Forest classifiers. Customer churn, which occurs when customers stop using a service, is critical for telecom companies to manage, as retaining customers is more economical than acquiring new ones.
By analyzing customer behavior, service preferences, and demographic data, we can identify patterns that help predict churn and allow companies to develop targeted retention strategies.

## Objectives
- Evaluate the performance of Decision Tree and Random Forest classification algorithms for predicting customer churn.
- Use key metrics such as F1-Score, Precision, and Recall to determine model effectiveness.
- Explore the impact of hyperparameter tuning on model performance.
- Recommend the best-performing model for churn prediction.

## Dataset
#### Source: The dataset contains 7043 rows and 21 columns, with no null values.
#### Columns:
Demographic details: Gender, SeniorCitizen, Dependents
Services: PhoneService, InternetService, StreamingTV, TechSupport
Contracts: Contract, PaperlessBilling, PaymentMethod
Churn status (Target): Yes, No
Class Label: Churn (binary: 0 = Not Churned, 1 = Churned).

## Data Mining Methodology
This project follows the Cross-Industry Standard Process for Data Mining (CRISP-DM) methodology:
#### Business Understanding: 
Predict customer churn to help the telecom company reduce losses and improve retention.
#### Data Understanding: 
Explore the data to identify trends and patterns related to churn.
#### Data Preparation:
Cleaned and preprocessed the dataset.
Addressed class imbalance for the churn label.
Split the dataset into training and testing sets.
#### Modeling:
Trained Decision Tree and Random Forest classifiers.
Performed hyperparameter tuning to optimize model performance.
#### Evaluation: 
Assessed models using Accuracy, Precision, Recall, and F1-Score.
#### Deployment: 
Recommendations were made to deploy the best-performing model.

## Results and Discussion
#### Performance Metrics Before Hyperparameter Tuning
Classifier	Accuracy	Precision (0/1)	Recall (0/1)	F1-Score (0/1)
Decision Tree	0.75	0.85 / 0.51	0.80 / 0.59	0.82 / 0.55
Random Forest	0.77	0.85 / 0.56	0.84 / 0.58	0.85 / 0.57
#### Performance Metrics After Hyperparameter Tuning
Classifier	Accuracy	Precision (0/1)	Recall (0/1)	F1-Score (0/1)
Decision Tree	0.75	0.86 / 0.51	0.78 / 0.66	0.82 / 0.58
Random Forest	0.77	0.86 / 0.56	0.84 / 0.60	0.85 / 0.58

## Key Observations:
Random Forest performed better before tuning but showed minimal improvement after tuning.
Decision Tree improved after hyperparameter tuning, achieving a higher Recall and slightly better F1-Score.

## Conclusion
Random Forest achieved higher precision, making it reliable for identifying customers not likely to churn.
Decision Tree excelled in recall, making it effective for detecting customers likely to churn.
While Random Forest performed slightly better overall, further improvement may be achieved using other ensemble algorithms.

## Recommendations for Future Study
Explore additional ensemble methods such as XGBoost or Gradient Boosting for better performance.
Address the class imbalance issue more effectively with techniques like SMOTE or undersampling.
Incorporate feature engineering to include new derived insights.
Technologies Used
Python: Scikit-learn, Pandas, NumPy, Matplotlib
Machine Learning Models: Decision Tree, Random Forest
Evaluation Metrics: Accuracy, Precision, Recall, F1-Score

## License
This project uses data licensed under the Creative Commons Attribution 4.0 International License. Proper credit is provided to the data owners.

## Contact
For questions or contributions, feel free to reach out:
Name: [Opeyemi Olalekan]
LinkedIn: [www.linkedin.com/in/opeyemiolalekan]
Email: [Olalekanopeyemi@ymail.com]
