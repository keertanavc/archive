## Effect of Agglomeration in the Restaurant Industry

**Project Description:** Although competition can dwindle the sales of a restaurant, it is found that restaurants tend to collocate with their competitors. 
Despite the associated costs, physical proximity to competitors can lead to positive externalities like increased demand and improved efficiency.
We empirically examine the effect of agglomeration in the restaurant industry by understanding how the type and performance of neighboring competitors affect a restaurant. 

**Data:** A time series data is constructed from Yelp Data Challenge 2018's data, this is the primary data source.
Other sources are US census data and Google Maps API.

**Feature Engineering:** The target variable is a binary 0/1 marking the survival of the resturant based on Yelp. 
To understand the effect of neighboring restaurants, variables measuring neighbor's performance, product, and affiliation.
The restaurants performance, product offering, discounts etc. are used as control variables.

**Models:**
The main model used in the study is a Cox proportional hazards model. 
This is a survival model that model time to event, in our case failure of restaurant.

**Findings:**
- Improvement in neighbor performance (footfall and ratings) was detrimental to a restaurant’s survival
- Collocating with restaurants operating in the same price bracket had a positive influence while neighbors’ food cuisine did not make a difference
- Franchises did better in neighborhoods crowded with other franchises and vice versa for non- affiliated restaurants

Tools and models used: 
- Data Collection: Google MAPs API, Census Data API
- Analysis: Cox Proportional Hazards Model in STATA


Check [this](https://github.com/keertanavc/Papers-and-Posters/blob/master/restaurant_agglomeration_working_paper.pdf) report for more details.
