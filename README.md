# 📊 Datheon — SuperStore Sales Analytics

> **An end-to-end retail sales analytics project using Python and Power BI to transform raw SuperStore data into meaningful business insights.**

---

## 📌 Project Overview

**Datheon** is a retail sales analytics project focused on exploring, cleaning, analyzing, and visualizing SuperStore sales data.

The project combines **Python-based data analysis** with an interactive **Power BI dashboard** to understand sales performance across different years, regions, categories, sub-categories, customers, and profitability metrics.

The main objective is to transform raw sales data into **clear, actionable business insights** that can support better decision-making.

---

## 🎯 Objectives

The key objectives of this project are:

- Clean and prepare raw SuperStore sales data.
- Perform exploratory data analysis using Python.
- Analyze sales and profit performance.
- Understand regional performance.
- Identify high-performing products and sub-categories.
- Analyze customer-level sales and profitability.
- Study yearly and monthly sales trends.
- Understand the impact of discounts on profitability.
- Build an interactive Power BI dashboard.
- Convert analytical findings into meaningful business recommendations.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| 🐍 **Python** | Data cleaning and exploratory data analysis |
| 🐼 **Pandas** | Data manipulation and analysis |
| 📊 **Matplotlib** | Data visualization |
| 📈 **Power BI** | Interactive dashboard and business intelligence |
| 📓 **Jupyter Notebook** | Python-based analysis |
| 📄 **CSV** | Dataset storage and processed data |
| 📝 **Markdown** | Documentation and business observations |

---

## 📂 Project Structure

```text
Datheon/
│
├── 📄 superstore_sales.csv
│   └── Original SuperStore sales dataset
│
├── 📄 cleaned_superstore_sales.csv
│   └── Cleaned and processed dataset
│
├── 📓 task1.ipynb
│   └── Python data cleaning and exploratory analysis
│
├── 📊 task2.pbix
│   └── Interactive Power BI dashboard
│
├── 📄 Business_Observations.md
│   └── Business insights and recommendations
│
├── 📄 SuperStore_Sales_Dashboard_Report.pdf
│   └── Dashboard report
│
└── 📄 README.md
    └── Project documentation
```

---

# 🔄 Project Workflow

```text
Raw SuperStore Dataset
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Business Insights
        ↓
Cleaned Dataset
        ↓
Power BI Dashboard
        ↓
Business Recommendations
```

---

# 🧹 Data Cleaning & Preparation

The raw dataset was first examined and prepared for analysis.

The cleaning process included:

- Removing duplicate records.
- Handling missing values.
- Filling missing categorical values with `"Unknown"`.
- Handling missing numerical values using appropriate statistical values.
- Converting date columns into proper datetime format.
- Creating additional time-based fields such as:
  - Year
  - Year-Month
- Checking the dataset for remaining null values.
- Preparing the cleaned dataset for visualization and further analysis.

---

# 📊 Exploratory Data Analysis

Python was used to explore different aspects of the SuperStore dataset.

### Key Areas Analyzed

- Regional performance
- Product and sub-category performance
- Customer performance
- Sales trends
- Profitability
- Discount impact
- Year-wise performance

---

# 💡 Key Business Insights

### 🌎 Regional Performance

The **West region** was the strongest contributor, generating approximately:

- **$725K Sales**
- **$108K Profit**

The **East region** was another strong-performing region with approximately:

- **$679K Sales**
- **$92K Profit**

This indicates that West and East are important contributors to overall business performance.

---

### 🛍️ Product & Sub-Category Performance

Different sub-categories showed different sales and profitability patterns.

- **Chairs** generated approximately **$328K in sales**.
- **Copiers** generated the highest profit among the analyzed sub-categories at approximately **$55.6K**.
- **Accessories** generated approximately **$167K sales** and **$41.9K profit**.
- **Bookcases** generated approximately **$115K sales but resulted in a loss of about $3.5K**.

This demonstrates that **high sales do not necessarily mean high profitability**.

---

### 👥 Customer Performance

Customer-level analysis showed that sales and profitability can vary significantly.

For example:

**Sean Miller**

- Sales: approximately **$25K**
- Profit: approximately **-$2K**

This highlights the importance of analyzing **customer profitability rather than focusing only on sales revenue**.

---

### 📈 Sales Trends

Year and month-based analysis was performed to understand changes in sales over time.

The Power BI dashboard also provides a yearly sales view showing approximately:

| Year | Sales Contribution |
|------|-------------------:|
| 2015 | 0.5M |
| 2016 | 0.5M |
| 2017 | 0.6M |
| 2018 | 0.7M |
| **Total** | **2.3M** |

The overall trend indicates increasing sales contribution across the displayed years.

---

### 💰 Discount & Profitability

Discount levels ranged from **0% to 80%**.

The analysis showed that higher discounts can negatively affect profitability.

For example, a transaction with approximately:

- **$957.58 Sales**
- **45% Discount**
- **-$383.03 Profit**

resulted in a significant loss.

Therefore, discount strategies should be carefully monitored.

---

# 📊 Power BI Dashboard

The Power BI dashboard provides an interactive overview of SuperStore performance.

### Dashboard KPIs

- 💰 **Total Sales:** 2.3M
- 📈 **Total Profit:** 286.4K
- 🛒 **Total Orders:** 5.0K

### Dashboard Features

The dashboard includes:

- Date range filtering
- Regional filtering
- Total Sales KPI
- Total Profit KPI
- Total Orders KPI
- Sales by Year
- Category analysis
- Sub-category analysis
- Interactive visual exploration

---

# 📸 Dashboard Preview

The dashboard provides a visual summary of sales performance across years, regions, categories, and sub-categories.

> Add your dashboard screenshot here if you want the README to display the preview.

```markdown
![SuperStore Sales Dashboard](dashboard.png)
```

---

# 📄 Business Report

A separate business report has been created to document the major observations and recommendations from the analysis.

The report covers:

- Regional performance
- Product performance
- Customer performance
- Sales trends
- Discount and profitability
- Data quality
- Business insights
- Recommendations

---

# 🎯 Business Recommendations

Based on the analysis, the following recommendations can be considered:

### 1. Focus on Strong Regions

Continue analyzing and strengthening sales strategies in the **West and East regions**, which are major contributors to sales and profit.

### 2. Review Loss-Making Products

Investigate products such as **Bookcases** that generate substantial sales but negative profit.

### 3. Focus on Customer Profitability

Identify customers who generate high revenue but low or negative profit and evaluate their discounts, product mix, and order patterns.

### 4. Optimize Discount Strategies

Avoid excessive discounting when it significantly reduces profitability.

### 5. Use Sales Trends for Planning

Historical sales trends can support:

- Inventory planning
- Promotional planning
- Sales forecasting
- Resource allocation

---

# 📚 Key Learning Outcomes

Through this project, I strengthened my practical understanding of:

- Data Cleaning
- Exploratory Data Analysis
- Python for Data Analytics
- Pandas
- Data Visualization
- Business Intelligence
- Power BI Dashboard Development
- Business Insight Generation
- Data-driven Decision Making

Most importantly, this project helped me understand how to move from:

> **Raw Data → Clean Data → Analysis → Visualization → Business Insights**

---

# 🚀 Future Enhancements

Possible future improvements include:

- Adding advanced sales forecasting.
- Creating customer segmentation.
- Adding profitability analysis by discount range.
- Developing more detailed regional dashboards.
- Adding automated data refresh.
- Implementing advanced Power BI DAX measures.
- Adding predictive analytics.

---

# 👩‍💻 About the Project

This project is part of my **Data Analytics portfolio**, demonstrating practical experience in combining **Python, data analysis, visualization, and Power BI** to solve business-oriented problems.

I focused not only on creating visualizations but also on understanding **what the data means from a business perspective**.

---

## ⭐ If You Find This Project Useful

Feel free to explore the project, share your feedback, or connect with me to discuss **Data Analytics, Python, Power BI, and Business Intelligence**.

---

### 🔗 Project Repository

**GitHub:**  
`https://github.com/Sakshi-Singh-17/Datheon`

---

## 🏷️ Tags

`#DataAnalytics` `#Python` `#Pandas` `#PowerBI` `#DataVisualization` `#BusinessIntelligence` `#EDA` `#DataScience` `#RetailAnalytics` `#DataAnalysis`
