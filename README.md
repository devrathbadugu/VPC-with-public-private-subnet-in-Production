# AWS PROJECT
# VPC-with-public-private-subnet-in-Production
This project showcases the creation of a Virtual Private Cloud (VPC) for production servers, enhancing resiliency by deploying servers across two Availability Zones using an Auto Scaling group and an Application Load Balancer. Servers are housed in private subnets, accessing the internet through a NAT gateway in each zone.

**OVERVIEW:**

•	The VPC has public subnets and private subnets in two Availability Zones.

•	Each public subnet contains a NAT gateway and a load balancer node.

•	The servers run in the private subnets are launched and terminated by using an Auto Scaling group, and receive traffic from the load balancer.

•	The servers can connect to the internet by using the NAT gateway.

**Reference Doc:**
(https://docs.aws.amazon.com/vpc/latest/userguide/vpc-example-private-subnets-nat.html)

**Reference Video:**
(https://youtu.be/FZPTL_kNvXc?si=QR8wJi_RMIlJCGnn)
