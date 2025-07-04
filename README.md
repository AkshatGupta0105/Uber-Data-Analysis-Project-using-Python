# 📊 Uber Rides Data Analysis Project

## 📁 Project Title
**Data-Driven Insights from Uber Ride Patterns using Python**

---

## 📌 Overview

This project focuses on extracting actionable insights from Uber’s ride-sharing dataset.  
By leveraging Python-based data analysis and visualization techniques, the study aims to explore customer behavior, trip preferences, time-based usage trends, and ride distances.

The analysis serves a dual purpose:
- **Business Intelligence**: Helps companies like Uber understand user behavior to optimize operations.
- **Skill Development**: Enhances capabilities in data analysis, Python programming, and visualization.

---

## 🧾 Dataset Description

- **File Used**: `UberDataset.csv`  
- **Total Records**: 1156 entries  
- **Columns**:
  - `START_DATE` & `END_DATE`: Date and time of ride start and end
  - `CATEGORY`: Type of trip (Business or Personal)
  - `START` & `STOP`: Pickup and drop-off locations
  - `MILES`: Distance travelled
  - `PURPOSE`: Reason for ride (e.g., Meeting, Errand, Meal, etc.)

---

## 🎯 Project Objectives

To answer six key business questions:

1. Which **category** sees the most bookings?
2. For which **purpose** are rides most booked?
3. At what **time of day** are Uber cabs most frequently used?
4. In which **months** is booking frequency the lowest?
5. Which **days of the week** have the highest number of bookings?
6. What is the **average ride distance**?

---

## 🛠️ Technologies and Tools Used

| Tool / Technology     | Purpose                        |
|-----------------------|--------------------------------|
| Python 3.8+           | Programming                    |
| Pandas                | Data manipulation              |
| NumPy                 | Numerical operations           |
| Matplotlib            | Basic data visualization       |
| Seaborn               | Advanced statistical plotting  |
| Jupyter Notebook      | Interactive analysis           |
| Microsoft Excel       | Initial dataset preview        |

---

## ⚙️ Steps Involved in the Project

### 1. Data Loading & Initial Exploration
- Loaded dataset using `pandas`.
- Identified missing values using `.info()` and `.isnull()`.

### 2. Data Cleaning & Preprocessing
- Filled missing values in the `PURPOSE` column with `"NOT"`.
- Converted `START_DATE` and `END_DATE` into datetime objects.
- Extracted new features:
  - `date`, `time`, `day-night`, `MONTH`, `DAY`
- Dropped null rows, final dataset: `420 rows × 10 columns`.

### 3. Feature Engineering
- Created categorical bins for `day-night`: Morning, Afternoon, Evening, Night.
- Mapped day numbers to names using `.map()`.

### 4. Data Visualization
- Created various plots using `matplotlib` and `seaborn`.

---

## 📊 Data Visualization & Analysis

### 🔹 Category and Purpose
- **Business** rides dominate over Personal.
- Common ride purposes include **Meeting**, **Meal/Entertainment**, and **Errand/Supplies**.

### 🔹 Time of Day Analysis
- Most rides happen during the **Evening** and **Afternoon**.

### 🔹 Month-wise Trends
- Peak bookings observed in **January**.
- Dip in ride frequency during **mid-year months**.

### 🔹 Day of Week Analysis
- **Tuesday** and **Wednesday** have the highest booking count.
- **Sunday** sees the least rides, reflecting downtime.

### 🔹 Distance (Miles) Analysis
- Majority of rides are **under 40 miles**.
- Boxplots and histograms used to visualize distributions.

---

## 📌 Key Insights

| Metric              | Insight                                |
|---------------------|----------------------------------------|
| Most used category  | Business                               |
| Common purposes     | Meeting, Entertainment, Errand         |
| Preferred time slot | Evening and Afternoon                  |
| Peak booking month  | January                                |
| Busiest weekdays    | Tuesday and Wednesday                  |
| Distance trend      | Most rides are under 40 miles          |

---

## 🧠 What I Learned

### 🛠 Technical Skills
- Hands-on with data cleaning and feature extraction.
- Proficiency in using `matplotlib` and `seaborn`.
- Manipulating time series data in `pandas`.

### 🔍 Analytical Thinking
- Interpreting data to form logical business conclusions.
- Connecting usage trends with potential user behavior patterns.

### 🚀 Real-World Relevance
- Understand how companies like Uber can improve:
  - **Pricing strategies**
  - **Targeted promotions**
  - **User engagement based on time/location**

---


