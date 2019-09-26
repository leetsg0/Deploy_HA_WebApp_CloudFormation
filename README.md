**Deploying a High Availability Web Application using Cloud Formation (Udacity Cloud DevOps Project 2)**
**Lito M.**

The diagram below depicts the network infrastructure and AWS services used for this project
![Network Diagram](/images/Project-2-Diagram.jpg)

**Instructions**
There are 2 CloudFormation scripts that:
1. Creates the infrastructure stack
1. Creates and deploys the web application servers

It must created in that order.  The create scripts are in .bat (batch) format and was run in a Windows environment.

First, create the infrastructure by running:
> .\create infrastack networkinfra.yml networkinfra-params.json

Check the AWS CloudFormation command console and verify that the infrastack was created and completed before proceeding to the next step.

Next, create and deploy the servers by running:
> .\create serverstack deployservers.yml server-params.json
