---
title: "Execute CFN template"
chapter: false
weight: 30
---

1. Launch the following CloudFormation template to create a prepared development environment in your account. Supported regions include US East (N. Virginia), US West (Oregon), Asia Pacific (Tokyo), Asia Pacific (Sydney), EU (Ireland), EU (Frankfurt), and any other region supporting Amazon Code Pipeline, Amazon Elasticsearch Service, and Amazon Kinesis Data Analytics for Java Applications.

	[![Launch CloudFormation Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=streaming-analytics-workshop&templateURL=https://s3.amazonaws.com/shausma-public/public/cfn-templates/streaming-analytics-workshop/StreamingAnalyticsWorkshop.template.json)

1. In the following dialog, choose **Next**

	![Lauch stack](/images/cfn-1-create-stack.png)

1. Choose `streaming-analytics-workshop` as **Stack name** and confirm with **Next**

1. Accept all default values on the next dialog page by clicking **Next** at the bottom of the page

1. On the last page of the dialog, confirm that CloudFormation may create IAM resource by selecting *I acknowledge that AWS CloudFormation might create IAM resources**. Click on **Create stack* at the bottom of the page.

	![Lauch stack](/images/cfn-4-confirm-capabilities.png)

It takes roughly 10 minutes until the CloudFromation template has been created successfully. You can already continue with the next step [Configure development environment](../../configure) while the template is still creating.
