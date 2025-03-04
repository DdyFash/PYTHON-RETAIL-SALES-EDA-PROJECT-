# Retail Customer Analysis - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project is an Exploratory Data Analysis (EDA) of a retail dataset containing customer transactions. The dataset includes demographic information, transaction details, and product categories. The goal is to derive insights into customer behavior, spending patterns, and store performance.

## 📂 Dataset Description
The dataset consists of **1,000,000 rows** and **22 columns**. Key features include:
- **🆔 customer_id**: Unique identifier for each customer
- **👤 Demographics**: age, gender, marital_status, education_level, occupation
- **💰 Financial Info**: income_bracket, loyalty_program, membership_years
- **🛒 Transaction Details**: transaction_id, transaction_date, product_id, product_category
- **📊 Purchase Details**: quantity, unit_price, discount_applied, total_price
- **🏬 Store Data**: payment_method, store_location
  
  ##🔗 Dataset Access
Due to the large size of the dataset, it can be accessed and downloaded from Kaggle using the following link:
https://www.kaggle.com/datasets/utkalk/large-retail-data-set-for-eda

## 🛠️ Data Cleaning Steps
✔ Removed unnecessary columns ( and extra dataset attributes)  
✔ Computed `total_price = quantity * unit_price * (1 - discount_applied)`  
✔ Verified data types and handled missing values  

## 🔍 Analysis Conducted
### 📊 1. Customer Demographics Analysis
- **Age Analysis**: Average customer age grouped by gender
- **Income Bracket Analysis**: Distribution of customers across income groups
- **Loyalty Program Analysis**: Percentage of customers enrolled in loyalty programs
- **Marital Status Analysis**: Breakdown of customers by marital status
- **Education Level Analysis**: Distribution of customers by education level
- **Occupation Analysis**: Number of customers categorized by occupation

### 🏬 2. Store Performance Analysis
- **Average Total Price per Store Location**: Comparison of store sales performance

### 🏷️ 3. Product Category Analysis
- **Total Revenue by Product Category**: Identified best-selling product categories

## 📊 Visualizations
- 📊 **Bar charts** for customer demographics and product sales
- 📉 **Pie charts** for categorical distributions (loyalty program, education, occupation, marital status)
- 📈 **Summary statistics** for numerical features

## 🔥 Insights & Key Findings
✅ **Balanced Gender Distribution**: No significant difference in average age across genders.  
✅ **Equal Distribution Across Income Brackets**: Customers are evenly distributed among high, medium, and low income brackets.  
✅ **Loyalty Program Participation**: Around **50%** of customers are enrolled in a loyalty program.  
✅ **Store Performance**: All stores have similar average total prices, indicating a balanced sales performance.  
✅ **Product Performance**: **Groceries** generated the highest revenue, followed by **Toys** and **Clothing**.  

## 📦 Requirements
To run this analysis, install the required Python libraries:
```sh
pip install pandas numpy matplotlib seaborn
```

## 🚀 How to Use
1. Load the dataset (`retail_data.csv`).
2. Run the Jupyter Notebook to generate the visualizations and insights.
3. Interpret the results to make data-driven business decisions.

---
This project provides a comprehensive analysis of retail customer data to identify spending patterns, customer segmentation, and store performance. **Future work** can include predictive modeling for customer retention and personalized marketing strategies. 🚀
