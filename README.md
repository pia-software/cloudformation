# cloudformation
AWS Cloud Formation templates to start the Pia Software Flow Logs Viewer

https://aws.amazon.com/marketplace/pp/B074N3YQ1P


## Purpose

These will:
* Create a security group to permit access on port 443
* Create the IAM User with the minimal permissions needed for the Flow Logs Viewer
* Create an access key for that user
* Launch the AMI into the subnet that the user specifies
* Create an output block for the user, and put the Access and Secret Key in CloudFormation's outputs.

## Resource Diagram

![Resource Diagram](ResourceDiagram.png)
