# USImmigrationETL
End to end ETL pipeline taking data from 1994 US Immigration data using Apache Airflow and Apache Spark to pipe from Amazon S3 -> Amazon Redshift

We will be reading, parsing and cleaning the data from local file systems, Amazon S3 and transferring data to redshift tables in AWS. We will be orchestrating the flow of data through Apache Airflow DAGs.

Finally we will be using some SQL queries to extract some valuable stats and graphs from the data itself.
