# NYC Motor Vehicle Collisions Dashboard

## Overview

This repository contains the Power BI dashboard for analyzing motor vehicle collisions in New York City. The dashboard aims to provide insights into accident trends, injury and fatality rates, and collision causes, leveraging NYC motor vehicle collision data. The insights derived from this dashboard can be used by city planners, policymakers, and transportation authorities to improve road safety and implement better traffic management strategies.

## Problem Statement

New York City experiences a significant number of motor vehicle collisions every year, leading to injuries and fatalities, especially among pedestrians and cyclists. The objective of this analysis is to uncover patterns in these incidents, identify high-risk time periods and locations, and explore the roles of different vehicle types in contributing to these accidents. Through a detailed examination of accident causes and their impact on various road users, this dashboard serves as a tool for understanding and mitigating traffic accidents across the city.

## Business Questions Addressed
The dashboard provides answers to several critical questions, including:

1. **How many car accidents occur annually in NYC?**
2. **Which NYC boroughs have the most collisions?**
3. **When do the majority of collisions occur?**
4. **Which boroughs experience the most fatal accidents?**
5. **What are the top causes of collisions?**
6. **How often are pedestrians, cyclists, and motorcyclists involved in collisions?**
7. **Are trucks frequently involved in NYC accidents?**
8. **What time of day and week see the highest rates of accidents?**

## Features

The Power BI dashboard includes:
- **Interactive Maps** showing the distribution of collisions across boroughs and high-risk zones.
- **Trend Analysis** for collisions over time, broken down by season, year, and time of day.
- **Vehicle Involvement Breakdown**, highlighting the types of vehicles involved in accidents (cars, motorcycles, trucks, etc.).
- **Fatality and Injury Reports**, detailing how many people were injured or killed in collisions, categorized by role (pedestrian, driver, cyclist).
- **Collision Causes**, identifying the top contributing factors to collisions.
  
## [Data Sources](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data)

The analysis uses the following data sources:
- **NYC Motor Vehicle Collision Data**: This dataset contains detailed information about collisions, including the number of people injured or killed, vehicle types, accident causes, and timestamps.

## Requirements

- **Power BI Desktop** for local editing and customization of the dashboard.
- A **Power BI Service Account** if publishing to the Power BI cloud for sharing and collaboration.

## How to Use

1. **Clone this repository** to your local machine:
   ```bash
   git clone https://github.com/your-repo/nyc-collisions-dashboard.git

2. Open Power BI Desktop and load the provided `.pbix` file from the repository.
3. If needed, refresh the data by connecting to the NYC motor vehicle collisions dataset. 
  (Link to Dataset: https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data)
4. Explore the dashboard using the provided visuals, filters, and slicers to answer key business questions.
5. Customize any visualizations as per your specific needs.

## Customization

Feel free to modify the following aspects of the dashboard:

- **Visualizations**: Adjust or add visualizations such as bar charts, scatter plots, or tree maps to fit your analysis preferences.
- **Filters**: Add additional filters or slicers to refine the data by time of day, vehicle type, borough, etc.
- **Themes**: Modify the Power BI theme to match your organization's branding or visual preferences.

## Contributions

We welcome contributions to improve this dashboard. Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request for review.

## License

This repository is licensed under the MIT License. See `LICENSE` for more details.

## Contact

For any questions or feedback, please open an issue or contact [charmidparmar@gmail.com](mailto:charmidparmar@gmail.com).

---

**Note**: This dashboard uses publicly available NYC motor vehicle collision data, which may be subject to updates. Please ensure to refresh your data periodically to maintain accurate and up-to-date insights.

