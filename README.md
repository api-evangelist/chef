# Chef (chef)

Chef (Progress Chef) provides infrastructure automation, compliance, and application delivery tooling. Chef exposes REST APIs for the Infra Server (managing nodes, cookbooks, roles, environments, and data bags), Chef Automate (visibility into convergence, compliance, and deployment), Habitat Builder (application packaging and delivery), and InSpec (a language and runner for security and compliance testing).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/chef/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/chef/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Application Delivery
- Automation
- Compliance
- Configuration Management
- DevOps
- DevSecOps
- Habitat
- Infrastructure as Code
- InSpec

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Chef Infra Server API

REST API for managing nodes, cookbooks, roles, environments, data bags, clients, and users on the Chef Infra Server. Authentication uses Chef signed-header authentication with an RSA client key.

- **Human URL:** [https://docs.chef.io/server/api_chef_server/](https://docs.chef.io/server/api_chef_server/)
- **Base URL:** `https://chef.example.com/organizations/example`

#### Tags

- Configuration Management
- Infrastructure

#### Properties

- [Documentation](https://docs.chef.io/server/api_chef_server/)
- [Authentication](https://docs.chef.io/server/server_security/)
- [OpenAPI](openapi/chef-infra-server-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chef-infra-server-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chef-infra-server-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chef Automate API

REST API for Chef Automate providing visibility into infrastructure convergence, compliance scans, and application deployment. Includes compliance profiles, scan jobs, reports, IAM, and configuration management endpoints.

- **Human URL:** [https://docs.chef.io/automate/api/](https://docs.chef.io/automate/api/)
- **Base URL:** `https://automate.example.com/api/v0`

#### Tags

- Automation
- Compliance
- Observability

#### Properties

- [Documentation](https://docs.chef.io/automate/api/)
- [Reference](https://docs.chef.io/automate/api_swagger/)
- [Authentication](https://docs.chef.io/automate/api_tokens/)
- [OpenAPI](openapi/chef-automate-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chef-automate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chef-automate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chef Habitat Builder API

REST API for Chef Habitat Builder, the package management service for Habitat application packages. Manages origins, packages, channels, and deployment events.

- **Human URL:** [https://docs.habitat.sh/docs/using-builder/](https://docs.habitat.sh/docs/using-builder/)
- **Base URL:** `https://bldr.habitat.sh/v1`

#### Tags

- Application Packaging
- Deployment
- Habitat

#### Properties

- [Documentation](https://docs.habitat.sh/docs/using-builder/)
- [Authentication](https://docs.habitat.sh/docs/using-builder/)
- [OpenAPI](openapi/chef-habitat-builder-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chef-habitat-builder-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chef-habitat-builder-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chef InSpec

InSpec is an open-source language and runner for security and compliance testing. It is consumed via the InSpec CLI and Ruby DSL, and surfaced inside Chef Automate as compliance profiles, scan jobs, and reports.

- **Human URL:** [https://docs.chef.io/inspec/](https://docs.chef.io/inspec/)

#### Tags

- Compliance
- Security
- Testing

#### Properties

- [Documentation](https://docs.chef.io/inspec/)
- [Git Hub](https://github.com/inspec/inspec)
- [Postman Collection](collections/chef-automate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chef-automate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chef-habitat-builder-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chef-habitat-builder-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chef-infra-server-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chef-infra-server-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/chef-software)
- [Website](https://www.chef.io/)
- [Documentation](https://docs.chef.io/)
- [Getting Started](https://docs.chef.io/)
- [Blog](https://www.chef.io/blog)
- [Git Hub](https://github.com/chef)
- [Support](https://www.chef.io/support)
- [Training](https://training.chef.io/)
- [Community](https://community.chef.io/)
- [Status Page](https://status.chef.io/)
- [Terms of Service](https://www.chef.io/terms-of-service)
- [Privacy Policy](https://www.chef.io/privacy-policy)
- [JSON-LD](json-ld/chef-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/chef-node-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/chef-role-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/chef-compliance-profile-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](spectral/chef-spectral.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
