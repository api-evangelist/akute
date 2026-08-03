# Akute Health (akute)

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

Akute Health is an automation-first, API- and developer-friendly EHR (electronic health record) platform for digital health, telehealth, direct primary care, and GLP-1 weight-loss clinics. Its REST API at https://api.akutehealth.com/v1 exposes FHIR-aligned resources - patients, appointments, clinical notes, tasks, documents, medications and e-prescribing, lab orders and results, plus signed webhooks - so customers can enrich the record and build patient-facing or internal applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/akute/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/akute/refs/heads/main/apis.yml)

## Tags

- Healthcare
- EHR
- EMR
- FHIR
- Digital Health
- Telehealth

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Akute Patients API

Create, update, retrieve, and search patient records by internal id or external_id, including demographics, contact details, and external id mapping for synchronizing patients between systems.

- **Human URL:** [https://developer.akutehealth.com/](https://developer.akutehealth.com/)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Patients
- Demographics
- FHIR

#### Properties

- [Documentation](https://developer.akutehealth.com/)
- [API Reference](https://developer.akutehealth.com/)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Appointments API

Book, update, cancel, and search appointments, list appointment types, and query practitioner availability windows for scheduling across the practice.

- **Human URL:** [https://developer.akutehealth.com/](https://developer.akutehealth.com/)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Appointments
- Scheduling
- Availability

#### Properties

- [Documentation](https://developer.akutehealth.com/)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Encounters API

Create and retrieve clinical encounter documentation as structured, multi-section notes (progress notes, phone notes, SOAP) with authors, signing user, service date, and final or preliminary status.

- **Human URL:** [https://developer.akutehealth.com/](https://developer.akutehealth.com/)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Encounters
- Clinical Notes
- Documentation

#### Properties

- [Documentation](https://developer.akutehealth.com/)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Tasks API

Create, update, retrieve, and search care-team tasks with owner, patient, priority, status, tags, and due-date ranges to coordinate clinical and administrative workflow.

- **Human URL:** [https://developer.akutehealth.com/](https://developer.akutehealth.com/)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Tasks
- Workflow
- Care Coordination

#### Properties

- [Documentation](https://developer.akutehealth.com/)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Documents API

Upload, retrieve, and search documents and file attachments, optionally associated with a patient, supporting PDF report storage and paginated, sortable listing.

- **Human URL:** [https://developer.akutehealth.com/](https://developer.akutehealth.com/)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Documents
- Files
- Attachments

#### Properties

- [Documentation](https://developer.akutehealth.com/)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Medications API

Search the drug catalog, retrieve patient medications and Surescripts medication history (live or cached), look up dispensable drugs and pharmacies, and manage patient pharmacies for e-prescribing.

- **Human URL:** [https://developer.akutehealth.com/](https://developer.akutehealth.com/)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Medications
- e-Prescribing
- Pharmacy

#### Properties

- [Documentation](https://developer.akutehealth.com/)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Labs API

Search lab procedures and facilities, place lab orders, track order requests, and retrieve diagnostic reports and individual lab and vital-sign observations, including report PDFs.

- **Human URL:** [https://help.akutehealth.com/article/196-ordering-labs-via-api](https://help.akutehealth.com/article/196-ordering-labs-via-api)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Labs
- Orders
- Diagnostic Reports
- Observations

#### Properties

- [Documentation](https://help.akutehealth.com/article/196-ordering-labs-via-api)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Webhooks API

Register and manage webhook subscriptions for resource events (patients, appointments, notes, tasks, medications, diagnostic reports, orders, faxes, conversations) with HMAC-SHA256 signed delivery via the x-akute-signature header.

- **Human URL:** [https://help.akutehealth.com/article/212-supported-webhooks](https://help.akutehealth.com/article/212-supported-webhooks)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://help.akutehealth.com/article/212-supported-webhooks)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/akute-health-inc)
- [LinkedIn](https://www.linkedin.com/company/akute-health)
- [Website](https://www.akutehealth.com/)
- [Documentation](https://developer.akutehealth.com/)
- [Plans](plans/akute-plans-pricing.yml)
- [Rate Limits](rate-limits/akute-rate-limits.yml)
- [Fin Ops](finops/akute-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
