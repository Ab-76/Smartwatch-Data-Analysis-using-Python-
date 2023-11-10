# Smartwatch Data Analysis

## Overview
This project involves the analysis of smartwatch data collected from 30 female users of Fitbit smartwatches. The dataset is publicly available on Kaggle and contains information about daily activity, including steps taken, distance traveled, active minutes, and calories burned.

## Tools Used
- Python
- Libraries: pandas, numpy, matplotlib, plotly

## Dataset Information
- **Columns:**
  - Id: User identifier
  - ActivityDate: Date of the recorded activity
  - TotalSteps, TotalDistance, TrackerDistance: Physical activity metrics
  - VeryActiveMinutes, FairlyActiveMinutes, LightlyActiveMinutes, SedentaryMinutes: Active minutes breakdown
  - Calories: Calories burned in a day

## Data Cleaning
- Checked for null values (none found).
- Converted "ActivityDate" column to datetime format.

## Descriptive Statistics
- Investigated key statistics of the dataset, including mean, min, max, and quartiles.
- Added a new column "TotalMinutes" as the sum of active minutes.

## Data Visualization

### 1. Relationship between Calories and Total Steps
- Plotted a scatter plot with a trendline to show the linear relationship.

### 2. Total Active Minutes Distribution
- Created a pie chart to visualize the distribution of very active, fairly active, lightly active, and sedentary minutes.

### 3. Active Minutes by Day of the Week
- Generated a bar chart to display very active, fairly active, and lightly active minutes for each day of the week.

### 4. Inactive Minutes by Day of the Week
- Presented a pie chart showcasing the distribution of sedentary minutes for each day of the week.

### 5. Calories Burned by Day of the Week
- Illustrated a pie chart indicating the distribution of calories burned for each day of the week.

## Findings
- A linear relationship exists between total steps and calories burned.
- Most individuals have a significant portion of inactive minutes in a day (81.3%).
- Tuesday appears to be the most active day, with the highest number of calories burned.

## Conclusion
This analysis provides insights into the activity patterns and calorie expenditure of individuals wearing Fitbit smartwatches. The visualizations help identify trends and patterns, enabling a better understanding of daily activity and potential areas for improvement in health and fitness.

For further details, refer to the Python script in this repository.
