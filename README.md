# NorthWind_Traders

## Project Objective
The objective of this project is to analyze the Northwind Traders dataset, a sample database representing a fictional trading company, to generate key insights into product performance, customer purchase behavior, and inventory management. This analysis will aid stakeholders in understanding sales trends, optimizing inventory levels, and adjusting pricing strategies.

## Dataset Description
The Northwind Traders dataset contains information about:

- Customers: Customer IDs, contact information, and regions.
- Products: Product IDs, prices, stock levels, and supplier information.
- Orders: Order details, quantities, discounts, and associated products.
- Suppliers: Supplier IDs and product sourcing.
- Categories: Product categories for organizing inventory.
## Data tables:

- Orders: Contains order information.
- OrderDetails: Links orders to products and contains pricing and quantity data.
- Products: Detailed product information including pricing and stock.
- Customers: Customer contact and demographic data.
- Suppliers: Information on suppliers and their locations.
- Categories: Classification of products by category.

## Technology Stack

- SQLite: For database management and SQL queries.
- Python: For further analysis, aggregation, and visualization of SQL results.
- Pandas: For data manipulation.
- SQLAlchemy: For handling SQLite database connections.
- Jupyter Notebook: To run and showcase the analysis steps.

## Aggregations and Analyses
- Total Revenue per Product

Calculate revenue by subtracting discounts and multiplying by quantity sold.

- Sales Volume by Category

Total quantity sold per category to understand category demand.

- Inventory Turnover

Measure how quickly products are sold by comparing unitsonorder with total quantity sold.

- Discount Impact Analysis

Evaluate how discounts affect sales volumes and revenue by comparing sales with and without discounts.

- Top Supplier Analysis

Sum the total revenue generated for each supplier to identify the most valuable suppliers.
