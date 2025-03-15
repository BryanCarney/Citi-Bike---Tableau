# Citi Bike - Tableau

### Background

As the new lead analyst for the New York Citi BikeLinks to an external site. program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to an external site. webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

### Tableau Public URL 

[CitiBike Data - Tableau Link](https://public.tableau.com/app/profile/bryan.carney/viz/CitiBikeData-Feb2025/CitiBikeData?publish=yes)

### Files

[Citi Bank Data Used](https://s3.amazonaws.com/tripdata/202502-citibike-tripdata.zip)

Files were Used from Citi Bike Trip Data from February 2025.  (Note - No "Bike ID" or "ZIP Codes" are present in these updated files)

### Instructions

In this assignment data is aggregate for Citi Bike Trip History Logs and find two unexpected phenomena.

### Questions Answered:

How many trips have been recorded in total during the chosen period? 

**2,031,257**

By what percentage has total ridership grown? 

**The total ridership growth throughout the month is displayed in a visual, which shows an increase in ridership toward the end of February.**

How have the proportions of short-term customers and annual subscribers changed? 

**Over the monthly data the members vs casual riders does remain pretty consistent based on the visual representations.**

What are the peak hours when bikes are used during the summer months?  

**Peak Hours are 8am, 4pm, 5pm and 6pm.  Likely due to people using the bikes for transportation to and from work.**

Today, what are the top 10 stations in the city for starting a journey? and what are the top 10 stations in the city for ending a journey? Based on data, why do you hypothesize these are the top locations?  

**The top 10 stations are displayed in the Station Metrics tab. I hypothesize that these locations are the primary starting points due to their central positioning within the city, where many people are employed. If individuals are primarily using the bikes for commuting to work, it is expected that the majority of start locations will be concentrated in these areas. This is also why these stations appear as the highest ending locations, as commuters often return bikes to the same central areas after their workday.**

Today, what are the bottom 10 stations in the city for starting a journey? and what are the bottom 10 stations in the city for ending a journey? Based on data, why? 

**The bottom 10 stations are displayed in the Station Metrics tab. Upon reviewing their locations on a map, it is evident that they are situated on the outskirts of the city in more isolated areas with limited surrounding communities. These stations are likely frequented primarily by casual riders, who infrequently use the service for regular transportation.** 

How does the average trip duration change by the type of user? (This may be under "User Type" or "member_casual" depending on the period the data is from).  

**The average trip duration in February remains relatively consistent across both casual and member riders. Casual riders have an average trip distance of 1.1984 miles, while member riders have a slightly shorter average of 1.0876 miles. This could suggest that members tend to use the service for shorter trips compared to casual riders. One possible explanation is that members may be more likely to use the service for quick, routine commutes, such as short-distance travel to work or local errands, whereas casual riders, who may use the service more sporadically, might be inclined to take longer trips. This difference in trip lengths could provide valuable insights into the distinct usage patterns between these two rider groups.**

What is the average distance in miles for a bike trip? 

**Average Casual 1.1984 Miles - Average Member 1.0876 Miles**

Which bikes (by ID) are most likely due for repair or inspection in the timespan?  

**Unable to answer as Bike Id's are not contained within data set**

How variable is the utilization by bike ID? 

**Unable to answer as Bike Id's are not contained within data set**


# Breakdowns of Visuals 

These Visualizations are put into three dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.

# Category Breakdowns (Emphasis on Membership Types)

![image](https://github.com/user-attachments/assets/207699ac-5ee2-4bdc-8098-693cb2dbf33f)

These visuals indicate that the majority of ridership is attributed to membership riders, with a minimal presence of casual riders. It can be inferred that there may be limited potential for new membership opportunities during the month of February. Additionally, considering that the city likely experiences lower tourism activity during this time, a logical next step would be to replicate these visuals for the summer months to assess if casual ridership experiences an uptick. Furthermore, the weather patterns in February suggest that as temperatures rose towards the end of the month, ridership also saw a corresponding increase.  

# Station Metrics

![image](https://github.com/user-attachments/assets/e9fca3f0-e615-4347-a888-0831b940369f)

It was surprising to observe that the top starting stations were also the top ending stations. However, upon further analysis and comparison with the city's map, it became clear that these stations were strategically located near major employment hubs. This proximity likely explains the frequent use of these stations, as they are commonly utilized for commuting purposes. The pattern suggests that riders are primarily using these stations for travel to and from work, reinforcing the connection between station usage and the locations of key professional centers within the city.

# Top Routes

![image](https://github.com/user-attachments/assets/64ff30bc-6d11-4fa1-b962-0ae386eebbf7)

By highlighting the top routes, the goal was to identify opportunities for optimizing bike availability at these key locations. Notably, the usage of electric bikes on these routes far exceeds that of classic bikes. This trend suggests a potential opportunity to increase the stock of electric bikes at these stations, particularly if the price point for electric bike rentals is higher, which could enhance revenue generation. Adjusting bike inventory based on this demand could lead to more efficient utilization and greater financial returns.


# HeatMaps

Create one of the following visualizations for city officials:

A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

![image](https://github.com/user-attachments/assets/abef8ca8-5ce8-40cc-91ab-78e8a11d45eb)

### Heatmap Overview:

The heatmap clearly shows a significant concentration of bike activity in the center of the city, particularly in areas with high foot traffic and employment hubs. Smaller clusters outside the city, in surrounding boroughs, suggest less frequent but still notable usage in suburban areas. The filters applied, such as Top 15 and Bottom 15 stations, membership type, bike type, days of the month, and hours of the day, offer a detailed view of user behavior across various dimensions.

### Filter 1: Top 15 and Bottom 15 Stations by Volume

**Top 15 Stations:**

The Top 15 stations are located primarily in the heart of the city, close to major transportation hubs, office buildings, and commercial areas. This suggests that these stations are heavily used for commuting purposes, particularly by members, as they are typically located in central, high-traffic areas.

These stations are crucial for short-distance travel between home and work, and potentially between work and leisure activities during peak hours.
Actionable Insight: It would be beneficial to ensure these stations are adequately stocked with bikes, particularly electric bikes, to meet the demand, especially during rush hours.

**Bottom 15 Stations:**

The Bottom 15 stations are located in less central, more isolated areas, often on the outskirts of the city or in boroughs with fewer commercial activities. These stations likely see less foot traffic and fewer commuters, contributing to their lower volume.
Casual riders are likely the primary users of these stations, with fewer daily commuters depending on them.
Actionable Insight: There may be an opportunity to increase marketing efforts or promotions to encourage greater use of bikes in these areas. Alternatively, these stations could be reevaluated for resource allocation to ensure operational efficiency.

### Filter 2: Membership Type

**Member Riders:**

The number of member riders far outnumbers casual riders, indicating a strong customer base of people who are likely using the service regularly for commuting. This aligns with the assumption that members use bikes for more predictable, routine trips, such as daily work commutes or regular errands.
The higher usage of electric bikes among members further emphasizes their preference for more efficient, comfortable, and potentially faster modes of transportation for daily travel.
Actionable Insight: Continue to focus on enhancing the membership model, perhaps by offering incentives for members to use bikes more frequently or by increasing availability of electric bikes at high-demand stations.

**Casual Riders:**

Casual riders tend to have more sporadic usage patterns, with lower volumes on weekdays and higher activity on weekends, which may suggest they use bikes for leisure or occasional trips.
Casual riders also show a higher propensity to use classic bikes, possibly due to the lower cost of renting these bikes compared to electric bikes.
Actionable Insight: Target casual riders with tailored promotions or discounts for electric bikes during off-peak hours, especially on weekends when demand may be higher, to drive greater usage.

### Filter 3: Bike Type (Electric vs Classic)

**Electric Bikes:**

The significant preference for electric bikes over classic bikes stands out. Electric bikes are likely more attractive for commuters who need to travel longer distances or want a faster and more comfortable experience, particularly during rush hours.
The higher cost of renting electric bikes may not deter members who see value in a more efficient commuting option.
Actionable Insight: It would be beneficial to maintain and increase the availability of electric bikes at the Top 15 stations and key locations in high-demand areas, especially during peak commuting hours, to ensure sufficient inventory for members.

**Classic Bikes:**

While classic bikes are still being used, they are significantly less popular compared to electric bikes, likely due to the reduced convenience and effort involved in using a pedal-powered bike for commuting, especially in urban environments.
Actionable Insight: Reassess the allocation of classic bikes in the system. Given the strong preference for electric bikes, consider scaling back the availability of classic bikes in areas with high commuter demand, or reallocating resources to areas with higher leisure riding demand.

### Filter 4: Days of the Month

**Weekdays (Monday to Friday):**

During weekdays, station volume is generally higher, particularly during morning and evening rush hours. The heatmap shows that these areas are well-utilized by members who are commuting to work or other regular destinations.
This could indicate that commuters are relying heavily on the bike share system to avoid congestion or to get to public transportation nodes.
Actionable Insight: Ensure that the system has an optimal number of bikes available at key stations during rush hours, particularly for electric bikes. You may also want to look at optimizing maintenance schedules so bikes are always available during peak periods.

**Weekends (Saturday and Sunday):**

Weekend usage is notably slower, with some increase in activity in leisure-focused areas. This is consistent with the behavior of casual riders, who are more likely to use bikes for recreational purposes.
It could also reflect reduced demand from commuters, as work-related trips decrease over the weekend.
Actionable Insight: Focus efforts on promoting electric bikes or offering discounts for casual riders on weekends to increase bike usage. Consider providing targeted promotions in recreational areas or near leisure destinations to attract more riders.

### Filter 5: Hours of the Day

**Daytime (9 AM - 6 PM):**

Daytime hours see the highest volume, especially between 9 AM and 6 PM, likely driven by the commuting patterns of both members and casual riders.
The morning rush (7 AM - 9 AM) and evening rush (5 PM - 7 PM) show the highest activity levels, with a significant concentration in the central city area.
Actionable Insight: To support these peak hours, ensure there are enough bikes, especially electric bikes, available at key stations. You may want to consider adjusting staffing or operational logistics to manage peak demands.

**Nighttime (After 7 PM):**

Nighttime activity is slower, as expected, with significantly lower usage outside of the central city areas. The volume of bikes available during these hours might be higher than needed, indicating potential inefficiency.
Actionable Insight: Consider adjusting bike availability in off-peak hours, potentially reallocating bikes from low-demand stations to high-demand ones. Additionally, consider offering incentives to encourage more nighttime usage, especially in areas with high nightlife or late-shift workers.

### Conclusion:

The heatmap and the associated filters reveal significant insights into rider behavior and station performance. 

**Key takeaways include:**

Central city locations are highly frequented by commuters, suggesting that station stocking should prioritize electric bikes in these areas.

Casual riders tend to use bikes more on weekends, while members primarily use them during weekdays for commuting.

Electric bikes are the clear preferred choice, particularly for commuting purposes, and should be prioritized at high-demand stations.

Weekday rush hours should be targeted with optimized bike availability, while weekend promotions for casual riders could help boost usage during slower periods.

By utilizing this data, there are clear opportunities to refine bike allocation, optimize station placement, and tailor promotions for different rider types, ultimately improving the efficiency of the bike-sharing system.

# Final presentation:

The Tableau story brings together the visualizations, requested maps, and dashboards.

[CitiBike Data - Tableau Link](https://public.tableau.com/app/profile/bryan.carney/viz/CitiBikeData-Feb2025/CitiBikeData?publish=yes)
