The discipline of sustainability addresses the long-term environmental, economic, and societal impact of your business activities. You can find prescriptive guidance on implementation in the [Sustainability Pillar whitepaper](https://docs.aws.amazon.com/wellarchitected/latest/sustainability-pillar/sustainability-pillar.html).


--------
## Important Concepts
- Six Design Principles

------------

### Design Principles

There are six design principles for sustainability in the cloud:

- Understand your impact
- Establish sustainability goals
- Maximize utilization
- Anticipate and adopt new, more efficient hardware and software offerings
- Use managed services
- Reduce the downstream impact of your cloud workloads

### Best Practices

Choose AWS [[Region]]s where you will implement workloads based on your business requirements and sustainability goals.

User behavior patterns can help you identify improvements to meet sustainability goals. For example, scale infrastructure down when not needed, position resources to limit the network required for users to consume them, and remove unused assets.

Implement software and architecture patterns to perform load smoothing and maintain consistent high utilization of deployed resources. Understand the performance of your workload components, and optimize the components that consume the most resources.

Analyze data patterns to implement data management practices that reduce the provisioned storage required to support your workload. Use lifecycle capabilities to move data to more efficient, less performant storage when requirements decrease, and delete data that’s no longer required.

Analyze hardware patterns to identify opportunities that reduce workload sustainability impacts by minimizing the amount of hardware needed to provision and deploy. Select the most efficient hardware for your individual workload.

In your development and deployment process, identify opportunities to reduce your sustainability impact by making changes, such as updating systems to gain performance efficiencies and manage sustainability impacts. Use automation to manage the lifecycle of your development and test environments, and use managed device farms for testing.