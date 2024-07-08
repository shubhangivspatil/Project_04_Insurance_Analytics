**** Project_04_Insurance_Analytics****


**Final Report: Insurance Analytics and Prediction**

 
 **Project Overview**
 The objective of this project is to leverage advanced analytics techniques, including classification, regression, and clustering, to extract valuable insights from insurance data. 
 By analyzing a comprehensive dataset, the project aims to enhance decision-making processes, optimize risk classification, and improve customer engagement and retention.

 **Data Preprocessing**
 Missing Values: Handled missing values in 'Annual_Income' and 'Changed_Credit_Limit' columns by imputing the mean.
 Categorical Encoding: Used LabelEncoder to transform categorical variables into numerical formats suitable for machine learning models.
 Exploratory Data Analysis (EDA)
 Distribution of Annual Income: Visualized using a histogram, showing a wide range of incomes with a concentration around certain values.
 Correlation Heatmap: Displayed correlations between numeric features, highlighting relationships such as a strong positive correlation between 'Annual_Income' and 'Monthly_Inhand_Salary'.

** Regression Analysis**
 Model: Linear Regression
 Target Variable: Annual Income
 Features: Various factors including age, occupation, and financial indicators.
 Performance Metrics:
 Mean Squared Error (MSE): 7661667.29
 R-squared: 0.9948

 Key Insights: The model explains a significant portion of the variance in annual income, indicating strong predictive power. High R-squared value suggests the model fits the data well.
 **Classification Analysis**
 Model: Decision Tree Classifier
 
 Target Variable: Credit Score
 Features: Financial and demographic variables excluding 'Credit_Mix' and 'Name'.
 Performance Metrics:
 Accuracy: 75%
 Precision, Recall, F1-score:
 Class 0: Precision: 0.70, Recall: 0.70, F1-score: 0.70
 Class 1: Precision: 0.74, Recall: 0.72, F1-score: 0.73
 Class 2: Precision: 0.77, Recall: 0.78, F1-score: 0.77
 Confusion Matrix: Displayed misclassifications and correct classifications for each class.
 Key Insights: The classifier performs well, particularly for classifying higher credit scores. The accuracy and F1-scores indicate reliable model performance.

** Clustering Analysis**
 
 Model: K-Means Clustering
 Optimal Clusters: 4 (based on the elbow method)
 Cluster Summary:
 Cluster 0: Younger policyholders, high income, numerous bank accounts.
 Cluster 1: Older policyholders, lower income, fewer bank accounts.
 Cluster 2: Younger policyholders, lower income, numerous bank accounts.
 Cluster 3: Older policyholders, high income, fewer bank accounts.
 Visualizations: Scatter plots showing clusters with key features such as 'Age' and 'Annual_Income'.
 
 Recommendations
 Based on Clustering Analysis:

 Cluster 0 (Younger, High Income, Numerous Bank Accounts):

 Target with online and mobile app services.
 Provide premium services and exclusive offers.
 Cross-sell financial products such as loans and credit cards.
 Suggest investment plans and wealth management services.
 Cluster 1 (Older, Lower Income, Fewer Bank Accounts):

 Offer in-person services and personalized advice.
 Offer budget-friendly insurance plans.
 Promote basic financial literacy and savings accounts.
 Provide basic savings and fixed deposit accounts.
 Cluster 2 (Younger, Lower Income, Numerous Bank Accounts):

 Target with online and mobile app services.
 Offer budget-friendly insurance plans.
 Cross-sell financial products such as loans and credit cards.
 Provide basic savings and fixed deposit accounts.
 Cluster 3 (Older, High Income, Fewer Bank Accounts):

 Offer in-person services and personalized advice.
 Provide premium services and exclusive offers.
 Promote basic financial literacy and savings accounts.
 Suggest investment plans and wealth management services.

**** Conclusion****
 This project successfully demonstrated the application of regression, classification, and clustering techniques to extract valuable insights from insurance data. 
 The analyses provided actionable recommendations for tailored marketing strategies, improved fraud detection, and optimized premium pricing.

 
 **Future work**
 Future work could involve incorporating additional data sources and exploring more advanced machine learning models to further enhance predictive accuracy and customer segmentation.

