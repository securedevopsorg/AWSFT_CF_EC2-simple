# AWS_CloudFormation_EC2-simple template

A CloudFormation simple EC2 instance template - Provided for demonstration.

There are 2 distinct code components to any deployment. These are:

  1. *Infrastructure Code* -  is consumed by CloudFormation or etc., and is used to specify/define the infrastructure as code that the application runs on/in.
  2. *Application Code* - Your application code - See https://github.com/securedevopsorg/Application_Deployment_Sample for a working sample.

Use this template with AWS CloudFormation to launch a Free Tier EC2 instance.

To use this template, you will need to point to it with CloudFormation. CloudFormation will then make use of the JSON information to configure and deploy AWS infrastructure.

# FAQ
Why are there no comments? *JSON does not offer comments built in. Unfortunately this means that using the JSON standard, comments cannot be included.*

Oh. Is there any way around that? *Yes. 2 I have found follow.*

1. https://aws.amazon.com/blogs/devops/adding-comments-inside-aws-cloudformation-templates/ - a kludgy hack...

2. Switch to YAML instead, which does support comments


**Contents:**
* LICENSE - Apache License (for information only)
* README.md - This file (for information only)
* AWS_CF_EC2-simple.template - A JSON formatted template file specifying AWS infrastructure and further configuration instructions to be consumed by CloudFormation to create and configure a deployment
* AWS_CF_EC2-simple.jpg - Visual representation of this install
* Application_Deployment_Sample-master.template - Original template as supplied by Amazon, which this template is derived from. Original link: http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/sample-templates-services-us-west-2.html

Author: Kenneth Ish
