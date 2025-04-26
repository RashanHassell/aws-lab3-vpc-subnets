# aws-lab3-vpc-subnets
AWS Lab 3 - Build a VPC with Public and Private Subnets. Created Public and Private Subnets, configured routing, launched EC2 instances, and connected via SSH.
AWS Lab 3: Build a VPC with Public and Private Subnets
Summary:
Created a custom VPC (10.0.0.0/16) with a Public Subnet (10.0.1.0/24) and a Private Subnet (10.0.2.0/24).

Configured an Internet Gateway and attached it to the VPC.

Created Public Route Table for the Public Subnet and a Private Route Table for the Private Subnet.

Launched an EC2 Instance into the Public Subnet with SSH key pair access.

Launched an EC2 Instance into the Private Subnet for backend simulation.

Successfully SSH connected into the Public EC2 using the FinalKey.pem key.

Began IAM Role setup for Systems Manager to enable private instance access (full connection pending NAT Gateway setup).

Skills Demonstrated:
VPC networking fundamentals

Subnet creation and CIDR allocation

Route table configuration

EC2 instance deployment

Key pair and SSH authentication

IAM role creation for secure access

Troubleshooting private subnet access

Screenshots:
Subnets (Public and Private created)

Route Tables setup (Public and Private associated)

EC2 Instances deployed (Public and Private)

SSH successful connection into Public Instance
