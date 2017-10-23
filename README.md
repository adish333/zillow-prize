# zillow-prize
## Kaggle Competition: Zillow’s Home Value Prediction (Zestimate)
Zillow’s Zestimate home valuation has shaken up the U.S. real estate industry since first released 11 years ago. “Zestimates” are estimated home values based on 7.5 million statistical and machine learning models that analyze hundreds of data points on each property. And, by continually improving the median margin of error (from 14% at the onset to 5% today).
The aim of this challenge is to develop an algorithm that makes predictions about the future sale prices of homes.
## Evalution Metric
Submissions are evaluated on Mean Absolute Error between the predicted log error and the actual log error. The log error is defined as
logerror=log(Zestimate)−log(SalePrice)
