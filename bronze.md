# Building the Bronze Layer

intro

![Medallion architecture layers](/images/medallion.png)

## Creating our starting point 

- Decide which data we need
- Create a notebook to read raw data from sources
- Apply minor clean-ups
- Save as tables

## Deciding on data
advice

## Ingestion
intro

### From a file 
Upload file
DBFS
read csv or other format
autoloader
schema inference
manual schema

### From a table
grant permissions
Use CRAS to remove unnecessary columns

## Minor clean-ups
constraints
null checks
custom validation functions

## Saving to tables
Alias columns
remove columns we don;t need

save out dataframe as delta table

# Next
[Building the silver layer](/silver.md)

[Back to Contents](/contents.md)
