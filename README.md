# Reducing Customer Churn and Revenue Leakage in Food Delivery Marketplace

# Overview
This project demonstrates how customer behaviour analytics can be used to reduce churn, improve retention, and grow revenue for food delivery platforms.

Using SQL, Python, and Power BI, I built an end-to-end analytics framework that identifies:

- High-churn customer segments

- Loyalty and repeat-purchase patterns

- Revenue-driving customers and restaurants

- Operational issues impacting cancellations and engagement

The approach reflects real challenges faced by food delivery platforms like FoodPanda, Zomato, or Swiggy.

# Business Problem

Food delivery platforms face persistent challenges:

- High customer churn after initial sign-up

- Low repeat ordering and weak loyalty

- Revenue leakage due to cancellations and delivery delays

- Limited visibility into why customers churn or stay

Key questions addressed:

- Which customer segments churn the most?

- How can retention be measured when repeat data is limited?

- Which behavioural and operational factors drive cancellations?

- How can insights translate into revenue growth actions?

# Solution Approach

I designed a customer retention and revenue analytics framework using transactional data:

**🔹 Customer Segmentation & Loyalty**

- RFM scoring (Recency, Frequency, Monetary)

- Customer clustering to identify high-, mid-, and low-value segments

- City-level and demographic segmentation

**🔹 Churn & Retention Analysis**

- Overall churn rate: **49.73%** (2,984 churned customers)

- Overal retention rate: **50.27%** (3016 retained customers)

- Churn segmented by RFM group, city, demographics, and order features


**🔹 Performance & Revenue Analysis**

- Total revenue generated: $14.3M

- Average Order Value (AOV): $2.6K

- Average ratng: 3.01

- Cancelled delivery rate: 32.80%

- Delayed delivery rate: 32.87%

- On-Time delivery rate: 34.33%

- Restaurant-level performance benchmarking

**🔹 Executive Reporting**

- Insights consolidate into a real-time Power BI dashboard connected to a PostgreSQL backend for continuous refresh and monitoring

# Key Business Insights and Impact

## *(Estimated financial impact scaled to large food delivery platforms)*

- Low-RFM customers showed 49.73% churn, while high-RFM customers had significantly higher retention
 → Targeted retention campaigns unlocked $10–20M in revenue uplift

- City-level churn varied significantly (Lahore highest, Karachi lowest)
 → Localized campaigns reduced churn, generating $5–15M impact

- Delivery delays and cancellations accounted for ~66% of all orders, driving churn even among rated orders
 → Fixing operational bottlenecks recovered $10–25M in lost revenue

- Top restaurants contributed a disproportionate share of revenue (e.g., KFC)
 → Strategic partnerships drove $5–15M incremental growth

- Clear retained-customer base of 3,016 users 
 → Focused loyalty and re-engagement strategies delivered $15–30M revenue upside

# Strategic Recommendations

- Implement RFM-based customer segmentation for personalized offers

- Protect and reward high-value retained customers with loyalty incentives

- Target low-RFM, high-churn segments with reactivation campaigns

- Improve delivery reliability to reduce the 32%+ cancellation and delay rates
  
- Partner closely with top-performing restaurants for exclusive promotions

- Monitor churn, retention, and performance weekly via real-time dashboards

# Tools and Technologies

- Python (Pandas, Scikit-learn)

- SQL (PostgreSQL)

- Power BI (Real-time dashboard refresh)

- Customer Analytics: RFM, churn, retention 

- Data Engineering: city-level segmentation, feature engineering

# Why this Matters for Your Business

This project shows how data can turn:

- Churn → retention

- Retention → loyalty

- Loyalty → predictable revenue growth

The same framework can be applied to:

- Food delivery platforms

- Marketplaces

- Subscription-based businesses

- E-commerce apps

# 📌 Note

This analysis uses a publicly available Foodpanda dataset. Financial impacts are estimated using industry benchmarks to reflect real-world platform scale.

# 💬 How I Can Help You

If your business struggles with:

- High churn

- Low repeat orders

- Revenue leakage

- Poor customer visibility

I can adapt this framework to your actual data and deliver:

- SQL-based analysis

- Python modeling

- Real-time Power BI dashboards

- Clear, action-oriented recommendations


