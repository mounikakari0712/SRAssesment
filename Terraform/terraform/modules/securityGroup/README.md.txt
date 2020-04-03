First needs to run terraform with aws access key and secret key.

Terraform commands:

terraform init

terraform plan

terraform apply

terraform destroy

Then run ansible to provision webserver servers.

Ansible command: ansible-playbook playbook.yml