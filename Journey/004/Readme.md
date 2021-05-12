# Launch an EC2 instance and log into it

## Introduction

An EC2 instance is a Virtual Machine in the Cloud. AWS has a lot of types of instances that can be launched, like some Linux flavours, Microsoft Windows, and Mac.

When lauching an EC2 instance, it is possible to configure where it should be place (Region, subnet/AZ), storage type and size, IAM rules, access mode for management, Security Groups to allow inbound and outbound traffic, and so on.

The main objectives of this lab is to comprehend the basic concepts related to EC2 instances by doing the following:
- Launch a Amazon Linux EC2 instance and access it using SSH.
- Launch a Windows EC2 instance and access it through RDP.

## Prerequisite

Basic understanding of:
- EC2 Service (Security Groups, key pair, AMI, etc)
- SSH and RDP accesses

## Use Case

One of the first things that is done when learning Cloud Computing is how to use Virtual Machines in the Cloud. When using AWS, it is about launching EC2 instances.

EC2 is one of the AWS Compute Services and is widely used in a lots of real world scenarios, like providing a Web Server or an application that will analyze some kind of data.

Therefore, it is an AWS foundational service and must be known to anyone who desires to start a Cloud journey.

## Cloud Research

Useful reference links to understand the concepts and complete this lab:

- [AWS Free-Tier Pricing](https://aws.amazon.com/ebs/pricing/?nc1=h_ls)
- [What is Amazon EC2?](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)
- [Security Groups](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security-groups.html)
- [Amazon Machine Images (AMIs)](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html)
- [Key pairs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-key-pairs.html)
- [Connect to your Linux instance using SSH](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AccessingInstancesLinux.html)
- [Connect to your Windows instance](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/connecting_to_windows_instance.html)

## Try yourself

Main steps (must be followed twice: once for Amazon Linux and then for Windows):

OBS: this lab may occur in charges. Terminate the instances after finishing the lab.

- Log in the AWS Management Console
- Access the EC2 Console
- Create an EC2 instance
    - Type: t2.micro (free-tier eligible)
    - Create a new key pair or use an existing one for remote access
    - Create a new Security Group or use an existing one allowing inbound access to SSH (Linux) and RDP (Windows) to your IP address
- Wait for the instance to be in the running state
- Access the instance

## Cloud Outcome

Concepts I learned:

- Elastic Compute Cloud (EC2) is a Web service that provides resizable virtual machines in the Cloud.
- It is fundamentally composed by an AMI (Amazon Machine Image), a set of information used to configure and launch the EC2 instance.
- An EC2 instance is launched in a public subnet (by default) associated with an Availability Zone (AZ) which, in turn, is located within a Region.
    - Regions: physical locations around the World.
    - AZs: set of interconnected datacenters within a Region.
    - Subnets: range of IP addresses used to provide communication for AWS resources.
- A Security Group (SG) is a resource that acts as virtual firewall for EC2 instances. It is used to control inbound and outbound traffic. SGs only work with allow rules.  If no existing rule applies for the traffic, it is dropped (implicit deny or deny by default rule).
- Access an EC2 instance is possible by using a key pair, a set of security credentials (private and public keys) used to prove identity during connection process.

## Social Proof

[Linkedin post](https://www.linkedin.com/posts/marcio-almeida_oidani100daysofcloud-activity-6798282998409125888-boXc)
