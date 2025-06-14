# ✈️ Aircraft Accident Risk Analysis - Which Aircraft Is Safer to Invest In?

This project performs a detailed analysis of a large dataset of aircraft accidents and incidents to **identify the least risky aircraft types for investment**. The dataset contains over 88,000 records and was sourced from [Kaggle](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses). 

The goal is to assist stakeholders and investors in the **aviation sector** to make informed decisions by highlighting aircraft categories with the **lowest accident rates, damage rates, and fatal injury statistics**.



## 📂 Table of Contents

- [Project Overview](#project-overview)
- [Questions of Interest](#questions-of-interest)
- [Dataset & Cleaning](#dataset--cleaning)
- [Analysis Summary](#analysis-summary)
- [Key Findings](#key-findings)
- [Graphs](#graphs)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)



## 📌 Project Overview

This analysis investigates historical accident and incident data to determine which aircraft categories are statistically safer. The dataset initially had **31 columns and 88,859 rows**, which was **cleaned, filtered, and refined** to focus on the most relevant information (aircraft category, damage, fatal injuries, engine type, etc.).



## ❓ Questions of Interest

Some of the key questions explored in this analysis include:

- What are the main aircraft categories in the dataset?
- Which aircraft have the highest number of accidents?
- How risky is a 1-engine aircraft?
- What is the destruction rate by aircraft type?
- What is the death rate per accident for each category?



## 🧹 Dataset & Cleaning

Key cleaning steps included:

- Removing duplicates
- Dropping rows with missing values
- Creating a “Year” column from event dates
- Filtering out irrelevant aircraft types with very low record counts

Final working dataset: **10,355 records**



## 📊 Analysis Summary

- Most accidents are caused by **Airplanes (81.14%)** and **Helicopters (14.28%)**
- Destruction rate is higher in **Helicopters (10.68%)** than in Airplanes (8.28%)
- 1-engine aircraft are involved in the majority of accidents across all categories
- **Death rates**:
  - Airplane: 37.34%
  - Helicopter: 39%
  - Glider: **14.28%** (lowest)
  - Gyrocraft: 17%



## ✅ Key Findings

✔️ **Gliders** are the **safest investment** based on:
- Only **28 records**
- Very low **destruction rate (3.57%)**
- Only **4 fatal injuries**
- **Death rate** of just **14.28%**

🚫 Recommendation to **avoid 1-engine Gliders**, as they caused 22 of the 28 accidents.

✔️ **Gyrocraft** is the next safest option after Gliders.



## 📈 Graphs

The project includes:
- Line plot showing the evolution of accidents over the years
- Pie chart comparing incidents vs accidents
- Bar plots by aircraft category and engine count



## 🧰 Technologies Used

- Python 🐍
- Pandas
- Matplotlib & Seaborn
- Jupyter Notebook
- Excel (for exporting cleaned dataset)



## ▶️ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/aircraft-risk-analysis.git

