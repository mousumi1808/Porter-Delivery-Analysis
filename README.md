Problem Statement:
Analyze Porter Delivery operational data to identify root causes of declining delivery-time satisfaction and provide data-driven recommendations to improve customer experience and protect market share.

Steps:
- Delivery performance and operational analytics.
- Explored market-level patterns and performance indicators.
- Tools Used: Python, Data Cleaning & EDA

Key insights :

- Italian, Spanish, Caribbean, brazilian, belgian are top 5 category taking more than 50 mins to deliver which shows either operational challenges for these stores of these categories like too many orders, partners not available to deliver,could be far away from the location of orders.
-- Saturday & sunday sees the most orders count.
-On an avg nearly 42-50 mins on an avg is taken to deliver.
- Hourly order volume has a 0.95 correlation with busy partners, indicating highly responsive capacity scaling.
- This analysis shows that with increase in the volume , no. of onshift partners also increases or remains more. Hour-wise demand and partner utilization show a ~0.90 correlation, indicating strong operational alignment between order inflow and rider availability, though some variance remains during peak periods.
- Moroccan, cheese, Burmese, irish, Italian are top categoring where more than 60% orders are above avg no. of orders.
- Onshift vs Busy: 0.998-Markets with more onshift partners also have more busy partners. Onshift vs Delivery Time: –0.43 ,More onshift partners → faster deliveries. Busy vs Delivery Time: –0.38 ,More busy partners → slightly faster delivery. Onshift and busy partners are almost perfectly correlated, indicating redundancy. Both show moderate negative correlation (~–0.4) with delivery time, suggesting partner availability helps but is not the primary driver.
- Detailed analysis in the code attached in folder.
- Partner utilization metrics revealed that resource distribution is uneven across markets.
- Aggregating data at market level helped identify high-risk locations contributing disproportionately to delivery delays.

Challenges Faced :
- Missing and inconsistent market-level data required careful aggregation and cleaning.
- Translating technical metrics into actionable business insights required market-level summarization.

Recommendations :
 Partner Management
- Increase on-shift partner availability in high-delay markets.
- Dynamically reallocate partners based on historical demand patterns.
- Introduce incentive programs during peak hours to improve partner participation.



