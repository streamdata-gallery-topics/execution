---
name: SmartBear Software
x-slug: smartbear-software
description: Testing and Development teams around the world use SmartBears automation,
  development and monitoring tools to build better software and applications.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
x-kinRank: "9"
x-alexaRank: "35193"
tags: Execution
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/apis.md
specificationVersion: "0.14"
apis:
- name: Ready! API TestServer API - Returns test run results stored on the TestServer.
  x-api-slug: readyapiexecutions-get
  description: Use this operation to get results of the latest test runs stored on
    the TestServer.<br/> The number of stored results is [configurable](http://readyapi.smartbear.com/testserver/reference/server_properties).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutions-get-openapi.md
- name: Ready! API TestServer API - Runs a test recipe.
  x-api-slug: readyapiexecutions-post
  description: Use this operation to send a test recipe to the TestServer. The recipe
    contents is passed in the request body (should be valid JSON contents).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutions-post-openapi.md
- name: Ready! API TestServer API - Executes a Ready! API project.
  x-api-slug: readyapiexecutionsxml-post
  description: Use this operation to send a Ready! API test project to the TestServer.
    You command the TestServer to execute the entire project, or an individual test
    suite or test case in it. The recipe request should have a Ready! API project
    file (.xml) attached to it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsxml-post-openapi.md
- name: Ready! API TestServer API - Executes a zipped Ready! API composite project.
  x-api-slug: readyapiexecutionscomposite-post
  description: Use this operation to send a zipped Ready! API composite project to
    the TestServer. You command the TestServer to execute the entire project, or an
    individual test suite or test case in it. The recipe request should have a Ready!
    API project file (.xml) attached to it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionscomposite-post-openapi.md
- name: Ready! API TestServer API - Cancels the specified recipe execution
  x-api-slug: readyapiexecutionsexecutionid-delete
  description: Use this operation to stop the run specified by <i>executionID</i>.
    You can find in the response to your execution request ([see how](http://readyapi.smartbear.com/testserver/tutorials/your_first_recipe/results)),
    or you can send a GET <code>/readyapi/executions</code> request to the TestServer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionid-delete-openapi.md
- name: Ready! API TestServer API - Returns the status of the specified recipe execution.
  x-api-slug: readyapiexecutionsexecutionidstatus-get
  description: Use this operation to get information on the recipe execution specified
    by <i>executionID</i>.  You can find in the response to your execution request
    ([see how](http://readyapi.smartbear.com/testserver/tutorials/your_first_recipe/results)),
    or you can send a GET <code>/readyapi/executions</code> request to the TestServer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidstatus-get-openapi.md
- name: Ready! API TestServer API - Returns the transaction logs for the specified
    recipe execution.
  x-api-slug: readyapiexecutionsexecutionidlogs-get
  description: Use this operation to get transaction logs (individual request and
    recponse of executed test steps) of the recipe execution specified by <i>executionID</i>.  You
    can find it in the response of your execution request ([see how](http://readyapi.smartbear.com/testserver/tutorials/your_first_recipe/results)),
    or you can send a GET <code>/readyapi/executions/{executionID}/logs</code> request
    to the TestServer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidlogs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidlogs-get-openapi.md
- name: Ready! API TestServer API - Posts a file for the specified test run
  x-api-slug: readyapiexecutionsexecutionidfiles-post
  description: Use this operation to send additional files required by the executed
    test recipes. For example, you may need to send an Excel file for your test recipe
    that uses an Excel data source. The test recipe will be in the "PENDING" status
    until it receives the required file. Use the <code>multipart/form-data</code>
    media type for this request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidfiles-post-openapi.md
- name: Ready! API TestServer API - Gets message exchange for a test step execution
    transaction
  x-api-slug: readyapiexecutionsexecutionidtransactionstransactionid-get
  description: A particular execution of a test step is referred as transaction. Use
    this operation to get the request and response for a transaction in HAR format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidtransactionstransactionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidtransactionstransactionid-get-openapi.md
- name: Ready! API TestServer API - Returns test run results stored on the TestServer.
  x-api-slug: readyapiexecutions-get
  description: Use this operation to get results of the latest test runs stored on
    the TestServer.<br/> The number of stored results is [configurable](http://readyapi.smartbear.com/testserver/reference/server_properties).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutions-get-openapi.md
- name: Ready! API TestServer API - Runs a test recipe.
  x-api-slug: readyapiexecutions-post
  description: Use this operation to send a test recipe to the TestServer. The recipe
    contents is passed in the request body (should be valid JSON contents).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutions-post-openapi.md
- name: Ready! API TestServer API - Executes a Ready! API project.
  x-api-slug: readyapiexecutionsxml-post
  description: Use this operation to send a Ready! API test project to the TestServer.
    You command the TestServer to execute the entire project, or an individual test
    suite or test case in it. The recipe request should have a Ready! API project
    file (.xml) attached to it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsxml-post-openapi.md
- name: Ready! API TestServer API - Executes a zipped Ready! API composite project.
  x-api-slug: readyapiexecutionscomposite-post
  description: Use this operation to send a zipped Ready! API composite project to
    the TestServer. You command the TestServer to execute the entire project, or an
    individual test suite or test case in it. The recipe request should have a Ready!
    API project file (.xml) attached to it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionscomposite-post-openapi.md
- name: Ready! API TestServer API - Cancels the specified recipe execution
  x-api-slug: readyapiexecutionsexecutionid-delete
  description: Use this operation to stop the run specified by <i>executionID</i>.
    You can find in the response to your execution request ([see how](http://readyapi.smartbear.com/testserver/tutorials/your_first_recipe/results)),
    or you can send a GET <code>/readyapi/executions</code> request to the TestServer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionid-delete-openapi.md
- name: Ready! API TestServer API - Returns the status of the specified recipe execution.
  x-api-slug: readyapiexecutionsexecutionidstatus-get
  description: Use this operation to get information on the recipe execution specified
    by <i>executionID</i>.  You can find in the response to your execution request
    ([see how](http://readyapi.smartbear.com/testserver/tutorials/your_first_recipe/results)),
    or you can send a GET <code>/readyapi/executions</code> request to the TestServer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidstatus-get-openapi.md
- name: Ready! API TestServer API - Returns the transaction logs for the specified
    recipe execution.
  x-api-slug: readyapiexecutionsexecutionidlogs-get
  description: Use this operation to get transaction logs (individual request and
    recponse of executed test steps) of the recipe execution specified by <i>executionID</i>.  You
    can find it in the response of your execution request ([see how](http://readyapi.smartbear.com/testserver/tutorials/your_first_recipe/results)),
    or you can send a GET <code>/readyapi/executions/{executionID}/logs</code> request
    to the TestServer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidlogs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidlogs-get-openapi.md
- name: Ready! API TestServer API - Posts a file for the specified test run
  x-api-slug: readyapiexecutionsexecutionidfiles-post
  description: Use this operation to send additional files required by the executed
    test recipes. For example, you may need to send an Excel file for your test recipe
    that uses an Excel data source. The test recipe will be in the "PENDING" status
    until it receives the required file. Use the <code>multipart/form-data</code>
    media type for this request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidfiles-post-openapi.md
- name: Ready! API TestServer API - Gets message exchange for a test step execution
    transaction
  x-api-slug: readyapiexecutionsexecutionidtransactionstransactionid-get
  description: A particular execution of a test step is referred as transaction. Use
    this operation to get the request and response for a transaction in HAR format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidtransactionstransactionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidtransactionstransactionid-get-openapi.md
- name: Ready! API TestServer API - Returns test run results stored on the TestServer.
  x-api-slug: readyapiexecutions-get
  description: Use this operation to get results of the latest test runs stored on
    the TestServer.<br/> The number of stored results is [configurable](http://readyapi.smartbear.com/testserver/reference/server_properties).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutions-get-openapi.md
- name: Ready! API TestServer API - Runs a test recipe.
  x-api-slug: readyapiexecutions-post
  description: Use this operation to send a test recipe to the TestServer. The recipe
    contents is passed in the request body (should be valid JSON contents).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutions-post-openapi.md
- name: Ready! API TestServer API - Executes a Ready! API project.
  x-api-slug: readyapiexecutionsxml-post
  description: Use this operation to send a Ready! API test project to the TestServer.
    You command the TestServer to execute the entire project, or an individual test
    suite or test case in it. The recipe request should have a Ready! API project
    file (.xml) attached to it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsxml-post-openapi.md
- name: Ready! API TestServer API - Executes a zipped Ready! API composite project.
  x-api-slug: readyapiexecutionscomposite-post
  description: Use this operation to send a zipped Ready! API composite project to
    the TestServer. You command the TestServer to execute the entire project, or an
    individual test suite or test case in it. The recipe request should have a Ready!
    API project file (.xml) attached to it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionscomposite-post-openapi.md
- name: Ready! API TestServer API - Cancels the specified recipe execution
  x-api-slug: readyapiexecutionsexecutionid-delete
  description: Use this operation to stop the run specified by <i>executionID</i>.
    You can find in the response to your execution request ([see how](http://readyapi.smartbear.com/testserver/tutorials/your_first_recipe/results)),
    or you can send a GET <code>/readyapi/executions</code> request to the TestServer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionid-delete-openapi.md
- name: Ready! API TestServer API - Returns the status of the specified recipe execution.
  x-api-slug: readyapiexecutionsexecutionidstatus-get
  description: Use this operation to get information on the recipe execution specified
    by <i>executionID</i>.  You can find in the response to your execution request
    ([see how](http://readyapi.smartbear.com/testserver/tutorials/your_first_recipe/results)),
    or you can send a GET <code>/readyapi/executions</code> request to the TestServer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidstatus-get-openapi.md
- name: Ready! API TestServer API - Returns the transaction logs for the specified
    recipe execution.
  x-api-slug: readyapiexecutionsexecutionidlogs-get
  description: Use this operation to get transaction logs (individual request and
    recponse of executed test steps) of the recipe execution specified by <i>executionID</i>.  You
    can find it in the response of your execution request ([see how](http://readyapi.smartbear.com/testserver/tutorials/your_first_recipe/results)),
    or you can send a GET <code>/readyapi/executions/{executionID}/logs</code> request
    to the TestServer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidlogs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidlogs-get-openapi.md
- name: Ready! API TestServer API - Posts a file for the specified test run
  x-api-slug: readyapiexecutionsexecutionidfiles-post
  description: Use this operation to send additional files required by the executed
    test recipes. For example, you may need to send an Excel file for your test recipe
    that uses an Excel data source. The test recipe will be in the "PENDING" status
    until it receives the required file. Use the <code>multipart/form-data</code>
    media type for this request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidfiles-post-openapi.md
- name: Ready! API TestServer API - Gets message exchange for a test step execution
    transaction
  x-api-slug: readyapiexecutionsexecutionidtransactionstransactionid-get
  description: A particular execution of a test step is referred as transaction. Use
    this operation to get the request and response for a transaction in HAR format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1157-smartbear-software.jpg
  humanURL: http://smartbear.com/
  baseURL: ://testserver.readyapi.io:8080//v1
  tags: Security, Testing, Monitoring, Performance, API LIfeyclessss, Stack Network,
    SaaS, Technology, Enterprise, Virtualizations, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidtransactionstransactionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/smartbear-software/readyapiexecutionsexecutionidtransactionstransactionid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://slack.api.gallery.streamdata.io
- type: x-api-stack
  url: http://smartbear.software.stack.network
- type: x-blog
  url: http://blog.smartbear.com/
- type: x-blog-rss
  url: http://feeds.feedburner.com/smartbear
- type: x-crunchbase
  url: https://crunchbase.com/organization/smart-bear-software
- type: x-crunchbase
  url: http://www.crunchbase.com/company/smart-bear-software
- type: x-github
  url: https://github.com/SmartBear
- type: x-twitter
  url: https://twitter.com/smartbear
- type: x-website
  url: http://smartbear.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---