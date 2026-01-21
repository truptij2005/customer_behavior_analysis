# customer_behavior_analysis
data project 
🔍 Overview

This project analyzes customer behavior using Python, SQL, and Power BI.
It covers the full data-analysis workflow: loading raw data, performing exploratory data analysis (EDA), cleaning the dataset, running SQL queries on PostgreSQL/MySQL/SQL Server, building a Power BI dashboard, and creating a final report and PPT using Gamma.
The goal is to derive meaningful insights that support data-driven decision-making.

📁 Dataset

Source: Provided CSV dataset (customer_behavior.csv)

Rows: Add actual count

Columns: Customer demographics, purchase amounts, items purchased, discount usage, product ratings, and more.

Key Features in the dataset:

Customer ID

Age, Gender

Purchase Amount

Discount Applied (Yes/No)

Product Category / Item Purchased

Rating

Purchase Date

🛠 Tools & Technologies
Category	Tools Used
Programming	Python (Pandas, NumPy, Matplotlib, Seaborn)
Databases	PostgreSQL / MySQL / SQL Server
Visualization	Power BI
Notebook	Jupyter Notebook
Presentation	Gamma App
Other	SQL, CSV
🔄 Project Workflow
1. Load Dataset

Imported the CSV file using Python (Pandas)

Displayed initial structure, data types, and sample rows

2. Exploratory Data Analysis (EDA)

Descriptive statistics

Distribution analysis

Correlation analysis

Outlier detection

Visualizations (Histograms, Bar charts, Boxplots, Heatmaps)

3. Data Cleaning

Handling missing values

Removing duplicates

Fixing data types

Treating outliers

Standardizing categorical values and formatting

4. SQL Analysis

Executed complex SQL queries using PostgreSQL/MySQL/SQL Server:

Examples:

Total revenue by gender

Customers using discounts but spending more than average

Most purchased items

Average product ratings

Customer segmentation based on spend

Python → PostgreSQL connection done using SQLAlchemy / psycopg2.

5. Power BI Dashboard

Created an interactive dashboard highlighting:

Total revenue

Sales by gender

Top product categories

Discount impact analysis

Average rating distribution

Customer segmentation visuals

Dashboard includes slicers, bar charts, KPIs, and trend visuals.

6. Report Creation

A clean, insights-focused Power BI report summarizing:

Key findings

Business implications

Recommendations

7. Presentation (Gamma PPT)

A polished PPT created using Gamma AI:

Project overview

Approach & methodology

EDA insights

SQL results

Dashboard screenshots

Final business recommendations

🧠 Key Insights / Results

Identified top-performing customer segments

Found which products contribute the most revenue

Quantified impact of discounts

Highlighted patterns in high-value customer behavior

Provided actionable recommendations for marketing & sales teams

(Customize this section with your findings.)

▶️ How to Run This Project
1. Clone the Repository
git clone https://github.com/yourusername/customer-behavior-analytics.git
cd customer-behavior-analytics

2. Install Required Libraries
pip install -r requirements.txt

3. Run Jupyter Notebook
jupyter notebook


Open: Customer_Analytics.ipynb

4. Configure Database

Update credentials inside the notebook:

host = "localhost"
user = "your_username"
password = "your_password"
database = "customer_behavior"

5. Run SQL Queries

Use pgAdmin / MySQL Workbench / SQL Server Management Studio
or run queries directly from Python.

6. Open Power BI Dashboard

Open Customer_Dashboard.pbix in Power BI Desktop.

7. View Final Report & PPT

/Report/Customer_Behavior_Report.pdf

/Presentation/Customer_Behavior_Presentation.gslides

📦 Project Structure
├── data/
│   └── customer_behavior.csv
├── notebooks/
│   └── Customer_Analytics.ipynb
├── sql/
│   └── queries.sql
├── dashboard/
│   └── Customer_Dashboard.pbix
├── report/
│   └── Final_Report.pdf
├── ppt/
│   └── Gamma_Presentation.pdf
└── README.md

⭐ Future Enhancements

Build a predictive model (Customer churn / purchase prediction)

Deploy dashboard online

Create automated ETL pipeline
