# Hotel Booking Cancellation EDA

## Overview
This project performs an Exploratory Data Analysis (EDA) on the **Hotel Booking Cancellation Dataset** from Kaggle. The dataset contains information about hotel bookings, including whether they were canceled or honored. The goal of this analysis is to uncover patterns, trends, and insights related to booking cancellations, as well as to visualize key aspects of the data.

## Dataset Description
The dataset includes the following key features:
- **hotel**: Type of hotel (Resort Hotel or City Hotel).
- **is_canceled**: Whether the booking was canceled (1 = Yes, 0 = No). This is the target variable.
- **lead_time**: Number of days between booking and arrival.
- **arrival_date_year/month/day**: Date of scheduled arrival.
- **stays_in_weekend_nights & stays_in_week_nights**: Duration of stay.
- **adults, children, babies**: Number of guests.
- **meal**: Type of meal package booked (e.g., BB = Bed & Breakfast).
- **country**: Customer's country of origin.
- **market_segment**: Booking channel (e.g., Online TA, Direct, Corporate).
- **deposit_type**: Deposit policy (No Deposit, Refundable, Non-Refundable).
- **customer_type**: Type of guest (Transient, Contract, Group).
- **adr**: Average daily rate (price per night).
- **required_car_parking_spaces**: If parking was requested.
- **total_of_special_requests**: Additional guest preferences.

## Objectives
1. **Understand the dataset**: Explore the structure, missing values, and basic statistics.
2. **Analyze cancellations**: Identify factors influencing booking cancellations.
3. **Visualize trends**: Create plots to highlight distributions, correlations, and anomalies.
4. **Derive insights**: Provide actionable insights for hotel management to reduce cancellations.

## Key Findings
- **Cancellation Rates**: Visualized the cancellation rates by hotel type, revealing differences between Resort and City Hotels.
- **Temporal Analysis**: Explored trends in cancellations over time, identifying peak cancellation periods.
- **Correlations**: Investigated relationships between lead time, deposit type, and cancellations.
- **Anomalies**: Detected unusual patterns in booking behavior, such as extreme lead times or unusual guest counts.

## Tools Used
- **Python**: Primary programming language for analysis.
- **Pandas**: Data manipulation and cleaning.
- **Matplotlib/Seaborn**: Data visualization.
- **Jupyter Notebook**: Interactive environment for code execution and documentation.

## Visualizations
- **Cancellation Overview**: Bar plot showing cancellation rates by hotel type.
- **Temporal Analysis**: Line plots or histograms displaying cancellations over time.
- **Correlation Heatmap**: Highlighting relationships between numerical features.
- **Anomaly Detection**: Box plots or scatter plots to identify outliers.

## Insights
- **Resort vs. City Hotels**: Resort hotels may have lower cancellation rates compared to city hotels.
- **Lead Time Impact**: Longer lead times might correlate with higher cancellation rates.
- **Deposit Policy**: Non-refundable deposits could reduce cancellations.
- **Seasonal Trends**: Cancellations may spike during certain months or events.

## Future Work
- **Predictive Modeling**: Build a machine learning model to predict cancellations.
- **Feature Engineering**: Create new features (e.g., seasonality, customer segments) for deeper analysis.
- **A/B Testing**: Test strategies (e.g., deposit policies) to reduce cancellations.

## Dataset Source
The dataset is available on Kaggle: [Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand).

## Author
[Nikul] - [Your Contact Information]
