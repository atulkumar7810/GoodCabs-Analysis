# GoodCabs - Performance Analysis 
## Problem Statement
GoodCabs, a cab service company in tier-2 cities, aims to enhance passenger satisfaction, optimize operations, and empower local drivers to achieve its growth targets. The analysis focuses on trip volume, passenger satisfaction, repeat passenger rates, trip distribution, and the balance between new and returning passengers.

## Objectives
- Evaluate operational efficiency and demand through trip volume analysis.
- Measure service quality using passenger satisfaction metrics.
- Understand customer retention with repeat passenger rates.
- Analyze trip distribution patterns and balance of new vs. returning passengers.

# Data Model Documentation
## Dimensions

- **dim_city**: Stores city-related information, such as ID and name.
- **dim_date**: Contains time-based attributes, including date, year, month, and quarter.
- **dim_repeat_trip_distribution**: Represents the frequency of repeat rides by customers.

## Facts

- **fact_passenger_summary**: Summarizes key passenger metrics, such as ride count, total spend, and average ride details.
- **fact_trips**: Captures individual trip details, including city, passenger, location, distance, duration, fare, and trip type.

## Targets

- **monthly_target_trips**: Specifies the monthly goals for the number of trips to be completed.
- **monthly_target_new_passenger**: Defines monthly targets for acquiring new passengers.
- **city_target_passenger_rating**: Tracks target and actual passenger ratings for each city.


The data was modeled using a Snowflake Schema, incorporating additional details about City Type to enhance analytics.

## Data Model

![Screenshot 2025-01-10 115602](https://github.com/user-attachments/assets/65243b88-6a68-4b08-90dd-d692cb31b6db)

## Dashboard Overview

![front_page](https://github.com/user-attachments/assets/dfffa613-52bf-4b83-bb86-025ae65abdd6)

### Driver-Passenger Analysis
Displays key metrics like average driver and passenger ratings, NCA rate, and total trips for 2024, along with city-wise performance, actual vs target trip differences, and the best/worst-rated cities.

![first_page](https://github.com/user-attachments/assets/ad717a20-07f7-48bc-b7a6-b5faae1a63c9)


![first_page_open](https://github.com/user-attachments/assets/0d8b26b1-cbc4-4f08-87aa-50ae21798cf7)

### City Metrics
Displays key metrics like trip count, RPR (Repeat Passenger Rate), and total trips for 2024, along with city-wise trip performance, top/bottom months by trip difference, and the best/worst cities by RPR.

![second_page](https://github.com/user-attachments/assets/3221221a-9b51-47d4-9a69-4886c2217448)

### Trip Insights 
The third page of the dashboard analyzes trip demand, passenger trends, and fare metrics across cities, with filters and insights.

![third_page](https://github.com/user-attachments/assets/1382421f-8ee4-4a43-b9ea-a190d87068c8)


## Key Insights
1. **City Performance**:
   - **Top Cities**: Jaipur (18%), Lucknow (15%), Surat (13%).
   - **Bottom Cities**: Visakhapatnam (7%), Coimbatore (5%), Mysore (4%).
2. **Fare Analysis**: Tourism cities have 108.9% higher fares and 77.2% longer distances than business cities.
3. **Passenger Ratings**: Jaipur and Kochi lead (8.99); Vadodara has the lowest repeat passenger rating (5.98).
4. **Seasonal Trends**: High demand in April-May; low in June-January.
5. **Repeat Passenger Rate (RPR)**:
   - **Top Cities**: Surat (42.6%), Lucknow (37.1%).
   - **Bottom Cities**: Mysore (11.2%), Jaipur (17.4%).

## Recommendations
1. **Service Quality**: Train drivers and offer performance-based incentives.
2. **Flexible Pricing**: Introduce dynamic pricing to cater to middle-class demographics.
3. **Seasonal Marketing**: Align campaigns with tourism seasons and local events.
4. **Sustainability**: Transition to EVs to attract eco-conscious customers.
5. **Partnerships**: Collaborate with local businesses to enhance loyalty and demand.

