# Sales and Campaign Analytics
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-blue?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-yellow?logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)

This project simulates a real-world analytics workflow, from raw data exploration in SQL to a fully interactive multi-page Power BI report. The dataset represents a fictional e-commerce company's CRM system: customers, orders, leads, campaigns, and sales reps across 6 countries. 

The goal was to answer three questions:
 
1. Where is sales revenue coming from, and who's driving it?
2. How well is the lead funnel converting, and where does it leak?
3. Which marketing channels are actually worth the spend?

# Dashboard
<img width="1295" height="807" alt="image" src="https://github.com/user-attachments/assets/cbb6c800-2aeb-47fb-9755-2a292552667a" />
<img width="1294" height="808" alt="image" src="https://github.com/user-attachments/assets/dde32678-0671-4390-a71c-bcc3097f638e" />
<img width="1295" height="807" alt="image" src="https://github.com/user-attachments/assets/6caa7a50-b625-4c83-95a0-fe11744ddd61" />


## Key Insights
 
**Sales**
- $16.1M in delivered revenue across 2,645 orders, average order value $6,086.14
- Delivered is 66.2% of all 2025 orders. Cancelled ($2.0M) and Returned ($1.4M) revenue is real leakage worth investigating
- Philippines (23.4%) and USA (23.2%) lead revenue, nearly neck and neck. Canada remains the weakest market at 8.4%
- Furniture ($8.4M) still dominates, more than double Electronics ($5.4M)

**Customers**
- 401 customers converted from leads in 2025
- Within the year, Repeat buyers (446 customers, 2-4 orders) already outpace One-Time buyers on revenue per customer ($14,875 vs $5,988). Loyal status (5+ orders) is rare within a single year, only 11 customers hit it, so loyalty is best measured across multiple years, not one

**Lead Funnel**
- 5,185 leads generated in 2025, 7.73% conversion (401 converted)
- LinkedIn remains the strongest source at 11.05% conversion, TikTok the weakest at 5.64%
- Qualified (32.6%) and Lost (24.3%) are the two biggest non-converted buckets, most drop-off still happens after a lead is already vetted

**Marketing ROI**
- Ranking shifts within 2025: Influencer is cheapest per signup at $249, followed by Facebook Ads at $417
- LinkedIn Ads is by far the most expensive in 2025 at $3,457 per signup, its worst showing of any channel
