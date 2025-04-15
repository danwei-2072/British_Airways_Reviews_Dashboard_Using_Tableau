# British Airways Review Analysis Dashboard

## Overview

This repository contains a Tableau project analyzing customer reviews for British Airways. The interactive dashboard explores various aspects of the passenger experience based on review data collected from March 2016 to October 2023. It allows users to visualize trends and comparisons across different metrics, time periods, traveller demographics, aircraft types, and geographical locations.

## Dashboard Preview

![British Airways Review Dashboard](https://github.com/danwei-2072/British_Airways_Reviews_Dashboard_Using_Tableau/blob/main/British_airways_Review.png)

The dashboard currently displays analysis focused on **Average Cabin Staff Service**, filtered for **Solo Leisure** travellers across **all Seat Types** within **Europe**.

## Key Features & Visualizations

The dashboard (`British_airways_Review.twbx`) includes the following components:

1.  **Key Performance Indicators (KPIs):** Displays overall average scores for:
    *   Overall Rating
    *   Cabin Staff Service
    *   Entertainment
    *   Food Beverages
    *   Ground Service
    *   Seat Comfort
    *   Value For Money

2.  **Average Metric By Month:** A line chart showing the trend of the selected metric (e.g., Cabin Staff Service) over time (March 2016 - October 2023). This helps identify seasonality or changes in performance over the years.

3.  **Average Metric By Country:** A map visualization (currently focused on Europe) showing the average rating of the selected metric shaded by country. Darker shades indicate higher average ratings.

4.  **Average Metric By Aircraft:** A dual-axis chart showing:
    *   A bar chart for the average rating of the selected metric broken down by aircraft type.
    *   A corresponding bar chart showing the number of reviews received for each aircraft type, providing context to the average ratings.

## Interactivity & Filters

Users can customize the view using the following filters:

*   **Pick a metric:** Select the core review aspect to analyze across the dashboard (Overall Rating, Cabin Staff Service, etc.).
*   **Month of Date:** Adjust the date range for the analysis (default: March 2016 - October 2023).
*   **Traveller Type:** Filter reviews based on the type of traveller (e.g., Business, Solo Leisure, Couple Leisure, Family Leisure).
*   **Seat Type:** Include or exclude reviews based on the class flown (e.g., Business Class, Economy Class, First Class, Premium Economy).
*   **Continent:** Filter reviews based on the geographical region (e.g., Europe).
*   **Aircraft (group) 1:** Filter by specific aircraft types or groups.

## Data Source

The analysis is based on three datasets containing anonymized customer review data for British Airways flights:

1.  `airlines_reviews.csv`
2.  `ba_reviews.csv`
3.  `Countries.csv`


The data covers the period from **March 2016 to October 2023**.

## Technology Used

*   **Tableau Desktop / Tableau Public:** Used for data visualization and dashboard creation.

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/danwei-2072/British_Airways_Reviews_Dashboard_Using_Tableau
    cd British_Airways_Reviews_Dashboard_Using_Tableau
    ```
2.  **Open the Dashboard:**
    *   You need Tableau Desktop or the free Tableau Reader installed.
    *   Open the `British_airways_Review.twbx` file.
    *   Tableau Packaged Workbooks (`.twbx`) contain the dashboard, worksheets, and the data extract, so no separate connection setup is required.
3.  **Explore:** Interact with the filters and visualizations to explore the British Airways review data.

## Files in this Repository

*   `British_airways_Review.twbx`: The main Tableau Packaged Workbook file containing the dashboard and data.
*   `airlines_reviews.csv`
*   `ba_reviews.csv`
*   `Countries.csv`
*   `README.md`: This file.

