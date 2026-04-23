# Building Risk and Wear Analysis

## Overview
This project presents an interactive **Power BI dashboard** focused on analyzing **building risk, wear level, and critical building elements**.

The report was built using publicly available CSV datasets and includes three main analytical pages:

1. **Executive Overview**
2. **Building Analysis**
3. **Building Elements Analysis**

The goal of the report is to provide a clear and structured view of:
- overall building condition
- municipality-level differences
- building age and wear patterns
- the riskiest and most worn building elements
- categories with the highest number of critical elements

---

## Project Pages

### 1. Executive Overview
This page provides a high-level summary of the dataset through:
- key KPI cards
- municipality comparison by average risk score
- municipality comparison by average wear score
- Top 10 elements by number of critical cases
- the most worn building elements

### 2. Building Analysis
This page focuses on building-level insights:
- number of buildings by age group
- number of buildings by wear level
- average risk by building age
- average wear by building age
- scatter plot showing the relationship between risk and wear
- municipality slicer for interactive filtering

### 3. Building Elements Analysis
This page focuses on building element-level insights:
- Top 10 elements by average risk score
- Top 10 elements by average wear score
- average risk score by category
- number of critical elements by category

---

## Tools Used
- **Power BI Desktop**
- **Power Query**
- **DAX**

---

## Data Preparation
The raw CSV files were imported into Power BI and prepared using **Power Query**.

Data preparation included:
- importing multiple CSV datasets
- checking and adjusting data types
- working with field names used in visuals
- preparing the data model for reporting and analysis

---

## Data Modeling and Calculations
The report uses:
- calculated **DAX measures**
- KPI logic
- **Top N filtering**
- interactive slicers
- category-level and element-level comparisons

Examples of analysis included in the report:
- average risk score
- average wear score
- number of critical elements
- Top 10 highest-risk elements
- Top 10 most worn elements

---

## Visualizations
The dashboard includes multiple visual types:
- KPI cards
- clustered bar charts
- clustered column charts
- scatter chart
- slicer

A consistent color logic was applied across pages:
- **blue** for risk-related visuals
- **green** for wear-related visuals
- **red** for critical element visuals

---

## Data Source
The data used in this project comes from the **Lithuanian Open Data Portal** dataset:

**Pastatų ir jų elementų rizikos bei nusidėvėjimo duomenų rinkiniai**

Source:
`https://data.gov.lt/datasets/4143/?resource_version=3280`

The project uses CSV resources related to:
- building risk and wear
- building element risk
- building element wear

---

## Key Insights
This report helps identify:
- municipalities with higher average risk scores
- municipalities with higher average wear scores
- the most critical building elements
- the most worn building elements
- element categories with the highest average risk
- categories with the highest number of critical elements
- the relationship between building age, risk, and wear

---

## What I Learned
This project helped me strengthen my practical skills in:
- building multi-page Power BI reports
- structuring dashboards for clear storytelling
- using Power Query for data import and preparation
- creating DAX measures for analysis
- applying Top N logic and slicers
- maintaining consistent visual design across report pages

---

## Repository Structure
```text
.
├── AD-Pastatu_Rizikos_Analize.pbix
├── data/
│   ├── PastatoRizikaNusidevejimas.csv
│   ├── PastatoElementoRizika.csv
│   └── PastatoElementoNusidevejimas.csv
├── images/
│   ├── executive-overview.png
│   ├── pastatu-analize.png
│   └── pastato-elementu-analize.png
├── README.md
└── README-lt.md
```

---

## Screenshots

### Executive Overview
![Executive Overview](images/executive-overview.png)

### Building Analysis
![Building Analysis](images/pastatu-analize.png)

### Building Elements Analysis
![Building Elements Analysis](images/pastato-elementu-analize.png)

---

## Project Summary
This project was created as a portfolio Power BI report to demonstrate:
- dashboard design
- business-oriented data storytelling
- data preparation with Power Query
- analytical calculations with DAX
- interactive reporting in Power BI

---

## Author
Created by **Aras Dobrovolskis**