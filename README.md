# Credit Card Financial Dashboard — Power BI

An interactive Power BI dashboard built on credit card transaction and customer data to monitor key financial KPIs, track revenue trends, and deliver actionable insights to stakeholders for data-driven decision making.

---

## Project Overview

Financial teams often rely on static reports that are slow to produce and hard to interpret. This project replaces that manual process with an automated, interactive dashboard that surfaces real-time insights across transaction volume, revenue, customer demographics, and card performance — all filterable by quarter, card type, and date range.

---

## Key Insights

- **Blue card dominates** — contributes ₹46M out of ₹55.3M total revenue (83%)
- **Bills is the top spend category** — ₹14M, followed by Entertainment (₹10M) and Fuel (₹9M)
- **Graduate customers generate the most revenue** — ₹22M vs ₹11M for High School
- **Businessmen are the highest revenue job segment** — ₹17.3M with avg income ₹98K
- **40–50 age group is the most valuable** — contributing ₹24M out of ₹55.3M
- **Swipe transactions lead** — ₹35M vs Chip (₹17M) and Online (₹3M)
- **Top 3 states (TX, NY, CA) contribute equally** — ₹13M each, showing national spread
- **Male customers outpace female** — ₹30M vs ₹25M in revenue

---

## What Was Built

- Connected Power BI to SQL database containing transaction and customer tables
- Automated data refresh replacing manual monthly reporting process
- Built 7–8 financial KPI cards with real-time filtering by quarter, card type, and date
- Created cross-page drill-through from transaction level to customer level
- Designed slicers for Week Start Date, Quarter, and Card Category for stakeholder self-service

---

## Tech Stack

```
Power BI Desktop    DAX (Data Analysis Expressions)
SQL                 Data Modelling
Power Query (M)     Interactive Visualisations
```

---

## Project Structure

```
Credit_card_transaction_report/
├── README.md
├── Credit Card Transaction Report.pdf     ← dashboard screenshots
├── credit_card.csv                        ← transaction data
└── customer.csv                           ← customer data
```

---

## How to View

The dashboard PDF with full screenshots is included in this repository. To interact with the live dashboard, open the `.pbix` file in Power BI Desktop (free download from Microsoft).

---

## Author

**Atharv** — [GitHub](https://github.com/cuuri0usatharv)
