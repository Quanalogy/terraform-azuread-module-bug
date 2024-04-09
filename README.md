# terraform-azuread-module-bug
A PoC repo for showcasing a bug with terraform and azuread where when an azuread_group is being created in a module it will after create not resolve any ID. This is only available after first time run.
