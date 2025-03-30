# aws-networking

How to create a Vpc
login aws account
go to AWS management console
VPC CAN BE SET IN YOUR SELECTED LOCATION
searchfor VPC
click on your VPC
theres always a default vpc and subnet when you open a AWS account
click on create VPC
name it Test-VPC

Note: the starting IP adress of your subnet shoild be the same as that of your VPC

Create subnet
create internet gateaway
create route table

Note; route table determines where the network of your vpc is directed to
attach VPC to route table, associate a subnet to it. edit the route to access internet gateway

Next thing you do is to launch an instance
go back to aws management console
search EC2
resources-instances-launch instances 
launch windown instances(sincei am using a window laptop)
choose an instance type
configue instance details
