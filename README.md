# 📄 SSRS Paginated Reports 

This repository features a collection of **paginated reports** built using **SQL Server Reporting Services (SSRS)**. These reports are optimized for print-ready exports (PDF, Excel), dynamic filtering, and enterprise-level formatting. Each `.rdl` report is designed for real-world use cases in healthcare and product analytics.

---

## 🏥 1. Hospital Claims Summary Report

![Hospital Report with Parameters](https://raw.githubusercontent.com/YashaswiniReddy/paginated-reports-SSRS/main/Hospital%20report%20with%20parameters.png)

- **Purpose:** Analyze yearly claim costs and patient admissions for healthcare organizations.
- **Features:**
  - Conditional formatting (red for low cost, green for high)
  - Filters by category and organization (using parameters)
  - Displays real-time timestamp with execution context
  - Here the red color indicates claimcost beow 500 and green indicates above 500

---

## 🧠 2. Report Design – Using Expressions

![SSRS Expressions](https://raw.githubusercontent.com/YashaswiniReddy/paginated-reports-SSRS/main/Paginated%20Report%20with%20subreport.png)

- **Purpose:** Demonstrates use of expressions and dynamic summaries
- **Features:**
  - Aggregated values (`SUM`, `COUNTDISTINCT`)
  - Dynamic header values like `[ExecutionTime]` and `[StartDate]`
  - Highlights the logic layer behind the visual

---

## 🛍️ 3. Product List with Subreport (Design Layout)

![Subreport Layout](![Subreport Layout](https://raw.githubusercontent.com/YashaswiniReddy/paginated-reports-SSRS/main/Paginated%20Report%20with%20subreport.png)
)

- **Purpose:** Displays a master-detail layout using subreports
- **Use Case:** Product listings where each product links to a related sales detail


---

## ✅ 4. Final Rendered Output of Subreport

![Subreport Output](https://raw.githubusercontent.com/YashaswiniReddy/paginated-reports-SSRS/main/Result%20of%20paginated%20subreport.png)

- **Purpose:** View the final output of a product-sales relationship report
- **Features:**
  - Dual table layout
  - Product prices and sales amounts
  - Ready for PDF/Excel export

---

## 🛠 Tools Used

- **SSRS (SQL Server Reporting Services)**
- **SQL Server Data Tools (SSDT)**
- **T-SQL Queries**
- **Paginated Report Builder**
- **Subreport and Parameter Integration**

