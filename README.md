# Practical Application Assignment 5.1:
## Will the Customer Accept the Coupon?

The goal of this project is to distinguish between customers who accepted a driving coupon versus those that did not.

### About the Data
Data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver.

### About the Analysis
The analysis is broken into two parts. The first part is focused on Coupon for Bar then the second part is focused on Coupon for Coffee Shop.

The data cleaning and analysis is done in Python and can be found in file: [prompt.ipynb](prompt.ipynb)

### Findings
The analysis shows that the following features are important in predicting whether a customer will accept a coupon:

 * The more often a customer uses a service, the more likely they are to accept a coupon.
 * Group of Drivers under 30 and go to bar more than once a month and the group of drivers who are not widowed and go to bar more than once a month having adults as passengers are more likely to accept the coupon than the last group.
 * Drivers under 30 and go to bar more than once a month are more numerous therefore are a better target for bar coupon.
 * Drivers who are over 25 and go to Cofee House more than once a month are more likely to accept the coupon than others.
 * Driver with income less than 50K who drives alone are less likely to accept the coupon than others.

### Recommendations
The applied methodologie allow us to quickly identify the acceptance ratio of a selected group of drivers and see some trend.

However I would recommend to use a more robust methodology to predict the acceptance ratio of a coupon. For example, we could use a machine learning algorithm to model the acceptance criteria of a coupon. This would allow to generate tailored coupon to maximise coupon efficiency.
