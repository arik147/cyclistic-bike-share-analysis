
# 🚴 Cyclistic Bike-Share Analysis

## 📌 Case Study – Google Data Analytics Capstone

This project is part of the **Google Data Analytics Professional Certificate**. The goal is to help the fictional bike-share company **Cyclistic** understand how annual members and casual riders use the service differently, and to support a data-driven marketing strategy.

---

## 📊 Business Task

**How do annual members and casual riders use Cyclistic bikes differently?**

As a junior data analyst working on the Cyclistic marketing team, I’ve been assigned to explore user behavior and deliver insights to help convert more casual riders into annual members.

---

## 📁 Data Source

Cyclistic's trip data is provided by [Motivate International Inc.](https://divvy-tripdata.s3.amazonaws.com/index.html), licensed under [this license](https://ride.divvybikes.com/data-license-agreement).

- **Data Used:**  
  - `Divvy_Trips_2019_Q1.csv`
  - `Divvy_Trips_2020_Q1.csv`

> ⚠️ The data has been anonymized to protect user privacy.

---

## 🧹 Data Cleaning

Performed using **R** in a Jupyter Notebook with the following libraries:

- `tidyverse`
- `lubridate`
- `janitor`

Key steps:
- Renamed columns for consistency
- Merged 2019 and 2020 datasets
- Converted time columns to datetime format
- Created new features such as `ride_length`, `day_of_week`, and `weekend`
- Removed invalid or extreme ride lengths

---

## 📈 Analysis & Visualizations

Exploratory Data Analysis (EDA) revealed key differences between user types:

- **Ride Length**  
  Casual riders take longer rides on average compared to members.
  ![image](https://github.com/user-attachments/assets/923040da-3a33-4ac3-bf93-1471bf1fc292)


- **Day of the Week**  
  Members ride more consistently on weekdays, while casual riders are more active on weekends.
  ![image](https://github.com/user-attachments/assets/e2c7270b-1a7f-4ff4-beba-35d1a0c26183)


- **Ride Patterns**  
  Casual users tend to use bikes more for recreation, while members use them for commuting.

Visualizations were created using `ggplot2`, including:
- Histogram of ride lengths by user type
- Bar chart of rides per weekday
- Comparison of average ride length on weekends vs weekdays

---

## 🧠 Key Findings

1. **Casual riders have longer ride durations** than members.
2. **Weekends are more popular** among casual riders.
3. **Members ride more regularly** across the week, especially on weekdays.

---

## ✅ Recommendations

1. **Promote annual memberships as ideal for frequent weekday riders.**
2. **Launch weekend-based membership campaigns targeting casual users.**
3. **Use targeted digital media** to highlight time/money savings for members.

---

## 🛠️ Tools Used

- R (via Jupyter Notebook)
- Tidyverse
- Git/GitHub

---

## 📎 Files Included

- `cyclistic_capstone.ipynb` – Full analysis in R
- `README.md` – Project documentation
- `Divvy_Trips_2019_Q1.csv & Divvy_Trips_2019_Q2.csv` - Cyclistic Bike dataset
