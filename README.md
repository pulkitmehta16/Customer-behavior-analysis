# Customer Behavior Analysis Project 📊

## Overview 📌
This project focuses on analyzing customer behavior data to extract meaningful business insights. The workflow covers the complete data analytics pipeline, starting from raw data processing to interactive dashboard creation.

The project includes:
- Loading and processing the dataset using Python
- Cleaning and transforming data
- Running SQL queries in MySQL for business insights
- Building an interactive dashboard in Power BI

The goal of this project is to identify patterns in customer purchasing behavior, reviews, and product preferences to support better decision-making.

---

## Dataset 🗂️
The dataset contains customer purchase and behavior-related information, including:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount (USD)
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases

**Dataset Size**
- Rows: 3,900
- Columns: 18

---

## Tools and Technologies 🛠️
- **Python** — Data loading and preprocessing
- **Pandas** — Data manipulation
- **MySQL** — SQL querying and analysis
- **Power BI** — Dashboard creation
- **Jupyter Notebook** — Development environment

---

## Project Workflow ⚙️

### 1. Data Loading 📥
The dataset was imported into Python using Pandas for initial exploration.

### 2. Data Cleaning 🧹
The dataset was cleaned and transformed to improve data quality.

Tasks performed:
- Handled missing values
- Removed duplicate records
- Standardized data formats
- Created derived columns for analysis

### 3. SQL Analysis Using MySQL 🗄️
The cleaned dataset was imported into MySQL, where SQL queries were used to extract meaningful business insights such as:
- Product performance
- Customer purchasing trends
- Average review ratings
- Sales by category
- Payment method preferences

### 4. Dashboard Development in Power BI 📈
An interactive dashboard was created to visualize key business insights using charts, KPI cards, and filters.

---

## Dashboard Preview 🖥️

<img width="1416" height="771" alt="Customer_dashboard" src="https://github.com/user-attachments/assets/d1a1d8e5-8e3b-4e0c-8362-6d8d47a63770" />

---

## Results and Insights 💡

Key findings from the analysis include:
- High-performing product categories
- Customer buying patterns
- Impact of discounts on purchases
- Popular payment methods
- Seasonal purchasing trends

These insights can help businesses improve:
- Marketing strategies
- Customer retention
- Product recommendations
- Pricing decisions

---

## How to Run the Project ▶️

### Clone Repository
```bash
git clone <repository_link>
cd project-folder
```

### Install Dependencies
```bash
pip install pandas numpy matplotlib sqlalchemy pymysql
```

### Run the Project
- Open the Jupyter Notebook or Python script.
- Execute the data loading and data cleaning steps.
- Import the cleaned dataset into MySQL and run the SQL queries.
- Open the Power BI (.pbix) file to explore the interactive dashboard.

---

## Future Improvements 🚀
Potential enhancements include:
- Automating the data pipeline
- Predictive analytics for customer behavior
- Recommendation systems
- Real-time dashboard integration

---

## Author 👨‍💻
**Pulkit Mehta**

**Skills:** Python, SQL, MySQL, Power BI, Excel
