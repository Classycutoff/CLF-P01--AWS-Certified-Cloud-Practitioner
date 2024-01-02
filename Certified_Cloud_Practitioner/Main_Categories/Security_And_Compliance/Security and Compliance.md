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
	- Recognize that logs exist for auditing and monitoring (do not have to understand the logs)
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

--------
## List of Resources
- [[Security, Identity and Compliance Services]]
	- [[AWS Certificate Manager]]
	- [[AWS Cognito]]
	- [[AWS Detective]]
	- [[AWS GuardDuty]]
	- [[AWS Inspector]]
	- [[AWS License Manager]]
	- [[AWS Macie]]
	- [[AWS Security Hub]]
	- [[STS]]
	- [[Secrets and Key Services]]
		- [[AWS CloudHSM]]
		- [[AWS Key Management Service]]
		- [[Secrets Manager]]