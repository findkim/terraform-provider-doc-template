---
layout: "foo"
page_title: "Provider: Foo"
sidebar_current: "docs-foo-index"
description: |-
  The Foo provider is used to interact with the many resources supported by FooCloud.
---

# Foo Provider

Description paragraph for provider Foo

## Example Usage

```hcl
# Configure the Foo Provider
provider "foo" {
	user_name = "admin"
	password = "admin"
}

resource "foobar" "example" {
	name = "the-foo-bar-experience"
}
```

## Argument Reference
The following arguments are supported:

* `user_name` - (Required) The username for HTTP basic authentication.
* `password` - (Required) The password to use for HTTP authentication.
* `arg1` - (Optional) arg1 description
* `arg2` - (Optional) arg2 description
