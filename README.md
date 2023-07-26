# Terraform-Project3
## Testing Terraform Modules
## Creating  Resource group and Storage account by using variables and modules

The Terraform Registry hosts a broad collection of publicly available providers and modules. Modules could be used for quickly deploying common infrastructure configurations and downloaded automatically if the appropriate source and version in a module is specified.

In order to create resource group and storage account, **main.tf** file is created.
After .tf files are created, we need to log in to our Azure account.

```
# to log in Azure portal
az login
```

The **terraform init** command initializes a working directory containing Terraform configuration files.

This is the first command that should be run after writing a new Terraform configuration or cloning an existing one from version control.

```
# to initialize a working directory
terraform init
```

The **terraform plan** command creates an execution plan, letting you preview the changes Terraform plans to make to your infrastructure. 

```
# to create execution plan
terraform plan
```
The **terraform apply** command executes the actions proposed in a Terraform plan. 

```
# to execute .tf files
terraform apply
```

Finally, we can log in to Azure Portal and see our resource group and resources in it. Here is an [example](https://github.com/havvanuryy/Test-TerraformModules/blob/main/portalimage.PNG).
