# AWS-OpenVPN-Setup
### STEP-1 : Created a VPC network of CIDR range 10.0.0.0/16
![step-1](https://github.com/user-attachments/assets/52e577d2-42d9-45f1-8ee3-5d1a0a55db54)

### STEP-2 :Inside this VPC, created two subnets.
1.	Subnet-1 (Public)
•	Name- Public_subnet
•	CIDR: 10.0.27.0/24
•	Web-server
•	Availability-Zone: us-east-1a
2.	Subnet-2 (Private)
•	Name- Private_subnet
•	CIDR:10.0.28.0/24
•	Database-server
•	Availability-Zone:us-east-1b


