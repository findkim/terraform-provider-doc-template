---
layout: "foo"
page_title: "Foo: foo_service"
sidebar_current: "docs-foo-data-source-service"
description: |-
  The data source description.
---

# foo_service

Description paragraph for data source service

## Example Usage

```hcl
data "foo_service" "example" {
	name = "the-foo-bar-experience"
}
```

## Argument Reference
The following arguments are supported:

* `name` - (Optional) The name of the source.

## Attributes Reference
The following attributes are exported:

* `id` - The ID of the service.
