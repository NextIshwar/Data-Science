# Linear Regression
* In oredr to find the best Linear Regression model we have to find $R^2$
* $R^2$ is **1-RSS/TSS**, $R^2$ is (variability in y expained by mmodel/total variability in y)
* RSS => Residual Squared error. ( The value of sum of squares of predicted value and actual value i.e y-yi where y is predicted value and yi is the actaul value ) 
* TSS => Total Sum of Squares ( The value sum of squares of average value and actaul value i.e  $\sum_{i=1}^{n} (y_i$-$\bar{y}$ )^2. Here $\bar{y}$ is average value.
* Higher the $R^2$ value the model becomes better
* The value of $R^2$ lies between 0 and 1, where 1 implies that the variance in the data is being explained by the model, and 0 implies that none of the variance values is being explained by the model. Obviously, it is very difficult to achieve either of the extreme values.
* Suppose that you run a linear regression on the data, where you have X as the independent variable and y as the target variable. You find that the correlation between y and X is -0.92. What can you say in this situation?
The absolute value of the correlated coefficient is very high. The negative sign just implies that X and y are negatively correlated. Hence, they have a very strong negative correlation.
* **Variance** is the measure of dispersion in a data set. In other words, it measures how spread out a data set is. It is calculated by first finding the deviation of each element in the data set from the mean, and then by squaring it.
* **What are the assumption of Linear Regression?**
  1. There is a linear relationship between X and Y.
  2. Error terms are normally distributed with mean zero(not X, Y).
  3. Error terms are independent of each other.
  4. Error terms have constant variance (homoscedasticity).
  5. 