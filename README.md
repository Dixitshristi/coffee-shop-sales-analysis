# ☕ Coffee Shop Sales & Performance Analysis

An end-to-end data analytics project examining **149K+ transactions** for a multi-location coffee shop chain. This project integrates an interactive **Power BI Executive Dashboard** with **Python (Pandas, Seaborn)** exploratory data analysis to uncover sales trends, peak rush periods, and revenue drivers.

---

## 📊 Dashboard Preview

![Dashboard Preview](assets/dashboard_preview.png)

---

## 📌 Executive Summary & Key KPIs

* **Total Revenue:** $698.81K
* **Total Transactions:** 149,116
* **Total Units Sold:** 214K
* **Average Order Value (AOV):** $4.69

---

## 🔍 Key Business Insights

1. **Peak Demand Window:**
   * Customer footfall spikes significantly between **8:00 AM and 10:00 AM** (morning rush), followed by steady daytime volume before tapering off post 7:00 PM.
2. **Category Performance:**
   * **Coffee** and **Tea** categories drive the primary revenue volume, with high-margin attachment opportunities in the **Bakery** section.
3. **Store Performance:**
   * Revenue is evenly distributed across all branches (~33% share each), led marginally by **Hell's Kitchen** ($236.51K), followed by **Astoria** ($232.24K) and **Lower Manhattan** ($230.06K).
4. **Monthly Trajectory:**
   * Revenue showcases steady month-over-month growth from January through June, peaking at $166K in June.

---

## 🛠️ Tech Stack & Tools

* **Business Intelligence:** Microsoft Power BI (DAX, Data Modeling, Custom Dark UI)
* **Programming & EDA:** Python (Pandas, NumPy, Matplotlib, Seaborn)
* **Environment:** Jupyter Notebook / Anaconda
* **Data Source:** Excel Dataset (`Coffee Shop Sales.xlsx`)

---

## 📂 Repository Structure

```text
├── data/
│   └── Coffee Shop Sales.xlsx       # Transaction dataset
├── power_bi/
│   └── coffee_sales_dashboard.pbix  # Power BI report file
├── notebook/
│   └── coffee_sales_analysis.ipynb  # Jupyter notebook analysis
├── assets/
│   └── dashboard_preview.png        # Dashboard screenshot
└── README.md                        # Documentation
