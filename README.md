# Interactions-in-Regression-Fixed-Effects-in-Regression-and-Logistic-Regression

Using the sales.csv, written the code to show effects of interactions, if any, on the linear regression model to predict the total_sales for a new area using given sales from three areas. Developed a full Logistic Regression Model using customer.csv whether the customer will purchase the product or not. Also, trained trimmed logistic regression models (Trimmed over features in the data). Computed the "in-sample R2" (pseudo) for the models trained and compared the models based on this metric.
For the Logistic Regression models trained above, picked the best model wrt to the in-sample R2 and interpreted model’s coefficients (For example, what effect does a positive or negative coefficient have on the model and so on).
Plotted the interactions of the ‘Age’ and ‘Gender’ features with the ‘Purchased’ output. 

# Linear Regression Analysis using sales.csv
In this analysis, we aim to explore the effects of interactions, if any, on the linear regression model to predict total sales for a new area using given sales from three areas. We use the sales.csv file, which contains the sales data for three different areas.

To start the analysis, we load the data and fit a linear regression model using the statsmodels package in Python. We then check for the significance of the interaction terms and plot the results.



# Logistic Regression Model using customer.csv
In this part of the analysis, we develop a full logistic regression model using the customer.csv file to predict whether a customer will purchase the product. We also train trimmed logistic regression models by eliminating some features from the dataset. We compute the in-sample R2 (pseudo) for all models and compare them based on this metric.

We use the sklearn package in Python for logistic regression and perform feature selection using the SelectKBest function. Please see the customer_logistic_regression.ipynb notebook for a detailed analysis and code.

Model Interpretation and Evaluation
After training the logistic regression models, we pick the best model based on the in-sample R2 and interpret the model's coefficients. We explain the effect of each feature on the model and give our reasoning behind including or excluding interaction terms.

We also discuss why accuracy may not be a good metric to judge the model's performance and suggest alternatives. Please see the customer_logistic_regression.ipynb notebook for a detailed analysis and code.

# Interaction Plots
We create interaction plots for the Age and Gender features with the Purchased output. These plots help us visualize the interaction effects of the features on the output variable.

Please see the interaction_plots.ipynb notebook for the plots and code.

Effect of Income and Change in Savings on Likelihood of Buying a House
We analyze the effect of Income and Change in Savings on the Likelihood of Buying a House using three different plots. For each plot, we decide whether the regression equation should include the interaction terms between Income and Average Savings or not and give our reasoning.

Please see the house_buying.ipynb notebook for a detailed analysis and code.
