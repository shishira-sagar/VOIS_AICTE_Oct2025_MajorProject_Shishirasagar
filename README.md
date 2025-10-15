# VOIS_AICTE_Oct2025_MajorProject_ShubhamBhadoria
Netflix Content Analysis Project — Data cleaning, EDA, and visualization of Netflix’s catalog (~7,800 titles) using Python (Pandas, Matplotlib). The project analyzes Movies vs TV Shows distribution, top genres, and country-wise contributions. Outputs include cleaned datasets, CSV summaries, and visual insights for Power BI / presentations.
# Netflix Content Analysis Project

## 📌 Project Overview
This project analyzes the Netflix dataset (~7,800 records of Movies and TV Shows) to understand content distribution, genre trends, and country contributions.  
It answers three main business questions:
1. Distribution of Movies vs TV Shows over the years.
2. Most common genres and how their popularity has changed.
3. Country-wise contributions to Netflix’s catalog.

The project helps Netflix (or similar streaming platforms) make **data-driven decisions** on content strategy and regional investments.

---

## 📂 Dataset
- **Source:** Provided CSV file (`Netflix Dataset.csv`)
- **Columns include:**
  - Show_Id, Category (Movie/TV Show), Title, Director, Cast, Country, Release_Date, Rating, Duration, Type (Genres), Description

---

## 🛠️ Technologies Used
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib  
- **Environment:** Jupyter Notebook  
- **Visualization & Reporting:** Power BI, PowerPoint  

---

## 📊 Data Cleaning Steps
1. Standardized column names (lowercase, underscores).  
2. Handled missing values:
   - Director → replaced NaN with `"Unknown Director"`.
   - Country → replaced NaN with `"Unknown Country"`.
3. Parsed `release_date` into `release_year`.  
4. Split multi-valued columns:
   - `type` → genres list.  
   - `country` → country list.  
5. Created cleaned dataset for further analysis.

---

## 🔍 Exploratory Data Analysis (EDA)
- **Movies vs TV Shows:** Count per year (`type_trend_by_year.csv`).  
- **Genres:** Most common genres overall and trend by year (`genre_counts.csv`, `genre_trend_by_year.csv`).  
- **Countries:** Contribution percentage (`country_counts.csv`).  

---

## ✅ Key Findings
- **Movies vs TV Shows:** 5,379 Movies vs 2,410 TV Shows (7,789 total).  
- **Top Genres:** International Movies, Dramas, Comedies, International TV Shows, Documentaries.  
- **Top Countries:** United States (~36%), India (~11%), UK (~8%), Canada (~4.5%), France (~3.9%).  

---

## 📂 Outputs
- `Netflix_cleaned_for_analysis.csv` → cleaned dataset  
- `type_trend_by_year.csv` → Movies vs TV Shows per year  
- `genre_counts.csv` → overall genre counts  
- `genre_trend_by_year.csv` → genre trends by year  
- `country_counts.csv` → country contribution counts  


