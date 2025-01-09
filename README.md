# AirBnB Listing Analysis

Welcome to my project analyzing AirBnB listings in Paris! This analysis explores how recent regulations have impacted host activity and listing prices. The dataset includes detailed information on over 250,000 AirBnB listings from 10 major cities and nearly 5 million guest reviews. My focus is on Paris, where I investigate pricing, hosting, and accommodations trends.

---
## About This Project

This analysis is part of a guided project from [Maven Analytics](https://app.mavenanalytics.io/guided-projects/4fee7ee7-4c04-46e7-9f3e-99b987980842). The project provided a structured approach to explore, analyze, and visualize AirBnB listings data while enhancing my Python and data analysis skills.

## Project Objectives

### 1. Data Profiling and Quality Assurance
I began by profiling and cleaning the dataset to focus exclusively on Paris listings. This involved:
- Importing and examining the `listings.csv` file.
- Casting date columns to a datetime format for easier analysis.
- Filtering the data to retain only Paris listings and keeping relevant columns:
  - `host_since`
  - `neighbourhood`
  - `city`
  - `accommodates`
  - `price`
- Performing QA checks, including identifying missing values and calculating basic statistics (minimum, maximum, and average) for numeric fields.

### 2. Data Preparation for Visualization
Next, I prepared the data for visualizations by aggregating and grouping it in meaningful ways:
- **Neighborhood Analysis**: Grouped listings by `neighbourhood` and calculated the mean price, sorted from low to high.
- **Accommodation Analysis**: Focused on Paris' most expensive neighborhood, grouped by `accommodates`, and calculated the mean price for each accommodation type.
- **Host Trends Over Time**: Grouped listings by the `host_since` year to calculate the average price and count of new hosts.

### 3. Visualizations and Insights
Finally, I built visualizations to summarize my findings:
- A horizontal bar chart of average prices by neighborhood.
- A horizontal bar chart of average prices by accommodation type in Paris’ most expensive neighborhood.
- Two line charts:
  - The number of new hosts over time.
  - The average price over time.
- A dual-axis line chart (bonus) showing new hosts and average price over time.

---

## Key Insights

- **Neighborhood Pricing**: Certain neighborhoods in Paris are significantly more expensive, reflecting differences in demand and location appeal.
- **Accommodation Trends**: Listings that accommodate more people generally have higher prices, but some exceptions exist in the most expensive neighborhood.
- **Host Growth and Pricing**: The number of new hosts and listing prices have fluctuated over time, particularly after the 2015 regulations. This analysis provides insights into how these regulations influenced host behavior and listing economics.

---

## Tools Used

- **Programming Language**: Python
- **Libraries**: pandas, matplotlib, seaborn
- **Visualization**: Horizontal bar charts, line charts, and dual-axis charts

---

## Dataset Details

The dataset is sourced from [Inside Airbnb](http://insideairbnb.com/) and is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). It contains:
- **250,000+ listings** from 10 cities
- **~5 million guest reviews**
- **36 fields** in the listings data

---

## Future Plans

While this project focuses on Paris, I plan to extend the analysis to other cities and explore additional dimensions of the dataset, such as guest reviews and host response rates. Stay tuned!

---

## How to Use This Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/airbnb-analysis.git
