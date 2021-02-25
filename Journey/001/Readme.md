# Secure the root account, create and secure an IAM admin user

## Introduction

IAM (Identity and Access Management) is a crucial security service in the AWS environment. It's essentially responsible for managing access permissions to the AWS account as well as to its resources. Hence, it's necessary to understand how it works and learn the basic configurations to allow a secure access.

## Prerequisite

Basic understanding of IAM service and its main components (User, Group, Role, and Policy), as well as basic knowledge of password enforcement and MFA (Multi-Factor Authentication).

## Use Case

After creating an AWS account, the first step is to secure it. So once at least the majority of the steps in this lab are included in the IAM security best practices, I believe they are fundamental to enable some security features to any AWS account, regardless of the type and size of the project.

## Cloud Research

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

Main steps:

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

Concepts I learned (in general lines):

- IAM stands for Identity and Access Management and is a Web service used to manage authentication and autorization to access AWS resources.
- The root account is the first and most important entity of an AWS account. It has all privileges and hence need to be secured and used only when strictly necessary. For that reason, instead of using the root account for every single operation, AWS recommends to create and IAM user with administrative permissions.
- A user can be a person or a service. A group is a collection of users. A policy is a list of allow permissions. A role is a set of policies that is attached to a user or group, allowing temporary an secure access to AWS resources.
- AWS allows two types of access: via management console (GUI) and programmatic access (API, CLI, SDK). An e-mail/login and a password (with or without MFA) can be used to access the management console. An access key ID and a secret access key can be used in a programmatic access.
- The access key ID and secret access key are generated when an IAM user is created. They can be downloaded and need to be stored in a safe location.
- MFA stands for Multi-Factor Authentication and is a way to add a security layer to the authentication process. It can be a physical or virtual token.

Besides that, I learned how to:

- create an alias to the AWS account (and that it makes the user access easier),
- secure an AWS root account,
- create and secure IAM users,
- create IAM groups,
- and attach roles to IAM groups.

Conclusion: during my studies and while practicing the lab, I was continuously remebered that IAM is one of the foundational services of AWS and is interconnected with every other AWS service. That said, a good understanding of it and a detail-oriented posture will help a lot when working on Cloud projects.

## Social Proof

[Linkedin post](link)
