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
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Execution Task Invocations
  x-api-slug: actiondescribemaintenancewindowexecutiontaskinvocations-get
  description: |-
    Retrieves the individual task executions (one per target) for a particular task executed
       as part of a Maintenance Window execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Execution Tasks
  x-api-slug: actiondescribemaintenancewindowexecutiontasks-get
  description: For a given Maintenance Window execution, lists the tasks that were
    executed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontasks-get-openapi.md
- name: AWS EC2 Systems Manager API - Get Automation Execution
  x-api-slug: actiongetautomationexecution-get
  description: Get detailed information about a particular Automation execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiongetautomationexecution-get-openapi.md
- name: AWS EC2 Systems Manager API - Get Maintenance Window Execution
  x-api-slug: actiongetmaintenancewindowexecution-get
  description: |-
    Retrieves details about a specific task executed as part of a Maintenance Window
       execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindowexecution-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindowexecution-get-openapi.md
- name: AWS EC2 Systems Manager API - Get Maintenance Window Execution Task
  x-api-slug: actiongetmaintenancewindowexecutiontask-get
  description: |-
    Retrieves the details about a specific task executed as part of a Maintenance Window
       execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindowexecutiontask-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiongetmaintenancewindowexecutiontask-get-openapi.md
- name: AWS EC2 Systems Manager API - Start Automation Execution
  x-api-slug: actionstartautomationexecution-get
  description: Initiates execution of an Automation document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actionstartautomationexecution-get-openapi.md
- name: AWS EC2 Systems Manager API - Stop Automation Execution
  x-api-slug: actionstopautomationexecution-get
  description: Stop an Automation that is currently executing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actionstopautomationexecution-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Automation Executions
  x-api-slug: actiondescribeautomationexecutions-get
  description: Provides details about all active and terminated Automation executions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribeautomationexecutions-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Executions
  x-api-slug: actiondescribemaintenancewindowexecutions-get
  description: |-
    Lists the executions of a Maintenance Window (meaning, information about when the
       Maintenance Window was scheduled to be active and information about tasks registered and run with
       the Maintenance Window).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutions-get-openapi.md
- name: AWS EC2 Systems Manager API - Send Command
  x-api-slug: actionsendcommand-get
  description: Executes commands on one or more remote instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actionsendcommand-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actionsendcommand-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Automation Executions
  x-api-slug: actiondescribeautomationexecutions-get
  description: Provides details about all active and terminated Automation executions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribeautomationexecutions-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Executions
  x-api-slug: actiondescribemaintenancewindowexecutions-get
  description: |-
    Lists the executions of a Maintenance Window (meaning, information about when the
       Maintenance Window was scheduled to be active and information about tasks registered and run with
       the Maintenance Window).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutions-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Automation Executions
  x-api-slug: actiondescribeautomationexecutions-get
  description: Provides details about all active and terminated Automation executions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribeautomationexecutions-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Executions
  x-api-slug: actiondescribemaintenancewindowexecutions-get
  description: |-
    Lists the executions of a Maintenance Window (meaning, information about when the
       Maintenance Window was scheduled to be active and information about tasks registered and run with
       the Maintenance Window).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutions-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.ec2.container.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.ec2.systems.manager.stack.network
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