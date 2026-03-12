# 📊 Adidas Sales Data Analysis (PySpark + SparkSQL)

## 📌 Project Overview

This project analyzes the **Adidas sales dataset for the years 2020 and 2021** to uncover key business insights and trends that help improve sales performance and support business decision-making.

The analysis was performed using **PySpark and Spark SQL in Databricks**, where data cleaning, transformation, aggregation, and visualization were implemented.

The main objective of this project is to:

* Understand sales trends across different regions, states, and retailers
* Identify high-performing products and cities
* Analyze sales performance across time
* Generate insights that support business strategy

---

## 🎯 Business Requirements

The following business metrics were analyzed:

1. Total Sales
2. Total Profit
3. Average Price per Unit
4. Total Units Sold
5. Total Sales by Month
6. Total Sales by State
7. Total Sales by Region
8. Total Sales by Product
9. Total Sales by Retailer
10. Units Sold by Product Category and Gender
11. Top Performing Cities by Profit

---

## 🛠️ Technologies Used

* Python
* Apache Spark
* PySpark
* Spark SQL
* Databricks
* Databricks Notebook Visualizations

---

## 📂 Project Workflow

### 1️⃣ Data Ingestion

The Adidas sales dataset was loaded into Databricks.

### 2️⃣ Data Cleaning & Transformation

Using PySpark, several transformations were applied:

* Handling missing values
* Data type conversions
* Currency conversion to INR
* Creating derived columns such as:

  * `date_id`
  * `month_name`
  * `is_weekend`
  * `region`

### 3️⃣ Data Analysis

Business metrics were calculated using **PySpark and Spark SQL**.

### 4️⃣ Data Visualization

Interactive visualizations were created in the Databricks notebook to analyze:

* Sales trends over time
* Region-wise performance
* Product sales distribution
* Top performing cities by profit

---

## 📊 Key Insights

* Identified **top performing cities based on profit**
* Observed **monthly sales trends**
* Determined **high revenue generating products**
* Analyzed **regional and state level sales performance**
* Evaluated **retailer contribution to total sales**

---

## 📁 Repository Structure

```
Adidas-Sales-Analysis
│
├── adidas_sales_analysis.ipynb   # Databricks Notebook containing PySpark analysis
├── dataset/                      # Adidas sales dataset
├── images/                       # Visualization screenshots
└── README.md                     # Project documentation
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/your-username/adidas-sales-analysis.git
```

### 2. Open the notebook in Databricks

Upload the notebook to your Databricks workspace.

### 3. Upload the dataset

Place the dataset in your Databricks storage or workspace.

### 4. Run the notebook

Execute all cells to perform the data analysis and generate visualizations.

---

## 📸 Sample Visualizations

This project includes visualizations such as:

* Monthly Sales Trend
* Sales by Region
* Top Cities by Profit
* Product Sales Analysis

---

## 💡 Learning Outcomes

Through this project I gained practical experience in:

* Large scale data processing using Apache Spark
* Data transformation using PySpark
* Writing analytical queries using Spark SQL
* Building end-to-end data analytics workflows
* Creating visual insights for business analysis

---

## 🚀 Future Improvements

Possible enhancements for this project:

* Integrate Power BI dashboards
* Build a complete Bronze → Silver → Gold data pipeline
* Deploy the pipeline on cloud platforms like AWS or Azure

---

## 👨‍💻 Author

**Sumran Harchirkar**
B.Tech – Artificial Intelligence & Data Science
