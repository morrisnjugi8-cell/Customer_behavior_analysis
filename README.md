# Customer_behavior_analysis
Data analytics project for cutomer_analysis using python,.sql and powerBI

---

#  Data Analytics Project

## Overview

This project demonstrates an end-to-end data analytics workflow using Python, PostgreSQL, and a visualization dashboard. The goal of the project is to transform raw data into actionable insights through data cleaning, exploratory analysis, SQL querying, and reporting.

The project follows a typical analytics pipeline:

1. Data loading
2. Exploratory Data Analysis (EDA)
3. Data cleaning and preparation
4. SQL analysis in PostgreSQL
5. Dashboard development
6. Final reporting and insights

---

## Dataset

The dataset contains structured tabular data used to analyze trends, patterns, and relationships between variables.

**Key characteristics**

* Format: CSV
* Size: *(3900 rows and 18 columns)*
* Key features include:

  * Demographic / categorical variables
  * Numerical performance indicators
  * Location variables
  * Currency

---

## Tools & Technologies

* Python (Pandas, NumPy, Matplotlib/Seaborn)
* PostgreSQL
* SQL
* Jupyter Notebook
* Power BI / Tableau
* Git & GitHub

---

## Project Workflow

###  Data Loading (Python)

* Imported dataset into Python using **Pandas**
* Checked structure, datatypes, and missing values
* Performed initial data inspection

Key tasks:

* Viewing dataset shape and info
* Checking duplicates
* Validating data types

---

### Exploratory Data Analysis (EDA)

Performed statistical and visual exploration to understand the dataset.

EDA included:

* Summary statistics
* Distribution analysis
* Correlation analysis
* Feature relationships visualization
* 
---

### Data Cleaning & Preparation

Data was cleaned to improve quality and reliability.

Cleaning steps:

* Missing Data Handling
* Column Standardization
* Feature Engineering
* Data Consistency Check
* Database Integration

Clean dataset was exported for SQL analysis.

---

### SQL Analysis (PostgreSQL)

The cleaned dataset was loaded into **PostgreSQL** for advanced querying.

Key SQL tasks:

* Creating tables and importing data
* Writing analytical queries
* Aggregations and grouping
* Creating views for dashboard consumption

Example analysis:

* Trend analysis
* Category performance comparison
* KPI calculations

---

### Dashboard Development

A dashboard was built to visualize key insights and support decision-making.

Dashboard includes:

* KPI summary cards
* Trend charts
* Category comparisons
* Interactive filters
* Data storytelling visuals

Tool used: **(Power BI / Tableau)**

---

## Results & Insights

The analysis revealed key patterns and business insights such as:

* Important trends and patterns in the data
* Key drivers influencing outcomes
* Performance differences across categories/groups
* Data-driven recommendations


---

## Project Structure

```
data-analytics-project/
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── notebooks/
│   ├── 01_data_loading.ipynb
│   ├── 02_eda.ipynb
│   └── 03_data_cleaning.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── dashboard.pbix / dashboard.twb
│
├── reports/
│   └── final_report.pdf
│
└── README.md
```

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/data-analytics-project.git
cd data-analytics-project
```

### 2. Create virtual environment

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Jupyter notebooks

```bash
jupyter notebook
```

Run notebooks in order:

1. Data loading
2. EDA
3. Data cleaning

### 5. Load data into PostgreSQL

* Create database
* Run SQL script inside `/sql/analysis_queries.sql`

### 6. Open Dashboard

Open the dashboard file in **Power BI / Tableau** to explore insights.

---

## Author

**Morris Njugi**
Data Analyst

---
