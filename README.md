#  📊  OTT Churn Analysis & Customer Intelligence

An end-to-end data analytics project that examines customer churn in an OTT subscription business. The project combines customer, subscription, and support data to identify churn patterns, high-risk segments, revenue loss, and practical retention opportunities.

##  🎯  Business Problem

Customer churn directly affects subscription revenue and customer lifetime value. This project answers:

- Who is likely to churn?
- Which plans, contracts, locations, and customer groups have higher churn?
- What revenue and CLTV are at risk?
- What actions can help improve customer retention?

## ✨ Key Insights

- Overall churn rate: **28.6%**
- Retention rate: **71.4%**
- Monthly-contract churn: **55.6%**
- Annual-contract churn: **8.3%**
- The Basic plan contributed the largest share of churn.
- Karnataka and September 2024 were highlighted as major churn areas.
- Churn resulted in measurable revenue loss and CLTV erosion.

##  🛠️ Tech Stack

- **Python**
- **SQL / SQLite**
- **Jupyter Notebook**
- **Pandas** - data extraction, cleaning, transformation, and analysis
- **NumPy** - numerical calculations and feature engineering
- **Matplotlib** - charts and visual analysis
- **Seaborn** - statistical visualizations

## 🗂️ Data Sources

The analysis integrates three relational tables:

| Table | Purpose |
|---|---|
| `db_customer` | Customer demographics and location details |
| `db_subscription` | Subscription plan, contract, charges, CLTV, and churn data |
| `db_support` | Complaints, escalations, CSAT score, and customer feedback |

## 🔄 Project Workflow

```text
OTT Churn Analysis
│
├── 1. Connect Database
│   ├── Connect SQLite database with Python
│   └── Extract relational tables using SQL queries
│
├── 2. Import & Understand Data
│   ├── Load customer, subscription, and support datasets
│   ├── Inspect columns and data types
│   └── Perform initial quality checks
│
├── 3. Clean Data
│   ├── Handle missing values
│   ├── Rename and select relevant columns
│   ├── Correct data types
│   └── Remove or review invalid records
│
├── 4. Feature Engineering
│   ├── Calculate customer tenure
│   ├── Create churn and retention metrics
│   ├── Segment customers by churn risk
│   └── Calculate revenue and CLTV impact
│
├── 5. Exploratory Data Analysis
│   ├── Analyze churn by plan type
│   ├── Analyze churn by country and state
│   ├── Compare monthly and annual contracts
│   ├── Analyze support escalations and CSAT
│   └── Identify high-risk customer segments
│
├── 6. Visualize Findings
│   ├── Churn-rate charts
│   ├── Plan and contract comparisons
│   ├── Location-based churn analysis
│   └── Revenue-loss and customer-risk visuals
│
└── 7. Business Recommendations
    ├── Prioritize high- and medium-risk customers
    ├── Investigate churn in Karnataka and September 2024
    ├── Improve Basic-plan experience and pricing strategy
    ├── Review complaints and technical issues
    └── Encourage migration from monthly to annual contracts
```

## 📈 Key Metrics Calculated

- Churn Rate
- Retention Rate
- Average Revenue Per User (ARPU)
- Average Customer Tenure
- Customer Lifetime Value (CLTV)
- Revenue at Risk
- Escalation Rate
- Average Complaints per Customer
- Churn by Plan Type
- Churn by Contract Type
- Churn by State and Country

## 📊 Visualizations

The project includes visualizations to make churn patterns and customer-risk insights easier to understand.

| Visualization | Business Purpose |
|---|---|
| Monthly Churn Trend | Identifies periods with unusually high customer churn |
| Churn Rate by Plan Type | Compares churn across Basic, Standard, and Premium plans |
| Churn Rate by State | Highlights locations requiring further investigation |
| Contract Type Analysis | Compares monthly and annual subscriber retention |
| Correlation Heatmap | Examines relationships among churn score, escalations, and churn status |
| Customer Risk Segmentation | Groups customers into low-, medium-, and high-churn-risk segments |


## 🧠 Skills Demonstrated

Through this project, I demonstrated practical data analytics skills, including:

- Extracting and querying relational data with **SQL and SQLite**
- Connecting a SQL database to **Python**
- Cleaning, transforming, and validating data using **Pandas and NumPy**
- Handling missing values, duplicates, inconsistent labels, and date columns
- Creating business KPIs such as churn rate, retention rate, ARPU, tenure, revenue loss, and CLTV impact
- Performing exploratory data analysis using grouping, aggregation, and pivot tables
- Creating business-focused visualizations with **Matplotlib and Seaborn**
- Converting analytical findings into actionable customer-retention recommendations
- Documenting a complete end-to-end analytics project for GitHub

## 💡 Recommendations

- Focus retention campaigns on customers with high churn risk and high CLTV.
- Encourage monthly subscribers to move to annual contracts.
- Investigate pricing, service, complaints, and competitor activity affecting the Basic plan.
- Review the causes of higher churn in Karnataka and during September 2024.
- Use support escalations and CSAT scores as early warning signals for churn.




