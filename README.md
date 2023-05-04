Download Link: https://assignmentchef.com/product/solved-cs4375-homework-2-simple-linear-regression
<br>
Simple Linear Regression

<ol>

 <li>Load library ISLR. Use the names() function and the summary() function to learn more about the Auto data set. Divide the data randomly into train and test sets, with 75% train. Use seed 1234 for reproducibility.</li>

 <li>Use the lm() function to perform simple linear regression on the train data with mpg as the response and horsepower as the predictor. Use the summary() function to evaluate the results. Calculate the MSE.</li>

 <li>(No code) Write in the white text area:

  <ol>

   <li>Write the equation from the model , filling in the parameters w, b</li>

   <li>Is there a strong relationship between horsepower and mpg?</li>

   <li>Is it a positive or negative correlation?</li>

   <li>Comment on the RSE, R^2, and F-statistic</li>

   <li>Comment on the MSE</li>

  </ol></li>

 <li>Plot train$mpg~train$horsepower and draw a blue abline(). Comment on how well the data fits the line. Predict mpg for horsepower of 98. Comment on the predicted value given the graph you created.</li>

 <li>Test on the test data using the predict function. Find the correlation between the predicted values and the mpg values in the test data. Comment on the results. Calculate the mse on the test results. Compare this to the mse for the training data.</li>

 <li>Plot the linear model in a 2×2 arrangement. Do you see evidence of non-linearity from the residuals?</li>

 <li>Create a second linear model with log(mpg) predicted by horsepower. Compare the summary statistic R^2 of the two models.</li>

 <li>Plot the function with an abline(). Comment on how well the line fits the data.</li>

 <li>Predict on the test data using lm2. Find the correlation of the predictions and log() of test mpg. Compare this correlation with the correlation you got for lm1. Calculate the MSE for the test data on lm2 and compare to lm1.</li>

 <li>Plot the second linear model in a 2×2 arrangement. How does it compare to the first set of graphs?</li>

</ol>

Multiple Linear Regression

<ol>

 <li>Produce a scatterplot matrix which includes all the variables in the data set using the command “pairs(Auto)”. List any possible correlations that you observe, listing positive and negative correlations separately, with at least 3 in each category.</li>

 <li>Display the matrix of correlations between the variables using function cor(). You should exclude the “name” variable since is it qualitative. Write the two strongest positive correlations and their values in the text area. Write the two strongest negative correlations and their values in the text area.</li>

 <li>Convert the origin variable to a factor. Use the lm() function to perform multiple linear regression with mpg as the response and all other variables <strong>except name</strong> as predictors. Use the summary() function to print the results. Which predictors appear to have a statistically significant relationship to the response?</li>

 <li>Use the plot() function to produce diagnostic plots of the linear regression fit. Comment on any problems you see with the fit. Are there any leverage points? Display a row from the data set that seems to be a leverage point.</li>

 <li>Use the * and + symbols to fit linear regression models with interaction effects, choosing whatever variables you think might get better results than your model in step 3 above. Compare the summaries of the two models, particularly R^2. Run anova() on the two models to see if your second model outperformed the previous one.</li>

</ol>


