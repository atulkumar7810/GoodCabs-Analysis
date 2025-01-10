# GoodCabs - Performance Analysis 
___
<p style="font-size:20px;">The primary goal of this analysis is to assess Goodcabs' performance across key performance indicators, including trip volume, passenger satisfaction levels, repeat passenger rates, trip distribution patterns, and the proportion of new passengers compared to repeat customers. By conducting this evaluation, we aim to uncover actionable insights that will contribute to achieving the organization's growth targets and service improvement objectives for the year 2024.</p>

## Datasets
- **dim_city**: Contains information about cities, including their unique IDs and names.  
- **dim_date**: Provides time-related details such as date, year, month, and quarter.  
- **dim_repeat_trip_distribution**: Captures the frequency of repeat rides taken by customers.  
- **fact_passenger_summary**: Summarizes key passenger metrics, including ride count, total spending, and average ride details.  
- **fact_trips**: Logs individual trip information, including city, passenger, location, distance, duration, fare, and trip type.  
- **monthly_target_trips**: Defines monthly goals for the number of trips to be completed.  
- **monthly_target_new_passenger**: Establishes monthly targets for acquiring new passengers.  
- **city_target_passenger_rating**: Specifies target and actual passenger ratings for each city.

I designed the data model using a Snowflake Schema structure, incorporating additional details about the City Type to enhance the dataset's analytical potential.






