# SimpleCloudFormationTemplate
CloudFormation Template that provisions 1 EC2 Instance and a S3 Bucket

This is a CloudFormation template that creates a VPC (Internet Gateway, Public and Private Subnet, Route Table), S3 Bucket and one EC2 Instance.

This template was built with YAML .

Note: Line 8-10 uses This parameter uses the AWS Systems Manager Parameter Store to retrieve the latest AMI (specified in the Default parameter, which in this case is Amazon Linux 2) for the stack's region. This makes it easy to deploy stacks in different regions without having to manually specify an AMI ID for every region.
