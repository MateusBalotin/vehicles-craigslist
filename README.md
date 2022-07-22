# vehicles-craigslist

This is a dataset of Vehicles listings from Craigslist.org, taken from:

https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data/code?datasetId=62920&sortBy=voteCount

<h1> Objective</h1>
In this project the goal was to try to predict the price of a vehicle on Craiglist from a few parameters.

<h1> Data Analysis and Cleaning </h1>
On the first part of the project I tried to understand the data, what type of parameters I had and their correlation with price.

After that, I did a bit of data cleaning, removing null values and adjusting some strings features.

Then I ploted the correlation between the features and price to have a more visual understanding of the dataset.

<h1> Findings </h1>
Some of the findings I had were: <br>

<ul>
<li>The best condition for a car was new, as one would expect. Though, one interesting fact was that I applied a 'n/a' category for the null values of the title_status feature and it had the third highest price. That makes sense in some way, if you saw the picture of a vehicle you usually have a pretty good understanding if it's new or old. </li>
<li> The vehicles with 8 cylinders had the highest price with 12 cylinders quite near. </li>
<li> Diesel type fuel had the highest price. </li>
<li> Purple was a bad color and yellow one of the best ones comparing prices. </li>
<li>Trucks and Pickups had the highest price. </li>
</ul>

<h1> Model </h1>
Finally, I tried RandomForest, Linear Regression and XGBoost to try to predict. Random Forest had the best performance.

<h1> Conclusion </h1>
So if you're think of selling your vehicle on Craigslist, your best shot would be to have a vehicle with 8 or 12 cylinders, Diesel type fuel and definitely not purple color!!





<h1> References </h1>
References: https://www.youtube.com/watch?v=Z9dGmL2G-4k&list=PL2zq7klxX5ATPC8RuqCuTDdki3b4NqKQv&index=2

References: https://www.kaggle.com/code/msagmj/data-cleaning-eda-used-cars-prediction-86
