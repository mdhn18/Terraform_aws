# Terraform_aws automation
command to run it ...


1. Pluging for the provider or talk to the ASW, AZURE, GCP

```
terraform init 
```

```
terraform plan
terraform apply –auto-approve
```

AWS: all documentation:

https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/appstream_user_stack_association

Azure all documentation:

https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs

Google all documentation:

https://registry.terraform.io/providers/hashicorp/google/latest/do


## Provisioning Cloud Resources
# Three approaches 
```
1. GUI with cloud provider 
2. API/CLI 
3. IaC (Infrastucture as Code)
```

# What is Infrastucture as Code (IaC)
- Categories of IaC tools:
```
1. Ad hoc scripts (shell csripts)
2. Configuration mangement tools. (Asible, puppet, manage to the SW or configuration)
3. Server Templating tools (Ami template)
4. Orchestration tools (Kubernatives application deployment)
5. Provisioning tools (Declarative vs. Imperative)
```
# IaC Provisioning Tools Landscape
- Cloud Specific:
```
1. Cloud Formation
2. Azure Resource Manager
3. Google cloud Deployment Manger
```
- Cloud Agnostic: 
```
1. Terraform 
2. Pulumi
```
<img width="1804" height="598" alt="image" src="https://github.com/user-attachments/assets/ddd73bdc-6d68-45c9-ab08-88e036e4204b" />
