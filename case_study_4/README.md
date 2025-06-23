# Support Plans & Cost Estimation

My tasks in this case study were to estimate the cost of operations of using Amazon Athena to read SQL queries against curated datasets that resided in Amazon S3. The curated zone has been already constructed on AWS Glue DataBrew and ETL jobs and cataloged on Glue Crawlers. I was the Analyst in the Academic Department where I had to perform the querying daily based on gender retention analysis utilizing structured data through Athena. Since my project scope, I calculated 20 queries per day, in which each query runs about 2 GB of data. I did also set the capacity-based pricing with 24 DPU and the average of estimated 8 hours per month of a scheduled usage of queries. This setup had an option of Spark session part that could be added in the event of more sophisticated transformations. These expenses were assessed with the help of AWS Pricing Calculator and captured in the form of screenshots as a part of the financial planning and optimization strategy of the data analytics infrastructure.


![image](https://github.com/user-attachments/assets/0bd77b82-ee34-42ba-94b9-db46b6e2f98c)

Datasets were stored in three zones namely, raw, clean, and curated via Amazon S3 storage. The costs of storing data were estimated based on monthly volume of data that may increase and versioning of data to be able to trace data and rollback the data.


![image](https://github.com/user-attachments/assets/f82a0f4f-dd37-42aa-9d45-9e27fbf11f7d)

Glue DataBrew was utilized for data cleaning and transformation of the retention and demographics datasets. Cost estimation included project, job runs, and the number of rows processed, based on actual lab activity.

![image](https://github.com/user-attachments/assets/fac496ed-a3ad-4730-9b51-eb570813da69)

Glue DataBrew was utilized for data cleaning and transformation of the retention and demographics datasets. Cost estimation included project, job runs, and the number of rows processed, based on actual lab activity.
AWS Glue was used to clean, transform, and join the StudentDemographics and RetentionRecords datasets. I applied DataBrew for data preparation, Crawlers to update the Data Catalog, and Glue Studio to create an ETL pipeline. All steps supported the retention analysis and were included in the cost estimation.

![image](https://github.com/user-attachments/assets/9874ae7e-3ef6-4f84-ad5e-10a2ce55de59)





