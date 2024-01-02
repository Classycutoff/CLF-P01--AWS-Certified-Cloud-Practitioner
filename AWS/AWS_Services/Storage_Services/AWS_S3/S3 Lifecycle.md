# S3 Lifecycle Management

To manage your objects so that they are stored cost effectively throughout their lifecycle, configure their _Amazon S3 Lifecycle_. An _S3 Lifecycle configuration_ is a set of rules that define actions that Amazon S3 applies to a group of objects. There are two types of actions:

- **Transition actions** – These actions define when objects transition to another storage class. For example, you might choose to transition objects to the S3 Standard-IA storage class 30 days after creating them, or archive objects to the S3 Glacier Flexible Retrieval storage class one year after creating them. For more information, see [Using Amazon S3 storage classes](https://docs.aws.amazon.com/AmazonS3/latest/userguide/storage-class-intro.html).
    
    There are costs associated with lifecycle transition requests. For pricing information, see [Amazon S3 pricing](https://aws.amazon.com/s3/pricing/).
    
- **Expiration actions** – These actions define when objects expire. Amazon S3 deletes expired objects on your behalf.
    
    Lifecycle expiration costs depend on when you choose to expire objects. For more information, see [Expiring objects](https://docs.aws.amazon.com/AmazonS3/latest/userguide/lifecycle-expire-general-considerations.html).
    

If there is any delay between when an object becomes eligible for a lifecycle action and when Amazon S3 transfers or expires your object, billing changes are applied as soon as the object becomes eligible for the lifecycle action. For example, if an object is scheduled to expire and Amazon S3 does not immediately expire the object, you won't be charged for storage after the expiration time. The one exception to this behavior is if you have a lifecycle rule to transition to the S3 Intelligent-Tiering storage class. In that case, billing changes do not occur until the object has transitioned to S3 Intelligent-Tiering.