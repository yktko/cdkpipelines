# Welcome to your CDK TypeScript project!

This is a blank project for TypeScript development with CDK.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `npm run test`    perform the jest unit tests
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template


npx cdk bootstrap   --profile ohmurayu   --cloudformation-execution-policies arn:aws:iam::aws:policy/AdministratorAccess aws://340935377354/us-east-2

npx cdk bootstrap --profile ohmurayu-srv01 --trust 340935377354 --cloudformation-execution-policies arn:aws:iam::aws:policy/AdministratorAccess aws://267114659816/us-west-2


