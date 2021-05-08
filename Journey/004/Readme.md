# Launch an EC2 instance and log into it

## Introduction

An EC2 instance is a Virtual Machine in the Cloud. AWS has a lot of types of instances that can be launched, like some Linux flavours, Microsoft Windows, and Mac.

When lauching an EC2 instance, it is possible to configure where it should be place (subnet/AZ), storage type and size, IAM rules, access mode for management, Security Groups to allow inbound and outbound traffic, and so on.

The main objectives of this lab are the following:
- Launch a Amazon Linux EC2 instance and access it using SSH.
- Launch a Windows EC2 instance and access it through RDP.

## Prerequisite

Basic understanding of the following AWS Services:
- EC2
- Security Groups
- Basic understanding of SSH and RDP protocols

## Use Case

One of the first things that is done when learning Cloud Computing is how to use Virtual Machines in the Cloud. When using AWS, it is about launching EC2 instances.

EC2 is one of the AWS Compute Services and is widely used in a lots of real world scenarios, like providing a Web Server or an application that will analyze some kind of data.

Therefore, it is an AWS foundational service and must be known to anyone who desires to start a Cloud journey.

## Cloud Research


https://github.com/100DaysOfCloud/100DaysOfCloudIdeas/blob/master/Projects/COM/COM03/COM03-AWS100.md

Useful reference links to understand the concepts and complete this lab:

- EC2[]()
- SG[]()
- SSH[]()
- RDP[]()

## Try yourself

Main steps (must be followed twice: once for Amazon Linux and then for Windows):

- Log in the AWS Management Console
- Access the EC2 Console
- Create an EC2 instance
    - Create just one Security Group
    - Allow inbound access to the required protocols: SSH (Linux) and RDP (Windows)
- Wait for the instance to be in the running state
- Access the instance

## Cloud Outcome

Concepts I learned:

- What is a region?
- What is an availability zone?
- What is a public subnet?
- How many subnets can there be in one region?
- How to launch EC2 instances in public / private subnets?
- What are AMIs?
- What are security groups?
- What are inbound/outbound rules?
- what is deny By default rule in security groups?
- How to allow access to EC2 from security groups?
- How to connect to EC2 instances from your machine?
- How to setup your simple static site with ec2?

## Social Proof

[Linkedin post]()