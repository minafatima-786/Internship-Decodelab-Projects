# E-Commerce Orders — Exploratory Data Analysis & Power BI Dashboard

An end-to-end data analytics project analyzing **1,200 e-commerce orders (2023 – mid 2025)** to uncover sales trends, customer behavior, cancellation patterns, and product performance.

Built as **Project 2** of the DecodeLabs Industrial Training Kit — Batch 2026.

---

## Objective

Transform raw e-commerce order data into clear business insights using Python for EDA and Power BI for interactive visual storytelling.

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python** (pandas, numpy, matplotlib, seaborn, scipy) | Data cleaning, EDA, statistics |
| **Jupyter Notebook** | Documentation of analysis |
| **Power BI** | Interactive dashboard |
| **Excel** | Raw data source |

---

## Key Insights

| # | Insight | Finding |
|---|---------|---------|
| 1 | **Cancellation & Return Rate** | ~41.4% of orders do NOT complete successfully (Cancelled 20.8% + Returned 20.6%) |
| 2 | **Order Value Distribution** | Mean = $1,054 · Median = $824 → right-skewed (few high-value orders pull the average up) |
| 3 | **Top Revenue Products** | Chair ($195.6K), Printer ($195.6K), Laptop ($192.1K) |
| 4 | **Coupon Usage** | ~74% of orders used a coupon (FREESHIP, WINTER10, SAVE10) |
| 5 | **Referral Source** | Instagram leads in revenue ($275.3K), followed by Email and Google |
| 6 | **Outliers** | Legitimate high-value orders → treated as **VIP signal**, not noise |
| 7 | **Time Trend** | 2023 had highest volume; 2025 data is partial (up to June) |

---

## Business Recommendations

1. **Urgent:** Investigate the **41% cancellation + return rate** — biggest operational red flag.
2. **VIP Segment:** Create a loyalty tier for customers with high TotalPrice / high quantity orders.
3. **Coupon Strategy:** A/B test **FREESHIP vs. discount coupons** for conversion impact.
4. **Referral Focus:** Double down on **Instagram** as the top-performing channel.
5. **Trend Monitoring:** Track monthly orders & revenue closely as 2025 progresses.

---

👤 Author
Mina Fatima
