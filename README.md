# Serverless Applicaiton using the AWS CDK

https://docs.aws.amazon.com/cdk/v2/guide/serverless_example.html

This example walks you through creating the resources for a simple widget dispensing service. (For the purpose of this example, a widget is just a name or identifier that can be added to, retrieved from, and deleted from a collection.) The example includes:

- An AWS Lambda function.
- An Amazon API Gateway API to call the Lambda function.
- An Amazon S3 bucket that holds the widgets.

This tutorial contains the following steps.

- Create an AWS CDK app
- Create a Lambda function that gets a list of widgets with `HTTP GET /`
- Create the service that calls the Lambda function
- Add the service to the AWS CDK app
- Test the app
- Add Lambda functions to do the following:
  - Create a widget with `POST /{name}`
  - Get a widget by name with `GET /{name}`
  - Delete a widget by name with `DELETE /{name}`
- Tear everything down when you're finished
