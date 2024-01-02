### AWS Snowball

AWS Snowball is available as a Compute Optimized device or a Storage Optimized device. Explore the options best suited for your needs. All devices are suited for extreme conditions, tamper proof, and highly secure.

- Storage
	- 80 TB - 210 TB

--------

## How it works

In the [AWS Snow Family console](https://console.aws.amazon.com/importexport/home), select your preferred device, either Snowball [[Edge]] Compute Optimized or Snowball [[Edge]] Storage Optimized. Create a job with an Amazon [[AWS S3]] bucket, select Amazon Simple Notification Service (Amazon [[AWS SNS]]): [LINK](https://aws.amazon.com/sns/) for tracking, and configure options like Amazon EC2 AMIs and a GPU. AWS prepares and ships the device to you, and you receive it in approximately 4-6 days. Once the device arrives, power it up and use AWS OpsHub to unlock it. Connect to your [[LAN]]. Use AWS OpsHub to manage the device, transfer data, or launch EC2 instances. When done, shut down and return the device to AWS. The shipping label automatically appears on the E Ink screen. When the device arrives at the AWS [[Region]], any data stored in your on-board bucket(s) is moved to your S3 bucket and verified in about the same time it took you to load the device. All data is then securely erased from the device, and it is sanitized of any customer information.