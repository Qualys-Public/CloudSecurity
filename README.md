# Qualys 'Cloud Security' Utilities
**Automation and Integration Scripts for Qualys Cloud Security offerings** 


## Table of Contents: 

### Sensor Automation
The Qualys Cloud Platform, with its active scanning (Scanner), always-on agents (Cloud Agent), cloud visibility connectors (Connector), provides global enterprises with unprecedented 2-second visibility of their cloud infrastructure.

1. **Pre-authorized virtual scanner**: The Qualys Virtual Scanner Appliance extends the reach of the Qualys Cloud Platform into the internal networks of Amazon VPC. This "Pre-Authorized Scanning" version of the virtual scanner is for use with the "EC2 Scanning" workflow within the Qualys Vulnerability Management solution 

AWS |
----|
[AWS_Scanner_CloudFormation](https://github.com/Qualys-Public/add_aws_Scanner) |
2. **Cloud Agent**: A lightweight agent that does continuous assessment of your environment for security and compliance.

AWS | AZURE | Google
----| ----- | ------
[Cloud_Agent_Ansible](https://github.com/Qualys-Public/deploy_qualys_Ansible) | [Cloud_Agent_Ansible](https://github.com/Qualys-Public/deploy_qualys_Ansible) | [Cloud_Agent_Ansible](https://github.com/Qualys-Public/deploy_qualys_Ansible)
[AWS_Cloud_Agent_SSM](https://github.com/Qualys-Public/deploy_qualys_SSM) | [AZURE_Cloud_Agent_AutomationAccount](https://github.com/Qualys-Public/deploy_qualys_Azure_Automation) |
[AWS_Cloud_Agent_Bootstrap](https://github.com/Qualys-Public/deploy_qualys_bootstap-AWS) | [CloudAgent-Azure-ARMTemplate](https://github.com/Qualys-Public/CloudAgent-Azure-ARMTemplate)
[AWS_Cloud_Agent_CodePipeline](https://github.com/Qualys-Public/deploy_qualys_CD_Pipeline_AWS) | 
[AWS_Cloud_Agent_UserdataScripts](https://github.com/Qualys-Public/deploy_qualys_s3)|  
3. **Connector**: The Qualys Connector continuously discovers assets using an API integration. Connectors may be configured to connect to one or more accounts/subscriptions/projects so they can automatically detect and synchronize changes to inventories across your Cloud.

AWS | AZURE | Google
----| ----- | ------
[add_ec2_connector](https://github.com/Qualys-Public/add_ec2_connector) | [CloudView-Connector-Azure](https://github.com/Qualys-Public/CloudView-Connector-Azure) | [CloudView-Connector-GCP](https://github.com/Qualys-Public/CloudView-Connector-GCP)
[aws-ec2-connector-cf](https://github.com/Qualys-Public/aws-ec2-connector-cf) |
[add_aws_account](https://github.com/Qualys-Public/add_aws_account) |
[aws-cv-connector-cf](https://github.com/Qualys-Public/aws-cv-connector-cf)|



### Process Automation
As part of our broader efforts to assist our customers to adopt cloud and secure it at rapid pace, we have other process automations.

AWS |
----|
[Golden AMI Pipeline](https://github.com/Qualys-Public/golden-ami-pipeline-with-qualys) |


### Integrations

SPLUNK | SLACK   |
-------| ------- |
[CloudView_Splunk_Scripted_Inputs](https://github.com/Qualys-Public/CloudView_Splunk_Scripted_Inputs) | [slack_cloudview_alerts](https://github.com/Qualys-Public/slack_cloudview_alerts)|

## Description

* **AWS_CV_Connector_CSV** - This helps you to do a CSV import of AWS Accounts to create Cloudview connectors. 
* **AWS_CV_Connector_CloudFormation** - This helps you to create cross-account role trust, assign Security Audit Policy, and CloudView Connector using a CloudFormation Template that can be run in AWS account. 
* **AWS_Connector_CSV** - This helps you to do a CSV import of AWS Accounts to create connectors. 
* **AWS_Connector_CloudFormation** - This helps you to create cross-account role trust, assign Security Audit Policy, and a Connector using a CloudFormation Template that can be run in AWS account. 
* **AWS_Scanner_CloudFormation** - This helps you to create a pre authorized scanners using a CloudFormation Template that can be run in AWS account. 
* **AZURE_Connector_CSV** - This helps you to do a CSV import of Azure subscriptions to create connectors. 
* **AWS_Cloud_Agent_SSM** - This helps you to deploy Cloud Agent across your AWS System Manager (SSM managed) managed instances using SSM. 
* **Cloud_Agent_Ansible** - This helps you to deploy Cloud Agent across your Linux instances in any cloud. 
* **AWS_Cloud_Agent_UserdataScripts** - This helps you to deploy Cloud Agent across your instances using user data scripts. 
* **AWS_Cloud_Agent_CodePipeline** - This helps you to deploy Cloud Agent across your instances using Ansible Playbook added in repository as Configuration management or Continuous Delivery. 
* **AWS_Cloud_Agent_Bootstrap** - This helps you to deploy Cloud Agent across your instances while its launching using AWS CloudWatch, Lambda & SSM Doc for Bootstrap. 
* **AZURE_Cloud_Agent_AutomationAccount** - This helps you to deploy Cloud Agent across your virtual machines using Azure Automation and Run command. 
* **AWS_BeanStalk_Cloud_Agent_Ebextensions** - This helps you to deploy Cloud Agent across your Elastic Beanstalk instances using yaml config file in .ebextensions folder. 
* **AWS_Golden_Ami_Pipeline** - This helps you to create a Golden AMI Pipeline integrated with a pre authorized scanner for vulnerability assessments.
* **CloudView_Splunk_Scripted_Inputs** - This helps you to integrate CloudView via python scripted inputs into Splunk Enterprise
* **CloudView-Connector-Azure** - This helps you to deploy Azure Connector(s) in CloudView using Management Group or ARM Template
* **CloudView-Connector-GCP** - This helps you to deploy GCP Connector(s) in CloudView using python to onboard GCP organization or projects in a CSV
* **CloudAgent-Azure-ARMTemplate** - This will help you to install Cloud Agent (CA) on Azure Linux or Windows VM using VM extension through ARM Template
* **slack_cloudview_alerts** - This helps you to integrate CloudView Assessment data into Slack for alerting

## Credits: 
we would like to thanks the contributors of various scripts under this project.

* [Mikesh Khanal](https://github.com/mkhanal1)
* [Sean Nicholson](https://github.com/snicholson-qualys)
* [Alex Mandernack](https://github.com/amandernackq)
* [Hari Srinivasan](https://github.com/hsrinivasanqualys)
* [Vishal Vetal](https://github.com/vvetal)

## License: 

_**THIS SCRIPT IS PROVIDED TO YOU "AS IS." 
TO THE EXTENT PERMITTED BY LAW, QUALYS HEREBY DISCLAIMS 
ALL WARRANTIES AND LIABILITY FOR THE PROVISION OR USE OF THIS SCRIPT. 
IN NO EVENT SHALL THESE SCRIPTS BE DEEMED TO BE CLOUD SERVICES AS PROVIDED BY QUALYS.**_
