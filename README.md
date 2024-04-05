Nowadays covid-19 is the talk of the town. Our project is based on a dataset named “COVID Dataset”. I work on different types of models like Linear Regression. We analyze Lab Test, Confirmed Case and Death
Case of total 626 days (2020-April-04 to 2021-December-20) data. As our Intermediate Progress we use different types of Exploratory Data Analysis (EDA) tools for analyzing these data such as the growth and
decay of covid-19 etc. In the Exploratory Data Analysis we have divided the data analysis into two types:
1) Univariate Analysis : lab test, confirmed case, death case are analyzed one by one in separate “Distplot”, “Line Plot” and “Box Plot” and analyze the kurtosis, skewness, IQR and others.
2) Multivariate Analysis: For the multivariate analysis we plot lab test vs confirmed case and death case as HUE. Also we draw the comparison graph of lab test vs confirmed case and confirmed case vs death case.
We also added weekly and monthly comparisons separately for lab test, confirmed case and death case. We used 5 regression models and two classification model.
For the regression model we implemented Linear Regression, Polynomial Regression, Lasso Regression, Ridge Regression, Elastic-net Regression.
As for the classification model, we implemented Logistic Regression and linear SVC (Support vector classifier). In the performance analysis We can say that the polynomial regression model gives the highest accuracy
of 96% compared to other regression and classification models like linear regression (94%), lasso regression (94%), ridge regression (94%), elastic net regression (94%), linear SVC (86%), Logistic regression (83%).
Note that, Logistic regression and SVC are classification models.
