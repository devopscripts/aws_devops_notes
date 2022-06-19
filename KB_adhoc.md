# Adhoc knowledge base

## Lambda

Lambda doesn't natively support rolling update, instead you can use lambda traffic shifting feature to in codedeploy to achieve something similar to rolling update. Pointing Lambda alias to different versions and config the percentage of each version.

## AWS Firewall Manager

AWS Firewall Manager is primarily used to manage your Firewall across multiple AWS accounts under your AWS Organizations.

## 

The AWSServiceRoleForOrganizations service-linked role is primarily used to only allow AWS Organizations to create service-linked roles for other AWS services. This service-linked role is present in all organizations and not just in a specific OU.