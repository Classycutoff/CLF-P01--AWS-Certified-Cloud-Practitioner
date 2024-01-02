# Amazon Inspector

Automated and continual vulnerability management at scale.

AWS Inspector is a security assessment service that helps you evaluate the security and compliance of your applications deployed on AWS. It assesses the vulnerabilities and deviations from best practices in your application's network configurations, operating systems, and applications. AWS Inspector provides insights and recommendations to help you remediate potential security vulnerabilities.

Key features of AWS Inspector:

- Scans instances for vulnerabilities, security misconfigurations, and deviations from security best practices.
- Generates detailed assessment reports with prioritized findings.
- Supports integration with other AWS services like [[AWS CloudFormation]] and AWS Systems Manager.
- Provides guidance on how to remediate security issues.

---------
Amazon Inspector is a service that automates security assessments and network accessibility testing for AWS [[Amazon EC2]] instances. It aids in the detection of vulnerabilities in your EC2 instances and apps. Furthermore, it enables you to make security testing a more frequent event as part of the development and IT operations.

Amazon Inspector displays a clear list of security and compliance issues that have been prioritized by severity level. Furthermore, these discoveries may be analyzed directly or as part of full evaluation records accessible through the API or the AWS Inspector UI. AWS Inspector security evaluations assist you in detecting unauthorized network access to EC2 instances as well as vulnerabilities on those EC2 instances.

It operates by first defining a target set of resources using tags, then configuring an assessment template that defines what we’re looking for (common vulnerabilities and exploits (CVEs), PCI requirements, and so on) and running an assessment against our target resources, examining the research results and reducing the issues discovered.