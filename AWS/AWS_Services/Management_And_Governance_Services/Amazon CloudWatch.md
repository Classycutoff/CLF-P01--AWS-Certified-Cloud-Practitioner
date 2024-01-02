## Amazon CloudWatch

AWS CloudWatch is a monitoring service. That means it allows you to monitor the performance of your AWS resources and applications.

**Where would you use AWS CloudWatch?**

- **To analyze logs** - CloudWatch is useful in exploring and analyzing logs. Why would you do that? By analyzing your logs, you might find issues that can be addressed to improve the performance of your applications. Besides that, when a resource/application fails, you can determine what happened and why by looking at the logs.
- **To monitor your applications** - For instance, you could monitor EC2 metrics such as CPU utilization, memory used, status check, network throughput, and more. It gives you insights about your application so you can act accordingly. For example, if you notice an EC2 instance is nearing capacity you can add another one to avoid degraded performance or downtime.
- **To optimize your resources** - With CloudWatch, you can specify what happens when a specific threshold is met or not. For example, terminate an EC2 instance if a condition is met. Or create additional instances to support more traffic.

Moreover, AWS CloudWatch is made up of multiple monitoring tools such as:

- **Events** - You can trigger an action based on an event. For instance, we could create an event that sends an email to the administrator when a resource fails. You specify how and when to trigger an action. Then you define what action to trigger. Thus, CloudWatch events are very useful.
- **Alarms** - With alarms, you need to define a threshold, a condition, and what to trigger. The most popular scenario is an alarm for billing. That is, trigger an alarm if the estimated charges are greater than the threshold set.
- **Logs** - CloudWatch logs allow you to store the log files for various sources such as EC2 instances, [[AWS CloudTrail]], and many more. You can then use these logs to detect issues, find leaks, patterns, and so on.

Finally, AWS CloudWatch is an excellent service that you can use to monitor the performance and metrics of your resources and applications that run in AWS. It helps you to improve and scale your applications. It also enables you to stay within a budget, and thus not having unwanted costs. Consider CloudWatch as a person that watches your applications to make sure they work correctly, and at the best prices.

--------

A CloudWatch alarm can be set up to monitor CPU utilization and trigger further action. Further action could be an [[Auto Scaling]] group adding another [[Amazon EC2]] instance and/or using [[AWS SNS]] to notify team members of the occurrence.
