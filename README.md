# Oracle Database 19c (oracle-database-19c)

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

Oracle Database 19c is a multi-model database management system that provides a comprehensive platform for enterprise data management, analytics, and application development.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/oracle-database-19c/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/oracle-database-19c/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Database
- Enterprise
- Json
- Machine-Learning
- Nosql
- Oracle
- Rest
- Sql

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Oracle REST Data Services (ORDS)

RESTful web services for Oracle Database enabling HTTP access to database resources, SQL queries, and PL/SQL procedures.

- **Human URL:** [https://www.oracle.com/database/technologies/appdev/rest.html](https://www.oracle.com/database/technologies/appdev/rest.html)
- **Base URL:** `https://example.oracle.com:8443/ords/`

#### Tags

- Database
- Oracle
- Rest
- Sql

#### Properties

- [Documentation](https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/19.2/)
- [API Reference](https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/19.2/orrst/)
- [Authentication](https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/19.2/orddg/developing-REST-applications.html)
- [OpenAPI](openapi/oracle-database-19c-ords-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-database-19c-ords.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-database-19c-ords.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/oracle-database-19c-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Oracle Database SODA (Simple Oracle Document Access)

Document-oriented NoSQL-style API for storing, retrieving, and querying JSON documents in Oracle Database.

- **Human URL:** [https://docs.oracle.com/en/database/oracle/simple-oracle-document-access/](https://docs.oracle.com/en/database/oracle/simple-oracle-document-access/)
- **Base URL:** `https://example.oracle.com:8443/ords/`

#### Tags

- Document-Store
- Json
- Nosql
- Oracle

#### Properties

- [Documentation](https://docs.oracle.com/en/database/oracle/simple-oracle-document-access/rest/)
- [R E S T  A P I  Guide](https://docs.oracle.com/en/database/oracle/simple-oracle-document-access/rest/adrst/index.html)
- [Tutorial](https://oracle.github.io/json-in-db/)
- [JSON Schema](json-schema/oracle-database-19c-soda-collection.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/oracle-database-19c-soda-document.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/oracle-database-19c-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Postman Collection](collections/oracle-database-19c-ords.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-database-19c-ords.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle SQL Developer Web

Browser-based interface for Oracle Database providing SQL worksheet, data modeler, and database administration capabilities.

- **Human URL:** [https://www.oracle.com/database/technologies/appdev/sql-developer-web.html](https://www.oracle.com/database/technologies/appdev/sql-developer-web.html)
- **Base URL:** `https://example.oracle.com:8443/ords/sql-developer/`

#### Tags

- Administration
- Development
- Sql
- Web-Interface

#### Properties

- [Documentation](https://docs.oracle.com/en/database/oracle/sql-developer-web/)
- [Getting Started](https://docs.oracle.com/en/database/oracle/sql-developer-web/sdwad/)
- [Postman Collection](collections/oracle-database-19c-ords.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-database-19c-ords.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Database API for MongoDB

MongoDB-compatible API allowing MongoDB applications to connect to Oracle Database.

- **Human URL:** [https://www.oracle.com/database/mongodb-api/](https://www.oracle.com/database/mongodb-api/)
- **Base URL:** `mongodb://example.oracle.com:27017/`

#### Tags

- Compatibility
- Document-Store
- Mongodb
- Nosql

#### Properties

- [Documentation](https://docs.oracle.com/en/database/oracle/mongodb-api/)
- [Quick  Start](https://www.oracle.com/database/mongodb-api/quickstart.html)
- [Postman Collection](collections/oracle-database-19c-ords.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-database-19c-ords.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Database JSON Collections API

RESTful API for managing JSON document collections with CRUD operations.

- **Human URL:** [https://docs.oracle.com/en/database/oracle/oracle-database/19/adjsn/](https://docs.oracle.com/en/database/oracle/oracle-database/19/adjsn/)
- **Base URL:** `https://example.oracle.com:8443/ords/`

#### Tags

- Collections
- Document-Api
- Json
- Rest

#### Properties

- [Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/adjsn/json-collections.html)
- [Developer  Guide](https://docs.oracle.com/en/database/oracle/oracle-database/19/adjsn/)
- [Postman Collection](collections/oracle-database-19c-ords.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-database-19c-ords.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Database REST API for AutoML

REST APIs for Oracle Machine Learning AutoML capabilities including model building and deployment.

- **Human URL:** [https://docs.oracle.com/en/database/oracle/machine-learning/](https://docs.oracle.com/en/database/oracle/machine-learning/)
- **Base URL:** `https://example.oracle.com:8443/omlmod/`

#### Tags

- Ai
- Analytics
- Automl
- Machine-Learning

#### Properties

- [Documentation](https://docs.oracle.com/en/database/oracle/machine-learning/oml4sql/19/)
- [API Reference](https://docs.oracle.com/en/cloud/paas/autonomous-database/omlug/rest-endpoints.html)
- [Postman Collection](collections/oracle-database-19c-ords.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-database-19c-ords.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/oracle)
- [Licensing](https://www.oracle.com/database/technologies/database19c-license.html)
- [Security  Alerts](https://www.oracle.com/security-alerts/)
- [Support  Portal](https://support.oracle.com)
- [Community  Forums](https://community.oracle.com/tech/developers/categories/oracle-database)
- [Downloads](https://www.oracle.com/database/technologies/oracle-database-software-downloads.html)
- [Pricing](https://www.oracle.com/database/technologies/database-pricing.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
