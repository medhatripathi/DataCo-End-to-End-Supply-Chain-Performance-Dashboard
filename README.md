# 📋 DataCo-End-to-End-Supply-Chain-Performance-Dashboard
An interactive Power BI dashboard analyzing 180K+ orders to optimize supply chain operations, improve delivery performance, and drive data-informed decision-making.
![Dashboard Preview](https://github.com/medhatripathi/DataCo-End-to-End-Supply-Chain-Performance-Dashboard/blob/main/Pg1Executive_Summary.png)

---

# 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development & visualization |
| **Power Query** | Data extraction, cleaning & transformation |
| **DAX** | Business logic & calculated measures |
| **GitHub** | Version control & documentation |

---

# 📁 Data Source

**Dataset:** [DataCo Smart Supply Chain Dataset](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

| Attribute | Details |
|-----------|---------|
| **Source** | Kaggle |
| **Records** | 180,000+ orders |
| **Columns** | 53 fields |
| **Time Period** | 2015-2018 |
| **File Format** | CSV |

**Key Data Fields Used:**
* Order & shipping dates
* Delivery status & delay metrics
* Product categories & pricing
* Customer segments & geography
* Shipping modes & carriers

---

# ✨ Features & Highlights

### Business Problem
Supply chain teams lacked visibility into:
* Delivery performance across regions and carriers
* Underperforming suppliers causing delays
* Inventory prioritization (which products matter most)
* Seasonal patterns affecting capacity planning
* Real-time KPI tracking for leadership decisions

### Goal of the Dashboard
Enable supply chain leaders to:
* Monitor on-time delivery rates at a glance
* Identify regional and carrier bottlenecks quickly
* Prioritize high-value products using ABC classification
* Track monthly trends and seasonal patterns
* Drill into product-level details for root cause analysis

---

### Dashboard Walkthrough

#### Page 1: Executive Summary
High-level KPIs for leadership decision-making.

![Executive Summary](https://github.com/medhatripathi/DataCo-End-to-End-Supply-Chain-Performance-Dashboard/blob/main/Pg1Executive_Summary.png)

| Visual | Business Question Answered |
|--------|---------------------------|
| KPI Cards | What's our current performance snapshot? |
| Monthly Revenue Trend | Is revenue growing or declining? |
| Orders by Segment | Which customer segments drive volume? |
| Delivery Status Breakdown | How many orders are delayed? |
| Top 5 Products | Where is revenue concentrated? |

#### Page 2: Delivery Performance
Deep dive into logistics efficiency.

![Delivery Performance](https://github.com/medhatripathi/DataCo-End-to-End-Supply-Chain-Performance-Dashboard/blob/main/Pg2Delivery%20Performance.png)

| Visual | Business Question Answered |
|--------|---------------------------|
| OTD Rate Card | Are we meeting delivery promises? |
| Late Deliveries by Region | Which regions need attention? |
| Shipping Mode Comparison | Which carriers are most reliable? |
| Delay Distribution | How severe are our delays? |
| Monthly OTD Trend | Is delivery performance improving? |

#### Page 3: Product Analysis
Inventory prioritization and category performance.

![Product Analysis](https://github.com/medhatripathi/DataCo-End-to-End-Supply-Chain-Performance-Dashboard/blob/main/Pg3Product%20Analysis.png)

| Visual | Business Question Answered |
|--------|---------------------------|
| Revenue by Category | Which categories drive revenue? |
| Top 10 Products | What are our best sellers? |
| ABC Classification | Which SKUs need priority focus? |
| Category Matrix | How do categories compare on key metrics? |

#### Page 4: Geographic View
Regional performance and market analysis.

![Geographic View](https://github.com/medhatripathi/DataCo-End-to-End-Supply-Chain-Performance-Dashboard/blob/main/Pg4Geographic%20View.png)

| Visual | Business Question Answered |
|--------|---------------------------|
| Revenue Map | Where are our strongest markets? |
| Region Comparison | How do regions compare? |
| Country Performance Table | Which countries need improvement? |

#### Page 5: Product Detail
Granular analysis for specific products.

![Product Detail](https://github.com/medhatripathi/DataCo-End-to-End-Supply-Chain-Performance-Dashboard/blob/main/Pg5Product%20Detail.png)

| Visual | Business Question Answered |
|--------|---------------------------|
| Product Name Card | Which product am I analyzing? |
| Monthly Sales Trend | How does this product perform over time? |
| Order Details Table | What are the individual order records? |

---

### Business Impact & Insights

#### 💡 Insight 1: Regional Delivery Gap

- Finding → Central America has 45% late delivery rate (vs. 23% average)
- Impact → Identified $50K+ potential savings in penalty costs
- Action → Flagged for carrier review and SLA renegotiation

#### 💡 Insight 2: Shipping Mode Optimization

- Finding → "Same Day" shipping achieves 95% OTD vs. 72% for "Standard"
- Impact → Opportunity to improve high-value order delivery
- Action → Recommended tiered shipping by order value

#### 💡 Insight 3: Product Prioritization

- Finding → 18% of SKUs (Class A) drive 80% of revenue
- Impact → Focused inventory management on 200 critical products
- Action → Increased safety stock for Class A items

#### 💡 Insight 4: Seasonal Capacity Gap

- Finding → Q4 shows 35% revenue spike with 15% OTD decline
- Impact → Identified capacity planning issue during peak season
- Action → Recommended pre-positioning inventory before October

#### 💡 Insight 5: Supplier Performance Issues

- Finding → 3 suppliers have >30% late delivery rate
- Impact → Directly affecting fill rates and customer satisfaction
- Action → Created supplier scorecard for procurement review
