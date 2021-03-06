# Create an SNS topic and create three Billing Alarms using CloudWatch

## Introduction

- SNS is the AWS Simple Notification Service and is used for sending messages to users or applications.
- CloudWatch is the AWS monitoring and observability service.
- Billing Alarms are a way of monitoring charges of the AWS account.

## Prerequisite

Basic understanding of SNS, CloudWatch, and Billing.

## Use Case

After creating an AWS account, it is also important to configure billing alarms to monitor the account charges. No one wants to be taken by surprise at the end of the month.

Some AWS services are free of charge but the majority of them are not. Therefore, it is fundamental to keep tracking of a project's spendings by using CloudWatch Billing Alarms, and be notified thanks to an SNS subscription.

## Cloud Research

Useful reference links to understand the concepts and complete this lab:

- [Amazon Simple Notification Service](https://aws.amazon.com/sns/)
- [Amazon CloudWatch](https://aws.amazon.com/cloudwatch/)
- [Setting Up Amazon SNS Notifications](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/US_SetupSNS.html)
- [Creating a Billing Alarm to Monitor Your Estimated AWS Charges](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html)

## Try yourself

Main steps:

- Enable the Monitoring of Estimated Charges in the Preferences option in the Billing service dashboard
- Create an SNS topic to send a notification when the Billing Alarm is triggered
- Confirm subscription to the previously created SNS topic
- Create a Total Estimated Charge Billing Alarm using CloudWatch

## Cloud Outcome

Concepts I learned:

About SNS

- SNS stands for Simple Notification Service, and can send simple text-based messages to applications and people using, for instance, e-mail or SMS.
- It is a pub/sub service, so it is necessary to subscribe to the desired SNS topic to receive its notifications (like people do with newsletters).
- Also, it is used as a messaging communication service in decoupled application architectures, like distributed systems, microservices, and event-driven serverless applications.

About CloudWatch

- CloudWatch is a monitoring and observability service used to collect data of AWS and on-premises applications and services.
- It collects and visualizes logs, metrics, and events.
- It can be used to set alarms and take pre-configured actions to troubleshoot problems.

About Billing Alarms

- Billing Alarms are a way of monitor charges.
- It is triggered when the specified metric threshold is reached.
- It is possible to be notified when a Billing Alarm is triggered thanks to SNS.
- Billing Alarms can be configured only in the <b>US East (N. Virginia) us-east-1</b> Region, because billing metric data is stored in this Region and represents worldwide charges.

## Social Proof

[Linkedin post]()
