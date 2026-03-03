# 📊 Crowe Inc. Financial Performance Analysis

## 🔗 Live Dashboard
**[View the Interactive Power BI Report here](https://app.powerbi.com/view?r=eyJrIjoiODZhOGUyZGQtNDhkOS00YWQzLWIxNzgtMzRhMDU0NmUwNGZkIiwidCI6ImVmNDVhMzIyLTdmMmEtNDBmYi04ZDU0LTVjNTVlY2NjNGIwMyJ9)**

---

## 🏢 Project Background
**Crowe Inc.** is a fictitious Canadian SME operating within the manufacturing sector. This project involves the end-to-end processing of two years of fiscal data (2019–2020), transforming raw journal entries into a high-level executive income statement dashboard.

The company operates through four regional hubs:
* 🧊 **North:** Specialized logistics & resource management.
* 🏭 **South:** Primary manufacturing & industrial hub.
* 📦 **East:** Regional assembly & customer support.
* 🌲 **West:** Supply chain procurement & distribution.

---

## 🧠 The Thought Process & Analysis

### 1. Data Structuring (The Accounting Foundation)
The project began with a raw **General Journal** and a **Chart of Accounts (COA)**. To ensure data integrityand clarity for the visualization, I performed the following:
* **Trial Balance Creation:** Validated that the total Debits equaled total Credits to ensure a balanced ledger.
* **Account Mapping:** Categorized accounts into Assets, Liabilities, Equity, Revenue, and Expenses.
* **Cleaning:** Handled contra-revenue accounts (Returns) and volume discounts to ensure "Net Sales" figures were accurate.

### 2. Data Modelling (Power BI)
I utilized a **Star Schema** to optimize the Power BI model, creating Dimension tables from the Fact table for better categorization and filtering: 
* **Fact Table:** The Journal transactions.
* **Dimension Tables:** * `Calendar Table` for time-intelligence (YoY, MoM growth).
    * `Chart of Accounts` for financial hierarchy.
    * `Divisions` for regional performance filtering.

---

## 🎨 Visualization Strategy
The dashboard was designed to provide both **Executive** and **Operational** views:
* **KPI Header:** Immediate visibility into Net Revenue, Total Expenses, and Net Income.
* **Trend Analysis:** Identifying seasonal peaks in the Canadian manufacturing cycle across 2019 and 2020.
* **Geographical Insights:** A comparative analysis of the four regional divisions to identify underperforming or high-growth areas.

---

## 🛠 Tech Stack
* **Excel:** Initial data audit and Trial Balance validation.
* **Power BI:** Trial Balance creation, Data modelling, DAX engineering, and UI/UX design.

---

## 📂 Repository Contents
* `Crowe Inc. Journal.xlsx`: The source dataset containing the Journal, Chart of Accounts and Context sheets.
* `Screenshot of Visualized Data`:  Screeshot of Crowe Inc.'s Financial Performance snapshot

---
