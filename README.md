📊 Adidas Sales Data Analysis (PySpark + SparkSQL)
📌 Project Overview

This project analyzes the Adidas sales dataset for the years 2020 and 2021 to uncover key business insights and trends that can help improve sales performance and optimize business strategies.

The analysis was implemented using PySpark and Spark SQL inside a Databricks Notebook, where data transformation, aggregation, and visualization were performed.

The goal of this project is to:

Understand sales performance across different regions, products, and retailers.

Identify trends and patterns in sales data.

Provide insights that can help in data-driven decision making.

🎯 Business Objectives

The following business metrics were analyzed:

Total Sales

Total Profit

Average Price per Unit

Total Units Sold

Total Sales by Month

Total Sales by State

Total Sales by Region

Total Sales by Product

Total Sales by Retailer

Units Sold by Product Category and Gender

Top Performing Cities by Profit

🛠️ Technologies Used

🐍 Python

⚡ Apache Spark

🔥 PySpark

🗄️ Spark SQL

📊 Data Visualization (Databricks Notebook Charts)

☁️ Databricks

📂 Project Workflow

The project follows a typical data analytics pipeline:

1️⃣ Data Ingestion

Raw Adidas sales dataset was loaded into Databricks.

2️⃣ Data Cleaning & Transformation

Using PySpark, several transformations were applied such as:

Handling null values

Data type conversion

Currency conversion to INR

Creating additional columns like:

month_name

date_id

is_weekend

region mapping

3️⃣ Data Analysis

Using Spark SQL and PySpark, the dataset was aggregated to calculate key business metrics.

4️⃣ Data Visualization

Charts and visualizations were created inside the Databricks notebook to present insights such as:

Sales trends by month

Profit by city

Sales distribution by region

Product performance

📊 Key Insights Generated

Some of the important insights obtained from this analysis include:

Identification of top-performing cities based on profit

Analysis of sales trends across months

Understanding which products generate the highest revenue

Comparison of sales performance across regions and states

Retailer-level sales contribution analysis

📁 Repository Structure
Adidas-Sales-Analysis
│
├── adidas_sales_analysis.ipynb   # Databricks Notebook
├── dataset/                      # Adidas sales dataset
├── images/                       # Visualizations
└── README.md                     # Project documentation
▶️ How to Run the Project

Clone the repository

git clone https://github.com/your-username/adidas-sales-analysis.git

Open the notebook in Databricks

Upload the dataset.

Run the notebook cells to perform the analysis and generate visualizations.

📸 Sample Visualizations

Examples of charts generated in this project include:

📈 Monthly Sales Trend

🌍 Sales by Region

🏙️ Top Cities by Profit

👟 Sales by Product Category

💡 Learning Outcomes

Through this project I gained practical experience in:

Large-scale data processing using Apache Spark

Data transformation with PySpark

Writing analytical queries using Spark SQL

Building end-to-end data analysis pipelines

Creating visual insights for business decision making

🚀 Future Improvements

Integrate **Power BI for advanced dashboards

Implement ETL pipeline architecture (Bronze–Silver–Gold layers)

Deploy the pipeline on cloud platforms like AWS or Azure

👨‍💻 Author

Sumran Harchirkar
B.Tech – Artificial Intelligence & Data Science
