
# Customer Purchase Behavior Analysis using Descriptive Statistics

## Project Overview
In this project, I performed a descriptive statistical analysis on a restaurant transaction dataset to understand customer spending behavior. The objective was to apply core statistical concepts such as central tendency, dispersion, correlation, and data visualization to extract meaningful insights.

This project demonstrates how basic statistical methods can be used to analyze customer purchase patterns and support decision-making in business environments.

---

## Dataset
**Dataset Used:** Tips Dataset  
**Source:** Seaborn built-in dataset

The dataset contains information about restaurant bills and tips, including:

- `total_bill` – total amount of the bill
- `tip` – tip given by the customer
- `sex` – gender of the customer
- `smoker` – whether the customer is a smoker
- `day` – day of the week
- `time` – lunch or dinner
- `size` – number of people in the party

---

## Objectives
The main objectives of this project were:

1. Load and understand the dataset.
2. Identify quantitative and qualitative variables.
3. Clean the data if necessary.
4. Compute measures of central tendency:
   - Mean
   - Median
   - Mode
5. Measure dispersion:
   - Range
   - Variance
   - Standard deviation
   - Interquartile range (IQR)
6. Create visualizations to understand patterns.
7. Perform correlation analysis.
8. Generate insights based on the analysis.

---

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Understanding
- Loaded the tips dataset from Seaborn.
- Identified numerical and categorical variables.

### 2. Data Cleaning
- Checked for missing or invalid values.
- Ensured numerical variables were valid for analysis.

### 3. Central Tendency Analysis
Calculated mean, median, and mode for:
- Total bill
- Tip
- Party size

Also compared these metrics across:
- Gender
- Day of the week

### 4. Dispersion Analysis
Computed:
- Range
- Variance
- Standard deviation
- Interquartile range (IQR)

For:
- Total bill
- Tip

### 5. Data Visualizations
Created:
- Histogram of total bill distribution
- Boxplot of total bill by gender
- Bar chart of transactions per day
- Scatter plot between party size and total bill

### 6. Correlation Analysis
Analyzed relationships between:
- Total bill and tip
- Total bill and party size

---

## Key Insights
- There is a positive relationship between total bill and tip.
- Larger groups generally generate higher total bills.
- Spending patterns vary slightly across different days.
- The distribution of total bills shows a few high-value outliers.

---

## Business Implications
- Larger parties can be targeted with group discounts or special offers.
- Peak days can be used for promotional campaigns.
- High-spending customers may be ideal for loyalty programs.

---

## Author
**Nihal Antony Lopez**  
B.Tech Student  
Aspiring Data Analyst / Data Scientist
