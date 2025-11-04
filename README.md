# aws-IAAC
Repo for AWS Resource management and configuration using IAAC

# Setup Terraform Storage Backend
Inorder to use Terraform, you will either need to create the following manually or bootstrap by running Terraform without Storage Backend
* **S3 Bucket** for Terraform State files (terraform.tfstate)
* **DynamoDB table** to enable state locking (to prevent concurrent modifications)
