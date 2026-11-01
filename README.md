# ☕ Coffee Shop Sales Analysis | Excel Dashboard

An interactive Excel dashboard built with **Pivot Tables, Pivot Charts and Slicers** to analyse six months of sales across three coffee shop locations in New York. The project looks at *when* customers buy, *what* they buy, and *where* the revenue comes from.

---

## Table of Contents
1. [Project Overview](#-project-overview)
2. [Business Questions](#-business-questions)
3. [Dashboard Preview](#-dashboard-preview)
4. [Key Metrics](#-key-metrics-kpis)
5. [Pivot Table Analysis](#-pivot-table-analysis)
6. [Key Insights](#-key-insights)
7. [Recommendations](#-recommendations)
8. [Data Notes & Limitations](#-data-notes--limitations)
9. [Tools Used](#-tools-used)
10. [Repository Structure](#-repository-structure)

---

## Project Overview

The dataset contains transaction-level records for a coffee shop chain operating in three stores: **Astoria**, **Hell's Kitchen** and **Lower Manhattan**, covering **January to June**. Raw transactions were summarised with Pivot Tables and visualised in a single dashboard with slicers for **Day Name** and **Month Name**, so any view can be filtered interactively.

## Business Questions

- How much revenue is generated, and how is it trending month over month?
- Which hours of the day and days of the week are the busiest?
- Which product categories and products drive the most sales?
- How do the three store locations compare in footfall and revenue?
- What is the distribution of order sizes?

## Dashboard Preview

![Coffee Shop Sales Dashboard](images/dashboard.png)

> Dashboard features: KPI cards, hourly demand line chart, category pie chart, weekday orders, top 5 products, store comparison, and order size distribution — all filterable by day and month.

## Key Metrics (KPIs)

| Metric | Value |
|---|---|
| **Total Sales** | $698,812.33 |
| **Total Footfall (transactions)** | 149,116 |
| **Average Bill / Person** | $4.69 |
| **Average Items / Order** | 1.4 |
| **Total Quantity Sold** | 214,470 units |

---

## 🧮 Pivot Table Analysis

### 1. Monthly Sales Trend

| Month | Total Sales | Change vs Previous Month |
|---|---:|---:|
| January | $81,677.74 | — |
| February | $76,145.19 | -6.8% |
| March | $98,834.68 | +29.8% |
| April | $118,941.08 | +20.3% |
| May | $156,727.76 | +31.8% |
| June | $166,485.88 | +6.2% |
| **Grand Total** | **$698,812.33** | |

### 2. Sales by Product Category

| Category | Total Sales | Share of Sales |
|---|---:|---:|
| Coffee | $269,952.45 | 38.6% |
| Tea | $196,405.95 | 28.1% |
| Bakery | $82,315.64 | 11.8% |
| Drinking Chocolate | $72,416.00 | 10.4% |
| Coffee Beans | $40,085.25 | 5.7% |
| Branded | $13,607.00 | 1.9% |
| Loose Tea | $11,213.60 | 1.6% |
| Flavours | $8,408.80 | 1.2% |
| Packaged Chocolate | $4,407.64 | 0.6% |
| **Grand Total** | **$698,812.33** | **100%** |

### 3. Footfall & Sales by Store Location

| Store | Footfall (Transactions) | Total Sales | Avg. Sale / Transaction |
|---|---:|---:|---:|
| Hell's Kitchen | 50,735 | $236,511.17 | $4.66 |
| Astoria | 50,599 | $232,243.91 | $4.59 |
| Lower Manhattan | 47,782 | $230,057.25 | $4.81 |
| **Grand Total** | **149,116** | **$698,812.33** | **$4.69** |

### 4. Quantity Ordered by Hour (Peak Hours)

| Hour | Quantity Ordered |
|---:|---:|
| 8 AM | 25,197 |
| 9 AM | 25,370 |
| **10 AM** | **26,713** |
| 11 AM | 14,035 |
| 12 PM – 5 PM | ~12,400 – 12,900 per hour |
| 8 PM (closing) | 880 |

*Total quantity across all hours (6 AM – 8 PM): 214,470.*

---

## Key Insights

**Revenue growth**
- Sales more than doubled from January ($81.7K) to June ($166.5K), a **~104% increase**. February was the only dip. Growth was strongest in March and May, and slowed to +6.2% in June.

**Peak demand**
- Demand peaks between **8 and 10 AM**, with 10 AM the single busiest hour (26,713 units). Hours 7–10 account for about **45% of all units sold**. Volume then drops by almost half at 11 AM and stays flat through the afternoon.

**Products**
- **Coffee and Tea make up ~67% of total revenue.** Bakery and Drinking Chocolate add another ~22%.
- The **top 5 product types** (Barista Espresso, Brewed Chai Tea, Hot Chocolate, Gourmet Brewed Coffee, Brewed Black Tea) contribute **$358,870.75, about 51% of sales**. Barista Espresso leads at $91.4K.

**Stores**
- The three stores are very close in performance, each contributing roughly a third of revenue. **Hell's Kitchen** earns the most, while **Lower Manhattan** has the lowest footfall but the **highest average spend per transaction ($4.81)**.

**Weekdays**
- Orders are evenly spread across the week (20.5K – 21.7K per day). **Friday** has the most orders (21,701), **Monday** the highest sales ($101.7K), and **Saturday** is the slowest on both measures.

**Order size**
- Regular (30.7%), Large (30.1%) and Not defined (29.9%) are nearly equal, while **Small orders are only 9.3%**.

## Recommendations

1. **Staff and stock for the morning rush (7–10 AM)** to reduce wait times and capture peak demand.
2. **Run afternoon promotions** (e.g. combo deals or happy hour) to lift the flat 12–5 PM period.
3. **Upsell at Lower Manhattan**: customers there already spend more per visit, so premium items and bundles could work well.
4. **Boost Saturday traffic** with weekend offers, since it is the weakest day.
5. **Bundle Bakery with Coffee/Tea** to grow the average items per order, currently only 1.4.
6. **Grow low-share categories** (Branded, Flavours, Packaged Chocolate) through better placement or promotions.

## Data Notes & Limitations

- Data covers **January – June only**, so seasonality across a full year cannot be assessed.
- About **30% of orders have an undefined size**, which limits size-based analysis. Capturing size at the point of sale would fix this.
- "Footfall" is measured as the **number of transactions**, not actual customer visits.

## Tools Used

- **Microsoft Excel**: Pivot Tables, Pivot Charts, Slicers, dashboard design

## Repository Structure

```
├── Coffee_Shop_Sales_Dashboard.xlsx   # Excel file with pivot tables & dashboard
├── images/
│   └── dashboard.png                  # Dashboard screenshot
└── README.md                          # Project report
```

## Author

**Your Name**
[LinkedIn](https://linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)

---
 If you found this project useful, consider giving it a star!
