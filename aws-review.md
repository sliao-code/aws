1. AWS allows users to manage their resources using a web based user interface. What is the name of this interface?
    - A. AWS CLI.
    - B. AWS API.
    - C. AWS SDK.
    - D. AWS Management Console.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      AWS CLI is a comandline tool. AWS API and SDK are programatic interface.
    </details>

2. You have noticed that several critical Amazon EC2 instances have been terminated. Which of the following AWS services would help you determine who took this action?
    - A. Amazon Inspector.
    - B. AWS CloudTrail.
    - C. AWS Trusted Advisor.
    - D. EC2 Instance Usage Report.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Amazon Inspector is automatically discovers workloads, such as Amazon EC2 instances, containers, and Lambda functions, and scans them for software vulnerabilities and unintended network exposure. 
      
      AWS CloudTrail tracks user activity and API usage on AWS and in hybrid and multicloud environments. 
      
      AWS Trusted Advisor inspects your AWS environment and provides recommendations to improve performance, security, and cost optimization. 
      
      EC2 Instance Usage Report displays historical usage and cost data for EC2 instances. You can control the time frame and granularity (monthly, daily, or hourly) of the report and you can filter on a number of instance attributes including availability zone, instance type, purchase option, consolidated billing account, tag, and platform.
    </details>

3. Which of the below options are related to the reliability of AWS? (Choose TWO)
    - A. Applying the principle of least privilege to all AWS resources.
    - B. Automatically provisioning new resources to meet demand.
    - C. All AWS services are considered Global Services, and this design helps customers serve their international users.
    - D. Providing compensation to customers if issues occur.
    - E. Ability to recover quickly from failures.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E

      A is about security. C is about how broad the services can be. D is about costs.
    </details>

4. Which statement is true regarding the AWS Shared Responsibility Model?
    - A. Responsibilities vary depending on the services used.
    - B. Security of the IaaS services is the responsibility of AWS.
    - C. Patching the guest OS is always the responsibility of AWS.
    - D. Security of the managed services is the responsibility of the customer.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      B is incorrect because users are responsible of security and anything other than hardware/building in Infrastructure as Service.

      C is incorrect because it depends on what services are used.

      D is incorrect becaused in __managed__ services, AWS is reponsible of everything other than user applications.
    </details>

5. You have set up consolidated billing for several AWS accounts. One of the accounts has purchased a number of reserved instances for 3 years. Which of the following is true regarding this scenario?
    - A. The Reserved Instance discounts can only be shared with the master account.
    - B. All accounts can receive the hourly cost benefit of the Reserved Instances.
    - C. The purchased instances will have better performance than On-demand instances.
    - D. There are no cost benefits from using consolidated billing; It is for informational purposes only.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      When using consolidated billing, all AWS accounts can share the benefits of the same services, no matter which account(s) purchased the services.
    </details>

6. A company has developed an eCommerce web application in AWS. What should they do to ensure that the application has the highest level of availability?
    - A. Deploy the application across multiple Availability Zones and Edge locations.
    - B. Deploy the application across multiple Availability Zones and subnets.
    - C. Deploy the application across multiple Regions and Availability Zones.
    - D. Deploy the application across multiple VPC’s and subnets.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      High availability means the service will be available all the time. Redundency is the best way to do it. 
      
      A is incorrect because Edge location is for content distribution purposes. 
      
      B is incorrect because subnets has nothing to do with availability. 
      
      D is incorrect because VPC and subnet are for network setup.
    </details>

7. What does AWS Snowball provide? (Choose TWO)
    - A. Built-in computing capabilities that allow customers to process data locally.
    - B. A catalog of third-party software solutions that customers need to build solutions and run their businesses.
    - C. A hybrid cloud storage between on-premises environments and the AWS Cloud.
    - D. An Exabyte-scale data transfer service that allows you to move extremely large amounts of data to AWS.
    - E. Secure transfer of large amounts of data into and out of the AWS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E

      AWS Anowball is for data transfer. 
      
      B is irrelavent. 
      
      C is incorrect because AWS Snowball is not a storage service. 
      
      D is incorrect because AWS Snowball is petabyte-scale data transfer service, not exabyte-scale.
    </details>

8. What are the benefits of having infrastructure hosted in AWS? (Choose TWO)
    - A. Increasing speed and agility.
    - B. There is no need to worry about security.
    - C. Gaining complete control over the physical infrastructure.
    - D. Operating applications on behalf of customers.
    - E. All of the physical security and most of the data/network security are taken care of for you.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E

      B is incorrect. Security is user's responsibility in IaaS. C is incorrect. Users are never responsible of physical infrastructure in AWS. D is irrelavent to the question.
    </details>

9. What do you gain from setting up consolidated billing for five different AWS accounts under another master account?
    - A. AWS services’ costs will be reduced to half the original price.
    - B. The consolidated billing feature is just for organizational purpose.
    - C. Each AWS account gets volume discounts.
    - D. Each AWS account gets five times the free-tier services capacity.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      A and D are incorrect. The statements are too specific and untrue. B is incorrect because of C.
    </details>

10. What should you do in order to keep the data on EBS volumes safe? (Choose TWO)
    - A. Regularly update firmware on EBS devices.
    - B. Create EBS snapshots.
    - C. Ensure that EBS data is encrypted at rest.
    - D. Store a backup daily in an external drive.
    - E. Prevent any unauthorized access to AWS data centers.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C

      "safe" has two meanings: data is not damaged, and is secure. 
      A is irrelavent to the question. EBS Snapshots can be used to retore data if data are damaged. 
      
      D is not a typical way for AWS. 
      
      E is AWS responsibility.
    </details>

11. One of the most important AWS best-practices to follow is the cloud architecture principle of elasticity. How does this principle improve your architecture’s design?
    - A. By automatically scaling your on-premises resources based on changes in demand.
    - B. By automatically scaling your AWS resources using an Elastic Load Balancer.
    - C. By reducing interdependencies between application components wherever possible.
    - D. By automatically provisioning the required AWS resources based on changes in demand.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      A: AWS doesn't scale on-premises resource. B: ELB distribute services based one loads. It doesn't scale the resources. C has nothing to with scaling.
    </details>

12. What does Amazon CloudFront use to distribute content to global users with low latency?
    - A. AWS Global Accelerator.
    - B. AWS Regions.
    - C. AWS Edge Locations.
    - D. AWS Availability Zones.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      AWS CloudFront is a content delivery service (CDN) hat helps you distribute your static and dynamic content quickly and reliably with high speed. "low latency" means fast reponse. 
      
      A: AWS Global Accelerator is a networking service that helps you improve the availability, performance, and security of your public applications. Global Accelerator provides two global static public IPs that act as a fixed entry point to your application endpoints. 

      B: Regions have nothing to do with low latency. D is incorrect. 
      
      C: Edge Location is a site that CloudFront uses to cache copies of your content for faster delivery to users at any location
    </details>

13. Which service provides DNS in the AWS cloud?
    - A. Route 53.
    - B. AWS Config.
    - C. Amazon CloudFront.
    - D. Amazon EMR.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      A: Route 53 is a highly available and scalable cloud domain name system (DNS) service. Enables to customize DNS routing policies to reduce latency.

      B: is a config tool that helps you assess, audit, and evaluate the configurations and relationships of your resources.

      C: Amazon CliudFront is a content delivery service.

      D: Amazon EMR (previously called Amazon Elastic MapReduce) is the industry-leading cloud big data solution for petabyte-scale data processing, interactive analytics, and machine learning using open-source frameworks such as Apache Spark, Apache Hive, and Presto.
    </details>

14. Hundreds of thousands of DDoS attacks are recorded every month worldwide. What service does AWS provide to help protect AWS Customers from these attacks? (Choose TWO)
    - A. AWS Shield.
    - B. AWS Config.
    - C. Amazon Cognito.
    - D. AWS WAF.
    - E. AWS KMS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D

      A: AWS Shield is a managed DDoS protection service that safeguards applications running on AWS.

      B: AWS Config is a config tool that helps you assess, audit, and evaluate the configurations and relationships of your resources.

      C: Amazon Cognito Implement secure, frictionless customer identity and access management that scales.

      D: AWS WAF (Web Application Firewall) helps you protect against common web exploits and bots that can affect availability, compromise security, or consume excessive resources.

      E: AWS KMS (Key Management Service) lets you create, manage, and control cryptographic keys across your applications and AWS services.
    </details>

15. You want to run a questionnaire application for only one day (without interruption), which Amazon EC2 purchase option should you use?
    - A. Reserved instances.
    - B. Spot instances.
    - C. Dedicated instances.
    - D. On-demand instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      A: Reserved Instances has reserved period of one or three years.

      B: Spot instances can be lost or interrupted. Not suitable for critical tasks. Most cost-efficient option. Good for batch work, image processiong, data analysis, workloads flexible with start and end time.

      C: Dedicated instances is most expensive option.

      D: On-demand instances are good for short term and uniterrupted workloads. You pay what you use.
    </details>

16. You are working on a project that involves creating thumbnails of millions of images. Consistent uptime is not an issue, and continuous processing is not required. Which EC2 buying option would be the most cost-effective?
    - A. Reserved Instances.
    - B. On-demand Instances.
    - C. Dedicated Instances.
    - D. Spot Instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

17. Which of the following can be described as a global content delivery network (CDN) service?
    - A. AWS VPN.
    - B. AWS Direct Connect.
    - C. AWS Regions.
    - D. Amazon CloudFront.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      A: AWS VPN is used by your remote workforce to securely access resources both on AWS and within your on-premises networks.

      B: AWS Direct Connect is a cloud service that links your network directly to AWS to deliver consistent, low-latency performance.

      C: AWS Regions are separate geographic areas. AWS Regions consist of multiple, physically separated and isolated Availability Zones that are connected with low latency, high throughput, highly redundant networking.
    </details>

18. Which of the following services allows customers to manage their agreements with AWS?
    - A. AWS Artifact.
    - B. AWS Certificate Manager.
    - C. AWS Systems Manager.
    - D. AWS Organizations.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      A: AWS Artifact provides on-demand access to select security reports, compliance reports, and agreements with AWS.

      B: AWS Certificate Manager is to provision and manage SSL/TLS certificates with AWS services and connected resources.

      C: AWS Systems Manager is a secure end-to-end management solution for resources on AWS and in multicloud and hybrid environments.

      D: is an account management service that lets you consolidate multiple AWS accounts into an organization that you create and centrally manage.
    </details>

19. Which of the following are examples of AWS-Managed Services, where AWS is responsible for the operational and maintenance burdens of running the service? (Choose TWO)
    - A. Amazon VPC.
    - B. Amazon DynamoDB.
    - C. Amazon Elastic MapReduce.
    - D. AWS IAM.
    - E. Amazon Elastic Compute Cloud.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C

      A: Amazon VPC (Virtual Private Cloud) is a service that lets you launch AWS resources in a logically isolated virtual network that you define.

      B: Amazon DynamoDB is serverless, NoSQL, fully managed database with single-digit millisecond performance at any scale.

      C: Amazon Elastic MapReduce (now called EMR) is a managed cluster platform that simplifies running big data frameworks, such as Apache Hadoop and Apache Spark , on AWS to process and analyze vast amounts of data.
    </details>

20. Your company has a data store application that requires access to a NoSQL database. Which AWS database offering would meet this requirement?
    - A. Amazon Aurora.
    - B. Amazon DynamoDB.
    - C. Amazon Elastic Block Store.
    - D. Amazon Redshift.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      A: is a global-scale relational database service built for the cloud with full MySQL and PostgreSQL compatibility.

      C:  is an easy to use, high-performance cloud Storage Area Network (SAN).

      D: Amazon Redshift is a fast, fully managed cloud data warehouse that makes it simple and cost-effective to analyze all your data.
    </details>

21. As part of the Enterprise support plan, who is the primary point of contact for ongoing support needs?
    - A. AWS Identity and Access Management (IAM) user.
    - B. Infrastructure Event Management (IEM) engineer.
    - C. AWS Consulting Partners.
    - D. Technical Account Manager (TAM).

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      Please review the support section.
    </details>

22. You have AWS Basic support, and you have discovered that some AWS resources are being used maliciously, and those resources could potentially compromise your data. What should you do?
    - A. Contact the AWS Customer Service team.
    - B. Contact the AWS Abuse team.
    - C. Contact the AWS Concierge team.
    - D. Contact the AWS Security team.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      A: too generic.

      B: AWS Abuse refers to the misuse or violation of the terms of service of Amazon Web Services (AWS) by customers or users.

      C: AWS Concierge is available to Enterprise Support Plan.

      D: AWS Security team owns security for all services offered by AWS, including EC2 and S3. 
    </details>

23. In order to implement best practices when dealing with a “Single Point of Failure,” you should attempt to build as much automation as possible in both detecting and reacting to failure. Which of the following AWS services would help? (Choose TWO)
    - A. ELB.
    - B. Auto Scaling.
    - C. Amazon Athen.
    - D. ECR.
    - E. Amazon EC2.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B

      A & B: It seems these two have nothing to do with failure dection, but the two help to redistribute and scale for service availability.

      C: Amazon Athen is a serverless, interactive analytics service that provides a simplified and flexible way to analyze petabytes of data where it lives.

      D: ECR (Elastic Container Registry) is a fully managed Docker container registry that makes it easy to store, share, and deploy container images.

      D: EC2 is a computing resource.
    </details>

24. A company is planning to host an educational website on AWS. Their video courses will be streamed all around the world. Which of the following AWS services will help achieve high transfer speeds?
    - A. Amazon SNS.
    - B. Amazon Kinesis Video Streams.
    - C. AWS CloudFormation.
    - D. Amazon CloudFront.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      A: SNS is notification service.

      B: Amazon Kinesis Video Streams capture, process, and store media streams for playback, analytics, and machine learning.

      C: it is irrelavent to the question.

      D: the question is about content delivery.
    </details>

25. A developer is planning to build a two-tier web application that has a MySQL database layer. Which of the following AWS database services would provide automated backups for the application?
    - A. A MySQL database installed on an EC2 instance.
    - B. Amazon Aurora.
    - C. Amazon DynamoDB.
    - D. Amazon Neptune.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Question requires MySQL and automated backup (managed service).

      A: it is not managed service.

      C: it is not MySQL.

      D: It is not MySQL based. Amazon Neptune is a fast, fully managed database service powering graph use cases such as identity graphs, knowledge graphs, and fraud detection.
    </details>

26. What is the AWS service that enables AWS architects to manage infrastructure as code?
    - A. AWS CloudFormation.
    - B. AWS Config.
    - C. Amazon SES.
    - D. Amazon EMR.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      A: AWS CloudFormation can create and manage AWS infrastructure resources.

      B: AWS Config is a config tool that helps you assess, audit, and evaluate the configurations and relationships of your resources.

      C: Amazon SES is Simple Email Service.

      D: Amazon EMR is a cluster service for big data.
    </details>

27. Under the shared responsibility model, which of the following is the responsibility of AWS?
    - A. Client-side encryption.
    - B. Configuring infrastructure devices.
    - C. Server-side encryption.
    - D. Filtering traffic with Security Groups.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      A, C and D can be responsibility of users, e.g. IaaS.
    </details>

28. What does the AWS Health Dashboard provide? (Choose TWO)
    - A. Detailed troubleshooting guidance to address AWS events impacting your resources.
    - B. Health checks for Auto Scaling instances.
    - C. Recommendations for Cost Optimization.
    - D. A dashboard detailing vulnerabilities in your applications.
    - E. Personalized view of AWS service health.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E

      You can use your AWS Health Dashboard to learn about AWS Health events. These events can affect your AWS services or AWS account. After you sign in to your account, the AWS Health Dashboard shows information in the following ways:
      * Your account events.
      * Your organization events.

      B: I think it doesn't do instance level.

      C: it is not AWS health.

      D: it is an application level, not service level issue.
    </details>

29. You have deployed your application on multiple Amazon EC2 instances. Your customers complain that sometimes they can’t reach your application. Which AWS service allows you to monitor the performance of your EC2 instances to assist in troubleshooting these issues?
    - A. AWS Lambda.
    - B. AWS Config.
    - C. Amazon CloudWatch.
    - D. AWS CloudTrail.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      C: Amazon CloudWatch monitors your Amazon Web Services (AWS) resources and the applications you run on AWS in real time. You can use CloudWatch to collect and track metrics, which are variables you can measure for your resources and applications.

      D: AWS CloudTrail enables you to monitor the calls made to the Amazon CloudWatch API for your account, including calls made by the AWS Management Console, AWS CLI, and other services. When CloudTrail logging is turned on, CloudWatch writes log files to the Amazon S3 bucket that you specified when you configured CloudTrail.
    </details>

30. Your company is developing a critical web application in AWS, and the security of the application is a top priority. Which of the following AWS services will provide infrastructure security optimization recommendations?
    - A. AWS Shield.
    - B. AWS Management Console.
    - C. AWS Secrets Manager.
    - D. AWS Trusted Advisor.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      A: AWS Shield is a managed DDoS protection service that safeguards applications running on AWS.

      C: AWS Secrets Manager allows you to rotate, manage, and retrieve database credentials, API keys, and other secrets through their lifecycle.

      D: AWS Trusted Advisor inspects your AWS environment and provides recommendations to improve performance, security, and cost optimization.
    </details>

31. Which of the following is not a benefit of Amazon S3? (Choose TWO)
    - A. Amazon S3 provides unlimited storage for any type of data.
    - B. Amazon S3 can run any type of application or backend system.
    - C. Amazon S3 stores any number of objects, but with object size limits.
    - D. Amazon S3 can be scaled manually to store and retrieve any amount of data from anywhere.
    - E. Amazon S3 provides 99.999999999% (11 9’s) of data durability.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D

      B: Amazon S3 is a storage service not a compute service.

      D: Amazon S3 scales __automatically__ to store and retrieve any amount of data from anywhere.
    </details>

32. In the AWS Shared responsibility Model, which of the following are the responsibility of the customer? (Choose TWO)
    - A. Disk disposal.
    - B. Controlling physical access to compute resources.
    - C. Patching the Network infrastructure.
    - D. Setting password complexity rules.
    - E. Configuring network access rules.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D, E

      A, B and C: Customers are never responsible of hardware related activities in AWS.
    </details>

33. What does AWS provide to deploy popular technologies such as IBM MQ on AWS with the least amount of effort and time?
    - A. Amazon Aurora.
    - B. Amazon CloudWatch.
    - C. AWS Quick Start reference deployments.
    - D. AWS OpsWorks.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      C: AWS Quick Start are automated reference deployments built by Amazon Web Services (AWS) solutions architects and AWS Partners.

      D: AWS OpsWorks is a configuration management service that helps automate the management of servers and applications in the cloud. It offers managed instances of Chef and Puppet, two open-source automation platforms that allow users to use code to automate server configurations. 
    </details>

34. Which service provides object-level storage in AWS?
    - A. Amazon EBS.
    - B. Amazon Instance Store.
    - C. Amazon EFS.
    - D. Amazon S3.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      EBS: is a network drive you can attach to your instances while they run.

      Instance Store: high performance hard drive. EC2 Instance Store lose their storage if they’re stopped.

      EFS: network file system.

      S3: object-level storage.
    </details>

35. Which S3 storage class is best for data with unpredictable access patterns?
    - A. Amazon S3 Intelligent-Tiering.
    - B. Amazon S3 Glacier Flexible Retrieval.
    - C. Amazon S3 Standard.
    - D. Amazon S3 Standard-Infrequent Access.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Amazon S3 Standard is typically used for data that is frequently accessed, and Amazon S3 Glacier is used for long-term cold storage like archiving where data retrievals are infrequent and planned. Amazon S3 Standard-Infrequent Access is useful for data that is infrequently accessed, but requires rapid access when needed.
    </details>

36. A company has moved to AWS recently. Which of the following AWS Services will help ensure that they have the proper security settings? (Choose TWO)
    - A. AWS Trusted Advisor.
    - B. Amazon Inspector.
    - C. Amazon SNS.
    - D. Amazon CloudWatch.
    - E. Concierge Support Team.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B

      C: SNS is a notification system. Not about security.

      D: CloudWatch is a real-time monitoring system.

      E: It is a support team. Not specific security support.
    </details>

37. You work as an on-premises MySQL DBA. The work of database configuration, backups, patching, and DR can be time-consuming and repetitive. Your company has decided to migrate to the AWS Cloud. Which of the following can help save time on database maintenance so you can focus on data architecture and performance?
    - A. Amazon RDS.
    - B. Amazon Redshift.
    - C. Amazon DynamoDB.
    - D. Amazon CloudWatch.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Amazon RDS is a fully managed, open-source cloud database service that allows you to easily operate and scale your relational database.

      Amazon Redshift is a data warehouse service. Amazon DynamoDB is noSQL database service. CloudWatch is not a DB service.
    </details>

38. According to the AWS Acceptable Use Policy, which of the following statements is true regarding penetration testing of EC2 instances?
    - A. Penetration testing is not allowed in AWS.
    - B. Penetration testing is performed automatically by AWS to determine vulnerabilities in your AWS infrastructure.
    - C. Penetration testing can be performed by the customer on their own instances without prior authorization from AWS.
    - D. The AWS customers are only allowed to perform penetration testing on services managed by AWS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      Penetration testing, also known as a pen test, is a simulated cyberattack on a computer system to evaluate its security. The goal is to identify vulnerabilities in the system's defenses that could be exploited by attackers.
    </details>

39. The principle “design for failure and nothing will fail” is very important when designing your AWS Cloud architecture. Which of the following would help adhere to this principle? (Choose TWO)
    - A. Multi-factor authentication.
    - B. Availability Zones.
    - C. Elastic Load Balancing.
    - D. Penetration testing.
    - E. Vertical Scaling.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C

      Failure means the intent service is not available.

      A: MFA is for security.

      D: it is a simulated cyberattack testing.

      E: Vertical scaling is the process of increasing the resources of a single machine or server to handle more workload. It's also known as scaling up or scaling vertically. It doesn't address availability issue.
    </details>

40. What is the AWS service that provides a virtual network dedicated to your AWS account?
    - A. AWS VPN.
    - B. AWS Subnets.
    - C. AWS Dedicated Hosts.
    - D. Amazon VPC.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      A virtual private cloud (VPC) is a virtual network dedicated to your AWS account. It is logically isolated from other virtual networks in the AWS Cloud. A VPC creates a private cloud within a public cloud, while a VPN secures connections to and from a network over the internet.

      AWS Dedicated Host is a physical server fully dedicated for your use, so you can help address corporate compliance requirements.
    </details>

41. According to the AWS Shared responsibility model, which of the following are the responsibility of the customer? (Choose TWO)
    - A. Managing environmental events of AWS data centers.
    - B. Protecting the confidentiality of data in transit in Amazon S3.
    - C. Controlling physical access to AWS Regions.
    - D. Ensuring that the underlying EC2 host is configured properly.
    - E. Patching applications installed on Amazon EC2.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E

      A, C, and D: AWS customers never hold responsibilities of environment, physical assets and their configurations.
    </details>

42. Your company is designing a new application that will store and retrieve photos and videos. Which of the following services should you recommend as the underlying storage mechanism?
    - A. Amazon EBS.
    - B. Amazon SQS.
    - C. Amazon S3.
    - D. Amazon Instance store.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

43. What is the AWS service that enables you to manage all of your AWS accounts from a single master account?
    - A. AWS WAF.
    - B. AWS Trusted Advisor.
    - C. AWS Organizations.
    - D. Amazon Config.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      AWS Organizations is an account management service that lets you consolidate multiple AWS accounts into an organization that you create and centrally manage. With Organizations, you can create member accounts and invite existing accounts to join your organization.
    </details>

44. You are working on two projects that require completely different network configurations. Which AWS service or feature will allow you to isolate resources and network configurations?
    - A. Internet gateways.
    - B. Virtual Private Cloud.
    - C. Security Groups.
    - D. Amazon CloudFront.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      VPC is a private cloud environment that's hosted within a public cloud. It provides a secure, isolated space for users to perform tasks that would normally be done in a traditional data center, such as storing data, running code, and hosting websites.

      Internet gateways is a horizontally scaled, redundant, and highly available VPC component that allows communication between your VPC and the internet.
      
      Security Groups act as virtual firewalls that control traffic to and from resources in a Virtual Private Cloud (VPC). Each security group has its own rules for inbound and outbound traffic, which can specify the source, port range, and protocol. When a security group is associated with an EC2 instance, it controls the traffic for that instance.

      CloudFront is a content delivery service.
    </details>

45. Which of the following services can help protect your web applications from SQL injection and other vulnerabilities in your application code?
    - A. Amazon Cognito.
    - B. AWS IAM.
    - C. Amazon Aurora.
    - D. AWS WAF.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      is a code injection technique used to attack data-driven applications, in which malicious SQL statements are inserted into an entry field for execution (e.g. to dump the database contents to the attacker).

      Amazon Cognito is an Amazon Web Services product that controls user authentication and access for mobile applications on internet-connected devices.

      Amazon Aurora is a relational database management system (RDBMS) built for the cloud with full MySQL and PostgreSQL compatibility.

      Amazon WAF is a web application firewall. WAF helps you protect against common web exploits and bots that can affect availability, compromise security, or consume excessive resources.
    </details>

46. What are the default security credentials that are required to access the AWS management console for an IAM user account?
    - A. MFA.
    - B. Security tokens.
    - C. A user name and password.
    - D. Access keys.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

47. In your on-premises environment, you can create as many virtual servers as you need from a single template. What can you use to perform the same in AWS?
    - A. IAM.
    - B. An internet gateway.
    - C. EBS Snapshot.
    - D. AMI.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      AMI is Amazon Machine Image, is an image that provides the software that is required to set up and boot an Amazon EC2 instance.
    </details>

48. What are two advantages of using Cloud Computing over using traditional data centers? (Choose TWO)
    - A. Reserved Compute capacity.
    - B. Eliminating Single Points of Failure (SPOFs).
    - C. Distributed infrastructure.
    - D. Virtualized compute resources.
    - E. Dedicated hosting.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, D

      A: is not specific to cloud.

      B: Cloud can only increase availability

      E: is actually the advantage of traditional data center
    </details>

49. Which statement best describes the operational excellence pillar of the AWS Well-Architected Framework?
    - A. The ability of a system to recover gracefully from failure.
    - B. The efficient use of computing resources to meet requirements.
    - C. The ability to monitor systems and improve supporting processes and procedures.
    - D. The ability to manage datacenter operations more efficiently.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      Five Pillars of AWS:
      * Operational Excellence Pillar includes the ability to support development and run workloads effectively, gain insight into their operations, and to continuously improve supporting processes and procedures to deliver business value.
      * The Security pillar includes the security pillar encompasses the ability to protect data, systems, and assets to take advantage of cloud technologies to improve your security.
      * The Reliability pillar includes the reliability pillar encompasses the ability of a workload to perform its intended function correctly and consistently when it’s expected to. this includes the ability to operate and test the workload through its total lifecycle.
      * The Performance Efficiency pillar includes the ability to use computing resources efficiently to meet system requirements, and to maintain that efficiency as demand changes and technologies evolve.
      * The Cost Optimization pillar includes the ability to run systems to deliver business value at the lowest price point.
    </details>

50. AWS has created a large number of Edge Locations as part of its Global Infrastructure. Which of the following is NOT a benefit of using Edge Locations?
    - A. Edge locations are used by CloudFront to cache the most recent responses.
    - B. Edge locations are used by CloudFront to improve your end users’ experience when uploading files.
    - C. Edge locations are used by CloudFront to distribute traffic across multiple instances to reduce latency.
    - D. Edge locations are used by CloudFront to distribute content to global users with low latency.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      C: is the function of ELB.
    </details>

51. Which of the following services allows you to run containerized applications on a cluster of EC2 instances?
    - A. Amazon ECS.
    - B. AWS Data Pipeline.
    - C. AWS Cloud9.
    - D. AWS Personal Health Dashboard.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Amazon ECS (Elastic Container Service): provides a fully managed container service solution that's easy to use, scalable, secure, and reliable.

      AWS Data Pipeline is a web service that you can use to automate the movement and transformation of data. Data pipelines let you integrate data from different sources and transform it for analysis.

      AWS Cloud9 is a cloud-based integrated development environment (IDE) that lets you write, run, and debug your code with just a browser.

      AWS Personal Health Dashboard provides a personalized view into the performance and availability of the AWS services you are using, as well as alerts.
    </details>

52. Which of the following services will help businesses ensure compliance in AWS?
    - A. CloudFront.
    - B. CloudEndure Migration.
    - C. CloudWatch.
    - D. CloudTrail.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      CloudEndure Migration simplifies, expedites, and automates large-scale migrations from physical, virtual, and cloud-based infrastructure to AWS.
    </details>

53. Which of the following procedures will help reduce your Amazon S3 costs?
    - A. Use the Import/Export feature to move old files automatically to Amazon Glacier.
    - B. Use the right combination of storage classes based on different use cases.
    - C. Pick the right Availability Zone for your S3 bucket.
    - D. Move all the data stored in S3 standard to EBS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      To reduce costs, use different classes of storage based on needs because pricing is different.
    </details>

54. Which of the following activities may help reduce your AWS monthly costs?
    - A. Enabling Amazon EC2 Auto Scaling for all of your workloads.
    - B. Using the AWS Network Load Balancer (NLB) to load balance the incoming HTTP requests.
    - C. Removing all of your Cost Allocation Tags.
    - D. Deploying your AWS resources across multiple Availability Zones.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      B: ELB doesn't reduce costs.

      C: Cost Allocation Tags don't cost, but help to group different cost categories.

      D: this increase availability, not costs.
    </details>

55. Which of the following AWS security features is associated with an EC2 instance and functions to filter incoming traffic requests?
    - A. AWS X-Ray.
    - B. Network ACL.
    - C. Security Groups.
    - D. VPC Flow logs.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      AWS X-Ray helps developers analyze and debug production, distributed applications, such as those built using a microservices architecture.

      Network ACL allows or denies specific inbound or outbound traffic at the subnet level.

      Security Group acts as a virtual firewall for your EC2 instances to control incoming and outgoing traffic.
    </details>

56. Using Amazon RDS falls under the shared responsibility model. Which of the following are customer responsibilities? (Choose TWO)
    - A. Building the relational database schema.
    - B. Performing backups.
    - C. Managing the database settings.
    - D. Patching the database software.
    - E. Installing the database software.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C

      A: database schema is the database structure. it is always customer's responsibility.

      B, D, and E: Amazon RDS is fully managed service. Customers don't do any tasks like backup, patching software, etc.

      C: database settings are up to customers.

    </details>

57. A company has a large amount of structured data stored in their on-premises data center. They are planning to migrate all the data to AWS, what is the most appropriate AWS database option?
    - A. Amazon DynamoDB.
    - B. Amazon SNS.
    - C. Amazon RDS.
    - D. Amazon ElastiCache.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      Strcutured data -> RDS
    </details>

58. A company has created a solution that helps AWS customers improve their architectures on AWS. Which AWS program may support this company?
    - A. APN Consulting Partners.
    - B. AWS TAM.
    - C. APN Technology Partners.
    - D. AWS Professional Services.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      APN Consulting Partners are professional services firms that help AWS customers design, build, migrate, and manage their applications and workloads on the AWS platform. They are a key part of the AWS Partner Network (APN), which is a global program that helps AWS partners grow their businesses.

      An AWS TAM (acronym for AWS Technical Account Manager) is a specific role within AWS in which quite simply, the customer is everything.

      APN Technology Partners are a type of partner in the Amazon Web Services (AWS) Partner Network (APN) that provide software, hardware, or connectivity services that are integrated with or hosted on the AWS platform.

      AWS Professional Services is a global team of experts that can help you realize your desired business outcomes when using the AWS Cloud. It is an AWS team that helps AWS customers.
    </details>

59. A developer needs to set up an SSL security certificate for a client's eCommerce website in order to use the HTTPS protocol. Which of the following AWS services can be used to deploy the required SSL server certificates? (Choose TWO)
    - A. Amazon Route 53.
    - B. AWS ACM.
    - C. AWS Directory Service.
    - D. AWS Identity & Access Management.
    - E. AWS Data Pipeline.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B

      Amazon Route 53 is a DNS service. It is needed by web service to translate web site name to IP address.

      AWS ACM is AWS Certificate Manager.

      AWS Directory Service provides multiple directory choices for customers who want to use existing Microsoft AD or Lightweight Directory Access Protocol (LDAP)–aware applications in the cloud. It also offers those same choices to developers who need a directory to manage users, groups, devices, and access.

      AWS IAM is for managing user identity and access.
    </details>

60. Which of the following AWS services scale automatically without your intervention? (Choose TWO)
    - A. Amazon EC2.
    - B. Amazon S3.
    - C. AWS Lambda.
    - D. Amazon EMR.
    - E. Amazon EBS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C

      B and C are fully managed.

      The rest are not.
    </details>

61. A company is planning to migrate an application from Amazon EC2 to AWS Lambda to use a serverless architecture. Which of the following will be the responsibility of AWS after migration? (Choose TWO)
    - A. Application management.
    - B. Capacity management.
    - C. Access control.
    - D. Operating system maintenance.
    - E. Data management.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D

      AWS Lambda is a fully managed service. Any responsibilities beyond the customer applications (application itself, access contro, data, etc) belongs to AWS. So B, D.
    </details>

62. How do ELBs improve the reliability of your application?
    - A. By distributing traffic across multiple S3 buckets.
    - B. By replicating data to multiple availability zones.
    - C. By creating database Read Replicas.
    - D. By ensuring that only healthy targets receive traffic.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      ELB route traffics to healthy targets.
    </details>

63. Which AWS Service is used to manage user permissions?
    - A. Security Groups.
    - B. Amazon ECS.
    - C. AWS IAM.
    - D. AWS Support.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      A: Security Groups are used for EC2 instance level access control.

      B: EC2 is a computing resource, not access control resource.

      D: AWS Support is a customer support service.
    </details>

64. Which support plan includes AWS Support Concierge Service?
    - A. Premium Support.
    - B. Business Support.
    - C. Enterprise Support.
    - D. Standard Support.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      Only Enterprise Support has AWS Support Concierge Service.
    </details>

65. What are the benefits of using an AWS-managed service? (Choose TWO)
    - A. Provides complete control over the virtual infrastructure.
    - B. Allows customers to deliver new solutions faster.
    - C. Lowers operational complexity.
    - D. Eliminates the need to encrypt data.
    - E. Allows developers to control all patching related activities.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C

      A, E belongs to AWS responsibilities. D is customer's responsibility.
    </details>

66. Which of the following are use cases for Amazon S3? (Choose TWO)
    - A. Hosting static websites.
    - B. Hosting websites that require sustained high CPU utilization.
    - C. Cost-effective database and log storage.
    - D. A media store for the CloudFront service.
    - E. Processing data streams at any scale.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D

      Amazon S3 is mainly for backups, video, images, static websites, etc.
    </details>

67. What is the benefit of using an API to access AWS Services?
    - A. It improves the performance of AWS resources.
    - B. It reduces the time needed to provision AWS resources.
    - C. It reduces the number of developers necessary.
    - D. It allows for programmatic management of AWS resources.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      using API is for programmatic way to manage AWS resources.

      API or SDK -> programmatic
    </details>

68. How can AWS customers track and avoid over-spending on underutilized reserved instances?
    - A. Customers can add all AWS accounts to an AWS Organization, enable Consolidated Billing, and turn off Reserved Instance sharing.
    - B. Customers can use Amazon Neptune to track and analyze their usage patterns, detect underutilized reserved instances, and then sell them on the Amazon EC2 Reserved Instance Marketplace.
    - C. Customers can use the AWS Budgets service to track the reserved instances usage and set up alert notifications when their utilization drops below the threshold that they define.
    - D. Customers can use Amazon CloudTrail to automatically check for unused reservations and get recommendations to reduce their bill.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      A: doesn't solve underutilized instances.

      B: Amazon Neptune is a fast, fully managed database service powering graph use cases such as identity graphs, knowledge graphs, and fraud detection.

      C: AWS Budgets is used to track and take action on your AWS costs and usage. You can use AWS Budgets to monitor your aggregate utilization and coverage metrics for your Reserved Instances (RIs) or Savings Plans.

      D: CloudTrail is an AWS service that helps you enable operational and risk auditing, governance, and compliance of your AWS account. Actions taken by a user, role, or an AWS service are recorded as events in CloudTrail. Events include actions taken in the AWS Management Console, AWS Command Line Interface, and AWS SDKs and APIs.
    </details>

69. What does AWS Service Catalog provide?
    - A. It enables customers to quickly find descriptions and use cases for AWS services.
    - B. It enables customers to explore the different catalogs of AWS services.
    - C. It simplifies organizing and governing commonly deployed IT services.
    - D. It allows developers to deploy infrastructure on AWS using familiar programming languages.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      AWS Service Catalog helps you create and manage IaC templates approved for use on AWS so anyone can discover approved, self-service cloud resources. AWS CloudFormation is a resource-centric service that focuses on infrastructure provisioning and management using templates, while AWS Service Catalog is a service-focused solution that allows for the creation and management of curated catalogs of pre-approved services.
    </details>

70. Which of the following AWS Services helps with planning application migration to the AWS Cloud?
    - A. AWS Snowball Migration Service.
    - B. AWS Application Discovery Service.
    - C. AWS DMS.
    - D. AWS Migration Hub.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      AWS Snowball Migration Service is a data transfer service that helps move large amounts of data into and out of AWS. 

      AWS Application Discovery Service helps you plan migrations to the cloud by collecting usage and configuration data about your on-premises servers.

      AWS DMS (database migration service) is a managed migration and replication service that helps move your database and analytics workloads to AWS quickly, securely, and with minimal downtime and zero data loss.

      AWS Migration Hub delivers a guided end-to-end migration and modernization journey through discovery, assessment, planning, and execution.
    </details>

71. Both AWS and traditional IT distributors provide a wide range of virtual servers to meet their customers’ requirements. What is the name of these virtual servers in AWS?
    - A. Amazon EBS Snapshots.
    - B. Amazon VPC.
    - C. AWS Managed Servers.
    - D. Amazon EC2 Instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

72. Which of the following activities supports the Operational Excellence pillar of the AWS Well-Architected Framework?
    - A. Using AWS Trusted Advisor to find underutilized resources.
    - B. Using AWS CloudTrail to record user activities.
    - C. Using AWS CloudFormation to manage infrastructure as code.
    - D. Deploying an application in multiple Availability Zones.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      Operational Excellence Pillar: the ability to support development and run workloads effectively, gain insight into their operations, and to continuously improve supporting processes and procedures to deliver business value.

      There are five design principles for operational excellence in the cloud:
      * Perform operations as code
      * Make frequent, small, reversible changes
      * Refine operations procedures frequently
      * Anticipate failure
      * Learn from all operational failures
    </details>

73. What are the benefits of using DynamoDB? (Choose TWO)
    - A. Automatically scales to meet required throughput capacity.
    - B. Provides resizable instances to match the current demand.
    - C. Supports both relational and non-relational data models.
    - D. Offers extremely low (single-digit millisecond) latency.
    - E. Supports the most popular NoSQL database engines such as CouchDB and MongoDB.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D

      DynamoDB is a fully managed NoSQL service.

      B: auto scaling, not manual scaling.

      C: it is NoSQL.

      E: It is Amazon version of MongoDB.
    </details>

74. Which of the following can be used to protect data at rest on Amazon S3? (Choose TWO)
    - A. Versioning.
    - B. Deduplication.
    - C. Permissions.
    - D. Decryption.
    - E. Conversion.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C

      Some or all of the following features can be used to protect data at rest on Amazon S3:
      - Permissions
      - Versioning
      - Replication
      - Backup
      - Encryption-server side
      - Encryption-client side

      B: opposite to duplication.
      D: opposite to encryption.
      E: irrelavent
    </details>

75. As part of the AWS Migration Acceleration Program (MAP), what does AWS provide to accelerate Enterprise adoption of AWS? (Choose TWO)
    - A. AWS Partners.
    - B. AWS Artifact.
    - C. AWS Professional Services.
    - D. Amazon Athena.
    - E. Amazon PinPoint.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C

      Both A and C can help customer to adopt AWS.

      B: AWS Artifact is about compliance documentation.

      D: Amazon Athena is a serverless, interactive analytics service that provides a simplified and flexible way to analyze petabytes of data where it lives.

      E: Amazon PinPoint is a flexible, scalable marketing communications service that connects you with customers over email, SMS, push notifications, or voice.
    </details>

76. AWS recommends some practices to help organizations avoid unexpected charges on their bill. Which of the following is NOT one of these practices?
    - A. Deleting unused EBS volumes after terminating an EC2instance.
    - B. Deleting unused AutoScaling launch configuration.
    - C. Deleting unused Elastic Load Balancers.
    - D. Releasing unused Elastic IPs after terminating an EC2instance.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      AutoScaling launch configuration itself doesn't incur costs.
    </details>

77. Which of the following allows you to create new RDS instances? (Choose TWO)
    - A. AWS CodeDeploy.
    - B. AWS Quick Starts.
    - C. AWS CloudFormation.
    - D. AWS DMS.
    - E. AWS Management Console.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, E

      AWS CodeDeploy is a service that automates code deployments to any instance, including Amazon EC2 instances and instances running on-premises. AWS CodeDeploy makes it easier for you to rapidly release new features, helps you avoid downtime during deployment, and handles the complexity of updating your applications.

      A: it is about deployment, not creating instances.

      B: Quick Starts are automated reference deployments built by Amazon Web Services (AWS) solutions architects and AWS Partners. It helps deployment, not creating instances.

      D: AWS DMS ia bout database migration.

      C and E: you can create RDS instances (EC2) via Management Console or CloudFormation or API/SDK.
    </details>

78. Which AWS Group assists customers in achieving their desired business outcomes?
    - A. AWS Security Team.
    - B. AWS Professional Services.
    - C. AWS Trusted Advisor.
    - D. AWS Concierge Support Team.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      A: it is about security.

      B: it is a global team of experts that can help you realize your desired business outcomes when using the AWS Cloud.

      C: it is about finding configuration issues.

      D: it is a customer support service.
    </details>

79. Which AWS Service allows customers to download AWS SOC & PCI reports?
    - A. AWS Well-Architected Tool.
    - B. AWS Artifact.
    - C. AWS Glue.
    - D. Amazon Chime.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      SOC (System and Organization Control) and PCI (Payment Card Industry). The question is about security and complaince.
    </details>

80. A company is migrating its on-premises database to Amazon RDS. What should the company do to ensure Amazon RDS costs are kept to a minimum?
    - A. Right-size before and after migration.
    - B. Use a Multi-Region Active-Passive architecture.
    - C. Combine On-demand Capacity Reservations with Saving Plans.
    - D. Use a Multi-Region Active-Active architecture.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Right-sizing is the process of matching instance types and sizes to your workload performance and capacity requirements at the lowest possible cost. By right-sizing before migration, you can significantly reduce your infrastructure costs. If you skip right-sizing to save time, your migration speed might be faster, but you will end up with higher cloud infrastructure spend for a potentially long time.

      B: It is used for for disaster recovery, not costs. 

      C: This only for EC2.

      D: It is for low latency. Using a Multi-Region Active-Active architecture will increase infrastructure costs, including Amazon RDS costs.
    </details>

81. What is the primary storage service used by Amazon RDS database instances?
    - A. Amazon Glacier.
    - B. Amazon EBS.
    - C. Amazon EFS.
    - D. Amazon S3.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

82. Which of the following AWS services is designed with native Multi-AZ fault tolerance in mind? (Choose TWO)
    - A. Amazon Redshift.
    - B. AWS Snowball.
    - C. Amazon Simple Storage Service.
    - D. Amazon EBS.
    - E. Amazon DynamoDB.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, E

      S3 and DynamoDB are fully managed, so they are native Multi-AZ fault tolerance.
    </details>

83. What are the Amazon RDS features that can be used to improve the availability of your database? (Choose TWO)
    - A. AWS Regions.
    - B. Multi-AZ Deployment.
    - C. Automatic patching.
    - D. Read Replicas.
    - E. Edge Locations.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D

      Improve availability -> make multiple copies.
    </details>

84. An organization runs many systems and uses many AWS products. Which of the following services enables them to control how each developer interacts with these products?
    - A. AWS Identity and Access Management.
    - B. Amazon RDS.
    - C. Network Access Control Lists.
    - D. Amazon EMR.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Only A and C are related to access control. C is specific to network. So it is A.
    </details>

85. Using Amazon EC2 falls under which of the following cloud computing models?
    - A. Iaas & SaaS.
    - B. IaaS.
    - C. SaaS.
    - D. PaaS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      EC2 is a virtual machine (equivalent to a computer equipment). It is part of infrastructures.
    </details>

86. Your company is designing a new application that will store and retrieve photos and videos. Which of the following services should you recommend as the underlying storage mechanism?
    - A. Amazon EBS.
    - B. Amazon SQS.
    - C. Amazon Instance store.
    - D. Amazon S3.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      it has appeared before.
    </details>

87. Amazon Glacier is an Amazon S3 storage class that is suitable for storing [...] & [...]. (Choose TWO)
    - A. Active archives.
    - B. Dynamic websites’ assets.
    - C. Long-term analytic data.
    - D. Active databases.
    - E. Cached data.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C

      Amazon Glacier is for backup, especially long term backups.
    </details>

88. What is the AWS service that performs automated network assessments of Amazon EC2 instances to check for vulnerabilities?
    - A. Amazon Kinesis.
    - B. Security groups.
    - C. Amazon Inspector.
    - D. AWS Network Access Control Lists.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      Amazon Kinesis cost-effectively processes and analyzes streaming data at any scale as a fully managed service.
    </details>

89. Under the Shared Responsibility Model, which of the following controls do customers fully inherit from AWS? (Choose TWO)
    - A. Patch management controls.
    - B. Database controls.
    - C. Awareness & Training.
    - D. Environmental controls.
    - E. Physical controls.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D, E
    </details>

90. A company needs to host a database in Amazon RDS for at least three years. Which of the following options would be the most cost-effective solution?
    - A. Reserved instances     - No Upfront.
    - B. Reserved instances     - Partial Upfront.
    - C. On-Demand instances.
    - D. Spot Instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Database needs to be on all the time. Spot Instance is not suitable. On-demand is most expensive.
    </details>

91. Your application has recently experienced significant global growth, and international users are complaining of high latency. What is the AWS characteristic that can help improve your international users’ experience?
    - A. Elasticity.
    - B. Global reach.
    - C. Data durability.
    - D. High availability.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      High latency == slow response. To reduce latency, you can reduce distance between users and your application. Global reach makes all users are close to one of your application sites.
    </details>

92. Savings Plans are available for which of the following AWS compute services? (Choose TWO)
    - A. AWS Batch.
    - B. AWS Outposts.
    - C. Amazon Lightsail.
    - D. Amazon EC2.
    - E. AWS Lambda.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D, E

      Need to remember these.
    </details>

93. Which statement is correct with regards to AWS service limits? (Choose TWO)
    - A. You can contact AWS support to increase the service limits.
    - B. Each IAM user has the same service limit.
    - C. There are no service limits on AWS.
    - D. You can use the AWS Trusted Advisor to monitor your service limits.
    - E. The Amazon Simple Email Service is responsible for sending email notifications when usage approaches a service limit.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D

      A makes sense. D: need to remember.

      B: apparently wrong. C: not true. E: SES is a service for customer to use. It is not for AWS to notify customers.
    </details>

94. What is the AWS tool that enables you to use scripts to manage all AWS services and resources?
    - A. AWS Console.
    - B. AWS Service Catalog.
    - C. AWS OpsWorks.
    - D. AWS CLI.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      CLI == Command Line Interface.
    </details>

95. How are AWS customers billed for Linux-based Amazon EC2 usage?
    - A. EC2 instances will be billed on one second increments, with a minimum of one minute.
    - B. EC2 instances will be billed on one hour increments, with a minimum of one day.
    - C. EC2 instances will be billed on one minute increments, with a minimum of one hour.
    - D. EC2 instances will be billed on one day increments, with a minimum of one month.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Amazon EC2 usage is calculated by either the __hour__ or the __second__ based on the size of the instance, operating system, and the AWS Region where the instances are launched. Pricing is per instance-hour consumed for each instance, from the time an instance is launched until it's terminated or stopped.
      * Each partial instance-hour consumed is billed __per-second__ for instances launched in __Linux__, __Windows__, or __Windows with SQL__ Enterprise, SQL Standard, or SQL Web instances.
      * Each partial instance-hour is billed as a __full hour__ for all other instance types.
    </details>

96. Which of the following will impact the price paid for an EC2 instance? (Choose TWO)
    - A. Instance type.
    - B. The Availability Zone where the instance is provisioned.
    - C. Load balancing.
    - D. Number of buckets.
    - E. Number of private IPs.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
    </details>

97. A customer spent a lot of time configuring a newly deployed Amazon EC2 instance. After the workload increases, the customer decides to provision another EC2 instance with an identical configuration. How can the customer achieve this?
    - A. By creating an AWS Config template from the old instance and launching a new instance from it.
    - B. By creating an EBS Snapshot of the old instance.
    - C. By installing Aurora on EC2 and launching a new instance from it.
    - D. By creating an AMI from the old instance and launching a new instance from it.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      AMI == Amazon Machine Image
    </details>

98. A company uses AWS Organizations to manage all of its AWS accounts. Which of the following allows the company to restrict what services and actions are allowed in each individual account?
    - A. IAM Principals.
    - B. AWS Service Control Policies (SCPs).
    - C. IAM policies.
    - D. AWS Fargate.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      IAM Principals entities that can perform actions and interact with AWS resources.

      AWS Service Control Policies (SCPs) are a type of organization policy that you can use to manage permissions in your organization. SCPs offer central control over the maximum available permissions for the IAM users and IAM roles in your organization.

      An AWS IAM policy defines the permissions of an identity (users, groups, and roles) or resource within the AWS account.

      AWS Fargate is a serverless compute engine for containers that works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes (EKS).
    </details>

99. Which of the following statements describes the AWS Cloud’s agility?
    - A. AWS allows you to host your applications in multiple regions around the world.
    - B. AWS provides customizable hardware at the lowest possible cost.
    - C. AWS allows you to provision resources in minutes.
    - D. AWS allows you to pay upfront to reduce costs.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      Agility == make application available quickly.
    </details>

100.  What are the benefits of using the Amazon Relational Database Service? (Choose TWO)
    - A. Lower administrative burden.
    - B. Complete control over the underlying host.
    - C. Resizable compute capacity.
    - D. Scales automatically to larger or smaller instance types.
    - E. Supports the document and key-value data structure.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C

      A and C: because Amazon RDSS is a fully managed service.

      B and D: incorrect. Customers have no control to underlying host or instances.

      E: they are NoSQL features. RDS is a SQL database.
    </details>

101. What is the connectivity option that uses Internet Protocol Security (IPSec) to establish encrypted connectivity between an on-premises network and the AWS Cloud?
    - A. Internet Gateway.
    - B. AWS IQ.
    - C. AWS Direct Connect.
    - D. AWS Site-to-Site VPN.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      IPSec is a VPN protocol. So it is D.

      A: Internet gateway is a general service to forward traffic between internet and private subnets.

      AWS IQ provides you with hands-on help from AWS experts who can complete work in your AWS account.

      C: Direct Connect may not use VPN.
    </details>

102. What is the minimum level of AWS support that provides 24x7 access to technical support engineers via phone and chat?
    - A. Enterprise Support.
    - B. Developer Support.
    - C. Basic Support.
    - D. Business Support.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      Need to review the details of different support levels.

      Basic Support: Trusted Advisor, 24/7 access to customer service, documents, etc. Personal Heath Dashnoard.

      Developer Support: Add the followings: business-hour email support, unlimited cases/1 primary contact. General < 24 hours. impaired < 12 hours.

      Business Support: intened for production workloads. 24/7 phone, email, and chat access to Support Engineers. unlimited cases/unlimited contacts. Production system impaired < 4 hours, production system down < 1 hour.

      Enterprise Support: Bussiness support + Access to TAM, Coneirge Support team, business critical < 15 minutes.
    </details>

103. Which of the following is used to control network traffic in AWS? (Choose TWO)
    - A. Network Access Control Lists (NACLs).
    - B. Key Pairs.
    - C. Access Keys.
    - D. IAM Policies.
    - E. Security Groups.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E

      B, C: just keys, not network traffic control. D: just policies for users, not network traffic related.
    </details>

104. A company has developed a media transcoding application in AWS. The application is designed to recover quickly from hardware failures. Which one of the following types of instance would be the most cost-effective choice to use?
    - A. Reserved instances.
    - B. Spot Instances.
    - C. On-Demand instances.
    - D. Dedicated instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      mdeia transcoding doesn't require continuous running. It can recover quickly. So Spot Instances are cheapest.
    </details>

105. Which AWS Service provides the current status of all AWS Services in all AWS Regions?
    - A. AWS Service Health Dashboard.
    - B. AWS Management Console.
    - C. Amazon CloudWatch.
    - D. AWS Personal Health Dashboard.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Need to remember this one.
    </details>

106. Which AWS service or feature can be used to call AWS Services from different programming languages?
    - A. AWS Software Development Kit.
    - B. AWS Command Line Interface.
    - C. AWS CodeDeploy.
    - D. AWS Management Console.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      programmatic -> SDK/API
    </details>

107. Which AWS Service can be used to register a new domain name?
    - A. Amazon Personalize.
    - B. Amazon Route 53.
    - C. AWS KMS.
    - D. AWS Config.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Route 53 -> Domain Name Service
    </details>

108. App development companies move their business to AWS to reduce time-to-market and improve customer satisfaction, what are the AWS automation tools that help them deploy their applications faster? (Choose TWO)
    - A. AWS CloudFormation.
    - B. AWS Migration Hub.
    - C. AWS IAM.
    - D. AWS Elastic Beanstalk.
    - E. Amazon Macie.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D

      It is about deployment. so B (migration), C (access control), E (data security) are incorrect.
    </details>

109. Which AWS service provides cost-optimization recommendations?
    - A. AWS Trusted Advisor.
    - B. AWS Pricing Calculator.
    - C. Amazon QuickSight.
    - D. AWS X-Ray.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      B: just calculate price, not a recommandation tool.

      C: is not related to costs.

      D: helps you debug and analyze your microservices applications with request tracing so you can find the root cause of issues and performance.
    </details>

110. What is the most cost-effective purchasing option for running a set of EC2 instances that must always be available for a period of two months?
    - A. On-Demand Instances.
    - B. Spot Instances.
    - C. Reserved Instances     - All Upfront.
    - D. Reserved Instances     - No Upfront.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

111. What is the AWS Support feature that allows customers to manage support cases programmatically?
    - A. AWS Trusted Advisor.
    - B. AWS Operations Support.
    - C. AWS Support API.
    - D. AWS Personal Health Dashboard.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

112. Which methods can be used by customers to interact with AWS Identity and Access Management (IAM)? (Choose TWO)
    - A. AWS CLI.
    - B. AWS Security Groups.
    - C. AWS SDKs.
    - D. AWS Network Access Control Lists.
    - E. AWS CodeCommit.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C
    </details>

113. How does AWS notify customers about security and privacy events pertaining to AWS services?
    - A. Using the AWS ACM service.
    - B. Using Security Bulletins.
    - C. Using the AWS Management Console.
    - D. Using Compliance Resources.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      AWS makes public notifications in the form of Security Bulletins, which are posted in the AWS Security website.
    </details>

114. Which of the following approaches will help you eliminate human error and automate the process of creating and updating your AWS environment?
    - A. Use Software test automation tools.
    - B. Use AWS CodeDeploy to build and automate your AWS environment.
    - C. Use code to provision and operate your AWS infrastructure.
    - D. Migrate all of your applications to a dedicated host.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      to eliminate human errors -> use code/scripts to automate the process.
    </details>

115. Which of the following factors should be considered when determining the region in which AWS Resources will be deployed? (Choose TWO)
    - A. The AWS Region’s security level.
    - B. Data sovereignty.
    - C. Cost.
    - D. The planned number of VPCs.
    - E. Geographic proximity to the company's location.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C

      A: there is no security difference among regions.

      D: # of VPC has nothing to do with regions.

      E: irelavant. There might be a point to be close to customers.
    </details>

116. You are running a financial services web application on AWS. The application uses a MySQL database to store the data. Which of the following AWS services would improve the performance of your application by allowing you to retrieve information from fast in-memory caches?
    - A. Amazon EFS.
    - B. Amazon Neptune.
    - C. Amazon ElastiCache.
    - D. DAX.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      it is about "cache". choose C.

      Amazon Neptune: is a fast, fully managed database service powering graph use cases such as identity graphs, knowledge graphs, and fraud detection.
    </details>

117. The TCO gap between AWS infrastructure and traditional infrastructure has widened over the recent years. Which of the following could be the reason for that?
    - A. AWS helps customers invest more in capital expenditures.
    - B. AWS automates all infrastructure operations, so customers save more on human resources costs.
    - C. AWS continues to lower the cost of cloud computing for its customers.
    - D. AWS secures AWS resources at no additional charge.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      TCO -> total costs of operation.
    </details>

118. Which of the following is a type of MFA device that customers can use to protect their AWS resources?
    - A. AWS CloudHSM.
    - B. U2F Security Key.
    - C. AWS Access Keys.
    - D. AWS Key Pair.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

119. Which of the following is NOT a factor when estimating the costs of Amazon EC2? (Choose TWO)
    - A. The amount of time the instances will be running.
    - B. Number of security groups.
    - C. Allocated Elastic IP Addresses.
    - D. Number of Hosted Zones.
    - E. Number of instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D

      A hosted zone is a container for records, and records contain information about how you want to route traffic for a specific domain. So "Hosted Zone" is not availability zone! It is not related to EC2.
    </details>

120. A user has opened a "Production System Down" support case to get help from AWS Support after a production system disruption. What is the expected response time for this type of support case?
    - A. 12 hours.
    - B. 15 minutes.
    - C. 24 hours.
    - D. One hour.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      Need to remember the following:
      * General guidance: <24 hours
      * System impaired: < 12 hours
      * Production system impaired: < 4 hours
      * Production system down: < 1 hour
      * Business-critical system down: < 15 miniutes
    </details>

121. Which of the following should be taken into account when performing a TCO analysis regarding the costs of running an application on AWS VS on-premises? (Choose TWO)
    - A. Labor and IT costs.
    - B. Cooling and power consumption.
    - C. Amazon EBS computing power.
    - D. Software architecture.
    - E. Software compatibility.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
    </details>

122. Which AWS Service provides integration with Chef to automate the configuration of EC2 instances?
    - A. AWS Config.
    - B. AWS OpsWorks.
    - C. AutoScaling.
    - D. AWS CloudFormation.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Need to remember this. Amazon OpsWorks is associated with Chef and Puppet.
    </details>

123. A customer is seeking to store objects in their AWS environment and to make those objects downloadable over the internet. Which AWS Service can be used to accomplish this?
    - A. Amazon EBS.
    - B. Amazon EFS.
    - C. Amazon S3.
    - D. Amazon Instance Store.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

124. A company is migrating a web application to AWS. The application’s compute capacity is continually utilized throughout the year. Which of the below options offers the company the most cost-effective solution?
    - A. On-demand Instances.
    - B. Dedicated Hosts.
    - C. Spot Instances.
    - D. Reserved Instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

125. Which of the following will help AWS customers save on costs when migrating their workloads to AWS?
    - A. Use servers instead of managed services.
    - B. Use existing third-party software licenses on AWS.
    - C. Migrate production workloads to AWS edge locations instead of AWS Regions.
    - D. Use AWS Outposts to run all workloads in a cost-optimized environment.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Need to focus on costs.

      A: managed services are often cheaper.

      C: edge location is only for cache content delivery, not for other production workloads.

      D: AWS Outposts are expensive in general.
    </details>

126. What should you do if you see resources, which you don’t remember creating, in the AWS Management Console? (Choose TWO)
    - A. Stop all running services and open an investigation.
    - B. Give your root account password to AWS Support so that they can assist in troubleshooting and securing the account.
    - C. Check the AWS CloudTrail logs and delete all IAM users that have access to your resources.
    - D. Open an investigation and delete any potentially compromised IAM users.
    - E. Change your AWS root account password and the passwords of any IAM users.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D, E

      "You don't remember creating" -> potentially unauthorized access.

      A: would be what you can do if you forget to stop services.

      B: Absolutely not.

      C: "deleting all IAM users" is too extreme.

      D and E: are to fix the security problems.
    </details>

127. Availability Zones within a Region are connected over low-latency links. Which of the following is a benefit of these links?
    - A. Create private connection to your data center.
    - B. Achieve global high availability.
    - C. Automate the process of provisioning new compute resources.
    - D. Make synchronous replication of your data possible.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      "low latency" == fast. The question is about what is a benefit of "having fast connection".
    </details>

128. Which of the following are true regarding the languages that are supported on AWS Lambda? (Choose TWO)
    - A. Lambda only supports Python and Node.js, but third party plugins are available to convert code in other languages to these formats.
    - B. Lambda natively supports a number of programming languages such as Node.js, Python, and Java.
    - C. Lambda is AWS’ proprietary programming language for microservices.
    - D. Lambda doesn’t support programming languages; it is a serverless compute service.
    - E. Lambda can support any programming language using an API.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E

      First of all, AWS Lambda supports many languages. You may not remember what languages exactly.

      A: never heard of converting languages.

      B: it lists several languages using "such as". It seems to be correct.

      C: apparently wrong. Nobody will use a proprietary language.

      D: is wrong.

      E: Looks right.
    </details>
