---
title: "Retrieve Windows password"
chapter: false
weight: 10
---


1. Navigate to the [CloudFormation console](https://console.aws.amazon.com/cloudformation/home) and select the correct CloudFormation stack. If you are running the workshop on your own the Stack is called **streaming-analytics-workshop** and if you are attending an AWS hosted event, there is only one Stack available in the account.

1. Verify that the CloudFormation stack was created successfully and is in the state **CREATE_COMPLETED**. Then, navigate to the **Output** section of the CloudFormation template.

	![Lauch stack](/images/cfn-5-completed.png)

1. Take a note of the public ip address of the EC2 instance containing the development environment and open the link to AWS Secrets Manager in a new browser tab
	
	![Lauch stack](/images/cfn-6-parameters.png)

1. In the AWS Secrets Manager console, click on **Retrieve secret value** to obtain the Administrator password that has been set for the instance

	![Lauch stack](/images/secrets-manager-retrieve-secret.png)

