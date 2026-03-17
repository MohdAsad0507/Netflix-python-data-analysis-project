# 🎬 Netflix Movies Data Analysis

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-green)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-blue)

---

## 🌟 Project Overview

This project analyzes a Netflix movies dataset to uncover patterns in **genre distribution, popularity trends, ratings, and yearly content production**.

The objective is to transform raw data into **actionable insights** using Python and visualization techniques.

---

## 🧠 Problem Statement

The entertainment industry generates massive datasets, but deriving insights is key. This project answers:

* Which genres dominate Netflix content?
* How are movies distributed based on ratings?
* Which movies are most/least popular?
* Which year had the highest movie releases?

---

## 🏗️ Project Workflow & Architecture

```text
Raw Data (CSV Files)
        ↓
Data Loading (Pandas)
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
Exploratory Data Analysis (EDA)
        ↓
Business Insights Generation
```

### 🔄 Workflow Breakdown

#### 🧹 Data Cleaning

* Removed irrelevant columns (`Overview`, `Poster_Url`, `Original_Language`)
* Checked for null values and duplicates
* Ensured dataset consistency

#### ⚙️ Data Preprocessing

* Converted `Release_Date` into **year format**
* Standardized column formats
* Converted datatypes for analysis

#### 🛠️ Feature Engineering

* Split multi-value `Genre` column
* Applied `explode()` for granular analysis
* Categorized `Vote_Average` into meaningful groups

#### 📊 Data Analysis

* Genre distribution analysis
* Popularity-based insights
* Year-wise movie production trends
* Rating segmentation

#### 📈 Data Visualization

* Count plots for categorical data
* Bar charts for yearly trends
* Distribution analysis charts

---

## 📂 Dataset Overview

* **Total Records:** ~9,800+
* **Features:** 9 columns

Key columns:

* `Title`
* `Genre`
* `Release_Date`
* `Popularity`
* `Vote_Average`

---

## 🛠️ Tech Stack

* 🐍 Python
* 📊 Pandas
* 🔢 NumPy
* 📈 Matplotlib
* 🎨 Seaborn

---

## 📊 Key Insights

* 🎭 Certain genres dominate Netflix content distribution
* ⭐ Majority of movies fall in **average rating category**
* 🔥 Clear variation in movie popularity across titles
* 📅 Some years show **significant spikes in movie releases**

---

## 🖼️ Visual Insights

* ### 📊 Genre Distribution Plot
  <img width="1210" height="837" alt="Genre distribution plot" src="https://github.com/user-attachments/assets/a3bcc927-0ccc-4f0e-99a7-e20ac34abe3c" />

* ### ⭐ Vote Average Category Distribution
  <img width="1208" height="839" alt="Vote avg category distribution" src="https://github.com/user-attachments/assets/989a6096-0ff0-4263-9465-843675b13610" />

* ### 📅 Top 10 Years by Movie Releases
  <img width="1067" height="828" alt="Top 10 years by movie releases" src="https://github.com/user-attachments/assets/5b2244e4-0a34-4ced-836d-7b2c7de52356" />


---

## 🧠 Skills Demonstrated

* 🧹 Data Cleaning & Preparation
* ⚙️ Data Preprocessing
* 🧠 Exploratory Data Analysis (EDA)
* 📊 Data Visualization
* 🧩 Feature Engineering
* 📈 Insight Generation
* 🗂️ Data Transformation using Pandas

---

## 🚀 Business Insights

* 🎯 High-frequency genres indicate audience demand trends
* ⭐ Most content falls in mid-quality range → scope for improvement
* 🔥 Popularity insights help identify successful content patterns
* 📅 Peak production years reflect content expansion strategies

---

## 💪 What Makes This Project Strong

* ✅ End-to-end data analysis workflow
* ✅ Real-world dataset with meaningful transformations
* ✅ Use of `explode()` for multi-value categorical analysis
* ✅ Clean and structured visualization approach
* ✅ Business-oriented insights (not just technical output)
* ✅ Portfolio-ready presentation

---


## ▶️ How to Run

1. Clone the repository
2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Run the Jupyter Notebook

---

## 💡 Key Learnings

* Importance of preprocessing before analysis
* Handling multi-value categorical columns
* Effective use of visualization for storytelling
* Translating data into actionable insights

---
## 👤 Author

**Mohd Asad**🎓<br>
Aspiring Data Analyst | Python | SQL | Power BI

---

