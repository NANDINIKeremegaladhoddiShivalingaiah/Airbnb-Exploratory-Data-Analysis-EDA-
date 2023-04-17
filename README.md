# Airbnb-Exploratory-Data-Analysis-EDA-
## Project Summary -
Data Preprocessing : Getting the dataset, Importing libraries, Loading datasets, About the Dataset, Understand the Variable, Data Exploration and Data Cleaning. 

Exploartory Data Analysis: Data Wrangling, Data Visualization.
## Problem Statement
Finding the distribution of price on Airbnb rentals in New York City.

Which neighbourhood group is expensive?

How do average price varies on each neighbourhood group?

Which are the cheapest neighbourhoods?

Which neighbourhood group and neighbourhood has more listings?

Which host has more listing? How many number of hosts in each neighbourhood group?

Finding the total number of room in Airbnb New York City and types of rooms.

Finding the total numbers of Reviews by Each Neighborhood Group.

How many minimum night of stay are required by hosts, once the rooms are booked?

Finding the availability of each room types in an year in Airbnb New York City.

## Data Overview:
id - Unique_ID

name - Names of the listing

host_id - Unique host_Id

host_name - Name of the host

neighbourhood_group - Location

neighbourhood - Area

latitude - GPS cordinates

longitude - GPs cordinates

room_type - Types of listing

price - Price of listing

minimum_nights - Minumum no of nights to be paid for

availability_365 - rooms availability around year

number_of_reviews - Number of reviews

last_review - Last reviewed date

reviews_per_month - Total reviews per month

calculated_host_listings_count - Total no of listing by host

##Let's Begin !
# Distribution Of Airbnb Bookings Price Range
The prices for all room types are distributed in a left-skewed pattern.

The range of prices being charged on Airbnb appears to be from 20 to 330 dollars , with the majority of listings falling in the price range of 50 to 150 dollars.

The distribution of prices appears to have a peak in the 50 to 150 dollars range, with a relatively lower density of listings in higher and lower price ranges.

There may be fewer listings available at prices above 250 dollars, as the density of listings drops significantly in this range.

# Price Distribution On Each Neighborhood Group
Price distribution is very high in Manhattan and Brooklyn. But Manhattan have more diversity in price range. Hence,Manhattan has highest price range and is the most expensive one.

Brooklyn comes in second which has higher range of price but is cheaper with respect to Manhattan.

Queens, Staten Island and Bronx have narrower price distribution and have cheaper option.

# Average Price Of Each Neighborhood Group
The average price of a listing in New York City varies significantly across different neighborhoods, with Manhattan having the highest 146 dollars/day average price and the Bronx having the lowest near 77 dollars/day.

The average price increases as you move from the outer boroughs (Bronx, Brooklyn, Queens, and Staten Island) towards the center of the city (Manhattan).

The average price in queens and Staten Island is relatively similar, despite being in different parts of the city.

# Average Minimum Price In each Neighborhoods
All of the neighborhoods listed are located in the outer boroughs of New York City (Bronx, Queens, and Staten Island). This suggests that these neighborhoods may have a lower overall cost of living compared to neighborhoods in Manhattan and Brooklyn.

Most of these neighborhoods are located in the Bronx and Staten Island. These boroughs tend to have a lower overall cost of living compared to Manhattan and Brooklyn.

# Total Listing/Property count in Each Neighborhood Group
Manhattan and Brooklyn have the highest number of listings on Airbnb around 19,000 listings each.

Queens and the Bronx have significantly fewer listings compared to Manhattan and Brooklyn, with 5,567 and 1,070 listings, respectively

Staten Island has the fewest number of listings, with only 365.

The distribution of listings across the different neighborhood groups is skewed, with a concentration of listings in Manhattan and Brooklyn.

Despite being larger in size, the neighborhoods in Queens, the Bronx, and Staten Island have fewer listings on Airbnb compared to Manhattan, which has a smaller geographical area.

This could suggest that the demand for Airbnb rentals is higher in Manhattan compared to the other neighborhoods, leading to a higher concentration of listings in this area.

# Top 10 Neighborhoods by Listing/property 
The top neighborhoods in New York City in terms of listing counts are Williamsburg, Bedford-Stuyvesant, Harlem, Bushwick, and the Upper West Side.

The top neighborhoods are primarily located in Brooklyn and Manhattan. This may be due to the fact that these boroughs have a higher overall population and a higher demand for housing.

Alternatively, it could be that the supply of listings is higher in above neighbourhood due to a higher number of homeowners or property owners in this neighborhood who are willing to list their properties on Airbnb.

# Top Hosts With More Listing/Property
The top three hosts in terms of total listings are Michael, David, and John, who have 383, 368, and 276 listings, respectively.

There is a relatively large gap between the top two hosts and the rest of the hosts. For example, john has 276 listings, which is significantly fewer than Michael's 383 listings.

In this top10 list Mike has 184 listings, which is significantly fewer than Michael's 383 listings. This could indicate that there is a lot of variation in the success of different hosts on Airbnb.

There are relatively few hosts with a large number of listings. This could indicate that the Airbnb market is relatively competitive, with a small number of hosts dominating a large portion of the market.

# Number Of Hosts in each neighbourhood group
Manhattan has the largest number of hosts with 19506, Brooklyn has the second largest number of hosts with 19415.

After that Queens with 5567 and the Bronx with 1070. while Staten Island has the fewest with 365.

Brooklyn and Manhattan have the largest number of hosts, with more than double the number of hosts in Queens and more than 18 times the number of hosts in the Bronx.

# Total Counts Of Each Room Type in NYC
The majority of listings on Airbnb are for entire homes or apartments with 49.6% (22784 listings), followed by private rooms with 47.9% (21996 listings), and shared rooms with 2.5% (1138 listings).

# Total Reviews on Each Neighborhood Group
Brooklyn has the largest share of total reviews on Airbnb with 43.3% followed by Manhattan with 38.9%.

Queens has the third largest share of total reviews with 14.2%, followed by the Bronx with 2.6% and Staten Island with 1.0%.

The data suggests that Airbnb is more popular in Brooklyn and Manhattan compared to the other neighborhood groups.

# Count Of Each Room Types In Entire Airbnb NYC
Manhattan has more listed properties with Entire home/apt around 24.6% of total listed properties followed by Brooklyn with around 19.5%.

Private rooms are more in Brooklyn as in 21.9% of the total listed properties followed by Manhattan with 16.9% of them. While 7.3% of private rooms are from Queens.

Very few of the total listed have shared rooms listed on Airbnb where there's negligible or almost very rare shared rooms in Staten Island and Bronx.

# Minimum night stay requirement
Majority of the host provide 2-3 day minimum night stay, about 12067 hosts provide 1-day minimum night stay, 6566 hosts provide 4-6 day minimum night stay.

The number of hosts providing minimum night stay requirement decreases as the length of stay increases.

There are relatively few hosts providing minimum stay requirement of more than 30 nights or more.

# Availability of room types in an year in Airbnb NYC
The availability of shared room is more compared to private and entire home/apt room types in entire Airbnb NYC.

Shared rooms are more available in Brooklyn, Manhatten and Queen when compared to other room types.

Staten Island doesn't have shared room, and the availbility of private and entire home/apt are more compared to other neighbourhood.

## BUSINESS CONCLUSION :-
Manhattan and Brooklyn have the highest demand for Airbnb rentals, as evidenced by the large number of listings and the majority of reviews in these neighborhoods. This could make them attractive areas for hosts to invest in property.

Manhattan is world-famous for its parks, museums, buildings, town, liberty, gardens, markets, island and also its substantial number of tourists throughout the year ,it makes sense that demand and price both high.

Brooklyn comes in second with significant number of listings and cheaper prices as compared to the Manhattan, With most listings located in Williamsburg and Bedford Stuyvesant two neighborhoods strategically close to Manhattan tourists get the chance to enjoy both boroughs equally while spending less.

Williamsburg, Bedford-Stuyvesant, Harlem, Bushwick, and the Upper West Side are the top neighborhoods in terms of listing counts, indicating strong demand for Airbnb rentals in these areas.

The average price of a listing in New York City is higher in the center of the city (Manhattan) compared to the outer boroughs. This could indicate that investing in property in Manhattan may be more profitable for Airbnb rentals. But Manhattan and Brooklyn have the largest number of hosts, indicating a high level of competition in these boroughs.

The data suggests that Airbnb rentals are primarily used for short-term stays, with relatively few listings requiring a minimum stay of 30 nights or more. Hosts may want to consider investing in property that can accommodate shorter stays in order to maximize their occupancy rate.

The majority of listings on Airbnb are for entire homes or apartments and also Private Rooms with relatively fewer listings for shared rooms. This suggests that travelers using Airbnb have a wide range of accommodation options to choose from, and hosts may want to consider investing in property that can accommodate multiple guests.

The data indicates that the availability of Airbnb rentals varies significantly across neighborhoods, with some neighborhoods having a high concentration of listings and others having relatively few.

The data indicates that there is a high level of competition among Airbnb hosts, with a small number of hosts dominating a large portion of the market. Hosts may want to consider investing in property in areas with relatively fewer listings in order to differentiate themselves from the competition.

The neighborhoods near the airport in Queens would have a higher average number of reviews, as they are likely to attract a lot of tourists or visitors who are passing through the area. The proximity to the airport could make these neighborhoods a convenient and appealing place to stay for travelers for short-term stay with spending less money because The price distribution is high in Manhattan and Brooklyn.
