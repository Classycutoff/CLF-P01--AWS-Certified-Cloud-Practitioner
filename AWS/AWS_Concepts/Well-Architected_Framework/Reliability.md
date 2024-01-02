The reliability pillar encompasses the ability of a [workload](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.workload.en.html "The set of components that together deliver business value.") to perform its intended function correctly and consistently when it’s expected to. This includes the ability to operate and test the [workload](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.workload.en.html "The set of components that together deliver business value.") through its total lifecycle. This paper provides in-depth, [best practice](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.best-practice.en.html "Proven ways of achieving successful outcomes.") guidance for implementing reliable [workloads](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.workload.en.html "The set of components that together deliver business value.") on AWS.

---------
## Important Concepts
- [[Loosely Coupled architecture]]
- 5 Design Principles
- Design the architecture to reduce inter-dependecies

--------
### Design Principles

There are five design principles for reliability in the cloud:

- Automatically recover from failure
- Test recovery procedures
- Scale horizontally to increase aggregate workload availability
- Stop guessing capacity
- Manage change in automation

### Best Practices

Before building any system, foundational requirements that influence reliability should be in place. For example, you must have sufficient network bandwidth to your data center. These requirements are sometimes neglected (because they are beyond a single project’s scope). With AWS, however, most of the foundational requirements are already incorporated or can be addressed as needed.

The cloud is designed to be nearly limitless, so it’s the responsibility of AWS to satisfy the requirement for sufficient networking and compute capacity, leaving you free to change resource size and allocations on demand.

A reliable workload starts with upfront design decisions for both software and infrastructure. Your architecture choices will impact your workload behavior across all six AWS Well-Architected pillars. For reliability, there are specific patterns you must follow, such as loosely coupled dependencies, graceful degradation, and limiting retries.

Changes to your workload or its environment must be anticipated and accommodated to achieve reliable operation of the workload. Changes include those imposed on your workload, like a spikes in demand, as well as those from within such as feature deployments and security patches.

Low-level hardware component failures are something to be dealt with every day in an on-premises data center. In the cloud, however, these are often abstracted away. Regardless of your cloud provider, there is the potential for failures to impact your workload. You must therefore [take steps to implement resiliency](https://docs.aws.amazon.com/whitepapers/latest/disaster-recovery-workloads-on-aws/shared-responsibility-model-for-resiliency.html) in your workload, such as fault isolation, automated failover to healthy resources, and a disaster recovery strategy.

--------------
- **Redundancy:** Cloud providers operate data centers in multiple geographic regions, offering redundancy and backup capabilities that enhance the reliability of your applications and data.
- **Data Backup and Recovery:** Regular automated backups and disaster recovery solutions are often provided by cloud platforms, minimizing the risk of data loss and downtime.
- **Data Durability:** Cloud storage services have built-in redundancy, ensuring data durability even in the face of hardware failures.
