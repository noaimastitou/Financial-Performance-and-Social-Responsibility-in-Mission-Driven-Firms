# Financial Performance and Corporate Social Responsibility in Mission-Driven Firms

This repository contains the complete data collection, processing, and econometric analysis pipeline developed for my Master's thesis on the relationship between **Corporate Social Responsibility (CSR)** and **financial performance** in French mission-driven companies.

## Overview

This project investigates whether obtaining the **Mission-Driven Company** status has a measurable impact on firms' financial performance between **2019 and 2024**. It combines automated data collection, data engineering, statistical analysis, and causal inference methods to evaluate the financial effects of CSR engagement.

## Features

- Automated web scraping using **Python** and **Selenium**
- ETL pipeline for financial data extraction and normalization
- CSR classification through keyword-based text mining
- Integration of financial and CSR datasets into a longitudinal panel
- Data cleaning, feature engineering, and exploratory analysis
- Difference-in-Differences (DiD) econometric models
- Two-Way Fixed Effects (TWFE) estimation
- Sun & Abraham estimator for staggered treatment analysis
- Robustness checks and event-study validation
- Data visualization and statistical reporting

## Dataset

The final analytical dataset contains:

- **616 French mission-driven firms**
- **2,073 firm-year observations**
- Financial indicators (Revenue, Net Income, ROA, ROE, Debt, Assets, etc.)
- Industry-adjusted CSR scores based on the EcoVadis framework
- Observation period: **2019–2024**

## Technologies

- Python
- Selenium
- Pandas
- NumPy
- Statsmodels
- linearmodels
- Matplotlib
- Econometrics (Panel Data)
- Difference-in-Differences (DiD)

## Main Findings

The analysis finds **no statistically significant average short-term financial effect** of Mission-Driven Company certification across most financial performance indicators. However, the results reveal important **heterogeneity between treatment cohorts**, suggesting that the financial impact of CSR may vary across firms and over longer time horizons.

## Academic Context

This project was completed as part of the **Master's Degree in Applied Economics** at the Faculty of Economics and Management during the 2025–2026 academic year.
