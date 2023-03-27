# American Express Default Prediction

### ABOUT THIS PROJECT
#### This project was based off of an old Kaggle competition. My professor for a university course called 'INTERMEDIATE BUSINESS APPLICATIONS OF ANALYTICS' let us choose any competition that required machine learning to demonstrate our knowledge of logistic regression, linear regression, KNN, and SVM models. My partner and I choose the American Express Default Prediction which would use a logistic regression for the predictive model.

### THE GOAL
#### To predict the percent of American Express customers would fulfill their payments and the percent of customers who would NOT (bceoming subject to a default event). Y = target (0 = paid, 1 = default event).

### CHALLENGES & OTHER COMMENTS
#### The most difficult part of this project was cleaning the data. But! We knew exactly what steps we neded to take being: 1) removing variables that seemed unimportant/less impactful to the predictive model, 2) deleting null values in the columns (aka X variables), 3) encoding variables that we were told were categorical, and 4) running a correlation matrix to further narrow down the variables to use for the model. (Note: After dropping the null values, it turned out that none of the categorical variables were left so we did not have to encode them.) However, my partner's computer could not run a file this large, and my computer struggled as well so we settled on using a sample size of 1,000,000 rows for the predictive model. Of course, this isn't ideal for calculating the accuracy because the actual datset had 5.5 million rows, and we only used 18% of that. In the future, I would go back, create a program that randomly select 25% of the data, and then run a logistic regression model multiple times (as it would select different rows each time) in order to gain a beter prediction. 

### OTHER
#### Tools used: Python (via Jupter Notebooks)
#### Dataset information: csv file containing American Express customer data
#### Link to source of dataset and the competition's instructions: https://www.kaggle.com/competitions/amex-default-prediction/data
