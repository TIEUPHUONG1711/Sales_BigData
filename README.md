# Big Data Ecommerce Project

## Pipeline
1. Load raw CSV vào MySQL
2. Sqoop import MySQL -> Hive
3. PySpark cleaning và tạo Hive table `ecommerce_done`
4. PySpark tạo fact/dim tables: fact_sales, dim_date, dim_product, dim_customer
5. Aggregate monthly revenue: agg_monthly_revenue
6. Connect Power BI trên Windows với Hive trên VMware để tạo dashboard

## Tech Stack
- Hadoop, HDFS, Hive, Sqoop
- MySQL
- PySpark, SparkSQL
- Power BI
- Python

## File structure
- mysql/: script tạo và load MySQL
- sqoop/: script import Sqoop
- hive/: script HiveQL
- pyspark/: script PySpark xử lý dữ liệu
- powerbi/: Dashboard PBIX
- README.md: mô tả project

## Author
Nguyễn Thị Tiểu Phương | Big Data Analyst
