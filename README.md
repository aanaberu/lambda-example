# lambda-example

This is sample example for setting up lambda function.

The sample-zip file contains a sample python lambda function which has event hendle welcome and the message.

Steps to setup the lambda function using Digital.ai Release:

## Step 1:

Create connection AWS: Server (Container) in Connection paga.

Step To Create a Function using S3 zip file:
While executing the Lambda function workflow provide the following details:

Sample:
Region: ap-south-1

Function Name: FunctionUsingS3Zip

Function Description: Function Using S3Zip

S3 Bucket Name: integ-test-bucket-1

S3 Object Key: lambda_function.zip

Runtime: python3.8

Role: arn:aws:iam::xxxxxxxxxxx:role/service-role/lambda-role-xxxxxx

Handler: lambda_function.lambda_handler

## Step to update Function Using s3 zip:

For updating an exsiting function provide the following details.
Sample:

Region: ap-south-1

Function Name: FunctionUsingS3Zip

S3 Bucket Name: integ-test-bucket-1

S3 Object Key: lambda_function.zip


## Step to Invoke Function:

Sample:

Region: ap-south-1

Function Name: FunctionUsingS3Zip

Payload: {"name": "Digital.ai"}

## Step to Delete a Function:

Sample:

Region: ap-south-1

Function Name: FunctionUsingS3Zip

## Step to Create Function using Image:

Sample:

Region: ap-south-1

Function Name: FunctionUsingImage

Function Description: Function Using Image

Role: arn:aws:iam::xxxxxxxx:role/service-role/lambda-role-xxxxxxxx

image Uri: xxxxxxxx.dkr.ecr.ap-south-1.amazonaws.com/newrepo@sha256:xxxxxxxxxxxxxxxxxxxxxxx

