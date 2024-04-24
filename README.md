# Project Name
> This assignment is a programming assignment wherein you have to build a regression model using regularisation for US-based housing company named Surprise Housing in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market.
- The model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- The company wants to know:
  - Which variables are significant in predicting the price of a house, and
  - How well those variables describe the price of a house.
- Data used is collected by Surprise Housing from the sale of houses in Australia.


## Conclusions

- There are no non linear features, so it is a Linear Regression problem.
- Sales Price (Target) seems to  dependent on Area of the house (basement area, 1st floor area, 2nd floor area, gound living area, garage area, etc.)
- All categorical variables seem to have some kind of impact
- Good Quality of the room, Recently built or remodeled houses have higher sales prices
- Amenities and features around the house also has significance on Sales Price.
- Plotting histogram of errors obtained, a normal distribution is obtained this means there is a linear relationship between demand and set of predictor variables
- Scatter plot for actual demand and calculated demand shows there is homoscedasticity, i.e. error terms have constant variance
- Lasso Regression seems to have lesser values for coefficint than linear regressiona and Ridge.
- By reguraliazing and removing unrequired variables Lasso is giving a good performance as compared to Ridge
- Lasso is the better model because it provided feature selection and better accuracy than ridge.
- Also due to regularization Lasso is more robust than vanilla Linear Regression.

## Technologies Used
- python     - version 3.11.8
- pandas     - version 2.1.4
- numpy      - version 1.26.4
- seaborn    - version 0.13.2
- matplotlib - version 3.8.4
- sklearn    - version 1.2.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was part of Upgrad's Exploratory Data Analysis Project.
- References if any...
  - [Seaborn Documentation](https://seaborn.pydata.org/api.html)
  - [Matplotlib Documentation](https://matplotlib.org/stable/api/index.html)
  - [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/reference/index.html)
  - [sklearn](https://scikit-learn.org/stable/modules/classes.html#)


## Contact
Created by [@tritammohanty] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->
