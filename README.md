# 📊 Retail Liquor Sales Analysis – Iowa (US)

> **A comprehensive Exploratory Data Analysis (EDA) project using Python to analyze retail liquor sales across Iowa, uncover sales patterns, evaluate product and vendor performance, and generate actionable business insights through statistical analysis and data visualization.**

---

# 📑 Table of Contents

- Project Overview
- Business Objective
- Dataset Information
- Project Workflow
- Technologies Used
- Python Libraries
- Data Preprocessing
- Exploratory Data Analysis
- Visualizations
- Key Findings
- Business Recommendations
- Project Structure
- Learning Outcomes
- Future Improvements
- Author

---

# 📌 Project Overview

The **Retail Liquor Sales Analysis** project focuses on performing a comprehensive **Exploratory Data Analysis (EDA)** on the Iowa Retail Liquor Sales dataset. The project follows a structured analytical workflow beginning with data cleaning and preprocessing, followed by descriptive statistics, exploratory analysis, correlation analysis, and interactive visualizations.

The objective is to transform raw transactional data into meaningful business insights that help understand customer purchasing behavior, product performance, regional sales trends, vendor contributions, and seasonal demand patterns.

---

# 🎯 Business Objective

The primary objectives of this project are:

| Objective | Description |
|------------|-------------|
| Data Cleaning | Handle missing values, duplicates, incorrect data types, and prepare the dataset for analysis. |
| Data Exploration | Understand the characteristics of numerical and categorical variables. |
| Sales Analysis | Identify sales trends across products, vendors, cities, and time. |
| Product Analysis | Determine the highest-performing liquor categories and products. |
| Vendor Analysis | Evaluate vendor contribution to overall sales revenue. |
| Geographical Analysis | Compare sales performance across different cities. |
| Trend Analysis | Identify monthly sales patterns and seasonal behavior. |
| Correlation Analysis | Measure relationships among sales-related numerical variables. |
| Business Insights | Generate meaningful recommendations based on analytical findings. |

---

# 📂 Dataset Information

| Attribute | Details |
|-----------|---------|
| Dataset | Iowa Retail Liquor Sales |
| Domain | Retail Analytics |
| File Format | CSV |
| Records | Retail liquor sales transactions |
| Analysis Tool | Python |
| Development Environment | Jupyter Notebook |

### Sample Features

- Invoice ID
- Order Date
- Store Name
- Store City
- Category Name
- Vendor Name
- Bottle Volume
- Pack Size
- Sales Bottles
- Sales Liters
- Sales Gallons
- Sales Dollars

---

# 🔄 Project Workflow

```
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Data Exploration
        │
        ▼
Statistical Analysis
        │
        ▼
EDA
        │
        ▼
GroupBy & Pivot Tables
        │
        ▼
Correlation Analysis
        │
        ▼
Data Visualization
        │
        ▼
Business Insights
        │
        ▼
Conclusion & Recommendations
```

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Jupyter Notebook | Development Environment |
| Pandas | Data Manipulation & Analysis |
| NumPy | Numerical Computation |
| Matplotlib | Static Data Visualization |
| Seaborn | Statistical Visualization |
| Plotly Express | Interactive Visualization |

---

# 📚 Python Libraries

| Library | Purpose |
|----------|---------|
| pandas | Loading, cleaning, filtering, grouping, aggregation |
| numpy | Mathematical operations and numerical calculations |
| matplotlib.pyplot | Static charts and figures |
| seaborn | Statistical plots and distribution analysis |
| plotly.express | Interactive bar charts, scatter plots, and heatmaps |

---

# 🧹 Data Preprocessing

The dataset was prepared before analysis using several preprocessing techniques.

| Task | Description |
|------|-------------|
| Missing Value Analysis | Identified missing values across all columns. |
| Missing Value Treatment | Appropriate methods applied to handle incomplete records. |
| Duplicate Check | Verified duplicate transactions. |
| Data Type Conversion | Converted date columns to datetime format. |
| Feature Engineering | Created Month and Year features for trend analysis. |
| Negative Value Validation | Checked for returns and adjustment transactions. |
| Outlier Detection | Examined extreme sales values using statistical methods. |
| Data Validation | Verified dataset consistency after preprocessing. |

---

# 🔍 Exploratory Data Analysis

The project includes three levels of exploratory analysis.

| Analysis | Description |
|----------|-------------|
| Univariate Analysis | Examined the distribution of individual variables. |
| Bivariate Analysis | Studied relationships between two variables. |
| Multivariate Analysis | Explored interactions among multiple variables simultaneously. |

### Statistical Analysis

- Descriptive Statistics
- Frequency Distribution
- GroupBy Analysis
- Pivot Table Analysis
- Correlation Analysis

---

# 📊 Visualizations

The following visualizations were developed during the project.

| Visualization | Library | Purpose |
|--------------|---------|---------|
| Histogram | Seaborn | Distribution analysis |
| Box Plot | Seaborn | Outlier detection |
| Bar Chart | Seaborn / Plotly | Category comparison |
| Line Chart | Matplotlib | Monthly sales trends |
| Scatter Plot | Plotly | Relationship analysis |
| Pie Chart | Matplotlib | Sales contribution analysis |
| Correlation Heatmap | Plotly | Correlation analysis |
| Subplots | Matplotlib | Comparative analysis |

---

# 📈 Key Findings

| Area | Insight |
|------|---------|
| Sales Distribution | Sales values are positively skewed with a small number of high-value transactions. |
| Product Categories | A limited number of liquor categories generate a significant portion of total revenue. |
| Vendor Performance | A few vendors contribute substantially to total sales. |
| City Performance | Sales are concentrated in major cities with higher transaction volumes. |
| Correlation | Sales Bottles, Sales Liters, Sales Gallons, and Sales Dollars exhibit strong positive relationships. |
| Seasonality | Monthly sales fluctuate, indicating seasonal purchasing behavior. |
| Outliers | High-value transactions were identified and retained because they represent genuine business activity. |

---

# 💡 Business Recommendations

| Recommendation | Reason |
|---------------|--------|
| Focus inventory on high-performing categories | Increase revenue potential. |
| Strengthen partnerships with top vendors | Improve product availability and sales. |
| Analyze low-performing cities | Identify opportunities for market expansion. |
| Monitor seasonal demand | Improve inventory planning and forecasting. |
| Continue tracking sales trends | Support strategic business decisions. |

---

# 📁 Project Structure

```
Retail-Liquor-Sales-EDA
│
├── data
│   ├── iowa_liquor_sales_target.csv
│   └── iowa_liquor_sales_cleaned.csv
│
├── notebook
│   └── Retail_Liquor_Sales_EDA.ipynb
│
├── images
│   ├── histogram.png
│   ├── boxplot.png
│   ├── bar_chart.png
│   ├── line_chart.png
│   ├── scatter_plot.png
│   ├── pie_chart.png
│   └── heatmap.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 🎓 Learning Outcomes

This project strengthened practical skills in:

| Skill | Description |
|-------|-------------|
| Data Cleaning | Preparing raw data for analysis |
| Exploratory Data Analysis | Identifying trends and patterns |
| Statistical Analysis | Summarizing and interpreting data |
| Data Visualization | Communicating insights effectively |
| Business Analytics | Converting analytical findings into recommendations |
| Python Programming | Using industry-standard data analysis libraries |

---

# 🚀 Future Improvements

- Develop an interactive dashboard using Power BI or Tableau.
- Build predictive models to forecast future liquor sales.
- Perform customer segmentation and market basket analysis.
- Analyze pricing strategies and product profitability.
- Automate the data processing workflow for recurring analysis.

---

# 👤 Author

| Information | Details |
|------------|---------|
| Name | **James Sebastian** |
| Project | **Retail Liquor Sales Analysis – Iowa (US)** |
| Skills | Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly |
| LinkedIn | https://linkedin.com/in/james-sebastian12 |

---

## ⭐ If you found this project useful, consider giving the repository a star!
