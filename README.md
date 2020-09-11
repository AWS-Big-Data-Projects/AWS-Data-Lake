# AWS-Data-Lake

 AWS Lake Formation makes it easy for you to set up, secure, and manage your data lakes also  data discovery using the metadata search capabilities of Lake Formation in the console, and metadata search results restricted by column permissions.


![image](https://user-images.githubusercontent.com/48589838/77393674-8e335300-6dc3-11ea-9857-8c44eae11188.png)



![image](https://user-images.githubusercontent.com/48589838/77393709-a60ad700-6dc3-11ea-80c3-aeca60ee7d45.png)



![image](https://user-images.githubusercontent.com/48589838/77393859-f7b36180-6dc3-11ea-9542-b2b58b5515a7.png)



## Steps

### Create the data lake

In the AWS Lake Formation console, in the left navigation pane, choose Register and ingest, Data lake locations. Select a single S3 bucket to house several independent data sources in your data lake.

### Add data to your data lake
Now that you have an S3 bucket configured as a storage resource for Lake Formation, you must add data to your data lake. You can add data to your data lake’s S3 bucket storage resource using AWS SDKs, AWS CLI, the S3 console, or a Lake Formation blueprint.

With Lake Formation, you can discover and set up the ingestion of your source data. When you add a workflow that loads or updates the data lake, you can choose a blueprint or template of the type of importer to add. Lake Formation provides several blueprints on the Lake Formation console for common source data types to simplify the creation of workflows. Workflows point to your data source and target and specify the frequency that they run.

### Sample Datasets are provided as follows

New York City Taxi and Limousine Commission (TLC) Trip Record Data
Amazon Customer Reviews

### Add Amazon customer reviews to your data lake

### Add New York taxi ride history to your data lake

### Create catalog databases

 define three logical databases:

o  amazon-reviews-prod

o  amazon-reviews-test

o  ny-taxi

### Add tables from S3 to your catalog databases

### Metadata search in the console

Search by classification
Search by keyword
Search by tag: attribute
Multiple filter searches
Metadata search results restricted by column permissions

###### reference material:https://aws.amazon.com/blogs/big-data/discovering-metadata-with-aws-lake-formation-part-1/
###### https://aws.amazon.com/blogs/big-data/discover-metadata-with-aws-lake-formation-part-2/

