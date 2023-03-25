# terraform
# Terraform Commands
terraform init
terraform plan
terraform apply
terraform destroy

terraform show
terraform output
terraform console
terraform import
terraform taint
Terraform State Commands
terraform state show
terraform state list
terraform state pull
terraform state rm
terraform state mv
terraform state push
for x in $(terraform state list | grep xyz); do terraform state mv -state-out=”terraform.tfstate”  $x $x; done

Terraform Workspace Commands
terraform workspace show
terraform workspace list
terraform workspace new
terraform workspace select
terraform workspace delete
${terraform.workspace}