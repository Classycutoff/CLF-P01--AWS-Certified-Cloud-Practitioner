Amazon S3 Standard-Infrequent Access (S3 Standard-IA)

S3 Standard-IA is for data that is accessed less frequently, but requires rapid access when needed. S3 Standard-IA offers the high durability, high throughput, and low latency of S3 Standard, with a low per GB storage price and per GB retrieval charge. This combination of low cost and high performance make S3 Standard-IA ideal for long-term storage, backups, and as a data store for disaster recovery files. S3 Storage Classes can be configured at the object level and a single bucket can contain objects stored across S3 Standard, S3 Intelligent-Tiering, S3 Standard-IA, and S3 One Zone-IA. You can also use S3 Lifecycle policies to automatically transition objects between storage classes without any application changes.

**Key Features:**

- Same low latency and high throughput performance of S3 Standard  
    
- Designed for durability of 99.999999999% of objects across multiple Availability Zones  
    
- Resilient against events that impact an entire Availability Zone  
    
- Data is resilient in the event of one entire Availability Zone destruction  
    
- Designed for 99.9% availability over a given year  
    
- Backed with the [Amazon S3 Service Level Agreement](https://aws.amazon.com/s3/sla/) for availability
- Supports SSL for data in transit and encryption of data at rest
- S3 Lifecycle management for automatic migration of objects to other S3 Storage Classes