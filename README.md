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

## 📊 Key Questions Analyzed:
1. How many unique start and stop locations are there?
2. What are the most frequently used start and stop locations?
3. What is the most frequent route taken?
4. What is the highest route speed recorded?

## 🔍 Project Execution & Analysis:
1️⃣ Data Cleaning & Transformation
- Extracted time from date-time columns using the formula:
- ![image](https://github.com/user-attachments/assets/cff358f0-55b0-4a05-ad63-30ec2152ac92)
- Used Text to Columns (Fixed Width) in Excel for cases where automatic extraction failed.
- Created separate date and time columns for better analysis.

2️⃣ Trip Duration Calculation
- Used an IF formula to handle trips that crossed midnight:
- ![image](https://github.com/user-attachments/assets/52ca241e-e92e-46b3-81d4-2cdffe81cf25)

- Converted trip duration to hours for readability:
- ![image](https://github.com/user-attachments/assets/ca69ff11-d224-4490-a671-383bfeee46b4)

3️⃣ Speed Calculation & Outlier Removal
- Calculated speed using:
- ![image](https://github.com/user-attachments/assets/eb15067c-1dc8-45b7-b6ba-a8b4b509de80)
- Removed unrealistic speed values (>160 km/h) to ensure data accuracy.

4️⃣ Data Analysis & Insights
- Found the most frequent start and stop locations.
- Determined the most popular routes.
- Identified the fastest route in the dataset.

## 📈 Project Insights
- Total Unique Start Locations: 177
- Total Unique Stop Locations: 188
- Most Frequent Start Location: Home
- Most Frequent Stop Location: Home
- Most Frequent Route: Home → Work
- Highest Speed Route: Cary → Morrisville

## 🛠 Skills Utilized
1. Data Cleaning (Extracting time, date, handling missing values)
2. Data Transformation (Splitting columns, using formulas)
3. Excel Formulas & Functions (IF, HOUR, MINUTE, Text to Columns)
4. Data Validation & Outlier Removal (Filtering incorrect speed values)
5. Data Analysis & Insights (Identifying patterns, frequency analysis)
6. Visualization & Reporting (Summarizing findings)

## 🎯 Final Conclusion
This project successfully cleaned, transformed, and analyzed Uber trip data using Excel. By leveraging formulas, functions, and data validation techniques, we extracted meaningful insights about commuting behavior.
