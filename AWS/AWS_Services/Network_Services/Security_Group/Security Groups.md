Acts acts at the [[Instance]] level.


In Amazon Web Services (AWS), security groups are a fundamental component of network security that control inbound and outbound traffic to and from AWS resources such as instances (virtual servers) and [[Elastic load balancer]]s. Security groups act as virtual firewalls, allowing you to specify rules that dictate which traffic is allowed or denied based on certain criteria.

## Important stuff

1. **Inbound Rules:** Inbound rules define the allowed incoming traffic to resources within the security group. You can configure rules to allow traffic from specific IP ranges, source security groups, or protocols. This category focuses on controlling how external entities can access your AWS resources.

2. **Outbound Rules:** Outbound rules determine the outgoing traffic from resources within the security group. These rules specify which resources can communicate with external systems or services. Outbound rules are important for controlling the communication initiated by your AWS resources.

3. **Application Layer Filtering:** Security groups can also be used to implement application layer filtering. You can define rules based on protocols and port numbers to control which services or applications are accessible through the security group. This helps restrict unauthorized access to specific applications running on your instances.

1. **Enforcement of Least Privilege:** Security groups adhere to the [[Principle of least Privilege]], which means that by default, all incoming traffic is denied, and you explicitly define rules to allow necessary traffic. This approach enhances security by limiting potential attack vectors.
    
5. **Dynamic and Elastic:** Security groups are dynamic and can be changed on-the-fly. Changes to security group rules take effect immediately, which enables you to adapt to changing security requirements or network configurations.
    
6. **Integration with AWS Resources:** Security groups can be associated with various AWS resources, including [[Amazon EC2]] instances, [[Amazon RDS]] databases, and [[Elastic Load Balancer]]s. This integration allows you to control access to resources at the network level.
