# CUSTOMER_SALES_ANALYSIS
📊 Customer Sales Analysis Dashboard
📌 Project Overview

This project performs a comprehensive Customer Sales Analysis using Python and Pandas.

The objective is to analyze transaction data, identify top customers, evaluate regional performance, detect seasonal trends, and generate actionable business insights.

The project follows a complete data analysis pipeline including:

Data loading

Data cleaning & preprocessing

Data merging

Aggregation & KPI calculation

Pivot table summarization

Professional data visualization

📂 Project Structure
Customer-Sales-Analysis/
│
├── customer_analysis.ipynb    # Main analysis notebook
├── sales_data.csv             # Sales transaction dataset
├── customer_data.csv          # Customer dataset
├── analysis_report.pdf        # Final business report
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation

🛠️ Technologies Used

Python 3

Pandas

Matplotlib

Seaborn

Jupyter Notebook

🔧 Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/your-username/Customer-Sales-Analysis.git
cd Customer-Sales-Analysis

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Notebook

Open in VS Code or Jupyter:

jupyter notebook


Run customer_analysis.ipynb from top to bottom.

📊 Key Analysis Performed
✅ 1. Key Performance Indicators (KPIs)

Total Revenue

Total Customers

Average Order Value

✅ 2. Top Customers

Identified highest revenue-generating customers using group-by aggregation.

✅ 3. Regional Sales Analysis

Visualized sales distribution across regions.

✅ 4. Monthly Sales Trend

Analyzed seasonal sales patterns.

✅ 5. Best-Selling Products

Determined most sold products by total quantity.

✅ 6. Pivot Table Analysis

Created region vs month summary using pd.pivot_table().

📈 Sample Business Insights

Certain customers contribute disproportionately to revenue.

Sales performance varies significantly by region.

Monthly trends indicate potential seasonal peaks.

Product demand varies across different locations.

Data suggests opportunities for targeted marketing campaigns.

🧠 Technical Implementation Highlights

Data merging using pd.merge()

Multiple group-by aggregations

Pivot table summarization

Professional visualizations

Cleaned column names for robustness

Debugging and error handling during development

📌 Assignment Requirements Covered

✔ Pandas for all data manipulation
✔ At least 3 aggregations
✔ Data merging/joining
✔ Pivot table creation
✔ Professional visualizations
✔ Written report with insights
