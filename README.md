# EC2 Role - Least Privilege

CloudFormation template to deploy a barebones EC2 role/instance profile. The template can be used as a starter instance profile. The deployment of the cloudforamtion as-is would give an instance profile that has 2 AWS Managed Policies attached that enable management for the EC2:

1. CloudWatch
2. SSM

Any additional policies can be attached after deployed or fork this project to further customize.

