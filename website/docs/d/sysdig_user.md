---
layout: "sysdig"
page_title: "Sysdig: sysdig_user"
sidebar_current: "docs-sysdig-user-ds"
description: |-
  Retrieves information about a user from their email
---

# sysdig\_user

Retrieves information about a user from their email

`~> **Note:** Sysdig Terraform Provider is under rapid development at this point. If you experience any issue or discrepancy while using it, please make sure you have the latest version. If the issue persists, or you have a Feature Request to support an additional set of resources, please open a [new issue](https://github.com/sysdiglabs/terraform-provider-sysdig/issues/new) in the GitHub repository.`

## Example usage

```hcl
data "sysdig_user" "user" {
	email = "terraform-test+user@sysdig.com"
}
```

## Attributes Reference

* `id` - The user's ID.

* `first_name` - The user's first name.

* `last_name` - The user's last name.

* `system_role` - The user's system role.