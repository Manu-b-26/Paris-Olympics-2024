# Paris-Olympics-2024

## Overview
This project provides insights into the Paris 2024 Olympic Summer Games dataset, encompassing various aspects of the event, such as athletes, teams, events, venues, schedules, and medal statistics. The analysis includes data cleaning, merging, and visualization to uncover significant trends and patterns related to performance, participation, and event distribution.

## Key Insights
### 1. Top Medal-Winning Disciplines
- Identified the top 20 disciplines based on medal wins.
- Highlights the most competitive and rewarding events.
### 2. Event Timeline Analysis
- Visualized event distribution across the games' timeline.
- Identifies peak activity days for better event planning.
### 3. Torch Relay Visualization
- Analyzed and plotted the top 20 cities involved in the torch relay route.
- Highlights the relay's geographical coverage and cultural significance.
### 4. Team Performance
- Merged team and medal data to rank the top 20 performing teams.
- Provides insights into team efficiency and dominance.
### 5. Medal Win Rates by Country
- Calculated medal win rates relative to the number of athletes from each country.
- Showcased the top-performing nations based on efficiency.
### 6. Coach-to-Athlete Ratio
- Analyzed the ratio of coaches to athletes by country.
- Highlights the resource allocation efficiency for athlete support.
### 7. Medal Distribution Heatmap
- Created a heatmap to visualize medal distribution by discipline and country.
- Highlights areas of dominance and diversity in medal acquisition.

## Data Cleaning and Preprocessing
- Converted multi-value columns like disciplines and events into singular rows using Python's explode() method.
- Standardized column formats and removed inconsistencies.
- Merged datasets like athletes, medals, and events for comprehensive analysis.

## How to Use
- *Visualization:* The dataset is ideal for creating visual analytics using libraries like Matplotlib and Seaborn.
- *Insights:* Gain actionable insights into event planning, team efficiency, and medal performance.
- *Exploration:* Extend the analysis to other aspects such as venue capacity or athlete demographics.

## Tools and Libraries
- *Data Analysis:* Pandas, NumPy
- *Visualization:* Matplotlib, Seaborn
- *Advanced Cleaning:* Python’s ast module for handling complex data structures

## Acknowledgements
Dataset Source: Kaggle - Paris 2024 Olympic Summer Games Dataset
