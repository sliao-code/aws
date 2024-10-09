1. Which of the following is true regarding the AWS availability zones and edge locations?
    - A. Edge locations are located in separate Availability Zones worldwide to serve global customers.
    - B. An availability zone exists within an edge location to distribute content globally with low latency.
    - C. An Availability Zone is a geographic location where AWS provides multiple, physically separated and isolated edge locations.
    - D. An AWS Availability Zone is an isolated location within an AWS Region, however edge locations are located in multiple cities worldwide.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      A: Edge locations are not located in separate AZ.

      B: incorrect.

      C: the statement seems to be about Regions, not AZ.
    </details>

2. A company is developing a mobile application and wants to allow users to use their Amazon, Apple, Facebook, or Google identities to authenticate to the application. Which AWS Service should the company use for this purpose?
    - A. Amazon GuardDuty.
    - B. Amazon Personalize.
    - C. Amazon Cognito.
    - D. AWS IAM.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      Remember the followings:

      Amazon GuardDuty: is a threat detection service that monitors for malicious activity and anomalous behavior to protect AWS accounts, workloads, and data.

      Amazon Personalize: accelerates your digital transformation with ML, making it easier to integrate personalized recommendations into existing websites, applications, email marketing systems, and more.

      Amazon Cognito lets you easily add user sign-up and authentication to your mobile and web apps. Amazon Cognito also enables you to authenticate users through an external identity provider and provides temporary security credentials to access your app's backend resources in AWS or any service behind Amazon API Gateway.

      AWS IAM cannot do external authentication.
    </details>

3. Which AWS Service can perform health checks on Amazon EC2 instances?
    - A. AWS CloudFormation.
    - B. Amazon Route 53.
    - C. Amazon Chime.
    - D. Amazon Aurora.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Amazon Route 53 performs three main functions: domain registration, DNS routing, and health checking. Remember these!

      Amazon Chime is a communications service that lets you meet, chat, and place business calls inside and outside your organization, all using a single application.

      Amazon Aurora is a relational database management system (RDBMS) built for the cloud with full MySQL and PostgreSQL compatibility.
    </details>

4. Which of the following are examples of AWS-managed databases? (Choose TWO)
    - A. Amazon Neptune.
    - B. Amazon CloudSearch.
    - C. Microsoft SQL Server on Amazon EC2.
    - D. MySQL on Amazon EC2.
    - E. Amazon RDS for MySQL.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E

      B: it is not a database service.

      C & D: Anything running on EC2 are not AWS-managed.

      Remember the following services! They are the often-asked services in certification test.

      Amazon Neptune is a fast, fully managed database service powering graph use cases such as identity graphs, knowledge graphs, and fraud detection.

      Amazon RDS is a fully managed, open-source cloud database service that allows you to easily operate and scale your relational database.
    </details>

5. You need to migrate a large number of on-premises workloads to AWS. Which AWS service is the most appropriate?
    - A. AWS File Transfer Acceleration.
    - B. AWS Server Migration Service.
    - C. AWS Database Migration Service.
    - D. AWS Application Discovery Service.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      If you are not familiar with all the services mentioned, the key of this question is to __migrate__ large number of __on-premise workload__. It doesn't mention what kinds of workloads, so the service should be more generic. A is specific to file transfer. C is specific to database. D doesn't look like a migration service.

      AWS File Transfer Acceleration: can speed up content transfers to and from Amazon S3 by as much as 50-500% for long-distance transfer of larger objects.

      AWS Server Migration Service: Provides End-to-End System Design, Deployment, Migration, Support, & Management Services.

      AWS Database Migration Service: provides migration solution from databases, data warehouses, and other type of data stores (eg S3, SAP).

      AWS Application Discovery Service: helps you plan migrations to the cloud by collecting usage and configuration data about your on-premises servers.
    </details>

6. What are some key benefits of using AWS CloudFormation? (Choose TWO)
    - A. It helps AWS customers deploy their applications without worrying about the underlying infrastructure.
    - B. It applies advanced IAM security features automatically.
    - C. It automates the provisioning and updating of your infrastructure in a safe and controlled manner.
    - D. It allows you to model your entire infrastructure in just a text file.
    - E. It compiles and builds application code in a timely manner.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, D

      A: Clound Formation is a tool for configuring the infrastructure. AWS customers still need to worry about the infrastructure. The lowes level or AWS is Infrastructure as a Service.

      B: CloudFormation needs to provide details for IAM security by customers, not automatically. It may automate the process. "Automatically" means the system will do thing for customers. "Automate process" means the customers write the process in a scripts or configuration file, and the process can be executed repeatedly without rewriting them.

      E: CloudFormation only configures the infrastructure, not specifically do application compiling or building.
    </details>

7. Which statement is true in relation to the security of Amazon EC2?
    - A. You should use instance store volumes to store login data.
    - B. You should regularly patch the operating system and applications on your EC2 instances.
    - C. You should deploy critical components of your application in the Availability Zone that you trust.
    - D. You can track all API calls using Amazon Athena.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      A: instance store volumes are temporary storage. They are lost after stopping EC2.

      B: EC2 is managed by customers, not AWS. So customers are responsible of all work (OS, patching, etc) except hardware and environemnt.

      C: All AZs are equally trustable, except for governemnt compliance.

      D: Amazon Athena is a serverless, interactive analytics service that provides a simplified and flexible way to analyze petabytes of data where it lives. It is not for track API calls. Amazon CloudTrail is for tracking API calls.
    </details>

8. What does AWS Cost Explorer provide to help manage your AWS spend?
    - A. Cost comparisons between AWS Cloud environments and on-premises environments.
    - B. Accurate estimates of AWS service costs based on your expected usage.
    - C. Consolidated billing.
    - D. Highly accurate cost forecasts for up to 12 months ahead.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS cloud costs and usage over time.

      A: It doesn't do comparison with on-premise.

      B: This is very similar with D. I think it is incorrect because the tool only forecasts the cost estomates up to 12 months.
    </details>

9. You are using several on-demand EC2 Instances to run your development environment. What is the best way to reduce your charges when these instances are not in use?
    - A. Deleting all EBS volumes attached to the instances.
    - B. You cannot minimize charges for on-demand instances.
    - C. Terminating the instances.
    - D. Stopping the instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      To reduce cost of unused on-demand EC2 instances is to stop them.

      A: the question is not about storage costs.

      B: incorrect.

      Terminating vs Stopping EC2: Terminating EC2 also deletes the associated EBS volumes. Stopping EC2 only put EC2 to __Stopped__ status. The instance will not be charged for usage, but any attached EBS volumes and Elastic IPs will still be charged. The data on the EBS volume will remain, but the data on the local hard drive will be lost.
    </details>

10. Which of the following are factors should be considered for Amazon EBS pricing? (Choose TWO)
    - A. The size of volumes provisioned per month.
    - B. The compute capacity you consume.
    - C. The amount of data you have stored in snapshots.
    - D. The compute time you consume.
    - E. The number of Snowball storage devices you request.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C

      A: size is a factor of pricing.

      B: compute capacity is not related to EBS.

      C: amount of data is part of pricing.

      D: compute time is not related to storage.

      E: Snowball storage is not related to EBS.
    </details>

11. Which of the following has the greatest impact on cost? (Choose TWO)
    - A. Compute charges.
    - B. The number of services used.
    - C. Data Transfer In charges.
    - D. Data Transfer Out charges.
    - E. The number of IAM roles provisioned.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D

      A: compute charges are important part fo costs.

      B: number of serives used don't translate costs. It is how much usage time of the services that matter for costs.

      C: Data Transfer In charges are less. Many services don't charge Data Transfer In.

      D: Data Transfer Out is charged by most of services.

      E: number of IAM roles provisioned doesn't translate to costs.
    </details>

12. Who from the following will get the largest discount?
    - A. A user who chooses to buy On-demand, Convertible, Partial upfront instances.
    - B. A user who chooses to buy Reserved, Convertible, All upfront instances.
    - C. A user who chooses to buy Reserved, Standard, No upfront instances.
    - D. A user who chooses to buy Reserved, Standard, All upfront instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      All upfront has always larger discount than partial upfront or no upfront. So the answer is either B or D.

      Convertible is more expensive than Reserved instances, so the answer is D.
    </details>

13. What does the term “Economies of scale” mean?
    - A. It means that you save more when you consume more.
    - B. It means as more time passes using AWS, you pay more for its services.
    - C. It means that AWS will continuously lower costs as it grows.
    - D. It means that you have the ability to pay as you go.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
      
      Economics of scale mean cheaper unit price when scale becomes larger.

      A, B are the opposite. D has nothing to do with "scale".

    </details>

14. Which of the following services provide real-time auditing for compliance and vulnerabilities? (Choose TWO)
    - A. AWS Config.
    - B. Amazon Redshift.
    - C. Amazon MQ.
    - D. AWS Trusted Advisor.
    - E. Amazon Cognito.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D

      Need to remember what are these services.

      AWS Config: is a config tool that helps you assess, audit, and evaluate the configurations and relationships of your resources.

      Amazon RedSshift: data warehouse service.

      Amazon MQ: is a managed message broker service for Apache ActiveMQ and RabbitMQ that simplifies setup and operation of open-source message brokers on AWS.

      AWS Trusted Advisor: inspects your AWS environment and provides recommendations to improve performance, security, and cost optimization.
    
      Amazon Cognito: helps you implement customer identity and access management (CIAM) into your web and mobile applications.
    </details>

15. Which of the following AWS services uses Puppet to automate how EC2 instances are configured?
    - A. AWS OpsWorks.
    - B. AWS CloudFormation.
    - C. AWS Quick Starts.
    - D. AWS CloudTrail.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Puppet and Chef are associated with AWS OpsWorks.
    </details>

16. Which of the following are use cases for Amazon EMR? (Choose TWO)
    - A. Enables you to backup extremely large amounts of data at very low costs.
    - B. Enables you to move Exabyte-scale data from on-premises datacenters into AWS.
    - C. Enables you to analyze and process extremely large amounts of data in a timely manner.
    - D. Enables you to easily run and scale Apache Spark, Hadoop,and other Big Data frameworks.
    - E. Enables you to easily run and manage Docker containers.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, D

      Amazon EMR: is a cloud big data platform for running large-scale distributed data processing jobs, interactive SQL queries, and machine learning applications.

      only C and D are related to big data.

      A: is about backup.

      B: is about data transfer.

      E: is about container.
    </details>

17. Your CTO has asked you to contact AWS support using the chat feature to ask for guidance related to EBS. However, when you open the AWS support center you can't see a way to contact support via Chat. What should you do?
    - A. There is no chat feature in AWS support.
    - B. The chat feature is available for all plans for an additional fee, but you have to request it first.
    - C. At a minimum, upgrade to Business support plan.
    - D. Upgrade from the Basic Support plan to Developer Support.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      Chat is only available to Business Support and above.

      Need to refresh and remember different levels of support and what include.
    </details>

18. Which of the following strategies help analyze costs in AWS?
    - A. Using tags to group resources.
    - B. Using AWS CloudFormation to automate the deployment of resources.
    - C. Deploying resources of the same type in different regions.
    - D. Configuring Amazon Inspector to automatically analyze costs and email reports.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      This is a tricky one. D seems to be the answer, but Amazon Inspector is for scanning vulnerability, not for costs.

      B: is for configuring infrastructure.

      C: is about deploying resiurces.

      A: tagging group resources can help to tracking costs of different categories.
    </details>

19. Which service can you use to route traffic to the endpoint that provides the best application performance for your users worldwide?
    - A. AWS Global Accelerator.
    - B. AWS Data Pipeline.
    - C. AWS DAX Accelerator.
    - D. AWS Transfer Acceleration.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Since it is about application performance worldwide, I woild choose A.

      B, C and D look like data transfer services.
    </details>

20. You have a real-time IoT application that requires sub-millisecond latency. Which of the following services should you use?
    - A. Amazon Redshift.
    - B. Amazon Athena.
    - C. AWS Cloud9.
    - D. Amazon ElastiCache for Redis.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      A: is for data warehouse.

      B: Amazon Athena is a serverless, interactive analytics service that provides a simplified and flexible way to analyze petabytes of data where it lives.

      C: AWS Cloud9 is a cloud-based integrated development environment (IDE) that lets you write, run, and debug your code with just a browser.

      Amazon ElastiCache is a fully managed Redis OSS and Memcached-compatible service delivering __real-time__, cost-optimized performance for modern applications.
    </details>

21. You are facing a lot of problems with your current contact center. Which service provides a cloud-based contact center that can deliver a better service for your customers?
    - A. Amazon Lightsail.
    - B. Amazon Connect.
    - C. AWS Direct Connect.
    - D. AWS Elastic Beanstalk.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Amazon Lightsail Is a Powerful Virtual Server That Is Built for Reliability & Performance.

      Amazon Connect Lets You Build Reliable and Inexpensive Automatic Calling Services. 

      AWS Direct Connect is a cloud service that links your network directly to AWS to deliver consistent, low-latency performance.

      AWS Elastic Beanstalk helps you deploy and manage web applications with capacity provisioning, app health monitoring, and more.
    </details>

22. Which of the following are valid Amazon EC2 Reserved Instance types? (Choose TWO)
    - A. Convertible.
    - B. Expedited.
    - C. Bulk.
    - D. Spot.
    - E. Standard.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E

      Need to review and remember all EC2 types abd subtypes.
    </details>

23. Which of the following services gives you access to all AWS auditor-issued reports and certifications?
    - A. AWS Artifact.
    - B. AWS Config.
    - C. Amazon CloudWatch.
    - D. AWS CloudTrail.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Review compliance section.
    </details>

24. You manage a blog on AWS that has different environments: development, testing, and production. What can you use to create a custom console for each environment to view and manage your resources easily?
    - A. AWS Resource Groups.
    - B. AWS Placement Groups.
    - C. AWS Management Console.
    - D. AWS Tag Editor.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      AWS Resource Groups is the service that lets you manage and automate tasks on large numbers of resources at one time.

      AWS Placement Groups is a logical grouping of instances within an Availability Zone that helps you to influence the placement of individual EC2 instances to meet specific requirements for performance, latency, or compliance.

      AWS Tag Editor enables you to effectively manage tags. Tags are key and value pairs that act as metadata for organizing your AWS resources.
    </details>

25. An organization needs to build a financial application that requires support for ACID transactions. Which AWS database service is most appropriate in this case?
    - A. RedShift.
    - B. RDS.
    - C. CloudHSM.
    - D. DMS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      RedShift is a data warehouse service.

      provides total access management control and protection for your encryption keys with secure and compliant hardware security modules (HSMs).

      DMS is database migration service.

      So only RDS is a real database service.
    </details>

26. Which of the following AWS services would help you migrate on-premise databases to AWS?
    - A. AWS DMS.
    - B. Amazon S3 Transfer Acceleration.
    - C. AWS Directory Service.
    - D. AWS Transit Gateway.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      See the last question.
    </details>

27. For new AWS customers, what is the EASIEST way to launch a simple WordPress website on AWS?
    - A. Run WordPress on an Amazon Lightsail instance.
    - B. Install WordPress on an Amazon EC2 instance.
    - C. Use the Amazon S3 Web hosting feature.
    - D. Host the website directly on AWS Cloud Development Kit (AWS CDK).

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      WordPress is a dynamic web server. So Amazon S3 is only for static web pages.

      "Easiest" --> full managed service --> LightSail.
    </details>

28. Which of the following services allows you to install and run custom relational database software?
    - A. Amazon EC2.
    - B. Amazon Cognito.
    - C. Amazon RDS.
    - D. Amazon Inspector.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Amazon RDS is a fully managed service.

      Only EC2 allows customers to install their own DB.
    </details>

29. What are some key design principles for designing public cloud systems? (Choose TWO)
    - A. Reserved capacity instead of on demand.
    - B. Loose coupling over tight coupling.
    - C. Servers instead of managed services.
    - D. Disposable resources instead of fixed servers.
    - E. Multi-AZ deployments instead of multi-region deployments.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D

      A: is not true for all scenarios.

      C: is not true for all scenarios.

      E: is a bit confusing, but there are circumstances multiple-regions are preferred.

      so answers are B and D. The key for this question is: is the statement suitable for all circumstances. There is a catch here. Fixed servers may be needed, but it is not preferred if possible (we are talking about AWS).
    </details>

30. You have developed a web application targeting a global audience. Which of the following will help you achieve the highest redundancy and fault tolerance from an infrastructure perspective?
    - A. There is no need to architect for these capabilities in AWS, as AWS is redundant by default.
    - B. Deploy the application in a single Availability Zone.
    - C. Deploy the application in multiple Availability Zones in a single AWS region.
    - D. Deploy the application in multiple Availability Zones in multiple AWS regions.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      the key words are: global, high redundancy and fault tolerance.

      global --> multiple regions
      high redudancy and fault tolerance --> multiple AZs.
    </details>

31. Which of the following factors affect Amazon CloudFront cost? (Choose TWO)
    - A. Number of Requests.
    - B. Traffic Distribution.
    - C. Number of Volumes.
    - D. Instance type.
    - E. Storage Class.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B

      CloudFront delivers your content through a worldwide network of data centers called edge locations. It is a content delivery service.

      Pricing is based on data transfer out and number of requests.

      "Traffic Distribution" is a confusing word. Compared to C, D, E, its seems to be related to data transfer.
    </details>

32. Which of the following is NOT a benefit of using AWS Lambda?
    - A. AWS Lambda runs code without provisioning or managing servers.
    - B. AWS Lambda provides resizable compute capacity in the cloud.
    - C. There is no charge when your AWS Lambda code is not running.
    - D. AWS Lambda can be called directly from any mobile app.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      AWS Lambda is a fully managed, acalable compute service. Only charged when running.

      A --> fully managed.

      B --> scalable.

      C --> charged only whenn running.

      D: no garantee of mobile access.
    </details>

33. Who is responsible for scaling a DynamoDB database in the AWS Shared Responsibility Model?
    - A. Your security team.
    - B. Your development team.
    - C. AWS.
    - D. Your internal DevOps team.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      DyanmoDB is a fully managed DB service, so AWS is reponsible of scaling it.
    </details>

34. What are the benefits of the AWS Organizations service? (Choose TWO)
    - A. Control access to AWS services.
    - B. Help organizations design and maintain an accelerated path to successful cloud adoption.
    - C. Manage your organization’s payment methods.
    - D. Help organization achieve their desired business outcomes with AWS.
    - E. Consolidate billing across multiple AWS accounts.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E
    </details>

35. Which feature enables users to sign into their AWS accounts with their existing corporate credentials?
    - A. Federation.
    - B. Access keys.
    - C. IAM Permissions.
    - D. WAF rules.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      To enable users to use their existing corporate credentials to sign in AWS accounts, there should be a service to connect or map the corporate credentials to AWS credentials.

      B: access keys are just keys to access AWS.

      C: it is just permissions, not signin credentials.

      D: WAF seems to be related to web.

      So guess it is A.

      Federation: allows organizations to securely provide access to their AWS resources and services without creating and managing AWS user identities. Instead, users can sign in using their existing corporate credentials from a trusted external identity provider (IdP) like Microsoft Active Directory, Facebook, Google, or another OpenID Connect-compatible provider.
    </details>

36. Which of the following procedures can reduce latency when your end users are retrieving data? (Choose TWO)
    - A. Store media assets in the region closest to your end users.
    - B. Store media assets on an additional EBS volume and increase the capacity of your server.
    - C. Replicate media assets to at least two availability zones.
    - D. Reduce the size of media assets using the Amazon Elastic Transcoder.
    - E. Store media assets in S3 and use CloudFront to distribute these assets.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E

      To reduce latency: reduce distance, increase connection speed.

      A: reduce distance

      B: has nothing to do with reducing latency.

      C: enhance availability and reliability, not latency.

      D: This will reduce the total access time, not latency.

      E: CloudFront is a content delivery service. It has cache to reduce latency.
    </details>

37. Which of the following are part of the seven design principles for security in the cloud? (Choose TWO)
    - A. Use manual monitoring techniques to protect your AWS resources.
    - B. Use IAM roles to grant temporary access instead of long-term credentials.
    - C. Scale horizontally to protect from failures.
    - D. Enable real-time traceability.
    - E. Never store sensitive data in the cloud.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D

      If know nothing, it takes some guess.

      A: manual monitoring doesn't seem right.

      B: it is correct.

      C: it is not about security.

      E: its is not always correct. A lot of data in teh cloud are sensitive data.
      
      Seven design principles of security in Cloud:
      1) __Defense in depth__: Use multiple independent layers of defense to make it harder for attackers to gain access to an asset. 
      2) __Automation__: Use automation to reduce the likelihood of human error. For example, you can set up automated security sweeps that run at regular intervals and alert the right team member when there's a problem. 
      3) __Data classification__: Use a classification system to determine what level of security your data needs. Then, secure your data using encryption, tokenization, or access control. 
      4) __Limit human access__: Use tools to reduce the need for human access to data. 
      5) __Prepare for security events__: Create an incident management and investigation policy, and train your team members on how to respond. 
      6) __Security as Code (SaC)__: Use SaC to automate security practices, such as vulnerability assessments, remediation, and security scanning. 
      7) __Stay up to date__: Stay up to date with security threats and recommendations. 
    </details>

38. What is one of the advantages of the Amazon Relational Database Service (Amazon RDS)?
    - A. It simplifies relational database administration tasks.
    - B. It provides 99.99999999999% reliability and durability.
    - C. It automatically scales databases for loads.
    - D. It enables users to dynamically adjust CPU and RAM resources.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Amazon RDS is a fully managed RDB service.

      A: looks right.

      B: its seems right, but it is not one of the advantages of RDS, because all AWS storage provides this type of reliability.

      C: It will auto scale for resources, not to scale database to fit resources, e.g. loads.

      D: it is fully managed.
    </details>

39. Which AWS service allows companies to connect an Amazon VPC to an on-premises data center? (Select TWO)
    - A. AWS VPN.
    - B. Amazon Redshift.
    - C. API Gateway.
    - D. Amazon Direct Connect.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D

      to directly connect on-premise data center to AWS, there are two ways:
      * VPN is always a way to connect between outside network to comapny network.
      * Amazon Direct Connect is a service offered by AWS to do that.
      
      B: is a data warehouse serice.
      C: doesn't do private connection.
    </details>

40. Which task is AWS responsible for in the shared responsibility model for security and compliance?
    - A. Granting access to individuals and services.
    - B. Encrypting data in transit.
    - C. Updating Amazon EC2 host firmware.
    - D. Updating operating systems.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      A: customers control account access.

      B: Customers are responsible of their own data.

      C: AWS is reponsible of EC2 hardware including firmware. The firmware is considered to be part of hardware function. It is below OS level.

      D: OS is customers' responsibility for EC2.
    </details>

41. According to the AWS shared responsibility model what is the sole responsibility of AWS?
    - A. Application security.
    - B. Edge location management.
    - C. Patch management.
    - D. Client-side data.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      AWS is alwaya responsible of hardware, environemnt, building, etc.

      A: Custmoers are responsible of application related things.

      C: for EC2, customers are responsible of patching OS, application, etc. Customers are always responsible of their own application patching.

      D: Any application, client-side, or other data are customers' responsibility.
    </details>

42. Which of the following are pillars of the AWS Well-Architected Framework? (Select TWO)
    - A. Multiple Availability Zones.
    - B. Performance efficiency.
    - C. Security.
    - D. Encryption usage.
    - E. High availability.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C

      Please review and __remember__ the 5 pillars of AWS.

      Operational excellence
      * Security
      * Reliability
      * Performance efficiency
      * Cost optimization
      * Sustainability: 
    </details>

43.  Which AWS service identifies security groups that allow unrestricted access to a user’s AWS resources?
    - A. AWS Trusted Advisor.
    - B. Amazon Inspector.
    - C. Amazon CloudWatch.
    - D. AWS CloudTrail.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Please __remember__ the differences of theses services.

      A: Trusted Advisor helps you __optimize costs__, increase __performance__, __improve security__ and resilience, and operate at scale in the cloud.

      B: Amazon Inspector automatically discovers workloads, such as Amazon EC2 instances, containers, and Lambda functions, and scans them for __software vulnerabilities and unintended network exposure__.

      C: Amazon CloudWatch monitors your Amazon Web Services (AWS) resources and the applications you run on AWS in real time. You can use CloudWatch to collect and track metrics, which are variables you can measure for your resources and applications. __It primarily monitors resource usages__.

      D: AWS CloudTrail Track __user activity and API usage__ on AWS and in hybrid and multicloud environments.
    </details>

44.  A company has deployed several relational databases on Amazon EC2 instances. Every month the database software vendor releases new security patches that need to be applied to the databases. What is the MOST efficient way to apply the security patches?
    - A. Connect to each database instance on a monthly basis and download and apply the necessary security patches from the vendor.
    - B. Enable automate patching for the instances using the Amazon RDS console.
    - C. In AWS Config. configure a rule for the instances and the required patch level.
    - D. Use AWS Systems Manager to automate database patching according to a schedule.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      A: this is the LEAST efficient way. So not the answer.

      B: the DB is on EC2, not on Amazon RDS. Users have to do patch by themselves.

      C: AWS Config is a config tool that helps you assess, audit, and evaluate the configurations and relationships of your resources. It doesn't seem to manage patching.

      D: AWS Systems Manager is a management service that helps you automatically collect software inventory, apply OS patches, create system images, and configure Windows and Linux operating systems. 
    </details>

45.  Which of the following is a benefit of using the AWS Cloud?
    - A. Permissive security removes the administrative burden.
    - B. Ability to focus on revenue-generating activities.
    - C. Control over cloud network hardware.
    - D. Choice of specific cloud hardware vendors.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      A: incorrect. 

      C, D: It is AWS responsibility.
    </details>

46.  Which of the following are categories of AWS Trusted Advisor? (Select TWO)
    - A. Fault Tolerance.
    - B. Instance Usage.
    - C. Infrastructure.
    - D. Performance.
    - E. Storage Capacity.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D

      Please doiubke check and remember what AWS Trusted Advisor does. Cannot guess 100% correct.
    </details>
47.  Which AWS services provide a way to extend an on-premises architecture to the aws cloud? (Select TWO)
    - A. Amazon EBS.
    - B. Amazon Connect.
    - C. AWS Storage Gateway.
    - D. Amazon CloudFront.
    - E. AWS Direct Connect.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, E

      A: it is purely AWS service. Not related to on-premise.

      B: Amazon Connect enables intelligent automation at all stages of the customer journey with fully-integrated, self-service capabilities including chatbots, task routing, and interactive voice response. It is not related to on-premise.

      C: sounds right. Please check what it is.

      D: it is a content delivery service. Not related to o-premise.

      E: it provides direct connection between AWS and on-premise data center.
    </details>

48.  Where can AWS compliance and certification reports be downloaded?
    - A. AWS Artifact.
    - B. AWS Concierge.
    - C. AWS Certificate Manager.
    - D. AWS Trusted Advisor.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      remember this. Compliance related documents --> Artifact.
    </details>

49.  Which AWS service would you use to obtain compliance reports and certificates?
    - A. AWS Artifact.
    - B. AWS Lambda.
    - C. Amazon Inspector.
    - D. AWS Certificate Manager.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      see above.
    </details>

50.  Which AWS services are defined as global instead of regional? (Select TWO)
    - A. Amazon Route 53.
    - B. Amazon EC2.
    - C. Amazon S3.
    - D. Amazon CloudFront.
    - E. Amazon DynamoDB.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D

      Please review AWS global vs regional services!
    </details>

51.  Which of the following can an AWS customer use to launch a new Amazon Relational Database Service (Amazon RDS) cluster? (Select TWO)
    - A. AWS Concierge.
    - B. AWS CloudFormation.
    - C. Amazon Simple Storage Service (Amazon S3).
    - D. Amazon EC2 Auto Scaling.
    - E. AWS Management Console.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E

      To launch Amazon RDS, or to launch an AWS services, there are 3 ways:
      * CloudFormation
      * AWS Management Console
      * Progrmatic API
    </details>

52. Which of the following are features of Amazon CloudWatch Logs? (Select TWO)
    - A. Summaries by Amazon Simple Notification Service (Amazon SNS).
    - B. Free Amazon Elasticsearch Service analytics.
    - C. Provided at no charge.
    - D. Real-time monitoring.
    - E. Adjustable retention.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D, E

      Need to review and remember Amazon CloudWatch functions!
    </details>

53. According to the AWS shared responsibility model who is responsible for configuration management?
    - A. It is solely the responsibility of the customer.
    - B. It is solely the responsibility of AWS.
    - C. It is shared between AWS and the customer.
    - D. It is not part of the AWS shared responsibility model.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      Configuration management is a shared responsibility. Some level of configurations belongs to AWS, others belong to customers.
    </details>

54. Which AWS service allows users to identify the changes made to a resource over time?
    - A. Amazon Inspector.
    - B. AWS Config.
    - C. AWS Service Catalog.
    - D. AWS IAM.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Need to review and remember what functions of Amazon Inspector and AWS Config.

      AWS Service Catalog doesn't seem to track resource changes.

      AWS IAM is for user access management.
    </details>

55. Which benefits are included with the AWS Business Support plan? (Select TWO)
    - A. 24/7 assistance by way of live chat or a telephone call.
    - B. Support from a dedicated AWS Technical Account Manager.
    - C. An unlimited number of cases and contacts.
    - D. 15-minute response time for production system interruption cases.
    - E. Annual operational reviews with AWS Solutions Architects.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C

      Please review and remember what include in the different levels of Support!
    </details>

56. Which AWS tools assist with estimating costs? (Select three)
    - A. Detailed billing report.
    - B. Cost allocation tags.
    - C. AWS Simple Monthly Calculator.
    - D. AWS Total Cost of Ownership (TCO) Calculator.
    - E. Cost Estimator.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C, D

      A: is not for estimates.

      Cost Estimator: There is no service like this. It is called Pricing Calculator.
    </details>

57. Access keys in AWS Identity and Access Management (IM1) are used to:
    - A. Log in to the AWS Management Console.
    - B. Make programmatic calls to AWS from AWS APIs.
    - C. Log in to Amazon EC2 instances.
    - D. Authenticate to AWS CodeCommit repositories.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      AWS Access Keys are the credentials used to provide programmatic or CLI-based access to the AWS APIs.

      When using ssh to log in EC2 instances, it uses SSH key.

      Password or MFA is used to login AWS Management Console.
    </details>

58. Which AWS service can be used to query stored datasets directly from Amazon S3 using standard SQL?
    - A. AWS Glue.
    - B. AWS Data Pipeline.
    - C. Amazon CloudSearch.
    - D. Amazon Athena.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      Amazon Athena is a serverless, interactive analytics service built on open-source frameworks, supporting open-table and file formats. Athena provides a simplified, flexible way to analyze petabytes of data where it lives. Analyze data or build applications from an Amazon Simple Storage Service (S3) data lake and 30 data sources, including on-premises data sources or other cloud systems using SQL or Python.
    </details>

59. Which AWS services can host a Microsoft SQL Server database? (Select TWO)
    - A. Amazon EC2.
    - B. Amazon Relational Database Service (Amazon RDS).
    - C. Amazon Aurora.
    - D. Amazon Redshift.
    - E. Amazon S3.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B

      A: EC2 can host anything. It is equivalent to a regular computer. You can install any softwares.

      B: Amazon RDS can install major relational databases, including MS SQL server.

      C: Aurora is MySQL or Postgrel related.

      D: data warehouse.

      E: S3 is a storage service only.
    </details>

60. Which AWS IAM feature allows developers to access AWS services through the AWS CLI?
    - A. API keys.
    - B. Access keys.
    - C. User names/Passwords.
    - D. SSH keys.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Access keys are used in CLI, or programetic API access to AWS.
    </details>

61. A customer would like to design and build a new workload on AWS Cloud but does not have the AWS-related software technical expertise in-house. Which of the following AWS programs can a customer take advantage of to achieve that outcome?
    - A. AWS Partner Network Technology Partners.
    - B. AWS Marketplace.
    - C. AWS Partner Network Consulting Partners.
    - D. AWS Service Catalog.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      This is for planning, designing and implementing AWS cloud services.

      In AWS Partner Network, AWS consultants provide services to help organizations implement and manage AWS solutions, while Technology Partners provide technology products that integrate with AWS to enhance its capabilities.
    </details>
