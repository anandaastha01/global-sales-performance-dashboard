# global-sales-performance-dashboard
This project analyzes worldwide sales data to uncover geographic, temporal, and product-level trends, using both Python for basic EDA and Power BI for interactive visualizations.
The dashboard highlights regional performance, profitability, shipping trends, and sales growth across countries and continents.
# project structure
global-sales-performance-dashboard

├── global_sales_data.csv # Raw dataset 
├── cleaned_global_sales.csv # Post-EDA cleaned dataset (used in Power BI)
├── global_salesdata_analysis.pbix # Power BI dashboard file
├── Gloabal_Sales_DataAnalysis.ipynb  # Python Bsic EDA file
├── Presentation - Gsales_Dashboard_brief.pdf # Final project summary 
└── README.md # This file
# tools and technologies
   - Python (Pandas, Matplotlib, Seaborn) – for initial data inspection, cleaning & preprocessing
   - Power BI Desktop – for building the final interactive dashboard
   - Git & GitHub – version control and code hosting
# dataset overview
5901 rows × multiple columns
   - Fields include: 'Country', 'region', 'product', 'category', 'sub category', 'sales', 'profit', etc.
   - A custom `Date' table was added in Power BI for time-based calculations
   - A group mapping was created to relate countries with their respective continents
   - DAX measures were used for visual analysis in Power BI
# dashboard features
   - page 1 : Executive Summary
   - page 2 : Regional & Segment Analysis
   - page 3 : Product & Monthly Trends
   - page 4 : Shipping & Delivery Performance
# How To Run
1. Python Notebook (EDA & Data Cleaning)
Open the notebook file:
Gloabal_Sales_DataAnalysis.ipynb

You can run it in any IDE or platform that supports Jupyter Notebooks:
Jupyter Notebook
VS Code (with Jupyter extension)
Google Colab
JupyterLab
This notebook includes:
   - Basic exploratory data analysis (EDA)
   - Data cleaning and transformation steps
   - Export of the cleaned dataset (cleaned_global_sales.csv) for Power BI usage
2. Power BI Dashboard  
   - Open 'global_salesdata_analysis.pbix' in Power BI Desktop
   - Refresh data if needed
   - Interact using slicers and filters on each page
#  Deliverables
   - Raw Dataset ('global_sales_data.csv')
   - Cleaned Dataset ('cleaned_global_sales.csv')
   - Python EDA File (.ipynb)
   - Power BI Dashboard (.pbix)
   - Project brief (PDF)
   - README.md 
