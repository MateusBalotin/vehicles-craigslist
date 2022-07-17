# vehicles-craigslist

This is a dataset of Vehicles listings from Craigslist.org, taken from:

https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data/code?datasetId=62920&sortBy=voteCount

In this project the goal was to try to predict the price of a vehicle on Craiglist from a few parameters.

On the first part of the project I tried to understand the data, what type of parameters I had and their correlation with price.

After that, I did a bit of data cleaning, removing null values and adjusting some strings features.

Then I ploted the correlation between the features and price to have a more visual understanding of the dataset.

Finally, I tried RandomForest, Linear Regression and XGBoost to try to predict. Random Forest had the best performance.
