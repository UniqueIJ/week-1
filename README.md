DSEAFRICA WK 1: PROJECT QUESTION:
Let’s say you’re a Product Data Scientist at Instagram. How would you measure the success of the Instagram TV product?
As a Product Data Scientist at Instagram, measuring the success of the Instagram TV product would involve a combination of quantitative and qualitative metrics.
1.	User Engagement:
User Retention: Monitor the number of users who continue to use Instagram TV over time. A high retention rate indicates that users find value in the product.

Time Spent: Measure the average time users spend on IGTV daily or weekly. An increase in time spent could signify engagement.

2.	User Growth:
User Acquisition: Track the number of new users signing up for IGTV

Active Users: Analyze the number of active users on IGTV. Consistent growth in active users indicates product success.

Inactive Users: Analyze the number of active users on IGTV, inconsistent growth in active users indicates product success.
3.	Content Metrics:
Content Uploads: Measure the rate at which users and creators upload new content. More content signifies a healthy environment.

4.	Advertisement
Channels of advertisement of the Instagram TV product for a pull of traffic to the website

Practically, I will measure the performance of the success of the Instagram Tv product by building a predictive model that creates data driven solutions that addresses:
1.	An understanding of the business problem 
-	Define the goal of the Instagram TV product to end users/customers
-	Determine how the Instagram TV product support the users goal (meet their needs)
-	Define the bench marks/ KPI’s to measure product performance of the Instagram TV
-	How  do we improves  the Instagram brand to retain customer patronage 
2.	Collection of Data 
•	number of users 
•	Time spent /duration
•	Frequency of logging in
•	Age range
•	User Content interests 
•	Number of New Users sign up
•	Number of Old users Log in
•	Number of Active users
•	Number of Inactive users
3.	Data cleaning, processing and determination of KPI’s 
4.	Exploratory data analysis
5.	Model building and Graphical visualization evaluation
6.	Communication of model results against set KPI’s



DSEAFRICA WK 2 PROJECT:
Question: Let’s say we want to build a model to predict booking prices on Airbnb. Between linear regression and random forest regression, which model would perform better and why?
The selection between Linear regression and Random Forest regression for predicting booking prices on Airbnb depends on various factors such as:
•	Nature of data
•	Relationship the features and the target variable
•	Amount and quality of data available
•	complexity of the relationship between the input features and the booking prices on Airbnb,
•	The desired level of interpretability versus predictive performance
Thus, in comparing both models,

Random forest regressions: discretize continuous variables based on decision trees and can split categorical and continuous variables.
Random forest regression is based on bagging, an ensemble learning technique that combines multiple decision trees to make predictions and are capable of capturing complex interactions and non-linear patterns in the data, making them more flexible than linear regression. It can handle large number of feature interactions and variable importance.
However, the interpretability of random forest models is generally lower than that of linear regression models. It can be challenging to understand the individual impact of each feature on the predictions.

Linear regression: is the standard regression technique that remote relationships are modeled using a linear predictor function, y = Ax + B.
Linear regression assumes a linear relationship between the features and the target variable as they represent the direction and magnitude of the impact of each feature on the target variable.
However, linear regression may not capture complex non-linear relationships in the data, leading to reduced predictive performance.

To determine the best model in the context of predicting booking prices on Airbnb, considering the complexity and non-linear nature of the data, random forest regression model is likely to perform better than a simple linear regression model. 
Reason: Random forests capture the interactions between various features such as location, listing amenities, and availability, which may have non-linear effects on booking prices. 
•	They can also handle categorical variables and missing data more effectively. 
•	However, it captures complex and non-linear relationship input features and the target variable.
•	Robust to outliers and not impacted by noise due to its ensemble nature (combining multiple decision trees).
•	Better performance with categorical data.
•	Yields higher accuracy

