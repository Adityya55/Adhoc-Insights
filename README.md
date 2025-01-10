# Adhoc-Insights
🌟Business Scenario: The top executives of AtliQ Hardware (an imaginary hardware manufacturing company from India) want some quick insights to make data-informed decisions. We have 10 ad-hoc requests which we need to execute.

🌟 Database: We have a SQL database named 'gdb023' (atliq_hardware_db) database with ~1 million sales records. It includes six tables:

dim_customer: contains customer-related data
dim_product: contains product-related data
fact_gross_price: contains gross price information for each product
fact_manufacturing_cost: contains the cost incurred in the production of each product
fact_pre_invoice_deductions: contains pre-invoice deductions information for each product
fact_sales_monthly: contains monthly sales data for each product.

Database schema:
