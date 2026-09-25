# Finance Dashboard

## 📊 Project Overview

This project is an interactive **Finance Dashboard built with Microsoft Power BI** to analyse financial transactions, customer segments, transaction activity, fees, taxes, and overall financial performance.

The dashboard is designed to provide a clear overview of financial data while allowing users to interact with the report using filters, dynamic measures, and drill-through functionality.

## 🎯 Objectives

* Analyse overall financial transaction performance
* Monitor transaction amounts, fees, and taxes
* Understand customer and transaction patterns
* Analyse transaction activity across different categories
* Provide interactive filtering for deeper analysis
* Enable users to drill down from summary information to individual transactions

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power BI Report Builder**
* **Data Modelling**
* **DAX Measures**
* **Interactive Visualisations**
* **Drill-through Analysis**

## 📌 Dashboard Pages

### 1. Overall Analysis

The main dashboard provides a high-level overview of the financial data.

Key features include:

* Financial KPI cards
* Transaction trend analysis
* Transaction type analysis
* Customer gender analysis
* Customer segmentation
* Category-based filtering
* Dynamic measure selection
* Interactive slicers
* Charts for financial performance analysis

### 2. Transactions

The Transactions page provides detailed transaction-level information.

It includes:

* Transaction ID
* Transaction Date
* Customer Name
* Transaction Type
* Transaction Status
* Gender
* Customer Segment
* Total Amount
* Total Fees
* Total Tax

This page is designed to support detailed investigation of the transactions behind the aggregated dashboard figures.

## 📈 Key Metrics

The dashboard includes several financial measures:

* **Total Amount**
* **Total Fees**
* **Total Tax**
* **Total Transactions**
* **Average Transaction Value**

A dynamic measure selector allows users to change the metric being analysed across supported visuals.

## 🔎 Interactivity

The dashboard includes interactive features such as:

* Category slicers
* Customer-related filters
* Transaction filters
* Dynamic measure selection
* Cross-filtering between visuals
* Drill-through from summary analysis to transaction details
* Page navigation

These features allow users to explore the data from different perspectives rather than relying only on static reports.

## 🧩 Data Model

The report uses financial transaction and customer information.

Key entities used in the dashboard include:

* `finance_transactions`
* `customers`
* `Dynamic Measures`

The financial transaction data contains information such as transaction dates, transaction types, transaction statuses, amounts, fees, taxes, and merchant categories. Customer data contains attributes such as customer name, gender, and customer segment.

## 📂 Repository Structure

```text
Finance-Dashboard/
│
├── Finance Dashboard.pbix
└── README.md
└── Snapshot of Dashboard.png
```

## 🚀 How to Use

1. Download or clone this repository.
2. Open `Finance Dashboard.pbix` using **Microsoft Power BI Desktop**.
3. Interact with the dashboard using the available slicers and visuals.
4. Use the drill-through functionality to explore detailed transactions.
