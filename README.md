# Airbnb_NYC

![New-York-City-Brooklyn-Bridge-Panorama-Juergen-Roth-2](https://user-images.githubusercontent.com/48190655/71230772-cfd1d080-229f-11ea-979b-3ae1782eb87b.jpg)

Airbnb provides a platform for hosts to accommodate guests with short-term lodging and tourism-related activities. Guests can search for lodging using filters such as lodging type, dates, location, and price. Guests have the ability to search for specific types of homes, such as bed and breakfasts, unique homes, and vacation homes.

Hosts provide prices and other details for their rental or event listings, such as the allowed number of guests, home type, rules, and amenities. Pricing is determined by the host, with recommendations from Airbnb Hosts and guests have the ability to leave reviews about the experience.

Since its inception in 2008, Airbnb has seen a exponential growth with the number of rentals listed on its website. Airbnb has successfully disrupted the traditional hospitality industry as more and more travellers utilize Airbnb as their premier acccomdation provider.

New York City has been one of the hottest markets for Airbnb. In the project, I performed an exploratory analysis of the Airbnb dataset to understand the rental landscape and consumer behavior with Airbnb listings in New York City. The listings are from 2019.

Questions to be explored:

1. Who has the most listings?

![Hosts with most listings](https://github.com/clvsushant/Airbnb_Proj/blob/main/Images/top10hostlistings.png)

The first host has 300+ listings. Third through tenth hosts have evenly distributed amount of listings.

2. Which Borough (neighbourhood group) have the most listings?

![Listings by Neighbourhood Groups](https://github.com/clvsushant/Airbnb_Proj/blob/main/Images/listingcntborough.png)

Most of Airbnb listings in New York are near Brooklyn and Manhattan which is expected since it's a popular destination for attractions, restaurants, and business travel.

3. What are the room types offered in each Borough?

![Listing price by Neighborhood Groups](https://github.com/clvsushant/Airbnb_Proj/blob/main/Images/roomtypebyborough.png)

The bar plot shows that Entire Home/Apartment are listed most near Manhattan while Private Rooms and Entire Home/Apartments near Brooklyn have similar count of listings.

4. Price Distribution by Room Type by Boroughs.

![shared room price](https://github.com/clvsushant/Airbnb_Proj/blob/main/Images/sharedroomprice.png)

A shared room is cheapest in Brooklyn and Bronx. This graph shows that 90% of shared rooms cost nearly 80(USD) per night whereas Manhattan is the most expensive at nearly 150(USD) per night.

![private room price](https://github.com/clvsushant/Airbnb_Proj/blob/main/Images/privateroomprice.png)

This chart shows that 90% of private rooms in Brooklyn, Bronx, Staten Island, Queens cost around 100 (USD) per night. On the contrary, private rooms in Manhattan cost nearly 180 (USD) per night

![entire home price](https://github.com/clvsushant/Airbnb_Proj/blob/main/Images/entirehomeprice.png)

This chart shows that entire home/apartments in Manhattan are most expensive, averaging nearly 400 (USD) per night. Staten Island, Queens, and Brooklyn lie between 250-275 (USD) per night. Bronx is the cheapest at 200 (USD) per night.

5. What is the overall price distribution by boroughs?

![overall price](https://github.com/clvsushant/Airbnb_Proj/blob/main/Images/rentalpricedistribution.png)

Based on this violin chart, Manhattan has the widest distribution (wide range of prices) with $ 150 as average. Brooklyn has the second highest distribution. Queens and Staten Island have similar distributions and averages. Bronx is the cheapest of them all. This violin chart is logical since Manhattan is known as one of the most expensive places in the world to live in whereas Bronx has a lower standard of living costs.

6. Find a trend in the words used in the listing description.

![Word Cloud Diagram](https://github.com/clvsushant/Airbnb_Proj/blob/main/Images/wordcloudlistings.png)

Based on this WordCloud diagram, it shows that hosts are simply describing their listings in a short form with very specific terms for easier search by potential travelers. Word such as room, bedroom, cozy, apartment, studio, park, and private. Since Airbnb is used internationally, hosts need to use simple terms to describe the listing and area surrounding the it.

                                                Geographical Visualizations

1. Basic Scatter Plot Map for all listings and price.

![heat map](https://github.com/clvsushant/Airbnb_Proj/blob/main/Images/heatmap.png)

Using latitude and longitude points were able to visualize all NYC listings. Also, we added a color-coded range for each point on the map based on the price of the listing. The prices are significantly higher in the Manhattan area as confirmed by the previous graphs on prices based on room type.

2. Folium Map to visualize all unique listings in New York City. I used the cluster marker for cleaner visuals.

![cluster maker](https://github.com/clvsushant/Airbnb_Proj/blob/main/Images/markercluster.png)

Zoomed in more to see distribution

![cluster marker 2](https://github.com/clvsushant/Airbnb_Proj/blob/main/Images/markercluster2.png)

This visual map confirms that most listings are indeed located in Manhattan and Brooklyn.

3. Folium map showing top 10 most reviewed listings.

![top 10 reviewed](https://github.com/clvsushant/Airbnb_Proj/blob/main/Images/top10listingmap.PNG)

I added several markers for popular attractions and restaurants. Attractions(blue) and restaurants(green) were pulled off TripAdvisor and Eatery NY, respectively.

4. Most expensive neighborhoods by average price per night.

![most exp neighborhoods](https://github.com/clvsushant/Airbnb_Proj/blob/main/Images/top10expneigh.PNG)

Not surprising 4 out of the 10 most expensive neighborhoods are in Manhattan.

Data Source: Kaggle [https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data]
