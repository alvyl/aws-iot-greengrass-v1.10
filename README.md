# aws-iot-greengrass-v1.10

An alternative Snap for AWS IoT Greengrass with GGC v1.10 support, because AWS won't.

## Because

The whole reason this repo exists is because, the current snap "aws-iot-greengrass" installs [AWS Greengrass Core 1.8.0](https://docs.aws.amazon.com/greengrass/latest/developerguide/what-is-gg.html#w119aab5c25b9b5b6). 

This is currently a problem because the AWS Greengrass Core 1.8.0 only supports lambdas with node runtime 6.10 and below. Hoever, AWS lambda only supports node runtime version 10.0 and above, and deprecated support for 8.10 and below.

And hence if you are looking to deploy a node lambda to greengrass core, you basically cannot.

## About "Greengrass Core Software License Agreement"

Kindly refer to the "Greengrass Core Software License Agreement" here. 

https://s3-us-west-2.amazonaws.com/greengrass-release-license/greengrass-license-v1.pdf
