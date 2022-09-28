# Advanced Regression Assignment: Housing price prediction
<p align="center">
  <img width="460" height="300" src="house.PNG">
</p>
  
>A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

>Required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- A regression model using regularization in order to predict the actual value of the prospective properties and decide whether to invest in them or not
- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house!


## Table of Contents
* [About Surprise Housing](#about-surprise-housing)
* [Summary](#summary)
* [Technologies Used](#technologies-used)
* [Contact](#contact)


<!-- You can include any other section that is pertinent to your problem -->

## About Surprise Housing
- It's a US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Summary
Lasso Regression helps in feature elimination, with Lass we are getting pritty good results with less number of features compred to Redge Regression

## Variable Significance:

  1. AllSF-Sq: Square root of sum of GrLivArea and TotalBsmtSF
    - Total SF including basement be the positive impact on the housing sales price 
  2. YearBuilt: Original construction date.
    - Construction date i.e. age of the house matters a lot on house price
  3. Neighborhood: Physical locations within Ames city limits.
    - Couple of segments in the Neighborhood variables are also having positive impact (Stone Brook and Crawford)
    - NWAmes, IDOTRR, and Old Town location having negative impact on sales price
  4. Condition1: Proximity to various conditions
    - Normal proximity have higher house price        
  5. LotArea: Lot size in square feet
    - Larger teh lot area higher the house price 
  6. Negative impacting features : Basement condition, Bedrooms, Lot configuration with frontage with 2 side etc

Similarly we have lot more variables, which can be seen from Feature Importance chart

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Language: Python
- Libraries: Pandas, Numpy, Seaborn, Matplotlib, Sklearn, Lasso, Ridge, LassoCV, RidgeCV, make_scorer
- IDE: Jupyter Notebook

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by https://www.linkedin.com/in/mmveereshkumar - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
