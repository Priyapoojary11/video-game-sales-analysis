# 🎮 Video Game Sales Data Analysis

This project analyzes a dataset of video game sales using Python. It focuses on cleaning the data, handling missing and inconsistent values, and visualizing key patterns in national and global sales across regions, countries, and genres.

---

## 📌 Project Overview

The goal of this project is to explore video game sales data and gain insights using Python libraries such as **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. The analysis includes:

- Data cleaning and preprocessing
- Summarizing sales by region and country
- Visualizing national and global sales trends
- Handling outliers and missing values

---

## 🧰 Tools & Technologies Used

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computations
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive development

---

## 🧹 Data Cleaning Steps

- **Removed duplicates** to avoid redundancy.
- **Filled missing values**:
  - *Region* → Replaced with `'North'`
  - *NA_Sales* → Cleaned symbols and filled with average sales
- **Standardized values** in the *Country* column (e.g., `'USA'` → `'United States'`)
- **Renamed columns** for clarity:
  - `'NA_Sales'` → `'National Sales'`
  - `'Global_Sales'` → `'Global Sales'`
- **Handled outliers** in `National Sales` by capping values at the 95th percentile.

---

## 📊 Data Visualizations

### 📉 1. Bar Chart: National Sales by Region and Country
Grouped bar chart showing total national sales per country within each region.

### 📦 2. Box Plot: National Sales by Country and Genre
Visualizes sales distribution and identifies outliers across different genres and countries.

### 🥧 3. Pie Charts: Sales by Country
- **Left:** National Sales by Country
- **Right:** Global Sales by Country

### 📈 4. Line Chart: National vs Global Sales Over Time
Illustrates trends and comparisons in sales performance over the years.

---

## ✅ What I Learned

- Handling missing data and inconsistent formatting in real-world datasets
- Using group by, aggregation, and visualization to draw insights
- Applying outlier detection and data transformation techniques
- Creating compelling visualizations to tell a data story

---

## 🚀 Future Improvements

- Integrate interactive dashboards using **Plotly** or **Streamlit**
- Perform **predictive analysis** using machine learning models
- Extend analysis to include profitability or market trends

---

## 📁 Dataset

> 📂 **File Used:** `VideoGamesSales.csv`  

---

## 📎 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Priyapoojary11/video-game-sales-analysis.git
   cd video-game-sales-analysis
