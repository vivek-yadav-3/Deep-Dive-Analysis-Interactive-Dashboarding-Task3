## 🎯 Objective
Answer complex, multi-faceted business problems by performing a deep-dive analysis and building an interactive, automated dashboard using real e-commerce data.

## 📊 Core KPIs Defined

| KPI | Formula | Business Rationale |
|-----|---------|-------------------|
| **Total Revenue** | Sum of all order revenues | Overall business health indicator |
| **Average Order Value (AOV)** | Total Revenue / Total Orders | Measures customer spending per transaction |
| **Revenue per Customer** | Total Revenue / Unique Customers | Indicates customer lifetime contribution |
| **Repeat Purchase Rate** | Repeat Buyers / Total Customers × 100 | Measures customer loyalty |
| **Category Revenue Share** | Category Revenue / Total Revenue × 100 | Identifies high-performing product lines |

---

## 🔍 Deep-Dive Analysis Areas

### 1. Cohort Analysis
- Tracks customer retention month-over-month
- Identifies which customer cohorts have the highest retention
- Visualized as a heatmap showing % of customers returning

### 2. Funnel Analysis
- Maps customer journey from first purchase → repeat buyer → high-value → VIP
- Identifies drop-off points in the customer lifecycle

### 3. RFM Customer Segmentation
Customers are scored on three dimensions:
- **Recency** — How recently did they purchase?
- **Frequency** — How often do they purchase?
- **Monetary** — How much do they spend?

Segments created:
| Segment | Description |
|---------|-------------|
|  Champions | Best customers — buy often, spend most |
|  Loyal Customers | Regular buyers with good spend |
|  Potential Loyalists | Recent buyers with potential |
|  At Risk | Were good customers, slipping away |
|  Lost Customers | Haven't bought in a long time |

---

## 📈 Dashboard Features
- ✅ Region filter (North / South / East / West / All)
- ✅ Monthly revenue bar chart
- ✅ Category revenue donut chart
- ✅ Top 10 products by revenue
- ✅ Revenue by region
- ✅ RFM customer segments
- ✅ Recency vs Revenue scatter plot

---

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| Python 3.10 | Core programming language |
| Pandas | Data manipulation |
| Matplotlib / Seaborn | Static visualizations |
| Plotly | Interactive charts |
| Dash | Web dashboard framework |
| Scikit-learn | Customer segmentation (KMeans) |
| Jupyter Notebook | Analysis environment |

---

## 📌 Key Findings
1. **Electronics** is the highest revenue category (~65% of total)
2. **North region** leads in revenue contribution
3. **December** shows peak sales (holiday effect)
4. **Champions segment** (top customers) drive majority of revenue
5. Cohort analysis shows strongest retention in Q4 cohorts
---
