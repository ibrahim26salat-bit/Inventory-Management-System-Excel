# 📦 Inventory Management System — Excel

## 📌 Project Overview

This project is an **Excel-based Inventory Management System** designed to manage products, customers, vendors, purchases, sales, inventory levels, and business performance.

The workbook combines **data entry, automated lookups, inventory calculations, transaction management, pivot analysis, and dashboard visualization** into a single Excel-based business management solution.

The project demonstrates how Microsoft Excel can be used to build a practical business operations and analytics system without requiring a separate database application.

---

# 🎯 Business Objective

The objective of this project is to create a centralized system for managing inventory-related business operations and monitoring key business metrics.

The system helps answer questions such as:

* What products are available?
* How much inventory has been purchased?
* How much inventory has been sold?
* What is the current stock level?
* Which products have low stock?
* Which customers generate the most revenue?
* Which products are selling the most units?
* What is the total purchase amount?
* What is the total sales amount?
* What is the current inventory value?
* What is the overall profit/loss based on the available transaction data?

---

# 🛠️ Tools & Technologies

* **Microsoft Excel**
* Excel Tables
* VLOOKUP
* SUMIF
* IF / IFERROR
* Pivot Tables
* Pivot-based analysis
* Automated calculations
* Data validation
* Dashboard visualization
* Business reporting

---

# 🧩 Workbook Structure

The workbook contains nine main worksheets:

```text
Dashboard
Customers
Products
Vendors
NewEntry
Purchase
Sales
Inventory
Pivots
```

---

# 📊 1. Dashboard

The Dashboard provides a visual summary of important business information.

It includes analysis of:

* Top Selling Products
* Top Customers by Revenue
* Inventory / Stock Levels
* Business performance metrics

The dashboard is designed to provide management with a quick overview of sales and inventory performance.

---

# 👥 2. Customers

The Customers sheet acts as the customer master table.

It contains:

* Customer ID
* Customer Name
* Email
* Address

This master data is used by the Sales module to automatically retrieve customer information.

---

# 🛍️ 3. Products

The Products sheet maintains the product master data.

It contains:

* HSN Code
* Product Name
* Cost
* Selling Price

The product master is used by the Purchase, Sales, and Inventory sheets.

---

# 🚚 4. Vendors

The Vendors sheet maintains vendor information.

It contains:

* HSN Code
* Product Name
* Vendor Name
* Phone
* Address

This information is connected to purchase and inventory records through lookup formulas.

---

# 📝 5. New Entry

The NewEntry sheet provides an entry interface for:

* Purchase Entry
* Sales Entry

This creates a more structured workflow for recording business transactions.

---

# 📥 6. Purchase Management

The Purchase sheet records incoming inventory transactions.

### Fields include:

* HSN Code
* Product Name
* Vendor
* Date
* Units
* Cost
* Amount

The workbook uses lookup formulas to retrieve product and vendor information automatically.

Purchase amount is calculated based on:

**Units × Cost**

---

# 📤 7. Sales Management

The Sales sheet records outgoing sales transactions.

### Fields include:

* Customer ID
* Customer Name
* HSN Code
* Product Name
* Date
* Available Stock
* Units Sold
* Selling Price
* Amount

Customer and product information is automatically retrieved using lookup formulas.

Sales amount is calculated based on:

**Units Sold × Selling Price**

---

# 📦 8. Inventory Management

The Inventory sheet automatically calculates inventory position using purchase and sales data.

### Key fields include:

* HSN Code
* Product Name
* Cost
* Purchased Units
* Sold Units
* Current Stock
* Stock Amount
* Vendor
* Stock Notification

### Inventory Calculation

Current stock is calculated using:

**Purchased Units − Sold Units**

Inventory value is calculated using:

**Current Stock × Cost**

The workbook also provides stock notifications such as:

* **In Stock**
* **Low Stock**

This helps identify products that may require replenishment.

---

# 📊 9. Pivot Analysis

The Pivots sheet provides summary calculations used for business reporting and dashboard visualization.

The workbook currently contains analysis for:

* Customer count
* Product count
* Purchase amount
* Sales amount
* Inventory value
* Sales by customer
* Sales by product
* Stock by product

---

# 📈 Current Business Metrics

Based on the current sample data in the workbook:

| Metric          |      Value |
| --------------- | ---------: |
| Customers       |          7 |
| Products        |         10 |
| Purchase Amount | ₹10,24,028 |
| Sales Amount    |  ₹2,35,440 |
| Inventory Value |  ₹8,21,948 |
| Profit/Loss     |    ₹33,360 |

> These values represent the current sample dataset contained in the workbook and will change when new transactions are entered.

---

# 💡 Business Insights Supported

The system can support businesses in:

* Monitoring current inventory.
* Identifying low-stock products.
* Tracking purchases.
* Tracking sales.
* Monitoring inventory value.
* Understanding customer revenue.
* Identifying top-selling products.
* Monitoring vendor information.
* Comparing purchase and sales values.
* Supporting inventory replenishment decisions.
* Monitoring overall business performance.

---

# 🔄 Business Process

The system follows a simple business workflow:

```text
Customer / Product / Vendor Master Data
                 ↓
          Purchase Entry
                 ↓
          Inventory Update
                 ↓
            Sales Entry
                 ↓
          Inventory Balance
                 ↓
        Pivot Analysis
                 ↓
            Dashboard
                 ↓
       Business Decision
```

---

# ⚙️ Excel Features Demonstrated

This project demonstrates practical use of:

* Excel Tables
* Structured References
* VLOOKUP
* SUMIF
* IF
* IFERROR
* Pivot Tables
* Automated calculations
* Linked worksheets
* Data validation
* Dashboard charts
* Inventory calculations
* Business KPI reporting

---

# 🚀 Skills Demonstrated

This project demonstrates skills relevant to **Business Analyst and Data Analyst roles**:

* Microsoft Excel
* Data Analysis
* Business Reporting
* Inventory Analytics
* Sales Analytics
* Customer Analysis
* Product Analysis
* Vendor Management
* Data Management
* KPI Development
* Dashboard Development
* Pivot Table Analysis
* Formula-based Automation
* Business Process Analysis

---

# 📁 Repository Structure

```text
Inventory-Management-System-Excel/
│
├── Inventory Management System.xlsx
├── Dashboard.png
│
├── images/
│   └── Inventory-Dashboard.png
│
└── README.md
```

---

# 📷 Dashboard Preview

![Inventory Management Dashboard](images/Inventory-Dashboard.png)

---

# 👨‍💻 Author

**Ibrahim Salat**

Aspiring Business Analyst | Power BI | Excel | SQL | Data Analytics
