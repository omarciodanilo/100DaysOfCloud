# Secure the root account, create and secure an IAM admin user

## Introduction

IAM (Identity and Access Management) is a crucial security service in the AWS environment. It's essentially responsible for managing access permissions to the AWS account as well as to its resources. Hence, it's necessary to understand how it works and learn the basic configurations to allow a secure access.

## Prerequisite

Basic understanding of IAM service and its main components (User, Group, Role, and Policy), as well as basic knowledge of password enforcement and MFA (Multi-Factor Authentication).

## Use Case

After creating an AWS account, the first step is to secure it. So once at least the majority of the steps in this lab are included in the IAM security best practices, I believe they are fundamental to enable some security features to any AWS account, regardless of the type and size of the project.

## Cloud Research

What is Identity and Access Management (IAM)?
What is a root user?
How is a root user different from an Admin user?
What is console access and programmatic access?
What is the access key and secret key?
What is MFA and why is it important?
What are IAM identities and how they can be created?
What are some good security practices for password policies?

Useful reference links to understand the concepts and complete this lab:

- [What is IAM?](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)
- [Your AWS account ID and its alias](https://docs.aws.amazon.com/IAM/latest/UserGuide/console_account-alias.html)
- [IAM Identities (users, groups, and roles)](https://docs.aws.amazon.com/IAM/latest/UserGuide/id.html)
- [Using multi-factor authentication (MFA) in AWS](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa.html)
- [Creating your first IAM admin user and group](https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started_create-admin-group.html)
- [Setting an account password policy for IAM users](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_passwords_account-policy.html?icmpid=docs_iam_console)
- [Managing access keys for IAM users](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html)
- [Security best practices in IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)

## Try yourself

- Log in as root
- Create an alias to the AWS account address
- Activate MFA for the root account
- Enable billing information for the IAM user
- Set up a password security policy
- Create an IAM admin group with administrator permissions
- Create an IAM admin user with management console and programmatic accesses, and add it to the IAM admin group previously created
- Download the .csv file with access key ID and secret access key
- Log out from the root account
- Log in as the IAM admin user
- Set up MFA for the IAM admin user

## ☁️ Cloud Outcome

✍️ (Result) Describe your personal outcome, and lessons learned.

## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](link)
