# Bellabeat-Smart-Device-Usage-Data-Analysis-Capstone-Project

Bellabeat Wellness Technology Case Study - Data Analysis
Project Overview
This project analyzes Fitbit fitness tracker data to uncover user behavior trends and deliver actionable insights for the marketing strategy of Bellabeat’s Leaf wellness product. The analysis follows the Bellabeat case study framework, demonstrating fundamental data analytics skills including data cleaning, exploratory data analysis, clustering, correlation studies, and trend analysis.

Key Deliverables
Clear statement of the business task and objectives

Description and preparation of Fitbit datasets

Comprehensive data cleaning and preprocessing documentation

Exploratory and advanced analysis with visualizations

Key findings and marketing strategy recommendations

Elevator pitch script summarizing insights for Bellabeat executives

Getting Started
Prerequisites
Make sure you have Python 3.x installed along with the required libraries:

bash
pip install pandas numpy matplotlib seaborn scikit-learn
Dataset
The analysis uses several Fitbit datasets. Download and place the following CSV files in the project directory:

dailyActivity_merged.csv

hourlyCalories_merged.csv

hourlyIntensities_merged.csv

hourlySteps_merged.csv

heartrate_seconds_merged.csv

minuteCaloriesNarrow_merged.csv

minuteIntensitiesNarrow_merged.csv

minuteMETsNarrow_merged.csv

minuteSleep_merged.csv

minuteStepsNarrow_merged.csv

weightLogInfo_merged.csv

Running the Analysis
Run the main Python script to perform data cleaning, exploratory data analysis, clustering, and visualization:

bash
python final.py
The script outputs cleaned data, analysis results, and visualizations to support the Bellabeat marketing strategy case study.

File Structure
final.py — Main Python analysis script

cleaned_daily_activity.csv — Example cleaned dataset output

visualizations/ — Folder containing generated charts and figures (if applicable)

Summary of Methods
Data ingestion and integration of Fitbit datasets

Cleaning and preprocessing including missing data and duplicates

Descriptive statistics and visualizations (histograms, scatter, boxplots)

Correlation matrix and clustering (K-means) analysis

Time series trends and sedentary vs active behavior insights
