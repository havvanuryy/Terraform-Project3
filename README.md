# Test-TerraformModules

## Creating  Resource group and Storage account by using variables and modules

The Terraform Registry hosts a broad collection of publicly available providers and modules. Modules could be used for quickly deploying common infrastructure configurations and downloaded automatically if the appropriate source and version in a module is specified.

In order to create resource group and storage account, main.tf file is created.
After .tf files are created, we need to log in to our Azure account.

# to log in Azure portal
az login
The terraform init command initializes a working directory containing Terraform configuration files.

This is the first command that should be run after writing a new Terraform configuration or cloning an existing one from version control.


# to initialize a working directory
terraform init
The terraform plan command creates an execution plan, which lets you preview the changes that Terraform plans to make to your infrastructure. By default, when Terraform creates a plan it:

Reads the current state of any already-existing remote objects to make sure that the Terraform state is up-to-date.
Compares the current configuration to the prior state and noting any differences.
Proposes a set of change actions that should, if applied, make the remote objects match the configuration. For further information and usage see.
# to create execution plan
terraform plan
The terraform apply command executes the actions proposed in a Terraform plan. For further information and usage see.

# to execute .tf files
terraform apply
Finally, we can log in to Azure Portal and see our resource group and resources in it. Here is an example.
