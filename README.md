## VPC

## Ex.4 Deployment and configuration of a Private Cloud in AWS

## Aim:

To set up of a Private Cloud in AWS.

## Setting up of a private cloud in AWS:

Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC), involves creating a logically isolated virtual network that you can use to launch AWS resources. This provides you with full control over your virtual networking environment, including resource placement, connectivity, and security. Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual networking environment, including resource placement, connectivity, and security. Get started by setting up your VPC in the AWS service console. Next, add resources to it such as Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS) instances. Finally, define how your VPCs communicate with each other across accounts, Availability Zones, or AWS Regions.

## Procedure:

## 1. Plan Your VPC:
● Determine your needs:
Define your use case, including application requirements, security needs, and compliance standards.

● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.

● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering redundancy and performance.

● Plan internet connectivity:
Determine if you need public internet access and how to configure it.

● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure environment.

## 3. Create Your VPC:
Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.  Choose "Create VPC": Initiate the VPC creation process. Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and other necessary settings. Create subnets: Define subnets within your VPC to isolate different parts of your network. Create route tables: Specify how traffic is routed within and outside the VPC.  Create security groups: Define access control rules for your resources.

## 4. Deploying Resources:
Launch EC2 instances: Create and launch virtual machines within your VPC.  Set up RDS instances: Deploy databases for your applications. Configure networking: Connect your resources to the appropriate subnets, security groups, and route tables. Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

## 5.Managing and Monitoring:
Use AWS CloudWatch: Monitor your VPC and resources for performance and health. Configure logging and auditing: Track access and activity within your VPC for security and compliance. Implement security best practices: Regularly review and update your security configuration. Scale and adjust as needed: Adjust your VPC infrastructure to meet changing demands.

## Output:

# Create VPC:

![image](https://github.com/user-attachments/assets/228aff71-e90d-4445-87f7-9f1640ff2ba6)


# Configure subnets:

![image](https://github.com/user-attachments/assets/432ed7f3-a562-4284-9ae2-c6e4cb77fec8)

![image](https://github.com/user-attachments/assets/bf0cf6ba-330b-4440-82e2-140d16d29641)


# Setting Internet Gateway:

![image](https://github.com/user-attachments/assets/7271afe4-b52f-4baf-a20b-ed1ac2032cb7)

![image](https://github.com/user-attachments/assets/738157cb-a28b-4a46-8df9-4e874ca542e6)

![image](https://github.com/user-attachments/assets/af57f4f1-bcd8-4176-a300-659bb623ff3a)


# Creating Route Table:

![image](https://github.com/user-attachments/assets/dc26c25f-5d9c-4ff4-8582-5e4bc016ac8c)


# Configuring Route Table:

![image](https://github.com/user-attachments/assets/d7949cb8-8d81-41d6-a119-0eec980842c3)

# Editing Routes:

![image](https://github.com/user-attachments/assets/30129483-9589-49d5-a13d-b9a5527adcd6)

# Creating Route Table:

![image](https://github.com/user-attachments/assets/dd892d0a-64d3-4adf-9337-f130cda5e88f)

## Result:

Thus, a private cloud on AWS involves using VPCs has been created for a dedicated, isolated network where we can manage our resources and control access according to our requirements.
