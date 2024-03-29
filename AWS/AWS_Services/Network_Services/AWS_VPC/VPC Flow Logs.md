
[[AWS VPC]] Flow Logs is a feature that enables you to capture information about the IP traffic going to and from network interfaces in your VPC. Flow log data can be published to the following locations: Amazon [[Amazon CloudWatch]] Logs, Amazon [[AWS S3]], or Amazon [[Kinesis Data Firehose]]. After you create a flow log, you can retrieve and view the flow log records in the log group, bucket, or delivery stream that you configured.

Flow logs can help you with a number of tasks, such as:

- Diagnosing overly restrictive security group rules
    
- Monitoring the traffic that is reaching your instance
    
- Determining the direction of the traffic to and from the network interfaces
    

Flow log data is collected outside of the path of your network traffic, and therefore does not affect network throughput or latency. You can create or delete flow logs without any risk of impact to network performance.