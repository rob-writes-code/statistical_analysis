# Statistical Analysis

An exploration of different datasets using statistical methods and Python data science libraries.

## Contents

1. [**Descriptive Statistics**](#descriptive-statistics)
1. [**Simple Linear Regression**](#simple-linear-regression)
1. [**Multiple Linear Regression**](#multiple-linear-regression)
1. [**Logistic Regression**](#logistic-regression)
1. [**Time Series Decomposition**](#time-series-decomposition)
1. [**Clustering**](#clustering)

### Descriptive Statistics

An exploration of a star dataset used for stellar classification using the Python `pandas` library.

[Descriptive Statistics - A Sample of the Stars](/notebooks/descriptive_stats.ipynb)

### Simple Linear Regression (SLR)

A small dataset containing salary information of employees at a company is explored in this section using simple linear regression.

I make my initial explorations using `pandas` and then plot a scatter graph and line of best fit using `matplotlib`.

I then create a statistical model using the Object Modelling System (OMS) from `statsmodels`. I test the validity of this stats model using a machine learning module: `sklearn`.

Finally, I use this model to make a prediction on salary based on number of years worked at the company.

[Single Linear Regression - Salaries](/notebooks/simple_linear_regression.ipynb)

### Multiple Linear Regression (MLR)

Here, I use MLR to analyse a dataset containing information about cars.

Using `pandas`, `matplotlib` and `seaborn`, I isolate the independent variables which most strongly influence the price of a car.

I then test for collinearity and use the results from these tests to refine my statistical model.

Finally, I use `sklearn` to validate my model, concluding that engine size and horsepower are the two most influential factors when predicting price.

[Multiple Linear Regression - Cars](/notebooks/multiple_linear_regression.ipynb)

### Logistic Regression

DESC HERE

### Time Series Decomposition

A breakdown of French stock market data over time, separated into four underlying factors: trends, seasonal, residual and noise.

[Time Series Decomposition](/notebooks/time_series_decomposition.ipynb)

### Clustering

DESC HERE

<hr>

Licensed under MIT.

