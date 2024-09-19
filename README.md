# AWS Data Analytic Platform for The City of Vancouver

## Implementation and Analysis of 3-1-1 Inquiry Volumes Using AWS

### Introduction
The City of Vancouver has migrated its data processing to Amazon Web Services (AWS) to optimize the speed and quality of data analysis for better decision-making. The 3-1-1 inquiry system is a crucial public service that allows citizens to report issues, ask questions, and request services from various city departments. This project establishes a Data Analytics Platform (DAP) on AWS for sourcing, storing, processing, and analyzing 3-1-1 inquiry volumes to improve resource allocation and service delivery.

---
# [AWS-1 Project 1](https://hemanth410792.github.io/projectpart1/)

# Project 1

## Project Title: AWS Data Analytic Platform for the City of Vancouver - Part 1

### Project Description:
The City of Vancouver requires a data platform to manage and analyze the volume and types of inquiries received via its 3-1-1 service, including requests related to public works, permits, and services. This project will leverage Amazon Web Services (AWS) to design and implement a Data Analytics Platform (DAP) that can store, process, and analyze data to improve the city's response to citizen inquiries, streamline services, and provide insights into public service needs and safety permits, especially for water systems.

### Project Objective:
To design and implement a Data Analytics Platform (DAP) using AWS to manage the 3-1-1 inquiry data, with a focus on analyzing the types of inquiries related to safety-issued operating permits and water systems (e.g., cooling towers, water features).

### Methodology:
The design and implementation process includes the following steps:

1. **Data Analytical Question Formulation:** Identify key questions regarding the volume and types of 3-1-1 inquiries related to public health and safety permits.
   
2. **Data Discovery:** Explore the 3-1-1 inquiry dataset, focusing on specific inquiry types, departments, and service channels.
   
3. **Storage Design:** Plan and implement storage solutions using AWS S3 or similar services to securely store the inquiry data.
   
4. **Data Preparation:** Prepare the dataset for analysis, ensuring it is clean and relevant for answering key questions.
   
5. **Data Injection:** Automate the process of injecting updated 3-1-1 inquiry data into the storage platform using AWS services such as Kinesis or Lambda.

6. **Data Pipeline Design:** Design a data pipeline to ensure efficient data flow from ingestion to analysis, leveraging AWS Glue and other relevant services.

7. **Data Cleaning:** Process and clean the 3-1-1 data, filtering relevant fields such as inquiry type, department, and channel.

8. **Data Structuring:** Structure the cleaned data into an analytics-friendly format, using AWS Redshift or similar solutions for structured storage.

9. **Data Pipeline Implementation:** Implement the data pipeline in AWS, ensuring scalability and efficiency.

10. **Data Analysis:** Analyze inquiry patterns, focusing on water system permits and public safety concerns to improve service response times.

11. **Data Visualization:** Use AWS QuickSight to visualize inquiry volumes and trends, allowing stakeholders to track performance metrics.

12. **Data Publishing:** Publish the analysis reports and visualizations to internal stakeholders to inform decision-making processes.




# [AWS-1 Project 1](https://hemanth410792.github.io/Projectpart-2/) 
  
### Screenshots and Visuals
Several screenshots were captured to visualize key configurations:
- **S3 Bucket Management and Replication Rules**: Demonstrates the lifecycle management and replication configurations used for redundancy and disaster recovery.
- **CloudTrail Logging and Governance**: Shows how CloudTrail was configured to log API requests and track changes across all AWS services involved in the project.
- **CloudWatch Dashboard**: Highlights critical metrics, including estimated charges and bucket size, for real-time system monitoring and cost management.

### Summary of Insights
The governance and monitoring components of this project provided several key insights:
- **Security and Data Integrity**: Data security was maintained using AWS's advanced security features, ensuring the integrity and confidentiality of the data.
- **Proactive Monitoring**: Real-time insights into system performance and costs enabled proactive management of resources, reducing the risk of unexpected cost overruns or system failures.
- **Data Governance Compliance**: Comprehensive tracking of all activities and changes in the system ensured that governance and compliance requirements were met without compromising operational efficiency.

### Conclusion
The governance, protection, and monitoring setup for the AWS Data Analytic Platform ensured that the City of Vancouver could safely and securely manage its 3-1-1 inquiry data while maintaining compliance with all necessary security and governance standards. The proactive monitoring using CloudWatch and the comprehensive logging through CloudTrail allowed stakeholders to maintain control over both the security and performance of the system, ensuring sustainable and efficient data processing for future use.






