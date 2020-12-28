# Lambda Canary Deployments with CodeDeploy
Safer Lambda Deployments with CodeDeploy Canary Deployments

![Lambda CodeDeploy canary deployments](./codedeploy-canary-deployments.png)

## AWS Costs

By following these instructions you will create resources in AWS that could result in AWS costs.
It is recommended that you delete the CloudFormation stack for this example once you have finished experimenting with it.

## Prerequisites

[AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)

## Deploying to AWS

aws cloudformation deploy \
--template-file sam.template.yaml \
--stack-name lambda-codedeploy-canary \
--capabilities CAPABILITY_IAM
