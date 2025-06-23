Dataset Retention Records and Student Demographics
Introduction
It is the case study of how the Retention Records & Student Demographics dataset can be handled both on-premises and in the cloud. It outlines the way of the main distinctions of data location, access controlling and privacy. This data contains sensitive student data as regards retention rates, academic performances, demographic background and program enrolment.
| **Aspect**   | **Traditional Environment**                                                                                         | **AWS Cloud Environment**                                                                                                                                                            |
|--------------|---------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Location** | The university stores information in servers located on physical servers under the IT department in the university. In most cases on-premises or local. | The data is stored in an Amazon S3 team in the US East (N. Virginia). These types of records are contained in folders divided by type: `RetentionRecords/`, `StudentDemographics/`. |
| **Access**   | Only the staff were allowed to access it over campus network or VPN; only limited user tracking.                    | The access is also controlled with a security notch using IAM Role (`labrole`), with the authorised AWS services such as Glue, SageMaker, and Athena accessing the information.      |
| **Privacy**  | May not be encrypted, and little audit logs; an increased likelihood of insider attacks.                            | As a measure of data security, the information is encrypted both at rest and in transit, tracked using CloudTrail, and safeguarded by AWS KMS. IAM policies provide fine-grained access control. |

AWS Knowledge Check

