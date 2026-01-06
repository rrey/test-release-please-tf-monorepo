# Dummy Module 2

This is a dummy Terraform module that creates a null resource.

## Usage

```hcl
module "dummy_2" {
  source = "./terraform/dummy-module-2"
}
```

## Resources

- `null_resource.dummy` - A dummy null resource with a timestamp trigger
