Here’s a polished **README section** combining both **insights** and **technologies used** from the *Retail.pdf* promotional campaign analysis. This is tailored for stakeholders, dashboard users, or collaborators reviewing your Power BI solution.

---

## 📊 Campaign Insights

This report analyzes the impact of promotional campaigns across multiple cities, stores, and product categories. It highlights performance metrics such as incremental revenue, sold units, and promotional effectiveness.

### 🔹 Key Metrics
- **Total Revenue (After Promo):** ₹436.31M  
- **Incremental Revenue:** ₹154.91M  
- **Incremental Sold Units (ISU):** 441.68K  
- **IR% (Incremental Revenue %):** 110.10%  
- **ISU% (Incremental Sold Units %):** 211.28%

### 🏪 Store Performance
- **Top Stores by IR:** STMYS-1 (Mysuru), STBLR-0 & STBLR-7 (Bengaluru), STCHE-7 (Chennai)
- **Bottom Stores by ISU:** STCBE-4 (Coimbatore), STTRV-1 (Trivandrum)

### 🎯 Promotion Effectiveness
| **Promo Type**     | **ISU %** | **IR ₹**     |
|--------------------|-----------|--------------|
| 500 Cashback       | 183.33%   | ₹91.05M      |
| BOGOF              | 639.96%   | ₹69.32M      |
| 25% OFF            | -12.99%   | ₹3.17M       |

- **BOGOF and Cashback** drove the highest volume and revenue.
- **25% OFF** underperformed, showing negative unit growth.

### 🧴 Category & Product Highlights
- **Top Categories by ISU:** Grocery & Staples, Home Appliances, Home Care
- **Top Products by IR%:**  
  - Atliq_waterproof_Immersi... (266.19%)  
  - Atliq_High_Glo_15W_LED... (262.98%)  
  - Atliq_Double_Bedsheet_set (258.27%)

---

## 🧰 Technologies & Software Used

### 🟦 Power BI
- **Purpose:** Dashboard development, data modeling, visualization
- **Features Used:**  
  - DAX for dynamic measures (IR%, ISU%)  
  - Conditional formatting (rules, field values)  
  - Slicer interactivity, drill-through, tooltips  
  - Custom visuals for bar charts, KPI cards

### 🐍 Python (via Power BI or external preprocessing)
- **Libraries:** `pandas`, `numpy`  
- **Use Cases:** Data cleaning, encoding error handling, preprocessing campaign data

### 🟨 Power Query (M Language)
- **Purpose:** ETL operations within Power BI  
- **Use Cases:** Data transformation, filtering, merging, type correction

### 🧮 DAX (Data Analysis Expressions)
- **Purpose:** Calculated columns, dynamic KPIs, context-aware logic  
- **Use Cases:** IR%, ISU%, promo segmentation, slicer-responsive visuals


---

Would you like help turning this into a collapsible info panel inside your dashboard or formatting it for Markdown, HTML, or PowerPoint documentation? I can also help you build a matching visual legend or tooltip overlay to explain the metrics interactively.
