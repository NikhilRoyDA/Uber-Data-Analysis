# Uber-Data-Analysis

## 🚀 Project Overview:
This project analyzes Uber trip data using Excel to uncover travel patterns, trip durations, speeds, and popular routes. The dataset is cleaned, transformed, and analyzed to gain valuable insights into commuting behavior.

## 📌 Project Objective:
The main objective of this project is to analyze Uber trip data by performing:

- Data Cleaning & Transformation to prepare raw data for analysis.
- Trip Duration & Speed Calculation to evaluate trip efficiency.
- Identifying Patterns & Trends such as the most frequent start/stop locations.
- Detecting Anomalies & Outliers (e.g., unrealistic speed values).
- Drawing Actionable Insights to understand ride behavior better.

## 📊 Key Questions (KPIs) Analyzed:
1. How many unique start and stop locations are there?
2. What are the most frequently used start and stop locations?
3. What is the most frequent route taken?
4. What is the highest route speed recorded?

🔍 Project Execution & Analysis
1️⃣ Data Cleaning & Transformation
Extracted time from date-time columns using the formula:
excel
Copy
Edit
=A2 - INT(A2)
Used Text to Columns (Fixed Width) in Excel for cases where automatic extraction failed.
Created separate date and time columns for better analysis.
2️⃣ Trip Duration Calculation
Used an IF formula to handle trips that crossed midnight:
excel
Copy
Edit
=IF(F2 > C2, F2 - C2, F2 - C2 + 1)
Converted trip duration to hours for readability:
excel
Copy
Edit
=(HOUR(H2) * 60 + MINUTE(H2)) / 60
3️⃣ Speed Calculation & Outlier Removal
Calculated speed using:
excel
Copy
Edit
=L2 / I2
Removed unrealistic speed values (>160 km/h) to ensure data accuracy.
4️⃣ Data Analysis & Insights
Found the most frequent start and stop locations.
Determined the most popular routes.
Identified the fastest route in the dataset.
