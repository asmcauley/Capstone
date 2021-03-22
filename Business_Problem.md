# Introduction and Business Problem

## Situation

A Virginia native is intending to start a Cajun restaurant and is choosing between Virginia Beach, Richmond, or Alexandria as her potential location. 
Which city has the lowest concentration of Cajun restuarants? Which neighborhood in that city tends to having the highest number of reviews? What about the highest ratings?

## Choose a location and see where success lies

We will gather Foursquare venue locations for all three cities. Then, we will calculate the proportion of all restaurants in each city that are Cajun restuarants and choose the city 
with the lowest market saturation to start the restaurant. After choosing the city, we will construct a feature which measures the restaurant's potential for success. Our metric of success will be 
the rating (5 stars = 1 and 1 star = 0) multiplied by the number of reviews. We will build a clustering model to examine the differences between the restaurants in the city.

## Choose a neighborhood and begin budgeting

Based on what we glean from the clustering model, we can then begin to investigate other important follow-up questions, such as: how many sqft do we need, or should we feature live music?
