# pet-nulls-stack

_This is an example stack configuration for the private preview of Terraform Stacks. Language
constructs and features are subject to change given feedback received during this preview. Do not
use Stacks for production workloads at this time._

<image>

This is a stack using two components, two environments, and the `random_pet` and `null_resource`
resources. The purpose is a no-authentication, state-only test of the stacks concepts. No identity
tokens are defined for OIDC authentication, no real infrastructure is provisioned.

_We do not recommend using this example within production accounts. This example will incur [small]
costs if provisioned. Please remember to destroy the infrastructure after using this example._

## Usage

_Prerequisites: You must have a Terraform Cloud account with access to the private preview of
Terraform Stacks and a GitHub account._

1. **Fork this repository** to your own GitHub account, such that you can edit this stack configuration
   for your purposes.
2. **Create a new stack** in Terraform Cloud and connect it to your forked configuration repository.
3. **"Provision" away!** Remember, this is a state-only example with no external effects.
