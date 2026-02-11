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

  3.Customer Subscription Status by count![revenue & Strategy dasboard](images/subscription%20count%201.3.png)

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


# Scope 2: ⚙️ Operational Performance Analysis ![revenue & Strategy dasboard](images/operational%20performance%201.1.png)

 Scope Objective - This section evaluates operational efficiency and execution performance across logistics, geography, seasonality, and payment processing.
  
The focus is to answer:
1. Where are our customers concentrated geographically?

2. How does shipping method affect revenue?

3. Are there seasonal operational revenue patterns?

4. Which payment methods drive higher transaction value?

5. How does logistics configuration influence average revenue?

1.Customer Count by Location ![revenue & Strategy dasboard](images/customer%20count%20by%20location%201.5.png) ![revenue & Strategy dasboard](images/customer%20count%20by%20location%201.5%202.png)
 Business Question: Where are our customers concentrated geographically?

 What the Visual Shows: A distribution of total customers across different locations.

 Why It Matters

- Identifies high-density markets
- Helps prioritize operational resources
- Supports regional marketing & distribution planning
- Assists in warehouse/logistics optimization decisions

Strategic Insight Angle - If 60%+ of customers are concentrated in a few locations, localized fulfillment centers could reduce shipping costs and delivery time.

2.Shipping Type Distribution ![revenue & Strategy dasboard](images/shipping%20type%20filter%201.2.png)

 Business Question - Which shipping methods are most used?

 What the Visual Shows - Breakdown of shipping type (e.g., Standard, Express, Same-Day).
 
 Why It Matters

- Shows customer preference behavior
- Impacts cost structure
- Impacts delivery timelines
- Helps forecast logistics workload
  
Operational Insight- If express shipping is high but average revenue is low, margins may be under pressure.

 3.Shipping Type + Average Revenue ![revenue & Strategy dasboard](images/shipping%20type%201.2.png)
 
  Business Question - Does shipping type influence customer spending?

  What the Visual Shows - Average purchase amount by shipping type.

  Why It Matters: 
- Identifies high-value shipping segments
- Supports premium shipping strategy
- Helps evaluate shipping profitability

Analytical Angle - If express customers spend significantly more, premium delivery can be positioned as a value-added service.

4.Total Revenue per Season ![revenue & Strategy dasboard](images/Total%20revenue%20by%20season%201.4.png)
 
Business Question - Are there seasonal revenue trends affecting operations?

What the Visual Shows - Revenue aggregated by season.

 Why It Matters:

-Identifies peak operational periods
-Supports inventory planning
-Improves workforce planning
-Enables proactive logistics scaling

Executive Insight - Strong seasonal spikes suggest the need for flexible operational capacity planning.

# Sope 3 : People & Customer Analytics  ![revenue & Strategy dasboard](images/Customer%20Analytics%201.1.png)
 Scope Objective : This section analyzes customer demographics and behavioral patterns to understand:

 - Who our customers are
 - How frequently they purchase
 - What drives higher spending
 - Which segments generate the most value

   The goal is to identify high-value customer segments and support targeted engagement, retention, and revenue growth strategies.

 1.Customer Count by Age  ![revenue & Strategy dasboard](images/Customer%20count%20by%20age%201.4.png)
Business Question - What is the age distribution of our customer base?

What the Visual Shows - Total number of customers grouped by age (or age band if grouped).

Why It Matters: 

- Identifies dominant demographic segments
- Supports targeted marketing strategies
- Helps tailor product positioning
- Assists in long-term customer lifecycle planning

 Strategic Insight Angle - If the majority of customers fall within a narrow age range, marketing and product development should prioritize that demographic profile.

2.Average Revenue by Frequency of Purchase  ![revenue & Strategy dasboard](images/average%20revenue%20by%20frequency%20of%20purchase%201.3.png)
Business Question - Does purchase frequency influence customer value?

 What the Visual Shows - Average revenue grouped by frequency of purchases.

Why It Matters:
- Identifies high-value repeat customers
- Highlights loyalty opportunities
- Measures potential customer lifetime value proxy
  
 Strategic Insight - If higher purchase frequency correlates with higher average revenue, investment in retention programs and loyalty incentives becomes justified.


3. Average Purchase Amount by Previous Purchases ![revenue & Strategy dasboard](images/average%20purchase%20amount%201.4.png)
   
 Business Question - Do customers with more historical purchases spend more per transaction?

What the Visual Shows - Average purchase amount based on number of previous purchases.

Why It Matters:

- Measures customer maturity impact
- Identifies whether repeat buyers increase or stabilize spending
- Supports retention and upsell strategies

Executive Insight - If average purchase value increases with previous purchases, this confirms the long-term value of customer retention strategies.


4. Payment Method – Customer Count & Average Purchase ![revenue & Strategy dasboard](images/payment%20Method%201.2.png)
   
Business Question -Which payment methods are most used, and do they influence spending behavior?

 What the Visual Shows:

 - A table displaying:
 - Count of customers per payment method
 - Average purchase amount per payment method

 Why It Matters:

 - Identifies dominant transaction channels
 - Reveals high-value payment segments
 - Supports fintech and checkout optimization strategies

Strategic Insight - If certain payment methods show both high usage and high average purchase amounts, partnerships or promotional efforts can be strategically aligned to those channels.


Executive Summary

This analysis examined 3,900 customer transactions to identify key revenue drivers, operational patterns, and customer behavior dynamics. Using SQL for data exploration and DAX for analytical modeling, the project delivers a structured evaluation across Revenue & Strategy, Operational Performance, and People Analytics.

From a revenue perspective, performance is driven primarily by specific product categories and repeat customer behavior. Subscription status and purchase frequency show measurable influence on revenue contribution, reinforcing the importance of customer retention strategies. Promotional levers such as discounts and promo codes demonstrate varying impact, indicating that targeted deployment is more effective than broad discounting.

Operationally, customer concentration by location and seasonal revenue patterns highlight the need for demand-aware logistics planning. Shipping type and payment method analysis further reveal behavioral differences that can inform checkout optimization and cost management strategies.

From a customer analytics standpoint, demographic distribution and purchase history patterns confirm that repeat customers contribute disproportionately to revenue stability. Average purchase value trends suggest that customer maturity and engagement directly influence transaction size, supporting investment in retention and loyalty initiatives.

Overall, this project demonstrates how structured analytics can move beyond descriptive reporting to support strategic decision-making. By aligning visuals with clear business questions and measurable outcomes, the dashboard framework provides management with actionable insight across revenue optimization, operational efficiency, and customer value management.


