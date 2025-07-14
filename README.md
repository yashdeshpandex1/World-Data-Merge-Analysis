# World-Data-Merge-Analysis

A data manipulation and analysis project combining global datasets on **energy supply**, **economic performance**, and **scientific output** for top-ranked countries. This project focuses on cleaning, transforming, and merging multiple real-world datasets to prepare them for analysis.

## 📊 Project Overview

This project merges data from three primary sources:

1. **Energy Indicators** – Data from the United Nations on energy supply and renewable percentages.
2. **World Bank GDP Data** – Country-level GDP data from 2006–2015.
3. **Scimago Journal & Country Rank** – Rankings and metrics related to scientific output.

The final merged dataset includes:
- Energy Supply and % Renewable
- GDP from 2006–2015
- Scientific metrics (Documents, Citations, H-index)
- Country ranking (Top 15 based on Scimago)

## 🛠️ Features

- Data cleaning (renaming, filtering, unit conversions, etc.)
- Merging datasets using common country names
- Handling missing values and inconsistent naming
- Preparing data for downstream visualization or statistical analysis

## 📁 Files

- `data_manipulation_project.ipynb`: Main Jupyter notebook containing the full data processing pipeline.
- `Energy Indicators.xls`: UN energy data.
- `world_bank.csv`: World Bank GDP data (with years 2006–2015).
- `scimagojr-3.xlsx`: Scimago scientific ranking data.

## 📌 Requirements

- Python 3.x
- pandas
- numpy
- openpyxl (for reading `.xlsx` files)

Install with:

```bash
pip install pandas numpy openpyxl
