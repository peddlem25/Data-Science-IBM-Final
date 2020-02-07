# Data-Science-IBM-Final
#Capstone Project - The Battle of the Neighborhoods (Week 2)
Applied Data Science Capstone by IBM/Coursera

By: Matt Peddle #
Completed Feb 7, 2020

![Ploted Leads](https://github.com/peddlem25/Data-Science-IBM-Final/blob/master/maprattingcolorcoded.png)
![Average Price Plot](https://github.com/peddlem25/Data-Science-IBM-Final/blob/master/venuepriceplot.png)


# Introduction: Business Problem

**TouchBistro Inc**. is a **Toronto**-based software company that develops a restaurant point of sale system for the iPad and named Best POS System for Restaurants by Business News Daily. As head of sales, it is my duty to find and contact leads specifically in the restaurant field. 

Internally within TouchBistro, I have discovered the profitability of an account is determined by the following:

* How busy they are
* Size of the restaurant (seating room)
* Average bill price (menu items)

In this report, I will analyze and map out potential new clients accounting for the above information. In addition, I will go one step further and highlight our current clients within a certain proximity, so when contacting these new restaurants I'll be able to reference happy current clients. 


# Data

# Based on the definition of our problem, the factors that will influence our decision are:

* Number of existing restaurants in the neighborhood (any type of restaurant)
* Distance of neighborhood from city center
* Average spend per customer

# New Section
Following data sources will be needed to extract/generate the required information:

* **Google Maps API reverse geocoding** will provide the mapping, approximate addresses of venues, busyness functional data. 
* **Foursquare API** will provide us with the venue names, restaurant types and their type and location in every neighborhood.  
* **Zomato API** To assist in providing additional information such as average spend and to verify Foursquare data will be using Zomato as they specialize in restaurant data. 


# Libraries we will be using:

* Python 3: Main coding language
* Pandas: Data Analysis
* Numpy: Handel data in a vectorized manner
* Random: Random number generation
* Conda: GeoCoders - converting addresses into latitude and longitude values
* Folium: Visualizing our data with maps.  
* Matplotlib: Mapping

![Ratings Graph](https://github.com/peddlem25/Data-Science-IBM-Final/blob/master/ratings.png)
![Foursquare Plot](https://github.com/peddlem25/Data-Science-IBM-Final/blob/master/foursquaremap.png)
![Zomato Plot](https://github.com/peddlem25/Data-Science-IBM-Final/blob/master/zomatomap.png)

# Why we do this
![Lead Sample](https://github.com/peddlem25/Data-Science-IBM-Final/blob/master/leadlistsample.png)


