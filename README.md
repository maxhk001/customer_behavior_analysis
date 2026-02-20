# Customer Behavior Analysis Project

## 📌 Overview
This project analyzes customer purchasing behavior using Python, SQL, and Power BI.  
The objective is to extract actionable insights from raw transactional data and present them through an interactive dashboard and business report.

The project demonstrates end-to-end data analytics workflow including:
- Data loading
- Data cleaning
- Exploratory Data Analysis (EDA)
- SQL-based data querying
- Dashboard creation
- Business reporting

---

## 📂 Dataset
The dataset contains customer transaction data including:
- Customer ID
- Age
- Gender
- Subscription Status
- Item Purchased
- Category
- Purchase Amount
- Review Rating
- Shipping Type

---

## 🛠 Tools & Technologies Used

- **Python** (Pandas, NumPy, Matplotlib)
- **SQL** (PostgreSQL)
- **SQLAlchemy**
- **Power BI**
- **pgAdmin**
- **Jupyter Notebook**

---

## 🔄 Project Workflow

### 1️⃣ Data Loading (Python)
- Imported CSV dataset using Pandas
- Inspected data structure and datatypes

### 2️⃣ Data Cleaning
- Checked for null values
- Fixed datatype inconsistencies
- Removed duplicates (if any)
- Validated categorical columns

### 3️⃣ Exploratory Data Analysis (EDA)
- Revenue by category
- Sales by age group
- Subscription-based revenue analysis
- Average purchase & review rating insights

### 4️⃣ SQL Integration
- Connected Python to PostgreSQL using SQLAlchemy
- Loaded DataFrame into PostgreSQL
- Performed aggregation queries:
  - Revenue by gender
  - Revenue by category
  - Customer segmentation

### 5️⃣ Dashboard Development (Power BI)
Created interactive dashboard including:
- KPI Cards (Total Customers, Avg Purchase, Avg Rating)
- Revenue by Category
- Sales by Age Group
- Subscription Distribution
- Dynamic Filters (Gender, Category, Shipping Type)

### 6️⃣ Business Report
- Summary insights prepared
- PPT created for presentation
- Key findings documented

---

## 📊 Key Insights

- Majority customers are non-subscribers.
- Clothing category generates highest revenue.
- Young adults contribute the highest sales volume.
- Average review rating is moderate (~3.75).
- Subscription status impacts purchasing behavior.

---

## ▶ How to Run

### Step 1: Clone Repository


### Step 2: Install Dependencies


### Step 3: Run Jupyter Notebook


### Step 4: PostgreSQL Setup
- Create database: `customer_behavior`
- Run provided SQL queries

### Step 5: Open Power BI File
- Open `.pbix` file in Power BI Desktop

---

## 📁 Project Structure

Customer-Behavior-Analysis/
│
├── data/
├── notebooks/
├── sql/
├── dashboard/
├── reports/
└── README.md


---

## 🎯 Skills Demonstrated

- Data Cleaning & EDA
- SQL Query Writing
- Database Integration
- Dashboard Design
- Business Insight Communication
- Debugging & Error Handling

---

## 📌 Conclusion
This project demonstrates a complete data analytics pipeline from raw dataset to business-ready dashboard and report.

It reflects practical skills in data processing, SQL querying, and visualization suitable for entry-level data analyst roles.
