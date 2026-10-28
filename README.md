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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

> **No longer operating.** This company or product has shut down, been discontinued, or been deprecated. This profile is kept as a historical record and is not maintained or rated.

Amazon Quantum Ledger Database (QLDB) is a fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log. QLDB tracks each and every application data change and maintains a complete and verifiable history of changes over time, making it ideal for systems of record where data integrity and auditability are critical.

**Areas:** AWS · Blockchain · Database · Ledger · Defunct

## Amazon QLDB on APIs.io (historical record)

Everything profiled for Amazon QLDB is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/amazon-qldb/](https://apis.io/providers/amazon-qldb/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Amazon QLDB Journal S3 Exports API](https://apis.io/apis/amazon-qldb/amazon-qldb-journal-s3-exports-api/) — The Journal S3 Exports API from Amazon QLDB — 1 operation(s) for journal s3 exports.
- [Amazon QLDB Ledgers API](https://apis.io/apis/amazon-qldb/amazon-qldb-ledgers-api/) — The Ledgers API from Amazon QLDB — 10 operation(s) for ledgers.
- [Amazon QLDB Tags API](https://apis.io/apis/amazon-qldb/amazon-qldb-tags-api/) — The Tags API from Amazon QLDB — 2 operation(s) for tags.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Amazon Qldb Agentic Access](https://apis.io/agentic-access/amazon-qldb/amazon-qldb-agentic-access/)

#### JSON Schema (41)

The data models the API reads and writes.

- [CancelJournalKinesisStreamResponse](https://apis.io/schemas/amazon-qldb/amazon-qldb-cancel-journal-kinesis-stream-response/)
- [CreateLedgerRequest](https://apis.io/schemas/amazon-qldb/amazon-qldb-create-ledger-request/)
- [CreateLedgerResponse](https://apis.io/schemas/amazon-qldb/amazon-qldb-create-ledger-response/)
- [DescribeJournalKinesisStreamResponse](https://apis.io/schemas/amazon-qldb/amazon-qldb-describe-journal-kinesis-stream-response/)
- [DescribeJournalS3ExportResponse](https://apis.io/schemas/amazon-qldb/amazon-qldb-describe-journal-s3export-response/)
- [DescribeLedgerResponse](https://apis.io/schemas/amazon-qldb/amazon-qldb-describe-ledger-response/)
- [EncryptionStatus](https://apis.io/schemas/amazon-qldb/amazon-qldb-encryption-status/)
- [ErrorCause](https://apis.io/schemas/amazon-qldb/amazon-qldb-error-cause/)
- [ExportJournalToS3Request](https://apis.io/schemas/amazon-qldb/amazon-qldb-export-journal-to-s3request/)
- [ExportJournalToS3Response](https://apis.io/schemas/amazon-qldb/amazon-qldb-export-journal-to-s3response/)
- [ExportStatus](https://apis.io/schemas/amazon-qldb/amazon-qldb-export-status/)
- [GetBlockRequest](https://apis.io/schemas/amazon-qldb/amazon-qldb-get-block-request/)
- [GetBlockResponse](https://apis.io/schemas/amazon-qldb/amazon-qldb-get-block-response/)
- [GetDigestResponse](https://apis.io/schemas/amazon-qldb/amazon-qldb-get-digest-response/)
- [GetRevisionRequest](https://apis.io/schemas/amazon-qldb/amazon-qldb-get-revision-request/)
- [GetRevisionResponse](https://apis.io/schemas/amazon-qldb/amazon-qldb-get-revision-response/)
- [JournalKinesisStreamDescription](https://apis.io/schemas/amazon-qldb/amazon-qldb-journal-kinesis-stream-description/)
- [JournalS3ExportDescription](https://apis.io/schemas/amazon-qldb/amazon-qldb-journal-s3export-description/)
- [KinesisConfiguration](https://apis.io/schemas/amazon-qldb/amazon-qldb-kinesis-configuration/)
- [LedgerEncryptionDescription](https://apis.io/schemas/amazon-qldb/amazon-qldb-ledger-encryption-description/)
- [LedgerState](https://apis.io/schemas/amazon-qldb/amazon-qldb-ledger-state/)
- [LedgerSummary](https://apis.io/schemas/amazon-qldb/amazon-qldb-ledger-summary/)
- [ListJournalKinesisStreamsForLedgerResponse](https://apis.io/schemas/amazon-qldb/amazon-qldb-list-journal-kinesis-streams-for-ledger-response/)
- [ListJournalS3ExportsForLedgerResponse](https://apis.io/schemas/amazon-qldb/amazon-qldb-list-journal-s3exports-for-ledger-response/)
- [ListJournalS3ExportsResponse](https://apis.io/schemas/amazon-qldb/amazon-qldb-list-journal-s3exports-response/)
- …and 16 more published on APIs.io

#### JSON Structure (41)

Data models expressed in JSON Structure.

- [Amazon Qldb Cancel Journal Kinesis Stream Response Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-cancel-journal-kinesis-stream-response-structure/)
- [Amazon Qldb Create Ledger Request Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-create-ledger-request-structure/)
- [Amazon Qldb Create Ledger Response Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-create-ledger-response-structure/)
- [Amazon Qldb Describe Journal Kinesis Stream Response Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-describe-journal-kinesis-stream-response-structure/)
- [Amazon Qldb Describe Journal S3Export Response Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-describe-journal-s3export-response-structure/)
- [Amazon Qldb Describe Ledger Response Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-describe-ledger-response-structure/)
- [Amazon Qldb Encryption Status Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-encryption-status-structure/)
- [Amazon Qldb Error Cause Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-error-cause-structure/)
- [Amazon Qldb Export Journal To S3Request Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-export-journal-to-s3request-structure/)
- [Amazon Qldb Export Journal To S3Response Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-export-journal-to-s3response-structure/)
- [Amazon Qldb Export Status Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-export-status-structure/)
- [Amazon Qldb Get Block Request Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-get-block-request-structure/)
- [Amazon Qldb Get Block Response Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-get-block-response-structure/)
- [Amazon Qldb Get Digest Response Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-get-digest-response-structure/)
- [Amazon Qldb Get Revision Request Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-get-revision-request-structure/)
- [Amazon Qldb Get Revision Response Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-get-revision-response-structure/)
- [Amazon Qldb Journal Kinesis Stream Description Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-journal-kinesis-stream-description-structure/)
- [Amazon Qldb Journal S3Export Description Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-journal-s3export-description-structure/)
- [Amazon Qldb Kinesis Configuration Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-kinesis-configuration-structure/)
- [Amazon Qldb Ledger Encryption Description Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-ledger-encryption-description-structure/)
- [Amazon Qldb Ledger State Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-ledger-state-structure/)
- [Amazon Qldb Ledger Summary Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-ledger-summary-structure/)
- [Amazon Qldb List Journal Kinesis Streams For Ledger Response Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-list-journal-kinesis-streams-for-ledger-response-structure/)
- [Amazon Qldb List Journal S3Exports For Ledger Response Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-list-journal-s3exports-for-ledger-response-structure/)
- [Amazon Qldb List Journal S3Exports Response Structure](https://apis.io/json-structure/amazon-qldb/amazon-qldb-list-journal-s3exports-response-structure/)
- …and 16 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Amazon Qldb Context](https://apis.io/jsonld/amazon-qldb/amazon-qldb-context/)

#### Examples (33)

Example requests and responses.

- [Amazon Qldb Cancel Journal Kinesis Stream Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-cancel-journal-kinesis-stream-response-example/)
- [Amazon Qldb Create Ledger Request Example](https://apis.io/examples/amazon-qldb/amazon-qldb-create-ledger-request-example/)
- [Amazon Qldb Create Ledger Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-create-ledger-response-example/)
- [Amazon Qldb Describe Journal Kinesis Stream Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-describe-journal-kinesis-stream-response-example/)
- [Amazon Qldb Describe Journal S3Export Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-describe-journal-s3export-response-example/)
- [Amazon Qldb Describe Ledger Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-describe-ledger-response-example/)
- [Amazon Qldb Export Journal To S3Request Example](https://apis.io/examples/amazon-qldb/amazon-qldb-export-journal-to-s3request-example/)
- [Amazon Qldb Export Journal To S3Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-export-journal-to-s3response-example/)
- [Amazon Qldb Get Block Request Example](https://apis.io/examples/amazon-qldb/amazon-qldb-get-block-request-example/)
- [Amazon Qldb Get Block Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-get-block-response-example/)
- [Amazon Qldb Get Digest Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-get-digest-response-example/)
- [Amazon Qldb Get Revision Request Example](https://apis.io/examples/amazon-qldb/amazon-qldb-get-revision-request-example/)
- [Amazon Qldb Get Revision Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-get-revision-response-example/)
- [Amazon Qldb Journal Kinesis Stream Description Example](https://apis.io/examples/amazon-qldb/amazon-qldb-journal-kinesis-stream-description-example/)
- [Amazon Qldb Journal S3Export Description Example](https://apis.io/examples/amazon-qldb/amazon-qldb-journal-s3export-description-example/)
- [Amazon Qldb Kinesis Configuration Example](https://apis.io/examples/amazon-qldb/amazon-qldb-kinesis-configuration-example/)
- [Amazon Qldb Ledger Encryption Description Example](https://apis.io/examples/amazon-qldb/amazon-qldb-ledger-encryption-description-example/)
- [Amazon Qldb Ledger Summary Example](https://apis.io/examples/amazon-qldb/amazon-qldb-ledger-summary-example/)
- [Amazon Qldb List Journal Kinesis Streams For Ledger Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-list-journal-kinesis-streams-for-ledger-response-example/)
- [Amazon Qldb List Journal S3Exports For Ledger Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-list-journal-s3exports-for-ledger-response-example/)
- [Amazon Qldb List Journal S3Exports Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-list-journal-s3exports-response-example/)
- [Amazon Qldb List Ledgers Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-list-ledgers-response-example/)
- [Amazon Qldb List Tags For Resource Response Example](https://apis.io/examples/amazon-qldb/amazon-qldb-list-tags-for-resource-response-example/)
- [Amazon Qldb S3Encryption Configuration Example](https://apis.io/examples/amazon-qldb/amazon-qldb-s3encryption-configuration-example/)
- [Amazon Qldb S3Export Configuration Example](https://apis.io/examples/amazon-qldb/amazon-qldb-s3export-configuration-example/)
- …and 8 more published on APIs.io

#### Collections (6)

Postman and Open Collection request collections.

- [Amazon QLDB Journal S3 Exports API](https://apis.io/collections/amazon-qldb/open-amazon-qldb-journal-s3-exports-api/)
- [Amazon QLDB Journal S3 Exports Ledgers API](https://apis.io/collections/amazon-qldb/open-amazon-qldb-ledgers-api/)
- [Amazon QLDB Journal S3 Exports Tags API](https://apis.io/collections/amazon-qldb/open-amazon-qldb-tags-api/)
- [Amazon QLDB Journal S3 Exports API](https://apis.io/collections/amazon-qldb/postman-amazon-qldb-journal-s3-exports-api/)
- [Amazon QLDB Journal S3 Exports Ledgers API](https://apis.io/collections/amazon-qldb/postman-amazon-qldb-ledgers-api/)
- [Amazon QLDB Journal S3 Exports Tags API](https://apis.io/collections/amazon-qldb/postman-amazon-qldb-tags-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Amazon QLDB — jsonschema rules](https://apis.io/rules/amazon-qldb/amazon-qldb-jsonschema-spectral-rules/)
- [Amazon QLDB API Rules](https://apis.io/rules/amazon-qldb/amazon-qldb-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Amazon Qldb Authentication](https://apis.io/security/amazon-qldb/amazon-qldb-authentication/)
- [Amazon Qldb Domain Security](https://apis.io/security/amazon-qldb/amazon-qldb-domain-security/)
- [Amazon Qldb Trust Center](https://apis.io/security/amazon-qldb/amazon-qldb-trust-center/)
- [Amazon Qldb Vulnerability Disclosure](https://apis.io/security/amazon-qldb/amazon-qldb-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Amazon Qldb Plans Pricing](https://apis.io/plans/amazon-qldb/amazon-qldb-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Amazon Qldb Rate Limits](https://apis.io/rate-limits/amazon-qldb/amazon-qldb-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Amazon Qldb Finops](https://apis.io/finops/amazon-qldb/amazon-qldb-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://aws.amazon.com/qldb/)
- [Documentation](https://docs.aws.amazon.com/qldb/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Terms of service](https://aws.amazon.com/service-terms/)
- [Privacy policy](https://aws.amazon.com/privacy/)
- [GitHub](https://github.com/aws)
- [Status](https://health.aws.amazon.com/health/status)

## API Evangelist rating

**Not rated** — this company is recorded as no longer operating, so no score is published. If it is in fact operating, say so on this repository and it will be re-profiled.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Amazon QLDB: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/amazon-qldb/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
