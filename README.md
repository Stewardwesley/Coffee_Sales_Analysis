# ☕ Coffee Sales Analysis Dashboard (Advanced Excel Project)

An end-to-end sales analysis built entirely in **Microsoft Excel**, combining data from multiple sheets, enriching it with lookup functions, and presenting it in a dynamic dashboard.

---

## 📂 Data Preparation & Enrichment

1. **Base Tables**  
   - **orders**: Contains the transactional fields  
     - Order ID, Order Date, Customer ID, Product ID, Quantity  
   - **customers**: Customer attributes  
   - **products**: Product attributes (type, roast, size, pricing, profit)

2. **Data Enrichment**  
   - Used **XLOOKUP** and **INDEX + MATCH** to pull in:  
     - Customer Name, Email, Country, Loyalty Card (from `customers`)  
     - Coffee Type, Roast Type, Size, Unit Price, Profit (from `products`)  
   - Calculated **Sales** = `Quantity × Unit Price`  
   - Standardized `Coffee Type Name` & `Roast Type Name` for clear labels

---

## 🔧 Tools & Techniques

- **Excel Functions**: XLOOKUP, INDEX/MATCH, SUMIFS  
- **Pivot Tables**: Aggregated sales by country, customer, time  
- **Charts**: Bar charts, line chart  
- **Slicers & Timeline**: Interactive filters for Roast Type, Size, Loyalty Card, and Date  
- **Conditional Formatting**: Highlighted high‐value customers and top‐selling products

---

## 📊 Dashboard Components

| Element                | What It Shows                                                    |
|------------------------|------------------------------------------------------------------|
| **Sales by Country**   | Total revenue by country                                          |
| **Top 5 Customers**    | Highest-spending customers                                        |
| **Total Sales Over Time** | Month-by-month sales trends                                      |
| **Timeline Slicer**    | Filter data by custom date ranges                                 |
| **Interactive Slicers**| Roast Type, Coffee Size, Loyalty Card status for rapid segmentation |

---

## 🎯 Key Insights

- **Geography**: United States and Ireland lead in overall sales volume.  
- **Customer Value**: Top 5 customers account for a large share of revenue—often loyalty-card holders.  
- **Product Mix**: Medium roasts (Size 1.0 kg & 2.5 kg) drive the most sales.  
- **Seasonality**: Clear monthly peaks/slumps visible—ideal for planning promotional campaigns.

---

## ✅ Outcome & Skills Demonstrated

- Built a **self-service dashboard** in Excel that business users can filter and explore.  
- Showcased proficiency in **data consolidation**, **lookup functions**, and **dynamic reporting**.  
- Gained insights that can guide inventory, marketing, and loyalty-program decisions.

---

📌 **Project by:** [Steward Wesley](https://github.com/Stewardwesley)

