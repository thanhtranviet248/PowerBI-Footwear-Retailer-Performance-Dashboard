
## Tools used

1 - Google Cloud

    1.1 - Cloud Storage (data warehouse):

    - Master data: DistributionChannel.csv (distribution channel information), Master_Calendar.csv (timeframe information), Product.arvo (product features information), SLOC (inventory features information)
    - Transactional data: Sales.arvo (sales data) and Inventory.arvo (inventory data)

    1.2 - BigQuery (ETL):

    - The data tables then are retrieved into BigQuery in order to perform initial data cleaning

2 - Power BI

    - After the inital cleaning step, the data are loaded into Power Query to recheck if any error/missing point exists and perform the second cleaning.
    - Finally the data model is setup between tables and dashboard is built
