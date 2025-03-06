# Data-Engineer-Projects
Create End to End Data Engineering Projects 

S3 Staging ---> Glue ETL ---> S3 DW -----> Crawler ----> Athena ----> Quicksight

Using AWS cloud move data from one source to another target
source is file.
target is table.
S3 Staging is our input.
S3 Dataware house is our target.
using AWS s3 we are storing data and for transfering data using AWS GLUE.
basically AWS S3 store both input and output data.
using AWS GLUE we are create job design and applly require transformation logics and transfer the data.
Crawler basically it does create table,database and tranfer output data into table format.
Using AWS Athena we can find our table and data base.
Using AWS Quicksight we can see the graphs.
