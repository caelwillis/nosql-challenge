# nosql-challenge

For this module challenge, we will be creating a mongo database and importing in a collection restaurant data for an analysis on the health of these establishments.

We first must create a database called 'uk_food' in import the data stored in the 'establishments.json' file located in our resources folder. Then this list must be updated with an additional restaurant who's details are provided to us. Then we must filter out any restuarants from areas we are not interested in analyzing. All data types in these restaurant entires must be updated to the proper data-type if need be. We are then able to begin our analysis.

We will be creating a few querys to manipulate our data. The first query will show us only the entries with a hygiene score equal to 20.
Then we will discover which establishments in London have a `RatingValue` greater than or equal to 4.
Next we are seeking to answer nearest to the restaurant "Penang Flavours", what are the top 5 establishments with a `RatingValue` rating value of 5, sorted by lowest hygiene score.
Our final analysis seeks to answer how many establishments in each Local Authority area have a hygiene score of 0.

We are converting the results of all analyses to data frames.
