---
layout: "foo"
page_title: "Foo: foo_foobar"
sidebar_current: "docs-foo-resource-foobar"
description: |-
  The resource description.
---

# foo_foobar

Description paragraph for resource foobar

## Example Usage

```hcl
resource "foobar" "example" {
	name = "the-foo-bar-experience"
}
```

## Argument Reference
The following arguments are supported:

* `name` - (Optional) The name of the resource.

## Attributes Reference
The following computed attributes are exported:

* `created_at` - The timestamp resource was created in RFC3339 text format.
