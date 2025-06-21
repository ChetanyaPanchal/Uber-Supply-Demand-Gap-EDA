# Uber-Supply-Demand-Gap-EDA
This project aims to analyze Uber ride request data to understand and address the supply-demand gap in a metropolitan area. The dataset includes thousands of ride requests along with associated details like timestamps, driver availability, pickup locations, and trip status.

# Dataset Overview
Request id: Unique identifier for each ride request

Pickup point: Indicates if the request was from the city or airport

Status: Status of the ride (e.g., Completed, Cancelled, No Cars Available)

Request timestamp & Drop timestamp: Times of request and drop

Driver id: Unique identifier for the driver (if assigned)

# Key Analyses and Visualizations
Our analysis highlighted that Uber's peak demand occurs during the Morning Rush (5–9 AM) and Evening Rush (5–9 PM). However, these are also the periods where Uber struggles the most to meet customer demand—either due to driver cancellations (especially in the City) or lack of available vehicles (especially at the Airport). These inefficiencies result in a significant number of unfulfilled ride requests, which can lead to negative customer experiences and loss of business.

The findings also showed that request behavior remains consistent across dates, meaning Uber can rely on historical trends to predict future demand. Our time slot classification and correlation analysis confirmed that hourly ride request patterns do not vary significantly with dates, allowing for more effective demand forecasting.

# Business Insights
Incentivize Drivers during rush hours to operate in high-demand zones (e.g., Airport in the morning)

Real-time Demand Prediction models can be used to forecast and match supply dynamically

Introduce Pooling or Scheduling Features to better manage demand surges

Penalty & Reward System to reduce driver cancellations and increase trip completions

# Recommendations
We recommended several strategic solutions, including targeted driver incentives, predictive scheduling, ride-pooling, and zone-specific planning. Implementing these strategies would not only help close the supply-demand gap but also enhance customer satisfaction and operational efficiency.

# Problem Statement
Uber is facing a major supply-demand gap during key hours of operation, where many user ride requests are either cancelled or remain unfulfilled due to the unavailability of drivers. This negatively affects customer satisfaction and driver efficiency. The goal is to analyze historical ride request data to uncover patterns that lead to this gap and propose data-driven strategies to resolve it.

# Business Objective
The business objective is to identify time slots, locations, and patterns where ride requests remain unfulfilled and suggest operational improvements. These insights should help Uber improve driver allocation, reduce cancellations, and ultimately enhance the customer experience and operational efficiency.
