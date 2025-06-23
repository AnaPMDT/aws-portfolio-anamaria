# Cost control and monitoring with CloudWatch

This case study is concerned with the application of governance and monitoring instruments in the AWS to make academic data processing according to such parameters as safe, audit-able, and efficient. The services offered by AWS I utilized were the S3, KMS, Glue studio, Cloudwatch and Cloud trail service to facilitate the versioning of data, encryption of data, visibility of pipeline execution and metrics monitoring as well as audit these activities. The design facilitates data integrity, accountability, cost-effective operations and goals of the academic department.

## S3 Bucket Configuration

![image](https://github.com/user-attachments/assets/ead7ccff-0b06-4a0b-b5fc-391b6db6745d)

![image](https://github.com/user-attachments/assets/c3c99aa1-b236-4931-9229-7522da339f56)

Encrypted s3 bucket: To keep academic information safe and monitor changes to files, I turned on versioning and server-side encryption to all S3 buckets (Raw, Clean, Curated zones). This provides the recoverable and confidentiality of student records.

## KMS Key Setup

![image](https://github.com/user-attachments/assets/d1941798-89f3-46b5-9286-b583c30fd635)

Encryption key was designed using a custom KMS to the sensitive datasets. The main restriction was due to academical role of laboratories as the key was limited to the activity of academic laboratory, giving a certain control of entry and adherence to data security standards.

## Visual ETL Pipeline Validation

![image](https://github.com/user-attachments/assets/0ba1a542-1084-4d51-b7de-928ee44c3ae1)

I determined the response to the ETL pipeline with the AWS Glue Studio visually applying an ETL pipeline to merge and transform retention data. This enables the non-technical stakeholders to audit the logic used.

## Governance Check (Pass/Fail)

![image](https://github.com/user-attachments/assets/cc52fb71-bd71-47fb-9e20-83c9c1f02e55)
![image](https://github.com/user-attachments/assets/81baea69-b80e-4f85-a280-c30dc0be1583)

AWS tools guided the verification that the ETL pipeline successfully completed governance validation, which implies that all the resources utilized are secure, documented, and are compliant with standards.

## CloudTrail Setup

![image](https://github.com/user-attachments/assets/8eb59cba-1375-4841-88f2-604914a06ac5)

I configured CloudTrail to log all activities related to S3 and Glue. This creates a traceable log of operations, which supports accountability and helps in identifying anomalies or misconfigurations.

## CloudWatch Dashboard

![image](https://github.com/user-attachments/assets/f2936cf4-2a4a-497f-8153-ec4e06d2638a)

I wrote some CloudWatch dashboard to check on the size of S3 bucket and the time it takes a job in Glue. These indicators give the academic team the ability to predict current storage increase and job backlog before it can occur, which will make resources planning much more effective.


