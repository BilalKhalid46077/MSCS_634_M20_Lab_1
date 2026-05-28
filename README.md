# Data Visualization & Preprocessing Lab

## Project Overview
This project is a data analysis lab that demonstrates how to perform data visualization, preprocessing, and statistical analysis using Python. The dataset used is the **Superstore Sales Dataset**, which contains information about customer orders, sales, categories, and regions.

The main objective of this lab is to understand how raw data is explored, cleaned, visualized, and prepared for further analysis.

---

## Dataset Information
The dataset includes the following key columns:
- Order ID
- Order Date
- Ship Mode
- Customer Details
- City, State, Region
- Product Category & Sub-Category
- Sales

Total records: ~9800 rows  
Total columns: 18

---

## Tools & Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Project Steps

### 1. Data Loading
- Dataset was loaded using Pandas `read_csv()`
- Initial exploration was done using:
  - `df.head()`
  - `df.info()`
  - `df.describe()`

---

### 2. Data Visualization
The following visualizations were created:
- Histogram of Sales distribution
- Bar chart of Sales by Category
- Scatter plot of Sales trends

These visualizations helped in understanding patterns and trends in the dataset.

---

### 3. Data Preprocessing
The dataset was cleaned and prepared by:
- Handling missing values
- Removing unnecessary columns
- Sampling data for analysis
- Creating reduced dataset

---

### 4. Outlier Detection
Outliers were detected using the **IQR (Interquartile Range) method** on the Sales column. Extreme values were identified and handled to improve data quality.

---

### 5. Data Scaling
Two scaling techniques were applied:
- Min-Max Normalization
- Z-Score Standardization

These methods helped normalize the data for better comparison.

---

### 6. Statistical Analysis
The following statistical measures were calculated:
- Mean, Median, Mode
- Minimum and Maximum values
- Variance and Standard Deviation
- Correlation matrix

---

## Screenshots
All required screenshots of outputs (graphs, preprocessing steps, and statistical results) are included in the `/screenshots` folder.

---

## Key Insights
- Sales data is highly skewed with some extreme values (outliers)
- Certain product categories generate higher total sales
- Data required preprocessing before analysis
- Scaling helped normalize large variations in sales values

---

## Challenges Faced
- Handling missing values in the dataset
- Dealing with outliers in sales data
- Choosing correct visualizations for analysis
- Memory issues with large dataset loading

---

## How to Run This Project
1. Clone the repository:
```bash
git clone https://github.com/your-username/repository-name.git
