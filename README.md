# ecommerce_sales_analytic_dashboard
Power BI dashboard analyzing ecommerce sales data with KPIs and filters
# Sales Analytics Dashboard | Power BI

An interactive Power BI dashboard designed to analyze sales performance across 7+ cities and 4+ product categories. This project features 5+ dynamic visualizations with year-based slicers and customer segmentation filters to support real-time decision-making.

- 📌 Built gender-based and regional sales insights across multiple customer segments
- ⚡ Achieved a 20% performance boost by optimizing DAX measures for faster report load time
- 📊 Tracked key performance indicators (KPIs) including revenue, customer count, and average order value
- 🧠 Designed for business leaders and analysts to explore trends, patterns, and growth opportunities

> 📁 Includes `.pbix` file, sample data, and dashboard screenshots to demonstrate capabilities.

---

## 🚀 Features

- Dynamic slicers (year, city, category, gender)
- 8+ responsive visuals: bar charts, line graphs, KPIs, matrix tables
- Custom DAX measures for YoY comparisons and performance analysis
- Customer segmentation and drill-through capability
- Optimized load time with query reduction techniques

---

## 🖼️ Dashboard Preview

![Dashboard Overview](Screenshot_dashboard-overview.png)

---

## 📁 Project Structure

power-bi-sales-dashboard/
├── Reports/
│   └── ecommerce_sales_analysis.pbix
├── Data/
│   └── uncleaned_ecoomerce_data1_synthetic.csv
├── Screenshots/
│   └── dashboard-overview.png
├── README.md
├── LICENSE
└── .gitignore

---

## 🧾 Dataset

- Sample sales data including:
  Column Name	Description
    Transaction_ID : Unique ID for each transaction
    Order_Date : Date the order was placed
    Ship_Date : Date the order was shipped
    Order_Processing_Time : Shipping delay in days (some negative values)
    Product_ID : Unique identifier for each product
    Product_Name : Name of the product
    Category, Subcategory : Product classification
    Customer_ID : Unique customer identifier
    Customer_Name : Customer full name
    Customer_Segment : Type of customer (e.g., Regular, Business)
    Customer_Location : Customer's location
    Quantity : Units sold per transaction
    Unit_Price : Price per unit
    Discount : Applied discount (0.0–0.15 range)
    Shipping_Cost : Delivery charges
    Total_Amount : Final order value
    Payment_Method : Payment type (Credit Card, Cash, etc.)
    Payment_Status : Paid, Refunded, or Failed
    Platform : Order source (Website, Mobile App)
    Referral_Source : Lead source (Instagram, Email, etc.)
    Is_Returned : Binary flag for return (1 = returned)
- All data is fictional or anonymized for demonstration purposes.
- Included in `Data/` folder.

---

## 🛠️ How to Use

1. Download this repository or clone it using Git:
   ```bash
   git clone https://github.com/Divyanshee09/ecommerce_sales_analytic_dashboard.git
