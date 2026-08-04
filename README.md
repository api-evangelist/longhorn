# Longhorn (longhorn)

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

Longhorn is a CNCF incubating lightweight, reliable, and easy-to-use distributed block storage system for Kubernetes. It creates a dedicated storage controller for each volume and replicates data across multiple nodes for high availability. Longhorn supports snapshots, backups to S3-compatible storage, disaster recovery, and recurring backup schedules.

**APIs.json:** [https://longhorn.io](https://longhorn.io)

## Scope

- **Type:** Index

## Tags

- Backup
- Block Storage
- Cloud Native
- Incubating
- Kubernetes
- Persistent Volumes

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Longhorn Manager API

The Longhorn Manager exposes a REST API for volume lifecycle management including creating, attaching, detaching, and deleting volumes. It also provides endpoints for snapshot management, backup operations, node management, engine image management, and system settings configuration. The API is used by the Longhorn UI and can be accessed directly for automation.

- **Human URL:** [https://longhorn.io/docs/](https://longhorn.io/docs/)

#### Tags

- REST API
- Snapshots
- Volume Management

#### Properties

- [Documentation](https://longhorn.io/docs/)
- [GitHub Repository](https://github.com/longhorn/longhorn)
- [OpenAPI](openapi/longhorn-manager-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/longhorn-manager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/longhorn-manager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/longhorn-volume-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [JSON-LD](json-ld/longhorn-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/longhorn-volume-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Website](https://longhorn.io/)
- [Documentation](https://longhorn.io/docs/)
- [Getting Started](https://longhorn.io/docs/1.11.1/deploy/install/)
- [Blog](https://longhorn.io/blog/)
- [Changelog](https://github.com/longhorn/longhorn/releases)
- [GitHub Organization](https://github.com/longhorn)
- [GitHub Repository](https://github.com/longhorn/longhorn)
- [Community](https://longhorn.io/community/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
