# assignment

PART-1 MYSQL

process follwed for uploading excel file data into database
* converted the excel file to csv format for easy processing.
* created table using sql code and imported data from the file. 
* screenshots are uploaded in the folder for better undestanding.


PART-2 ELASTICSEARCH

process follwed for uploading excel file data into ES database
* created index mapping using curl before creating index for both product_listing and group_listing.
* excel file is converted into csv format and given as a input to LOGSTASH tool.
* used logstash for data ingestion and json code is used.
* mutate filter is applied for converting text into integer format 
* as result output an index is created in Elasticsearch Database which can be beautifully visualized in kibana.
* the code for all the process is uploaded in the file
