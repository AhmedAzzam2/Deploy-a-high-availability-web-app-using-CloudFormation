
Install the AWS CLI if you haven't already.

![Alt text](screanshot/Screenshot%202023-01-10%20224154.jpg)
![Alt text](screanshot/Screenshot%202023-01-10%20225733.jpg)
![Alt text](screanshot/Screenshot%202023-01-10%20230035.jpg)
![Alt text](screanshot/Screenshot%202023-01-10%20230443.jpg)
![Alt text](screanshot/Screenshot%202023-01-10%20230643.jpg)


Save the CloudFormation template to a file (for example, template.yaml) on your local machine.

Run the following command to create a new stack:

### Deploying your website
Using the AWS CLI, run:

```bash
sh create.sh <stack_name> template.yml template-params.json
```

To update the current stack run:
```bash
sh update.sh <stack_name> template.yml template-params.json
```

To delete stack run:
```bash
sh update.sh <stack_name> template.yml template-params.json
```
