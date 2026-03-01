# 📊 AI-Powered Sales Forecasting Dashboard

## 🔍 Overview
An end-to-end data analytics project that analyzes retail sales data from a 
US-based superstore, stores it in a MySQL database, predicts future revenue 
using Machine Learning, and presents insights through an interactive Power BI dashboard.

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| Python | Data cleaning, analysis & ML modeling |
| Pandas & Seaborn | Data manipulation & visualization |
| Scikit-learn | Linear Regression forecasting model |
| MySQL (XAMPP) | Database storage & SQL querying |
| Power BI | Interactive dashboard & reporting |

## 📁 Project Structure
```
Sales-Forecasting-Dashboard/
│
├── Sales Forecasting.ipynb    # Main analysis notebook
├── Sample - Superstore.csv    # Raw dataset (9,994 records)
├── monthly_sales.csv          # Monthly aggregated sales
├── top_products.csv           # Top 10 products by revenue
├── region_sales.csv           # Region wise performance
├── forecast.csv               # 12-month ML predictions
└── Sales_Forecasting_Dashboard.pdf  # Power BI dashboard export
```

## 📈 Key Findings
- 📦 **Canon imageCLASS** is the highest revenue generating product ($62K)
- 🌍 **West region** leads with 31.58% of total sales
- 📅 Sales show consistent growth with seasonal peaks
- 🤖 ML model forecasts next 12 months with measurable accuracy

## 🧠 ML Model Performance
| Metric | Value |
|--------|-------|
| Algorithm | Linear Regression |
| RMSE | *(your value)* |
| R-Squared | *(your value)* |

## 🎯 Skills Demonstrated
- End-to-End Data Pipeline Development
- Database Design & SQL Querying
- Machine Learning Model Building & Evaluation
- Business Intelligence & Dashboard Creation
- Version Control with Git & GitHub

## 📌 How to Run
1. Clone this repository
2. Install required libraries: `pip install pandas numpy matplotlib seaborn scikit-learn sqlalchemy pymysql`
3. Start XAMPP and run MySQL
4. Open `Sales Forecasting.ipynb` in Jupyter Notebook
5. Run all cells sequentially
