# Terraform
[DOCUMENTATION OFFICIELLE](https://learn.hashicorp.com/terraform)
## Prerequis

[Download](https://www.terraform.io/downloads) Terraform

Verify that the installation worked by opening a new terminal session and listing Terraform's available subcommands.
```bash
terraform -h
```

Any Troubleshoot ?  
Visit terraform [Documentation](https://learn.hashicorp.com/tutorials/terraform/install-cli?in=terraform/aws-get-started#troubleshoot)
## Configuration for each cloud provider

[Get Started](https://learn.hashicorp.com/terraform)

## Commands

Initialize a configuration
```bash
terraform init
```
Apply the configuration
```bash
terraform Apply
```
Apply custom variables from terminal
```bash
terraform apply -var "instance_name=YetAnotherName"
```
Destroy the resources you created
```bash
terraform destroy
```
Terraform prints output values to the screen when you apply your configuration. Query the outputs with the terraform output command.
```bash
terraform output
terraform output <output_name>
```