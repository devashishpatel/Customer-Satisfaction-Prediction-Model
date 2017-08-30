# Customer Satisfaction Prediction Model

## Objective:
Building a Linear Regression Model to predict customer satisfactions as well as to identify factors that lead to increasing customer satisfaction for use in differentiated marketing campaigns

## Background:
Management of a company was interested in better predicting the satisfaction levels of its customers. If successfull, the model could provide a better foundation for their marketing effors. Currently, the marketing campaigns done by the company did not seem to get the appropriate response from their customers. With the help of the Linear Regression Model, the company wanted to pin-point the exact factors that affected customer satifaction so that it could tailor the marketing campaigns accordingly.

## Dataset:
The Dataset provided by the company had 13 independent variables representing the perception of the company's performance. They were:
* X6: Product Quality
* X7: E-Commerce
* X8: Technical Support
* X9: Complaint Resolution
* X10: Advertising
* X11: Product Line
* X12: Salesforce Image
* X13: Competitive Pricing
* X14: Warranty and Claims
* X15: New Products
* X16: Ordering and Billing
* X17: Price Flexibility
* X18: Delivery Speed
The dependent variable was X19: Customer Satisfaction.

## Linear Regression Model and Results:
The Entire process - code as well as analysis - of Building the Linear Regression Model is detailed in the [R Notebook](https://github.com/devashishpatel/Customer-Satisfaction-Prediction-Model/blob/master/Customer%20Satisfaction%20Prediction%20Model-%20Linear%20Regression.ipynb).

The Linear Regression Model that was deemed valid as well as having the highest predictive power is:

Y = -1.151 +0.319X9 + 0.369X6 + 0.775X12 + (-0.417)X7 + 0.174X11

With this equation the expected customer satisfaction level for any customer could be calculated if that customers evaluation of the company's perception was know with an accuracy of 78%

To identify the key factors that aid in improving customer satisfaction, we find the model with standardized Beta Coefficients and rank the factors according to their importance below:

1. X12: Salesforce Image [Beta Coefficient: 0.697]
2. X6: Product Quality [Beta Coefficient: 0.432]
3. X9: Complaint Resolution [Beta Coefficient: 0.324]
4. X7: E-Commerce [Beta Coefficient: 0.245]
5. X11: Product Line [Beta Coefficient: 0.192]
This indicates that Sales Force Image has 6 times the impact on Customer satisfaction in comparison to the Product Line.

Management of the company now has an objective analysis that confirms not only the specific influences of the key variables but also the perceptual dimensions that must be considered in any form of business planning aimed at customer satisfaction.
