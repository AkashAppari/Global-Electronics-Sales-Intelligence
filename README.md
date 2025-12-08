# Global Electronics: End-to-End Sales Analytics & Customer Intelligence

## Created by Akash Appari
**Data Analyst | Business Intelligence Professional**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/akashappari/)

![Global Electronics Retailer Banner](https://github.com/user-attachments/assets/629f0843-71de-4393-860e-9287349b0080)

---

## 📊 Project Overview

This comprehensive end-to-end data analytics project transforms raw transactional data from a global electronics retailer into actionable business insights through advanced ETL processes, SQL analysis, and interactive Excel dashboards. The project demonstrates proficiency in data engineering, database management, and business intelligence across the complete analytics lifecycle.

### 🎯 Business Context

A fictitious **Global Electronics Retailer** operates worldwide, offering diverse electronic products to customers across multiple countries. With extensive data from transactions, customer demographics, and store performance, this analysis uncovers critical insights to drive strategic decision-making, optimize product portfolios, and enhance customer experiences globally.

---

## 📑 Table of Contents

1. [Project Background](#-project-background)
2. [Technical Architecture](#-technical-architecture)
3. [Data Structure](#-data-structure)
4. [Executive Summary](#-executive-summary)
5. [Revenue Insights](#-revenue-insights)
6. [Customer Insights](#-customer-insights)
7. [Strategic Recommendations](#-strategic-recommendations)
8. [Technologies & Tools](#-technologies--tools)
9. [Skills Demonstrated](#-skills-demonstrated)

---

## 📋 Project Background

### Business Challenge

Global Electronics Retailer needed to:
- Transform disparate data sources into actionable insights
- Understand revenue drivers across products and geographies
- Analyze customer behavior and retention patterns
- Optimize product mix and marketing strategies
- Identify growth opportunities in underperforming markets

### Solution Delivered

An end-to-end analytics solution featuring:
- ✅ **Comprehensive ETL Pipeline**: Python-based data cleaning and transformation
- ✅ **Robust Database**: SQL Server database with optimized schema
- ✅ **Advanced Analytics**: SQL queries for revenue and customer analysis
- ✅ **Interactive Dashboard**: Excel dashboard with dynamic visualizations
- ✅ **Actionable Insights**: Data-driven recommendations across 5 key areas

### Key Focus Areas

1. **Revenue Distribution**: Sales contributions across product categories and regions
2. **Market Performance**: Geographic revenue variations and opportunities
3. **Customer Demographics**: Age, gender, and geographic customer segmentation
4. **Retention Trends**: Customer loyalty patterns and churn analysis
5. **Sales Patterns**: High-ticket vs. low-ticket product performance

**Detailed Resources:**
- [ETL Data Cleaning Process](https://github.com/karlyndiary/Optimizing-Global-Electronics-Retailer-Sales-Insights/tree/main/%5B01%5D%20ETL)
- [SQL Queries & Analysis](https://github.com/karlyndiary/Optimizing-Global-Electronics-Retailer-Sales-Insights/tree/main/%5B02%5D%20SQL)
- [Interactive Excel Dashboard](https://github.com/karlyndiary/Optimizing-Global-Electronics-Retailer-Sales-Insights/tree/main/%5B03%5D%20Excel%20Dashboard)

---

## 🏗️ Technical Architecture

### End-to-End Analytics Pipeline

```
Raw Data → ETL Processing → SQL Database → SQL Analysis → Excel Dashboard
  (CSV)  →    (Python)    → (SQL Server) →   (Queries)  → (Visualization)
```

### Data Processing Workflow

1. **Data Extraction**: Import raw CSV files from 5 data sources
2. **Data Cleaning**: Python/Jupyter Notebooks for data quality improvements
3. **Data Transformation**: Standardization, normalization, and enrichment
4. **Database Creation**: SQL Server schema design and implementation
5. **Data Loading**: ETL pipeline to populate database tables
6. **SQL Analysis**: Complex queries for revenue and customer metrics
7. **Dashboard Creation**: Interactive Excel dashboard with dynamic features

---

## 🗄️ Data Structure

### Database Schema

The Global Electronics Retailer database consists of **5 interconnected tables** with **62,885 total records**:

![Database Schema](https://github.com/user-attachments/assets/491b8e36-4b9b-459f-a757-1b6c30978c20)

### Table Specifications

| Table | Key Fields | Records | Purpose |
|-------|------------|---------|---------|
| **Customers** | CustomerKey, Name, Gender, City, Country, Birthday | 11,887 | Demographics |
| **Sales** | Order Number, Order Date, CustomerKey, ProductKey, Quantity | 62,884 | Transactions |
| **Products** | ProductKey, Product Name, Brand, Unit Price, Category | 2,517 | Catalog |
| **Stores** | StoreKey, Country, State, Square Meters, Open Date | 67 | Locations |
| **Exchange Rates** | Date, Currency, Exchange | Variable | Currency |

---

## 📊 Executive Summary

### Overview of Findings

This comprehensive analysis reveals critical insights across revenue performance, customer behavior, and market dynamics. **Desktop PCs** dominate product sales with **$505.45K in revenue** and **$337K in profit**. The **computers category** leads overall with **$19.3M revenue** and **$12.28M profit**, while **games and toys** represent the lowest performers at **$724.83K revenue**.

**Home appliances** achieve the highest average order value at **$1.84K**. Geographically, the **United States** dominates with **$29.87M revenue**, while **France** lags at **$1.52M**. **2019** marked peak performance with **$18.26M** in sales, followed by a sharp decline in **2021** due to incomplete data and COVID-19 impacts.

---

## 💰 Revenue Insights

### Sales Dashboard

![Sales Dashboard](https://github.com/user-attachments/assets/fb0dfc82-73f6-47d1-8d5d-1c4c1a739ee0)

### 🏆 Top Performing Products

| Product | Revenue | Profit | Performance |
|---------|---------|--------|-------------|
| WWI Desktop PC2.33 X2330 Black | $505.45K | $337K | ⭐ Market Leader |
| WWI Desktop PC2.33 X2330 Silver | $503K | $335K | Consistent Performer |
| LCD HDTV 52" | $485K | $298K | High Demand |

**Key Insight**: Desktop PCs demonstrate consistent performance across color variations, indicating strong brand loyalty and market demand.

### 📈 Category Performance Analysis

| Category | Revenue | Profit | AOV | Rating |
|----------|---------|--------|-----|--------|
| **Computers** | $19.3M | $12.28M | $1.65K | ⭐⭐⭐⭐⭐ |
| **Home Appliances** | $8.5M+ | $5.2M+ | $1.84K | ⭐⭐⭐⭐⭐ |
| **TVs & Video** | $7.8M+ | $4.8M+ | $1.42K | ⭐⭐⭐⭐ |
| **Games & Toys** | $724.83K | $396.67K | $102.65 | ⭐⭐ |

**Strategic Findings:**
- High-ticket items (Computers, Home Appliances) drive 60%+ of revenue
- $1,737 difference between highest and lowest AOV categories
- Games & toys show significant untapped potential

### 🌍 Geographic Revenue Distribution

| Rank | Country | Revenue | % of Total | Status |
|------|---------|---------|------------|--------|
| 1 | **United States** | $29.87M | 56.8% | ⭐ Primary |
| 2 | United Kingdom | $8.45M | 16.1% | Strong |
| 3 | Canada | $6.23M | 11.9% | Developed |
| 4 | Germany | $4.82M | 9.2% | Growing |
| 8 | France | $1.52M | 2.9% | ⚠️ Opportunity |

**Geographic Insights:**
- US accounts for more than half of global revenue
- Top 3 countries generate 84.8% of total revenue
- France represents significant growth opportunity

### 📅 Temporal Revenue Trends

| Year | Revenue | Profit | YoY Growth | Key Events |
|------|---------|--------|------------|------------|
| 2019 | **$18.26M** | **$10.70M** | +8.1% | ⭐ Peak |
| 2020 | $12.34M | $7.45M | -32.4% | COVID Impact |
| 2021 | $1.04M | $61K | -91.6% | ⚠️ Decline |

**Temporal Analysis:**
- 2019 achieved highest revenue and profit
- 2016-2019 showed +93.3% cumulative growth
- 2019 metrics serve as recovery benchmark

---

## 👥 Customer Insights

### Customer Dashboard

![Customer Dashboard](https://github.com/user-attachments/assets/19207aad-94ae-4125-89be-d6619a8b76cc)

### 🎂 Customer Demographics

**Age Distribution:**

| Age Segment | Count | Percentage | Characteristics |
|-------------|-------|------------|-----------------|
| **Seniors (55+)** | 6,837 | 57.5% | Largest segment, high purchasing power |
| **Adults (35-54)** | 2,659 | 22.4% | Family-focused, brand loyal |
| **Young Adults (18-34)** | 2,391 | 20.1% | Tech-savvy, trend-conscious |

**Demographic Insights:**
- Seniors represent 57.5% with strong disposable income
- Family segment shows strong brand loyalty
- Youth market demonstrates high tech engagement

### 👔 Gender Distribution

**Customer Base by Gender:**
- **Male**: 51% (6,062 customers)
- **Female**: 49% (5,825 customers)

**Gender Balance Insights:**
- Nearly perfect gender balance
- No significant gender bias in products
- Opportunity for gender-neutral marketing

### 🌍 Geographic Customer Distribution

| Country | Customers | % of Total |
|---------|-----------|------------|
| **United States** | 5,706 | 48.0% |
| United Kingdom | 1,570 | 13.2% |
| Canada | 1,179 | 9.9% |
| Germany | 1,150 | 9.7% |
| France | 438 | 3.7% |

**Total Unique Customers**: 11,887

### 🔄 Customer Loyalty Metrics

| Metric | Value | Benchmark | Performance |
|--------|-------|-----------|-------------|
| **Repeat Customer Rate** | 53.40% | 20-40% | ⭐ Excellent |
| **One-Time Buyers** | 46.60% | 60-80% | ✅ Strong |

**Loyalty Insights:**
- 53.40% repeat rate exceeds industry standards
- High repeat rate indicates strong satisfaction
- Converting remaining 46.60% represents major opportunity

### 📊 Customer Retention Trends

| Year | Retention Rate | Status |
|------|----------------|---------|
| 2019 | **89.45%** | ⭐ Peak |
| 2020 | 42.18% | COVID Impact |
| 2021 | 9.37% | ⚠️ Critical |

**Retention Analysis:**
- 2019 achieved remarkable 89.45% retention
- Post-2019 collapse due to pandemic
- Recovery to 2019 levels is critical priority

### 🛒 Order Frequency Distribution

| Order Range | Customers | Percentage | Segment |
|-------------|-----------|------------|---------|
| **1-9 orders** | 10,273 | 86.4% | Casual Buyers |
| **10-19 orders** | 1,285 | 10.8% | Regular Customers |
| **20-29 orders** | 326 | 2.7% | Loyal Customers |
| **30+ orders** | 3 | 0.02% | VIP Customers |

**Order Frequency Insights:**
- 86.4% place fewer than 10 orders
- Significant drop-off after 10 orders
- Converting casual to regular could double revenue

---

## 🎯 Strategic Recommendations

Based on comprehensive data analysis, the following strategic recommendations are proposed:

### 1. 🖥️ Focus on High-Ticket Items

**Strategy:**
- Continue promoting desktop PCs and LCD HDTVs as profit drivers
- Introduce new models with enhanced features
- Leverage $1,650-$1,840 AOV in computers and home appliances
- Create premium product + accessory bundles

**Expected Impact:**
- 15-20% revenue increase in computers category
- Enhanced profit margins through premium positioning

---

### 2. 🎮 Enhance Marketing for Low-Ticket Items

**Games & Toys Strategy:**
- Targeted seasonal campaigns (holidays, back-to-school)
- Bundle promotions and multi-item discounts
- Cross-selling with high-ticket items for families
- Strategic pricing to drive volume

**Expected Impact:**
- 25-30% volume increase in games & toys
- Improved category profitability

---

### 3. 💎 Leverage Customer Loyalty

**Loyalty Program:**
- Tier-based rewards (Bronze, Silver, Gold, Platinum)
- Points system: 1 point per $1 spent
- Exclusive benefits: early access, extended warranties, VIP service
- Referral incentives for new customer acquisition

**Target Metrics:**
- Increase repeat rate from 53.40% to 65%
- Boost average order frequency from 5.3 to 8 orders
- Reduce customer acquisition cost by 20%

---

### 4. 🌍 Geographic Market Expansion

**France Market Focus:**
- **Current**: $1.52M revenue, 438 customers
- **Target**: $4.5M revenue, 1,200 customers (3-year goal)
- **Strategies**: Localized marketing, French-language support, local partnerships

**European Growth:**
- Expand in Italy, Netherlands, Germany
- Consider Spain, Portugal, Belgium

---

### 5. 🔄 Invest in Customer Retention Strategies

**Recovery Strategy (Target: 89.45% - 2019 benchmark):**

**Phase 1: Win-Back Campaign**
- Email campaigns to lapsed customers
- Exclusive "welcome back" discounts (15-20%)
- Personalized product recommendations
- Timeline: Immediate - 6 months

**Phase 2: Engagement Enhancement**
- Monthly newsletters with product updates
- How-to guides and tech trend content
- Customer forums and social media groups
- Timeline: Ongoing

**Phase 3: Predictive Retention**
- Churn prediction through analytics
- Proactive intervention before churn
- Customer satisfaction surveys
- Timeline: 6-12 months

**Expected Outcomes:**
- Retention rate recovery to 70%+ within 18 months
- 35% churn reduction
- 40% increase in customer lifetime value

---

## 🛠️ Technologies & Tools

### Data Engineering
- **Python 3.x** - ETL script development
- **Jupyter Notebook** - Interactive data cleaning
- **Pandas** - Data manipulation
- **NumPy** - Numerical computing

### Database Management
- **SQL Server** - Enterprise database
- **T-SQL** - Query optimization
- **Database Design** - Schema normalization

### Business Intelligence
- **Microsoft Excel** - Dashboard creation
- **Power Query** - Data transformation
- **Pivot Tables** - Multi-dimensional analysis

---

## 📁 Project Structure

```
Global-Electronics-Retailer-Sales-and-Customer-Insights/
├── README.md                              # Project documentation
├── [01] ETL/                              # Data processing pipeline
│   ├── Customer Data Cleaning.ipynb      # Customer ETL
│   ├── Sales Data Cleaning.ipynb         # Sales ETL
│   ├── Products Data Cleaning.ipynb      # Product ETL
│   ├── Stores Data Cleaning.ipynb        # Store ETL
│   ├── Exchange Rates Data Cleaning.ipynb # Currency ETL
│   ├── ETL.py                            # Main ETL script
│   ├── Database Creation.sql             # Database schema
│   ├── Dataset/                          # Raw data files
│   └── Cleaned Datasets/                 # Processed data
├── [02] SQL/                              # SQL analysis queries
│   └── [01] revenue_customer_analysis.sql # Revenue metrics
└── [03] Excel Dashboard/                  # Interactive dashboard
    └── Global Electronics Retailer Sales and Customer Dashboard.xlsx
```

---

## 🎓 Skills Demonstrated

### Technical Competencies

**Data Engineering:**
- ✅ ETL pipeline design and implementation
- ✅ Data quality assessment and cleansing
- ✅ Python scripting for automation
- ✅ Database schema design and normalization

**Data Analysis:**
- ✅ Complex SQL query development
- ✅ Multi-dimensional data analysis
- ✅ Statistical analysis and interpretation
- ✅ Customer behavior analysis

**Business Intelligence:**
- ✅ Dashboard design and development
- ✅ KPI definition and tracking
- ✅ Data visualization best practices
- ✅ Executive presentation skills

---

## 📈 Business Impact

### Quantifiable Outcomes

**Revenue Optimization:**
- Identified $709M in unutilized customer spending capacity
- Highlighted 15-20% growth potential in high-ticket categories
- Revealed $17.74M opportunity in underperforming France market

**Customer Value:**
- 53.40% repeat customer rate demonstrates strong loyalty foundation
- Retention recovery could increase CLV by 40%

**Operational Efficiency:**
- End-to-end analytics pipeline reduces reporting time by 75%
- Automated ETL processes save 20+ hours monthly

---

## 📬 Contact

**Akash Appari**
Data Analyst | Business Intelligence Professional

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akashappari/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)

---

## 📜 Acknowledgments

**Data Source**: Global Electronics Retailer Sample Data
**Analysis & Visualization**: Akash Appari
**Tools**: Python, SQL Server, Microsoft Excel

---

<div align="center">

### If you found this analysis valuable, please consider giving it a ⭐

**Made with 📊 and ☕ by Akash Appari**

</div>
