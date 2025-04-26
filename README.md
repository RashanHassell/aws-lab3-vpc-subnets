![Screenshot 2025-04-26 183514](https://github.com/user-attachments/assets/a1019601-cb7c-4662-b777-e1ff81f2944c)
![Screenshot 2025-04-26 183415](https://github.com/user-attachments/assets/7eede572-9060-4715-b2d0-348f1fadd988)
![Screenshot 2025-04-26 183332](https://github.com/user-attachments/assets/a71fce7b-4d6a-4d8f-a04c-79047c275f0b)
![Screenshot 2025-04-26 183257](https://github.com/user-attachments/assets/56816ecb-d741-4a75-8a77-fd6d5f37f678)
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
