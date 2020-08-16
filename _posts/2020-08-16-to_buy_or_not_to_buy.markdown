---
layout: post
title:      "To buy or not to buy?"
date:       2020-08-16 20:27:28 +0000
permalink:  to_buy_or_not_to_buy
---



## Background
For Years it has been the case that buyers around the US have felt cheated by the housing market. in 2007/8 the systemic issues in the market for houses were exemplified. People thought things would change however this has not been the case.

It was my aim to create a model for house buyers in King County. The goal of the model would be to allow buyers to be able to easily guage the proce of their house compared to similar houses. This would allow them to not be cheated my estate agents and sellers. 

## Project outlines 
* I have access to data set that gives details on houses sold in 2014-2015. These details include proces, number of bedrooms, location etc.
* using this data set i should create a regression model that, to a high degree of accuracy, is able to predict the prices of houses in King county 
* The model should be easy to understnad, easy to interperate and easy to use to make predictions this is becuase it is designed to be used by all buyers 

## Data analysis

### Zip code on house prices
we found that the location of a property and by definition its zip code make a very large difference on the price of a house. Houses that were located tended to be high priced than houses located in the south, and houses in the west tended to br higher priced than houses in the east.

Around the world location tends to be the biggest contributer to the price of houses. We say this first hand in King county. If we had two identical houses, there were zom zipcodes that had the potential to add $600,000 + to the cost of the house while there were others that would reduce the price of the house by $40,000+.

### Date of sale of house prices
Stragenly house prices changed at differnet parts of the year. We found that in wuarter 2 house prices are highest while in quater 4 and early into quater 1 house prices were at their lowest. Thus if you are not pressed to buy a house quickly you should wait till quater 4.

After futher research we found that this is a world wide phenomenon and happens for a couple of reasons:
* The winter market tends to be slower. Sellers who list at this time of year (instead of waiting for spring)
tend to be highly motivated. Often, the seasonal lull also leads to price reductions.
* Houses look nicer in spring and summer months


### Other Variables
there were many other variables that we found play a significant role in the cost of houses. these include:
* Bedrooms = - 4,308
* Bathrooms = 17,773
* Basement = -13,305
* Condition = 23,238
* Floors = -55,716
* Grade = 28,418
* SQFT Living = -14
* SQFT Lot = 0.82
* Waterfront = 327,949
* Year Built = -595
* SQFT living X grade = 12 
* SQFT living X Floors = 26

Most suprisingly Bedrooms had a negative impact on the price of the house. When analysed in singularity it had a positive impact however in conjunction with all the other variables it was found to have a negative impact in the price of houess.


## Conclusion 
our model had an adjusted R-Squared of 0.82 and a mean average error of $61,822. Thus although not perfect, is a good baseline for house buyers to base the price they should expect to pay of off.

futher work on seeing how houes prices change over time and a more detailied analysis on the variabels would make this an even better and more useful model.
