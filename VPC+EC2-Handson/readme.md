This Projects mainly concentrates on creating VPC, two ec2 linux instances one to be placed in public subnet  and other in the private subnet. One can access the pubic subnet using Internet gateway Internet gateway for public access to public subnet, where as the private subnet has only access within the vpc.

Create VPC
1)Name                   : Demo VPC
2)VPC CIDR               : 10.0.0.0/16

Create Subnets:
Public Subnet:
CIDR : 10.0.0.0/24
Availabily-zone : ap-south-1a
Private Subnet:
CIDR : 10.0.1.0/24
Availabily-zone : ap-south-1b
