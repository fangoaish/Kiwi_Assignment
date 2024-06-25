# Analyzing Driver Performance and Ride Metrics

## Project Overview
This project aims to analyze and understand the performance and behavior of drivers based on ride data. By leveraging data from driver onboarding, ride details, and ride event timestamps, we can gain insights into driver activity, ride efficiency, and the impact of PrimeTime pricing. The analysis will help identify patterns and trends in ride distances, durations, and the effects of PrimeTime on ride metrics, ultimately contributing to optimized driver performance and customer satisfaction.

![image](https://github.com/fangoaish/Python_Analyzing_Driver_Performance_and_Ride_Metrics/assets/51399519/03288cc5-79f5-44a5-acb9-aae588842684)


## Business Objectives

It aims to optimize driver performance and customer satisfaction by analyzing data to increase driver lifetime value (LTV), extend driver tenure, predict and mitigate churn, and optimize high-value driver segments. This involves calculating LTV and tenure, identifying churn indicators, tailoring strategies for valuable segments, and enhancing revenue and ride efficiency with optimal pricing strategies and improved service reliability.


## Data Sources
These three datasets are provided to investigate:

### data/driver_ids.csv 
- **driver_id**: Unique identifier for a driver 
- **driver_onboard_date**: Date on which driver was onboarded 
### data/ride_ids.csv 
- **driver_id**: Unique identifier for a driver 
- **ride_id**: Unique identifier for a ride that the driver completed 
- **ride_distance**: Ride distance in meters 
- **ride_duration**: Ride durations in seconds 
- **ride_prime_time**: PrimeTime applied on the ride 
### data/ride_timestamps.csv 
- **ride_id**: Unique identifier for a ride 
- **event**: event describes the type of event (see below) 
- **timestamps**: Time of event 
