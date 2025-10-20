# Sales-Analysis

This project use the Candid Co's 2014-2018 sales data to identify key revenue and profit drivers across products, channels, and regions. In addition, the project uncovered seasonal trend and outliers with an aim to aligning performance against budget. Aid in optimizing pricing, promotions and market expansion for sustainable growth.
 
# Objectives

- Identify major **revenue and profit drivers** across products, channels, and regions  
- Detect **seasonal trends, peaks, and troughs** in sales cycles  
- Examine **regional and product-level concentration** to manage market risks  
- Provide **interactive visualization** for real-time regional performance monitoring  
- Support **data-driven pricing, promotional, and expansion strategies**


# Key Insights

# Insights and Analysis

### 1. Seasonal Trends

Sales cycles fluctuate between **$24M and $26M** per month, showing **clear peaks in March and August–December**, and troughs in **January**.

- The **first peak (March)** likely reflects seasonal demand recovery post-winter and early-year promotional campaigns.  
- The **second peak (Aug–Dec)** aligns with back-to-school and holiday spending, representing the most profitable period annually.  
- Despite recurring January troughs, **total January revenue (2014–2017)** remains **above the average of other months**, suggesting strong baseline demand.  
- **February** consistently records the **lowest total revenue (<$92M over 3 years)**, confirming it as a true off-peak period.

<img width="1106" height="655" alt="image" src="https://github.com/chinguyen19/Sales-Analysis/blob/78792f92ac0e83816e533739f9880ba4ffcf8c50/seasonal-trends_1.png" />

---

### 2. Annual and Aggregate Revenue Patterns
- **Observation:** While January typically dips, total revenue over multiple years shows strong baseline performance.  
- **Seasonality:** Sales start to rebound in spring and maintain consistent high levels from August through December, reflecting predictable cyclical behavior.  

<img width="1106" height="655" alt="image" src="https://github.com/chinguyen19/Sales-Analysis/blob/78792f92ac0e83816e533739f9880ba4ffcf8c50/seasonal-trends.png" />

---

### 3. Product Performance
- **Top-tier Products:** Product 25 and Product 26 generate over **$100M** across three years, indicating strong market demand.
- **Mid-tier Products:** Revenue ranges from **$68M to $75M**, showing steady but moderate contribution.
- **Bottom-tier Products:** Products below **$60M**, which may require review or promotion strategies.

<img width="1106" height="655" alt="image" src="https://github.com/chinguyen19/Sales-Analysis/blob/78792f92ac0e83816e533739f9880ba4ffcf8c50/product-performance.png" />

---

### 4. Sales Channels
- **Wholesale:** Accounts for **54% of total sales** (~$668.2M), indicating reliance on domestic bulk distribution.
- **Exports:** Around **15% (~$180.6M)**, showing a smaller but significant contribution from international markets.
- **Implication:** Business strategy should balance domestic bulk channels with potential export growth.

<img width="1106" height="655" alt="image" src="https://github.com/chinguyen19/Sales-Analysis/blob/78792f92ac0e83816e533739f9880ba4ffcf8c50/sales-channel.png" />

---

### 5. Regional Performance
- **West:** ~$360M (~35%) – market leader.
- **South & Midwest:** Each contributes over ~$320M (~32%), showing strong and consistent central region demand.
- **Northeast:** ~$210M (~20%), indicating opportunities for growth and targeted investment.
- **Implication:** Regional focus and marketing should prioritize growth in Northeast while maintaining leadership in West.

<img width="1106" height="655" alt="image" src="https://github.com/chinguyen19/Sales-Analysis/blob/78792f92ac0e83816e533739f9880ba4ffcf8c50/regional-performance.png" />

---

### 6. State-Level Performance
- **Top-tier States:** Revenue above $228.8M.
- **Mid-tier States:** Example – Texas ($55.5M), consistent but trailing top states.
- **Lower-tier States:** Example – New Jersey ($35M), highlighting uneven market penetration.
- **Implication:** Sales strategies should be tailored to state performance levels.

<img width="1106" height="655" alt="image" src="https://github.com/chinguyen19/Sales-Analysis/blob/78792f92ac0e83816e533739f9880ba4ffcf8c50/state.png" />

---

### 7. Order Value Distribution
- **Observation:** Order values are right-skewed.
  - Most orders cluster between **$20K and $80K**.
  - Long tail extends to **$400K**, but large orders are rare (less than 100).
- **Implication:** Focus on optimizing mid-sized orders while monitoring high-value outliers for special handling or opportunities.

<img width="1106" height="655" alt="image" src="https://github.com/chinguyen19/Sales-Analysis/blob/78792f92ac0e83816e533739f9880ba4ffcf8c50/aov.png" />


# Key Takeaways

- Strong **seasonal and regional patterns** drive revenue performance  
- **Wholesale dominance** suggests channel concentration risk  
- **West region leadership** and **Northeast growth potential** offer strategic focus points  
- Insights support **pricing, promotion, and expansion optimization** for sustained growth

# Dashboard

The **Regional Sales Dashboard** enables users to:

- View **revenue by U.S. region**  
- Drill down into **product, channel, and customer performance**  
- Detect **seasonal patterns and anomalies**  
- Support **strategic pricing and promotion planning**

> **Note:** The dashboard focuses on *regional* performance aggregation, not individual product or customer details.
<img width="1106" height="655" alt="image" src="https://github.com/chinguyen19/Sales-Analysis/blob/16f70bd7ae20a6a7c8496c36e09ecf9bab266cd1/Screenshot%202025-10-01%20150520.png"/>


# Tools & Technologies

- **Power BI** – Interactive dashboard design  
- **SQL** – Data extraction and transformation  
- **Python (Pandas, Matplotlib)** – Data cleaning, trend analysis, and visualization  
- **Excel** – Data validation and quick exploratory summaries  
