# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
My goal with this project was to get all the bike spots from the city of São Paulo using the CityBike API, and to locate restaurants, coffee shops, and bakeries within a 200-meter radius of each rental bike spot, and analyze the data to identify patterns and possibly some opportunities.
## Process
1- Get all the bike points in the the city of São Paulo, and record the latitude and longitude with the location id.
2- Connect to foursquare and Yelp API, find Restaurants, Bakeries and Coffee Shops in a 200m radius. Record all the relevant information for data analyses.
3- Combine the data from CityBikes API with the Yelp APi in one data set.
4- Generate a sqlite database, with all the API's.
5- Build a regression model, to check if any of the variables have any influence in the business ratings.

## Results
The Yelp API was easier to use, but because I only had access to a free account, I faced limitations on the number of calls I could make daily. The Foursquare API gave me all the important columns with null values, so the data could not be used effectively.

## Challenges 
The API documentation is good, but as this was my first project, I spent a lot of time figuring out how to return the correct data from Yelp and Foursquare. I also didn’t have enough time to check my data before conducting my linear regression.

## Future Goals
If I had more time, I would fine-tune my request from the API and process my data more thoroughly before conducting my analysis."
