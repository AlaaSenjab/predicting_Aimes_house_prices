# Ames Housing Data Analysis 


This notebook analysis Aimes House sale prices. The data is for residential properties sale prices from 2006 to 2010 in Aimes, Iowa. The data contains more than 80 features that evaluates houses sale prices for 2051 houses.  

### Problem Statement:
The value of a house is often estimated by several personals who come to check the size, quality, condition, features, location of the house. While this method doesn't give accurate scores, it also makes it hard for home buyers and sellers to know the true value of the property.

One of the websites that lead buying/selling houses in the U.S. is Zillow. It can estimate the prices for houses that are on and off market with very high accuracy. Currently, Zestimate, our house predication platform, can estimate house prices for on-market houses with %1.5 maiden error, and %7.5 for off-market houses. The better lower these error scores are, the better our house price predictions are, which yields into more people using our platform and more money for us.

##Important Features

We can see that overall quality and total size of the house actually are the most important along with the year that it was built.
![Image description](https://git.generalassemb.ly/DSI-US-9/Real-Time-Weapon-Detection/blob/master/Demo/de1.gif)


### Model Generalization

The model can be generalized to other cities. The only feature in this data frame that makes it more specific to this city is the Neighborhood feature. Other Cities, of course, will have different house prices depending on their location. Regardless, if we can get a Neighborhood feature for the city we want to compare this model to, it would be sufficient to predict the other city's home prices.


## Conclusion

The data Frame contains a lot of features, some are important and others are not. This model predicts the house prices with an error (RMSE) of 21,300 or a percentage of around %9
This model works good for houses that are for less than 300,000 dollar. After that, the error increases and the predicted house prices become very different from the actual ones. 

To better address this issue, we can split our data into two data frames; for more and less than 300,000 dollar. Doing this will not only make better house prices predictions for more expensive houses, but also our model for houses less than 300,000 dollar will increase sharply. and our %9 error will become much closer to the actual predicted houses.
