# Dummy Module 1

This is a dummy Terraform module that creates a null resource.

## Usage

```hcl
module "dummy_1" {
  source = "./terraform/dummy-module-1"
}
```

## Resources

- `null_resource.dummy` - A dummy null resource
