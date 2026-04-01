# 🎬 Netflix Content Analytics Dashboard

An end-to-end data analytics project exploring Netflix's global content 
library through data preprocessing, exploratory data analysis (EDA), 
and an interactive Tableau dashboard — uncovering trends in content 
distribution, ratings, genres, and international growth patterns.

---

## 📌 Project Overview

Netflix has grown into one of the world's largest content platforms, 
with thousands of movies and TV shows spanning every genre and country. 
This project dives deep into that catalog — analyzing what kind of 
content Netflix produces, where it comes from, how it's rated, and 
how its library has evolved over time.

The goal was to transform raw data into a clean, insightful, and 
visually compelling dashboard that tells a clear story about Netflix's 
content strategy.

---

## 🔄 Project Workflow
```
Raw Dataset → Data Cleaning → EDA → Feature Engineering → Tableau Dashboard
```

1. **Data Collection** — Sourced the Netflix Movies & TV Shows dataset from Kaggle
2. **Data Cleaning** — Handled missing values, standardized date formats, 
   parsed multi-valued genre/country columns
3. **Exploratory Data Analysis (EDA)** — Analyzed distributions, trends, 
   and relationships across key variables
4. **Dashboard Design** — Built an interactive, filter-driven Tableau 
   dashboard with multiple chart types and a title-level detail view

---

## 📊 Dashboard Features

### 🗺️ Total Movies & TV Shows by Country
A choropleth world map displaying the volume of Netflix content 
produced by each country, with the US leading at 2,032 titles.

### ⭐ Ratings Distribution
Bar chart breaking down all content by audience rating:
- TV-MA: 2,027 | TV-14: 1,698 | TV-PG: 701 | R: 508 | PG-13: 286

### 🍩 Movies vs TV Shows Distribution
Visual split showing Netflix's content type ratio:
- **Movies**: 4,265 titles — 68.42%
- **TV Shows**: 1,969 titles — 31.58%

### 🎭 Top 10 Genres
Horizontal bar chart of the most represented content categories:
- Documentaries (299), Stand-Up Comedy (273), 
  International Dramas (248), Independent Movies (186), and more

### 📈 Content Growth by Year (2008–2020)
Area chart tracking the year-over-year increase in Movies and 
TV Shows added to the platform — highlighting Netflix's aggressive 
content expansion post-2015.

### 🔍 Title-Level Explorer
Dropdown filters for **Type** and **Title** that dynamically display:
Rating | Duration | Release Year | Genre | Full Description

---

## 📁 Dataset

| Field | Details |
|---|---|
| Source | [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) |
| Records | 8,000+ titles |
| Features | Title, Type, Director, Cast, Country, Date Added, Release Year, Rating, Duration, Genre, Description |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python (Pandas, NumPy) | Data cleaning & preprocessing |
| Matplotlib / Seaborn | Exploratory data analysis |
| Tableau Desktop Public | Dashboard design & visualization |
| Excel / CSV | Data storage & intermediate processing |

---

## 💡 Key Insights

- Netflix's catalog is **movie-dominant**, with nearly 7 in 10 titles being films
- **TV-MA rated content** forms the largest single rating segment, 
  reflecting Netflix's focus on mature, premium content
- **Documentaries and Stand-Up Comedy** are the most produced 
  single-genre categories, suggesting strong investment in non-fiction content
- The US dominates production volume, but **international content** 
  (India, UK, Japan, South Korea) forms a significant and growing share
- Content additions **grew exponentially after 2015**, aligning with 
  Netflix's global expansion strategy

---

## 📂 Repository Structure
```
netflix-content-analytics/
│
├── data/
│   ├── netflix_titles.csv          # Raw dataset
│   └── netflix_cleaned.csv         # Cleaned dataset
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb      # Preprocessing steps
│   └── 02_eda.ipynb                # Exploratory data analysis
│
├── dashboard/
│   └── netflix_dashboard.twbx      # Tableau packaged workbook
│
├── assets/
│   └── dashboard_preview.png       # Dashboard screenshot
│
└── README.md
```

---

## 🚀 How to Use

1. Clone this repository
```bash
   git clone https://github.com/your-username/netflix-content-analytics.git
```
2. Open the Jupyter notebooks in `/notebooks` to explore the cleaning and EDA steps
3. Open `netflix_dashboard.twbx` in **Tableau Desktop** or 
   **Tableau Public** to interact with the dashboard
4. Use the **Type** and **Title** dropdowns to explore individual titles

---

## 🙋‍♀️ About

Built as part of a data analytics portfolio to demonstrate end-to-end 
project capabilities — from raw data to production-ready visualization.

📧 Feel free to connect or raise an issue if you have feedback!
