# AtliQ Hotel Data Analysis

![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-blue.svg)

A comprehensive exploratory data analysis (EDA) on AtliQ Hotel's booking data to uncover insights into occupancy rates, revenue patterns, and guest behavior. The project involved importing and cleaning the data, followed by generating meaningful insights through various analyses and visualizations.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Data Cleaning and Handling](#data-cleaning-and-handling)
- [Insights Generation](#insights-generation)
- [Results](#results)

## Introduction
This project focuses on analyzing booking data from AtliQ Hotels to derive actionable insights. The analysis covered various aspects, including occupancy rates, revenue trends, and guest booking patterns. The project was executed using Python, leveraging libraries like Pandas, Matplotlib, and Seaborn.

## Features
- **Data Import and Exploration:** Loaded and explored the dataset to understand its structure and contents.
- **Data Cleaning:** Addressed invalid guest entries, removed outliers using the formula `mean + 3*std`, and handled missing values.
- **Data Handling:** Calculated the occupancy percentage for each hotel and added it as a new column.
- **Insights Generation:** 
  - Calculated the average occupancy rate per room category and per city.
  - Compared occupancy rates between weekdays and weekends.
  - Analyzed occupancy rates for different cities in June.
  - Generated month-by-month revenue reports and visualized revenue realized per hotel type.
  - Created a pie chart to display revenue distribution across different booking platforms.

## Technology Stack
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## Data Cleaning and Handling
- **Invalid Entries:** Removed entries with invalid guest information.
- **Outlier Removal:** Used the formula `mean + 3*std` to identify and remove outliers.
- **Null Handling:** Addressed missing data by either filling or dropping null values.
- **Occupancy Percentage:** Added a new column to the dataset to represent the occupancy percentage for each booking.

## Insights Generation
- **Occupancy Analysis:**
  - **Room Categories:** Analyzed the average occupancy rate for each room category.
  - **City-wise Analysis:** Evaluated the average occupancy rate per city and compared occupancy rates between weekdays and weekends.
  - **June Analysis:** Focused on June to understand occupancy trends across different cities.
- **Revenue Analysis:**
  - **Monthly Revenue:** Visualized month-by-month revenue trends.
  - **Hotel Type Revenue:** Compared revenue realized across different hotel types.
  - **Booking Platform Revenue:** Created a pie chart to illustrate the revenue share of each booking platform.

## Results
The analysis provided valuable insights into the occupancy trends and revenue generation of AtliQ Hotels:
- **Occupancy Rates:** The average occupancy rate varied significantly across room categories and cities, with weekends generally showing higher occupancy.
- **Revenue Insights:** Monthly revenue trends were identified, along with the revenue contributions of different hotel types and booking platforms.

