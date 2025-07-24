# 🛒 Ecommerce Return Risk Project

This project analyzes sales, profit, and return risk data from an e-commerce dataset. It aims to uncover insights that help minimize product return rates and increase profitability.


## 📁 Project Structure

| File Name                      | Description |
|-------------------------------|-------------|
| A-Project-BI.pbix           | Power BI dashboard file with all visualizations and KPIs |
| Final_Ecommerce_Sales_Data2.csv | The main dataset used for analysis |
| Project-sql.txt             | Contains SQL queries used for data exploration |
| README.md                   | Project documentation |
| A-Project-ss1.png to A-Project-ss6.png | Screenshots of different sql dashboard views |
| final-project-ss.png        | Combined view of final bi dashboard |



## 🧠 Objectives

- Identify return risk patterns based on discounts, segments, and regions
- Analyze top-performing products by sales and profit
- Detect products with high discount but negative profit
- Understand the monthly sales trends
- Summarize orders and profit by region, category, and customer segment



## 🗃 Dataset Overview

- *Records:* 10,000+ order-level rows
- *Columns Include:*
  - Order ID, Order Date, Ship Date
  - Product Name, Category, Sub-Category
  - Sales, Quantity, Discount, Profit
  - Customer Info (ID, Name, Segment)
  - Shipping Info, Region, Return Risk



## 🛠 Tools Used

- *Power BI* – For dashboard design and visualization
- *SQL* – For data extraction, transformation and pattern detection
- *GitHub* – For version control and project sharing



## 📊 Dashboard Highlights

- ✅ Total Sales, Profit, Order Count, Loss Orders as KPIs
- 📈 Monthly sales trends (2011–2014)
- 🧾 Top 5 products by sales
- 🧭 Profit analysis by region and return risk
- 🚩 High discount + negative profit product detection
- 🗂 Filters: Year, Region, Segment, Category



## 🧐 Key Insights
  
- 📉 *Products with more than 0.3% discount* tend to produce *negative profit*, indicating poor pricing strategies and higher return risk.

- 📊 Among segments:
  - *Consumer segment* generates the highest sales and profit but also has higher return risks.
  - *Corporate segment* performs steadily with moderate profit and lower returns.

- 🌍 *West region* contributes the *highest profit (~108K)* among all regions, followed by Central and South.

- 📅 *Sales trend* shows consistent growth with seasonal spikes around *September to December*, indicating high performance in Q3 & Q4.

- 💸 *Total Loss* from return-prone or discounted items is significant (~156K), and 1,871 orders have resulted in loss.

- 🧾 *Return Risk* is highly correlated with *discount rate. When discount crosses **25%*, average profit starts decreasing sharply and risk increases.

- 📈 *2014* was the *best performing year* in both sales and profit, showing strong year-on-year growth.

- 🔁 *High shipment delays* (not shown in dashboard but inferred from SQL) may also contribute to returns — further investigation can be done.

- 📦 More than *9,994 orders* were processed in total, showing a large and rich dataset for analysis.

  


## 👤 Author

- *Sattwik Roy*
- 🔗 GitHub: [sattwik001](https://github.com/sattwik001)

---

## 📌 License

This project is open for educational and portfolio purposes. Feel free to fork and enhance!
