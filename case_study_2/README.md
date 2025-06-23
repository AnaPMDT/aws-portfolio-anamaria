
Cloud deployment models
This case study pits the three major models of cloud deployment: Public Cloud, Private Cloud and Hybrid Cloud against each other and considers an example of how to use it in an academic department. The objective is to come up with the most appropriate model which can be used in storing and analysis of student retention and demography data. In the analysis some of the important features which are considered are data sensitivity, privacy levels, cost, flexibility and scalability. The last recommendation will concern the choice of the model that will help to ensure not only secure data management but good academic analytics.
 
Deployment Models Comparison

## Deployment Models Comparison

| Deployment Model | Description | Application to Academic Department | Pros | Cons |
|------------------|-------------|------------------------------------|------|------|
| **Public Cloud** | The resources are shared among the users and run on facilities that are hosted by a third-party provider (e.g., AWS). | AWS S3 can store the demographic data of students and non-sensitive retention data as well as analyze it using AWS Glue, Athena, and DataBrew. | - Low-cost  <br> - Elastic <br> - No need to maintain infrastructure <br> - Easy to combine with AWS analytics tools | - Multiple user access settings <br> - Little control <br> - More risks of privacy for sensitive data |
| **Private Cloud** | Cloud systems used exclusively by one organization, hosted either in its own data center or privately in the cloud. | University IT staff can handle sensitive retention records (e.g., academic performance or dropout reasons) using internal servers. | - Complete security control <br> - Custom compliance <br> - Appropriate for confidential info | - Costly to maintain <br> - Harder to scale <br> - Slower to implement |
| **Hybrid Cloud** | Integration of government and business cloud technology collaborating with each other. | Demographic data compliant with SaaS is hosted on public cloud and analyzed. Localized sensitive retention data remains on-site and is accessed with restrictions using private cloud. | - Cost-balanced and controlled <br> - Adaptable and expandable <br> - Sensitive info stays protected <br> - Allows high-level analytics | - Complex integration <br> - Requires strong governance <br> - More effort to set up/manage |

The Hybrid Cloud model is the most suitable choice of the academic department. It enables the institution to utilize AWS scalable analytics programs, to analyze non-sensitive demographic information, whereas the sensitive academic information is stored in a closed network. This is a Trade-off in terms of privacy of data, its flexibility, and cost-effectiveness, which makes this deployment model a perfect fit in the case of student retention analytics. It also aids in the adherence to the academic data governance policies and delivers strategic decision-making via cloud-based insights.

![image](https://github.com/user-attachments/assets/40becedc-9894-4f5c-97e0-7f15c502ddca)
