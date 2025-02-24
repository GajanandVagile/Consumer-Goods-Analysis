# Consumer-Goods-Analysis
SQL-based Data Analysis Project on Consumer Goods Industry


📌 Project Overview:

This project focuses on analyzing consumer goods data to gain insights into sales trends, customer behavior, and market performance. By leveraging SQL, we extract meaningful patterns to drive data-driven decision-making.

With a well-structured relational database, this analysis helps businesses optimize marketing strategies, inventory management, and revenue forecasting.

📂 Database Schema:

The project is built on a structured relational database consisting of fact tables, dimension tables, views, stored procedures, and functions.

🗃 Tables

📌 Dimension Tables (Reference Data)

    dim_customer – Stores customer details.

    dim_product – Contains product information.

📌 Fact Tables (Transactional Data)

    fact_act_est – Actual vs. estimated sales data.
    
    fact_forecast_monthly – Monthly sales forecast.

    fact_freight_cost – Shipping and transportation costs.

    fact_gross_price – Gross price data for products.

    fact_manufacturing_cost – Cost of manufacturing goods.

    fact_post_invoice_deductions – Discounts and deductions applied after invoicing.

    fact_pre_invoice_deductions – Discounts applied before invoicing.

    fact_sales_monthly – Monthly sales performance data.

👀 Views (Precomputed Queries for Quick Insights)

    croma_gross_sales_view – Displays gross sales for the Croma market.

    gross_sales_view – Shows total gross sales.

    net_sales_view – Provides net sales after deductions.

    post_invoice_discount_view – Analyzes discounts applied after invoicing.

⚙️ Stored Procedures (Reusable SQL Logic)

    get_monthly_gross_sales_for_customer – Retrieves monthly sales for a specific customer.
  
    get_top_n_markets_by_net_sales – Identifies top-performing markets based on net sales.

    get_top_n_products_by_division_by_fy – Ranks top products within each division for a fiscal year.

    get_top_n_products_by_fiscal_year – Fetches top products by total sales per fiscal year.

    top_n_customers_by_fiscal_year – Lists the top customers for a given fiscal year.

🛠 Functions (Reusable SQL Calculations)

    get_fiscal_year – Determines the fiscal year for a given date.

🔍 **Key Business Insights & Analysis**

1️⃣ Revenue Trends & Sales Performance

  📌 Analyzing gross vs. net sales to identify revenue trends

  📌 Comparing forecasted vs. actual sales for future demand prediction

2️⃣ Market Segmentation & Regional Analysis

  📌 Identifying high-performing regions with top revenue generation

  📌 Understanding regional sales variations to optimize strategies

3️⃣ Customer Purchasing Behavior

  📌 Tracking customer spending habits to identify high-value customers

  📌 Evaluating the impact of invoice discounts on revenue

4️⃣ Product Demand Forecasting

  📌 Determining best-selling products using historical sales data

  📌 Analyzing manufacturing costs vs. sales price for profitability

🛠 **Technologies Used**

✔ SQL (MySQL) – Database management, querying, views, and stored procedures

**📩 Contact & Contribution**

For suggestions, feedback, or collaboration:

📧 Email: gajanandvaghile2003@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/gajanand-vagile-d9/
