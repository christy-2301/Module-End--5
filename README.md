# Social Media Engagement Analytics Using Python

## Project Overview
This project analyzes social media engagement data using Python to understand content performance, user behavior, and factors that influence audience engagement.

The analysis uses data from 5,000 social media records and applies data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization.

## Objectives
- Analyze engagement across different post types and categories.
- Identify countries with higher average engagement rates.
- Understand the relationship between age and engagement.
- Compare engagement between verified and non-verified accounts.
- Analyze device usage and watch time.
- Explore how sentiment relates to engagement.

## Dataset Overview
- **Dataset:** `social_media_engagement_5000.csv`
- **Total Records:** 5,000
- **Original Columns:** 19

The dataset includes information about users, posts, likes, comments, shares, impressions, watch time, countries, devices, sentiment, and engagement rates.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Cleaning and Preparation
The following steps were performed:

- Checked and handled missing values.
- Filled missing numerical values using the median.
- Filled missing categorical values using the mode.
- Checked and removed duplicate records where necessary.
- Converted the `age` column into an appropriate numeric format.
- Converted `posted_at` into datetime format.
- Standardized categorical values.
- Created a new `hashtag_count` column.
- Created an `engagement_score` column using likes, comments, and shares.

**Engagement Score = Likes + Comments + Shares**

## Exploratory Data Analysis

### 1. Content Performance
- Video posts recorded the highest average engagement score (12,664.59).
- Music was the best-performing content category (12,788.55).
- Brazil recorded the highest average engagement rate (1.54).

### 2. User Trends
- Age showed a very weak relationship with engagement.
- The 13–17 age group recorded slightly higher average engagement.
- Non-verified accounts had a higher average engagement score (12,644.31) than verified accounts (12,309.28).

### 3. Behavioral Insights
- Mobile users recorded the highest average watch time (4,087.83 seconds).
- Tuesday recorded the highest average impressions.
- The dataset contained dates but no exact posting times, so the best time of day could not be determined.

### 4. Sentiment Analysis
- Negative-sentiment posts recorded the highest average engagement score (12,731.50).
- Positive-sentiment posts followed (12,665.80).
- Neutral-sentiment posts recorded the lowest average engagement score (12,448.16).

## Key Learnings
- Practiced data cleaning and preprocessing using Pandas.
- Used NumPy for numerical operations.
- Performed grouping, aggregation, and statistical analysis.
- Created visualizations using Matplotlib and Seaborn.
- Learned to interpret engagement patterns and communicate data-driven insights.

## Conclusion
This project demonstrates how Python can be used to transform raw social media data into meaningful insights. The analysis helped identify patterns in content performance, audience behavior, device usage, and sentiment. It also highlighted the importance of data quality and understanding dataset limitations when drawing conclusions.

## Project Deliverables
- Python analysis notebook
- Data visualizations
- Project findings and summary report

drive link : https://drive.google.com/drive/folders/1Myjr8uTX5s2jdNLyiYLvPHU4ANDm3Gz6?usp=sharing
