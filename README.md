# Exploratory-Data-Analysis-Viewership-Dataset
## Databricks Notebooks
You can access the databricks notebook for the EDA using the link below:
[view on databricks] (https://dbc-3585e9bf-7c57.cloud.databricks.com/editor/notebooks/852575783857406?o=3909121773184344)
## OVERVIEW
# 📊 Viewership Data Analysis
This repository contains viewership data for exploratory data analysis (EDA) and visualization using **Python, and Databricks**. The dataset provides insights into customer engagement, platform usage, and video consumption patterns.
## 📂 Dataset Description
The dataset includes the following fields:

* **DateID** – Date of activity (YYYYMMDD format)

* **CustomerID** – Unique identifier for each customer

* **TotalTimeWatched** – Total viewing time in minutes

* **Platform** – Device or platform used (e.g., Leanback,iOS, web, Android

* **PlayEventType** – Type of playback event (e.g., such as LiveTV, CatchUp)

* **VideoTitle** – Title of the video watched

## 📂Transformed Data

### Transformed Data

After data cleaning and transformation, the dataset is ready for analysis. The following steps were applied:

- **Duplicates removed:** Ensured only unique rows remain for accurate analysis.
  
- **Data type conversion:** `TotalTimeWatched` converted to numeric (`double`) and `DateID` converted to date format.
  
- **Malformed values handled:** Rows with invalid `TotalTimeWatched` were removed.
  
- **Derived columns added:**
  - **TotalTimeWatched_Hours** – total watch time converted from minutes/seconds to hours.

  - **DayOfWeekName** – day of the week for each record in full name format (e.g., Monday, Tuesday).

This transformed dataset provides a clean and structured foundation for **time trend analysis, customer behavior analysis, and visualization** on Databricks using Python.

## 🎯 Purpose
* Clean and preprocess raw viewership data
* Identify and remove missing values and duplicates
* Perform customer-level analysis (e.g., engagement trends, active users)
* Create time-series visualizations of watch behavior
* Explore insights using Databricks notebooks
  
## 🛠️ Technologies Used

**Databricks** – Cloud-based data analysis and visualization

**Python** - Used as a programming language to transform, clean, and visualize viewership data

**Pandas & NumPy** – Libraries used for Data wrangling and manipulation

**Matplotlib & Seaborn** – Data visualization - to be used visuals in the next phase

## 🚀 Next Steps

In the next phase, visual analysis and advanced insights will be developed once we have been taken through the matplotlib & seaborn libraries.

