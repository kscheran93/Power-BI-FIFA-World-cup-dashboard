Certainly! Here's a README for your GitHub repository:

---

# FIFA World Cup Dashboard

## Overview

This project leverages the FIFA World Cup dataset to create an insightful Power BI dashboard, focusing on the history of the FIFA World Cup from 1930 to 2014. The dashboard provides a comprehensive analysis of various aspects of the tournament, including attendance, competition statistics, countries qualified, World Cup winners, and host countries. The goal is to offer a detailed look into the historical data of the FIFA World Cup, making it easier for stakeholders to understand trends and key metrics across the years.

## Snapshot of Dashboard

![Dashboard_Snapshot](your_image_link_here)

### Dashboard Link: [https://app.powerbi.com/groups/me/reports/a07588b5-7a2e-4b4a-a438-f7f91b9490ad/e2191b154718a71d6834?experience=power-bi)

## Problem Statement

The FIFA World Cup dashboard is designed to provide key insights into the tournament's history. It allows users to explore various aspects of the World Cup, such as attendance figures, competition statistics, participating countries, and winners over the years. This information is vital for understanding the evolution of the tournament and identifying patterns or trends that have shaped the FIFA World Cup.

## Data Sources

The dataset used in this project is sourced from Kaggle and includes the following files:

- **WorldCupMatches.csv:** Contains match-level data from 1930 to 2014.
- **WorldCups.csv:** Includes overall tournament data for each World Cup held between 1930 and 2014.
- **WorldCupPlayers.csv:** Provides player-level data for the World Cups during the specified period.

### Dataset Link: [Kaggle - FIFA World Cup Dataset](https://www.kaggle.com/datasets/abecklas/fifa-world-cup?select=WorldCupMatches.csv)

## Steps Followed

- **Step 1:** Imported the dataset into Power BI Desktop.
- **Step 2:** Cleaned and prepared the data using Power Query Editor, focusing on ensuring data integrity and handling missing values.
- **Step 3:** Created visualizations to highlight different aspects of the FIFA World Cup data:
  - **Tree Map:** Displays attendance by country and year.
    - **Location:** `country`
    - **Legend:** `attendance`
  - **Stacked Column Chart:** Shows competition statistics by year, including goals scored, matches played, and qualified teams.
    - **X-Axis:** `year`
    - **Y-Axis:** Sum of `goals scored`, `matches played`, and `QualifiedTeams`
  - **Horizontal Bar Chart:** Displays the number of times each country qualified for the World Cup.
    - **Y-Axis:** `team`
    - **X-Axis:** Count of `year`
  - **Doughnut Chart:** Illustrates the distribution of World Cup winners.
    - **Legend:** `winner`
    - **Values:** Count of `winner`
    - **Tooltip:** `first year`
  - **Horizontal Bar Chart:** Highlights the countries that have hosted the World Cup.
    - **Y-Axis:** `country`
    - **X-Axis:** Count of `country`
- **Step 4:** Added text boxes to provide context for the data and insights.
- **Step 5:** Designed and formatted the dashboard to ensure a user-friendly and visually appealing layout.
- **Step 6:** Published the dashboard to Power BI Service for sharing and broader accessibility.

## Insights

The FIFA World Cup dashboard reveals several key insights into the tournament's history:

### [1] Attendance by Country and Year
   - The tree map visualization highlights the distribution of attendance figures across different countries and years, providing an understanding of how audience engagement has varied.

### [2] Competition Statistics by Year
   - The stacked column chart presents a summary of goals scored, matches played, and the number of qualified teams each year, offering insights into the tournament's competitive aspects.

### [3] Countries Qualified for the World Cup
   - The horizontal bar chart shows which countries have qualified for the World Cup most frequently, highlighting the dominance or consistent performance of certain teams.

### [4] World Cup Winners
   - The doughnut chart visualizes the number of times each country has won the World Cup, providing a quick reference to the most successful teams in World Cup history.

### [5] Countries Hosted the World Cup
   - The horizontal bar chart shows the countries that have hosted the World Cup, indicating the geographical spread and frequency of hosting.

## Conclusion

This FIFA World Cup Power BI dashboard serves as a powerful tool for analyzing the tournament's history from 1930 to 2014. It allows users to explore key metrics and trends, making it easier to gain insights into the evolution and impact of the FIFA World Cup over the decades.

---

You can customize this README further by adding your own images, additional links, or any other specific details relevant to your project.
