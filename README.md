# Longhorn (longhorn)

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
