# Access Control Lists (ACLs)
------------------
Network ACLs is an optional layer of security for your [[VPC]] that ensures the proper traffic is allowed into the [[subnet]].

Access Control Lists (ACLs) are a security mechanism used in computer systems and networks to control access to resources, such as files, folders, devices, or network services. ACLs define the permissions and restrictions that determine who can access a particular resource and what actions they can perform on it. They are commonly used to enforce security and maintain the confidentiality, integrity, and availability of data.


## AWS S3 ACLs
[[AWS S3]] access control lists (ACLs) enable you to manage access to buckets and objects. Each bucket and object has an ACL attached to it as a subresource. It defines which AWS accounts or groups are granted access and the type of access. When a request is received against a resource, Amazon S3 checks the corresponding ACL to verify that the requester has the necessary access permissions.

S3 Object Ownership is an Amazon S3 bucket-level setting that you can use to both control ownership of the objects that are uploaded to your bucket and to disable or enable ACLs. By default, Object Ownership is set to the bucket owner enforced setting, and all ACLs are disabled. When ACLs are disabled, the bucket owner owns all the objects in the bucket and manages access to them exclusively by using access-management policies.