
# Footwear Retailer Sales & Inventory Dashboard

This project is a full process from getting the raw data to the cleaning, processing and visualizing steps in order to bring the general performance and the detail analysis views of sales and inventory to decision makers.

Link to the dashboard: https://app.powerbi.com/view?r=eyJrIjoiOGQzM2NkYTYtOGJlNS00YTU0LTk4YjMtOTg3ZTRjYTEyM2NmIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

## Tools used

1 - Google Cloud

    1.1 - Cloud Storage (data warehouse):

    - Master data: DistributionChannel.csv (distribution channel information), Master_Calendar.csv (timeframe information), Product.arvo (product features information)
    - Transactional data: Sales.arvo (sales data), Inventory.arvo (inventory data)

    1.2 - BigQuery (ETL):

    - The data tables are retrieved into BigQuery for initial data cleaning (check N/A, null, missing, etc.)

2 - Power Query and Power BI

    - After the inital cleaning step, the data are loaded into Power Query to recheck if any errors and missing points still exist
    - Finally the data model is setup between tables and dashboard is built
