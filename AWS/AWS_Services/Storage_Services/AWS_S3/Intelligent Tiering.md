Amazon S3 Intelligent-Tiering (S3 Intelligent-Tiering)

[**Amazon S3 Intelligent-Tiering (S3 Intelligent-Tiering)**](https://aws.amazon.com/s3/storage-classes/intelligent-tiering/) is the first cloud storage that automatically reduces your storage costs on a granular object level by automatically moving data to the most cost-effective access tier based on access frequency, without performance impact, retrieval fees, or operational overhead. S3 Intelligent-Tiering delivers milliseconds latency and high throughput performance for frequently, infrequently, and rarely accessed data in the Frequent, Infrequent, and Archive Instant Access tiers. You can use S3 Intelligent-Tiering as the default storage class for virtually any workload, especially data lakes, data analytics, new applications, and user-generated content.

For a small monthly object monitoring and automation charge, S3 Intelligent-Tiering monitors access patterns and automatically moves objects that have not been accessed to lower-cost access tiers. S3 Intelligent-Tiering automatically stores objects in three access tiers: one tier that is optimized for frequent access, a 40% lower-cost tier that is optimized for infrequent access, and a 68% lower-cost tier optimized for rarely accessed data. S3 Intelligent-Tiering monitors access patterns and moves objects that have not been accessed for 30 consecutive days to the Infrequent Access tier and after 90 days of no access to the Archive Instant Access tier. For data that does not require immediate retrieval, you can set up S3 Intelligent-Tiering to monitor and automatically move objects that aren’t accessed for 180 days or more to the Deep Archive Access tier to realize up to 95% in storage cost savings.

There are no retrieval charges in S3 Intelligent-Tiering. If an object in the Infrequent or Archive Instant Access tier is accessed later, it’s automatically moved back to the Frequent Access tier. If the object you’re retrieving is stored in the optional Deep Archive tiers, before you can retrieve the object, you must first restore a copy using RestoreObject.  For information about restoring archived objects, see [Restoring Archived Objects](https://docs.aws.amazon.com/AmazonS3/latest/userguide/restoring-objects.html). No additional tiering charges apply when objects are moved between access tiers within the S3 Intelligent-Tiering storage class.

**Key Features:**

- Frequent, Infrequent, and Archive Instant Access tiers have the same low-latency and high-throughput performance of S3 Standard  
    
- The Infrequent Access tier saves up to 40% on storage costs  
    
- The Archive Instant Access tier saves up to 68% on storage costs  
    
- Opt-in asynchronous archive capabilities for objects that become rarely accessed  
    
- Deep Archive Access tier has the same performance as Glacier Deep Archive and saves up to 95% for rarely accessed objects  
    
- Designed for durability of 99.999999999% of objects across multiple Availability Zones and for 99.9% availability over a given year
- Backed with the [Amazon S3 Service Level Agreement](https://aws.amazon.com/s3/sla/) for availability
- Small monthly monitoring and auto tiering charge
- No operational overhead, no lifecycle charges, no retrieval charges, and no minimum storage duration
- Objects smaller than 128KB can be stored in S3 Intelligent-Tiering but will always be charged at the Frequent Access tier rates, and are not charged the monitoring and automation charge.