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
  - 
  <img width="1208" height="688" alt="1" src="https://github.com/user-attachments/assets/4a66a300-2d15-4d82-bf25-a0702b6c0dbd" />
  <img width="1218" height="481" alt="2" src="https://github.com/user-attachments/assets/d26004ae-1836-48b2-8f08-7a42c65f08f5" />
  <img width="1219" height="332" alt="3" src="https://github.com/user-attachments/assets/bb89c92b-a003-45b0-a3f2-729b581163d6" />



---

### 2. Data Visualization
The following visualizations were created:
- Histogram of Sales distribution
- Bar chart of Sales by Category
- Scatter plot of Sales trends

These visualizations helped in understanding patterns and trends in the dataset.

<img width="1226" height="570" alt="5" src="https://github.com/user-attachments/assets/4d261809-485e-4b15-88b3-a1e1f0ae418a" />
<img width="1223" height="670" alt="6" src="https://github.com/user-attachments/assets/0c466eac-c241-4cb3-a297-e4da67108b6f" />
<img width="1215" height="600" alt="7" src="https://github.com/user-attachments/assets/6767f4f5-3774-48c4-973f-3e1c8319dc77" />


---

### 3. Data Preprocessing
The dataset was cleaned and prepared by:
- Handling missing values
- Removing unnecessary columns
- Sampling data for analysis
- Creating reduced dataset

<img width="1224" height="375" alt="4" src="https://github.com/user-attachments/assets/e0cadfdd-2763-4624-b79f-ddf5b44d52fd" />
<img width="1248" height="153" alt="11" src="https://github.com/user-attachments/assets/0f76cabe-b8ef-4a39-9c35-51ef00c4e075" />
<img width="1216" height="80" alt="12" src="https://github.com/user-attachments/assets/e6dd9d7b-4b5a-4dc2-a96e-abff9c601944" />


---

### 4. Outlier Detection
Outliers were detected using the **IQR (Interquartile Range) method** on the Sales column. Extreme values were identified and handled to improve data quality.

<img width="1226" height="163" alt="8" src="https://github.com/user-attachments/assets/3846d224-2e06-4f33-aff6-fea4117823c5" />
<img width="1223" height="124" alt="9" src="https://github.com/user-attachments/assets/5ad5dee0-1a25-4b3a-8444-faa8e2cf1361" />
<img width="1234" height="770" alt="10" src="https://github.com/user-attachments/assets/1f98af03-1eaa-42fa-93e5-3c38b728d140" />


---

### 5. Data Scaling
Two scaling techniques were applied:
- Min-Max Normalization
- Z-Score Standardization

These methods helped normalize the data for better comparison.

<img width="1216" height="94" alt="13" src="https://github.com/user-attachments/assets/68caf87e-011e-4684-8099-6839553143fb" />
<img width="1216" height="97" alt="14" src="https://github.com/user-attachments/assets/aa23cf50-b651-403e-b65a-7ac4669540f1" />


---

### 6. Statistical Analysis
The following statistical measures were calculated:
- Mean, Median, Mode
- Minimum and Maximum values
- Variance and Standard Deviation
- Correlation matrix

<img width="1220" height="259" alt="15" src="https://github.com/user-attachments/assets/0b8dcf8c-945e-4b61-b474-d1218cdfb756" />
<img width="1211" height="801" alt="16" src="https://github.com/user-attachments/assets/6db16085-9929-4b33-a2df-c04bee1f7329" />
<img width="1242" height="145" alt="17" src="https://github.com/user-attachments/assets/58ee46da-36df-434d-8c93-0db2f119b1cc" />


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
