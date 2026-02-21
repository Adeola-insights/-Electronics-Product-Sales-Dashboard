# Electronics-Product-Sales-Dashboard
A comprehensive Power BI sales analytics dashboard tracking revenue, profit, and performance across products, cities, regions, sales reps, and channels for an electronics retail business in Nigeria.
# Project Overview
 This project is a Power BI business intelligence dashboard built to analyze the sales performance of an electronics retail company operating across multiple Nigerian cities. It provides real-time visibility into key business metrics, enabling data-driven decision-making at both the strategic and operational level.
 The dashboard was analyzed using a structured filter-based approach — drilling into each sales representative, region, product category, city, channel, and time period to extract actionable insights.
 ### Tools & Technologies

|Tools | Pourpose|
|------|---------|
| Microsoft Power BI | Dashboard creation and data visualization |
| DAX | Calculated measures and KPIs |
| Power Query | Data transformation and modelling |

### Key Metrics Tracked

| Metric | Overall Value|
|--------|--------------|
|: Total Revenue | ₦2 Billion |
| : Total Sales | 2,100 units| 
| : Total Profit | ₦467 Million |
| : Profit Margin | ~23% |

### Dashboard Sections
1. KPI Cards 

Profit — Total profit generated across all reps, products, and cities
Revenue — Gross revenue before deductions
Total Sales — Count of all transactions

2. Profit By Category

Horizontal bar chart showing profit contribution from:
Electronics (highest — ₦0.27bn)
Home Appliances (₦0.11bn)
Furniture (₦0.09bn)

3. Revenue By City

Column chart comparing revenue across:
Abuja, Port Harcourt, Lagos, Kano

4. Revenue By Channel

Donut chart showing split between:
Store (offline) — ~53%
Online — ~47%

5. Revenue By Month

Line chart tracking January through May revenue trend — reveals a significant May revenue drop requiring investigation.

6. Sales By Region

Bar chart showing sales volume across East, West, and North regions.


![elect](https://github.com/user-attachments/assets/074fac54-848c-4db5-96b3-d84aecdbadc9)

# Key Insights 

### Overall Performance

The business generated ₦2 billion in revenue with a profit of ₦467 million across 2,100 total sales. This gives an approximate profit margin of ~23%, which is reasonably healthy for an electronics retail business.

### 🏷️ Profit By Category

Electronics is the clear leader at ₦0.27bn profit, followed by Home Appliances at ₦0.11bn and Furniture at ₦0.09bn. This tells us that:
Electronics drives the majority of profitability and should be prioritized in inventory and marketing
Furniture, while present, contributes the least — management may want to evaluate whether it's worth maintaining this category

### 🌍 Revenue By City

Abuja leads with ₦0.66bn, followed closely by Port Harcourt (₦0.58bn), Lagos (₦0.55bn), and Kano (₦0.55bn). Notably:
Abuja outperforms Lagos, which is surprising given Lagos is Nigeria's commercial hub — this could suggest stronger competition in Lagos or untapped Abuja market potential
The relatively balanced performance across cities suggests good geographic diversification
### 📺 Revenue By Channel

The donut chart shows the business leans more toward Store (offline) sales compared to Online, with Store appearing to hold roughly 60-65% share. This indicates:
The business is still heavily brick-and-mortar dependent
There's a significant opportunity to grow the online channel, especially given Nigeria's growing e-commerce market

### 📅 Revenue By Month (January–May)

This is the most concerning insight. Revenue showed a steady growth trend from ₦0.35bn in January, peaking around ₦0.58bn in April, but then crashed sharply in May to approximately ₦0.25bn. This is alarming because:
The drop is steep and sudden — not a gradual decline
It could indicate seasonal factors, stock-out issues, a loss of a major client, or external market disruption
Management should urgently investigate what caused the May drop

### 🗺️ Sales By Region

The East region leads in sales volume, followed by West, then North. This aligns with the city data where Abuja (FCT/North-Central) performs well but the Eastern region overall dominates in units sold.

### 🛒 Product Range

The business carries 10 products across categories , from Air Conditioners and Smartphones to Furniture (Sofa Classic, Office Chair Pro). The product mix is diverse but could lead to inventory management challenges.

# Sales Rep Performance
|Rank   | Rep   | Revenue | Profit | Region | Key Strength|
|-------|-------|-------|-------|-------|-------|
| 🥇 1 | Peter  | ₦422M | ₦84M | West | Highest overall revenue |
| 🥇 2 | Grace | ₦399M | ₦80M | North | Best city distribution |
| 🥉 3 | Chidinma | ₦398M | ₦80M | East | Best channel balance (50/50) |
| 🥉 4 | Musa | ₦382M | ₦76M | North | Strong online adoption |
| 🥉 5 | David | ₦370M | ₦74M | East | Consistent performer | 
| 🥉 6 | Aisha | ₦367M | ₦73M | West | Top Furniture seller |

* All 6 reps maintain a healthy ~20% profit margin
* Electronics is the highest profit-generating category across all reps
* Business is geographically diversified across 4 major Nigerian cities
* Channel mix is approaching a balanced online/offline split
 ###  Areas of Concern
1. May Revenue Collapse
Revenue dropped ~94% in May from a peak of ~₦580M in April to only ₦23M in May with just 16 recorded transactions. This affected all reps, all cities, all products, and both channels simultaneously  indicating a company-level supply, operational cost.
2. Aisha's Electronics Gap
Aisha generates only ₦36M in Electronics profit versus Peter's ₦49M  a 36% gap on the highest-margin category.
3. Lagos Underperformance
Nigeria's largest commercial city is tied last in revenue despite its population and commercial activity.
4. Store Channel Dependency
Peter and Grace  the top two revenue generators — are also the most store-dependent, leaving significant online revenue potential untapped.

### Business Recommendations

* Inventory & Supply Chain: Maintain a 30-day safety stock buffer, diversify suppliers and set minimum stock alerts to prevent another May-style collapse
* Online Channel Growth: Shift channel balance to at least 50/50 by year-end through e-commerce presence and digital sales training for reps
* Lagos Market: Investigate why Nigeria's biggest city ranks last in revenue and deploy targeted campaigns or a dedicated rep there
* Product Strategy: Expand Electronics range, review Furniture's true ROI including storage costs, and grow Home Appliances selection
* Sales Team Development: Pair top performers with lower ones as mentors, implement a team-wide performance review and balanced incentive structure
* Revenue Stability: Introduce monthly targets with weekly check-ins and promotional campaigns for slow months to smooth revenue peaks and crashes
* Regional Expansion: Stabilize current operations first, then consider Ibadan, Enugu or Kaduna as next city targets
* Data & Reporting: Add daily Power BI refresh, target vs actual visuals, and automated alerts for drops exceeding 20% week-over-week
* Profitability: Reduce Furniture dependency and grow Electronics to push margins from 23% toward 27%
* Governance: Hold weekly data-driven sales meetings, document the May incident, and assign clear KPI ownership per rep

