# High Availability

High availability in cloud computing refers to the ability of cloud services to maintain seamless operations and access to resources even in the face of hardware failures, network issues, or other disruptions. Cloud providers achieve high availability through redundancy, failover mechanisms, and load balancing, ensuring minimal downtime and uninterrupted service for users.

If it is needed to have high availability, you can :
- Deploy the application to span across multiple [[Availability Zone]]s.
	- Deploying applications to multiple AZs replicates applications across multiple data centers in the same Region, supporting high availability.
- Utilize a multi-[[Region]] deployment when deploying the application.
	- Multi-Region deployments are best for applications that have extremely high availability requirements.
- Utilize Load Balancing ([[Elastic Load Balancer]]):
	- Load balancers distribute traffic across multiple instances or resources, improving application availability and preventing overload on any single resource.