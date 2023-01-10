# Deploy-a-high-availability-web-app-using-CloudFormation

Install the AWS CLI if you haven't already.

Save the CloudFormation template to a file (for example, template.yaml) on your local machine.

Run the following command to create a new stack:

Copy code
``` aws cloudformation create-stack --stack-name my-stack --template-body file://template.yaml ```
