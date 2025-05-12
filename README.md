# AWS_Certified_Cloud_Practitioner



# AWS Certified Cloud Practitioner - Questions and Answers

This document collects a series of AWS Certified Cloud Practitioner–style questions, the available choices, and the correct answers.

1. **Continuous monitoring of AWS accounts and workloads**

   * **Question:** A company wants to continuously monitor its AWS accounts and workloads for malicious activity. The company also wants to receive detailed security findings for visibility and remediation. Which AWS service should the company use to meet these requirements?
   * **Choices:**

     * A. Amazon GuardDuty
     * B. AWS Shield
     * C. AWS WAF
     * D. AWS CloudTrail
   * **Answer:** A. Amazon GuardDuty

2. **DDoS protection with service credits**

   * **Question:** A company is running an application on AWS. The company wants to protect the application’s resources from DDoS attacks. The company also wants to receive a service credit if a DDoS attack increases the utilization of AWS resources. Which AWS solution will meet these requirements?
   * **Choices:**

     * A. Amazon GuardDuty
     * B. AWS Shield Advanced
     * C. AWS Shield Standard
     * D. AWS WAF
   * **Answer:** B. AWS Shield Advanced

3. **Logging IP connections to EC2 instances**

   * **Question:** A company is deploying a set of Amazon EC2 instances into a VPC. The company needs to create a list of IP addresses that try to connect to the EC2 instances. Which AWS service or feature will provide this information?
   * **Choices:**

     * A. AWS CloudTrail logs
     * B. Amazon CloudWatch metrics
     * C. AWS Config
     * D. VPC Flow Logs
   * **Answer:** D. VPC Flow Logs

4. **Hybrid low-latency file storage for Windows**

   * **Question:** A company needs hybrid AWS Cloud storage for Windows users. The storage must provide low-latency performance for frequently accessed data. Which AWS service will meet these requirements?
   * **Choices:**

     * A. Amazon FSx File Gateway
     * B. Amazon Elastic File System (EFS)
     * C. Amazon S3
     * D. Amazon Elastic Block Store (EBS)
   * **Answer:** A. Amazon FSx File Gateway

5. **Encrypted connection over the public internet**

   * **Question:** A company needs a secure, encrypted connection between its data center workload and the AWS Cloud. The connection needs to use the public internet. Which AWS service will meet these requirements?
   * **Choices:**

     * A. AWS Direct Connect
     * B. Amazon Connect
     * C. AWS Site-to-Site VPN
     * D. AWS Client VPN
   * **Answer:** C. AWS Site-to-Site VPN

6. **Identifying which business unit uses resources**

   * **Question:** Which AWS service or feature can a company use to determine which business unit is using specific AWS resources?
   * **Choices:**

     * A. Cost allocation tags
     * B. Key pairs
     * C. Amazon Inspector
     * D. AWS Trusted Advisor
   * **Answer:** A. Cost allocation tags

7. **Well‑Architected Framework pillar for resilience**

   * **Question:** A company wants to set up its workload to retain data with periodic backups and recover quickly from failure. Which pillar of the AWS Well‑Architected Framework aligns with these goals?
   * **Choices:**

     * A. Performance efficiency
     * B. Sustainability
     * C. Reliability
     * D. Security
   * **Answer:** C. Reliability

8. **Full set of Trusted Advisor best practice checks**

   * **Question:** Which AWS support plan is required to obtain the full set of AWS Trusted Advisor best practice checks?
   * **Choices:**

     * A. AWS Developer Support
     * B. AWS Business Support
     * C. AWS Enterprise On-Ramp Support
     * D. AWS Enterprise Support
   * **Answer:** D. AWS Enterprise Support

9. **Automated vulnerability management**

   * **Question:** A company needs an automated vulnerability management service that continually scans AWS workloads for software vulnerabilities. Which AWS service will meet these requirements?
   * **Choices:**

     * A. Amazon GuardDuty
     * B. Amazon Inspector
     * C. AWS Security Hub
     * D. AWS Shield
   * **Answer:** B. Amazon Inspector

10. **Serverless data integration service**

    * **Question:** A company needs a serverless data integration service to discover, prepare, and combine data for analytics. Which AWS service will meet these requirements?
    * **Choices:**

      * A. Amazon EMR
      * B. Amazon Redshift
      * C. AWS Glue
      * D. AWS Step Functions
    * **Answer:** C. AWS Glue

11. **Collecting performance metrics**

    * **Question:** A company needs to collect performance metrics about Amazon RDS instances and Amazon EC2 instances. Which AWS service will meet this requirement?
    * **Choices:**

      * A. AWS CloudTrail
      * B. Amazon CloudWatch
      * C. Amazon Inspector
      * D. AWS Config
    * **Answer:** B. Amazon CloudWatch

12. **Shared responsibility for DynamoDB**

    * **Question:** Which option is a customer responsibility when using Amazon DynamoDB under the AWS Shared Responsibility Model?
    * **Choices:**

      * A. Physical security of DynamoDB
      * B. Patching of DynamoDB
      * C. Access to DynamoDB tables
      * D. Encryption of data at rest in DynamoDB
    * **Answer:** C. Access to DynamoDB tables

13. **Network ACL features (Select TWO)**

    * **Question:** Which of the following are features of network ACLs as they are used in the AWS Cloud? (Select TWO.)
    * **Choices:**

      * A. They are stateless.
      * B. They are stateful.
      * C. They evaluate all rules before allowing traffic.
      * D. They process rules in order, starting with the lowest numbered rule, when deciding whether to allow traffic.
      * E. They operate at the instance level.
    * **Answer:** A. They are stateless.
      D. They process rules in order, starting with the lowest numbered rule.

14. **Temporary credentials for IAM/federated users**

    * **Question:** A company needs to request temporary, limited‑privilege credentials for IAM users and for the federated users that the company authenticates. Which AWS service will provide these credentials?
    * **Choices:**

      * A. Amazon GuardDuty
      * B. AWS Key Management Service (KMS)
      * C. AWS Security Token Service (STS)
      * D. AWS Identity and Access Management Access Analyzer
    * **Answer:** C. AWS Security Token Service (STS)

15. **Detailed cost tracking by department**

    * **Question:** A company needs to organize its resources and track AWS costs on a detailed level. The company needs to categorize costs by business department, environment, and application. Which solution will meet these requirements?
    * **Choices:**

      * A. Access the AWS Cost Management console to organize resources, set an AWS Budget, and receive notifications of unintentional usage.
      * B. Use tags to organize the resources. Activate cost allocation tags to track AWS costs on a detailed level.
      * C. Create Amazon CloudWatch dashboards to visually organize and track costs individually.
      * D. Access the AWS Billing and Cost Management dashboard to organize and track resource consumption on a detailed level.
    * **Answer:** B. Use tags and cost allocation tags

16. **Blocking SQL injection and XSS**

    * **Question:** A company wants to control the protection of its AWS resources. The company wants to block SQL injection attacks and cross‑site scripting. Which AWS service or feature will meet these requirements?
    * **Choices:**

      * A. Amazon GuardDuty
      * B. AWS WAF
      * C. Security groups
      * D. AWS Shield
    * **Answer:** B. AWS WAF

17. **Managing increasing call volume**

    * **Question:** A company’s application is gaining popularity. The company needs to set up a phone number to manage the increasing volume of calls that the company’s support staff receives. Which AWS service should the company use?
    * **Choices:**

      * A. Amazon Connect
      * B. Amazon CloudFront
      * C. AWS Direct Connect
      * D. AWS Trusted Advisor
    * **Answer:** A. Amazon Connect

18. **On‑premises server and application inventory**

    * **Question:** A company needs to collect and assess on‑premises server and application inventory data before moving its infrastructure to AWS. Which AWS service provides this functionality?
    * **Choices:**

      * A. Amazon AppFlow
      * B. AWS Migration Hub
      * C. Amazon QuickSight
      * D. AWS Step Functions
    * **Answer:** B. AWS Migration Hub (via Application Discovery)

19. **Transferring on‑premises data (Select TWO)**

    * **Question:** Which AWS services can a company use to transfer on‑premises data to the AWS Cloud? (Select TWO.)
    * **Choices:**

      * A. AWS Snowcone
      * B. AWS Transit Gateway
      * C. AWS DataSync
      * D. AWS Backup
      * E. Amazon Connect
    * **Answer:** A. AWS Snowcone
      C. AWS DataSync

20. **Text‑to‑speech service**

    * **Question:** Which AWS service will turn text into lifelike speech?
    * **Choices:**

      * A. Amazon Polly
      * B. Amazon Rekognition
      * C. Amazon Connect
      * D. Amazon Kendra
    * **Answer:** A. Amazon Polly

21. **15‑minute critical response support plan**

    * **Question:** A company runs critical workloads on AWS. The company needs a response from AWS technical support within 15 minutes if a critical system goes down. Which AWS Support plan offers this response time?
    * **Choices:**

      * A. AWS Basic Support
      * B. AWS Business Support
      * C. AWS Enterprise Support
      * D. AWS Developer Support
    * **Answer:** C. AWS Enterprise Support

22. **Workforce transformation perspective**

    * **Question:** A company wants to transform its workforce by attracting and developing a digitally fluent, high‑performance workforce. The company wants to attract a diverse and inclusive workforce with an appropriate mix of technical and non‑technical skills. Which AWS Cloud Adoption Framework (CAF) perspective aligns with these goals?
    * **Choices:**

      * A. Business
      * B. People
      * C. Platform
      * D. Operations
    * **Answer:** B. People

23. **Cost‑effective multi‑AZ infrequently accessed file storage**

    * **Question:** A company needs to store data across multiple Availability Zones in an AWS Region. The data will not be accessed regularly but must be immediately retrievable. Which Amazon EFS storage class meets these requirements most cost‑effectively?
    * **Choices:**

      * A. EFS Standard
      * B. EFS Standard‑Infrequent Access (Standard‑IA)
      * C. EFS One Zone
      * D. EFS One Zone‑Infrequent Access (One Zone‑IA)
    * **Answer:** B. EFS Standard‑Infrequent Access (Standard‑IA)

24. **Applying best practices across AWS accounts**

    * **Question:** A company uses AWS Organizations. The company wants to apply AWS Well‑Architected security best practices to all of its AWS accounts. Which AWS service will meet these requirements?
    * **Choices:**

      * A. Amazon Macie
      * B. Amazon Detective
      * C. AWS Control Tower
      * D. AWS Secrets Manager
    * **Answer:** C. AWS Control Tower

---

*End of document.*
