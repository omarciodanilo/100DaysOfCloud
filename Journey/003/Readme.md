# Create a Cost Budget

## Introduction

AWS Budgets is a service that allows cost and usage tracking, monitoring, and reports.

## Prerequisite

Basic understanding of AWS Budgets.

## Use Case

When using AWS, it is fundamental to plan, monitor, and keep track of its service related costs. It is also important to be notified when these costs are close to (or maybe over) a user-defined amount.

For me this is part of the initial configurations of any AWS account (personal or professional), together with securing your account and setting up billing alarms.

## Cloud Research

Useful reference links to understand the concepts and complete this lab:

- [Creating a cost budget](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/budgets-create.html#create-cost-budget)
- [Best practices for AWS Budgets](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/budgets-best-practices.html)

## Try yourself

Main steps:

- Log in the AWS account as a user with billing permissions
- Create a Cost Budget in the AWS Billing and Cost Management console
    - Define a percentage threshold of 80%
    - Add an e-mail to receive a notification when the Cost Budget reaches 80% of the threshold

## Cloud Outcome

Concepts I learned:

- AWS Budgets is a service that helps to plan, monitor, and keep track of the usage and costs of an AWS account.
- It also can send notifications via email, Amazon SNS topic, or AWS Chatbot Alert.
- To create budgets, a user must allowed to view billing information, create Amazon CloudWatch alarms, and create Amazon SNS notifications.
- Budgets can be created using the AWS Billing and Cost Management console or programmatically using the Budgets API. In this case, AWS recommends to create a unique IAM user for allowing programmatic access, so it is possible to control who has access to the console and the API.
- Budgets can be set in a recurring basis (automatically renew every month) or in a expiring basis (automatically renew until due date).
- There are two types of thresholds: percentage and absolute value.
- There are four types of budget:
    - Cost Budget: for overall costs.
    - Usage Budget: for specific usage type groups.
    - Reservation Budget: for reserved instances usage (EC2, RDS, Redshift, Elasticache, Elasticsearch).
    - Savings Plans Budget: for savings plans.

## Social Proof

[Linkedin post]()
