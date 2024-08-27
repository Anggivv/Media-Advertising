# Media Advertising

## Introduction
Advertising plays a crucial role in influencing consumer purchasing decisions. Companies often invest significant amounts of money in various advertising channels such as TV, radio, and newspapers to boost product sales. However, one of the main challenges is understanding how effective each advertising channel is in driving sales. Analyzing advertising data can provide insights into the relationship between advertising spend and sales, helping companies allocate their budgets more efficiently.
This project aims to analyze advertising data to determine how much each media channel (TV, radio, newspaper) contributes to product sales. By utilizing linear regression techniques, we can predict sales based on advertising expenditure across these media channels.

## Goal
* Understand the relationship between advertising spend on TV, radio, and newspapers, and product sales.
* Build a predictive model that estimates sales based on the advertising budget across the three media channels.
* Identify which advertising medium is the most effective in driving sales.

## Step-by-Step Process
#### 1. Import Data:
* Importing the dataset into the analysis environment using libraries like Pandas. This is the initial step to start exploring and analyzing the data.

#### 2. Least Squares Line:
* A method to determine the best-fit regression line that minimizes the squared errors between the actual values and the values predicted by the line.

#### 3. Polyfit:
* A function from NumPy for polynomial fitting, often used to find the best line or curve that represents the relationship between variables.

#### 4. Train-Test Split:
* Splitting the dataset into two parts: one for training the model (train) and one for testing its performance (test), to ensure the model works well on unseen data.

#### 5. Create Model:
* Building a predictive model using algorithms like linear regression, based on the training data.

#### 6. Test the Model:
* Evaluating the model's performance using the test data, with metrics like R-squared or Mean Squared Error (MSE).

#### 7. Coefficients:
* Coefficients in a regression model describe how much the dependent variable (output) changes when there is a change in the independent variable (input).

## Conclusion:
This advertising data analysis provides valuable insights into the effectiveness of various media channels in driving product sales. The linear regression model results can help identify that certain media, such as TV or radio, may have a more significant impact on sales compared to newspapers. These conclusions can guide companies in optimizing their advertising budget allocation to maximize sales. Future steps could involve testing the model with a larger dataset or incorporating additional factors such as seasonality, demographics, and market trends to further improve prediction accuracy.
