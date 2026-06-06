# Customer Churn & Revenue Leakage Analysis
### Food Delivery Marketplace | SQL · Python · Power BI

---

## Overview

This project builds an end-to-end customer analytics framework to identify 
churn drivers, quantify revenue leakage, and surface retention opportunities 
for food delivery platforms.

Using a public Foodpanda dataset, I applied RFM segmentation, churn analysis, 
and operational diagnostics to model the commercial impact of customer behaviour 
patterns — translating raw transactional data into actionable business decisions.

**Tools:** SQL (PostgreSQL) · Python (Pandas, Scikit-learn) · Power BI · 
RFM Analysis · Cohort Analysis · Feature Engineering

---

## Business Problem

Food delivery platforms face a persistent challenge: high acquisition costs 
combined with low repeat ordering mean that churn directly erodes unit economics.

Key questions this project addresses:

- Which customer segments churn the most — and why?
- Where is revenue leaking operationally?
- Which behavioural signals predict churn before it happens?
- How can retention strategy be prioritised by commercial impact?

---

## Analytical Approach

**Customer Segmentation & RFM Scoring**
- RFM scoring (Recency, Frequency, Monetary) to classify high-, mid-, 
  and low-value customers
- City-level and demographic segmentation to identify geographic 
  churn patterns

**Churn & Retention Analysis**
- Overall churn rate: 49.73% (2,984 churned customers)
- Overall retention rate: 50.27% (3,016 retained customers)
- Churn segmented by RFM group, city, demographics, and order behaviour

**Operational & Revenue Diagnostics**
- Total revenue analysed: $14.3M
- Average Order Value: $2.6K
- Cancelled delivery rate: 32.80%
- Delayed delivery rate: 32.87%
- On-time delivery rate: 34.33%
- Restaurant-level performance benchmarking

**Executive Reporting**
- Real-time Power BI dashboard connected to PostgreSQL backend
- KPIs: churn rate, retention rate, AOV, cancellation rate, 
  city-level performance

---

## Key Findings

**~50% churn concentrated in low-RFM segments**
RFM analysis revealed churn was not evenly distributed — low-frequency, 
low-recency customers churned at nearly 50%, while high-RFM customers 
showed significantly stronger retention. This enables targeted, 
segment-specific retention strategy rather than blanket campaigns.

**~66% of all orders affected by cancellations or delays**
Delivery delays (32.87%) and cancellations (32.80%) together accounted 
for approximately 66% of all orders — directly driving churn even among 
customers who had previously rated the service positively.

**City-level churn variation is significant**
Churn rates varied materially by city (Lahore highest, Karachi lowest), 
indicating that geography-specific operational and marketing interventions 
would outperform a one-size-fits-all approach.

**Revenue is disproportionately concentrated**
A small number of top-performing restaurants (e.g., KFC) contributed a 
disproportionate share of total revenue — creating both a concentration 
risk and a strategic partnership opportunity.

---

## Modelled Business Impact

*Financial impacts are modelled estimates based on the public dataset, 
scaled using industry benchmarks to reflect real-world platform economics.*

| Finding | Modelled Impact |
|---|---|
| Targeted retention for low-RFM churners | ~$10M+ revenue uplift potential |
| Fixing cancellation & delivery bottlenecks | ~$10M+ in recoverable leakage |
| City-specific churn reduction campaigns | ~$5M+ incremental impact |
| High-value restaurant partnership strategy | ~$5M+ growth opportunity |

---

## Strategic Recommendations

- Implement RFM-based segmentation for personalised retention offers
- Protect high-value retained customers with loyalty incentives
- Run reactivation campaigns targeting low-RFM, high-churn segments
- Reduce cancellation and delay rates — operational reliability is 
  the single biggest churn driver
- Monitor churn, retention, and delivery performance weekly via 
  live dashboards
- Build city-specific playbooks rather than national campaigns

---

## Tools & Technologies

| Tool | Usage |
|---|---|
| SQL (PostgreSQL) | Data extraction, RFM scoring, operational metrics |
| Python (Pandas, Scikit-learn) | EDA, segmentation, churn modelling |
| Power BI | Real-time executive dashboard |
| RFM Analysis | Customer value segmentation |
| Feature Engineering | City-level and behavioural signal creation |

---

## Dataset Note

This analysis uses a publicly available Foodpanda dataset. 
All financial impacts are modelled estimates — not real business outcomes. 
The methodology reflects real analytical approaches used in food delivery 
and marketplace analytics.

---

*Part of the E-Commerce & Supply Chain Analytics Portfolio*  
*[View full portfolio](https://aarushijain16.github.io/sales-demand-customer-growth-portfolio/)*
