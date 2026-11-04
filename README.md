# Customer Behaviour Analysis

**An End-to-End Data Analytics Project Using Python, PostgreSQL & Power BI**

## 1. Project Overview

This project focuses on analyzing retail customer shopping behaviour to identify purchasing patterns, understand customer preferences and generate actionable business insights.

Using a dataset containing **3,900 customer records and 18 features**, the project explores customer demographics, purchasing habits, product categories, discount usage, subscription preferences and shipping choices.

The project follows an end-to-end analytics workflow involving Python-based data preparation, SQL-based business analysis and interactive Power BI visualization.

## 2. Business Problem Statement

A retail company wants to better understand its customers' shopping behaviour to improve sales, customer satisfaction and long-term loyalty.

The company aims to identify patterns across customer demographics, product categories, discounts, reviews, seasons and purchasing preferences.

**Central Business Question:**

How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?

## 3. Key Business Questions

The analysis focuses on answering the following questions:

1. What is the revenue contribution of male and female customers?
2. Which customers use discounts but still spend above the average purchase amount?
3. Which products have the highest average review ratings?
4. How do average purchase amounts differ between Standard and Express shipping?
5. Do subscribed customers spend more than non-subscribers?
6. Which products have the highest percentage of discounted purchases?
7. How can customers be segmented based on previous purchasing frequency?
8. What are the most purchased products within each category?
9. Are repeat buyers more likely to subscribe?
10. Which age groups contribute the most revenue?

## 4. Project Objectives

- Prepare and clean raw customer shopping data.
- Perform exploratory data analysis using Python.
- Analyze customer purchasing behaviour using PostgreSQL.
- Identify patterns across demographics, products and purchasing preferences.
- Develop an interactive Power BI dashboard.
- Translate analytical findings into actionable business recommendations.

## 5. Tools & Technologies

| Technology | Application |
|---|---|
| Python | Data preparation and analysis |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Exploratory data visualization |
| PostgreSQL | Database management |
| SQL | Business analysis |
| Power BI | Interactive dashboard development |
| Jupyter Notebook | Analysis environment |

## 6. Project Workflow

### Phase 1: Data Preparation & Cleaning

**Tool: Python**

- Loaded and inspected the raw dataset.
- Identified missing values and duplicate records.
- Handled missing review ratings using category-level median imputation.
- Renamed columns for consistency.
- Created age groups.
- Transformed purchase frequency into a numerical representation.
- Removed redundant columns.
- Prepared the cleaned dataset for database analysis.

### Phase 2: SQL Analysis

**Tool: PostgreSQL**

Performed business-oriented analysis using SQL queries.

Key analytical areas:

- Gender-wise revenue comparison.
- Discount usage and purchase amounts.
- Product ratings and popularity.
- Shipping type and average purchase amount.
- Subscription status and customer spending.
- Product-level discount rates.
- Customer purchasing-frequency segmentation.
- Top products within each category.
- Subscription patterns among repeat buyers.
- Revenue contribution across age groups.

SQL concepts used:

- Aggregate functions
- GROUP BY and ORDER BY
- Subqueries
- CASE statements
- Common Table Expressions (CTEs)
- Window functions
- Conditional aggregation

### Phase 3: Data Visualization

**Tool: Power BI**

Developed an interactive dashboard to explore customer shopping behaviour and communicate key metrics.

Dashboard components include:

- Customer-related KPIs.
- Average purchase amount.
- Average review rating.
- Subscription distribution.
- Category-wise purchasing analysis.
- Customer demographic comparisons.
- Interactive filters and slicers.

Phase 4: Business Insights & Recommendations

The analytical findings will be used to answer the central business question.

This phase focuses on:

Identifying important customer segments.

Understanding purchasing and discount patterns.

Evaluating subscription-related spending.

Identifying popular products and categories.

Recommending data-driven marketing and customer engagement strategies.

## 7. Key Findings & Business Recommendations

The SQL analysis revealed several patterns in customer purchasing behaviour, product preferences, discount usage and subscription activity.

**### Key Findings

**1. Gender-wise Revenue Contribution**
- Male customers generated $157,890 in revenue.
- Female customers generated $75,191 in revenue.
- Male customers accounted for the larger share of recorded purchase revenue.

**2. Discount Usage and Spending**
- Identified 839 customers who used discounts while spending above the average purchase amount.
- This indicates that discount usage is not necessarily limited to lower-value purchases.

**3. Highest-Rated Products**

The top five products by average review rating were:
- Gloves: 3.86
- Sandals: 3.84
- Boots: 3.82
- Hat: 3.80
- Skirt: 3.78

**4. Shipping Type Comparison**
- Express shipping customers had an average purchase amount of $60.48.
- Standard shipping customers had an average purchase amount of $58.46.

**5. Subscription Analysis**
- Subscribers: 1,053 customers, with an average purchase amount of $59.49.
- Non-subscribers: 2,847 customers, with an average purchase amount of $59.87.
- Non-subscribers generated higher total revenue due to their larger customer count.

**6. Products with the Highest Discount Rates**

The products with the highest proportions of discounted purchases were:
- Hat: 50.00%
- Sneakers: 49.66%
- Coat: 49.07%
- Sweater: 48.17%
- Pants: 47.37%

**7. Customer Segmentation**

Based on the existing purchase-history segmentation logic:
- Loyal: 3,116 customers.
- Returning: 701 customers.
- New: 83 customers.

**8. Top Products by Category**

The highest-purchased products identified in each category included:
- Accessories: Jewelry (171 purchases).
- Clothing: Blouse (171 purchases).
- Footwear: Sandals (160 purchases).
- Outerwear: Jacket (163 purchases).

**9. Repeat Buyers and Subscription Behaviour**
- Among customers with more than five previous purchases, 958 were subscribers and 2,518 were non-subscribers.
- Approximately 91.0% of subscribers and 88.4% of non-subscribers had more than five previous purchases.

**10. Revenue Contribution by Age Group**
- Young Adult: $62,143.
- Middle-aged: $59,197.
- Adult: $55,978.
- Senior: $55,763.

Young Adults contributed the highest recorded purchase revenue among the four age groups.

### Business Recommendations

Based on the observed patterns, the following business strategies are recommended:

- **Boost Subscriptions:** Promote exclusive benefits and evaluate subscription offerings to encourage membership adoption.
- **Customer Loyalty Programs:** Introduce rewards and engagement initiatives to encourage repeat purchasing.
- **Review Discount Policies:** Evaluate discount effectiveness and balance promotional activity with profit margin considerations.
- **Product Positioning:** Highlight highly rated and popular products in marketing campaigns.
- **Targeted Marketing:** Develop age-group-specific campaigns based on observed revenue contribution.
- **Shipping Strategy:** Evaluate express shipping options as a potential way to improve the purchasing experience and support higher-value orders.

*Note: These findings describe patterns observed in the available dataset. They represent associations and descriptive results, not proof of causation.***


8. Dashboard Preview

Dashboard screenshots will be added here.

9. Dataset Information

Total records: 3,900

Total features: 18

Data format: CSV

Domain: Retail Customer Shopping Behaviour

The dataset includes information relating to customer demographics, purchase amounts, product categories, discount information, subscription status, shipping preferences and previous purchasing behaviour.

10. How to Run the Project

Prerequisites

Python 3.x

Jupyter Notebook

PostgreSQL

Power BI Desktop

Step 1: Clone the Repository

git clone YOUR_REPOSITORY_URL
cd Customer-Behaviour-Analysis

Step 2: Install Dependencies

pip install -r requirements.txt

Step 3: Run the Python Notebook

jupyter notebook

Open the notebook and execute the analysis cells.

Step 4: Configure PostgreSQL

Create a PostgreSQL database.

Configure database credentials using environment variables.

Refer to .env.example for the required configuration.

Execute the SQL queries provided in the project.

Step 5: Explore the Power BI Dashboard

Open the .pbix file using Power BI Desktop to explore the interactive dashboard.

11. Future Improvements

Develop advanced customer segmentation techniques.

Introduce customer churn and retention prediction.

Explore machine learning models for customer behaviour analysis.

Enhance dashboard interactivity and data storytelling.

Develop more advanced customer analytics.
