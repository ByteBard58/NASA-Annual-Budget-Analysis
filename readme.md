# 🚀 NASA Budget Analysis (1959–2022)

This project analyzes the **annual budget of NASA** from 1959 to 2022, using real-world datasets from [Our World In Data](https://ourworldindata.org/) and [Kaggle](https://www.kaggle.com/). It explores how NASA's funding has changed over the decades and correlates those trends with major events in U.S. space history.

---

## 📌 Objective

- Visualize how NASA’s annual funding has changed from 1959 to 2022
- Highlight key historical events (e.g. Apollo program, Shuttle era, Mars missions)
- Apply smoothing techniques (rolling mean) to reveal long-term trends
- Compare NASA’s budget to the U.S. Military budget to show funding disparities
- Practice time-series visualization and data storytelling using `pandas`, `matplotlib`, and `seaborn`

---

## 📊 Dataset Overview

### 1. NASA Annual Budget Dataset
- **Source**: Our World In Data  
- **Columns**: `Entity`, `Code`, `Year`, `Annual budget of NASA`  
- **Unit**: Constant **2020 USD**  
- **Transformed**: Values converted to **Billions** for visualization

### 2. US Military Defense Budget Dataset
- **Source**: Kaggle (by Brandon Conrady)  
- **Columns**: `Year`, `DefenseBudget`, `GDP`, `Population`  
- **Unit**: Already in **Billions USD**

---

## 📈 Visualizations & Insights

- 📍 **Line plot** of NASA’s annual budget with annotations for:
  - Apollo Program (1961–1972)
  - Space Shuttle Era (1981–2011)
  - Mars Missions Era (1996–2022)
  - Challenger (1986) & Columbia (2003) disasters
- 🔁 **Smoothed line** using a 5-year rolling average
- 📊 **Histogram & KDE** showing the distribution of NASA budget over time
- ⚔️ **NASA vs U.S. Military budget comparison** (1960–2020)

---

## 🧠 Key Takeaways

- NASA’s budget peaked during the **Apollo era**, followed by a major dip
- A long stable period followed during the **Shuttle and ISS** era
- Gradual rise during **Mars exploration programs**
- **Military spending has consistently dwarfed NASA's budget** over the decades

---

## 🛠️ Technologies Used

- Python 3.11
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

---

## 😀 Thanks 
I appreciate your review of this work. I hope you found the overall quality satisfactory.
Have a great day!

**Made by Sakib**
