# Citi Bike Bike-Sharing Analysis

## Overview
The purpose of this analysis is to visualize data from the Citi Bike bike-sharing program in NYC. These visualizations will help investors to understand the viability of starting bike sharing programs in other cities, helping entrepreneurs to secure funding. 

### The data
This analysis is based on data provided by Citi Bike for the month of August 2019. August was chosen based on a presumption that summer months will be the most busy and produce a bette approximation of peak service demands. 

Generally, these visualizations show how long most bike trips last and when the most bike trips happen. This information is additionally  broken down in to gender and subscription status of customers. Also included is the overall gender make-up of the riders studied, and a graph depicting which bikes are used the most, giving an idea of how much maintenance may need to be done on a potential bike fleet. 

## Results

All data visualizations for this analysis are part of a Tableau story. Interactive versions of each of the visualizations below are publicly available by [clicking this link](https://public.tableau.com/shared/MP7437QWN?:display_count=n&:origin=viz_share_link):

### Checkout times for users
![BikesharingStory1](https://user-images.githubusercontent.com/114126935/214342860-fae3fbfb-d529-43b9-96d3-de6c465d7374.png)

The above graph shows the length of bike rides. We can clearly see that majority of rides are fairly short, lasting less than an hour, with a major peak at just 5 minutes. With this data, we can anticipate that most riders will ride short distances and hand off their bikes to other potential users in under an hour.

### Gender breakdown
![BikesharingStory2](https://user-images.githubusercontent.com/114126935/214343021-ef51471d-d486-4a76-9758-0ebc3ddc6aef.png)

The following data include breakdowns by gender, so it is meaningful to first understand the gender breakdown of the entire dataset. Male riders (yellow) make up most of the data. Female riders (blue) make up about a quarter, and the remaining riders (red) are of unknown gender. 

### Checkout times by gender
![BikesharingStory3](https://user-images.githubusercontent.com/114126935/214343068-5c363654-a33a-4df6-afd8-49d736d1874c.png)

The above image shows that gender has little effect on checkout times. The gender breakdowns closely match the non-gender chart and look to be in proportion with the overall gender breakdown. Riders of unknown gender do not slope down as steeply from 5 minutes as do male and female riders.

### Trips per weekday per hour
![BikesharingStory4](https://user-images.githubusercontent.com/114126935/214343139-d7a12786-d78a-4ab1-ba24-7123cc99b5c9.png)

This heat map allows us to see that the most popular ride times on weekdays are 7:00AM to 10:00AM and 5:00PM to 8:00PM. On weekends the most popular times are about 9:00AM to 5:00PM. This graph also shows that 1:00AM to 5:00AM are unpopular all week. Perhaps this is when bike maintenance should be done. 

### Trips by gender (weekday per hour)
![BikesharingStory5](https://user-images.githubusercontent.com/114126935/214343181-1bdb927d-0b77-464b-8661-91a825cc3014.png)

These heat maps break down the prior one by gender. They show little difference between male and female riders. Riders of unknown gender look to be slightly more busy on the weekends than on weekdays. Perhaps this has something to do with how gender data was originally collected. 

### User trips by gender by weekday
![BikesharingStory6](https://user-images.githubusercontent.com/114126935/214343233-9cd79bc9-8980-4f2c-b942-919f09db141d.png)

This visualization shows several things. First, we can see that subscribers are much busier than customers. It looks that for both male and female subscribers, Monday, Tuesday, Thursday, and Friday are the busiest days of the week (indicated by the very dark blue rectangles). We can also see that customers are busier on the weekends than on weekdays. Furthermore, as indicated by the darker shades of blue, there are more customers of unknown gender than subscribers of unknown gender. This may have to do with the way gender information is collected or reported by Citi Bike for subscribers versus customers. 

### Bikes needing maintenance
 ![BikesharingStory7](https://user-images.githubusercontent.com/114126935/214343269-41da1d95-828f-4f05-ad65-2080ce6d42f0.png)

In the above image, each rectangle represents a bike. A rectangle’s position and color display how much the bike that it represents is used. For each time a bike is used, its rectangle moves up and towards the left. This chart helps us to approximate the proportion of bikes that are most used and will require more frequent attention. Red rectangles represent heavily used bikes, and black rectangles represent less frequented bikes. 


## Summary
In conclusion, these visualizations may lead us to expect that,

Most bike-share riders will be male. 
Subscribers will be busier than customers. 
Weekdays will be busier than the weekend.
Most rides will last under an hour, and a larger proportion of those will be 5 minutes or less.
More customers will rent on the weekend.
One quarter to one third of the bikes will require extra maintenance.
The best time to repair an maintain bikes and avoid service interruption will be between 1:00AM and 5:00AM

With this dataset visualizations could also be made to examine if bikes tend to pool in certain locations and where those locations are. Other useful visualization may break down rides by age. For example, one may wish to visually compare the age of riders to length of rides. Does age correlate to length of bike rental? How is age distributed throughout subscribers and customers.  
 
