# World Happiness Analysis (Excel)

## Project Overview

This project analyzes the **World Happiness dataset** using Microsoft Excel to explore relationships between national economic indicators and reported happiness scores.

The goal of the project was to practice fundamental data analysis workflows in Excel, namely:

- Data cleaning
- Derived columns
- Pivot table analysis
- Dashboard creation

The analysis focuses primarily on the relationship between **GDP per capita** and **reported happiness levels**.

---

## Tools Used

- Microsoft Excel
- Excel Tables
- Pivot Tables
- XLOOKUP
- IF formulas
- Basic data visualization

---

## Dataset

The dataset contains country-level information including:

- Country name
- Happiness score
- GDP per capita
- Other economic and social indicators

The raw dataset was imported into Excel and organized into a Excel table for analysis.

---

## Analysis Workflow

The project follows a simple data analysis pipeline:

### 1. Raw Data

The dataset was first loaded into a worksheet titled **Raw_Data**.

---

### 2. Cleaned Data

A second worksheet titled **Cleaned_Data** was created to structure the data using Excel tables and create additional derived columns.

Derived columns include:

- **GDP Category** (using XLOOKUP against a reference table)
- **Happiness Category** (using XLOOKUP against a reference table)
- **Above/Below Average Happiness** (using an IF formula comparing scores to the dataset average)

---

### 3. Pivot Table Analysis

Pivot tables were created to explore relationships in the dataset, including:

- Average happiness score by GDP category
- Top countries by happiness score
- Distribution of countries across GDP and happiness categories
- A slicer allowing filtering by **GDP category**

---

### 4. Dashboard

A simple dashboard was created to summarize the analysis visually.

The dashboard includes:

- A bar chart showing **average happiness score by GDP category**
- A pie chart showing **the proportion of countries within each GDP category**
- A table listing **top 10 countries by happiness score**

---

## Key Insights

Some general observations from the analysis include:

- Countries with higher GDP per capita tend to report higher happiness scores on average.
- The majority of the highest-ranked countries in happiness also fall within the highest GDP category -- in fact, the top 10 are all high-GDP
- Lower GDP categories generally show lower average happiness scores.

These patterns suggest a relationship between **economic prosperity and reported life satisfaction**.

---

## Repository Structure

## Repository Structure

```
world-happiness-excel-analysis
│
├── happiness_analysis.xlsx
├── dashboard_screenshot.png
└── README.md
```

---

## Purpose of the Project

This project was created as part of a broader data analytics portfolio to demonstrate foundational Excel skills used in data analysis, including:

- Data cleaning
- Lookup functions
- Derived metrics
- Pivot table analysis
- Basic dashboard creation

It complements additional, more extensive projects using **MySQL, Python, and Tableau**.
