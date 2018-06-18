---
name: AWS EC2 Systems Manager
x-slug: aws-ec2-systems-manager
description: Amazon EC2 Systems Manager is a management service that helps you automatically
  collect software inventory, apply OS patches, create system images, and configure
  Windows and Linux operating systems. These capabilities help you define and track
  system configurations, prevent drift, and maintain software compliance of your EC2
  and on-premises configurations. By providing a management approach that is designed
  for the scale and agility of the cloud but extends into your on-premises data center,
  EC2 Systems Manager makes it easier for you to seamlessly bridge your existing infrastructure
  with AWS.EC2 Systems Manager is easy to use. Simply access EC2 Systems Manager from
  the EC2 Management Console, select the instances you want to manage, and define
  the management tasks you want to perform. EC2 Systems Manager is available now at
  no cost to manage both your EC2 and on-premises resources.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Execution
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon EC2 Systems Manager API Describe Automation Executions
  x-api-slug: amazon-ec2-systems-manager-api
  description: Provides details about all active and terminated Automation executions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeAutomationExecutions
  tags: Automation, Executions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribeautomationexecutions-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Maintenance Window Executions
  x-api-slug: amazon-ec2-systems-manager-api
  description: |-
    Lists the executions of a Maintenance Window (meaning, information about when the
       Maintenance Window was scheduled to be active and information about tasks registered and run with
       the Maintenance Window).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeMaintenanceWindowExecutions
  tags: Maintenance, Window, Executions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutions-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Maintenance Window Execution Task
    Invocations
  x-api-slug: amazon-ec2-systems-manager-api
  description: |-
    Retrieves the individual task executions (one per target) for a particular task executed
       as part of a Maintenance Window execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeMaintenanceWindowExecutionTaskInvocations
  tags: Maintenance, Window, Execution, Task, Invocations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Maintenance Window Execution Tasks
  x-api-slug: amazon-ec2-systems-manager-api
  description: For a given Maintenance Window execution, lists the tasks that were
    executed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeMaintenanceWindowExecutionTasks
  tags: Maintenance, Window, Execution, Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontasks-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Automation Execution
  x-api-slug: amazon-ec2-systems-manager-api
  description: Get detailed information about a particular Automation execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetAutomationExecution
  tags: Automation, Execution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiongetautomationexecution-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Maintenance Window Execution
  x-api-slug: amazon-ec2-systems-manager-api
  description: |-
    Retrieves details about a specific task executed as part of a Maintenance Window
       execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetMaintenanceWindowExecution
  tags: Maintenance, Window, Execution
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindowexecution-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindowexecution-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Maintenance Window Execution Task
  x-api-slug: amazon-ec2-systems-manager-api
  description: |-
    Retrieves the details about a specific task executed as part of a Maintenance Window
       execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetMaintenanceWindowExecutionTask
  tags: Maintenance, Window, Execution, Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindowexecutiontask-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindowexecutiontask-get-openapi.md
- name: Amazon EC2 Systems Manager API Start Automation Execution
  x-api-slug: amazon-ec2-systems-manager-api
  description: Initiates execution of an Automation document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=StartAutomationExecution
  tags: Start, Automation, Execution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actionstartautomationexecution-get-openapi.md
- name: Amazon EC2 Systems Manager API Stop Automation Execution
  x-api-slug: amazon-ec2-systems-manager-api
  description: Stop an Automation that is currently executing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=StopAutomationExecution
  tags: Stop, Automation, Execution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actionstopautomationexecution-get-openapi.md
- name: Amazon EC2 Systems Manager API
  x-api-slug: amazon-ec2-systems-manager-api
  description: Amazon EC2 Systems Manager is a management service that helps you automatically
    collect software inventory, apply OS patches, create system images, and configure
    Windows and Linux operating systems. These capabilities help you define and track
    system configurations, prevent drift, and maintain software compliance of your
    EC2 and on-premises configurations. By providing a management approach that is
    designed for the scale and agility of the cloud but extends into your on-premises
    data center, EC2 Systems Manager makes it easier for you to seamlessly bridge
    your existing infrastructure with AWS.EC2 Systems Manager is easy to use. Simply
    access EC2 Systems Manager from the EC2 Management Console, select the instances
    you want to manage, and define the management tasks you want to perform. EC2 Systems
    Manager is available now at no cost to manage both your EC2 and on-premises resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Execution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/ssm/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/ec2/systems-manager/faqs/
- type: x-getting-started
  url: http://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/systems-manager.html
- type: x-website
  url: https://aws.amazon.com/ec2/systems-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---