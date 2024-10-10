# Supply-Chain-Analytics


## Overview
This data analytics initiative is centered on examining and visualizing the supply chain information of a company specializing in fashion and makeup products. The dataset employed in this project encompasses a diverse range of features related to the supply chain, including product details, sales figures, revenue, customer demographics, inventory levels, lead times, shipping information, supplier data, and more.

The project follows a workflow divided into three key stages: Extract, Transform, and Load (ETL) the data using Python; importing the processed data into Snowflake; and finally, developing a dashboard in Power BI to facilitate data visualization.

## Dataset Overview
The dataset comprises the following features related to the fashion and makeup product supply chain:

- **Product Type**: The category of the product (e.g., clothing, accessories, makeup).
- **SKU**: Stock Keeping Unit, a unique identifier for each product.
- **Price**: The price of the product.
- **Availability**: The current availability status of the product.
- **Number of Products Sold**: The number of products sold for a given period.
- **Revenue Generated**: The total revenue generated from product sales.
- **Customer Demographics**: Information about the customers, such as age, gender, location, etc.
- **Stock Levels**: The quantity of each product available in the inventory.
- **Lead Times**: Time taken for an order to be fulfilled from the supplier's end to the customer's end.
- **Order Quantities**: The number of products ordered in each transaction.
- **Shipping Times**: Time taken for shipping products to customers.
- **Shipping Carriers**: The company responsible for shipping the products.
- **Shipping Costs**: The cost incurred for shipping each product.
- **Supplier Name**: The name of the supplier providing the products.
- **Location**: Location of the supplier.
- **Production Volumes**: The volume of products manufactured.
- **Manufacturing Lead Time**: Time taken for the manufacturing process.
- **Manufacturing Costs**: The cost incurred during the manufacturing process.
- **Inspection Results**: The results of quality inspection for products.
- **Defect Rates**: The percentage of defective products.
- **Transportation Modes**: The modes of transportation used to deliver products.
- **Routes**: The transportation routes taken for delivery.
- **Costs**: Various costs associated with the supply chain process.

## Project Steps

### Step 1: Extract, Transform, and Load (ETL)
1. **Data Extraction:** The dataset will be obtained from a specified location or file format, such as a CSV or Excel file.

2. **Data Cleaning and Transformation:** Python will be used to clean the data, addressing missing values and preparing it for analysis through various transformations.

3. **Data Integration:** Data from multiple sources or files will be combined into a unified dataset to ensure consistency and completeness for analysis.

4. **Data Loading into Snowflake:** The cleaned and integrated dataset will be uploaded to the Snowflake data warehouse, enabling efficient storage and processing.

### Step 2: Data Visualization with Power BI
1. **Data Connection**: Power BI will connect to the Snowflake data warehouse to access the transformed dataset.
2. **Dashboard Creation**: A comprehensive dashboard will be created in Power BI, showcasing various supply chain metrics and KPIs. The dashboard will include interactive visualizations like charts, graphs, tables, and maps.
3. **Data Insights**: The Power BI dashboard will allow users to gain valuable insights into the supply chain process, identify trends, and make data-driven decisions to optimize operations.

## Project Structure
The project repository will have the following structure:

- |-- README.md
- |-- data/
- |-- processed/
- |   |-- processed_data.csv
- |-- raw/
- |   |--supply_chain_data.xlsx
- |-- src/
- |   |-- ETL.py
- |   |-- snowflake_utils.py
- |-- power_bi/
- |   |-- supply_chain_dashboard.pbix

## Getting Started
* Clone the repository to your local machine.

* Ensure you have Python and the required libraries installed.

* Run the ETL script (ETL_script.py) to perform the data extraction, transformation, and loading into Snowflake.

* Connect Power BI to Snowflake using the provided connection credentials (snowflake_connection_credentials.json).

* Open the Power BI file (supply_chain_dashboard.pbix) to explore the supply chain dashboard.

## Conclusion
This data analytics project showcases how ETL is applied to process and load supply chain data into Snowflake, followed by the development of an interactive, insightful dashboard in Power BI. The dashboard enables users to effectively analyze supply chain metrics and make informed decisions to optimize the efficiency of the entire supply chain process.
