# 📊 Customer Shopping Behavior Analysis

## 📌 Overview

This project analyzes customer shopping behavior using transactional data to uncover **spending patterns, customer segments, and product insights**.
It follows an end-to-end analytics workflow using **Python, SQL, and Power BI**, transforming raw data into actionable business recommendations.


## 📂 Dataset

* **File:** `customer_shopping_behavior.xlsx`
* **Records:** 3,900 transactions
* **Features:** 18 columns

### Includes:

* Customer demographics (Age, Gender, Location, Subscription Status)
* Purchase details (Category, Item, Amount, Season, Size, Color)
* Behavioral data (Discounts, Frequency, Ratings, Shipping Type)

## 🛠️ Tech Stack

* **Python (Pandas)** → Data Cleaning & EDA
* **SQL (PostgreSQL)** → Business Analysis
* **Power BI** → Dashboard & Visualization
* **Excel** → Raw Dataset
* **Gamma / PowerPoint** → Presentation

## 🔄 Project Workflow

### 1. Data Cleaning & Preparation

* Handled missing values using **median imputation (category-wise)**
* Standardized column names to **snake_case**
* Removed redundant fields (`promo_code_used`)

### 2. Feature Engineering

* Created `age_group` for segmentation
* Derived `purchase_frequency_days`

### 3. Exploratory Data Analysis

* Identified trends in customer spending
* Analyzed category-wise performance
* Visualized key behavioral patterns

### 4. SQL Analysis

Performed business-driven queries to answer:

* Revenue distribution by gender
* High-spending discount users
* Top-rated products
* Customer segmentation (New, Returning, Loyal)
* Subscription impact on revenue
* Discount dependency of products

### 5. Dashboard Development

* Built interactive dashboard in **Power BI**
* Included KPIs, filters, and category-level insights

  <img width="634" height="345" alt="image" src="https://github.com/user-attachments/assets/f3f2fd25-a1b5-4788-a491-0f5e9ee640fe" />


## 📊 Dashboard Highlights

* Revenue & sales KPIs
* Category performance analysis
* Customer segmentation
* Purchase behavior trends
* Interactive filtering


## 📈 Key Insights

* Loyal customers contribute significantly higher revenue
* Subscription users show more consistent purchasing behavior
* Certain products rely heavily on discounts
* Higher purchase values are associated with express shipping


## 💡 Business Recommendations

* Promote subscription plans for retention
* Target high-value customer segments
* Introduce loyalty programs
* Optimize discount strategies
* Highlight top-performing products in marketing


## 📁 Project Structure

```
├── customer_shopping_behavior_analysis.ipynb
├── customer_shopping_behavior.xlsx
├── customer_shopping_behavior_dashboard.pbix
├── customer_shopping_analysis_report.pdf
├── business_problem_document.pdf
├── customer_shopping_behavior_analysis.pptx
└── README.md
```

## ▶️ How to Run

### 1. Clone Repository

```bash
git clone https://github.com/your-username/customer-shopping-analysis.git
cd customer-shopping-analysis
```

### 2. Run Notebook

```bash
jupyter notebook
```

### 3. Open Dashboard

* Open `.pbix` file in **Power BI Desktop**

### 4. SQL Analysis

* Import dataset into PostgreSQL
* Run queries used in analysis



## 🚀 Key Takeaways

* End-to-end data analytics pipeline
* Strong integration of Python, SQL, and BI tools
* Focus on business insights and decision-making

## Credits

This project is based on a guided tutorial by Amlan Mohanty.
I followed the project to understand data analysis workflows and implemented the code myself.

Original repository: `https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI`


