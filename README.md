What is the difference between supervised learning and unsupervised learning?

Supervised learning is the concept where you have input vector / data with corresponding target value (output).
On the other hand unsupervised learning is the concept where you only have input vectors / data without any corresponding target value.
In supervised learning, the algorithm “learns” from the training dataset by iteratively making predictions on the data and adjusting for the correct answer.
While supervised learning models tend to be more accurate than unsupervised learning models, they require upfront human intervention to label the data appropriately. For example, a supervised learning model can predict how long your commute will be based on the time of day, weather conditions and so on. 
But first, you’ll have to train it to know that rainy weather extends the driving time.

Unsupervised learning models, in contrast, work on their own to discover the inherent structure of unlabeled data. 
Note that they still require some human intervention for validating output variables. 
For example, an unsupervised learning model can identify that online shoppers often purchase groups of products at the same time. 
However, a data analyst would need to validate that it makes sense for a recommendation engine to group baby clothes with an order of diapers, applesauce and sippy cups.


Data Science Case study -

https://workera.ai/resources/data-science-case-study-interview



What is the random forest algorithm?

Random forest is a Supervised Machine Learning Algorithm that is used widely in Classification and Regression problems. 
It builds decision trees on different samples and takes their majority vote for classification and average in case of regression.

What is the decision tree algorithm? 

A decision tree is a type of supervised machine learning used to categorize or make predictions based on how a previous set of questions were answered. 
The model is a form of supervised learning, meaning that the model is trained and tested on a set of data that contains the desired categorization.

What is the logistic algorithm?

Logistic regression is a supervised learning algorithm used to predict a dependent categorical target variable. 
In essence, if you have a large set of data that you want to categorize, logistic regression may be able to help.
Logistic regression is a statistical analysis method to predict a binary outcome, such as yes or no, based on prior observations of a data set. 
A logistic regression model predicts a dependent data variable by analyzing the relationship between one or more existing independent variables.

What are the pros and cons of a linear model?


A linear model has a number of advantages over other models. First, it is very easy to understand and explain. Second, it is easy to use and implement. Finally, linear models are very flexible and can be easily extended to more complex situations.
However, linear models also have a number of disadvantages. First, they can be inaccurate in predicting outcomes. Second, they can be too simplistic and may not capture all the important relationships in the data. Finally, linear models can be sensitive to outliers and can be easily affected by them.

How would you use SQL to find all duplicates in a data set?


SELECT * 
FROM data 
GROUP BY data 
HAVING COUNT(*) > 1
