# Global Workforce Reductions (2020–2023)
### SQL Data Cleaning & Exploratory Data Analysis

**Prepared by:** Anchal Chauhan  
**Tools:** MySQL | SQL | Data Cleaning | Exploratory Data Analysis

## Project Overview

This project explores global workforce reductions between 2020 and 2023, examining how layoffs varied across companies, industries, countries and time periods.

Using SQL, I focused on preparing the dataset for analysis, identifying patterns in workforce reductions and understanding which sectors and organisations experienced the greatest impact.

## Project Objectives

- Clean and prepare the raw dataset for analysis.
- Identify companies and industries with the highest reported layoffs.
- Examine yearly and monthly layoff trends.
- Compare workforce reductions across countries.
- Explore patterns using SQL queries and analytical functions.

## Dataset

The dataset contains **2,361 records** of reported company layoffs between March 2020 and March 2023.

It includes company names, locations, industries, layoff counts, percentages, dates, funding stages and countries.

**Dataset:** [Kaggle – Layoffs 2022](https://www.kaggle.com/datasets/swaptr/layoffs-2022)

## SQL Techniques

The project covers:

- Data cleaning and duplicate identification
- Handling missing and inconsistent values
- Standardising industry and country names
- Date formatting and transformation
- Aggregate functions (`SUM`, `COUNT`, `MAX`, `AVG`)
- `GROUP BY`, `ORDER BY` and filtering
- Common Table Expressions (CTEs)
- Window functions and ranking
- Monthly and yearly trend analysis

## Key Findings

The analysis highlighted several patterns in global workforce reductions:

- **Industry differences:** Layoffs were concentrated in particular industries, showing that workforce reductions were not evenly distributed across sectors.
- **Geographical patterns:** Some countries accounted for a substantially larger share of reported layoffs than others.
- **Company-level impact:** A relatively small number of companies contributed significantly to the total reported layoffs.
- **Changes over time:** Layoff activity varied considerably between 2020 and early 2023, with periods of particularly high workforce reductions.

These findings demonstrate how SQL can be used to transform raw business data into meaningful insights.

## Data Visualisation

The accompanying analysis report includes:

1. Annual workforce reduction trends
2. Monthly layoff trends
3. Industries with the highest reported layoffs
4. Countries with the highest reported layoffs
5. Companies reporting the largest workforce reductions

## Project Files

| File | Description |
|---|---|
| `layoffs.csv` | Original dataset |
| `Data_Cleaning_&_EDA.sql` | SQL cleaning and exploratory analysis script |
| `Anchal_Chauhan_SQL_Layoffs_Analysis_Report_Final.pdf` | Analytical report containing findings, charts and conclusions |

## Conclusion

This project helped me explore how SQL can be applied to real-world datasets to identify trends, compare business performance and investigate patterns across different dimensions.

It also reinforced the importance of data cleaning, particularly when working with missing values, duplicate records and inconsistently formatted information.

The analysis provides a broader understanding of global workforce reductions while demonstrating practical SQL and exploratory data analysis skills.

---

**Anchal Chauhan**  
MSc Data Science | Birmingham Newman University  
**Project Submission:** 30 November 2026
