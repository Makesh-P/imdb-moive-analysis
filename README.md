# 🎬 IMDb Movie Success Analysis

> **What Defines a Successful Movie?** — An analysis of audience ratings, critic scores, and box office performance.

---

## 📌 Project Overview

This project explores **1,000 IMDb movies** to uncover what makes a movie truly successful — whether it's audience reception, critical acclaim, or box office revenue. The analysis was built using **Excel** for data cleaning and **Power BI** for interactive dashboard development.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data cleaning & preprocessing |
| Microsoft Power BI | Dashboard development & visualization |

---

## 📂 Dataset

- **Source:** IMDb Top 1000 Movies
- **Size:** 1,000 rows × 8 columns
- **Columns:** Title, Director, Release Year, Runtime, Genre, IMDb Rating, Metascore, Gross Revenue

### Data Cleaning Steps Performed:
- Identified and replaced fake missing values (zeros) in Metascore and Gross columns
- Replaced missing **Metascore** values with **mean** (no significant outliers)
- Replaced missing **Gross Revenue** values with **median** (outliers present)
- Converted Gross Revenue from text format (`$37.7M`) to numeric values
- Fixed inconsistent Release Year formats (`(I) (2006)` → `2006`)
- Removed negative signs from Release Year column
- Cleaned Runtime column by removing `min` text suffix
- Checked and confirmed no duplicate rows

---

## 📊 Dashboard Overview

The dashboard is split into **2 pages:**

### Page 1 — Movie Success Overview
- **KPI Cards** → Total Movies, Avg IMDb Rating, Total Revenue, Avg Metascore
- **Which genre has the highest average rating?** → Bar Chart
- **Which genre generates the highest box office?** → Bar Chart
- **Critics vs Audience: Do They Agree?** → Scatter Plot
- **Movies Released Over Years** → Line Chart
- **Interactive Year Slicer** → Filter entire dashboard by year range

### Page 2 — Deep Dive Analysis
- **Top 10 Highest Rated Movies** → Bar Chart
- **Top 10 Highest Grossing Movies** → Bar Chart
- **Top 10 Directors by Avg Rating** → Bar Chart
- **Box Office Revenue Trend Over the Years** → Line Chart
- **Movie Details Table** → Complete reference table

---

## 🔍 Key Insights

- 🏆 **Highest Rated Genre** → Adventure, Western (Avg Rating: 8.8)
- 💰 **Highest Grossing Genre** → Animation, Adventure, Comedy ($5.2K M)
- 📅 **Peak Movie Year** → 2014 (31 movies released)
- 🎬 **Top Director** → Frank Darabont (Avg Rating: 8.95)
- 🎥 **Highest Grossing Movie** → Star Wars: Episode VII ($937M)
- 🤝 **Critics vs Audience** → Positive correlation — they mostly agree on great movies!

---

## 💡 Key Learnings

- Hands-on experience with real-world messy data cleaning in Excel
- Understanding the difference between mean vs median for handling missing values
- Building multi-page interactive dashboards in Power BI
- Using DAX measures, slicers, filters and scatter plots effectively
- Telling a data story through structured visual layout

---

## 👤 Author

**Makesh**
- 🔗 [LinkedIn](linkedin.com/in/makesh-p)
- 🐙 [GitHub](https://github.com/Makesh-P)

---

*This project was built as part of my data analytics portfolio while pursuing my BCA degree.*
