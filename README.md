# 🎬 IMDB Movie Analysis (2021–2024) | Data Analytics Project

## Overview

This project analyzes a dataset of **379 IMDB movies (2021–2024)** to explore trends in ratings, runtime, votes, and box office performance.

The goal is to identify patterns in **movie popularity, audience engagement, and commercial success** using Python-based data analysis.

---

## Dataset

* **Total Records:** 379
* **Total Columns:** 12
* **Time Period:** 2021–2024
* **Missing Values:** 0
* **Duplicate Records:** 0

### Dataset Features

* Title, Genre, Director, Actors
* Runtime, Rating, Votes
* Gross Collection (Cr)
* Year and Verdict

---

## Tools & Technologies

| Tool       | Purpose                      |
| ---------- | ---------------------------- |
| Python     | Data analysis                |
| Pandas     | Data cleaning & manipulation |
| NumPy      | Numerical computations       |
| Matplotlib | Data visualization           |
| Seaborn    | Statistical visualization    |

---

## Project Steps

### 1. Data Loading

* Imported dataset using Pandas
* Viewed dataset structure using `head()`, `tail()`, and `info()`

### 2. Data Cleaning

* Checked missing values (none found)
* Removed duplicate records (none found)
* Dropped unnecessary columns
* Verified data types and structure

### 3. Exploratory Data Analysis (EDA)

* Analyzed runtime, ratings, votes, and gross revenue
* Computed summary statistics using `describe()`
* Identified trends across years (2021–2024)
* Compared performance across directors and genres

### 4. Data Analysis

* Year-wise vote distribution
* Year-wise gross revenue comparison
* Top 10 longest movies
* Top directors by average rating
* Identification of high-runtime films (≥180 minutes)

---

## Key Results

### Audience Engagement

* **2023** recorded the highest audience engagement with over **1.7M votes**

### Revenue Performance

* **2024** generated the highest box office revenue of **₹4,229 Cr**

### Top Performers

* Longest movies included *Animal (Dub)*, *Pushpa 2*, and *RRR*
* Top-rated directors consistently achieved **8.0+ ratings**

### Content Trends

* Longer movies (180+ minutes) often aligned with high-budget productions
* Ratings varied between **1.5 to 9.0**, showing mixed audience reception

### Data Quality

* Dataset was clean with **zero missing or duplicate values**
* Reliable structure enabled strong trend analysis

---

## Key Insights

* 2023 had maximum audience engagement, while 2024 achieved highest revenue
* High-budget films with longer runtimes tend to perform better commercially
* A small group of directors consistently produces high-rated movies
* Industry shows a shift toward large-scale, high-revenue productions
* Audience ratings indicate mixed but generally positive reception

---

## Report & Presentation

* A detailed **analysis report** was prepared based on findings
* A **presentation (PPT)** was created using **Gamma AI** summarizing insights and conclusions

---

## How to Run

### 1. Clone Repository

```bash "
git clone <repository-link>
```

### 2. Install Required Libraries

```bash "
pip install pandas numpy matplotlib seaborn
```

### 3. Run Analysis

* Open Jupyter Notebook or Python script
* Execute step-by-step analysis

---

## Repository Structure

```plaintext id="x9kq2z"
IMDB-Movie-Analysis/
│
├── Dataset/
├── Python_Notebooks/
├── Visualizations/
├── Report/
├── Presentation/
└── README.md
```

---

## Author

**Rajendhar Banoth**
Aspiring Data Analyst | Python | Data Visualization | EDA

