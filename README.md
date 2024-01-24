# SHAPEAI BOTCAMP ON PYTHON AND MACHINE LEARNING
Hi I made this project during the 7 Days Bootcamp, conducted by <b> SHAPEAI
</b>.
The instructor during the session was Mr. Shaurya Sinha (Data Analyst Intern at Jio). I got to
learn a lot during these 7 days and it was an amazing experience learning with SHAPEAI. <br><br>Here's the link for you to watch the sessions as well<br>
<a href="https://www.youtube.com/playlist?list=PL7zl8TDRnbulNEA-59W7wWgCWE8LEOD6h"> <img src="https://github.com/ShapeAI/PYTHON-AND-DATA-ANALYTICS/blob/main/YOUTUBE%20THUMBNAIL-5.png"> </a>
<br>I got to have hands on experience on:
<li>Python
<li>Machine Learning

# Regression model and analysis
In multiple regression, we predicting dependent variable from two or more independent variables e.g. predicting height from weight and age. Linear regression implies that the relationship between the dependent variable and independent variables is linear and thus can be described by a linear plane known as the regression plane. We are in the process of finding a regression plane that fits the maximum number of data points.

**MLR MODEL**

Objective: Predict the dependent variable Yi

Model structure: Yi=β0 + β1XI + β2X2 + ...  βKXK + εi where β0 (y-intercept/constant) and βK (slope) are population regression coefficients and εi is the prediction error (prediction does not match with the actual)

Model parameters: sample regression coefficients b0, b1... bk

Model hyperparameters: Mean square error

Methods to estimate model parameters: Ordinary Least square (Minimise error function)

Model assumptions: Relationship between dependent and independent variables is linear, No correlation (a measure of the relationship between two variables derived from covariance) between errors & between error and independent variables, all errors have equal variances, errors follow a normal probability distribution, independent variables are not collinear (no multicollinearity)
  
**USE CASE**

The boston dataset is builtin in sklearn library. There are 13 independent features. The model is evaluated on MSE and R square metrics. 

**RESULTS**

Duplicate values: None
Missing value: None
Multicollinearity: Yes. 
Regression coefficients:
[ 3.85906801e+00  6.81446545e-03 -1.50026956e+00 -4.86738066e-01
 -1.01775264e+00 -1.10716124e-02 -1.21310401e-01  2.51124642e+00
 -1.62312529e+01 -9.98516565e-03  4.44664254e-02  1.13416945e-02
  2.42143466e-01]

y-intercept: 37.937107741832705

prediction on test data (first 12 values)
[24.9357079  23.75163164 29.32638296 11.97534566 21.37272478 19.19148525
 20.5717479  21.21154015 19.04572003 20.35463238  5.44119126 16.93688709]
 
MSE is 27.19
R square is 0.52921.

The <a
href=
"https://github.com/tissyamalik/shapeai-mlr-boston-house-pricing/blob/main/predict-price.ipynb">python code</a> python code is available on GitHub
