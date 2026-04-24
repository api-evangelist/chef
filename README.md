# Chef (chef)

Chef (Progress Chef) provides infrastructure automation, compliance, and application delivery tooling. Chef exposes REST APIs for the Infra Server (managing nodes, cookbooks, roles, environments, and data bags), Chef Automate (visibility into convergence, compliance, and deployment), Habitat Builder (application packaging and delivery), and InSpec (a language and runner for security and compliance testing).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/chef/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Application Delivery, Automation, Compliance, Configuration Management, DevOps, DevSecOps, Habitat, Infrastructure as Code, InSpec

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-23

## APIs

### Chef Infra Server API

REST API for managing nodes, cookbooks, roles, environments, data bags, clients, and users on the Chef Infra Server. Authentication uses Chef signed-header authentication with an RSA client key.

- **Documentation:** [https://docs.chef.io/server/api_chef_server/](https://docs.chef.io/server/api_chef_server/)
- **OpenAPI:** [openapi/chef-infra-server-api-openapi.yml](openapi/chef-infra-server-api-openapi.yml)

### Chef Automate API

REST API for Chef Automate providing visibility into infrastructure convergence, compliance scans, and application deployment. Includes compliance profiles, scan jobs, reports, IAM, and configuration management endpoints.

- **Documentation:** [https://docs.chef.io/automate/api/](https://docs.chef.io/automate/api/)
- **Reference:** [https://docs.chef.io/automate/api_swagger/](https://docs.chef.io/automate/api_swagger/)
- **OpenAPI:** [openapi/chef-automate-api-openapi.yml](openapi/chef-automate-api-openapi.yml)

### Chef Habitat Builder API

REST API for Chef Habitat Builder, the package management service for Habitat application packages. Manages origins, packages, channels, and deployment events.

- **Documentation:** [https://docs.habitat.sh/docs/using-builder/](https://docs.habitat.sh/docs/using-builder/)
- **OpenAPI:** [openapi/chef-habitat-builder-api-openapi.yml](openapi/chef-habitat-builder-api-openapi.yml)

### Chef InSpec

InSpec is an open-source language and runner for security and compliance testing. It is consumed via the InSpec CLI and Ruby DSL, and surfaced inside Chef Automate as compliance profiles, scan jobs, and reports.

- **Documentation:** [https://docs.chef.io/inspec/](https://docs.chef.io/inspec/)
- **GitHub:** [https://github.com/inspec/inspec](https://github.com/inspec/inspec)

## Common Properties

- [Website](https://www.chef.io/)
- [Documentation](https://docs.chef.io/)
- [Blog](https://www.chef.io/blog)
- [GitHub Organization](https://github.com/chef)
- [Support](https://www.chef.io/support)
- [Training](https://training.chef.io/)
- [Community](https://community.chef.io/)
- [Status](https://status.chef.io/)
- [Terms of Service](https://www.chef.io/terms-of-service)
- [Privacy Policy](https://www.chef.io/privacy-policy)
- [JSON-LD Context](json-ld/chef-context.jsonld)
- [Node JSON Schema](json-schema/chef-node-schema.json)
- [Role JSON Schema](json-schema/chef-role-schema.json)
- [Compliance Profile JSON Schema](json-schema/chef-compliance-profile-schema.json)
- [Spectral Rules](spectral/chef-spectral.yml)
- [Naftiko Capabilities](naftiko/chef-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
