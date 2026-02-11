# Customer shipping behaviour - Project Overview 

This project analyzes customer purchase behavior using transactional data sourced from Excel and modeled for analysis using SQL and DAX.
The dataset contains 3,900 records, capturing customer demographics, purchasing patterns, product attributes, payment behavior, and engagement indicators such as subscription status and purchase frequency.
The goal of this analysis is not only to demonstrate technical competency in data modeling, SQL querying, and DAX measure creation, but also to present business-driven insights that would be valuable to management, operations teams, and hiring decision-makers.
Rather than creating disconnected visuals, the analysis is structured around business questions, ensuring every visual contributes to a coherent narrative and supports data-driven decision-making.

# Data Description
- The dataset includes the following key dimensions:
- Customer Information: Age, Gender, Location
- Product Details: Item Purchased, Category, Size, Color, Season
- Financial Metrics: Purchase Amount (USD), Discounts, Promo Code Usage
- Behavioral Indicators: Subscription Status, Previous Purchases, Frequency of Purchases
- Operational Factors: Shipping Type, Payment Method
- Customer Feedback: Review Rating
All data was imported from Excel, cleaned, and prepared for analysis before being modeled for reporting.

# Analytical Scopes
The analysis is organized into three core scopes to reflect how organizations typically evaluate performance:
1. Revenue & Strategy
2. Operational Performance
3. People & Customer Analytics
Each scope addresses a specific set of business questions and is supported by targeted visuals and measures.

# Scope 1: Revenue & Strategy

The Revenue & Strategy scope focuses on understanding what drives revenue, where value is being generated, and which strategic levers management can optimize to improve financial performance.
The visuals in this section are designed to support:
1.Strategic planning
2.Pricing and promotion decisions
3.Customer segmentation and retention strategies
All insights presented here are derived using a combination of SQL for data exploration and DAX measures for dynamic calculations, ensuring accuracy, scalability, and analytical depth.

# Revenue & Strategy Analysis ![revenue & Strategy dasboard](images/revenue%20%26%20startegy%201.1.png)
This section evaluates revenue performance drivers and strategic levers that influence financial outcomes. Each visual is aligned to a specific business question and supports data-driven decision-making.

1. Total Revenue Overview ![revenue & Strategy dasboard](images/revenue%20and%20discount%201.2.png)

Business Question:
What is the overall revenue performance of the business?

Visual Purpose:
Provides a high-level summary of total revenue generated within the dataset period.

Why It Matters:
This acts as the financial baseline. All strategic discussions—growth, segmentation, discount impact—are anchored to total revenue.

Strategic Value:

 1. Establishes revenue scale
 2. Supports performance benchmarking
 3. Serves as a KPI reference point for executive review

2.Revenue by Product Category ![revenue & Strategy dasboard](images/Total%20revenue%20by%20category%201.4.png)

Business Question:
Which product categories contribute the most to revenue?

Visual Purpose:
Breaks down revenue across product categories to identify top-performing segments.

Why It Matters:
Category-level revenue helps management prioritize inventory investment, marketing focus, and expansion strategies.

Strategic Value:
1. Identifies revenue concentration risk
2. Highlights growth opportunities
3. Supports category-level promotional planning



3. Customer Subscription Status by count![revenue & Strategy dasboard](images/subscription%20count%201.3.png)

Business Question:
Do subscribed customers generate more revenue than non-subscribed customers?

Visual Purpose:
Compares the numbers of subscribers versus non-subscribers.

Why It Matters:
Determines whether subscription programs are financially impactful.

Strategic Value:
1. Evaluates ROI of loyalty/subscription programs
2. Supports retention strategy
3. Informs customer engagement investments


Scope 2: ⚙️ Operational Performance Analysis ![revenue & Strategy dasboard](images/operational%20performance%201.1.png)

  Scope Objective
This section evaluates operational efficiency and execution performance across logistics, geography, seasonality, and payment processing.
The focus is to answer:
1. Where are our customers concentrated geographically?

2. How does shipping method affect revenue?

3. Are there seasonal operational revenue patterns?

4. Which payment methods drive higher transaction value?

5. How does logistics configuration influence average revenue?






