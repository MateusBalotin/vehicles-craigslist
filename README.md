# vehicles-craigslist

This is a dataset of Vehicles listings from Craigslist.org, taken from:

https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data/code?datasetId=62920&sortBy=voteCount

In this project the goal was to try to predict the price of a vehicle on Craiglist from a few parameters.

On the first part of the project I tried to understand the data, what type of parameters I had and their correlation with price.

After that, I did a bit of data cleaning, removing null values and adjusting some strings features.

Then I ploted the correlation between the features and price to have a more visual understanding of the dataset.

Some of the finding I had was:

* The best condition for a car was new, as one would expect. Though, one interesting fact was that I applied a 'n/a' category for the null values of the title_status feature and it had the third highest price. That makes sense in some way, if you saw the picture of a vechile you usually have a pretty good understanding if it's new or old.

* The vehicles with 8 cylinders had the highest price with 12 cylinders quite near.
* Diesel type fuel had the highest price.
* Purple was a bad color and yellow one of the best ones comparing prices.
* Trucks and Pickups had the highest price.

So if you're think of selling your vehicle on Craigslist, your best shot would be to have a vehicle with 8 or 12 cylinders, Diesel type fuel and definitely not purple color!!


Finally, I tried RandomForest, Linear Regression and XGBoost to try to predict. Random Forest had the best performance.


References: https://www.youtube.com/watch?v=Z9dGmL2G-4k&list=PL2zq7klxX5ATPC8RuqCuTDdki3b4NqKQv&index=2

References: https://www.kaggle.com/code/msagmj/data-cleaning-eda-used-cars-prediction-86
