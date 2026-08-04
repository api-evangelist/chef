# Chef (chef)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
