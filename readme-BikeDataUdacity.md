# (Dataset Exploration Title)
## by (your name here)


## Dataset

Ford GoBike(formerly known as Bay Wheels) is a general public bicycle sharing system in California's San Fransisco Bay Area. 
Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. 
The bicycles are available 24 hours a day, seven days a week for periods ranging from a single ride (up to 30 minutes) to a day pass, in 30-minute increments, or customers can purchase an annual subscription which gives them unlimited rides up to 45-minutes in duration, thus catering to all people at all times.
The dataset given here consists of the data of such people using their services for February 2019.


## Summary of Findings

1. Change data type of multiple fields i.e. start_time, end_time should be datetime type,
   start_station_id, end_station_id,bike_id to string type and
   user_type and member_gender should be categorical data type.

2. Derive new columns for trip duration in minute from duration_sec column, 
  trip start hour of the day, day of week from start_time column.
   
3. Add a new column by creating a function to calculating riders age from 'member_birth_year' column.

4. Filter out outlier ages from visual examination of the member age distribution and drop the corresponding rows.

5. Convert 'dayofweek' to category data type.


## Summary 

1. The Subscribers took more number of trips peaked around 8-9am and 17-18pm during a day, 
    there were more trips on work days (Mon-Fri) compared to weekends and were older group compared to the Customers. 

2. The Customers took long riding trips on weekends and were younger. Their usage on the weekdays wasnt indicating that their trips 
   were casual in nature.

3. The number of male riders were more compared to the female riders. 

4. Male Subscribe riders did not share the bike for all trips. Most of the riders were in the age group of 25 to 40.




## Key Insights for Presentation

1. At each exploration stage, the ideas were put forth and integrated and strengthened the analysis when the 
   multivariate plots were drawn. 

2. Different usage patterns between the two user types are seen from the exploration. 
   Subscribers ride more on weekdays i.e. Monday through Friday whereas customers ride more on weekends.
   This further emphasises on the fact that Subscribers are older and hence stick to 8 to 5 routine, whereas
   the Customers are younger and take more casual trips on the weekends.

A feedback for the presentation was taken and change was with respect to the font which I could not do much about.

