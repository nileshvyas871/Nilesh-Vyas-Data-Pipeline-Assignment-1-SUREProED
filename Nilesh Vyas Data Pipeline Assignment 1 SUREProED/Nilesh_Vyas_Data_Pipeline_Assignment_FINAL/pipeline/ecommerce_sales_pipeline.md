# E-commerce Sales Data Pipeline

## Selected Source

An e-commerce sales system that produces sales/order data.

Logical Architecture
E-commerce Sales Data

Data Ingestion

Raw Data Storage

Data Processing

Analytical Storage

BI / Analytics

Technology Mapping
CSV / Excel
    
Python Ingestion
    
Cloud Storage
    
Dataflow
    
BigQuery
    
Looker Studio

Why These Components?

Python Ingestion:Reads incoming sales files and starts the data ingestion process.
Cloud Storage: Keeps the raw source files before transformation.
Dataflow: Cleans and transforms the sales data.
BigQuery:Stores processed data for analytical queries.
Looker Studio:Presents the processed data through reports and dashboards.

Example Processing

Dataflow can:

remove duplicate records
handle missing valuescorrect data types
filter invalid records
calculate derived values such as total revenue

Data Movement

The data moves from one stage to another because each stage has a different responsibility: receiving the source data, retaining the raw input, transforming it, storing the clean analytical data, and finally making the results useful to business users.


