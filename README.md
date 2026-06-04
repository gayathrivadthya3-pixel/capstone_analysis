# capstone_analysis
# Week 8 Capstone: Real-World Business Analysis

A complete end-to-end data science project spanning three business domains.

## Project Structure
```
capstone/
├── data/
│   ├── house_prices.csv       # 300 residential properties
│   ├── customer_churn.csv     # 500 telecom customers
│   └── sales_data.csv         # 100 retail transactions
├── notebooks/
│   └── capstone_analysis_notebook.py   # Documented analysis script
├── reports/
│   ├── executive_summary.pdf  # 1-page executive summary
│   ├── technical_report.pdf   # Full technical report (7 pages)
│   ├── fig1_real_estate.png   # EDA visualisations
│   ├── fig2_churn.png
│   ├── fig3_sales.png
│   ├── fig4_advanced.png
│   └── fig5_dashboard.png
└── presentations/
    └── business_presentation.pptx  # 10-slide deck
```

## Business Problems
1. **Real Estate**: Identify key price drivers in the residential market
2. **Customer Churn**: Profile churn risk and root causes by contract type
3. **Sales Performance**: Optimise product and regional revenue strategy

## Analysis Techniques
- Exploratory Data Analysis (EDA)
- Linear Regression (Price ~ Area, R²=0.64)
- One-Way ANOVA (Location × Price/sqft, F=8.3, p<0.001)
- Chi-Square Test (Contract × Churn, χ²=6.8, p=0.033)
- Correlation Matrix Analysis

## Key Findings
| Domain | Finding |
|--------|---------|
| Real Estate | Area explains 64% of price variance; City Centre commands 28% premium |
| Churn | Month-to-month customers churn 4× more than 2-year contract holders |
| Sales | Laptops lead revenue (₹3.9M); North region dominates |

## Top Recommendations
1. 🔴 **HIGH**: Contract upgrade campaign — saves ~₹150K/yr in churn revenue
2. 🔴 **HIGH**: Expand Laptop inventory & East region — est. +15-20% revenue
3. 🟡 **MED**: City Centre Villa development pipeline
4. 🟡 **MED**: Laptop + Headphones cross-sell bundle

## Setup
```bash
pip install pandas numpy matplotlib seaborn scipy reportlab
python notebooks/capstone_analysis_notebook.py
```

## Deliverables
- Executive Summary 
- Technical Report
- Business Presentation 
- Analysis Script 
- 5 Professional Visualisations 
