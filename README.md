# Big Data Homework: Level 1
## Background
In this assignment you will put your ETL skills to the test. Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average local computer. Your first goal for this assignment will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal will be to use PySpark or SQL to perform a statistical analysis of selected data.

There are two levels to this homework assignment. The second level is optional, so only the first level was completed.
* Create DataFrames to match production-ready tables from two big Amazon customer review datasets.
* Analyze whether reviews from Amazon's Vine program are trustworthy.
## Instructions
### Level 1
* Use the furnished schema to create tables in your RDS database.
* Create two separate Google Colab notebooks and extract any two datasets from the list at review dataset, one into each notebook.
* Be sure to handle the header correctly. If you read the file without the header parameter, you may find that the column headers are included in the table rows.
* For each notebook (one dataset per notebook), complete the following:
* Count the number of records (rows) in the dataset.
* Transform the dataset to fit the tables in the schema file. Be sure the DataFrames match in data type and in column name.
* Load the DataFrames that correspond to tables into an RDS instance. Note: This process can take up to 10 minutes for each. Be sure that everything is correct before uploading.
### Shoes csv uploaded as an example (other files were too big to upload)
