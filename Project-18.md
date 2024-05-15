## **Documentation for Project 18**

### Automate Infrastructure With IAC using Terraform Part 3

### Terraform Module and Packer Machine Image Build Automation

### Refactoring our Terraform code into modules for best practice and to structure our TF code. Below is a tree representation of my directory after refactoring

![Terraform-codes-arranged-into-modules](./Images/Terraform-codes-arranged-into-modules.png)

### Creating S3 Bucket and dynamodb to manage our terraform state file and lock file

![S3-bucket-creation](./Images/S3-bucket-creation.png)

### S3 Bucket and dynamodb launched with empty files due to S3 Backend not initialized yet

![S3-bucket-creation](./Images/S3-bucket-created.png)

![terraform-locks-created-in-dynamo-DB](./Images/terraform-locks-created-in-dynamo-DB.png)

### S3 backend initialized so as to manage our terraform state file and lock file using S£ bucket and Dynamodb

![creating-S3-Backend](./Images/creating-S3-Backend.png)

### Tfstate file and State lock being handled by S3 bucket and Dynamodb respectively after running terraform plan

![tfstate-managed-by-S3-bucket](./Images/tfstate-managed-by-S3-bucket.png)

![tfstate-lock-managed-by-dynamodb](./Images/tfstate-lock-managed-by-dynamodb.png)