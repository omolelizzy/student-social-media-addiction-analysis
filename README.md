# Student-Social-Media-Addiction-Analysis
Analysis of students’ social media usage, sleep patterns, and addiction indicators using Excel
# Student Social Media Usage and Addiction Analysis

## Project Overview
This project explores students’ social media usage patterns and examines how usage intensity and addiction levels relate to sleep duration and mental health. The objective is to transform cleaned survey data into actionable insights that highlight behavioral risks associated with excessive social media use.
The project was completed in two stages:
1. Data cleaning and preparation
2. Exploratory and behavioral analysis

## Business Problem
With increasing reliance on social media among students, there is growing concern about its impact on sleep quality, mental well-being, and addictive behavior. This analysis aims to identify usage thresholds and behavioral patterns that may negatively affect students, providing data-driven insights that can inform awareness campaigns, student support services, and policy discussions.

## Dataset
- The dataset consists of survey responses from students and includes:
- Demographic information (age, gender, academic level, country)
- Average daily social media usage
- Most used social media platform
- Sleep duration
- Mental health scores
- Addiction and conflict indicators.
Each row represents one student respondent.

## Tools Used
1. Microsoft Excel – data cleaning, validation, and feature creation
2. Python (pandas, matplotlib, seaborn) – exploratory analysis and visualization
3. SQL – descriptive statistics and demographic analysis

## Data Cleaning & Preparation
1. Data cleaning was performed in Excel using clearly defined rules:
2. Removed records with missing critical fields such as student ID and daily usage
3. Standardized categorical values (gender, academic level, platforms)
4. Validated numeric ranges for usage hours, sleep duration, and scores
5. Removed duplicates
6. Created derived columns including:
     - Usage category (Low, Moderate, High)
     - Sleep category
     - Addiction level

## Data Validation & Quality Checks
Pivot tables and summary statistics were used to validate logical relationships across variables such as:
   - Usage category vs sleep duration
   - Addiction level vs mental health score
   - Academic level vs usage patterns
   - Any anomalies identified during validation were traced back to the source data and corrected.

## Exploratory & Behavioral Analysis
The exploratory analysis focused on:
 - Distribution of daily social media usage
 - Platform popularity across demographics
 - Usage differences by gender and academic level
 - Relationships between usage, sleep duration, mental health, and addiction levels
- Visualizations included bar charts, boxplots, scatterplots, and correlation heatmaps.

## Key Insights
- Students with higher social media usage tend to sleep fewer hours and exhibit more irregular sleep patterns compared to low-usage students.
- There is a strong negative relationship between daily social media usage and mental health scores, especially among students with high addiction levels.
- Addiction score shows the strongest negative association with mental health, indicating that addictive behavior is a key driver of poor well-being outcomes.
- Adequate sleep is positively associated with better mental health, reinforcing the role of sleep as a protective factor.
- Heavy usage and high addiction levels cluster together, highlighting a high-risk student group.

## Conclusion
The analysis demonstrates that excessive and addictive social media usage is linked to reduced sleep quality and poorer mental health outcomes among students. By combining behavioral patterns with demographic insights, this project shows how data can be used to identify risk groups and support evidence-based decision-making.

## Output
- Cleaned and validated dataset
- Exploratory visualizations illustrating behavioral trends.
- SQL-ready data structure for further analysis or dashboard development.
- Jupyter Notebook documenting code, analysis, and insights.

