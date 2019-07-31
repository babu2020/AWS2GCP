# VPN-From-AWS-To-GCP

Here is the Terraform configuration. You will need to set the following environment variables:

AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY

Put them all together on the same directory. The bastion.pem is the key you will use to login to the bastion instance.

Run 'terraform apply' to create the AWS resources.
Run 'terraform destroy' to destroy the AWS resources when you are done.
