### Bank Customer Churn Analysis: Project Report

This project analyzed a dataset of 10,000 European bank customers to understand factors contributing to customer churn and develop predictive models. The analysis aimed to identify characteristics of churners, explore demographic patterns, and segment customers.
Methodology


- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) using Python (Pandas, Matplotlib, Seaborn)
- Statistical analysis of customer attributes
- Machine learning models: Logistic Regression and Random Forest for churn prediction
- K-means clustering for customer segmentation


Key Findings

1. Churn Characteristics

Churners and non-churners showed similar average credit scores (650.69 vs 650.40)
Slight differences in average age (churners: 38.79, non-churners: 39.06)
Minimal difference in average tenure (churners: 5.03, non-churners: 5.00)
Churners had slightly higher average estimated salary (€100,522 vs €99,662)

2. Demographic Insights

Gender distribution: 54.58% Male, 45.42% Female
Geographical distribution: Germany had the highest representation
Age and credit score distributions were relatively similar across geographies

3. Geographical Differences

Germany had the highest average credit score (651.48) and age (39.77)
French customers had the lowest average credit score (647.86) and age (38.05)
FRA customers had the highest average estimated salary (€101,251)

4. Customer Segmentation
K-means clustering revealed 5 distinct customer segments:

Cluster 0: High tenure, medium credit score, medium age
Cluster 1: High tenure, high credit score, young
Cluster 2: Medium tenure, medium credit score, oldest
Cluster 3: Low tenure, medium credit score, young, lowest salary
Cluster 4: Low tenure, high credit score, young, highest salary


5. Predictive Modeling
Logistic Regression and Random Forest models were developed
Best performing Random Forest model:

Parameters: max_depth: None, min_samples_split: 6, n_estimators: 95
Accuracy: 51% (slight improvement over baseline)




Conclusions


Churners and non-churners have subtle differences in their characteristics
Age, credit score, and estimated salary vary across geographical regions
Customer segments with distinct profiles were identified
Predicting churn remains challenging, suggesting the need for additional features or advanced modeling techniques


Recommendations


Focus retention efforts on identified high-risk segments
Investigate additional factors that may influence churn
Consider developing tailored services for different customer segments
Explore more advanced machine learning techniques to improve predictive accuracy
