# 📊 AdventureWorks – Sales Performance Analysis Dashboard

## 📌 Project Overview

This project delivers an **interactive sales performance dashboard** built on the AdventureWorks dataset using **SQL + Power BI**.
It provides actionable insights into **sales, profitability, market share, and customer behavior**, enabling data-driven business decisions.

---

## 🎯 Key Features

* **Data Engineering (SQL):**

  * Created cleaned views for Customers, Products, Sales Territories, Dates, and Internet Sales.
  * Integrated external **Sales Target data (CSV)** with transactional data for benchmarking.

* **Data Visualization (Power BI):**

  * Designed dashboards for sales trends, profitability analysis, and market share.
  * Built **DAX measures** (Market Share, YTD Growth, Profit Margin, Performance vs Target).
  * Interactive filters for **region, product category, and time period**.

* **Business Impact:**

  * Identified **top-performing regions & products**.
  * Compared **actual vs. target performance**.
  * Provided management-ready reporting to support strategic planning.

---

## 🛠️ Tech Stack

* **Database:** SQL Server (AdventureWorks Sample Database)
* **Querying & Cleaning:** SQL Views (`SQL Scripts/`)
* **Visualization:** Power BI Desktop
* **Data Integration:** CSV (`Sales Target.csv`)
* **Analytics:** DAX Measures

---

## 📂 Project Structure

```
AdventureWorks-Sales-Performance-Analysis/
 ┣ README.md
 ┣ Sales Target.csv                 # External dataset
 ┣ AdventureWorks Sales Performance Dashboard.jpg  # Dashboard snapshot
 ┣ Business Requests.docx           # KPI/business requirement document
 ┣ Market Share DAX Measure.txt     # DAX formulas
 ┣ SQL Scripts/                     # Data cleaning scripts
 ┃ ┣ cleaned_dim_customers_view.sql
 ┃ ┣ cleaned_dim_date_view.sql
 ┃ ┣ cleaned_dim_product_view.sql
 ┃ ┣ cleaned_dim_sales_territory_view.sql
 ┃ ┣ cleaned_fact_internet_sales_view.sql
 ┃ ┣ update_database.sql
 ┣ Images/
 ┃ ┣ Logo.png
 ┃ ┗ order icon.png
```

---

## 🚀 How to Run the Project

### 1️⃣ Setup Database

1. Install **SQL Server** and **SQL Server Management Studio (SSMS)**.
2. Download and restore the **AdventureWorks sample database** from Microsoft.
3. Open the `SQL Scripts/` folder and run scripts in SSMS to create cleaned views.

### 2️⃣ Load Data into Power BI

1. Open **Power BI Desktop**.
2. Connect to SQL Server and import the cleaned views.
3. Import `Sales Target.csv` into Power BI.

### 3️⃣ Apply DAX Measures

1. Open `Market Share DAX Measure.txt`.
2. Copy-paste formulas into **Power BI → Modeling → New Measure**.

### 4️⃣ Build Dashboard

1. Use `Business Requests.docx` as KPI requirements.
2. Add charts, KPIs, and slicers as shown in `AdventureWorks Sales Performance Dashboard.jpg`.

---

## 📈 Dashboard Preview

![Dashboard](AdventureWorks%20Sales%20Performance%20Dashboard.jpg)

---

## 📊 Insights Gained

* Sales performance tracked **against targets** across time and region.
* Identification of **high-performing product categories** and **top sales territories**.
* Analysis of **profitability and growth trends** with interactive drilldowns.

---

## 🔐 Compliance & Best Practices

* Data cleaned and anonymized for safe usage.
* Structured SQL views for reproducibility.
* Follows **business request → data pipeline → visualization → insights** workflow.

---

## 📎 References

* [AdventureWorks Sample Database – Microsoft](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure)
* [Power BI Desktop](https://powerbi.microsoft.com/desktop/)


👉 Do you also want me to create a **shorter README version** (only overview, setup, and preview) for quick GitHub browsing, or keep this **detailed version**?
