# Terraform
This code creates the following resources on AWS using Terraform:\
VPC\
An Internet Gateway\
Custom Route Table\
Subnet\
Subnet Association with the Route Table\
Security Group to allow port 22, 80, 443\
Network interface with an IP in the subnet that was created in step 4\
Assign an elastic IP to the network interface created in step 7\
Ubuntu server and install/enable apache2