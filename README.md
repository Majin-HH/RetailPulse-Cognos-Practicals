# RetailPulse – IBM Cognos Analytics Practicals

**Name:** Hetish  
**Roll No:** 54  
**Course:** BCA (Data Science & AI), Section BCADS23  
**University:** Babu Banarasi Das University (BBD University), Lucknow  
**Instructor:** Ms. Monica Rao  
**Tool Used:** IBM Cognos Analytics (Cloud Trial)

---

## 📌 Project Overview
RetailPulse is a sample retail business. In these six practicals, sales and customer data was loaded into IBM Cognos Analytics and used to build different types of reports and a dashboard.

## 📂 Repository Structure
```
RetailPulse-Cognos-Practicals/
├── README.md
├── dataset/
│   ├── RetailPulse_Sales_Dataset.xlsx      (sales data – Practicals 1-5)
│   ├── RetailPulse_Sales_Dataset.csv       (same sales data in CSV)
│   └── RetailPulse_Customers (1).xlsx      (customer data – Practical 6)
└── reports/
    ├── RetailPulse - First Sales Report.pdf              (Practical 1)
    ├── RetailPulse - Grouped Sales Report.pdf            (Practical 2)
    ├── RetailPulse - Filtered Sales Report.pdf           (Practical 3)
    ├── RetailPulse Region-Product Crosstab.pdf           (Practical 4)
    ├── RetailPulse Sales Prompt Report.pdf               (Practical 5)
    └── RetailPulse Customer Insights Dashboard.pdf       (Practical 6)
```

## 🧪 Practicals Summary

| # | Practical | Type | What it shows |
|---|-----------|------|---------------|
| 1 | First Sales Report | List report | Region, Product Category and Sales Amount in a simple table |
| 2 | Grouped Sales Report | Grouped list | Sales grouped by Region → Store → Product Category with subtotals and overall total (₹10,88,800) |
| 3 | Filtered Sales Report | List + filter | Only the **North** region records, with Sales Date, Quantity and totals (₹2,66,400) |
| 4 | Region–Product Crosstab | Crosstab | Regions (rows) × Product Categories (columns) with row/column totals |
| 5 | Sales Prompt Report | Prompt crosstab | User chooses a region (e.g. West) at run time; report shows only that region (₹2,16,000) |
| 6 | Customer Insights Dashboard | Dashboard | KPI (3545 Active Customers), line chart of Returning vs New Customers by month, bar chart of Active Customers by Loyalty Segment |

## 📊 Dataset
- **Sales dataset** (`RetailPulse_Sales_Dataset`): 16 records with Order Date, Region, Store, Product Category, Units Sold and Sales Amount (₹). Orders span June–September 2026. Total sales = ₹10,88,800.
- **Customer dataset** (`RetailPulse_Customers (1).xlsx`): 64 records (4 months × 4 regions × 4 loyalty segments) with Month, Region, Loyalty Segment, New Customers, Returning Customers and Active Customers. Total active customers = 3,545.
- Regions: East, West, North, South. Product categories: Groceries, Apparel, Electronics, Home & Kitchen. Loyalty segments: Bronze, Silver, Gold, Platinum.

## 🔑 Key Observations
- **Total sales:** ₹10,88,800
- **Top region:** West (₹3,08,000); **lowest:** East (₹2,56,000)
- **Top category:** Electronics (₹4,65,000); **lowest:** Groceries (₹1,33,000)
- **Customers:** Bronze is the largest loyalty segment (1,370 active customers) and Platinum the smallest (373).
- Returning customers rise from 386 (June) to 547 (September), while new customers fall from 468 to 355.

## 🛠️ How to Reproduce
1. Log in to IBM Cognos Analytics.
2. Upload the files from the `dataset/` folder (**My content → Upload data**).
3. Create a new report/dashboard and select the uploaded data module.
4. Build each report as described in the table above and export as PDF.

## 📎 Reports
All exported PDFs are available in the [`reports/`](./reports) folder.
