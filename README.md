# Real_Estate_Transactions
This is a model used for predicting if a house will sell for a high price or a low price. This was done to see what attributes would correlate the strongest and how accurate it can be. The sample data set can be found [here.](https://support.spatialkey.com/spatialkey-sample-csv-data/ "Data Set") 

After doing an analysis on the data set, the predictor was able to predict if a house will sell above or below the average price with a 93% accuracy. This is 16% higher than the base rate for the data set. The predictor is a Random Tree Forest set to 150 iterations. The two main attributes that contribute to the model are Sales Date and Zip code. This makes a lot of sense as prices of houses fluctuate based on the time of year and certain regions tend to have similar pricing for houses. A surprising take away, is that the square footing of the home did not necessarily correlate to more expensive homes.

To further improve this predictor, I would further pre-process the data, try and remove any irrelevant attributes, and try more specialized predicting models. This would all depend on what the client is aiming to gain for the analysis.
