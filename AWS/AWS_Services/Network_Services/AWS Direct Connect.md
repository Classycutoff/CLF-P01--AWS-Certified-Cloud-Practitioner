Direct Connect is a private (bypasses the public internet), dedicated physical network connection from your on-premises data center to AWS. Since the connection is private, it is extremely fast. [https://aws.amazon.com/directconnect/](https://aws.amazon.com/directconnect/ "undefined")

------

[AWS Direct Connect](http://aws.amazon.com/directconnect/) makes it easy to establish a dedicated connection from an on-premises network to one or more [[AWS VPC]]s. AWS Direct Connect can reduce network costs, increase bandwidth throughput, and provide a more consistent network experience than internet-based connections. It uses industry-standard 802.1Q VLANs to connect to Amazon VPC using private IP addresses. The VLANs are configured using [virtual interfaces](https://docs.aws.amazon.com/directconnect/latest/UserGuide/WorkingWithVirtualInterfaces.html) (VIFs), and you can configure three different types of VIFs:

- **Public virtual interface** - Establish connectivity between AWS public endpoints and your data center, office, or colocation environment.
    
- **Transit virtual interface** - Establish private connectivity between AWS Transit Gateway and your data center, office, or colocation environment. This connectivity option is covered in the section [AWS Direct Connect + AWS Transit Gateway](https://docs.aws.amazon.com/whitepapers/latest/aws-vpc-connectivity-options/aws-direct-connect-aws-transit-gateway.html).
    
- **Private virtual interface** - Establish private connectivity between Amazon VPC resources and your data center, office, or colocation environment. The use of private VIFs is shown in the following figure.