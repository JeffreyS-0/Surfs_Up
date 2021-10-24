# Surfs_Up

## Overview
Last year, I found my love of surfing while in Hawaii and I am now determined to open a Surf and Ice Cream shop so I can live on the island and surf every-day. In order to open the shop, I need some investor backing and I found the perfect investor for this business. A man named W. Avy has the money to back my dream; however, in order to get his investment I need to analyze past weather data to see if the business is sustainable year-round. Here I am analyzing weather data specifically for the months of June and December to get a better representation of how the weather is during the summer and winter months.

## Results
- As we can see below, there isn't too much variation between temperatures in the month of December versus the month of June.

![June_temps_describe](https://user-images.githubusercontent.com/69607218/138609359-a5440e5f-7d05-45f2-b864-6b9a1460877f.png)
![Dec_temps_describe](https://user-images.githubusercontent.com/69607218/138609365-1458f09f-ba85-46a9-9b6a-6da622bd53c9.png)

- After plotting our data, we can see that there is a larger variance in frequency for the average temperature for December compared to June.
 
![June_temps_plot](https://user-images.githubusercontent.com/69607218/138610558-b6df6718-8c0f-4cf7-bdb5-ec008701d896.png)
![Dec_temps_plot](https://user-images.githubusercontent.com/69607218/138610564-1d9a098a-da68-4ec5-a4fc-5f14eee9a200.png)

- From our visualizations we can see that Oahu has a standard deviation of 3-4 degrees for each month respectively, and the averages between December and June only differ 3 degrees as well.

## Summary
From our results we can conclude that with only a 3-4 degree difference between the averages of the two months, we can assume that the temperatures in June compared to December are roughly the same. However, we can also determine that the averages may be very similar, we see that in the winter months the temperature varies much more drastically with a minimum temperature of 56 and a maximum of 83. While in the summer months, we can see the minimum being 64 and the max being 85.

To follow up on our analysis, we could run two additional queries for historical weather data and complete a picture of what life is like on the islands of Hawaii.
  1. We could query precipitation levels for the months of December and June to determine which month typically sees more rainy weather.
  2. We could also query the weather stations with temperature and precipitation levels and then filter out which weather stations would be closest to our Surf and Ice Cream shop in Oahu. 

By querying this additional data, it could help us determine if we are choosing the best location to put our storefront, because at the end of the day, we want the location that will gain the most foot traffic year-round so we can fulfill our dream of living the island life and surfing every-day.
