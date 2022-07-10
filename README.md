
# Rossmann Sales Prediction

In any supply chain, an ability to accurately predict sales has a direct impact on its operating expenditure. Being able to accurately predict the sales validates understanding of the factors influencing it. A good understanding of these underling factors enable in taking “decisions” that can improve sales. 
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied

### Keywords: 
Sales Prediction, NumPy, scikit-learn, machine-learning, RMSE, Linear regression, lasso regression ,decision tree
## Introduction
In the following project, we have applied machine learning to a real world problem of predicting retail stores sales. Such predictions help store managers in creating effective staff schedules that increase productivity. We used the popular open source programming language Python and used its libraries like NumPy, scikit-learn, pandas , matplotlib for modelling, analysis and prediction and visualization. We used feature selection, model selection to improve our prediction result. In view of the nature of our problem, Root Mean Square Error (RMSE) is used to measure the prediction accuracy. 


## Problem Statement


## Dataset
[Dataset from Rossmann stores.](https://drive.google.com/file/d/1nCuTVec4BuoF-QgUnWER2RtG0cX_8lLN/view?usp=sharing)



## Algorithm Used
We were successful in building aMachine Learning models that will forecast future sales. Various methods of sales forecasting model that we will use in our project includes:

1.	Linear Regression (OLS) 

Ordinary Least Squares  is a method which helps us estimate the unknown parameters in the Linear regression model. How does it estimate the parameters though? Well, it estimates the parameters by minimizing the sum of squared residuals. The way it does this is , it draws a line through the data points such that the squared differences between the observed values and the corresponding  fitted value is minimized.

Linear regression attempts to model the relationship between two variables by fitting a linear equation to observed data. ... A linear regression line has an equation of the form Y = a + bX, where X is the explanatory variable and Y is the dependent variable.

2.	 Lasso Regression
Basically, Lasso makes leaps in the most optimally calculated direction without overfitting the model. 
Normalize all values to have zero mean and unit variance.
Find a variable that is most highly correlated to the residual. Move the regression line in this direction until we reach another variable that has the same or higher correlation.
When we have two variables that have the same correlation, move the regression line at an angle that is in between (i.e., least angle between the two variables).
Continue this until all of our data is exhausted or until you think the model is big and ‘general’ enough.

Continue and repeat until all predictors are in the model.

3.	 Decision Tree Regression

Decision trees build regression or classification models in the form of a tree structure. It breaks down a dataset into smaller and smaller subsets while at the same time an associated decision tree is incrementally developed. The final result is a tree with decision nodes and leaf nodes. A decision node (e.g., Outlook) has two or more branches (e.g., Sunny, Overcast and Rainy), each representing values for the attribute tested. Leaf node (e.g., Hours Played) represents a decision on the numerical target. The topmost decision node in a tree which corresponds to the best predictor called root node. Decision trees can handle both categorical and numerical data. 

Model Comparison & Selection
There are two popular metrics used in measuring the performance of regression (continuous variable) models i.e MAE & RMSE. 

●	Mean Absolute Error (MAE): It is the average of the absolute difference between the predicted values and observed values.

●	Root Mean Square Error (RMSE): It is the square root of the average of squared differences between the predicted values and observed values.

MAE is easier to understand and interpret but RMSE works well in situations where large errors are undesirable. This is because the errors are squared before they are averaged, thus penalizing large errors.
So, we choose RMSE as a metric to measure the performance of our models.

## Conclusion
●	Rossmann should focus on increasing the promotional offers per quarter for 1,2,3 and can minimize for 2.

●	The most selling and crowded store type is 2

●	Sales is highly correlated to the number of Customers.

●	For all stores, Promotion leads to increase in Sales and Customers both.

●	The stores which are opened during the School Holiday have more sales than normal days.

●	More stores are opened during School holidays than State holidays.

●	Rossman should try to focus on reducing the Promo offers for store type b during StateHolidays as there is no substantial increase in Sales.

●	that people buy more beauty products during a Christmas celebration.

●	Rossmann can divert some of the Promos from being offered on SchoolHolidays to No SchoolHolidays to maximise the Sales revenue. 

●	Absence of values in features CompetitionOpenSinceYear/Month doesn’t indicate the absence of competition as CompetitionDistance values are not null where the other two values are null.

●	After analysing sales using Fourier decomposition, we found that there’s a little seasonality component in the Sales data.

## Reference
1.  Applied Science Article  MDPI
2.  GeeksforGeeks
3.  Wikipedia
4.  DataCamp

## 🚀 About Me


- 👋 Hi, I’m Shahrukh, a curious Data Dcientist
- 👀 I’m currently working on Machine Learning projects.
- 🌱 I’m currently learning various machine learning models and deep learning techniques.
- 💞️ I’m would love to collaborate on Machine Learning projects.
- 📫 How to reach me : khan441shahrukh@gmail.com
- 👀 LinkedIn : https://www.linkedin.com/in/md-shahrukh-khan-49a027172/
