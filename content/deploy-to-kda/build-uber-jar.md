---
title: "Build Uber Jar"
chapter: false
weight: 20
---

1. Expand the Maven pane and click on the **m** to execute `clean package` as a Maven goal

	![](/images/intellij-7-maven-package.png)

1. Maven will now build a jar file that includes all the dependencies of the Flink application. The jar file is stored in the *target* directory and can be deployed to KDA for Java.

{{% notice info %}}
If you are feeling lucky, you can upload the generated jar file to an S3 bucket and subsequently deploy it to KDA for Java. However, the following steps will use a precompiled jar file that is tested and works as intended.
{{% /notice %}}
