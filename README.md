NOTE: This is EXPERIMENTAL.

TLDR; A Node.js application to help manage multiple Terraform configurations with dreams of application lifecycle nirvana. Personal project, not a programmer.

SimpleStack attempts to glue together some great tooling to provide event-based, multi-cloud application lifecycle management.

Some intended tooling includes several from Hashicorp including Packer and Terraform as well as Prometheus. For SimpleStack itself, I'm looking at Express/React with an OpenAPI 3.0 compliant API. If it works out, I want to add more capabilities to help manage a full and flexible application pipeline.

Tentative Data Model:

* Tenants
  * Projects
    * Stacks
      * Catalog Items
      * Events
      * Health
      * Metrics
      * Operations
  * Providers
* Catalogs
  * Applications
  * Infrastructure
  * Services
* Images
  * Container?
  * Operating System
* Users
