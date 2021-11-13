# Terraform course

`terraform show`  shows the resources information

`terraform providers`  shows a list of all the providers used on a project

`terraform output`  or `terraform output NAME_OF_THE_RESOURCES`

`terraform refresh`  modify the state file

`Mutable vrs Immutable Resources`

Mutable infrastructure: We don't destroy the infrastructure to make update or changes on the infrastructure
Immutable infrastructure: We destroy the old infrastructure to make updates or changes (Immutable means don't changes)

`Configuration drift:` when the settings (dependencies, updates or configurations) between two or more servers that provide the same services are different from a baseline

## Lifecycles rules on Terraform 

* `create_before_destroy = true`
* `prevent_destroy = true`  The only way to destroy a resource is using the ```terraform destroy``` command

