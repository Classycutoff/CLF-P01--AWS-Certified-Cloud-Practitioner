# AWS Certified Cloud Practitioner (CLF-C01) Exam Guide
---------
## Introduction

The AWS Certified Cloud Practitioner (CLF-C01) exam is intended for individuals who can effectively demonstrate an overall knowledge of the AWS Cloud independent of a specific job role.
The exam validates a candidate’s ability to complete the following tasks:

- Explain the value of the AWS Cloud
- Understand and explain the AWS shared responsibility model
- Understand security best practices
- Understand AWS Cloud costs, economics, and billing practices
- Describe and position the core AWS services, including compute, network, databases, and storage
- Identify AWS services for common use cases
-----
## Target candidate description
The target candidate should have 6 months, or the equivalent, of active engagement with the AWS Cloud, with exposure to AWS Cloud design, implementation, and/or operations. Candidates will demonstrate an understanding of well-designed AWS Cloud solutions.

### Recommended AWS knowledge
The target candidate should have the following knowledge:

- AWS Cloud concepts
- Security and compliance within the AWS Cloud
- Understanding of the core AWS services
- Understanding of the economics of the AWS Cloud

**What is considered out of scope for the target candidate?**
The following is a non-exhaustive list of related job tasks that the target candidate is not expected to be able to perform. These items are considered out of scope for the exam:
- Coding
- Designing cloud architecture
- Troubleshooting
- Implementation
- Migration
- Load and performance testing
- Business applications (for example, Amazon Alexa, Amazon Chime, Amazon WorkMail)

To view a detailed list of specific tools and technologies that might be covered on the exam, as well as lists of in-scope AWS services, refer to the Appendix.

--------




## Exam Content

### **Response types**
There are two types of questions on the exam:
- Multiple choice: Has one correct response and three incorrect responses (distractors)
- Multiple response: Has two or more correct responses out of five or more response options

Select one or more responses that best complete the statement or answer the question. Distractors, or incorrect answers, are response options that a candidate with incomplete knowledge or skill might choose. Distractors are generally plausible responses that match the content area.

Unanswered questions are scored as incorrect; there is no penalty for guessing. The exam includes 50 questions that will affect your score.

### **Unscored content**

The exam includes 15 unscored questions that do not affect your score. AWS collects information about candidate performance on these unscored questions to evaluate these questions for future use as scored questions. These unscored questions are not identified on the exam.

### Exam results

The AWS Certified Cloud Practitioner exam is a pass or fail exam. The exam is scored against a minimum standard established by AWS professionals who follow certification industry best practices and guidelines. 

Your results for the exam are reported as a scaled score of 100–1,000. The minimum passing score is 700. Your score shows how you performed on the exam as a whole and whether or not you passed. Scaled scoring models help equate scores across multiple exam forms that might have slightly different difficulty levels.

Your score report may contain a table of classifications of your performance at each section level. This information is intended to provide general feedback about your exam performance. The exam uses a compensatory scoring model, which means that you do not need to achieve a passing score in each section. You need to pass only the overall exam.

Each section of the exam has a specific weighting, so some sections have more questions than others. The table contains general information that highlights your strengths and weaknesses. Use caution when interpreting section-level feedback.

### Content outline

This exam guide includes weightings, test domains, and objectives for the exam. It is not a comprehensive listing of the content on the exam. However, additional context for each of the objectives is available to help guide your preparation for the exam. The following table lists the main content domains and their weightings. The table precedes the complete exam content outline, which includes the additional context. The percentage in each domain represents only scored content.



| Domain                            | % of Exam |
|-----------------------------------|-----------|
| Domain 1: Cloud Concepts          | 26 %      |
| Domain 2: Security and Compliance | 25 %      |
| Domain 3: Technology              | 33 %      |
| Domain 4: Billing and Pricing     | 16 %      |
| TOTAL                             | 100 %     |


### Domain 1: [[Cloud Concepts]]

#### 1.1 Define the AWS Cloud and its value proposition

- Define the [[Benefits of the AWS cloud]] including:
	- [[AWS/AWS_Concepts/Well-Architected_Framework/Security]]
	- [[Reliability]]
	- [[High Availability]]
	- [[Elasticity]]
	- [[Agility]]
	- [[Pay-as-you-go]] pricing
	- [[Scalability]]
	- [[Global Reach]]
	- [[Economy of scale]]
	- Check out both [[Benefits of the AWS cloud]] and [[Well-Architected Framework]] to get the whole picture.
- Explain how the AWS cloud allows users to focus on business value
	- Shifting technical resources to revenue-generating activities as opposed to managing infrastructure

#### 1.2 Identify aspects of AWS Cloud economics

- Define items that would be part of a Total Cost of Ownership proposal ([[TCO]])
	- Understand the role of operational expenses ([[OpEx]])
	- Understand the role of capital expenses ([[CapEx]])
	- Understand[[ labor costs]] associated with on-premises operations
	- Understand the impact of [[software licensing costs]] when moving to the cloud
- Identify which operations will be [[reducing costs by moving to the cloud]]
	- [[Right-sized infrastructure]]
	- [[Benefits of automation]]
	- [[Reduce compliance scope]] (for example, reporting)
	- Managed services (for example, [[Amazon RDS]], [[Amazon ECS]], [[Amazon EKS]], [[Amazon DynamoDB]])

#### 1.3 Explain the different cloud architecture design principles

- Explain the [[design principles]]
	- [[Design for failure]]
	- [[Decouple components versus monolithic architecture]]
	- [[Implement elasticity in the cloud versus on-premises]]
	- [[Think parallel]]
---------------
### Domain 2: [[Security and Compliance]]

#### 2.1 Define the AWS shared responsibility model

- Recognize the elements of the [[Shared Responsibility Model]]
- Describe the [[Customer responsibility]] on AWS
	- Describe how the customer’s responsibilities may shift depending on the service used (for example with [[Amazon RDS]], [[AWS Lambda]], or [[Amazon EC2]])
- Describe [[AWS responsibility]]

#### 2.2 Define AWS Cloud security and compliance concepts

- Identify where to find AWS [[compliance services]] information
	- Locations of lists of recognized available compliance controls (for example, [[HIPAA]], [[SOC]]s)
	- Recognize that compliance requirements vary among AWS services
- At a high level, describe how customers achieve compliance on AWS
	- Identify different encryption options on AWS (for example, [[In Transit]], [[At Rest]])
- Describe [[who enables encryption on AWS]] for a given service
- Recognize there are services that will aid in auditing and reporting
	- Recognize that logs exist for [[audit]]ing and [[monitor]]ing (do not have to understand the logs)
	- Define [[Amazon CloudWatch]], [[AWS Config]], and [[AWS CloudTrail]]
- Explain the [[Principle of least Privilege]].

#### 2.3 Identify AWS access management capabilities

- Understand the purpose of User and Identity Management 
	- [[Access Key]]s and password policies (rotation, complexity)
	- Multi-Factor Authentication ([[MFA]])
	- AWS Identity and Access Management ([[AWS IAM]])
		- [[IAM User Groups]]/[[IAM Users]]
		- [[IAM Roles]]
		- [[IAM Policies]], managed policies compared to custom policies
- [[Tasks that require use of root accounts]]
- [[Protection of root accounts]]

#### 2.4 Identify resources for security support

- Recognize there are different network security capabilities
	- Native AWS services (for example, [[security groups]], Network [[ACLs]]s, [[AWS WAF]])
	- 3rd party security products from the [[AWS Marketplace]]
- Recognize there is documentation and where to find it (for example, best practices, whitepapers, official documents)
	- [[AWS Knowledge Center]], [[AWS Security Hub]], security forum, and security blogs
	- Partner Systems Integrators
- Know that security checks are a component of [[AWS Trusted Advisor]]
-----------



### Domain 3: [[Technology]]


#### 3.1 Define methods of deploying and operating in the AWS Cloud

- Identify at a high level different ways of provisioning and operating in the AWS cloud
	- Programmatic access, [[API]]s, [[SDK]]s, [[AWS Management Console]], [[CLI]], Infrastructure as Code ([[IaC]])
- Identify [[Different types of cloud deployment]] models
	- All in with cloud/[[cloud native]]
	- [[Hybrid Cloud]]
	- [[On-premises]]
- Identify connectivity options
	- [[VPN]]
	- [[AWS Direct Connect]]
	- [[Public internet]]

#### 3.2 Define the AWS global infrastructure

- Describe the relationships among [[Region]]s, [[Availability Zone]]s, and [[Edge Location]]s
- Describe how to achieve [[high availability]] through the use of multiple Availability Zones
	- Recall that high availability is achieved by using multiple Availability Zones
	- Recognize that Availability Zones do not share single points of failure
- Describe when to consider the use of multiple AWS Regions
	- Disaster recovery/business continuity
	- Low latency for end-users
	- Data sovereignty
- Describe at a high level the [[benefits of Edge Locations]]
	- [[AWS CloudFront]]
	- [[AWS Global Accelerator]]
#### 3.3 Identify the core AWS services

- Describe the [[categories of services]] on AWS (compute, storage, network, database)
- Identify AWS compute services
	- Recognize there are different compute families
	- Recognize the different services that provide compute (for example, [[AWS Lambda]] compared to Amazon Elastic Container Service ([[Amazon ECS]]), or [[Amazon EC2]], etc.)
	- Recognize that [[elasticity]] is achieved through [[Auto Scaling]]
	- Identify the purpose of load balancers ([[Elastic Load Balancer]])
- Identify different AWS storage services
	- Describe [[AWS S3]]
		- Describe Amazon S3 [[Glacier]]
	- Describe Amazon Elastic Block Store ([[Amazon EBS]])
	- Describe [[Snow Family]]
		- Describe [[AWS Snowball]]
	- Describe Amazon Elastic File System ([[Amazon EFS]])
	- Describe [[AWS Storage Gateway]]
- Identify AWS networking services
	- Identify [[AWS VPC]]
	- Identify [[Security Groups]]
	- Identify the purpose of [[AWS Route 53]]
	- Identify [[VPN]], [[AWS Direct Connect]]
- Identify different AWS database services
	- Install databases on Amazon EC2 compared to AWS managed databases

	- Identify [[Amazon RDS]]
	- Identify [[Amazon DynamoDB]]
	- Identify [[AWS Redshift]]
	- Identify [[Amazon Aurora]]


#### 3.4 Identify resources for technology support

- Recognize there is documentation (best practices, whitepapers, [[AWS Knowledge Center]], forums, blogs)
- Identify the various levels and scope of AWS support
	- [[AWS Abuse]]
	- AWS support cases
	- Premium support
	- [[AWS Technical Account Manager]]
- Recognize there is a partner network (marketplace, third-party) including Independent Software Vendors and System Integrators
- Identify sources of AWS technical assistance and knowledge including professional services, solution architects, training and certification, and the [[Amazon Partner Network]]
- Identify the benefits of using [[AWS Trusted Advisor]]
-------
### Domain 4: [[Billing and Pricing]]

#### 4.1 Compare and contrast the various pricing models for AWS (for example, On-Demand Instances, Reserved Instances, and Spot Instance pricing)

- Identify scenarios/best fit for [[On-Demand]] Instance pricing
- Identify scenarios/best fit for [[Reserved]]-Instance pricing
	- Describe Reserved-Instances flexibility
	- Describe Reserved-Instances behavior in [[AWS Organizations]]
- Identify scenarios/best fit for [[Spot]] Instance pricing

#### 4.2 Recognize the various account structures in relation to AWS billing and pricing

- Recognize that consolidated billing is a feature of [[AWS Organizations]]
- Identify [[how multiple accounts aid in allocating costs]] across departments

#### 4.3 Identify resources available for billing support

- Identify ways to get billing support and information
	- [[AWS Cost Explorer]], [[AWS Cost and Usage Report]], [[Amazon QuickSight]], third-party partners, and [[AWS Marketplace ]]tools
	- Open a billing support case
	- The role of the [[Concierge ]]for [[Enterprise Support]] customers
- Identify where to find pricing information on AWS services
	- [[AWS Simple Monthly Calculator]]
	- [[AWS Services product pages]]
	- [[AWS Pricing API]]
- Recognize that alarms/alerts exist
- Identify how tags are used in cost allocation
-----------

## Appendix

### Which key tools, technologies, and concepts might be covered on the exam?

The following is a non-exhaustive list of the tools and technologies that could appear on the exam. This list is subject to change and is provided to help you understand the general scope of services, features, or technologies on the exam. The general tools and technologies in this list appear in no particular order. AWS services are grouped according to their primary functions. While some of these technologies will likely be covered more than others on the exam, the order and placement of them in this list are no indication of
relative weight or importance:

- [[API]]s
- [[AWS Cost Explorer]]
- [[AWS Cost and Usage Report]]
- AWS Command Line Interface ([[CLI]])
- [[Elastic Load Balancer]]s
- Amazon [[Amazon EC2]] instance types (for example, [[Reserved]], [[On-Demand]], [[Spot]])
- AWS global infrastructure (for example, AWS [[Region]]s, [[Availability Zone]]s)
- Infrastructure as Code ([[IaC]])
- Amazon Machine Images ([[AMI]]s)
- AWS [[AWS Management console]]
- [[AWS Marketplace]]
- [[AWS Professional Services]]
- AWS [[Personal Health Dashboard]]
- [[Security Groups]]
- AWS [[Service Catalog]]
- [[AWS Service Health Dashboard]]
- [[AWS Service quotas]]
- AWS software development kits ([[SDK]]s)
- [[AWS Support Center]]
- AWS Support tiers ([[Support Plans]])
- Virtual private networks ([[VPN]]s)

## AWS services and features

#### Analytics:
- [[Amazon Athena]]
- [[Amazon Kinesis]]
- [[Amazon QuickSight]]
#### Application Integration:
- Amazon Simple Notification Service ([[AWS SNS]])
- Amazon Simple Queue Service ([[AWS SQS]])

#### Compute and Serverless:
- [AWS Batch]
- [[Amazon EC2]]
- [[AWS Elastic Beanstalk]]
- [[AWS Lambda]]
- [[Amazon Lightsail]]
- [[AWS WorkSpaces]]

#### Containers:
- Amazon Elastic Container Service ([[Amazon ECS]])
- Amazon Elastic Kubernetes Service ([[Amazon EKS]])
- [[AWS Fargate]]

#### Database:
- [[Amazon Aurora]]
- [[Amazon DynamoDB]]
- [[Amazon ElastiCache]]
- [[Amazon RDS]]
- [[AWS Redshift]]

#### Developer Tools:
- [[AWS CodeBuild]]
- [[AWS CodeCommit]]
- [[AWS CodeDeploy]]
- [[AWS CodePipeline]]
- [[AWS CodeStar]]

#### Customer Engagement:
- [[Amazon Connect]]
#### Management, Monitoring, and Governance:
AWS [[Auto Scaling]]
[[AWS Budgets]]
[[AWS CloudFormation]]
[[AWS CloudTrail]]
[[Amazon CloudWatch]]
[[AWS Config]]
[[AWS Cost and Usage Report]]
[[Amazon EventBridge]] (Amazon CloudWatch Events)
[[AWS License Manager]]
[[AWS Managed Services]]
[[AWS Organizations]]
AWS [[Secrets Manager]]
[[AWS Systems Manager]]
[[AWS Systems Manager Parameter Store]]
[[AWS Trusted Advisor]]

#### Networking and Content Delivery:
Amazon [[API]] Gateway
[[AWS CloudFront]]
[[AWS Direct Connect]]
[[AWS Route 53]]
[[AWS VPC]]
#### Security, Identity, and Compliance:
- [[AWS Artifact]]
- [[AWS Certificate Manager ]](ACM)
- [[AWS CloudHSM]]
- [[AWS Cognito]]
- [[AWS Detective]]
- [[AWS GuardDuty]]
- AWS Identity and Access Management ([[AWS IAM]])
- [[AWS Inspector]]
- [[AWS License Manager]]
- [[AWS Macie]]
- [[AWS Shield]]
- [[AWS WAF]]

#### Storage:
- [[AWS Backup]]
- Amazon Elastic Block Store ([[Amazon EBS]])
- Amazon Elastic File System ([[Amazon EFS]])
- [[AWS S3]]
- Amazon S3 [[Glacier]]
- [[AWS Snowball Edge]]
- [[AWS Storage Gateway]]
