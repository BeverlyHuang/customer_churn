# Customer Churn Prediction

By Beverly Huang

### Goal
* Predicting customer churn based on available communication records
* Enabling the company to take actions to retain customers

### Conclusion
In this project, we build classification machine learning models in Python for customer churn prediction. Four classification models are evaluated in terms of accuracy, precision and recall. From business impact viewpoint, we choose recall as the most important metric.

The modeling and evaluation results show that Random Forest performs better than Logistic Regression and SVM in terms of recall.
Using this best model, we identify three important factors: Number of Email Messages, Total Day Calls, and Total International Charge.
Through data exploration and visualization, it is suggested that customers sending more email messages, giving more day calls and having higher international charge are more likely to churn.

Recommendations:
* It is very likely that customers who want to churn increase usage by sending more email messages and giving more day calls before the packages expired. Therefore, the company should frequently monitor customer usage data, especially on Number of Email Messages and Total Day Calls, and use the best model to identify who is likely to churn. Then the company can retain customers by giving customized packages.
* Customer churn is also positively correlated with Total International Charge. Thus, lowering the price when the customer is likely to churn is another way to retain customers and build customer relationship.
