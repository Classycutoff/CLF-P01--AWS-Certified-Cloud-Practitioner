In the context of cloud services, durability refers to the ability to maintain data integrity and availability over time, even in the face of hardware failures, data corruption, or other unforeseen events.

- Redundancy
- Data Replication
- Data Backups
- Data Integrity Checks

-----

### Cloudguru question
A DevOps engineer is planning for the deployment of an application that can't be impacted if an entire geographic location is affected by a disaster. How can the engineer deploy this application?

-------

AWS logically groups its [[Region]]s into geographic locations. Each Region is spread out and fully independent and isolated from other Regions. If there's a flood, tsunami or earthquake in 1 Region, the other Regions will not be impacted. Because of this, it makes sense to deploy your application to multiple Regions.