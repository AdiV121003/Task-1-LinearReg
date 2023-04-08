# Title - Prediction using Simple Linear Regression in R
# Problem - Predicting student's scores by the hours they study.
# Using Simple Linear Regression to solve Task - 1 of my TSF Internship in Data Science & Business Analytics.  
Independent Variable - Hours 
Dependent Variable - Scores 
Programming language - R
Software - RStudio
# Both are numeric values with one dependent variable so linear regression can be applied here. 
Read CSV file using read.csv function

<img width="502" alt="GH1" src="https://user-images.githubusercontent.com/123164713/230734925-ecc06df2-00b3-4287-b6c5-742bf9e2994a.png">

View and summarise the CSV file contents. 

Using the lm() function, we fit a linear model on the dataset. 
Summarising the model gives us it's Coeffecients, Residuals, R squared value, P value, T and F test statistics and Slope and Intercept of regression line. 

<img width="502" alt="GH2" src="https://user-images.githubusercontent.com/123164713/230735036-b6e41cc7-3377-4a3f-98d4-7ef964e889b0.png">

Plot the linear model using plot() function and add it's regression line using abline() function
<img width="462" alt="GH3" src="https://user-images.githubusercontent.com/123164713/230735111-3829eb33-923b-4120-8f37-59dd88f58672.png">

Question in internship Task - 1: Predict the score if student studies for 9.25 hours a day? 
Store the hours whose score has to be predicted in a dataframe.
Here i used as.data.frame() function to directly store the values in data frame named "p"
Name column names of data frame as "Hours" using colnames() function
Use predict() function to get the prediction of Scores if Hours of study is 9.25. 
<img width="476" alt="GH4" src="https://user-images.githubusercontent.com/123164713/230735201-4c52fd89-6d25-453d-b4f3-f10a4025dba9.png">


