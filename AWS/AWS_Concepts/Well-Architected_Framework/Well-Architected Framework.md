# Well-Architected Framework

## Six pillars of the Framework

[Link To a good blog post about this](https://aws.amazon.com/blogs/apn/the-6-pillars-of-the-aws-well-architected-framework/)

- [[Operational Excellence]]
- [[Security]]
- [[Reliability]]
- [[Performance Efficiency]]
- [[Cost Optimization]]
- [[Sustainability]]


## General Design Principles

The Well-Architected Framework identifies a set of general design principles to facilitate good design in the cloud:

- **Stop guessing your capacity needs**: If you make a poor capacity decision when deploying a [workload](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.workload.en.html "The set of components that together deliver business value."), you might end up sitting on expensive idle resources or dealing with the [performance](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.pillar.performance.en.html "The ability to use computing resources efficiently to meet system requirements, and to maintain that efficiency as demand changes and technologies evolve.") implications of limited capacity. With cloud computing, these [problems](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.problem.en.html "An event that requires intervention and either recurs or cannot currently be resolved.") can go away. You can use as much or as little capacity as you need, and scale up and down automatically.
    
- **Test systems at production scale**: In the cloud, you can create a production-scale test environment on demand, complete your testing, and then decommission the resources. Because you only pay for the test environment when it's running, you can simulate your live environment for a fraction of the [cost](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.pillar.costOptimization.en.html "The ability to run systems to deliver business value at the lowest price point.") of testing on premises.
    
- **Automate to make architectural experimentation easier**: Automation allows you to create and replicate your [workloads](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.workload.en.html "The set of components that together deliver business value.") at low [cost](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.pillar.costOptimization.en.html "The ability to run systems to deliver business value at the lowest price point.") and avoid the expense of manual effort. You can track changes to your automation, audit the impact, and revert to previous parameters when necessary.
    
- **Allow for evolutionary architectures**: Allow for evolutionary [architectures](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.architecture.en.html "How components interact and communicate."). In a traditional environment, architectural decisions are often implemented as static, one-time [events](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.event.en.html "An instance of something happening that is significant to the workload."), with a few major versions of a system during its lifetime. As a business and its context continue to evolve, these initial decisions might hinder the system's ability to deliver changing business requirements. In the cloud, the capability to automate and test on demand lowers the risk of impact from design changes. This allows systems to evolve over time so that businesses can take advantage of innovations as a standard practice.
    
- **Drive architectures using data**: In the cloud, you can collect data on how your architectural choices affect the behavior of your [workload](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.workload.en.html "The set of components that together deliver business value."). This lets you make fact-based decisions on how to improve your [workload](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.workload.en.html "The set of components that together deliver business value."). Your cloud infrastructure is code, so you can use that data to inform your [architecture](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.architecture.en.html "How components interact and communicate.") choices and improvements over time.
    
- **Improve through game days**: Test how your [architecture](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.architecture.en.html "How components interact and communicate.") and processes perform by regularly scheduling [game days](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.gameday.en.html "Simulates a failure or event to test systems, processes, and teams responses") to simulate [events](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.event.en.html "An instance of something happening that is significant to the workload.") in production. This will help you understand where improvements can be made and can help develop organizational experience in dealing with [events](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.event.en.html "An instance of something happening that is significant to the workload.").