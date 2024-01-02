# [[Amazon EBS]] vs [[Amazon EFS]] vs [[AWS S3]]

## **EBS: high performance, per-instance block storage**

EBS used to be accessible to a single [[Amazon EC2]] instance only, making it most like your physical hard drive. That’s still generally how it’s used (as per-instance storage), but in special cases, Amazon EBS Multi-Attach can turn EBS into multi-instance storage, like EFS. EBS Instances can be either General Purpose SSD (for general use) or Provisioned IOPS SSD, for mission-critical workloads.
### **What kind of storage is EBS?**

EBS is a block storage service, which means all data within EBS is stored in equally sized blocks. This system offers some performance advantages over traditional storage, and generally boasts lower latency, too.
### **When to use EBS?**

EBS’s use case is more easily understood than the other two. It must be paired with an EC2 instance. So when you need a high-performance storage service for a single instance, use EBS.

------------
## **EFS: scalable file storage for multiple EC2 instances**

Unlike EBS, EFS can be mounted by multiple EC2 instances, meaning many virtual machines may store files within an EFS instance. But its main feature is its scalability. EFS can grow or shrink according to demand, with more and more files being added without disturbing your application or having to provision new infrastructure.

### **What kind of storage is EFS?**

EFS is a file storage system. File storage is the system you’ll likely be most familiar with, as it’s how files are stored in the hard drive on your computer. File storage is fast and accessible, but it doesn’t offer the increased potential for complex queries that object storage does (more on that in the S3 section).

### **When to use EFS?**

EFS may be used whenever you need a shared file storage option for multiple EC2 instances with automatic, high-performance scaling. 

This makes it a great candidate for file storage for content management systems; for lift and shift operations, as its autoscaling potential means you do not need to re-architect; for application development, as EFS’s shareable file storage is ideal for storing code and media files.

----------------
## **S3: object storage for complex queries and archived data**

S3 is scalable, like EFS, and has access to multiple EC2 instances. However, it can also be accessed by other cloud services, and its object storage system makes it ideal for handling large volumes of static data as well as complex queries.

### **What kind of storage is S3?**

S3 is an object storage service. Unlike file storage – in which all data is organised hierarchically in a top-down network of folders – data in S3 is contained on the same flat plane, with more comprehensive metadata (labels) to make it manageable.

Think of the difference between a family tree, and a family party at which each family member is wearing a name tag. In the first scenario, people exist in hierarchal relation to one another; in the second all are milling about on equal footing. 

Having each object marked like this makes it easier to run complex queries on each object without reference to an existing hierarchy.

### **When to use S3?**

S3 is good at storing long-term data due to its archiving system. Things like reports and records, which may go unused for years, can be stored on S3 at a lower cost than the other two storage services discussed. 

As already stated, S3 is also useful for storing data on which complex queries may be run. This makes it useful for data related to customer purchases, behaviour or profiles, because that data can be easily queried and fed into analytics tools.

This  capacity for interfacing with other tools also makes S3 great for back-up and restoration, as it can be paired with Amazon Glacier for even more secure backing up.

S3 also supports static websites, so if you need to host a static HTML page, S3 is a good choice.