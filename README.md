# Digital Marketing Campaign Profitability & ROI Analysis

A comprehensive data analysis of 8,000 marketing campaign records to evaluate ad spend efficiency, identify high-performing channels, and optimize customer acquisition strategies.

**[➡️ View Interactive Dashboard on Tableau Public]https://public.tableau.com/views/Digital-Marketing-Profitability-Dashboard/DigitalMarketingProfitabilityDashboard?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link**

---

## Executive Summary (Business Case)
The primary objective of this project is to translate transactional marketing data into actionable business strategies. By developing core financial KPIs, this analysis demonstrates how to maximize Return on Investment (ROI) by strategically reallocating ad budgets toward channels with the highest net profit margins.

### Global Portfolio Metrics
* **Total Net Profit:** $65.2M
* **Total Ad Spend:** $40.0M
* **Average ROI:** 162.9%

---

## Key Data Insights

1. **The Power of Word-of-Mouth:** The **Referral** channel serves as the primary revenue driver, generating the highest net profit ($14.1M) and significantly outperforming traditional paid channels (PPC and Social Media) in cost efficiency.
2. **Conversion Friction:** Web behavior analysis indicates a direct correlation between average time on site and successful conversion rates, validating the need for targeted UI/UX optimizations.
3. **Funnel Efficiency:** *(Optional: Add a brief finding from your funnel chart here. Example: The Retention stage yields a substantially higher ROI compared to top-of-funnel Awareness campaigns, proving the value of customer loyalty.)*

---

## Strategic Recommendations

* **Budget Reallocation:** Reduce ad spend in underperforming Social Media campaigns by 15% and redirect that capital toward scaling the Referral program and customer loyalty incentives.
* **Audience Targeting:** Focus the upcoming quarter's marketing budget on the highest-performing demographic segments to decrease Customer Acquisition Cost (CAC) and increase overall Lifetime Value (LTV).

---

## Technical Execution & Tools
* **Primary Visualization Tool:** Tableau Desktop / Public.
* **Data Processing:** Structured data cleaning, logical modeling, and dimension categorization (casting boolean 0/1 integers to discrete dimensions for accurate segmentation).
* **Business Logic & Calculated Fields:**
  * `Estimated Revenue = [Conversion] * 15000`
  * `Profit = [Estimated Revenue] - [Ad Spend]`
  * `ROI = SUM([Profit]) / SUM([Ad Spend])`

---

### Dashboard Preview
*(To explore the data by specific segments, please use the interactive link at the top of this page).*

![Marketing Analytics Dashboard](dashboard_preview.png)
