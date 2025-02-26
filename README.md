# Capstone Project - Wordpress Site on AWS
Project scenario: A small to medium sized digital marketing agency, “DigitalBoost” wants to enhance it’s online presence by creating a high performance Wordpress-based website for their clients. The agency needs a scalable, secure, and cost effective solution that can handle increasing traffic and seamlessly integrate with their existing infrastructure. My task as an AWS solution architect is to design and implement a Wordpress solution using various AWS services, such as networking, compute, object storage and databases.

## VPC Setup
Objective: Create a VPC to isolate and secure the Wordpress architecture.
- Define IP address range for the VPC
![Create-VPC](./img/1-create-vpc.png)

- Create VPC with public subnet
![Create-public-subnet](./img/2-create-public-subnet.png)

- Create private subnet
![create-private-subnet](./img/3-create-private-subnet.png)

- Create public route table
![create-route-table](./img/4-create-route-table.png)

- Public route table association
![public-rt-association](./img/5-publicRT-association.png)

- Create private route table
![create-private-rt](./img/6-create-private-RT.png)

- Private route table association
![private-rt-association](./img/7-private-RT-association.png)

- Create internet gateway
![create-internet-gateway](./img/8-create-internet-gateway.png)

- Attach internet gateway to VPC
![attach-igw-to-vpc](./img/9-attach-IGW-VPC.png)

- Add route for public subnet
![add-route-for-public-subnet](./img/10-add-route-for-public-subnet.png)

- Create NAT gateway
![create-nat-gateway](./img/11-create-NAT.png)

- Add route for private subnet
![add-route-for-private-subnet](./img/12-add-route-for-private.png)

- Create EFS
![create-efs](./img/13-create-efs.png)
