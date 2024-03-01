<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-azure-linux-virtual-machine-scale-set/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraspace Azure Linux Virtual Machine Scale Set

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

Creates a Linux Virtual Machine Scale Set

* Azure Docs: [What are virtual machine scale sets?](https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/overview)
* Terraform Docs: [azurerm_linux_virtual_machine_scale_set](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/linux_virtual_machine_scale_set)

## Env Vars

You should configure these env vars:

* ARM_CLIENT_ID
* ARM_CLIENT_SECRET
* ARM_SUBSCRIPTION_ID
* ARM_TENANT_ID

As covered in: [Terraspace Azure Getting Started Docs: Configure Azure](https://terraspace.cloud/docs/learn/azure/configure/)

## Deploy

To deploy:

    terraspace up linux_scaleset

## Video

[![Watch the video](https://uploads-learn.boltops.com/pzenal2iod7kvp85nssa7m83d75e)](https://learn.boltops.com/courses/terraspace-azure/lessons/terraspace-azure-linux-virtual-machine-scale-set)

Note: Premium video content requires a subscription.
