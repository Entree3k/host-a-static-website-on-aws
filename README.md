# host-a-static-website-on-aws

![Host_a_Static_Website_on_AWS](https://github.com/user-attachments/assets/238cadbf-ccd6-4318-ae4c-0be6d062c775)

Host a Static Website on AWS
I recently finished a DevOps project where I hosted a static html web app on AWS, utilizing the resources
listed below. I have uploaded the reference diagram and scripts I used to deploy the web app on an EC2
instance to a GitHub repository for the project. Please use this information to create a readme file for
the project.
1. Configured a Virtual Private Cloud (VPC) with both public and private subnets across two
different availability zones.
2. Deployed an Internet Gateway to facilitate connectivity between VPC instances and the wider
Internet.
3. Established Security Groups as a network firewall mechanism.
4. Leveraged two Availability Zones to enhance system reliability and fault tolerance.
5. Utilized Public Subnets for infrastructure components like the NAT Gateway and Application Load
Balancer.
6. Implemented EC2 Instance Connect Endpoint for secure connections to assets within both public
and private subnets.
7. Positioned web servers (EC2 instances) within Private Subnets for enhanced security.
8. Enabled instances in both the private Application and Data subnets to access the Internet via the
NAT Gateway.
9. Hosted the website on EC2 Instances.
10. Employed an Application Load Balancer and a target group for evenly distributing web traffic to
an Auto Scaling Group of EC2 instances across multiple Availability Zones.
11. Utilized an Auto Scaling Group to automatically manage EC2 instances, ensuring website
availability, scalability, fault tolerance, and elasticity.
12. Stored web files on GitHub for version control and collaboration.
13. Secured application communications using a Certificate Manager.
14. Configured Simple Notification Service (SNS) to alert about activities within the Auto Scaling
Group.
15. Registered the domain name and set up a DNS record using Route 53
