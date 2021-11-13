# Terraform course

`terraform show`  shows the resources information

`terraform providers`  shows a list of all the providers used on a project

`terraform output`  or `terraform output NAME_OF_THE_RESOURCES`

`terraform refresh`  To sync manual changes on the infrastructure with state file, this command modify the state file

## Mutable vs Immutable Resources

Mutable infrastructure: We don't destroy the infrastructure to make update or changes on the infrastructure
Immutable infrastructure: We destroy the old infrastructure to make updates or changes (Immutable means don't changes)

__Configuration drift:__ when the settings (dependencies, updates or configurations) between two or more servers that provide the same services are different from a baseline

## Lifecycles rules on Terraform 

* `create_before_destroy = true`
* `prevent_destroy = true`  This prevent deleting your infrastructure by accident, the only way to destroy a resource is using the `terraform destroy` command

