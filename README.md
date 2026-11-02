# Supply Chain & Logistics Analytics Dashboard (Power BI)

An interactive Power BI dashboard analyzing end-to-end supply chain operations, including sales, supplier performance, inventory, shipments, and production quality. Uses Power Query for data transformation and DAX for KPI calculations to generate actionable insights and support data-driven decisions.

---

## Dashboard Preview

### 1. Home
Landing page with navigation to every section of the report.

<img width="1473" height="815" alt="image" src="https://github.com/user-attachments/assets/7166457c-a1f5-46ec-ba63-d9d955fa564c" />




### 2. Overview
Executive summary of revenue, profit, profit margin %, perfect order %, shipments, inventory value, defect rate, and delivery delays, with top suppliers, products, carriers, and customers.

<img width="1472" height="812" alt="image" src="https://github.com/user-attachments/assets/3555b084-c6a1-4ffb-a08e-12e905891b55" />





### 3. Supplier
Supplier performance: average lead time, quality score, unit cost, and order quantity by supplier and country, plus a monthly cost trend.

<img width="1475" height="817" alt="image" src="https://github.com/user-attachments/assets/0d5c4870-5abb-48fc-aa7d-7a3f03670c15" />





### 4. Inventory
Inventory health: inventory value, safety stock vs reorder point, turnover rate, days of inventory, defect rate by product, and defective units over time.

<img width="1468" height="820" alt="image" src="https://github.com/user-attachments/assets/344db71e-a851-4752-8499-1a679bd2c17c" />





### 5. Shipment
Delivery performance: delivered % and delays by carrier, delay reasons, shipment status, and monthly shipment cost.

<img width="1480" height="820" alt="image" src="https://github.com/user-attachments/assets/47abb862-2bf4-48b8-acbc-0a6f945761a3" />





### 6. Customer
Sales and profitability: revenue, profit and growth trends, top customers, discount impact on revenue, and revenue split by sales channel.

<img width="1466" height="816" alt="image" src="https://github.com/user-attachments/assets/056d383b-6c22-40bc-9c07-a00fcf63606a" />





---

## Key Metrics

| Area | KPIs |
|------|------|
| **Sales** | Gross Revenue, Total Revenue, Profit, Profit Margin %, Growth Revenue, Discount %, Discount Amount |
| **Supplier** | Avg Lead Time, Avg Quality Score, Avg Unit Cost, Total Unit Cost, Order Quantity |
| **Inventory** | Inventory Value, Safety Stock, Reorder Point, Turnover Rate, Days of Inventory |
| **Shipment** | Total Shipment, Delivered %, Total Delay, Shipment Cost, Delivered Quantity |
| **Quality** | Defect Rate, Defective Units, Perfect Order % |

---

## Visuals Used

KPI cards, donut charts, clustered bar and column charts, line charts, combo charts (line + column), scatter plot, slicers, and a page navigator with navigation buttons.

---

## Tools & Techniques

- **Power BI Desktop**: report design and visualization
- **Power Query**: data cleaning and transformation
- **DAX**: KPI and measure calculations
- **Data Modeling**: relationships across supplier, product, customer, and shipment tables

---

## Repository Structure

```
├── logistic_project.pbix     # Power BI report
└── README.md
```

---

## How to Use

1. Clone or download this repository
2. Open `logistic_project.pbix` in **Power BI Desktop**
3. Use the page navigator, buttons, and slicers to explore each section

---

## Business Insights Supported

- Identify suppliers with long lead times or low quality scores
- Spot products with high defect rates or stock below the reorder point
- Find carriers and delay reasons causing late deliveries
- See which customers, channels, and discount levels drive revenue and profit

---

## Author

**Mohammed Owais Ahmed**
Computer Science and Engineering student | Aspiring Data Analyst
