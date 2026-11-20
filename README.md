# CodeAlpha – Exploratory Data Analysis (EDA)

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a Books Dataset containing 1,000 books collected from Books to Scrape.

The objective is to understand the dataset, identify patterns, analyze book prices and ratings, detect data quality issues, and perform statistical hypothesis testing.

## Objectives
- Explore dataset structure and data types.
- Identify missing values and duplicate records.
- Analyze book price, rating, and availability distributions.
- Identify trends and relationships between price and rating.
- Detect potential outliers using the IQR method.
- Perform statistical hypothesis testing using the Kruskal-Wallis test.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Dataset Information
- Total Records: 1,000
- Total Columns: 4

### Dataset Columns
1. Book Name
2. Price
3. Rating
4. Availability

## Analysis Performed
1. Dataset Structure Analysis
2. Data Quality Checking
3. Univariate Analysis
4. Bivariate Analysis
5. Outlier Detection using IQR
6. Statistical Hypothesis Testing

## Key Findings
- Total Books Analyzed: 1,000
- Average Book Price: £35.07
- Highest Book Price: £59.99
- Lowest Book Price: £10.00
- Most Common Rating: 1 Star
- Missing Values: 0
- Duplicate Rows: 0
- IQR Outliers: 0

## Statistical Hypothesis Testing
The Kruskal-Wallis test was used to examine whether book prices differ across rating groups.

- Test Statistic: 1.5642
- P-value: 0.8152
- Significance Level: 0.05

Since the p-value is greater than 0.05, we fail to reject the null hypothesis.

There is no statistically significant evidence of a difference in book prices across rating groups in this dataset.

## Conclusion
This project helped me understand the structure and quality of a real-world dataset, perform exploratory data analysis, visualize patterns, detect outliers, and apply statistical hypothesis testing using Python.

## Internship
This project was completed as part of the CodeAlpha Data Analytics Internship.