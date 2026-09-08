# Task 5 – Exploratory Data Analysis (EDA)

## Data Analyst Internship

This project is part of my **Data Analyst Internship – Task 5**, where I performed Exploratory Data Analysis (EDA) on the **Supermart Grocery Sales – Retail Analytics Dataset** using Python.

The main purpose of this task is to understand the dataset, explore important variables, identify relationships and trends, and extract useful business insights through statistical analysis and data visualization.



## Objective

The objectives of this task are:

- Understand the structure and characteristics of the dataset.
- Check data quality and completeness.
- Perform statistical analysis using descriptive statistics.
- Analyze the distribution of Sales and Profit.
- Identify potential outliers.
- Study relationships between Sales, Profit, and Discount.
- Analyze correlation between numerical variables.
- Compare sales performance across categories and regions.
- Analyze yearly sales trends.
- Summarize the key findings from the EDA.



## Dataset

**Dataset Name:** Supermart Grocery Sales – Retail Analytics Dataset

The dataset contains **9,994 records and 11 columns** related to grocery sales transactions.

Some important columns used in the analysis are:

- Order Date
- Category
- Sub Category
- City
- Region
- Sales
- Discount
- Profit



## Tools and Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook



## Work Performed

### 1. Data Loading

- Imported the required Python libraries.
- Loaded the Supermart Grocery Sales CSV dataset using Pandas.
- Converted the `Order Date` column into date format.

### 2. Data Understanding

Performed basic data exploration using:

- `df.head()`
- `df.shape`
- `df.info()`
- Missing value checking
- Duplicate value checking
- `df.describe()`

The dataset contains **9,994 rows and 11 columns**.

There are **no missing values** and **no duplicate records**.

### 3. Category Analysis

Used `value_counts()` to understand the distribution of product categories in the dataset.

### 4. Sales Distribution

Created a **histogram of Sales** to understand the distribution of sales values.

**Observation:** Sales values are concentrated at lower ranges, with a smaller number of high-value transactions.

### 5. Profit Distribution

Created a **histogram of Profit** to examine the distribution and shape of profit values.

**Observation:** Profit is moderately right-skewed, with most observations concentrated at lower profit values and fewer high-profit transactions.

### 6. Profit Outlier Analysis

Created a **boxplot of Profit** to identify potential outliers.

The IQR method identified approximately **43 potential Profit outliers**.

These observations were not automatically removed because they may represent legitimate high-value business transactions.

### 7. Sales vs Profit Analysis

Created a **scatterplot between Sales and Profit**.

**Observation:** Sales and Profit show a moderate positive relationship. Higher sales generally tend to be associated with higher profit.

The correlation between Sales and Profit is approximately **0.61**.

### 8. Discount vs Profit Analysis

Created a **scatterplot between Discount and Profit**.

**Observation:** There is no strong linear relationship between Discount and Profit. Profit values are widely scattered across different discount levels, suggesting that discount alone does not strongly influence profit.

### 9. Correlation Analysis

Created a **correlation matrix and heatmap** to examine relationships between numerical variables.

The heatmap helps identify the strength and direction of relationships between Sales, Discount, and Profit.

### 10. Pairplot Analysis

Created a **pairplot** for:

- Sales
- Discount
- Profit

This was used to visually examine multiple relationships and distributions between the numerical variables.

### 11. Sales by Category

Created a bar chart showing total Sales for each product category.

**Observation:** **Eggs, Meat & Fish** has the highest total sales, while **Oil & Masala** has comparatively lower sales.

### 12. Sales by Region

Created a bar chart to compare total Sales across regions.

**Observation:** The **West region** has the highest sales performance. The North region has very limited observations, so its result should be interpreted cautiously.

### 13. Yearly Sales Trend

Created a yearly sales trend to understand how sales changed over time.

**Observation:** Sales increased from **2015 to 2018**, with **2018 recording the highest annual sales**.

## Key Findings

- The dataset contains **9,994 records and 11 columns**.
- There are **no missing values or duplicate records**.
- Total Sales is approximately **14.96 million**.
- Total Profit is approximately **3.75 million**.
- Profit is moderately right-skewed.
- Some potential high-value Profit outliers were identified.
- Sales and Profit have a moderate positive correlation of approximately **0.61**.
- Discount has a weak relationship with Profit.
- **Eggs, Meat & Fish** is the highest-sales category.
- The **West region** has the strongest sales performance.
- Sales increased from **2015 to 2018**.
- **2018** recorded the highest annual sales.



## Conclusion

The Exploratory Data Analysis provides useful insights into the Supermart Grocery Sales dataset. The analysis shows positive sales growth over time and a moderate relationship between Sales and Profit. There are also noticeable differences in sales performance across categories and regions.

Profit contains some potential outliers, while Discount does not show a strong linear relationship with Profit. Overall, the EDA helps identify important business patterns and provides a foundation for further analysis and decision-making.


## Project Structure

```text
Task 5 – Exploratory Data Analysis/
│
├── Task 5_Exploratory Data Analysis.ipynb
├── README.md
└── Supermart Grocery Sales - Retail Analytics Dataset.csv
and Report of Findings.pdf
