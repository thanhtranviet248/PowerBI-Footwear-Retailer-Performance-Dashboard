
# Footwear Retailer Sales & Inventory Dashboard

This project is a comprehensive process from getting the raw data to the cleaning, processing and visualizing steps
in order to bring both of the general and the detail analysis views of sales and inventory performance to decision makers.

Link to the dashboard: https://app.powerbi.com/view?r=eyJrIjoiNjVhNTMxMjAtNTVlYy00M2E0LTg1ZmMtMWVlMmMxMmU4ZmY2IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

## Tools used

1 - Google Cloud

    1.1 - Cloud Storage (data warehouse):

    - Master data: DistributionChannel.csv (distribution channel information), Master_Calendar.csv (timeframe information), Product.arvo (product features information), SLOC (inventory features information)
    - Transactional data: Sales.arvo (sales data), Inventory.arvo (inventory data)

    1.2 - BigQuery (ETL):

    - The data tables are retrieved into BigQuery for initial data cleaning

2 - Power Query and Power BI

    - After the inital cleaning step, the data are loaded into Power Query to recheck if any error and missing point exists
    - Finally the data model is setup between tables and dashboard is built
