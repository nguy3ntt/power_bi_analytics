# Global Health Statistics Dashboard

## Project Overview

This project is a Power BI dashboard built using the Global Health Statistics dataset from Kaggle.

The dashboard analyses global disease patterns, health outcomes, treatment effectiveness, mortality rates, and country-level health comparisons. The purpose of this project is to practise Power BI dashboard development while showcasing skills in public-health analytics, KPI design, data preparation, DAX measures, and insight communication.

Unlike a business sales dashboard, this project focuses on global health trends and disease-outcome analysis from a public-health and policy perspective.

## Dataset

Dataset: [Global Health Statistics on Kaggle](https://www.kaggle.com/datasets/malaiarasugraj/global-health-statistics)

The dataset provides global health statistics across countries and years, focusing on diseases, treatments, outcomes, prevalence, incidence, mortality rates, treatment effectiveness, and healthcare infrastructure.

The raw dataset is not stored in this repository. It can be downloaded from the Kaggle link above.

## Dashboard Preview

![Dashboard Preview](./images/dashboard_preview.png)

## Business / Analytical Questions

This dashboard explores the following questions:

1. Which diseases have the highest prevalence, incidence, and mortality rates?
2. How do health outcomes differ across countries and regions?
3. How does treatment effectiveness vary by disease?
4. Which countries show higher disease burden?
5. How do disease and mortality trends change over time?
6. What public-health areas may require more attention?

## Key Metrics

The dashboard includes the following metrics:

- Average Disease Prevalence Rate
- Average Disease Incidence Rate
- Average Mortality Rate
- Average Treatment Effectiveness
- Number of Countries
- Number of Diseases
- Disease Burden Score
- Mortality by Disease
- Treatment Effectiveness by Disease
- Health Outcomes by Country
- Yearly Disease Trend

## Tools Used

- Power BI
- Power Query
- DAX
- Kaggle dataset

## Data Preparation

Basic data preparation was completed in Power Query:

- Renamed columns for readability
- Checked and corrected data types
- Checked missing values and duplicate records
- Standardised country, disease, and treatment fields where needed
- Created disease burden groups for comparison
- Created treatment effectiveness groups
- Prepared year fields for trend analysis
- Removed or ignored columns not used in the dashboard

## Dashboard Pages

### 1. Global Health Overview

This page provides a high-level view of global health patterns.

It includes KPI cards for average prevalence rate, incidence rate, mortality rate, treatment effectiveness, number of countries, and number of diseases.

It also compares disease burden by country, disease prevalence by disease type, and yearly health trends.

The purpose of this page is to give users a broad understanding of global health conditions across countries and diseases.

### 2. Disease & Treatment Outcomes

This page focuses on disease severity, mortality, and treatment performance.

It analyses mortality rate by disease, treatment effectiveness by disease, disease burden groups, and country-level outcome differences.

The purpose of this page is to identify diseases and countries that may require greater public-health attention.

## Skills Demonstrated

This project demonstrates:

- Importing and preparing public-health data in Power BI
- Cleaning and transforming data in Power Query
- Creating calculated columns
- Creating DAX measures
- Building public-health KPI cards
- Analysing prevalence, incidence, mortality, and treatment effectiveness
- Creating grouped health-risk categories
- Using slicers for interactivity
- Comparing countries and diseases
- Designing an academic-style analytics dashboard
- Communicating insights from global health data

## Notes

This is a practice and portfolio project using a public Kaggle dataset. The dashboard is intended to demonstrate Power BI and public-health analytics skills rather than provide official medical or epidemiological conclusions.