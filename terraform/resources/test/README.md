## Requirements

No requirements.

## Providers

No provider.

## Inputs

No input.

## Outputs

No output.

## Useful Terraform commands
terraform init -backend-config tf-backend.tfvars

terraform plan -var-file tf.tfvars

terraform apply -var-file tf.tfvars

terraform destroy -auto-approve

terraform validate

terraform fmt

terraform workspace new dev
terraform workspace select dev

terraform show

