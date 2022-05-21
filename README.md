# PyBer_Analysis

## Analysis Overview:

The purpose of this analysis is to review ride share data for the company Pyber in order to determine trends around the number of rides, cost per ride, and driver count in urban, suburban and rural areas for a certain period of time. By grouping the data by city type (ie: urban, suburban, or rural), we were able to see clear differences in the number of rides given, the average cost per ride and the number of drivers for each type of location.
- - - -
## Results:

### The headline for the dataset is: urban areas had more drivers, more rides and lower costs, whereas rural areas had fewer drivers, fewer rides and higher costs.

Overall this makes sense. With a scarcity of drivers, it’s possible that rural areas have to offer surge pricing to incentivize drivers to turn on their apps, and then customers have fewer rideshare options and are likely to pay more for a ride, especially if they have a longer distance to travel in order to get to their destination. Conversely, an urban area means more people in general, and likely more young people who are frequently going out and taking advantage of ride shares. Urban areas also likely have less parking and more people who rely on public transit and ride shares to get around, rather than personal vehicles.

Below, I've included the Pyber summary data frame, as well as a line chart that shows the weekly average fares by city type from January through April. 2019. Below those charts, I've also included a detailed breakdown of the results with some visualizations.

#### Pyber Summary Data Frame:

![pyber summary data frame](https://user-images.githubusercontent.com/103781847/169670479-b0ebf20b-d7be-4682-a565-ef6aa571e0ab.png)

#### Pyber Weekly Fare Summary:

![PyBer_fare_summary](https://user-images.githubusercontent.com/103781847/169670497-201ad869-71be-4b8f-a4c4-9901f978f2a1.png)

### Results Breakdown:

#### Total Rides: 2,375

Of the total rides, 5.3% were in rural areas, 26.3% were in suburban areas and 68.4% were in urban areas.

![Fig6](https://user-images.githubusercontent.com/103781847/169670683-3f22e017-e0e1-46ad-bb90-520f1e9d4137.png)

#### Total Drivers:2,973

Of the total drivers, only 2.6% were rural, 16.5% were suburban and 80.9% were urban. Urban drivers make up an even larger percentage of the total than urban rides, which points to potentially having a surplus of drivers in urban areas. 

![Fig7](https://user-images.githubusercontent.com/103781847/169670718-ed49143e-a8cb-4154-b3dd-d1a41bbf2359.png)

#### Total Fares:

Of the total fares, 6.8% were charged in rural areas, 30.5% were in suburban areas and 62.7% were in urban areas. Taking the other data points into consideration (number of rides and drivers), it appears to be much more expensive to use Pyber's rideshare service if you're in a rural area, than if you're in an urban area. 

![Fig5](https://user-images.githubusercontent.com/103781847/169670756-00ab6874-f949-40cd-aab3-2453bd2a5004.png)

#### Average Fare (y-axis) per Ride (x-axis) and driver count (size of bubbles):

Here, we see the same data trend: in urban areas where there are a higher number of rides and drivers, the fares are lower. Conversely, rural areas have fewer rides and drivers, and the fares are higher.

![Fig1](https://user-images.githubusercontent.com/103781847/169670845-c7756203-0168-42f8-a16e-d146d42ea954.png)

#### Total Fare by City Type:
In the box and whisker plot below, we can see that there are a wider range of rural fares than suburban and urban fares. Urban fare ranges are much lower than both suburban and rural ranges, which are more similar (though rural fares are still higher).

![Fig3](https://user-images.githubusercontent.com/103781847/169670905-6058f500-9396-49da-94f2-69414b9bcc4a.png)

- - - -
## Summary and Business Recommendations:

### As the CEO of Pyber, my first concern would be continuing to acquire and retain clients and drivers, in order to keep my company profitable. Here are my recommendations for doing so:

1. Do a more qualitative study (could be a survey) with drivers and riders in rural areas, in order to understand the needs there.
    
    1. Are riders feeling like they don’t have enough drivers or ride options in their area? Are they waiting a long time to get picked up? Are their ride     costs reasonable for the distance they need to travel? 
    
    2. Similarly, I would like to know how drivers in rural areas are feeling. Is there enough demand to make it worth their time to drive in their area?       Is there too much demand given the low number of drivers? What are the contributing factors to the cost of their rides? Distance? Surge pricing?

2. My second recommendation would be to focus on how they can continue to drive business in suburban areas.
   
   1.  Fares begin an upward trend in April of 2019, so I would want to understand what drove that demand. Was there targeted marketing in urban areas?        Were there large events that drove people to need to utilize ride fares more, such as spring festivals?
   
   2.  Since suburban areas are the second largest area in terms of number of rides and many people left cities for more suburban areas during the            pandemic, I would want to see how we can get more drivers, more rides and lower costs, in order to take a bigger market share in suburban areas and        compete with other ride companies in those areas.

3. Finally, my third recommendation would be to consider making some changes around the number of drivers in Urban areas.
    
    1. We seem to have a large number of drivers and are able to keep ride costs down, which makes me wonder: do we have too many drivers in urban areas?       Is there a way we could incentivize them to flex into nearby rural/suburban areas in order to support demand and lower costs there?
    
    2. On a different note, urban fares were highest at the end of February and the beginning of March, 2019, respectively. Do we know why that’s the case?     Is there an opportunity to flex some drivers between suburban and urban areas (such as having them focus on the suburbs of a large city) depending on       where the demand is greatest? If we can optimize for demand and keep our drivers busy, we can drive customer and driver satisfaction.
- - - -
