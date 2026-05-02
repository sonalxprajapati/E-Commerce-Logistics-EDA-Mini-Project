# E-Commerce Sales Analysis using Python

## Project Overview

This project performs Exploratory Data Analysis (EDA) on an e-commerce retail dataset to identify sales trends, customer purchasing behavior, product performance, and revenue patterns using Python.

The analysis focuses on:
- data cleaning and preprocessing,
- handling invalid transactions,
- feature engineering,
- revenue trend analysis,
- customer behavior analysis,
- and business insight generation through data visualization.

---

## Dataset Information

- **Dataset:** Online Retail Dataset
- **Link:** [[https://archive.ics.uci.edu/ml/datasets/Online+Retail](https://amanxai.com/2025/03/02/try-these-datasets-to-master-data-cleaning/)](https://drive.google.com/file/d/13EGGRgJPiTADcPZzGyFDsj9uZliSOcJE/view?usp=sharing)

> Due to GitHub file size limitations, the original dataset is not included in this repository.

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter

---

## Project Workflow

### 1. Data Loading & Exploration
- Loaded and inspected the dataset
- Reviewed dataset structure, datatypes, and summary statistics
- Identified missing values

### 2. Data Cleaning & Preprocessing
- Removed duplicate records
- Handled invalid transactions
- Removed negative quantity and pricing values
- Converted date columns to datetime format

### 3. Feature Engineering
Created new analytical features including:
- `TotalPrice`
- `YearMonth`
- `Hour`

### 4. Exploratory Data Analysis (EDA)
Performed analysis on:
- Revenue by country
- Top-selling products
- Monthly revenue trends
- Customer revenue contribution
- Correlation analysis
- Customer purchasing activity by hour

### 5. Data Visualization
Generated multiple visualizations including:
- Bar charts
- Line plots
- Scatter plots
- Correlation heatmaps
- Boxplots

---

## Key Findings

1. The United Kingdom generated the highest revenue by a significant margin, indicating strong customer concentration in that market.

2. Revenue increased substantially during September–November 2011, with November recording the highest sales.

3. Several transactions involved unusually large purchase quantities, suggesting wholesale or bulk purchasing behaviour.

4. Quantity purchased showed a strong positive relationship with total revenue.

5. Customer purchasing activity peaked between 12 PM and 3 PM.

6. A small number of products contributed disproportionately high sales volumes.

7. Negative quantities and unit prices were identified as cancelled transactions or pricing adjustments and were removed during preprocessing.

---
