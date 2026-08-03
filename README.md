# Amazon QLDB

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

Amazon Quantum Ledger Database (QLDB) is a fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log. QLDB tracks each and every application data change and maintains a complete and verifiable history of changes over time, making it ideal for systems of record where data integrity and auditability are critical.

**URL:** [Visit APIs.json URL](https://aws.amazon.com/qldb/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Blockchain, Database, Ledger

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon QLDB API
The Amazon QLDB API provides programmatic access to manage ledger databases with immutable, transparent, and cryptographically verifiable transaction logs. It enables developers to create and manage ledgers, submit PartiQL statements, stream journal data, and export ledger blocks for verification and auditing purposes.

**Human URL:** [https://aws.amazon.com/qldb/](https://aws.amazon.com/qldb/)

#### Tags:

 - AWS, Blockchain, Database, Ledger

#### Properties

- [Documentation](https://docs.aws.amazon.com/qldb/)
- [OpenAPI](openapi/amazon-qldb-openapi.yml)
- [Pricing](https://aws.amazon.com/qldb/pricing/)
- [Getting Started](https://aws.amazon.com/qldb/getting-started/)
- [FAQ](https://aws.amazon.com/qldb/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/qldb/)
- [Documentation](https://docs.aws.amazon.com/qldb/)
- [Terms of Service](https://aws.amazon.com/service-terms/)
- [Privacy Policy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [GitHub Organization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/qldb/)
- [Sign Up](https://signin.aws.amazon.com/signup?request_type=register)
- [Login](https://aws.amazon.com/console/)
- [Status](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)
- [JSON-LD](json-ld/amazon-qldb-context.jsonld)
- [JSONSchema](json-schema/amazon-qldb-cancel-journal-kinesis-stream-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-create-ledger-request-schema.json)
- [JSONSchema](json-schema/amazon-qldb-create-ledger-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-describe-journal-kinesis-stream-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-describe-journal-s3export-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-describe-ledger-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-encryption-status-schema.json)
- [JSONSchema](json-schema/amazon-qldb-error-cause-schema.json)
- [JSONSchema](json-schema/amazon-qldb-export-journal-to-s3request-schema.json)
- [JSONSchema](json-schema/amazon-qldb-export-journal-to-s3response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-export-status-schema.json)
- [JSONSchema](json-schema/amazon-qldb-get-block-request-schema.json)
- [JSONSchema](json-schema/amazon-qldb-get-block-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-get-digest-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-get-revision-request-schema.json)
- [JSONSchema](json-schema/amazon-qldb-get-revision-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-journal-kinesis-stream-description-schema.json)
- [JSONSchema](json-schema/amazon-qldb-journal-s3export-description-schema.json)
- [JSONSchema](json-schema/amazon-qldb-kinesis-configuration-schema.json)
- [JSONSchema](json-schema/amazon-qldb-ledger-encryption-description-schema.json)
- [JSONSchema](json-schema/amazon-qldb-ledger-state-schema.json)
- [JSONSchema](json-schema/amazon-qldb-ledger-summary-schema.json)
- [JSONSchema](json-schema/amazon-qldb-list-journal-kinesis-streams-for-ledger-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-list-journal-s3exports-for-ledger-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-list-journal-s3exports-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-list-ledgers-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-list-tags-for-resource-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-output-format-schema.json)
- [JSONSchema](json-schema/amazon-qldb-permissions-mode-schema.json)
- [JSONSchema](json-schema/amazon-qldb-s3encryption-configuration-schema.json)
- [JSONSchema](json-schema/amazon-qldb-s3export-configuration-schema.json)
- [JSONSchema](json-schema/amazon-qldb-s3object-encryption-type-schema.json)
- [JSONSchema](json-schema/amazon-qldb-stream-journal-to-kinesis-request-schema.json)
- [JSONSchema](json-schema/amazon-qldb-stream-journal-to-kinesis-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-stream-status-schema.json)
- [JSONSchema](json-schema/amazon-qldb-tag-resource-request-schema.json)
- [JSONSchema](json-schema/amazon-qldb-update-ledger-permissions-mode-request-schema.json)
- [JSONSchema](json-schema/amazon-qldb-update-ledger-permissions-mode-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-update-ledger-request-schema.json)
- [JSONSchema](json-schema/amazon-qldb-update-ledger-response-schema.json)
- [JSONSchema](json-schema/amazon-qldb-value-holder-schema.json)
- [JSONStructure](json-structure/amazon-qldb-cancel-journal-kinesis-stream-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-create-ledger-request-structure.json)
- [JSONStructure](json-structure/amazon-qldb-create-ledger-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-describe-journal-kinesis-stream-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-describe-journal-s3export-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-describe-ledger-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-encryption-status-structure.json)
- [JSONStructure](json-structure/amazon-qldb-error-cause-structure.json)
- [JSONStructure](json-structure/amazon-qldb-export-journal-to-s3request-structure.json)
- [JSONStructure](json-structure/amazon-qldb-export-journal-to-s3response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-export-status-structure.json)
- [JSONStructure](json-structure/amazon-qldb-get-block-request-structure.json)
- [JSONStructure](json-structure/amazon-qldb-get-block-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-get-digest-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-get-revision-request-structure.json)
- [JSONStructure](json-structure/amazon-qldb-get-revision-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-journal-kinesis-stream-description-structure.json)
- [JSONStructure](json-structure/amazon-qldb-journal-s3export-description-structure.json)
- [JSONStructure](json-structure/amazon-qldb-kinesis-configuration-structure.json)
- [JSONStructure](json-structure/amazon-qldb-ledger-encryption-description-structure.json)
- [JSONStructure](json-structure/amazon-qldb-ledger-state-structure.json)
- [JSONStructure](json-structure/amazon-qldb-ledger-summary-structure.json)
- [JSONStructure](json-structure/amazon-qldb-list-journal-kinesis-streams-for-ledger-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-list-journal-s3exports-for-ledger-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-list-journal-s3exports-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-list-ledgers-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-list-tags-for-resource-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-output-format-structure.json)
- [JSONStructure](json-structure/amazon-qldb-permissions-mode-structure.json)
- [JSONStructure](json-structure/amazon-qldb-s3encryption-configuration-structure.json)
- [JSONStructure](json-structure/amazon-qldb-s3export-configuration-structure.json)
- [JSONStructure](json-structure/amazon-qldb-s3object-encryption-type-structure.json)
- [JSONStructure](json-structure/amazon-qldb-stream-journal-to-kinesis-request-structure.json)
- [JSONStructure](json-structure/amazon-qldb-stream-journal-to-kinesis-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-stream-status-structure.json)
- [JSONStructure](json-structure/amazon-qldb-tag-resource-request-structure.json)
- [JSONStructure](json-structure/amazon-qldb-update-ledger-permissions-mode-request-structure.json)
- [JSONStructure](json-structure/amazon-qldb-update-ledger-permissions-mode-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-update-ledger-request-structure.json)
- [JSONStructure](json-structure/amazon-qldb-update-ledger-response-structure.json)
- [JSONStructure](json-structure/amazon-qldb-value-holder-structure.json)
- [Example](examples/amazon-qldb-cancel-journal-kinesis-stream-response-example.json)
- [Example](examples/amazon-qldb-create-ledger-request-example.json)
- [Example](examples/amazon-qldb-create-ledger-response-example.json)
- [Example](examples/amazon-qldb-describe-journal-kinesis-stream-response-example.json)
- [Example](examples/amazon-qldb-describe-journal-s3export-response-example.json)
- [Example](examples/amazon-qldb-describe-ledger-response-example.json)
- [Example](examples/amazon-qldb-export-journal-to-s3request-example.json)
- [Example](examples/amazon-qldb-export-journal-to-s3response-example.json)
- [Example](examples/amazon-qldb-get-block-request-example.json)
- [Example](examples/amazon-qldb-get-block-response-example.json)
- [Example](examples/amazon-qldb-get-digest-response-example.json)
- [Example](examples/amazon-qldb-get-revision-request-example.json)
- [Example](examples/amazon-qldb-get-revision-response-example.json)
- [Example](examples/amazon-qldb-journal-kinesis-stream-description-example.json)
- [Example](examples/amazon-qldb-journal-s3export-description-example.json)
- [Example](examples/amazon-qldb-kinesis-configuration-example.json)
- [Example](examples/amazon-qldb-ledger-encryption-description-example.json)
- [Example](examples/amazon-qldb-ledger-summary-example.json)
- [Example](examples/amazon-qldb-list-journal-kinesis-streams-for-ledger-response-example.json)
- [Example](examples/amazon-qldb-list-journal-s3exports-for-ledger-response-example.json)
- [Example](examples/amazon-qldb-list-journal-s3exports-response-example.json)
- [Example](examples/amazon-qldb-list-ledgers-response-example.json)
- [Example](examples/amazon-qldb-list-tags-for-resource-response-example.json)
- [Example](examples/amazon-qldb-s3encryption-configuration-example.json)
- [Example](examples/amazon-qldb-s3export-configuration-example.json)
- [Example](examples/amazon-qldb-stream-journal-to-kinesis-request-example.json)
- [Example](examples/amazon-qldb-stream-journal-to-kinesis-response-example.json)
- [Example](examples/amazon-qldb-tag-resource-request-example.json)
- [Example](examples/amazon-qldb-update-ledger-permissions-mode-request-example.json)
- [Example](examples/amazon-qldb-update-ledger-permissions-mode-response-example.json)
- [Example](examples/amazon-qldb-update-ledger-request-example.json)
- [Example](examples/amazon-qldb-update-ledger-response-example.json)
- [Example](examples/amazon-qldb-value-holder-example.json)
- [NaftikoCapability](capabilities/shared/amazon-qldb.yaml)
- [SpectralRules](rules/amazon-qldb-spectral-rules.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-qldb-openapi-original.yaml](openapi/amazon-qldb-openapi-original.yaml)

### JSON Schema

- [amazon-qldb-cancel-journal-kinesis-stream-response-schema.json](json-schema/amazon-qldb-cancel-journal-kinesis-stream-response-schema.json)
- [amazon-qldb-create-ledger-request-schema.json](json-schema/amazon-qldb-create-ledger-request-schema.json)
- [amazon-qldb-create-ledger-response-schema.json](json-schema/amazon-qldb-create-ledger-response-schema.json)
- [amazon-qldb-describe-journal-kinesis-stream-response-schema.json](json-schema/amazon-qldb-describe-journal-kinesis-stream-response-schema.json)
- [amazon-qldb-describe-journal-s3export-response-schema.json](json-schema/amazon-qldb-describe-journal-s3export-response-schema.json)
- [amazon-qldb-describe-ledger-response-schema.json](json-schema/amazon-qldb-describe-ledger-response-schema.json)
- [amazon-qldb-encryption-status-schema.json](json-schema/amazon-qldb-encryption-status-schema.json)
- [amazon-qldb-error-cause-schema.json](json-schema/amazon-qldb-error-cause-schema.json)
- [amazon-qldb-export-journal-to-s3request-schema.json](json-schema/amazon-qldb-export-journal-to-s3request-schema.json)
- [amazon-qldb-export-journal-to-s3response-schema.json](json-schema/amazon-qldb-export-journal-to-s3response-schema.json)
- ...and 31 more

### JSON Structure

- [amazon-qldb-cancel-journal-kinesis-stream-response-structure.json](json-structure/amazon-qldb-cancel-journal-kinesis-stream-response-structure.json)
- [amazon-qldb-create-ledger-request-structure.json](json-structure/amazon-qldb-create-ledger-request-structure.json)
- [amazon-qldb-create-ledger-response-structure.json](json-structure/amazon-qldb-create-ledger-response-structure.json)
- [amazon-qldb-describe-journal-kinesis-stream-response-structure.json](json-structure/amazon-qldb-describe-journal-kinesis-stream-response-structure.json)
- [amazon-qldb-describe-journal-s3export-response-structure.json](json-structure/amazon-qldb-describe-journal-s3export-response-structure.json)
- [amazon-qldb-describe-ledger-response-structure.json](json-structure/amazon-qldb-describe-ledger-response-structure.json)
- [amazon-qldb-encryption-status-structure.json](json-structure/amazon-qldb-encryption-status-structure.json)
- [amazon-qldb-error-cause-structure.json](json-structure/amazon-qldb-error-cause-structure.json)
- [amazon-qldb-export-journal-to-s3request-structure.json](json-structure/amazon-qldb-export-journal-to-s3request-structure.json)
- [amazon-qldb-export-journal-to-s3response-structure.json](json-structure/amazon-qldb-export-journal-to-s3response-structure.json)
- ...and 31 more

### JSON-LD

- [amazon-qldb-context.jsonld](json-ld/amazon-qldb-context.jsonld)

### Examples

- [amazon-qldb-cancel-journal-kinesis-stream-response-example.json](examples/amazon-qldb-cancel-journal-kinesis-stream-response-example.json)
- [amazon-qldb-create-ledger-request-example.json](examples/amazon-qldb-create-ledger-request-example.json)
- [amazon-qldb-create-ledger-response-example.json](examples/amazon-qldb-create-ledger-response-example.json)
- [amazon-qldb-describe-journal-kinesis-stream-response-example.json](examples/amazon-qldb-describe-journal-kinesis-stream-response-example.json)
- [amazon-qldb-describe-journal-s3export-response-example.json](examples/amazon-qldb-describe-journal-s3export-response-example.json)
- [amazon-qldb-describe-ledger-response-example.json](examples/amazon-qldb-describe-ledger-response-example.json)
- [amazon-qldb-export-journal-to-s3request-example.json](examples/amazon-qldb-export-journal-to-s3request-example.json)
- [amazon-qldb-export-journal-to-s3response-example.json](examples/amazon-qldb-export-journal-to-s3response-example.json)
- [amazon-qldb-get-block-request-example.json](examples/amazon-qldb-get-block-request-example.json)
- [amazon-qldb-get-block-response-example.json](examples/amazon-qldb-get-block-response-example.json)
- ...and 23 more

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [amazon-qldb.yaml](capabilities/shared/amazon-qldb.yaml)

## Rules

- [amazon-qldb-spectral-rules.yml](rules/amazon-qldb-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
