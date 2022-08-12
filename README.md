# Movie-Analysis-
Movie Analysis using Linear Regression Methods
This analysis is focused on modeling and predicting what factors lead to success for Western films in the United States.
Using RStudio, I was able to conduct exploratory data analysis and determine whether the variables I investigated satisfied the conditions for Multiple Linear Regressiong modeling ---
1. Linear relationships between the explanatory and response variable
 - Assessed using a scatter plot of the numerical variables being modeled 
2. Nearly normal residuals
 - Assessed using a histogram of the residuals as well as a qqplot
3. Constant variability of residuals
 - Assessed using a residuals chart plotted against fitted values

After concluding a linear relationship was present between the two variables, the null hypothesis was rejected and a model was fitted via parsimonious model selection. 
- p values were assessed from each model to obtain the highest R^2 value for the model. 

The final model of predicting audience scores for a given movie included the following variables:
- IMDB rating
- Critic score on Rotten Tomatoes
- Genre
A final R^2 value of 0.7643 was obtained. 

The model was then used to predict the audience score of a movie not in the original data set. The model predicted an audience score value within the 95% confidence interval. 
