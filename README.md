# Introduction 
This is a CloudFormation template to set up an architecture which consists of an EC2 instance running a web server deployed in a public subnet and an RDS instance running MySQL in a private subnet. The web server running on the EC2 instance accesses the database hosted on the MySQL instance to retrieve and update data.
We use the Cafe Web application.
It deploys the basic resources, including the VPC subnet(s), the proper security group(s), the EC2 instance and the RDS instance, using a CloudFormation template.
