On AWS, the responsibility for enabling [[Encryption|Encryption]] for a given service is shared between AWS as the cloud provider and the customer who is using the service. The division of responsibilities depends on the type of encryption, whether it's in transit or at rest.

1. **Encryption [[In Transit]]:** AWS is responsible for providing encryption in transit for its services. This means that AWS ensures that data moving between different components and services within its infrastructure is encrypted during transmission. For example, when data is sent between an [[Amazon EC2]] instance and an [[Amazon RDS]] database, AWS ensures that the communication is encrypted using secure protocols like [[TLS]]/[[SSL]].
    
2. **Encryption [[At Rest]]:** The responsibility for enabling encryption at rest is often shared between AWS and the customer, depending on the service and configuration.
    
    - **AWS-Managed Services:** For some AWS-managed services like Amazon RDS (Relational Database Service), [[AWS S3]] (Simple Storage Service), and [[Amazon EBS]] (Elastic Block Store), AWS provides options to enable encryption at rest. AWS manages the encryption process and key management for these services. Customers can enable encryption while creating or configuring these services through the [[AWS Management Console]] or [[API]].
        
    - **Customer-Managed Services:** For services where customers have more control over the underlying infrastructure, such as EC2 instances or self-managed databases, customers are responsible for implementing encryption at rest. This involves selecting and configuring encryption mechanisms at the OS, file system, or database level. AWS provides guidance and best practices for implementing encryption at rest on these types of services.
        

It's important to note that AWS offers various encryption options and features, and the specifics can vary depending on the service, region, and use case. Additionally, [[AWS Key Management Service]] (KMS) is a central component that allows customers to manage encryption keys for their AWS resources, including both in transit and at rest encryption.