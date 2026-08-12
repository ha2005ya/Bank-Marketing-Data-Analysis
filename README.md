# Bank Marketing Data Analysis

An end-to-end data analytics project built around a bank marketing campaign dataset. The project covers data cleaning, SQL analysis with DuckDB, and interactive Tableau dashboards designed to transform customer and campaign data into actionable business insights.

## Project Objective

The goal of this project is to understand:

* Who the bank's customers are and how many subscribed to a term deposit.
* Which campaign factors are associated with higher subscription rates.
* Which customer segments could be prioritized in future campaigns.

## Tools & Technologies

* **Excel** — Data cleaning and validation
* **SQL** — Business analysis and aggregation
* **DuckDB** — Local analytical database and query execution
* **Tableau** — Interactive dashboards and data storytelling
* **ChatGPT** — AI-assisted validation during the cleaning process

## Dataset

The cleaned dataset contains:

* **11,162 customer records**
* **17 columns**
* Target variable: **`subscribed`** (`yes` / `no`)

The analysis focuses on customer demographics, account information, campaign contact details, previous campaign outcomes, and subscription behavior.

## Data Cleaning

The cleaning stage included:

* Standardizing the target column as `subscribed`
* Validating customer ages against the required range
* Reviewing unusually high campaign-contact values
* Checking for exact duplicate rows
* Standardizing yes/no categorical values to lowercase
* Exporting the cleaned dataset as `bank_cleaned.csv`

## Analysis Areas

### 1. Customer Profile & Campaign Overview

Explores the overall customer base and subscription behavior, including:

* Total customers contacted
* Total subscriptions
* Overall subscription rate
* Subscription rate by job and customer profile
* Customer balance and subscription distribution

### 2. Campaign Performance & Conversion Analysis

Investigates which campaign factors were associated with better conversion, including:

* Conversion rate by contact type
* Campaign attempts
* Conversion rate by month
* Average call duration
* Previous campaign outcome

### 3. Strategic Customer Intelligence

Focuses on identifying stronger customer groups and patterns that can support future targeting decisions.

## Key Insights

Based on the cleaned dataset:

* **5,289 of 11,162 customers subscribed**, giving an overall subscription rate of approximately **47.38%**.
* **Students had the highest subscription rate by job category at 74.72%**, followed by **retired customers at 66.32%**.
* Customers contacted by **cellular** had a subscription rate of approximately **54.33%**.
* Customers with a **successful previous campaign outcome** showed a subscription rate of approximately **91.32%**.
* Customers with **no housing loan and no personal loan** showed a subscription rate of approximately **59.65%**.

## Tableau Dashboards

The Tableau workbook contains three dashboards:

**Customer Profile & Campaign Overview**

**Campaign Performance & Conversion Analysis**

**Strategic Customer Intelligence**

The dashboards are combined into a Tableau Story to present the analysis from general customer profiling to campaign performance and strategic insights.

## Repository Structure

```text
Bank-Marketing-Data-Analysis/
│
├── data/
│   ├── bank.csv
│   └── bank_cleaned.csv
│
├── sql/
│   ├── queries.sql
│   └── results/
│
├── tableau/
│   └── Bank_Marketing_Insights_Story.twbx
│
├── docs/
│   └── AI_Prompts.docx
│
├── images/
│   ├── dashboard_1.png
│   ├── dashboard_2.png
│   └── dashboard_3.png
│
├── README.md
└── .gitignore
```

## Dashboard Preview

Dashboard screenshots will be added here to provide a quick visual overview of the analysis.

```markdown
![Customer Profile Dashboard](images/dashboard_1.png)

![Campaign Performance Dashboard](images/dashboard_2.png)

![Strategic Customer Intelligence Dashboard](images/dashboard_3.png)
```

## What I Learned

This project strengthened my ability to work through a complete analytics workflow: cleaning raw data, translating business questions into SQL queries, validating results, and communicating insights through interactive dashboards.

It also helped me focus on the difference between simply presenting metrics and using data to answer real business questions.

## Author

**Haya Hany Abo Said**

Data Analytics Project
