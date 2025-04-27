# Analyzing Data on Bicycle Rental

**Case study**: Cyclistic  
**Author**: Kolomiiets Ruslan  
**Date**: 2025-03-20

---

## Project Overview

Cyclistic operates 692 bike sharing stations across Chicago. Customers can unlock bikes from one station and return them to any other.  
There are two types of customers:
- **Casual users**: Single-ride or full-day pass buyers
- **Annual members**: Subscribers with annual passes

Cyclistic’s financial team concluded that **annual members are more profitable**. Therefore, the marketing strategy aims to **convert casual users into annual members**.

The objective of this project is to understand the behavior differences between annual members and casual users and to identify strategies to support this business goal.

---

## Statement of Work

- **Purpose**: Developed as part of the Google Data Analytics Professional Certificate program.
- **Data Analyst**: Ruslan Kolomiiets
- **Client**: Cyclistic bike-share company
- **Research Objective**:  
  > *Do annual members and casual riders use Cyclistic bikes differently?*

### Scope / Major Activities
- Data collection, cleaning, and preparation
- Analysis of parameters and trend identification
- Forecasting growth scenarios
- Drawing conclusions and communicating findings

### Out of Scope
- Research beyond the task description
- Unapproved forecasts or statistical modeling beyond basic needs
- Complex statistical calculations

---

## Business Task

**Main Question**:  
> *What is the difference in bike usage between annual users and occasional customers?*

**Analysis Focus**:
- User type (Subscriber or Customer)
- User age
- User gender (Male, Female)
- Trip duration
- Trip type (One-way or Return to start station)
- Day of the week (weekday/weekend)
- Time of day
- Month of the year

---

## Data and Sources

**Data Source**:  
- Divvy’s public bike-sharing travel data (2019), provided under the Divvy Data License Agreement.

**Data Characteristics**:
- Period covered: Full year of 2019
- Quarterly CSV files
- No confidential or sensitive information

**Key Columns**:
- `trip_id`: Unique trip identifier
- `start_time`, `end_time`: Trip start and end timestamps
- `bikeid`: Bike ID
- `tripduration`: Trip duration
- `from_station_id`, `from_station_name`: Start station details
- `to_station_id`, `to_station_name`: End station details
- `usertype`: User type (Subscriber or Customer)
- `gender`: User gender
