Cost control and monitoring with CloudWatch
This case study is concerned with the application of governance and monitoring instruments in the AWS to make academic data processing according to such parameters as safe, audit-able, and efficient. The services offered by AWS I utilized were the S3, KMS, Glue studio, Cloudwatch and Cloud trail service to facilitate the versioning of data, encryption of data, visibility of pipeline execution and metrics monitoring as well as audit these activities. The design facilitates data integrity, accountability, cost-effective operations and goals of the academic department.

S3 Bucket Configuration

![image](https://github.com/user-attachments/assets/ead7ccff-0b06-4a0b-b5fc-391b6db6745d)

![image](https://github.com/user-attachments/assets/c3c99aa1-b236-4931-9229-7522da339f56)



Encrypted s3 bucket: To keep academic information safe and monitor changes to files, I turned on versioning and server-side encryption to all S3 buckets (Raw, Clean, Curated zones). This provides the recoverable and confidentiality of student records.

KMS Key Setup

![image](https://github.com/user-attachments/assets/d1941798-89f3-46b5-9286-b583c30fd635)

Encryption key was designed using a custom KMS to the sensitive datasets. The main restriction was due to academical role of laboratories as the key was limited to the activity of academic laboratory, giving a certain control of entry and adherence to data security standards.

Visual ETL Pipeline Validation

![image](https://github.com/user-attachments/assets/0ba1a542-1084-4d51-b7de-928ee44c3ae1)








