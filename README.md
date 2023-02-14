# Linear-Regression

Linear Regression is one of the most fundamental algorithms in the Machine Learning world. It is the door to the magical world ahead. But before proceeding with the algorithm.Linear Regression is one of the most fundamental and widely known Machine Learning Algorithms which people start with. Building blocks of a Linear Regression Model are:

1. Discreet/continuous independent variables

2. A best-fit regression line

3. Continuous dependent variable. i.e., A Linear Regression model predicts the dependent variable using a regression line based on the independent variables. The equation of the Linear Regression is:

                                         Y=a+b*X + e 
Where, a is the intercept, b is the slope of the line, and e is the error term. The equation above is used to predict the value of the target variable based on the given predictor variable(s).

## Simple Linear Regression
Simple Linear regression is a method for predicting a quantitative response using a single feature ("input variable"). The mathematical equation is:

                                           𝑦=𝛽0+𝛽1𝑥
What do terms represent?

1. 𝑦 is the response or the target variable
2. 𝑥 is the feature
3. 𝛽1 is the coefficient of x (slope)
4. 𝛽0 is the intercept
5. 𝛽0 and 𝛽1 are the model coefficients. To create a model, we must "learn" the values of these coefficients.

## Multiple Linear Regression
Till now, we have created the model based on only one feature. Now, we’ll include multiple features and create a model to see the relationship between those features and the label column. This is called Multiple Linear Regression.

                                          𝑦=𝛽0+𝛽1𝑥1+...+𝛽𝑛𝑥𝑛
Each 𝑥
 represents a different feature, and each feature has its own coefficient. In this case:

𝑦=𝛽0+𝛽1×𝑇𝑉+𝛽2×𝑅𝑎𝑑𝑖𝑜+𝛽3×𝑁𝑒𝑤𝑠𝑝𝑎𝑝𝑒𝑟
Let's use Statsmodels to estimate these coefficients
